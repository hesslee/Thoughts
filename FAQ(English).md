### BUG-49743 Altibase 서버 구동 시 리빌드되지 않은 인덱스 접근 시 Altibase 서버가 비정상 종료합니다.

-   **module** : sm

-   **Category** : Fatal

-   **재현 빈도** : Always

-   **설명** : Altibase 서버 구동 시 리빌드되지 않은 인덱스 접근 시 Altibase 서버가 비정상 종료하는 현상을 수정합니다. 이 버그 현상은
    비공개 프로퍼티 INDEX\_REBUILD\_AT\_STARTUP 값을 0으로 설정하고 Altibase 서버 구동 후 사용자 인덱스에 접근하는 DML 수행 시
    발생합니다. 앞으로 DML 수행 시 리빌드되지 않은 인덱스에 접근하면 아래와 같은 에러 메시지가 발생하도록 수정하였습니다.
    
    `ERR-111BE : Failed to scan the index because it was not rebuilt.(Index Name :index_name)`
    
    이 에러 메시지는 새로 추가된 에러 메시지로, 자세한 내용은 Error Code 항목을 참고하세요.
    
-   **재현 방법**

    -   **재현 절차**

    -   **수행 결과**

    -   **예상 결과**

-   **Workaround**

-   **변경사항**

    -   Performance view
    
    -   Property
    
    -   Compile Option
    
    -   Error Code
        
        ~~~
        0x111BE (  70078) smERR_ABORT_NOT_BUILT_INDEX Failed to scan the index because it was not rebuilt. (Index Name :<0%s>) 
        # *Cause: This index was not rebuilt when the Altibase server was starting up. The value of INDEX_REBUILD_AT_STARTUP property is set to 0.
        # *Action: Rebuild this index. Or to rebuild all the indexes, delete INDEX_REBUILD_AT_STARTUP = 0 in altibase.properties and restart the Altibase server.
        ~~~
        
        

### BUG-49746 윈도우(분석) 함수, ORDER BY 절, GROUP BY 절을 사용한 질의문에서 디스크 임시 공간을 사용하면 결과 오류가 발생합니다.

-   **module** : qp-select

-   **Category** : Functional Error

-   **재현 빈도** : Always

-   **설명** : 아래 조건을 모두 만족하는 질의문 수행 시 결과 오류가 발생합니다.
    
    - 윈도우(분석) 함수 사용
    
    - GROUP BY 절, ORDER BY 절, 윈도우(분석) 함수 사용
    
    - ORDER BY 절에 사용된 컬럼이 윈도우(분석) 함수 OVER 절에서 같은 순서로 사용
    
    - ORDER BY 절에 사용된 컬럼이 SELECT 절에서 표현식으로 사용

    - 쿼리 수행 시 디스크 임시 공간 사용

    이 버그 현상을 회피하는 방법은  Work Around 부분을 확인해주세요.

    **패치 시 주의 사항**

    결괏값 오류를 개선한 버그로, 패치 후 버그 조건에 만족하는 질의문 수행 시 결과가 달라질 수 있습니다.
