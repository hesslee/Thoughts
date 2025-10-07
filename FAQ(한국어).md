1. Home . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 3

1.1 01. 설치, 패치, 업그레이드 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 4
1.1.1 01-01. Altibase HDB가 지원하는 플랫폼(OS)은? . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 4
1.1.2 01-02. Unix 및 Linux 에서 알티베이스 서버 패치 절차 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 6
1.1.3 01-03. 알티베이스 클라이언트 설치 방법(ALTIBASE HDB 5.5.1 부터) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 12
1.1.4 01-04. 윈도우에서 알티베이스 설치 할 때 "이미 설치가 되었다"고 합니다. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 17
1.2 02. 운영 및 관리 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 18
1.2.1 02-01. [Linux] Altibase 서버 프로세스 자동 시작 스크립트 등록 방법 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 18
1.2.2 02-02. column modify 하는 방법 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 25
1.2.3 02-03. Database 를 stop 하고 start 하는 방법 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 27
1.2.4 02-04. Database 의 db name을 바꾸는 방법 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 33
1.2.5 02-05. Datafile 을 추가한 이력 확인 방법 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 37
1.2.6 02-06. DB 이름 변경 후 server create 오류발생시 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 38
1.2.7 02-07. floating point 형 data type (double, float) 사용 시 주의사항 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 39
1.2.8 02-08. HP-UX에서 부팅 시 알티베이스를 자동으로 시작(startup)하는 방법 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 43
1.2.9 02-09. IPC 통신을 위한 알티베이스 서버 설정 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 48
1.2.10 02-10. LOCK TIMEOUT 발생 시 조치 방법 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 51
1.2.11 02-11. Lock 잡고 있는 세션을 강제로 종료하는 방법 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 54
1.2.12 02-11. Maximum Capacity Specifications for Altibase . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 55
1.2.13 02-12. MEM_MAX_DB_SIZE 프로퍼티 설정 변경 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 55
1.2.14 02-13. PUBLIC SYNONYM 을 삭제해도 되나요? . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 60
1.2.15 02-14. Solaris에서 OS booting 시 자동 altibase startup . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 60
1.2.16 02-15. sys 유저 패스워드 변경 방법 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 64
1.2.17 02-16. Table 데이터는 Disk 에 저장하고 인덱스만 Memory 에 생성이 가능한가요? . . . . . . . . . . . . . . . . . . . . . . . 66
1.2.18 02-17. TRANSACTION_TABLE_SIZE 변경 시 고려사항 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 67
1.2.19 02-18. 데이터베이스 보안 점검 체크리스트 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 71
1.2.20 02-19. 동시 접속 세션 수(MAX_CLIENT) 증가 시 고려사항 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 88
1.2.21 02-20. 로그디스크 FULL이 발생하는 경우와 대처 방법 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 91
1.2.22 02-21. 사용자 생성(CREATE USER) 및 패스워드 변경(ALTER USER) 방법 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 96
1.2.23 02-22. 사용자 패스워드 길이 제약 - 버전 별 차이 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 97
1.2.24 02-23. 작업(Job)객체 생성 및 실행 방법 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 98
1.2.25 02-24. 캐릭터셋 변경 방법 상세 절차 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 103
1.2.26 02-25. 테이블스페이스 데이터 파일 경로 변경 방법 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 108
1.2.27 02-26. 로그앵커, 온라인 로그파일, 아카이브 로그파일, 더블 라이트(Double Write)파일 경로 변경 방법 . . . . . . . . . 114
1.3 03. 이중화 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 117
1.3.1 03-01. replication conflict 발생원인과 해결방법 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 117
1.3.2 03-02. 동일 IP로 여러 개의 이중화 객체를 생성하는 방법 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 120
1.3.3 03-03. 알티베이스 이중화 대상 테이블에 대한 DDL 작업 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 122
1.3.4 03-04. 이중화 give-up에 대해 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 123
1.3.5 03-05. 이중화 객체 IP 변경 방법 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 125
1.3.6 03-06. 이중화 객체 생성 및 삭제 방법 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 126
1.3.7 03-07. 이중화 대상 테이블 추가/삭제 방법 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 135
1.3.8 03-08. 이중화 모니터링 쿼리 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 138
1.4 04. 백업 및 복구 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 142
1.4.1 04-01. aexport 및 iloader 이용 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 142
1.4.1.1 04-01-01. aexport, iloader 란? . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 142
1.4.1.2 04-01-02. aexport 를 이용한 데이터베이스 객체 백업 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 143
1.4.1.3 04-01-03. iloader 를 이용한 데이터 다운로드 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 146
1.4.1.4 04-01-04. 데이터베이스 객체 생성 및 데이터 업로드 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 150
1.4.2 04-02. Cold Backup한 것을 Directory 경로변경 하여 복구하는 방법 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 153
1.4.3 04-03. Online Backup 및 Time Based Recovery 방법 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 156
1.5 05. SQL . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 161
1.5.1 05-01. varchar, char 타입 비교 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 161
1.5.2 05-02. 객체에 부여된 권한을 확인하는 방법 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 162

1.6 06. Stored Procedures . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 163

1.6.1 06-01. Stored Procedure 내에서 DML 로 영향 받은 레코드 수 확인 방법 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 163
1.6.2 06-02. 저장 프로시저 내용 확인 방법 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 164
1.7 07. 개발 및 API . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 170
1.7.1 07-01. Connection 연결이 끊어지는 경우와 각 경우의 에러 코드 및 에러 메세지(APRE*C/C++, SQLCLI) . . . . . . . . . 170
1.7.2 07-02. JDBC . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 175

1.7.2.1 07-02-01. Altibase JDBC에서 Fail-Over 사용하는 방법은? . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 175
1.7.2.2 07-02-02. jdbc.trc 파일 생성 위치 변경 방법 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 177
1.7.3 07-03. ODBC . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 178

1.7.3.1 07-03-01. 64-bit Windows에서 32-bit ODBC 설치 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 178
1.7.3.2 07-03-02. ODBC 함수, SQLFreeStmt . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 181
1.7.3.3 07-03-03. unix_odbc와 연동하기 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 182
1.7.4 07-04. PHP . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 186
1.7.4.1 07-04-01. php 사용중인데 한글이 깨집니다. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 186
1.7.5 07-05. Spring+iBatis 트랜잭션 관리 방법 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 189
1.8 08. 모니터링 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 193
1.8.1 08-01. Altibase에서 수행된 쿼리 로그 남기는 방법(altiProfile)은? . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 193
1.8.2 08-02. Lock 관련 정보 조회 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 208


1.8.3 08-03. OS별 시스템 정보 보기 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 210
1.8.4 08-04. Windows 용 모니터링 툴 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 230
1.8.5 08-05. 디스크 테이블 및 인덱스 사용량 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 233

1.8.5.1 08-05-01. ALTIBASE HDB 4.3.9.x . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 234

1.8.5.2 08-05-02. ALTIBASE HDB 5.1.5.x . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 238

1.8.5.3 08-05-03. ALTIBASE HDB 5.3.x, 5.5.1, 6.1.1, 6.3.1 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 243
1.8.6 08-06. 디스크 테이블스페이스 사용량 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 250

1.8.6.1 08-06-01. ALTIBASE HDB 4.3.9 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 250

1.8.6.2 08-06-02. ALTIBASE HDB 5.1.5 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 252

1.8.6.3 08-06-03. ALTIBASE HDB 5.3.3, 5.3.5 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 253
1.8.6.4 08-06-04. ALTIBASE HDB 5.5.1, 6.1.1, 6.3.1 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 256
1.8.7 08-07. 롤백(rollback) 중인 쿼리를 확인하는 방법 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 258
1.8.8 08-08. 메모리 테이블 및 인덱스 사용량 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 260
1.8.9 08-09. 메모리 테이블스페이스 사용량 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 265
1.8.9.1 08-09-01. ALTIBASE HDB 5.5.1, 6.1.1, 6.3.1 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 266
1.8.10 08-10. 알티몬(altimon) 설정 및 실행 방법 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 268
1.8.11 08-11. 언두 테이블스페이스(UNDO TABLESPACE) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 273
1.8.11.1 08-11-01. 언두 테이블스페이스 사용량 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 273
1.8.11.2 08-11-02. 언두 테이블스페이스 사용량 증가 시 모니터링 방법 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 275
1.8.12 08-12. 테이블/컬럼 정의서 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 289
1.9 09. 에러메시지 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 293
1.9.1 09-01. [Notify : Fetch Timeout] Session Closed by Server. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 293
1.9.2 09-02. [Warning] Memory allocation failed. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 302
1.9.3 09-03. altibase_boot.log의 TRY_COUNT, LOCK_COUNT, MISS_COUNT 메시지 의미 . . . . . . . . . . . . . . . . . . . . . . 303
1.9.4 09-04. altibase_qp.log의 8자리 errorcode 확인방법 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 306
1.9.5 09-05. Closed Socket by client is Detected . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 307
1.9.6 09-06. ERR-0109D Insufficient memory . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 308
1.9.7 09-07. ERR-311E0 The estimated size of the index key exceeds the maximum limit. . . . . . . . . . . . . . . . . . . . . . 310
1.9.8 09-08. ERR-410D2 (266450) Fetch out of sequence. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 312
1.9.9 09-09. ERR-1105D Unable to begin a new update statement. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 318
1.9.10 09-10. ERR-4103C (266300) Request of fetching data to an unprepared SQL statement. . . . . . . . . . . . . . . . . . 321
1.9.11 09-11. ERR-4109C Invalid session property . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 328
1.9.12 09-12. ERR-5102E ( 331822) Invalid cursor state. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 333
1.9.13 09-13. ERR-7101D ( 462877) Protocol header error. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 335
1.9.14 09-14. ERR-11030 ( 69680) The data file cannot be extended because the requested size is bigger than the

maximum size (FID:<0%d>). . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 337
1.9.15 09-15. ERR-11036 The data file is in use. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 340
1.9.16 09-16. ERR-11049 ( 69705) Too many pages are allocated ( Maximum Number of Pages= 숫자). . . . . . . . . . . . 341
1.9.17 09-17. ERR-11075 ( 69749) The transaction has exceeded the lock timeout specified by the user. . . . . . . . . . . 343
1.9.18 09-18. ERR-11118 ( 69912) The update log size '?????' is bigger than TRX_UPDATE_MAX_LOGSIZE '?????' . . . 347
1.9.19 09-19. ERR-11183 ( 70019) Insufficient page descriptor area in the temp table. . . . . . . . . . . . . . . . . . . . . . . . 353
1.9.20 09-20. ERR-11184 ( 70020) Insufficient free space in work area . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 358
1.9.21 09-21. ERR-21010 Value overflow . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 360

1.9.22 09-22. ERR-21011 : Invalid literal . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 361

1.9.23 09-23. ERR-31283 Unable to create a primary key or a unique key constraint in the local non-prefixed index. . . 363
1.9.24 09-24. ERR-41059 ( 266329) Task pool overflow. Check properties. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 366
1.9.25 09-25. ERR-71018 ( 462872) Failed to invoke a system function, read() 또는 Failed to invoke the read() system

function . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 372
1.9.26 09-26. ERR-71019(errno=104) Failed to invoke a system function, write() . . . . . . . . . . . . . . . . . . . . . . . . . . . 375
1.9.27 09-27. ERR-91015 ( 593941) Communication failure . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 375
1.9.28 09-28. Not found data . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 378
1.9.29 09-29. tablespace does not have enough free space 에러 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 384
1.10 10. 마이그레이션 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 385
1.11 11. 유틸리티 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 385
1.11.1 11-01. AdminCenter2 실행 파일 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 385

1.11.2 11-02. iLoader . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 386

1.11.2.1 11-02-01. 도스 형식 데이터 파일을 iloader로 업로드 할 때 에러가 발생 합니다. . . . . . . . . . . . . . . . . . . . . 386
1.12 12. 기타 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 388
1.12.1 12-01. Thread process debugging방법 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 388
1.12.2 12-02. 대용량 DRDB Index 구축 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 391
1.13 13. 일반 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 392
1.13.1 13-01. Altibase는 어떤 인터페이스를 제공하나요? . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 392
1.13.2 13-02. Altibase와 디스크 기반 DBMS의 가장 큰 차이점은 무엇인가요? . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 394
1.13.3 13-03. 메모리에 전체 데이터베이스가 존재하는데 데이터의 안전성에는 문제가 없나요? . . . . . . . . . . . . . . . . . . . . 395


# Home

This is the home of the FAQ space.


To help you on your way, we've inserted some of our favourite macros on this home page. As you start creating pages, blogging and
commenting you'll see the macros below fill up with all the activity in your space.




















|NO|분류|FAQ|
|---|---|---|
|1|설치, 패치,<br>업그레이드|01-01. Altibase HDB가 지원하는 플랫폼(OS)은?<br>01-02. Unix 및 Linux 에서 알티베이스 서버 패치 절차<br>01-03. 알티베이스 클라이언트 설치 방법(ALTIBASE<br>HDB 5.5.1 부터)<br>01-04. 윈도우에서 알티베이스 설치 할 때 "이미 설치가<br>되었다"고 합니다.<br>More|
|2|운영 및 관리<br>|02-01. [Linux] Altibase 서버 프로세스 자동 시작<br>스크립트 등록 방법<br>02-02. column modify 하는 방법<br>02-03. Database 를 stop 하고 start 하는 방법<br>02-04. Database 의 db name을 바꾸는 방법<br>02-05. Datafile 을 추가한 이력 확인 방법<br>More|
|3|이중화|03-01. replication conflict 발생원인과 해결방법<br>03-02. 동일 IP로 여러 개의 이중화 객체를 생성하는<br>방법<br>03-03. 알티베이스 이중화 대상 테이블에 대한 DDL 작업<br>03-04. 이중화 give-up에 대해<br>03-05. 이중화 객체 IP 변경 방법<br>More|
|4|백업 및 복구<br>|04-01. aexport 및 iloader 이용<br>04-02. Cold Backup한 것을 Directory 경로변경 하여<br>복구하는 방법<br>04-03. Online Backup 및 Time Based Recovery 방법<br>More|
|5|SQL|05-01. varchar, char 타입 비교<br>05-02. 객체에 부여된 권한을 확인하는 방법<br>More|
|6|Stored<br>Procedures|06-01. Stored Procedure 내에서 DML 로 영향 받은<br>레코드 수 확인 방법<br>06-02. 저장 프로시저 내용 확인 방법<br>More|
|7|개발 및 API|07-01. Connection 연결이 끊어지는 경우와 각 경우의<br>에러 코드 및 에러 메세지(APRE*C/C++, SQLCLI)<br>07-02. JDBC<br>07-03. ODBC<br>07-04. PHP<br>07-05. Spring+iBatis 트랜잭션 관리 방법<br>More|


|8|모니터링|08-01. Altibase에서 수행된 쿼리 로그 남기는<br>방법(altiProfile)은?<br>08-02. Lock 관련 정보 조회<br>08-03. OS별 시스템 정보 보기<br>08-04. Windows 용 모니터링 툴<br>08-05. 디스크 테이블 및 인덱스 사용량<br>More|
|---|---|---|
|9|에러메시지|09-01. [Notify : Fetch Timeout] Session Closed by<br>Server.<br>09-02. [Warning] Memory allocation failed.<br>09-03. altibase_boot.log의 TRY_COUNT,<br>LOCK_COUNT, MISS_COUNT 메시지 의미<br>09-04. altibase_qp.log의 8자리 errorcode 확인방법<br>09-05. Closed Socket by client is Detected<br>More|
|10|마이그레이션<br>|More|
|11|유틸리티|11-01. AdminCenter2 실행 파일<br>11-02. iLoader<br>More|
|12|기타|12-01. Thread process debugging방법<br>12-02. 대용량 DRDB Index 구축<br>More|
|13|일반|13-01. Altibase는 어떤 인터페이스를 제공하나요?<br>13-02. Altibase와 디스크 기반 DBMS의 가장 큰<br>차이점은 무엇인가요?<br>13-03. 메모리에 전체 데이터베이스가 존재하는데<br>데이터의 안전성에는 문제가 없나요?<br>More|


Navigate space

### 01. 설치, 패치, 업그레이드

#### 01-01. Altibase HDB가 지원하는 플랫폼(OS)은?


6.5.1

6.3.1

6.1.1

Java Version


6.5.1


|OS|CPU|Version|Bit(Server)|Bit(Client)|
|---|---|---|---|---|
|AIX|PowerPC|6.1 tl03 or later|64-bit|64-bit, 32-bit|
|HP-UX|IA64|11.31 or later|64-bit|64-bit, 32-bit|


|LINUX|x86, x86-64<br>(GNU glibc 2.12 or later)|Ubuntu 12, 13<br>Redhat 6, 7<br>CentOS 6, 7<br>Fedora 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 21<br>openSUSE 12<br>Oracle Linux 6.5, 6.6, 7.1|64-bit|64-bit, 32-bit|
|---|---|---|---|---|
|SUN|SPARC|2.10 or later|64-bit|64-bit, 32-bit|
|Windows|x86, x86-64|Windows 2008<br>Windows 2012<br>Windows 7, 8|64-bit|64-bit, 32-bit|


6.3.1















|OS|CPU|Version|Bit(Server)|Bit(Client)|
|---|---|---|---|---|
|AIX|PowerPC|5.3 tl1 or later|64-bit|64-bit, 32-bit|
|HP-UX|PA-RISC|11.11 or later|64-bit|64-bit, 32-bit|
|HP-UX|IA64|11.23 or later|11.23 or later|11.23 or later|
|LINUX|x86, x86-64<br>(GNU glibc 2.3.4 or later)|Ubuntu 8, 9, 10, 11, 12, 13<br>Redhat 4, 5, 6, 7<br>CentOS 4, 5, 6, 7<br>Fedora 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 21<br>openSUSE 9, 10, 11, 12<br>Oracle Linux 6.5, 6.6, 7.1|64-bit|64-bit, 32-bit|
|SUN|SPARC|2.8 or later|64-bit|64-bit, 32-bit|
|SUN|i86PC|2.10 or later|2.10 or later|2.10 or later|
|Windows|x86, x86-64|Windows 2008<br>Windows 2012<br>Windows 7, 8|64-bit|64-bit, 32-bit|


6.1.1














|OS|CPU|Version|Bit(Server)|Bit(Client)|
|---|---|---|---|---|
|AIX|PowerPC|5.3 tl1 or later|64-bit|64-bit, 32-bit|
|HP-UX|PA-RISC|11.00 or later|64-bit|64-bit, 32-bit|
|HP-UX|IA64|11.23 or later|11.23 or later|11.23 or later|
|LINUX|x86, x86-64<br>(GNU glibc 2.3.4 or later)|Ubuntu 8, 9, 10, 11, 12, 13<br>Redhat 4, 5, 6, 7<br>CentOS 4, 5, 6, 7<br>Fedora 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 21<br>openSUSE 9, 10, 11, 12<br>Oracle Linux 6.5, 6.6, 7.1|64-bit|64-bit, 32-bit|
|SUN|SPARC|2.8 or later|64-bit|64-bit, 32-bit|
|SUN|||||
|SUN|||||


|Col1|Col2|Col3|Col4|Col5|
|---|---|---|---|---|
||i86PC|2.10 or later|2.10 or later|2.10 or later|
|Windows|x86, x86-64|Windows 2003<br>Windows 2008<br>Windows 2012<br>Windows 7, 8|64-bit|64-bit, 32-bit|


Java Version


Altibase HDB 6 이상 버전의 JDBC는 JDK 1.4 이상에서 호환됩니다.

#### 01-02. Unix 및 Linux 에서 알티베이스 서버 패치 절차


개요
패치 전 확인 사항
패치 절차

1. 현재 버전 확인
2. 알티베이스 서버 shutdown **
3. 기존 설치 파일 백업
4. 패치 패키지 업로드 및 권한 변경
5. 패치 수행
6. 패치 버전 확인
7. 백업 파일에서 필요한 파일들 복사
8. ALTIBASE HDB 서버 startup**
주의 사항

패치 전/후 meta 버전 확인
ALTIBASE HDB 4.3.9.1 ~ 4.3.9.50 에서 4.3.9.51 ~ 으로 패치할 경우**


개요





패치는 마이너 버전이 변경되는 것을 의미합니다.
알티베이스 서버 버전은 4자리 숫자 또는 5자리 숫자로 이루어져 있습니다.
앞 세 자리는 메이저 버전을 의미하고 뒤의 한 자리 또는 두 자리는 마이너 버전을 의미합니다.
앞 세 자리 변경없이 뒷 자리가 변경되는 것을 '패치'라 하고 앞 세 자리가 변경되는 것은 '업그레이드'라 합니다.


이 페이지에서는 Unix 및 Linux 환경에서의 알티베이스 서버 패치 절차에 대해 설명합니다.
알티베이스 서버 패치는 알티베이스 서버를 shutdown 한 후에 수행해야 하기 때문에 서비스 중단 시간이 필요합니다.
따라서 패치 작업 전 반드시 down time 을 확보해야 합니다.


패치 전 확인 사항


패치를 고려하는 경우 아래 사항을 확인 후 진행하도록 합니다.


알티베이스 서버 down time 확보가 가능한 지? (고객사에서 확인)
패치 후 meta 버전이 변경되는 지? (알티베이스 엔지니어에게 확인)
패치 버전이 현 버전이 너무 차이 나는 경우 주의할 점이 있는 지? (알티베이스 엔지니어에게 확인)


예. ALTIBASE HDB 4.3.9.44 에서 ALTIBASE HDB 4.3.9.233 으로 패치해야 할 경우.


패치 절차


1. 현재 버전 확인


아래 버전 확인 결과를 메모 해 둡니다.





2. 알티베이스 서버 shutdown **


알티베이스 서버를 shutdown 합니다.





shutdown 후 알티베이스 서버 프로세스 및 서비스 포트 LISTEN 상태를 확인합니다.
아래 두 명령어를 수행했을 때 결과가 아무것도 나오지 않아야 정상적으로 shutdown 된 상태입니다.


$ ps -ef | grep 'altibase -p' | grep -v grep      # 알티베이스 서버 프로세스 확인 방법
$ netstat -an | grep 20300               # 서비스 포트 확인 방법.


3. 기존 설치 파일 백업


패치 후 문제 발생 시 원복할 수 있도록 필요한 디렉토리들을 백업합니다.


$ALTIBASE_HOME 디렉토리 크기가 크지 않다면 아래와 같이 $ALTIBASE_HOME 디렉토리를 전체 백업해도 됩니다.


$ cp -Rp altibase_home altibase_home.bak


4. 패치 패키지 업로드 및 권한 변경


ALTIBASE HDB 서버 5.5.1 이상 버전 (5.5.1, 6.1.1, 6.3.1 및 6.3.1 이후 모든 버전)


ALTIBASE HDB 서버 설치 유저로 로그인 합니다.
패치 패키지를 임의의 경로에 업로드 합니다.
ALTIBASE HDB 서버 5.5.1 버전부터는 자바 기반의 인스톨러를 사용하게 되었고 패키지 이름이 아래와 같이 .run 으로 끝납니다.
패키지를 실행할 수 있도록 실행 권한을 부여합니다.





ALTIBASE HDB 서버 5.5.1 이전 버전(4.3.9, 5.3.3 등 5.3.3 이하 모든 버전)


ALTIBASE HDB 서버 설치 유저로 로그인 합니다.
패치 패키지를 $ALTIBASE_HOME 디렉토리 아래에 업로드 합니다.
ALTIBASE HDB 서버 5.5.1 이전 버전에서는 압축 파일 형태의 파일을 제공합니다.


altibase-XEON_LINUX_redhat_Enterprise_release5-64bit-5.3.3.84-release-GCC4.1.2.tgz


5. 패치 수행


ALTIBASE HDB 서버 5.5.1 이상 버전 (5.5.1, 6.1.1, 6.3.1 및 6.3.1 이후 모든 버전)


아래와 같이 실행 파일을 실행한 후 이후 동작은 메세지에 따라서 진행합니다.


$ ./altibase-HDB-server-6.1.1.3.8-LINUX-X86-64bit-release.run


ALTIBASE HDB 서버 5.5.1 이전 버전(4.3.9, 5.3.3 등 5.3.3 이하 모든 버전)


$ALTIBASE_HOME 디렉토리로 이동 후 아래와 같이 압축을 해제 합니다.


$ cd $ALTIBASE_HOME
$ gzip -cd altibase-XEON_LINUX_redhat_Enterprise_release5-64bit-5.3.3.84-release-GCC4.1.2.tgz |

tar xvf 

6. 패치 버전 확인


패치 실행 완료 후 버전을 확인하여 패치 적용 여부를 확인합니다.





7. 백업 파일에서 필요한 파일들 복사


sys 유저의 기본 패스워드(manager)를 변경했을 경우 $ALTIBASE_HOME/bin/server, is, il 스크립트가 변경되었을 것입니다.
이러한 경우 백업한 디렉토리 중 bin 디렉토리에서 server, is, il 를 $ALTIBASE_HOME/bin 으로 복사합니다.


$ cd $ALTIBASE_HOME
$ cp -p bin.bak/server bin/
$ cp -p bin.bak/is bin/
$ cp -p bin.bak/il bin/


8. ALTIBASE HDB 서버 startup**


알티베이스 서버 프로세스 구동 후 프로세스 및 서비스 포트 LISTEN 상태를 확인합니다.


$ server start


shutdown 후 알티베이스 서버 프로세스 및 서비스 포트 LISTEN 상태를 확인합니다.


아래 두 명령어를 수행했을 때 결과가 아무것도 나오지 않아야 정상적으로 shutdown 된 상태입니다.


$ ps -ef | grep 'altibase -p' | grep -v grep      # 알티베이스 서버 프로세스 확인 방법
altibase 10758 1 0 12:01 ? 00:00:14 /home/altibase/bin/altibase -p boot from admin


$ netstat -an | grep 20300               # 서비스 포트 확인 방법.
tcp    0   0 0.0.0.0:20300        0.0.0.0:*          LISTEN


주의 사항


패치 전/후 meta 버전 확인


meta 버전이 변경되면 데이터베이스를 하위 버전으로 되돌릴 수 없습니다.
상위 버전으로 패치 후 불가피하게 하위 버전으로 되돌려야하는 경우가 있을 수 있는데, meta 버전이 변경되면 이런 작업을 할 수
없습니다.
따라서 meta 버전이 변경되는 경우는 이 점을 숙지하고 패치를 진행해야 하며 필요 시 패치 전에 오프라인 전체 백업을 수행해야
합니다.
오프라인 전체 백업 대상으로는 데이타 파일, 로그 앵커 파일, 로그 파일, 설정 파일이 있습니다.


ALTIBASE HDB 4.3.9.1 ~ 4.3.9.50 에서 4.3.9.51 ~ 으로 패치할 경우**


아래 조건을 만족하는 경우 패치 후 이중화가 동작하지 않는 문제가 발생합니다.


ALTIBASE HDB 4.3.9.1 ~ 4.3.9.50 에서 4.3.9.51 ~ 으로 패치하고자 할 때
이중화 환경


따라서 위 조건을 만족하는 경우 반드시 아래 절차에 따라 패치를 진행해야 합니다.



1.


2.


3.


4.


5.



알티베이스 서버 down time 확보


알티베이스 서버 shutdown

패치 절차 2단계 참고하세요.


서비스 포트 변경
알티베이스로의 접근을 확실히 차단하기 위해 패치 작업 중 서비스 포트를 임시로 변경합니다.


$ cd $ALTIBASE_HOME/conf
$ vi altibase.properties        # altibase.properties 에서 PORT_NO 을 변경함.


알티베이스 서버 startup

패치 절차 8단계 를 참고하세요.


이중화 gap 확인**
반드시 0 임을 확인해야 합니다.


6.


7.


8.


9.


10.


11.


12.


13.


14.



aexport 를 수행하여 이중화 객체 생성 구문 백업


$ aexport           # aexport 수행 후 생성된 SYS_CRT_REP.sql 파일에서 이중화 객체 생성 구문을
확인할 수 있습니다.


이중화 객체 drop**


-- 이중화 객체명 확인

iSQL> SELECT REPLICATION_NAME FROM SYSTEM_.SYS_REPLICATIONS_;


-- 이중화 stop
iSQL> ALTER REPLICATION replication_name STOP;


-- 이중화 객체 drop
iSQL> DROP REPLICATION replication_name;


체크포인트 수행


iSQL> ALTER SYSTEM CHECKPOINT;          -- 4번 정도 반복 수행


알티베이스 서버 shutdown
패치 절차 2단계 참고하세요.


패치 수행

패치 절차 3단계부터 7단계까지 참고하세요.


CHECK_LOGFILE 프로퍼티 추가**


$ cd $ALTIBASE_HOME/conf
$ vi altibase.properties        # altibase.properties 파일 마지막 라인에 CHECK_LOGFILE = 0 추가 후
저장.


알티베이스 서버 startup

패치 절차 8단계 를 참고하세요.


CHECK_LOGFILE 프로퍼티 삭제**


$ cd $ALTIBASE_HOME/conf
$ vi altibase.properties        # altibase.properties 파일 마지막 라인에 추가한 CHECK_LOGFILE = 0
삭제 후 저장.


임시 테이블 생성 후 데이터 insert.
이전 버전에서 생성된 로그 파일을 다 쓰고 새로운 로그 파일을 생성시키기 위함입니다.


15.


16.


17.


18.


19.


20.


21.



CREATE TABLE IMSI_T (C1 INTEGER, C2 INTEGER);


CREATE OR REPLACE PROCEDURE IMSI_PROC AS V1 INTEGER;

BEGIN

FOR V1 IN 1 .. 300000 LOOP
INSERT INTO IMSI_T VALUES (V1, V1);

END LOOP;

END;

/


iSQL> SELECT CUR_WRITE_LF_NO FROM V$LFG;     -- 수행 결과(숫자) 확인.
iSQL> EXEC IMSI_PROC;               -- 임시 테이블에 insert 수행.
iSQL> SELECT CUR_WRITE_LF_NO FROM V$LFG;     -- 위에서 확인한 결과보다 크면 완료. 만약

위에서 확인한 결과와 달라지지 않았다면, IMSI_PROC 프로시저 재수행.
iSQL> DROP PROCEDURE IMSI_PROC;          -- 임시 테이블 및 프로시저 drop.

iSQL> DROP TABLE IMSI_T;


체크포인트 수행


iSQL> ALTER SYSTEM CHECKPOINT;          -- 4번 정도 반복 수행


이중화 객체 생성


$ is -f SYS_CRT_REP.sql             # aexport 수행 후 생성된 SYS_CRT_REP.sql 파일 수행.


이중화 start


-- 이중화 객체명 확인

iSQL> SELECT REPLICATION_NAME FROM SYSTEM_.SYS_REPLICATIONS_;


-- 이중화 stop
iSQL> ALTER REPLICATION replication_name START;


알티베이스 서버 shutdown

패치 절차 2단계 참고하세요.


서비스 포트 변경
임시로 변경한 서비스 포트를 원래대로 변경합니다.


$ cd $ALTIBASE_HOME/conf
$ vi altibase.properties        # altibase.properties 에서 PORT_NO 을 변경함.


알티베이스 서버 startup

패치 절차 8단계 를 참고하세요.


서비스 확인.


#### 01-03. 알티베이스 클라이언트 설치 방법(ALTIBASE HDB 5.5.1 부터)

대상 OS
알티베이스 클라이언트 설치 파일 다운로드
알티베이스 클라이언트 설치 파일 업로드
알티베이스 클라이언트 설치 파일 실행 권한 변경
설치 시작
OS 사용자 초기화 파일 확인
OS 사용자 초기화 파일 적용
설치 확인


대상 OS


Linux

HP-UX

AIX

Solaris


알티베이스 클라이언트 설치 파일 다운로드


http://support.altibase.com/kr/product 페이지에서 클라이언트 설치 파일 다운로드 합니다.
설치하고자 하는 버전의 클라이언트가 없는 경우 02-2082-1114 또는 http://support.altibase.com/kr/ 에서 고객서비스 -> 기술지원
요청 메뉴를 통해 요청해주세요.


알티베이스 클라이언트 설치 파일 업로드


알티베이스 클라이언트를 설치하고자 하는 서버에 설치 파일을 업로드 합니다.
설치하고자 하는 OS 유저로 설치 패키지를 임의 경로에 업로드 합니다.


알티베이스 클라이언트 설치 파일 실행 권한 변경


알티베이스 클라이언트 설치 파일을 기본 권한으로 읽기와 쓰기 권한만 가지고 있습니다.
설치를 진행하려면 실행 권한이 필요합니다.


아래와 같이 실행 권한을 추가하세요.





권한 변경 후 아래와 같이 rw rw -r  실행 권한이 추가된 것을 확인합니다.x x x


설치 시작


아래와 같이 설치 파일을 실행합니다.





설치 과정 예시


$ ./altibase-HDB-client-6.3.1.3.1-LINUX-X86-64bit-release.run

---------------------------------------------------------------------------
Welcome to the ALTIBASE HDB Client 6.3.1.3.1 setup wizard.


---------------------------------------------------------------------------
Installation Directory


Please specify the installation directory for ALTIBASE HDB Client 6.3.1.3.1


Installation directory [/data/heejung.lee/altibase_home]:  # 설치 할 디렉토리를 절대 경로로
입력합니다.


Please select the installation type.


Installation type


[1] Patch: patch package install

[2] Full installation: full package install
Please choose an option [1] :                 # 2번 입력 후 엔터


---------------------------------------------------------------------------
ALTIBASE HDB Property setting


ALTIBASE HDB connection port number (1024-65535) [20300]:  # 알티베이스 서버의 서비스 포트를
입력합니다. 기본값이면 엔터를 입력합니다.


---------------------------------------------------------------------------
Setup is now ready to install ALTIBASE HDB Client 6.3.1.3.1.


Do you want to continue? [Y/n]:                # 설치를 시작하기 위해 엔터 누릅니다.


---------------------------------------------------------------------------
Please wait until the setup wizard finishes installing ALTIBASE HDB Client

6.3.1.3.1.


Installing

0% ______________ 50% ______________ 100%

########################################Info:

The following ALTIBASE HDB environment variables were added.


-- ALTIBASE_HOME=/data/heejung.lee/altibase_home

-- ALTIBASE_PORT_NO=20300

-- PATH

-- LD_LIBRARY_PATH

-- CLASSPATH


=========================

Please perform [re-login]
or [source .bash_profile]
or [. .bash_profile]

==========================

Press [Enter] to continue :

#

---------------------------------------------------------------------------
Setup has finished installing the ALTIBASE HDB Client 6.3.1.3.1 on your client.
$                               # 설치 종료.


정상적으로 설치가 끝나면 설치 디렉토리 아래에는 아래와 같은 디렉토리들이 생성됩니다.





OS 사용자 초기화 파일 확인


위 과정이 정상적으로 수행되었다면 OS 사용자의 환경 설정 파일에 아래와 같은 내용이 포함됩니다.





OS 사용자 초기화 파일의 이름은 SHELL 마다 다릅니다.

```
    Bourne shell(sh), korn shell(ksh)  .profile

```

`bash shell(bash)  .bash_profile` 또는 .profile

```
    C shell(csh)  .login .cshrc

```

OS 사용자 초기화 파일 적용


초기화 파일에 추가된 환경 변수들을 적용하기 위해 아래와 같이 수행합니다.


$ . ~/.bash_profile


또는


$ . ~/.profile


환경 변수 값을 확인하여 적용 여부를 확인합니다.





설치 확인


iSQL 을 이용하여 알티베이스 서버 접속 테스트를 수행합니다.


isql -u DB사용자이름 -p 패스워드 -s IP -port 서비스포트


수행 예


$ isql -u sys -p manager -s 192.168.1.145 -port 20300

----------------------------------------------------------------
Altibase Client Query utility.

Release Version 6.3.1.3.1

Copyright 2000, ALTIBASE Corporation or its subsidiaries.
All Rights Reserved.

----------------------------------------------------------------
ISQL_CONNECTION = TCP, SERVER = 192.168.1.145, PORT_NO = 20300

iSQL>
iSQL> SELECT PRODUCT_VERSION FROM V$VERSION;

PRODUCT_VERSION

---------------------------------------------
6.3.1.3.8

1 row selected.

iSQL>

#### 01-04. 윈도우에서 알티베이스 설치 할 때 "이미 설치가 되었다"고 합니다.


현상


윈도우에 알티베이스 install 과 uninstall을 반복했을 경우 정상적으로 install 되지 않는 경우가 있습니다.


에러내용은 full package로 설치하려고 하면 이미 설치 되어있다고 에러가 나오며, patch로 하려고 하면 할 수 없다는 에러가 발생 합니다.


조치


위와 같은 증상은 레지스트리에 등록된 알티베이스 프로그램이 정상적으로 지워지지 않았기 때문입니다.


따라서 레지스트리에서 해당 항목을 삭제하도록 합니다.


레지스트리 실행은 다음과 같습니다. (윈도우 시작 -> 실행 -> regedit.exe 실행)


아래는 삭제할 항목 입니다.





위 항목을 삭제하게 되면 레지스트리에서 정리 되었으므로 install을 정상적으로 진행 할 수 있습니다.

### 02. 운영 및 관리

#### 02-01. [Linux] Altibase 서버 프로세스 자동 시작 스크립트 등록 방법


개요
RedHat 계열 v7 이상

Altibase 자동 시작 및 종료 서비스 작성
Altibase 서비스에서 수행할 파일 작성
altibased.service 심볼릭 링크 설정
systemctl에 altibased.service 등록 및 테스트
systemctl 상태 확인
SELinux 모드 변경 및 상태 확인

SELinux 모드 확인
SELinux Current mode 임시 변경
SELinux Current mode 영구 변경
OS 재기동 후 SELinux 상태 확인
Red Hat 계열 v6 이하

자동 시작 및 종료 스크립트 작성
altibased 수행 권한 변경
chkconfig 등록 및 확인


개요


이 문서는 Redhat 계열 Linux 서버에서 OS 시작 및 종료 시 Altibase DB를 자동으로 시작, 종료하게 하는 방법에 대하여 설명합니다.


하나의 서버에서 1개의 Altibase 서버를 운영시 사용하며, Linux OS의 root 계정으로 모든 항목을 등록 하여야 합니다.


Redhat 계열 v6와 v7으로 나누어 가이드 합니다.


Altibase v4 이상
Red Hat Enterprise Linux 7 이상
Red Hat Enterprise Linux 6 이하





이 문서는 정보 제공을 목적으로 제공되며, 사전에 예고 없이 변경될 수 있습니다. 이 문서는 오류가 있을 수 있으며, 상업적 또는 특정
목적에 부합하는 명시적, 묵시적인 책임이 일절 없습니다.


이 문서에 포함된 Altibase 제품의 특징이나 기능의 개발, 발표 등의 시기는 Altibase 재량입니다.


Altibase는 이 문서에 대하여 관련된 특허권, 상표권, 저작권 또는 기타 지적 재산권을 보유할 수 있습니다.


RedHat 계열 v7 이상


Redhat 계열의 v7 이상에서는 SELinux(Security Enhanced Linux)의 상태를 확인하여 enabled이라면 current mode를 permissive 로 변경해야
됩니다.


SELinux 상태 및 모드의 영구 변경 가이드는 다음의 URL을 참조하세요


URL : https://docs.redhat.com/ko/documentation/red_hat_enterprise_linux/8/html/system_design_guide/changing-selinux-states-andmodes_system-design-guide#changing-selinux-states-and-modes_system-design-guide


Redhat SELinux는 OS의 정책에 따라 변경을 하여야 합니다.


Altibase 자동 시작 및 종료 서비스 작성


File Name : altibased.service
File Path : /usr/lib/systemd/system
altibased.service 스크립트 작성


[root@localhost] # vi altibased.service


[Unit]

Description=AltibaseAutoStartStop
After=network.target syslog.target


[Service]

Type=forking

User=altibase

Group=altibase

LimitNOFILE=1048576

LimitNPROC=infinity

TimeoutSec=0

KillMode=none


ExecStart=/etc/rc.d/init.d/altibase start
ExecStop=/etc/rc.d/init.d/altibase stop


[Install]

WantedBy=multi-user.target

|주요항목 설명|Col2|
|---|---|
|Description|서비스 설명|
|User|수행될 OS 계정명|
|Group|OS 계정의 Group|
|ExecStart|서비스 시작 시 수행할 파일|
|ExecStop|서비스 종료 시 수행할 파일|



altibased.service 작성 후 파일 권한을 755로 권한 변경을 합니다.


[root@localhost] # chmod 755 altibased.service


Altibase 서비스에서 수행할 파일 작성


altibased.service에서 수행할 자동 시작, 종료 스크립트를 작성합니다.


File Name : altibase
File Path : /etc/rc.d/init.d
altibase 스크립트 작성


[root@localhost] # vi altibase


Altibase의 환경 파일 위치는 사용자 환경에 맞게 변경하여야 합니다.


#!/bin/bash

# Startup Script for the Altibase Server
# path: /etc/rc.d/init.d/altibase
# chkconfig: 345 90 10
# processname: altibase

. /home/altibase/altibase_home/conf/altibase_user.env

case "$1" in
start)
echo "Startup altibase: "
${ALTIBASE_HOME}/bin/server start

;;

stop)
echo "Shutdown altibase: "
${ALTIBASE_HOME}/bin/server stop

;;

*)
echo "Usage: service altibase {start | stop}"

exit 1

esac

exit 0


altibase 작성 후 파일 권한을 755로 권한 변경을 합니다.


[root@localhost] # chmod 755 altibase


altibased.service 심볼릭 링크 설정


작성한 서비스 파일 altibased.service 파일을 다음의 위치에서 심볼릭 링크로 존재하여야 합니다.


[root@localhost] # cd /etc/systemd/system/multi-user.target.wants

[root@localhost] # ln -s /usr/lib/systemd/system/altibased.service altibased.service  ==> 심볼릭 링크 설정


systemctl에 altibased.service 등록 및 테스트


systemctl에 altibased.service를 등록하여야 합니다.


[root@localhost] # systemctl enable altibased.service  ==> altibased.service 등록

[root@localhost] # systemctl start altibased.service  ==> altibase start 테스트

[root@localhost] # systemctl stop altibased.service   ==> altibase stop 테스트


서버 종료, 서버 기동 하면서 $ALTIBASE_HOME/trc에 Altibase 정상적으로 중지 및 시작 되는지 확인합니다.


systemctl 상태 확인


[root@localhost] # systemctl status altibased.service


SELinux 모드 변경 및 상태 확인


RedHat 계열 v7 이상에서의 SELinux 모드 변경 및 상태확인 방법입니다.


SELinux 모드 확인


[root@localhost] # sestatus

SELinux status:         enabled

SELinuxfs mount:        /sys/fs/selinux
SELinux root directory:     /etc/selinux
Loaded policy name:       targeted
Current mode:          enforcing    ==> 현재 SELinux 모드
Mode from config file:     enforcing
Policy MLS status:       enabled
Policy deny_unknown status:   allowed
Memory protection checking:   actual (secure)
Max kernel policy version:   31


SELinux Current mode 임시 변경


SELinux의 Current mode를 임시로 변경하면 OS 재기동 후 원래 상태로 변경됩니다.


Current mode를 임시로 변경하며 OS 재기동 시 Altibase Process가 자동으로 시작하지 않습니다.


[root@localhost] # setenforce 0   ==> current mode를 permissive mode로 변경


[root@localhost] # setenforce 1   ==> current mode를 enforoing mode로 변경


SELinux Current mode 영구 변경


SELinux의 Current mode를 영구 변경하기 위해서는 다음의 설정 파일을 변경하여야 합니다.


/etc/selinux/config 파일의 SELINUX 항목을 permissive 값으로 변경 후 OS를 재기동합니다.


[root@localhost] # cd /etc/selinux


[root@localhost] # vi config

# This file controls the state of SELinux on the system.

# SELINUX= can take one of these three values:

#    enforcing - SELinux security policy is enforced.
#    permissive - SELinux prints warnings instead of enforcing.
#    disabled - No SELinux policy is loaded.
#SELINUX=enforcing  # 기존 enforcing
SELINUX=permissive  # 변경 permissive

# SELINUXTYPE= can take one of these two values:

#    targeted - Targeted processes are protected,
#    mls - Multi Level Security protection.


OS 재기동 후 SELinux 상태 확인


[root@localhost] # sestatus

SELinux status:         enabled

SELinuxfs mount:        /sys/fs/selinux
SELinux root directory:     /etc/selinux
Loaded policy name:       targeted
Current mode:          permissive
Mode from config file:     permissive
Policy MLS status:       enabled
Policy deny_unknown status:   allowed
Memory protection checking:   actual (secure)
Max kernel policy version:   31


Red Hat 계열 v6 이하


RedHat 계열 v6에서는 다음의 순서로 Altibase Process를 자동 시작, 종료를 진행합니다.


자동 시작 및 종료 스크립트 작성


altibased 자동 시작, 종료 스크립트를 작성합니다.


File Name : altibased
File Path : /etc/init.d


altibased 스크립트 작성


[root@localhost] # vi altibased


user 항목은 OS에 접속한 OS 계정으로 변경한다.


#!/bin/bash

#

# altibase

#

# chkconfig: 2345 20 80
# description: ALTIBASE process startup


user=altibase


start() {
echo -e "`date +"%Y-%m-%d %H:%M:%S"` : Altibase Server Startup \n" >>
/var/log/${user}_altibased.log 2>&1


ALTIBASE_STATUS=`ps -ef | grep ${user} | grep 'altibase -p' | grep -v grep | wc -l`


if [ $ALTIBASE_STATUS -ne 1 ]; then
su - ${user} -c "server start" >> /var/log/${user}_altibased.log 2>&1

fi

}


stop() {
echo -e "`date +"%Y-%m-%d %H:%M:%S"` : Altibase Server Shutdown \n" >>
/var/log/${user}_altibased.log 2>&1


ALTIBASE_STATUS=`ps -ef | grep ${user} | grep 'altibase -p'| grep -v grep | wc -l`


if [ $ALTIBASE_STATUS -eq 1 ]; then
su - ${user} -c "server stop" >> /var/log/${user}_altibased.log 2>&1

fi

}


case "$1" in
start)

start

;;

stop)

stop

;;

esac


이 스크립트는 샘플 파일입니다. 고객사 OS 유저의 환경 설정에 따라 의도와 다르게 동작할 수도 있으니 반드시 테스트하여 정상 수행
여부를 확인하시기 바랍니다.
로그는 /var/log/${user}_altibased.log 에 남도록 설정했습니다.


altibased 수행 권한 변경


작성한 altibased 파일의 권한을 변경합니다.


[root@localhost] # chmod +x altibased

[root@localhost] # ls -l altibased
-rwxr-xr-x 1 root root 811 Sep 3 13:50 /etc/init.d/altibased


chkconfig 등록 및 확인


chkconfig 유틸리티를 이용하여 서비스를 등록 합니다.


[root@localhost] # chkconfig --add altibased     ==> 서비스 등록


[root@localhost] # ls -l /etc/rc.d/rc*.d/K*alti*   ==> 서비스 등록 확인

[root@localhost] # ls -l /etc/rc.d/rc*.d/S*alti*   ==> 서비스 등록 확인

#### 02-02. column modify 하는 방법


지원버전

구문

TOLERATE DATA LOSS 옵션
DATE 타입의 변환
주의점
사용예시
참고


지원버전


ALTIBASE HDB 5.3.3 이상 버전 부터  ALTER TABLE ~ MODIFY COLUMN ~ 구문을 통해서 테이블의 칼럼타입과 칼럼의 length 를 변경할
수 있습니다.


구문


ALTER TABLE table_name MODIFY COLUMN ( column_name column_type(length) )


TOLERATE DATA LOSS 옵션


테이블의 데이터가 NULL 이 아닌 경우 변환타입에 따라서 자료 손실 (data loss ) 가 발생할 수 있습니다. 만일 이러한 자료 손실을
감수하고서라도 자료형을 변경하고자 하는 경우 TOLERATE DATA LOSS 옵션을 사용할 수 있습니다.


DATE 타입의 변환


DATE 타입 변경시에는 DEFAULT_DATE_FORMATE 프라퍼티에 따라 칼럼의 데이터가 변환됩니다.


주의점


column modify 명령은 잘못 사용할 경우 데이터 손실 ( data loss ) 및 대상 테이블의 데이터 량에 따라서 DB에 부하를 줄 수 있으므로
주의해서 사용해야 합니다.



1. 칼럼 사이즈를 원래 크기 미만으로 줄이지 못합니다.


2. 컬럼의 자료형을 변경하는 경우 자료형에 따라 데이터 손실이 일어날 수 있습니다. 만일 이러한 자료 손실을 감수하고


자료형을 변경하고자 하는 경우 TOLERATE DATA LOSS 옵션을 사용할 수 있습니다



3. 이중화 대상 테이블을 대상으로 작업할 경우 이중화 환경에서의 DDL 작업절차에 따라서 작업을 해야 합니다. 알티베이스 이중화 대상

테이블에 대한 DDL 작업절차 를 참고하십시요.

4. 대상 테이블의 row가 많은 경우 작업시간지연과 logs 영역의 사용량 증가 문제가 발생할 수 있습니다.



컬럼 modify 작업시 만약 변경할 테이블이 메모리 테이블이고 현 ALTIBASE 버전이 5.3.3 이라면 복원을 위한 copy table 형태로
메모리테이블에 생성됩니다.


즉, 메모리 테이블 스페이스의 여유가 있어야 합니다. (참고로 6.1.1 에서는 copy table 형태가 disk tablespace로 저장하기에
tablespace와 disk공간 만 있다면 작업이 가능합니다.)


ALTIBASE에서 권고하는 방법으로는 대상 테이블이 메모리 테이블일 경우 iloader 작업으로 백업을 진행한 다음 대상 테이블을 새로
만들고 data를 import 하는 방식으로 작업방식을 권고 드립니다.


사용예시


<질의> 테이블 book 의 isbn 컬럼을 CHAR(20) 형으로, edition 컬럼을 BIGINT 형으로 변경하라.


iSQL> ALTER TABLE book MODIFY COLUMN (isbn CHAR(20), edition BIGINT);


Alter success.


<실행 예> 아래는 위 질의에 대한 실행 예입니다.


iSQL> create table t1(c1 integer);
Create success.

iSQL> desc t1;

[ TABLESPACE : SYS_TBS_MEM_DATA ]

[ ATTRIBUTE ]

-----------------------------------------------------------------------------

NAME TYPE IS NULL

-----------------------------------------------------------------------------

C1 INTEGER FIXED

T1 has no index

T1 has no primary key
iSQL> insert into t1 values(1111111111);
1 row inserted.

iSQL> select * from t1;

C1

-------------
1111111111

1 rows selected.
iSQL> alter table t1 modify(c1 numeric(10));

[ERR-312EE : Invalid length for the data type
0001 : alter table T1 modify(C1 NUMERIC(10))
^ ^
]
iSQL> alter table t1 modify(c1 numeric(10) tolerate data loss);
Alter success.

iSQL> desc t1;

[ TABLESPACE : SYS_TBS_MEM_DATA ]

[ ATTRIBUTE ]

-----------------------------------------------------------------------------

NAME TYPE IS NULL

-----------------------------------------------------------------------------

C1 NUMERIC(10) FIXED
T1 has no index

T1 has no primary key


참고


보다 자세한 사용법에 관한 내용은 SQL Reference Manual 에서 modify column 사용법을 참고하십시요.

#### 02-03. Database 를 stop 하고 start 하는 방법


ALTIBASE를 stop하는 방법
ALTIBASE 를 start 하는 방법
Database 를 기동한 후 정상 기동 유무를 확인하는 방법
ALTIBASE를 강제 종료하는 방법
ALTIBASE server start/stop 시의 에러 메세지


ALTIBASE를 stop하는 방법


ALTIBASE database 를 stop하는 방법은 아래의 2가지 방법이 있습니다.


(1) server stop script를 이용하는 방법


간단한 명령으로 db server를 중지할 수 있으며 가장 많이 사용되는 방식입니다. ALTIBASE를 설치한 unix 유저 계정에서 아래와 같이
"server stop" 이란 명령으로 db server 의 기동을 중단할 수 있습니다.


명령어 사용법: shell> server stop


(2) isql 접속후 shutdown 명령을 사용하는 방법


isql 로 접속한 후 shutdown 명령을 통해서 shutdown 방식을 선택적으로 사용하여 db를 stop할 수 있습니다.






ALTIBASE 를 start 하는 방법


ALTIBASE database 를 start하는 방법은 아래의 2가지 방법이 있습니다.


(1) server start script를 이용하는 방법


간단한 명령으로 db server를 기동할 수 있으며 가장 많이 사용되는 방식입니다.  ALTIBASE를 설치한 unix 유저 계정에서 아래와 같이 "server
start" 이란 명령으로 db server 를 기동시킬 수 있습니다.


명령어 사용법: shell> server start









(2) isql 접속후 startup 명령을 통해서 start하는 방법


ALTIBASE를 설치한 unix 유저 계정에서 isql 로 sysdba 모드로 db에 접속한 후 단계적을 db를 start할 수 있습니다.


Database 를 기동한 후 정상 기동 유무를 확인하는 방법


ALTIBASE를 기동한 후 성공적으로 ALTIBASE DB 서버가 기동했는지 여부는 아래의 방법으로 확인할 수 있습니다.


(1) server start 후 출력 메세지


server start 명령 또는 isql 을 통해서 DB를 start 했을 때 다음과 같이 " — STARTUP Process Success — "가 출력 됐는지 여부를
확인합니다.


(2) isql 을 통한 접속 테스트


대화형 쿼리 실행 도구인 is 또는 isql 상에서 간단한 SQL문을 실행하여 쿼리를 정상동작 유무 확인을 통해서 DB의 상태를 확인할 수
있습니다.





(3) 간단한 점검 쿼리


아래의 쿼리를 실행해서 간단히 DB의 상태를 확인할 수 있습니다.


세션수 확인 : DB에 현재 접속되어 있는 세션수를 확인합니다.


iSQL> select count(*) from v$session;

COUNT

----------------------
1

1 row selected.


이중화 gap 확인 : 이중화(Replication) 을 사용중인 경우 이중화 gap 을 확인하여  이중화 상태를 확인할 수 있습니다.
이중화 gap 값이  증감을 반복할 경우는 정상상태적인 상태입니다.


iSQL> select rep_name, rep_gap from v$repgap;

REP_NAME                 REP_GAP

-----------------------------------------------------------------
REP1                   567

1 rows selected.

iSQL>


트랜잭션 처리 상태
DML 별 또는 DB에서 현재 처리되고 있는 누적 트랜잭션 처리량을 조회합니다. 계속 증가하고 있으면 정상적인 상태입니다.


iSQL> select * from v$sysstat where name like '%execute%count%';

SEQNUM   NAME                        VALUE

-----------------------------------------------------------------------------
----------
28     execute success count                3186

29     execute success count : insert           3119

30     execute success count : update           0

31     execute success count : delete           0

32     execute success count : select           66

33     rep_execute success count : insert         0
34     rep_execute success count : update         0
35     rep_execute success count : delete         0

36     execute failure count                0

9 rows selected.

iSQL>


ALTIBASE를 강제 종료하는 방법


시스템의 오동작 또는 시스템 리소스 부족등으로  ALTIBASE Database server 가 Hang 상태에 빠져서 server stop 과 같은 정상적인
방법으로는 DB를 stop할 수 없는 경우는 아래의 명령을 사용할 수 있습니다.





강제 종료시 주의점
server kill 은 ALTIBASE를 kill -9 로 죽이는 것과 같은 방식으로 DB process를 강제 종료시키는 것으로 정상적인 상황에서는
사용하지 않는 것이 좋습니다.


server kill 로 ALTIBASE를 강제 종료한 경우, 다음 번 start 시엔 recovery 과정을 거치게 됩니다. recovery 과정 중에 undo 와 redo
할 트랜잭션의 양이 많다면 server start 시에 장시간이 소요될 수도 있습니다.


따라서 가급적이면 정상적인 server stop 명령을 통한 Database를 정지시키는 것이 좋습니다.


ALTIBASE server start/stop 시의 에러 메세지


(1)  The database server is already up and running.


ALTIBASE server 가 이미 기동 되어 있는 상태에서 추가로 server start를 시도한 경우 아래와 같은 메세지가 출력 됩니다. 이미 Database 가
기동 되어 있으므로 server start 를 할 수 없습니다.


(2) Another SYSDBA session is already running


sysdba 권한을 가진 세션은 DB에 오직 한개만 연결을 허용합니다.  sysdba 로 이미 접속되어 있는 session 이 존재하는 경우 server start
또는 server stop 을 위한 추가적인 sysdba 연결이 실패할 경우 나오는 에러 메세지입니다.


이미 연결된 sysdba 세션을 종료한 후 다시 연결을 시도해야 합니다.




#### 02-04. Database 의 db name을 바꾸는 방법

Database 의 db name을 바꾸는 방법
대상버전
유의점
변경절차


Database 의 db name을 바꾸는 방법


ALTIBASE database 를 db name을 바꾸는 방법에 대해서 설명합니다.


대상버전


ALTIBASE HDB 5.3.3 이상의 버전에 대해서 적용되는 방법입니다.


유의점


DB NAME을 바꾸려면 DB를 재생성해야 합니다.  DB를 재생성하면 기존 데이타는 사라지므로  기존 데이타를 복구하면 DB
데이타를 export 해서 백업을 받아 두어야 합니다.


변경절차


(1) DB stop


DB stop 명령으로 DB를 stop 시킵니다.





(2) altibase.properties 의 DB Name 변경


$ALTIBASE_HOME/conf/altibase.properties 파일안의 DB_NAME 을 변경하려고 하는 DB명으로 수정합니다.





(3) server script 수정


$ALTIBASE_HOME/bin/server  script 내의  db create 수행부분의 기본 DB명을  변경하려는 DB 명으로 수정합니다.


(4) 기존 데이타베이스 삭제


새로 Database를 생성하기 위해서는 기존 DB를 삭제해야 합니다.  기존 DB의 삭제는 $ALTIBASE_HOME/dbs/*  와
$ALTIBASE_HOME/logs/*  파일을 삭제하면 됩니다.





(5) 새로운 DB name으로 DB를 새로 생성


server create 명령을 통해서 DB를 새로 생성합니다.


(6) DB 기동


server start 명령으로 DB를 start 합니다.




(7) 변경된 Database명의 확인


DB 기동후에 다음의 쿼리로 변경된 DB명을 확인할 수 있습니다.




#### 02-05. Datafile 을 추가한 이력 확인 방법

확인 방법
지원버전
프라퍼티 변경법
로그 확인 법


확인 방법


데이터파일을 추가하거나 변경한 시간 정보는  별도의 성능뷰 나 v$datafiles 에 기록하지 않습니다. 하지만  DDL문은
QP_MSGLOG_FLAG 프라퍼티가 DDL문을 기록하도록 설정되어 있다면


$ALTIBASE_HOME/trc/altibase_qp.log 에 기록되므로 이 파일을 열어서 datafile 의 변경 내용을 확인할 수 있습니다.


지원버전


HDB 4.3.9 이상의 모든 버전에서 지원합니다.


프라퍼티 변경법


QP_MSGLOG_FLAG의 설정값을 DDL 이 altibase_qp.log 에 로깅 될 수 있도록 변경합니다. 변경방법은 다음 2가지 중 한가지 방법을
사용할 수 있습니다.


ALTER SYSTEM 명령을 사용하는 방법


이 방법을 사용하여 변경할 경우 서버를 재구동 하지 않고 프라퍼티의 값을 변경할 수 있습니다. 서버가 다시 구동될 경우 default 값으로
원복되므로 서버 재구동 후에도 변경값을 유지하려면 $ALTIBASE_HOME/conf/altibase.properties 파일안에


프라퍼티 변경값을 적용해야 합니다.


altibase.properties 파일에 반영하는 방법


1) $ALTIBASE_HOME/conf/altibase.properties 파일안에 아래의 라인을 추가합니다.


QP_MSGLOG_FLAG = 2 # 2: DDL logging


2) ALTIBASE 프로세스를 재구동합니다.


shell> server restart


3) 변경된 값이 적용되었는지 확인합니다.


iSQL> select name, value1 from v$property where name='QP_MSGLOG_FLAG';


HDB 5.1.5.33 이상의 버전부터는 QP_MSGLOG_FLAG 의 default 값이 2 이므로  모든 DDL 이 기본적으로 altibase_qp.log 에
기록됩니다.


로그 확인 법


alter tablespace ~ add datafile 문으로 데이터파일을 추가하면 altibase_qp.log 에 아래와 같은 로그가 남습니다.


[2013/11/27 14:10:57] [Thread-1094719840] [Level-2]

[EXEC_DDL_BEGIN : alter tablespace TEST_TBS add DATAFILE '/altibase_home_533/dbs/test02.dbf']


[2013/11/27 14:10:58] [Thread-1094719840] [Level-2]

[EXEC_DDL_END : SUCCESS]


이를 아래와 같은 구문으로 하시면 결과를 볼 수 있습니다.


shell> $awk '/DATAFILE/ {print last " : " $0}{last=$0}' altibase_qp.log | grep -i 'add'

[2013/11/27 14:10:57] [Thread-1094719840] [Level-2] : [EXEC_DDL_BEGIN : alter tablespace TEST_TBS add DATAFILE
'/altibase_home_533/dbs/test02.dbf']


단, 트레이스 로그파일을 grep 하는 형식의 방법이기 때문에 로그파일에서 지워질 정도로 오래된 이력은 찾을 수 없습니다.

#### 02-06. DB 이름 변경 후 server create 오류발생시


내용


5.3.3 이하 버전 까지는 수동으로 DB를 생성 해줘야 합니다.


server 라는 명령어를 수행하여 아래와 같은 종류의 작업을 수행할 수 있으며  server create 명령을 통해서 DB를 생성할 수 있습니다.


최초 DB 생성시 DB NAME은 mydb로 설정 되어 있으며, 변경은 altibase.properties에서 DB_NAME을 변경하면 됩니다.



DB_NAME 변경 후 server craete 수행 시 아래와 같은 오류가 발생 합니다.





해결방법


이는 $ALTIBASE_HOME/bin/server 스크립트 파일에 DB 이름이 mydb로 되어 있기 때문입니다.





altibase.properties 에서 변경한 DB_NAME과 동일하게 변경 후 DB를 생성 합니다.

#### 02-07. floating point 형 data type (double, float) 사용 시 주의사항


double, float data type 사용 시 주의사항


영향을 받는 버전


double형 숫자값이 잘려서 표현되는 예


iSQL 에서 값이 잘려서 표현되는 현상


iLoader 에서 data 를 export 했을 때


프로그램에서 double 형 호스트 변수에 가져올 올 경우는 정상 조회된다.


Oracle sqlplus 에서도 동일한 현상


문제 해결방안


double, float data type 사용 시 주의사항


알티베이스의 double data type 은 C언어의 double 형 데이터타입과 동일합니다.  double data type은 고정 소수점 방식보다 넓은 범위의
수를 나타낼 수 있는 반면, 근사값으로 표현되기 때문에


그 값이 정확하지 않을 수 있으며 소숫점 뒤의 의미없는 값들이 지나치게 길게 나올수 있습니다.


또한 double/float 형 값을 iSQL로 조회하거나 iloader 로 export 할 경우 소수점 이하의 값이 잘려서 나오지 않을 수 있습니다.


따라서 소수점이하의 값을 정확하게 조회하거나 저장하기 위해서는  numeric 과 같은 고정 소수점 숫자타입을 사용하여야 합니다.


영향을 받는 버전


모든 알티베이스 버전에 동일하게 해당하는 사항입니다.


double형 숫자값이 잘려서 표현되는 예


iSQL 에서 값이 잘려서 표현되는 현상


iLoader 에서 data 를 export 했을 때


프로그램에서 double 형 호스트 변수에 가져올 올 경우는 정상 조회된다.


Oracle sqlplus 에서도 동일한 현상


확인결과 Oracle 의 sqlplus 에서도 동일하게 값이 잘리는 현상이 있습니다.







문제 해결방안


소수점이하의 값을 정확하게 조회하거나 저장하기 위해서는  numeric(scale, presicion )  과 같은 고정 소수점 숫자타입을 사용하여야
합니다.


아래는  numeric 형을 사용할 경우 iSQL에서 값이 정상 조회되는 실행 예입니다.


#### 02-08. HP-UX에서 부팅 시 알티베이스를 자동으로 시작(startup)하는 방법

개요
HP-UX Startup Script란?
알티베이스 자동 구동/종료를 위한 스크립트 작성 방법


STEP 1

STEP 2

STEP 3

STEP 4

STEP 5

STEP 6

STEP 7


개요


HP-UX에서 부팅 시 알티베이스를 자동으로 구동시키기 위한 방법에 대해 설명합니다.


HP-UX Startup Script란?


HP-UX에서는 시스템 부팅/종료 시 수행되는 스크립트 파일들을 다음과 같이 관리합니다.



1.

2.


3.



부팅 시 수행하는 실제 스크립트 파일들은 /sbin/init.d 디렉토리에 존재합니다.
위 스크립트 파일들을 위한 설정파일들은 /etc/rc.config.d 디렉토리에 존재합니다. 하나의 rc script 마다 하나의 설정파일을 가지며
스크립트 수행에 필요한 변수들의 정의와 값을 설정합니다.
부팅 시 수행하는 스크립트 파일들은 /sbin/rc*.d 디렉토리에 존재하며 이 파일들은 /sbin/init.d 디렉토리에 존재하는 파일들의 심볼릭
링크입니다.


알티베이스 자동 구동/종료를 위한 스크립트 작성 방법


STEP 1


/etc/rc.config.d/altibase_conf 파일을 만듭니다.


위에서 설명했듯이 이 파일에 알티베이스의 구동/종료 시 필요한 변수들을 정의하고 값을 설정합니다.


이 파일의 내용은 아래와 같습니다.


만약 HP-UX 부팅 시 알티베이스의 자동 구동을 하고 싶지 않다면 START_ALTIBASE의 값을 0으로 설정합니다. 그리고
ALTIBASE_OWNER나 ALTIBASE_HOME이 변경되었을 경우에는 반드시 altibase_conf 파일도 수정해야 합니다.


STEP 2


/sbin/init.d/alti_start 파일을 만듭니다.


이 파일은 알티베이스 구동 명령어를 이용하여 실제로 알티베이스를 구동하는 스크립트입니다.





STEP 3


/sbin/init.d/alti_stop 파일을 만듭니다.


이 파일은 알티베이스 종료 명령어를 이용하여 실제로 알티베이스를 종료하는 스크립트입니다.


STEP 4


/sbin/init.d/altibase 파일을 만듭니다.


이 파일은 /sbin/init.d/template 파일을 복사해서 만들면 되는데, 실제로 나중에 Start/Stop script가 Symbolic Link를 만들 파일입니다.


#!/sbin/sh


#


# @(#)B.11.11_LR


#


# NOTE: This script is not configurable! Any changes made to this


# script will be overwritten when you upgrade to the next


# release of HP-UX.


#


# WARNING: Changing this script in any way may lead to a system that


# is unbootable. Do not modify this script.


#


rval=0


# Check the exit value of a command run by this script. If non-zero, the


# exit code is echoed to the log file and the return value of this script


# is set to indicate failure.


set_return() {


x=$?


if [ $x -ne 0 ]; then


echo "EXIT CODE: $x"


rval=1 # script FAILed


fi


}


# Kill the named process(es).


# $1=


killproc() {


pid=`ps -el | awk '( ($NF ~ /'"$1"'/) && ($4 != mypid) && ($5 != mypid) )


{ print $4 }' mypid=$$ `


if [ "X$pid" != "X" ]; then


if kill "$pid"; then


echo "$1 stopped"


else


rval=1


echo "Unable to stop $1"


fi


fi


}


case $1 in


'start_msg')


# Emit a _short_ message relating to running this script with


# the "start" argument; this message appears as part of the checklist.


echo "Starting the Altibase Database"


;;


'stop_msg')


# Emit a _short_ message relating to running this script with


# the "stop" argument; this message appears as part of the checklist.


echo "Stopping the Altibase Database"


;;


'start')


# source the system configuration variables


if [ -f /etc/rc.config.d/altibase_conf ] ; then


. /etc/rc.config.d/altibase_conf


else


echo "ERROR: /etc/rc.config defaults file MISSING"


fi


# Check to see if this script is allowed to run...


if [ "$START_ALTIBASE" != 1 ]; then


rval=2


else


# Execute the commands to start your subsystem


su - $ALTIBASE_OWNER -c "/sbin/init.d/alti_start"


fi


;;


'stop')


# source the system configuration variables


if [ -f /etc/rc.config.d/altibase_conf ] ; then


. /etc/rc.config.d/altibase_conf


else


echo "ERROR: /etc/rc.config defaults file MISSING"


fi


# Check to see if this script is allowed to run...


if [ "$START_ALTIBASE" != 1 ]; then


rval=2


else


su - $ALTIBASE_OWNER -c "/sbin/init.d/alti_stop"


# Execute the commands to stop your subsystem


fi


;;


*)


echo "usage: $0 {start|stop|start_msg|stop_msg}"


rval=1


;;


esac


STEP 5


/sbin/rc2.d 디렉토리에서 Startup Script와 Shutdown Script의 Symbolic Link를 만듭니다.





STEP 6


각각의 스크립트가 정상적으로 수행될 수 있도록 실행 권한을 수정합니다.





STEP 7


정상적으로 동작하는지 테스트해 봅니다. 이 때 테스트는 root 계정에서 수행해야 합니다.




#### 02-09. IPC 통신을 위한 알티베이스 서버 설정

개요
버전
ALTIBASE HDB 서버 설정
OS 설정
응용 프로그램의 통신 방법


개요


ALTIBASE HDB 에서 제공하는 데이터베이스 서버와 클라이언트 간 통신 방법은 아래 4가지가 있습니다. 이 중 IPC 통신을 위해
필요한 ALTIBASE HDB 및 OS 설정에 대해 설명합니다.


TCP/IP
유닉스 도메인 소켓(Unix Domain Socket, UDS)를 이용한 IPC
공유 메모리(Shared Memory)를 이용한 IPC 방식
IPCDA (ALTIBASE HDB 7.1.0 부터 지원)
SSL/TLS (ALTIBASE HDB 6.5.1 부터 지원)


각 통신 방법에 대한 설명은 자세한 내용은 http://support.altibase.com/kr/manual 에서 사용하고 있는 버전의 매뉴얼의 Administrator's
Manual 에서 '12. 서버/클라이언트 통신' 부분을 참고하시기 바랍니다.


버전


ALTIBASE HDB 모든 버전


ALTIBASE HDB 서버 설정


기본적으로 알티베이스 서버는 IPC 접속을 허용하지 않습니다. 그래서 IPC 커넥션 타입으로 알티베이스 서버에 접속하기 위해 알티베이스 서버
프로퍼티를 변경해줘야 합니다.


관련 프로퍼티들은 알티베이스 서버 운용 상태에서 변경할 수 없습니다. 따라서 프로퍼티 값을 변경하기 위해서 알티베이스 서버는 재구동이
필요합니다.


IPC_PORT_NO


Windows 시스템에서 알티베이스 서버를 운용할 때 필요한 프로퍼티입니다.
Unix 및 Linux 에서는 IPC 연결을 위해 파일 형태의 '유닉스 도매인 소켓'을 사용하지만 Windows 에서는 이를 지원하지 않기 때문에 IPC 연결을
위해 TCP 포트가 필요합니다.
Windows 에서 IPC 연결은 TCP 연결을 통해 공유 메모리, 세마포어, 뮤텍스를 사용하여 통신합니다.


IPC_CHANNEL_COUNT


알티베이스 서버에 접속할 수 있는 최대 IPC 세션 수를 설정하는 프로퍼티입니다. 기본값이 0 으로 알티베이스 서버는 IPC 접속을 허용하지
않도록 설정되어 있습니다.


IPC_FILEPATH


IPC는 파일 형태의 '유닉스 도메인 소켓'을 통해 ALTIBASE HDB 서버와 통신합니다.
'유닉스 도메인 소켓' 파일이 존재하지 않거나 경로가 올바르지 않게 설정되어 있는 경우 연결이 실패합니다.


이 경로는 IPC_FILEPATH 프로퍼티를 통해 사용자가 임의로 변경할 수 있으며 설정값은 성능 뷰에서 확인할 수 있습니다.


5.5.1.4.2 이상


SELECT NAME, MEMORY_VALUE1 FROM X$PROPERTY WHERE NAME = 'IPC_FILEPATH';


5.5.1.4.1 이하





프로퍼티 변경 방법



1.


2.


3.


4.



altibase.properties 파일 변경
$ALTIBASE_HOME/conf/altibase.properties 파일에서 위에서 설명한 프로퍼티 중에서 필요한 값을 변경하고 altibase.properites
파일을 저장합니다.


$ cd $ALTIBASE_HOME/conf
$ vi altibase.properties


ALTIBASE HDB 재구동
변경한 프로퍼티 값을 알티베이스 서버에 반영하기 위해 알티베이스 서버를 재구동합니다.


$ server restart


프로퍼티 확인 방법
값이 제대로 반영되었는 지 확인합니다.


$ is
iSQL> SELECT NAME, MEMORY_VALUE1 FROM X$PROPERTY WHERE NAME IN ('IPC_FILEPATH',
'IPC_CHANNEL_COUNT');


IPC 접속 테스트
IPC 타입으로 iSQL 접속 테스트 해 봅니다.


$ export ISQL_CONNECTION=IPC                        # iSQL 접속 타입을 설정하는
환경변수를 변경합니다.

$ is

----------------------------------------------------------------
Altibase Client Query utility.

Release Version 7.1.0.6.5

Copyright 2000, ALTIBASE Corporation or its subsidiaries.
All Rights Reserved.

----------------------------------------------------------------
ISQL_CONNECTION = IPC, SERVER = localhost                 # ISQL_CONNECTION = IPC

으로 나오고 iSQL 프롬프트가 떠야 IPC 접속 성공

iSQL>



OS 설정


IPC 통신에는 공유메모리와 세마포어라는 자원이 사용됩니다. 따라서 IPC 타입을 사용하려면 이와 관련된 커널 파라미터를 설정해야 합니다.


OS 에 따라 아래 문서를 참고하세요. AIX 와 WIndows 는 권고 설정이 없습니다.


Linux  : [기술문서] ALTIBASE 운영을 위한 Linux 설정가이드
SunOS : [기술문서] ALTIBASE 운영을 위한 Solaris 설정가이드
HP-UX : [기술문서] ALTIBASE 운영을 위한 HP-UX 설정가이드


응용 프로그램의 통신 방법


응용 프로그램에서의 연결 속성 설정 방법은 http://support.altibase.com/kr/manual 에서 사용하고 있는 버전의 매뉴얼을 참조하십시오.


CLI/ODBC : CLI User's Manual 에서 2. ALTIBASE HDB CLI 함수 -> SQLDriverConnect 함수 설명 참고
APRE (C/C++ Precompiler) : Precompiler User's Manual 에서 6. 내장 SQL문 -> 연결 관련 SQL문 -> CONNECT
JDBC : JDBC User's Manual 에서 1. JDBC 시작하기 -> 연결 정보

#### 02-10. LOCK TIMEOUT 발생 시 조치 방법


개요
버전
발생원인
조치방법
참고


개요


SQL 실행 도중 다음과 같이 오류가 나서 원하는 작업을 못할 때가 있습니다.
The transaction exceeds lock timeout specified by user


$ altierr -w "lock timeout"
0x11075 ( 69749) smERR_ABORT_smcExceedLockTimeWait The transaction exceeds lock timeout
specified by user.
# *Cause: The transaction failed to lock the object.
# *Action: Please abort the transaction.


버전


ALTIBASE HDB 4 이상


발생원인


SQL 실행 도중 다음과 같이 오류가 나서 원하는 작업을 못할 때가 있습니다


위의 오류코드 내용과 같이 해당 객체 - 테이블이나 뷰저장 프로시져 등, - 에 대해 lock을 잡을 수가
없다는 오류입니다.


테이블에 접근하는 모든 세션은 해당 테이블에 LOCK을 잡고 접근하게 됩니다.
즉 그 테이블에 SELECT/INSERT/UPDATE 등의 DML을 수행하거나 ALTER TABLE 등의 DDL을 수행하는
등의
작업을 누군가 하고 있을 때 DROP TABLE을 수행하면 이전 작업이 commit/rollback할 때 까지 기다리게
됩니다.


이 경우사용자가 없는지 확인하고 이전 작업이, commit할 때가지 기다리거나, 세션을 강제로 끊을 수
있습니다.

아래 예와(조치방법) 같이 alter database 문을 사용하면 세션을 강제로 끊을 수 있습니다.


조치방법


 - lock 정보 확인


select T.table_name, X.lock_desc from system_.sys_tables_ T, v$lock X where T.table_oid = X.table_oid and
T.table_name = 'T1'; //T1 테이블 LOCK 정보 확인


- 세션 강제 종료 방법


1. SESSION ID 찾기


select 'alter database mydb session close '||ses_id||'; '
from (select T.table_name,

SES.id ses_id,

X.lock_desc,

X.lock_cnt,

x.TRANS_ID,

SES.client_pid pid,
SES.COMM_NAME,

STM.query qry
from v$session SES,
v$statement STM,
v$lock X,

system_.sys_tables_ T

where SES.id = STM.session_id

and STM.tx_id = X.trans_id

and X.table_oid= T.table_oid
-- and T.table_name like 'TEST1%' -- 원하는 테이블을 명시하십시오.
)

group by ses_id ;

'alter database mydb session close '||SES_

---------------------------------------------
alter database mydb session close 159;
alter database mydb session close 160;
alter database mydb session close 161;
alter database mydb session close 162;

4 rows selected.


2. 세션 종료시키기


$ isql -sysdba -u sys -p manager
iSQL(sysdba)>
alter database mydb session close 159;
alter database mydb session close 160;
alter database mydb session close 161;
alter database mydb session close 162; -- 위의 SQL 결과를 copy/paste 해서 실행합니다.


참고


alter database 명령어로 session을 종료해도 해당 세션외의 다른 부분에는 영향을 미치지 않습니다.


그러나 서비스 중인 시스템에서 session id를 잘못 알고 session을 종료했을 경우, 문제가 될 수
있습니다.


운영을 위한 참고사항으로서비스 중인 시스템일 경우,, 접속된 세션을 끊어도 또 다른 application이
접속하여 해당 테이블에 접근하면 lock이 추가될 수 있으므로 이부분에 대한 고려도 필요합니다.


가능하다면 작업중에는 해당 application이 실행되지 않도록 하는 것이 좋습니다.


#### 02-11. Lock 잡고 있는 세션을 강제로 종료하는 방법

개요
버전
조치방법
참고


개요


Lock 잡고 있는 세션을 강제로 종료하는 방법입니다.


버전


ALTIBASE HDB 4 이상


조치방법


sys 계정으로 접속하셔서 수행해야 합니다.


1. v$lock 에서 table 이름과 transaction ID, lock 종류를 확인합니다.


Select a.table_name, b.trans_id, b.lock_desc From system_.sys_tables_ a, v$lock b

Where a.table_oid = b.table_oid;


2. 위에서 얻은 trans_id 를 이용하여 session 을 찾습니다.


Select session_id, execute_flag, total_time, execute_time, rpad(query,400) From v$statement
Where tx_id = 위에서 얻은 trans_id;


3. session_id 를 이용하여 session 정보를 확인합니다.


Select comm_name, client_app_info From v$session Where id = 위에서 얻은 session_id;


4. session 을 Disconnect 시킵니다.


iSQL> Alter database mydb session close session_id;
mydb 는 database name 으로 $ALTIBASE_HOME/conf/altibase.properties 파일을 열어보면 DB_NAME
항목설정으로 확인하시면 됩니다.

Session_id 는 물론 위에서 획득한 session_id 를 입력합니다.


참고


- 롤백(Roll back) 이 진행중인 세션은 session close 를 수행해도 Disconnect 되지 않아 롤백이 끝날때까지 대기해야 합니다.


- 위의 v$ 뷰 OR SYSTEM_META_TABLE 컬럼에 대한 정보는 Admin 메뉴얼을 참고하시기 바랍니다.

#### 02-11. Maximum Capacity Specifications for Altibase

|Altibase Database Engine Object|Maximum sizes / Numbers Altibase|
|---|---|
|Identifier length|40 bytes|
|Tablespaces per database|64 * 1,024 개|
|Datafiles per tablespace|1,023 개|
|Datafile size|32 gigabytes (64bit 기준)|
|Users per database|2,147,483,638 개|
|Tables per database|2,097,151 개|
|Indexes per table|64 개|
|Columns per table|1,024 개|
|Columns per index|32 개|
|Rows per table|Limited by available storage OR maxrows 개|
|Partitions per partitioned table or index|2,147,483,638 개|
|Constraints per database|2,147,483,638 개|
|Replications per database|6.1.1 이하 버전 : 32개<br>6.3.1 이상 버전 : REPLICATION_MAX_COUNT 프로퍼티로 설정|
|Tables per replication|2147483647|


#### 02-12. MEM_MAX_DB_SIZE 프로퍼티 설정 변경


개요
대상버전
설명
고려사항

현재 값 보다 크게 설정하고자 할 때
현재 값 보다 작게 설정하고자 할 때
DB재구동
절차

변경절차


발생 가능 에러 메세지
확인절차


개요


MEM_MAX_DB_SIZE에 대한 내용 확인 및 변경방법에 대해 알아 봅니다.


대상버전


Altibase 전체 버전


설명


물리 메모리에 저장되는 메모리 테이블스페이스(메모리 테이블 또는 메모리 데이터)로 사용할 수 있는 최대 메모리 크기를 의미합니다.
모든 메모리 테이블스페이스를 합한 전체 사용량에 대한 제약입니다.
메모리 테이블스페이스 각각이 사용할 수 있는 최대 크기가 아닙니다.
메모리 테이블에 생성한 인덱스 크기는 포함되지 않습니다.

변경 트랜잭션 수행 시 발생하는 과거 데이터도 포함됩니다.
변경 트랜잭션이 수행될 경우 트랜잭션이 종료되기 전까지 과거 데이터를 유지하는데(MVCC기법), 메모리 테이블의 경우 메모리 테이블
내에 레코드의 복제본을 생성합니다.
메모리 테이블스페이스 생성 시 최대값을 지정하지 않으면 MEM_MAX_DB_SIZE 설정 값만큼 자동 확장됩니다.


고려사항


현재 값 보다 크게 설정하고자 할 때


MEM_MAX_DB_SIZE 를 현재 값보다 크게 설정하고자 할 때 고려해야 할 부분에 대해 설명합니다


최대 값


물리 메모리의 약 60~70% 정도로 설정할 것을 권장합니다.
메모리 데이터 뿐 아니라 변경 트랜잭션 수행 시 MVCC 기법에 의해 생성될 레코드 복제본 크기도 고려해야 합니다.
예를 들어, 1G짜리 메모리 테이블에 변경 트랜잭션이 발생한 경우 트랜잭션이 완료된 시점에는 해당 테이블의 크기는 2G 가 될
수 있습니다.
메모리는 알티베이스 서버 프로세스 뿐 아니라 OS 및 다른 프로세스에서도 사용해야 할 공유 자원이기 때문에 물리 메모리보다
작게 설정해야 합니다.
물리 메모리보다 크게 MEM_MAX_DB_SIZE를 설정할 수는 있지만 물리 메모리를 초과하여 메모리가 사용될 경우 swap in/out
발생으로 성능 저하 및 시스템에 다양한 문제가 발생할 수 있습니다.


디스크 공간


메모리 테이블스페이스는 백업 용도로 두 벌의 '메모리 체크포인트 이미지 파일'을 디스크에 저장합니다. 그래서 메모리 데이터

사용량보다 보다 두 배의 디스크 공간이 필요합니다.
MEM_MAX_DB_SIZE 를 크게 설정하면 디스크 사용량도 증가하므로 MEM_MAX_DB_SIZE 변경 전에 디스크 공간을 여유있게
확보해야 합니다.
예) MEM_MAX_DB_SIZE 가 60G 일 경우, 120G 의 디스크 공간이 필요.


사용자 환경 설정 (Linux/Unix)


ulimit -a 로 수행하여 아래 설정들이 OS 에서 허용하는 최대 값으로 설정되어 있는 지 확인해야 합니다.
max memory size / virtual memory


커널 파라미터(AIX, HP-UX)


AIX 경우 /etc/security/limits 파일 내용에서 data, rss, fsize등에 대해서 -1로 설정이 되어 있는지 확인합니다.
HP의 경우 kctune을 통해 maxdsiz_64bit 값이 충분히 크게 설정 되어 있는지 확인합니다.
Linux, SunOS 는 해당 없습니다.


현재 값 보다 작게 설정하고자 할 때


MEM_MAX_DB_SIZE 를 현재 값보다 작게 설정하고자 할 때 고려해야 할 부분에 대해 설명합니다.


MEM_MAX_DB_SIZE 는 무조건 작게 설정할 수 없습니다.
증가한 '체크포인트 이미지 파일' 크기를 확인한 후 그보다 크게 설정해야 합니다.
아래 문장으로 그 크기를 확인할 수 있습니다.


TOTAL 이 MAX 보다 작다면 TOTAL 보다는 크면서 기존 값보다는 작게 MEM_MAX_DB_SIZE 를 설정합니다.


IE 사용자에게
IE 에서 SQL 문장을 복사하면 빈 줄이 생길 수 있으니 필요 시 첨부 파일을 사용하시기 바랍니다. total_memory_table
spaces_usage.txt


set linesize 1024

set colsize 20
SELECT TO_CHAR(MEM_MAX_DB_SIZE/1024/1024, '999,999,999') '    MAX(M)',
-- MAX(M)  : MEM_MAX_DB_SIZE 설정 값
TO_CHAR(MEM_ALLOC_PAGE_COUNT*32/1024, '999,999,999') '   TOTAL(M)',
-- TOTAL(M) : 메모리 테이블스페이스로 할당 된 전체 페이지 크기. 체크포인트 이미지 파일 크기를

의미하기도 함.
TO_CHAR((MEM_ALLOC_PAGE_COUNT-MEM_FREE_PAGE_COUNT)*32/1024,
'999,999,999') '   ALLOC(M)',       -- ALLOC(M) : 메모리 테이블스페이스에서 사용하는

메모리 크기
(SELECT TO_CHAR(SUM((FIXED_USED_MEM + VAR_USED_MEM))/1024/1024,
'999,999,999')
FROM V$MEMTBL_INFO) '   USED(M)',
-- USED(M) : ALLOC 중에서 데이터가 저장된 메모리 크기

TO_CHAR((((MEM_ALLOC_PAGE_COUNT-MEM_FREE_PAGE_COUNT)*32*1024)/MEM_MAX_DB_
SIZE)*100, '99.99') 'USAGE(%)' -- USAGE(%) : MAX 대비 ALLOC 사용률
FROM V$DATABASE ;
MAX(M)     TOTAL(M)     ALLOC(M)     USED(M)   USAGE(%)

-----------------------------------------------------------------------
------------------
5,120      2,920       621       142   12.13

1 row selected.


TOTAL 은...

TOTAL(M) 은 메모리 테이블스페이스로 할당 된 전체 페이지 크기를 의미합니다.


이 값에는 메모리 테이블스페이스의 free page 도 포함합니다.
free page 는 물리 메모리에 로딩되지 않을 수도 있습니다. 그래서 이 값을 메모리 테이블스페이스의 물리 메모리
사용량으로 볼 수는 없습니다.


이 값은 체크포인트 이미지 파일의 크기를 의미하기도 합니다.


TOTAL 은 DROP TABESPACE 한 경우를 제외하고는 줄어들지 않습니다. 알티베이스 서버를 재구동 해도 줄어들지
않습니다.





DB재구동


MEM_MAX_DB_SIZE 의 값을 변경하기 위해서는 Altibase를 재구동해야만 합니다.
운용중 property를 동적으로 변경 할 수 없습니다. (서비스 중단이 필요합니다)

## 절차


변경절차



a.


b.


c.



알티베이스 서버 중지


$ server stop


altibase.properties 파일 변경


알티베이스 서버 프로퍼티 파일($ALTIBASE_HOME/conf/altibase.properties) 에서 MEM_MAX_DB_SIZE 를 변경 후
저장합니다.


$ vi $ALTIBASE_HOME/conf/altibase.properties

MEM_MAX_DB_SIZE    = 2G # MEM_MAX_DB_SIZE


알티베이스 서버 구동


$ server start


발생 가능 에러 메세지


[FAILURE] The size of the DB file(SYS_TBS_MEM_DATA-숫자-숫자) exceeds the size specified in the


MEM_MAX_DB_SIZE property.


[원인]


MEM_MAX_DB_SIZE를 증가한 '체크포인트 이미지 파일' 크기보다 작게 설정할 경우, 구동시(startup) 에러가 발생할 수
있습니다


[해결방법]


MEM_MAX_DB_SIZE를 증가한 '체크포인트 이미지 파일' 크기보다 크게 설정해야 합니다.


Error 전문


$ server start

----------------------------------------------------------------
Altibase Client Query utility.

Release Version 7.1.0.5.9

Copyright 2000, ALTIBASE Corporation or its subsidiaries.
All Rights Reserved.

----------------------------------------------------------------
ISQL_CONNECTION = UNIX, SERVER = localhost

[ERR-910FB : Connected to idle instance]

Connecting to the DB server.... Connected.


TRANSITION TO PHASE : PROCESS


TRANSITION TO PHASE : CONTROL

[FAILURE] The size of the DB file(SYS_TBS_MEM_DATA-0-2) exceeds the size specified in
the MEM_MAX_DB_SIZE property.
Startup Failed....

[ERR-91015 : Communication failure.]


확인절차


아래 쿼리로 확인 가능합니다.


-- v$property

iSQL> set linesize 1024

iSQL> set colsize 20
iSQL> SELECT NAME, TO_CHAR(VALUE1/1024/1024, '999,999') AS 'VALUE(MB)' FROM
V$PROPERTY WHERE NAME = 'MEM_MAX_DB_SIZE';
-- v$database

iSQL> set linesize 1024

iSQL> set colsize 20
iSQL> SELECT TO_CHAR(MEM_MAX_DB_SIZE/1024/1024, '999,999') AS
'MEM_MAX_DB_SIZE(MB)' FROM V$DATABASE;


## 참고

관련링크
ERR-11049 ( 69705) Too many pages are allocated ( Maximum Number of Pages= 숫자).
동영상
http://youtube.com/watch?v=tWAC4ghMO3c

#### 02-13. PUBLIC SYNONYM 을 삭제해도 되나요?


삭제 시 영향도
PUBLIC SYNONYM 삭제 방법
PUBLIC SYNONYM 생성 방법


삭제 시 영향도


PUBLIC SYNONYM은 모두 DROP 해도 알티베이스 서버 운용에는 영향을 미치지 않습니다.


PUBLIC SYNONYM 삭제 방법


PUBLIC SYNONYM 은 DB 사용자에게 편의성을 제공하기 위해 데이터베이스 생성 시 생성되는 것으로,
dual 테이블 조회 같은 일반적인 쿼리를 사용하거나 print, println 처럼 프로시저 내에서 많이 사용하고 있어 삭제를 권고하지는 않습니다.


하지만 불가피하게 삭제해야 할 경우, 아래와 같이 DROP 구문을 사용하면 됩니다.


어플리케이션에서 PUBLIC SYNONYM 의 사용 여부를 확인 후 drop 하시기 바랍니다.


PUBLIC SYNONYM 삭제 구문


~~DROP PUBLIC SYNONYM~~ ~~SYNONYM NAME;~~


PRINTLN 삭제 예


~~DROP PUBLIC SYNONYM~~ ~~PRINTLN;~~


PUBLIC SYNONYM 생성 방법


삭제한 PUBLIC SYNONYM 이 필요하게 된 경우 아래와 같이 생성할 수 있습니다.


PUBLIC SYNONY 생성 구문


~~CREATE PUBLIC SYNONYM~~ ~~SYNONYM NAME~~ ~~FOR SYSTEM~~ ~~OBJECT NAME;~~


PRINTLN 생성 예


~~CREATE PUBLIC SYNONYM~~ ~~PRINTLN~~ ~~FOR SYSTEM~~ ~~PRINTLN;~~

#### 02-14. Solaris에서 OS booting 시 자동 altibase startup


요약


Sun Solaris에서 booting시 자동으로 Altibase server를 startup하는 스크립트 작성 방법 입니다.


방법


Solaris는 run level과 관계가 있는 rc스크립트를 제공합니다. 이 스크립트들은 /sbin 디렉토리 안에 존재하며 /etc 디렉토리의 rc 스크립트와


심볼릭 링크되어 있습니다.


/sbin/rc# 스크립트들은 그들과 일치하는 이름의 /etc/rc#.d 디렉토리 아래에 해당하는 파일들이 존재하는데, /etc/rc#.d 디렉토리에는 run
level을 위해 시스템 프로세스를 start하고 stop하는 스크립트들을 포함하고 있습니다.


이 디렉토리 안에 존재하는 파일들을 파일명이 K와 S로 시작하며, K* 스크립트는 프로세스 kill할 때 사용되며, S* 스크립트는 프로세스를 start할
때 사용됩니다. 이들 파일은 alphanumeric 순으로 수행됩니다.


/etc/init.d 디렉토리 안에는 프로세스를 start 시키거나 또는 kill 시키는 실질적인 run control 파일들이 존재하는데 이들은 etc/rc#.d 디렉토리와
하드링크 되어 있습니다.


단계


STEP1


/etc/alti-conf.d/alti.conf file을 만듭니다. 이 file에서는 자동 구동시 필요한 변수들을 정의하고 Setting합니다. 이 file의 내용은 아래와
같습니다.





만약 자동 구동을 하고 싶지 않다면 START_ALTIBASE의 값을 0으로 맞추면 됩니다. 그리고 ALTIBASE_OWNER나 ALTIBASE_HOME이
변경되었을 경우에는 반드시 이 File에 있는 값을 수정 해 주어야 합니다.


STEP2


/etc/init.d/alti_start file을 만든다. 이 script에서는 알티베이스 구동 명령어를 이용해서 실제로 DBMS를 startup하는 script 입니다.







STEP3


/etc/init.d/alti_stop file을 만듭니다.


이 script에서는 알티베이스 구동 명령어를 이용해서 실제로 DBMS를 stop하는 script입니다.


STEP4


/etc/init.d/altibase file을 만듭니다.


이 file은 실제로 나중에 startup script나 stop script가 symbolic link를 만들 file입니다. 이 file의 내용은 아래와 같습니다.


STEP5


/etc/rc3.d Directory에서 Startup Script와 Shutdown Script의 Hard Link를 만듭니다.





STEP6


각각의 Script가 정상적으로 수행될 수 있도록 수행 권한을 Setting합니다.


STEP7


정상적으로 동작하는 지 Test를 해봅니다. 이 때 Test는 root계정에서 수행해 보아야 합니다.




#### 02-15. sys 유저 패스워드 변경 방법

개요
버전
절차

1. alter user 명령어 수행
2. altipasswd 수행
3. sys 패스워드가 포함된 스크립트 수정
문제해결

server start 시 "Invalid password" 에러 발생할 경우 조치방법


개요


sys 계정의 패스워드 변경 절차에 대한 설명입니다.


버전


ALTIBASE HDB 4 이상


절차


sys 계정의 패스워드를 변경하기 위해서는 아래 3가지 단계를 수행해야 합니다.


1. alter user 명령어 수행


알티베이스 서버에 sys 유저로 접속 후 alter user 명령어로 패스워드를 변경합니다.


ALTER USER sys IDENTIFIED BY "new_password";


2. altipasswd 수행


알티베이스 서버 온라인 상태에서 수행합니다.






3. sys 패스워드가 포함된 스크립트 수정


아래 세 개 스크립트에는 sys 패스워드가 포함되어 있습니다.


그래서 sys 패스워드 변경 시 이 스크립트들도 수정해야 합니다.


server 스크립트


$ALTIBASE_HOME/bin/server 스크립트에서 -p 옵션 뒤의 패스워드를 새 패스워드로 변경합니다.


$ cd $ALTIBASE_HOME/bin
$ vi server
ADMIN="${ALTIBASE_HOME}/bin/isql -u sys -p manager -sysdba -noprompt"
ISQL="${ALTIBASE_HOME}/bin/isql -s localhost -u sys -p manager -silent"


is 스크립트
$ALTIBASE_HOME/bin/is 스크립트에서 -p 옵션 뒤의 패스워드를 새 패스워드로 변경합니다.


$ cd $ALTIBASE_HOME/bin
$ vi is
${ALTIBASE_HOME}/bin/isql -s localhost -u sys -p manager $*


il 스크립트


$ALTIBASE_HOME/bin/il 스크립트에서 -p 옵션 뒤의 패스워드를 새 패스워드로 변경합니다.


$ cd $ALTIBASE_HOME/bin
$ vi il
${ALTIBASE_HOME}/bin/iloader -S localhost -U SYS -P MANAGER $*


문제해결



1.



server start 시 "Invalid password" 에러 발생할 경우 조치방법



a.


b.



$ALTIBASE_HOME/bin/server 스크립트를 열어서 아래 부분에 변경한 패스워드로 수정되었는지 확인한다.


위 a는 변경한 패스워드로 적용되어 있는데도 invalid password 에러가 발생한다면 alter user 명령어로만 sys의 패스워드를
변경하고 altipasswd는 실행하지 않았을 가능성이 있다.
이때는 altipasswd를 수행하여 변경한 패스워드를 적용해준 후 server start를 시도한다.


#### 02-16. Table 데이터는 Disk 에 저장하고 인덱스만 Memory 에 생성이 가능한가요?

현상


인덱스는 기본적으로 테이블과 같은 타입으로만 생성되기 때문에 디스크 테이블의 인덱스를 메모리 테이블스페이스에 생성할 수 없으며
ERR-311EC 에러를 출력하게 됩니다.


디스크 테이블스페이스에 테스트 테이블 T1 생성


iSQL> create table t1 (c1 char(10), c2 char(5)) tablespace SYS_TBS_DISK_DATA;


Create success.


메모리 테이블스페이스에 테스트 테이블에 대한 인덱스 생성


아래와 같이 디스크테이블의 인덱스를 메모리테이블스페이스(SYS_TBS_MEM_DATA) 에 생성하려고 할 경우 ERR-311EC 에러가
발생합니다.


iSQL> create index idx_t1 on t1(c1 desc) tablespace SYS_TBS_MEM_DATA;

[ERR-311EC : The type (memory/disk/volatile) of tablespace in which to create the index is not the same as the type of the table.]


해결


디스크 테이블의 인덱스는 디스크테이블스페이스에 생성되도록 하면 에러가 발생하지 않고 정상적으로 생성됩니다.


디스크테이블스페이스에 디스크테이블의 인덱스를 생성


iSQL> create index idx_t1 on t1(c1 desc) tablespace SYS_TBS_DISK_DATA;


Create success.

#### 02-17. TRANSACTION_TABLE_SIZE 변경 시 고려사항


개요
제약 사항
변경 방법

오프라인으로 변경
관련 버그
변경 절차

데이터 마이그레이션이 필요한 경우
오프라인으로 변경 가능한 경우
최대값
TRANSACTION_TABLE_SIZE 와 메모리 사용
TRANSACTION_TABLE_SIZE 를 초과한 경우
성능 뷰
에러 메시지
참고


개요


TRANSACTION_TABLE_SIZE 는 알티베이스 서버 프로퍼티로, 데이터베이스 운용 중 동시에 수행할 수 있는 최대 트랜잭션 수를 의미합니다.


하나의 세션에서는 항상 한 개의 트랜잭션이 수행됩니다. 따라서 동시 접속 세션 수가 증가할 경우 동시에 수행되는 트랜잭션 수도 증가할
가능성이 있기 때문에 MAX_CLIENT 프로퍼티 값을 증가할 때 TRANSACTION_TABLE_SIZE 변경도 고려해야 합니다.


TRANSACTION_TABLE_SIZE 는 트랜잭션의 고유 번호(TID)를 의미하기도 합니다. 잘못된 변경으로 TID 가 꼬이게 되는 경우 서로 다른
트랜잭션이 하나의 트랜잭션으로 인식될 수 있어 변경 시 주의를 요하는 프로퍼티입니다.


또한 ALTIBASE HDB 버전에 따라 변경 방법에 차이가 있으니 관련 내용에 대해 정리합니다.


제약 사항


ALTIBASE HDB 버전에 따라 TRANSACTION_TABLE_SIZE 를 변경하기 위해서 데이터 마이그레이션이 필요한 버전이 있습니다. 아래
'변경 방법' 참고하시기 바랍니다.
현재 값 보다 큰 2^n 값으로만 변경할 수 있습니다.
2^n 인 16 -> 32 -> 64 -> 128 -> 256 -> 512 -> 1024 -> 2048 -> 4096 -> 8192 -> 16384 순으로 변경할 수 있습니다.
큰 값에서 작은 값으로 변경할 수 없습니다.
동시 수행 트랜잭션 수는 사용자 트랜잭션, 이중화 트랜잭션, 내부 트랜잭션을 모두 포함하기 때문에 MAX_CLIENT 보다 크게 설정해야
합니다.
이중화 환경인 경우 이중화 트랜잭션까지 고려하여 MAX_CLIENT 의 두 배까지 설정해야 할 수 있습니다.
이중화 환경인 경우 이중화 대상 서버 간에 TRANSACTION_TABLE_SIZE 가 모두 동일해야 합니다. TRANSACTION_TABLE_SIZE 가
다르면 이중화 sender 쓰레드가 구동되지 않습니다.


변경 방법


오프라인으로 변경


아래 명시된 버전부터는 오프라인으로 변경할 수 있습니다. (ALTIBASE HDB 4 버전은 제외)
















|ALTIBASE HDB 서버<br>버전|4.3.9|5.1.5.93 부터|5.3.3.48 부터|5.3.5.17 부터|5.5.1.1.0 부터|
|---|---|---|---|---|---|
|오프라인으로 변경|변경 불가.<br>데이터 마이그레이션<br>필요.|변경 가능<br>데이터 마이그레이션<br>필요.|변경 가능<br>데이터 마이그레이션<br>필요.|변경 가능<br>데이터 마이그레이션<br>필요.|변경 가능<br>데이터 마이그레이션<br>필요.|







|ALTIBASE HDB 서버<br>버전|4.3.9|5.1.5.0 ~ 5.1.5.92|5.3.3.0 ~ 5.3.3.47|5.3.5.0 ~ 5.3.5.16|5.5.1.0.0 ~ 5.5.1.0.9|
|---|---|---|---|---|---|
|오프라인으로 변경|변경 불가.<br>데이터 마이그레이션<br>필요.|변경 불가.<br>데이터 마이그레이션<br>필요.|변경 불가.<br>데이터 마이그레이션<br>필요.|변경 불가.<br>데이터 마이그레이션<br>필요.|변경 불가.<br>데이터 마이그레이션<br>필요.|


1


24


ALTER SYSTEM 으로 변경











ALTER SYSTEM 으로 변경 시 Alter success. 가 떨어져서 변경 가능한 것처럼 보일 수 있지만 TRANSACTION_TABLE_SIZE 는 온라인 상태에서
변경할 수 없습니다.






|ALTIBASE<br>HDB 서버<br>버전|4.3.9|5.1.5|5.3.3.64 부터|5.3.5.26 부터|5.5.1.2.13 부터|
|---|---|---|---|---|---|
|온라인으로 변경<br>(alter system)|alter system 으로<br>수행가능한 것처럼<br>보이나<br>실제로는 변경 불가 함.|alter system 으로<br>수행가능한 것처럼 보이나<br>실제로는 변경 불가 함.|변경 불가<br>alter system 으로<br>수행가능한 것처럼 보이나|변경 불가<br>alter system 으로<br>수행가능한 것처럼 보이나|변경 불가<br>alter system 으로<br>수행가능한 것처럼 보이나|
























|ALTIBASE<br>HDB 서버<br>버전|4.3.9|5.1.5|5.3.3.0 ~ 5.3.3.63|5.3.5.0 ~ 5.3.5.25|5.5.1.0.0 ~ 5.5.1.2.12|
|---|---|---|---|---|---|
|온라인으로 변경<br>(alter system)|alter system 으로<br>수행가능한 것처럼<br>보이나<br>실제로는 변경 불가 함.|alter system 으로<br>수행가능한 것처럼 보이나<br>실제로는 변경 불가 함.|alter system 으로<br>수행가능한 것처럼 보이나<br>실제로는 변경 불가 함.|alter system 으로<br>수행가능한 것처럼 보이나<br>실제로는 변경 불가 함.|alter system 으로<br>수행가능한 것처럼 보이나<br>실제로는 변경 불가 함.|



BUG-33467 이 반영된 버전에서는 ALTER SYSTEM 으로 변경 시 [ERR-0104E : The property [TRANSACTION_TABLE_SIZE] is read-only.]
에러가 발생합니다.


1


2


관련 버그


BUG-33467 TRANSACTION_TABLE_SIZE 프로퍼티 속성을 readonly 로 변경합니다. ALTER SYSTEM 으로 변경할 수 없게 수정합니다.


BUG-31862 마이그레이션 없이 TRANSACTION_TABLE_SIZE 를 변경할 수 있게 개선합니다. 현재값 보다 큰 2^n 값으로만 변경 가능합니다.


변경 절차


데이터 마이그레이션이 필요한 경우



1.

2.

3.

4.

5.

6.

7.



서비스 downtime 확보
aexport, iloader 를 이용하여 데이터베이스 백업
알티베이스 서버 shutdown
altibase.properties 에서 TRANSACTION_TABLE_SIZE 변경
데이터베이스 재생성
2.에서 백업한 백업본으로 데이터 업로드
알티베이스 서버 startup



오프라인으로 변경 가능한 경우



1.

2.

3.

4.



서비스 downtime 확보
알티베이스 서버 shutdown
altibase.properties 에서 TRANSACTION_TABLE_SIZE 변경
알티베이스 서버 startup



최대값


ALTIBASE HDB 서버 버전에 따라 TRANSACTION_TABLE_SIZE 최대값이 다릅니다. 이전 버전에서는 최대값 설명에 오류가 있는 매뉴얼도
있으니 아래 표를 참고하시기 바랍니다.

|ALTIBASE HDB 서버 버전|4.3.9.222 부터|5.1.5.112 부터|5.3.3.91 부터|5.3.5.35 부터|5.5.1.5.3 부터|
|---|---|---|---|---|---|
|최대값|16384|16384|16384|16384|16384|


|ALTIBASE HDB 서버 버전|4.3.9.0 ~ 4.3.9.221|5.1.5.0 ~ 5.1.5.111|5.3.3.0 ~ 5.3.3.90|5.3.5.0 ~ 5.3.5.34|5.5.1.0.0 ~ 5.5.1.5.2|
|---|---|---|---|---|---|
|최대값|8192|8192|8192|8192|8192|



관련 버그


BUG-37851 TRANSACTION_TABLE_SIZE 값의 최대값을 수정해야 합니다.


TRANSACTION_TABLE_SIZE 와 메모리 사용


ALTIBASE HDB 서버 구동 시에 TRANSACTION_TABLE_SIZE 를 위한 메모리가 미리 할당됩니다. 그래서 TRANSACTION_TABLE_SIZE
설정값에 따라 메모리 사용이 다소 증가할 수 있습니다.


다음은 TRANSACTION_TABLE_SIZE 설정 값에 따른 메모리 사용을 비교한 예입니다.


메모리 사용량은 시스템 환경에 따라 다를 수 있습니다. TRANSACTION_TABLE_SIZE 설정 값에 따른 차이만 참고하기 바랍니다. 단위는 KB
입니다.


|Col1|1024|2048|4096|8192|16384|
|---|---|---|---|---|---|
|VSZ|1,484,952|1,647,264|2,019,544|2,911,096|5,309,148|


테스트 서버 환경은 아래와 같습니다.


Linux
환경 변수 MALLOC_ARENA_MAX=4
ALTIBASE HDB 6.3.1.2.7


v$memstat 에서 가장 큰 차이를 보이는 세부 항목. byte 단위.

|v$memstat|1024|16384|차이|
|---|---|---|---|
|Storage_Memory_Locking|7,276,872|1,618,233,672|1,610,956,800|
|Storage_Memory_Utility|73,101,528|1,149,161,688|1,076,060,160|
|Storage_Memory_Transaction|70,129,144|1,093,979,352|1,023,850,208|
|Transaction_Table|5,852,872|89,657,032|83,804,160|
|Mutex_Manager|71,388,392|136,578,888|65,190,496|
|Transaction_Table_Info|1,662,976|26,607,616|24,944,640|



TRANSACTION_TABLE_SIZE 를 초과한 경우


동시 수행 트랜잭션 수가 TRANSACTION_TABLE_SIZE 를 초과한 경우 다음과 같은 현상으로 데이터베이스가 hang 상태로 보일 수 있으며,


신규 세션 접속 불가
접속되어 있는 세션에서 SQL 수행 시 응답 없음


altibase_boot.log 에 아래와 같은 메시지가 나타납니다.


TRANSACTION_TABLE_SIZE is full !!

Current TRANSACTION_TABLE_SIZE is 1024

Please check TRANSACTION_TABLE_SIZE


성능 뷰


TRANSACTION_TABLE_SIZE 설정 값과 수행 중인 트랜잭션의 수는 V$TRANSACTION_MGR 에서 확인할 수 있습니다.


-- TOTAL_COUNT 는 TRANSACTION_TABLE_SIZE 설정 값을 의미하며 ACTIVE_COUNT 는 수행 중인 트랜잭션의

수를 의미합니다.


iSQL> SELECT TOTAL_COUNT, ACTIVE_COUNT FROM V$TRANSACTION_MGR;

TOTAL_COUNT ACTIVE_COUNT

---------------------------
8192    4

1 row selected.


에러 메시지


ERR-10166(errno=2) TRANSACTION_TABLE_SIZE ['4094'] is not a power of two.


TRANSACTION_TABLE_SIZE 프로퍼티의 값이 2^n 이 아닌 경우 발생하는 에러 메시지입니다.


2^n 값은 16, 32, 64, 128, 256, 512, 1024, 2048, 4096, 8192, 16384 입니다.


ERR-10018(errno=0) The version of data file for backup is not compatible with the version of storage manager. Backup DB => [ Version ID =


4.11.1, Bit = 64, Endian = BIG LogSize = 10485760 Transaction Table Size = 1024 ] Server=>[ Version ID = 4.11.1, Bit = 64, Endian = BIG


LogSize = 10485760 Transaction Table Size = 2048 ]


데이터베이스 생성 시 설정한 TRANSACTION_TABLE_SIZE 를 변경할 수 없는 버전에서 발생하는 에러 메시지입니다.


큰 값에서 작은 값으로 변경할 때로 발생할 수 있습니다.


참고


BUG-31862 TRANSACTION_TABLE_SIZE 확장

#### 02-18. 데이터베이스 보안 점검 체크리스트


개요
계정 관리

계정의 목록화 (비 인가자의 접근 차단을 위한 사용자 계정 관리)
취약한 패스워드 사용 (기본 계정 및 패스워드 변경)
권한 관리

DBA 권한 관리(System Privilege 권한 제한)
WITH GRANT OPTION 사용
환경 파일 점검

il, is, server 파일 접근 권한 설정
altibase.properties 파일 접근 권한 설정
Log Anchor, Logfile, Datafile 접근 권한 설정
Trc 파일 권한 설정
iSQL 명령 쉘 히스토리 검사
DBMS 보안 설정

Public Synonym 사용
로그인 실패 횟수에 따른 잠금시간 등 계정 잠금 정책 설정
패스워드 복잡도 설정
패스워드의 주기적인 변경
ALTIBASE HDB 서비스 포트 기본 값 변경
세션 IDLE_TIMEOUT 설정
기본적인 감사(사용자 문장, 권한, 객체 등) 설정
원격에서 DB 서버로의 접속 제한
SYSDBA 로그인 제한 설정
보안 패치

보안 패치 적용


개요


DB 보안 점검 및 조치 방법에 대한 가이드입니다.


계정 관리


계정의 목록화 (비 인가자의 접근 차단을 위한 사용자 계정 관리)


점검 방법





조치 방법


데이터베이스 사용자 출력 결과에서 불 필요한 계정이 확인되면, DBA 또는 어플리케이션 담당자 확인 후 해당 계정을 제거합니다.


-- 사용자 삭제

DROP USER user_name ;


-- 사용자와 사용자가 생성한 모든 객체 삭제

DROP USER user_name CASCADE;


예외 조치


SYS, SYSTEM_, PUBLIC 계정은 알티베이스 데이터베이스 설치 시 기본으로 생성되는 계정이며, 삭제가 불가능합니다.


취약한 패스워드 사용 (기본 계정 및 패스워드 변경)


점검 방법


ALTIBASE HDB 설치 시 생성되는 사용자 디폴트 패스워드는 아래와 같습니다.

|USER|PASSWORD|
|---|---|
|SYS|MANAGER|



데이터베이스에 접속하여 디폴트 패스워드 사용 여부를 확인합니다.


iSQL> CONNECT SYS/MANAGER;

Connect success.


조치 방법


디폴트 패스워드로 접속이 가능하다면 어플리케이션과의 연관성 확인 후 해당 사용자의 패스워드를 변경합니다.





SYS 사용자 패스워드 변경 방법은 'sys 유저 패스워드 변경 방법' 페이지를 참고하세요.


권한 관리


DBA 권한 관리(System Privilege 권한 제한)


데이터베이스 사용자가 가진 권한을 확인하여 불필요한 시스템 권한을 가지고 있다면 삭제합니다.


단, ROLE 기능은 ALTIBASE HDB 6.5.1 버전부터 지원합니다.


점검 방법


조치 방법





WITH GRANT OPTION 사용


WITH GRANT OPTION은 객체 접근 권한을 부여 받은 사용자가 해당 권한을 다른 사용자에게 부여할 수 있으므로 객체 접근 권한을 DBA 관리
없이 남용할 수 있습니다.


점검 방법





조치 방법





환경 파일 점검


il, is, server 파일 접근 권한 설정


알티베이스는 데이터베이스 구동 및 접속 편의를 위해 is, il, server 스크립트를 제공합니다.
이 파일들의 권한은 보안 진단 기준에 맞춰 수정할 수 있습니다.


점검 방법


조치 방법


파일 권한 설정을 700 으로 설정한다.





altibase.properties 파일 접근 권한 설정


altibase.properties 파일은 알티베이스의 핵심 설정 파일입니다. 이 파일의 접근 권한은 보안 진단 기준에 따라 조정할 수 있습니다.


점검 방법





조치 방법


altibase.properties 파일 권한 설정을 600 또는 640 으로 설정한다.





Log Anchor, Logfile, Datafile 접근 권한 설정


ALTIBASE HDB 데이터베이스 운용에 중요 파일인 하나인 Log Anchor, Logfile, Datafile 파일을 악의적인 의도로 변경하면 데이터베이스 장애가
발생할 수 있습니다.


점검 방법


조치 방법


logs, dbs 디렉토리 권한 설정을 700 또는 750 으로 한다.


Log Anchor, Logfile, Datafile 파일 권한 설정을 600 또는 640 으로 설정한다.





Trc 파일 권한 설정


알티베이스는 데이터베이스 트레이스 로그파일의 권한을 보안 진단 기준에 맞춰 수정할 수 있습니다.


적용 버전


ALTIBASE HDB 6.3.1 이하


조치 방법


6.3.1 버전 이하에서는 기본적으로 666(rw-rw-rw-) 으로 생성 됩니다.


chmod 명령어로 해당 파일의 권한 설정이 가능합니다.





적용 버전


ALTIBASE HDB 6.5.1 이상


조치 방법


6.5.1 버전 이상에서는 기본적으로 644(rw-r--r--) 으로 생성 됩니다.


6.5.1 버전 이상부터 트레이스 로그파일에 대해서 TRC_ACCESS_PERMISSION 프로퍼티로 권한 설정이 가능합니다.


주의 사항


만약 데이터베이스에 접속하는 사용자 중에 다른 그룹에 속한 사용자가 IPC 방식으로 접속할 계획이 있는 경우,


altibase_ipc.log 파일의 권한 설정을 변경할 때 주의가 필요합니다. 권한을 잘못 설정하면 해당 사용자가 IPC로 데이터베이스에 연결하지
못하는 문제가 발생할 수 있습니다.


iSQL 명령 쉘 히스토리 검사


iSQL을 사용하여 데이터베이스에 접속 할 때 계정 및 패스워드를 함께 입력하면 쉘 히스토리 파일에 기록이 남기 때문에 패스워드가 유출될 수
있습니다.


점검 방법





조치 방법


iSQL 접속 시 쉘 프롬프트에 사용자와 패스워드를 입력하지 않습니다.





쉘 히스토리 파일 보호를 위하여 접근 권한을 600으로 설정합니다.


$ chmod 600 ~/.*history


DBMS 보안 설정


Public Synonym 사용


점검 방법





조치 방법


PUBLIC SYNONYM은 데이터베이스 사용 편의를 위해 자동으로 생성되는 객체입니다.
이들은 DUAL 테이블 조회, PRINT 또는 PRINTLN 같은 프로시저 내에서 널리 사용되므로 삭제를 권장하지 않습니다.
하지만 부득이하게 삭제해야 할 경우, 운영자 및 개발자와 충분히 협의한 후 아래 DROP 하시기 바랍니다.





우회 방안


PUBLIC SYNONYM이 삭제된 경우에도 운영자와 개발자는 SYNONYM 사용이 필요할 수 있습니다.


이러한 상황에서는 PUBLIC이 아닌 PRIVATE SYNONYM을 생성하시면 됩니다.


해당 계정으로 로그인한 후 PRIVATE SYNONYM을 생성할 수 있습니다.


로그인 실패 횟수에 따른 잠금시간 등 계정 잠금 정책 설정


적용 버전


ALTIBASE HDB 4.3.9.211 부터
ALTIBASE HDB 5.3.3.89 부터
ALTIBASE HDB 5.5.1.5.1 부터
ALTIBASE HDB 6.1.1.2.1 부터

ALTIBASE HDB 6.3.1

ALTIBASE HDB 6.5.1

ALTIBASE HDB 7.1

ALTIBASE HDB 7.3


점검 방법





조치 방법






패스워드 복잡도 설정


적용 버전


ALTIBASE HDB 4.3.9.211 부터
ALTIBASE HDB 5.3.3.89 부터
ALTIBASE HDB 5.5.1.5.1 부터
ALTIBASE HDB 6.1.1.2.1 부터

ALTIBASE HDB 6.3.1

ALTIBASE HDB 6.5.1

ALTIBASE HDB 7.1

ALTIBASE HDB 7.3


점검 방법





조치 방법


데이터베이스 사용자 패스워드 복잡도 설정을 위해 콜백 함수를 생성하고 CREATE USER 또는 ALTER USER 수행 시 LIMIT 절에
PASSWORD_VERIFY_FUNCTION 옵션을 사용합니다.


콜백함수 생성


CREATE OR REPLACE FUNCTION pwd_verify_function
( username varchar(20),
password varchar(20))
RETURN varchar(100)

AS
result    varchar(100);

pwdLength   integer;
isDigit    boolean;

isChar    boolean;

isPunctuation  boolean;
digitArray  varchar(20);
punctuationArray varchar(25);
charArray   varchar(52);


BEGIN

digitArray  := '0123456789';
charArray   := 'abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ';
punctuationArray :='!"#$%&()``*+,-/:;<=>?_';


-- Check if the password is same as the username
IF LOWER(password) = LOWER(username) THEN
result := 'Password same as or similar to user';

RETURN result;

END IF;


-- Check for the minimum length of the password
IF LENGTH(password) < 4 THEN
result := 'Password length less than 4';

RETURN result;

END IF;


-- Check if the password is too simple.
IF LOWER(password) IN ('welcome', 'database', 'account', 'user', 'password', 'altibase', 'computer', 'abcd')

THEN

result := 'Password too simple';


RETURN result;

END IF;


-- Check if the password contains at least one letter, one digit and one
-- punctuation mark.
-- 1. Check for the digit
isDigit := FALSE;
pwdLength := length(password);

FOR i IN 1...10 LOOP

FOR j IN 1...pwdLength LOOP
IF substr(password,j,1) = substr(digitArray,i,1) THEN
isDigit := TRUE;

GOTO findchar;

END IF;

END LOOP;

END LOOP;

IF isDigit = FALSE THEN
result := 'Password should contain at least one digit, one character and one punctuation';

RETURN result;

END IF;


-- 2. Check for the character

<<findchar>>

isChar := FALSE;
FOR i IN 1...length(charArray) LOOP
FOR j IN 1...pwdLength LOOP
IF substr(password,j,1) = substr(charArray,i,1) THEN

isChar := TRUE;

--GOTO findpunct;

END IF;

END LOOP;

END LOOP;

IF isChar = FALSE THEN

result := 'Password should contain at least one digit, one character and one punctuation';

RETURN result;

END IF;


-- 3. Check for the punctuation
<<findpunct>>

isPunctuation := FALSE;
FOR i IN 1...length(punctuationArray) LOOP
FOR j IN 1...pwdLength LOOP
IF substr(password,j,1) = substr(punctuationArray,i,1) THEN

isPunctuation := TRUE;

GOTO endsearch;

END IF;

END LOOP;

END LOOP;

IF isPunctuation = FALSE THEN

result := 'Password should contain at least one digit, one character and one punctuation';

RETURN result;

END IF;


<<endsearch>>


result := 'TRUE';


RETURN result;

END;

/


패스워드의 주기적인 변경


적용 버전


ALTIBASE HDB 4.3.9.211

ALTIBASE HDB 5.3.3.89

ALTIBASE HDB 5.5.1.5.1

ALTIBASE HDB 6.1.1.2.1

ALTIBASE HDB 6.3.1

ALTIBASE HDB 6.5.1

ALTIBASE HDB 7.1

ALTIBASE HDB 7.3


점검 방법





조치 방법 아래 명령어로 PASSWORD_LIFE_TIME 프로퍼티를 확인하여 값이 0 이라면 패스워드의 만료일이 설정되어 있지


않음을 의미합니다.


$ALTIBASE_HOME/conf/altibase.properties 에서 PASSWORD_LIFE_TIME 과 PASSWORD_GRACE_TIME 프로퍼티 추가 후 ALTIBASE HDB
서버를 재 시작 합니다.


이 프로퍼티 설정 후 데이터베이스 사용자를 생성하면 이 값을 기준으로 패스워드 만료일 및 유예 기간이 설정됩니다.










ALTIBASE HDB 서비스 포트 기본 값 변경


ALTIBASE HDB 서버의 서비스 포트 기본 값은 20300 입니다.


점검 방법





조치 방법


$ALTIBASE_HOME/conf/altibase.properties 에서 PORT_NO 의 값을 변경 후 알티베이스 서버 프로세스를 재 시작


세션 IDLE_TIMEOUT 설정


IDLE_TIMEOUT 은 세션 별로 설정 변경이 가능하여 접속 시 ALTIBASE HDB 서버 프로퍼티의 영향을 받더라도 세션에서 변경할 수 있습니다.


점검 방법









조치 방법


알티베이스 서버 프로세스 재 시작 시에도 변경 값을 반영하려면 $ALTIBASE_HOME/conf/altibase.properties 에서 IDLE_TIMEOUT
프로퍼티의 값을 변경해야 합니다.


기본적인 감사(사용자 문장, 권한, 객체 등) 설정


Audiiting 기능은 ALTIBASE HDB 6.3.1 버전부터 제공합니다.


점검 방법









각 필드에 대한 설명은 General Reference 메뉴얼의 데이터 딕셔너리 부분을 참고.


조치 방법


Administrator's Manual 과 SQL Reference 에서 AUDIT 부분을 참고하여 설정하세요.
매뉴얼 다운로드 페이지 : http://support.altibase.com/kr/manual


원격에서 DB 서버로의 접속 제한


이 기능은 ALTIBASE HDB 5 부터 제공합니다.


점검 방법


$ALTIBASE_HOME/conf/altibase.properties 에서 ACCESS_LIST 프로퍼티 확인.


General Reference 매뉴얼에서 ACCESS_LIST 프로퍼티 설명을 참고합니다.


조치 방법


$ALTIBASE_HOME/conf/altibase.properties 에서 ACCESS_LIST 변경 후 알티베이스 서버 프로세스를 재 시작





SYSDBA 로그인 제한 설정


ALTIBASE HDB 는 SYSDBA 에 대해 로그인 제한이 없고, 원격 접근만 제어할 수 있습니다.
이 기능은 ALTIBASE HDB 5 버전부터 제공합니다.


점검 방법





조치 방법






알티베이스 서버 프로세스 재시작 시에도 변경 값을 반영하려면 $ALTIBASE_HOME/conf/altibase.properties 에서
REMOTE_SYSDBA_ENABLE 프로퍼티의 값을 변경해야 합니다.


보안 패치


보안 패치 적용


Altibase 보안 패치는 고객지원서비스포털 에서 확인할 수 있습니다.


보안관련 버그를 포함한 주요한 버그가 반영된 경우에 고객지원서비스포털에 신규 패치를 업로드 합니다.

#### 02-19. 동시 접속 세션 수(MAX_CLIENT) 증가 시 고려사항


개요
버전
변경 절차
고려 사항

MAX_CLIENT 프로퍼티
TRANSACTION_TABLE_SIZE
OS 사용자 리소스 open files 변경
참고


개요


ALTIBASE HDB 서버에 동시 접속할 수 있는 최대 세션 수 변경 방법에 대해 안내합니다.
동시 접속 세션 수는 알티베이스 서버 프로퍼티 MAX_CLIENT 로 제한할 수 있는데, 이 프로퍼티를 변경해야 할 때 함께 고려해야 할 사항들이
있습니다.


버전


ALTIBASE HDB 모든 버전


변경 절차



1.

2.

3.

4.

5.



서비스 downtime 확보
ALTIBASE HDB 서버 shutdown
알티베이스 서버 프로퍼티 변경. (아래 '고려 사항' 참고)
OS 사용자 리소스 확인 및 필요 시 변경 (아래 '고려 사항' 참고)
ALTIBASE HDB 서버 startup



고려 사항


MAX_CLIENT 프로퍼티


ALTIBASE HDB 서버에 동시에 접속할 수 있는 최대 세션 수를 설정합니다.
기본값은 1000 으로 필요 시 그 이상 변경할 수 있습니다. 이 프로퍼티는 운용 중에 변경할 수 없으므로 변경이 필요할 경우 ALTIBASE HDB
서버를 재구동 해야합니다.


현재 설정 확인 방법


SELECT NAME, VALUE1 FROM V$PROPERTY WHERE NAME = 'MAX_CLIENT';


설정 변경 방법


$ALTIBASE_HOME/conf/altibase.properties 파일에서 MAX_CLIENT 값 변경


TRANSACTION_TABLE_SIZE


이 프로퍼티는 ALTIBASE HDB 서버에서 동시에 수행할 수 있는 트랜잭션의 최대 수를 설정합니다. 동시 접속 세션 수가 증가하면 동시에
수행하는 트랜잭션 수도 증가할 수 있기 때문에 함께 변경할 것을 권고하고 있습니다.
이 프로퍼티는 운용 중에 변경할 수 없으므로 변경이 필요한 경우 ALTIBASE HDB 서버를 재구동 해야합니다.
트랜잭션은 유저가 수행한 트랜잭션 뿐 아니라 시스템 트랜잭션, 이중화 트랜잭션도 포함하기 때문에 MAX_CLIENT 보다 크게 설정해야 합니다.


현재 설정 확인 방법


SELECT NAME, VALUE1 FROM V$PROPERTY WHERE NAME = 'TRANSACTION_TABLE_SIZE';


설정 변경 방법


$ALTIBASE_HOME/conf/altibase.properties 파일에서 TRANSACTION_TABLE_SIZE 값 변경


TRANSACTION_TABLE_SIZE 프로퍼티 설정 값은 현재 값 보다 큰 2^n 으로 설정할 수 있으며 큰 값에서 작은 값으로 변경이 불가
합니다.


ALTIBASE HDB 서버 버전에 따라 변경 방법이 상이하므로 반드이 이 페이지(TRANSACTION_TABLE_SIZE 변경 시 고려사항)를
참고하여 진행하시기 바랍니다.


OS 사용자 리소스 open files 변경


open files 는 프로세스에서 열 수 있는 파일의 수로 프로세스가 접근하는 파일 뿐만 아니라 통신 소켓까지 포함합니다.
예를 들어, 이 값이 10으로 제한된 사용자 환경에서 ALTIBASE HDB 서버를 운영할 경우 동시에 접속 가능한 세션은 10개가 됩니다. (실제로
ALTIBASE HDB 서버가 사용하는 파일까지 고려하면 접속 가능한 세션이 없을 수도 있습니다.)
해당 운영 체제에서 허용하는 최대 값(가능하다면 unlimited)으로 설정할 것을 권고합니다.


설정 값 확인


$ ulimit -Sn   # soft limit

2000


$ ulimit -Hn   # hard limit

unlimited


soft limit 는 OS 사용자에게 설정된 값이고 hard limit 은 root 유저에서 설정한 값입니다. soft limit 은 hard limit 보다 클 수 없습니다.
hard limit 보다 큰 값으로 설정해야 할 경우 root 유저의 설정도 변경해야 합니다.


변경 방법


사용자 환경 설정 변경 방법


환경 설정 파일(.bash_profile 또는 .profile) 에 아래 명령어를 추가합니다.





root 사용자가 변경하는 방법


참고


ALTIBASE HDB 서버 프로퍼티 관련 설명은 http://support.altibase.com/kr/manual 에서 General Reference 메뉴얼을 참고하세요.
MAX_CLIENT 및 관련 설정들은 최대값을 지정한 것이기 때문에 더 크게 변경했다고 해서 DB 성능이나 시스템 자원에 영향을 주지는
않습니다.
설정 변경으로 동시 접속 세션 및 동시에 수행하는 트랜잭션이 증가할 경우 시스템 자원이 증가할 수 있습니다만, 운용 환경에 따라
달라지는 부분이라 어느 정도 영향을 미치는지는 답변하기가 어렵습니다.

#### 02-20. 로그디스크 FULL이 발생하는 경우와 대처 방법


개요
적용버전
Disk Full이 발생한 경우 알티베이스 운용 상태
로그 화일이 있는 디렉토리가 full이 난 경우
Log Disk Full이 발생한 경우 대처방법


개요


알티베이스 운용시 디스크 full이 발생하는 경우 중 로그 화일이 존재하는 디렉토리에서 full이 발생한 경우에 한해


발생할 수 있는 상황과 대처 방법에 대해 기술합니다.


## 적용버전

ALTIBASE HDB 6.3.1 을 기준으로 작성 되었습니다.
추가 문의내용 및 업데이트가 필요한 경우 http://support.altibase.com/kr/ 또는 이 페이지에 댓글로 요청 글 남겨주세요.


Disk Full이 발생한 경우 알티베이스 운용 상태


알티베이스 운용 중 filesystem Full 현상은 DB 화일이 있는 화일시스템의 Full 또는 로그 화일이 있는 화일시스템의 Full일 수 있습니다.


DB 화일이 있는 화일 시스템이 full이 난 경우에는 일반 트랜잭션에는 영향을 미치지 않습니다.


그러나, checkpoint 수행시 충분한 디스크 여유 공간이 없기 때문에 checkpoint 작업이 수행되지 못합니다.


따라서, DB에 수행된 모든 변경 작업은 메모리 상의 DB에만 반영하게됩니다.


LOG 화일이 있는 화일 시스템이 full이 난 경우에는 DB에 변경을 가하는 트랜잭션들은 더 이상 수행되지 않으며


altibase process는 waiting 상태에 들어갑니다.


즉, select를 제외한 서비스들이 중지되는 현상이 발생하게 됩니다.


일반적으로 Disk Full이 발생하는 경우는 파일시스템 크기가 작기 때문이며 충분한 디스크 공간을 확보한 후 알티베이스를


운용하는 것이 바람직합니다.


로그 화일이 있는 디렉토리가 full이 난 경우


디스크 공간을 충분히 확보하여 운용함에도 불구하고 로그 화일이 삭제되지 않아


비정상적으로 로그 화일들이 많이 존재하는 경우는 다음과 같습니다.



1.


2.


3.



이중화를 사용하는 경우 네트워크 불안정이나 기타 다른 이유로 인하여 이중화 데이타가 상대편 서버로 반영되지 못한 경우
=> 이를 확인하기 위하여 이중화 갭을 확인합니다.


SELECT * FROM V$REPGAP;


ARCHIVE_FULL_ACTION 프로퍼티의 값이 1으로 설정된 경우
=> ARCHIVE_DIR에 설정된 디렉토리가 속한 파일 시스템에 충분한 디스크 공간이 없는 경우 아카이브 로그 백업(archive log
backup)을 수행하는 아카이브 쓰레드의 동작을 제어하는 프로퍼티이다.
값이 0인 경우 아카이브 쓰레드는 오류 메시지를 출력한 후, 아카이브 로그파일을 백업하는 작업을 중지하게 된다. 이후 충분한 디스크
공간이 확보된 후에라도 사용자가 명시적으로 아카이브 로그 백업을 활성화하는 명령을 입력하지 않는 한 아카이브 로그 백업은
재개되지 않는다. 이 경우 체크포인트가 발생하면 아카이브 로그파일이 백업되지 않았더라도 불필요한 로그 파일들은 삭제되기 때문에
운영시 주의가 필요하다.
값이 1인 경우 아카이브 쓰레드는 충분한 디스크 공간이 확보되어 아카이브 로그파일을 백업할 수 있을 때까지 기다린다. 이 기간
동안은 체크포인트가 발생하더라도 아카이브 로그파일을 백업할 수 없기 때문에 로그 파일들은 삭제되지 않는다.
$ALTIBASE_HOME/conf/altibase.properties 화일을 참조하거나 isql 상에서 이 프로퍼티의 값을 확인할 수 있다.


select name, value1 from v$property where name like '%ARCHIVE_FULL_ACTION%';


checkpoint가 수행되지 않은 경우
=> 로그 화일의 삭제는 checkpoint 시에만 발생하므로 checkpoint가 정상적으로 수행되었는지의 여부를 확인한다.
checkpoint 수행 여부는 $ALTIBASE_HOME/trc/altibase_sm.log 화일을 참조하여 확인 가능하다.
아래와 같이 checkpoint 정상 수행시 로그가 기록된다.


[2015/12/14 10:42:50] [Thread-140330825209600] [Level-9]

[CHECKPOINT BY USER]

[2015/12/14 10:42:50] [Thread-140330825209600] [Level-9]

[CHECKPOINT-BEGIN]

[2015/12/14 10:42:50] [Thread-140330825209600] [Level-9]

[CHECKPOINT-step2] Write BeginChkpt Log [0,0,6232554]
Active Tx Recovery LSN [0,0,6232554]
Disk Buffer Oldest LSN [0,0,6232554]

[2015/12/14 10:42:50] [Thread-140330825209600] [Level-9]

[CHECKPOINT-step3] Flush Dirty Page(s)

[2015/12/14 10:42:50] [Thread-140330825209600] [Level-9]

[PRE-DirtyPageCount=0]

[2015/12/14 10:42:50] [Thread-140330825209600] [Level-9]

[NEW-DirtyPageCount=8]

[2015/12/14 10:42:50] [Thread-140330825209600] [Level-9]

[DUP-DirtyPageCount=0]

[2015/12/14 10:42:50] [Thread-140330825209600] [Level-9]
+ Begin Sync For All-LFG - Request LSN [0,0,6232995]

[2015/12/14 10:42:50] [Thread-140330825209600] [Level-9]

+ End Sync For All-LFG

[2015/12/14 10:42:50] [Thread-140330825209600] [Level-9]

[FLU-DirtyPageCount=8]

[2015/12/14 10:42:50] [Thread-140330825209600] [Level-9]

[REM-DirtyPageCount=0]

[2015/12/14 10:42:50] [Thread-140330825209600] [Level-9]

[CHECKPOINT-step4] sync Database File

[2015/12/14 10:42:50] [Thread-140330825209600] [Level-0]

==========================================================

SM IO STAT - Checkpoint
DB SIZE   :    262144 Byte ( 8 Page)
LOG SIZE   :     441 Byte

TOTAL TIME  :   0 s 2416 us

LOG SYNC TIME:   0 s 665 us

DB FLUSH TIME:   0 s 1751us

SYNC TIME :   0 s 860 us

WAIT TIME :   0 s 0 us

WRITE TIME:   0 s 891 us

LOG IO PERF : 136.16138155429 MB/sec
DB IO PERF  : 142.775556824672 MB/sec

=========================================================

[2015/12/14 10:42:50] [Thread-140330825209600] [Level-9]

[CHECKPOINT-step5] Write End_Chkpt Log [0,0,6233141]

[2015/12/14 10:42:50] [Thread-140330825209600] [Level-9]

[CHECKPOINT-step6] Sync Log File

[2015/12/14 10:42:50] [Thread-140330825209600] [Level-9]
+ Begin Sync For All-LFG - Request LSN [0,0,6233182]

[2015/12/14 10:42:50] [Thread-140330825209600] [Level-9]

+ End Sync For All-LFG

[2015/12/14 10:42:50] [Thread-140330825209600] [Level-9]

[CHECKPOINT-step7] Check LogFiles That Is Not Needed

[2015/12/14 10:42:50] [Thread-140330825209600] [Level-9]

Replication MinSN48192

[2015/12/14 10:42:50] [Thread-140330825209600] [Level-9]


[2015/12/14 10:42:50] [Thread 140330825209600] [Level 9]

[CHECKPOINT-step8] Update and Flush Log Anchor

[2015/12/14 10:42:50] [Thread-140330825209600] [Level-9]

[CHECKPOINT-step9] Remove Online Log File[None]

[2015/12/14 10:42:50] [Thread-140330825209600] [Level-6]

[CHECK DATABASE SID=0, PPID=0, FID=0]

[2015/12/14 10:42:50] [Thread-140330825209600] [Level-6]

LogAnchor SpaceID=0, SmVersion=100794369, LFGCount=1
DBFileHdr SpaceID=0, SmVersion=100794369, LFGCount=1

[2015/12/14 10:42:50] [Thread-140330825209600] [Level-6]
RedoLSN=control[0,0,6232554], [0,0,6232554]

[2015/12/14 10:42:50] [Thread-140330825209600] [Level-6]
CreateLSN=control[0,0,504], [0,0,504]

[2015/12/14 10:42:50] [Thread-140330825209600] [Level-6]

[CHECK DATABASE SID=0, PPID=1, FID=0]

[2015/12/14 10:42:50] [Thread-140330825209600] [Level-6]

LogAnchor SpaceID=0, SmVersion=100794369, LFGCount=1
DBFileHdr SpaceID=0, SmVersion=100794369, LFGCount=1

[2015/12/14 10:42:50] [Thread-140330825209600] [Level-6]
RedoLSN=control[0,0,6232554], [0,0,6232554]

[2015/12/14 10:42:50] [Thread-140330825209600] [Level-6]
CreateLSN=control[0,0,504], [0,0,504]

[2015/12/14 10:42:50] [Thread-140330825209600] [Level-6]

[CHECK DATABASE SID=1, PPID=0, FID=0]

[2015/12/14 10:42:50] [Thread-140330825209600] [Level-6]

LogAnchor SpaceID=1, SmVersion=100794369, LFGCount=1
DBFileHdr SpaceID=1, SmVersion=100794369, LFGCount=1

[2015/12/14 10:42:50] [Thread-140330825209600] [Level-6]
RedoLSN=control[0,0,6232554], [0,0,6232554]

[2015/12/14 10:42:50] [Thread-140330825209600] [Level-6]
CreateLSN=control[0,0,1426], [0,0,1426]

[2015/12/14 10:42:50] [Thread-140330825209600] [Level-6]

[CHECK DATABASE SID=1, PPID=1, FID=0]

[2015/12/14 10:42:50] [Thread-140330825209600] [Level-6]

LogAnchor SpaceID=1, SmVersion=100794369, LFGCount=1
DBFileHdr SpaceID=1, SmVersion=100794369, LFGCount=1

[2015/12/14 10:42:50] [Thread-140330825209600] [Level-6]
RedoLSN=control[0,0,6232554], [0,0,6232554]

[2015/12/14 10:42:50] [Thread-140330825209600] [Level-6]
CreateLSN=control[0,0,1426], [0,0,1426]

[2015/12/14 10:42:50] [Thread-140330825209600] [Level-9]

[CHECKPOINT-summary] BeginChkptLSN=[0,0,6232554],
EndChkptLSN=[0,0,6233141], DiskRecLSN=[0,0,6232554]

[2015/12/14 10:42:50] [Thread-140330825209600] [Level-9]
Minimum LSN = [0,0,6232554]

[2015/12/14 10:42:50] [Thread-140330825209600] [Level-9]


4.




[CHECKPOINT-END]

[2015/12/14 10:42:50] [Thread-140326782105344] [Level-9]
Sleep checkpoint thread ( next time : 2015-12-14 12:22:50 )


checkpoint가 정상적으로 수행된 경우
(1) checkpoint 수행시 출력되는 메세지 내용 중
[CHECKPOINT-step9] Remove Online Log File 이 부분을 확인한다.
checkpoint 수행 때마다 뒷부분에 나타나는 [None], skip의 경우 checkpoint는 정상 수행되었으나 long transaction이 존재하거나
이중화 데이타가 넘어가지 않아서 로그 화일들이 삭제될 수 없는 경우로 판단한다.


(2) 체크포인트 발생 때마다 계속 로그 화일이 삭제됨에도 불구하고 로그 파티션에 full이 발생했다면 트랜잭션이 굉장히
busy하게 발생하는지의 여부와 파일시스템의 크기를 확인한다.
=> checkpoint가 수행되는 도중에 트랜잭션이 매우 busy하게 발생하여 로그 화일이 삭제되는 갯수만큼 새로운 로그 화일이 생길 수
있기 때문에 이를 고려하여 화일 시스템의 크기를 충분히 크게 설정해야한다.



Log Disk Full이 발생한 경우 대처방법


$ALTIBASE_HOME/logs 공간에 있는 log 파일들을 여유있는 공간으로 옮겨 소프트 링크를 걸어주고
logs 공간을 확보하여 DBMS가 log파일을 I/O 할수있는 공간을 확보해야 합니다.


- 로그파일 move 및 심볼릭 링크 걸어주는 스크립트


echo "Move Logfile Number"

read i

echo "Move Logfile Count"
read j
echo "ALTIBASE LOG DIR"

ALTI_DIR=/sas_home/hychoi/altibase_home_631/logs
echo $ALTI_DIR

echo "MOVE LOG DIR"

MOVE_DIR=/sas_home/hychoi/altibase_home_631/backuplog
echo $MOVE_DIR
MAX=`expr $i + $j`

cd

while true

do

log='logfile'$i
mv $ALTI_DIR/$log $MOVE_DIR
ln -s $MOVE_DIR/$log $ALTI_DIR/$log
i=`expr $i + 1`
if [ $i -eq $MAX ]

then

exit;

fi;

done


참고적으로 현재 DB 가 기동되어 있는 상태라면 사용중인 로그파일은 제외하고 move 시키고 링크를 걸어주어야 합니다.


*사용중인 로그파일 확인방법


lsof -p PID(ALTIBASE DB) | grep logfile


#### 02-21. 사용자 생성(CREATE USER) 및 패스워드 변경(ALTER USER) 방법

개요
적용버전
사용자 생성 및 패스워드 변경방법
SYS사용자 변경
참조 메뉴얼


개요


시스템 사용자인 SYS 사용자 외에 일반 사용자는 create user문을 이용해 생성할 수 있으며, User생성 이후 alter user문을 이용해 사용자의

패스워드를 변경할 수 있습니다.


적용버전


ALTIBASE HDB 6.3.1 을 기준으로 작성 되었습니다.
추가사항 또는 업데이트가 필요한 경우 http://support.altibase.com/kr/ 또는 이 페이지에 댓글로 요청 글 남겨주세요.


사용자 생성 및 패스워드 변경방법


-- 생성

CREATE USER user_name IDENTIFIED BY password;
-- 변경

ALTER USER user_name IDENTIFIED BY change_password;
-- 삭제

DROP USER user_name;

DROP USER user_name CASCADE;


SYS사용자 변경


SYS사용자의 경우 데이터베이스 관리유저로 특별한 역할을 수행합니다.


따라서, 패스워드 변경시 추가작업이 필요하며, 다음의 URL을 통해 확인하시기 바랍니다.


http://aid.altibase.com/pages/viewpage.action?pageId=6521708


참조 메뉴얼


ALTIBASE SQL User's Manual


#### 02-22. 사용자 패스워드 길이 제약 - 버전 별 차이

개요
길이 제약 없음에서 8자리로 변경된 버전
패스워드 길이 8자리에서 16자리로 변경된 버전
패스워드 길이 16자리에서 40자리로 변경된 버전


개요


ALTIBASE HDB 서버 버전에 따른 데이터베이스 사용자 패스워드의 길이 제약을 정리합니다.


길이 제약 없음에서 8자리로 변경된 버전


사용자 패스워드 설정 시 길이 제한이 없었으나, ALTIBASE HDB 내부에서는 입력된 패스워드에서 앞의 8자리만 잘라 저장했습니다.


이로 인해 사용자에게 혼란을 줄 수 있어, 아래 버전부터는 실제 구조에 맞게 패스워드 길이를 제한하도록 변경되었습니다.


적용 버전

ALTIBASE HDB 4.3.9.200

ALTIBASE HDB 5.1.5.98

ALTIBASE HDB 5.3.3.62

ALTIBASE HDB 5.3.5.25

ALTIBASE HDB 5.5.1.2.10

ALTIBASE HDB 6.1.1.0.0


플랫폼 별 패스워드 길이 차이
Windows, Solaris(sparc, x86) : 11byte
그 외 플랫폼 : 8byte


패스워드 길이 8자리에서 16자리로 변경된 버전


패스워드 길이가 8자리로 제한되면서 길이가 짧다는 사용자의 의견을 반영하여 패스워드 길이가 2배인 16자리로 확장 되었습니다.


적용 버전

ALTIBASE HDB 4.3.9.221

ALTIBASE HDB 5.3.3.89

ALTIBASE HDB 5.5.1.5.1

ALTIBASE HDB 6.1.1.1.5

ALTIBASE HDB 6.3.1


플랫폼 별 패스워드 길이 차이
Windows, solaris(sparc, x86) : 22byte
그 외 플랫폼 : 16byte


패스워드 길이 16자리에서 40자리로 변경된 버전


패스워드 길이를 고객의 더 높은 보안 요구 사항을 충족하고 강력한 비밀번호 사용을 권장하기 위하여 기존 16자리에서 40자리로 길이가
늘어나게 되었습니다.


적용 버전

ALTIBASE HDB 6.5.1

ALTIBASE HDB 7.1


ALTIBASE HDB 7.3


플랫폼 별 패스워드 길이 차이
Windows : 40byte


패스워드 길이 증가는 '패스워드 정책 기능'이 추가되면서 반영하게 되었습니다.

ALTIBASE HDB 5.1.5, 5.3.5 버전은 이 기능이 반영되지 않아 패스워드 길이에 변화가 없습니다. (8자리로 변경된 이후 변경 사항
없음)

#### 02-23. 작업(Job)객체 생성 및 실행 방법


개요
버전
사용 방법

작업 스케줄러 활성화(알티베이스 서버 프로퍼티 설정)
프로시저 생성
작업(Job) 객체 생성
작업(Job) 객체 활성화
작업(Job) 객체 및 수행 결과 확인
관련 프로퍼티

JOB_SCHEDULER_ENABLE
JOB_THREAD_COUNT
JOB_THREAD_QUEUE_SIZE
참고


개요


이 문서에서는 작업 개체를 만들고 실행하는 방법과 이를 모니터링하는 방법에 대해 설명한다.

## 버전


Altibase 6.3.1 이상


## 사용 방법

작업(Job) 객체 생성 및 정상적인 동작을 위해서 아래 순서대로 진행해야 한다.



1.

2.

3.

4.

5.



작업 스케줄러 기능 활성화
작업(Job) 객체에 등록할 프로시저 생성
작업(Job) 객체 생성
작업(Job) 객체 활성화 (Altibase 6.5.1 이상에서만 수행함. Altibase 6.3.1은 해당없음)
작업(Job) 객체 및 수행 결과 확인



작업 스케줄러 활성화(알티베이스 서버 프로퍼티 설정)


작업(Job) 객체를 처음 사용한다면 아래 두 개의 알티베이스 서버 프로퍼티를 변경하여 작업 스케줄러 기능을 활성화해야 한다.
작업 스케줄러는 작업(Job)객체에 등록된 설정에 따라 프로시저를 수행시키는 기능을 한다.


JOB_SCHEDULER_ENABLE : 작업 스케줄러 활성화 설정
JOB_THREAD_COUNT     : 작업(Job) 객체 수행을 위한 쓰레드 수


위 두 프로퍼티가 모두 1로 설정되어 있어야 작업 스케줄러를 사용할 수 있다. 기본값이 0이기 때문에 작업 스케줄러를 처음 사용한다면 반드시
확인해야 한다.


JOB_SCHEDULER_ENABLE 프로퍼티는 알티베이스 서버가 구동된 상태에서도 변경할 수 있지만 JOB_THREAD_COUNT 프로퍼티의 값을
변경하기 위해서는 Altibase 서버를 재구동해야 한다.


따라서 작업 스케줄러를 처음 사용할 경우 아래 절차에 따라 프로퍼티를 변경한다.



1.


2.


3.


4.



Altibase 서버 종료


$ server stop


altibase.properties 파일에서 JOB_SCHEDULER_ENABLE 와 JOB_THREAD_COUNT 프로퍼티를 찾아서 값을 1로 변경 후 저장



알티베이스 서버 시작


$ server start


프로퍼티 설정 값 확인


SELECT NAME, MEMORY_VALUE1 FROM X$PROPERTY WHERE NAME IN ('JOB_SCHEDULER_ENABLE',
'JOB_THREAD_COUNT');





프로시저 생성


작업(Job) 객체에 등록할 프로시저를 생성하고 프로시저가 정상적으로 수행하는지 확인한다.
프로시저 정상 수행 여부를 확인하는 이유는 작업 스케줄러에 의해 Job객체가 설정대로 동작하지 않을 경우 프로시저 문제 가능성을 배제하기
위해서이다.


작업(Job) 객체 생성


JOB 객체를 생성한다.


JOB 객체에는 실행할 저장 프로시저와 실행 시각, 실행 주기 등을 설정할 수 있다. JOB 객체 생성 구문은 SQL Reference 매뉴얼을 참고한다.
(매뉴얼 다운로드 페이지 : http://support.altibase.com/kr/manual)


CREATE JOB job1
EXEC proc1
START sysdate
END sysdate + 3

INTERVAL 1 HOUR;


작업(Job) 객체 활성화


이 작업은 Altibase 6.5.1에서 특정 JOB을 활성화/비활성화시키는 기능이 추가되면서 추가된 절차이다.
Altibase 6.3.1 에서는 JOB객체 생성 시 바로 '활성화' 상태가 되지만 Altibase 6.5.1 부터는 CREATE JOB 구문에서 ENABLE 옵션을 사용하지
않으면 기본적으로 '비활성화' 상태이다.
따라서 Altibase 6.5.1부터는 Job객체 생성 후 Job이 동작하도록 하려면 활성화 상태로 변경해야 한다.


변경 방법은 아래와 같다.





Altibase 6.5.1 부터는 JOB객체 생성 시 바로 '활성화' 상태로 설정할 수도 있다.


CREATE JOB job1
EXEC proc1
START sysdate
END sysdate + 3

INTERVAL 1 HOUR

ENABLE;


작업(Job) 객체 및 수행 결과 확인


아래 쿼리로 Job 객체 정보와 Job의 수행 결과를 확인할 수 있다.


-- JOB_NAME : 작업(Job) 객체 이름
-- PROC_NAME : 작업(Job) 객체에 등록한 프로시저 이름
-- INTERVAL, INTERVAL_TYPE : 수행 주기
-- STATE : 작업(Job) 객체 수행 여부 확인. ING 면 작업(Job) 객체에 등록된 프로시저가 수행되고 있음을 알 수

있음.
-- EXEC_COUNT : 작업(Job) 객체 생성 후 실행된 횟수
-- ERROR_CODE : 작업(Job) 객체에 등록한 프로시저 수행이 실패한 경우 에러 코드
-- START_TIME, END_TIME : 작업(Job) 객체가 처음 수행된 시각과 종료 시각
-- LAST_EXEC_TIME : 작업(Job) 객체가 수행된 마지막 시각

SELECT JOB_NAME
, DECODE(IS_ENABLE, 'T', 'ENABLE', 'F', 'DISABLE') IS_ENABLE         -- Altibase 6.3.1 에서는 삭제

후 사용

, EXEC_QUERY PROC_NAME

, INTERVAL
, RPAD(DECODE(INTERVAL_TYPE, 'YY', 'YEARLY', 'MM', 'MONTHLY', 'DD', 'DAILY', 'HH', 'HOURLY', 'MI',
'MINUTELY'), 13) INTERVAL_TYPE
, RPAD(DECODE(STATE, 0, '-', 1, 'ING'), 5) STATE
, RPAD(EXEC_COUNT, 10) EXEC_COUNT
, RPAD(ERROR_CODE, 10) ERROR_CODE
, TO_CHAR(SYSDATE, 'YYYY-MM-DD HH:MI:SS') SYSDATE
, TO_CHAR(START_TIME, 'YYYY-MM-DD HH:MI:SS') START_TIME
, TO_CHAR(END_TIME, 'YYYY-MM-DD HH:MI:SS') END_TIME
, TO_CHAR(LAST_EXEC_TIME, 'YYYY-MM-DD HH:MI:SS') LAST_EXEC_TIME

FROM SYSTEM_.SYS_JOBS_;





에러 코드에 해당하는 에러 메시지 확인 방법
altierr 유틸리티를 이용하여 에러 코드에 해당하는 에러 메시지를 확인할 수 있다.


$ altierr 0x31129


0x31129 ( 201001) qpERR_ABORT_QSV_NOT_EXIST_PROC_SQLTEXT Procedure or function not found : <0%s>.
# *Cause: The specified procedure or function name was not found in the database.
# *Action: Verify that the procedure or function exists.


관련 프로퍼티


JOB_SCHEDULER_ENABLE


프로퍼티 설명


작업 스케줄러 기능을 활성화 또는 비활성화하기 위한 프로퍼티이다.
기본값은 0 으로 작업 스케줄러의 동작을 중지한다.


설정값 변경 방법


ALTER SYSTEM 으로 변경할 수 있다.


ALTER SYSTEM SET JOB_SCHEDULER_ENABLE = 1;      -- 잡 스케줄러 기능 활성화


또는

ALTER SYSTEM SET JOB_SCHEDULER_ENABLE = 0;      -- 잡 스케줄러 기능 비활성화


설정값 확인 방법


아래 쿼리로 JOB_SCHEDULER_ENABLE 설정값을 확인할 수 있다.


SELECT NAME, MEMORY_VALUE1 FROM X$PROPERTY WHERE NAME = 'JOB_SCHEDULER_ENABLE';


JOB_THREAD_COUNT


프로퍼티 설명


작업(Job)을 처리하기 위한 쓰레드 수를 설정하는 프로퍼티이다.
기본값은 0으로 Altibase 서버 구동 시 작업 스케줄러 수행을 위한 쓰레드가 구동되지 않는다.
JOB_THREAD_COUNT 를 0 이 아닌 값으로 설정하면 JobScheduler 쓰레드와 JOB_THREAD_COUNT 수만큼 JobThread 쓰레드가
구동된다.
작업(Job)은 서비스 쓰레드에 의해 수행되지 않고 JobThread 라 불리우는 쓰레드에 의해 처리된다. 그래서 작업 스케줄러에 의해
작업(Job)이 수행되게 하려면 이 프로퍼티를 반드시 설정해야 한다.
이 프로퍼티 값을 변경하려면 Altibase 서버 재구동 작업이 필요하다.


설정값 변경 방법


Altibase 서버 중지
$ALTIBASE_HOME/conf/altibase.properties 에서 JOB_THREAD_COUNT 를 찾아 값 변경 후 저장
Altibase 서버 구동


설정값 확인 방법


아래 쿼리로 JOB_THREAD_COUNT 설정값을 확인할 수 있다.


SELECT NAME, MEMORY_VALUE1 FROM X$PROPERTY WHERE NAME = 'JOB_THREAD_COUNT';


JOB_THREAD_QUEUE_SIZE


프로퍼티 설명


여러 개의 작업(Job) 객체가 동시에 수행될 때 이를 처리하기 위한 큐의 갯수를 설정하는 프로퍼티이다.


예를 들어 작업 스케줄러에 의해 4개의 작업(Job)객체가 같은 시각에 수행될 경우,
JOB_THREAD_COUNT, JOB_THREAD_QUEUE_SIZE 수에 따라 아래와 같은 순서대로 처리된다.


   - JOB_THREAD_COUNT = 4, JOB_THREAD_QUEUE_SIZE = 1 : 동시에 4개가 수행될 수 있음
   - JOB_THREAD_COUNT = 2, JOB_THREAD_QUEUE_SIZE = 2 : 동시에 2개가 수행되고 나머지 2개는 이어서 수행됨
   - JOB_THREAD_COUNT = 1,JOB_THREAD_QUEUE_SIZE = 4 : 동시에 1개가 수행되고 나머지 3개는 이어서 수행됨


기본값 및 최소값이 64 로 충분히 크게 설정되어 있어서 사용자가 임의로 설정할 필요는 없다.
Read-Only 속성으로 이 프로퍼티 값을 변경하려면 알티베이스 서버를 중지해야 한다.


설정값 변경 방법


Altibase 서버 중지
$ALTIBASE_HOME/conf/altibase.properties 에서 JOB_THREAD_QUEUE_SIZE 변경 후 저장
Altibase 서버 구동


설정값 확인 방법


아래 쿼리로 JOB_THREAD_QUEUE_SIZE 설정값을 확인할 수 있다.


SELECT NAME, MEMORY_VALUE1 FROM X$PROPERTY WHERE NAME = 'JOB_THREAD_QUEUE_SIZE';


참고


다음은 작업 스케줄러 관련 설명을 볼 수 있는 매뉴얼들이다.


Administrator's Manual  > 5. 데이터베이스 객체 및 권한 > 작업(Job)
SQL Reference       > 3. 데이터 정의어 > ALTER JOB /

SQL Reference       > 3. 데이터 정의어 > CREATE JOB
SQL Reference       > 3. 데이터 정의어 > DROP JOB
General Reference    > 2. ALTIBASE HDB 프로퍼티 > 기타 프로퍼티
General Reference    > 3. 데이터 딕셔너리 > SYS_JOBS_


매뉴얼 다운로드 페이지 : http://support.altibase.com/kr/manual

#### 02-24. 캐릭터셋 변경 방법 상세 절차


개요


대상버전


변경절차


변경절차 요약


변경절차 상세


STEP 1. 데이터 베이스의 스키마를 다운로드 받습니다.


STEP 2. 데이터를 현재의 character set 으로 다운로드 받습니다.


STEP 3. 데이터베이스를 삭제하고 새로 데이터베이스를 변경하고자 하는 character set 설정으로 생성합니다.


STEP 4 : STEP1에서 다운로드 받은 스키마 정보를 이용하여 새로 생성된 DB에 스키마를 구성합니다.


STEP 5 : 데이터 import 툴을 사용하여 STEP2 에서 다운로드 받은 데이터를 변경된 character set 을 사용하여


업로드합니다.


개요


데이터베이스의 character set은 데이터베이스 생성 시점에 설정값에 의해서 정해지며 다시 변경할 수 없습니다. 따라서 변경을 하려면
데이터베이스를 삭제하고 새로 생성해야 합니다.


데이터베이스가 삭제되면 모든 객체와 데이터가 사라지므로 필요한 데이터는 백업후 데이터베이스를 재생성후 다시 import해야만 합니다.


필요한 데이터를 보존하면서 데이터베이스 character set 을 변경하는 상황을 가정하고 설명합니다.


대상버전


다국어 지원이 가능한 ALTIBASE HDB 5.3.1 이상 버전에 해당하는 설명입니다.


변경절차


변경절차 요약


변경절차는 전체적으로 요약하면 아래와 같은 단계로 진행합니다.


변경절차 상세


상세한 변경절차는 아래와 같은 단계로 진행합니다. 현재 DB의 character set 이 US7ASCII 인 DB의 character set 을 MS949로 변경하는
절차에 대한 설명입니다.


STEP 1. 데이터 베이스의 스키마를 다운로드 받습니다.


STEP 2. 데이터를 현재의 character set 으로 다운로드 받습니다.


STEP 3. 데이터베이스를 삭제하고 새로 데이터베이스를 변경하고자 하는 character set 설정으로 생성합니다.


STEP 4 : STEP1에서 다운로드 받은 스키마 정보를 이용하여 새로 생성된 DB에 스키마를 구성합니다.





STEP 5 : 데이터 import 툴을 사용하여 STEP2 에서 다운로드 받은 데이터를 변경된 character set 을 사용하여


업로드합니다.


#### 02-25. 테이블스페이스 데이터 파일 경로 변경 방법

개요
변경 절차 요약
상세 절차

1. 데이터 파일 현재 경로 확인
2. Altibase 서버 중지
3. 데이터 파일 기본 경로 변경
4. 물리적인 데이터 파일 경로 복사
5. 컨트롤 단계로 Altibase 서버 구동
6. 데이터 파일 경로 변경 DDL 수행
7. 서비스 단계로 Altibase 서버 구동
작업 중 발생할 수 있는 에러 메세지


The data file does not exist
The data file 'XXXXXX' has an invalid header
Unable to invoke the create() function on [XXXXXX/dwfile0.dwf]
CANNOT IDENTIFY DATAFILE

참고


개요


디스크 테이블스페이스의 데이터 파일 및 메모리 테이블스페이스의 메모리 체크포인트 이미지 파일의 경로 변경 절차를 관해 설명합니다.


데이터 파일 경로 변경 작업은 서비스 다운 타임 확보 후


변경 절차 요약



1.

2.

3.

4.

5.

6.

7.



데이터 파일 현재 경로 확인
Altibase 서버 중지
데이터 파일 기본 경로 변경
데이터 파일을 새로운 경로로 복사
컨트롤 단계로 Altibase 서버 구동
데이터 파일 경로 변경 DDL 수행
서비스 단계로 Altibase 서버 구동



상세 절차


1. 데이터 파일 현재 경로 확인


디스크 테이블스페이스와 메모리 테이블스페이스에 따라 확인 방법이 다르므로 각각 확인해야 합니다.


아래 쿼리를 이용하여 확인 후 출력 결과를 메모해둡니다


디스크 테이블스페이스의 데이터 파일 경로





메모리 테이블스페이스의 체크포인트 이미지 파일 경로


2. Altibase 서버 중지


데이터 파일들을 물리적으로 이동해야 하므로 Altibase 서버를 중지해야합니다.


# Altibase 서버 중지 명령어
$ server stop


# Altibase 서버 프로세스 확인 방법
$ ps -ef | grep 'altibase -p' | grep -v grep


3. 데이터 파일 기본 경로 변경


데이터 파일 기본 경로는 테이블스페이스를 생성하거나 데이터 파일 추가할 때 경로를 지정하지 않고 데이터 파일 이름만 지정한 경우
데이터 파일이 위치할 경로를 의미합니다.
데이터 파일 경로 변경 작업 시 기본 경로도 변경해야 할 경우 수행합니다.
altibase.properties 파일에서 설정하며 MEM_DB_DIR, DEFAULT_DISK_DB_DIR 프로퍼티를 찾아 기본 경로를 변경합니다.


# 디스크, 메모리 테이블스페이스에 따라 프로퍼티 이름이 다릅니다.
# altibase.properties 파일에서 MEM_DB_DIR, DEFAULT_DISK_DB_DIR 프로퍼티를 찾아 기본 경로를
변경합니다.
$ egrep 'MEM_DB_DIR|DEFAULT_DISK_DB_DIR' $ALTIBASE_HOME/conf/altibase.properties
MEM_DB_DIR     = ?/dbs # Memory DB Directory
DEFAULT_DISK_DB_DIR = ?/dbs # Disk  DB Directory


4. 물리적인 데이터 파일 경로 복사


"1. 데이터 파일 현재 경로 확인" 에서 확인한 경로에 위치한 모든 데이터 파일과 메모리 체크포인트 이미지 파일들을 변경하려는 경로로
복사합니다.


파일 수 및 파일 크기를 비교하여 정상적으로 복사되었는지 확인합니다.


# 파일 수 비교
$ ls -l /old_path/* | wc -l
$ ls -l /new_path/* | wc -l


# 파일 크기 비교
$ du -sk /old_path/*
$ du -sk /new_path/*


원본 경로를 다른 이름으로 변경합니다.


Altibase 서버 구동 시 원본 파일을 읽을 가능성을 피하고 원본 파일 백업을 위해 원본 경로를 다른 이름으로 변경합니다.


$ mv /old_path /old_path_backup


5. 컨트롤 단계로 Altibase 서버 구동


sysdba 권한으로 iSQL 접속 후


$is -silent -sysdba

[ERR-910FB : Connected to idle instance]
iSQL(sysdba)> STARTUP CONTROL


컨트롤 단계로 구동합니다.


iSQL(sysdba)> STARTUP CONTROL
Connecting to the DB server.... Connected.

TRANSITION TO PHASE : PROCESS

TRANSITION TO PHASE : CONTROL

Command executed successfully.
iSQL(sysdba)>


6. 데이터 파일 경로 변경 DDL 수행


디스크 데이터 파일 및 메모리 체크포인트 이미지 파일 경로 정보는 로그앵커 파일에 저장됩니다. 로그앵커가 알고 있는 정보를 변경하기 위해
DDL 문을 수행합니다.


디스크 데이터 파일 경로 변경 방법


"1. 데이터 파일 현재 경로 확인" 에서 확인한 모든 데이터 파일 수만큼 ALTER DATABASE 문을 반복 수행합니다. 파일 이름은 동일하게
경로만 변경하여 입력해야 합니다.


iSQL(sysdba)> ALTER DATABASE RENAME DATAFILE
'/old_path/system001.dbf' TO '/new_path/system001.dbf';

Alter success.


디스크 데이터 파일 변경 경로 확인


경로가 올바르게 변경되었는지 확인합니다.


# 디스크 테이블스페이스 이름과 데이터 파일 경로와 이름을 출력합니다.

set linesize 1024

set colsize 100

SELECT T.NAME TBS_NAME, D.NAME DATAFILE
FROM V$DATAFILES D, V$TABLESPACES T

WHERE D.SPACEID = T.ID

ORDER BY D.SPACEID, D.ID ;


메모리 체크포인트 이미지 파일 경로 변경


"1. 데이터 파일 현재 경로 확인" 에서 확인한 메모리 테이블스페이스 수 만큼 ALTER TABLESPACE 문을 반복 수행합니다. 이 때
파일명을 지정하지 않고 이전 경로와 새로운 경로만 사용합니다.









메모리 체크포인트 이미지 파일 변경 경로 확인 방법


7. 서비스 단계로 Altibase 서버 구동


sysdba 권한으로 iSQL에 접속한 상태에서 수행합니다.


iSQL(sysdba)> startup
The database server is already up and running.

TRANSITION TO PHASE : META

...중략...

--- STARTUP Process SUCCESS --
Command executed successfully.
iSQL(sysdba)>


작업 중 발생할 수 있는 에러 메세지


데이터 파일 경로 변경 작업 중 발생할 수 있는 에러 메세지와 조지 방법입니다.


The data file does not exist


원인
물리적인 데이터 파일 이동 없이 변경 구문을 수행한 경우 발생할 수 있습니다.


조치
데이터파일을 변경하려는 위치에 데이타 파일을 먼저 이동시킨 후 DB에서의 데이터파일 위치를 변경하는 rename 구문을
실행합니다.


The data file 'XXXXXX' has an invalid header


원인
물리적으로 데이터 파일 복사 단계에서 정상 수행되지 않은 경우 발생할 수 있습니다. 서비스 단계로 데이터베이스 구동 시 구동이
실패합니다.


조치
물리적인 데이터 파일의 작업을 다시 수행합니다.


Unable to invoke the create() function on [XXXXXX/dwfile0.dwf]


원인
double write 파일이 존재하지 않은 경우 발생할 수 있습니다. double write 파일은 데이터베이스 비정상 종료 시 Restart Recovery할
때에 필요한 파일로 기본 경로는 $ALTIBASE_HOME/dbs 입니다. $ALTIBASE_HOME/dbs 경로의 모든 파일을 이동했을 경우 에러가
발생할 수 있습니다.
Altibase 서버 버전에 따라 에러 메시지에 차이가 있을 수 있습니다.


조치
dwfile0.dwf, dwfile1.dwf 파일을 touch 명령어로 임의 생성 후 구동이 가능합니다.
또는 $ALTIBASE_HOME/conf/altibase.properties 에 USE_DW_BUFFER = 0 으로 변경하고 (없으면 추가합니다.) Altibase 서버를
구동합니다. Altibase 서버가 구동되면 USE_DW_BUFFER = 1 로 변경하거나 USE_DW_BUFFER 설정을 altibase.properties 에서
삭제합니다.
double write 파일의 기본 경로를 변경 후 Altibase 서버를 구동해도 됩니다.


# DOUBLE_WRITE_DIRECTORY 프로퍼티 값을 변경.
$ vi $ALTIBASE_HOME/conf/altibase.properties
DOUBLE_WRITE_DIRECTORY    = ?/dbs
DOUBLE_WRITE_DIRECTORY    = ?/dbs


CANNOT IDENTIFY DATAFILE


원인


서비스 단계로 Altibase 서버를 구동할 때 메타 테이블에서 저장된 데이타 파일 경로에서 물리적인 데이터 파일을 찾을 수 발생합니다.
컨트롤 단계에서 올바르지 않은 데이터 파일 경로를 입력한 경우 발생할 수 있습니다.


iSQL(sysdba)> startup
The database server is already up and running.

TRANSITION TO PHASE : META
[SM-WARNING] CANNOT IDENTIFY DATAFILE
[TBS:USER_DATA, PPID-0-FID-0] Datafile Not Found
[SM-WARNING] CANNOT IDENTIFY DATAFILE
[TBS:USER_DATA, PPID-1-FID-0] Datafile Not Found

[FAILURE] The data file does not exist.

Startup Failed....

[ERR-91015 : Communication failure.]
$


조치


컨트롤 단계에서 올바른 경로를 지정하여 DDL 문을 수행합니다.


참고


로그앵커, 온라인 로그파일, 아카이브 로그파일, 더블 라이트(Double Write)파일 경로 변경 방법

#### 02-26. 로그앵커, 온라인 로그파일, 아카이브 로그파일, 더블 라이트(Double Write)파일 경로 변경 방법


개요
변경 절차 요약
상세 절차

1. 현재 경로 설정 확인
2. Altibase 서버 중지
3. 파일 복사 및 프로퍼티 변경

로그 앵커
온라인 로그파일
아카이브 로그파일
더블 라이트(Double Write) 파일
파일 종류 별 프로퍼티와 파일 이름 형식 표
3. Altibase 서버 구동
4. 변경 경로 확인
참고


개요


로그앵커, 온라인 로그파일, 아카이브 로그파일, 더블 라이트(Double Write)파일 경로를 변경하는 방법에 관해 설명합니다.


이 파일들의 경로를 변경하려면 Altibase 서버 재구동을 해야하므로 반드시 서비스 다운 타임을 확보 후 수행해야 합니다.


변경 절차 요약



1.

2.

3.

4.

5.



현재 경로 설정 확인
Altibase 서버 중지
파일 복사 및 프로퍼티 변경
Altibase 서버 구동
변경 경로 확인



상세 절차


1. 현재 경로 설정 확인


아래 문장을 참고하여 각 프로퍼티의 현재 경로를 확인하고 메모합니다.


iSQL> SELECT NAME, VALUE1 FROM V$PROPERTY WHERE NAME IN ('LOGANCHOR_DIR', 'LOG_DIR',
'DOUBLE_WRITE_DIRECTORY', 'ARCHIVE_DIR');


수행 예)
iSQL(sysdba)> set linesize 1024
iSQL(sysdba)> set colsize 60
iSQL(sysdba)> SELECT NAME, VALUE1 FROM V$PROPERTY WHERE NAME IN ('LOGANCHOR_DIR',
'LOG_DIR', 'DOUBLE_WRITE_DIRECTORY', 'ARCHIVE_DIR');

NAME                             VALUE1

----------------------------------------------------------------------------------
-------------------------------------------
LOG_DIR                            /data/eheejung/65166/logs     # 온라인 로그파일 경로
LOGANCHOR_DIR                         /data/eheejung/65166/logs     # 로그앵커 파일 경로


ARCHIVE_DIR                          /data/eheejung/65166/arch_logs  # 아카이브 로그파일 경로


DOUBLE_WRITE_DIRECTORY                    /data/eheejung/65166/dbs     # 더블
라이트(Double Write)파일 경로

4 rows selected.


2. Altibase 서버 중지


Altibase 서버를 중지합니다.


$ server stop


3. 파일 복사 및 프로퍼티 변경


경로를 변경하려는 파일을 새로운 경로로 복사하고 각각의 프로퍼티를 변경합니다.


로그 앵커


로그 앵커 파일은 loganchor0, loganchor1, loganchor2 세 개입니다.
LOGANCHOR_DIR 프로퍼티에 위치한 경로에서 세 개 파일을 모두 새로운 경로로 복사합니다.
$ALTIBASE_HOME/conf/altibase.properties 파일에서 LOGANCHOR_DIR 프로퍼티를 찾아 새로운 경로로 변경합니다.


온라인 로그파일


온라인 로그파일 이름 형식은 logfile 입니다.#
LOG_DIR 프로퍼티에 위치한 경로에서 logfile로 시작하는 모든 파일을 새로운 경로로 복사합니다.
$ALTIBASE_HOME/conf/altibase.properties 파일에서 LOG_DIR 프로퍼티를 찾아 새로운 경로로 변경합니다.


아카이브 로그파일


아카이브 로그파일 이름 형식은 logfile 입니다.#
ARCHIVE_DIR 프로퍼티에 위치한 경로에서 logfile로 시작하는 모든 파일을 새로운 경로로 복사합니다.
$ALTIBASE_HOME/conf/altibase.properties 파일에서 ARCHIVE_DIR 프로퍼티를 찾아 새로운 경로로 변경합니다.


더블 라이트(Double Write) 파일


더블 라이트 파일 이름 형식은 *.dwf 입니다.
DOUBLE_WRITE_DIRECTORY 프로퍼티에 위치한 경로에서 *.dwf로 끝나는 모든 파일을 새로운 경로로 복사합니다.
$ALTIBASE_HOME/conf/altibase.properties 파일에서DOUBLE_WRITE_DIRECTORY 프로퍼티를 찾아 새로운 경로로 변경합니다.


파일 종류 별 프로퍼티와 파일 이름 형식 표

|파일 종류|프로퍼티|파일 이름 형식|
|---|---|---|
|로그 앵커|LOGANCHOR_DIR|loganchor0<br>loganchor1<br>loganchor2|
|온라인 로그파일|LOG_DIR|logfile#|
|아카이브 로그파일|ARCHIVE_DIR|logfile#|
|더블 라이트(Double Write) 파일|DOUBLE_WRITE_DIRECTORY|*.dwf|



3. Altibase 서버 구동


Altibase 서버를 구동합니다.


$ server start


4. 변경 경로 확인


1. 현재 경로 설정 확인 에서 수행한 SQL문으로 변경 경로를 확인합니다.


SELECT NAME, VALUE1 FROM V$PROPERTY WHERE NAME IN ('LOGANCHOR_DIR', 'LOG_DIR',
'DOUBLE_WRITE_DIRECTORY', 'ARCHIVE_DIR');


참고


테이블스페이스 데이터 파일 경로 변경 방법

### 03. 이중화

#### 03-01. replication conflict 발생원인과 해결방법


요약
replication 환경에서 데이터 충돌이 발생하는 경우
conflict를 최대한 방지 할 수 있는 방안
conflict 유형


요약


replication conflict 발생원인과 해결방법을 설명 합니다.


replication 환경에서 데이터 충돌이 발생하는 경우


replication conflict 는 동일한 key 값에 대하여 동시에 insert/update/delete 를 수행할 경우 발생합니다.


- insert conflict: INSERT 충돌이 발생하면, INSERT는 실패하며 altibase_rp.log에 충돌 오류 메시지가 출력됩니다. 존재하는 레코드와 동일한
Key를 가진 데이터를 삽입하려는 경우 발생하는 충돌을 해결하는 정책을 설정하려면, REPLICATION_INSERT_REPLACE 프로퍼티를 사용
합니다. REPLICATION_INSERT_REPLACE=1: 삭제 후 삽입 합니다. REPLICATION_INSERT_REPLACE=0: 삭제하지 않거나 삽입하며, 오류
메시지 출력를 합니다.


- update conflict: UPDATE 충돌이 발생하면, UPDATE는 실패하며 altibase_rp.log에 충돌 오류 메시지가 출력됩니다. 충돌 해결을 위해
REPLICATION_UPDATE_REPLACE 프로퍼티를 사용할 수 있습니다. 이전 이미지가 다른 데이터를 변경시키거나, 존재하지 않는 프라이머리
키로 변경하려 할 때 발생합니다. 예를 들어, 현재 10이라는 데이터가 있는데 복제 트랜잭션은 20에서 30으로 바꾸라는 갱신이 발생한 경우,
상황에 따라 다음과 같은 정책을 사용할 수 있습니다. REPLICATION_UPDATE_REPLACE=1 : 갱신 합니다.
REPLICATION_UPDATE_REPLACE=0 : 갱신하지 않으며, 충돌 오류 메시지를 출력 합니다.


- delete conflict: DELETE 충돌이 발생하면, DELETE 는 실패하며 altibase_rp.log에 충돌 오류 메시지가 출력됩니다.


insert 의 경우를 예를 들면


1) A 서버에서 key=1 인 데이타가 insert 된 후 B서버로 이중화데이타를 전송하기 전에


2) B서버에서 동일한 key=1 데이타가 insert 될 경우 나중에 B서버에서 수신한 이중화 데이터는 이미 B서버에 동일한 key=1 인 데이타가
존재하므로 conflict 가 발생하게 됩니다.


conflict를 최대한 방지 할 수 있는 방안


가장 좋은 방법은 양쪽서버에서 동일한 Key 값으로 insert/update/delete 를 수행하지 않도록 하는 것입니다.


예를 들어 만약 특정테이블에 대하여 Sequence 가 primary key 일경우 한쪽은 홀수로 다른쪽 서버에는 짝수로만 데이타를 insert/update/delete
수행한다면 절대로 replication conflict가 발생되지 않습니다.


그리고 bulk 성 insert/update/delete 를 수행하지 않도록 해야 합니다.


알티베이스에서 지원하는 replication conflict resolution 은 다음의 3가지 방안이 있습니다.


1) User-Oriented Scheme


(1) insert conflict : 동일한 key를 가진 데이타를 insert하려는 경우, 반영하지 않습니다. (altibase_rp.log 에 Conflict Error Message 출력 )


(2) delete confilct : 동일한 key를 가진 데이타를 Delete하려는 경우, 반영하지 않습니다. (altibase_rp.log 에 Conflict Error Message 출력 )


(3) update conflict : 동일한 key를 가진 데이타를 Update하려는 경우 아래의 속성 값에 따라서 반영여부를 판단합니다.


- REPLICATION_UPDATE_REPLACE=1 : 갱신함


- REPLICATION_UPDATE_REPLACE=0 : 갱신하지 않으며 Conflict


Error Message 출력


2) Master-slave Scheme


이중화객체를 선언시 구문에 as master 또는 as slave 를 지정하면 다음과 같이 이중화 conflict를 처리합니다.


(1) Master 의 처리방식 : Insert/Update/Delete conflict 에 대하여 모두 반영하지 않는다.


(2) Slave 의 처리방식


- Insert conflict : 기존에 존재하는 레코드를 삭제하고 새로운 레코드를 추가한다.


- Update conflict : 충돌을 무시하고 무조건 반영한다.


- Insert conflict : 반영하지 않는다.


3) Timestamp-based Scheme


REPLICATION_TIMESTAMP_RESOLUTION 프로퍼티 값을 1로 설정한 후 이중화테이블에 timestamp 컬럼을 사용하여 최신의 값으로 반영하는
방법입니다. 이 방법은 이중화대상 테이블 모두에 timestamp 컬럼을 추가해야 하고 이중화되는 양 서버간의 시간을 동일하게 설정해야 하는
제약사항이 존재합니다.


conflict 유형


conflict가 발생하면 $ALTIBASE_HOME/trc/altibase_rp.log에 로그가 남습니다.


- insert conflict: 이미 동일한 PK(Primary Key)가 존재할 경우 발생 합니다.


[2015/04/28 10:11:33] [Thread-489] [Level-2]
ERR-11058(errno=0) The row already exists in a unique index.


[2015/04/28 10:11:33] [Thread-489] [Level-3]
INSERT INTO TEST VALUES ( 14, 0, 0,, 0, 0, 0, 0 );


- update conflict: PK(Primary Key) 는 같으나 리모트 서버에서 온 변경전 값이 현재값과 다를 경우 발생 합니다.


[2015/04/27 18:49:32] [Thread-489] [Level-2]
ERR-610f7(errno=16) [Receiver] Unable to find record in executeUpdate() function


[2015/04/27 18:49:32] [Thread-489] [Level-2]
ERR-61000(errno=16) The received record is not found in the database.


[2015/04/27 18:49:32] [Thread-489] [Level-3]

UPDATE TEST SET C2 = 20150428 WHERE C1 =1231232 ;


- delete conflict: PK(Primary Key) 는 같으나 리모트 서버에서 온 변경전 값이 현재값과 다를 경우 발생 합니다.


[2015/10/28 17:03:08] [Thread-140059163547392] [Level-2]
ERR-610f7(errno=16) [Receiver] Unable to find record in executeDelete() function


[2015/10/28 17:03:08] [Thread-140059163547392] [Level-3]

DELETE FROM TEST WHERE C1 = 21987744;


#### 03-02. 동일 IP로 여러 개의 이중화 객체를 생성하는 방법

개요
버전
절차

관련 프로퍼티 확인
관련 프로퍼티 변경
이중화 객체 생성
이중화 객체의 호스트 정보 확인 방법
참고


개요


알티베이스 이중화는 다수의 이중화 객체 생성 시 동일한 IP Address 를 사용할 수 없는 제약을 가지고 있었다.





Altibase 6.5.1 부터 추가된 프로퍼티로 이러한 제약없이 동일한 호스트 정보로 서로 다른 이중화 객체를 생성할 수 있게 되었다.


버전


Altibase 6.5.1 이상


절차


관련 프로퍼티 확인


알티베이스 서버 프로퍼티 REPLICATION_ALLOW_DUPLICATE_HOSTS 의 값을 확인한다.


이 프로퍼티의 기본값은 0으로 서로 다른 이중화 객체가 동일한 호스트 정보를 가지는 것을 허용하지 않는다.


set linesize 1024

set colsize 60

SELECT NAME, VALUE1 FROM V$PROPERTY WHERE NAME = 'REPLICATION_ALLOW_DUPLICATE_HOSTS';


관련 프로퍼티 변경


REPLICATION_ALLOW_DUPLICATE_HOSTS프로퍼티의 값이 0인 경우 1로 변경한다.


ALTER SYSTEM SET REPLICATION_ALLOW_DUPLICATE_HOSTS = 1;


프로퍼티의 변경값을 영구적으로 적용하고자 할 경우 altibase.properties 파일에서 해당 프로퍼티의 값을 수정 후 저장한다.


cd $ALTIBASE_HOME/conf

vi altibase.properties

REPLICATION_ALLOW_DUPLICATE_HOSTS   = 1


이중화 객체 생성


동일한 호스트 정보를 가진 하나 이상의 이중화 객체를 생성한다.





이중화 객체의 호스트 정보 확인 방법


이중화 객체에 등록된 호스트 정보는 아래 문장으로 확인할 수 있다.


SELECT REPLICATION_NAME, HOST_IP, PORT_NO FROM SYSTEM_.SYS_REPL_HOSTS_ ORDER BY HOST_NO;


참고


Altibase 6.5.1 New Features Guide
General Reference (Altibase 6.5.1 이상)
매뉴얼 다운로드 : http://support.altibase.com/kr/manual

#### 03-03. 알티베이스 이중화 대상 테이블에 대한 DDL 작업


개요
대상버전
방법

서비스 중단하에서의 작업
서비스 무중단 제약하에서의 작업


개요


일반적으로 DB 에 대한 DDL 작업은 테이블에 대한 독점적인 잠금(Lock) 을 필요로 합니다. ALTIBASE HDB 는 지역서버에서 발생한 트랜잭션
로그를 상대편 서버에 전송하여 데이터를 일치시키는 형태의 네트워크 기반의 이중화 기법을 사용하며


DDL 같은 작업은 로그로 전송하지 않아 DDL 작업은 복제되지 않습니다. 따라서 디스크 공유방식과는 다르게 각각의 노드(Server) 에서 DDL
작업을 수행하는 다른 방식의 작업절차가 필요합니다.


대상버전


ALTIBASE HDB는 버전에 따라서 지원하는 DDL 구문의 종류가 다르며 이중화 관련한 DDL 구문의 기능도 차이가 있습니다.


자세한 내용은 http://support.altibase.com/kr/manual 에서 사용하고 있는 버전의 매뉴얼을 참조하십시오.


방법


서비스 중단하에서의 작업


데이터베이스에 접근하는 서비스를 일정시간 동안 모두 중단할 수 있는 환경에서는 상대적으로 간단한 작업단절차를 통해서 완료할 수
있습니다.






|순서|A노드|B노드|
|---|---|---|
|STEP<br>1|서비스 중지( 트랜잭션이 발생하지 않도록 조치)<br>확실하게 서비스를 막기 위해서 DB 를 stop 한 후 서비스 포트를 변경하여 구동 후 수행하기도 합니다.<br>데이터 베이스에 접속한 세션 확인 또는 수행중인 문장 확인<br>iSQL> select count(*) from v$session;<br>iSQL> select count(*) from v$statement where execute_flag =1 ;|서비스 중지( 트랜잭션이 발생하지 않도록 조치)<br>확실하게 서비스를 막기 위해서 DB 를 stop 한 후 서비스 포트를 변경하여 구동 후 수행하기도 합니다.<br>데이터 베이스에 접속한 세션 확인 또는 수행중인 문장 확인<br>iSQL> select count(*) from v$session;<br>iSQL> select count(*) from v$statement where execute_flag =1 ;|


|STEP<br>2|대상 노드의 이중화 갭이 모두 "0" 임을 확인 ( 이중화 Sender 가 구동된 DB를 의미)<br>DDL 수행 대상 테이블이 속해 있는 이중화 객체 확인<br>iSQL> select REPLICATION_NAME,LOCAL_USER_NAME, LOCAL_TABLE_NAME from<br>SYSTEM_.SYS_REPL_ITEMS_;<br>이중화 갭 확인<br>iSQL> SELECT rep_name, rep_gap FROM v$repgap; # rep_gap 이 모두 0 임을 확인.|
|---|---|
|STEP<br>3|대상노드의 이중화를 중지<br>iSQL>  ALTER REPLICATION<br> STOP;   # 이중화 객체(REP_NAME) 은 STEP 2에서 확인<br>rep_name|
|STEP<br>4|이중화 객체에서 DDL을 수행하려는 대상 테이블을 제거<br>iSQL> ALTER REPLICATION<br> DROP TABLE FROM<br> TO<br>; <br>rep_name<br>user_name.table_name<br>user_name.table_name|
|STEP<br>5|DDL 작업 수행<br> iSQL> ALTER TABLE t1 ADD COLUMN ( c1 INTEGER);|
|STEP<br>6|STEP 4에서 제거한 이중화 대상 테이블을 다시 이중화 객체 리스트에 추가<br>iSQL> ALTER REPLICATION<br> ADD TABLE FROM<br> TO<br>; <br>rep_name<br>user_name.table_name<br>user_name.table_name|
|STEP<br>7|대상노드에서 이중화 시작<br> iSQL> ALTER REPLICATION<br> START<br>rep_name|
|STEP<br>8|서비스 개시<br>STEP 1에서 DB의 서비스 포트 번호를 변경했다면 서비스 포트를 다시 원복하고 데이터 베이스를 재구동합니다.<br>Application 을 구동하여 DB 서비스를 재개한 후 DB의 상태를 확인합니다.|



서비스 무중단 제약하에서의 작업


서비스 무중단이 필요한 환경에서는 한 노드는 데이터베이스를 운영하는 상태에서 한 노드씩 교대로 작업을 해야만 하는 제약사항이 있을 수
있습니다.


이런 조건하에서는 앞서 설명한 서비스 중단이 가능한 환경에 비해서 상대적으로 여러 단계의 작업절차가 필요하며 주의가 필요할 수 있습니다.


자세한 내용은 http://support.altibase.com/kr/manual 에서 사용하고 있는 버전의 매뉴얼을 참조하십시오.
ALTIBASE 기술지원본부로부터 기술지원을 받으십시요 ( 서비스포털: http://support.altibase.com, TEL 02-2082-1114 )

#### 03-04. 이중화 give-up에 대해


개요
적용버전
이중화와 로그파일
이중화 GIVE-UP 이란
이중화 GIVE-UP 발생 시 미치는 영향
이중화 GIVE-UP 방지 방법
이중화 GIVE-UP 발생 시 이중화 진행여부 설정(자동)
이중화 GIVE-UP 확인 주기
이중화 GIVE-UP 발생 여부의 확인


개요


이중화 사용 시 발생할 수 있는 GIVE-UP 현상과 이중화 GIVE-UP 이 미치는 영향에 대해 설명합니다.


적용버전


ALTIBASE HDB 6.1.1 이상 버전에 적용되는 내용입니다.


추가사항 또는 업데이트가 필요한 경우 http://support.altibase.com/kr/ 또는 이 페이지에 댓글로 요청 글 남겨주세요.


이중화와 로그파일


Altibase 이중화는 Redo 로그를 기반으로 한 Data 동기화 기능입니다.
즉, Active Server 에서 생성된 Redo 로그들을 Standby Server 로 전송함으로써 양 서버간의 Data 일치를 보장하는 방법입니다.


Altibase 에서 Redo 로그 파일은 정해진 파일 수를 유지하며 Circular하게 재활용하는 방식이 아닌, Transaction 을 처리하면서 발생되는 로그를
개수 제한 없이 생성하고 반영 완료 후 로그 파일이 삭제되어 정리되는 방식입니다.


로그 파일이 정리되는 시점은 Checkpoint 가 수행되는 시점이며, 다음과 같은 특정 조건에 해당하는 로그 파일들은 삭제될 수 없습니다.


(1) 현재 진행 중인 트랜잭션이 참조하고 있는 로그파일
(2) (1)은 완료되었지만 이중화 전송이 완료되지 않아 이중화에서 참조해야 하는 로그파일 (이중화 GAP 으로 남아 있는 로그파일)
(3) CLR(Compensation Log Record의 약자이며 트랜잭션 롤백시 생성되는 로그 레코드의 타입) 로그가 참조하고 있는 로그 화일


위 세 조건에 해당되어 Redo 로그 파일이 정리되지 않고 지속적으로 쌓여간다면 Active Server Disk Full 장애 상황이 발생할 수 있습니다.


이중화 GIVE-UP 이란


이중화 문제로 Redo 로그 파일이 정리되지 않는 경우 Disk Full 장애를 방지하기 위해 이중화에서 최대 유지할 수 있는 Redo 로그 파일 개수를
설정할 수 있습니다.


정리되지 않은 Redo 로그 파일의 개수가 설정한 값을 초과하게 되면, Standby Sever 에서 Data 가 동기화가 되지 않았더라도 이중화 Gap 을
포기하고 Redo 로그를 삭제하여 Active Server 의 Disk Full 장애를 방지하게 됩니다.


이처럼 이중화 동기화가 완료되지 않았지만 Active Server 의 Disk full 장애 방지를 위하여 이중화에 필요한 Redo 로그 파일을 삭제하는 현상을
이중화 GIVE-UP 이라 합니다.


이중화 GIVE-UP 발생 시 미치는 영향


이중화 GIVE-UP 이 발생하면 Active Server 와 Standby Server 간의 Data 가 불일치한 상황이 되며, 심각한 문제를 초래할 수도
있습니다.


이중화 GIVE-UP 방지 방법


이중화 GIVE-UP 을 방지하려면 이중화 성능에 영향을 줄 수 있는 네트워크 성능이 안정적으로 유지되어야 합니다.
그리고, 비정상적인(정전, 네트워크 단절 등) 상태에서도 최악의 상황을 고려하여 관련 프로퍼티 값을 상황에 맞게 수정해 주어야
합니다.


REPLICATION_MAX_LOGFILE = 400


해당 프로퍼티 단위는 Redo 로그 파일 개수이며 400으로 설정한 경우, 정리되지 않아 Redo 로그 파일 개수가 400개 이상 생성되었다면
이중화 GIVE-UP 이 동작하게 됩니다.
이 프로퍼티는 $ALTIBASE_HOME/conf/altibase.properties 에서 수정 가능하며 자세한 내용은 General Reference 메뉴얼의 REPLIC

ATION_MAX_LOGFILE 부분 참조하시기 바랍니다.


이중화 GIVE-UP 발생 시 이중화 진행여부 설정(자동)


REPLICATION_MAX_LOGFILE 프로퍼티로 설정된 값을 초과하여 이중화 GIVE-UP 동작 이후, 다시 시작되는 방식을 설정할 수 있습니다.


REPLICATION_SENDER_START_AFTER_GIVING_UP = 1 (default)


0으로 설정된 경우

SYS_REPLICATIONS_ 메타 테이블의 IS_STARTED 컬럼 값이 0으로 바뀐다.
이중화 "재시작 SN" 값(즉 SYS_REPLICATIONS_ 메타 테이블의 XSN 컬럼 값)은 -1로 초기화되며, 이중화는 중지된다. (이
경우 이중화가 중단 된 상태를 유지하더라도 이로 인한 logfile 증가 현상은 발생하지 않는다)
1으로 설정된 경우

이중화 "재시작 SN" 값은 현재 로그 파일의 마지막 (가장 큰) SN으로 변경되고, 이중화는 이 "재시작 SN" 부터 다시 동기화
된다. (현 시점부터 동기화 진행)


이중화 GIVE-UP 확인 주기


이중화 GIVE-UP 동작 여부 결정은 Redo 로그 파일을 정리하는 Checkpoint 수행 중에 판단하게 됩니다.


이중화 GIVE-UP 발생 여부의 확인


give-up이 발생하면 이중화 메타테이블에 give-up 시간이 기록됩니다.


이중화 GIVE-UP 이 발생하면 SYSTEM_.SYS_REPLICATIONS_ 테이블에 GIVE-UP 관련 내용을 기록합니다.


iSQL> set vertical on;

iSQL> select replication_name, is_started, give_up_time from SYSTEM_.SYS_REPLICATIONS_;

REPLICATION_NAME     : REP1

IS_STARTED        : 1

GIVE_UP_TIME       :

1 row selected.

|컬럼명|내용|
|---|---|
|REPLICATION_NAME|이중화 이름|
|IS_STARTED|이중화 시작 여부 (start : 1, stop : 0)|
|GIVE_UP_TIME|가장 최근에 이중화를 포기한 일시|


#### 03-05. 이중화 객체 IP 변경 방법


개요
절차

1.변경 대상 이중화 객체 중지
2. 신규 IP 추가
3. 기존 IP 제거
4. 이중화 객체 구동
5. 이중화 객체의 호스트 정보 확인


개요


이중화 객체 생성 시 등록한 IP를 다른 IP 로 변경하기 위한 절차 안내입니다.


절차


1.변경 대상 이중화 객체 중지


ALTER REPLICATION replication_name STOP;


2. 신규 IP 추가


ALTER REPLICATION replication_name ADD HOST 'new_ip_address', replication_port;


3. 기존 IP 제거


ALTER REPLICATION replication_name DROP HOST 'old_ip_address', replication_port;


4. 이중화 객체 구동


ALTER REPLICATION replication_name START;


5. 이중화 객체의 호스트 정보 확인


SELECT REPLICATION_NAME, HOST_IP, PORT_NO FROM SYSTEM_.SYS_REPL_HOSTS_ ORDER BY HOST_NO

#### 03-06. 이중화 객체 생성 및 삭제 방법


개요
버전


버전

준비할 것
이중화 기능 활성화
이중화 객체 생성
이중화 시작
이중화 객체 삭제
에러 메시지
참고문서


개요


이중화를 처음 사용하는 사용자를 대상으로 이중화 객체를 생성하고 삭제하는 방법에 관해 설명합니다.


이중화 설계 또는 구성을 위한 사전 작업을 마친 것으로 가정하고 설명합니다.
이중화 대상 서버 간 데이터가 일치하는 것을 가정합니다. 데이터가 모두 동일하게 존재하거나 양쪽 모두 0 건이거나.


이중화 설계 및 구성에 관한 가이드는 아래의 기술 문서를 참고합니다.


D24_ALTIBASE_효율적인_이중화_가이드.pdf
D67_ALTIBASE_이중화_제약사항_가이드.pdf


버전


Altibase 4.3.9 이상


준비할 것


이중화 전용 IP
이중화에 사용할 IP는 서비스망과 분리된 전용 라인을 사용할 것을 권장합니다.


이중화 서비스 포트
이중화 용 서비스 포트 번호를 정합니다. 사용자가 임의로 정할 수 있으며 일반적으로 30300을 사용합니다.


이중화 대상 테이블 선정
복제할 이중화 대상 테이블은 Primay Key가 존재해야 합니다.


이중화 기능 활성화


Altibase 서버의 이중화 기능은 기본적으로 비활성화 상태이므로,


-- REPLICATION_PORT_NO 프로퍼티의 기본값은 0 으로 이중화 기능이 비활성화 상태를 의미.


iSQL> SELECT NAME, VALUE1 FROM V$PROPERTY WHERE NAME = 'REPLICATION_PORT_NO';

NAME              VALUE1

------------------------------------------------------------------
REPLICATION_PORT_NO       0

1 row selected.


이중화 기능을 사용하려면 관련 프로퍼티를 변경하여 활성화해야합니다.
이중화 기능을 활성화하는 작업은 Altibase 서버 재기동이 필요합니다.


REPLICATION_PORT_NO 프로퍼티 변경


Altibase 서버 프로퍼티 REPLICATION_PORT_NO의 값을 변경하는 것으로 이중화 기능을 활성화합니다.
REPLICATION_PORT_NO 프로퍼티는 이중화 쓰레드 간 사용할 포트 번호를 의미하기도 합니다.
포트 번호는 서버에서 사용하지 않는 번호로 사용자가 임의로 지정하며 일반적으로 30300을 사용하기도 합니다.



1.


2.


3.


4.



이중화 대상 서버에서 사용자가 지정한 이중화 포트가 사용 중인지 확인합니다.


LISTEN 상태가 보이면 해당 포트는 다른 프로세스에서 사용한다는 것으로 이중화 포트로 사용할 수 없습니다.


# 이중화 포트, REPLICATION_PORT_NO를 30300으로 지정하였을 때 수행 예


$ netstat -an | grep 30300 | grep LISTEN


altibase.properties 파일을 열어서 REPLICATION_PORT_NO 값을 변경하고 저장합니다. 이 작업은 이중화 대상 서버에서 각각
수행해야합니다.



Altibase 서버 프로세스를 재구동합니다.


$ server restart


이중화 객체 생성 과정 동안 어플리케이션을 막고자 할 경우


이중화 객체 생성 과정 동안 어플리케이션의 접근을 막고자 할 경우 Altibase 서버 서비스 포트 변경 후 재구동합니다.


$ export ALTIBASE_PORT_NO=20400
$ server restart


Altibase 서버 구동 후 이중화 포트 LISTEN 상태와 프로퍼티 설정값을 확인합니다.




이중화 객체 생성


이중화 객체는 CREATE REPLICATION 구문으로 생성하며 이중화 모드, 이중화 서버 정보와 이중화 대상 테이블 등 이중화 관련 정보를
정의합니다.
이중화 대상 서버는 2대가 쌍을 이룹니다.
이중화 객체는 쌍을 이루는 이중화 대상 서버에 동일한 객체 이름으로 각각 생성해야 합니다.





이중화 객체 생성 구문의 추가 옵션은 Replication Manual -> 3. 이중화 사용 -> 이중화 생성 (CREATE REPLICATION) 부분을
참고하세요.
매뉴얼 다운로드 페이지 : http://support.altibase.com/kr/manual


이중화 객체 생성 절차 - 예제 1 (이중화 대상 서버가 2대인 경우)


이중화 객체 생성 조건이 다음과 같을 때 이중화 객체를 생성하는 예입니다.


이중화 대상 서버는 A, B서버 2대이다.
이중화 객체 이름은 REP1으로 생성한다.
이중화 대상 서버 A의 IP 주소는 192.168.1.112, 이중화 포트 번호는 25524 이고
이중화 대상 서버 B의 IP 주소는 192.168.1.113, 이중화 포트 번호는 35524 이다.
이중화 대상 테이블은 SYS유저의 employees 테이블과 departments 테이블이다.


1.


2.


3.



A 서버 : IP 192.168.1.112, 이중화 포트 25524



이중화 객체 생성 확인





B 서버 : IP 192.168.1.113, 이중화 포트 35524








이중화 객체 생성 절차 - 예제 2 (이중화 대상 서버가 3대인 경우)


이중화 객체 생성 조건이 다음과 같을 때 이중화 객체를 생성하는 예입니다.


이중화 대상 서버는 A, B, C 3대이고
A는 B, C와
B는 A, C와
C는 A, B와 서로서로 동기화한다.


이중화 객체 이름은 다음과 같이 정한다.

   - A와 B서버의 경우 REP_A_B

   - B와 C서버의 경우 REP_B_C

   - A와 C서버의 경우 REP_C_A


각 서버의 IP 주소와 이중화 포트 번호는 아래와 같다.

    - 서버 A : 192.168.1.112, 30300

    - 서버 B : 192.168.1.113, 30300

    - 서버 C : 192.168.1.114, 30300


이중화 대상 테이블은 SYS유저의 employees 테이블과 departments 테이블이다.



1.


2.



A 서버 : IP 192.168.1.112, 이중화 포트 30300



B 서버 : IP 192.168.1.113, 이중화 포트 30300




3.


4.



C 서버 : IP 192.168.1.114, 이중화 포트 30300



이중화 객체 생성 확인








이중화 시작


이중화 시작은 데이터 동기화를 시작하는 것을 의미합니다.
이중화 시작을 수행한 서버는 이중화 송신 쓰레드(Sender)가 구동되며 해당 서버와 쌍을 이루는 원격 서버는 수신 쓰레드(Receiver)가
구동됩니다.


1.


2.


3.



이중화 시작 서버(Active 서버) 선정


이중화 시작을 수행할 서버, 이중화 송신 쓰레드(Sender)를 구동할 서버는 변경 트랜잭션이 발생하는 서버를 말하며 Active 서버라
부르기도 합니다.
쌍을 이루는 이중화 대상 서버 중 데이터 변경이 발생하는 곳이 Active 서버이고 다른 쪽 서버는 Standby 서버가 됩니다.
양 서버 모두 변경 트랜잭션이 발생하여 양 방향 동기화 할 경우 두 서버 모두 Active 서버가 됩니다.


이중화 시작


Active 서버에서 ALTER REPLICATION 구문으로 이중화를 시작합니다. replication_name 은 이중화 객체 생성 단계에서 생성한 객체
이름입니다.


-- 이 명령을 수행한 서버에는 이중화 송신 쓰레드(Sender)가 구동되며 해당 서버와 쌍을 이루는 원격
서버는 수신 쓰레드(Receiver)가 구동된다.

iSQL> ALTER REPLICATION replication_name START;


이중화 시작 상태 확인


이중화 송신 쓰레드(Sender)와 수신 쓰레드(Receiver) 구동 여부를 확인하는 문장입니다.









이중화 객체 삭제


이중화 객체를 삭제하는 방법입니다.


-- 먼저 이중화를 중지합니다.

iSQL> ALTER REPLICATION replication_name STOP;


-- 이중화 객체를 삭제합니다.

iSQL> DROP REPLICATION replication_name ;


에러 메시지


이중화 객체 생성 과정 중 발생할 수 있는 에러 메시지 몇 가지를 소개합니다.


[ERR-61023 : Replication is disabled]


CREATE REPLICATION 구문 수행 시 만날 수 있는 에러 메세지로, 이중화 기능이 비활성화되어 있는 경우 발생합니다.
REPLICATION_PORT_NO 프로퍼티의 값을 확인하세요. 이중화 기능 활성화 부분을 참고합니다.


[ERR-61113 : A replicated table must have a primary key. (user_name table_name. )]


CREATE REPLICATION 구문 수행 시 발생할 수 있는 에러 메시지입니다.
FROM절에서 지정한 이중화 대상 테이블에 primary key가 없는 경우 발생합니다.
에러 메시지 마지막 부분 () 안의 테이블에 primary key를 생성하고 이중화 객체 생성 문장을 수행해야합니다.


[ERR-6100D : [Sender] Failed to handshake with the peer server (Handshake Process Error)]


ALTER REPLICATION replication_name START 실행 시 발생할 수 있는 에러 메시지이다.
WITH 절에 입력한 원격 서버의 IP와 이중화 포트 번호가 올바른지, 해당 IP와 포트로 접근이 가능한지 확인합니다.


참고문서


Replication Manual
SQL Reference
매뉴얼 다운로드 페이지
http://support.altibase.com/kr/manual


#### 03-07. 이중화 대상 테이블 추가/삭제 방법

개요
버전
이중화 대상 테이블 추가
이중화 대상 테이블 삭제
참고 문서


개요


이중화 객체에 이중화 대상 테이블을 추가하거나 삭제하는 방법에 관한 설명합니다.


버전


Altibase 4.3.9 이상


이중화 대상 테이블 추가


이중화 객체에 이중화 대상 테이블 추가하기 위한 작업 절차입니다.



1.


2.



이중화 중지


이중화 송신 쓰레드가 구동된 서버에서 수행합니다.
아래 문장으로 지역 서버의 이중화 송신 쓰레드(Sender)와 원격 서버의 수신 쓰레드(Receiver)를 중지합니다.


iSQL> ALTER REPLICATION replication_name STOP;


-- 이중화 구동 상태 확인
iSQL> SELECT REPLICATION_NAME, DECODE(IS_STARTED, 0, 'STOPPED', 1, 'STARTED') IS_STARTED

FROM SYSTEM_.SYS_REPLICATIONS_;


이중화 대상 테이블 추가


이중화 객체에 이중화 대상 테이블을 추가하는 구문입니다.이중화 대상 서버에서 각각 수행합니다.


iSQL> ALTER REPLICATION replication_name ADD TABLE FROM user_name.table_name TO

user_name.table_name;


이중화 객체에 추가되었는지 확인합니다.


3.


4.



iSQL> SELECT REPLICATION_NAME, LOCAL_USER_NAME, LOCAL_TABLE_NAME FROM

SYSTEM_.SYS_REPL_ITEMS_;


이중화 SYNC


양 서버에 데이터가 서로 일치하지 않을 경우, 한 쪽 서버 테이블을 TRUNCATE 한 후 데이터가 존재하는 서버에서 SYNC 구문을
수행하여 데이터를 일치시킵니다.
양 서버에 데이터가 일치하는 경우 4. 이중화 시작을 수행합니다.


iSQL> ALTER REPLICATION replication_name SYNC ONLY TABLE user_name.table_name;


이중화 시작


양 서버에 데이터가 서로 일치한다면, 이중화 시작 구문을 수행합니다.


iSQL> ALTER REPLICATION replication_name START;


-- 이중화 구동 상태 확인
iSQL> SELECT REPLICATION_NAME, DECODE(IS_STARTED, 0, 'STOPPED', 1, 'STARTED') IS_STARTED

FROM SYSTEM_.SYS_REPLICATIONS_;



이중화 대상 테이블 삭제


이중화 객체에 이중화 대상 테이블 삭제하기 위한 작업 절차입니다.



1.


2.



이중화 중지


이중화 송신 쓰레드가 구동된 서버에서 수행합니다.
아래 문장으로 지역 서버의 이중화 송신 쓰레드(Sender)와 원격 서버의 수신 쓰레드(Receiver)를 중지합니다.


iSQL> ALTER REPLICATION replication_name STOP;


-- 이중화 구동 상태 확인
iSQL> SELECT REPLICATION_NAME, DECODE(IS_STARTED, 0, 'STOPPED', 1, 'STARTED') IS_STARTED

FROM SYSTEM_.SYS_REPLICATIONS_;


이중화 대상 테이블 삭제


이중화 객체에 이중화 대상 테이블을 삭제하는 구문입니다.이중화 대상 서버에서 각각 수행합니다.


3.



iSQL> ALTER REPLICATION replication_name DROP TABLE FROM user_name.table_name TO

user_name.table_name;


-- 이중화 객체의 이중화 대상 테이블 확인 문장

iSQL> SELECT REPLICATION_NAME, LOCAL_USER_NAME, LOCAL_TABLE_NAME FROM

SYSTEM_.SYS_REPL_ITEMS_;


이중화 시작


iSQL> ALTER REPLICATION replication_name START;


-- 이중화 구동 상태 확인
iSQL> SELECT REPLICATION_NAME, DECODE(IS_STARTED, 0, 'STOPPED', 1, 'STARTED') IS_STARTED

FROM SYSTEM_.SYS_REPLICATIONS_;



참고 문서


ALTER REPLICATION 문장의 구문 설명 및 추가적인 옵션은 SQL Reference 매뉴얼 -> 3. 데이터 정의어 -> ALTER REPLICATION
부분을 참고하시기 바랍니다.
매뉴얼 다운로드 페이지
http://support.altibase.com/kr/manual

#### 03-08. 이중화 모니터링 쿼리


이중화 전체 현황
이중화 sender 정보
이중화 receiver 정보
이중화 gap


이중화 전체 현황


set linesize 1024

set colsize 20

SELECT a.replication_name rep_name
, d.host_ip || decode(d.host_ip, b.peer_ip, ' (*)', NULL) peer_ip
, nvl(to_char(e.rep_gap), '-') as rep_gap

, a.xsn restart_xsn
, decode(b.peer_port, NULL, 'OFF', 'ON') as sender
, decode(c.peer_port, NULL, 'OFF', 'ON') as receiver
FROM system_.sys_repl_hosts_ d
, system_.sys_replications_ a
left outer join v$repsender b on a.replication_name = b.rep_name
left outer join v$repreceiver c on a.replication_name = c.rep_name
left outer join
(select rep_name, max(rep_gap) rep_gap from v$repgap group by rep_name) e
on a.replication_name = e.rep_name
WHERE a.replication_name = d.replication_name
ORDER BY rep_name;

REP_NAME       PEER_IP        REP_GAP        RESTART_XSN     SENDER RECEIVER

----------------------------------------------------------------------------------
----------------------------
REP

192.168.1.149 (*)   0           9668         ON  ON


주요 컬럼 설명

|컬럼 이름|설명|
|---|---|
|restart_xsn|이중화 대상인 원격서버가 반영한 SN, 이중화 재 시작 시 재전송 기점을 의미|
|sender|sender의 작동 유무|
|receiver|receiver의 작동 유무|



이중화의 이름, ip, SENDER, RECEIVER의 상태를 확인할 수 있습니다.


이중화 sender 정보


set linesize 1024

set colsize 20

SELECT trim(REP_NAME) as REP_NAME
, decode(START_FLAG, 0, 'Normal',
1, 'Quick',
2, 'Sync',
3, 'Sync Only') as START_FLAG
, decode(net_error_flag, 0, 'OK', 'Error') as NET_ERROR_FLAG
, decode(STATUS, 0, 'Stop', 1, 'Run', 2, 'Retry') as STATUS
, peer_ip

, peer_port
, XSN
FROM V$REPSENDER;

REP_NAME       START_FLAG NET_ERROR_FLAG STATUS PEER_IP        PEER_PORT  XSN


----------------------------------------------------------------------------------
-------------------------------------
REP          Normal   OK       Run   192.168.1.149     30300    9675


주요 컬럼 설명

|컬럼 이름|설명|
|---|---|
|rep_name|이중화 객체의 이름|
|peer_ip|이중화 대상인 원격서버의 ip 주소|
|peer_port|이중화 대상인 원격서버의 포트번호|
|Status|sender의 현재 상태로 1 이어야 정상이다. / STOP(0), RUN(1), RETRY(2)|
|repl_mode|sender의 현재 이중화 모드 / lazy, eager|
|NET_ERROR_FLAG|network 에러 여부로 0이어야 정상이다. / OK(0), ERROR(1)|
|XSN|sender가 마지막으로 송신한 SN(Serial Number/리두로그일련번호)으로 v$repgap의 REP_SN과 동일|



이중화 SENDER의 원격서버의 IP, PORT, network 에러 여부, 상태 등을 확인할 수 있습니다.


이중화 receiver 정보


set linesize 1024

set colsize 20

SELECT trim(REP_NAME)
, trim(MY_IP)
, trim(PEER_IP)

, MY_PORT

, PEER_PORT

, apply_xsn
FROM X$REPRECEIVER;
TRIM(REP_NAME)    TRIM(MY_IP)      TRIM(PEER_IP)     MY_PORT   PEER_PORT  APPLY_XSN


----------------------------------------------------------------------------------
----------------------------------
REP          192.168.1.145     192.168.1.149     30300    26722    13461585


주요 컬럼 설명

|컬럼 이름|설명|
|---|---|
|peer_ip|이중화 주체인 원격서버의 ip 주소|
|peer_port|이중화 주체인 원격서버의 포트번호|
|apply_xsn|receiver가 현재 반영중인 원격서버의 SN|



이중화 RECEIVER의 원격서버의 IP, PORT 등을 확인할 수 있습니다.


이중화 gap


[Altibase 7 미만 버전]


"REP_GAP" 컬럼은 REP_LAST_SN 과 REP_SN 간의 로그 일련번호의 간격을 나타냅니다.


즉 지역서버 트랜잭션에 의해 가장 최근에 로깅된 로그 레코드와 이중화 송신 쓰레드가 현재 송신중인 로그 레코드의 간격을 의미합니다.


set linesize 1024

set colsize 20

select rep_name

, rep_gap
from v$repgap;

REP_NAME       REP_GAP

---------------------------------------------
REP          0


주요 컬럼 설명

|컬럼 이름|설명|
|---|---|
|rep_name|이중화 이름|
|rep_gap|rep_last_sn과 rep_sn의 간격으로 비동기화 정도를 나타낸다. (즉, rep_last_sn - rep_sn)|



[Altibase 7 이상 버전]


Altibase 7부터는 v$repgap 뷰에 ''REP_GAP_SIZE'' 컬럼이 추가되어 이중화 GAP의 크기를 *바이트(Byte) 단위*로 확인할 수 있습니다.


"REP_GAP" 컬럼의 의미가 기존과 달리 지역서버 트랜잭션에 의해 가장 최근에 로깅된 로그 위치부터 이중화 송신 쓰레드가 현재 송신중인 로그
위치까지의 크기입니다.


기본값은 MB 단위이며 REP_GAP_SIZE에서 REPLICATION_GAP_UNIT 프로퍼티를 나눈 값입니다.


set linesize 1024

set colsize 20

select rep_name

, rep_gap
, rep_gap_size
from v$repgap;

REP_NAME    REP_GAP       REP_GAP_SIZE

-------------------------------------------------------------------
REP       0          0


주요 컬럼 설명


|컬럼 이름|설명|
|---|---|
|rep_name|이중화 이름|
|rep_gap|이중화 갭의 로그파일 사이즈를 프로퍼티REPLICATION_GAP_UNIT에 설정된 단위로 보여준다.<br>(단위: REPLICATION_GAP_UNIT, 기본값 1MB)<br>* REP_GAP = CEIL(REP_GAP_SIZE / REPLICATION_GAP_UNIT)|
|rep_gap_size|이중화 갭의 로그파일 사이즈를 의미하며, 바이트 단위로 보여준다.|



- 이중화 gap이 많이 늘어났을 경우 확인 해야할 사항이 있습니다.



1.

2.

3.



Network 상태 확인(작업, 장애, 방화벽에 의해 IP 또는 PORT가 막혀 있을 경우 등)
원격 장비 상태 확인(하드웨어 장애, 원격DB의 shutdown 등)
BULK성 DML 작업 여부 확인



위의 경우 이중화 gap이 증가할 수 있으므로 확인이 필요 합니다.

### 04. 백업 및 복구

#### 04-01. aexport 및 iloader 이용


aexport 와 iloader 유틸리티를 이용하여 데이터베이스 객체와 데이터를 사용자가 확인 가능한 텍스트 파일 형태로 다운로드하는 방법과
다운로드 파일로 업로드하는 방법을 소개하고 있습니다.


이 페이지에서는 가장 기본적이고 단순한 형태를 소개하고 있습니다. aexport 와 iloader 는 다양한 옵션을 사용하여 여러 형태로 응용할 수
있으니 필요한 내용은 다음 메뉴얼을 참고하시기 바랍니다.


iLoader User's Manual

Utilities Manual
메뉴얼 다운로드 페이지 : http://support.altibase.com/kr/manual


04-01-01. aexport, iloader 란?


aexport 는...


aexport 는 데이터베이스의 객체 생성 스크립트와 데이터를 텍스트 파일로 다운로드할 수 있는 스크립트를 생성해주는 유틸리티입니다.


aexport 가 추출할 수 있는 데이터베이스 객체는 아래와 같습니다.


데이터베이스 사용자
사용자 권한
테이블스페이스
테이블
테이블 제약 조건
인덱스

뷰
Materialized View (ALTIBASE HDB 6.3.1 부터 제공)
저장 프로시저
이중화 객체


aexport 는 데이터베이스 객체 변경이 있을 때마다 수행할 것을 권장합니다.


iloader 는...


iloader 는 데이터베이스의 데이터를 테이블 단위로 다운로드하거나 업로드 할 수 있는 유틸리티입니다. 데이터는 사용자가 확인 가능한 텍스트
파일 형태로 저장됩니다.


이것은 데이터베이스 마이그레이션이나 테이블 단위 백업의 용도로 사용할 수 있습니다.


iloader를 이용하여 테이블의 데이터를 백업하기 위해서는 form 파일과 여러 옵션을 필요로 하는데 aexport 를 수행하면 iloader 수행 명령을
스크립트로 생성해줍니다.


04-01-02. aexport 를 이용한 데이터베이스 객체 백업


aexport 수행 전 필수 작업


aexport.properties 파일에서 아래 설정들의 값을 변경합니다.


ILOADER_FILED_TERM
ILOADER_ROW_TERM


ILOADER_FIELD_TERM 는 필드 구분자, ILOADER_ROW_TERM 는 레코드 구분자를 의미합니다.


aexport.properties 파일을 한번도 변경한 적이 없다면 이 설정들은 주석이 되어 있고 기본값은 아래와 같이 설정되어 있습니다.





위와 같이 기본값으로 설정되어 있다면 아래와 같이 다소 복잡하게 변경합니다.





aexport.properties 파일의 위치는 $ALTIBASE_HOME/conf 입니다. 이 파일이 존재하지 않을 경우 aexport.properties.sample 파일을 복사하여
사용합니다.


$ cd $ALTIBASE_HOME/conf
$ ls -l aexport.properties*
-rw-r--r-- 1 user1 user1 1636 Mar 9 2022 aexport.properties.sample


$ cp -p aexport.properties.sample aexport.properties


aexport 를 수행하면 다음과 같은 스크립트 들이 생성됩니다.


데이터베이스 객체 생성 스크립트
iloader 를 이용한 데이터 다운로드/업로드 스크립트


iloader 를 이용한 데이터 다운로드/업로드 스크립트에는 iloader 명령어들이 포함되어 있습니다. iloader 는 여러 옵션들을 사용할 수 있는데 위
설정에 따라 옵션에 사용된 값이 달라집니다.
위 설정은 각각 필드 구분자와 로우 구분자를 의미하는데 기본 값이 단순하게 설정되어 있습니다. 만약 이 설정값이 문자형 데이터 타입 컬럼에
포함된 경우 데이터 업로드 시 데이터가 정상적으로 업로드 되지 않는 문제가 발생할 수 있습니다.
그러니 이 설정 값은 다소 복잡하게 설정하는 것이 좋습니다.


aexport 수행


aexport.properties 를 변경한 후 aexport 를 수행합니다.


aexport 수행 예


$ aexport


$ p


----------------------------------------------------------------
Altibase Export Script Utility.

Release Version 6.3.1.2.7

Copyright 2000, ALTIBASE Corporation or its subsidiaries.
All Rights Reserved.

----------------------------------------------------------------
Write Server Name (default:localhost) :     # 로컬에서 수행하는 경우는 엔터, 원격에 설치된 알티베이스

서버에 접속하는 경우는 IP 입력.

Write UserID :                  # 데이터베이스 내 전체 객체를 백업할 경우는 sys 입력, 특정 유저의
객체만 백업할 경우는 해당 USER 입력

Write Password :                 # USER 의 패스워드 입력


##### TBS #####


##### USER #####
** input user ALTITEST's password(default - same with USER_NAME):      # UserID 에 sys 를 입력한 경우
데이터베이스 내 생성된 모든 USER 의 패스워드를 입력해야 합니다.
** input user USER1's password(default - same with USER_NAME): USER1     # 패스워드를 임의로 입력해도
백업 스크립트는 생성되지만 실제 iloader 백업시 패스워드가 일치하지 않으면 iloader는 실패 합니다. 또한 여기서

입력한 패스워드로 create user ~ identified by ~ 구문을 생성한다는 것을 알고 있어야 합니다.
** input user USER2's password(default - same with USER_NAME): USER2


##### SYNONYM #####


##### DIRECTORY #####


##### TABLE #####

** "ALTITEST"."ORDERS"


** "SYS"."CUSTOMERS"


** "SYS"."DATE_T"


** "SYS"."DEMO_EX1"


** "SYS"."DEPARTMENTS"


** "SYS"."DISK_T"


** "SYS"."DISK_T2"


** "SYS"."EMPLOYEES"


** "SYS"."GOODS"


** "SYS"."MEM_T"


** "SYS"."ORDERS"


** "SYS"."PLAN_TEST"


** "SYS"."T"


** "SYS"."TEST_EMP_TBL"


** "SYS"."T_BINARY"


** "SYS"."T_BLOB"


** "SYS"."T_BYTES"


** "SYS"."T_CLOB"


** "SYS"."T_NIBBLE"


** "SYS"."VOL_T"


** "USER1"."T"


##### QUEUE #####


##### SEQUENCE #####


##### DATABASE LINK #####


##### VIEW #####


##### MATERIALIZED VIEW #####


##### STORED PROCEDURE #####


##### STORED PACKAGE #####


##### TRIGGER #####


##### LIBRARY #####


##### REPLICATION #####


##### JOB #####

------------------------------------------------------
##### The following script files were generated. #####
1. run_il_out.sh      : [ iloader formout, data-out script ]
2. run_is.sh        : [ isql table-schema script ]
3. run_il_in.sh       : [ iloader data-in script ]
4. run_is_refresh_mview.sh : [ isql materialized view refresh script ]
5. run_is_index.sh     : [ isql table-index script ]
6. run_is_fk.sh       : [ isql table-foreign key script ]
7. run_is_repl.sh      : [ isql replication script ]
8. run_is_job.sh      : [ isql job script ]

------------------------------------------------------

aexport 를 수행하면 다음과 같이 .sh(Windows 시스템의 경우 .bat) 파일들과 .sql 파일들이 생성됩니다.


sql 파일들은 데이터베이스 객체 생성 구문을 담고 있고 .sh 파일들을 .sql 파일들을 한 번에 실행시키는 스크립트들입니다.


(※ Altibase 버전 별 지원 객체 범위에 따라서 .sh 파일 개수는 달라 질 수 있습니다.)


------------------------------------------------------
##### The following script files were generated. #####
1. run_il_out.sh      : [ iloader formout, data-out script ]
2. run_is.sh        : [ isql table-schema script ]
3. run_il_in.sh       : [ iloader data-in script ]
4. run_is_refresh_mview.sh : [ isql materialized view refresh script ]
5. run_is_index.sh     : [ isql table-index script ]
6. run_is_fk.sh       : [ isql table-foreign key script ]
7. run_is_repl.sh      : [ isql replication script ]
8. run_is_job.sh      : [ isql job script ]

------------------------------------------------------

04-01-03. iloader 를 이용한 데이터 다운로드


iloader 수행 전 필수 작업
백업 수행

데이터베이스 내 전체 테이블의 데이터 다운로드
특정 유저에 속한 테이블의 데이터 다운로드
특정 테이블의 데이터 다운로드
데이터 다운로드 결과 확인

run_il_out.sh 수행 로그 확인
테이블 별 로그 확인
데이터 다운로드 파일


iloader 수행 전 필수 작업


iloader 수행 전에 반드시 아래 환경 변수를 확인 후 진행하도록 합니다.


ALTIBASE_NLS_USE 는 한글 데이터가 깨지는 것을 방지 하기 위해서 필요하며 ILO_DATEFORM 은 date 형 컬럼이 unique 한 값을 갖는 경우
중복을 막기 위해서 설정해야 합니다.


ALTIBASE_NLS_USE
ILO_DATEFORM


iloader 를 수행하는 세션에서 아래와 같이 export 명령어로 설정하거나 사용자 환경 설정 파일(.bash_profile 또는 .profile)에 추가하고 로그
아웃, 로그인 해도 적용됩니다.


환경 변수 설정 방법





환경 변수 설정 방법


$ echo $ALTIBASE_NLS_USE
$ echo $ILO_DATEFORM


알티베이스 서버 캐릭터 셋은 아래 문장으로 확인할 수 있습니다.NLS_CHARACTERSET 가 알티베이스 서버의 캐릭터 셋이며 NLS_USE 는
클라이언트의 캐릭터 셋입니다. 이 둘이 동일하게 설정되어야 한글 데이터가 깨지지 않습니다.


백업 수행


테이블의 데이터 백업을 위해 run_il_out.sh를 이용합니다.


$ ls --l run_il_out.sh

rw-rw-rw 1 eheejung eheejung 633 Nov 1 11:00 run_il_out.sh


데이터베이스 내 전체 테이블의 데이터 다운로드


run_il_out.sh 은 aexport 수행 시 UserID 를 sys 로 입력한 후 생성된 파일이어야 합니다.
run_il_out.sh 을 수행합니다.





특정 유저에 속한 테이블의 데이터 다운로드


특정 유저 소유의 테이블만 백업하고 싶은 경우 해당 유저로 aexport 를 수행한 run_il_out.sh 을 이용합니다.


$ aexport

----------------------------------------------------------------
Altibase Export Script Utility.

Release Version 6.3.1.2.7

Copyright 2000, ALTIBASE Corporation or its subsidiaries.
All Rights Reserved.

----------------------------------------------------------------
Write Server Name (default:localhost) :

Write UserID : altitest

Write Password :

...중략...


$ cat run_il_out.sh

iloader -s localhost -u ALTITEST -p ALTITEST formout -f ALTITEST_ORDERS.fmt -T ORDERS


iloader -s localhost -u ALTITEST -p ALTITEST out -f ALTITEST_ORDERS.fmt -d ALTITEST_ORDERS.dat -log
ALTITEST_ORDERS.log


sys 로 aexport 를 수행했다면, run_il_out.sh 에서 해당 유저만 추출하여 수행할 수도 있습니다.





특정 테이블의 데이터 다운로드


특정 테이블만 다운로드하고자 할 경우 run_il_out.sh 에서 원하는 테이블만 추출하여 백업합니다.





iloader formout, iloader out 명령을 차례대로 수행합니다.


테이블이 많거나 데이터가 많은 경우 download.out 을 모니터링하여 종료 여부를 확인합니다.





데이터 다운로드 결과 확인


run_il_out.sh 수행 로그 확인


run_il_out.sh 수행 로그는 tee 명령에 지정된 파일입니다.


$ sh run_il_out.sh | tee download.out


지정한 파일에서 아래와 같이 에러 발생 여부를 확인합니다.


$ grep –i err- download.out

[ERR-311F4 : Invalid column name         # 이와 같이 ERR- 로 시작하는 것이 나오면 에러가 발생했다는

의미입니다.

# 상황에 따라 조치해야 하니 에러 확인 후 직접 조치가 어려운 경우 연락

주십시오.


테이블 별 로그 확인


run_il_out.sh 를 수행하면 DBUSER TABLENAME_ .log 형태의 로그 파일들이 생깁니다. (예, altitest 유저의 orders 테이블이라면
ALTITEST_ORDERS.log)
이 파일들에서 아래 명령으로 에러 여부를 확인합니다.


$ cat run_il_out.sh | grep fmt | wc -l                      # 데이터베이스 내 테이블 수 확인

106


$ ls -l *.fmt | wc -l                               # *.fmt 파일 수로 백업 대상 테이블 수를 확인.

106


$ cat *.log | grep 'Error Row Count' | awk -F: '{print $2}' | wc -l       # Error Row Count 발생 수가 .fmt
파일 갯수와 다르다면 차이 난 수만큼 특정 테이블에서 에러가 발생했다는 의미입니다.
106                                        # run_il_out.sh수행 로그(download.out)를 열어서

테이블 이름으로 검색해서 확인합니다.


$ cat *.log | grep 'Error Row Count' | awk -F: '{print $2}' | sort -u      # 결과가 0 뿐이라면
DBUSER_TABLENAME.log 내에서 download 실패한 것이 없음을 알 수 있음.
0                                         # 0 이 아닌 결과가 있다면 해당 테이블을 찾아 .log 과
.bad 파일로 원인을 찾아야 합니다.


데이터 다운로드 파일


run_il_out.sh 수행으로 생성된 백업 파일은 USERNAME TABLENAME_ .dat 형식으로 생성됩니다.


$ ls -l *.dat

-rw-rw-rw- 1 heejung.lee heejung.lee 12457 2014-11-19 15:03 ALTITEST_ORDERS.dat


$ ls -l *.dat | wc -l                               # 백업 파일 수를 테이블 수와 비교하여 다시 한

번 백업 결과를 점검해볼 수 있습니다.


$ ls -l ALTITEST_ORDERS*                             # 테이블 별로 .dat, .fmt, .log 파일이 생성
됨.

-rw-rw-rw- 1 heejung.lee heejung.lee  0 2014-11-19 15:03 ALTITEST_ORDERS.dat
-rw-rw-rw- 1 heejung.lee heejung.lee 210 2014-11-19 15:03 ALTITEST_ORDERS.fmt
-rw-rw-rw- 1 heejung.lee heejung.lee 169 2014-11-19 15:03 ALTITEST_ORDERS.log


04-01-04. 데이터베이스 객체 생성 및 데이터 업로드


데이터베이스 객체 및 데이터 업로드 절차
데이터 업로드 전 필수 작업
데이터베이스 객체 생성


데이터 업로드
데이터 업로드 결과 확인

.sh 수행 로그 확인
테이블 별 로그 파일 확인


데이터베이스 객체 및 데이터 업로드 절차


데이터베이스 객체 및 데이터를 모두 복원하고자 하는 경우 aexport 수행 시 생성된 아래 .sh 파일들을 차례로 수행합니다.


2. ~ 8. 중에서, 순서대로 수행하면 됩니다.


1. run_il_out.sh      : [faq: iloader formout, data-out script ]     # 데이터 백업을 위한 스크립트니니 이
단계에서는 제외합니다.
2. run_is.sh        : [faq: isql table-schema script ]
3. run_il_in.sh       : [faq: iloader data-in script ]
4. run_is_refresh_mview.sh : [faq: isql materialized view refresh script ]
5. run_is_index.sh     : [faq: isql table-index script ]
6. run_is_fk.sh       : [faq: isql table-foreign key script ]
7. run_is_repl.sh      : [faq: isql replication script ]
8. run_is_job.sh      : [faq: isql job script ]


각 파일에는 객체 생성 문장이 담긴 .sql 파일들을 실행하는 isql 명령들이 담겨져 있습니다.


$ cat run_is.sh

isql -s localhost -u SYS -p MANAGER -f ALL_CRT_TBS.sql
isql -s localhost -u SYS -p MANAGER -f ALL_CRT_USER.sql
isql -s localhost -u SYS -p MANAGER -f ALL_CRT_SYN.sql
isql -s localhost -u SYS -p MANAGER -f ALL_CRT_DIR.sql
isql -s localhost -u SYS -p MANAGER -f ALL_CRT_TBL.sql
isql -s localhost -u SYS -p MANAGER -f ALL_CRT_SEQ.sql
isql -s localhost -u SYS -p MANAGER -f ALL_CRT_LIB.sql
isql -s localhost -u SYS -p MANAGER -f ALL_CRT_VIEW_PROC.sql
isql -s localhost -u SYS -p MANAGER -f ALL_CRT_LINK.sql


데이터 업로드 전 필수 작업


데이터를 복원하기 전에 반드시 아래 환경 변수를 확인 후 진행하도록 합니다.


ALTIBASE_NLS_USE 는 한글 데이터가 깨지는 것을 방지 하기 위해서 필요하며 ILO_DATEFORM 은 date 형 컬럼이 unique 한 값을 갖는 경우
중복을 막기 위해서 설정해야 합니다.


ALTIBASE_NLS_USE
ILO_DATEFORM


iloader 를 수행하는 세션에서 아래와 같이 export 명령어로 설정하거나 사용자 환경 설정 파일(.bash_profile 또는 .profile)에 추가하고 로그
아웃, 로그인 해도 적용됩니다.


환경 변수 설정 방법





환경 변수 설정 방법


$ echo $ALTIBASE_NLS_USE
$ echo $ILO_DATEFORM


알티베이스 서버 캐릭터 셋은 아래 문장으로 확인할 수 있습니다.NLS_CHARACTERSET 가 알티베이스 서버의 캐릭터 셋이며 NLS_USE 는
클라이언트의 캐릭터 셋입니다. 이 둘이 동일하게 설정되어야 한글 데이터가 깨지지 않습니다.





데이터베이스 객체 생성


.sh 파일을 실행할 때는 로그 파일을 남겨 에러 여부를 확인해야 합니다.





데이터 업로드


데이터 업로드는 run_il_in.sh 를 이용해서 수행하는데, 특정 유저 소유의 테이블만 업로드 하고 싶거나 특정 테이블만 업로드하고 싶은 경우
아래와 같이 run_il_in.sh 에서 원하는 것만 추출하여 수행할 수도 있습니다.






테이블이 많거나 데이터가 많은 경우 upload.out 을 모니터링하여 종료 여부를 확인합니다.





데이터 업로드 결과 확인


.sh 수행 로그 확인


.sh 수행 시마다 모두 로그를 남겨서 .sh 수행 후 정상 여부를 로그를 통해 확인합니다.





테이블 별 로그 파일 확인


아래 명령어들을 수행하여 데이터 업로드 시 에러 발생한 부분이 있는 지 확인합니다.


$ grep -i err- upload.out                         # run_il_int.sh 스크립트 수행 결과에서 에러가 발생
했는 지 확인합니다.

[ERR-311F4 : Invalid column name                     # 이와 같이 ERR- 로 시작하는 것이 나오면

에러가 발생했다는 의미입니다.


$ ls -l *.fmt|wc -l                            # 테이블 수 확인
$ ls -l *.log|wc -l                            # run_il_in.sh 수행으로 생성된 로그 파일 수 확인


$ cat *.log | grep 'Error Row Count' | awk -F: '{print $2}' | wc -l   # 이 결과의 수가 위 두 결과의 수와
일치해야합니다. 만약 다르다면 차이 난 수 만큼 에러가 발생했다는 의미입니다.


$ cat *.log | grep 'Error Row Count' | awk -F: '{print $2}' | sort -u  # 이 결과가 0 이면 업로드 수행 시
실패한 것이 없음을 알 수 있습니다.

0

#### 04-02. Cold Backup한 것을 Directory 경로변경 하여 복구하는 방법


개요
버전
Directory 경로 변경방법
Directory 경로 변경절차
참고


개요


Cold Backup 후 불가피하게 각 데이터 파일 등 주요 데이터베이스 파일들의 디렉토리 경로를 변경하여 복구하는 방법을 기술합니다.


버전


ALTIBASE HDB 4 이상


Directory 경로 변경방법


Cold Backup 데이터베이스 파일들을 이용하여 복구할 시, 디렉토리 경로 변경이 없다면, 해당 디렉토리에 mydb*(메모리디비),
*.dbf(디스크디비), logs, loganchor를 복사(cp) 후,


B를 Start하면, 백업 시점으로 DB를 복구시킬 수 있습니다.


하지만, 불가피하게 디렉토리명을 변경해야 한다면, 각 데이터베이스 파일들의 (메모리DB, logs, loganchor)의 디렉토리 경로를 변경하고


변경된 디렉토리에 파일을 복사하는 것으로 해결되지만, 디스크DB는 Control단계에서, datafile의 rename을 수행해야 합니다.


Directory 경로 변경절차


1. 원하는 디렉토리를 만들고, Cold Backup한 파일을 복사합니다.
Cold Backup(mydb*, *.dbf, logs, loganchor)한 것을 OS copy 명령어를 이용해 원하는 디렉토리에 복사합니다.


2. $ALTIBASE_HOME/conf/altibase.properties를 수정합니다.


..중략
MEM_DB_DIR     = /home/cheol2/altibase_home/dbs # Memory DB Directory

DEFAULT_DISK_DB_DIR =/home/cheol2/altibase_home/dbs # Disk  DB Directory

LOGANCHOR_DIR    =/home/cheol2/altibase_home/logs # LOGANCHOR_DIR1 // 로그앵커
LOGANCHOR_DIR    = /home/cheol2/altibase_home/logs # LOGANCHOR_DIR2
LOGANCHOR_DIR    = /home/cheol2/altibase_home/logs # LOGANCHOR_DIR3

LOG_DIR = /home/cheol2/altibase_home/logs # 리두로그 파일 디렉토리
ARCHIVE_DIR  = /home/cheol2/altibase_home/logs # 아카이브 디렉토리
..중략


3. Control 단계로 Startup 합니다.


[cheol2@as48-x64 ~/altibase_home/conf]$ is -sysdba

----------------------------------------------------------------
Altibase Client Query utility.

Release Version 6.5.1.0.6

Copyright 2000, ALTIBASE Corporation or its subsidiaries.
All Rights Reserved.

----------------------------------------------------------------
ISQL_CONNECTION = UNIX, SERVER = localhost, PORT_NO = 33889
iSQL(sysdba)>startup control;

TRANSITION TO PHASE : PROCESS

TRANSITION TO PHASE : CONTROL

Command execute success.


4. ISQL에서 datafile을 rename합니다.. (디렉토리 경로변경)


iSQL(sysdba)>alter database rename datafile '/home/cheol2/altibase_home/dbs2/system001.dbf' to
'/home/cheol2/altibase_home/dbs/system001.dbf';
iSQL(sysdba)>alter database rename datafile '/home/cheol2/altibase_home/dbs2/system002.dbf' to
'/home/cheol2/altibase_home/dbs/system002.dbf';
iSQL(sysdba)>alter database rename datafile '/home/cheol2/altibase_home/dbs2/temp001.dbf' to
'/home/cheol2/altibase_home/dbs/temp001.dbf';
iSQL(sysdba)>alter database rename datafile '/home/cheol2/altibase_home/dbs2/undo001.dbf' to
'/home/cheol2/altibase_home/dbs/undo001.dbf';
iSQL(sysdba)>alter database rename datafile '/home/cheol2/altibase_home/dbs2/system001.dbf' to
'/home/cheol2/altibase_home/dbs/system001.dbf';
iSQL(sysdba)>alter database rename datafile '/home/cheol2/altibase_home/dbs2/system002.dbf' to
'/home/cheol2/altibase_home/dbs/system002.dbf';
iSQL(sysdba)>alter database rename datafile '/home/cheol2/altibase_home/dbs2/temp001.dbf' to
'/home/cheol2/altibase_home/dbs/temp001.dbf';
iSQL(sysdba)>alter database rename datafile '/home/cheol2/altibase_home/dbs2/undo001.dbf' to
'/home/cheol2/altibase_home/dbs/undo001.dbf';


5. ISQL에서 startup합니다.


iSQL(sysdba)> startup service;ISQL_CONNECTION = UNIX, SERVER = localhost, PORT_NO = 33889

[ERR-910FB : Connected to idle instance]

Connecting to the DB server... Connected.

TRANSITION TO PHASE : PROCESS

TRANSITION TO PHASE : CONTROL

TRANSITION TO PHASE : META
[SM] Recovery Phase - 1 : Preparing Database
: Dynamic Memory Version => Parallel Loading
[SM] Recovery Phase - 2 : Loading Database
[SM] Recovery Phase - 3 : Skipping Recovery & Starting Threads...
Refining Disk Table
[SM] Refine Memory Table : ............................................................................................................

[SUCCESS]
[SM] Rebuilding Indices [Total Count:117]
........................................................................................................... [SUCCESS]

TRANSITION TO PHASE : SERVICE
[CM] Listener started : TCP on port 33889 [IPV4]
[CM] Listener started : UNIX
[CM] Listener started : IPC
[RP] Initialization : [PASS]

--- STARTUP Process SUCCESS --
Command executed successfully.


참고


좀 더 상세한 내용은 General Reference 목차에서 확인 할수 있습니다.

#### 04-03. Online Backup 및 Time Based Recovery 방법


개요
버전
온라인 백업 절차
Time Based 복구
참고


개요


아카이브 로그 모드로 알티베이스 서버를 운영할 경우 수행할수 있는 온라인 백업(Online Backup) 및 특정시간을 기준으로(Time Based
Recovery) 백업하는 방법에 대해 설명합니다.


아카이브 모드(Archivelog Mode)가 아니면 온라인 백업(Online Backup)이 불가능 합니다.


버전


ALTIBASE HDB 4 이상


온라인 백업 절차


1. 온라인백업은 반드시 아카이브모드로 DB가 운영중일 경우에만 가능하며, 아카이브모드 확인 및 변경하는 절차는 다음과 같습니다.


가. Archivelog Mode 확인방법


iSQL> select ARCHIVE_MODE from v$archive;ARCHIVE_MODE

----------------------
0            // 0 : Archive_mode 미 사용, 1 : Archive mode 사용


나. Archive Mode 변경방법
온라인 중에 Archive Mode를 변경할 수 없으며 DB shutdown 후 Control 단계에서 변경가능합니다.


sysdba 모드로 접속 후 Control 단계로 startup 하여 아카이브 모드로 변경합니다.


[cheol@as48-x64 ~]$ is -sysdba
iSQL(sysdba)> startup control;
Connecting to the DB server...

Connected.TRANSITION TO PHASE : PROCESS

TRANSITION TO PHASE : CONTROL

Command execute success.

2) Archivelog mode로 변경합니다
iSQL(sysdba)> alter database archivelog;Alter success.


2. DB가 Archivelog Mode로 운영중 일 경우 Online Backup을 수행하는 절차


가. 데이터베이스 시스템에 의한 데이터베이스 Online Backup


1) 데이터베이스 단위 온라인 백업


iSQL> alter database backup database to '/backup'; // backup 디렉토리는 임의로 변경가능 합니다.


아래와 같은 파일들이 /backup 디렉토리로 copy 됩니다.


SYS_TBS_MEM_DIC-0-0

SYS_TBS_MEM_DATA-0-0

system001.dbf
system002.dbf

undo001.dbf

loganchor0
loganchor2
loganchor1


2) 특정 테이블스페이스 단위 Online Backup하는 경우


iSQL(sysdba)> alter database backup tablespace SYS_TBS_MEM_DIC to ‘/backup_dir’; // SYS_TBS_MEM_DIC
데이터 파일 중에서 안정(stable)된 버전이 /backup_dir 디렉터리에 온라인 백업됩니다.
$ ls /backup_dirSYS_TBS_MEM_DIC-0-0


3) 로그앵커 온라인 백업


iSQL(sysdba)> alter database backup loganchor to ‘/backup_dir’; // 모든 로그앵커 파일이 /backup_dir
디렉터리에 온라인 백업됩니다.
$ ls /backup_dir
loganchor0 loganchor1 loganchor2


나. DBA에 의한 온라인 백업


1) 테이블스페이스 단위 온라인 백업


Ex) /backup_dir 에 USER_MEMORY_TBS 와 USER_DISK_TBS 테이블스페이스의 데이터 파일들을 온라인 백업 합니다.


Ex) /backup_dir 에 USER_MEMORY_TBS 와 USER_DISK_TBS 테이블스페이스의 데이터 파일들을 온라인 백업
합니다.


메모리 테이블스페이스 데이터 파일은 안정(stable) 버전의 데이터 파일인지 확인 후 온라인 백업합니다.


iSQL(sysdba)> alter tablespace USER_MEMORY_TBS begin backup;
iSQL(sysdba)> select * from v$stable_mem_datafiles;

MEM_DATA_FILE

-------------------------------------------------
/altibase_home/dbs/USER_MEM_TBS-0-0 //안정적인 버전

$ cp $ALTIBASE_HOME/dbs/USER_MEMORY_TBS-0-0 /backup_dir/

iSQL(sysdba)> alter tablespace USER_MEMORY_TBS end backup;
iSQL(sysdba)> alter tablespace USER_DISK_TBS begin backup;

$ cp $ALTIBASE_HOME/dbs/USER_DISK_TBS.dbf /backup_dir/

iSQL(sysdba)> alter tablespace USER_DISK_TBS end backup;

$ ls /backup_dir

USER_MEMORY_TBS-0-0 USER_DISK_TBS.dbf


2) DBA에 의한 온라인 백업 마무리


백업과 관련된 로그 파일을 강제로 아카이브(archive) 하는 명령을 수행해야 하여 현재 로그 파일을 다 쓰지 않았어도 닫고 다음 로그 파일에
로깅을 계속하도록 명령합니다.


iSQL(sysdba)> ALTER SYSTEM SWITCH LOGFILE;


Time Based 복구


Archivelog Mode로 운영중이며, 원하는 복구 시점 이전에 전체 DB에 대한 Online Backup(또는 Cold Backup)을 1회 이상 수행 하였을 경우
복구 절차 입니다.


ex) 실수로 테이블스페이스 USER_DISK_TBS 가 삭제되었다. (2015년 7월 23일 14:11)


테이블스페이스가 존재했던 10 분 전의 상태로 데이터베이스 복구절차


마지막 백업 시 다음과 같이 전체 DB 를 백업하였습니다.


iSQL(sysdba)> ALTER DATABASE BACKUP DATABASE TO ‘/backup_dir’;


가. 백업 받은 데이터베이스의 모든 디스크 테이블스페이스의 데이터 파일들을 데이터 파일들의 원래 위치로 복사합니다.


$ cp /backup_dir/*.dbf $ALTIBASE_HOME/dbs
$ cp /backup_dir/SYS_TBS_* $ALTIBASE_HOME/dbs


나. 복구에 필요한 아카이브 로그 파일을 확인 및 백업된 로그앵커 파일을 복사하여 사용합니다.


1) 복구에 필요한 아카이브 로그파일 확인


iSQL(sysdba)> select last_deleted_logfile from v$lfg;

LAST_DELETED_LOGFILE

-----------------------
15021        // 복구에 필요한 아카이브 로그파일번호


$ALTIBASE_HOME/trc 디렉터리에 생성되는 altibase_sm.log 파일에서 백업 완료 시 강제로 아카이브 처리된 파일을 확인 합니다.


[2015/07/23 13:59:59] [Thread-6] [Level-9]Waiting logfile15341 to archive //강제로 아카이브 처리된
파일번호즉 복구를 위해 logfile15021 ~ logfile15341 파일이 필요합니다.


2) 백업된 로그앵커 파일 복사


$ cp /backup_dir/loganchor* /ALTIBASE_HOME/logs;


3) SYS_TBS_DISK_TEMP 테이블스페이스는 백업되지 않기 때문에 해당 일을 새로 만듭니다.


iSQL(sysdba)> ALTER DATABASE CREATE DATAFILE ‘temp001.dbf’


4)불완전 미디어 복구를 수행합니다.


iSQL(sysdba)> ALTER DATABASE RECOVER DATABASE UNTIL TIME '2015-07-23:14:01:00';


불완전 미디어 복구를 수행하였기 때문에 meta 구동 단계로 가면서 resetlogs 옵션을 사용해야 합니다.


iSQL(sysdba)> ALTER DATABASE mydb META RESETLOGS;


5)서버를 구동하고 로그가 리셋되었기 때문에 전체데이터 베이스 백업 합니다.


iSQL(sysdba)> ALTER DATABASE mydb SERVICE;
iSQL(sysdba)> ALTER DATABASE BACKUP DATABASE TO ‘/backup_dir’;


참고


좀 더 상세한 내용은 Admin Manual 백업 및 복구사례 목차에서 확인 할수 있습니다.

### 05. SQL

#### 05-01. varchar, char 타입 비교


개요


varchar타입과 char 타입에 대한 비교 입니다.


버전


알티베이스 모든 버전에 해당합니다.


VARCHAR 타입과 CHAR 타입의 비교


iSQL> create table dual (X char(1));


Create success.
iSQL> insert into dual values ('x');
1 row inserted.

iSQL> select 1 from dual;

1

-------------
1

1 row selected.
iSQL> select 1 from dual where char'a ' = char'a ';

1

-------------
1

1 row selected.
iSQL> select 1 from dual where varchar'a ' = varchar'a ';

1

-------------
No rows selected.
iSQL> select 1 from dual where varchar'a' = char'a ';

1

-------------
No rows selected.
iSQL> select 1 from dual where varchar'a' = char'a';

1

-------------
1

1 row selected.
iSQL> select 1 from dual where varchar'a ' = char'a ';


1

-------------
1

1 row selected.


char type 인 경우 비교시 length가 큰쪽을 기준으로 0x20이 더해져서 비교되고
char, varchar의 비교시 varchar의 유효 데이타 (0x00의 위치) 기준으로 비교되는 것을 보여주고 있습니다.
가끔 SESC 코딩시 변수를 varchar의 경우는 0x00으로 초기화 하고 char의 경우는
0x20으로 초기하는 경우가 있는데 위의 규칙이 있으므로 0x00으로 초기화하는 것이 좋습니다.

#### 05-02. 객체에 부여된 권한을 확인하는 방법


개요


DB 유저간에는 객체에 대한 권한을 grant 구문을 사용하여 부여할 수 있습니다.  DB 전체에 부여된 DB 유저끼리의 객체권한의 관계를

쿼리를 사용하여 조회해 볼 수 있습니다.


대상버전


ALTIBASE HDB 4.3.9 이상 모든 버전에서 사용 가능합니다.


방법


아래의 쿼리로 조회가 가능합니다.


SELECT a.user_name grantee,                   -- 권한을 부여받은 유저
c.user_name grantor,                   -- 권한을 준 유저
f.user_name object_owner,                -- 객체의 소유자
e.table_name object_name,                -- 객체이름
e.table_type object_type,                -- 객체 종류
replace(d.priv_name, '_', ' ') priv_name,        -- 부여 권한명
decode(b.with_grant_option, 0, 'NO', 'YES') grantable  -- 해당 객체에 대한 권한 재부여
가능 여부

FROM system_.sys_users_ a,
system_.sys_grant_object_ b,

system_.sys_users_ c,
system_.sys_privileges_ d,
system_.sys_tables_ e,
system_.sys_users_ f
WHERE c.user_name <> 'SYSTEM_'

and b.grantee_id = a.user_id
and b.grantor_id = c.user_id
and b.priv_id = d.priv_id
and b.obj_id = e.table_id

and e.user_id = f.user_id

ORDER BY grantee,

grantor,
object_owner,
object_type,
object_name,
priv_name ;








### 06. Stored Procedures

#### 06-01. Stored Procedure 내에서 DML 로 영향 받은 레코드 수 확인 방법


SQL%ROWCOUNT 를 사용하면 DML 로 영향을 받은 레코드 수를 알 수 있습니다.





IE 사용자에게
IE 에서 프로시저 생성 구문을 복사하면 빈 공간이 생길 수 있으니 필요 시 첨부 파일을 사용하시기 바랍니다. SP_DML_RECORD_CO
UNT.txt

#### 06-02. 저장 프로시저 내용 확인 방법


개요
버전
방법

메타 테이블 이용
aexport 유틸리티 이용


개요


저장 프로시저 내용을 확인하는 방법에 대해 안내합니다.


버전


ALTIBASE HDB 모든 버전


방법


저장 프로시저 내용을 확인하는 방법은 두 가지가 있습니다.


메타 테이블 이용
aexport 유틸리티 이용


메타 테이블 이용


메타 테이블 SYSTEM_.SYS_PROCEDURES_, SYSTEM_.SYS_PROC_PARSE_ 를 이용한 사용자 정의 프로시저 생성 후 이를 사용하여 저장
프로시저 내용을 확인할 수 있습니다.


사용자 정의 프로시저 생성 방법


저장 프로시저 및 사용자 정의 함수 출력을 위한 저장 프로시저


저장 프로시저 내용을 확인하기 위한 저장 프로시저


사용자 정의 저장 프로시저 실행 방법


저장 프로시저 및 사용자 정의 함수 목록 확인


iSQL> exec showProcedures;


저장 프로시저 내용 확인


~~iSQL> exec showProcBody(~~ ' ~~USER NAME~~ ' ' ~~PROC NAME~~ ' ~~);~~


aexport 유틸리티 이용


aexport는 데이터베이스 객체 생성 구문을 파일에 저장해주는 유틸리티입니다. aexport 수행 후 생성된 파일에서 저장 프로시저 내용을 확인할


p p


수 있습니다.


aexport 수행 - 모든 객체


aexport 수행 후 생성된 파일 중 ALL_CRT_PROC.sql 에서 모든 저장 프로시저의 생성 구문을 확인할 수 있습니다.






유저 별 aexport 수행


aexport 의 -u 옵션에 데이터베이스 사용자 이름을 입력하고 -p 옵션에 해당 사용자의 패스워드를 입력 후 aexport를 수행하면 해당
사용자 소유의 객체 스키마만 추출합니다.
저장 프로시저 내용은 ALL_CRT_PROC.sql 파일을 참고하세요.


수행 방법





객체 별 aexport 수행


object 옵션을 사용하면 특정 객체 스키마만 추출할 수 있습니다. 이 옵션은 ALTIBASE HDB 5.5.1 부터 사용할 수 있습니다.
저장 프로시저의 경우 -object 유저명프로시저명. 형식으로 값을 줄 수 있습니다.
결과는 유저명프로시저명_ _CRT.sql 형식의 이름을 가진 파일이 생성됩니다.
수행 방법




### 07. 개발 및 API

#### 07-01. Connection 연결이 끊어지는 경우와 각 경우의 에러 코드 및 에러 메세지(APRE*C/C++, SQLCLI)

개요
적용버전
응용프로그램별 에러 코드와 에러 메시지 확인방법
Connection 에러 상황 및 에러 메시지
결론


개요


응용프로그램에서 커넥션이 단절되는 경우와 각 상황에서의 에러 코드,메시지를 설명합니다.


적용버전


ALTIBASE HDB 6.3.1 을 기준으로 작성 되었습니다.
추가사항 또는 업데이트가 필요한 경우 http://support.altibase.com/kr/ 또는 이 페이지에 댓글로 요청 글 남겨주세요.

## 응용프로그램에서 Connection이 단절되는 경우


다음과 같은 상황은 Connection이 되지않은 상태입니다.



1.

2.

3.

4.


5.

6.



Connect를 안한 경우
통신소켓이상이나 서버쪽에서 연결을 끊은 경우
이전에 끊어진 연결을 감지 못했을 경우 (이전에 Connection이 단절된 경우)
Timeout에 의해 끊어진 경우.
Query Timeout, Fetch Timeout, UTrans Timeout, Idle Timeout이 있으며, Query Timeout의 경우에는 Connection이 끊기지 않으나
이외에 나머지 경우는 모두 Connection이 끊어집니다.
DB Server가 종료된 경우
DB Server가 종료되어 있어 연결은 못하는 경우 (Connect 실패)



응용프로그램별 에러 코드와 에러 메시지 확인방법


응용프로그램이 ALTIBASE Embedded SQL(APRE*C/C++) 로 작성된 경우 확인할 수 있는 값은 다음과 같습니다.



1.

2.

3.

4.



sqlca.sqlcode (쿼리 수행 리턴값 - SQL_SUCCESS, SQL_ERROR, etc)
sqlca.sqlerrm.sqlerrmc (에러메시지)
SQLCODE (에러코드)
SQLSTATE (상태코드)



응용프로그램이 SQLCLI로 작성된 경우 확인할 수 있는 값은 다음과 같습니다.
SQLError(env,dbc,stmt,state,err,msg,msgMax,msgLength) 를 호출하여 확인할수 있습니다.



1.

2.

3.



state (상태코드)
err (에러코드)
msg (에러메시지)



Connection 에러 상황 및 에러 메시지



1.



Connect를 안했거나 이전에 Disconnect 한 경우


2.


3.




[APRE*C/C++]

====================================================

sqlca STRUCTURE
.sqlcode [-2] (SQL_ERROR)
.sqlerrm.sqlerrmc The connection does not exist. (Name:default connection)
SQLCODE [-2]
SQLSTATE ["08003"]

====================================================


[SQLCLI/ODBC]

1. 이전에 한번도 connect를 안한 경우

====================================================

return value [-2]
SQLError(env,dbc,stmt,state,err,msg,msgMax,msgLength)
error state (state) [""]
error number (err) [0] in Hex(0)
error message (msg) [ ?]

====================================================

2. 이전에 disconnect 한 경우

====================================================

return value [-1] (SQL_ERROR)
SQLError(env,dbc,stmt,state,err,msg,msgMax,msgLength)
error state (state) ["08003"]
error number (err) [331830] in Hex(51036)
error message (msg) [Connection does not exist (err8)]

====================================================


Connection이 단절된 경우 (서버에서 끊었거나 네트워크 에러)


[APRE*C/C++]

====================================================

sqlca STRUCTURE
.sqlcode [-1]
.sqlerrm.sqlerrmc [Communication link failure('errno')]
SQLCODE [-331843] in Hex(51043)
SQLSTATE ["08S01"]

====================================================


[SQLCLI/ODBC]

====================================================

return value [-1]
SQLError(env,dbc,stmt,state,err,msg,msgMax,msgLength)
error state (state) ["08S01"]
error number (err) [331843] in Hex(51043)
error message (msg) [Communication link failure('errno')]

====================================================


이전에 연결이 단절된 것을 감지 못하고 다시 쿼리를 수행한 경우


4.


5.




[APRE*C/C++]

====================================================

sqlca STRUCTURE
.sqlcode [-1]
.sqlerrm.sqlerrmc [Connection does not exist (err11)]
SQLCODE [-1]
SQLSTATE ["08003"]

====================================================


[SQLCLI/ODBC]

====================================================

return value [-1]
SQLError(env,dbc,stmt,state,err,msg,msgMax,msgLength)
error state (state) ["08003"]
error number (err) [331830] in Hex(51036)
error message (msg) [Connection does not exist (err8)]

====================================================


Timeout에 의해 단절된 경우
Fetch Timeout, UTrans Timeout, Idle Timeout 모두 같은 에러가 리턴됨. (altibase_boot.log에 timeout 내용이 기록됨.)


[APRE*C/C++]

====================================================

sqlca STRUCTURE
.sqlcode [-1]
.sqlerrm.sqlerrmc [Communication link failure(131)]
SQLCODE [-331843] in Hex(51043)
SQLSTATE ["08S01"]

====================================================


[SQLCLI/ODBC]

====================================================

return value [-1]
SQLError(env,dbc,stmt,state,err,msg,msgMax,msgLength)
error state (state) ["08S01"]
error number (err) [331843] in Hex(51043)
error message (msg) [Communication link failure(131)]

====================================================


DB Server가 종료된 경우


6.




[APRE*C/C++]

====================================================

sqlca STRUCTURE
.sqlcode [-1]
.sqlerrm.sqlerrmc [Communication link failure(131)]
SQLCODE [-331843] in Hex(51043)
SQLSTATE ["08S01"]

====================================================


[SQLCLI/ODBC]

====================================================

return value [-1]
SQLError(env,dbc,stmt,state,err,msg,msgMax,msgLength)
error state (state) ["08S01"]
error number (err) [331843] in Hex(51043)
error message (msg) [Communication link failure(131)]

====================================================


Connect 실패


[APRE*C/C++]

====================================================

sqlca STRUCTURE
.sqlcode [-1]
.sqlerrm.sqlerrmc [Client unable to establish connection]
SQLCODE [-327730] [50032]
SQLSTATE [08001]

====================================================


[SQLCLI/ODBC]

====================================================

return value [-1]
SQLError(env,dbc,stmt,state,err,msg,msgMax,msgLength)
error state (state) [08001]
error number (err) [327730] in Hex(50032)
error message (msg) [Client unable to establish connection]

====================================================



결론


각 상황별로 에러코드로 확인한 결과 다음과 같이 3가지의 경우가 있습니다.


   - SQLSTATE(state) ["08001"] SQLCODE [1(0x01)] errno [32770(0x050032)]

   - connect 실패


   - SQLSTATE(state) ["08003"] SQLCODE(errno) [331830(0x051036)]

  - Connect를 안하고 (disconnect 한 후) 수행하는 경우

  - 이미 Connect가 끊어져 있는 경우


   - SQLSTATE(state) ["08S01"] SQLCODE(errno) [331843(0x051043)]

   - socket 단절

  - timeout에 의해 끊어진 경우

  - 서버가 종료되있는 경우

#### 07-02. JDBC


07-02-01. Altibase JDBC에서 Fail-Over 사용하는 방법은?


개요
용어 설명
Fail-Over 관련 연결 속성
Fail-Over 성공 여부 확인
예제
참고문서


개요


데이터베이스 시스템을 운영하는 도중, 장애가 발생하였을 때 이를 극복하고 장애에 관계없이 서비스를 계속할 수 있도록 Fail-Over 기능을
제공합니다.


여기에서는 Altibase JDBC Fail-Over 의 기능과 사용 방법에 대해 설명합니다.


용어 설명


CTF(Connection Time Fail-Over) : DBMS 접속 시점에 장애가 감지되면 다른 가용 노드의 DBMS로 접속을 재시도하는 것을
의미합니다.

Connection String 에 AlternateServer 속성을 설정하면 기본으로 CTF가 동작합니다.
일반적인 응용프로그램은 다시 Connection 을 시도해야 합니다.
WAS 와 같이 Connection Pool 을 유지하는 형태에서는 WAS 의 Connection
Validation 설정을 통하여 자동적 수행할 수 있습니다.
STF(Service Time Fail-Over) : DBMS 가 클라이언트의 요청을 처리하는 도중에 장애가 감지되면 다른 가용 노드의 DBMS에 다시
접속하는 것을 의미합니다.

Connection 까지만 수행후 성공여부를 에러로 반환하기에 statement 의 prepare
부터 다시 진행될 수 있도록하는 사용자 코딩이 수반되어야 합니다.
기본서버(Primary Server) : Connection URL에서 첫 번째에 명시된 서버정보를 의미합니다.
대체서버(Alternative Server) : AlternateServer 연결속성에 명시된 서버들의 정보를 의미합니다.
명시적 연결(Explicit Connection) : Connection 객체의 connect 메소드를 호출하는 것을 의미합니다.
내부적 연결(Implicit Connection) : connect 메소드가 실패하거나 STF가 발생하여 JDBC 내부적으로 다른 가용 노드의 DBMS로 접속을
재시도하는 것을 의미합니다.


Fail-Over 관련 연결 속성


- 대소문자 구분하지 않음.


AlternateServer : 대체서버들을 의미하며 (IP1:Port1, IP2:Port2,...) 형식으로 기술합니다.
대체서버들은 LoadBalance와 SessionFailOver의 설정에 따라 다음의 경우에 연결 대상 서버가 될 수
있습니다.

connect 메소드 호출 시
connect 메소드 실패로 재연결 시도 시
STF 발생으로 재연결 시도 시
ConnectionRetryCount : 동일 서버로 접속 시도 반복 횟수를 설정합니다.
ConnectionRetryDelay : 동일 서버로 접속 시도 대기 시간으로 단위는 초(second)입니다.
참고) ConnectionRetryCount와 ConnectionRetryDelay 속성은 내부적 연결 시에만 적용되며, ConnectionRetryCount *
ConnectionRetryDelay 만큼 수행 후 실패하면 또 다른 가용 서버로 동일한 방법으로 접속을 시도합니다.
LoadBalance : DBMS 연결 시 기본서버와 대체서버의 연결 시도 순서를 설정합니다.
ON으로 설정 시 기본서버와 대체서버 중에서 랜덤으로 연결 시도합니다.
OFF로 설정 시 기본서버부터 연결 시도하고, 실패할 경우 대체서버의 나열 순서대로 연결 시도합니다.
이 설정은 명시적 연결과 내부적 연결 모두에 해당합니다.
SessionFailOver : STF를 할 것인지 여부를 설정합니다.
ON으로 설정 시 CTF+STF로 동작합니다.
OFF로 설정 시 CTF만 동작합니다.
FailOver_Source : Failover를 수행할 때, 서버에 전달하는 Failover source에 대한 설명을 지정합니다. 이 정보는 V$SESSION 성능 뷰의


FAILOVER_SOURCE 칼럼에 저장됩니다.
HealthCheckDuration : Altibase JDBC는 Failover를 위해 가용 서버 목록을 관리합니다. Failover 시 가용 서버 목록의 서버들을
대상으로 재연결을 시도합니다. 이는 모든 서버가 장애 상황에서 무한루프로 연결 시도하는 것을 막기 위함입니다.


HealthCheckDuration 속성은 Failover가 발생한 서버가 다시 가용 서버 목록으로 설정되기 위한
대기시간을 지정합니다.
Failover가 발생하면 해당 서버는 가용 서버 목록에서 삭제되었다가 HealthCheckDuration
시간이 지난 후에 다시 가용 서버 목록에 추가되며 이 속성의 단위는 초(second)입니다.


Fail-Over 성공 여부 확인


CTF : 데이터베이스 연결이 되는지에 따라 성공 여부를 바로 알 수 있습니다.
STF : exception 처리를 통해서 확인할 수 있습니다.
SQLException에서 getSQLState() 메소드의 반환값이 08F01(6.3.1 이상) 또는 ES_08FO01(6.1.1 이하)이면 FailOver가
성공한 것입니다.


예제


프로그램 작성 시 다음 예제를 참고하세요.


import Altibase.jdbc.driver.*;
import Altibase.jdbc.driver.ex.*;
import java.util.Properties;
import java.sql.*;
import java.io.*;


class FailOverSampleSTF
{
public static void main(String args[]) throws Exception
{
//--------------------------------------------------// Initialization
//--------------------------------------------------
String sURL = "jdbc:Altibase://127.0.0.1:" + args[0]+"/mydb?AlternateServers=(128.1.3.52:20300,128.1.3.53:20300

)&ConnectionRetryCount=3&ConnectionRetryDelay=10&SessionFailOver=on&LoadBalance=off";


try
{
Class.forName("Altibase.jdbc.driver.AltibaseDriver");
}
catch ( Exception e )
{
System.err.println("Can't register Altibase Driver\n");

return;
}


//--------------------------------------------------// Test Body
//--------------------------------------------------

Properties sProp = new Properties();
Connection sCon;

PreparedStatement sStmt = null;
ResultSet sRes = null ;
sProp.put("user", "SYS");
sProp.put("password", "MANAGER");

sCon = DriverManager.getConnection(sURL, sProp);


sStmt = sCon.prepareStatement("SELECT C1 FROM T2  ORDER BY C1");


while(true)
{
try
{
sRes = sStmt.executeQuery();
while( sRes.next() )
{
System.out.println( "VALUE : " + sRes.getString(1) );
}
}
catch ( SQLException e )
{
//Failover 확인.
//if (e.getSQLState().equals("ES_08FO01")) // 6.1.1 이하
if (e.getSQLState().equals("08F01"))       // 6.3.1 이상
{
sStmt = sCon.prepareStatement("SELECT * FROM tb_test1");  // Failover 발생 시 prepare를 다시
해주어야 한다.

continue;
}
System.out.println( "EXCEPTION : " + e.getMessage() );
break;
}
break;
}

sRes.close();


//--------------------------------------------------// Finalize
//--------------------------------------------------
sStmt.close();
sCon.close();
}
}


참고문서


Replication Manual -> 4장 FailOver
JDBC User's Manual -> 1장 JDBC 시작하기 -> 연결정보


3장 고급기능 -> JDBC와 FailOver

ALTIBASE JBOSS 연동가이드

07-02-02. jdbc.trc 파일 생성 위치 변경 방법


생성 시기 및 용도
대상버전
생성 위치
생성 경로 변경 방법


생성 시기 및 용도


jdbc.trc 파일은 JDBC 관련 trace를 위해 생성하는 로그 파일로, jdbc driver가 초기화 될 때 자동 생성됩니다.


커넥션 URL 에 fail-over를 명시한 경우 fail-over가 발생될 때 event trace 용도로도 사용됩니다.


connection url에서 fail-over를 명시하지 않았거나, fail-over가 발생하지 않으면 0 byte~초기값이 됩니다.


파일 사이즈는 플랫폼마다 약간의 차이가 있습니다.


하나의 자바 프로그램을 동시에 수행하면 아래와 같이 수행한 수만큼 생성되고
jdbc.trc
jdbc.trc.lck
jdbc.trc.1
jdbc.trc.1.lck


jdbc.trc.2
jdbc.trc.2.lck
하나의 자바 프로그램 내에서 커넥션 객체를 각자 별개로 접속할 경우에는 jdbc.trc 파일을 공유해서 사용합니다.


대상버전


jdbc.trc 파일은 ALTIBASE HDB 5.5.1 이후부터  jdbc 관련 trace 를 위해서 생성됩니다.


생성 위치


클라이언트 환경에서 ALTIBASE_HOME 환경 변수가 설정되어 있는 경우 $ALTIBASE_HOME/trc 에 생성되고
ALTIBASE_HOME 환경 변수가 설정되어 있지 않은 경우 자바 프로그램을 실행한 위치에 생성됩니다.


간혹 jdbc.trc 파일이 생성되는 디렉토리에 write 권한이 없는 경우 파일 생성 실패로 응용 프로그램에서 아래와 같은 오류가 발생할 수
있습니다.


java.io.IOException: Couldn't get lock for /opt/altibase-HDB-server-6.1.1/trc/jdbc.trc


위와 같은 오류가 발생할 경우 해당 디렉토리에 퍼미션(permission) 을 주거나 ALTIBASE_HOME 환경변수를 적정한 위치로 설정하십시요.


생성 경로 변경 방법

|ALTIBASE HDB Version|jdbc.trc 로그 생성 위치 변경하는 방법|
|---|---|
|version 6.1.1.1.3 이하|변경 가능한 방법 없음|
|version 6.1.1.1.4   ~  6.1.1.1.7|java 실행시 옵션으로 설정 가능함<br>java -DALTIBASE_JDBC_TRCLOG_DISABLE=true|
|version 6.1.1.1.8 이상|java 실행시 옵션 설정.<br>java -DALTIBASE_JDBC_TRCLOG_DISABLE=true<br>또는<br> java 실행 유저의 환경변수로 설정<br>exportALTIBASE_JDBC_TRCLOG_DISABLE=true|


#### 07-03. ODBC


07-03-01. 64-bit Windows에서 32-bit ODBC 설치


개요
버전
Altibase ODBC 설치
ODBC 설정


개요


Windows Server 2003 64-bit 시스템에 32-bit ODBC 드라이버를 설정하는 방법에 관해 설명합니다.


버전


~ Altibase 6.5.1 (※ 7.1 부터는 32bit 용 ODBC 드라이버를 지원하지 않습니다.)


Altibase ODBC 설치



1.


2.



Windows Altibase 32-bit 클라이언트 설치 파일 또는 Altibase 32-bit ODBC 설치 파일을 다운로드 합니다.
다운로드 경로 : http://support.altibase.com/kr/product
클라이언트 설치 파일 이름 예 : altibase-HDB-client-x.x.x.x.x-WINDOWS-X86-32bit-release.exe
ODBC 설치 파일 이름 예 : altibase-HDB-ODBC-x.x.x.x.x-WINDOWS-X86-32bit-release.exe


Windows Altibase 32-bit 클라이언트를 설치합니다.
설치 방법은 Installation Guide 매뉴얼에서 2. 패키지 인스톨러를 이용한 제품 설치 -> 윈도우에서 ALTIBASE HDB 클라이언트 제품
설치 부분을 참고합니다.
매뉴얼 다운로드 : http://support.altibase.com/kr/manual



ODBC 설정



1.


2.



32-bit ODBC 용 데이터 원본 관리자를 실행합니다.

C:\windows\sysWOW64\odbcad32.exe 를 더블클릭합니다.


새 데이터 원본 만들기
ODBC 데이터 원본 관리자 창의 사용자 'DSN 탭'에서 '추가' 버튼을 클릭하여 새 데이터 원본 만들기 창을 엽니다.
Altibase 32-bit ODBC 드라이버를 선택하고 '마침'을 누릅니다.


3.


4.



'Altibase Connection Config' 창이 뜨면 Altibase 서버 접속 정보를 입력합니다.


- Windows DSN Name
데이터 원본의 이름을 사용자가 지정하여 입력합니다.

- host (name or IP)
Altibase 서버의 IP를 입력합니다.

- Port (default 20300)
Altibase 서버의 서비스 포트를 입력합니다.
altibase.properties 파일(Altibase 서버 프로퍼티 파일)에서 PORT_NO 값을 확인하거나 Altibase 서버에서 ALTIBASE_PORT_NO
환경변수 값을 확인합니다.

- User
데이터베이스 사용자 이름을 입력합니다.

- Password
데이터베이스 사용자 비밀번호를 입력합니다.

- Database
데이터베이스 이름을 입력합니다.
데이터베이스 이름은 SELECT DB_NAME FROM V$DATABASE; 로 확인할 수 있습니다.

- NLS_USE
Altibase 서버 캐릭터셋을 입력합니다.
Altibase 서버 캐릭터셋은 SELECT NLS_CHARACTERSET FROM V$NLS_PARAMETERS; 로 확인합니다.


Test Connection 버튼을 클릭하여 접속 여부를 확인합니다.


5. 사용자 DSN 탭에 추가된 Altibase DSN 을 확인합니다.


07-03-02. ODBC 함수, SQLFreeStmt


개요
적용버전

## 개요


ODBC 함수, SQLFreeStmt의 사용방법에 대한 설명입니다.


적용버전


ALTIBASE HDB 6.3.1 을 기준으로 작성 되었습니다.
추가사항 또는 업데이트가 필요한 경우 http://support.altibase.com/kr/ 또는 이 페이지에 댓글로 요청 글 남겨주세요.

## SQLFreeStmt 옵션


다음과 같은 4가지 옵션의 내용을 기술하고 있습니다.

|SQL_CLOSE|stmt와 관련된 커서를 닫고 모든 보류중인 결과들을 폐기한다. 애플리케이션은 같은 또는 다른 변수들을 사용해<br>다시 SELECT 문을 수행함으로서 나중에 이 커서를 다시 열 수 있다. 만약 어떠한 커서도 열려 있지 않으면, 이 옵션<br>애플리케이션에 대해 아무런 영향을 주지 않는다.|
|---|---|
|SQL_DROP|입력 명령문 핸들과 연관된 자원이 해제되고 핸들이 무효화된다. 열린 커서가 있는 경우 닫히고 모든 미결인 결과가<br>삭제된다.|
|SQL_UNBIND|이 명령문 핸들에서 이전의 SQLBindCol() 호출에 의해 바인드된 모든 열이 해제된다.|
|SQL_RESET_PARAMS|이 명령문 핸들에서 이전의 SQLBindParameter() 호출에 의해 설정된 모든 매개변수가 해제된다. 애플리케이션 변수<br>또는 파일 참조와 명령문 핸들의 SQL문 매개변수 마커 사이의 연관이 깨진다.|



이 중 주로 사용되는 것이 SQL_CLOSE, SQL_DROP입니다.



1.


2.



SQLFreeStmt(stmt, SQL_DROP):
prepared 된 stmt(statement handle)에 대한 자원을 완전히 해제한다는 의미가 됩니다.
즉 해당 stmt를 재사용하지 않을 때만 호출합니다.


SQLFreeStmt(stmt, SQL_CLOSE):
검색된 데이타를 모두 Fetch 하지 않았을 경우, SQLFreeStmt(SQL_CLOSE) 없이 SQLExecute를 다시 실행하면 오류가 발생합니다.

SQLFreeStmt(stmt, SQL_CLOSE)를 사용하면, SQLAllocStmt()를 하지 않고 기존 stmt를 재사용할수 있습니다.



07-03-03. unix_odbc와 연동하기


개요


UNIX_ODBC 와 altibase 연동관련 가이드입니다.


버전


ALTIBASE HDB 모든 버전


UNIX_ODBC 종류 및 URL


unix_odbc 는 open source project 로서 주로 unixODBC 가 사용됩니다.


_ p p j


1. unixODBC는 아래 링크에 다운로드 받으실 수 있습니다.

- http://www.unixodbc.org/


INSTALL





옵션설명
prefix : unixODBC를 설치할 경로
enable-gui : GUI ODBC Administrator를 build 여부
enable-threads : The default is "yes" if thread-support is found on your machine. All modern Linuxes will have pthreads
support in glibc so it is probably best to leave this to default.

만일 enable-threads 옵션을 no로 설정할 경우 isql로 접속테스트시 아래 에러가 발생할 수 있습니다.
$ ./isql Altiodbc
./isql: symbol lookup error: /home/wonsik/altibase_home/lib/libaltibase_odbc-64bit-ul64.so: undefined symbol:
pthread_sigmask
$ ./isql Altiodbc
./isql: symbol lookup error: /home/wonsik/altibase_home/lib/libaltibase_odbc-64bit-ul64.so: undefined symbol: pthread_sigma
sk


PHP, PERL 연동


PHP, PERL 등에서 unix_odbc 를 지원하므로 위의 방식으로 altibase와 연동할 수 있습니다.


PHP 연동 가이드



1.


2.


3.


4.



관련 환경 변수 설정



unixODBC의 odbc.ini 파일 수정


odbc ini 파일에LongDataCompat=ON을추가해줌으로써lob 데이터를처리하도록설정가능합니다


PHP 컴파일 및 설치 작업





SQLLEN, SQLULEN 확인




5.



php.ini 설정


#### 07-04. PHP

07-04-01. php 사용중인데 한글이 깨집니다.


현상
PHP 실행구조
주요 원인

ODBC 설정에서 NLS_USE 설정
터미널창에서 한글 지원 코드 설정
PHP 설정에서 변수에 설정되는 최대 길이 설정


현상


PHP를 사용하는 web 페이지에서 한글 조회시 한글이 깨지는 경우는 있습니다.


자주 발생하는 한글 깨짐 현상의 원인과 해결 방법에 대해서 알아봅니다.


PHP 실행구조


odbc driver manager 인 unixODBC ( http://www.unixodbc.org/ ) 와 ALTIBASE 가 제공하는 odbc driver를 사용하여  php 페이지에서
ODBC API를 통해 ALTIBASE HDB DB에 접근할 수 있습니다.


ALTIBASE 와 PHP 를 연동하는 방법에 대한 설명은 『 ALTIBASE PHP 연동가이드』 를 참고하시기 바랍니다.


주요 원인


한글이 깨지는 현상은 web 서버 설정, php 설정, unixODBC 설정등 다양한 부분에서의 설정 문제로 발생할 수 있으므로 먼저
unixODBC에서 한글을 포함하는 DB 결과가 정상적으로 출력되는 것을 먼저 확인해야 합니다.


unixODBC에서 제공하는 $UNIXODBC_HOME/bin/isql 유틸리티를 사용하여 DB에 쿼리를 실행해서 한글을 포함한 쿼리 결과가 정상적으로
출력되는 지 확인 후 다음으로 php 설정을 확인합니다.


이 후 마지막 단계로 web 서버 설정이나 web page 설정을 확인해서 한글 관련한 character set 설정에 문제가 없는지 확인합니다.


ODBC 설정에서 NLS_USE 설정


unixODBC 설정인 odbc.ini 에 DB 에 connection 에 사용되는 client character set 을 지정하는 NLS_USE 설정이 있습니다. 이
설정값과 DB의 character set 설정이 맞지않는 경우 한글 출력에 문제가 있을 수 있습니다.


이 프라퍼티는  DB의 character set 과 동일한 값으로 설정해야 합니다.


터미널창에서 한글 지원 코드 설정


DB에서 정상적으로 데이타를 가져왔음에도 이를 출력하는 터미널 창에서 한글 문자셋 출력을 지원하지 못할 경우 한글이 제대로 출력되지
못할 수 있습니다.


DB character set 이 UTF8 로 설정되어 있는 경우 window command 창에서도  유니코드를 보여줄 수 있도록  코드 페이지(chcp
명령)가  설정되어야 하며 그렇지 않을 경우 한글이 정상적으로 출력되지 않습니다.







일반적으로 많이 사용하는 터미널 접속 프로그램 인 Secure CRT 와 같은 프로그램도 UTF8 인 한글 문자를 출력할 경우 session 설정중에
unicode  관련 설정이 맞게 설정되어 있어야 한글이 정상 출력됩니다.


PHP 설정에서 변수에 설정되는 최대 길이 설정


php 프로그램을 하는 경우 데이터가 큰 varchar 또는 clob 데이터가 깨지거나 같은 데이터가 반복적으로 나오는 경우가 있습니다. 만약 특정부

분 부터 데이터 출력에 문제가 있다면 odbc 설정 부분을 살펴봐야 합니다.


증상이 위와 같은 경우 php.ini에서 odbc.defaultlrl 값을 데이터가 모두 포함될 수 있도록 변경하여 줍니다.


예를들어, 컬럼이 varchar(65536)일 경우 기본 설정 값 odbc.defaultlrl = 4096에 의해 데이터가 잘 못 출력 될 수 있습니다.


odbc.defaultlrl = 65536으로 변경하게 되면 64KByte까지는 정상적으로 데이터가 출력됨을 확인 할 수 있습니다.


일반적으로 php.ini는 /etc 밑에 있으나, 이는 설정에 따라 달라 질 수 있습니다.

#### 07-05. Spring+iBatis 트랜잭션 관리 방법


개요
방법
상세 설명

공통 적용사항
1-1. DataSourceTransactionManager 를 직접사용하는 경우
1-2. TransactionTemplate 를 사용하는 경우
2-1. <tx:advice> 태그를 이용한 방법
2-2. TransactionProxyFactoryBean 태그를 이용한 방법
2-3 @Transactional 어노테이션을 이용한 방법
참고

샘플 코드


개요


Spring+iBatis 트랜잭션 관리 방법에 대해 설명합니다.


방법


1. BMT(Bean Managed Transaction), 명시적 트랜잭션 관리(소스에서 트랜잭션 처리를 고려하는 방법)


1-1. DataSourceTransactionManager 를 직접사용하는 경우
1-2. TransactionTemplate 를 사용하는 경우


2. CMT(Container Managed Transaction), 선언적 트랜잭션 관리(설정화일을 이용하고, 소스에서는 트랜잭션 처리를 위한 고려를 줄이는 방법)


2-1. <tx:advice> 태그를 이용한 방법
2-2. TransactionProxyFactoryBean 태그를 이용한 방법
2-3 @Transactional 어노테이션을 이용한 방법


상세 설명


공통 적용사항






1-1. DataSourceTransactionManager 를 직접사용하는 경우


설정 파일 : 추가적으로 설정할 것이 없습니다.
소스 상에서 직접 commit, rollback 처리를 해아합니다.
트랜잭션으로 처리를 해주기 위해서는 setAutoCommit(false)를 호출해야 합니다.
주의할점은, blob select시에는 필히 setAutoCommit(false)를 호출해 주어야 한다는 것입니다.


1-2. TransactionTemplate 를 사용하는 경우


설정 파일


<bean id="transactionTemplate"
class="org.springframework.transaction.support.TransactionTemplate">
<property name="transactionManager"><ref local="transactionManager"/></property>
</bean>


<bean id="xxxService" class="…">

<property name="transactionTemplate"><ref local=" transactionTemplate"/></property>
</bean>


소스 상에서 transactionTemplate.execute(), doInTransaction() 등의 함수를 이용하여야 합니다.
주의할 점은 blob select시에 기존 오라클에서는 트랜잭션 처리를 해주지 않았겠지만 알티베이스로 사용시에는 꼭, 소스상에서
transactionTemplate.execute(), doInTransaction() 등의 함수를 이용하여 트랜잭션 처리를 해주어야 한다는 점입니다.


2-1. <tx:advice> 태그를 이용한 방법


설정 파일


<bean id="sqlMapClient" class="org.springframework.orm.ibatis.SqlMapClientFactoryBean">
<property name="configLocation"><value>sqlmap.xml</value></property>
<property name="dataSource"><ref bean="dataSource" /></property>
<property name="lobHandler"><ref bean="defaultLobHandler"/></property>
<property name="transactionConfigProperties">

<props>
<prop key="DefaultAutoCommit">false</prop>
<prop key="SetAutoCommitAllowed">true</prop>
</props>
</property>
</bean>
<tx:advice id="txAdvice" transaction-manager="transactionManager">

<tx:attributes>

<!-- all methods starting with 'get' are read-only -->
<tx:method name="get*" read-only="true" rollback-for="Exception"/>
<!-- other methods use the default transaction settings (see below) -->
<tx:method name="*" propagation=”REQUIRED”/>
</tx:attributes>
</tx:advice>


소스 상에는 트랜잭션 관련 코드 필요 없습니다.


2-2. TransactionProxyFactoryBean 태그를 이용한 방법


설정 파일


<bean id="sqlMapClient" class="org.springframework.orm.ibatis.SqlMapClientFactoryBean">
<property name="configLocation"><value>sqlmap.xml</value></property>
<property name="dataSource"><ref bean="dataSource" /></property>
<property name="lobHandler"><ref bean="defaultLobHandler"/></property>
<property name="transactionConfigProperties">

<props>
<prop key="DefaultAutoCommit">false</prop>
<prop key="SetAutoCommitAllowed">true</prop>
</props>
</property>
</bean>
<bean id="txProxyTemplate" abstract="true"
class="org.springframework.transaction.interceptor.TransactionProxyFactoryBean">
<property name="transactionManager">
<ref local="transactionManager"></ref>
</property>
<property name="transactionAttributes">

<props>
<prop key="insert*">PROPAGATION_REQUIRED</prop>
<prop key="update*">PROPAGATION_REQUIRED</prop>
<prop key="delete*">PROPAGATION_REQUIRED</prop>
<prop key="save*">PROPAGATION_REQUIRED</prop>
<prop key="*">PROPAGATION_SUPPORTS</prop>
</props>
</property>
</bean>


소스 상에는 트랜잭션 관련 코드 필요 없습니다.


2-3 @Transactional 어노테이션을 이용한 방법


설정 파일


참고



<bean id="sqlMapClient" class="org.springframework.orm.ibatis.SqlMapClientFactoryBean">
<property name="configLocation"><value>sqlmap.xml</value></property>
<property name="dataSource"><ref bean="dataSource" /></property>
<property name="lobHandler"><ref bean="defaultLobHandler"/></property>
<property name="transactionConfigProperties">

<props>
<prop key="DefaultAutoCommit">false</prop>
<prop key="SetAutoCommitAllowed">true</prop>
</props>
</property>
</bean>
<tx:annotation-driven transaction-manager="transactionManager"/>


소스 상에서 트랜잭션이 필요한 클래스는 @Transactional(propagation=Propagation.REQUIRED) 표기가 필요합니다.


표준프레임워크에서 안내하는 AltibaseClobStringTypeHandler 를 적용하면 CLOB 이 0 byte 인 경우에 오류가 발생할 수 있습니다.
이 경우는 TypeHandler 를 사용하지 않고 어노테이션 추가하여 정상적으로 조회 되는 것을 확인할 수 있습니다.



샘플 코드


LOB 데이터 처리하는 샘플 코드입니다.


LobSpringIbatisSample.zip

### 08. 모니터링

#### 08-01. Altibase에서 수행된 쿼리 로그 남기는 방법(altiProfile)은?


개요
프로파일링 관련 프로퍼티
프로파일링 시작 및 중지 방법
결과 분석 방법
주의사항


개요


Altibase 서버 내에서 수행되는 작업과 서버의 상태 정보를 기록할 수 있다.


Altibase Property 항목에 의해 설정/해제함으로써 가능하며, SQL문 외에 수행시간, 색인/디스크 접근 정보, PLAN 정보, 세션 정보 그리고


Altibase 시스템 정보도 함께 수집 가능합니다.


본 문서에서는 Altibase 프로파일링 및 결과 확인 방법에 대해 설명합니다.


프로파일링 관련 프로퍼티






|값|이름|설명|
|---|---|---|
|0||기록하지 않음 (기본값)|
|1|[STATEMENT]|SQL 문이 실행될 때마다 실행된 SQL문, 실행시간, 실행정보, 색인 및 디스크 접근 정보<br>출력.<br>단, 실행시간이 제대로 출력되게 하려면 TIMED_STATISTICS 프로퍼티를 1로 설정해야<br>한다.|
|2|[BIND]|prepare된 SQL문이 실행될 때마다 Bind Parameter 값 출력 (변수값 바인딩 정보가 있는<br>경우에 한함.)|
|4|[PLAN]|SQL문이 실행될 때마다 실행계획 출력|
|8|[SESSION<br>STAT]|3초마다 세션 정보 출력(V$SESSTAT 정보)|
|16|[SYSTEM<br>STAT]|3초마다 시스템 정보 출력(V$SYSSTAT 정보)|
|32|[MEMORY<br>STAT]|3초마다 메모리 정보 출력(V$MEMSTAT 정보)|



|Property Name|설명|
|---|---|
|QUERY_PROF_FLAG|서버의 상태 및 작업 내용을 수집 기록하기 위한 레벨을 설정<br>값<br>이름<br>설명<br>0<br> <br>기록하지 않음 (기본값)<br>1<br>[STATEMENT]<br>SQL 문이 실행될 때마다 실행된 SQL문, 실행시간, 실행정보, 색인 및 디스크 접근 정보<br>출력.<br>단, 실행시간이 제대로 출력되게 하려면 TIMED_STATISTICS 프로퍼티를 1로 설정해야<br>한다.<br>2<br>[BIND]<br>prepare된 SQL문이 실행될 때마다 Bind Parameter 값 출력 (변수값 바인딩 정보가 있는<br>경우에 한함.)<br>4<br>[PLAN]<br>SQL문이 실행될 때마다 실행계획 출력<br>8<br>[SESSION<br>STAT]<br>3초마다 세션 정보 출력(V$SESSTAT 정보)<br>16<br>[SYSTEM<br>STAT]<br>3초마다 시스템 정보 출력(V$SYSSTAT 정보)<br>32<br>[MEMORY<br>STAT]<br>3초마다 메모리 정보 출력(V$MEMSTAT 정보)<br>QUERY_PROF_FLAG 값의 조합으로 다양한 서버의 상태 정보 및 작업 내용을 수집할 수 있다.<br>예를 들어, 7(1 + 2 + 4)로 설정하면 매 SQL문 실행시 Statement 및 수행시간, Bind 되는 변수 값, SQL 수행에<br>대한 Plan 정보가 출력됩니다.<br>또한 63(1 + 2 + 4 + 8 + 16 + 32)으로 설정하면 출력 가능한 모든 정보가 출력되는데, 매 SQL문 실행시 마다<br>[STATEMENT] [BIND] [PLAN] 순서로 SQL문 실행정보가 출력되며<br>[SESSION STAT] [SYSTEM STAT] [MEMORY STAT] 시스템 정보는 3초마다 Altibase 상태 정보가 출력됩니다.|
|QUERY_PROF_LOG_DIR|Altibase에서 수행된 작업과 서버의 상태 정보가 저장될 디렉토리 경로<br>기본값 : $ALTIBASE_HOME/trc<br>Altibase 운영 중 ALTER SYSTEM 문을 이용하여 변경 가능합니다.|


프로파일링 시작 및 중지 방법


프로파일링 시작
다음 명령어 수행 후부터 실행되는 모든 SQL문에 대한 정보를 로그파일에 기록합니다.





TIMED_STATISTICS : 상세한 수행 시간을 측정하기 위하여 설정하여야 합니다.


value : 프로파일링 프로퍼티 QUERY_PROF_FLAG 설명을 참고합니다.


프로파일링 중지
프로파일링을 중지하려면 다음 명령어를 수행합니다.


결과 분석 방법


프로파일링을 시작하면 QUERY_PROF_LOG_DIR 프로퍼티에 설정된 디렉토리에 alti#시간-#번호.prof 형식으로 로그파일이 생성됩니다. (기본
설정은 $ALTIBASE_HOME/trc/alti#시간-#번호.prof 형식으로 생성 됨)


로그파일은 이진형태이므로 altiProfile 명령어를 이용하여 텍스트 파일로 변환해야 하며 방법은 아래와 같습니다.





로그파일 변환결과가 stdout으로 출력되므로 위 예제와 같이 파일로 저장하는 것을 권장합니다.


다음은 변환된 결과 내용에 대한 설명입니다.


QUERY_PROF_FLAG = 1 로 설정한 경우






QUERY_PROF_FLAG = 3 로 설정한 경우 ( QUERY_PROF_FLAG 1+2 )
Statement, prepare된 SQL문에 바인드 되는 변수값을 출력 합니다.


QUERY_PROF_FLAG = 7 로 설정한 경우 ( QUERY_PROF_FLAG 1+2+4 )
Statement. Bind 변수 값, SQL문의 실행을 위해 생성되는 실행계획 정보를 출력합니다.





QUERY_PROF_FLAG = 15 로 설정한 경우 ( QUERY_PROF_FLAG 1+2+4+8 )
현재 서버에 생성된 모든 세션에 대해, 아래와 같이 세션정보가 기록되며 select * from v$sesstat order by sid, seqnum 실행결과와
동일합니다.







예제


[SESSION STAT] 2025/07/16 10:05:23 (1)

logon current               =     1
logon cumulative             =     1
data page read              =     0
data page write              =     0
data page gets              =     0
data page fix               =     0
data page create             =     0
undo page read              =     0
undo page write              =     0
undo page gets              =     0
undo page fix               =     0
undo page create             =     0

base time in second            =     0

query timeout               =     0

ddl timeout                =     0

idle timeout               =     0

fetch timeout               =     0


utrans timeout              =     0

session terminated            =     0

ddl sync timeout             =     0

statement rebuild count          =     0

unique violation count          =     0
update retry count            =     0
delete retry count            =     0
lock row retry count           =     0

session commit              =     0

session rollback             =     0

fetch success count            =     0

fetch failure count            =     0

execute success count           =     5

execute success count : insert      =     0

execute success count : update      =     0

execute success count : delete      =     0

execute success count : select      =     0

rep_execute success count : insert    =     0
rep_execute success count : update    =     1
rep_execute success count : delete    =     0

execute failure count           =     0

prepare success count           =     4
prepare failure count           =     0

rebuild count               =     0

write redo log count           =     1
write redo log bytes           =    272

read socket count             =     6

write socket count            =     7

byte received via inet          =    677
byte sent via inet            =    620
byte received via unix domain       =     0
byte sent via unix domain         =     0
semop count for receiving via ipc     =     0
semop count for sending via ipc      =     0
memory table cursor full scan count    =     0
memory table cursor index scan count   =     1
memory table cursor GRID scan count    =     0

disk table cursor full scan count     =     0

disk table cursor index scan count    =     0

disk table cursor GRID scan count     =     0

lock acquired count            =     3

lock released count            =     0

service thread created count       =     0

memory table access count         =     1
missing ppco x-trylatch count       =     0

read IB count               =     0

write IB count              =     0

byte received via IB           =     0
byte sent via IB             =     0
elapsed time: query parse         =    407
elapsed time: query validate       =     0
elapsed time: query optimize       =     0
elapsed time: query execute        =  66497143
elapsed time: query fetch         =     0
elapsed time: soft prepare        =    155
elapsed time: analyze values in DML(disk) =     0
elapsed time: record lock validation in DML(disk) =     0
elapsed time: allocate data slot in DML(disk) =     0
elapsed time: write undo record in DML(disk) =     0


elapsed time: allocate tss in dml(disk)  =     0
elapsed time: allocate undopage in dml(disk) =     0
elapsed time: index operation in dml(disk) =     0
elapsed time: create page(disk)      =     0
elapsed time: get page(disk)       =     0
elapsed time: fix page(disk)       =     0
elapsed time: logical aging by tx in dml(disk) =     0
elapsed time: phyical aging by tx in dml(disk) =     0
elapsed time: replace(plan cache)     =     0
elapsed time: victim free in replace(plan cache) =     0
elapsed time: hard rebuild        =     0
elapsed time: soft rebuild        =     0
elapsed time: add hard-prepared plan to plan cache =     0
elapsed time: add hard-rebuild plan to plan cache =     0
elapsed time: search time for parent PCO =     42
elapsed time: creation time for parent PCO =     0
elapsed time: search time for child PCO  =     0
elapsed time: creation time for child PCO =     0
elapsed time: validation time for child PCO =     23
elapsed time: creation time for new child PCO by rebuild at execution  =     0
elapsed time: creation time for new child PCO by rebuild at soft prepare =     0
elapsed time: hard prepare time      =    510
elapsed time: matching time for child PCO =     33
elapsed time: waiting time for hard prepare =     0
elapsed time: moving time from cold region to hot region. =     0
elapsed time: waiting time for parent PCO when choosing plan cache replacement victim. =     0
elapsed time: privilege checking time during soft prepare. =     9
elapsed time: copying logs to replication log buffer (sender side) =     0
elapsed time: sender(s) waiting for new logs =     0
elapsed time: sender(s) reading logs from replication log buffer =     0
elapsed time: sender(s) reading logs from log file(s) =     0
elapsed time: sender(s) checking whether logs are useful =     0
elapsed time: sender(s) analyzing logs  =     0
elapsed time: sender(s) sending xlogs to receiver(s) =     0
elapsed time: sender(s) receiving ACK from receiver(s) =     0
elapsed time: sender(s) setting ACKed value =     0
elapsed time: receiver(s) receiving xlogs from sender(s) =     0
elapsed time: receiver(s) performing endian conversion =     0
elapsed time: receiver(s) beginning transaction(s) =     0
elapsed time: receiver(s) committing transaction(s) =     0
elapsed time: receiver(s) aborting transaction(s) =     0
elapsed time: receiver(s) opening table cursor(s) =     0
elapsed time: receiver(s) closing table cursor(s) =     0
elapsed time: receiver(s) inserting rows =     0
elapsed time: receiver(s) updating rows  =     0
elapsed time: receiver(s) deleting rows  =     0
elapsed time: receiver(s) opening lob cursor(s) =     0
elapsed time: receiver(s) preparing to write LOB(s) =     0
elapsed time: receiver(s) writing LOB piece(s) =     0
elapsed time: receiver(s) finish writing LOBs =     0
elapsed time: receiver(s) closing LOB cursor(s) =     0
elapsed time: receiver(s) comparing images to check for conflicts =     0
elapsed time: receiver(s) sending ACK   =     0


elapsed time: receiver(s) trim LOB(s)   =     0
elapsed time: task schedule        =     0

max   time: task schedule        =     0


QUERY_PROF_FLAG = 31 로 설정한 경우 ( QUERY_PROF_FLAG 1+2+4+8+16 )
Altibase 시스템의 전반적인 내용을 출력하며 select * from v$sysstat order by seqnum 실행 결과와 동일합니다.


예제


[SYSTEM STAT] 2025/07/16 10:15:26 (0)

logon current               =     1
logon cumulative             =     12
data page read              =     4
data page write              =     0
data page gets              =   13390
data page fix               =    735
data page create             =   27754
undo page read              =     0
undo page write              =     0
undo page gets              =     0
undo page fix               =     0
undo page create             =     0

base time in second            = 1752628526

query timeout               =     0

ddl timeout                =     0

idle timeout               =     0

fetch timeout               =     0

utrans timeout              =     2

session terminated            =     0

ddl sync timeout             =     0

statement rebuild count          =     0

unique violation count          =     0
update retry count            =     0
delete retry count            =     0
lock row retry count           =     0

session commit              =     85

session rollback             =     11

fetch success count            =     57

fetch failure count            =     0

execute success count           =    158

execute success count : insert      =     0

execute success count : update      =     0

execute success count : delete      =     0

execute success count : select      =     57

rep_execute success count : insert    =     0
rep_execute success count : update    =     20
rep_execute success count : delete    =     0

execute failure count           =     12

prepare success count           =    135
prepare failure count           =     23

rebuild count               =     0

write redo log count           =   31862
write redo log bytes           =  4552687

read socket count             =    230

write socket count            =    596


byte received via inet          =   95951
byte sent via inet            =   173741
byte received via unix domain       =    140
byte sent via unix domain         =    9237
semop count for receiving via ipc     =     0
semop count for sending via ipc      =     0
memory table cursor full scan count    =    439
memory table cursor index scan count   =    8337
memory table cursor GRID scan count    =     0

disk table cursor full scan count     =     18

disk table cursor index scan count    =     0

disk table cursor GRID scan count     =     0

lock acquired count            =    8436

lock released count            =    2489

service thread created count       =     25

memory table access count         =   13918
missing ppco x-trylatch count       =     0

read IB count               =     0

write IB count              =     0

byte received via IB           =     0
byte sent via IB             =     0
elapsed time: query parse         =   19280
elapsed time: query validate       =   11934
elapsed time: query optimize       =    5714
elapsed time: query execute        = 3199359716
elapsed time: query fetch         =    4968
elapsed time: soft prepare        =    4675
elapsed time: analyze values in DML(disk) =     0
elapsed time: record lock validation in DML(disk) =     0
elapsed time: allocate data slot in DML(disk) =     0
elapsed time: write undo record in DML(disk) =     0
elapsed time: allocate tss in dml(disk)  =     0
elapsed time: allocate undopage in dml(disk) =     0
elapsed time: index operation in dml(disk) =     0
elapsed time: create page(disk)      =     0
elapsed time: get page(disk)       =     0
elapsed time: fix page(disk)       =     0
elapsed time: logical aging by tx in dml(disk) =     0
elapsed time: phyical aging by tx in dml(disk) =     0
elapsed time: replace(plan cache)     =     0
elapsed time: victim free in replace(plan cache) =     0
elapsed time: hard rebuild        =     0
elapsed time: soft rebuild        =     0
elapsed time: add hard-prepared plan to plan cache =     71
elapsed time: add hard-rebuild plan to plan cache =     0
elapsed time: search time for parent PCO =    451
elapsed time: creation time for parent PCO =    279
elapsed time: search time for child PCO  =     0
elapsed time: creation time for child PCO =     34
elapsed time: validation time for child PCO =    2247
elapsed time: creation time for new child PCO by rebuild at execution  =     0
elapsed time: creation time for new child PCO by rebuild at soft prepare =     0
elapsed time: hard prepare time      =   39568
elapsed time: matching time for child PCO =    400
elapsed time: waiting time for hard prepare =     0
elapsed time: moving time from cold region to hot region. =     0
elapsed time: waiting time for parent PCO when choosing plan cache replacement victim. =     0
elapsed time: privilege checking time during soft prepare. =    219
elapsed time: copying logs to replication log buffer (sender side) =     0


elapsed time: sender(s) waiting for new logs =     0
elapsed time: sender(s) reading logs from replication log buffer =     0
elapsed time: sender(s) reading logs from log file(s) =     0
elapsed time: sender(s) checking whether logs are useful =     0
elapsed time: sender(s) analyzing logs  =     0
elapsed time: sender(s) sending xlogs to receiver(s) =     0
elapsed time: sender(s) receiving ACK from receiver(s) =     0
elapsed time: sender(s) setting ACKed value =     0
elapsed time: receiver(s) receiving xlogs from sender(s) =     0
elapsed time: receiver(s) performing endian conversion =     0
elapsed time: receiver(s) beginning transaction(s) =     0
elapsed time: receiver(s) committing transaction(s) =     0
elapsed time: receiver(s) aborting transaction(s) =     0
elapsed time: receiver(s) opening table cursor(s) =     0
elapsed time: receiver(s) closing table cursor(s) =     0
elapsed time: receiver(s) inserting rows =     0
elapsed time: receiver(s) updating rows  =     0
elapsed time: receiver(s) deleting rows  =     0
elapsed time: receiver(s) opening lob cursor(s) =     0
elapsed time: receiver(s) preparing to write LOB(s) =     0
elapsed time: receiver(s) writing LOB piece(s) =     0
elapsed time: receiver(s) finish writing LOBs =     0
elapsed time: receiver(s) closing LOB cursor(s) =     0
elapsed time: receiver(s) comparing images to check for conflicts =     0
elapsed time: receiver(s) sending ACK   =     0


elapsed time: receiver(s) trim LOB(s)   =     0
elapsed time: task schedule        =     0

max   time: task schedule        =     0


QUERY_PROF_FLAG = 63 로 설정한 경우 ( QUERY_PROF_FLAG 1+2+4+8+16+32 )
해당 시점에서 Altibase 모듈별 메모리 사용량을 출력하며 select * from v$memstat order by seqnum 실행 결과와 동일합니다.







예제


[MEMORY STAT] 2025/07/16 10:25:59
Main_Module_DirectAttach : (0/ 0/ 0)
Main_Module_Channel : (0/ 0/ 0)
Main_Module_CDBC_MAIN : (0/ 0/ 0)
Main_Module_CDBC_QP : (0/ 0/ 0)
Main_Module_CDBC_STATE_MEMPOOL : (0/ 0/ 0)
Main_Module_CDBC_CURSORDATA_MEMPOOL : (0/ 0/ 0)
Main_Module_CDBC_CONDITIONBUF_MEMPOOL : (0/ 0/ 0)
Main_Module_Distributed : (0/ 0/ 0)
Main_Module_Thread : (0/ 0/ 0)
Main_Module_Queue : (0/ 0/ 0)
Main_Module_Utility : (0/ 0/ 0)
SQL_Plan_Cache_Control : (0/ 0/ 0)
GIS_DataType : (0/ 0/ 0)
GIS_Disk_Index : (0/ 0/ 0)
GIS_Function : (0/ 0/ 0)
GIS_TEMP_MEMORY : (0/ 0/ 0)
Query_Common : (0/ 0/ 0)
Query_Meta : (0/ 0/ 0)
Query_DML : (0/ 0/ 0)
Query_Sequence : (0/ 0/ 0)
Query_PSM_Concurrent_Execute : (0/ 0/ 0)
Replication_Common : (0/ 0/ 0)
Replication_Control : (0/ 0/ 0)
Replication_Data : (0/ 0/ 0)
Replication_Met : (0/ 0/ 0)
Replication_Network : (0/ 0/ 0)
Replication_Recovery : (0/ 0/ 0)
Replication_Storage : (0/ 0/ 0)
Replication_Executor : (0/ 0/ 0)
Replication_Sender : (0/ 0/ 0)
Replication_Receiver : (0/ 0/ 0)
Replication_Sync : (0/ 0/ 0)
Replication_Module_Property : (0/ 0/ 0)
Query_PSM_Node : (0/ 0/ 0)
Query_PSM_Execute : (0/ 0/ 0)
Query_Prepare : (0/ 0/ 0)
Query_PSM_Varray : (0/ 0/ 0)
Query_Execute : (0/ 0/ 0)
Query_Binding : (0/ 0/ 0)
Query_Transaction : (0/ 0/ 0)


Query_Conversion : (0/ 0/ 0)
Query_Execute_Cache : (0/ 0/ 0)
Query_Result_Cache : (0/ 0/ 0)
Query_PSM_Internal_Execute : (0/ 0/ 0)
Mathematics : (0/ 0/ 0)
Storage_Disk_Buffer : (0/ 0/ 0)
Storage_Disk_Collection : (0/ 0/ 0)
Storage_Disk_Datafile : (0/ 0/ 0)
Storage_Disk_SecondaryBuffer : (0/ 0/ 0)
Storage_Tablespace : (0/ 0/ 0)
Storage_DataPort : (0/ 0/ 0)
Storage_Disk_Index : (0/ 0/ 0)
Storage_Disk_Page : (0/ 0/ 0)
Storage_Disk_Recovery : (0/ 0/ 0)
Storage_Global_Memory_Manager : (0/ 0/ 0)
Storage_Memory_Ager : (0/ 0/ 0)
Storage_Memory_Logical_Ager : (0/ 0/ 0)
Storage_Memory_Collection : (0/ 0/ 0)
Storage_Memory_Interface : (0/ 0/ 0)
Storage_Memory_Locking : (0/ 0/ 0)
Storage_Memory_Manager : (0/ 0/ 0)
Storage_Memory_Index : (0/ 0/ 0)
Fixed_Table : (0/ 0/ 0)
Storage_Memory_Page : (0/ 0/ 0)
Storage_Memory_Recovery : (0/ 0/ 0)
Storage_Memory_Recovery_Chkpt_Thread : (0/ 0/ 0)
Storage_Memory_Recovery_LFG_Thread : (0/ 0/ 0)
Storage_Memory_Recovery_Archive_Thread : (0/ 0/ 0)
Storage_Memory_Utility : (0/ 0/ 0)
Storage_Memory_Transaction : (0/ 0/ 0)
Volatile_Log_Buffer : (0/ 0/ 0)
Volatile_Memory_Manager : (0/ 0/ 0)
Volatile_Memory_Page : (0/ 0/ 0)
Temp_Memory : (0/ 0/ 0)
Transaction_Table : (0/ 0/ 0)
Legacy_Transaction_Manager : (0/ 0/ 0)
Transaction_OID_List : (0/ 0/ 0)
Transaction_Private_Buffer : (0/ 0/ 0)
Transaction_Segment_Table : (0/ 0/ 0)
Transaction_DiskPage_Touched_List : (0/ 0/ 0)
Transaction_Table_Info : (0/ 0/ 0)
Index_Memory : (0/ 0/ 0)
LOG_Memory : (0/ 0/ 0)
InMemoryRecovery_Memory : (0/ 0/ 0)
CatalogCache_Memory : (0/ 0/ 0)
OS_Independent : (0/ 0/ 0)
Utility_Module : (0/ 0/ 0)
Async_IO_Manager : (0/ 0/ 0)
Mutex : (0/ 0/ 0)
Clock_Manager : (0/ 0/ 0)
Timer_Manager : (0/ 0/ 0)
Profile_Manager : (0/ 0/ 0)
Socket_Manager : (0/ 0/ 0)
External_Procedure : (0/ 0/ 0)
External_Procedure_Agent : (0/ 0/ 0)
Audit_Manager : (0/ 0/ 0)
Altiwrap : (0/ 0/ 0)
Process_ThreadInfo : (0/ 0/ 0)
CM_Buffer : (0/ 0/ 0)


CM_NetworkInterface : (0/ 0/ 0)
CM_Multiplexing : (0/ 0/ 0)
CM_DataType : (0/ 0/ 0)
CM_Interface : (0/ 0/ 0)
Database_Link : (0/ 0/ 0)
Dynamic Module Loader : (0/ 0/ 0)
Tablespace_Free_Extent_Pool : (0/ 0/ 0)
Condition_Variable : (0/ 0/ 0)
WATCHDOG : (0/ 0/ 0)
Latch : (0/ 0/ 0)
Thread_Stack : (0/ 0/ 0)
Remote_Call_Server : (0/ 0/ 0)
Remote_Call_Client : (0/ 0/ 0)
Query_Common_Remote_Call : (0/ 0/ 0)
IDU_MEM_OTHER : (0/ 0/ 0)
MMAP : (0/ 0/ 0)


SYSTEM : (0/ 0/ 0)
Shared Meta : (0/ 0/ 0)
RESERVED : (0/ 0/ 0)


altiProfile의 -stat 옵션을 사용하여 실행된 SQL문의 통계정보를 출력할 수 있으며 -stat 옵션으로는 query / session 으로 구분됩니다.
이 정보는 튜닝 대상의 SQL문을 찾는데 도움이 됩니다.
session 옵션은 query 옵션을 실행한 통계 정보에 SESSION ID가 추가됩니다.
stat 옵션으로 수행된 통계정보 파일은 .txt, .csv 2개의 파일 형식을 생성됩니다.





예제


$ altiProfile -stat query alti-1752630730-0.prof
### Processing [alti-1752630730-0.prof]...
100% [====================]
### Writing CSV File [alti-prof-stat-1752631027.csv]...
### Writing TEXT File [alti-prof-stat-1752631027.txt]...
### Successfully done.
$ ls -la ==> 통계 정보 생성 File

-rw-rw-rw- 1 alti0 alti0   747 Jul 16 10:57 alti-prof-stat-1752631027.csv
-rw-rw-rw- 1 alti0 alti0  1241 Jul 16 10:57 alti-prof-stat-1752631027.txt
$ cat alti-prof-stat-1752631027.txt

COUNT   AVG     TOTAL     MIN     MAX  SUCCESS FAIL  QUERY

===================================================================================

========================

4   3.959910  15.839640   0.002116   7.665345   4   0  EXEC PROC1(3001, '01046585724', 1)

7   2.262010  15.834073   0.000159   7.663861   7   0  UPDATE EMPLOYEES SET DNO = ?,

EMP_TEL = ? WHERE ENO = ?

9   0.620658   5.585918   0.000081   5.584472   9   0  UPDATE EMPLOYEES SET DNO = :v1,

EMP_TEL = :v2 WHERE ENO = :v3

10   0.000352   0.003520   0.000088   0.002201  10   0  select * from SYS.CUSTOMERS

8   0.000364   0.002911   0.000149   0.001264   8   0  commit

1   0.002279   0.002279   0.002279   0.002279   1   0  ALTER SYSTEM SET QUERY_PROF_FLAG

= 7

12   0.000153   0.001840   0.000072   0.000454  12   0  select * from SYS.DEPARTMENTS

6   0.000249   0.001492   0.000059   0.000880   6   0  select * from ALTITEST.ORDERS

===================================================================================

========================

[TOTAL] Count(Query): 57 Avg(Time): 0.653889 Sum(Time): 37.2717

$ altiProfile -stat session alti-1752630730-0.prof
### Processing [alti-1752630730-0.prof]...
100% [====================]
### Writing CSV File [alti-prof-stat-1752631158.csv]...
### Writing TEXT File [alti-prof-stat-1752631158.txt]...
### Successfully done.
$ ls -la

-rw-rw-rw- 1 alti0 alti0  2319 Jul 16 10:59 alti-prof-stat-1752631158.txt
-rw-rw-rw- 1 alti0 alti0  1393 Jul 16 10:59 alti-prof-stat-1752631158.csv
$ cat alti-prof-stat-1752631158.txt

SESSION  COUNT   AVG     TOTAL     MIN     MAX  SUCCESS FAIL  QUERY


===================================================================================

========================

1    5   1.117055   5.585273   0.000166   5.584472   5   0  UPDATE EMPLOYEES SET DNO =

:v1, EMP_TEL = :v2 WHERE ENO = :v3
1    2   2.114851   4.229702   0.002116   4.227586   2   0  EXEC PROC1(3001, '01046585724',
1)

1    3   1.408920   4.226760   0.000335   4.225859   3   0  UPDATE EMPLOYEES SET DNO = ?,

EMP_TEL = ? WHERE ENO = ?

1    5   0.000562   0.002812   0.000112   0.002201   5   0  select * from SYS.CUSTOMERS

1    1   0.002279   0.002279   0.002279   0.002279   1   0  ALTER SYSTEM SET

QUERY_PROF_FLAG = 7

1    6   0.000367   0.002201   0.000149   0.001264   6   0  commit

1    4   0.000332   0.001328   0.000115   0.000880   4   0  select * from ALTITEST.ORDERS

1    6   0.000175   0.001049   0.000082   0.000454   6   0  select * from SYS.DEPARTMENTS

===================================================================================

========================

[SUB-TOTAL] Count(Query): 32 Avg(Time): 0.439106 Sum(Time): 14.0514
2    2   5.804969  11.609938   3.944593   7.665345   2   0  EXEC PROC1(3001, '01046585724',
1)

2    4   2.901828  11.607313   0.000159   7.663861   4   0  UPDATE EMPLOYEES SET DNO =

?, EMP_TEL = ? WHERE ENO = ?

2    6   0.000132   0.000791   0.000072   0.000229   6   0  select * from SYS.DEPARTMENTS

2    2   0.000355   0.000710   0.000261   0.000449   2   0  commit

2    5   0.000142   0.000708   0.000088   0.000186   5   0  select * from SYS.CUSTOMERS

2    4   0.000161   0.000645   0.000081   0.000305   4   0  UPDATE EMPLOYEES SET DNO =

:v1, EMP_TEL = :v2 WHERE ENO = :v3

2    2   0.000082   0.000164   0.000059   0.000105   2   0  select * from ALTITEST.ORDERS


===================================================================================

========================

[SUB-TOTAL] Count(Query): 25 Avg(Time): 0.928811 Sum(Time): 23.2203


주의사항


프로파일링을 활성화 할 경우, Altibase 서버 내에서 실행되는 모든 SQL문에 대해 수행정보를 로그파일에 기록하며, 설정에 따라 3초 주기로
Altibase 상태를 프로파일링하므로, Altibase 성능에 영향을 줄 뿐만 아니라 시스템에도 부하를 줄 수 있습니다.


또한 프로파일링에 의한 로그 기록으로 디스크 사용량이 높아져 디스크 풀 발생 가능성도 있습니다.


따라서 기본적으로 운영 서버에서 프로파일링을 활성화하는 것은 권장하지 않습니다.


테스트, 성능 분석 및 튜닝 시에 단시간 사용하기를 권장하며, 프로파일링 할 때 반드시 디스크 사용량을 함께 모니터링하여 적절히 중지하시기
바랍니다.

#### 08-02. Lock 관련 정보 조회


개요
적용버전
조회 방법


개요


트랜잭션 lock으로 인한 성능저하를 모니터링할수 있습니다.


적용버전


ALTIBASE HDB 6.3.1 을 기준으로 작성 되었습니다.
ALTIBASE HDB 5, ALTIBASE HDB 6 모두 사용할 수 있으나 일부 모니터링 항목에서 결과 오류가 발생할 수 있습니다.
필요한 경우 http://support.altibase.com/kr/ 또는 이 페이지에 댓글로 요청 글 남겨주세요.

## 조회 방법


먼저 알티베이스의 lock 정보는 크게 두 performance view 를 조회해 보시면 됩니다.


v$lock, v$lock_statement 입니다.


먼저 v$lock 에서는 어떤 테이블에 대해 어떤 종류의 lock 이 걸려 있는지를 조회해 볼 수 있는데
select문의경우 IS_LOCK, insert나 update, delete 등의 변경 작업 이라면 IX_LOCK 이 걸리게 됩니다.
이 뷰와 system_.sys_tables_ 메타 테이블을 조인 해서 테이블 이름과 lock 정보를 조회해 보실 수 있습니다.


select table_name, lock_desc
from system_.sys_tables_ a, v$lock b

where a.table_oid = b.table_oid;


또한 v$lock_statement 를 통해 lock 을 잡고 있는 쿼리를 확인할 수 있습니다.
v$lock 의 trans_id 와 v$lock_statement 의 tx_id 를 조인해서 lock 을 잡고 있는 쿼리를 조회해 보실 수 있습니다.


select query
from v$lock a, v$lock_statement b

where a.trans_id = b.tx_id;


여러 조인을 이용해서 현재 lock 을 잡고 있는 쿼리의 session id 를 확인 하실 수 있습니다.
desc v$lock;
desc v$lock_statement; 를 통해 어떤 컬럼을 가지고 있는지 확인해 보시기 바랍니다.
이렇게 얻어낸 session_id 를 가지고 해당 session 을 kill 할 수도 있습니다.


ALTER DATABASE database_name SESSION CLOSE session_id;


위 명령은 sysdba 로 들어가셔서 수행할 수 있습니다.


connect sys/manager as sysdba;


++ Lock wait query


select query, tx_id
from v$statement
where tx_id in ( select trans_id from v$lock_wait);


++ v$lock_wait 뷰를 기반으로 waiting 하는 tx_id, lock 부여 시간, 관련 REDO logfile 위치 등 조회.


select

id tx_id,

lw.wait_for_trans_id wait_tx_id,
decode (status,0,'BEGIN',
1,'PRECOMMIT',
2,'COMMIT_IN_MEMORY',
3,'COMMIT',
4,'ABORT',
5,'BLOCKED',
6,'END', 'UNKNOWN') status,
decode(update_status,0,'READ',1,'UPDATING','UNKNOWN') TTYPE,
decode(first_undo_next_lsn_fileno,-1,'READ_TRN',first_undo_next_lsn_fileno) firstlog,
base_time - decode(first_update_time, 0, base_time, first_update_time) time

from

v$transaction tx
left outer join v$lock_wait lw

on tx.id = lw.trans_id,
(select base_time from v$sessionmgr) base

where status != 6

order by time desc;


++ lock을 잡고 있는 client_pid 및 session_id를 확인


select a.table_oid, a.lock_desc, c.client_pid, b.session_id
from v$lock a, v$statement b, v$session c

where a.trans_id = b.tx_id

and b.session_id = c.id;

#### 08-03. OS별 시스템 정보 보기


개요


각 OS(LINUX, SUN, IBM, HP ) 별 시스템 정보 및 현황을 확인할 수 있는 명령어들입니다.


여기서는 각 OS 별 CPU, MEMORY, SYSTEM, DISK, NETWORK 의
사용량을 확인 하는 방법을 간단하게 기술합니다.


버전


ALTIBASE HDB 모든 버전


LINUX


1. CPU
CPU 정보 : cat /proc/cpuinfo


CPU 사용량 : top





2. MEMORY
Memory 정보 : cat /proc/meminfo


Process Memory : ps -elf, ps -aux


$$> ps -elf

F S UID    PID PPID C PRI NI ADDR SZ WCHAN STIME TTY     TIME CMD
4 S root     1   0 0 76  0 - 1193 109952 Dec17 ?    00:00:01 init [5]
1 S root     2   1 0 -40  - -   0 migrat Dec17 ?    00:00:00 [migration/0]
1 S root     3   1 0 94 19 -   0 ksofti Dec17 ?    00:00:00 [ksoftirqd/0]
1 S root     4   1 0 -40  - -   0 migrat Dec17 ?    00:00:00 [migration/1]
1 S root     5   1 0 94 19 -   0 ksofti Dec17 ?    00:00:00 [ksoftirqd/1]
1 S root     6   1 0 -40  - -   0 migrat Dec17 ?    00:00:01 [migration/2]
1 S root     7   1 0 94 19 -   0 ksofti Dec17 ?    00:00:00 [ksoftirqd/2]


SZ : approximate amount of swap space that would be required if the process were to dirty all
writable pages and then be swapped out. This number is very rough!


$> ps aux

USER    PID %CPU %MEM  VSZ RSS TTY   STAT START  TIME COMMAND
root     1 0.0 0.0 4772 564 ?    S  Dec17  0:01 init [5]
root     2 0.0 0.0   0  0 ?    S  Dec17  0:00 [migration/0]
root     3 0.0 0.0   0  0 ?    SN  Dec17  0:00 [ksoftirqd/0]
root     4 0.0 0.0   0  0 ?    S  Dec17  0:00 [migration/1]
root     5 0.0 0.0   0  0 ?    SN  Dec17  0:00 [ksoftirqd/1]
root     6 0.0 0.0   0  0 ?    S  Dec17  0:01 [migration/2]

RSS : resident set size, the non-swapped physical memory that a task has used (in kiloBytes).
VSZ : virtual memory usage of entire process.


System Memory : free, vmstat


$> free

total    used    free   shared  buffers   cached

Mem:   16423300  15075408  1347892     0   227604  8810452

-/+ buffers/cache:  6037352  10385948

Swap:   32764556   928104  31836452


$> vmstat 1 5

procs -----------memory---------- ---swap-- -----io---- --system-
----cpu---r b  swpd  free  buff cache  si  so  bi  bo  in  cs us sy id wa

0 0 928104 1348148 227612 8810444  0  0   3  26  1   5 1 0 99 0

0 0 928104 1348148 227612 8810444  0  0   0  156 1047 34212 0 0 100 0

0 0 928104 1348148 227612 8810444  0  0   0  60 1012 34163 2 0 98 0

0 0 928104 1348148 227612 8810444  0  0   0   0 1024 34142 0 0 100 0

0 0 928104 1348148 227612 8810444  0  0   0  20 1014 34142 0 0 100 0

swpd: the amount of virtual memory used.
free: the amount of idle memory.
buff: the amount of memory used as buffers.
cache: the amount of memory used as cache.


3. SYSTEM
LOG : /var/log/messages


LOG /var/log/messages





OS Version : uname -a





Patch No : rpm -qa | grep -i kernel





4. DISK : iostat 3 1


$> iostat 3 1

avg-cpu: %user  %nice  %sys %iowait  %idle

0.70  0.00  0.09  0.03  99.18

Device:      tps  Blk_read/s  Blk_wrtn/s  Blk_read  Blk_wrtn

sda        1.08     4.70    19.46  4417994  18312224

sda1       0.56     0.43    10.33   403074  9717672

sda2       0.01     0.13     2.05   120828  1930960

sda3       0.24     2.02     2.75  1905302  2586944

sda4       0.00     0.00     0.00     2     0

sda5       0.00     0.00     0.00    3646     16

sda6       0.27     2.11     4.33  1984142  4076632

sdb        4.36    43.73    401.08  41142700 377382768

sdb1       2.27    29.27    297.20  27540998 279645952

sdb2       2.09    14.45    103.87  13600254  97736816

tps
Indicate the number of transfers per second that were issued to the device. A transfer is
an I/O request to
the device. Multiple logical requests can be combined into a single I/O request to the

device. A transfer is

of indeterminate size.

Blk_read/s

Indicate  the amount of data read from the drive expressed in a number of blocks per

second. Blocks are

equivalent to sectors with 2.4 kernels and newer and therefore have a size of 512 bytes.
With older kernels,

a block is of indeterminate size.

Blk_wrtn/s

Indicate the amount of data written to the drive expressed in a number of blocks per

second.

Blk_read

The total number of blocks read.

Blk_wrtn

The total number of blocks written.


5. NETWORK : netstat, ifconfig


$> netstat
Active Internet connections (w/o servers)

Proto Recv-Q Send-Q Local Address        Foreign Address       State
tcp    0   0 localhost:50273       localhost:20416       ESTABLISHED
tcp    0   0 localhost:20416       localhost:50273       ESTABLISHED
tcp    0   0 localhost:ftp-data     192.168.6.18:62643     TIME_WAIT
tcp    0   0 localhost:ftp-data     192.168.6.18:62640     TIME_WAIT


Proto
The protocol (tcp, udp, raw) used by the socket.

Recv-Q

The count of bytes not copied by the user program connected to this socket.

Send-Q

The count of bytes not acknowledged by the remote host.

Local Address
Address and port number of the local end of the socket. Unless the --numeric (-n) option
is specified, the socket
address is resolved to its canonical host name (FQDN), and the port number is translated
into the corresponding

service name.

Foreign Address
Address and port number of the remote end of the socket. Analogous to "Local Address."

State

The state of the socket. Since there are no states in raw mode and usually no states used in
UDP, this column may

be left blank.





SUN SYSTEM


1. CPU
CPU 정보 : psrinfo -v


CPU 사용량 : top





2. MEMORY
Memory 정보 : prtconf


$> prtconf


System Configuration: Sun Microsystems i86pc
Memory size: 2048 Megabytes
System Peripherals (Software Nodes):


i86pc
scsi_vhci, instance #0
isa, instance #0
motherboard (driver not attached)
i8042, instance #0
mouse, instance #0
keyboard, instance #0
asy, instance #0 (driver not attached)
fdc, instance #0
fd, instance #0
fd, instance #1 (driver not attached)
pci, instance #0
pci1022,7460, instance #0
pci17c2,10, instance #0
pci17c2,10, instance #1
display, instance #0
pci1022,7468 (driver not attached)
pci-ide, instance #0
ide, instance #0 (driver not attached)
ide, instance #1
sd, instance #0
st, instance #7 (driver not attached)
pci1022,7450, instance #1
pci17c2,10, instance #0
pci17c2,10, instance #1
pci17c2,10, instance #0
sd, instance #1
sd, instance #2 (driver not attached)
sd, instance #3 (driver not attached)
sd, instance #4 (driver not attached)
sd, instance #5 (driver not attached)
sd, instance #6 (driver not attached)
sd, instance #7 (driver not attached)
sd, instance #8 (driver not attached)
sd, instance #9 (driver not attached)
sd, instance #10 (driver not attached)
sd, instance #11 (driver not attached)
sd, instance #12 (driver not attached)
sd, instance #13 (driver not attached)
sd, instance #14 (driver not attached)
sd, instance #15 (driver not attached)
sd, instance #16 (driver not attached)
st, instance #0 (driver not attached)
st, instance #1 (driver not attached)
st, instance #2 (driver not attached)
st, instance #3 (driver not attached)
st, instance #4 (driver not attached)
st, instance #5 (driver not attached)
st, instance #6 (driver not attached)
pci17c2,10 (driver not attached)
pci1022,7450 (driver not attached)
pci17c2,10 (driver not attached)
pci1022,1100 (driver not attached)
pci1022,1101 (driver not attached)
pci1022,1102 (driver not attached)
pci1022,1103 (driver not attached)
pci1022,1100 (driver not attached)
pci1022,1101 (driver not attached)
pci1022,1102 (driver not attached)
pci1022,1103 (driver not attached)
pseudo, instance #0
options, instance #0
xsvc, instance #0
objmgr, instance #0 (driver not attached)
used-resources (driver not attached)
cpus (driver not attached)
cpu, instance #0 (driver not attached)
cpu instance #1 (driver not attached)


Process Memory : ps -elf


$> ps -elf

F S   UID  PID PPID  C PRI NI   ADDR   SZ  WCHAN  STIME TTY     TIME CMD

1 T   root   0   0  0  0 SY    ?   0      Sep 28 ?      1:48 sched
0 S   root   1   0  0 40 20    ?  501    ?  Sep 28 ?      0:53 /sbin/init
1 S   root   2   0  0  0 SY    ?   0    ?  Sep 28 ?      0:01 pageout
1 S   root   3   0  0  0 SY    ?   0    ?  Sep 28 ?    2647:44 fsflush
0 S   root  116   1  0 40 20    ?  634    ?  Sep 28 ?      0:00 /usr/lib/picl/picld


SZ : The total size of the process in virtual memory,  including all mapped files and
devices, in pages.


System Memory : prtmem, vmstat






3. SYSTEM
LOG : /var/adm/messages, dmesg





OS Version : uname -a


$> uname -a
SunOS v20z 5 10 Generic Patch i86pc i386 i86pc


Patch No : showrev -a


4. DISK : iostat 3 1


$> iostat 3 5

tty    sd0      sd1      nfs1      cpu
tin tout kps tps serv kps tps serv kps tps serv  us sy wt id

0  1  0  0  0  2  0  15  0  0  0  0 0 0 99

0  65  0  0  0  0  0  0  0  0  0  0 0 0 99

0  22  0  0  0  0  0  0  0  0  0  0 0 0 99

0  22  0  0  0  0  0  0  0  0  0  1 0 0 99

0  22  0  0  0  1  0  0  0  0  0  0 1 0 98


5. NETWORK : netstat, ifconfig


$> ifconfig -a
lo0: flags=2001000849<UP,LOOPBACK,RUNNING,MULTICAST,IPv4,VIRTUAL> mtu 8232 index

1

inet xxx.xxx.xxx.xxx netmask ff000000

bge0: flags=1000843<UP,BROADCAST,RUNNING,MULTICAST,IPv4> mtu 1500 index 2

inet xxx.xxx.xxx.xxx netmask ffffff00 broadcast 192.168.1.255


AIX


1. CPU

CPU 정보 : sar -P ALL 1 3





CPU 사용량 : topas


Topas Monitor for host:  aix53-t9       EVENTS/QUEUES  FILE/TTY

Tue Dec 22 13:54:01 2015  Interval: 2     Cswitch  40310 Readch  31765

Syscall  32027 Writech 712.6K

CPU User% Kern% Wait% Idle%         Reads    20 Rawin     0

ALL  20.6  16.3  1.4  61.7         Writes    7 Ttyout   825
Forks     0 Igets     0

Network KBPS  I-Pack O-Pack  KB-In KB-Out Execs     0 Namei    204

en0    1.0   3.5   1.5   0.2   0.9 Runqueue  0.0 Dirblk    0
lo0    0.0   0.0   0.0   0.0   0.0 Waitqueue  0.0
Disk  Busy%   KBPS   TPS KB-Read KB-Writ PAGING      MEMORY

hdisk1  5.0   2.8K  10.1   0.0   2.8K Faults    89 Real,MB  7936

hdisk0  0.0   0.0   0.0   0.0   0.0 Steals    0 % Comp   90.0
PgspIn    0 % Noncomp  9.9
Name      PID CPU% PgSp Owner      PgspOut    0 % Client  9.9
altibase   700654  6.1 663.3 hanulcat    PageIn    0
altibase   737490  5.8 377.4 durusari    PageOut   177 PAGING SPACE
java     786586  5.1 57.7 wsalti3     Sios    177 Size,MB  16896
altibase   508126  4.1 780.6 jeehb              % Used   61.1
altibase   549024  3.1 396.0 dongjun     NFS (calls/sec) % Free   39.9

altibase   794804  3.1 1808.6 wsalti3    ServerV2    0

altibase   577762  2.3 448.4 high7777    ClientV2    0  Press:
altibase   696356  1.4 1486.1 hyun1     ServerV3    0  "h" for help
altibase   282794  1.0 411.8 newhyuki    ClientV3    0  "q" to quit

altibase   532612  1.0 276.5 cheol

altibase   467112  0.9 411.2 gom
altibase   553176  0.8 258.0 taeseong

altibase   417846  0.8 1022.7 durusari

altibase   372888  0.7 309.9 hyundong
altibase   438348  0.6 284.7 eheejung
topas    389362  0.3  1.4 wsalti3
java     159854  0.1 20.3 root  i
getty    319520  0.0  0.5 root

ksh     802892  0.0  0.5 wsalti3

telnetd   675996  0.0  0.6 root


2. MEMORY
Memory 정보 : lsconf


Process Memory : ps aux


$> ps aux

USER    PID %CPU %MEM  SZ RSS  TTY STAT  STIME TIME COMMAND

root    8196 19.5 0.0 384 384   - A   Apr 14 141722:02 wait
root   53274 18.6 0.0 384 384   - A   Apr 14 134782:46 wait
hanulcat 700654 3.5 1.0 686892 42184   - A   Oct 23 6062:39 /home/ts2_team/h
durusari 737490 2.8 5.0 394120 389104   - A   Dec 16 500:43 /home/ts2_team/d
wsalti3 786586 1.9 0.0 59168 16052   - A   Sep 17 5331:05 /usr/java5/bin/j


SZ: The virtual size of the data section of the process (in 1KB units).
RSS : The real-memory (resident set) size of the process (in 1KB units)


System Memory : vmstat


$>vmstat 1

System configuration: lcpu=2 mem=7936MB
kthr  memory       page       faults    cpu

----- ----------- ------------------------ ------------ ----------
r b  avm  fre re pi po fr  sr cy in  sy cs us sy id wa

15 0 4186138 3380  0  0  0  0  0  0 13 31222 40260 21 16 63 0

3 0 4186139 3379  0  0  0  0  0  0  7 30787 39611 21 16 63 0

1 0 4186140 3378  0  0  0  0  0  0  9 30636 39011 22 16 62 0

13 0 4186136 3382  0  0  0  0  0  0 17 31331 40298 21 16 62 0

16 0 4186136 3382  0  0  0  0  0  0  7 31859 40632 22 16 62 0


Memory: information about the usage of virtual and real memory. Virtual pages are considered
active if they have been accessed.
A page is 4096 bytes.
avm : Active virtual pages.

fre : Size of the free list.


3. SYSTEM

LOG : errpt -a





OS Version : oslevel -r


$> oslevel -r

5300-08


Patch No : lslpp -L|grep motif


4. DISK : iostat 3 1


$>iostat 3 1

System configuration: lcpu=2 drives=2 paths=2 vdisks=0
tty:   tin     tout  avg-cpu: % user % sys % idle % iowait

0.0     19.3        20.4 16.3  60.5   2.8

Disks:    % tm_act   Kbps   tps  Kb_read  Kb_wrtn

hdisk1      6.0   1893.3   13.3     0   5680

hdisk0      5.3   24.0    6.0     0    72


% tm_act : Indicates the percentage of time the physical disk/tape was active
(bandwidth utilization for the drive).
Kbps : Indicates the amount of data transferred (read or written) to the drive in KB per second.
tps : Indicates the number of transfers per second that were issued to the physical disk/tape. A
transfer is an I/O request to the
physical disk/tape. Multiple logical requests can be combined into a single I/O request to

the disk.

A transfer is of indeterminate size.

Kb_read : The total number of KB read.

Kb_wrtn : The total number of KB written.


5. NETWORK : netstat, ifconfig


$> netstat

Active Internet connections
Proto Recv-Q Send-Q Local Address     Foreign Address    (state)
tcp4    0   2 81.altibase.loca.telne 192.168.6.26.pscupd  ESTABLISHED
tcp4    0   0 localhost.29945    localhost.38131    ESTABLISHED
tcp4    0   0 localhost.38131    localhost.29945    ESTABLISHED
tcp4    0   0 81.altibase.loca.42129 as48-x64.altibas.39945 TIME_WAIT
tcp4    0   0 81.altibase.loca.42130 as48-x64.altibas.39945 TIME_WAIT


HP-UX


1. CPU
CPU 정보 : glance(a)


$> glance (glance 수행 후 a 키)

GlancePlus C.04.55.00     15:57:51  rx6600   ia64  Current Avg High

-----------------------------------------------------------------------
-------
CPU Util  SUU                        | 6%  6%  6%
Disk Util  F     FV V                  | 29%  29%  29%
Mem Util  S   SU         U             | 57%  57%  57%
Swap Util  UUR   R                     | 20%  20%  20%

-----------------------------------------------------------------------
-------
CPU BY PROCESSOR          Users=  6
CPU State   Util  LoadAvg(1/5/15 min)  CSwitch  Last Pid

-----------------------------------------------------------------------
-------
3 Enable   12.1   0.1/ 0.0/ 0.0    175    25741
4 Enable   0.0   0.1/ 0.1/ 0.1    167    18641
6 Enable   0.0   0.1/ 0.1/ 0.1    158    1769
7 Enable   5.2   0.0/ 0.0/ 0.0    263    1979
8 Enable   53.4   0.1/ 0.1/ 0.1    155    1979
10 Enable   0.9   0.1/ 0.1/ 0.1    163    1979
13 Enable   0.9   0.0/ 0.0/ 0.0    244    18641
5 Enable   0.0   0.0/ 0.0/ 0.0    219    1979
2 Enable   1.7   0.1/ 0.1/ 0.1    204    1979
9 Enable   13.8   0.0/ 0.0/ 0.0    261    25223
0 Enable   0.0   0.1/ 0.1/ 0.1    160    18641


CPU 사용량 : top, glance


$> top
System: rx6600                    Tue Dec 22 16:00:58 2015
Load averages: 0.08, 0.07, 0.07
430 processes: 362 sleeping, 68 running
Cpu states:

CPU  LOAD  USER  NICE  SYS  IDLE BLOCK SWAIT  INTR  SSYS

0  0.15  3.8%  0.0%  1.4% 94.9%  0.0%  0.0%  0.0%  0.0%

1  0.03  1.8%  0.0%  1.6% 96.6%  0.0%  0.0%  0.0%  0.0%

2  0.08  8.9%  0.0%  2.0% 89.1%  0.0%  0.0%  0.0%  0.0%

3  0.04  9.5%  0.0%  1.2% 89.3%  0.0%  0.0%  0.0%  0.0%

4  0.06  7.9%  0.0%  0.4% 91.7%  0.0%  0.0%  0.0%  0.0%

5  0.04  4.5%  0.0%  1.0% 94.5%  0.0%  0.0%  0.0%  0.0%

6  0.13 14.8%  0.0%  0.0% 85.2%  0.0%  0.0%  0.0%  0.0%

7  0.04  3.8%  0.0%  1.4% 94.9%  0.0%  0.0%  0.0%  0.0%

8  0.09 14.8%  0.0%  2.0% 83.2%  0.0%  0.0%  0.0%  0.0%

9  0.06  8.3%  0.0%  1.0% 90.7%  0.0%  0.0%  0.0%  0.0%

10  0.14 11.9%  0.0%  1.4% 86.8%  0.0%  0.0%  0.0%  0.0%

11  0.06  5.1%  0.0%  0.8% 94.1%  0.0%  0.0%  0.0%  0.0%

12  0.09 17.2%  0.0%  2.2% 80.6%  0.0%  0.0%  0.0%  0.0%

13  0.04  7.7%  0.0%  0.4% 91.9%  0.0%  0.0%  0.0%  0.0%

14  0.14 11.7%  0.0%  2.6% 85.8%  0.0%  0.0%  0.0%  0.0%

15  0.06  3.2%  0.0%  1.0% 95.9%  0.0%  0.0%  0.0%  0.0%

---  ---- ----- ----- ----- ----- ----- ----- ----- ----
avg  0.08  8.3%  0.0%  1.4% 90.3%  0.0%  0.0%  0.0%  0.0%


2. MEMORY
Memory 정보 : machinfo






Process Memory : ps -elf


$> ps -elf

F S   UID  PID PPID C PRI NI       ADDR  SZ      WCHAN  STIME TTY    TIME

COMD
1003 S   root   0   0 0 127 20 e000000100769810  0 e000000100000004 12▒▒ 21 ?

0:25 swapper
541 R   root   1   0 0 152 20 e00000010415e380 481        - 12▒▒ 21 ?     0:04

init
1003 S   root  13   0 0 152 20 e0000001301a4080  0 e0000001301a30a0 12▒▒ 21 ?

0:00 net_str_cached
1003 S   root  12   0 0 152 20 e000000131004d00  0 e0000001301a3080 12▒▒ 21 ?

0:00 net_str_cached
1003 R   root  11   0 0 152 20 e000000131004a00  0        - 12▒▒ 21 ?     0:03

escsid


sz : The size in physical pages of the core image of the process, including text, data, and stack

space.
Physical page size is defined by _SC_PAGE_SIZE in the header file <unistd.h>


System Memory : vmstat


$> vmstat 1 5

procs      memory          page               faults    cpu
r   b   w   avm  free  re  at  pi  po  fr  de  sr   in   sy  cs us sy id

1   0   0 5614057 2977741  0  0   0  0   0  0   2  4639 11383 3479  0 0

100

1   0   0 5614057 2977750  0  0   1  0   0  0   0  4648 10931 3786  0 0

100

1   0   0 5614057 2977633  0  0   0  0   0  0   0  4645 10537 3788  0 0

100

1   0   0 5614057 2977633  0  0   0  0   0  0   0  4642 10072 3783  0 0

100

1   0   0 5614057 2977633  0  0   0  0   0  0   0  4638  9594 3776  0 0 100


memory : Information about the usage of virtual and real memory.
Virtual pages are considered active if they belong to processes
that are running or have run in the last 20 seconds.
avm : Active virtual pages

free : Size of the free list


3. SYSTEM
LOG : /var/adm/syslog/syslog.log


OS Version : uname -a


$> uname -a
HP-UX rx6600 B 11 31 U ia64 0436529332 unlimited-user license


3. DISK : iostat 3 1


4. NETWORK : netstat -nr


$> netstat -nr

IPv4 Routing tables:
Destination      Gateway      Flags  Refs Interface Pmtu

127.0.0.1       127.0.0.1     UH  0  lo0    32808

192.168.1.28     192.168.1.28    UH  0  lan0   32808

192.168.1.0      192.168.1.28    U   2  lan0    1500

127.0.0.0       127.0.0.1     U   0  lo0    32808

default        192.168.1.1    UG  0  lan0    1500

IPv6 Routing tables:
Destination/Prefix     Gateway         Flags Refs Interface Pmtu
::1/128           ::1           UH  0  lo0   32808
fe80::217:a4ff:fe51:7308/128

fe80::217:a4ff:fe51:7308 UH  0  lan0   32808

fe80::/10          fe80::217:a4ff:fe51:7308 U   2  lan0   1500

default           fe80::221:d8ff:feb6:123f UG  0  lan0     0

#### 08-04. Windows 용 모니터링 툴


개요
적용 버전
모니터링 배치 프로그램
설정

접속 정보 확인
모니터링 항목 추가
모니터링 주기
지난 로그 삭제 기능
altimon.vbs 파일 수정
실행

포그라운드(foreground)로 실행하는 방법
백그라운드(background)로 실행하는 방법
종료

포그라운드로 실행했을 경우
백그라운드로 실행했을 경우

로그


개요


Windows 용 모니터링 툴입니다.


적용 버전


이 툴은 ALTIBASE HDB 6.3.1 을 기준으로 작성 되었습니다.
ALTIBASE HDB 5, ALTIBASE HDB 6 모두 사용할 수 있으나 일부 모니터링 항목에서 결과 오류가 발생할 수 있습니다.
필요한 경우 http://support.altibase.com/kr/ 또는 이 페이지에 댓글로 요청 글 남겨주세요.


모니터링 배치 프로그램


아래 압축 파일을 다운로드 하여 임의 폴더에 올려놓은 다음 압축을 풀어주세요.


altimon_for_windows.zip


압축을풀면두개의폴더와두개의파일이있습니다


압축을 풀면 두 개의 폴더와 두 개의 파일이 있습니다.


altimon.bat : 모니터링을 위한 배치 프로그램
altimon.vbs : 배치 프로그램을 백그라운드로 실행 시키기 위한 VB 파일
ALTIMON_SCRIPT 폴더 : 모니터링 쿼리를 담고 있는 .sql 파일들이 존재
ALTIMON_LOG 폴더 : 로그 파일 저장


설정


접속 정보 확인


altimon.bat 파일에서 ALTIBASE HDB 서버 접속 명령어 부분을 환경에 맞게 변경합니다.


set ISQL="%ALTIBASE_HOME%\bin\isql.exe" -s localhost -u sys -p manager -silent


모니터링 항목 추가


기본 모니터링 항목 외에 추가하고 싶은 항목이 있다면 ALTIMON_SCRIPT 폴더에 있는 all.sql 파일에 모니터링 쿼리를 추가하세요.


모니터링 쿼리에서 SELECT 절의 첫 번째 컬럼은 sysdate 를, 두 번째 컬럼은 _MON_ 로 시작하는 식별자를 넣어주세요.





모니터링 주기


altimon.bat 에서 마지막 부분, 아래 명령어에서 -n 뒤에 숫자를 변경해주세요. 이 숫자는 모니터링 주기를 의미 합니다.
초 단위로 환경에 맞게 수정합니다.


ping -n 60 127.0.0.1 > nul


예) 5분으로 설정할 경우 -n 60 을 -n 300 으로


지난 로그 삭제 기능


altimon.bat 파일 아래 부분에 forfiles 로 시작하는 명령어가 있습니다.
이 명령어에서 /D -30 옵션이 30일 전 로그를 삭제하라는 의미이니, /D 옵션 뒤 숫자를 변경합니다.


forfiles /P . /M mon.log* /D -30 /C "cmd /c del @file"


altimon.vbs 파일 수정


위 파일들을 다운로드 후 모니터링 할 서버의 임의 폴더에 올려주세요.


그리고 altimon.vbs 파일에서 두 번째 라인의 경로를 환경에 맞게 수정해줍니다.


Set WshShell = CreateObject("WScript.Shell")
WshShell.Run chr(34) & "C:\Users\Altibase\Desktop\altimon.bat" & Chr(34), 0
Set WshShell = Nothing


실행


포그라운드(foreground)로 실행하는 방법


윈도우즈의 명령 프롬프트(실행 창) 을 실행합니다. altimon.bat 파일이 위치한 폴더로 이동하고 배치 프로그램을 실행합니다.









윈도우 탐색기에서 배치 프로그램(altimon.bat) 이 위치한 폴더로 이동하고 alti_mon.bat 파일을 더블 클릭해도 됩니다.


포그라운드로 배치 프로그램을 실행시키면, 실행 창에 아래와 같이 알림 메시지가 뜹니다.


포그라운드로 실행한 배치 프로그램은 열린 창을 닫으면 배치 프로그램이 종료됩니다.


백그라운드(background)로 실행하는 방법


첨부된 파일들을 같은 폴더에 넣고 도스 창을 열어 해당 폴더로 이동 후 아래 명령어 수행합니다.


C> alti_mon.vbs





백그라운드로 실행한 배치 프로그램은 열린 창을 닫아도 배치 프로그램이 종료되지 않습니다. 종료하려면 taskkill 명령어를 이용해야
합니다. 종료 부분을 참고하세요.


종료


포그라운드로 실행했을 경우


배치 프로그램(altimon.bat)을 실행 한 실행 창을 닫거나 Ctrl+c 를 누릅니다.


백그라운드로 실행했을 경우


윈도우즈의 명령 프롬프트(실행 창) 실행하고 아래 명령어 수행합니다.


C> taskkill /fi "windowtitle eq ALTIMON FOR WINDOWS"





로그


배치 프로그램을 수행하면 ALTIMON_LOG 라는 폴더 아래에 mon.log.YYYY-MM-DD 형태의 로그 파일이 생성됩니다.

#### 08-05. 디스크 테이블 및 인덱스 사용량


개요
참고


개요


버전 별 디스크 테이블 및 인덱스 사용량 조회 쿼리 정리합니다.


디스크 테이블의 사용량은 다음 두 가지 방법을 이용할 수 있는데 이 페이지에서는 v$segment(x$segment) 를 이용한 쿼리를 제공합니다.


v$segment : 테이블을 풀 스캔하면서 물리적인 페이지를 계산하는 방식
v$usage : 통계 정보를 이용한 샘플링 방식


참고


08-05-01. ALTIBASE HDB 4.3.9.x


개요
디스크 테이블 사용량 조회
디스크 인덱스 사용량 조회
참고 - 디스크 테이블 및 인덱스 수 확인 방법


개요


ALTIBASE HDB 4.3.9 버전의 디스크 테이블 및 인덱스 사용량 조회 쿼리입니다.


이 쿼리는 ALTIBASE HDB 5.1.1 에서도 사용할 수 있습니다.


디스크 테이블 사용량 조회


디스크 인덱스 사용량 조회


참고 - 디스크 테이블 및 인덱스 수 확인 방법


08-05-02. ALTIBASE HDB 5.1.5.x


개요
디스크 테이블
디스크 인덱스
참고 - 디스크 테이블 및 인덱스 수 확인 방법


개요


ALTIBASE HDB 5.1.5 버전 용 디스크 테이블 및 인덱스 사용량 조회 쿼리입니다.
ALTIBASE HDB 5 에서는 디스크 테이블의 구조 변경으로 테이블에 할당된 크기만 알 수 있고 실 사용량을 확인할 수 없습니다.
데이터가 DELETE 후 발생한 free 공간을 제외한 크기는 계산할 수 없음을 의미합니다.
ALTIBASE HDB 5.3.3.33, 5.3.5.15, 5.5.1.0.3 부터는 사용량을 구할 수 있게 개선되었습니다.


디스크 테이블


ALTIBASE HDB 5.1.5 디스크 테이블 사용량 조회 쿼리


set linesize 1024

set colsize 30

SELECT U.USER_NAME

USER_NAME

-- 데이터베이스 사용자
, DECODE(TBL.IS_PARTITIONED, 'T', 'PARTITIONED', 'F', 'NON-PARTITIONED')
PARTITIONED                    -- 파티션드 테이블이면 PARTITIONED,

논-파티션드 테이블이면 NON-PARTITIONED

, TBL.TABLE_NAME

TABLE_NAME

-- 테이블 이름
, DECODE(TBL.IS_PARTITIONED, 'T', TBL.PARTITION_NAME, 'F', '-')
PARTITIONED_TABLE                     -- 파티션드 테이블 이름

, TBS.NAME

TABLESPACE_NAME

-- 테이블스페이스
, TO_CHAR((D.MAX * TBS.PAGE_SIZE)/1024, '999,999,999')
'MAX(KB)'                              -- 테이블이 속한

테이블스페이스의 최대 크기
, TO_CHAR((TBS.EXTENT_PAGE_COUNT * TBS.PAGE_SIZE *
SEG.EXTENT_TOTAL_COUNT)/1024, '999,999,999') 'ALLOC(KB)'        -- 현재까지

할당받은 전체 크기
, TO_CHAR((((TBS.EXTENT_PAGE_COUNT * TBS.PAGE_SIZE *
SEG.EXTENT_TOTAL_COUNT)/(D.MAX*TBS.PAGE_SIZE))*100), '99.99') 'USAGE(%)' -
테이블스페이스 최대 크기 대비 사용률
FROM (SELECT TBL.USER_ID
, DECODE(TBL.IS_PARTITIONED, 'F', TBL.TABLE_OID, 'T', PT.PARTITION_OID)

TABLE_OID

, TBL.TABLE_NAME

, PT.PARTITION_NAME
, DECODE(TBL.IS_PARTITIONED, 'F', TBL.TBS_ID, 'T', PT.TBS_ID) TBS_ID

, TBL.IS_PARTITIONED

FROM SYSTEM_.SYS_TABLES_ TBL LEFT OUTER JOIN

SYSTEM_.SYS_TABLE_PARTITIONS_ PT ON TBL.TABLE_ID = PT.TABLE_ID
) TBL
, V$SEGMENT SEG

, SYSTEM_.SYS_USERS_ U
, V$TABLESPACES TBS
, (SELECT SPACEID
, SUM(DECODE(MAXSIZE, 0, CURRSIZE, MAXSIZE)) AS MAX
, DECODE(MAX(AUTOEXTEND),1,'ON','OFF') 'AUTOEXTEND'
FROM V$DATAFILES
GROUP BY SPACEID) D

WHERE 1=1

AND SEG.SEGMENT_TYPE = 'TABLE' /* 'TABLE' : 테이블, 'INDEX' : 인덱스 */

AND SEG.TABLE_OID = TBL.TABLE_OID

AND U.USER_ID = TBL.USER_ID

AND D.SPACEID = TBL.TBS_ID

AND TBS.ID = TBL.TBS_ID

ORDER BY USER_NAME, PARTITIONED, TABLE_NAME, PARTITIONED_TABLE

;


디스크 인덱스


ALTIBASE HDB 5.1.5 디스크 인덱스 사용량 조회 쿼리


set linesize 1024

set colsize 20

SELECT U.USER_NAME

USER_NAME

-- 데이터베이스 사용자

,

I_LIST.TABLE_NAME

-- 테이블 이름
, DECODE(I_LIST.PARTITION_NAME, NULL, 'NON-PARTITIONED',
I_LIST.PARTITION_NAME) PARTITIONED_NAME             -- 파티션드 테이블
이름, 논-파티션드 테이블이면 NON-PARTITIONED

, I_LIST.INDEX_NAME

INDEX_NAME

-- 인덱스 이름
, DECODE(I_LIST.INDEX_PARTITION_NAME, NULL, 'NON-PARTITIONED',
I_LIST.INDEX_PARTITION_NAME) PARTITIONED_INDEX       -- 파티션드 인덱스 이름

, TBS.NAME

TBS_NAME

-- 인덱스가 속한 테이블스페이스
, TO_CHAR((D.MAX * TBS.PAGE_SIZE)/1024, '999,999,999')
'MAX(KB)'                             -- 테이블스페이스의

최대 크기
, TO_CHAR((TBS.EXTENT_PAGE_COUNT * TBS.PAGE_SIZE *
SEG.EXTENT_TOTAL_COUNT)/1024, '999,999,999') 'ALLOC(KB)'        -- 인덱스에서

할당 받은 전체 크기
, TO_CHAR((((TBS.EXTENT_PAGE_COUNT * TBS.PAGE_SIZE *
SEG.EXTENT_TOTAL_COUNT)/(D.MAX*TBS.PAGE_SIZE))*100), '99.99') 'USAGE(%)'  -
테이블스페이스 최대 크기 대비 사용률
FROM (SELECT T.TABLE_NAME

, PT.PARTITION_NAME

, I.INDEX_NAME

, PI.INDEX_PARTITION_NAME
, DECODE(T.IS_PARTITIONED, 'F', I.TABLE_ID, 'T', PT.TABLE_ID) TABLE_ID
, DECODE(T.IS_PARTITIONED, 'F', T.TABLE_OID, 'T', PT.PARTITION_OID)

TABLE_OID
, DECODE(I.IS_PARTITIONED, 'F', I.TBS_ID, 'T', PI.TBS_ID) TBS_ID

, I.INDEX_ID

, T.USER_ID

FROM SYSTEM_.SYS_INDICES_ I LEFT OUTER JOIN

SYSTEM .SYS INDEX PARTITIONS PI ON PI.INDEX ID = I.INDEX ID LEFT OUTER JOIN


_ _ N _ N _ N N _ N _ N


SYSTEM_.SYS_TABLE_PARTITIONS_ PT ON PT.PARTITION_ID = PI.TABLE_PARTITION_ID LEFT
OUTER JOIN SYSTEM_.SYS_TABLES_ T ON T.TABLE_ID = I.TABLE_ID ) I_LIST
, V$SEGMENT SEG
, V$INDEX I
, V$TABLESPACES TBS

, SYSTEM_.SYS_USERS_ U
, (SELECT SPACEID
, SUM(DECODE(MAXSIZE, 0, CURRSIZE, MAXSIZE)) AS MAX
, DECODE(MAX(AUTOEXTEND),1,'ON','OFF') 'AUTOEXTEND'
FROM V$DATAFILES
GROUP BY SPACEID) D

WHERE 1=1

AND SEG.TABLE_OID = I.TABLE_OID

AND SEG.SEGMENT_PID = I.INDEX_SEG_PID

AND SEG.SPACE_ID = I_LIST.TBS_ID

AND I_LIST.INDEX_ID = I.INDEX_ID

AND I_LIST.TABLE_OID = I.TABLE_OID

AND I_LIST.TBS_ID = TBS.ID

AND D.SPACEID = I_LIST.TBS_ID

AND U.USER_ID = I_LIST.USER_ID


ORDER BY I_LIST.TABLE_NAME, I_LIST.INDEX_NAME, I_LIST.PARTITION_NAME,

I_LIST.INDEX_PARTITION_NAME

;





참고 - 디스크 테이블 및 인덱스 수 확인 방법


08-05-03. ALTIBASE HDB 5.3.x, 5.5.1, 6.1.1, 6.3.1


개요
버전
디스크 테이블 및 인덱스의 사용량을 확인하려면...
디스크 테이블
디스크 인덱스
참고 - 디스크 테이블 및 인덱스 수 확인 방법


개요


버전


본 페이지에 소개된 모니터링 쿼리는 BUG-31372 가 반영된 버전부터 사용 가능합니다.


ALTIBASE HDB 5.3.3.33

ALTIBASE HDB 5.3.5.15

ALTIBASE HDB 5.5.1.0.3

ALTIBASE HDB 6.1.1

ALTIBASE HDB 6.3.1


BUG-31372 에서 디스크 테이블의 실 사용량을 조회할 수 있게 X$SEGMENT의 TOTAL_USED_SIZE 칼럼이 추가되었습니다.


BUG-31372 가 변영되지 않은 ALTIBASE HDB 5.3.3, 5.3.5, 5.5.1 버전에서는 아래 쿼리 사용 시 에러가 발생할 수 있습니다.


디스크 테이블 및 인덱스의 사용량을 확인하려면...


ALTER TABLE table_name AGING, ALTER INDEX index_name AGING 명령을 수행해야 정확한 사용량을 구할 수 있습니다.
aging 되지 않은 공간은 used 로 계산하기 때문에 테이블에 delete 가 잦은 경우 aging 을 수행하지 않으면 실제 사용량보다 크게
산정될 수 있습니다.
ALTER TABLE table_name AGING, ALTER INDEX index_name AGING 명령 수행 중에는 테이블에 X LOCK 을 잡고 테이블을 풀
스캔하기 때문에 해당 테이블 및 인덱스에 대한 다른 작업이 대기하게 됩니다.
v$segment 의 TOTAL_USED_SIZE 는 휘발성 임시 데이터로 알티베이스 서버 재 시작 시 실 사용양이 아닌 테이블 및 인덱스의 총 할당
크기로 초기화 됩니다.
v$segment 조회 자체는 데이터베이스에 영향을 주지 않습니다.


디스크 테이블


DELETE 로 테이블의 데이터를 삭제하더라도 USED 는 줄어들지 않습니다.
DELETE 후 FREE PAGE 를 제외한 실제 USED 를 확인하려면 ALTER TABLE table_name AGING ; 을 수행해야 합니다.
ALTER TABLE ~ AGING ; 수행 중에는 테이블에 X락을 잡기 때문에 해당 테이블에 대한 다른 요청은 대기 상태가 되므로 수행 시 주의
해야 합니다.


디스크 인덱스


DELETE 로테이블의데이터를삭제하더라도인덱스의USED 는줄어들지않습니다.


DELETE 로 테이블의 데이터를 삭제하더라도 인덱스의 USED 는 줄어들지 않습니다.

DELETE 후 FREE PAGE 를 제외한 실제 USED 를 확인하려면 ALTER INDEX index_name AGING ; 을 수행해야 합니다.
ALTER INDEX ~ AGING 작업이 수행 중에는 테이블에 X락을 잡기 때문에 해당 테이블에 대한 다른 요청은 대기 상태가 되므로 수행 시
주의해야 합니다.


ALTIBASE HDB 5.3.x, 5.5.1, 6.1.1, 6.3.1 디스크 인덱스 사용량 조회 쿼리


-- 디스크 인덱스 사용량 컬럼 설명

-- USER_NAME : 데이터베이스 사용자

-- TABLE_NAME : 테이블 이름

-- PARTITIONED_NAME : 파티션드 테이블 이름, 논-파티션드 테이블이면

NON-PARTITIONED

-- INDEX_NAME : 인덱스 이름

-- PARTITIONED_INDEX : 파티션드 인덱스 이름

-- TBS_NAME : 인덱스가 속한 테이블스페이스
-- MAX(KB) : 테이블스페이스의 최대 크기
-- ALLOC(KB) : 할당 받은 전체 크기
-- USED(KB) : 할당 받은 공간 중 데이터가 포함된 크기
-- USAGE(%) : 테이블스페이스 최대 크기 대비 사용률

set linesize 1024

set colsize 20

SELECT U.USER_NAME USER_NAME


, I_LIST.TABLE_NAME


, DECODE(I_LIST.PARTITION_NAME, NULL, 'NON-PARTITIONED',
I_LIST.PARTITION_NAME) PARTITIONED_NAME

, I_LIST.INDEX_NAME INDEX_NAME


, DECODE(I_LIST.INDEX_PARTITION_NAME, NULL, 'NON-PARTITIONED',
I_LIST.INDEX_PARTITION_NAME) PARTITIONED_INDEX

, TBS.NAME TBS_NAME


, TO_CHAR((D.MAX * TBS.PAGE_SIZE)/1024, '999,999,999') 'MAX(KB)'


, TO_CHAR((TBS.EXTENT_PAGE_COUNT * TBS.PAGE_SIZE *
SEG.TOTAL_EXTENT_COUNT)/1024, '999,999,999') 'ALLOC(KB)'
, TO_CHAR(SEG.TOTAL_USED_SIZE/1024, '999,999,999,999') 'USED(KB)'


, TO_CHAR(((SEG.TOTAL_USED_SIZE/(D.MAX*TBS.PAGE_SIZE))*100), '99.99')
'USAGE(%)'
FROM (SELECT T.TABLE_NAME

, PT.PARTITION_NAME

, I.INDEX_NAME

, PI.INDEX_PARTITION_NAME
, DECODE(T.IS_PARTITIONED, 'F', I.TABLE_ID, 'T', PT.TABLE_ID) TABLE_ID
, DECODE(T.IS_PARTITIONED, 'F', T.TABLE_OID, 'T', PT.PARTITION_OID)

TABLE_OID
, DECODE(I.IS_PARTITIONED, 'F', I.TBS_ID, 'T', PI.TBS_ID) TBS_ID

, I.INDEX_ID

, T.USER_ID

FROM SYSTEM_.SYS_INDICES_ I LEFT OUTER JOIN

SYSTEM_.SYS_INDEX_PARTITIONS_ PI ON PI.INDEX_ID = I.INDEX_ID

LEFT OUTER JOIN SYSTEM_.SYS_TABLE_PARTITIONS_ PT ON

PT.PARTITION_ID = PI.TABLE_PARTITION_ID


LEFT OUTER JOIN SYSTEM_.SYS_TABLES_ T ON T.TABLE_ID
= I.TABLE_ID AND T.TABLE_TYPE = 'T') I_LIST
, X$SEGMENT SEG
, V$INDEX I
, V$TABLESPACES TBS

, SYSTEM_.SYS_USERS_ U
, (SELECT SPACEID
, SUM(DECODE(MAXSIZE, 0, CURRSIZE, MAXSIZE)) AS MAX
, DECODE(MAX(AUTOEXTEND),1,'ON','OFF') 'AUTOEXTEND'
FROM V$DATAFILES
GROUP BY SPACEID) D

WHERE 1=1

AND SEG.TABLE_OID = I.TABLE_OID

AND SEG.SEGMENT_PID = I.INDEX_SEG_PID

AND SEG.SPACE_ID = I_LIST.TBS_ID

AND I_LIST.INDEX_ID = I.INDEX_ID

AND I_LIST.TABLE_OID = I.TABLE_OID

AND I_LIST.TBS_ID = TBS.ID

AND D.SPACEID = I_LIST.TBS_ID

AND U.USER_ID = I_LIST.USER_ID


ORDER BY I_LIST.TABLE_NAME, I_LIST.INDEX_NAME, I_LIST.PARTITION_NAME,

I_LIST.INDEX_PARTITION_NAME

;





참고 - 디스크 테이블 및 인덱스 수 확인 방법


#### 08-06. 디스크 테이블스페이스 사용량

개요


개요


버전 별 디스크 테이블스페이스 사용량 조회 쿼리를 정리합니다.


08-06-01. ALTIBASE HDB 4.3.9


08-06-02. ALTIBASE HDB 5.1.5


개요


디스크 테이블스페이스 사용량 조회


개요


ALTIBASE HDB 5 에서는 디스크 테이블의 구조 변경으로 디스크 테이블스페이스의 사용량을 구할 수 없고 할당 크기만을 알 수
있습니다.
ALTIBASE HDB 5.3.3 부터는 사용량을 구할 수 있게 개선되었습니다. (언두 테이블스페이스 및 임시 테이블스페이스는 제외)


디스크 테이블스페이스 사용량 조회


08-06-03. ALTIBASE HDB 5.3.3, 5.3.5


개요
디스크 테이블스페이스 사용량 조회


개요


ALTIBASE HDB 5.3.3 버전부터는 X$SEGMENT의 TOTAL_USED_SIZE 칼럼 정보를 이용해서 테이블스페이스의 실 사용량을 확인할
수 있습니다.
X$SEGMENT의 TOTAL_USED_SIZE 칼럼은 BUG-31372 에서 추가되었습니다.
BUG-31372 가 반영된 버전은 아래와 같습니다.


ALTIBASE HDB 5.3.3.33

ALTIBASE HDB 5.3.5.15

ALTIBASE HDB 5.5.1.0.3
따라서 BUG-31372 가 변영되지 않은 ALTIBASE HDB 5.3.3, 5.3.5, 5.5.1 버전에서는 아래 쿼리 사용 시 에러가 발생할 수 있습니다.
이 버전에서는 언두 테이블스페이스와 임시 테이블스페이스의 실 사용량을 구할 수 없습니다.


디스크 테이블스페이스 사용량 조회


08-06-04. ALTIBASE HDB 5.5.1, 6.1.1, 6.3.1


개요
관련 버그

BUG-39985 V$DISK_UNDO_USAGE 계산 오류 수정


개요


ALTIBASE HDB 5.5.1 에서 V$DISK_UNDO_USAGE 가 추가되었습니다.
이 성능 뷰를 통해 언두 테이블스페이스의 사용량을 확인할 수 있습니다.

## 디스크 테이블스페이스 사용량 조회 쿼리


관련 버그


BUG-39985 V$DISK_UNDO_USAGE 계산 오류 수정


V$DISK_UNDO_USAGE 의 REUSABLE_EXT_CNT 컬럼은 언두 테이블스페이스 내의 재사용 가능한 크기를 의미합니다.
언두 테이블스페이스 풀 현상이 발생하였는데 REUSABLE_EXT_CNT 컬럼에서는 재사용 가능한 공간이 있다고 보여주는 오류가 있어서
개선되었습니다.
아래 버전부터 이 버그가 반영되어 있습니다.


ALTIBASE HDB 6.1.1.4.9
ALTIBASE HDB 6.3.1 은 아직 반영된 tag 가 안나왔음..

#### 08-07. 롤백(rollback) 중인 쿼리를 확인하는 방법


개요


버전


확인 방법


ALTIBASE HDB 5.1.5 이상 버전에서 모두 사용가능한 방법


ALTIBASE HDB 6.1.1.2.0 부터 변경된 확인 방법


개요


변경 트랜잭션이 수행 중일 때 해당 세션을 강제로 끊거나 세션 타임 아웃 설정에 의해 트랜잭션이 중단된 경우 해당 트랜잭션은
롤백(ROLLBACK)이 진행됩니다.


다음은 롤백 중인 쿼리를 확인하는 방법입니다.


버전


Altibase 5.1.5 이상


확인 방법


ALTIBASE HDB 5.1.5 이상 버전에서 모두 사용가능한 방법


아래 쿼리 수행 결과에서CURRENT_UNDO_NEXT_LSN_FILENO 컬럼과CURRENT_UNDO_NEXT_LSN_OFFSET 컬럼의 값이 점점 줄어들고
있다면 해당 트랜잭션이 롤백 중임을 알 수 있습니다.


롤백 작업은 변경 트랜잭션이 수행했던 작업을 취소하는 undo 작업을 수행합니다.


CURRENT_UNDO_NEXT_LSN으로 시작하는 컬럼은 이 undo 작업이 진행하면서 undo 할 다음 로그(logfile)를 가리키는 값을 의미합니다.


롤백 전에 수행된 변경 트랜잭션이 logfile 1 ~ logilfe 10 까지 기록되었다면 롤백 시 undo 는 logfile 10 부터 진행되기 때문에 CURRENT_UND

O_NEXT_LSN 으로 시작하는 컬럼의 값이 줄어든다는 것으로 롤백이 수행 중임을 알 수 있습니다.


SELECT tx.ID TX_ID,

tx.SESSION_ID,

tx.STATUS,
DECODE(tx.FIRST_UPDATE_TIME, 0, '0', TO_CHAR(TO_DATE('1970010109', 'YYYYMMDDHH') +
tx.FIRST_UPDATE_TIME / (60*60*24), 'MM/DD HH:MI:SS')) FIRST_UPDATE_TIME,
st.TOTAL_TIME/1000000 TOTAL,

tx.CURRENT_UNDO_NEXT_LSN_FILENO,

tx.CURRENT_UNDO_NEXT_LSN_OFFSET,
SUBSTR(QUERY, 1, 100) QUERY
FROM V$TRANSACTION tx,
V$STATEMENT st

WHERE tx.ID = st.TX_ID
AND tx.SESSION_ID <> SESSION_ID();


해당 쿼리가 수행한 시각은 FIRST_UPDATE_TIME
롤백 시작 시각은 FIRST_UPDATE_TIME + TOTAL


ALTIBASE HDB 6.1.1.2.0 부터 변경된 확인 방법


ALTIBASE HDB 6.1.1.2.0 버전부터 v$transaction 의 status 컬럼으로 롤백 중인 문장을 간단하게 확인할 수 있게 되었습니다.


select query from v$statement where session id in (select session id from v$transaction where status=4);


v$transaction 의 status 컬럼은 트랜잭션 상태를 나타나는 값으로 0 ~ 6 값을 가질 수 있으며 값의 의미는 아래와 같습니다.


0: BEGIN                : 트랜잭션 시작 됨
1: PRECOMMIT           : 사용 안함
2: COMMIT_IN_MEMORY  : 사용 안함
3: COMMIT              :트랜잭션 커밋 됨
4: ABORT               :롤백되어 abort 됨
5: BLOCKED             :Lock 또는 다른 트랜잭션을 위해 대기함
6: END                 :트랜잭션을 다 사용하여 Free된 상태

#### 08-08. 메모리 테이블 및 인덱스 사용량


개요
메모리테이블 데이타 사용량 조회쿼리
메모리테이블 인덱스 사용량 조회

메모리테이블 인덱스 정보 구하는 쿼리 ( HDB 4 ~ HDB 6 까지 모두 사용 가능 )
메모리 테이블 인덱스당 사용량 구하는 쿼리 ( HDB 5.x 이상부터 사용가능)
메모리 테이블당 총인덱스 사용량 구하는 쿼리 ( HDB 5.x 이상부터 사용가능 )
메모리테이블 인덱스당 크기 조회 쿼리( 6.x 용 )


개요


메모리 테이블의 데이타 사용량 과 인덱스 사용량을 조회하는 쿼리를 설명합니다.


메모리테이블 데이타 사용량 조회쿼리


다음의 쿼리는 HDB 4.3.9.x 부터 HDB 6.3.1.x 까지 모든 버전에서 사용할 수 있습니다.


set linesize 2048;

set colsize 30;

SELECT  a.user_name
,NVL(d.name,'SYS_TBS_MEMORY') AS 'TABLESPACE_NAME'

, b.table_name
, round((c.fixed_alloc_mem + c.var_alloc_mem)/(1024*1024),2) 'ALLOC(M)'
, round((c.fixed_used_mem + c.var_used_mem)/(1024*1024),2) 'USED(M)'
, round((c.fixed_used_mem + c.var_used_mem)/(c.fixed_alloc_mem +
c.var_alloc_mem)*100,2) 'EFFICIENCY(%)'

FROM  system_.sys_users_ a
, system_.sys_tables_ b
, v$memtbl_info c left outer join v$tablespaces d on c.tablespace_id = d.id
WHERE b.table_type = 'T'

and a.user_id = b.user_id

and b.table_oid = c.table_oid

order by 1,2,3, 4 desc ;





메모리테이블 인덱스 사용량 조회


메모리테이블의 인덱스 사용량은 쿼리로 직접 구할 수 없습니다  알티베이스 메모리테이블은 인덱스 칼럼의 갯수와 타입에 상관없이
인덱스당 16byte 크기를 갖으며 인덱스 사용량은 16byte * 레코드 건수로 계산할 수 있습니다.


.


메모리테이블 인덱스 정보 구하는 쿼리 ( HDB 4 ~ HDB 6 까지 모두 사용 가능 )


다음의 쿼리로 테이블별 인덱스 정보를 확인할 수 있습니다 . 인덱스 크기확인은 레코드 건수를 확인후 따로 계산하거나  function 이
들어간  메모리 테이블 인덱스 크기 구하는 쿼리를 사용해야 합니다.


set linesize 2048;

set colsize 30;


SELECT

c.user_name
, decode(f.table_type, 'Q', 'QUEUE', 'T', 'TABLE') object_type
, table_name object_name

, e.index_name
, rpad(case2(e.index_type=1, 'b-tree', 'r-tree'),10,' ') index_type
, '16 bytes * rowcount' 'ALLOC'
FROM   v$memtbl_info a
, v$index b

, system_.sys_users_ c
, system_.sys_indices_ e
, system_.sys_tables_ f

WHERE

a.table_oid = f.table_oid

and b.index_id = e.index_id

and e.user_id = c.user_id

and f.user_id = e.user_id

and f.tbs_id = a.tablespace_id

and f.table_oid = b.table_oid
and c.user_name <> 'SYSTEM_' ;





메모리 테이블 인덱스당 사용량 구하는 쿼리 ( HDB 5.x 이상부터 사용가능)


다음의 쿼리를 사용하여 메모리테이블의 인덱스당 사용량을 구할 수 있습니다.  쿼리를 사용하기 전에 해당 테이블을 레코드 건수를 구할 수
있는 DB function 을 생성해야 합니다.


1. 테이블의 레코드 건수를 count 할 수 있는 function 을 생성합니다.
CREATE FUNCTION GETCOUNT(u_name varchar(40), t_name varchar(40))

RETURN INTEGER

AS

RECORDCOUNT integer;

BEGIN
EXECUTE IMMEDIATE 'SELECT count(*) FROM ' || u_name||'.'||t_name INTO

RECORDCOUNT ;

RETURN RECORDCOUNT;


END;


/


2. function 을 이용하여 인덱스당 사용량을 조회합니다.

set linesize 2048;

set colsize 30;

SELECT

c.user_name
, decode(f.table_type, 'Q', 'QUEUE', 'T', 'TABLE') object_type
, table_name object_name

, e.index_name
, rpad(case2(e.index_type=1, 'b-tree', 'r-tree'),10,' ') index_type
, ROUND( 16 * GETCOUNT(c.user_name, f.table_name) / 1024/1024, 2) 'ALLOC(M)'
FROM   v$memtbl_info a
, v$index b

, system_.sys_users_ c
, system_.sys_indices_ e
, system_.sys_tables_ f

WHERE

a.table_oid = f.table_oid

and b.index_id = e.index_id

and e.user_id = c.user_id

and f.user_id = e.user_id

and f.tbs_id = a.tablespace_id

and f.table_oid = b.table_oid
and c.user_name <> 'SYSTEM_' ;






메모리 테이블당 총인덱스 사용량 구하는 쿼리 ( HDB 5.x 이상부터 사용가능 )


메모리 테이블이 사용하는 테이블당 총 인덱스 사용량을 조회합니다. 쿼리를 사용하기 전에 해당 테이블을 레코드 건수를 구할 수 있는 DB
function 을 생성해야 합니다.


1. 테이블의 레코드 건수를 count 할 수 있는 function 을 생성합니다.
CREATE FUNCTION GETCOUNT(u_name varchar(40), t_name varchar(40))

RETURN INTEGER

AS

RECORDCOUNT integer;

BEGIN
EXECUTE IMMEDIATE 'SELECT count(*) FROM ' || u_name||'.'||t_name INTO

RECORDCOUNT ;

RETURN RECORDCOUNT;


END;


/


2. function을 사용하여 테이블당 총 인덱스 사용량 크기를 조회합니다.

select

user_name

, table_name
, count(index_name) AS 'INDEX_COUNT'
, round( SUM(alloc) /1024/1024, 2 ) as 'Alloc(M)'
from (

SELECT

c.user_name

, f.table_name

, e.index_name
, 16 * GETCOUNT(c.user_name, f.table_name) AS alloc
FROM   v$memtbl_info a
, v$index b

, system_.sys_users_ c
, system_.sys_indices_ e
, system_.sys_tables_ f

WHERE

a.table_oid = f.table_oid

and b.index_id = e.index_id

and e.user_id = c.user_id

and f.user_id = e.user_id

and f.tbs_id = a.tablespace_id

and f.table_oid = b.table_oid
and c.user_name <> 'SYSTEM_'
)

group by user_name, table_name;


메모리테이블 인덱스당 크기 조회 쿼리( 6.x 용 )


다음의 쿼리로 좀더 정확한 메모리테이블의 인덱스당 사용량을 조회할 수 있습니다.  6.1.1 이상 버전에서 사용할 수 있습니다.


SELECT U.USER_NAME, T.TABLE_NAME TABLE_NAME

, B.INDEX_NAME
, LPAD(I.IS_PARTITIONED, 14) INDEX_PARTITIONED
, ROUND(((USED_NODE_COUNT+ PREPARE_NODE_COUNT) / 15 * 32768)/1024/1024, 1)
AS 'SIZE(MB)'
FROM V$MEM_BTREE_HEADER B

, SYSTEM_.SYS_INDICES_ I

, SYSTEM_.SYS_TABLES_ T

, SYSTEM_.SYS_USERS_ U

WHERE 1=1

AND B.INDEX_ID = I.INDEX_ID

AND I.TABLE_ID = T.TABLE_ID

AND B.INDEX_TBS_ID <> 0

AND U.USER_ID = T.USER_ID

ORDER BY TABLE_NAME, B.INDEX_ID

;






#### 08-09. 메모리 테이블스페이스 사용량

08-09-01. ALTIBASE HDB 5.5.1, 6.1.1, 6.3.1


개요
참고 - 메모리 테이블스페이스 속성 정보


개요


ALTIBASE HDB 5.5.1 부터 Volatile 메모리 테이블스페이스의 정보를 저장하는 V$VOL_TABLESPACES 가 추가되었습니다.
이 Performance View 를 활용하여 Volatile메모리 테이블스페이스 사용량을 포함한 모든 메모리 테이블스페이스 사용량를 다음의
쿼리로 조회 가능합니다.


ALTIBASE HDB 5.5.1, 6.1.1, 6.3.1 메모리 테이블스페이스 사용량 조회 쿼리


-
--TBS_ID  : 테이블스페이스 고유 번호

--TBS_TYPE : 메모리 테이블스페이스 유형.

--      0 - 시스템 메모리 테이블스페이스. 데이터베이스 시스템의 운영상 필요한 메타 데이터를

저장하기 위한 테이블스페이스.

--      1 - 시스템 메모리 테이블스페이스. 데이터베이스 생성 시 기본으로 생성되는 데이터를

저장할 수 있는 테이블스페이스.

--      2 - 유저 메모리 테이블스페이스. 사용자가 생성한 메모리 테이블스페이스.

--      8 - 유저가 생성한 휘발성 테이블스페이스.

--TBS_NAME : 메모리 테이블스페이스 이름.
--MAX(M)  : 메모리 테이블스페이스에서 사용할 수 있는 최대 메모리 크기.
--      테이블스페이스 생성 시 MAXSIZE 를 지정하지 않는 경우는 MEM_MAX_DB_SIZE 를

출력함.

--      테이블스페이스 속성이 AUTOEXTEND OFF 인 경우 TOTAL 을 출력함.
--TOTAL(M) : 메모리 테이블스페이스에서 할당받은 페이지 합계. 체크포인트 이미지 파일 생성

크기와 동일하다.

--      여기에는 free page 도 포함하고 있다. free page는 알티베이스 서버 구동 시에 메모리로
로딩되지 않는다. 그래서 이 값만큼 물리 메모리를 사용하고 판단하기 어렵다.

--      이 값은 DROP TABLESPACE 를 수행해야만 줄어든다.
--ALLOC(M) : 메모리 테이블스페이스에서 사용 중인 메모리 크기.
--USED(M) : ALLOC 중에서 데이터를 저장하고 있는 메모리 크기.
--USAGE(%) : MAX 대비 ALLOC 사용률.

--STATE  : 테이블스페이스의 상태.

--      1 - 오프라인, 2 - 온라인, 3 - 백업 중인 오프라인 상태의 테이블스페이스, 4 - 백업 중인
온라인 상태의 테이블스페이스,
--      128 - 삭제된(dropped) 테이블스페이스, 1024 - 폐기된(discarded) 테이블스페이스,
1028 - 백업 중인 폐기된(discarded) 상태의 테이블스페이스

set linesize 1024

set colsize 20

SELECT ID TBS_ID
, DECODE(TYPE, 0, 'MEMORY_DICTIONARY', 1, 'MEMORY_SYS_DATA', 2,
'MEMORY_USER_DATA', 8, 'VOLATILE_USER_DATA') TBS_TYPE

, NAME TBS_NAME

, ROUND( DECODE(M.MAXSIZE, 140737488322560, D.MEM MAX DB SIZE, 0,


, ROUND( DECODE(M.MAXSIZE, 140737488322560, D.MEM_MAX_DB_SIZE, 0,

T.TOTAL_PAGE_COUNT * T.PAGE_SIZE, M.MAXSIZE) /1024/1024, 2 ) 'MAX(M)'
, ROUND( M.ALLOC_PAGE_COUNT * T.PAGE_SIZE / 1024 / 1024, 2) 'TOTAL(M)'

,
ROUND(NVL(M.ALLOC_PAGE_COUNT-M.FREE_PAGE_COUNT,T.TOTAL_PAGE_COUNT)*PAGE_
SIZE/1024/1024, 2) 'ALLOC(M)'
, NVL(MT.USED, 0) 'USED(M)'
, ROUND(DECODE(MAXSIZE, 140737488322560,
(M.ALLOC_PAGE_COUNT-M.FREE_PAGE_COUNT)*T.PAGE_SIZE/ D.MEM_MAX_DB_SIZE,0,
(M.ALLOC_PAGE_COUNT-M.FREE_PAGE_COUNT) / T.TOTAL_PAGE_COUNT,
(M.ALLOC_PAGE_COUNT-M.FREE_PAGE_COUNT) * T.PAGE_SIZE/ M.MAXSIZE) * 100, 2)
'USAGE(%)'
, DECODE(T.STATE,1,'OFFLINE',2,'ONLINE',5,'OFFLINE BACKUP',6,'ONLINE
BACKUP',128,'DROPPED', 'DISCARDED') STATE
, DECODE(M.AUTOEXTEND_MODE,1,'ON','OFF') 'AUTOEXTEND'
FROM V$DATABASE D
, V$TABLESPACES T
, (SELECT SPACE_ID

, SPACE_NAME

, ALLOC_PAGE_COUNT

, FREE_PAGE_COUNT
, DECODE(MAX_SIZE, 0, (SELECT VALUE1 FROM V$PROPERTY WHERE NAME =
'VOLATILE_MAX_DB_SIZE'), MAX_SIZE) AS MAXSIZE

, AUTOEXTEND_MODE
FROM V$VOL_TABLESPACES

UNION ALL

SELECT SPACE_ID

, SPACE_NAME

, ALLOC_PAGE_COUNT

, FREE_PAGE_COUNT

, MAXSIZE

, AUTOEXTEND_MODE
FROM V$MEM_TABLESPACES ) M LEFT OUTER JOIN(SELECT TABLESPACE_ID,
ROUND(SUM((FIXED_USED_MEM + VAR_USED_MEM))/(1024*1024),3) USED


FROM V$MEMTBL_INFO
GROUP BY TABLESPACE_ID ) MT ON M.SPACE_ID = MT.TABLESPACE_ID

WHERE T.ID = M.SPACE_ID;





참고 - 메모리 테이블스페이스 속성 정보


SELECT SPACE_NAME
, TO_CHAR(CURRENT_SIZE/1024/1024, '999,999,999') 'CURR_SIZE(MB)'
, TO_CHAR(AUTOEXTEND_NEXTSIZE/1024/1024, '999,999,999') 'NEXT_SIZE(MB)'
, TO_CHAR(DECODE(MAXSIZE, 0, CURRENT_SIZE, 140737488322560, D.MEM_MAX_DB_SIZE,
MAXSIZE)/1024/1024, '999,999,999') ' MAXSIZE(MB)'
, DECODE(AUTOEXTEND_MODE, 1, 'ON', 0, 'OFF') 'AUTOEXTEND'
FROM V$MEM_TABLESPACES, V$DATABASE D

UNION ALL

SELECT SPACE_NAME
, TO_CHAR(CURRENT_SIZE/1024/1024, '999,999,999') 'CURR_SIZE(MB)'
, TO_CHAR(NEXT_SIZE/1024/1024, '999,999,999') 'NEXT_SIZE(MB)'
, TO_CHAR(DECODE(MAX_SIZE, 0, CURRENT_SIZE, 140737488322560, D.MEM_MAX_DB_SIZE,
MAX_SIZE)/1024/1024, '999,999,999') ' MAXSIZE(MB)'
, DECODE(AUTOEXTEND_MODE, 1, 'ON', 0, 'OFF') 'AUTOEXTEND'
FROM V$VOL_TABLESPACES, V$DATABASE D ;

#### 08-10. 알티몬(altimon) 설정 및 실행 방법


ALTIMON 이란?

ALTIMON USER GUIDE

ALTIMON 실행 파일 및 설정 파일

ALTIMON 실행 파일
ALTIMON 설치 파일
ALTIMON 설정 파일
ALTIMON 파일 업로드
ALTIMON 실행 파일 복사


ALTIMON 설정 파일 복사
ALTIMON 설정 파일에서 변경해야 할 항목
ALTIMON 실행
ALTIMON 로그 확인


ALTIMON 이란?


ALTIMON 은 ALTIBASE HDB 서버의 운영 상태를 주기적으로 확인하는 모니터링 프로그램으로 장애 상황 발생 시 ALTIBASE HDB 서버 상태를
확인하여 장애 원인을 추적하는데 도움을 줍니다.
이 페이지는 ALTIMON 설정 및 구동 방법을 간략히 설명하고 있습니다.
ALTIMON 관련하여 더 상세한 내용을 원하면 ALTIMON USER GUIDE 를 참고하시기 바랍니다.


ALTIMON USER GUIDE


ALTIMON_USER_GUIDE.pdf


ALTIMON 실행 파일 및 설정 파일


ALTIMON 실행 파일

|Col1|Linux|SunOS Sparc|SunOS x86|HP-UX IA|AIX|
|---|---|---|---|---|---|
|Altibase 6.3.1|altimon_linux_631.tar|||||
|Altibase 6.1.1|altimon_linux_611.tar|||||
|Altibase 4.3.9|||altimon_sunos_x86_439.tar|||



ALTIMON 설치 파일


Linux : altimon_linux_611.tar
HP-UX IA : altimon_linux.tar
HP-UX PA-RISC

SunOS Sparc : altimon_hpux_ia64.tar
SunOS x86 :

AIX : altimon_sunos_sparc.tar
WIndwos 용은 제공하지 않습니다. Windows의 경우 Windows 용 모니터링 툴 페이지를 참고하세요.


ALTIMON 설정 파일


Altibase 6.3.1 버전 : altimon.conf.631
ALTIBASE HDB 5.1.5 버전 용 : altimon.conf.5.1.5
ALTIBASE HDB 4.3.9 버전 용 :


ALTIMON 파일 업로드


첨부 파일(altimon.tar) 을 알티베이스 서버 프로세스가 구동 중인 시스템의 임의 디렉토리에 업로드합니다.


첨부 파일 압축을 풉니다.


$ tar xvf altimon.tar


압축을 풀면 altimon 이라는 디렉토리가 생성됩니다.


$ ls -l altimon

total 8336

drwxr-xr-x  2 eheejung staff      256 Dec 30 15:26 ACTION_LOG
drwxr-xr-x  2 eheejung staff      256 Dec 30 15:26 ACTION_SCRIPT
-rw-r--r--  1 eheejung staff      318 Dec 30 11:23 Makefile
-rwxr-xr-x  1 eheejung staff    3991619 Dec 30 15:10 altimon      // 실행 파일
-rw-r--r--  1 eheejung staff     18120 Dec 30 11:23 altimon.conf    // 설정 파일
-rw-r--r--  1 eheejung staff     78141 Dec 30 11:23 altimon.cpp
-rw-r--r--  1 eheejung staff    166311 Dec 30 15:10 altimon.o
drwxr-xr-x  2 eheejung staff      256 Dec 30 15:26 log


ALTIMON 실행 파일 복사


ALTIMON 실행 파일을 $ALTIBASE_HOME/bin 디렉토리로 복사합니다.


$ cp -p altimon $ALTIBASE_HOME/bin/


ALTIMON 설정 파일 복사


ALTIMON 설정 파일을 $ALTIBASE_HOME/conf/ 디렉토리로 복사합니다.


$ cp -p altimon.conf $ALTIBASE_HOME/conf/


ALTIMON 설정 파일에서 변경해야 할 항목


ALTIMON 설정 파일($ALTIBASE_HOME/conf/altimon.conf) 에서 Connection Group 부분과 ALTIMON PROPERTY 부분에서 아래 주석
부분을 환경에 맞게 변경합니다.


LONG_RUN_QUERY를 포함하여, 시간관련된 쿼리들이 제대로 수행되기 위해서는 TIMED_STATISTICS 프라퍼티의 값이 1 이어야 합니다.


#########################################

## Connection Group

#########################################

<CONNECTION_INFO>
<DB_IP>    127.0.0.1 </DB_IP>
<SYS_PASSWD>  manager   </SYS_PASSWD>        # sys 계정 패스워드 입력
<PORT_NO>   20300    </PORT_NO>         # 알티베이스 서버 서비스 포트 입력
<NLS_USE>   US7ASCII  </NLS_USE>         # 데이터베이스 서버 캐릭터 셋 입력 iSQL> select
NLS_CHARACTERSET from v$nls_parameters; 로 확인 가능.
</CONNECTION_INFO>


#########################################

## ALTIMON PROPERTY

#########################################

<ALTIMON_PROPERTY>
<DATE_FORMAT>  1  </DATE_FORMAT>
<SLEEP_TIME>  300 </SLEEP_TIME>                    # 문제 발생 시 당시 상황을 로그에 남길 수

있도록 환경에 맞게 변경합니다. 단위는 초 입니다.
<LOG_FILE>   /home/altibase/altimon/log/altimon.log </LOG_FILE>    # 로그 파일 경로를 환경에 맞게
변경합니다. 절대 경로로 입력하며 파일 이름은 그대로 두고 경로만 변경합니다.
<LOG_DIR>    /home/altibase/altimon/log </LOG_DIR>          # 로그 파일 경로를 환경에 맞게 다시
한 번 절대 경로로 입력합니다.
<LIFE_CYCLE>  3  </LIFE_CYCLE>                    # 로그 파일 보관 기간으로 일단위 입니다.

환경에 맞게 변경합니다.
<LOGGING_LV>  2  </LOGGING_LV>
<ALARM_FILE>  /home/altibase/altimon/log/alarm.log  </ALARM_FILE>   # 알람 로그 파일 경로를 환경에
맞게 변경합니다. 절대 경로로 입력하고 파일 이름은 그대로 두고 경로만 변경합니다.
<DB_SAVE>    OFF  </DB_SAVE>
<LISTEN_PORT>  22300 </LISTEN_PORT>
</ALTIMON_PROPERTY>


아래 설정부터는 $HOME/altimon/ACTION_SCRIPT/ 경로가 계속 사용됩니다.


아래와 다르게 altimon 디렉토리가 위치한 경우는 변경해주세요.


altimon.tar 를 $HOME 디렉토리에 놓고 tar 를 풀었다면 아래 설정을 변경할 필요가 없습니다.


#########################################

## PROCESS CHECK PROPERTY

#########################################

<OS_QUERY_GROUP_SET>
<CPU_USAGE> 80 </CPU_USAGE>
<CPU_ACT>                    # 이 설정부터는 $HOME/altimon/ACTION_SCRIPT/ 경로가 계속

사용됩니다. 아래와 다르게 altimon 디렉토리가 위치한 경우는 변경합니다.
is -silent -f $HOME/altimon/ACTION_SCRIPT/cpu_act.sql -o
$HOME/altimon/ACTION_LOG/cpu_act.log.`date +%Y%m%d_%H%M%S`
</CPU_ACT>
<MEM_USAGE> 100000000 </MEM_USAGE>

<MEM_ACT>
is -silent -f $HOME/altimon/ACTION_SCRIPT/mem_act.sql -o
$HOME/altimon/ACTION_LOG/mem_act.log.`date +%Y%m%d_%H%M%S`
</MEM_ACT>
<DISK_CHK_ENABLE> ON </DISK_CHK_ENABLE>
<DISK1> /home    </DISK1>          # 모니터링 할 파일 시스템으로 수정해주세요.
<DISK1_USAGE> 90   </DISK1_USAGE>       # 파일 시스템 사용량 임계치를 입력합니다. 단위는 %

입니다.

<DISK2> /home1  </DISK2>
<DISK2_USAGE> 90   </DISK2_USAGE>

<DISK_ACT>
</DISK_ACT>
</OS_QUERY_GROUP_SET>


ALTIMON 실행


환경 변수 설정 후 ALTIMON 을 실행합니다.


$ export UNIX95=1       (본 쉘, 콘 쉘, 배시 쉘의 경우)

또는
$ setenv UNIX95 1       ( C 쉘의 경우)


AIX의 경우 NMON 환경 변수도 설정합니다.


$ export NMON=t       (본 쉘, 콘 쉘, 배시 쉘의 경우)

또는
$ setenv NMON t       ( C 쉘의 경우)


altimon 을 실행합니다.


$ altimon start


ALTIMON 로그 확인


로그화일들은 $ALTIBASE_HOME/conf/altimon.conf 에서 설정한 아래 경로에 저장됩니다.


log 디렉토리와 ACTION_LOG 디렉토리에서 장애 발생 날짜의 로그들을 보내주시면 됩니다.

#### 08-11. 언두 테이블스페이스(UNDO TABLESPACE)


08-11-01. 언두 테이블스페이스 사용량


개요
버전
언두 테이블스페이스 사용량
V$DISK_UNDO_USAGE 성능 뷰
관련 버그


개요


V$DISK_UNDO_USAGE 를 이용하여 언두 테이블스페이스 실 사용량을 확인하는 방법을 소개합니다.


언두 테이블스페이스의 ALLOC 과 USED


언두 테이블스페이스는 세그먼트 단위로 이루어져 있으며 세그먼트는 익스텐트라는 더 작은 단위로 이루어져 있습니다.
디스크 테이블에 변경 트랜잭션 발생 시 익스텐트 단위로 할당받게 되며 익스텐트를 새롭게 할당 받을 때마다 언두 테이블스페이스

ALLOC 크기가 증가합니다.
트랜잭션이 종료되면 익스텐트는 재사용 가능한 상태가 됩니다.
하지만 세그먼트 내의 익스텐트 중 하나라도 사용 중이라면 재 사용 가능한 익스텐트가 있더라도 해당 세그먼트 내의 익스텐트는 모두
사용할 수 없는 상태가 됩니다. (UNSTEALABLE EXTENT)
변경 트랜잭션이 수행 중이어서 익스텐트를 사용하거나 UNSTEALABLE 익스텐트는 언두 테이블스페이스의 USED 로 계산됩니다.


버전


이 모니터링 쿼리는 아래 버전에서 사용할 수 있습니다.


Altibase 5.5.1

Altibase 6.1.1

Altibase 6.3.1

Altibase 6.5.1

Altibase 7.1.1

Altibase 7.3.1


언두 테이블스페이스 사용량


디스크 테이블에 변경 트랜잭션이 수행 중에는 ALLOC 과 USED 가 증가할 수 있습니다.


트랜잭션이 커밋된 경우 트랜잭션 수행 중에 증가한 USED 는 줄어듭니다.
트랜잭션이 롤백된 경우 트랜잭션 수행 중에 증가한 ALLOC 과 USED 는 줄어듭니다.










|컬럼 이름|설 명|
|---|---|
|TBS_NAME|테이블스페이스 이름|
|MAX(M)|언두 테이블스페이스의 최대 크기|
|TOTAL(M)|언두 테이블스페이스로 할당 받은 전체 크기|
|ALLOC(M)|현재까지 할당 받은 페이지 중 '빈 페이지'를 제외한 '사용 중인 페이지' 만의 합계|
|USED(M)|변경 트랜잭션에 의해 사용 중이거나 재사용할 수 없는 EXTENT의 크기|
|USAGE(%)|사용량 (MAX 대비 USED)|
|STATE|테이블스페이스 상태|


V$DISK_UNDO_USAGE 성능 뷰







|컬럼 이름|데이터<br>타입|설명|
|---|---|---|
|TX_EXT_CNT|BIGINT|트랜잭션 상태 정보를 저장하는 세그먼트(Transaction Status Segment, TSS) 용 익스텐트 수.<br>디스크 테이블에 갱신 트랜잭션 발생 시 할당 받는다.|
|USED_EXT_CNT|BIGINT|트랜잭션에 사용되고 있는 언두 세그먼트 내 익스텐트 수.<br>디스크 테이블에 갱신 트랜잭션 발생 시 필요한 만큼 할당 받는다.|
|UNSTEALABLE_EXT_CNT|BIGINT|다른 언두 세그먼트에서 가져갈 수 없는 익스텐트 수.<br>온라인 상태의 언두 세그먼트에 속한 익스텐트, 헤더 정보를 가지고 있는 익스텐트. 트랜잭션이<br>접근하고 있는 익스텐트들을 포함한다.<br>해당 언두 세그먼트에 재 사용 가능한 익스텐트가 있다 하더라고 다른 언두 세그먼트에서 가져가지<br>못한다.|
|REUSABLE_EXT_CNT|BIGINT|재사용 가능한 익스텐트 수<br>트랜잭션 진행 중에 사용된 USED_EXT_CNT 는 해당 트랜잭션이 커밋되면 USED_EXT_CNT 는<br>감소한 만큼 REUSABLE_EXT_CNT 이 증가한다.|
|TOTAL_EXT_CNT|BIGINT|언두 테이블 스페이스에서 할당 받은 총 익스텐트 수.<br>트랜잭션이 롤백 된 경우, 그 트랜잭션에 사용된 익스텐트들은 언두 테이블 스페이스로 반환된다.<br>트랜잭션이 커밋 된 경우, 그 트랜잭션에 사용된 익스텐트들은 해당 언두 세그먼트에서 가지고 있는다.|


관련 버그


버그 내용


재 사용 할 수 없는 언두 영역을 사용 가능한 공간으로 계산되는 문제를 개선함. (UNSTEALABLE_EXT_CNT 컬럼에 해당되는
익스텐트가 사용 가능한 익스텐트로 계산되는 문제) (BUG-39985)


반영 버전


Altibase 6.1.1.4.9 이상
Altibase 6.3.1.3.3 이상
Altibase 6.5.1 이상


08-11-02. 언두 테이블스페이스 사용량 증가 시 모니터링 방법


개요
모니터링 항목
버전 별 모니터링 방법

Altibase 5.3.3, 5.5.1, 6.1.1, 6.3.1, 6.5.1, 7.1.0, 7.3.1
Altibase 4.3.9, 5.1.5
조치 방법

언두 테이블스페이스 크기 증가
세션 강제 종료
장시간 수행하는 트랜잭션 방지


개요


언두 테이블스페이스 사용량이 지속적으로 증가할 경우 모니터링 방법에 대해 설명합니다.


모니터링 항목


언두 테이블스페이스의 사용량이 증가한다면 다음 두 가지 경우를 확인해야 합니다.


디스크 테이블의 데이터를 변경하는 변경 트랜잭션이 존재하는지
변경 트랜잭션에서 생성한 old image 를 바라보는 조회 트랜잭션이 존재하는지


버전 별 모니터링 방법


Altibase 5.3.3, 5.5.1, 6.1.1, 6.3.1, 6.5.1, 7.1.0, 7.3.1


트랜잭션 별 언두 테이블스페이스 사용량 모니터링 쿼리


아래 모니터링 쿼리를 통해 TX_STATUS 가 BEGIN 또는 END 상태로 장시간 수행 중인 트랜잭션을 찾아 조치합니다.


쿼리 결과에서 아래와 같은 정보들을 확인할 수 있습니다.


언두 테이블스페이스를 사용하거나 접근하고 있는 세션의 정보. (Autocommit mode, Client IP 및 Process id, UTRANS_TIMEOUT 설정
값)
언두 영역을 사용하는 변경 트랜잭션 존재 여부
언두 영역에 접근하는 조회 트랜잭션 존재 여부
변경 트랜잭션에서 사용 중인 언두 사용량
트랜잭션의 마지막 SQL 문장 및 수행 시각
SQL 문장 수행 여부


트랜잭션 별 언두 테이블스페이스 사용량 조회 쿼리


SELECT RPAD(DECODE(TX.LOG_TYPE, 1, REP.REP_NAME, TX.SESSION_ID), 10) SESSION_ID

-- 트랜잭션을 수행한 세션 ID.
, RPAD(TX.ID, 20) TX_ID

-- 트랜잭션 ID
, RPAD(DECODE(ST.ID, NULL, 'REP''S TX', ST.ID), 20) STATEMENT_ID

-- STATEMENT ID
, RPAD(DECODE(TX.TSS_RID, 0, 'SELECT', 'UPDATE'), 7) TX_TYPE
-- 트랜잭션 타입. SELECT : 조회 문장만 있는 트랜잭션. UPDATE : DELETE, UPDATE 등 데이터를

변경한트랜잭션


변경한 트랜잭션

, RPAD(DECODE(TX.STATUS, 0, 'BEGIN', 1, 'PRECOMMIT', 2, 'COMMIT_IN_MEMORY', 3,
'COMMIT', 4, 'ABORT', 5, 'BLOCKED', 6, 'END'), 16) TX_STATUS  -- 트랜잭션 상태
, RPAD(DECODE(ST.EXECUTE_FLAG, NULL, 'REP''S TX', 1, 'SQL ING', 0, 'SQL END'), 10)
SQL_STATUS                         -- SQL 상태
, RPAD(DECODE(TX.LOG_TYPE, 1, 'REP '||REP.PEER_IP||':'||REP.PEER_PORT,
S.COMM_NAME||' PID:'||S.CLIENT_PID), 40) CLIENT_IP           -- 클라이언트 IP와

프로세스 ID
, RPAD(DECODE(S.AUTOCOMMIT_FLAG, 1, 'ON', 0, 'OFF', NULL, 'REP''S TX'), 10)

AUTOCOMMIT                             -- AUTOCOMMIT 모드
, RPAD(DECODE(TX.LOG_TYPE, 1, 'REP''S TX', S.UTRANS_TIME_LIMIT), 15)
UTRANS_TIMEOUT                              -- 세션의 UTRANS_TIMEOUT

설정값
, TO_CHAR(SYSDATE, 'YYYY-MM-DD HH:MI:SS') CURRENT_TIME

-- 현재 시각
, DECODE(ST.LAST_QUERY_START_TIME, NULL,
TO_CHAR(TO_DATE('1970010109','YYYYMMDDHH') + TX.FIRST_UPDATE_TIME / (60*60*24),
'YYYY-MM-DD HH:MI:SS'), ST.LAST_QUERY_START_TIME) LAST_QUERY_START_TIME  -
SQL문 시작 시각
, RPAD(LTRIM(TXM.SYS_MIN_DISK_VIEWSCN), 10) SYS_MIN_DISK_VIEWSCN

-- 언두 영역을 보고 있는 SCN 중 가장 작은 SCN
, DECODE(TX.DISK_VIEW_SCN, 'INFINITE(         0)', '-', LTRIM(TX.DISK_VIEW_SCN))
DISK_VIEW_SCN                    -- 조회 트랜잭션에서 바라보는 가장 작은 SCN
, DECODE(TX.MIN_DISK_LOB_VIEW_SCN, 'INFINITE(         0)', '-',
LTRIM(TX.MIN_DISK_LOB_VIEW_SCN)) MIN_DISK_LOB_VIEW_SCN        -- LOB 데이터를

조회하는 트랜잭션에서 바라보는 가장 작은 SCN
, TO_CHAR(((UD_S.TOTAL_EXTENT_COUNT*UD_S.PAGE_COUNT_IN_EXTENT*8192)/1024),
'999,999,999') 'UNDO_USED(KB)'                   -- 변경 트랜잭션에서 사용한 언두

영역 크기.
, DECODE(TX.LOG_TYPE, 1, 'REMOTE_TX_ID : '||REP_TX.REMOTE_TID, ST.QUERY) QUERY

-- 언두를 사용하거나 접근한 트랜잭션에서 수행한 마지막 쿼리
FROM V$TRANSACTION TX LEFT OUTER JOIN (SELECT SESSION_ID, TX_ID, ID,
TO_CHAR(TO_DATE('1970010109','YYYYMMDDHH') + (LAST_QUERY_START_TIME) /
(60*60*24), 'YYYY-MM-DD HH:MI:SS') LAST_QUERY_START_TIME, EXECUTE_FLAG,
UNDO_READ_PAGE, UNDO_GET_PAGE, SUBSTR(QUERY, 1, 60) QUERY
FROM V$STATEMENT
WHERE (SESSION_ID

, TX_ID
, LAST_QUERY_START_TIME) IN (SELECT SESSION_ID

, TX_ID
, MAX(LAST_QUERY_START_TIME) LAST_QUERY_START_TIME
FROM V$STATEMENT

GROUP BY SESSION_ID
, TX_ID)) ST ON TX.ID = ST.TX_ID LEFT OUTER JOIN V$SESSION S ON
TX.SESSION_ID = S.ID LEFT OUTER JOIN V$REPRECEIVER_TRANSTBL REP_TX ON TX.ID =
REP_TX.LOCAL_TID LEFT OUTER JOIN V$REPRECEIVER REP ON REP_TX.REP_NAME =

REP.REP_NAME
LEFT OUTER JOIN V$TXSEGS TX_S ON TX.ID = TX_S.TRANS_ID LEFT OUTER JOIN
V$UDSEGS UD_S ON TX_S.ID = UD_S.TXSEG_ENTRY_ID
, V$TRANSACTION_MGR TXM

WHERE 1=1

AND (TX.TSS_RID <> 0

OR ST.UNDO_READ_PAGE <> 0
OR ST.UNDO_GET_PAGE <> 0)


ORDER BY SESSION_ID

, TX_ID

, LAST_QUERY_START_TIME;


출력 결과


아래는 언두를 사용하는 변경 트랜잭션을 보여주는 출력 예입니다.


iSQL> /

SESSION_ID TX_ID           STATEMENT_ID        TX_TYPE    TX_STATUS

SQL_STATUS      CLIENT_IP         AUTOCOMMIT      UTRANS_TIMEOUT

CURRENT_TIME        LAST_QUERY_START_TIME   SYS_MIN_DISK_VIEWSCN DISK_VIEW_SCN
MIN_DISK_LOB_VIEW_SCN   UNDO_USED(KB)  QUERY

----------------------------------------------------------------------------------
----------------------------------------------------------------------------------
----------------------------------------------------------------------------------
----------------------------------------------------------------------------------
--------------------------------------------------------------
4      61397121          262147           UPDATE    BEGIN           SQL_END

TCP 127.0.0.1:45076 PID:1 OFF          0             2015-03-11 12:27:11    2015-03-11

09:30:40    800767        -             -                  256   UPDATE LOB_T SET C3

= 'UN

11410

_DO TEST'

6      586566273         393216           UPDATE    BEGIN           SQL_ING

TCP 127.0.0.1:45044 PID:1 OFF          3600            2015-03-11 12:27:11    2015-03-11

09:30:30    800767        800767           800767              68,864   UPDATE EMP SET

JOIN_DATE=

11242

SYSDATE

2 rows selected.


TX_TYPE 이 UPDATE 인 경우 해당 트랜잭션에 데이터 변경 작업이 한 번이라도 발생했음을 의미합니다.
SQL_STATUS 가 SQL_END 인 경우 트랜잭션에서 수행한 SQL 문의 수행이 종료하였으나 트랜잭션은 종료되지 않은 상태를
의미합니다. (아래 결과에서 4번 세션의 TX_ID 61397121)
SQL_STATUS 가 SQL_ING 인 경우 트랜잭션에서 수행한 SQL 문장이 수행 중임을 의미합니다. (아래 결과에서 6번 세션의 TX_ID
61397121)
LAST_QUERY_START_TIME 으로 트랜잭션에서 수행한 마지막 SQL문의 시작 시각을 알 수 있습니다. 현재 시각과 차이로 해당
트랜잭션이 얼마나 오래 수행 중인지 판단할 수 있습니다.
UTRANS_TIMEOUT 은 변경 트랜잭션이 수행할 수 있는 최대 소요 시간(초 단위)을 의미합니다.
UNDO_USED(KB)는 해당 트랜잭션에서 사용한 언두의 크기를 kbyte 단위로 보여줍니다.


아래는 변경 트랜잭션에서 언두 영역에 생성한 변경 전 데이터를 바라보는 조회 트랜잭션을 보여주는 출력 결과입니다.


iSQL> /

SESSION_ID TX_ID           STATEMENT_ID        TX_TYPE    TX_STATUS

SQL_STATUS      CLIENT_IP         AUTOCOMMIT      UTRANS_TIMEOUT

CURRENT_TIME        LAST_QUERY_START_TIME   SYS_MIN_DISK_VIEWSCN DISK_VIEW_SCN
MIN_DISK_LOB_VIEW_SCN   UNDO_USED(KB)  QUERY

----------------------------------------------------------------------------------
----------------------------------------------------------------------------------

----------------------------------------------------------------------------------
----------------------------------------------------------------------------------
--------------------------------------------------------------
2      7374720          131072           SELECT    BEGIN           SQL_END

TCP 127.0.0.1:45173 PID:1 OFF          0             2015-03-11 12:30:25    2015-03-11

09:31:43    800783        -             800783                   SELECT * FROM

LOB_T

12123


5      1613185          327681           SELECT    BEGIN           SQL_ING

TCP 127.0.0.1:44251 PID:4 ON          3600            2015-03-11 12:30:25    2015-03-11

09:33:42    800783        800783           800783                   SELECT ENO,

C_DATE

0252

FROM EMP

2 rows selected.


iSQL> /

SESSION_ID TX_ID           STATEMENT_ID        TX_TYPE    TX_STATUS

SQL_STATUS      CLIENT_IP         AUTOCOMMIT      UTRANS_TIMEOUT

CURRENT_TIME        LAST_QUERY_START_TIME   SYS_MIN_DISK_VIEWSCN DISK_VIEW_SCN
MIN_DISK_LOB_VIEW_SCN   UNDO_USED(KB)  QUERY

----------------------------------------------------------------------------------
----------------------------------------------------------------------------------
----------------------------------------------------------------------------------
----------------------------------------------------------------------------------
--------------------------------------------------------------
2      7374720          131072           SELECT    BEGIN           SQL_END

TCP 127.0.0.1:45173 PID:1 OFF          0             2015-03-11 12:35:12    2015-03-11

09:31:43    800783        -             800783                   SELECT * FROM

LOB_T

12123


1 rows selected.


iSQL> /

SESSION_ID TX_ID           STATEMENT_ID        TX_TYPE     TX_STATUS

SQL_STATUS      CLIENT_IP         AUTOCOMMIT      UTRANS_TIMEOUT

CURRENT_TIME        LAST_QUERY_START_TIME   SYS_MIN_DISK_VIEWSCN DISK_VIEW_SCN
MIN_DISK_LOB_VIEW_SCN   UNDO_USED(KB)  QUERY

----------------------------------------------------------------------------------
----------------------------------------------------------------------------------
----------------------------------------------------------------------------------
----------------------------------------------------------------------------------
-----------------------------------------------------------------
9      376196           589824           SELECT     BEGIN           SQL END

TCP 127.0.0.1:21792 PID:2 OFF          3600            2015-03-11 16:00:13    2015-03-11

15:54:19    800951        -             -                      SELECT DEP_LOCATION

FROM

20176

DEPT WHERE DNO BETWEEN '1


001' AND '

1 rows selected.


TX_TYPE 이 SELECT 인 경우 변경 문장을 한 번도 수행하지 않은 트랜잭션을 의미합니다.


LOB 데이터가 포함되지 않은 SELECT 문은 데이터베이스로부터 데이터를 fetch 한 후에는 언두 이미지를 더 이상 바라보지 않습니다.


   - Autocommit-Mode 의 트랜잭션은 fetch 를 완료하면 결과에서 사라집니다. (5번 세션의 TX_ID 1613185 참고. DISK_VIEW_SCN 에
SCN 이 표시된 것은 LOB데이터를 포함하지 않음을 의미함.)

   - Non-autocommit-Mode 의 트랜잭션은 fetch 종료 후 commit 수행 전까지 DISK_VIEW_SCN, MIN_DISK_LOB_VIEW_SCN 이 모두

   - 로 표시됩니다. (9번 세션의 TX_ID 376196)


LOB 데이터를 포함한 SELECT 문은 fetch 가 종료되어도 commit 또는 rollback 을 수행하기 전까지 언두 이미지를 바라봅니다.
DISK_VIEW_SCN - 이고 MIN_DISK_LOB_VIEW_SCN 에 SCN 이 표시되어 있으면 LOB 데이터를 조회하는 트랜잭션을 의미합니다.
(2번 세션의 TX_ID 7374720)
LOB 데이터의 경우 lob cursor 라는 정보가 존재하는데 이것이 open 된 상태에서는 언두 이미지를 바라보게 됩니다. lob cursor 는
commit 또는 rollback 을 수행해야만 close 됩니다.
이 상태의 트랜잭션은 언두 사용을 증가시키는 원인이 될 수 있습니다.


다음은 언두 영역을 사용하는 이중화 트랜잭션을 보여주는 결과입니다.





CLIENT_IP 로 트랜잭션을 보낸 서버의 IP 를 확인할 수 있습니다.
SESSION_ID 로 이중화 객체 이름을 알 수 있습니다.
REP'S TX 라는 값은 로컬에서 확인할 수 없는 값을 의미합니다. (이중화 트랜잭션의 세션, SQL 정보는 로컬에서 확인 불가)
QUERY에 출력된 REMOTE_TX_ID로 원격 서버의 TX_ID 를 알 수 있습니다.


Altibase 4.3.9, 5.1.5


트랜잭션 별 언두 테이블스페이스 사용량 모니터링 쿼리


아래 모니터링 쿼리를 통해 언두를 사용하고있거나 접근하고 있는 트랜잭션을 찾아 조치합니다.


쿼리 결과에서 아래와 같은 정보들을 확인할 수 있습니다.


언두 테이블스페이스를 사용하거나 접근하고 있는 세션의 정보. (Autocommit mode, Client IP 및 Process id, UTRANS_TIMEOUT 설정
값)
언두 영역을 사용하는 변경 트랜잭션 존재 여부
언두 영역에 접근하는 조회 트랜잭션 존재 여부
트랜잭션의 마지막 SQL 문장 및 수행 시각
SQL 문장 수행 여부


트랜잭션 별 언두 테이블스페이스 사용량 조회 쿼리


SELECT RPAD(DECODE(TX.LOG_TYPE, 1, REP.REP_NAME, ST.SESSION_ID), 10) SESSION_ID

-- 트랜잭션을 수행한 세션 ID.
, RPAD(TX.ID, 20) TX_ID

-- 트랜잭션 ID
, RPAD(DECODE(ST.ID, NULL, 'REP''S TX', ST.ID), 20) STATEMENT_ID

-- STATEMENT ID
, RPAD(DECODE(TX.TSS_RID, 0, 'SELECT', 'UPDATE'), 7) TX_TYPE
-- 트랜잭션 타입. SELECT : 조회 문장만 있는 트랜잭션. UPDATE : DELETE, UPDATE 등 데이터를

변경한 트랜잭션
, RPAD(DECODE(TX.STATUS, 0, 'BEGIN', 1, 'PRECOMMIT', 2, 'COMMIT_IN_MEMORY', 3,
'COMMIT', 4, 'ABORT', 5, 'BLOCKED', 6, 'END'), 16) TX_STATUS    -- 트랜잭션 상태
, RPAD(DECODE(ST.EXECUTE_FLAG, NULL, 'REP''S TX', 0, 'SQL_END', 1, 'SQL_ING'), 16)
SQL_STATUS                           -- SQL문 상태
, RPAD(DECODE(TX.LOG_TYPE, 1, 'REP '||REP.PEER_IP||':'||REP.PEER_PORT,
S.COMM_NAME||' PID:'||S.CLIENT_PID), 40) CLIENT_IP             -- 클라이언트 IP와

프로세스 ID
, RPAD(DECODE(S.AUTOCOMMIT_FLAG, 1, 'ON', 0, 'OFF', NULL, 'REP''S TX'), 10)

AUTOCOMMIT                               -- AUTOCOMMIT 모드
, RPAD(DECODE(TX.LOG_TYPE, 1, 'REP''S TX', S.UTRANS_TIME_LIMIT), 15)
UTRANS_TIMEOUT                                -- 세션의 UTRANS_TIMEOUT

설정값
, TO_CHAR(SYSDATE, 'YYYY-MM-DD HH:MI:SS') CURRENT_TIME

-- 현재 시각
, DECODE(ST.LAST_QUERY_START_TIME, NULL,
TO_CHAR(TO_DATE('1970010109','YYYYMMDDHH') + TX.FIRST_UPDATE_TIME / (60*60*24),
'YYYY-MM-DD HH:MI:SS'), ST.LAST_QUERY_START_TIME) LAST_QUERY_START_TIME -
SQL문 시작 시각
, DECODE(TX.LOG_TYPE, 1, 'REMOTE_TX_ID : '||REP_TX.REMOTE_TID, ST.QUERY) QUERY

-- 언두를 사용하거나 접근한 트랜잭션에서 수행한 마지막 쿼리
FROM V$TRANSACTION TX LEFT OUTER JOIN (SELECT SESSION_ID, TX_ID, ID,
TO_CHAR(TO_DATE('1970010109','YYYYMMDDHH') + (LAST_QUERY_START_TIME) /
(60*60*24), 'YYYY-MM-DD HH:MI:SS') LAST_QUERY_START_TIME, UNDO_READ_PAGE,
UNDO_GET_PAGE, EXECUTE_FLAG, SUBSTR(QUERY, 1, 60) QUERY
FROM V$STATEMENT
WHERE (SESSION_ID

, TX_ID
, LAST_QUERY_START_TIME) IN (SELECT SESSION_ID

, TX_ID
, MAX(LAST_QUERY_START_TIME) LAST_QUERY_START_TIME
FROM V$STATEMENT


GROUP BY SESSION_ID
, TX_ID)) ST ON TX.ID = ST.TX_ID LEFT OUTER JOIN V$SESSION S ON
ST.SESSION_ID = S.ID LEFT OUTER JOIN V$REPRECEIVER_TRANSTBL REP_TX ON TX.ID =
REP_TX.LOCAL_TID LEFT OUTER JOIN V$REPRECEIVER REP ON REP_TX.REP_NAME =

REP.REP_NAME

WHERE 1=1

AND TX.STATUS <> 6
AND (TX.TSS_RID <> 0

OR ST.UNDO_READ_PAGE <> 0
OR ST.UNDO_GET_PAGE <> 0)


ORDER BY SESSION_ID

, TX_ID

, LAST_QUERY_START_TIME;


출력 결과


아래는 언두를 사용하는 변경 트랜잭션을 보여주는 출력 예입니다.


iSQL> /

SESSION_ID TX_ID         STATEMENT_ID     TX_TYPE TX_STATUS     SQL_STATUS

CLIENT_IP            AUTOCOMMIT UTRANS_TIMEOUT  CURRENT_TIME

LAST_QUERY_START_TIME      QUERY

----------------------------------------------------------------------------------
----------------------------------------------------------------------------------
----------------------------------------------------------------------------------
---------------------
453698   876975109       0           UPDATE  BEGIN       SQL_ING

SOCKET-INET-SERVER : 127.0.0.1 OFF     0        2015-03-11 14:21:38       2015-03-11

14:07:11       UPDATE EMP SET JOIN_DATE = SYS

PID:12959

DATE

453832   34379778       0           UPDATE  BEGIN       SQL_END

SOCKET-INET-SERVER : 127.0.0.1 OFF     0        2015-03-11 14:21:38       2015-03-11

14:06:32       UPDATE LOB_T SET C1 = 'T'

PID:13015


2 rows selected.


TX_TYPE 이 UPDATE 인 경우 해당 트랜잭션에 데이터 변경 작업이 한 번이라도 발생했음을 의미합니다.
SQL_STATUS 가 SQL_END 인 경우 트랜잭션에서 수행한 SQL 문의 수행이 종료하였으나 트랜잭션은 종료되지 않은 상태를
의미합니다. (아래 결과에서 4번 세션의 TX_ID 61397121)
SQL_STATUS 가 SQL_ING 인 경우 트랜잭션에서 수행한 SQL 문장이 수행 중임을 의미합니다. (아래 결과에서 6번 세션의 TX_ID
61397121)
LAST_QUERY_START_TIME 으로 트랜잭션에서 수행한 마지막 SQL문의 시작 시각을 알 수 있습니다. 현재 시각과 차이로 해당
트랜잭션이 얼마나 오래 수행 중인지 판단할 수 있습니다.
UTRANS_TIMEOUT 은 변경 트랜잭션이 수행할 수 있는 최대 소요 시간(초 단위)을 의미합니다.


다음은 변경 트랜잭션에서 언두 영역에 생성한 변경 전 데이터를 바라보는 조회 트랜잭션을 보여주는 출력 결과입니다.


iSQL> /

SESSION_ID TX_ID         STATEMENT_ID     TX_TYPE TX_STATUS     SQL_STATUS

CLIENT_IP            AUTOCOMMIT UTRANS_TIMEOUT  CURRENT_TIME

LAST_QUERY_START_TIME      QUERY

----------------------------------------------------------------------------------
----------------------------------------------------------------------------------
----------------------------------------------------------------------------------
---------------------
462187   34470914       0           SELECT  BEGIN       SQL_ING

SOCKET-INET-SERVER : 127.0.0.1 OFF     0        2015-03-11 16:31:28       2015-03-11

16:28:27       SELECT JOIN_DATE FROM EMP

PID:16067


1 row selected.


TX_TYPE 이 SELECT 인 경우 변경 문장을 한 번도 수행하지 않은 트랜잭션을 의미합니다.


다음은 언두 영역을 사용하는 이중화 트랜잭션을 보여주는 결과입니다.


iSQL> /

SESSION_ID TX_ID         STATEMENT_ID     TX_TYPE TX_STATUS     SQL_STATUS

CLIENT_IP            AUTOCOMMIT UTRANS_TIMEOUT  CURRENT_TIME

LAST_QUERY_START_TIME      QUERY

----------------------------------------------------------------------------------
----------------------------------------------------------------------------------
----------------------------------------------------------------------------------
---------------------
REP     16617476       REP'S TX       UPDATE  BLOCKED      REP'S TX     REP

192.168.1.145:27206     REP'S TX  REP'S TX     2015-03-11 14:21:38       2015-03-11 14:21:34

REMOTE_TX_ID : 3875


1 rows selected.


CLIENT_IP 로 트랜잭션을 보낸 서버의 IP 를 확인할 수 있습니다.
SESSION_ID 로 이중화 객체 이름을 알 수 있습니다.
REP'S TX 라는 값은 로컬에서 확인할 수 없는 값을 의미합니다. (이중화 트랜잭션의 세션, SQL 정보는 로컬에서 확인 불가)
QUERY에 출력된 REMOTE_TX_ID로 원격 서버의 TX_ID 를 알 수 있습니다.


조치 방법


언두 테이블스페이스 크기 증가


언두 테이블스페이스의 데이터 파일을 추가하거나 기존 데이터 파일의 크기를 확장해야 합니다.


언두 사용량이 증가하고 있을 때 조치 할 수 있는 방법 중 하나입니다.


데이터 파일 추가


기존 데이터 파일 이름 확인 후 기존 네이밍 룰에 맞춰 데이터 파일을 추가합니다.


데이터 파일 이름 확인


SELECT RPAD(T.NAME, 20) SPACE_NAME
, RPAD(DECODE(D.AUTOEXTEND, 0, 'OFF', 1, 'ON'), 10) AS AUTOEXTEND
, DECODE(D.MAXSIZE, 0, ROUND((D.CURRSIZE*T.PAGE_SIZE)/1024/1024),
ROUND((D.MAXSIZE*T.PAGE_SIZE)/1024/1024)) AS 'MAXSIZE(KB)'

, D.NAME DATAFILE
, DECODE(D.AUTOEXTEND, 0, 'OFF', 1, 'ON') 'AUTOEXTEND'
FROM V$TABLESPACES T, V$DATAFILES D

WHERE T.ID = D.SPACEID AND T.TYPE = 7

ORDER BY 1, 2 ;


-- 수행 결과 예

iSQL> /
SPACE_NAME      AUTOEXTEND      MAXSIZE(KB) DATAFILE

AUTOEXTEND

-----------------------------------------------------------------------
-----------------------------------------------------
SYS_TBS_DISK_UNDO   ON          2048
/data/heejung.lee/63138/dbs/undo001.dbf       ON

1 row selected.





파란색으로 Italic 되어 있는 부분은 사용자 환경에 맞게 변경가능합니다. 구문 설명은 https://github.com/ALTIBASE/Documents/blob/master

/Manuals/Altibase_7.3/kor/SQL%20Reference.md 에서 SQL Reference 을 참고하세요.


기존 데이터 파일 크기 확장


기존 데이터 파일의 이름과 최대 크기를 확인 후 현재 값 보다 크게 최대 크기를 설정합니다.


데이터 파일 이름과 최대 크기는 위의 쿼리를 이용하여 확인하세요.


파란색으로 Italic 되어 있는 부분은 사용자 환경에 맞게 변경가능합니다. 구문 설명은 https://github.com/ALTIBASE/Documents/blob/master

/Manuals/Altibase_7.3/kor/SQL%20Reference.md 에서 SQL Reference 을 참고하세요.


세션 강제 종료


언두 테이블스페이스를 장시간 사용하는 세션을 강제 종료합니다.


언두 사용량이 증가하고 있을 때 조치 할 수 있는 방법 중 하나입니다.


세션을 강제 종료하더라도 트랜잭션 종류에 따라 트랜잭션 종료 시점이 다를 수 있습니다.


조회 트랜잭션의 경우 세션 종료 즉시 트랜잭션이 종료됩니다.
변경 트랜잭션의 경우 rollback 수행 후 트랜잭션이 종료되므로 언두 사용량 증가 현상이 조치되기까지는 최소 트랜잭션이 진행된
만큼의 시간이 걸릴 수 있습니다.


세션 종료 방법


Altibase 에서 세션 강제 종료





위 문장은 sysdba 사용자만 수행할 수 있습니다.


session_id 는 '트랜잭션 별 언두 테이블스페이스 사용량 모니터링 쿼리' 수행 결과에서 SESSION_ID 값을 입력하고, database_nam

e 은 아래 쿼리로 확인하세요.


SELECT DB_NAME FROM V$DATABASE;


클라이언트 프로세스 종료
클라이언트 프로그램에서 제공하는 방법으로 정상 종료하거나 kill 명령어로 강제 종료합니다.


$ kill -9 process id


장시간 수행하는 트랜잭션 방지


장시간 수행되는 트랜잭션(bulk 트랜잭션)은 아래와 같은 문제들을 발생시킬 수 있습니다.


bulk 성 트랜잭션으로 인해 언두 테이블스페이스 사용량이 증가하는 현상을 피하기 위해 아래와 같은 사항들을 확인 후 권장 사항 참고하여
변경합니다.


1. 작은 단위의 트랜잭션으로 나누어 처리


많은 양의 데이터를 하나의 트랜잭션으로 처리하는 것보다 작은 단위로 나누어 처리하도록 합니다.










2. UTRANS_TIMEOUT 설정


UTRANS_TIMEOUT 을 0 이 아닌 값으로 설정하도록 합니다.
변경 연산(UPDATE, INSERT, DELETE)을 수행하는 트랜잭션의 수행 시간이 길어짐에 따라 발생할 수 있는 문제들을 막기 위해 이 값을
설정합니다.
수행 시간이 프로퍼티 값보다 커지면 세션을 강제 종료되고 트랜잭션을 롤백됩니다.


세션 단위 변경 방법


아래 구문을 이용하거나





커넥션 스트링에 UTRANS_TIMEOUT 속성을 사용할 수 있습니다.









시스템 단위 변경 방법


데이터베이스 운용 중에 아래 문장을 수행하면 이후 접속하는 세션은 변경 값이 적용됩니다.





ALTER SYSTEM 으로 변경한 값은 Altibase 서버를 재시작하면 altibase.properties 에 설정된 값으로 초기화됩니다. 영구적으로 적용을
원한다면 altibase.properties 파일도 수정해주어야 합니다.


3. commit 수행 여부 확인


Non-autocommit 모드로 수행하는 트랜잭션은 반드시 commit 또는 rollback 을 수행해야만 트랜잭션이 종료됩니다.


어플리케이션에서 Non-autocommit 모드로 트랜잭션을 수행하고 commit 또는 rollback 을 수행하지 않는 부분이 있는 지 확인하여 잘못
처리하는 부분이 있다면 수정해야 합니다.

#### 08-12. 테이블/컬럼 정의서


개요
테이블 정의서
컬럼 정의서


개요


사용자 테이블 및 컬럼 정의서 작성 시 필요한 쿼리입니다.


테이블 정의서


테이블 소유자, 테이블 이름, 레코드 수, 테이블 생성 날짜 및 마지막 DDL 수행 날짜 정보를 알 수 있습니다.


레코드는 수는 통계 정보 관련 성능뷰가 추가된 Altibase 6.3.1 부터 확인할 수 있습니다.


버전 별로 쿼리문에 차이가 있으니 각 버전에 해당하는 문장을 참고하세요.


컬럼 정의서


컬럼 이름, 데이터 타입, 크기, NOT NULL, 제약조건 정보 및 컬럼 순서 정보를 알 수 있습니다.


버전 별로 쿼리문에 차이가 있으니 각 버전에 해당하는 문장을 참고하세요.


### 09. 에러메시지

#### 09-01. [Notify : Fetch Timeout] Session Closed by Server.

개요
버전
현상

알티베이스 서버
알티베이스 클라이언트

Orange for ALTIBASE
iSQL
APRE(SESC), SQLCLI, ODBC, CAPI
JDBC

원인

조치

응용 프로그램 로직 확인
FETCH_TIMEOUT 설정 값 변경

세션 프로퍼티 변경
시스템 프로퍼티 변경
FETCH_TIMEOUT 프로퍼티 값 확인 방법


개요


Fetch Timeout 메시지에 대해 설명합니다.


버전


ALTIBASE HDB 모든 버전.


현상


알티베이스 서버


알티베이스 서버 로그에서는 다음과 같은 로그를 볼 수 있습니다.


알티베이스 서버 로그($ALTIBASE_HOME/trc/altibase_boot.log)에서 확인합니다.
버전 별 출력 형태가 다르므로 아래 결과를 참고하세요.
로그 출력 시각, CLIENT_INFO, Caused by Query 를 종합적으로 확인하여 클라이언트 쪽 현상과 관련이 있는지 확인합니다.


ALTIBASE HDB 5 이상





ALTIBASE HDB 4.3.9


ALTIBASE HDB 4.3.9 의 알티베이스 서버 로그에서는 클라이언트 IP 정보를 확인할 수 없습니다. 로그 출력 시각과 Caused by Query
를 통해 판단해야 합니다.


알티베이스 클라이언트


알티베이스 클라이언트 쪽에서 아래와 같은 현상이 발생합니다.


클라이언트에서 알티베이스 서버로 요청을 보내는 시점에 에러 메시지를 확인할 수 있습니다.
따라서 알티베이스 서버 측(altibase_boot.log) 에 남겨진 시각보다 이후에 발생할 수 있습니다.
SELECT 중(Fetch 요청 시) 알티베이스 서버와의 연결이 끊어집니다.
Fetch 결과를 가지고 어플리케이션에서 처리하다가 다시 데이터베이스로 FETCH 를 요청할 때 연결이 끊긴 에러가 발생합니다.
클라이언트 로그에 The session has been closed by the server 메시지가 보입니다. (ALTIBASE HDB 5.5.1 이상 버전에 해당)
클라이언트 로그에 Server closed the connection. 메시지가 보입니다. (ALTIBASE HDB 5.5.1 이상 버전에 해당.)


클라이언트 별 에러 메시지 종류는 아래를 참고하세요.


Orange for ALTIBASE


SELECT 수행 후 아래 결과 창의 스크롤을 내릴 때 아래의 에러 메시지가 발생합니다.





iSQL



iSQL 에서 SELECT 수행 중 아래의 에러 메시지가 발생합니다.


APRE(SESC), SQLCLI, ODBC, CAPI


APRE, SQLCLI, ODBC, CAPI 에서는 Fetch 중 Communication link failure. Server closed the connection. 이 발생합니다.


ALTIBASE HDB 5 부터 해당됩니다.









SESC (ALTIBASE HDB 4 ~ 5.1.5)





JDBC



ALTIBASE HDB 4.3.9 에서는 FETCH 수행 중 아래와 같이 에러가 발생하며 애플리케이션이 중단될 수 있습니다.


ALTIBASE HDB 5 버전부터 6.1.1 까지는 FETCH 중 에러가 발생하고 이후 애플리케이션에서 알티베이스 서버로 요청을 보낼 때마다
연결 단절 에러가 발생합니다.






ALTIBASE HDB 6.3.1 부터는 FETCH 수행 중 The session has been closed by the server 에러 메시지가 발생하고 알티베이스 서버로
요청을 보낼 때마다 연결 단절 에러가 발생합니다.


원인


세션 매니저(SessionManager) 가 FETCH_TMEOUT 에 걸린 세션을 정리하면서 남기는 알림성 메시지입니다.


FETCH_TMEOUT 는 알티베이스 서버 프로퍼티로 SELECT 문을 수행하는 시간이 길어짐에 따라 DBMS 의 자원이 비정상적으로 증가하는 것을
막기 위하여 제공하는 프로퍼티입니다.


클라이언트에서 Fetch 요청하면 DBMS는 Fetch 결과를 일정량씩(통신 버퍼에) 나누어 클라이언트에게 전송합니다. 클라이언트는 통신 버퍼에
담긴 결과셋을 모두 읽으면 다음 결과셋을 DB 서버로 요청합니다.


다음 결과셋을 요청하는 시간 간격이 FETCH_TIMEOUT 설정 값을 초과할 경우 세션을 정리하고 수행 중이던 트랜잭션은 롤백됩니다.


변경 트랜잭션에서 생성한 old image 를 조회 트랜잭션에서 바라보고 있을 경우 변경 트랜잭션이 종료해도 old image 가 정리되지 않습니다.


이런 이유로 SELECT 문이 장시간 수행될 경우 아래와 같이 현상이 발생할 수 있습니다.


메모리 테이블의 경우 메모리 사용량 증가
디스크 테이블의 경우 언두 테이블스페이스 사용량 증가


조치


응용 프로그램 로직 확인


FETCH_TIMEOUT은 주로 응용 프로그램에서 Fetch 결과를 가공하여 다른 작업을 수행하는데 이 처리 시간이 길어지는 경우 문제가 될
수 있습니다.
따라서, 응용 프로그램에서 Fetch 결과를 어떻게 처리하는 지 살펴보고 개선의 여지가 있는 지 파악 후 조치해야 합니다. ( 아래와 같은
부분이 있는 지 확인 후 조치)









FETCH_TIMEOUT 설정 값 변경


FETCH_TIMEOUT 프로퍼티 기본값은 60초입니다. 운영 환경 상 이 값이 작다고 판단되는 경우 변경하여 사용할 수 있습니다.
이 프로퍼티는 시스템 프로퍼티 또는 세션 프로퍼티로 변경할 수 있습니다.


세션 프로퍼티 변경


세션 프로퍼티는 세션 단위로, ALTER SESSION 을 수행한 세션에서 적용되며 ALTER SESSION 을 수행한 이후에 수행된 쿼리에
적용됩니다.





어플리케이션에서도 변경할 수 있습니다.









시스템 프로퍼티 변경


시스템 프로퍼티는 ALTER SYSTEM 을 수행 이후 접속된 세션에 영향을 미칩니다.





변경한 시스템 프로퍼티 값을 알티베이스 서버 프로세스를 재 시작한 후에도 유지하려면 altibase.properties 파일을 수정해야 합니다.





FETCH_TIMEOUT 프로퍼티 값 확인 방법


세션에 적용된 프로퍼티 값 확인 방법


FETCH_TIMEOUT 은 세션 단위로도 변경이 가능하기 때문에 세션마다 설정된 값이 다를 수 있습니다.
세션에 설정된 프로퍼티 값은 V$SESSION 에서 확인할 수 있습니다.


시스템 프로퍼티 값 확인
ALTER SYSTEM 으로 변경하거나 altibase.properties 에 설정한 값은 V$PROPERTY 에서 확인 가능합니다.




#### 09-02. [Warning] Memory allocation failed.

개요
버전
현상
원인 및 조치

커널 파라미터에 의해 메모리 사용이 제한된 경우
32비트 OS에서 알티베이스 서버를 운용하는 경우
물리 메모리가 부족한 경우
참고


개요


[Warning] Memory allocation failed. 에 대해 설명합니다. 이 메시지는 OS 환경으로 인해 메모리 할당이 실패한 경우 발생하는 메시지입니다.


버전


ALTIBASE HDB 모든 버전


현상


$ALTIBASE HOME/trc/altibase boot.log 에[Warning] Memory allocation failed. 에러가발생합니다.


$ALTIBASE_HOME/trc/altibase_boot.log 에 [Warning] Memory allocation failed. 에러가 발생합니다.

[ERR-01051 : Memory allocation failed.] 와 같이 에러가 남을 수도 있습니다.
이 에러는 트랜잭션 수행 중 또는 알티베이스 서버 STARTUP/SHUTDOWN 시에도 발생할 수 있습니다.
이 에러가 발생하면 신규 접속도 실패할 수 있습니다.
주로 HP-UX 에서 발생합니다.


원인 및 조치


커널 파라미터에 의해 메모리 사용이 제한된 경우


가장 많이 발생하는 원인입니다.
HP-UX 의 경우 커널 파라미터에 의해 프로세스가 사용할 수 있는 메모리 크기를 제한할 수 있습니다. 알티베이스 서버 프로세스의 메모리
사용이 이 파라미터의 설정값을 초과할 경우 [Warning] Memory allocation failed. 메시지가 발생합니다.
해당 커널 파라미터는 아래와 같습니다.


maxdsiz      (32bit 프로세스의 경우)
maxdsiz_64bit (64bit 프로세스의 경우)


커널 파라미터 확인 방법은 아래와 같습니다. 단위는 바이트 단위이며 물리 메모리 크기를 고려하여 충분히 크게 설정해야 합니다. 필요하면
시스템 엔지니어에게 요청하여 변경해주세요.


$ /usr/sbin/kctune | grep maxdsiz


32비트 OS에서 알티베이스 서버를 운용하는 경우


32비트 OS는 하나의 프로세스가 사용할 수 있는 메모리 크기가 2G로 제한되어 있어 이를 고려하지 않고 알티베이스 서버를 운용할 경우 이
메시지가 발생할 수 있습니다.


물리 메모리가 부족한 경우


실제 물리 메모리가 부족한 경우도 이 메시지가 발생합니다. top, glance 등 시스템 자원 모니터링 툴을 이용하여 물리 메모리 사용률을
확인하세요.


참고


ALTIBASE HDB 서버의 기본 테이블스페이스는 SYS_TBS_MEM_DATA 입니다. 그래서 CREATE TABLE 수행 시 테이블스페이스를 따로
지정하지 않으면 이 테이블스페이스가 기본으로 지정됩니다.
이 테이블스페이스는 시스템 메모리 테이블스페이스로 테이블의 데이터는 메모리를 사용합니다. 때문에 사용자 의도와 다르게 메모리
사용이 커질 수 있으니 이 점도 확인해보아야 합니다.
ALTIBASE_운영을_위한_HPUX_설정_가이드.pdf

#### 09-03. altibase_boot.log의 TRY_COUNT, LOCK_COUNT, MISS_COUNT 메시지 의미


개요


현상


원인


6.3.1 이하


6.5.1


7.1.0 이상


조치


개요


altibase_boot.log 에  "reset Mutex Statistics" 라는 제목의 메세지가 다량으로 기록되는 경우가 있습니다.  이 메세지에 대한 간략한 설명을
기술합니다.


현상


altibase_boot.log 에 아래와 같은 메세지가 반복해서 기록되는 경우가 있습니다.





원인


이 메세지는 v$mutex 성능뷰테이블(View Table) 의 try_count, lock_count, miss_count 컬럼 값이 최대 값을 초과하여 값이 초기화 될 때
보여지는 메시지입니다.


v$mutex 는 데이터베이스 내 동시성 제어와 관련한 뮤텍스 정보를 기록하는데, 해당 컬럼들의 값이 계속 증가하여 최대 값을 초과하면 value
overflow 가 발생하므로 해당 값을 altibase_boot.log 에 기록한 후 0 으로 초기화합니다.





6.3.1 이하


6.5.1





7.1.0 이상


조치


뮤텍스(Mutex) 관련 정보를 저장할 수 있는 칼럼의 최대 값에 도달한 경우 altibase_boot.log 에 정보를 기록하는 것으로 특별히 심각한 문제가
있거나 조치가 필요한 내용은 아닙니다.

#### 09-04. altibase_qp.log의 8자리 errorcode 확인방법


대상 버전
증상
8자리 에러코드 확인방법
참고 사항


대상 버전


6.1.1 이하 버전.


6.3.1 이상 버전에서는 5자리 에러코드로 표현됨.


증상


알티베이스 버전에 따라 $ALTIBASE_HOME/trc/altibase_qp.log 에 에러코드에 대한 표현방식이 다릅니다.


# 6.1.1 버전 예 (8자리 에러코드로 표현)


[EXEC_DDL_BEGIN : DROP USER ALTITEST CASCADE]

[2013/04/01 11:02:17] [Thread-1105209696] [Level-2]

[EXEC_DDL_END : FAILURE] errorcode 822329545


# 6.3.1 버전 예 (5자리 에러코드 및 에러메시지가 표시됨)


[EXEC_DDL_BEGIN : DROP USER ALTITEST CASCADE]

[2014/05/21 15:12:48] [Thread-1157658976] [Level-2]

[EXEC_DDL_END : FAILURE] ERR-3103c : Undefined user name. The user specified as the owner of a table
or an object was not found in the database.

0001 : DROP USER ALTITEST CASCADE

^    ^


6.3.1 이상 버전에서는 altierr 에서 바로 확인 가능한 에러코드 및 메시지까지 표시되어 에러 확인에 어려움이 없지만, 6.1.1 이하 버전에서는
알수 없는 에러코드 및 에러메시지도 없어 에러내용 확인에 어려움이 있습니다.


8자리 에러코드 확인방법


8자리 10진수 에러코드를 hexa값으로 변환합니다. (윈도우 계산기 이용)


변환된 숫자의 앞 5자리가 에러코드입니다.


예를 들어 위 에러코드 822329545를 hexa로 변환하면 3103C0C9 이 됩니다.


그럼 실제 에러코드는 3103C 이 됩니다.


이렇게 구한 에러코드를 altierr를 이용하여 에러 내용을 확인할 수 있습니다.


참고 사항

#### 09-05. Closed Socket by client is Detected


대상 버전
증상
원인
해결 방안
참고 사항


대상 버전


모든 버전


증상


altibase_boot.log에 다음 에러메시지가 기록됨.


[Notify : Detect] Closed Socket by client is Detected. : Session ID = 7687977


원인


클라이언트에서 disconnect를 호출하면 서버와 클라이언트는 정상적으로 커넥션(세션)이 종료됩니다.


그 외에 클라이언트에서 프로그램을 강제종료하거나 네트워크 문제 등으로 서버가 클라이언트와의 커넥션이 끊어짐을 감지한 경우, 위
에러메시지를 기록하고 해당 세션을 정리합니다.


해결 방안


이미 연결이 끊어진 세션에 대해 로그를 기록하고 세션을 정리하는 것이므로 서버에 문제가 있어서 남기는 에러메시지가 아닙니다.


따라서 알티베이스 서버에 대해 별도의 조치가 필요한 상황도 아닙니다.


다만 해당 시간대에 어플리케이션 재기동 등의 작업이 있었는지 확인하시고.. 그렇지 않다면 네트워크 쪽에 문제가 없는지 체크해보시기
바랍니다.


참고 사항


서비스에 문제가 없었다면 이 에러메시지는 무시하셔도 됩니다.

#### 09-06. ERR-0109D Insufficient memory


대상 버전
증상
원인
해결 방안
참고


대상 버전


모든 버전


본 에러메시지의 경우, 알티베이스 버전에 따라 동일한 오류 원인에 대해 이 에러가 발생할 수도 있고 다른 에러가 발생할 수도 있습니다.


뿐만 아니라 본 에러메시지에 대해 알티베이스 버전에 따라 오류 원인도 다를 수 있습니다.


증상


# 예제


create table t (c1 integer, c2 integer);
create table t2 (c1 integer, c2 integer);
create table t3 (c1 integer, c2 integer);
create index t_idx_01 on t(c1, c2);
create index t2_idx_01 on t2(c1, c2);
create index t3_idx_01 on t3(c1, c2);

insert into t select level, level from dual connect by level < 301;
insert into t2 select level, level from dual connect by level < 301;
insert into t3 select level, level from dual connect by level < 301;
alter system set EXECUTE_STMT_MEMORY_MAXIMUM = 1048576;


# 5.5.1 이상 버전에서 수행 결과


iSQL> select count(*) from (select count(*) from t, t2, t3 group by t.c2, t2.c2, t3.c2);

[ERR-0109D : Insufficient memory]


# 5.3.3 버전에서 수행 결과


iSQL> select count(*) from (select count(*) from t, t2, t3 group by t.c2, t2.c2, t3.c2);

[ERR-01067 : The allocated memory size of statement exceeds the maximum limit ( Name : Query_Execute,
Wanted Memory Size : 1114112, Max size : 1048576 ).]


원인


다음과 같이 altierr 유틸리티를 이용하여 해당 에러에 대한 설명을 확인할 수 있습니다.


메모리테이블에 대해 order by, group by 등의 쿼리를 수행할 때 temporary 영역을 사용하는데, temporary 영역도 메모리 공간을 사용합니다.


알티베이스 서버가 쿼리 수행을 위해 메모리 할당 요청을 했는데 EXECUTE_STMT_MEMORY_MAXIMUM 속성값에 의해 에러를 리턴받은 경우
본 에러가 발생합니다.


해결 방안


다음 프로퍼티 값을 늘려주어야 합니다.


1. 쿼리 수행 중 해당 에러가 발생했다면 아래의 SQL문으로 "EXECUTE_STMT_MEMORY_MAXIMUM" 프로퍼티 값을 확인합니다.


iSQL> set vertical on;
iSQL> select name, value1 from v$property where name='EXECUTE_STMT_MEMORY_MAXIMUM';

NAME  : EXECUTE_STMT_MEMORY_MAXIMUM

VALUE1 : 1073741824


2. ALTER문으로 해당 프로퍼티 값을 적절히 늘려줍니다. (단위는 byte입니다.)


다음은 2G로 설정하는 예제입니다.


iSQL> alter system set EXECUTE_STMT_MEMORY_MAXIMUM = 2147483648;

Alter success.


3. 위 명령어는 수행 이후 서버 전체에 적용되지만 알티베이스를 재구동하면 프로퍼티파일의 설정값으로 적용됩니다.


따라서 영구적으로 적용을 위해서는 프로퍼티파일에도 해당 프로퍼티 값을 변경해야 합니다.


$ALTIBASE_HOME/conf/altibase.properties 파일에서 해당 프로퍼티의 값을 위와 동일하게 변경해 주세요.


참고


1. EXECUTE_STMT_MEMORY_MAXIMUM 프로퍼티는 최대값을 지정하는 프로퍼티로, 미리 설정값만큼 메모리를 할당받는 것은 아닙니다.


그러나 설정값만큼 메모리사용량이 증가할 수 있으므로 설정 시 주의를 요합니다.


따라서 미리 크게 설정하기보다 경험적으로 적절히 늘려주시기를 권장합니다.


2. "Insufficient memory" 에러는 여기에서 설명한 케이스 외에도 다양한 메모리 할당 실패 에러일 수 있습니다.


따라서 위 해결방안으로 문제가 해결되지 않는다면 알티베이스 기술지원으로 연락주세요.

#### 09-07. ERR-311E0 The estimated size of the index key exceeds the maximum limit.


대상 버전
증상
원인
해결 방안
참고 사항


대상 버전


6.1.1 이하 버전.


6.3.1 이상 버전에서는 에러 발생하지 않음.


증상


디스크 테이블에 대해 조인이나 Order by / Group by 등을 사용할 때 다음 에러 발생.


[ERR-311E0 : The estimated size of the index key exceeds the maximum limit.]


원인


다음과 같이 altierr 유틸리티를 이용하여 해당 에러에 대한 설명을 확인할 수 있습니다.


디스크테이블에 대해 조인이나 Order by / Group by 등을 수행할 때 알티베이스는 내부적으로 Temp Tablespace를 사용합니다.


Temp Tablespace는 Disk Tablespace이며 8K의 고정된 Page Size를 가지는데, Temp Tablespace를 사용할 때 8K 이상의 레코드를 만들어야
하는 경우 위와 같은 에러가 발생할 수 있습니다.


참고로 Disk Tablespace의 1Page(8K) 크기를 초과하는 경우는 데이터의 길이가 약 3000Bytes 이상인 경우입니다.


# 예제


iSQL> CREATE TABLE T1( I1 CHAR(6000) ) TABLESPACE SYS_TBS_DISK_DATA;

Create success.

iSQL> insert into t1 values(1);

1 row inserted.

iSQL> insert into t1 values(2);

1 row inserted.

iSQL> insert into t1 values(3);

1 row inserted.

iSQL> SELECT * FROM T1 ORDER BY I1;

[ERR-311E0 : The estimated size of the index key exceeds the maximum limit.]


# 6.3.1 버전 예제


iSQL> CREATE TABLE T1( I1 CHAR(6000) ) TABLESPACE SYS_TBS_DISK_DATA;

Create success.

iSQL> insert into t1 values(1);

1 row inserted.

iSQL> insert into t1 values(2);

1 row inserted.

iSQL> insert into t1 values(3);

1 row inserted.

iSQL> SELECT * FROM T1 ORDER BY I1;

I1

-------------
1

2

3

3 rows selected.


해결 방안


1. TEMP_TBS_MEMORY 힌트를 이용하여 디스크 Temp Tablespace의 1Page(8K) 크기 제약사항을 피할 수 있습니다.


뿐만 아니라 이 힌트는 temp 영역으로 디스크 대신 메모리 영역을 사용하기 때문에 쿼리 성능 개선에도 효과가 있습니다.


iSQL> SELECT /*+ TEMP_TBS_MEMORY */ * FROM T1 ORDER BY I1;

I1

-------------
1

2

3

3 rows selected.


2. 6.3.1 이상 버전으로 업그레이드.


6.3.1 이상 버전에서는 동일 상황에서 에러가 발생하지 않습니다.


참고 사항


#### 09-08. ERR-410D2 (266450) Fetch out of sequence.

개요
버전
현상
원인

커서(CURSOR) OPEN 상태에서 COMMIT/ROLLBACK 수행한 경우
조치

커서(CURSOR) OPEN 상태에서 COMMIT/ROLLBACK 수행한 경우

1. fetch 세션과 변경 DML 세션 분리
2. 통신 버퍼에 담길 만큼만 커서 선언 후 반복적 커서 오픈

3. fetch across commit

참고

버전 별 차이
참고 매뉴얼


개요


여러 개의 레코드를 반환하는 select 문 처리를 위해 커서를 사용하여 레코드 fetch 과정 중 발생하는 오류에 관해 설명한다.


버전


Altibase 6.3.1 이상


현상


여러 개의 레코드를 반환하는 질의문 처리를 위해서는 아래와 같은 과정으로 커서(CURSOR)를 이용해야 한다.



1.

2.

3.

4.



커서 선언 (DECLARE CURSOR)
커서 OPEN (OPEN CURSOR)
커서 FETCH (FETCH CURSOR)
커서 CLOSE/RELEASE (CLOSE CURSOR 또는 RELEASE CURSOR)



위와 같이 커서를 사용하였으나 '3. 커서 FETCH' 단계에서 어느 정도 FETCH 진행하다가 어느 순간 FETCH 할 레코드가 남아있음에도 ERR-41
0D2 (266450) Fetch out of sequence. 에러가 발생한다.


아래는 커서 사용 시 에러가 발생하는 부분과 에러 발생 결과 예시이다.


원인


커서(CURSOR) OPEN 상태에서 COMMIT/ROLLBACK 수행한 경우


Altibase는 ANSI 표준을 준수하여 기본적으로 fetch across commit 방식을 지원하지 않도록 설정되어 있다. 따라서 커서 OPEN 후 COMMIT
또는 ROLLBACK을 수행하면 ANSI 표준에 따라 커서를 강제로 닫는다.


fetch across commit 이란
커서 OPEN 후 단위 레코드를 FETCH하면서 COMMIT을 수행하는 방식으로 ANSI 표준에서 권장하지 않는 방식이다.


이런 이유로 애플리케이션에서 커서 OPEN 후 COMMIT 또는 ROLLBACK을 수행한 경우 에러가 발생할 수 있다.


어느 정도 FETCH 수행하다가 에러가 발생하는 이유는 처음 커서 FETCH 시 일정량의 레코드가 통신 버퍼에 담기기 때문이다. 통신 버퍼에 담긴
레코드를 모두 FETCH하고 다음 일정량의 레코드를 통신 버퍼에 담기 위한 FETCH를 할 때 에러가 발생하게 된다.


아래는 커서 OPEN 상태에서 COMMIT 또는 ROLLBACK을 수행하여 에러가 발생할 수 있는 애플리케이션 작성 예이다.


non-autocommit mode


커서(CURSOR) 선언


커서(CURSOR) OPEN


while(1)
{
커서(CURSOR) FETCH ;

if (sqlca.sqlcode == SQL_SUCCESS) {

/* 변경 DML 수행 */

/* COMMIT 또는 ROLLBACK 수행 */

}
else if (sqlca.sqlcode == SQL_NO_DATA) {

...

}
else {
/* 처음 통신 버퍼에 담긴 레코드를 모두 처리한 후 두 번째 통신 버퍼에 담길 때 이 단계에서 에러가 발생한다.
*/

...

}
}


조치


커서(CURSOR) OPEN 상태에서 COMMIT/ROLLBACK 수행한 경우


이 에러를 조치하기 위한 3가지 방법을 안내한다.


다중 연결을 사용하여 fetch와 변경 DML 작업을 분리하는 방법
통신 버퍼에 담길 만큼만 커서 선언 후 반복적 커서 오픈하는 방법
fetch across commit 을 이용하는 방법


위 방법은 모두 애플리케이션 변경이 필요하다.


1. fetch 세션과 변경 DML 세션 분리


하나의 애플리케이션 내에 다중 연결을 사용하여 COMMIT 또는 ROLLBACK 수행이 커서에 영향이 없도록 한다.


커서를 사용하는 세션과 변경 DML문을 수행하는 세션을 생성한다. 각각 CONN1, CONN2로 정의하여 설명한다.
변경 DML문을 수행하는 세션(CONN2)는 non-autocommit mode로 설정한다.
커서를 사용하는 세션(CONN1)에서 커서 FETCH 수행할 때마다 CONN2에서 변경DML을 수행하고 COMMIT 또는 ROLLBACK


을 수행한다.


아래는 이 조치를 반영한 애플리케이션 작성 예이다.


/* FETCH를 위한 세션 */

EXEC SQL AT conn1 CONNECT;

/* 변경DML 수행을 위한 세션 */

EXEC SQL AT conn2 CONNECT;


EXEC SQL AT conn2 AUTOCOMMIT OFF;

/* CONN1에서 커서 선언, OPEN, FETCH 수행 */

EXEC SQL AT conn1 DECLARE cursor;

EXEC SQL AT conn1 OPEN cursor;
while (1)
{
/* conn1에서 FETCH 수행. */

EXEC SQL AT conn1 FETCH cursor

if (sqlca.sqlcode == SQL_SUCCESS) {

/* conn2에서 변경DML 및 COMMIT 또는 ROLLBACK 수행 */

EXEC SQL AT conn2 INSERT or UPDATE or DELETE ;

/* check sqlca.sqlcode */
if (sqlca.sqlcode == SQL_SUCCESS) {

...

}
else {

...

}

/* conn2에서 수행한 commit 또는 rollback은 conn1의 커서 사용에 영향을 주지 않는다. */

EXEC SQL AT conn2 commit or rollback;

/* check sqlca.sqlcode */
if (sqlca.sqlcode == SQL_SUCCESS) {

...

}
else {

...

}
}
else if (sqlca.sqlcode == SQL_NO_DATA) {

...

}
else {

...

}
}


2. 통신 버퍼에 담길 만큼만 커서 선언 후 반복적 커서 오픈


한번의FETCH 로통신버퍼에담길만큼의레코드수를산정한후LIMIT 절을사용해커서를선언한다.


한 번의 FETCH 통신 버퍼에 담길 만큼의 레 수를 산정한 후 LIMIT 절을 사용해 커서를 선언한다.


Altibase 5 이상 버전의 통신 버퍼 크기는 32K이다. 통신 버퍼에 담기는 레코드 수는 레코드 크기에 따라 다르기 때문에 LIMIT절 마지막
값은 운영 환경에 따라 달라진다.


LIMIT절에 통신 버퍼에 담길 만큼의 레코드 수를 지정하고 커서 오픈 전에 LIMIT절의 시작 값을 변경하면서 커서를 다시 오픈하여
사용한다.


아래는 이 조치를 반영한 애플리케이션 작성 예이다.


/* LIMIT 절을 사용하여 커서를 선언한다. n은 LIMIT절에서 반환할 마지막 레코드 값으로 운영 환경에 맞게
정의해야 한다. 통신 버퍼에 담기는 레코드 수는 레코드 크기에 따라 다르다. */

DECLARE 커서

SELECT ~

FROM ~

WHERE ~

LIMIT :s_start, n;


/* LIMIT 절에 사용한 시작 값을 선언한다. */

s_start = 1;

while(1)
{
/* 조건에 맞는 레코드를 모두 FETCH할 때까지 커서 오픈을 반복한다. */

OPEN 커서

while(1)
{
커서(CURSOR) FETCH ;

if (sqlca.sqlcode == SQL_SUCCESS) {

/* 변경 DML 수행 */
}
else if (sqlca.sqlcode == SQL_NO_DATA) {

...

}
else {

...

}
}

/* COMMIT 또는 ROLLBACK 수행 */

/* LIMIT 절의 시작 값을 지정한다. n은 예시이다. */

s_start = s_start + n ;

}


CLOSE 커서 또는 CLOSE RELEASE 커서


3. fetch across commit


ANSI 표준에서 권장하는 방식은 아니지만 타 DBMS에 익숙한 사용자 편의를 위해 6.3.1부터 추가된 기능이다.


Precompiler(APRE) 의 경우 커서 선언 시 WITH HOLD 커서를 선언하여 사용한다.





참고


버전 별 차이


Altibase 버전에 따라 같은 상황에서 발생하는 에러 메시지는 다를 수 있다.


Non-autocommit 환경에서 FETCH 중 COMMIT/ROLLBACK 수행할 경우 발생하는 에러 메시지 차이는 아래와 같다.

|버전|에러코드|에러메시지|참고 페이지|
|---|---|---|---|
|Altibase 4.3.9|ERR-4103C|Request of fetching data to an unprepared SQL statement.|http://aid.altibase.com/x/6YKZ|
|Altibase 5.3.3 ~ 6.1.1|100|Not found data|http://aid.altibase.com/x/7YKZ|
|Altibase 6.3.1 이상|ERR-410D2|Fetch out of sequence.||



참고 매뉴얼


Altibase 6.3.1부터 제공하는 fetch across commit과 관련한 매뉴얼을 안내한다.


Precompiler User's Manual : 8. 커서 처리 SQL문 -> 커서 관련 내장 SQL문 -> DECLARE CURSOR

CLI User's Manual : 2. ALTIBASE HDB CLI 함수 -> SQLSetStmtAttr

JDBC User's Manual : 3. 고급 기능 -> ResultSet 사용하기 -> Holdability


매뉴얼은 아래 페이지에서 다운로드 할 수 있다.


http://support.altibase.com/kr/manual

#### 09-09. ERR-1105D Unable to begin a new update statement.


개요


버전


현상


원인


해결방안


개요


질의문 수행 시 발생하는 ERR-1105D, ERR-31386 의 발생 원인과 조치 방법에 관해 설명한다.


ERR-1105D : Unable to begin a new update statement.


ERR-31386 : Cannot perform a DML, commit, or rollback inside a query.


버전


6.1.1 이하 버전에는 ERR-1105D 에러코드 및 메시지만 출력됩니다.
6.3.1, 6.5.1 버전과 7.1.0 이상 버전에서는 ERR-31386 에러코드 및 메시지(포멧라인)가 변경되었습니다.


현상


SELECT문 안에서 함수 사용 시 다음 에러가 발생합니다.


6.1.1 이하 버전


iSQL> select func1() from dual;

[ERR-1105D : Unable to begin a new update statement.
0004 : insert into T1 values(C1);

^             ^

]


6.3.1, 6.5.1 버전


iSQL> select func1() from dual;

[ERR-31386 : Cannot perform a DML, commit, or rollback inside a query.

In FUNC1
0004 : insert into T1 values(C1);

^             ^

]


7.1.0 이상 버전


iSQL> select func1() from dual;

[ERR-31386 : Cannot perform a DML, commit, or rollback inside a query.
at "SYS.FUNC1", line 4]


원인


다음과 같이 altierr 유틸리티를 이용하여 해당 에러에 대한 설명을 확인할 수 있습니다.


6.1.1 이하 버전


6.3.1 이상 버전


SELECT문 안에서 함수 사용 시 해당 함수는 SELECT문만 포함해야 합니다.


해당 함수에 INSERT/UPDATE 등이 포함되면 위 에러가 발생합니다.


해결방안


SELECT문 안에서 사용하는 함수는 SELECT문만 포함해야 합니다.


# INSERT문을 포함하는 함수를 SELECT문 안에서 사용했을 때 에러가 발생하는 예제


iSQL> create or replace function func1() return varchar(10) as c1 varchar(10);
2 begin

3 select c1 into c1 from t1;

4 insert into t1 values(c1);

5 return c1;

6 end;

7 /

Create success.

iSQL> select func1() from dual;

[ERR-1105D : Unable to begin a new update statement.
0004 :    insert into T1 values(C1);

^             ^

]


# 위 함수를 EXECUTE 구문을 사용하여 수행하는 예제
EXECUTE 구문에서는 성공적으로 수행됨.


iSQL> select * from t1;

C1

-------------
abc

1 row selected.

iSQL> var c1 varchar(10);
iSQL> exec :c1 := func1();

Execute success.

iSQL> print var;

[ HOST VARIABLE ]

------------------------------------------------------
NAME         TYPE         VALUE

------------------------------------------------------
C1          VARCHAR(10)     abc

iSQL> select * from t1;

C1

-------------
abc

abc

2 rows selected.


# 위 함수를 SELECT문 안에서 사용하기 위해 INSERT문을 제거하고 SELECT문 안에서 사용했을 때 성공적으로 수행되는 예제


iSQL> create or replace function func1() return varchar(10) as c1 varchar(10);
2 begin

3 select c1 into c1 from t1;

4 return c1;

5 end;

6 /

Create success.

iSQL> select func1() from dual;

FUNC1

-------------
abc

1 row selected.

#### 09-10. ERR-4103C (266300) Request of fetching data to an unprepared SQL statement.


개요
버전
현상
원인

커서(CURSOR) OPEN 상태에서 COMMIT/ROLLBACK 수행한 경우
조치

커서(CURSOR) OPEN 상태에서 COMMIT/ROLLBACK 수행한 경우

1. fetch 세션과 변경 DML 세션 분리
2. 통신 버퍼에 담길 만큼만 커서 선언 후 반복적 커서 오픈
참고

버전 별 차이


개요


여러 개의 레코드를 반환하는 select 문 처리를 위해 커서를 사용하여 레코드 fetch 과정 중 발생하는 오류에 관해 설명한다.


버전


Altibase 4.3.9


현상


여러 개의 레코드를 반환하는 질의문 처리를 위해서는 아래와 같은 과정으로 커서(CURSOR)를 이용해야 한다.



1.

2.

3.

4.



커서 선언 (DECLARE CURSOR)
커서 OPEN (OPEN CURSOR)
커서 FETCH (FETCH CURSOR)
커서 CLOSE/RELEASE (CLOSE CURSOR 또는 RELEASE CURSOR)



위와 같이 커서를 사용하였으나 '3. 커서 FETCH' 단계에서 어느 정도 FETCH 진행하다가 어느 순간 FETCH 할 레코드가 남아있음에도 ERR-41
03C (266300) Request of fetching data to an unprepared SQL statement. 에러가 발생한다.


아래는 커서 사용 시 에러가 발생하는 부분과 에러 발생 결과 예시이다.


원인


커서(CURSOR) OPEN 상태에서 COMMIT/ROLLBACK 수행한 경우


Altibase는 ANSI 표준을 준수하여 fetch across commit 방식을 지원하지 않는다. 따라서 커서 OPEN 후 COMMIT 또는 ROLLBACK을 수행하면
ANSI 표준에 따라 커서를 강제로 닫는다.


fetch across commit 이란
커서 OPEN 후 단위 레코드를 FETCH하면서 COMMIT을 수행하는 방식으로 ANSI 표준에서 지양하는 방식이다.


이런 이유로 애플리케이션에서 커서 OPEN 후 COMMIT 또는 ROLLBACK을 수행한 경우 이 에러가 발생할 수 있다.


어느 정도 FETCH 수행하다가 에러가 발생하는 이유는 처음 커서 FETCH 시 일정량의 레코드가 통신 버퍼에 담기기 때문이다. 통신 버퍼에 담긴
레코드를 모두 FETCH하고 다음 일정량의 레코드를 통신 버퍼에 담기 위한 FETCH를 할 때 에러가 발생하게 된다.


아래는 커서 OPEN 상태에서 COMMIT 또는 ROLLBACK을 수행하여 에러가 발생할 수 있는 애플리케이션 작성 예이다.


non-autocommit mode


커서(CURSOR) 선언


커서(CURSOR) OPEN


while(1)
{
커서(CURSOR) FETCH ;

if (sqlca.sqlcode == SQL_SUCCESS) {

/* 변경 DML 수행 */

/* COMMIT 또는 ROLLBACK 수행 */

}
else if (sqlca.sqlcode == SQL_NO_DATA) {

...

}
else {
/* 처음 통신 버퍼에 담긴 레코드를 모두 처리한 후 두 번째 통신 버퍼에 담길 때 이 단계에서 에러가 발생한다.
*/

...

}
}


조치


커서(CURSOR) OPEN 상태에서 COMMIT/ROLLBACK 수행한 경우


이 에러를 조치하기 위한 2가지 방법을 안내한다.


다중 연결을 사용하여 fetch와 변경 DML 작업을 분리하는 방법
통신 버퍼에 담길 만큼만 커서 선언 후 반복적 커서 오픈하는 방법


위 방법은 모두 애플리케이션 변경이 필요하다.


1. fetch 세션과 변경 DML 세션 분리


하나의 애플리케이션 내에 다중 연결을 사용하여 COMMIT 또는 ROLLBACK 수행이 커서에 영향이 없도록 한다.


커서를 사용하는 세션과 변경 DML문을 수행하는 세션을 생성한다. 각각 CONN1, CONN2로 정의하여 설명한다.
변경 DML문을 수행하는 세션(CONN2)는 non-autocommit mode로 설정한다.
커서를 사용하는 세션(CONN1)에서 커서 FETCH 수행할 때마다 CONN2에서 변경DML을 수행하고 COMMIT 또는 ROLLBACK
을 수행한다.


아래는 이 조치를 반영한 애플리케이션 작성 예이다.


/* FETCH를 위한 세션 */

EXEC SQL AT conn1 CONNECT;

/* 변경DML 수행을 위한 세션 */

EXEC SQL AT conn2 CONNECT;


EXEC SQL AT conn2 AUTOCOMMIT OFF;

/* CONN1에서 커서 선언, OPEN, FETCH 수행 */

EXEC SQL AT conn1 DECLARE cursor;

EXEC SQL AT conn1 OPEN cursor;
while (1)
{
/* conn1에서 FETCH 수행. */

EXEC SQL AT conn1 FETCH cursor

if (sqlca.sqlcode == SQL_SUCCESS) {

/* conn2에서 변경DML 및 COMMIT 또는 ROLLBACK 수행 */

EXEC SQL AT conn2 INSERT or UPDATE or DELETE ;

/* check sqlca.sqlcode */
if (sqlca.sqlcode == SQL_SUCCESS) {

...

}
else {

...

}

/* conn2에서 수행한 commit 또는 rollback은 conn1의 커서 사용에 영향을 주지 않는다. */

EXEC SQL AT conn2 commit or rollback;

/* check sqlca.sqlcode */
if (sqlca.sqlcode == SQL_SUCCESS) {

...

}
else {

...

}
}
else if (sqlca.sqlcode == SQL_NO_DATA) {

...

}
else {

...

}
}


2. 통신 버퍼에 담길 만큼만 커서 선언 후 반복적 커서 오픈


한 번의 FETCH 로 통신 버퍼에 담길 만큼의 레코드 수를 산정한 후 LIMIT 절을 사용해 커서를 선언한다.


Altibase 4.3.9 의 통신 버퍼 크기는 64K이다. 통신 버퍼에 담기는 레코드 수는 레코드 크기에 따라 다르기 때문에 LIMIT절 마지막 값은
운영 환경에 따라 달라진다.


LIMIT절에 통신 버퍼에 담길 만큼의 레코드 수를 지정하고 커서 오픈 전에 LIMIT절의 시작 값을 변경하면서 커서를 다시 오픈하여
사용한다.


아래는 이 조치를 반영한 애플리케이션 작성 예이다.


/* LIMIT 절을 사용하여 커서를 선언한다. n은 LIMIT절에서 반환할 마지막 레코드 값으로 운영 환경에 맞게
정의해야 한다. 통신 버퍼에 담기는 레코드 수는 레코드 크기에 따라 다르다. */

DECLARE 커서

SELECT ~

FROM ~

WHERE ~

LIMIT :s_start, n;


/* LIMIT 절에 사용한 시작 값을 선언한다. */

s_start = 1;

while(1)
{
/* 조건에 맞는 레코드를 모두 FETCH할 때까지 커서 오픈을 반복한다. */

OPEN 커서

while(1)
{
커서(CURSOR) FETCH ;

if (sqlca.sqlcode == SQL_SUCCESS) {

/* 변경 DML 수행 */
}
else if (sqlca.sqlcode == SQL_NO_DATA) {

...

}
else {

...

}
}

/* COMMIT 또는 ROLLBACK 수행 */

/* LIMIT 절의 시작 값을 지정한다. n은 예시이다. */

s_start = s_start + n ;

}


CLOSE 커서 또는 CLOSE RELEASE 커서


참고


버전 별 차이


Altibase 버전에 따라 같은 상황에서 발생하는 에러 메시지는 다를 수 있다.


Non-autocommit 환경에서 FETCH 중 COMMIT/ROLLBACK 수행할 경우 발생하는 에러 메시지 차이는 아래와 같다.

|버전|에러코드|에러메시지|참고 페이지|
|---|---|---|---|
|Altibase 4.3.9|ERR-4103C|Request of fetching data to an unprepared SQL statement.||
|Altibase 5.3.3 ~ 6.1.1|100|Not found data|http://aid.altibase.com/x/7YKZ|
|Altibase 6.3.1 이상|ERR-410D2|Fetch out of sequence.|http://aid.altibase.com/x/9oKZ|


#### 09-11. ERR-4109C Invalid session property


현상
동일 메이저 버전 내에서 발생하는 경우


ALTIBASE HDB 5.5.1

ALTIBASE HDB 6.1.1

원인

조치
참고

ALTIBASE HDB 서버 버전 확인 방법(Unix/Linux/Windows 모두 동일)
알티베이스 클라이언트 버전 확인 방법


현상


ALTIBASE HDB 클라이언트에서 알티베이스 서버로 접속이 실패합니다.


아래 두 가지 경우에 해당될 때 에러가 발생할 수 있습니다. 버전에서 앞 세자리가 메이저 버전, 뒷 자리가 패치 버전입니다.


서버와 클라이언트의 메이저 버전이 동일하나 클라이언트의 패치 버전이 서버 보다 높을 때.
클라이언트의 메이저 버전이 서버의 메이저 버전보다 높을 때.


동일 메이저 버전 내에서 발생하는 경우


ALTIBASE HDB 5.5.1


JDBC 클라이언트


ALTIBASE JDBC DRIVER 버전 5.5.1.3.7 을 포함한 상위 버전에서 5.5.1.3.7 보다 낮은 버전의 서버로 접속 시 연결이 실패합니다. (예, JDBC
드라이버 버전 5.5.1.3.7 -> ALTIBASE HDB 서버 5.5.1.3.6)


CLI 클라이언트


5.5.1.4.6 을 포함한 상위 버전 클라이언트에서 5.5.1.4.6 보다 낮은 버전의 서버로 접속 시 연결이 실패합니다. (예, iSQL 버전 5.5.1.4.6 ->
ALTIBASE HDB 서버 5.5.1.4.4)


ALTIBASE HDB 6.1.1


JDBC 클라이언트


ALTIBASE JDBC DRIVER 버전 6.1.1.0.9 을 포함한 상위 버전에서 6.1.1.0.9 보다 낮은 버전의 서버로 접속 시 연결이 실패합니다. (예, JDBC
드라이버 버전 6.1.1.0.9 -> ALTIBASE HDB 서버 6.1.1.0.8)


CLI 클라이언트


6.1.1.1.10 을 포함한 상위 버전 클라이언트에서 6.1.1.1.10 보다 낮은 버전의 서버로 접속 시 연결이 실패합니다. (예, iSQL
버전 6.1.1.1.10 -> ALTIBASE HDB 서버 6.1.1.1.9)


원인


클라이언트가 서버로 접속 시 서버가 모르는 서버 프로퍼티를 요청하여 발생하는 에러입니다.


클라이언트는 접속 시점에 클라이언트 설정에 필요한 서버 프로퍼티를 ALTIBASE HDB 서버로 요청합니다.


그런데 상위 버전에서 서버 프로퍼티가 추가되고 상위 버전의 클라이언트가 하위 버전으로 접속하게 되면 아래와 같은 상황으로 에러가 납니다.


조치


ALTIBASE HDB 서버와 동일한 버전이나 낮은 버전의 클라이언트를 사용합니다.
상위 버전의 클라이언트를 사용해야 할 경우 ALTIBASE HDB 서버 버전도 동일한 버전으로 패치 또는 업그레이드 합니다.


참고


ALTIBASE HDB 서버 버전 확인 방법(Unix/Linux/Windows 모두 동일)


쉘 프롬프트 또는 도스 창에서 아래 명령어 수행.


$ altibase -v


ALTIBASE HDB 서버에 접속하여 아래 쿼리로 조회.


iSQL> SELECT PRODUCT_VERSION FROM V$VERSION;


알티베이스 클라이언트 버전 확인 방법


알티베이스 클라이언트 패키지를 설치했을 경우 (Unix/Linux/Windows 모두 동일)


$ apre -v


ODBC 드라이버의 경우


윈도우 탐색기에서 altiodbc.dll 파일의 속성에서 확인.


JDBC 드라이버의 경우


$ java -jar Altibase.jar

#### 09-12. ERR-5102E ( 331822) Invalid cursor state.


개요
버전
현상
원인 및 조치

1. FETCH 완료 후 커서 CLOSE 하지 않고 같은 이름의 커서를 재사용한 경우
2. FETCH 완료 후 커서 CLOSE 실패 시 예외 처리를 누락한 경우
3. FETCH 할 데이터가 결과가 남아 있는 상태에서 커서를 재사용한 경우


개요


애플리케이션에서 statement 를 핸들링할 때 이미 open 되어 있는 커서를 다시 재사용할 때 발생하는 에러입니다.


버전


ALTIBASE HDB 4 이상


HDB 4.3.9 Error Message 매뉴얼이나 altierr 유틸리티로 Invalid cursor state. 에 대한 설명을 확인할 수는 없지만 HDB 4.3.9 에서도 이 에러가
발생할 수 있습니다.


현상


APRE(또는 SESC)에서 CURSOR FETCH 중 CURSOR DECLARE 또는 CURSOR OPEN 수행 시 Invalid cursor state 발생.
APRE(또는 SESC)에서 CURSOR FETCH 후 CURSOR DECLARE 또는 CURSOR OPEN 수행 시 Invalid cursor state 발생.
SQLCLI 또는 ODBC에서 SQLFetch() 수행 중 SQLExecute(), SQLPrepare(), SQLExecDirect() 중 한 가지 수행 시 Invalid cursor
state 발생.
SQLCLI 또는 ODBC에서 SQLFetch() 수행 후 SQLExecute(), SQLPrepare(), SQLExecDirect() 중 한 가지 수행 시 Invalid cursor
state 발생.


원인 및 조치


1. FETCH 완료 후 커서 CLOSE 하지 않고 같은 이름의 커서를 재사용한 경우


HDB 5 이상 버전에 해당하는 내용입니다. HDB 4 버전에서는 이와 같은 경우 에러가 발생하지 않습니다.
간혹 커서 CLOSE 를 수행하지 않고 같은 이름의 커서를 재사용하여 에러가 발생하는 경우도 있습니다.
예제 코드


declare cursor A;

open cursor A;
fetch cursor A;    // fetch 완료!
// close cursor A;  // 커서 close 처리를 안 함!
declare cursor A;   // 같은 이름의 커서 재사용!


이 원인에 해당하는 경우 커서 CLOSE 구문을 추가합니다.


2. FETCH 완료 후 커서 CLOSE 실패 시 예외 처리를 누락한 경우


커서 CLOSE 가 실패했는데 예외 처리를 하지 않아서 커서 CLOSE 실패 사실을 모르고 같은 이름의 커서를 재사용하는 경우입니다.
HDB 5 이상 버전에 해당하는 내용입니다. HDB 4 버전에서는 이와 같은 경우 에러가 발생하지 않습니다.
예제 코드


declare cursor A;
if ( sqlca.sqlcode != SQL_SUCCESS ) {
예외처리;
}

open cursor A;
if ( sqlca.sqlcode != SQL_SUCCESS ) {
예외처리;
}
fetch cursor A;                     // fetch 완료!
if ( sqlca.sqlcode != SQL_SUCCESS ) {
예외처리;
}

close cursor A;                     // 예외처리 없음.
/* close cursor A 실패!! */

declare cursor A;
if ( sqlca.sqlcode != SQL_SUCCESS ) {
예외처리;
}


이 원인에 해당하는 경우 커서 CLOSE 구문에 예외 처리를 추가하고 커서 CLOSE 가 실패한 원인이 무엇인지 파악합니다.


3. FETCH 할 데이터가 결과가 남아 있는 상태에서 커서를 재사용한 경우


DB 서버에 FETCH 할 데이터가 남아있는 경우 커서 CLOSE 할 때 그 결과가 삭제해버립니다.
다시 말하면 FETCH 할 데이터가 삭제되기 전까지는 같은 이름의 커서를 재사용할 수 없습니다. 재사용하려 한다면 커서를 OPEN 후에
FETCH 해야 함.
예제 코드


이 원인에 해당하는 경우 커서 CLOSE 구문을 추가 후 커서를 재사용하도록 합니다.

#### 09-13. ERR-7101D ( 462877) Protocol header error.


버전
현상

원인

조치
참고


버전


Altibase 모든 버전


현상


Altibase 트레이스 로그 altibase_boot.log 에 아래와 $ALTIBASE_HOME/trc/altibase_boot.log 에 다음 에러메시지가 기록됨.


ERR-7101d(errno=0) Protocol header error.(TCP 127.0.0.1:13036)

Protocol processing failed. Close connection...


원인


다음과같이altierr 유틸리티를이용하여해당에러에대한설명을확인할수있습니다


다음과 같이 altierr 유틸리티를 이용하여 해당 에러에 대한 설명을 확인할 수 있습니다.


이 에러는 알티베이스 서버와 호환되지 않는 버전의 클라이언트에서 서버로 접속 시도 시 서버의 altibase_boot.log에 기록되는 메시지입니다.


이력을 남기는 메시지로, 알티베이스 서버 운영에는 영향이 없습니다.


조치


이 에러메시지가 계속해서 기록된다면 접속 시도하는 클라이언트를 찾아서 서버와 호환 가능한 버전의 클라이언트로 재설치하시기 바랍니다.


참고


알티베이스 5.3.3 미만 버전에서는 서버와 클라이언트의 cm protocol version이 동일해야 클라이언트에서 서버로 접속이 가능합니다.
알티베이스 5.3.3 이상 버전부터는 서버와 클라이언트의 하위호환성을 보장하여 cm protocol version 상관없이 클라이언트에서
동일버전 또는 그 이상 버전의 서버로 접속이 가능합니다.
그러나 반대의 경우, 즉 서버보다 클라이언트의 버전이 높은 경우는 접속되지 않습니다.
여기에서 말하는 버전은 제품버전의 앞 3자리를 의미합니다.(4번째 이하 자리의 패치버전은 버전 체크시 상관 없습니다.)


# 서버 및 클라이언트 버전에 따른 접속 예제














|구분|서버<br>버전|클라이언트<br>버전|접속<br>결과|비고|
|---|---|---|---|---|
|서버 버전 ><br>클라이언트 버전<br>(5.3.3 이상 버전)|6.3.1|5.3.3|성공|5.3.3 이상 버전에서 하위호환성 보장|
|서버 버전 ><br>클라이언트 버전<br>(5.3.3 미만 버전)|6.3.1|4.3.9|실패|서버, 클라이언트 모두 5.3.3 이상 버전일 때 하위호환성 보장.<br>클라이언트가 5.3.3 미만 버전이므로 하위호환성 보장하지 않으며, 4.3.9의 경우 cm protocol<br>version이 동일한 경우에만 접속 가능.|
|서버 버전 <<br>클라이언트 버전|6.1.1|6.3.1|실패|클라이언트 버전이 높은 경우는 알티베이스 버전 상관없이 접속 실패.<br>클라이언트 버전은 서버 버전과 동일하거나 그 보다 낮아야 함.|



# 서버 및 클라이언트 버전 확인 방법


서버 버전 확인 방법


클라이언트 버전 확인 방법


JDBC Driver를 이용한 버전 확인 방법


$ java -jar $ALTIBASE_HOME/lib/Altibase.jar
JDBC Driver Info : Altibase Ver = 6 3 1 0 9 for JavaVM v1 4 CMP:7 1 1 Mar 20 2014 17:07:25


WINDOWS 환경에서 ODBC 라이브러리를 이용한 버전 확인 방법


알티베이스 설치 디렉토리 (예. C:\Program Files (x86)\Altibase\altibase-server-6.3.1) 아래 lib 디렉토리에서
altiodbc dll -> 속성-> 자세히-> 제품버전

#### 09-14. ERR-11030 ( 69680) The data file cannot be extended because the requested size is bigger than the maximum size (FID:<0%d>).


개요
버전
원인

조치
참고


개요


디스크 테이블스페이스 데이터 파일 크기 변경 작업 시 아래와 같은 에러 메시지를 만날 수 있습니다.


iSQL> alter tablespace DISK_USER_TBS alter datafile '/home/altibase_home/dbs/user.dbf' size 200M;

[ERR-11030 : The data file cannot be extended because the requested size is bigger than the maximum size
(FID:0).]


버전


ALTIBASE HDB 4


원인


위 에러 메시지는 AUTOEXTEND OFF 속성을 가진 데이터 파일의 크기를 maxsize 보다 크게 변경할 때 발생합니다.


데이터 파일의 autoextend 속성 및 설정된 크기는 다음 구문으로 확인할 수 있습니다.(autoextend 가 1 이면 on, 0 이면 off)


iSQL> select name, AUTOEXTEND, INITSIZE, MAXSIZE from v$datafiles;

NAME                   AUTOEXTEND INITSIZE       MAXSIZE

---------------------------------------------------------------------------------
-----------------
/home/altibase_home/dbs/temp001.dbf   1      12800        262144
/home/altibase_home/dbs/user.dbf


autoextend on 인 데이터 파일은 maxsize 까지 크기가 자동 증가하기 때문에 초기 설정 크기(INITSIZE) 와 최대 크기(MAXSIZE)에 차이를
보입니다.
하지만, autoextend off 인 데이터 파일의 최대 크기(MAXSIZE) 은 초기 설정 크기(INITSIZE)와 동일하게 설정됩니다.
이 때문에 최대 크기(MAXSIZE) 보다 크게 변경하려는 경우에 위와 같은 에러가 발생할 수 있습니다.


조치


해당 데이터 파일의 AUTOEXTEND 속성을 ON 으로 변경 후 데이터 파일 크기 변경 작업을 진행해야 합니다.
아래 순서대로 진행하면 됩니다.


1) AUTOEXTEND 속성 변경
iSQL> alter tablespace DISK_USER_TBS alter datafile '/home/altibase_home/dbs/user.dbf' autoextend on; Alter

success.

2) 데이터 파일 크기 변경
iSQL> alter tablespace DISK_USER_TBS alter datafile '/home/altibase_home/dbs/user.dbf' size 100M; Alter

success.


참고


사실상 autoextend off 속성을 가진 데이터 파일은 초기 설정 크기(initsize) 만 의미가 있습니다.
CREATE TABLESPACE 구문 또는 ALTER TABLESPACE 구문에서 autoextend off 절을 포함할 경우, size 절 외에 nextsize 및 maxsize 절은
같이 사용하지 못합니다.


같이 사용하면 아래와 같이 SQL 구문 오류가 납니다.


iSQL> create tablespace user_disk_tbs2 datafile 'user2.dbf' size 1M autoextend off next 1M;

[ERR-31001 : SQL syntax error
line 1: parse error create tablespace USER_DISK_TBS2 DATAFILE 'user2.dbf' SIZE 1M autoextend off NEXT 1M


ALTIBASE HDB 4.3.9 에서는 이에 대한 처리가 부족했습니다.
ALTIBASE HDB 5 부터는 이러한 제약이 반영되어 autoextend off 속성을 가진 데이터 파일의 maxsize 를 OS file limit 값으로 설정하게 됩니다.


이 변경으로 4.3.9 와는 다르게 v$datafile 을 조회했을 때 maxsize 를 0 으로 출력하며,


iSQL> select name, AUTOEXTEND, INITSIZE, currsize, MAXSIZE from v$datafiles;

NAME                AUTOEXTEND INITSIZE       CURRSIZE      MAXSIZE

----------------------------------------------------------------------------------
-------------------
/home/altibase_home/dbs/user.dbf  0      128         128         0


size 변경도 가능하게 되었습니다.


iSQL> alter tablespace USER_DISK_TBS alter datafile '/home/altibase_home/dbs/user.dbf' size 8M; Alter

success.

iSQL> select name, AUTOEXTEND, INITSIZE, currsize, MAXSIZE from v$datafiles;

NAME                AUTOEXTEND INITSIZE       CURRSIZE       MAXSIZE

---------------------------------------------------------------------------------
---------------------
/home/altibase_home/dbs/user.dbf  0      128         2048         0


OS file limit 은 ulimit –a 으로 확인할 수 있습니다.


$ ulimit -a
core file size (blocks, -c) 2097151
data seg size      (kbytes, -d) 2097152
file size        (blocks, -f) unlimited
max memory size     (kbytes, -m) unlimited
open files           (-n) 5030
pipe size      (512 bytes, -p) 16
stack size       (kbytes, -s) 131072
cpu time        (seconds, -t) unlimited
max user processes       (-u) 3278
virtual memory     (kbytes, -v) unlimited

#### 09-15. ERR-11036 The data file is in use.


대상 버전
증상
원인
해결 방안
참고 사항


대상 버전


모든 버전


증상


alter tablespace ~ drop datafile 수행 시 아래와 같이 에러가 발생.


iSQL> alter tablespace SYS_TBS_DISK_DATA drop datafile '/altibase/dbs/DISK_DATA2.dbf';

[ERR-11036 : The data file is in use.|ERR-11036 : The data file is in use.]


원인


다음과 같이 altierr 유틸리티를 이용하여 해당 에러에 대한 설명을 확인할 수 있습니다.


한 번이라도 사용된 적이 있는 데이터 파일은 삭제할 수 없습니다.


insert 했다가 delete 하여 해당 데이터파일이 모두 free 공간만 가지고 있더라도 한 번 사용된 적이 있는 데이터파일은 삭제할 수 없습니다.


위 에러는 한번이라도 사용된 적이 있는 데이터파일을 drop 하려고 할 때 발생하는 에러입니다.


참고로 한번도 사용된 적이 없는 데이터파일은 drop 가능합니다.


해결 방안


한번이라도 사용된 적이 있는 데이터파일은 drop 할 수 있는 방법이 없습니다.


해당 데이터파일을 drop 하기 위해서는 테이블스페이스를 재생성해야 합니다.


테이블스페이스 재생성을 위해서는 다음 과정이 필요합니다.


참고 사항

#### 09-16. ERR-11049 ( 69705) Too many pages are allocated ( Maximum Number of Pages= 숫자).


버전
원인
MEM_MAX_DB_SIZE란?
메모리 사용율 조회 방법
조치 방법

변경 방법
변경시 유의사항

사용자 환경 설정 (Linux/Unix)
커널 파라미터(AIX, HP-UX)
참고자료


버전


ALTIBASE HDB 모든 버전


원인


ALTIBASE 메모리 테이블스페이스의 경우는 모든 메모리 테이블스페이스의 합산이 $ALTIBASE_HOME/conf/altibase.properties 에서
MEM_MAX_DB_SIZE를 초과할 수 없습니다. 이 에러메시지는 모든 공간이 소진되어 발생합니다.


MEM_MAX_DB_SIZE란?


물리 메모리에 저장되는 메모리 테이블스페이스(메모리 테이블 또는 메모리 데이터)로 사용할 수 있는 최대 메모리 크기를 의미합니다.
모든 메모리 테이블스페이스를 합한 전체 사용량에 대한 제약입니다.
메모리 테이블스페이스 각각이 사용할 수 있는 최대 크기가 아닙니다.
메모리 테이블에 생성한 인덱스 크기는 포함되지 않습니다.

변경 트랜잭션 수행 시 발생하는 과거 데이터도 포함됩니다.
변경 트랜잭션이 수행될 경우 트랜잭션이 종료되기 전까지 과거 데이터를 유지하는데(MVCC기법), 메모리 테이블의 경우 메모리 테이블
내에 레코드의 복제본을 생성합니다.
메모리 테이블스페이스 생성 시 최대값을 지정하지 않으면 MEM_MAX_DB_SIZE 설정 값만큼 자동 확장됩니다.


메모리 사용율 조회 방법


set linesize 1024

set colsize 20
SELECT TO_CHAR(MEM_MAX_DB_SIZE/1024/1024, '999,999,999') '    MAX(M)',
-- MAX(M)  : MEM_MAX_DB_SIZE 설정 값
TO_CHAR(MEM_ALLOC_PAGE_COUNT*32/1024, '999,999,999') '   TOTAL(M)',
-- TOTAL(M) : 메모리 테이블스페이스로 할당 된 전체 페이지 크기. 체크포인트 이미지 파일 크기를 의미하기도 함.


TO_CHAR((MEM_ALLOC_PAGE_COUNT-MEM_FREE_PAGE_COUNT)*32/1024, '999,999,999') '
ALLOC(M)',       -- ALLOC(M) : 메모리 테이블스페이스에서 사용하는 메모리 크기
(SELECT TO_CHAR(SUM((FIXED_USED_MEM + VAR_USED_MEM))/1024/1024, '999,999,999')
FROM V$MEMTBL_INFO) '   USED(M)',                                 -- USED(M) :

ALLOC 중에서 데이터가 저장된 메모리 크기

TO_CHAR((((MEM_ALLOC_PAGE_COUNT-MEM_FREE_PAGE_COUNT)*32*1024)/MEM_MAX_DB_SIZE)*100,
'99.99') 'USAGE(%)' -- USAGE(%) : MAX 대비 ALLOC 사용률
FROM V$DATABASE ;
MAX(M)     TOTAL(M)     ALLOC(M)     USED(M)   USAGE(%)

----------------------------------------------------------------------------------
-------
5,120       920       621       142   12.13

1 row selected.


위의 조회 결과 ALLOC_SIZE가 MEM_MAX_DB_SIZE까지 도달하였을 때 'Too many pages are allocated' 에러가 발생 합니다.


조치 방법


아래 에러가 발생하지 않게 하기 위해서는 $ALTIBASE_HOME/conf/altibase.properties 에서 MEM_MAX_DB_SIZE 프로퍼티값을 늘려주셔야
합니다.


이 값을 늘려주면 알티베이스 DB Size는 최대 이 사이즈까지 증가할 수 있습니다. 프로퍼티 수정 후 알티베이스를 재구동 해주셔야 적용됩니다.


조치 이후에는 어떤 이유로 메모리 테이블스페이스의 사용량이 증가 하였는지 각 테이블 별 사용량의 조회나 대량 변경작업등이 발생하지
않았는지 확인하여 조치할 필요가 있습니다.


변경 방법



1.


2.


3.



알티베이스 서버 중지

```
$ server stop

```

altibase.properties 파일 변경


알티베이스 서버 프로퍼티 파일($ALTIBASE_HOME/conf/altibase.properties) 에서 MEM_MAX_DB_SIZE 를 변경 후 저장합니다.

```
$ vi $ALTIBASE_HOME/conf/altibase.properties
MEM_MAX_DB_SIZE    = 2G # MEM_MAX_DB_SIZE

```

알티베이스 서버 구동

```
$ server start

```

변경시 유의사항


디스크 공간


메모리 테이블스페이스는 백업 용도로 두 벌의 '메모리 체크포인트 이미지 파일'을 디스크에 저장합니다. 그래서 메모리 데이터 사용량보다 보다

두 배의 디스크 공간이 필요합니다.


MEM_MAX_DB_SIZE 를 크게 설정하면 디스크 사용량도 증가하므로 MEM_MAX_DB_SIZE 변경 전에 디스크 공간을 여유있게 확보해야 합니다.


예) MEM_MAX_DB_SIZE 가 60G 일 경우, 120G 의 디스크 공간이 필요.


사용자 환경 설정 (Linux/Unix)


ulimit -a 로 수행하여 아래 설정들이 OS 에서 허용하는 최대 값으로 설정되어 있는 지 확인해야 합니다.


max memory size
virtual memory


커널 파라미터(AIX, HP-UX)


AIX 경우 /etc/security/limits 파일 내용에서 data, rss, fsize등에 대해서 -1로 설정이 되어 있는지 확인합니다.
HP의 경우 kctune을 통해 maxdsiz_64bit 값이 충분히 크게 설정 되어 있는지 확인합니다. maxdsiz_64bit 값이 ALTIBASE의 property의
MEM_MAX_DB_SIZE값보다 작을 시에도 'Too many pages are allocated' 에러가 발생할 수 있으므로 root 계정으로 ALTIBASE의 property의
MEM_MAX_DB_SIZE보다 크게 설정해야 합니다.
Linux, SunOS 는 해당 없습니다.


참고자료


MEM_MAX_DB_SIZE 란 ?

#### 09-17. ERR-11075 ( 69749) The transaction has exceeded the lock timeout specified by the user.


개요
버전
현상

1. DDL 문장 수행 시 발생하는 경우
2. 메모리 테이블에 변경 트랜잭션 수행 시 발생하는 경우
3. SELECT FOR UPDATE WAIT N (또는 NOWAIT) 을 사용한 SELECT 문장 수행 시 발생하는 경우
4. 이중화 환경에서 altibase_rp.log 에 발생하는 경우
원인

1. DDL 문장 수행 시 발생하는 경우
2. 메모리 테이블에 변경 트랜잭션 수행 시 발생하는 경우


3. SELECT FOR UPDATE WAIT N (또는 NOWAIT) 수행 시
4. 이중화 환경에서 altibase_rp.log 에 발생하는 경우
조치
참고


개요


변경 트랜잭션 수행 시 발생할 수 있는 에러 메시지에 관해 수행합니다.


버전


이 에러 메시지는 Altibase 모든 버전에서 발생할 수 있으나 Altibase 서버 버전에 따라 에러 메시지에 차이가 있습니다.


ALTIBASE HDB 4.3.9 ~ 5.3.3
ERR-11075 ( 69749) The transaction exceeds lock timeout specified by user.


ALTIBASE HDB 5.5.1 이상
ERR-11075 ( 69749) The transaction has exceeded the lock timeout specified by the user.


현상


다음은 이 에러 메시지가 발생하는 주로 발생하는 몇 가지 현상에 대한 예입니다.


1. DDL 문장 수행 시 발생하는 경우

|세션-1|세션-2<br>DDL(truncate문) 수행 시 에러 발생|
|---|---|
|autocommit off;||
|update test_emp_tbl set emp_no = 10;<br>||
|update 수행 중...|truncate table test_emp_tbl;<br>[ERR-11075 : The transaction has exceeded the lock timeout specified by<br>the user.]|



2. 메모리 테이블에 변경 트랜잭션 수행 시 발생하는 경우


세션-1 세션-2


|iSQL> autocommit off;<br>Set autocommit off success.<br>iSQL> update tb_test1 set c10=sysdate where<br>c1=1;<br>1 row updated.|Col2|
|---|---|
||iSQL> select count(*) from tb_test1;<br>COUNT<br>-----------------------<br>1000000<br>1 row selected.<br>iSQL> alter session set TRX_UPDATE_MAX_LOGSIZE=100000000;<br>Alter success.<br>iSQL> alter system set LOCK_ESCALATION_MEMORY_SIZE=100000000;<br>Alter success.<br>iSQL> update tb_test1 set c10=sysdate;<br>[ERR-11075 : The transaction has exceeded the lock timeout specified by the<br>user.]|


3. SELECT FOR UPDATE WAIT N (또는 NOWAIT) 을 사용한 SELECT 문장 수행 시 발생하는 경우

|세션-1|세션-2|
|---|---|
|autocommit off;<br>update test_emp_tbl set emp_no = 10;||
||select * from test_emp_tbl for update wait 1;<br>[ERR-11075 : The transaction has exceeded the lock timeout specified by the user.]|
||select * from test_emp_tbl for update nowait;<br>[ERR-11075 : The transaction has exceeded the lock timeout specified by the user.]|



4. 이중화 환경에서 altibase_rp.log 에 발생하는 경우


이중화 환경에서 $ALTIBASE_HOME/trc/altibase_rp.log 에서 에러가 발생할 수 있습니다.


[2014/08/28 13:00:14] [FAQINTERNAL:Thread-1398925664] [FAQINTERNAL:Level-2]
ERR-11075(errno=0) The transaction has exceeded the lock timeout specified by the user.

[2014/08/28 13:00:14] [FAQINTERNAL:Thread-1398925664] [FAQINTERNAL:Level-3]
INSERT INTO SYS.TB_TEST1 VALUES ( 1000001,,,,,,,,, 2014-08-28 13:00:09.960371 ); (TID : 35456)


원인


이 에러는 객체에 락을 획득하려는데 이미객체에 락이 걸려있어 락을 획득할 수 없을 때 발생합니다.


$ altierr 0x11075
0x11075 ( 69749) smERR_ABORT_smcExceedLockTimeWait The transaction has exceeded the lock timeout

specified by the user.
# *Cause: The transaction failed to lock the object.
# *Action: Increase the transaction's lock timeout value or check whether the data has a transaction with a

long-term lock.


1. DDL 문장 수행 시 발생하는 경우


DDL 구문 수행 시 대상 테이블에 이미 다른 트랜잭션에 의해 LOCK 이 걸려있는 경우 DDL 수행을 위한 LOCK 을 바로 획득하지 못해 DDL
수행이 실패할 수 있습니다.


이것은 알티베이스 서버 프로퍼티 DDL_LOCK_TIMEOUT 설정에 따라 다르게 동작할 수 있습니다.


DDL_LOCK_TIMEOUT = 0 (기본값)
LOCK 을 획득하지 못하면 바로 실패 처리합니다.

DDL_LOCK_TIMEOUT = -1
LOCK 을 획득하지 못할 경우 무한정 대기합니다.
DDL_LOCK_TIMEOUT = 초
DDL 수행 시 LOCK 을 획득하지 못하면 지정한 시간만큼 대기 후 다시 시도합니다.
다시 시도할 때도 LOCK 을 획득하지 못하면 실패하게 됩니다.


2. 메모리 테이블에 변경 트랜잭션 수행 시 발생하는 경우


메모리 테이블에 수행한 변경 트랜잭션으로 트랜잭션 로그 파일의 크기가 LOCK_ESCALATION_MEMORY_SIZE 프로퍼티 설정값를 초과하면
레코드 레벨 IX_LOCK에서 테이블 레벨 X_LOCK 으로 전환합니다. 이 때 다른 세션에서 해당 테이블의 다른 레코드에 IX_LOCK이 걸려 있다면
테이블 레벨 X_LOCK 획득이 실패하여 에러가 발생 할 수 있습니다.


3. SELECT FOR UPDATE WAIT N (또는 NOWAIT) 수행 시


SELECT FOR UPDATE WAIT N 혹은 SELECT FOR UPDATE NOWAIT 을 사용한 SELECT 문장은 해당 레코드에 대해 락을 걸고 수행합니다.


그런데 동일 테이블에 다른 세션에서 먼저 락이 걸려있는 경우 락을 획득하지 못해 에러가 발생할 수 있습니다.


4. 이중화 환경에서 altibase_rp.log 에 발생하는 경우


이중화 반영해야 할 트랜잭션이 로컬 서버의 트랜잭션이 끝나기를 기다리는 경우.

|Active Server|Standby Server|
|---|---|
|alter replication rep1 start;||
||iSQL>  autocommit off;<br>Set autocommit off success.<br>iSQL> insert into tb_test1(c1,c10) values(1000001, sysdate);<br>1 row inserted.|
|iSQL> autocommit off;<br>Set autocommit off success.<br>iSQL> insert into tb_test1(c1,c10) values(1000001, sysdate);<br>1 row inserted.||



Active Server의 insert문이 Standby Server에 반영해야하는데 Standby Server의 로컬 트랜잭션에 의해 이중화 트랜잭션이 반영될 수 없을 때
altibase_rp.log 에 에러 메시지가 기록됩니다.


이 현상은 REPLICATION_LOCK_TIMEOUT 프로퍼티 값에 영향을 받습니다.


이중화 로그를 반영하는 서버(위 예제에서는 Standby Server)에서 REPLICATION_LOCK_TIMEOUT(초) 시간 안에 LOCK을 획득하지 못하면 위
에러가 발생하고 반영하려던 이중화 트랜잭션은 실패합니다.


조치


DDL 수행 시 발생하는 경우
일반적으로 DDL 수행은 가장 idle한 시간에 수행할 것을 권장합니다.
서비스 중지 상태가 아니라면 순간적으로 X LOCK 획득에 실패할 수 있으므로 에러가 발생하면 DDL을 여러번 반복 수행해봅니다.
동일 에러가 계속 발생한다면 대상 테이블이 busy한 상태인지 또는 long run query(수행시간이 오래 걸리는 쿼리 또는 commit 하지
않은 쿼리)가 있는지 확인해 보시고 조치 후 다시 DDL을 수행하시기 바랍니다.


메모리에 변경 트랜잭션 수행 시 발생하는 경우
LOCK_ESCALATION_MEMORY_SIZE 에 의해 위 에러가 발생했다면 대량의 변경 트랜잭션의 가능성이 큽니다.
근본적인 해결 방법은 대량의 변경 연산을 하지 않도록 주의해야합니다.
조건절 및 limit절 등을 이용하여 변경 대상 레코드 수를 적게 하여, 여러 번에 나누어서 변경 트랜잭션을 수행하기를 권장합니다.


SELECT FOR UPDATE문 수행 시 발생하는 경우
SELECT FOR UPDATE문을 성공할 때까지 반복 시도합니다.
커밋되지 않은 트랜잭션을 찾아서 커밋 또는 롤백합니다.
WAIT 옵션의 시간을 늘립니다.


이중화 환경에서 발생하는 경우
이중화 설계 시 동일 레코드에 대해 양 서버에서 동시에 변경하지 않도록 고려되어야 합니다.
본 에러 발생 시 양 서버의 데이터 정합성에 문제가 될 수 있으니 데이터를 확인해야 합니다.


참고


LOCK_ESCALATION_MEMORY_SIZE 관련 추가 설명
ERR-11118 ( 69912) The update log size '?????' is bigger than TRX_UPDATE_MAX_LOGSIZE '?????'

#### 09-18. ERR-11118 ( 69912) The update log size '?????' is bigger than TRX_UPDATE_MAX_LOGSIZE '?????'


개요
버전
현상
원인

조치

UPDATE 대상 레코드 수 줄이기
TRX_UPDATE_MAX_LOGSIZE 프로퍼티 설정값 변경
참고

관련 버그


개요


메모리 테이블에 변경 트랜잭션 수행 중 발생하는 에러에 관해 설명합니다.


버전


Altibase 4.3.9 이상


현상


메모리 테이블에 대해 변경 트랜잭션 수행 중 발생할 수 있는 에러입니다.


Altibase 버전에 따라 에러 코드에 차이가 있습니다.


알티베이스 버전에 따른 에러 코드 차이
Altibase 5 이상


ERR-11118 ( 69912) The update log size '?????' is bigger than TRX_UPDATE_MAX_LOGSIZE '?????'


Altibase 4.3.9


ERR-110C3 ( 69827) The update log size '?????' is bigger than TRX_UPDATE_MAX_LOGSIZE '?????'


원인


하나의 변경 트랜잭션에 의해 생성되는 온라인 트랜잭션 로그의 크기가 TRX_UPDATE_MAX_LOGSIZE 설정 값을 초과하여 발생하는
에러입니다.


TRX_UPDATE_MAX_LOGSIZE는 알티베이스 서버 프로퍼티로, 대량의 변경 트랜잭션에 의해 생성되는 메모리 테이블의 버전닝으로 인해
메모리를 과도하게 사용하는 것을 막기 위한 역할을 합니다.


메모리 테이블의 버전닝?


알티베이스는 동시성 제어를 위해 다중 버전 동시성 제어 (MVCC, Multi-Version Concurrency Control) 기법을 사용합니다. MVCC란 하나의
레코드에 대해 DML구문이 발생할 경우 그 레코드는 원래 상태 그대로 둔 채, 그 레코드의 복사본에 DML 구문을 실행하여 그 레코드의 새로운
버전을 만드는 것을 말합니다. 이 기법으로 하나의 레코드에 대한 조회 트랜잭션은 변경 트랜잭션에 영향을 받지 않습니다.


디스크와 메모리는 각각이 가지고 있는 특성 상 디스크 테이블은 in-place, 메모리 테이블은 Out-place기법으로 서로 다른 MVCC 기법이
사용됩니다.


메모리 테이블의 Out-place MVCC는 하나의 레코드에 update가 일어나면, 기존 레코드는 그대로 두고 새 공간에 새 버전을 추가함으로서 여러
버전을 유지합니다. 이로 인해 메모리가 증가하는 등 시스템에 부하가 발생하는 것을 방지하기 위해 TRX_UPDATE_MAX_LOGSIZE 및
LOCK_ESCALATION_MEMORY_SIZE 프로퍼티를 제공합니다.


INSERT는 이전 버전이 없기 때문에 버저닝이 발생하지 않고, DELETE는 새로운 버전이 없기 때문에 delete flag 만 세팅하므로 여러 버전의
버저닝이 발생하지 않습니다.


조치


이 에러가 발생할 경우 아래의 방법 중 하나로 조치할 수 있습니다.


UPDATE 대상 레코드 수 줄이기


UPDATE문에 의해 한번에 변경되는 레코드 수를 줄여 하나의 트랜잭션에 의해 생성되는 트랜잭션 로그의 양을 줄입니다.


한 테이블에 변경해야 할 레코드가 많은 경우






하나의 트랜잭션에서 여러 테이블에 UPDATE를 수행하는 경우


TRX_UPDATE_MAX_LOGSIZE프로퍼티는 트랜잭션 단위로 적용되므로 아래와 같이 하나의 트랜잭션에 여러 문장이 사용된 경우,
COMMIT 또는 ROLLBACK을 수행할 때까지 TRX_UPDATE_MAX_LOGSIZE가 증가할 수 있습니다.


iSQL> AUTOCOMMIT OFF;

iSQL> UPDATE T1 SET C1 = 100;

iSQL> COMMIT;                 -- commit 주기를 짧게 가져간다.

iSQL> UPDATE T2 SET C1 = 200;

iSQL> COMMIT;


TRX_UPDATE_MAX_LOGSIZE 프로퍼티 설정값 변경


TRX_UPDATE_MAX_LOGSIZE 프로퍼티의 기본값은 10M입니다. 이 값이 너무 작다고 판단될 경우 세션 또는 시스템 레벨에서 값을 변경할 수
있습니다.


먼저, 특정 트랜잭션에서 생성하게 될 트랜잭션 로그의 크기를 산정하는 방법과 TRX_UPDATE_MAX_LOGSIZE 변경 시 주의사항에 관해 설명한
후 변경 방법에 관해 설명합니다.


트랜잭션의 TRX_UPDATE_MAX_LOGSIZE 값 산정


TRX_UPDATE_MAX_LOGSIZE를 변경하기 위해 특정 트랜잭션에서 사용할 트랜잭션 로그의 양을 산정하는 방법입니다.


|세션1 - UPDATE 문 수행|세션2 - 성능 뷰 조회|
|---|---|
|iSQL> AUTOCOMMIT OFF;<br>iSQL> UPDATE ORDER_LINE SET<br>OL_DELIVERY_D = SYSDATE LIMIT 1;<br>-- limit 1 주고 수행||


|Col1|아래 쿼리문을 수행하여 나온 결과 중 UPDATE_SIZE * 'update 대상<br>레코드 수' 가 해당 트랜잭션에서 생성하게 될 트랜잭션 로그의<br>크기입니다.<br>iSQL> SELECT ST.SESSION_ID SESSION_ID,<br>TX.ID TX_ID<br>, TX.UPDATE_SIZE<br>, SUBSTR(ST.QUERY, 1, 100) QUERY<br>FROM V$TRANSACTION TX,<br>V$STATEMENT ST<br>WHERE TX.ID = ST.TX_ID AND<br>TX.UPDATE_SIZE <> 0 ;|
|---|---|
|iSQL> ROLLBACK;||


TRX_UPDATE_MAX_LOGSIZE 변경 시 주의사항


TRX_UPDATE_MAX_LOGSIZE는 LOCK_ESCALATION_MEMORY_SIZE 보다 작게 설정할 것을 권장합니다.
메모리 테이블 MVCC로 인해 메모리가 증가하는 것을 방지하기 위해 TRX_UPDATE_MAX_LOGSIZE와
LOCK_ESCALATION_MEMORY_SIZE 프로퍼티를 제공하고 있습니다.


하나의 트랜잭션에서 생성하는 트랜잭션 로그의 크기가
TRX_UPDATE_MAX_LOGSIZE를 초과할 경우 해당 트랜잭션을 에러 처리하고 롤백합니다.
LOCK_ESCALATION_MEMORY_SIZE를 초과할 경우 해당 트랜잭션의 LOCK 모드가 레코드 레벨 IX_LOCK에서 테이블 레벨 X
LOCK으로 전환됩니다.


X LOCK의 경우 대상 테이블에 대한 조회 트랜잭션도 대기하게 하므로 서비스에 문제를 발생시킬 수도 있습니다.
이런 문제를 방지하기 위해서는 TRX_UPDATE_MAX_LOGSIZE를 LOCK_ESCALATION_MEMORY_SIZE보다 작게 설정하여 X LOCK으로
전환하는 일이 발생하지 않도록 해야 합니다.


변경 방법


프로퍼티 설정값 확인 방법


TRX_UPDATE_MAX_LOGSIZE는 LOCK_ESCALATION_MEMORY_SIZE 보다 작게 설정해야 하므로 두 프로퍼티를 같이 확인합니다.






세션 단위 변경 방법


ALTER SESSION 수행 후 수행하는 트랜잭션에 적용됩니다.


iSQL> ALTER SESSION SET TRX_UPDATE_MAX_LOGSIZE = 52428800;    -- 값은 byte 단위


시스템 레벨 변경 방법


ALTER SYSTEM 수행 후 신규 세션에서 수행하는 트랜잭션부터 영향을 받습니다. ALTER SYSTEM 으로 변경한 값은 Altibase 서버 구동
중에만 적용되며 Altibase 서버를 재구동하면 기본값으로 되돌아갑니다.


iSQL> ALTER SYSTEM SET TRX_UPDATE_MAX_LOGSIZE = 52428800;


변경값을 Altibase 서버에 영구적으로 반영하고 싶을 경우 altibase.properties 파일도 변경합니다.


iSQL> ALTER SYSTEM SET TRX_UPDATE_MAX_LOGSIZE = 52428800;


shell> vi $ALTIBASE_HOME/conf/altibase.properties         -- altibase.properties 파일을 열고
TRX_UPDATE_MAX_LOGSIZE를 찾아 값을 변경 후 저장.

TRX_UPDATE_MAX_LOGSIZE = 52428800


위와 같이 수행하면 Altibase 서버 재구동을 하여도 변경값을 유지할 수 있습니다.


참고


관련 버그


몇몇 버전에서 TRX_UPDATE_MAX_LOGSIZE 관련 버그로 인해 TRX_UPDATE_MAX_LOGSIZE의 설정값을 변경하여도 정상적으로 동작하지
않는 경우가 있습니다.


|Altibase 서버<br>버전|현상|버그|
|---|---|---|
|4.3.9.103 ~<br>4.3.9.133|TRX_UPDATE_MAX_LOGSIZE의 기본값이 10M인데 V$SESSION의 TRX_UPDATE_MAX_LOGSIZE 컬럼<br>값이 0(무제한)으로 설정된 현상.|BUG-20511|
|4.3.9.163 ~<br>4.3.9.165|TRX_UPDATE_MAX_LOGSIZE를 잘못 읽는 버그로 TRX_UPDATE_MAX_LOGSIZE로 인해 에러가 발생해야<br>할 상황에서 에러가 발생하지 않는 현상.|BUG-26311|


#### 09-19. ERR-11183 ( 70019) Insufficient page descriptor area in the temp table.

개요
버전
현상
원인

조치


개요


질의문 수행 시 발생하는 ERR-11183 ( 70019) Insufficient page descriptor area in the temp table. 의 발생 원인과 조치 방법에 관해
설명한다.


버전


Altibase 서버 6.3.1 이상
Altibase 서버 7.1.0.5.0 까지

Altibase 7.1.0.5.1 이상은 BUG-48369 반영으로 이 에러가 발생하지 않는다.


현상


질의문에 디스크 테이블이 사용되고 SORT 또는 HASH 연산 처리가 필요한 질의문을 수행할 때 발생할 수 있다.


원인


이 에러는 아래의 조건을 만족하는 경우 발생한다.


디스크 임시 테이블스페이스의 최대 크기가 TEMP_MAX_PAGE_COUNT 보다 크게 설정되어 있고
TEMP_MAX_PAGE_COUNT를 초과한 크기의 디스크 임시 테이블스페이스가 필요한 질의문을 수행한 경우


Altibase 서버는 디스크 테이블에 대한 질의 처리 과정에서 SORT/HASH 연산이 필요할 경우 빠른 연산을 위해 메모리에 일정 크기를 할당하여
사용한다. 만약 정해진 크기의 메모리를 모두 사용하고 SORT/HASH 연산을 위한 공간이 추가적으로 필요한 경우 디스크 임시 테이블스페이스를
사용한다. 이때 디스크 임시 테이블스페이스로 사용할 수 있는 전체 페이지 수는 TEMP_MAX_PAGE_COUNT 프로퍼티에 의해 정해져 있다.


Insufficient page descriptor area in the temp table. 에러 발생 예


디스크 임시 테이블스페이스의 최대 크기가 2G, TEMP_MAX_PAGE_COUNT프로퍼티의 값이 32767(256MB) 로 설정되어 있고,


iSQL> set vertical off;

iSQL> set linesize 1024

iSQL> set colsize 25


-- 디스크 임시 테이블스페이스가 최대 2G까지 사용할 수 있게 설정되어있다.

iSQL> SELECT 'DISK_TEMP_TBS_MAX_SUM'
, SUM(DECODE(F.MAXSIZE, 0, F.CURRSIZE, F.MAXSIZE)*TBS.PAGE_SIZE) AS 'MAX_SIZE(BYTE)'
FROM V$DATAFILES F,
V$TABLESPACES TBS

WHERE F.SPACEID = TBS.ID
AND TBS.TYPE IN (5, 6);
'DISK_TEMP_TBS_MAX_SUM' MAX_SIZE(BYTE)

--------------------------------------------------
DISK_TEMP_TBS_MAX_SUM 2147475456

1 row selected.


-- TEMP_MAX_PAGE_COUNT 프로퍼티 값의 단위는 페이지 수로, 크기로 환산하면 256MB이다.

-- 아래 결과는 디스크 임시 테이블스페이스로 사용할 수 있는 페이지는 256MB임을 의미한다.
iSQL> SELECT NAME, VALUE1, VALUE1*8192 FROM V$PROPERTY WHERE NAME =
'TEMP_MAX_PAGE_COUNT';

NAME            VALUE1           VALUE1*8192

--------------------------------------------------------------------------------
TEMP_MAX_PAGE_COUNT    32767           268427264

1 row selected.


SORT 연산을 위한 크기가 TEMP_MAX_PAGE_COUNT프로퍼티 값 32767(256MB)을 초과하는 질의문을 수행한 경우.


iSQL> select count(*) from (select count(*) from t, t2, t3 group by t.c2, t2.c2, t3.c2);

[ERR-11183 : Insufficient page descriptor area in the temp table.]


질의문 수행 중 디스크 임시 테이블스페이스 사용량을 조회하면 디스크 임시 테이블스페이스 사용량이 TEMP_MAX_PAGE_COUNT프로퍼티
값과 근사함을 볼 수 있다.


조치


디스크 임시 테이블스페이스의 최대값에 맞춰 TEMP_MAX_PAGE_COUNT 프로퍼티의 값을 변경한다.


1. 디스크 임시 테이블스페이스의 최대값 확인


TEMP_MAX_PAGE_COUNT는 모든 디스크 임시 테이블스페이스가 최대로 사용될 상황을 가정하고 설정해야 한다. 그러므로 아래
질의문으로 Altibase 서버에 생성한 모든 디스크 임시 테이블스페이스의 최대값을 더한 값을 확인한다.





2. TEMP_MAX_PAGE_COUNT 프로퍼티 적정값 계산


TEMP_MAX_PAGE_COUNT 프로퍼티의 단위는 페이지 수로, 값은 아래 수식으로 계산한다.


TEMP MAX PAGE COUNT = 디스크임시테이블스페이스최대값총합 / 8192


디스크 임시 테이블스페이스 최대값 별 TEMP_MAX_PAGE_COUNT 값


TEMP_MAX_PAGE_COUNT 산정 예시


디스크 임시 테이블스페이스의 최대값 총 합이 17179869184 byte(16GB) 인 경우, 17179869184 / 8192 = 2097152로
TEMP_MAX_PAGE_COUNT 프로퍼티의 값은 2097152가 된다.


디스크 임시 테이블스페이스의 최대값 총 합 별 TEMP_MAX_PAGE_COUNT 설정 값


8G 의 경우 TEMP_MAX_PAGE_COUNT = 1048576
16G 의 경우 TEMP_MAX_PAGE_COUNT = 2096128
32G 의 경우 TEMP_MAX_PAGE_COUNT = 4192256
64G 의 경우 TEMP_MAX_PAGE_COUNT = 8388608



3. TEMP_MAX_PAGE_COUNT 프로퍼티 변경


TEMP_MAX_PAGE_COUNT는 Altibase 운용 중 시스템 레벨로 변경할 수 있다.


ALTER SYSTEM SET TEMP_MAX_PAGE_COUNT = value;


V$PROPERTY를 조회하여 변경값을 확인한다.


SELECT NAME, VALUE1 FROM V$PROPERTY WHERE NAME = 'TEMP_MAX_PAGE_COUNT';


ALTER SYSTEM 으로 변경한 값이 Altibase 서버 재구동 후에도 반영되도록 Altibase 서버 설정 파일도 변경한다.


shell> cd $ALTIBASE_HOME/conf
shell> vi altibase.properties    # altibase.properties 파일에 TEMP_MAX_PAGE_COUNT이 없으면
추가하고 있으면 기존값을 변경한다.

TEMP_MAX_PAGE_COUNT = value;


4. TEMP_MAX_PAGE_COUNT 프로퍼티 변경 시 고려사항


아래 세 개 프로퍼티는 TEMP_MAX_PAGE_COUNT에 영향을 받는다.


TOTAL_WA_SIZE
SORT_AREA_SIZE
HASH_AREA_SIZE


따라서 TEMP_MAX_PAGE_COUNT를 변경하면 이 프로퍼티들도 변경해야한다.


각 프로퍼티 별 권고값은 아래와 같다. 권고값은 기본값 비율에 따라 산정한 것으로 운용 중 해당 프로퍼티의 적정값은 변경될 수 있다.


TOTAL_WA_SIZE : TEMP_MAX_PAGE_COUNT의 256배
SORT_AREA_SIZE : TEMP_MAX_PAGE_COUNT의 2배
HASH_AREA_SIZE : TEMP_MAX_PAGE_COUNT의 8배


예를들어 TEMP_MAX_PAGE_COUNT = 1048576 로 변경할 경우 각 프로퍼티의 권고값은 아래와 같다.


TOTAL_WA_SIZE = 1048576*256 = 268435456 (단위는 바이트)
SORT_AREA_SIZE = 1048576*2 = 2097152 (단위는 바이트)
HASH_AREA_SIZE = 1048576*8 = 8388608 (단위는 바이트)


아래 세 프로퍼티도 TEMP_MAX_PAGE_COUNT와 마찬가지로 Altibase 운용 중 시스템 레벨로 변경할 수 있다.


ALTER SYSTEM SET TOTAL_WA_SIZE = value;

ALTER SYSTEM SET SORT_AREA_SIZE = value;

ALTER SYSTEM SET HASH_AREA_SIZE = value;


V$PROPERTY를 조회하여 변경값을 확인한다.


SELECT NAME, VALUE1 FROM V$PROPERTY WHERE NAME IN ('TOTAL_WA_SIZE', 'SORT_AREA_SIZE',
'HASH_AREA_SIZE');


ALTER SYSTEM 으로 변경한 값이 Altibase 서버 재구동 후에도 반영되도록 Altibase 서버 설정 파일도 변경한다.


shell> cd $ALTIBASE_HOME/conf
shell> vi altibase.properties    # altibase.properties 파일에서 각 프로퍼티를 찾아서 변경합니다.

TOTAL_WA_SIZE            = 134217728 # default = 134217728

SORT_AREA_SIZE            = 1048576  # default = 1048576

HASH_AREA_SIZE            = 4194304  # default = 4194304



5. 프로퍼티 변경 시 영향도


TOTAL_WA_SIZE 프로퍼티의 경우 설정 즉시 V$MEMSTAT의 ALLOC_SIZE와 MAX_TOTAL_SIZE가 증가하며 동시에 Altibase 서버
프로세스의메모리도증가한다


프로세스의 메모리도 증가한다.


메모리가 증가하는 영역은 Altibase 버전에 따라 다르다. Altibase 7 의 경우 Temp_Memory 영역이 증가하며, Altibase 6.3.1, 6.5.1의
경우 Storage_Disk_Buffer 영역이 증가한다.


V$MEMSTAT 확인 방법은 아래와 같다.









Unix/Linux의 경우 ps명령어로 Altibase 서버 프로세스의 메모리 증가 여부를 확인할 수 있다.


TOTAL_WA_SIZE 변경 직후 확인 시 vsz가 증가하며 sort/hash 연산 발생할 때 rss가 증가한다.












#### 09-20. ERR-11184 ( 70020) Insufficient free space in work area

개요
버전
현상
원인

조치

Work Area 설정값 확인 방법
Work Area 설정값 변경 방법
Work Area 설정값 변경 시 주의사항


개요


질의문 수행 시 발생하는 ERR-11184 ( 70020) Insufficient free space in work area 에러의 발생 원인과 조치 방법에 관해 설명한다.


버전


Altibase 서버 6.3.1 이상


현상


질의문에 디스크 테이블이 사용되고 SORT 또는 HASH 연산 처리가 필요한 질의문을 수행할 때 발생할 수 있다.


원인


Work Area라는 메모리 공간이 부족하여 발생하는 에러이다.


Work Area는 디스크 테이블 데이터에 대해 SORT/HASH 연산 수행 시 보다 나은 성능을 위해 Altibase 서버 구동 시 OS로부터 예약해놓은 일정
크기의 메모리 공간을 의미한다.


질의문 수행 시 SORT 또는 HASH 연산이 필요할 경우 정해진 크기만큼 Work Area에서 할당받아 사용한다. SORT 연산이 필요한 경우 Work
Area에서 SORT_AREA_SIZE 만큼 할당받아 사용하고 HASH 연산이 필요한 경우 Work Area에서 HASH_AREA_SIZE 만큼 할당받아 사용한다.


SORT/HASH 연산이 필요한 트랜잭션이 동시에 여러 개 수행될 수 있다. 이 때 SORT_AREA_SIZE 또는 HASH_AREA_SIZE를 Work Area로부터
할당받으려는데 Work Area에서 할당해 줄 여유 메모리가 없는 경우 이 에러가 발생한다.


조치


Work Area가 부족하여 발생한 것이므로 Work Area 크기를 현재값보다 크게 증가시켜야 한다.


Work Area는 Altibase 서버 프로퍼티 TOTAL_WA_SIZE 로 그 크기를 설정할 수 있다.


Work Area 설정값 확인 방법


아래 문장으로 현재 설정값을 확인한다.


SELECT NAME, VALUE1 FROM V$PROPERTY WHERE NAME = 'TOTAL_WA_SIZE';


Work Area 설정값 변경 방법


ALTER SYSTEM 구문으로 변경한다.


ALTER SYSTEM SET TOTAL_WA_SIZE = value ; -- value는 바이트 단위이다.


ALTER SYSTEM 으로 변경한 값이 Altibase 서버 재구동 후에도 반영되도록 Altibase 서버 설정 파일도 변경한다.


shell> cd $ALTIBASE_HOME/conf
shell> vi altibase.properties    # altibase.properties 파일에서 TOTAL_WA_SIZE 프로퍼티를 찾아서
변경.

TOTAL_WA_SIZE            = 134217728 # default = 134217728


Work Area 설정값 변경 시 주의사항


TOTAL_WA_SIZE를 현재 설정값보다 크게 변경하면 V$MEMSTAT의 크기가 증가하고 Altibase 서버 프로세스 메모리 사용량, VSZ도
증가한다.
Altibase 7 이상의 경우 V$MEMSTAT의 Temp_Memory 영역이 증가하고
Altibase 6.3.1, 6.5.1 의 경우 V$MEMSTAT의 Storage_Disk_Buffer 영역이 증가한다.
디스크 SORT/HASH 연산이 필요한 질의문 수행 중(Work Area를 사용하는 트랜잭션 수행)에 ALTER SYSTEM SET TOTAL_WA_SIZE
문장을 수행할 경우 이 문장은 먼저 수행한 트랜잭션이 종료할 때까지 대기한다.
ALTER SYSTEM SET TOTAL_WA_SIZE = ... 구문 수행 중에 디스크 SORT/HASH 연산이 필요한 질의문이 수행될 경우 해당 트랜잭션은
ALTER SYSTEM 문장이 끝날 때까지 대기한다.

#### 09-21. ERR-21010 Value overflow


대상 버전
증상
원인
해결 방안
참고 사항


대상 버전


모든 버전


증상


INSERT/UPDATE 등 수행 시 다음 에러 발생.


[ERR-21010 : Value overflow]


원인


다음과 같이 altierr 유틸리티를 이용하여 해당 에러에 대한 설명을 확인할 수 있습니다.





즉, 입력한 값이 해당 데이터타입에서 지원하는 범위를 초과한 경우 발생하는 에러입니다.


# 예제


iSQL> create table test(i1 integer);

Create success.

iSQL> insert into test values(2147483648);

[ERR-21010 : Value overflow
0001 : insert into TEST values(2147483648)

^     ^

]
iSQL> insert into test values(2147483647);

1 row inserted.


integer 타입 값의 범위는 -2,147,483,647 ~ 2,147,483,647 까지의 정수 값입니다.


따라서 컬럼에 저장하려던 값이 integer 값의 범위를 벗어났기 때문에 해당 에러가 발생한 것입니다.


해결 방안


특정 컬럼에 저장하려는 입력값이 컬럼 데이터타입의 최대크기를 초과하는 값이 아닌지 확인해 봅니다.


최대크기를 초과할 경우, 입력값을 수정하던지 컬럼의 데이터타입 변경이 필요합니다.


참고 사항


알티베이스에서 지원하는 데이터타입(Data Type)별 값의 범위는 http://support.altibase.com/kr/manual 내 General Reference 매뉴얼에서
확인하실 수 있습니다.

#### 09-22. ERR-21011 : Invalid literal


개요
버전
원인


개요


Invalid literal 에러 발생 원인과 발생 사례에 대해 설명합니다.


버전


ALTIBASE HDB 모든 버전.


원인


TO_NUMBER, CAST 등의 변환 함수나 비교 연산자 사용 시 비교 대상 간의 데이터 타입이 일치하지 않을 때 발생합니다.


자동 형 변환 과정에서 변환하려는 데이터 타입으로 변환할 수 없는 값을 가질 때 발생할 수도 있습니다.


사례 1. UNION, UNION ALL 사용 시 맵핑이 되는 컬럼에 대해 데이터 타입이 다를 때.


iSQL> SELECT 0 from DUAL

2 UNION

3 SELECT 'A' from DUAL;

0

-------------
0

[ERR-21011 : Invalid literal]

1 row selected.


사례 2. TO_NUMBER 함수에 주어진 값이 숫자형으로 변환할 수 없는 문자형일 때.


iSQL> SELECT TO_NUMBER('1-1') from DUAL;

[ERR-21011 : Invalid literal
0001 : SELECT TO_NUMBER('1-1') from DUAL

^  ^

]

iSQL>


사례 3. 비교 연산에 사용된 컬럼에 자동 형 변환할 수 없는 데이터 값이 존재하는 경우.


iSQL> CREATE TABLE T (NO CHAR(1));

Create success.

iSQL> INSERT INTO T VALUES('1');

1 row inserted.

iSQL> INSERT INTO T VALUES('2');

1 row inserted.

iSQL> SELECT * FROM T WHERE NO = 1;     -- CHAR형 컬럼의 값을 숫자형 데이터와 비교함. NO 컬럼의

값이 숫자형으로 자동 형 변환이 이루어짐.

NO                     -- NO 컬럼에 숫자형으로 변환 가능한 값만 존재하기 때문에 에러없이 수행됨.

-----
1

1 row selected.


iSQL> INSERT INTO T VALUES('A');      -- NO 컬럼에 숫자형으로 변환할 수 없는 값이 입력.

1 row inserted.

iSQL> SELECT * FROM T WHERE NO = 1;     -- NO 컬럼의 값을 숫자형으로 자동 형 변환이 이루어지면서 'A'

라는 값 때문에 Invalid literal 에러가 발생함.

[ERR-21011 : Invalid literal]


iSQL> SELECT * FROM T WHERE NO = '1';    -- 문자형 컬럼에는 비교 값에 작은 따옴표(') 를 사용해야함.

NO

-----
1

1 row selected.


iSQL> INSERT INTO T VALUES(' ');      -- NO 컬럼에 공백 문자로 포함된 경우도 Invalid literal 에러가

발생함.

1 row inserted.

iSQL> SELECT TO_NUMBER(NO) FROM T;

[ERR-21011 : Invalid literal]


iSQL> SELECT TO_NUMBER(TRIM(NO)) FROM T;  -- 공백 문자의 경우 TRIM 함수를 이용하면 에러를 없앨 수

있음.
TO_NUMBER(TRIM(CODE))

-----------------------
1

2

3 rows selected.

iSQL>

#### 09-23. ERR-31283 Unable to create a primary key or a unique key constraint in the local non-prefixed index.


대상 버전
증상
원인
해결 방안
참고 사항


대상 버전


6.1.1 이하 버전


증상


파티션 테이블에 PK 또는 UNIQUE INDEX 생성 시 다음 에러 발생.


[ERR-31283 : Unable to create a primary key or a unique key constraint in the local non-prefixed index.]


원인


다음과 같이 altierr 유틸리티를 이용하여 해당 에러에 대한 설명을 확인할 수 있습니다.





알티베이스 6.1.1 이하 버전에서는 global index를 지원하지 않습니다.


따라서 모든 파티션 인덱스는 local index이고 local non-prefixed index를 PK나 UNIQUE INDEX로 생성할 수 없습니다.


local non-prefixed index를 PK나 UNIQUE INDEX로 생성할 수 없는 이유는 해당 컬럼값이 특정 파티션 내에서 유일한 값이더라도 테이블
전체에서 UNIQUE함을 보장할 수 없기 때문입니다.


(테이블 전체에서 UNIQUE 속성을 검사하기 위해서는 전체 파티션을 검사해야 하는데 local index는 특정 파티션 내에서만 UNIQUE 속성을
검사함.)


해결 방안


1. PK나 UNIQUE INDEX는 prefixed index로 생성해야 합니다. 즉, PK나 UNIQUE INDEX는 파티션 키컬럼과 인덱스 컬럼이 동일해야 합니다.


2. 파티션 키컬럼과 동일하지 않은 컬럼으로 인덱스 생성을 원하다면 NON-UNIQUE INDEX로 생성할 수 있습니다.


3. 알티베이스를 6.3.1 이상 버전으로 업그레이드 하면 global index로 PK나 UNIQUE INDEX 생성이 가능합니다.


# 예제


iSQL> CREATE TABLE REALSET_CONTENTS
2 (
3 CT_ID VARCHAR (32) NOT NULL,
4 CT_TYPE VARCHAR (2) NOT NULL,
5 CT_PATH VARCHAR (256) NOT NULL,
6 CT_URL VARCHAR (256) NOT NULL,

7 REG_DATE DATE NOT NULL,
8 FILE_NAME VARCHAR (256) NOT NULL,
9 STATUS VARCHAR (4) NOT NULL
10 )
11 PARTITION BY RANGE (REG_DATE)
12 (
13 PARTITION P_1 VALUES LESS THAN (to_date('2013-05-01', 'YYYY-MM-DD')),
14 PARTITION P_2 VALUES LESS THAN (to_date('2013-09-01', 'YYYY-MM-DD')),

15 PARTITION P_DEF VALUES DEFAULT
16 )

17 TABLESPACE SYS_TBS_DISK_DATA;

Create success.
iSQL> alter table REALSET_CONTENTS add primary key(CT_ID,REG_DATE);

[ERR-31283 : Unable to create a primary key or a unique key constraint in the local non-prefixed index.]


1. PK 컬럼 순서를 바꾸어 local prefixed index를 PK로 생성하는 예제.


iSQL> alter table REALSET_CONTENTS add primary key(REG_DATE,CT_ID);

Alter success.

iSQL> desc REALSET_CONTENTS

[ TABLESPACE : SYS_TBS_DISK_DATA ]

[ ATTRIBUTE ]

-----------------------------------------------------------------------------
NAME                   TYPE            IS NULL

-----------------------------------------------------------------------------
CT_ID                  VARCHAR(32)         NOT NULL
CT_TYPE                 VARCHAR(2)         NOT NULL
CT_PATH                 VARCHAR(256)        NOT NULL
CT_URL                  VARCHAR(256)        NOT NULL

REG_DATE                 DATE            NOT NULL
FILE_NAME                VARCHAR(256)        NOT NULL
STATUS                  VARCHAR(4)         NOT NULL

[ INDEX ]

-----------------------------------------------------------------------------
NAME                   TYPE   IS UNIQUE   COLUMN

-----------------------------------------------------------------------------
__SYS_IDX_ID_142             BTREE  UNIQUE    REG_DATE ASC,

CT_ID ASC

[ PRIMARY KEY ]

-----------------------------------------------------------------------------
REG_DATE, CT_ID


2. local non-prefixed index를 PK로 생성하지 않고 non-unique index로 생성하는 예제.


iSQL> create index REALSET_CONTENTS_IDX1 on REALSET_CONTENTS(CT_ID,REG_DATE) local;

Create success.

iSQL> desc REALSET_CONTENTS

[ TABLESPACE : SYS_TBS_DISK_DATA ]

[ ATTRIBUTE ]

-----------------------------------------------------------------------------
NAME                   TYPE            IS NULL

-----------------------------------------------------------------------------
CT_ID                  VARCHAR(32)         NOT NULL
CT_TYPE                 VARCHAR(2)         NOT NULL
CT_PATH                 VARCHAR(256)        NOT NULL
CT_URL                  VARCHAR(256)        NOT NULL

REG_DATE                 DATE            NOT NULL
FILE_NAME                VARCHAR(256)        NOT NULL
STATUS                  VARCHAR(4)         NOT NULL

[ INDEX ]

-----------------------------------------------------------------------------
NAME                   TYPE   IS UNIQUE   COLUMN

-----------------------------------------------------------------------------
REALSET_CONTENTS_IDX1          BTREE         CT_ID ASC,

REG_DATE ASC

REALSET_CONTENTS has no primary key


3. 6.3.1 버전으로 업그레이드 후 global index로 PK를 생성하는 예제.


iSQL> alter table REALSET_CONTENTS add primary key(CT_ID,REG_DATE);

Alter success.

iSQL> desc REALSET_CONTENTS

[ TABLESPACE : SYS_TBS_DISK_DATA ]

[ ATTRIBUTE ]

-----------------------------------------------------------------------------
NAME                   TYPE            IS NULL

-----------------------------------------------------------------------------
CT_ID                  VARCHAR(32)         NOT NULL
CT_TYPE                 VARCHAR(2)         NOT NULL
CT_PATH                 VARCHAR(256)        NOT NULL
CT_URL                  VARCHAR(256)        NOT NULL

REG_DATE                 DATE            NOT NULL
FILE_NAME                VARCHAR(256)        NOT NULL
STATUS                  VARCHAR(4)         NOT NULL

[ INDEX ]

-----------------------------------------------------------------------------
NAME                   TYPE   IS UNIQUE   COLUMN

-----------------------------------------------------------------------------
__SYS_IDX_ID_922             BTREE  UNIQUE    CT_ID ASC,

REG_DATE ASC

[ PRIMARY KEY ]

-----------------------------------------------------------------------------
CT_ID, REG_DATE


참고 사항


# 파티션 테이블을 위한 인덱스 종류




















|분류조건1|분류조건2|분류조건3|인덱스 종류|알티베이스 지원여부|
|---|---|---|---|---|
|인덱스가 파티션 되어 있음.|index part key = table part<br>key|index part key = index<br>key|(Partitioned) Local prefixed Index|지원|
|||index part key != index<br>key|(Partitioned) Local nonprefixed<br>Index|지원|
||index part key != table part<br>key|index part key = index<br>key|(Partitioned) Global prefixed Index|미지원|
|||index part key != index<br>key|(Partitioned) Global nonprefixed<br>Index|미지원|
|인덱스가 파티션 되어 있지<br>않음.|||Nonpartitioned global index|6.3.1 이상 버전에서<br>지원|



prefixed index와 nonprefixed index를 구분하는 이유는 unique 속성 때문입니다.


nonprefixed index의 경우 파티션 내에서 unique 하더라도 테이블 전체에서 unique 함을 보장하지 못합니다.


따라서 nonprefixed index는 PK나 UNIQUE INDEX로 생성하지 못하는 것입니다.

#### 09-24. ERR-41059 ( 266329) Task pool overflow. Check properties.


버전
현상
원인

신규 접속 수가 증가한 경우
서비스 쓰레드가 모두 EXECUTE 상태에서 신규 접속이 발생한 경우
트랜잭션 수가 TRANSACTION_TABLE_SIZE 에 도달한 상태에서 신규 접속이 발생한 경우
확인 방법


체크 리스트
MAX_CLIENT 설정 값 확인 방법
세션 수 확인 방법
task 수 확인 방법
조치

MAX_CLIENT 프로퍼티 변경
어플리케이션 검토


버전


ALTIBASE HDB 5 이상


현상


클라이언트에서 알티베이스 서버로 신규 접속 시도 시 아래와 같은 에러 메시지로 실패할 때,


[ERR-91015 : Communication failure.]


알티베이스 서버의 altibase_boot.log 에서 아래의 에러 메시지를 볼 수 있습니다.


ERR-41059(errno=16) Task pool overflow. Check properties.
Dispatcher failed callback


원인


알티베이스 서버에 생성된 task 수가 MAX_CLIENT 에 도달했을 때 발생합니다.


task 는 알티베이스 서버에 새로운 연결이 맺어질 때 생성되는 객체로, 동시에 생성할 수 있는 최대 수가 알티베이스 서버 프로퍼티 MAX_CLIENT
값에 영향을 받습니다.


현재 생성된 task 의 수가 MAX_CLIENT 에 도달하여 새로운 task 객체를 생성할 수 없을 때 Task pool overflow 라는 메시지가 나타납니다.


MAX_CLIENT 는 동시에 접속할 수 있는 최대 세션 수를 의미하기도 하는데, task 는 결국 세션과 대응되기 때문에 같은 프로퍼티에 영향을
받습니다.


발생할 수 있는 원인은 다음과 같습니다.


신규 접속 수가 증가한 경우


신규 접속 수가 증가하여 task 의 수가 MAX_CLIENT 를 초과하는 경우 발생할 수 있습니다.


서비스 쓰레드가 모두 EXECUTE 상태에서 신규 접속이 발생한 경우


모든 서비스 쓰레드가 EXECUTE 상태에서 신규 접속이 실패한 경우 해당 연결은 알티베이스 서버 내에서 task 형태로 남아 있습니다. 따라서
이런 이유로 접속이 실패하더라도 신규 접속이 발생한 만큼 task 수가 증가하게 됩니다.


아래와 같이 접속이 실패하다가


$ is -silent

[ERR-5104D : Connection timeout.]


task 의 수가 MAX_CLIENT 를 초과하게 되면 접속 실패 에러 메시지가 아래와 같이 바뀝니다.


$ is -silent

[ERR-91015 : Communication failure.]


트랜잭션 수가 TRANSACTION_TABLE_SIZE 에 도달한 상태에서 신규 접속이 발생한 경우


동시 수행 중인 트랜잭션의 수가 TRANSACTION_TABLE_SIZE 에 도달한 상태에서 신규 접속이 실패한 경우 해당 연결은 알티베이스 서버
내에서 task 형태로 남아 있습니다. 따라서 이런 이유로 접속이 실패하더라도 신규 접속이 발생한 만큼 task 수가 증가하게 됩니다.


아래와 같이 접속이 실패하다가


$ is -silent

[ERR-5104D : Connection timeout.]


task 의 수가 MAX_CLIENT 를 초과하게 되면 접속 실패 에러 메시지가 아래와 같이 바뀝니다.


$ is -silent

[ERR-91015 : Communication failure.]


이 경우 altibase_boot.log 에서는 아래와 같은 메시지가 발생합니다.


TRANSACTION_TABLE_SIZE is full !!

Current TRANSACTION_TABLE_SIZE is 1024

Please check TRANSACTION_TABLE_SIZE


확인 방법


체크 리스트


Task pool overflow 의 원인을 찾기 위해서는 아래 항목들을 확인해야 합니다.


MAX_CLIENT 프로퍼티 설정 값

알티베이스 서버에 접속된 세션 수
알티베이스 서버에 접속된 세션 수가 MAX_CLIENT 와 동일하면 세션 증가가 원인이고 MAX_CLIENT 보다 작다면 task 수를
확인합니다.

알티베이스 서버에서 생성된 task 수
세션 수가 MAX_CLIENT 보다 작고 task 수가 MAX_CLIENT 와 같거나 크다면 아래 원인을 의심해 볼 수 있습니다.


1. 서비스 쓰레드가 모두 EXECUTE 상태에서 신규 접속이 발생하여 task 가 증가한 경우
2. 트랜잭션 수가 TRANSACTION_TABLE_SIZE 에 도달한 상태에서 신규 접속이 발생하여 task 가 증가한 경우


$ALTIBASE_HOME/trc/altibase_boot.log
트랜잭션 수가 TRANSACTION_TABLE_SIZE 을 초과한 경우 TRANSACTION_TABLE_SIZE is full 이라는 메시지가 남습니다.


MAX_CLIENT 설정 값 확인 방법


Task pool overflow 은 task 의 수가 MAX_CLIENT 프로퍼티의 설정 값을 초과할 때 발생하므로 먼저 이 프로퍼티의 설정 값을 확인합니다.


iSQL 접속이 가능한 경우





iSQL 접속이 불가능한 경우





세션 수 확인 방법


iSQL 접속이 가능한 경우


iSQL 접속이 가능하다면 성능 뷰를 통해 세션 수를 확인할 수 있으며 이를 통해 Task pool overflow 의 원인을 어느


정도 유추할 수 있습니다.


현재 세션 수와 MAX_CLIENT 값을 비교하여 값이 같은 경우 세션 증가가 원인입니다.


현재 세션 수가 MAX_CLIENT 보다 작다면 세션 증가가 아닌 다른 두 가지가 원인일 수 있습니다.


iSQL 접속이 불가능한 경우


iSQL 접속이 어려운 경우 OS 상의 정보로 세션 수를 확인해야 합니다.


클라이언트의 접속 방법에 따라 아래 두 가지 방법으로 확인할 수 있습니다.


TCP, IPC 두 가지 방법으로 접속하는 경우 수행 결과를 모두 더하여 MAX_CLIENT 와 비교하여 세션 증가가 원인인 지


다른 부분이 원인인 지 판단할 수 있습니다.










task 수 확인 방법


iSQL 접속이 가능한 경우


세션 수가 MAX_CLIENT 보 다 작다면 다른 원인을 살펴봐야 합니다.


아래 명령어로 task 의 수를 확인하고 task 수와 MAX_CLIENT 를 비교합니다. logon current 의 값은 생성된 task 의


수를 의미하며 세션 수 보다 클 수 있습니다.





세션 수가 MAX_CLIENT 보다 작고 logon current 의 값이 MAX_CLIENT 와 같거나 큰 경우 아래 두 가지가 원인일 수


있습니다


- 서비스 쓰레드가 모두 EXECUTE 상태에서 신규 접속이 발생하여 task 가 증가한 경우


- 트랜잭션 수가 TRANSACTION_TABLE_SIZE 에 도달한 상태에서 신규 접속이 발생하여 task 가 증가한 경우


iSQL 접속이 불가능한 경우


생성된 task 수는 v$sysstat 의 logon current 값으로 확인할 수 있습니다. 하지만 Task pool overflow 이 발생한


상황이라면 새로운 연결이 맺어지지 않기 때문에 위 문장을 수행하지 못할 수 있습니다.


이 때는 lsof 명령으로 알티베이스 서버 프로세스의 오픈 파일 수로 task 수를 확인해야 합니다.





Solaris 의 경우 lsof 대신 pfiles 명령어를 이용해도 됩니다.


조치


MAX_CLIENT 프로퍼티 변경


실제 동시 접속 세션이 많아졌을 경우 MAX_CLIENT 를 변경해야 합니다.


동시 접속 세션이 많아지면 동시에 수행하는 트랜잭션도 많아지고 Unix/Linux 시스템의 경우 open file 수가 증가하게 됩니다.


따라서 MAX_CLIENT 를 기존 값보다 크게 변경할 경우 다음의 값들을 같이 변경해야 합니다.


TRANSACTION_TABLE_SIZE
max open files


변경 방법에 관한 설명은 동시 접속 세션 수(MAX_CLIENT) 증가 시 고려사항 페이지를 참고하시기 바랍니다.


어플리케이션 검토


어플리케이션이 아래와 같은 특성을 가진 경우 그 필요성을 다시 한 번 확인 작업이 필요합니다.


서비스 특성 상 위와 같은 처리가 불가피한 경우가 아니라면 트랜잭션 완료 후 세션을 바로 종료하도록 변경하는 것을 검토해야 합니다.


계속 새로운 연결을 맺는 경우
더 이상 연결을 맺고 있을 필요가 없음에도 불필요하게 연결된 세션을 유지하는 경우


#### 09-25. ERR-71018 ( 462872) Failed to invoke a system function, read() 또는 Failed to invoke the read() system function





개요


DB 연결 종료 메시지는 TCP 연결 타입으로 Altibase 서버에 접속한 경우, Altibase 클라이언트 프로그램이 정상적으로 DB 연결 종료(Session
close)를 수행하지 않았을 때 발생합니다. 이 경우, Altibase 서버 트레이스 로그 파일인 altibase_boot.log에 관련 에러 메시지가 기록됩니다.


본 문서에서는 이러한 에러 메시지의 유형과 발생 원인에 대해 설명합니다.


에러 메세지 유형


Altibase 버전에 따라 기록되는 에러 메시지는 다소 차이가 있습니다.


ALTIBASE HDB 4 ~ ALTIBASE HDB 5.3.3


ERR-71018(errno=238) Failed to invoke a system function, read()
ERR-71019(errno=104) Failed to invoke a system function, write()


ALTIBASE HDB 5.5.1 ~ 이상버전


ERR-71018(errno=238) Failed to invoke the read() system function
ERR-71019(errno=104) Failed to invoke the write() system function


에러 메세지 설명


Altibase 서버의 세션 매니저 쓰레드가 클라이언트와의 연결이 단절되었음을 감지하고 해당 세션을 정리하였음을 알리는 메시지입니다.


세션 매니저 쓰레드는 Altibase 서버와 클라이언트의 연결 상태를 주기적으로 점검하며, 다음과 같은 역할을 수행합니다:



1.


2.



클라이언트 비정상 종료 감지
클라이언트 프로세스가 비정상 종료되면 해당 세션의 상태를 즉시 감지하여 종료 처리합니다.


서버 내부 작업 중 연결 상태 확인
Altibase 서버가 내부 작업을 수행하느라 연결 상태를 실시간으로 확인하지 못할 경우에도, 세션 관리 쓰레드가 이를 주기적으로
점검합니다.



에러 메시지 의미


ERR-71018
클라이언트의 요청을 기다리는 단계에서 연결이 끊어진 경우를 나타냅니다. (read() 호출 실패)


ERR-71019
클라이언트로 응답을 보내는 단계에서 연결이 끊어진 경우를 나타냅니다. (write() 호출 실패)


에러 메세지 발생 원인


에러 메시지의 발생 원인은 시스템 에러 코드(errno)로 유추할 수 있습니다.


ERR-71018(errno=113) Failed to invoke a system function, read()
ERR-71019(errno=104) Failed to invoke a system function, write()


주요 시스템 에러 코드


주로 발생하는 에러는 아래와 같습니다.


1. ECONNRESET


클라이언트가 RST 패킷(연결이 유효하지 않음을 알리는 패킷)을 보낸 경우 발생합니다.
Altibase 서버는 클라이언트로부터 RST 패킷을 수신하면 errno를 ECONNRESET으로 설정합니다.


시스템 에러 코드


Linux : 104

AIX : 73

HP-UX : 232

SUN : 131

Windows : 10054


2. ETIMEDOUT


TCP 통신에서 클라이언트에서 응답이 없을 때 발생합니다.
OS는 연결 상태를 확인하기 위해 패킷 재전송을 시도하며, 설정된 시간 내 응답이 없으면 ETIMEDOUT 에러가 발생합니다.


시스템 에러 코드


Linux : 110

AIX : 78

HP-UX : 238

SUN : 145

Windows : 10060


참고 자료


Linux : /usr/include/asm-x86_64/errno.h
AIX : /usr/include/errno.h
기타 OS : errno.h 헤더 파일 참조


주요 발생 사례


다음과 같은 상황에서 TCP 세션 연결 종료 에러가 자주 발생합니다:


1. 네트워크 환경 문제


L4 스위치 또는 방화벽에서 Idle 상태의 TCP 세션을 강제로 정리한 경우.
LAN 카드 및 기타 네트워크 장비의 기계적 오류.


2. DB 클라이언트 문제


DB 클라이언트 프로그램의 비정상 종료 또는 재시작.


조치 사항


Altibase 서버에서 클라이언트와의 연결 단절을 감지하고 세션을 정리했음을 알리는 메시지로, 서버 측에서 추가적인 조치는 필요하지 않습니다.


추가 참고


이중화 환경에서는 altibase_rp.log에 유사한 에러 메시지가 기록될 수 있습니다.
이는 이중화 Sender가 로그 전송 중 Receiver의 종료 상태를 감지했을 때 발생합니다.

#### 09-26. ERR-71019(errno=104) Failed to invoke a system function, write()




#### 09-27. ERR-91015 ( 593941) Communication failure

버전


원인 및 조치 방법


알티베이스 서버로 접속 시도 시


알티베이스 서버에 접속된 상태에서 발생하는 경우


알티베이스 서버 프로퍼티에 의해 세션이 종료된 경우


sysdba 유저에 의해 세션이 종료된 경우


데이터베이스 서버 구동 시


개요


ERR-91015 ( 593941) Communication failure 에 대해 설명합니다.


버전


ALTIBASE HDB 모든 버전


현상


ERR-91015 ( 593941) Communication failure 에러는 아래와 같이 다양한 환경에서 발생할 수 있습니다.


알티베이스 서버로 접속 시도 시
알티베이스 서버로 접속 시 이 에러가 발생하는 경우는 주로 iSQL 을 이용하는 경우입니다.





알티베이스 서버에 접속된 상태에서 발생하는 경우


알티베이스 서버 구동 시





원인 및 조치 방법


알티베이스 서버로 접속 시도 시


ALTIBASE HDB 호환성 정책에 따라 상위 버전의 알티베이스 클라이언트에서 클라이언트보다 낮은 버전의 알티베이스 서버로 접속 시도 시 이
에러가 발생할 수 있습니다.


이 원인에 의한 경우 알티베이스 서버 측 altibase_boot.log 에 알티베이스 서버 버전에 따라 다양한 형태의 메시지가 출력됩니다. (하지만 특정
버전에서는 메시지가 전혀 남지 않을 수도 있습니다.)


따라서 알티베이스 서버로 접속 시 이 에러가 발생한다면 가장 먼저 알티베이스 서버와 클라이언트 버전을 확인해보세요. 클라이언트 버전이
서버 버전보다 상위 버전이라면 클라이언트 버전을 서버와 동일하게 맞추거나 서버보다 낮은 버전으로 설치하여 사용해야 합니다.


ALTIBASE HDB 서버 버전 확인 방법


$ altibase -v
version 6.1.1.4.9 X86_64_LINUX_redhat_Enterprise_ES4-64bit-6.3.1.4.4-release-GCC3.4.6
(x86_64-unknown-linux-gnu) Apr 14 2015 11:31:37, binary db version 6.2.1, meta version
~~6 3 1 cm protocol version 7 1 1 replication protocol version 7 4 1~~


ALTIBASE HDB 클라이언트 버전 확인 방법


$ apre -v
Altibase Precompiler2(APRE) Ver.1 6.1.1.4.9 XEON_LINUX_redhat_Enterprise_ES4-64bit-6.1.1.4.9-release-GCC3.4.
~~6 (xeon-redhat-linux-gnu) Dec 9 2014 16:06:42~~


또는 iSQL 접속 시에는 배너에서도 버전을 확인할 수 있습니다.


$ is

----------------------------------------------------------------
Altibase Client Query utility.
Release Version 6.1.1.4.9

Copyright 2000, ALTIBASE Corporation or its subsidiaries.
All Rights Reserved.

~~-----------------------------------------------------------------~~


알티베이스 서버에 접속된 상태에서 발생하는 경우


알티베이스 서버 프로퍼티에 의해 세션이 종료된 경우


알티베이스 서버 프로퍼티 FETCH_TIMEOUT, UTRANS_TIMEOUT, IDLE_TIMEOUT 에 의해 세션이 종료된 경우 클라이언트에서는
Communication failure 메시지가 발생할 수 있습니다.
이런 이유로 세션이 종료될 경우 알티베이스 서버 측 altibase_boot.log 에 아래와 같이 타임 아웃 설정에 의해 종료되었다는 에러
메시지가 남습니다.
(altibase_boot.log 는 $ALTIBASE_HOME/trc 디렉토리 아래에 있습니다. $ALTIBASE_HOME 은 알티베이스 서버 설치 위치를
의미합니다.)









세션 프로퍼티 관련한 상세 내용이나 조치 방법은 아래 페이지를 참고하시기 바랍니다.

FETCH_TIMEOUT : http://aid.altibase.com/x/lACL
UTRANS_TIMEOUT : https://docs.altibase.com/x/ugOB
IDLE_TIMEOUT : https://docs.altibase.com/x/ZoNj


sysdba 유저에 의해 세션이 종료된 경우


sysdba 가 ALTER DATABASE database_name SESSION CLOSE session_id ; 문장으로 세션이 강제 종료한
경우에도 Communication failure 에러가 발생할 수 있습니다.
이 경우 알티베이스 서버 또는 클라이언트 쪽에 아무런 추가 에러 정보가 남지 않습니다.


데이터베이스 서버 구동 시


알티베이스 서버 프로퍼티가 올바르게 설정되어 있지 않을 경우 알티베이스 서버 startup 시 Communication failure 에러가 발생할 수
있습니다.
경우에 따라 터미널 상에 보여주는 로그로는 원인 찾기가 어려울 수 있으니 아래 정보들을 통해 어떤 프로퍼티 때문에 발생하는 지 찾아가야
합니다.


터미널 상에 출력되는 로그
altibase_boot.log 파일 ($ALTIBASE_HOME/trc 에 위치, $ALTIBASE_HOME 은 알티베이스 서버 설치 위치를 의미합니다.)
altibase.properties 파일 ($ALTIBASE_HOME/conf 에 위치)

#### 09-28. Not found data


개요
버전
현상
원인

커서(CURSOR) OPEN 상태에서 COMMIT/ROLLBACK 수행한 경우
조치

커서(CURSOR) OPEN 상태에서 COMMIT/ROLLBACK 수행한 경우

1. fetch 세션과 변경 DML 세션 분리
2. 통신 버퍼에 담길 만큼만 커서 선언 후 반복적 커서 오픈
참고

버전 별 차이


개요


여러 개의 레코드를 반환하는 select 문 처리를 위해 커서를 사용하여 레코드 fetch 과정 중 발생하는 오류에 관해 설명한다.


버전


Altibase 5.3.3

Altibase 5.5.1

Altibase 6.1.1


현상


여러 개의 레코드를 반환하는 질의문 처리를 위해서는 아래와 같은 과정으로 커서(CURSOR)를 이용해야 한다.



1.

2.

3.

4.



커서 선언 (DECLARE CURSOR)
커서 OPEN (OPEN CURSOR)
커서 FETCH (FETCH CURSOR)
커서 CLOSE/RELEASE (CLOSE CURSOR 또는 RELEASE CURSOR)



위와 같이 커서를 사용하였으나 '3. 커서 FETCH' 단계에서 어느 정도 FETCH 진행하다가 어느 순간 FETCH 할 레코드가 남아있음에도 Not
found data 에러가 발생한다.


아래는 커서 사용 시 에러가 발생하는 부분과 에러 발생 결과 예시이다.






원인


커서(CURSOR) OPEN 상태에서 COMMIT/ROLLBACK 수행한 경우


Altibase는 ANSI 표준을 준수하여 fetch across commit 방식을 지원하지 않는다. 따라서 커서 OPEN 후 COMMIT 또는 ROLLBACK을 수행하면
ANSI 표준에 따라 커서를 강제로 닫는다.


fetch across commit 이란
커서 OPEN 후 단위 레코드를 FETCH하면서 COMMIT을 수행하는 방식으로 ANSI 표준에서 권장하지 않는 방식이다.


이런 이유로 애플리케이션에서 커서 OPEN 후 COMMIT 또는 ROLLBACK을 수행한 경우 에러가 발생할 수 있다.


어느 정도 FETCH 수행하다가 에러가 발생하는 이유는 처음 커서 FETCH 시 일정량의 레코드가 통신 버퍼에 담기기 때문이다. 통신 버퍼에 담긴
레코드를 모두 FETCH하고 다음 일정량의 레코드를 통신 버퍼에 담기 위한 FETCH를 할 때 에러가 발생하게 된다.


아래는 커서 OPEN 상태에서 COMMIT 또는 ROLLBACK을 수행한 애플리케이션 작성 예이다.


non-autocommit mode


커서(CURSOR) 선언


커서(CURSOR) OPEN


while(1)
{
커서(CURSOR) FETCH ;

if (sqlca.sqlcode == SQL_SUCCESS) {

/* 변경 DML 수행 */

/* COMMIT 또는 ROLLBACK 수행 */

}
else if (sqlca.sqlcode == SQL_NO_DATA) {
/* 처음 통신 버퍼에 담긴 레코드를 모두 처리한 후 두 번째 통신 버퍼에 담길 때 이 단계에서 에러가 발생한다.
*/
}
else {

...

}
}


조치


커서(CURSOR) OPEN 상태에서 COMMIT/ROLLBACK 수행한 경우


이 에러를 조치하기 위한 2가지 방법을 안내한다.


다중 연결을 사용하여 fetch와 변경 DML 작업을 분리하는 방법
통신 버퍼에 담길 만큼만 커서 선언 후 반복적 커서 오픈하는 방법


위 방법은 모두 애플리케이션 변경이 필요하다.


1. fetch 세션과 변경 DML 세션 분리


하나의 애플리케이션 내에 다중 연결을 사용하여 COMMIT 또는 ROLLBACK 수행이 커서에 영향이 없도록 한다.


커서를 사용하는 세션과 변경 DML문을 수행하는 세션을 생성한다. 각각 CONN1, CONN2로 정의하여 설명한다.
변경 DML문을 수행하는 세션(CONN2)는 non-autocommit mode로 설정한다.
커서를 사용하는 세션(CONN1)에서 커서 FETCH 수행할 때마다 CONN2에서 변경DML을 수행하고 COMMIT 또는 ROLLBACK
을 수행한다.


아래는 이 조치를 반영한 애플리케이션 작성 예이다.


/* FETCH를 위한 세션 */

EXEC SQL AT conn1 CONNECT;

/* 변경DML 수행을 위한 세션 */

EXEC SQL AT conn2 CONNECT;


EXEC SQL AT conn2 AUTOCOMMIT OFF;

/* CONN1에서 커서 선언, OPEN, FETCH 수행 */

EXEC SQL AT conn1 DECLARE cursor;

EXEC SQL AT conn1 OPEN cursor;
while (1)
{
/* conn1에서 FETCH 수행. */

EXEC SQL AT conn1 FETCH cursor

if (sqlca.sqlcode == SQL_SUCCESS) {

/* conn2에서 변경DML 및 COMMIT 또는 ROLLBACK 수행 */

EXEC SQL AT conn2 INSERT or UPDATE or DELETE ;

/* check sqlca.sqlcode */
if (sqlca.sqlcode == SQL_SUCCESS) {

...

}
else {

...

}

/* conn2에서 수행한 commit 또는 rollback은 conn1의 커서 사용에 영향을 주지 않는다. */

EXEC SQL AT conn2 commit or rollback;

/* check sqlca.sqlcode */
if (sqlca.sqlcode == SQL_SUCCESS) {

...

}
else {

...

}
}
else if (sqlca.sqlcode == SQL_NO_DATA) {

...

}
else {

...

}
}


2. 통신 버퍼에 담길 만큼만 커서 선언 후 반복적 커서 오픈


한번의FETCH 로통신버퍼에담길만큼의레코드수를산정한후LIMIT 절을사용해커서를선언한다.


한 번의 FETCH 통신 버퍼에 담길 만큼의 레 수를 산정한 후 LIMIT 절을 사용해 커서를 선언한다.


Altibase 5 이상 버전의 통신 버퍼 크기는 64K이다. 통신 버퍼에 담기는 레코드 수는 레코드 크기에 따라 다르기 때문에 LIMIT절 마지막
값은 운영 환경에 따라 달라진다.


LIMIT절에 통신 버퍼에 담길 만큼의 레코드 수를 지정하고 커서 오픈 전에 LIMIT절의 시작 값을 변경하면서 커서를 다시 오픈하여
사용한다.


아래는 이 조치를 반영한 애플리케이션 작성 예이다.


/* LIMIT 절을 사용하여 커서를 선언한다. n은 LIMIT절에서 반환할 마지막 레코드 값으로 운영 환경에 맞게
정의해야 한다. 통신 버퍼에 담기는 레코드 수는 레코드 크기에 따라 다르다. */

DECLARE 커서

SELECT ~

FROM ~

WHERE ~

LIMIT :s_start, n;


/* LIMIT 절에 사용한 시작 값을 선언한다. */

s_start = 1;

while(1)
{
/* 조건에 맞는 레코드를 모두 FETCH할 때까지 커서 오픈을 반복한다. */

OPEN 커서

while(1)
{
커서(CURSOR) FETCH ;

if (sqlca.sqlcode == SQL_SUCCESS) {

/* 변경 DML 수행 */
}
else if (sqlca.sqlcode == SQL_NO_DATA) {

...

}
else {

...

}
}

/* COMMIT 또는 ROLLBACK 수행 */

/* LIMIT 절의 시작 값을 지정한다. n은 예시이다. */

s_start = s_start + n ;

}


CLOSE 커서 또는 CLOSE RELEASE 커서


참고


버전 별 차이


Altibase 버전에 따라 같은 상황에서 발생하는 에러 메시지는 다를 수 있다.


Non-autocommit 환경에서 FETCH 중 COMMIT/ROLLBACK 수행할 경우 발생하는 에러 메시지 차이는 아래와 같다.

|버전|에러코드|에러메시지|참고 페이지|
|---|---|---|---|
|Altibase 4.3.9|ERR-4103C|Request of fetching data to an unprepared SQL statement.|http://aid.altibase.com/x/6YKZ|
|Altibase 5.3.3 ~ 6.1.1|100|Not found data||
|Altibase 6.3.1 이상|ERR-410D2|Fetch out of sequence.|http://aid.altibase.com/x/9oKZ|


#### 09-29. tablespace does not have enough free space 에러


개요


버전


원인


조치


참고


개요


테이블 스페이스 공간부족


버전


ALTIBASE HDB 4 이상


원인


이 에러는 특정 테이블스페이스의 크기 부족으로 발생한 것입니다 .


조치


1. 테이블스페이스 공간 사용량을 확인합니다.


사용하는 알티베이스 버전에 맞는 쿼리문을 사용하여 사용량 확인 합니다.


http://aid.altibase.com/pages/viewpage.action?pageId=6520890


2. 테이블스페이스 사용량 조회 후 쿼리 결과값에서 USAGE(%) 가 100% 에 가까운 테이블스페이스에 공간을 추가합니다.


ALTER TABLESPACE 테이블스페이스명 add datafile '/경로/파일명' size 2G autoextend off;


참고


데이터 파일 추가시 해당 테이블스페이스에 lock 이 발생하기 때문에 서비스를 차단하고 작업길 권장합니다.


HDB 5.3.3 이하는 테이블스페이스 추가 작업이 완료될때까지 select 및 DML 및 쿼리가 대기 합니다.


HDB 5.5.1 이상부터 최신의 V6 까지는 테이블스페이스 추가 작업이 완료될때까지 DML은 대기하지만 select
문은 정상적으로 수행됩니다.

### 10. 마이그레이션 11. 유틸리티

#### 11-01. AdminCenter2 실행 파일


개요


AdminCenter2 마지막 버전입니다.


AdminCenter2 는 ALTIBASE HDB 4 버전까지만 사용 가능합니다.


ALTIBASE HDB 5 부터는 웨어밸리 사의 Orange for Altibase ( Orange for Altibase 다운로드 : http://www.warevalley.com )


AdminCenter2 는 유지보수가 종료되어 사용 시 발생하는 문제에 대해 접수 받지 않습니다.


실행 파일


AdminCenter2.zip


실행 방법


실행 파일을 다운로드 후 압축을 풀고 AdminCenter.exe 파일을 실행합니다.


ALTIBASE HDB 접속에 필요한 JDBC Driver 는 ALTIBASE HDB 서버가 운용 중인 서버에서 $ALTIBASE_HOME/lib/Altibase.jar 를 이용하세요.


매뉴얼


AdminCenter.exe 실행 후 Help -> Help Contents 메뉴를 이용해주세요.


한글 버전은 따로 제공하지 않습니다.

#### 11-02. iLoader


11-02-01. 도스 형식 데이터 파일을 iloader로 업로드 할 때 에러가 발생 합니다.


개요
제거 방법

윈도우즈에서
Linux/Unix에서

dos2unix 를 이용하여 unix 형 파일로 변환
sed 를이용하여 ^M 제거
ALTIBASE HDB 5.5.1 부터는 ...


개요


도스 형식의 데이터 파일을 Unix/Linux 서버에서 iloader로 업로드하기 위해서는 에디트 프로그램 또는 dos2unix 를 이용하여 파일을 변환해야
합니다.


변환없이 iloader 를 수행할 경우 아래와 같은 에러가 발생할 수 있습니다.


ERR-9102B : Token value length overflow.


도스 형식의 파일은 Row Termination Code 가 CR(Carriage Return) + LF(Line Feed) 로 구성되어 있습니다.


iloader는 데이터 파일을 파싱할 때 %n(LF) 을 줄바꿈(Row terminator) 으로 인식합니다. 그래서 도스 형식의 데이터 파일을 업로드 할 때


파싱 에러가 발생할 수 있습니다.


도스 형식의 파일을 Linux/Unix 에서 vi 로 파일을 열어보면 라인 끌에 ^M 가 붙어있거나 아래와 같이 보입니다.


"SYS_T.dat" [도스] 225L, 33822C


제거 방법


윈도우즈에서


윈도우즈에서는 에디트 프로그램을 이용하여 변환할 수 있습니다.
예) UltraEdit 에서 파일 -> 변환 -> 'DOS->UNIX' 선택 후 저장


Linux/Unix에서


dos2unix 를 이용하여 unix 형 파일로 변환


dos2unix 명령은 DOS/MAC 파일을 UNIX 형식으로 변환해줍니다.









sed 를이용하여 ^M 제거


sed 를 이용하여 ^M 제거 한 파일을 iloader 데이터 파일로 사용합니다.
^M 은 Ctrl+v+m 으로 입력해야 합니다.






ALTIBASE HDB 5.5.1 부터는 ...


ALTIBASE HDB 5.5.1 부터는 레코드 구분자로 CR+LF를 의미하는 %r%n 을 사용하면 파일 변환/수정 없이 업로드 할 수 있습니다.




### 12. 기타

#### 12-01. Thread process debugging방법

개요


unix 상에서 프로세스가  cpu 를 과점유하거나 프로세스 hang 과 같은 상황에 빠질 경우 unix OS별로 제공되는 process debugging Utility
를 이용하여 현재 running 중인 Call stack 분석을 통해서


원인을 찾는 데 유용하게 활용할 수 있습니다.


Unix process Debugging 방법들은  Utility마다 틀리고 Unix별로도 조금씩 차이가 나기 때문 에 command가 혼동되는 경우가 많습니다.
간단한 Command위주로 각 Thread Stack을 보는 방법을 설명합니다.


pstack 이용


SUN과 기타 몇개의 Unix, Linux에서 제공하는 Utility로서 Running중인 Process의 Call Stack을 Thread별로 볼수 있는 아주 유용한
Command입니다. DB Hang일때 돌리면 됩 니다.


사용법


리눅스


shell> pstack processid


Sun


shell> pstack -F processid



사용예





dbx 이용


AIX, HP, SUN 에서 제공한다.  dbx 명령을 통해서 실행중인 프로세스의 call stack 정보를 확인할 수도 있고 core 파일에서 Thread별
stack 도 확인할 수 있습니다.


AIX상에서 사용하는 방법을 예로 설명합니다.


사용법



1.


2.


3.


4.


5.


6.



문제가 있는 procesd의 process id를 확인합니다.
shell> ps -eafl | grep altibase
process 에 attach 합니다.
shell> dbx -a <pid of altibase process>
모든 thread 정보를 보기
(dbx) thread
개별적인 thread 정보만 보기
(dbx) thread current < thread number>
(dbx) where
detach 하기
(dbx) detach


반드시 detach 명령을 수행해서 연결된 process를 해제해야 합니다. 그렇지 않고 exit 할 경우 대상 process까지 종료되는
경우가 있으므로 주의해야 합니다.


exit 하기
(dbx) quit



사용예


gdb 이용


gdb ( GNU debugger) 가 설치되어 있을 경우 gdb를 활용하여 thread별 stack 정보를 확인할 수 있습니다.


사용법



1.


2.


3.


4.


5.


6.



gdb 를 대상 process에 attach
shell> $gdb $ALTIBASE_HOME/bin/altibase  process-id
각 thread별 정보 출력
(gdb) info threads
모든 thread의 stack trace를 출력
(gdb) thread apply all bt
특정 thread로 switch
(gdb) t 1  : 1번 thread 로 switch
현재 thread의 stack 출력
(gdb) bt  : stack 출력
종료
(gdb) quit



사용예


#### 12-02. 대용량 DRDB Index 구축

개요


인덱스는 데이타를 읽어 정렬하고 저정하는 과정을 가집니다.


그래서 인덱스를 병렬로 동작시키는건 과도한 디스크 IO나 버퍼미스 를 발생시켜 오히려 성능이 떨어집니다.


아래와 같이 프로퍼티를 설정해서 IO 와 버퍼 미스를 줄이고 정렬과정을 최적화 해서 대용량 디스크 인덱스 빌드 시간을 단축시킬수 있습니다.


해결책


버전 6.5.1~7.1.0


1.BUFFER_AREA_SIZE(단위 bytes) = (클수록 좋습니다.)
2.SORT_AREA_SIZE(단위 bytes) = (장비 물리코어 수 * 20MB)
3.DISK_INDEX_BUILD_MERGE_PAGE_COUNT(단위 page수) = (BUFFER_AREA_SIZE의 1% 추천하지만 DISK_INDEX_BUILD_MERGE_PAGE_

COUNT(아래 고려사항3번)을 고려해야 합니다.)
4.INDEX_BUILD_THREAD_COUNT(core수) = (장비 물리코어 수)


고려사항


1.BUFFER_AREA_SIZE


값이 클수록 STARTUP 시간이 더 걸립니다.


2.SORT_AREA_SIZE


인덱스 1개 빌드시 최소 SORT_AREA_SIZE 크기이상의 메모리를 사용합니다. 만약, 병렬로 2개를 빌드하면 SORT_AREA_SIZE *
2배의 메모리량이 사용됩니다.
SORT_AREA_SIZE는 디스크 템프테이블에서도 공유하는 프로퍼티로, 변경 시 디스크 템프테이블의 동작에 영향이 있습니다.


3.DISK_INDEX_BUILD_MERGE_PAGE_COUNT


프로퍼티의 단위는 페이지 수이고, BUFFER_AREA_SIZE 프로퍼티 단위는 bytes 입니다.
프로퍼티의 값이 크고 인덱스 크기가 작을경우, 오히려 성능이 떨어지는 현상이 있을수 있습니다.

   - 아래의 조건을 만족하는 경우 인덱스 빌드 성능이 떨어질수 있습니다.
DISK_INDEX_BUILD_MERGE_PAGE_COUNT > ( 인덱스키길이 * RECORD수 ) / SORT_AREA_SIZE

### 버전 7.3.0 ~


1.BUFFER_AREA_SIZE(단위 bytes) = (클수록 좋습니다.)
2.DISK_INDEX_BUILD_SORT_AREA_SIZE(단위 bytes) = (장비물리코어수 * 20MB)
3.DISK_INDEX_BUILD_MERGE_PAGE_COUNT(단위 page수) = (BUFFER_AREA_SIZE의 1%)
4.INDEX_BUILD_THREAD_COUNT(core수) = (장비 물리코어수)


고려사항


1.BUFFER_AREA_SIZE


값이 클수록 STARTUP 시간이 더 걸립니다.


2.DISK_INDEX_BUILD_SORT_AREA_SIZE


인덱스 1개 빌드시 최소 DISK_INDEX_BUILD_SORT_AREA_SIZE 크기이상의 메모리를 사용합니다. 만약, 병렬로 2개를 빌드하면
DISK_INDEX_BUILD_SORT_AREA_SIZE * 2배의 메모리량이 사용됩니다.
(SORT_AREA_SIZE를 사용하지 않습니다)


3.DISK_INDEX_BUILD_MERGE_PAGE_COUNT


프로퍼티의 단위는 페이지 수이고, BUFFER_AREA_SIZE 프로퍼티 단위는 bytes 입니다.
아래 문제는 7.3.0 이상 에서는 발생하지 않습니다.

~~프로퍼티의 값이 크고 인덱스 크기가 작을경우, 오히려 성능이 떨어지는 현상이 있을수 있습니다.~~

~~- 아래의 조건을 만족하는 경우 인덱스 빌드 성능이 떨어질수 있습니다.~~
~~DISK_INDEX_BUILD_MERGE_PAGE_COUNT > ( 인덱스키길이 * RECORD수 ) / SORT_AREA_SIZE~~

### 13. 일반

#### 13-01. Altibase는 어떤 인터페이스를 제공하나요?


개요


버전


알티베이스가 제공하는 인터페이스


개요


알티베이스가 제공하는 인터페이스에 대해 설명드립니다.


버전


Altibase HDB 6.1.1 이상


알티베이스가 제공하는 인터페이스


국제 표준의 ANSI SQL-1999를 준수하고, ODBC, ADO. Net, JDBC, Embedded SQL등 다양한 표준 인터페이스를 제공하고 있습니다.


Client 개발환경









|인터페이스 종류|지원 기능|
|---|---|
|ODBC|비주얼 베이직, 파워빌더 같은 RAD(Rapid Application Development) 툴은 물론 대부분의 개발 환경에서 ALTIBASE<br>접근 시 활용<br>재 구현을 통해서 표준 지원을 강화|
|JDBC|JAVA 환경에서 ALTIBASE 응용프로그램 개발 시 활용<br>WAS에서 Connection Pool 구성 시에도 사용<br>재 구현을 통해 성능 향상<br>알티베이스 6.1.1 까지 JDBC 2.0 API 지원, JDBC 3.0 API 일부 지원<br>알티베이스 6.3.1 부터 JDBC 3.0 API 지원<br>알티베이스 7.1.0 부터 JDBC 3.0 API 지원, JDBC 4.2 API 일부 지원<br>알티베이스 7.3.0 부터 JDBC 4.2 API 지원|
|SQLCLI|C 언어 기반의 Altibase의 저수준 API<br>LOB API, ALA (ALTIBASE Log Analyzer) API, ACS (ALTIBASE Call-Level for Spatial) API 제공|
|Embedded<br>SQL<br>(Pre-Compiler)|C 또는 C++의 호스트 언어에서 사용하는 인터페이스<br>SQL 문장을 그대로 호스트 언어에서 사용하므로 개발 생산성 향상|
|ADO.NET|6.5.1 까지 .Net Framework 기반의 .Net Data Provider를 제공<br>7.1.0.8.3 / 7.3.0.0.5 이상부터 .NET Core 3.1 기반의 Altibase ADO .NET 를 제공|
|Unix ODBC|Unix에서 Windows ODBC 소스와 호환되는  표준 DB 접속 API<br>DataStage, Informatica 등의 ETL Tool과 MSTR, Sagent 등의 OLAP Tool과의 호환성 제공|
|PDO|PHP5.3.3 및 PHP7.1.20 과 PHP8.1.8 기반의 PDO 인터페이스를 제공|
|Hibernate<br>Support|Altibase 7.1.0.9.2 및 Altibase 7.3.0.0.2 부터 Hibernate 6.4 를 지원|


Server 개발환경





기능 특징


|SQL|Full Featured SQL92 지원<br>Sub Query INLINE View 같은 국제 기준의 복잡한 Query 지원<br>Hint, SQL 실행 Plan 을 이용한 튜닝 지원|
|---|---|
|Built-in Function|100개 이상의 Built-in Function을 제공<br>사용자는 Built-in Function을 이용하여 SQL 문장 안에서 다양한 연산 수행 가능|
|Stored Procedure & Function|ANSI SQL 표준에 기반한 Stored Procedure 및 Stored Function 지원<br>Procedure에서 Result Set을 클라이언트로 전송 가능<br>Procedure 내에서 Structured Type, Array Type 지원<br>Procedure 내에서 Dynamic SQL/DDL 지원|
|View|여러 개의 테이블을 Union하거나 특정 SQL를 View로 생성하여 효율적으로 조회|
|Trigger|데이터 이벤트 형태의 업무 기능을 위해 표준에 의한 Trigger 지원|

#### 13-02. Altibase와 디스크 기반 DBMS의 가장 큰 차이점은 무엇인가요?

개요


In-Memory 기반 DBMS와 Disk 기반 DBMS간의 가장 큰 차이점에 대한 설명입니다.


버전


ALTIBASE HDB 모든 버전


In-Memory 기반 DBMS와 Disk 기반 DBMS간의 가장 큰 차이점


Altibase Hybrid DBMS로서 In-Memory DB와 Disk 기반 DB를 모두 지원하고 있습니다.


Altibase HDB의 In-Memory DB와 차이점



1.



DBMS 운영시 데이터베이스가 상주하는 위치가 다릅니다.


디스크 기반 DBMS는 전체 데이터베이스가 디스크에 상주하고 필요한 데이터를 메모리 버퍼에 캐싱하여 관리하는 반면에


In-Memory DBMS는 디스크에 존재하는 백업데이터베이스 전체를 메인메모리에 상주시켜 관리합니다.



2. 현격한 성능의 차이가 존재합니다.


기능적인 측면에서 거의 동일하지만, In-Memory DBMS는 디스크 기반 DBMS보다 운영 환경에 따라 약 4 ~ 10 배 이상
빠릅니다.
Altibase HDB를 Memory Only, Hybrid 및 Disk Only 3가지 방식으로 나누어 구성하고 TPC-C 기준에 부합하는 가상의
5가지 동시 발생 트랜잭션


(주문 트랜잭션, 지불 트랜잭션, 배송 트랜잭션, 주문 상태 트랜잭션, 재고수준 트랜잭션)들을
조합하여 온라인 트랜잭션 처리 성능을 측정한 결과 Disk DBMS 대비 높은 성능을 나타내었습니다.


TPC-C란?
온라인 트랜잭션 처리(OLTP) 시스템의 처리 성능을 측정하는 벤치마크 표준 규격의 C모델

#### 13-03. 메모리에 전체 데이터베이스가 존재하는데 데이터의 안전성에는 문제가 없나요?


개요
적용버전
안전성 확보방법
장애 관리 운영 방안


개요


휘발성 특성을 가진 Main Memory의 데이터 안정성을 보장하는 기법을 기술합니다.


적용버전


ALTIBASE HDB 모든 버전에 적용되는 내용입니다.
추가사항 또는 업데이트가 필요한 경우 http://support.altibase.com/kr/ 또는 이 페이지에 댓글로 요청 글 남겨주세요.


안전성 확보방법



1.


2.



WAL프로토콜 방식
데이터베이스의 영속성을 제공하고 Commit된 트랜잭션에 대한 안정성 확보를 위해서 트랜잭션 처리시의 WAL (Write Ahead Logging)
로깅 방식을 사용하고 있으며, 로그파일 개수가 일정 개수이상 되거나 정해진 주기가 되면 메모리의 변경된 데이터 페이지를 디스크로
Write하는 체크 포인트를 통해 복구 시간을 최소화 시키고 있습니다.

- WAL : 로그를 먼저 디스크에 저장하고 DB 페이지를 저장하는 절차. 디스크에 최종 트랜잭션 정보가 저장되어 있어 비정상종료시
트랜잭션로그를 통해 복구할수 있습니다.

백업 및 복구 지원
백업은 DBMS의 비정상 상황에 대비해서 논리적/물리적으로 데이터베이스의 사본을 생성합니다. 이러한 데이터베이스의 사본은 DB
운영 시에 온라인으로 생성이 가능하며, 복구 상황 시에는 백업 받은 데이터베이스 사본을 이용하여 완전복구 또는 불완전 복구를
수행하여 데이터베이스를 정상화시킬 수 있습니다.



장애 관리 운영 방안








|유형|Col2|내 용|
|---|---|---|
|Transaction<br>Failure|원인|내부 혹은 외부적인 요인에 의해 Transaction 중단으로 발생|
|Transaction<br>Failure|해결방안|Transaction의 정상적인 Rollback 을 통해 데이터를 자동 복구하여 데이터베이스의 일관성 유지|
|System Failure|원인|운영시스템의 결함 혹은 정전 등의 장애로 발생|
|System Failure|해결방안|시스템의 Restart 시에 백업 데이터 파일과 Active Log 를 통해서 시스템 Failure 시점까지의 상태로 자동 복구<br>(Restart Recovery)|
|Disk Failure|원인|백업 데이터 파일이 저장된 디스크의 오류로 인해 백업 데이터 파일 손상으로 발생|
|Disk Failure|해결방안|이전의 데이터 백업 파일이 있는 경우 이 파일을 통해 최근의 데이터베이스로 복구가 가능<br>단, 로그 디스크가 손상된다거나 Archive Log 를 삭제하였을 경우, 가장 최근의 상태로의 복구가 불가능|


