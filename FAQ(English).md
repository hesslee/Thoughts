    -   Error Code
        
        ```
        0x111BE (  70078) smERR_ABORT_NOT_BUILT_INDEX Failed to scan the index because it was not rebuilt. (Index Name :<0%s>) 
        # *Cause: This index was not rebuilt when the Altibase server was starting up. The value of INDEX_REBUILD_AT_STARTUP property is set to 0.
        # *Action: Rebuild this index. Or to rebuild all the indexes, delete INDEX_REBUILD_AT_STARTUP = 0 in altibase.properties and restart the Altibase server.
        ```
