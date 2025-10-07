1. Home . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 5


1.1 01. Installation, Patch, Upgrade . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 5
1.1.1 Altibase Client Installation . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 5

1.1.1.1 Starting from ALTIBASE HDB 5.5.1 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 5
1.1.2 Altibase Server Patch Procedure on Unix and Linux . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 9
1.1.3 What Platforms (OS) Altibase HDB supports? . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 15
1.1.4 What to do when installing Altibase on Windows, and it says "It has already been installed" . . . . . . . . . . . . . . . . 16
1.2 02. Operation and Management . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 17
1.2.1 [Linux] How to register Altibase server process auto start script . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 17
1.2.2 Altibase Server Configuration for IPC Communication . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 19
1.2.3 Automatic altibase startup during OS booting in Solaris . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 21
1.2.4 Can PUBLIC SYNONYM be dropped? . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 25
1.2.5 Can table data be saved on disk and only indexes can be created in memory? . . . . . . . . . . . . . . . . . . . . . . . . . 25
1.2.6 Database Security Checklist . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 26
1.2.7 Detailed procedure for changing character set . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 40
1.2.8 How to change sys user password . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 44
1.2.9 How to change the database's db name . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 46
1.2.10 How to change the path of log anchor, online log file, archive log file, and double write file . . . . . . . . . . . . . . . 49
1.2.11 How to change the tablespace data file path . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 52
1.2.12 How to check the history of adding datafiles . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 58
1.2.13 How to create and execute Job objects . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 59
1.2.14 How to create a user (CREATE USER) and change a password (ALTER USER) . . . . . . . . . . . . . . . . . . . . . . . . 64
1.2.15 How to forcefully close a session that is being locked . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 65
1.2.16 How to modify column . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 66
1.2.17 How to resolve when LOCK TIMEOUT occurs . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 68

1.2.18 How to start and stop the database . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 70
1.2.19 How to startup Altibase automatically when booting from HP-UX . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 77
1.2.20 Maximum Capacity Specifications for Altibase . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 82
1.2.21 Notes/Considerations when changing TRANSACTION_TABLE_SIZE . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 82
1.2.22 Notes/Considerations when increasing the number of concurrent connection sessions (MAX_CLIENT) . . . . . . . . 86
1.2.23 Notes on using floating point data type (double, float) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 89
1.2.24 User password length limitation - Differences by version . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 92
1.2.25 What is MEM_MAX_DB_SIZE? . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 93
1.2.26 When log disk is FULL and its countermeasures . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 96
1.2.27 When server create errors occur after DB name change . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 100
1.3 03. Replication . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 101
1.3.1 Causes and Solutions of Replication Conflicts . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 101
1.3.2 DDL operation on the table for Altibase replication . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 104
1.3.3 How to add/delete replication target table . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 105
1.3.4 How to change replication object IP . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 107
1.3.5 How to create/delete replication objects . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 108
1.3.6 How to create multiple replication objects with the same IP . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 116
1.3.7 Replication give-up . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 118
1.3.8 Replication monitoring query . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 120
1.4 04. Backup and Recovery . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 123
1.4.1 How to recover cold backup by changing directory path . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 123
1.4.2 Online Backup and Time Based Recovery . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 126
1.4.3 Using aexport and iloader . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 129
1.4.3.1 Create database object and upload data . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 130
1.4.3.2 Database object backup using aexport . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 133
1.4.3.3 Data download using iloader . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 137
1.4.3.4 What is aexport, iloader? . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 141
1.5 05. SQL . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 142
1.5.1 Comparison between VARCHAR and CHAR types . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 142
1.5.2 How to check the privileges granted to an object . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 143
1.6 06. Stored Procedure . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 145

1.6.1 How to check the contents of stored procedure . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 145
1.6.2 How to check the number of records affected by DML within the stored procedure . . . . . . . . . . . . . . . . . . . . . . 149
1.7 07. Development and API . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 150
1.7.1 Connection disconnection, error codes, and error messages in each case (APRE*C/C++, SQLCLI) . . . . . . . . . . . 150
1.7.2 How to manage Spring+iBatis transaction . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 154
1.7.3 JDBC . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 158

1.7.3.1 How to change the jdbc.trc file creation location . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 158
1.7.3.2 How to use Fail-Over in Altibase JDBC . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 159

1.7.4 ODBC . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 162

1.7.4.1 32-bit ODBC installation on 64-bit Windows . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 162

1.7.4.2 Integrating with unix_odbc . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 165
1.7.4.3 ODBC function, SQLFreeStmt . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 169
1.7.5 PHP . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 170

1.7.5.1 Hangul is broken when using php . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 170
1.8 08. Monitoring . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 173
1.8.1 Disk table and index usage . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 173


1.8.1.1 ALTIBASE HDB 4.3.9.x . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 174

1.8.1.2 ALTIBASE HDB 5.1.5.x . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 176

1.8.1.3 ALTIBASE HDB 5.3.x, 5.5.1, 6.1.1, 6.3.1 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 183
1.8.2 Disk tablespace usage . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 190
1.8.2.1 ALTIBASE HDB 4.3.9 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 190

1.8.2.2 ALTIBASE HDB 5.1.5 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 192

1.8.2.3 ALTIBASE HDB 5.3.3, 5.3.5 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 193
1.8.2.4 ALTIBASE HDB 5.5.1, 6.1.1, 6.3.1 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 195
1.8.3 How to determine which queries are being rolled back . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 199
1.8.4 How to log queries performed in Altibase (altiProfile)? . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 201
1.8.5 How to set up and execute altimon . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 209
1.8.6 Lock related properties . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 213
1.8.7 Memory table and index usage . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 214
1.8.8 Memory tablespace usage . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 220
1.8.8.1 ALTIBASE HDB 5.5.1, 6.1.1, 6.3.1 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 220
1.8.9 Monitoring Tools for Windows . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 223
1.8.10 System information by OS . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 227
1.8.11 Table/Column Definition . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 245
1.8.12 Undo Tablespace . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 249
1.8.12.1 Monitoring method when undo tablespace usage increases . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 249
1.8.12.2 Undo tablespace usage . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 261
1.9 09. Error Messages . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 264
1.9.1 [Notify : Fetch Timeout] Session Closed by Server. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 264
1.9.2 [Warning] Memory allocation failed. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 272
1.9.3 altibase_boot.log - TRY_COUNT, LOCK_COUNT, MISS_COUNT . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 274
1.9.4 Closed Socket by client is Detected . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 275
1.9.5 ERR-0109D Insufficient memory. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 276
1.9.6 ERR-311E0 The estimated size of the index key exceeds the maximum limit. . . . . . . . . . . . . . . . . . . . . . . . . . . 278
1.9.7 ERR-410D2 (266450) Fetch out of sequence. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 279
1.9.8 ERR-1105D Unable to begin a new update statement. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 286
1.9.9 ERR-4103C (266300) Request of fetching data to an unprepared SQL statement. . . . . . . . . . . . . . . . . . . . . . . . 289
1.9.10 ERR-4109C Invalid session property. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 295
1.9.11 ERR-5102E ( 331822) Invalid cursor state. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 298
1.9.12 ERR-7101D ( 462877) Protocol header error. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 300
1.9.13 ERR-11030 ( 69680) The data file cannot be extended because the requested size is bigger than the maximum size

(FID:<0%d>). . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 303
1.9.14 ERR-11036 The data file is in use. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 305
1.9.15 ERR-11049 ( 69705) Too many pages are allocated ( Maximum Number of Pages= #). . . . . . . . . . . . . . . . . . . 306
1.9.16 ERR-11075 The transaction has exceeded the lock timeout specified by the user. . . . . . . . . . . . . . . . . . . . . . . 309
1.9.17 ERR-11118 ( 69912) The update log size '?????' is bigger than TRX_UPDATE_MAX_LOGSIZE '?????' . . . . . . . . 312
1.9.18 ERR-11183 ( 70019) Insufficient page descriptor area in the temp table. . . . . . . . . . . . . . . . . . . . . . . . . . . . . 317
1.9.19 ERR-11184 ( 70020) Insufficient free space in work area . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 322
1.9.20 ERR-21010 Value overflow. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 324

1.9.21 ERR-21011 : Invalid literal . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 325

1.9.22 ERR-31283 Unable to create a primary key or a unique key constraint in the local non-prefixed index. . . . . . . . 327
1.9.23 ERR-41059 ( 266329) Task pool overflow. Check properties. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 331
1.9.24 ERR-71018 ( 462872) Failed to invoke a system function, read() or Failed to invoke the read() system function . 336
1.9.25 ERR-71019(errno=104) Failed to invoke a system function, write() . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 338
1.9.26 ERR-91015 ( 593941) Communication failure . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 338
1.9.27 How to check the 8-digit errorcode of altibase_qp.log . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 342
1.9.28 Not found data . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 343

1.9.29 tablespace does not have enough free space error . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 349
1.10 10. Migration . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 350
1.11 11. Utilities . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 350

1.11.1 AdminCenter2 execution file . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 350

1.11.2 iLoader . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 351

1.11.2.1 An error occurs when uploading a DOS format data file to iloader. . . . . . . . . . . . . . . . . . . . . . . . . . . . . 351
1.12 12. Others . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 353

1.12.1 Thread process debugging method . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 353
1.13 13. General . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 356

1.13.1 The entire database exists in memory. Is there any problem with the safety of the data? . . . . . . . . . . . . . . . . . . 356
1.13.2 What interface does Altibase provide? . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 357
1.13.3 What is the biggest difference between Altibase and disk-based DBMS? . . . . . . . . . . . . . . . . . . . . . . . . . . . . 358
1.14 Altibase Error Messages . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 360
1.14.1 make Cannot find a rule to create target connect1.o from dependencies. . . . . . . . . . . . . . . . . . . . . . . . . . . . . 360
1.14.2 ERR-0106B The session has been disconnected by the client . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 361
1.14.3 ERR-01044 Client's query exceeded in the execution time limitation . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 362
1.14.4 ERR-01050 License File does not exist . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 362

1.14.5 ERR-01067 The memory size allocated for the statement has exceeded the maximum limit . . . . . . . . . . . . . . . 363
1.14.6 ERR-0108D License invalid or expired . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 364
1.14.7 ERR-0109D Insufficient memory . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 364
1.14.8 ERR-11030 The data file cannot be extended because the requested size is bigger than the maximum size (262144


pages) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 366
1.14.9 ERR-11036 The data file is in use . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 367

1.14.10 ERR-11041 A deadlock situation has been detected . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 368

1.14.11 ERR-11049 Too many pages were allocated . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 369
1.14.12 ERR-1105D Unable to begin a new update statement . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 369
1.14.13 ERR-11058 The row already exists in a unique index . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 372
1.14.14 ERR-11075 The transaction has exceeded the lock timeout specified by the user . . . . . . . . . . . . . . . . . . . . . 372
1.14.15 ERR-11118 The update log size '10485760' is bigger than TRX_UPDATE_MAX_LOGSIZE . . . . . . . . . . . . . . . . 376
1.14.16 ERR-11123 The tablespace does not have enough free space . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 377
1.14.17 ERR-11098 smERR_ABORT_BackupLogMode cannot be executed in no archive log mode . . . . . . . . . . . . . . . 378
1.14.18 ERR-110AA Duplicate tablespace names . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 379
1.14.19 ERR-2100D Invalid length of the data type . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 380
1.14.20 ERR-21010 Value overflow . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 380

1.14.21 ERR-21011 Invalid literal . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 381

1.14.22 ERR-21013 Calculation stack overflow . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 382

1.14.23 ERR-31088 A replicated table must have a primary key . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 382
1.14.24 ERR-3109F REPL sender failure to handshake with peer server . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 383
1.14.25 ERR-311E0 The estimated size of the index key exceeds the maximum limit . . . . . . . . . . . . . . . . . . . . . . . . . 383
1.14.26 ERR-31283 Unable to create a primary key or a unique key constraint in the local non-prefixed index . . . . . . . 385
1.14.27 ERR-40029 Failed to invoke a system function, flock_trywrlock() . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 388
1.14.28 ERR-4102C Incompatible NLS between the client and the server . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 389
1.14.29 ERR-41047 The transaction is already active . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 390
1.14.30 ERR-41059 Task pool overflow . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 390
1.14.31 ERR-4109C invalid session property . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 391
1.14.32 ERR-410CF Too many statements have been allocated to this session . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 392
1.14.33 ERR-410D5 Client unable to establish connection. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 392

1.14.34 ERR-7101d Protocol header error . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 393

1.14.35 ERR-51039 Invalid Protocol . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 394

1.14.36 ERR-51043 Communication link failure . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 395

1.14.37 ERR-6100D Sender failed to handshake with the peer server . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 395
1.14.38 ERR-61035 Receiver - An update conflict occurred . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 396
1.14.39 ERR-61100 rpERR_ABORT_RPC_DUPLICATE_REPLICATION Duplicate replication names. The replication name

already exists in the database. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 396
1.14.40 ERR-71018 Failed to invoke the read() system function . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 397
1.14.41 ERR-71019 Failed to invoke the write() system function Flush protocol failed. Close connection . . . . . . . . . . . 398
1.14.42 ERR-91020 No Connection State . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 398

1.14.43 ERR-9103D Data parsing error - LineXXXX . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 399
1.14.44 ERR-201436 The number of host variables exceed the maximum limit (1024) . . . . . . . . . . . . . . . . . . . . . . . . 399
1.14.45 ERR-11025 The data file already exists . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 400
1.14.46 ERR-11027 The data file does not exist . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 400

1.14.47 ERR-11035 The tablespace does not have enough free space . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 401
1.14.48 ERR-11136 The LogAnchor file already exists . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 401
1.14.49 ERR-135181 Invalid data type length . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 402
1.14.50 ERR-266300 Request of fetching data to an unprepared SQL statement . . . . . . . . . . . . . . . . . . . . . . . . . . . . 402
1.14.51 ERR-266447 mmERR_ABORT_TOO_MANY_STATEMENTS_IN_THE_SESSION . . . . . . . . . . . . . . . . . . . . . . . . . 403
1.14.52 ERR-31020 You cannot execute DDL on a replicated table . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 404
1.14.53 ERR-3103F No DDL statement is allowed to be executed on a replicated table . . . . . . . . . . . . . . . . . . . . . . . 404
1.14.54 ERR-311B1 The user must have SYSDBA privilege(s) to execute this statement . . . . . . . . . . . . . . . . . . . . . . . 405
1.14.55 ERR-312C4 Cannot execute this DDL on a replicated table when the system property REPLICATION_DDL_ENABLE is

0 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 406

1.14.56 ERR-1051 Memory allocation failed . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 407
1.14.57 ERR-0001c Unable to shutdown the communication channel . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 407

1.14.58 ERR-01002 Invalid character in use . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 408

1.14.59 ERR-01027 No more IPC channel . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 409
1.14.60 ERR-0109F Library file for external procedure(function) not found . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 409
1.14.61 ERR-11009 Failed to invoke a system function, shmat() . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 410
1.14.62 ERR-11107 smERR_ABORT_UNABLE_TO_CREATE_CUZ_VOL_MAX_DB_SIZE Unable to create the tablespace

because the database would be larger than VOLATILE_MAX_DB_SIZE . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 410
1.14.63 ERR-11118 The update log size '…' is bigger than TRX_UPDATE_MAX_LOGSIZE '…' . . . . . . . . . . . . . . . . . . . 411
1.14.64 ERR-31233 The fixed record size exceeds the page size . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 412
1.14.65 ERR-31240 Invalid request to process SQL statement . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 412
1.14.66 ERR-4105A Several statements still open . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 413
1.14.67 ERR-410B7 Invalid size of data to bind to a host variable Data Size . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 413

1.14.68 ERR-51024 Different protocol versions . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 414
1.14.69 ERR-5102E Invalid cursor state . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 414

1.14.70 ERR-51041 Indicator variable required but not supplied . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 415
1.14.71 ERR-5104F Communication link failure. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 416

1.14.72 ERR-5105A The connection does not exist. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 416

1.14.73 ERR-52027 String data right-truncated . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 417
1.14.74 ERR-61001 A conflict occurred while executing the received statement . . . . . . . . . . . . . . . . . . . . . . . . . . . . 418
1.14.75 ERR-61016 rpERR_ABORT_RP_SENDER_MAKE_XLOG Sender Failed to make an xlog . . . . . . . . . . . . . . . . . . 418
1.14.76 ERR-61023 rpERR_ABORT_RP_REPLICATION_DISABLED Replication is disabled . . . . . . . . . . . . . . . . . . . . . . 419


1.14.77 ERR-61036 Receiver err_not found in deleteXlog() . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 419
1.14.78 ERR-6103a Receiver err_not_found in updateXlog() . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 420
1.14.79 ERR-610CF The transaction table size of the replication does not match . . . . . . . . . . . . . . . . . . . . . . . . . . . 420
1.14.80 ERR-610D2 The primary key column count of the replicated table does not match . . . . . . . . . . . . . . . . . . . . . 421
1.14.81 ERR-610a0 Sender Stopping REP1 sender thread . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 421
1.14.82 ERR-61113 A replicated table must have a primary key. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 422
1.14.83 ERR-71015 cmERR_ABORT_SELECT_ERROR Failed to invoke the select() system function . . . . . . . . . . . . . . . 422
1.14.84 ERR-91013 The query was too long the maximum length is 65536 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 423
1.14.85 ERR-9102B utERR_ABORT_Token_Value_Range_Error Token value length overflow. Maximum token length=0%d.

Column =1%s, Value=2%s . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 424
1.14.86 ERR-91044 Error occurred during data file IO. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 424
1.14.87 ERR-A100C Conversion not applicable . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 425
1.14.88 ERR-A1013 Calculation stack overflow . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 425

1.14.89 ERR-0104E The property XXX is read-only . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 426
1.14.90 ERR-110F0 Unable to extend the tablespace (SYS_TBS_MEM_DIC) because the database would be larger than

MEM_MAX_DB_SIZE(12582912K) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 426
1.14.91 ERR-41041 Another SYSDBA session is already running . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 428
1.14.92 ERR-51014 Function sequence error . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 429
1.14.93 ERR-5104D Connection timeout . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 429

1.14.94 ERR-51067 Neither PORT_NO in the connection string or ALTIBASE_PORT_NO environment variable are set . . . 430
1.14.95 ERR-51192 The call to getaddrinfo() failed. The host name or service may be unknown . . . . . . . . . . . . . . . . . 430
1.14.96 ERR-61000 The received record was not found in the database . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 431

1.14.97 ERR-6100C rpERR_ABORT_RP_RECEIVER_NOT_FOUND The receiver does not exist . . . . . . . . . . . . . . . . . . . 431
1.14.98 ERR-1102A Tablespace node not found . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 432
1.15 ALTIBASE HDB Administration . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 432

1.15.1 How to terminate a session . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 432

1.15.2 Useful SQL . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 434
1.15.2.1 Miscellaneous queries . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 434
1.15.2.2 SQL about Objects . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 438
1.15.2.3 SQL about Replication . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 451
1.15.2.4 SQL about Sessions . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 454

1.15.2.5 SQL about Statements . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 456
1.15.2.6 SQL about Tablespaces . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 460
1.16 ALTIBASE HDB Architecture . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 465

1.16.1 ALTIBASE HDB Architecture Overview . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 465

1.16.2 How a query is executed in ALTIBASE HDB . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 466
1.16.3 Transaction Durability in ALTIBASE HDB . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 467
1.17 ALTIBASE HDB Developer . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 469
1.18 ALTIBASE HDB General Information . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 469

1.19 ALTIBASE HDB Performance Tuning . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 469
1.19.1 Performance diagnostics for ALTIBASE HDB . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 469
1.19.1.1 1. Application side diagnostics . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 469
1.19.1.2 2. Database side diagnostics . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 472
1.19.1.3 3. System side diagnostics . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 475
1.20 ALTIBASE HDB Replication . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 478
1.20.1 Replication Overview . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 478
1.20.2 What is a Replication Conflict? . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 481
1.20.3 How to resolve a replication conflict? . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 482
1.20.4 What is Offline Replicator? . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 483
1.21 ALTIBASE HDB Troubleshooting . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 484
1.21.1 Information required to diagnose ALTIBASE HDB problems . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 484
1.21.2 A transaction exceeds lock timeout value specified by user . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 487
1.21.3 The number of logfiles grows rapidly . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 488
1.21.4 A user tablespace does not have enough free space . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 490
1.21.5 Cannot insert new records after deleting bulk records . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 491
1.21.5.1 1. Test case with ALTIBASE HDB 5.3.3 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 493

1.21.5.2 2. How did we determine that the cause of the problem is the Index Segment ? . . . . . . . . . . . . . . . . . . . 496
1.21.5.3 3. How to avoid the problem by seperating Tablespaces ? . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 497
1.21.6 Performance degradation issue when upgrading AIX OS to 6.1 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 504


# Home

This is the home of the FAQ space.


To help you on your way, we've inserted some of our favorite macros on this home page. As you start creating pages, blogging, and
commenting you'll see the macros below fill up with all the activity in your space.

## 01. Installation, Patch, Upgrade

### Altibase Client Installation


Starting from ALTIBASE HDB 5.5.1


OS

Download Altibase Client Installation File

Upload Altibase Client Installation File
Change Altibase installation file execution permission
Start Installation

Check OS user initialization file

Apply OS user initialization file
Installation verification


OS


Linux

HP-UX

AIX

Solaris


Download Altibase Client Installation File


Download the client installation file from http://support.altibase.com/en/product
If you do not have the version of the client you want to install, please request it through the Customer Service -> Request
Technical Support menu at +82-2-2082-1114 or http://support.altibase.com/en/.


Upload Altibase Client Installation File


Upload the installation file to the server where you want to install the Altibase client.
As the OS user, you want to install and upload the installation package to a random path.


Change Altibase installation file execution permission


Altibase client installation files have only read and write permissions as default permissions.
Execute permission is required to proceed with the installation.


Add the execution permission as follows.





After changing the permission, check that the rw rw -r execution permission has been added as shown below.x x x


Start Installation


Execute the installation file as shown below.





Example of the installation process


$ ./altibase-HDB-client-6.3.1.3.1-LINUX-X86-64bit-release.run

---------------------------------------------------------------------------
Welcome to the ALTIBASE HDB Client 6.3.1.3.1 setup wizard.


---------------------------------------------------------------------------
Installation Directory


Please specify the installation directory for ALTIBASE HDB Client 6.3.1.3.1


Installation directory [/data/heejung.lee/altibase_home]:  # Enter the directory to install as an
absolute path.


Please select the installation type.


Installation type


[1] Patch: patch package install

[2] Full installation: full package install
Please choose an option [1] :                 # Enter after entering 2 times


---------------------------------------------------------------------------
ALTIBASE HDB Property setting


ALTIBASE HDB connection port number (1024-65535) [20300]:  # Enter the service port of the
Altibase server. If it is the default, type enter.


---------------------------------------------------------------------------
Setup is now ready to install ALTIBASE HDB Client 6.3.1.3.1.


Do you want to continue? [Y/n]:                # Press Enter to start the installation.


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
$                               # Installation ended.


Check OS user initialization file


If the above process is successful, the following contents are included in the OS user's configuration file.





The name of the OS user initialization file is different for each SHELL.
.profile for Bourne shell(sh), korn shell(ksh)
.bash_profile or .profile for the bash shell (bash)
.Login or .cshrc for C shell(csh)


Apply OS user initialization file


To apply the environment variables added to the initialization file, proceed as follows.


$ . ~/.bash_profile


Or


$ . ~/.profile


Check the value of the environment variable to see if it applies.


$ echo $ALTIBASE_HOME
/data/heejung.lee/altibase_home


Installation verification


Altibase server connection test is performed by using iSQL


isql -u DBusername -p password -s IP -port serviceport


Example


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

### Altibase Server Patch Procedure on Unix and Linux


Overview

Preparation before patching
Patch Procedure


1. Check the current version

2. Shutdown Altibase Server **

3. Backup existing installation files
4. Upload patch package and change permissions

ALTIBASE HDB server version 5.5.1 or later (all versions since 5.5.1, 6.1.1, 6.3.1, and 6.3.1)
ALTIBASE HDB server version 5.5.1 or earlier (all versions below 5.3.3 such as 4.3.9, 5.3.3, etc.)
5. Perform the patch

ALTIBASE HDB server version 5.5.1 or later (all versions since 5.5.1, 6.1.1, 6.3.1, and 6.3.1)
ALTIBASE HDB server version 5.5.1 or earlier (all versions below 5.3.3 such as 4.3.9, 5.3.3, etc.)
6. Check the patch version
7. Copy necessary files from the backup file
8. STARTUP ALTIBASE HDB Server **

Precautions

Check meta version before/after patch
When patching from ALTIBASE HDB 4.3.9.1 ~ 4.3.9.50 to 4.3.9.51 ~**


Overview


Patching means minor version changes.
Altibase server version consists of 4 or 5 digits.
The first three digits refer to the major version and the last one or two digits refer to the minor version.
Changing the last three digits without changing the first three digits is called a 'patch', and changing the first three digits is
called 'upgrade'.


This page describes the procedure for patching Altibase servers in Unix and Linux environments.
Since the Altibase server patch must be performed after the Altibase server is shut down, service downtime is required.
Therefore, the user must secure downtime before patching.


Preparation before patching


Check the following before proceeding.


Can Altibase server downtime be secured? (Confirmed with the client)
Does the meta version change after patching? (Confirm with Altibase engineer)
Are there any caveats if the patch version is different from the current version? (Confirm with Altibase engineer)
Example: In order to patch from HDB 4.3.9.44 to Altibase HDB 4.3.9.233.


Patch Procedure


1. Check the current version


Make a note of the version check result below.





2. Shutdown Altibase Server **


Shutdown the Altibase server.





After the shutdown, check the Altibase server process and service port LISTEN status. When the following two commands are
executed, there should be no results to indicate a normal shutdown.


$ ps -ef | grep 'altibase -p' | grep -v grep      # To check the Altibase server process
$ netstat -an | grep 20300               # To check the service port


3. Backup existing installation files


Back up necessary directories so that problems can be recovered after patching.





If the size of the $ALTIBASE_HOME directory is not large, the user can make a full backup of the $ALTIBASE_HOME directory as
shown below.


$ cp -Rp altibase_home altibase_home.bak


4. Upload patch package and change permissions


ALTIBASE HDB server version 5.5.1 or later (all versions since 5.5.1, 6.1.1, 6.3.1, and 6.3.1)


Log in as the ALTIBASE HDB server installation user.
Upload the patch package to a random path.
From ALTIBASE HDB server version 5.5.1, the Java-based installer was used, and the package name ends with .run as shown
below.

Grant execute permission to run the package.





ALTIBASE HDB server version 5.5.1 or earlier (all versions below 5.3.3 such as 4.3.9, 5.3.3, etc.)


Log in as the ALTIBASE HDB server installation user.
Upload the patch package under the $ALTIBASE_HOME directory.
ALTIBASE HDB Server versions earlier than 5.5.1 provide compressed files.


altibase-XEON_LINUX_redhat_Enterprise_release5-64bit-5.3.3.84-release-GCC4.1.2.tgz


5. Perform the patch


ALTIBASE HDB server version 5.5.1 or later (all versions since 5.5.1, 6.1.1, 6.3.1, and 6.3.1)


After executing the executable file as shown below, the subsequent operation proceeds according to the message.


$ ./altibase-HDB-server-6.1.1.3.8-LINUX-X86-64bit-release.run


ALTIBASE HDB server version 5.5.1 or earlier (all versions below 5.3.3 such as 4.3.9, 5.3.3, etc.)


Move to the $ALTIBASE_HOME directory and extract the files as follows.


$ cd $ALTIBASE_HOME
$ gzip -cd altibase-XEON_LINUX_redhat_Enterprise_release5-64bit-5.3.3.84-release-GCC4.1.2.tgz |

tar xvf 

6. Check the patch version


After completing the patch execution, check the version to see if the patch is applied.






7. Copy necessary files from the backup file


If the default password (manager) of the sys user is changed, the $ATLIBASE_HOME/bin/server, is, il scripts would have
changed.
In this case, copy server, is, and il from the bin directory of the backup directory to $ALTIBASE_HOME/bin.


$ cd $ALTIBASE_HOME
$ cp -p bin.bak/server bin/
$ cp -p bin.bak/is bin/
$ cp -p bin.bak/il bin/


8. STARTUP ALTIBASE HDB Server **


After starting the Altibase server process, check the process and service port listen status.


$ server start


After shutdown, check the Altibase server process and service port LISTEN status.


When the following two commands are executed, there should be no results to indicate a normal shutdown.


$ ps -ef | grep 'altibase -p' | grep -v grep      # To check the Altibase server process
altibase 10758 1 0 12:01 ? 00:00:14 /home/altibase/bin/altibase -p boot from admin


$ netstat -an | grep 20300               # To check the service port.
tcp    0   0 0.0.0.0:20300        0.0.0.0:*          LISTEN


Precautions


Check meta version before/after patch


If the meta version changes, the database cannot be reverted to a lower version.
After patching to a higher version, there may be cases where the user inevitably needs to revert to a lower version. If the meta
version is changed, this cannot be done.
Therefore, if the meta version changes, the user should be aware of this and proceed with the patching, and if necessary, take

an offline full backup before the patch.
Offline full backup targets include data files, log anchor files, log files, and configuration files.


When patching from ALTIBASE HDB 4.3.9.1 ~ 4.3.9.50 to 4.3.9.51 ~**


If the following conditions are satisfied, the replication will not work after patching.


When patching from ALTIBASE HDB 4.3.9.1 ~ 4.3.9.50 to 4.3.9.51 ~
Replication environment


Therefore, if the above conditions are satisfied, the user must follow the procedure below to apply the patch.



1.


2.



Secure the Altibase server downtime


Shutdown the Altibase server (Refer to step 2 of the patch procedure)


3.


4.


5.


6.


7.


8.


9.


10.


11.


12.


13.



( p p p )


Change the service port
Temporarily change the service port during patching to ensure that access to Altibase is blocked.


$ cd $ALTIBASE_HOME/conf
$ vi altibase.properties        # Changed PORT_NO in altibase.properties.


Startup the Altibase server (Refer to step 3 of the patch procedure)


Check the replication gap**
Must make sure it is 0.



Backup the replicated object creation syntax by performing aexport


$ aexport           # The user can check the syntax for creating a replication object in the
SYS_CRT_REP.sql file created after performing aexport.


Drop replication object**


-- Check the replication object name

iSQL> SELECT REPLICATION_NAME FROM SYSTEM_.SYS_REPLICATIONS_;


-- Stop the replicaiton
iSQL> ALTER REPLICATION replication_name STOP;


-- Drop replication object
iSQL> DROP REPLICATION replication_name;


Perform the checkpoint


iSQL> ALTER SYSTEM CHECKPOINT;          -- Repeat 4 times


Shutdown the Altibase server (Refer to step 2 of the patch procedure)


Perform the patch (Refer to step 2 to step 7 of the patch procedure)


Add CHECK_LOGFILE property**


$ cd $ALTIBASE_HOME/conf
$ vi altibase.properties        # Save after adding CHECK_LOGFILE = 0 to the last line of
altibase.properties file.


Startup the Altibase Server (Refer to step 8 of the patch procedure)


Delete CHECK_LOGFILE property**




14.


15.


16.


17.


18.


19.



$ cd $ALTIBASE_HOME/conf
$ vi altibase.properties        # CHECK_LOGFILE added to the last line of altibase.properties file = 0

Delete and save.


Insert data after creating temporary table
This is to use up the log files created in the previous version and create a new log file.


CREATE TABLE IMSI_T (C1 INTEGER, C2 INTEGER);


CREATE OR REPLACE PROCEDURE IMSI_PROC AS V1 INTEGER;

BEGIN

FOR V1 IN 1 .. 300000 LOOP
INSERT INTO IMSI_T VALUES (V1, V1);

END LOOP;

END;

/


iSQL> SELECT CUR_WRITE_LF_NO FROM V$LFG; - Check the result (number).

iSQL> EXEC IMSI_PROC; - Perform an insert on a temporary table.
iSQL> SELECT CUR_WRITE_LF_NO FROM V$LFG; - If it is greater than the result checked above, it is
completed. If it is not different from the result checked above, re-execute the IMSI_PROC procedure.
iSQL> DROP PROCEDURE IMSI_PROC; - Drop temporary tables and procedures.

iSQL> DROP TABLE IMSI_T;


Perform the checkpoint


iSQL> ALTER SYSTEM CHECKPOINT;          -- Repeat 4 times.


Create replication object


$ is -f SYS_CRT_REP.sql             # Execute the created SYS_CRT_REP.sql file after executing

aexport.


Start replication


   - Check the replicaiton object name

iSQL> SELECT REPLICATION_NAME FROM SYSTEM_.SYS_REPLICATIONS_;

   - Stop the replication
iSQL> ALTER REPLICATION replication_name START;


Shutdown Altibase server (Refer to step 2 of the patch procedure)
Change the temporarily changed service port to the original.


Change the service port
Change the temporarily changed service port to the original.


20.


21.



$ cd $ALTIBASE_HOME/conf
$ vi altibase.properties        # Changed PORT_NO in altibase.properties.


Startup the Altibase server (Refer to step 8 of the patch procedure)


Check the service


### What Platforms (OS) Altibase HDB supports?

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
|---|---|---|---|---|
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
|SUN|i86PC|2.10 or later|2.10 or later|2.10 or later|
|Windows|x86, x86-64|Windows 2003<br>Windows 2008<br>Windows 2012<br>Windows 7, 8|64-bit|64-bit, 32-bit|


Java Version


Altibase HDB 6 and later versions of JDBC are compatible with JDK 1.4 and later.




### What to do when installing Altibase on Windows, and it says "It has already been installed"

Situation


If the user repeats Altibase installation and uninstallation on Windows, it may not install normally.


As for the error, if the user tries to install the full package, the user will get an error saying that it is already installed. In addition, if the
user tries to patch it, it will get an error saying that it cannot be done.


Solution


The above situation is because the Altibase program registered in the registry has not been deleted normally.


So, the user has to delete the entry from the registry.


Here is how to run the registry: (Windows Start -> Run -> Run regedit.exe)


Below is the item to be deleted.





If the user deletes the above item, it is cleaned up in the registry, so the user can proceed with the install the Altibase normally.

## 02. Operation and Management

### [Linux] How to register Altibase server process auto start script


Overview

Version

OS

How to register

Sample of autostart script

Register the script in /etc/init.d
Change the script
Change the script execution permission
Execute chkconfig
Check the chkconfig registration
Log


Overview


This section describes how to automatically start the Altibase server process when booting the OS on the Linux server.


Version


Altibase 4 or later


OS


Linux


How to register


Sample of autostart script


altibased


The automatic startup script was written to run in the following situations.


One Altibase server running on one server
Installing Altibase server in OS user altibase and have startup/shutdown privileges
Running in bash shell
Using the chkconfig utility


This script is a sample file. Depending on the client's OS user's environment settings, it may operate differently than intended, so be sure
to test it to check whether it is running properly.


Register the script in /etc/init.d


Upload the autostart script altibased file to the /etc/init.d directory.


Change the script


Change the user variable at the top of the script to suit the client's environment.


$ vi /etc/init.d/altibased
#!/bin/bash

#

# altibase

#

# chkconfig: 2345 20 80
# description: ALTIBASE process startup
user=altibase             # Change to a user with privileges to start/stop Altibase server processes


Change the script execution permission


$ chmod +x altibased


$ ls -l altibased
-rwxr-xr-x 1 root root 811 Sep 3 13:50 /etc/init.d/altibased


Execute chkconfig


$ chkconfig --add altibased


Check the chkconfig registration


$ ls -l /etc/rc.d/rc*.d/K*alti*
$ ls -l /etc/rc.d/rc*.d/S*alti*


Log


The log is set to remain in /var/log/${user}_altibased.log.

### Altibase Server Configuration for IPC Communication


Overview

Version

ALTIBASE HDB Server Configurations
OS Configurations
How the application communicates


Overview


There are four communication methods between the database server and client provided by ALTIBASE HDB. Among these, this
document describes the ALTIBASE HDB and OS configurations required for IPC communication.


TCP/IP

Unix Domain Socket

IPC using shared memory
SSL/TLS (supported starting from ALTIBASE HDB version 6.5.1)


For a description of each communication method, please refer to the "12. Server/Client Communication" section from the Administrator's
manual.


Manual Page:


https://github.com/ALTIBASE/Documents/tree/master/Manuals
http://support.altibase.com/en/manual


Version


All the ALTIBASE HDB versions


ALTIBASE HDB Server Configurations


By default, the Altibase server does not allow IPC access. So, in order to connect to the Altibase server with the IPC connection type, the
Altibase server properties must be changed.


Related properties cannot be changed while the Altibase server is running. Therefore, the Altibase server needs to be restarted in order
to change the property value.


IPC_PORT_NO


This property is required when running an Altibase server on a Windows system.


Unix and Linux use the 'Unix domain socket' in the form of a file for IPC connection, but Windows does not support this, so a TCP port is
required for IPC connection.


In Windows, IPC connections communicate using shared memory, semaphores, and mutexes over TCP connections.


IPC_CHANNEL_COUNT


This property configures the maximum number of IPC sessions that can be connected to the Altibase server. The default value is 0, and
the Altibase server is configured not to allow IPC access.


IPC_FILEPATH


IPC communicates with the ALTIBASE HDB server with the 'Unix domain socket' in the form of a file.
If the 'Unix domain socket' file does not exist or the path is set incorrectly, the connection will fail.
Starting from ALTIBASE HDB server version 5.5.1.4.2, the user can change this path arbitrarily with the IPC_FILEPATH property, and the
setting value can be checked in the performance view.


SELECT NAME, MEMORY_VALUE1 FROM X$PROPERTY WHERE NAME = 'IPC_FILEPATH';


ALTIBASE HDB server versions prior to 5.5.1.4.2 cannot change the default path and do not provide a separate verification method.


The default setting of ALTIBASE HDB server version 4.3.9
The location and name of the Unix domain socket file is $ALTIBASE_HOME/trc/alti-ipc.
The default setting of ALTIBASE HDB server version 4.3.9 or later and earlier than 5.5.1.4.2
The location and name of the Unix domain socket file is $ALTIBASE_HOME/trc/cm-ipc.


How to change properties



1.


2.


3.


4.



Changing altibase.properties file
Change the required values among the properties described above in the $ALTIBASE_HOME/conf/altibase.properties file and
save the altibase.properties file.


$ cd $ALTIBASE_HOME/conf
$ vi altibase.properties


Restarting ALTIBASE HDB
Restart the Altibase server to reflect the changed property values to the Altibase server.


$ server restart


Checking properties
Check that the values have been properly reflected.


$ is
iSQL> SELECT NAME, MEMORY_VALUE1 FROM X$PROPERTY WHERE NAME IN ('IPC_FILEPATH',
'IPC_CHANNEL_COUNT', 'IPC_FILEPATH');


Testing IPC connection
Try to test the iSQL connection with the IPC type.


$ export ISQL_CONNECTION=IPC                        # Change the environment variable
that sets the iSQL connection type.
$ is

----------------------------------------------------------------
Altibase Client Query utility.

Release Version 5.5.1.4.6

Copyright 2000, ALTIBASE Corporation or its subsidiaries.
All Rights Reserved.

----------------------------------------------------------------
ISQL_CONNECTION = IPC, SERVER = localhost, PORT_NO = 20300         # IPC connection is

successful only when ISQL_CONNECTION = IPC appears and the iSQL prompt appears.

iSQL>


OS Configurations


Shared memory and semaphore resources are used for IPC communication. Therefore, to use the IPC type, the related kernel parameters
must be set.


Please refer to the documents below depending on the OS. There is no recommended configurations for AIX and Windows.


Linux: Linux Setup Guide for Altibase
SunOS: HPUX Setup Guide for Altibase
HP-UX: Solaris Setup Guide for Altibase


How the application communicates


Please refer to each manual for how to set the connection properties in the application program.


CLI/ODBC: Refer to 2. ALTIBASE HDB CLI function -> SQLDriverConnect function description in CLI User's Manual.
APRE (C/C++ Precompiler): From Precompiler User's Manual 6. Embedded SQL statement -> SQL statement related to
connection -> CONNECT
JDBC: From the JDBC User's Manual 1. Getting Started with JDBC -> Connection Information

### Automatic altibase startup during OS booting in Solaris


Overview

How to automatically startup Altibase
Steps

STEP 1

STEP2

STEP3

STEP4

STEP5

STEP6

STEP7


Overview


This document describes how to write a script that automatically starts up the Altibase server when booting in Sun Solaris.


How to automatically startup Altibase


Solaris provides an rc script that is related to the run level. These scripts reside in the /sbin directory and are symlinked to the rc scripts
in the /etc directory.


The /sbin/rc# scripts exist under the /etc/rc#.d directory with matching names, which contains scripts to start and stop system
processes for run levels.


File names in this directory start with K and S, K* scripts are used to kill processes, and S* scripts are used to start processes. These
files are run in alphanumeric order.


In the /etc/init.d directory there are actual run control files that start or kill processes, which are hard-linked to the etc/rc#.d directory.


Steps


STEP 1


Create the /etc/alti-conf.d/alti.conf file. In this file, variables necessary for automatic operation are defined and set. The contents of this
file are as follows.





If the user does not want to run the file automatically, set the value of START_ALTIBASE to 0. And when ALTIBASE_OWNER or
ALTIBASE_HOME is changed, the value in this file must be modified.


STEP2


Create the /etc/init.d/alti_start file. In this script, it is a script that actually starts up the DBMS by using the Altibase startup command.





STEP3


Create the /etc/init.d/alti_stop file.
In this script, it is a script that actually stops the DBMS by using the Altibase command.


STEP4


Create the /etc/init.d/altibase file.
This file is actually the file that the startup script or stop script will create a symbolic link later on. The contents of this file are as follows.


STEP5


Create a Hard Link of Startup Script and Shutdown Script in /etc/rc3.d Directory.





STEP6


Set the execution authority so that each script can be executed normally.


STEP7


Test to see if it operates normally. At this time, the test should be performed under the root account.




### Can PUBLIC SYNONYM be dropped?

Impact of dropping PUBLIC SYNONYM
How to drop PUBLIC SYNONYM
How to create PUBLIC SYNONYM


Impact of dropping PUBLIC SYNONYM


Even if PUBLIC SYNONYM is all dropped, it does not affect the operation of the Altibase server.


How to drop PUBLIC SYNONYM


PUBLIC SYNONYM is created when a database is created to provide convenience to DB users, and it is not recommended to drop it
because it uses general queries such as dual table lookup, or it is frequently used in procedures such as print and println.


However, if it needs to be dropped, the DROP statement can be used as follows.


Please drop it after checking whether PUBLIC SYNONYM is used in the application.









How to create PUBLIC SYNONYM


If a dropped PUBLIC SYNONYM is needed, create it as follows.








### Can table data be saved on disk and only indexes can be created in memory?

Phenomenon


Since indexes are basically created in the same type as the table, indexes of disk tables cannot be created in the memory tablespace,
and an ERR-311EC error is displayed.


Create test table T1 in disk tablespace


iSQL> create table t1 (c1 char(10), c2 char(5)) tablespace SYS_TBS_DISK_DATA;


Create success.


Create an index for the test table in the memory tablespace


If the user tries to create a disk table index in the memory tablespace (SYS_TBS_MEM_DATA) as shown below, an ERR-311EC error

occurs.


iSQL> create index idx_t1 on t1(c1 desc) tablespace SYS_TBS_MEM_DATA;

[ERR-311EC : The type (memory/disk/volatile) of the tablespace in which to create the index is not the same as the type of the table.]


Solution


If the index of the disk table is created in the disk tablespace, it is created normally without causing an error.


Create disk table index in disk tablespace


iSQL> create index idx_t1 on t1(c1 desc) tablespace SYS_TBS_DISK_DATA;


Create success.

### Database Security Checklist


Overview

Account Manager

List of accounts (User account management to block unauthorized access)
Using weak password (change default account and password)
Privileges Management

DBA Privilege Management (System Privilege Restriction)
Using WITH GRANT OPTION
Checking Environment Files

il, is, server file permission setting
Altibase.properties file permission setting
Log Anchor, Logfile, Datafile access privilege setting
Checking iSQL command shell history
DBMS Security Settings

Using Public Synonym
Account lockout policy settings such as lockout time according to the number of login failure
Password complexity setting
Periodic change of password
Changing the ALTIBASE HDB default service port
Session IDLE_TIMEOUT settings
Basic auditing (user sentences, privileges, objects, etc.)
Restriction of remote access to DB server

Setting SYSDBA login restrictions
Security Patch

Applying security patch


Overview


This document explains DB security checklist.


Account Manager


List of accounts (User account management to block unauthorized access)


How to check





How to manage


If there is an unnecessary account in the database user output result, check the DBA or application manager and remove it.


-- Delete user

DROP USER user_name ;


-- Delete the user and all objects created by the user

DROP USER user_name CASCADE;


Using weak password (change default account and password)


How to check


The default password for the user is created when ALTIBASE HDB is installed is as follows.

|USER|PASSWORD|
|---|---|
|SYS|MANAGER|
|ALTITEST|ALTITEST|



Connect to the database and check whether to use the default password.


iSQL> CONNECT SYS/MANAGER;

Connect success.


How to manage


If access is possible with the default password, change the password of the user after checking the association with the application.


To know how to change the SYS user password, refer to the "How to change the sys user password' page.


Privileges Management


DBA Privilege Management (System Privilege Restriction)


Check the privileges of the database user and delete any unnecessary system privileges.


ROLE is supported from ALTIBASE HDB 6.5.1.


How to check






How to manage





Using WITH GRANT OPTION


With WITH GRANT OPTION, the user who has been granted object access privileges can grant the appropriate privileges to other users,
so object access privileges can be abused without DBA management.


SELECT DISTINCT(A.USER_NAME) GRANTEE,   -- Users with WITH GRANT OPTION

C.USER_NAME GRANTOR,        -- User granted WITH GRANT OPTION
B.OBJ_TYPE,             -- 객Object type (T: table, S: sequence, P: stored procedure or stored
function, V: view)
B.OBJ_ID,              -- Object ID (for tables, views, and sequences, maps to the TABLE_ID of
SYS_TABLES_; for stored procedures and stored functions, maps to the PROC_OID of SYS_PROCEDURES_)
D.PRIV_NAME,            -- Previlege name
B.WITH_GRANT_OPTION         -- If the value is 1, it means that WITH GRANT OPTION has been

granted.

FROM SYSTEM_.SYS_USERS_ A,

SYSTEM_.SYS_GRANT_OBJECT_ B,

SYSTEM_.SYS_USERS_ C,

SYSTEM_.SYS_PRIVILEGES_ D
WHERE A.USER_NAME <> 'SYSTEM_'

AND B.GRANTEE_ID = A.USER_ID

AND B.GRANTOR_ID = C.USER_ID

AND B.PRIV_ID = D.PRIV_ID

AND B.WITH_GRANT_OPTION = 1;


How to manage


Checking Environment Files


il, is, server file permission setting


These files include password.


How to check





How to manage


Set file permission to 700.





Altibase.properties file permission setting


Maliciously altered altibase.properties file, one of the Altibase critical files, can lead to database failure.


How to check






How to manage


Set the altibase.properties file permission to 600 or 640.





Log Anchor, Logfile, Datafile access privilege setting


Database failure may occur if the log anchor, logfile and datafile files, which are important files for ALTIBASE HDB database operation,
are modified with malicious intent.


How to check





How to manage


logs and dbs directory permissions are set to 700 or 750.


Log Anchor, Logfile and Datafile file permissions are set to 600 or 640.





Checking iSQL command shell history


When connecting to a database using iSQL, if an account and password are entered together, the password may be leaked because the
record is recorded in the shell history file.


How to check






How to manage


When connecting to iSQL, do not enter the user and password at the shell prompt.





Set access privilege to 600 to protect the shell history (.history or .sh_history) file.


$ chmod 600 ~/.*history


DBMS Security Settings


Using Public Synonym


How to check





How to Manage


PUBLIC SYNONYM is created when a database is created to provide convenience to DB users, and it is not recommended to delete it
because it uses general queries such as dual table lookup, or it is frequently used in procedures such as print and println.


However, if it inevitably needs to be dropped, the user can use the DROP statement as shown below.


Please drop it after checking whether PUBLIC SYNONYM is used in the application.


Account lockout policy settings such as lockout time according to the number of login failure


Applicable version


From ALTIBASE HDB 4.3.9.211

From ALTIBASE HDB 5.3.3.89

From ALTIBASE HDB 5.5.1.5.1

From ALTIBASE HDB 6.1.1.2.1

From ALTIBASE HDB 6.3.1


How to check





How to manage


-- After adding FAILED_LOGIN_ATTEMPTS and PASSWORD_LOCK_TIME properties in
$ALTIBASE_HOME/conf/altibase.properties, restart ALTIBASE HDB server.
-- When a database user is created after setting this property, the password locking is set based on this

value.

-- The following is how to check the property settings.


SELECT NAME, VALUE1 FROM V$PROPERTY WHERE NAME IN ('FAILED_LOGIN_ATTEMPTS',
'PASSWORD_LOCK_TIME');






Password complexity setting


Applicable version


From ALTIBASE HDB 4.3.9.211

From ALTIBASE HDB 5.3.3.89

From ALTIBASE HDB 5.5.1.5.1

From ALTIBASE HDB 6.1.1.2.1

ALTIBASE HDB 6.3.1


How to check


SELECT USER_NAME, PASSWORD_VERIFY_FUNCTION FROM SYSTEM_.SYS_USERS_;     -- The

PASSWORD_VERIFY_FUNCTION column means password complexity setting,
-- If it is NULL, it means it is not set.


How to manage


To set the database user password complexity, create a callback function and use the PASSWORD_VERIFY_FUNCTION option in the
LIMIT clause when executing CREATE USER or ALTER USER.


CREATE USER username IDENTIFIED BY password LIMIT (PASSWORD_VERIFY_FUNCTION user callback
function); -- PASSWORD_VERIFY_FUNCTION option password complexity setting in LIMIT clause


-- Example
CREATE USER user1 IDENTIFIED BY "user1" LIMIT (PASSWORD_VERIFY_FUNCTION pwd_verify_function);


ALTER USER username LIMIT (PASSWORD_VERIFY_FUNCTION user callback function);


-- Example
ALTER USER user1 LIMIT (PASSWORD_VERIFY_FUNCTION pwd_verify_function);


To create callback function


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


Periodic change of password


Applicable version


ALTIBASE HDB 4.3.9.211

ALTIBASE HDB 5.3.3.89

ALTIBASE HDB 5.5.1.5.1

ALTIBASE HDB 6.1.1.2.1

ALTIBASE HDB 6.3.1


How to check





Check the PASSWORD_LIFE_TIME property with the command below. If the value is 0, it means that the password


expiration date is not set.


After adding the PASSWORD_LIFE_TIME and PASSWORD_GRACE_TIME property in $ALTIBASE_HOME/conf/altibase.properties, restart
the ALTIBASE HDB server.


When a database user is created after setting this property, the password expiration date and grace period is set based on this value.





CREATE USER user1 IDENTIFIED BY user1 LIMIT (PASSWORD_LIFE_TIME 5, PASSWORD_GRACE_TIME 3);

-- Setting the password expiration date and grace period using the LIMIT clause





Changing the ALTIBASE HDB default service port


The default service port of the ALTIBASE HDB server is 20300.


How to check





How to manage


After changing the value of PORT_NO in $ALTIBASE_HOME/conf/altibase.properties, restart the Altibase server process.


Session IDLE_TIMEOUT settings


IDLE_TIMEOUT can be changed for each session, so it can be changed in session even if it is affected by ALTIBASE HDB server
properties when connected.


How to check









How to manage





To reflect the changed value even when the Altibase server process is restarted, the value of the IDLE_TIMEOUT property must
be changed in $ALTIBASE_HOME/conf/altibase.properties.


Basic auditing (user sentences, privileges, objects, etc.)


Auditing function is provided starting from ALTIBASE HDB version 6.3.1.


How to check


For a description of each field, please refer to Data Dictionary section of the General Reference manual.


How to manage


Refer to Administrator's Manual and SQL Reference AUDIT section.


Manual download page: http://support.altibase.com/en/manual


Restriction of remote access to DB server


This feature is available starting from ALTIBASE HDB 5.


How to check and manage


Check the ACCESS_LIST property in $ALTIBASE_HOME/conf/altibase.properties.


If it is not set, you need to restart after changing the setting in altibase.properties file.


Refer to ACCESS_LIST property in General Reference Manual.


Setting SYSDBA login restrictions


ALTIBASE HDB has no login restrictions for SYSDBA and can only control remote access.
This feature is available starting from ALTIBASE HDB version 5.


How to check


SELECT NAME, VALUE1 FROM V$PROPERTY WHERE NAME ='REMOTE_SYSDBA_ENABLE'; --value1 = 1:

remote access of sysdba is possible, value1 = 0: remote access of sysdba is not possible


How to manage





To reflect the changed value even when the Altibase server process is restarted, the value of the REMOTE_SYSDBA_ENABLE
property must be changed in $ALTIBASE_HOME/conf/altibase.properties.


Security Patch


Applying security patch


Security patch of Altibase can be found on the Customer Support Service Portal.


When major bugs including security bugs are fixed, new patch is uploaded on the Customer Support Service Portal.

### Detailed procedure for changing character set


Overview


Version


Change procedure


Summary of change procedure


Details of change procedure


STEP 1: Download the entire schema of the database using the database export tool.


STEP 2: Download the database data in the current DB character set. Example) KSC5601


STEP 3: Delete the database and create a new database with the character set setting the user wants to


change. Example) UTF8


STEP 4: Use the schema information downloaded from STEP1 to configure the schema in the newly created DB.


STEP 5: Use the data import tool to upload the data downloaded in STEP2 using the changed character set.


Example) UTF8


Overview


The character set of the database is determined by the set value at the time of database creation and cannot be changed again. So, to
make any changes, the database must be deleted, and create a new one.


When the database is deleted, all objects and data disappear. Therefore, the necessary data must be backed up and re-imported after
recreating the database.


This document assumes and describes a situation where the database character set is changed while preserving the necessary data.


Version


This document is written based on ALTIBASE HDB version 5.3.1 or later, which supports multi-language support.


Change procedure


Summary of change procedure


In summary, the change procedure proceeds in the following steps.


Details of change procedure


The detailed change procedure proceeds in the following steps. This is an explanation of the procedure for changing the character set of
the DB whose current DB character set is US7ASCII to MS949.


STEP 1: Download the entire schema of the database using the database export tool.






STEP 2: Download the database data in the current DB character set. Example) KSC5601


STEP 3: Delete the database and create a new database with the character set setting the user wants to change.


Example) UTF8


STEP 4: Use the schema information downloaded from STEP1 to configure the schema in the newly created DB.





STEP 5: Use the data import tool to upload the data downloaded in STEP2 using the changed character set. Example)


UTF8


### How to change sys user password

Overview

Version

Procedure


1. Execute the alter user command

2. Execute altipasswrd
3. Modify the script containing the sys password
Solution

What to do if an "Invalid password" error occurs when starting the server


Overview


This document explains the procedure for changing the password of the sys account.


Version


ALTIBASE HDB version 4 or later


Procedure


To change the password for the sys account, follow the three steps below.


1. Execute the alter user command


Connect to the Altibase server as the sys user and change the password with the alter user command.


ALTER USER sys IDENTIFIED BY "new_password";


2. Execute altipasswrd


Execute while the Altibase server is online.






3. Modify the script containing the sys password


The three scripts below contain the sys password.


So, when changing the sys password, these scripts also need to be modified.


server script
Change the password after the -p option in the $ALTIBASE_HOME/bin/server script to the new password.


$ cd $ALTIBASE_HOME/bin
$ vi server
ADMIN="${ALTIBASE_HOME}/bin/isql -u sys -p manager -sysdba -noprompt"
ISQL="${ALTIBASE_HOME}/bin/isql -s localhost -u sys -p manager -silent"


is script


Change the password after the -p option in the $ALTIBASE_HOME/bin/is script to the new password.


$ cd $ALTIBASE_HOME/bin
$ vi is
${ALTIBASE_HOME}/bin/isql -s localhost -u sys -p manager $*


il script
Change the password after the -p option in the $ALTIBASE_HOME/bin/il script to the new password.


$ cd $ALTIBASE_HOME/bin
$ vi il
${ALTIBASE_HOME}/bin/iloader -S localhost -U SYS -P MANAGER $*


Solution


What to do if an "Invalid password" error occurs when starting the server


a. Open the $ALTIBASE_HOME/bin/server script and check if the password has been modified in the lower part.





b. If an invalid password error occurs even though the above is applied with the changed password, it is possible that the sys password
was changed only with the alter user command and altipasswd was not executed.


In this case, execute altipasswd, apply the changed password, and then try to start the server.

### How to change the database's db name


How to change the database's db name
Version
Notes/Considerations
Change procedure

(1) DB stop
(2) Change the DB name of altibase.properties
(3) Modify server script
(4) Delete existing database
(5) Create a new DB with a new DB name
(6) Start the DB
(7) Check the changed database name


How to change the database's db name


This section describes how to change the db name of the Altibase database.


Version


This method is applied to ALTIBASE HDB version 5.3.3 or later.


Notes/Considerations


To change the DB NAME, the DB must be recreated. When the DB is recreated, the existing data disappears, so when the
existing data is restored, the DB data must be exported and backed up.


Change procedure


(1) DB stop


Stop DB with DB stop command.





(2) Change the DB name of altibase.properties


Change the DB_NAME in the $ALTIBASE_HOME/conf/altibase.properties file to the DB name you want to change.





(3) Modify server script


Change the default DB name of the db create-part in $ALTIBASE_HOME/bin/server script to the DB name you want to change.


EOF


(4) Delete existing database


To create a new database, the existing DB must be deleted. To delete the existing DB, delete the $ALTIBASE_HOME/dbs/* and
$ALTIBASE_HOME/logs/* files.





(5) Create a new DB with a new DB name


Create a new DB with the server create command.





(6) Start the DB


Start the DB with the server start command.


(7) Check the changed database name


After starting the DB, the changed DB name can be checked with the following query.






### How to change the path of log anchor, online log file, archive log file, and double write file

Overview

Summary of change procedure
Detailed procedure

1. Check the current path setting
2. Stop the Altibase server
3. Copy the files and change properties

Log anchor
Online log file


Archive log file
Double Write file

File type properties and file name format table
3. Start the Altibase server

4. Check the change path
Reference


Overview


This section describes how to change the path of log anchor, online log file, archive log file, and double write file.


In order to change the paths of these files, the Altibase server must be restarted, so be sure to perform it after securing service
downtime.


Summary of change procedure



1.

2.

3.

4.

5.



Check the current path setting.
Stop the Altibase server.
Copy files and change properties.
Start the Altibase server.

Check the change path.



Detailed procedure


1. Check the current path setting


Refer to the sentence below to check the current path of each property and make a note of it.


iSQL> SELECT NAME, VALUE1 FROM V$PROPERTY WHERE NAME IN ('LOGANCHOR_DIR', 'LOG_DIR',
'DOUBLE_WRITE_DIRECTORY', 'ARCHIVE_DIR');


Example)
iSQL(sysdba)> set linesize 1024
iSQL(sysdba)> set colsize 60
iSQL(sysdba)> SELECT NAME, VALUE1 FROM V$PROPERTY WHERE NAME IN ('LOGANCHOR_DIR',
'LOG_DIR', 'DOUBLE_WRITE_DIRECTORY', 'ARCHIVE_DIR');

NAME                             VALUE1

----------------------------------------------------------------------------------
-------------------------------------------
LOG_DIR                            /data/eheejung/65166/logs     # Online log file path
LOGANCHOR_DIR                         /data/eheejung/65166/logs     # Log anchor file path
ARCHIVE_DIR                          /data/eheejung/65166/arch_logs  # Archive log file path
DOUBLE_WRITE_DIRECTORY                    /data/eheejung/65166/dbs     # Double Write file
path

4 rows selected.


2. Stop the Altibase server


Stop the Altibase server.


$ server stop


3. Copy the files and change properties


Copy the file which path you want to change to the new path and change the properties of each.


Log anchor


There are three log anchor files: loganchor0, loganchor1, and loganchor2.
Copy all three files from the path located in the LOGANCHOR_DIR property to the new path.
Find the LOGANCHOR_DIR property in the $ALTIBASE_HOME/conf/altibase.properties file and change it to a new path.


Online log file


The online log file name format is logfile#.
Copy all files starting with logfile from the path located in the LOG_DIR property to the new path.


Find the LOGANCHOR_DIR property in the $ALTIBASE_HOME/conf/altibase.properties file and change it to a new path.


Archive log file


The Archive log file name format is logfile#.
Copy all files starting with logfile from the path located in the ARCHIVE_DIR property to the new path.
Find the LOGANCHOR_DIR property in the $ALTIBASE_HOME/conf/altibase.properties file and change it to a new path.


Double Write file


The Double Lite file name format is *.dwf.

Copy all files ending in *.dwf from the path located in the DOUBLE_WRITE_DIRECTORY property to the new path.
Find the DOUBLE_WRITE_DIRECTORY property in the $ALTIBASE_HOME/conf/altibase.properties file and change it to a new
path.


File type properties and file name format table

|파일 종류|Property|File name format|
|---|---|---|
|Log anchor|LOGANCHOR_DIR|loganchor0<br>loganchor1<br>loganchor2|
|Online log file|LOG_DIR|logfile#|
|Archive log file|ARCHIVE_DIR|logfile#|
|Double Write file|DOUBLE_WRITE_DIRECTORY|*.dwf|



3. Start the Altibase server


Start the Altibase server.


$ server start


4. Check the change path


1. Check the change path with the SQL statement executed in Check the current path settings.


SELECT NAME, VALUE1 FROM V$PROPERTY WHERE NAME IN ('LOGANCHOR_DIR', 'LOG_DIR',
'DOUBLE_WRITE_DIRECTORY', 'ARCHIVE_DIR');


Reference


How to change the tablespace data file path

### How to change the tablespace data file path


Overview

Summary of change procedure
Detailed procedure

1. Check the current path of the data file
2. Stop the Altibase server
3. Change the data file default path
4. Copy the physical data file path
5. Start the Altibase server as a control stage
6. Execute the data file path change DDL
7. Start the Altibase server as a service stage
Error messages that may occur during the operation

The data file does not exist
The data file 'XXXXXX' has an invalid header
Unable to invoke the create() function on [XXXXXX/dwfile0.dwf]
CANNOT IDENTIFY DATAFILE

Reference


Overview


This document describes the procedure for changing the path of data files in disk tablespaces and memory checkpoint image files in
memory tablespaces.


Change the data file path after securing service downtime.


Summary of change procedure



1.

2.

3.

4.

5.

6.

7



Check the current path of the data file
Stop the Altibase server.
Change the data file path.
Copy the data file to the new path.
Start Altibase server as a control stage.
Execute the data file path change DDL.
Start the Altibase server as a service stage


7. Start the Altibase server as a service stage.


Detailed procedure


1. Check the current path of the data file


The verification method differs depending on the disk tablespace and the memory tablespace, so they need to be checked separately.
Use the query below to check and write down the output result.


Data file path of disk tablespace





Path to checkpoint image file in memory tablespace









2. Stop the Altibase server


The Altibase server must be stopped as the user needs to physically move the data files.


# Altibase server stop command
$ server stop


# How to check the Altibase server process
$ ps -ef | grep 'altibase -p' | grep -v grep


3. Change the data file default path


The data file default path refers to the path where the data file will be located if the user specifies only the data file name without
specifying a path when creating a tablespace or adding a data file.
Do this if the user also needs to change the default path when working with data file path change.
Set in the altibase.properties file, find the MEM_DB_DIR, DEFAULT_DISK_DB_DIR properties, and change the default path.


# Property names differ depending on the disk and memory tablespaces.
# Find the properties MEM_DB_DIR, DEFAULT_DISK_DB_DIR in the altibase.properties file and change
the default path.
$ egrep 'MEM_DB_DIR|DEFAULT_DISK_DB_DIR' $ALTIBASE_HOME/conf/altibase.properties
MEM_DB_DIR     = ?/dbs # Memory DB Directory
DEFAULT_DISK_DB_DIR = ?/dbs # Disk  DB Directory


4. Copy the physical data file path


Copy all data files and memory checkpoint image files located in the path identified in "1. Check the current path of the data file"
to the path the user wants to change.





파일 수 및 파일 크기를 비교하여 정상적으로 복사되었는지 확인합니다.


# Compare the number of files
$ ls -l /old_path/* | wc -l
$ ls -l /new_path/* | wc -l


# Compare the size of files
$ du -sk /old_path/*
$ du -sk /new_path/*


Change the original path to another name.


When starting the Altibase server, avoid the possibility of reading the original file and change the original path to a different name
for the backup of the original file.


$ mv /old_path /old_path_backup


5. Start the Altibase server as a control stage


After connecting to the iSQL with sysdba privileges


$is -silent -sysdba

[ERR-910FB : Connected to idle instance]
iSQL(sysdba)> STARTUP CONTROL


Start as a control stage


iSQL(sysdba)> STARTUP CONTROL
Connecting to the DB server.... Connected.

TRANSITION TO PHASE : PROCESS

TRANSITION TO PHASE : CONTROL

Command executed successfully.
iSQL(sysdba)>


6. Execute the data file path change DDL


The disk data file and memory checkpoint image file path information are stored in the log anchor file. Execute the DDL statement to
change the information known to the log anchor.


How to change the disk data file path


The ALTER DATABASE statement is repeated as many times as the number of all data files checked in "1. Check the current path
of data files". The user must enter the same file name by changing only the path.


iSQL(sysdba)> ALTER DATABASE RENAME DATAFILE
'/old_path/system001.dbf' TO '/new_path/system001.dbf';

Alter success.


Check the disk data file change path


Make sure the path has been changed correctly.


# Output the disk tablespace name and data file path and name.

set linesize 1024

set colsize 100

SELECT T.NAME TBS_NAME, D.NAME DATAFILE
FROM V$DATAFILES D, V$TABLESPACES T

WHERE D.SPACEID = T.ID

ORDER BY D.SPACEID, D.ID ;


Change the memory checkpoint image file path


1. Repeat the ALTER TABLESPACE statement as many as the number of memory tablespaces checked in "Check the current
path of the data file". In this case, only the old and new paths are used without specifying a file name.


How to check the memory checkpoint image file change path





7. Start the Altibase server as a service stage


Execute while connected to the iSQL with sysdba privilege.


iSQL(sysdba)> startup
The database server is already up and running.

TRANSITION TO PHASE : META

...Omitted...

--- STARTUP Process SUCCESS --
Command executed successfully.
iSQL(sysdba)>


Error messages that may occur during the operation


These are error messages that may occur while changing the data file path, and this section describes how to prevent these errors.


The data file does not exist


Cause

This can happen if the change statement was performed without physically moving the data file.


Solution

After moving the data file to the location where you want to change the data file, execute the rename statement that changes the
location of the data file in the DB.


The data file 'XXXXXX' has an invalid header


Cause

This can happen if the data file copy phase is not physically performed normally. When starting the database in the service
stage, the startup fails.


Solution

Redo the operation of the physical data file


Unable to invoke the create() function on [XXXXXX/dwfile0.dwf]


Cause


This can happen if the double write file does not exist. The double write file is a file required for restart recovery when the
database is abnormally terminated. The default path is $ALTIBASE_HOME/dbs.If all files in the $ALTIBASE_HOME/dbs path are
moved, an error may occur. The error message may differ depending on the Altibase server version.


Solution

dwfile0.dwf and dwfile1.dwf files can be created after creating them with the touch command.


Or change $ALTIBASE_HOME/conf/altibase.properties to USE_DW_BUFFER = 0 (add it if it doesn't exist) and start the Altibase
server. When the Altibase server is started, change it to USE_DW_BUFFER = 1 or delete the USE_DW_BUFFER setting from
altibase.properties.
After changing the default path of the double write file, the Altibase server can be started.


# Change the value of the DOUBLE_WRITE_DIRECTORY property.
$ vi $ALTIBASE_HOME/conf/altibase.properties
DOUBLE_WRITE_DIRECTORY    = ?/dbs
DOUBLE_WRITE_DIRECTORY    = ?/dbs


CANNOT IDENTIFY DATAFILE


Cause


When starting the Altibase server as a service phase, it happens that the physical data file cannot be found in the path of the
data file stored in the meta table. This can happen if an incorrect data file path was entered in the control stage.


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


Solution


The control stage executes the DDL statement by specifying the correct path.


Reference


How to change the path of log anchor, online log file, archive log file, and double write file

### How to check the history of adding datafiles


How to check

Version

How to change properties

How to use the ALTER SYSTEM command

How to reflect in the altibase.properties file
How to check logs


How to check


Data file addition or change time information is not recorded in a separate performance view or v$datafiles. However, if the
QP_MSGLOG_FLAG property is set to record DDL statements, DDL statements are recorded in $ALTIBASE_HOME/trc/altibase_qp.log, so
this file can be opened, and the changes can be checked in the datafile.


Version


This is supported by Altibase HDB version 4.3.9 or later.


How to change properties


Change the setting value of QP_MSGLOG_FLAG so that DDL can be logged in altibase_qp.log. One of the following two methods can be
used to change the method.


How to use the ALTER SYSTEM command


If the user changes it by using this method, the value of the property can be changed without restarting the server. When the server is
restarted, the default value is restored. To keep the changed value even after the server is restarted, the property change value must be
applied in the $ALTIBASE_HOME/conf/altibase.properties file.





How to reflect in the altibase.properties file


1) Add the following line in the $ALTIBASE_HOME/conf/altibase.properties file.


QP_MSGLOG_FLAG = 2 # 2: DDL logging


2) Restart the ALTIBASE process.


shell> server restart


3) Check if the changed value has been applied.


iSQL> select name, value1 from v$property where name='QP_MSGLOG_FLAG';


Starting from Altibase HDB version 5.1.5.33 or later, the default value of QP_MSGLOG_FLAG is 2, so all DDLs are written to
altibase_qp.log by default.


How to check logs


When a data file is added with the alter tablespace ~ add datafiles statement, the following log is displayed in altibase_qp.log.


[2013/11/27 14:10:57] [Thread-1094719840] [Level-2]

[EXEC_DDL_BEGIN : alter tablespace TEST_TBS add DATAFILE '/altibase_home_533/dbs/test02.dbf']


[2013/11/27 14:10:58] [Thread-1094719840] [Level-2]

[EXEC_DDL_END : SUCCESS]


If the user uses the following syntax, the following will be the result.


shell> $awk '/DATAFILE/ {print last " : " $0}{last=$0}' altibase_qp.log | grep -i 'add'

[2013/11/27 14:10:57] [Thread-1094719840] [Level-2] : [EXEC_DDL_BEGIN : alter tablespace TEST_TBS add DATAFILE
'/altibase_home_533/dbs/test02.dbf']


However, since it is a method of grep-ing the trace log file, the history that is old enough to be deleted from the log file cannot be
found.

### How to create and execute Job objects


Overview

Version

How to use

Enabling the task scheduler function (Altibase Server Property Settings)
Creating the procedure
Creating the Job object
Enabling the job object
Check the Job object and execution result
Related Properties

JOB_SCHEDULER_ENABLE
JOB_THREAD_COUNT
JOB_THREAD_QUEUE_SIZE

Reference


Overview


This document describes how to create and execute Job objects, and how to monitor them.


Version


Altibase version 6.3.1 or later


How to use


To create a Job object and operate normally, the user must proceed in the following order.



1.

2.

3.

4.

5.



Enable the task scheduler function

Create the procedure to register in the Job object
Create the Job object
Enable the Job object (only performed on Altibase 6.5.1 or later. Altibase 6.3.1 is not applicable)
Check the Job object and execution result



Enabling the task scheduler function (Altibase Server Property Settings)


If the user is using the Job object for the first time, the job scheduler function must be enabled by changing the following Altibase server
properties.


The job scheduler performs a procedure according to the settings registered in the job object.


JOB_SCHEDULER_ENABLE : Task Scheduler Enable settings
JOB_THREAD_COUNT     : Number of threads to execute Job object


Both of the above properties must be set to 1 to use the task scheduler. The default value is 0, so be sure to check if the user is using
Task Scheduler for the first time.


The JOB_SCHEDULER_ENABLE property can be changed even when the Altibase server is running, but to change the value of the
JOB_THREAD_COUNT property, the Altibase server must be restarted.


Therefore, when using the task scheduler for the first time, change the properties according to the procedure below.


1. Stop the Altibase server


$ server stop


2. Find the JOB_SCHEDULER_ENABLE and JOB_THREAD_COUNT properties in the altibase.properties file, change the value to 1, and

save.





3. Start the Altibase server


$ server start


4. Check the property setting value


SELECT NAME, MEMORY_VALUE1 FROM X$PROPERTY WHERE NAME IN ('JOB_SCHEDULER_ENABLE',
'JOB_THREAD_COUNT');


Creating the procedure


Create a procedure to be registered in the Job object and check if the procedure is executed normally.


The reason for checking whether the procedure is normally executed is to exclude the possibility of a procedure problem if the Job
object does not operate as set by the job scheduler.


Creating the Job object


Create a JOB object.


The stored procedure to be executed, execution time, and execution cycle can be set in the JOB object. For the statement of creating a
JOB object, refer to the SQL Reference manual. (Manual download page: http://support.altibase.com/en/manual or https://github.com/A
LTIBASE/Documents/tree/master/Manuals/)


CREATE JOB job1
EXEC proc1
START sysdate
END sysdate + 3

INTERVAL 1 HOUR;


Enabling the job object


This operation is an added procedure with the addition of a function to enable/disable a specific JOB in Altibase version 6.5.1.


In Altibase version 6.3.1, when creating a JOB object, it becomes 'enabled' immediately, but from Altibase 6.5.1, if the ENABLE option is
not used in the CREATE JOB statement, it is 'disabled'.


Therefore, starting from Altibase version 6.5.1, after creating a Job object, in order to make the Job run, it must be changed to the
enabled state.


The change method is as follows.





Starting from Altibase version 6.5.1, it is also possible to set it to "Enabled" immediately when creating a Job object.


CREATE JOB job1
EXEC proc1
START sysdate
END sysdate + 3

INTERVAL 1 HOUR

ENABLE;


Check the Job object and execution result


The user can check the job object information and job execution result with the query below.


-- JOB_NAME : Name of Job object
-- PROC_NAME : Name of the procedure registered in the Job object
-- INTERVAL, INTERVAL_TYPE : Performance cycle
-- STATE : Check whether Job object is executed. If ING, the user can see that the procedure registered in
the Job object is being executed.
-- EXEC_COUNT : Number of times the job object was executed after creation
-- ERROR_CODE : Error code when the procedure registered in the Job object fails
-- START_TIME, END_TIME : Time when the Job object was first executed / Time when it was finished
-- LAST_EXEC_TIME : Last time the Job object was performed

SELECT JOB_NAME
, DECODE(IS_ENABLE, 'T', 'ENABLE', 'F', 'DISABLE') IS_ENABLE         -- Delete then use it in

Altibase 6.3.1

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






How to check the error message corresponding to the error code
The error message corresponding to the error code can be checked by using the altierr utility.


$altierr 0x31129


0x31129 (201001) qpERR_ABORT_QSV_NOT_EXIST_PROC_SQLTEXT Procedure or function not found : <0%s>.
# *Cause: The specified procedure or function name was not found in the database.
# *Action: Verify that the procedure or function exists.


Related Properties


JOB_SCHEDULER_ENABLE


Property description


This property is to enable or disable the task scheduler function.
The default value is 0, which disables the task scheduler.


How to change the set value


It can be changed by using ALTER SYSTEM.


ALTER SYSTEM SET JOB_SCHEDULER_ENABLE = 1;      -- Enable the job scheduler function


Or,

ALTER SYSTEM SET JOB_SCHEDULER_ENABLE = 0;      -- Disable the job scheduler fucntion


How to check the set value


The JOB_SCHEDULER_ENABLE set value can be checked with the query below.


SELECT NAME, MEMORY_VALUE1 FROM X$PROPERTY WHERE NAME = 'JOB_SCHEDULER_ENABLE';


JOB_THREAD_COUNT


Property description


This property configures the number of threads to process a job.
The default value is 0. When the Altibase server is started, the thread for executing the task scheduler is not started.
If JOB_THREAD_COUNT is set to a value other than 0, JobScheduler threads and JobThread threads as many as
JOB_THREAD_COUNT are started.
Job is not executed by the service thread, but are processed by a thread called JobThread. So, if the user wants the job to be
executed by the job scheduler, this property must be set.
Change this property value requires restarting the Altibase server.


How to change the set value


Stop the Altibase server.
Find JOB_THREAD_COUNT in $ALTIBASE_HOME/conf/altibase.properties, change the value, and save.
Start the Altibase server.


How to check the set value


The JOB_THREAD_COUNT set value can be checked with the query below.


SELECT NAME, MEMORY_VALUE1 FROM X$PROPERTY WHERE NAME = 'JOB_THREAD_COUNT';


JOB_THREAD_QUEUE_SIZE


Property description


This property sets the number of queues to process multiple job objects are executed at the same time.
For example, when 4 job objects are executed at the same time by the job scheduler, they are processed in the following order
according to the number of JOB_THREAD_COUNT and JOB_THREAD_QUEUE_SIZE.


    - JOB_THREAD_COUNT = 4, JOB_THREAD_QUEUE_SIZE = 1: 4 can be executed at the same time

    - JOB_THREAD_COUNT = 2, JOB_THREAD_QUEUE_SIZE = 2: Two are executed at the same time, and the other two are
executed consecutively.

    - JOB_THREAD_COUNT = 1,JOB_THREAD_QUEUE_SIZE = 4: 1 is executed at the same time and the remaining 3 are executed
consecutively.


The default and minimum values are set large enough to 64, so there is no need for users to set them arbitrarily.
To change the value of this property with the Read-Only attribute, the Altibase server must be stopped.


How to change the set value


Stop the Altibase server.
Save after changing JOB_THREAD_QUEUE_SIZE in $ALTIBASE_HOME/conf/altibase.properties.
Start the Altibase server.


How to check the set value


The JOB_THREAD_QUEUE_SIZE set value can be checked with the query below.


SELECT NAME, MEMORY_VALUE1 FROM X$PROPERTY WHERE NAME = 'JOB_THREAD_QUEUE_SIZE';


Reference


The following are manuals for the description of the task scheduler.


Administrator's Manual> 5. Database Objects and Permissions> Job
SQL Reference> 3. Data Definition Language> ALTER JOB /
SQL Reference> 3. Data Definition Language> CREATE JOB
SQL Reference> 3. Data Definition Language> DROP JOB
General Reference> 2. ALTIBASE HDB Properties> Other Properties
General Reference> 3. Data Dictionary> SYS_JOBS_


Manual Download Page: http://support.altibase.com/en/manual or https://github.com/ALTIBASE/Documents/tree/master/Manua
ls/

### How to create a user (CREATE USER) and change a password (ALTER USER)


Overview

Applicable versions
How to create a user and change a password
How to change SYS user
Reference Manual


Overview


In addition to the system user SYS user, general users can be created using the create user statement, and after creating the user, the
user's password can be changed using the alter user statement.


Applicable versions


This document is written based on ALTIBASE HDB 6.3.1.
If you need additional inquiries or updates, please leave a request post at http://support.altibase.com/en/ or make a comment
on this page.


How to create a user and change a password


-- Create

CREATE USER user_name IDENTIFIED BY password;
-- Change
ALTER USER user_name IDENTIFIED BY change_password;

-- Delete

DROP USER user_name;

DROP USER user_name CASCADE;


How to change SYS user


The SYS user plays a special role as the database administrator.


Therefore, additional work is required when changing the password, please check through the following link:


How to change sys user password


Reference Manual


ALTIBASE SQL User's Manual

### How to forcefully close a session that is being locked


Overview

Version

Solution

Reference


Overview


This is a method of forcibly ending a session that is being locked


This is a method of forcibly ending a session that is being locked.


Version


ALTIBASE HDB version 4 or later


Solution


It must be performed by accessing the sys account.


1. Check the table name, transaction ID, and lock type in v$lock.


Select a.table_name, b.trans_id, b.lock_desc From system_.sys_tables_ a, v$lock b

Where a.table_oid = b.table_oid;


2. Use the trans_id obtained above to find the session.


Select session_id, execute_flag, total_time, execute_time, rpad(query,400) From v$statement

Where tx_id = trans_id obtained from above;


3. Use the session_id to check the session information.


Select comm_name, client_app_info From v$session

Where id = session_id obtained from above;


4. Disconnect the session.


iSQL> Alter database mydb session close session_id;
For mydb, open the $ALTIBASE_HOME/conf/altibase.properties file as the database name and check it by
setting the DB_NAME item.

Enter the Session_id as well as the session_id obtained above.


Reference


-A session in which rollback is in progress is not disconnected even if session close is performed, so must wait until the rollback is
finished.


-For information on the above v$ view OR SYSTEM_META_TABLE column, refer to the Admin manual.

### How to modify column


Version

Statement


TOLERATE DATA LOSS Option
Conversion of DATE type
Precaution


Precaution

Example
Reference


Version


Starting from Altibase HDB version 5.3.3 or later, the column type and length of a table can be modified by using the ALTER TALBE ~
MODIFY COLUMN ~ statements.


Statement


ALTER TABLE table_name MODIFY COLUMN ( column_name column_type(length) )


TOLERATE DATA LOSS Option


If the table data is not NULL, data loss may occur depending on the conversion type. In order to change the data type at the expense of
this data loss, TOLERATE DATA LOSS option can be used.


Conversion of DATE type


When the DATE type is changed, the column data is converted according to the DEFAULT_DATE_FORMATE property.


Precaution


If used incorrectly, the column modify command may cause a load on the DB depending on data loss and the amount of data in the
target table, so it should be used with precaution.



1. Cannot reduce the column size below the original size
2. If the data type of a column is changed, data loss may occur depending on the data type. If the user wants to change the data

type at the expense of this data loss, the TOLERATE DATA LOSS option can be used.

3. When operating with the target table for replication, it must follow the DDL operation procedure in a replication environment.

Please refer to the DDL procedure for the Altibase replication target table.

4. If there are many rows in the target table, there may be a delay in operating time and an increase in usage of the logs area.


When modifying columns, if the table to be changed is a memory table and the current ALTIBASE version is 5.3.3, it is created
in the memory table as a copy table for restoration.


In order words, there must be room for memory tablespaces. (For reference, in version 6.1.1, the copy table is saved as a disk
tablespace, so if there are only a tablespace and a disk space, it is operatable.)


As recommended by ALTIBASE, if the target table is a memory table, backup is performed with an iloader operation, then a new
target table is created and data is imported.


Example


<Query> Change the isbn column of the table book to CHAR(20) type and the edition column to BIGINT type.


iSQL> ALTER TABLE book MODIFY COLUMN (isbn CHAR(20), edition BIGINT);


Alter success.


<Example> Below is an example of executing the above query.


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


Reference


For more detailed information on how to use it, refer to how to use modify columns in the SQL Reference Manual.

### How to resolve when LOCK TIMEOUT occurs


Overview

Version


Causes

Solution

Reference


Overview


During SQL execution, the following errors sometimes prevent the desired operation:


The transaction exceeds lock timeout specified by user


$ altierr -w "lock timeout"
0x11075 ( 69749) smERR_ABORT_smcExceedLockTimeWait The transaction exceeds lock timeout specified by user.
# *Cause: The transaction failed to lock the object.
# *Action: Please abort the transaction.


Version


ALTIBASE HDB version 4 or later


Causes


During SQL execution, there are times when the following error occurs and the desired operation cannot be performed.


As shown in the above error code, it is an error that the object-table, view, stored procedure, etc. cannot be locked.


All sessions accessing the table hold the LOCK on the table and access it. In other words, if someone is executing DML such as
SELECT/INSERT/UPDATE on the table or DDL such as ALTER TABLE, if DROP TABLE is executed, the previous operation will wait to
commit/rollback.


In this case, make sure there are no users and wait for the previous operation to commit, or the session can be forced to be
disconnected. The session can be forcibly terminated by using the alter database statement as shown in the example below.


Solution


- Check the lock information


select T.table_name, X.lock_desc from system_.sys_tables_ T, v$lock X where T.table_oid = X.table_oid and
T.table_name = 'T1'; //Check the T1 table LOCK information


- To forcefully close the session


1. Find the SESSION ID


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
-- and T.table_name like 'TEST1%' -- Please specify the table.
)

group by ses_id ;

'alter database mydb session close '||SES_

---------------------------------------------
alter database mydb session close 159;
alter database mydb session close 160;
alter database mydb session close 161;
alter database mydb session close 162;

4 rows selected.


2. Close the session


$ isql -sysdba -u sys -p manager
iSQL(sysdba)>
alter database mydb session close 159;
alter database mydb session close 160;
alter database mydb session close 161;
alter database mydb session close 162; -- Copy/paste the above SQL result and execute it.


Reference


Terminating a session with the alter database command does not affect other parts of the session.


However, if the service system incorrectly identifies the session id and terminates the session, it may be a problem.


As a reference for operation, if the system is in service, even if the connected session is disconnected, if another application connects
to access the table, a lock may be added, so it is necessary to consider this part as well.


If possible, it is advisable to disable the application while operating.

### How to start and stop the database


How to stop Altibase


How to stop Altibase

(1) Using the server stop script
(2) Using the shutdown command after connecting to isql
How to start Altibase

(1) Using the server start script
(2) Using the startup command after connecting to isql
How to check whether the database is started normally after starting the database

(1) Displayed message after server start
(2) Connection test with isql
(3) Simply checking query
How to forcibly shutdown Altibase
Error message at ALTIBASE server start/stop

(1)  The database server is already up and running.
(2) Another SYSDBA session is already running


How to stop Altibase


There are two methods to stop the Altibase database as follows.


(1) Using the server stop script


The DB server can be stopped with a simple command and this is the most used method. The DB server can be stopped from starting
with the command "server stop" in the unix user account where Altibase is installed.


Command: shell> server stop





(2) Using the shutdown command after connecting to isql


After connecting to isql, the DB can be stopped by selectively using the shutdown method with the shutdown command.


How to start Altibase


There are two methods to start the Altibase database.


(1) Using the server start script


The DB server can be started with a simple command and this is the most used method. The DB server can be started with the
command "server start" as follows from the unix user account where Altibase is installed.


Command: shell> server start


(2) Using the startup command after connecting to isql


The DB can be started step by step after connecting to the DB in sysdba mode with isql from the unix user account where Altibase is
installed.


How to check whether the database is started normally after starting the database


After starting Altibase, it can be checked whether the ALTIBASE DB server has been successfully started using the following method.


(1) Displayed message after server start


When starting the DB with the server start command or isql, it checks whether "— STARTUP Process Success —" is output as follows.


(2) Connection test with isql


The DB status can be checked by executing a simple SQL statement on is or isql, an interactive query execution tool, and checking
whether the query is operating normally.





(3) Simply checking query


The DB status can be checked by executing the query below.


Check the number of sessions: Check the number of sessions currently connected to the DB.


iSQL> select count(*) from v$session;

COUNT

----------------------
1

1 row selected.


Check the replication gap: If the user is using the replication, the replication gap can be checked.


If the replication gap value increases or decreases repeatedly, it is normal.


iSQL> select rep_name, rep_gap from v$repgap;

REP_NAME                 REP_GAP

-----------------------------------------------------------------
REP1                   567

1 rows selected.

iSQL>


Transaction processing status
Inquire about the accumulated transaction throughput currently being processed by DML or DB. If it continues to increase, it is
normal.


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


How to forcibly shutdown Altibase


If the Altibase database server is in a hang state due to system malfunction or lack of system resources, and the DB cannot be stopped
using a normal method such as server stop, the following command can be used.





server kill kills the DB process in the same way as killing ALTIBASE with kill -9. It is not recommended under normal
circumstances.


If ALTIBASE is forcibly shutdown with the server kill, the recovery process will be performed at the next start. If there is a large
amount of undo and redo transactions during the recovery process, it may take a long time to start the server.


Therefore, it is recommended to set the database with the normal server stop command if possible.


Error message at ALTIBASE server start/stop


(1)  The database server is already up and running.


If the user tries to start an additional server while the Altibase server is already started, the following message is displayed. The server
cannot be started because the database has already been started.


(2) Another SYSDBA session is already running


Sessions with sysdba privileges only allow one connection to the DB. This is an error message that appears when an additional sysdba
connection for server start or server stop fails when there is a session already connected to sysdba.
Try to reconnect after ending a connected sysdba session.

### How to startup Altibase automatically when booting from HP-UX


Overview

What is HP-UX Startup Script?
How to write a script for automatic startup/stop of Altibase

STEP 1

STEP 2

STEP 3

STEP 4

STEP 5

STEP 6

STEP 7


Overview


This section describes how to automatically startup Altibase when booting from HP-UX.


What is HP-UX Startup Script?


In HP-UX, script files that are executed during system boot/shutdown are managed as follows.



1.

2.


3.



The actual script files that are executed at boot time exist in the /sbin/init.d directory.
The configuration files for the above script files are in the /etc/rc.config.d directory. Each rc script has one configuration file and
sets the definitions and values of variables necessary for script execution.
Script files that are executed at boot time exist in the /sbin/rc*.d directory, and these files are symbolic links to the files in the
/sbin/init.d directory.



How to write a script for automatic startup/stop of Altibase


STEP 1


Create the /etc/rc.config.d/altibase_conf file.
As described above, in this file, variables necessary for starting/shutdown of Altibase are defined and values are set.


The contents of this file are shown below.


If the user does not want to automatically start Altibase when booting HP-UX, set the value of START_ALTIBASE to 0. And if
ALTIBASE_OWNER or ALTIBASE_HOME is changed, modify the altibase_conf file must be also modified.


STEP 2


Create the /sbin/init.d/alti_start file. This file is a script that actually starts up Altibase by using the Altibase startup command.





STEP 3


Create the /sbin/init.d/alti_stop file.This file is a script that actually shuts down Altibase by using the Altibase shutdown
command.


STEP 4


Create the /sbin/init.d/altibase file.
This file can be created by copying the /sbin/init.d/template file, which is actually the file that the Start/Stop script will create
symbolic links later on.


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


Create Symbolic Link of Startup Script and Shutdown Script in /sbin/rc2.d directory.


STEP 6


Modify the execution permission so that each script can be executed normally.





STEP 7


Test to see if it works properly. At this time, the test must be performed under the root account.




### Maximum Capacity Specifications for Altibase


|Altibase Database Engine Object|Maximum sizes / Numbers Altibase|
|---|---|
|Identifier length|40 bytes|
|Tablespaces per database|64 * 1,024|
|Datafiles per tablespace|1,023|
|Datafile size|32 gigabytes (64bit standard)|
|Users per database|2,147,483,638|
|Tables per database|2,097,151|
|Indexes per table|64|
|Columns per table|1,024|
|Columns per index|32|
|Rows per table|Limited by available storage OR maxrows|
|Partitions per partitioned table or index|2,147,483,638|
|Constraints per database|2,147,483,638|
|Replications per database|6.1.1 or earlier : 32<br>6.3.1 or later : Set to REPLICATION_MAX_COUNT property|
|Tables per replication|2147483647|


### Notes/Considerations when changing TRANSACTION_TABLE_SIZE

Overview

Restriction

How to change

Change (offline)
Change (ALTER SYSTEM)
Change procedures

When data migration is required
When it is possible to change to offline
Maximum value

TRANSACTION_TABLE and Memory usage
When TRANSACTION_TABLE_SIZE is exceeded
Performance View

Error Messages


Overview


TRANSACTION_TABLE_SIZE is an Altibase server property and means the maximum number of transactions that can be executed
simultaneously while operating the database.


There is always one transaction in one session. Therefore, if the number of concurrent connection sessions increases, the number of
concurrent transactions may increase. Therefore, when increasing the MAX_CLIENT property value, consider changing the
TRANSACTION_TABLE_SIZE.


TRANSACTION_TABLE_SIZE also refers to the unique number (TID) of the transaction. This property requires caution when changing
because different transactions can be recognized as one transaction if the TID causes problems due to an incorrect change.


Also, the change method differs depending on the ALTIBASE HDB version, so the related contents are summarized.


Restriction


Depending on the ALTIBASE HDB version, there are versions that require data migration to change TRANSACTION_TABLE_SIZE.
Please refer to the 'How to change' section below.
It can only be changed to a 2^n value greater than the current value.
It can be changed in the order of 2^n 16 -> 32 -> 64 -> 128 -> 256 -> 512 -> 1024 -> 2048 -> 4096 -> 8192 -> 16384.
It cannot be changed from a large value to a small value.
The number of concurrent transactions must be set higher than MAX_CLIENT because it includes all user transactions, replication
transactions, and internal transactions.
In a replication environment, it may be necessary to set up to twice of MAX_CLIENT in consideration of replication transactions.
In a replication environment, the TRANSACTION_TABLE_SIZE must all be the same between the replication target servers. If the
TRANSACTION_TABLE_SIZE is different, the replication sender thread will not start.





How to change


Change (offline)


From the version specified below, it can be changed to offline. (Except for ALTIBASE HDB 4 version)


|ALTIBASE HDB server<br>version|4.3.9|From 5.1.5.93|From 5.3.3.48|From 5.3.5.17|From 5.5.1.1.0|
|---|---|---|---|---|---|
|Change (offline)|Cannot be<br>changed.<br>Data migration<br>required.|Changeable데이터<br>마이그레이션 필요.|Changeable<br>데이터 마이그레이션<br>필요.|Changeable<br>데이터 마이그레이션<br>필요.|Changeable<br>데이터 마이그레이션<br>필요.|







|ALTIBASE HDB server<br>version|4.3.9|5.1.5.0 ~ 5.1.5.92|5.3.3.0 ~ 5.3.3.47|5.3.5.0 ~ 5.3.5.16|5.5.1.0.0 ~ 5.5.1.0.9|
|---|---|---|---|---|---|
|Change (offline)|Cannot be changed.<br>Data migration<br>required.|Cannot be changed.<br>Data migration<br>required.|Cannot be changed.<br>Data migration<br>required.|Cannot be changed.<br>Data migration<br>required.|Cannot be changed.<br>Data migration<br>required.|


Change (ALTER SYSTEM)











Alter success when changing to ALTER SYSTEM may appear to be changeable by falling off, but TRANSACTION_TABLE_SIZE cannot be
changed while online.
















|ALTIBASE HDB<br>server version|4.3.9|5.1.5|From<br>5.3.3.64|From<br>5.3.5.26|From<br>5.5.1.2.13|
|---|---|---|---|---|---|
|Change (online)<br>(alter system)|It looks like it can be done with an alter<br>system, but it cannot be changed.|It looks like it can be done with an alter<br>system, but it cannot be changed.|Cannot be<br>changed|Cannot be<br>changed|Cannot be<br>changed|
















|ALTIBASE<br>HDB server<br>version|4.3.9|5.1.5|5.3.3.0 ~ 5.3.3.63|5.3.5.0 ~ 5.3.5.25|5.5.1.0.0 ~ 5.5.1.2.12|
|---|---|---|---|---|---|
|Change<br>(online)<br>(alter<br>system)|It looks like it can be<br>done with an alter<br>system, but it cannot be<br>changed.|It looks like it can be<br>done with an alter<br>system, but it cannot be<br>changed.|It looks like it can be<br>done with an alter<br>system, but it cannot be<br>changed.|It looks like it can be<br>done with an alter<br>system, but it cannot be<br>changed.|It looks like it can be<br>done with an alter<br>system, but it cannot be<br>changed.|



In the version where BUG-33467 is reflected, [ERR-0104E: The property [TRANSACTION_TABLE_SIZE] is read-only.] error occurs when
changing to ALTER SYSTEM.


Related bug


BUG-33467 Change TRANSACTION_TABLE_SIZE property attribute to read-only. Modify so that it cannot be changed with ALTER
SYSTEM.


BUG-31862 Improves the ability to change TRANSACTION_TABLE_SIZE without migration. It can only be changed to a value of 2^n

greater than the current value.


Change procedures


When data migration is required



1.

2.

3.

4.

5.

6.

7.



Secure service downtime

Database backup using aexport, iloader
Shutdown Altibase server

Change TRANSACTION_TABLE_SIZE in altibase.properties
Recreate database

Upload data to the backup backed up in 2
Startup Altibase server



When it is possible to change to offline



1.

2.

3.

4.



Securing service downtime
Altibase server shutdown

Change TRANSACTION_TABLE_SIZE in altibase.properties
Startup Altibase server


Maximum value


Depending on the ALTIBASE HDB server version, the maximum value for TRANSACTION_TABLE_SIZE is different. In previous versions,
some manuals have errors in the description of the maximum value, so please refer to the table below.

|ALTIBASE HDB server version|From 4.3.9.222|From 5.1.5.112|From 5.3.3.91|From 5.3.5.35|From 5.5.1.5.3|
|---|---|---|---|---|---|
|Maximum value|16384|16384|16384|16384|16384|


|ALTIBASE HDB server version|4.3.9.0 ~ 4.3.9.221|5.1.5.0 ~ 5.1.5.111|5.3.3.0 ~ 5.3.3.90|5.3.5.0 ~ 5.3.5.34|5.5.1.0.0 ~ 5.5.1.5.2|
|---|---|---|---|---|---|
|Maximum value|8192|8192|8192|8192|8192|



Related bug


BUG-37851 The maximum value of the TRANSACTION_TABLE_SIZE value needs to be modified.


TRANSACTION_TABLE and Memory usage


When running the ALTIBASE HDB server, memory for TRANSACTION_TABLE_SIZE is allocated in advance. So, depending on the
TRANSACTION_TABLE_SIZE setting, memory usage may increase slightly.


The following is an example of comparing memory usage according to the TRANSACTION_TABLE_SIZE setting value.


Memory usage may vary depending on the system environment. Please note only the difference according to the
TRANSACTION_TABLE_SIZE setting value. The unit is KB.

|Col1|1024|2048|4096|8192|16384|
|---|---|---|---|---|---|
|VSZ|1,484,952|1,647,264|2,019,544|2,911,096|5,309,148|
|RSS|660,900|825,956|1,164,640|2,093,068|4,465,108|



The test server environment is as follows:


Linux

Environment variable MALLOC_ARENA_MAX=4
ALTIBASE HDB 6.3.1.2.7


When TRANSACTION_TABLE_SIZE is exceeded


If the number of concurrent transactions exceeds TRANSACTION_TABLE_SIZE, the database may appear to hang due to the following
phenomena.


Unable to connect to a new session

No response when executing SQL in the connected session


The following message appears in altibase_boot.log.


TRANSACTION_TABLE_SIZE is full !!

Current TRANSACTION_TABLE_SIZE is 1024

Please check TRANSACTION_TABLE_SIZE


Performance View


The TRANSACTION_TABLE_SIZE setting value and the number of running transactions can be checked in V$TRANSACTION_MGR.


-- TOTAL_COUNT refers to the value of TRANSACTION_TABLE_SIZE setting, and ACTIVE_COUNT refers to the
number of transactions in progress.


iSQL> SELECT TOTAL_COUNT, ACTIVE_COUNT FROM V$TRANSACTION_MGR;

TOTAL_COUNT ACTIVE_COUNT

---------------------------
8192    4

1 row selected.


Error Messages


ERR-10166(errno=2) TRANSACTION_TABLE_SIZE ['4094'] is not a power of two.


This is an error message that occurs when the value of the TRANSACTION_TABLE_SIZE property is not 2^n.


2^n values are 16, 32, 64, 128, 256, 512, 1024, 2048, 4096, 8192, 16384.


ERR-10018(errno=0) The version of data file for backup is not compatible with the version of storage manager. Backup DB => [ Version ID =


4.11.1, Bit = 64, Endian = BIG LogSize = 10485760 Transaction Table Size = 1024 ] Server=>[ Version ID = 4.11.1, Bit = 64, Endian = BIG


LogSize = 10485760 Transaction Table Size = 2048 ]


This is an error message that occurs in the version where the TRANSACTION_TABLE_SIZE set when creating the database cannot be
changed.


This can happen when changing from a large value to a small value.

### Notes/Considerations when increasing the number of concurrent connection sessions (MAX_CLIENT)


Overview

Version

Changing Procedure
Considerations


MAX_CLIENT property

How to check the current settings
How to change the settings
TRANSACTION_TABLE_SIZE

How to check the current settings
How to change the settings
Changing OS user resource open files

Check the setting value
Reference


Overview


This document explains how to change the maximum number of sessions that can be connected to the ALTIBASE HDB server at the
same time.


The number of concurrent sessions can be limited by the Altibase server property MAX_CLIENT, and there are some things to consider
when changing this property.


Version


All the ALTIBASE HDB versions


Changing Procedure



1.

2.

3.

4.

5.



Secure service downtime

Shutdown ALTIBASE HDB server
Change ALTIBASE server properties (refer to 'Considerations' below)
Check OS user resources and change them if necessary (refer to' Considerations' below)
Startup ALTIBASE HDB server



Considerations


MAX_CLIENT property


Set the maximum number of sessions that can be connected to the ALTIBASE HDB server at the same time.


The default value is 1000, which can be changed more if necessary. Since this property cannot be changed during operation, the
ALTIBASE HDB server must be restarted if changes are required.


How to check the current settings


SELECT NAME, VALUE1 FROM V$PROPERTY WHERE NAME = 'MAX_CLIENT';


How to change the settings


Change the MAX_CLIENT value in the $ALTIBASE_HOME/conf/altibase.properties file


TRANSACTION_TABLE_SIZE


This property sets the maximum number of transactions that can be performed concurrently on the ALTIBASE HDB server. As the number
of concurrently connected sessions increases, the number of concurrent transactions may increase. Therefore, it is recommended to
change them together.


Since this property cannot be changed during operation, the ALTIBASE HDB server must be restarted if it needs to be changed.


Transactions should be set to be larger than MAX_CLIENT because not only transactions performed by users, but also system
transactions and replication transactions.


How to check the current settings


SELECT NAME, VALUE1 FROM V$PROPERTY WHERE NAME = 'TRANSACTION_TABLE_SIZE';


How to change the settings


Change the TRANSACTION_TABLE_SIZE value in the $ALTIBASE_HOME/conf/altibase.properties file


The TRANSACTION_TABLE_SIZE property setting value can be set to 2^n, which is larger than the current value, and cannot be
changed from a large value to a small value.


Since the change method differs depending on the ALTIBASE HDB server version, be sure to refer to this page (Considerations
when changing TRANSACTION_TABLE_SIZE) to proceed.


Changing OS user resource open files


open files are the number of files that can be opened by a process, including not only files accessed by the process, but also
communication sockets.


For example, if the ALTIBASE HDB server is operated in a user environment where this value is limited to 10, 10 sessions can be
connected at the same time. (In fact, considering the files used by the ALTIBASE HDB server, there may not be an accessible session.)


It is recommended to set it to the maximum value allowed by the operating system (if possible, unlimited).


Check the setting value


$ ulimit -Sn   # soft limit

2000


$ ulimit -Hn   # hard limit

unlimited


The soft limit is the value set by the OS user, and the hard limit is the value set by the root user. The soft limit cannot be greater than the
hard limit.


If the user needs to set it to a value greater than the hard limit, the user also needs to change the setting of the root user.


How to change


How to change user preferences


Add the following command to the environment configuration file (.bash_profile or .profile).


$ id                             # Log in as the OS user running the ALTIBASE HDB server
uid=509(altibase) gid=512(altibase) groups=512(altibase)


$ vi \~/.bash_profile                     # Add configuration command to environment configuration
file (Environment configuration file may be different depending on the shell.)


ulimit \-n unlimited


$ . ~/.bash_profile                      # Apply user preferences (after logout)


$ ulimit -Sn                         # Check the applied value

unlimited


How the root user changes


Change the user's nofiles value in /etc/security/limits.conf file


Setting example) When changing the number of open files of altibase user to 65535

altibase soft nofile 65535

altibase hard nofile 65535













Reference


For information on ALTIBASE HDB server properties, refer to the General Reference manual at https://github.com/ALTIBASE/Doc

uments/tree/master/Manuals/.
MAX_CLIENT and related settings are the maximum values, so large changes do no affect DB performance or system resources.
System resources may increase if the number of concurrent connection sessions and concurrent transactions increases due to
configuration changes. However, it is difficult to answer how much impact it will have as it depends on the operating
environment.

### Notes on using floating point data type (double, float)


Notes when using double or float data types
Version

Example of truncated double numeric value

Phenomenon that the value is truncated in iSQL
When data is exported from iLoader
When it comes to a double type host variable from a program, it is normally retrieved.
Same phenomenon in Oracle sqlplus
Solution


Notes when using double or float data types


Altibase's double data type is the same as the C language's double data type. While the double data type can represent a wider range of
numbers than the fixed-point method, the value may be inaccurate because it is expressed as an approximate value, and meaningless
values after the decimal point may be too long.


In addition, when double/float type values are retrieved with iSQL or exported to iloader, the value after the decimal point may not be
truncated.


Therefore, in order to accurately retrieve or store values below the decimal point, a fixed-point number type such as numeric must be
used.


Version


This is the same for all Altibase versions.


Example of truncated double numeric value


Phenomenon that the value is truncated in iSQL





When data is exported from iLoader


When it comes to a double type host variable from a program, it is normally retrieved.


Same phenomenon in Oracle sqlplus


As a result of checking, there is a phenomenon that the same value is truncated in the Oracle sqlplus.







Solution


In order to accurately retrieve or store values below the decimal point, a fixed-point number type such as numeric(scale, precision) must
be used.


The following is an example of executing a value in iSQL when using numeric type.


### User password length limitation - Differences by version

Overview


Version changed from no limit to 8 digits
Password length changed from 8 digits to 16 digits


Overview


This section summarizes the restrictions on the length of database user passwords that differ depending on the ALTIBASE HDB server
version.


Version changed from no limit to 8 digits


There is no length limit when setting a user password, but in ALTIBASE HDB, only 8 digits of the entered password are cut and saved.


This part was confusing to the users, so from the version below it has been changed to limit the password length to fit the actual

structure.


Applied versions
ALTIBASE HDB 4.3.9.200

ALTIBASE HDB 5.1.5.98

ALTIBASE HDB 5.3.3.62

ALTIBASE HDB 5.3.5.25

ALTIBASE HDB 5.5.1.2.10

ALTIBASE HDB 6.1.1.0.0

Difference in password length by platform
Windows, Solaris(sparc, x86) : 11byte
Other platforms: 8byte


Password length changed from 8 digits to 16 digits


As the length of the password is limited to 8 digits, the length of the password has been doubled to reflect the opinion that the length is
short.


Applied versions
ALTIBASE HDB 4.3.9.221

ALTIBASE HDB 5.3.3.89

ALTIBASE HDB 5.5.1.5.1

ALTIBASE HDB 6.1.1.1.5

Difference in password length by platform
Windows, solaris(sparc, x86) : 22byte
Other platforms: 8byte


The increase in password length was reflected by the addition of the 'Password Policy Function'.

ALTIBASE HDB versions 5.1.5 and 5.3.5 do not reflect this function, so there is no change in the password length. (No change
after change to 8 digits)




### What is MEM_MAX_DB_SIZE?

Definition

Maximum Value

How to Change

When to set it larger than the current value
When to set it less than the current value

How to change
Check the setting value


Definition


This refers to the maximum amount of memory that can be used as a memory tablespace (memory table or memory data) stored
in physical memory.
Constraints on the total usage of all memory tablespaces combined.
This is not the maximum size that each of the memory tablespaces can use.
The size of the index created on the memory table is not included.
It also includes historical data that occurs when performing change transactions.
When a change transaction is performed, the past data is retained until the transaction is terminated (MVCC technique). In the
case of a memory table, a replica of the record is created in the memory table.
If the maximum value is not specified when creating a memory tablespace, it is automatically expanded by the value set for
MEM_MAX_DB_SIZE.


Maximum Value


It is recommended to set it to about 60~70% of the physical memory.

In addition to the memory data, must consider the size of the record replicas that will be created by the MVCC technique when
performing a change transaction.
For example, if a change transaction occurs in a 1G memory table, the size of the table may be 2G when the transaction is
completed.
Since memory is a shared resource that should be used by the OS and other processes as well as the Altibase server process, it
should be set lesser than the physical memory.
Although it is possible to set MEM_MAX_DB_SIZE larger than the physical memory, if the memory is used beyond the physical
memory, swap in/out may occur, resulting in performance degradation and various problems in the system.


How to Change


When to set it larger than the current value


This section describes the parts to be considered when setting MEM_MAX_DB_SIZE larger than the current value.


Disk space


Memory tablespaces store two sets of 'memory checkpoint image files on disk for backup purposes. So it requires twice as much disk
space as the memory data usage.


If MEM_MAX_DB_SIZE is set large, disk usage will also increase, so make sure to free up disk space before changing
MEM_MAX_DB_SIZE.


Ex) If MEM_MAX_DB_SIZE is 60G, 120G of disk space is required.


User environment setting (Linux/Unix)


The user should run ulimit -a to make sure that the settings below are set to the maximum values allowed by the OS.


max memory size
virtual memory


Kernel parameters (AIX, HP-UX)


For AIX, check if data, rss, fsize, etc. are set to -1 in the /etc/security/limits file.


For HP, check that the maxdsiz_64bit value is set large enough via kctune.


Linux and SunOS are not applicable.


When to set it less than the current value


This section describes the parts to be considered when setting MEM_MAX_DB_SIZE less than the current value.


MEM_MAX_DB_SIZE cannot be set less unconditionally.
Check the increased 'Checkpoint Image File' size and set it larger than that.
Its size can be checked with the statement below.


If TOTAL is less than MAX, set MEM_MAX_DB_SIZE to be larger than TOTAL and smaller than the existing value.


If the user copies the SQL statement in IE, a blank line may appear, so please use the attached file if necessary.
total_memory_tablespaces_usage.txt


set linesize 1024

set colsize 20
SELECT TO_CHAR(MEM_MAX_DB_SIZE/1024/1024, '999,999,999') '    MAX(M)',
-- MAX(M)  : MEM_MAX_DB_SIZE setting value
TO_CHAR(MEM_ALLOC_PAGE_COUNT*32/1024, '999,999,999') '   TOTAL(M)',
-- TOTAL(M) : The total page size allocated to the memory tablespace. Also refers to the size of the
checkpoint image file.
TO_CHAR((MEM_ALLOC_PAGE_COUNT-MEM_FREE_PAGE_COUNT)*32/1024, '999,999,999') '
ALLOC(M)',       -- ALLOC(M) : Amount of memory used by the tablespace
(SELECT TO_CHAR(SUM((FIXED_USED_MEM + VAR_USED_MEM))/1024/1024, '999,999,999')
FROM V$MEMTBL_INFO) '   USED(M)',                                 -- USED(M) :

Memory size in which data is stored among ALLOCs

TO_CHAR((((MEM_ALLOC_PAGE_COUNT-MEM_FREE_PAGE_COUNT)*32*1024)/MEM_MAX_DB_SIZE)*100,
'99.99') 'USAGE(%)' -- USAGE(%) : ALLOC utilization rate compared to MAX
FROM V$DATABASE ;
MAX(M)     TOTAL(M)     ALLOC(M)     USED(M)   USAGE(%)

----------------------------------------------------------------------------------
-------
5,120       920       621       142   12.13

1 row selected.


TOTAL is...

TOTAL(M) means the total page size allocated to the memory tablespace.


This value also includes free pages in the memory tablespace.
Free pages may not be loaded into physical memory. So this value cannot be viewed as the physical memory usage of the memory
tablespace.


This value also refers to the size of the checkpoint image file.


TOTAL does not decrease except in the case of DROP TABESPACE. Restarting the Altibase server does not decrease the value.





How to change


1. Stop the Altibase Server


$ server stop


2. Change the altibase.properties file


Save after changing MEM_MAX_DB_SIZE in the Altibase server properties file ($ALTIBASE_HOME/conf/altibase.properties).


$ vi $ALTIBASE_HOME/conf/altibase.properties

MEM_MAX_DB_SIZE    = 2G # MEM_MAX_DB_SIZE


3. Start the Altibase Server


$ server start


Check the setting value


The setting value can be checked in two methods as below.


iSQL> set linesize 1024

iSQL> set colsize 20
iSQL> SELECT NAME, TO_CHAR(VALUE1/1024/1024, '999,999') AS 'VALUE(MB)' FROM V$PROPERTY WHERE
NAME = 'MEM_MAX_DB_SIZE';


Or,


SELECT TO_CHAR(MEM_MAX_DB_SIZE/1024/1024, '999,999') AS 'MEM_MAX_DB_SIZE(MB)' FROM
V$DATABASE;

### When log disk is FULL and its countermeasures


Overview

Applicable versions
Altibase operation status when the disk is full
When the directory containing log files is full
Countermeasures when the log disk is full


Overview


This document describes the situation and countermeasures that can occur only when a full disk occurs in the directory where the log file


This document describes the situation and countermeasures that can occur only when a full disk occurs in the directory where the log file

exists during the operation.


Applicable versions


This document is written based on ALTIBASE HDB 6.3.1.
If you need additional inquiries or updates, please leave a request post at http://support.altibase.com/en/ or make a comment
on this page.


Altibase operation status when the disk is full


The filesystem full phenomenon during the Altibase operation may be a full file system with a DB file or a full file system with a log file.


If the file system with the DB file is full, it does not affect general transactions.


However, the checkpoint operation cannot be performed because there is not enough free disk space when performing checkpoint.


Therefore, all changes made to the DB are reflected only in the DB in memory.


When the file system with the LOG file is full, transactions that make changes to the DB are no longer executed and the Altibase process
enters a waiting state. In other words, services except for 'select' are stopped.


In general, disk full occurs because the file system size is small, and it is recommended to operate Altibase after securing sufficient disk

space.


When the directory containing log files is full


The following are cases in which there are abnormally many log files because the log files are not deleted even though the disk space is
secured and operated.



1.


2.


3.



When using replication, replication data is not reflected the other server due to network instability or other reasons
=> To confirm this, check the replication gap.


SELECT * FROM V$REPGAP;


When the value of the ARCHIVE_FULL_ACTION property is set to 1
=> This property controls the operation of the archive thread that performs archive log backup when there is not enough disk
space in the file system to which the directory set in ARCHIVE_DIR belongs.
If the value is 0, the archive thread outputs an error message and then stops backing up the archive log file. Even after sufficient
disk space is secured thereafter, archive log backup is not resumed unless the user explicitly enters a command to enable
archive log backup. In this case, when a checkpoint occurs, unnecessary log files are deleted even if the archive log files are not
backed up, so be cautious during the operation.
If the value is 1, the archive thread waits until enough disk space is available to back up the archive log file. During this period,
even if a checkpoint occurs, log files are not deleted because archive log files cannot be backed up.
The user can refer to the $ALTIBASE_HOME/conf/altibase.properties file or check the value of this property in isql.


select name, value1 from v$property where name like '%ARCHIVE_FULL_ACTION%';


If the checkpoint has not been performed
=> Since log file deletion occurs only at the checkpoint, check whether or not the checkpoint has been successfully executed.
Checkpoint execution can be checked by referring to the $ALTIBASE_HOME/trc/altibase_sm.log file.
Logs are recorded when the checkpoint is normally executed as shown below.


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

[CHECKPOINT-summary] BeginChkptLSN=[0,0,6232554], EndChkptLSN=[0,0,6233141],
DiskRecLSN=[0,0,6232554]

[2015/12/14 10:42:50] [Thread-140330825209600] [Level-9]
Minimum LSN = [0,0,6232554]

[2015/12/14 10:42:50] [Thread-140330825209600] [Level-9]


4.




[CHECKPOINT-END]

[2015/12/14 10:42:50] [Thread-140326782105344] [Level-9]
Sleep checkpoint thread ( next time : 2015-12-14 12:22:50 )


When the checkpoint is executed normally
(1) Among the message contents displayed when executing checkpoint

[CHECKPOINT-step9] Check the Remove Online Log File part.
In the case of [None] and skip appearing at the end of each checkpoint execution, it has appeared that the log files cannot be
deleted because the checkpoint is normally executed, but there is a long transaction or the redundant data does not pass.
(2) If the log partition is full even though the log file is deleted every time a checkpoint occurs, check whether the transaction is
very busy and the size of the file system.
=>Since transactions are very busy while the checkpoint is being executed, new log files may be created as many as the number
of log files deleted. Consider this and set the size of the file system to be large enough.



Countermeasures when the log disk is full


Move the log files in the $ALTIBASE_HOME/logs space to free space, attach a soft link, and secure the logs space to secure space for
the DBMS to I/O log files.


*Script to move log files and make symbolic links


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


For reference, if the current DB is running, the user must move and link the log files except for the log files in use.


- How to check the log files in use


lsof -p PID(ALTIBASE DB) | grep logfile


### When server create errors occur after DB name change

Contents


Up to version 5.3.3 or earlier, the DB must be manually created.


The following types of tasks can be performed by executing the server command, and the DB can be created with the server create
command.





When the first DB is created, the DB NAME is set to mydb, and DB_NAME can be changed in altibase.properties.





When performing server craete after changing DB_NAME, the following error occurs.





Solution


This occurs because the DB name is mydb in the $ALTIBASE_HOME/bin/server script file.


Create the DB after making the same change as DB_NAME changed in altibase.properties.

## 03. Replication


### Causes and Solutions of Replication Conflicts

Overview

When data conflicts occur in a replication environment
Measures to prevent conflict as much as possible
Conflict type


Overview


This document describes the causes and solutions of replication conflicts.


When data conflicts occur in a replication environment


A replication conflict occurs when insert/update/delete is executed on the same key value at the same time.


- insert conflict: When an INSERT conflict occurs, the INSERT fails and a conflict error message is an output to altibase_rp.log. Use the
REPLICATION_INSERT_REPLACE property to set a policy that resolves conflicts that occur when inserting data with the same key as an
existing record. REPLICATION_INSERT_REPLACE=1: Insert after deletion. REPLICATION_INSERT_REPLACE=0: Do not delete or insert,
and output an error message.


- update conflict: When an UPDATE conflict occurs, the UPDATE fails and a conflict error message is displayed in altibase_rp.log. The
REPLICATION_UPDATE_REPLACE property can be used for conflict resolution. This occurs when the previous image changes other data
or attempts to change to a primary key that does not exist. For example, if it currently has data of 10 and a replication transaction has an
update to change from 20 to 30, the following policy can be used depending on the situation: REPLICATION_UPDATE_REPLACE=1:
Update. REPLICATION_UPDATE_REPLACE=0: Does not update and displays a conflict error message.


- delete conflict: When a DELETE conflict occurs, the DELETE fails and a conflict error message is displayed in altibase_rp.log.


For example in the case of insert:


1) After data with key=1 is inserted in server A, before transmitting the replication data to server B


2) When the same key=1 data is inserted in server B, the replication data received later in server B already has data with the same key=1
in server B, so a conflict occurs.


Measures to prevent conflict as much as possible


The best way is to avoid insert/update/delete with the same Key value on both servers.


For example, if the sequence is the primary key for a specific table, if the user inserts/updates/deletes data only with odd numbers on
one side and even numbers on the other server, there will be no replication conflict.


In addition, do not do bulk insert/update/delete.


There are three solutions for replication conflict provided by Altibase.


1) User-Oriented Scheme


(1) Insert conflict: If you try to insert data with the same key, it is not reflected. (Output Conflict Error Message to altibase_rp.log)


(2) delete conflict: If you want to delete data with the same key, it is not reflected. (Output Conflict Error Message to altibase_rp.log)


(3) Update conflict: In the case of updating data with the same key, it is specified whether or not it is reflected according to the following
attribute values.


-REPLICATION_UPDATE_REPLACE=1: Updated


-REPLICATION_UPDATE_REPLACE=0: Do not update and it is a conflict


Error message output


2) Master-slave Scheme


When declaring a replication object, if as a master or as a slave is specified in the syntax, the replication conflict is handled as follows.


(1) Master's processing method: All Insert/Update/Delete conflicts are not reflected.


(2) Slave processing method


-Insert conflict: Delete an existing record and add a new record.


-Update conflict: The conflict is ignored and unconditionally reflected.


-Insert conflict: Not reflected.


3) Timestamp-based Scheme


After setting the REPLICATION_TIMESTAMP_RESOLUTION property value to 1, a timestamp column is used in the replication table to
reflect the latest value. In this method, there is a limitation that the timestamp column must be added to all of the replication target
tables, and the time between both servers being replicated must be set equally.


Conflict type


When a conflict occurs, a log is recorded in $ALTIBASE_HOME/trc/altibase_rp.log.


- Insert conflict: Occurs when the same PK (Primary Key) already exists.


[2015/04/28 10:11:33] [Thread-489] [Level-2]
ERR-11058(errno=0) The row already exists in a unique index.


[2015/04/28 10:11:33] [Thread-489] [Level-3]
INSERT INTO TEST VALUES ( 14, 0, 0,, 0, 0, 0, 0 );


- update conflict: Occurs when the PK (Primary Key) is the same, but the pre-change value from the remote server is different from the
current value.


[2015/04/27 18:49:32] [Thread-489] [Level-2]
ERR-610f7(errno=16) [Receiver] Unable to find record in executeUpdate() function


[2015/04/27 18:49:32] [Thread-489] [Level-2]
ERR-61000(errno=16) The received record is not found in the database.


[2015/04/27 18:49:32] [Thread-489] [Level-3]

UPDATE TEST SET C2 = 20150428 WHERE C1 =1231232 ;


- delete conflict: Occurs when the PK (Primary Key) is the same, but the pre-change value from the remote server is different from the
current value.


[2015/10/28 17:03:08] [Thread-140059163547392] [Level-2]
ERR-610f7(errno=16) [Receiver] Unable to find record in executeDelete() function


[2015/10/28 17:03:08] [Thread-140059163547392] [Level-3]

DELETE FROM TEST WHERE C1 = 21987744;

### DDL operation on the table for Altibase replication


Overview

Version

Procedure


Operation under service outages
Operation under uninterrupted constraints


Overview


In general, DDL operations on the DB require an exclusive lock on the table. ALTIBASE HDB uses a network-based redundancy
technique in which data is matched by transmitting the transaction log generated in the local server to the other server.


DDL-like operations are not sent to the log, so DDL operations are not replicated. Therefore, different from the disk sharing method, a
different method of performing DDL operations on each node (Server) is required.


Version


ALTIBASE HDB supports different types of DDL statements depending on the version, and the functions of DDL statements related to
replication are also different.


In the case of simple DDL operation, the operation procedure in this document can be used as it is in ALTIBASE HDB 4.3.9, but it is
mainly described for ALTIBASE HDB 5.3.3 or later.


Procedure


If there is a possibility that a large amount of data change may occur due to the DDL statement, other safer operation procedures should
be used, and please refer to the DDL Guide of ALTIBASE Replication Environment.


Operation under service outages


In an environment where all services accessing the database can be stopped for a certain period of time, it can be completed with a
relatively simple procedure.


Step A node B node


|STEP<br>1|Stop the serve (take action to prevent transactions from occurring)<br>In order to stop the service, the service port is changed after the DB is stopped, and the service is started.<br>Check the session connected to the database or checking the statement being executed<br>iSQL> select count(*) from v$session;<br>iSQL> select count(*) from v$statement where execute_flag =1 ;|
|---|---|
|STEP<br>2|Check that the replication gaps of the target nodes are all "0" (this means the DB where the replication sender is driven)<br> <br>Check the replication object to which the target table for DDL execution belongs<br>iSQL> select REPLICATION_NAME,LOCAL_USER_NAME, LOCAL_TABLE_NAME from<br>SYSTEM_.SYS_REPL_ITEMS_;<br>Check the replication gap<br>iSQL> SELECT rep_name, rep_gap FROM v$repgap;      # Check that rep_gap is all 0.|
|STEP<br>3|Stop the replication of target node<br>iSQL>  ALTER REPLICATION<br> STOP;   # The replication object (REP_NAME) is checked in STEP 2.<br>rep_name|
|STEP<br>4|Remove the target table to execute DDL from the replication object<br>iSQL> ALTER REPLICATION<br> DROP TABLE FROM<br> TO<br>; <br>rep_name<br>user_name.table_name<br>user_name.table_name|
|STEP<br>5|Perform DDL operation<br> iSQL> ALTER TABLE t1 ADD COLUMN ( c1 INTEGER);|
|STEP<br>6|Add the replication target table removed in STEP 4 back to the replication object list<br>iSQL> ALTER REPLICATION<br> ADD TABLE FROM<br> TO<br>; <br>rep_name<br>user_name.table_name<br>user_name.table_name|
|STEP<br>7|Start the replication at the target node<br> iSQL> ALTER REPLICATION<br> START<br>rep_name|
|STEP<br>8|Initiate the service<br>If the service port number of the DB is changed in STEP 1, restore the service port and restart the database.<br>After restarting the DB service by running the application, check the DB status.|



Operation under uninterrupted constraints


In an environment that requires uninterrupted service, there may be a limitation that one node must alternately work one node at a time
while operating the database.


Under these conditions, compared to the environment in which service disruption described above is possible, several steps are required
and caution may be required.


Please refer to the DDL guide document of the ALTIBASE replication environment.
Get technical support from ALTIBASE Technical Support Division (Service Portal:http://support.altibase.com/en/, TEL
+82-2-2082-1114)

### How to add/delete replication target table


Overview

Version

Adding replication target table
Deleting replication target table
Reference documents


Overview


This document describes how to add or delete replication target tables in the replication object.


Version


Altibase version 4.3.9 or later


Adding replication target table


This is the procedure for adding tables to be replicated in the replication object.



1.


2.


3.


4.



Stop the replication
Execute in the server where the replication sending thread is running.
With the statement below, the replication sender of the local server and the receive thread of the remote server are stopped.


iSQL> ALTER REPLICATION replication_name STOP;


-- Check the replication running status
iSQL> SELECT REPLICATION_NAME, DECODE(IS_STARTED, 0, 'STOPPED', 1, 'STARTED') IS_STARTED

FROM SYSTEM_.SYS_REPLICATIONS_;


Add the replication target table


iSQL> SELECT REPLICATION_NAME, LOCAL_USER_NAME, LOCAL_TABLE_NAME FROM

SYSTEM_.SYS_REPL_ITEMS_;


SYNC the replication
If the data on both servers do not match, TRUNCATE one server table and then perform a SYNC statement on the server where
the data exists to match the data.

If the data matches on both servers 4, start the replication.


iSQL> ALTER REPLICATION replication_name SYNC ONLY TABLE user_name.table_name;


Start the replication
If the data on both servers match each other, execute the replication start statement.


iSQL> ALTER REPLICATION replication_name START;


-- Chcek the replication running status.
iSQL> SELECT REPLICATION_NAME, DECODE(IS_STARTED, 0, 'STOPPED', 1, 'STARTED') IS_STARTED

FROM SYSTEM_.SYS_REPLICATIONS_;



Deleting replication target table


This is the procedure for deleting tables to be replicated in the replication object.



1.



Stop the replication
Execute in the server where the replication sending thread is running.
With the statement below, the replication sender of the local server and the receive thread of the remote server are stopped.


2.


3.



iSQL> ALTER REPLICATION replication_name STOP;


-- Chcek the replication running status.
iSQL> SELECT REPLICATION_NAME, DECODE(IS_STARTED, 0, 'STOPPED', 1, 'STARTED') IS_STARTED

FROM SYSTEM_.SYS_REPLICATIONS_;


Delete the replication target table


This is the statement for deleting the replication target table in the replication object in each of the replication target servers.


iSQL> ALTER REPLICATION replication_name DROP TABLE user_name.table_name TO

user_name.table_name;


-- Statement for checking the replication target table.
iSQL> SELECT REPLICATION_NAME, LOCAL_USER_NAME, LOCAL_TABLE_NAME FROM

SYSTEM_.SYS_REPL_ITEMS_;


Start the replication


iSQL> ALTER REPLICATION replication_name START;


-- Check the replication running status
iSQL> SELECT REPLICATION_NAME, DECODE(IS_STARTED, 0, 'STOPPED', 1, 'STARTED') IS_STARTED

FROM SYSTEM_.SYS_REPLICATIONS_;



Reference documents


For syntax explanation and additional options of the ALTER REPLICATION statement, refer to SQL Reference Manual -> 3. Data
Definition Language -> ALTER REPLICATION.
Manual download page: http://support.altibase.com/en/manual
Github: https://github.com/ALTIBASE/Documents/tree/master/Manuals/

### How to change replication object IP


Overview

Procedure


Overview


This is a procedure guide for changing the registered IP to another IP when creating a replication object.


Procedure


1. Stop the replication object to be changed.


ALTER REPLICATION replication_name STOP;


2. Add new IP


ALTER REPLICATION replication_name ADD HOST 'new_ip_address', replication_port;


3. Remove exist IP


ALTER REPLICATION replication_name DROP HOST 'old_ip_address', replication_port;


4. Start replication object


ALTER REPLICATION replication_name START;


5. Check the host information of the replication object


SELECT REPLICATION_NAME, HOST_IP, PORT_NO FROM SYSTEM_.SYS_REPL_HOSTS_ ORDER BY HOST_NO

### How to create/delete replication objects


Overview

Version

Preparation
Enabling the replication function
Creating replication object
Starting replication
Deleting replication object
Error messages
Reference Documents


Overview


For users who are new to replication, this document explains how to create and delete replication objects.


This document is written assuming that the user has completed the preliminary operation for replication structure or
configuration.
This document is written assuming that the data is consistent between the target servers for replication. Either all of the data
exist the same, or both are zero.


Version


Altibase version 4.3.9 or later


Preparation


Dedicated IP for replication
It is recommended to use a dedicated line separate from the service network for the IP to be used for replication.
Replication service port
Set the service port number for replication. It can be arbitrarily set by the user, and 30300 is generally used.
Select the target table for replication
The table to be replicated must have a primary key.


Enabling the replication function


Altibase server's replication function is disabled by default,


-- The default value of the REPLICATION_PORT_NO property is 0, which means that the replication

function is disabled.


iSQL> SELECT NAME, VALUE1 FROM V$PROPERTY WHERE NAME = 'REPLICATION_PORT_NO';

NAME              VALUE1

------------------------------------------------------------------
REPLICATION_PORT_NO       0

1 row selected.


To use the replication function, the user must enable it by changing the relevant properties.
Enabling the replication function requires restarting the Altibase server.


Changing REPLICATION_PORT_NO property


Replication is enabled by changing the value of the Altibase server property REPLICATION_PORT_NO.
The REPLICATION_PORT_NO property also means the port number to be used between replication threads.
The port number is not used by the server and is arbitrarily assigned by the user, and 30300 is also used in general.



1.


2.


3.



Check if the replication port specified by the user is in use on the replication target server.


# Example of execution when the replication port, REPLICATION_PORT_NO is set to 30300
$ netstat -an | grep 30300 | grep LISTEN


Open the altibase.properties file, change the REPLICATION_PORT_NO value, and save it. This must be done on each of the
replication target servers.


# Example of setting REPLICATION_PORT_NO when setting the replication port to 30300


$ cd $ALTIBASE_HOME/conf
$ vi altibase.properties

REPLICATION_PORT_NO = 30300


Restart the Altibase server process.


$ server restart


Click here to expand...

In order to block access to the application during the process of creating a replication object, change the Altibase server


4.



service port and restart it.


$ export ALTIBASE_PORT_NO=20400
$ server restart


After starting the Altibase server, check the replication port LISTEN status and property settings.


# Example of Replication port when REPLICATION_PORT_NO is set to 30300
$ netstat -an | grep 30300 | grep LISTEN
tcp    0   0 0.0.0.0:30300        0.0.0.0:*          LISTEN


-- # Example of Replication port when REPLICATION_PORT_NO is set to 30300


iSQL> SELECT NAME, VALUE1 FROM V$PROPERTY WHERE NAME = 'REPLICATION_PORT_NO';

NAME              VALUE1

------------------------------------------------------------------
REPLICATION_PORT_NO       30300

1 row selected.



Creating replication object


Replication objects are created with the CREATE REPLICATION statement and define information related to replication such as
replication mode, replication server information, and replication target table.
Two servers to be replicated are paired.
Replication objects must each be created with the same object name on the paired replication server.





Refer to Replication Manual -> 3. Using Replication -> Create Replication (CREATE REPLICATION) for additional options of the
replication object creation syntax.
Manual page: http://support.altibase.com/en/manual


Procedure for creating replication objects-Example 1 (when there are 2 replication target servers)

This is an example of creating a replication object when the conditions for creating a replication object are as follows.


The target server for replication is two A and B servers.
The replication object name is created as REP1.
The IP address of the target server A is 192.168.1.112 and the port number is 25524.
The IP address of the target server B is 192.168.1.113 and the port number is 35524.


1.


2.


3.



The target tables for replication are the SYS user's employees table and departments table.


Server A: IP 192.168.1.112, replication port: 25524


CREATE REPLICATION rep1 WITH '192.168.1.113', 35524
FROM sys.employees TO sys.employees,
FROM sys.departments TO sys.departments;

Create success.


Server B: IP 192.168.1.113, replication port: 35524


CREATE REPLICATION rep1 WITH '192.168.1.112', 25524
FROM sys.employees TO sys.employees,
FROM sys.departments TO sys.departments;

Create success.


Check whether the replication object was created






Procedure for creating replication objects-Example 2 (when there are 3 replication target servers)

This is an example of creating a replication object when the conditions for creating a redundant replication are as follows.


The target servers for replication are A, B, and C
A is B, C and
B is A, C and
C synchronizes with A and B with each other.
The name of the replication object is determined as follows.
-REP_A_B for servers A and B
-REP_B_C for servers B and C
-REP_C_A for A and C servers
The IP address and replication port number of each server are as follows.
-Server A: 192.168.1.112, 30300
-Server B: 192.168.1.113, 30300
-Server C: 192.168.1.114, 30300


The target tables for replication are the SYS user's employees table and departments table.



1.


2.



A Server : IP 192.168.1.112, Replication port: 30300


CREATE REPLICATION rep_a_b WITH '192.168.1.113', 30300 FROM sys.employees TO
sys.employees, FROM sys.departments TO sys.departments;
CREATE REPLICATION rep_c_a WITH '192.168.1.114', 30300 FROM sys.employees TO
sys.employees, FROM sys.departments TO sys.departments;


B Server : IP 192.168.1.113, Replication port: 30300


3.


4.



CREATE REPLICATION rep_a_b WITH '192.168.1.112', 30300 FROM sys.employees TO
sys.employees, FROM sys.departments TO sys.departments;
CREATE REPLICATION rep_b_c WITH '192.168.1.114', 30300 FROM sys.employees TO
sys.employees, FROM sys.departments TO sys.departments;


C Server : IP 192.168.1.114, Replication port: 30300


CREATE REPLICATION rep_c_a WITH '192.168.1.112', 30300 FROM sys.employees TO
sys.employees, FROM sys.departments TO sys.departments;
CREATE REPLICATION rep_b_c WITH '192.168.1.113', 30300 FROM sys.employees TO
sys.employees, FROM sys.departments TO sys.departments;


Check whether the replication object was created






Starting replication


Starting replication means starting the data synchronization.
The server that started the replication starts the replication sender thread, and the remote server paired with the server starts the
receive thread.



1.



Selecting the replication start server (active server)
The server that starts the replication and the server that runs the replication sender refers to the server where the change
transaction occurs and is also called the active server.

Among the replication target servers in a pair, the place where data change occurs is the active server, and the other server


2.


3.



becomes the standby server.
If a change transaction occurs on both servers and synchronizes in both directions, both servers become active servers.
Start of replication
The active server starts replication with the ALTER REPLICATION statement. replication_name is the name of the object created in
the replication object creation step.


   - The replication sender thread runs on the server that executes this command, and the receiver thread
is runs on the remote server paired with the server.
iSQL> ALTER REPLICATION replication_name START;


Check the status of starting/running replication
This is a statement to check whether the replication sending thread (Sender) and receiving thread (Receiver) are running.





Deleting replication object


This section describes how to delete replication objects.


   - Stop the replicaiton first.
iSQL> ALTER REPLICATION replication_name STOP;


   - Delete the replication object.
iSQL> DROP REPLICATION replication_name ;


Error messages


Here are some of the error messages that may occur during the process of creating replication objects.


[ERR-61023 : Replication is disabled]


This is an error message that can be encountered when executing the CREATE REPLICATION statement. It occurs when the
replication function is disabled
Check the value of the REPLICATION_PORT_NO property. Refer to the section on enabling the replication function.


[ERR-61113 : A replicated table must have a primary key. (user_name table_name. )]


This is an error message that may occur when executing the CREATE REPLICATION statement.
This occurs when there is no primary key in the replication target table specified in the FROM clause.
At the end of the error message, a primary key needs to be created in the table inside () and perform a duplicate object creation

statement.


[ERR-6100D : [Sender] Failed to handshake with the peer server (Handshake Process Error)]


This is an error message that may occur when ALTER REPLICATION replication_name START is executed.
Check if the remote server's IP and redundancy port number entered in the WITH clause are correct, and that access to the
corresponding IP and port is possible.


Reference Documents


Replication Manual
SQL Reference
Download manual page: http://support.altibase.com/en/manual
Github: https://github.com/ALTIBASE/Documents/tree/master/Manuals/

### How to create multiple replication objects with the same IP


Overview

Version

Procedure


Check the related property
Change the related property
Create replication objects
Check the host information of the replication object
Reference


Overview


Altibase replication had a limitation that the same IP address could not be used when creating multiple redundant objects.


As a property added to Altibase version 6.5.1 or later, it is possible to create different redundant objects with the same host information
without such restrictions.


Version


Altibase version 6.5.1 or later


Procedure


Check the related property


Check the value of the Altibase server property REPLICATION_ALLOW_DUPLICATE_HOSTS.


The default value of this property is 0, which does not allow different objects to have the same host information.


set linesize 1024

set colsize 60

SELECT NAME, VALUE1 FROM V$PROPERTY WHERE NAME = 'REPLICATION_ALLOW_DUPLICATE_HOSTS';


Change the related property


If the value of the REPLICATION_ALLOW_DUPLICATE_HOSTS property is 0, change it to 1.


ALTER SYSTEM SET REPLICATION_ALLOW_DUPLICATE_HOSTS = 1;


In order to permanently apply the property change value, modify the property value in the altibase.properties file and save it.


cd $ALTIBASE_HOME/conf

vi altibase.properties

REPLICATION_ALLOW_DUPLICATE_HOSTS   = 1


Create replication objects


Create more than one duplicate object with the same host information.


Check the host information of the replication object


Host information registered in the replicated object can be checked with the following sentence.


SELECT REPLICATION_NAME, HOST_IP, PORT_NO FROM SYSTEM_.SYS_REPL_HOSTS_ ORDER BY HOST_NO;


Reference


Altibase 6.5.1 New Features Guide
General Reference (Altibase 6.5.1 or later)
Manual Download: http://support.altibase.com/en/manual or https://github.com/ALTIBASE/Documents/tree/master/Manuals/

### Replication give-up


Overview

Version

Replication and log files
Replication give-up
Effect of give-up occurrence
How to prevent give-up
Set whether to proceed with replication when give-up occurs (automatic)
Cycle
Check whether give-up has occurred


Overview


This document explains the effects of give-up, which is a symptom that can occur when using replication.


Version


This document is written based on Altibase HDB version 6.3.1
For more detailed information or updates, please leave a request at http://support.altibase.com/en/ or in the comment section
on this page.


Replication and log files


Altibase replication uses the log_based replication method. In other words, this is a method to ensure data consistency between both
servers by transferring logs created on the active side to the standby side.


In Altibase, log files are not circularly recreated by creating only a certain number of log files, but log files are automatically created
continuously as long as the log is created. Therefore, unnecessary log files must be deleted periodically to prevent disk full.


Log files are deleted when the checkpoint is executed, and log files under the following conditions cannot be deleted.


(1) Log file referenced by the transaction currently in progress


(2) Log file that needs to be referenced in replication because replication transmission is not possible


(3) Log file referenced by the CLR log (Abbreviation for Compensation Log Record, the type of log record created when a transaction is
rolled back)


Therefore, if the replication data transmission is slow for some reason, the log file cannot be deleted and disk full may occur.


Replication give-up


If log files are not deleted due to a replication problem, the user can specify the maximum number of log files that can be kept in
replication to prevent disk full.


If the number of log files that have not been deleted exceeds this number, even if the replication data has not been transmitted, the
replication data is abandoned and the log file is deleted to prevent the disk to be full.


In this way, the phenomenon of deleting log files necessary for replication even though replication data is not transmitted is called
replication give-up.


Effect of give-up occurrence


When replication give-up occurs, data inconsistency between both active and standby servers may occur, resulting in serious problems.


How to prevent give-up


To prevent replication give-up, the user must ensure that network speeds that can affect replication performance are always stable.


In addition, in order to avoid give-up even in abnormal conditions such as power failure or network disconnection, consider the
worst-case and increase the value of the property so that give-up does not occur.


REPLICATION_MAX_LOGFILE = 400


The unit of this property means the number of log files, and if it is set to 400 as in the example above, if the number of log files that have
not been deleted currently is 400 or more, a replication give-up occurs.


Set whether to proceed with replication when give-up occurs (automatic)


The user can set how to restart the replication after a brief pause after exceeding the value set by the REPLICATION_MAX_LOGFILE
property.


REPLICATION_SENDER_START_AFTER_GIVING_UP = 1 (default)


If set to 0, the replication "restart SN" (that is, the value of the XSN column of the SYS_REPLICATIONS_ meta table) is initialized to -1,
and the replication is stopped. Then, the value of the IS_STARTED column of the SYS_REPLICATIONS_ meta table is changed to 0.


When set to 1, the value of "Restart SN" for replication is changed to the last (largest) SN of the current log file, and replication is
performed again from this "Restart SN".


Cycle


A check of whether a give-up needs to be performed is made when the checkpoint is performed.


This is because the log file is deleted at a checkpoint.


Check whether give-up has occurred


When give-up occurs, the give-up time is recorded in the replication meta table.


iSQL> set vertical on;

iSQL> select replication_name, is_started, give_up_time from SYSTEM_.SYS_REPLICATIONS_;

REPLICATION_NAME     : REP1

IS_STARTED        : 1

GIVE_UP_TIME       :

1 row selected.


REPLICATION_NAME : Replication name


IS_STARTED    : Whether the replication has started (start 1, stop 0)


GIVE_UP_TIME   : The date and time that the replicated was most recently given up.

### Replication monitoring query


Overall status of replication
Replication sender information
Replication receiver information
Replication gap


Overall status of replication


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
REP          192.168.1.149 (*)   0           9668         ON  ON


Column description







|Column<br>name|Description|
|---|---|
|restart_xsn|SN reflected by the remote server that is the target of replication, and the starting point for retransmission when the<br>replication is restarted|
|sender|Whether the sender is running or not|
|receiver|Whether the receiver is running or not|


The name of the replication, IP, sender status, and receiver status can also be checked.


Replication sender information


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


Column description

|Column name|Description|
|---|---|
|rep_name|Name of replication object|
|peer_ip|IP address of the replication target remote server|
|peer_port|Port number of the replication target remote server|
|Status|It is normal when the current state of sender is 1. / STOP(0), RUN(1), RETRY(2)|
|repl_mode|sender's current replication mode / lazy, eager|
|NET_ERROR_FLAG|network 에러 여부로 0이어야 정상이다. / OK(0), ERROR(1)|
|XSN|sender가 마지막으로 송신한 SN(Serial Number/리두로그일련번호)으로 v$repgap의 REP_SN과 동일|



The IP, port, network error, and status of the replication sender's remote server can also be checked.


Replication receiver information


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


Column description

|Column name|Description|
|---|---|
|peer_ip|IP address of the remote server as the subject of replication|
|peer_port|Port number of the remote server that is the subject of replication|
|apply_xsn|SN of the remote server currently being reflected by the receiver|



The IP and port of the remote server of the replication receiver can be checked.


Replication gap


set linesize 1024

set colsize 20

select rep_name

, rep_gap
from v$repgap;

REP_NAME       REP_GAP

---------------------------------------------
REP          0


Column description

|Column name|Description|
|---|---|
|rep_name|Name of replication|
|rep_gap|The degree of unsynchronization is indicated by the interval between rep_last_sn and rep_sn. (I.e. rep_last_sn-rep_sn)|



If the replication gap is increased by a lot, there are things to check.



1.

2.

3.



Check the network status (operation, failure, if IP or port is blocked by the firewall, etc.)
Check the remote requirement status (hardware failure, remote DB shutdown, etc.)
Check the BULK DML operation



In the above case, the replication gap may increase, so it is necessary to check the above cases.

## 04. Backup and Recovery

### How to recover cold backup by changing directory path


Overview

Version

How to change directory path
Directory path change procedure
Reference


Overview


This document describes how to recover by changing the directory path of major database files such as each data file inevitably after


Cold Backup.


Version


ALTIBASE HDB version 4 or later


How to change directory path


When restoring using Cold Backup database files, if there is no change in the directory path, copy (cp) mydb* (memory db), *.dbf (disk
db), logs, and loganchor to the corresponding directory, and then when starting B, DB can be restored to the point of backup.


However, if the directory must be renamed inevitably, it is resolved by changing the directory path of each database file (memoryDB,
logs, loganchor) and copying the file to the changed directory, but the disk DB must perform the renaming of the data file at the control
stage.


Directory path change procedure


1. Create the desired directory and copy the Cold Backup files.


Copy Cold Backup (mydb*, *.dbf, logs, loganchor) to the desired directory using the OS copy command.


2. Modify $ALTIBASE_HOME/conf/altibase.properties.


..Omitted

MEM_DB_DIR     = /home/cheol2/altibase_home/dbs # Memory DB Directory

DEFAULT_DISK_DB_DIR =/home/cheol2/altibase_home/dbs # Disk  DB Directory

LOGANCHOR_DIR    =/home/cheol2/altibase_home/logs # LOGANCHOR_DIR1 // 로그앵커
LOGANCHOR_DIR    = /home/cheol2/altibase_home/logs # LOGANCHOR_DIR2
LOGANCHOR_DIR    = /home/cheol2/altibase_home/logs # LOGANCHOR_DIR3

LOG_DIR = /home/cheol2/altibase_home/logs # Redo log file directory
ARCHIVE_DIR  = /home/cheol2/altibase_home/logs # Archive directory

..Omitted


3. Startup at the Control stage.


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


4. Rename datafile in ISQL. (Change directory path)


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


5. Startup in ISQL.


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


Reference


More detailed information can be found in the Table of Contents of the General Reference Manual.


### Online Backup and Time Based Recovery

Overview

Version

Online backup procedure
Time based recovery
Reference


Overview


This section explains how to perform Online Backup and Time Based Recovery, which can be performed when the Altibase server is
operated in archive log mode.


Online Backup is not possible except in Archivelog Mode.


Version


ALTIBASE HDB version 4 or later


Online backup procedure


1. Online backup is possible only when the DB is running in the archive mode, and the procedure to check and change the archive mode
is as follows.


A. How to check Archivelog mode


iSQL> select ARCHIVE_MODE from v$archive;ARCHIVE_MODE

----------------------
0            // 0: Archive_mode not used, 1: Archive mode used


B. How to change Archive mode


The Archive mode cannot be changed while online and can be changed at the Control stage after DB shutdown.


After connecting to sysdba mode, start-up in the Control stage and change to Archive mode.


[cheol@as48-x64 ~]$ is -sysdba
iSQL(sysdba)> startup control;
Connecting to the DB server...

Connected.TRANSITION TO PHASE : PROCESS

TRANSITION TO PHASE : CONTROL

Command execute success.

2) Change to Archivelog mode
iSQL(sysdba)> alter database archivelog;Alter success.


2. Procedure to perform Online Backup when DB is operating in Archivelog Mode


A. Database Online Backup by database system


A. Database Online Backup by database system


1) Database unit online backup


iSQL> alter database backup database to '/backup'; // The backup directory can be arbitrarily changed.


The following files are copied to the /backup directory.


SYS_TBS_MEM_DIC-0-0

SYS_TBS_MEM_DATA-0-0

system001.dbf
system002.dbf

undo001.dbf

loganchor0
loganchor2
loganchor1


2) In case of online backup for a specific tablespace unit


iSQL(sysdba)> alter database backup tablespace SYS_TBS_MEM_DIC to ‘/backup_dir’; // A stable version of
the SYS_TBS_MEM_DIC data files is backed up online to the /backup_dir directory.
$ ls /backup_dirSYS_TBS_MEM_DIC-0-0


3) Log anchor online backup


iSQL(sysdba)> alter database backup loganchor to ‘/backup_dir’; // All log anchor files are backed up online
to the /backup_dir directory.
$ ls /backup_dir
loganchor0 loganchor1 loganchor2


B. Online backup by DBA


1) Online backup by tablespace


Ex) Online backup of data files of USER_MEMORY_TBS and USER_DISK_TBS tablespaces in /backup_dir.


Ex) Online backup of data files of USER_MEMORY_TBS and USER_DISK_TBS tablespaces in /backup_dir.


The memory tablespace data file is backed up online after confirming that it is a stable version of the data file.


iSQL(sysdba)> alter tablespace USER_MEMORY_TBS begin backup;
iSQL(sysdba)> select * from v$stable_mem_datafiles;

MEM_DATA_FILE

-------------------------------------------------
/altibase_home/dbs/USER_MEM_TBS-0-0 // stable version

$ cp $ALTIBASE_HOME/dbs/USER_MEMORY_TBS-0-0 /backup_dir/

iSQL(sysdba)> alter tablespace USER_MEMORY_TBS end backup;
iSQL(sysdba)> alter tablespace USER_DISK_TBS begin backup;

$ cp $ALTIBASE_HOME/dbs/USER_DISK_TBS.dbf /backup_dir/

iSQL(sysdba)> alter tablespace USER_DISK_TBS end backup;

$ ls /backup_dir

USER_MEMORY_TBS-0-0 USER_DISK_TBS.dbf


2) Finishing online backup by DBA


Commands to force archive log files related to the backup must be executed so that even if the current log file is not used up, it is
instructed to close it and continue logging to the next log file.


iSQL(sysdba)> ALTER SYSTEM SWITCH LOGFILE;


Time based recovery


It is operating in Archivelog Mode and is a recovery procedure when online backup (or cold backup) for the entire DB is performed more
than once before the desired recovery point.


Ex) The tablespace USER_DISK_TBS was deleted by mistake. (July 23, 2015 14:11)


Database recovery procedure to the state of 10 minutes before the tablespace existed


At the last backup, the entire DB was backed up as follows.


iSQL(sysdba)> ALTER DATABASE BACKUP DATABASE TO ‘/backup_dir’;


A. Copy the data files of all disk tablespaces of the backed up database to the original location of the data files.


$ cp /backup_dir/*.dbf $ALTIBASE_HOME/dbs
$ cp /backup_dir/SYS_TBS_* $ALTIBASE_HOME/dbs


B. Check the archive log files required for recovery and copy and use the backed up log anchor files.


1) Check the archive log files required for recovery


iSQL(sysdba)> select last_deleted_logfile from v$lfg;

LAST_DELETED_LOGFILE

-----------------------
15021        // Archive log file number required for recovery


In the altibase_sm.log file created in the $ALTIBASE_HOME/trc directory, check the files that were forcibly archived when the backup was
completed.


[2015/07/23 13:59:59] [Thread-6] [Level-9]Waiting logfile15341 to archive //Forced archived file number,
i.e. logfile15021 ~ logfile15341 files are required for recovery.


2) Copy the backed up log anchor file


$ cp /backup_dir/loganchor* /ALTIBASE_HOME/logs;


3) Because the SYS_TBS_DISK_TEMP tablespace is not backed up, create a new one.


iSQL(sysdba)> ALTER DATABASE CREATE DATAFILE ‘temp001.dbf’


4) Perform incomplete media recovery.


iSQL(sysdba)> ALTER DATABASE RECOVER DATABASE UNTIL TIME '2015-07-23:14:01:00';


Since the incomplete media recovery has performed, the resetlogs option must be used while going to the meta startup stage.


iSQL(sysdba)> ALTER DATABASE mydb META RESETLOGS;


5) Since the server was started and the log was reset, the entire database was backed up.


iSQL(sysdba)> ALTER DATABASE mydb SERVICE;
iSQL(sysdba)> ALTER DATABASE BACKUP DATABASE TO ‘/backup_dir’;


Reference


More detailed information can be found in the Table of Contents of the Admin Manual > Backup and Recovery cases.


### Using aexport and iloader

This document how to download database objects and data in a text file that can be checked by the user using the aexport and iloader
utilities, and how to upload it as a downloadable file.


This document introduces the most basic and simplest form. Since aexport and iloader can be applied in various forms by using various
options, please refer to the following manual for necessary information.


iLoader User's Manual

Utilities Manual
Manual download page: http://support.altibase.com/en/manual/
Github: https://github.com/ALTIBASE/Documents/tree/master/Manuals/


Create database object and upload data


Database object and data upload procedure


Preparation before uploading data


Creating database object


Uploading data


Checking the data upload result


Checking the .sh running log


Checking log files for each table


Database object and data upload procedure


In order to restore all database objects and data, execute the following .sh files created when aexport is executed in order.


From 2. to 8., execute it in order.


1. run_il_out.sh      : [faq: iloader formout, data-out script ]     # This is a script for backing up data,
so it is excluded from this step.
2. run_is.sh        : [faq: isql table-schema script ]
3. run_il_in.sh       : [faq: iloader data-in script ]
4. run_is_refresh_mview.sh : [faq: isql materialized view refresh script ]
5. run_is_index.sh     : [faq: isql table-index script ]
6. run_is_fk.sh       : [faq: isql table-foreign key script ]
7. run_is_repl.sh      : [faq: isql replication script ]
8. run_is_job.sh      : [faq: isql job script ]


Each file contains isql commands that execute .sql files containing object creation statements.


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


Preparation before uploading data


Before restoring data, be sure to check the following environment variables before proceeding.


ALTIBASE_NLS_USE is required to prevent the breakdown of Korean data, and ILO_DATEFORM should be set to prevent duplication when
a date type column has a unique value.


ALTIBASE_NLS_USE
ILO_DATEFORM


In the session of executing iloader, it is applied by setting it with the export command as shown below or adding it to the user
environment configuration file (.bash_profile or .profile) and logging out and logging in.


How to set environment variables


$ export ALTIBASE_NLS_USE=Database server character set
$ export ILO_DATEFORM='YYYY/MM/DD HH:MI:SS.SSSSSS'


How to set environment variables


$ echo $ALTIBASE_NLS_USE
$ echo $ILO_DATEFORM


The ALTIBASE HDB server character set can be checked with the following statement: NLS_CHARACTERSET is the ALTIBASE server's
character set and NLS_USE is the client's character set. Hangul data is not broken only when these two are set identically.





Creating database object


When running the .sh file, the user should leave a log file to check for errors.


Uploading data


Data upload is performed using run_il_in.sh. In order to upload only a table owned by a specific user or only a specific table, the user
can extract only what the user wants from run_il_in.sh as follows.









If there are many tables or a lot of data, monitor upload.out to see if it is terminated.





Checking the data upload result


Checking the .sh running log


Whenever .sh is running, all logs are left to check whether it is normal or not through the log after running .sh.


Checking log files for each table


Execute the following commands to check if there is an error when uploading data.


$ grep -i err- upload.out                         # Check whether an error has occurred in the
result of running the run_il_int.sh script.

[ERR-311F4 : Invalid column name                     # If something starts with ERR- like this, it

means that an error has occurred.
$ ls -l *.fmt|wc -l                            # Check the number of tables
$ ls -l *.log|wc -l                            # Check the number of log files created by running

run_il_in.sh


$ cat *.log | grep 'Error Row Count' | awk -F: '{print $2}' | wc -l   # The number of these results should
match the number of the two results above. If it is different, it means that the error has occurred as many

times as the difference.


$ cat *.log | grep 'Error Row Count' | awk -F: '{print $2}' | sort -u  # If this result is 0, nothing has failed
when performing the upload.

0


Database object backup using aexport


Preparation before executing aexport


Change the values of the following settings in the aexport.properties file.


ILOADER_FILED_TERM
ILOADER_ROW_TERM


ILOADER_FIELD_TERM stands for field separator, and ILOADER_ROW_TERM stands for record separator.


If the aexport.properties file has never been changed, these settings are commented out and the defaults are set as follows.





If it is set as the default as above, it's a bit complicated, but change it as follows.


The location of the aexport.properties file is $ALTIBASE_HOME/conf. If this file does not exist, copy and use the
aexport.properties.sample file.


$ cd $ALTIBASE_HOME/conf
$ ls -l aexport.properties*
-rw-r-r- 1 heejung.lee heejung.lee 915 2014-07-21 15:32 aexport.properties.sample


$ cp -p aexport.properties.sample aexport.properties


When aexport is executed, the following scripts are created.


Database object creation script
Data download/upload script using iloader


The data download/upload script using iloader contains iloader commands. iloader can use several options, and the value used for the
option depends on the above setting.


The above setting means field separator and row separator, respectively, and the default values are simply set. If this setting value is
included in the character data type column, data may not be uploaded normally when uploading data.


Therefore, it is recommended to set this setting value rather complicated.


Executing aexport


Execute aexport after changing aexport.properties.


$ aexport

----------------------------------------------------------------
Altibase Export Script Utility.

Release Version 6.3.1.2.7

Copyright 2000, ALTIBASE Corporation or its subsidiaries.
All Rights Reserved.

----------------------------------------------------------------
Write Server Name (default:localhost) :     # Press enter when running locally, and enter IP when
connecting to a remotely installed Altibase server.
Write UserID :                  # Enter sys to back up all objects in the database, and enter
corresponding USER to back up objects of a specific user.
Write Password :                 # Enter USER's password


##### TBS #####


##### USER #####
** input user ALTITEST's password(default - same with USER_NAME):      # If sys is entered for UserID,
passwords of all users created in the database must be entered.
** input user USER1's password(default - same with USER_NAME): USER1     # Even if the user enters the
password randomly, a backup script is created, but if the password does not match during the actual iloader
backup, iloader will fail. Also, be aware that you are creating the create user ~identified by ~ syntax with the
password entered here.
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

When aexport is executed, .sh (.bat for Windows system) files and .sql files are created as follows. The .sql files contain the syntax for
creating database objects and are scripts that execute .sh files to .sql files at once.


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

Data download using iloader


Preparation for iloader
Performing backup

Download data for all tables in the database

Downloading data of a table belonging to a specific user
Downloading data for a specific table
Check the data download result


Check the run_il_out.sh execution log
Check log by table
Data download file


Preparation for iloader


Before executing the iloader, be sure to check the following environment variables before proceeding.


ALTIBASE_NLS_USE is required to prevent the breakdown of Korean data, and ILO_DATEFORM should be set to prevent duplication when
a date type column has a unique value.


ALTIBASE_NLS_USE
ILO_DATEFORM


In the session of executing the iloader, it is applied by setting it with the export command as shown below or adding it to the user
environment configuration file (.bash_profile or .profile) and logging out and logging in.


How to set environment variables





How to set environment variables


$ echo $ALTIBASE_NLS_USE
$ echo $ILO_DATEFORM


The ALTIBASE HDB server character set can be checked with the following sentence: NLS_CHARACTERSET is the ALTIBASE server's
character set and NLS_USE is the client's character set. Hangul data is not broken only when these two are set identically.
Error rendering macro 'code': Invalid value specified for parameter 'firstline'


iSQL> set linesize 1024;

iSQL> set colsize 20;
iSQL> select NLS_USE, NLS_CHARACTERSET from v$nls_parameters;
NLS_USE        NLS_CHARACTERSET

----------------------------------------------
MS949         MS949

1 row selected.


Performing backup


Use run_il_out.sh to backup table data.


$ ls --l run_il_out.sh

rw-rw-rw 1 eheejung eheejung 633 Nov 1 11:00 run_il_out.sh


Download data for all tables in the database


run_il_out.sh must be a file created after entering UserID as sys when executing aexport.
Run run_il_out.sh.





Downloading data of a table belonging to a specific user


In order to back up only tables owned by a specific user, use run_il_out.sh that aexport-ed to that user.


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

...Omitted...


$ cat run_il_out.sh

iloader -s localhost -u ALTITEST -p ALTITEST formout -f ALTITEST_ORDERS.fmt -T ORDERS


iloader -s localhost -u ALTITEST -p ALTITEST out -f ALTITEST_ORDERS.fmt -d ALTITEST_ORDERS.dat -log
ALTITEST_ORDERS.log


If aexport is executed by sys, it can extract only the user from run_il_out.sh and execute it.





Downloading data for a specific table


In order to download only specific tables, extract only the tables you want from run_il_out.sh and back them up.





Execute iloader formout and iloader out commands in sequence.


If there are many tables or a lot of data, monitor download.out to see if it is shutting down.





Check the data download result


Check the run_il_out.sh execution log


The run_il_out.sh run log is the file specified in the tee command.


$ sh run_il_out.sh | tee download.out


Check whether an error has occurred in the specified file as follows.


$ grep –i err- download.out

[ERR-311F4 : Invalid column name         # If something starts with ERR- like this, it means that an error

has occurred.

# Actions are required according to the situation, so if it is difficult to take
action directly after checking the error, contact us.


Check log by table


When run_il_out.sh is executed, log files in the form of DBUSER_TABLENAME.log are created. (Eg, ALTITEST_ORDERS.log in the altitest
user's orders table)
In these files, check for errors with the command below.


$ cat run_il_out.sh | grep fmt | wc -l                      # Check the number of tables in the

database

106


$ ls -l *.fmt | wc -l                               # Check the number of tables to be backed up
by the number of *.fmt files.

106


$ cat *.log | grep 'Error Row Count' | awk -F: '{print $2}' | wc -l       # If the number of Error Row
Count occurrences is different from the number of .fmt files, it means that an error occurred in a specific table
by the number of differences.
106                                        # Open the run_il_out.sh execution log
(download.out) and search by table name to check.


$ cat *.log | grep 'Error Row Count' | awk -F: '{print $2}' | sort -u      # If the result is only 0, there is
no download failure in DBUSER_TABLENAME.log.

0                                         # If there is a non-zero result, the user need to

look for that table and find the cause with the .log and .bad files.


Data download file


The backup file created by running run_il_out.sh is created in USERNAME_TABLENAME.dat format.


$ ls -l *.dat

-rw-rw-rw- 1 heejung.lee heejung.lee 12457 2014-11-19 15:03 ALTITEST_ORDERS.dat


$ ls -l *.dat | wc -l                               # Tthe backup result can be checked once
again by comparing the number of backup files with the number of tables.


$ ls -l ALTITEST_ORDERS*                             # .Dat, .fmt, .log files are created for

each table.

-rw-rw-rw- 1 heejung.lee heejung.lee  0 2014-11-19 15:03 ALTITEST_ORDERS.dat
-rw-rw-rw- 1 heejung.lee heejung.lee 210 2014-11-19 15:03 ALTITEST_ORDERS.fmt
-rw-rw-rw- 1 heejung.lee heejung.lee 169 2014-11-19 15:03 ALTITEST_ORDERS.log


What is aexport, iloader?


aexport


aexport is a utility that creates scripts that can download object creation scripts and data from the database as text files.


The database objects that aexport can extract are as follows:


Database user

User privilege
Tablespace
Table

Table constraint

Index

View
Materialized view (Provided starting from ALTIBASE HDB 6.3.1)
Stored procedure
Replication object


It is recommended that aexport be performed whenever there is a database object change.


iloader


iloader is a utility that allows you to download or upload database data in table units. The data is saved in a text file that can be viewed
by the user.


This can be used for database migration or table-by-table backup purposes.


To back up table data using iloader, a form file and various options are required. If aexport is executed, the iloader execution command
is created as a script.

## 05. SQL

### Comparison between VARCHAR and CHAR types


Overview

Version

Comparison between VARCHAR and CHAR types


Overview


This is a comparison between varchar type and char type.


Version


Applicable to all versions of Altibase.


Comparison between VARCHAR and CHAR types


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


In the case of char type, 0x20 is added and compared based on the larger length when comparing, and when comparing char and
varchar, the comparison is performed based on the valid data of varchar (position of 0x00).


Sometimes, when SESC coding, variables are initialized to 0x00 for varchar and 0x20 for char. There are rules above, so it is better to
initialize them to 0x00.

### How to check the privileges granted to an object


Overview

Version

How to check


Overview


DB users can grant privileges to objects using the grant statement. the user can search the relationship of object authority between DB
users granted to the entire DB by using a query.


Version


Available in all versions of ALTIBASE HDB 4.3.9 or later


How to check


It can be searched with the query below.


SELECT a.user_name grantee,                   -- User grantee
c.user_name grantor,                   -- User grantor
f.user_name object_owner,                -- Owner of the object
e.table_name object_name,                -- Name of object
e.table_type object_type,                -- Type of object
replace(d.priv_name, '_', ' ') priv_name,        -- Name of privilege
decode(b.with_grant_option, 0, 'NO', 'YES') grantable  -- Whether it is possible to
re-grant the rights to the object
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


## 06. Stored Procedure

### How to check the contents of stored procedure

Overview

Version

How to check


Using meta table
Using the aexport utility


Overview


This document describes how to check the contents of the stored procedure.


Version


All the versions of ALTIBASE HDB


How to check


There are two ways to check the contents of the stored procedure.


Use meta table

Use aexport utility


Using meta table


After creating a user-defined procedure using the meta tables SYSTEM_.SYS_PROCEDURES_, SYSTEM_.SYS_PROC_PARSE_, use this to
check the contents of the stored procedure.


How to create a custom procedure


Stored Procedure for User-Defined Function Output


-- Output stored procedure and user-defined function names to the screen.

-- EXEC showProcedures;

CREATE OR REPLACE PROCEDURE showProcedures

AS

CURSOR C1 IS

SELECT U.USER_NAME, PROC.PROC_NAME,
DECODE(PROC.OBJECT_TYPE, 0, 'PROCEDURE', 1, 'FUNCTION')

FROM SYSTEM_.SYS_PROCEDURES_ PROC, SYSTEM_.SYS_USERS_ U

WHERE PROC.USER_ID = U.USER_ID;
V1 CHAR(40);
V2 CHAR(40);
V3 CHAR(20);

BEGIN

SYSTEM_.PRINTLN('---------------------------------------------------------------------------------------------------');
SYSTEM_.PRINT(' USER_NAME                PROC_NAME');
SYSTEM_.PRINTLN('                PROCEDURE/FUNCTION');

SYSTEM_.PRINTLN('---------------------------------------------------------------------------------------------------');

OPEN C1;

LOOP

FETCH C1 INTO V1, V2, V3;

EXIT WHEN C1%NOTFOUND;
SYSTEM_.PRINT(' ');
SYSTEM_.PRINT(V1);
SYSTEM_.PRINT(V2);
SYSTEM_.PRINTLN(V3);

END LOOP;

SYSTEM_.PRINTLN('---------------------------------------------------------------------------------------------------');

CLOSE C1;

END;

/


Stored procedure to check the contents of the stored procedure


-- Output the contents of the specified stored procedure on the screen.
-- EXEC showProcBody('USER_NAME', 'PROCEDURE_NAME');
CREATE OR REPLACE PROCEDURE showProcBody(p1 IN VARCHAR(40), p2 IN VARCHAR(40))

AS

CURSOR C1 IS

SELECT SYSTEM_.SYS_PROC_PARSE_.PARSE

FROM SYSTEM_.SYS_PROC_PARSE_
WHERE SYSTEM_.SYS_PROC_PARSE_.PROC_OID = (SELECT P.PROC_OID

FROM SYSTEM_.SYS_PROCEDURES_ P,

SYSTEM_.SYS_USERS_ U

WHERE U.USER_ID = P.USER_ID

AND P.PROC_NAME = p2
AND U.USER_NAME = p1)

ORDER BY SYSTEM_.SYS_PROC_PARSE_.SEQ_NO;
V1 VARCHAR(4000);

BEGIN

OPEN C1;
SYSTEM_.PRINTLN('---------------------------------');
SYSTEM_.PRINT(P1);
SYSTEM_.PRINTLN(' PROCEDURE');
SYSTEM_.PRINTLN('---------------------------------');
SYSTEM_.PRINTLN('');

LOOP

FETCH C1 INTO V1;

EXIT WHEN C1%NOTFOUND;
SYSTEM_.PRINTLN(V1);

END LOOP;

CLOSE C1;

SYSTEM_.PRINTLN('');
SYSTEM_.PRINTLN('---------------------------------');

END;

/


How to Execute user-defined stored procedure


Check the list of stored procedures and user-defined functions


iSQL> exec showProcedures;


Check the contents of the stored procedure


iSQL> exec showProcBody('USER NAME' 'PROC NAME');


Using the aexport utility


aexport is a utility that saves database object creation statements to a file. After performing aexport, the contents of the stored
procedure can be checked in the created file.


Execute aexport - all objects


The creation statement of all stored procedures can be checked in ALL_CRT_PROC.sql among the files created after executing
aexport.


$ aexport





Execute aexport for each user


If the user executes aexport after entering the database user name in the -u option of aexport and the password of the user in
the -p option, only the object schema owned by the user is extracted.
For the stored procedure information, refer to the ALL_CRT_PROC.sql file.
How to execute


$ aexport -u user_name -p user_password -s Altibase_Server_IP

Or,

$ aexport
Write Server Name (default:127.0.0.1) :   # Enter the Altibase server IP

Write UserID :      # Enter the object owner or sys user. Whatever is typed, the result is the same.

Write Password :    # Password of the user entered above


Execute aexport for each object


The object option allows extracting only specific object schemas. This option is available as of ALTIBASE HDB version 5.5.1 or
later.

For stored procedures, values can be given in the format -object user name.procedure name.
As a result, a file with a name in the form of user name_procedure name_CRT.sql is created.
How to execute


$ aexport -s Altibase_Server_IP -u user_name -p user_password -object
user_name.procedure_name

또는

$ aexport -object user_name.procedure_name
Write Server Name (default:127.0.0.1) :    # Enter the Altibase server IP

Write UserID :      # Enter the object owner or sys user. Whatever is typed, the result is the same.

Write Password :    # Password of the user entered above

### How to check the number of records affected by DML within the stored procedure


Use SQL%ROWCOUNT to find out how many records were affected by DML.






IE users

Copying the procedure creation statement in IE may create a blank space, so please use the attached file if necessary.
SP_DML_RECORD_COUNT.txt

## 07. Development and API

### Connection disconnection, error codes, and error messages in each case (APRE*C/C++, SQLCLI)


Overview

Version

When the connection is disconnected from the application program
How to check error codes and error messages for each application program
Connection error state and error message
Conclusion


Overview


This document describes the cases where the connection is disconnected in the application program and the error codes and messages
in each situation.


Version


This document is written based on ALTIBASE HDB version 6.3.1.
For additional information or updates, please leave a request at http://support.altibase.com/en/ or leave a comment on this

page.


When the connection is disconnected from the application program


In the following situations, the connection is not established.



1.

2.

3.

4.


5.

6.



It is not connected

Communication socket error or disconnection from the server-side
If a previously disconnected connection was not detected (if the connection was previously disconnected)
If it is disconnected by timeout
There are Query Timeout, Fetch Timeout, UTrans Timeout, and Idle Timeout. In the case of Query Timeout, the connection is not
disconnected, but in all other cases, the connection is disconnected.
When the DB Server is shutdown
If the connection is not possible because the DB server is shutdown (Connect failure)



How to check error codes and error messages for each application program


If the application program is written in ALTIBASE Embedded SQL (APRE*C/C++), the values that can be checked are as follows.



1.

2.

3.

4.



sqlca.sqlcode (query execution return value - SQL_SUCCESS, SQL_ERROR, etc)
sqlca.sqlerrm.sqlerrmc (error message)
SQLCODE (error code)
SQLSTATE (state code)



If the application is written in SQLCLI the following values can be checked


If the application is written in SQLCLI, the following values can be checked.


It can be checked by calling SQLError(env,dbc,stmt,state,err,msg,msgMax,msgLength).



1.

2.

3.



state (state code)
err (error code)
msg (error message)



Connection error state and error message



1.


2.



In case of not connecter or previously disconnected


[APRE*C/C++]

====================================================

sqlca STRUCTURE
.sqlcode [-2] (SQL_ERROR)
.sqlerrm.sqlerrmc The connection does not exist. (Name:default connection)
SQLCODE [-2]
SQLSTATE ["08003"]

====================================================


[SQLCLI/ODBC]

1. In case of haven't connected

====================================================

return value [-2]
SQLError(env,dbc,stmt,state,err,msg,msgMax,msgLength)
error state (state) [""]
error number (err) [0] in Hex(0)
error message (msg) [ ?]

====================================================

2. In case of disconnected before

====================================================

return value [-1] (SQL_ERROR)
SQLError(env,dbc,stmt,state,err,msg,msgMax,msgLength)
error state (state) ["08003"]
error number (err) [331830] in Hex(51036)
error message (msg) [Connection does not exist (err8)]

====================================================


In case of the connection is disconnected (the server disconnection or a network error)


3.


4.




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


In case of the query was executed again without detecting that the connection was previously disconnected.


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


In case of disconnection by Timeout
Fetch Timeout, UTrans Timeout, Idle Timeout all return the same error. (Timeout is recorded in altibase_boot.log.)


5.


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


In case of the DB server is shutdown


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


Connection failure


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


Conclusion


As a result of checking the error code for each situation, there are 3 cases as follows.


    - SQLSTATE(state) ["08001"] SQLCODE [1(0x01)] errno [32770(0x050032)]
Connection failure

    - SQLSTATE(state) ["08003"] SQLCODE(errno) [331830(0x051036)]
In case of not connected (after disconnection)
In case the connection is already disconnected

    - SQLSTATE(state) ["08S01"] SQLCODE(errno) [331843(0x051043)]
Socket disconnection

In case of interruption due to timeout
In case of the server being shutdown

### How to manage Spring+iBatis transaction


Overview

How to manage
Detailed description

Common application
1-1. When using DataSourceTransactionManager directly
1-2. When to use TransactionTemplate
2-1. Method using <tx:advice> tag
2-2. Method using TransactionProxyFactoryBean tag
2-3 Method using the @Transactional annotation
Reference

Sample code


Overview


This document describes how to manage Spring+iBatis transactions.


How to manage


1. Bean Managed Transaction (BMT), explicit transaction management (how to consider transaction processing in the source)


1-1 When directly using DataSourceTransactionManager


1-2 When using TransactionTemplate


2. CMT (Container Managed Transaction), declarative transaction management (using a configuration file and reducing consideration for
transaction processing in the source)


2-1 Method using <tx:advice> tag


2-2. Method using TransactionProxyFactoryBean tag


2-3 Method using the @Transactional annotation


Detailed description


Common application





1-1. When using DataSourceTransactionManager directly


Configuration file: There is no additional configuration.
Commit and rollback are processed directly on the source.
SetAutoCommit(false) must be called in order to process as a transaction.
Note that setAutoCommit(false) must be called when selecting blobs.


1-2. When to use TransactionTemplate


Configuration file


<bean id="transactionTemplate"
class="org.springframework.transaction.support.TransactionTemplate">
<property name="transactionManager"><ref local="transactionManager"/></property>
</bean>


<bean id="xxxService" class="…">

<property name="transactionTemplate"><ref local=" transactionTemplate"/></property>
</bean>


The user must use functions such as transactionTemplate.execute() and doInTransaction() on the source.
Note that when selecting blobs, Oracle did not process transactions, but when using Altibase, the user must use functions such
as transactionTemplate.execute() and doInTransaction() on the source to process transactions.


2-1. Method using <tx:advice> tag


Configuration file


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


There is no need for transaction-related code on the source.


2-2. Method using TransactionProxyFactoryBean tag


Configuration file


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


There is no need for transaction-related code on the source.


2-3 Method using the @Transactional annotation


Configuration


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


Classes that require transactions on the source require @Transactional(propagation=Propagation.REQUIRED) notation.


Reference


If AltibaseClobStringTypeHandler is applied guided by the standard framework, an error may occur when CLOB is 0 byte.
In this case, the user can check that it is normally searched by adding annotations without using TypeHandle.


Sample code


Sample code for handling LOB data.


LobSpringIbatisSample.zip

### JDBC


How to change the jdbc.trc file creation location


Creation time and usage
Version

Creation location

How to change the creation path


Creation time and usage


The jdbc.trc file is a log file created for JDBC-related traces, and is automatically generated when the JDBC driver is initialized.


If fail-over is specified in the connection URL, it is also used for event trace when fail-over occurs.


If fail-over is not specified in the connection url, or fail-over does not occur, it is 0 byte to the default value.


File size varies slightly from platform to platform.


When one Java program is executed at the same time, as many as the number of executions are created,


jdbc.trc
jdbc.trc.lck
jdbc.trc.1
jdbc.trc.1.lck
jdbc.trc.2
jdbc.trc.2.lck


When connecting each connection object separately in a single Java program, the jdbc.trc file is shared and used.


Version


The jdbc.trc file is created for JDBC-related traces from ALTIBASE HDB version 5.5.1 or later.


Creation location


If the ALTIBASE_HOME environment variable is set in the client environment, it is created in $ALTIBASE_HOME/trc,
If the ALTIBASE_HOME environment variable is not set, it is created in the location where the Java program is executed.


Sometimes, if the user does not have write permission in the directory where the jdbc.trc file is created, the following error may occur in
the application due to file creation failure.


java.io.IOException: Couldn't get lock for /opt/altibase-HDB-server-6.1.1/trc/jdbc.trc


If the above error occurs, give permission to the directory or set the ALTIBASE_HOME environment variable to an appropriate location.


How to change the creation path

|ALTIBASE HDB Version|How to change the jdbc.trc log creation location|
|---|---|
|version 6.1.1.1.3 or earlier|Not available|
|version 6.1.1.1.4   ~  6.1.1.1.7|Can be set as an option when running java<br>java -DALTIBASE_JDBC_TRCLOG_DISABLE=true|
|version 6.1.1.1.8 or later|Set option when running java<br>java -DALTIBASE_JDBC_TRCLOG_DISABLE=true<br>Or<br>Set as an environment variable of the java execution user<br>exportALTIBASE_JDBC_TRCLOG_DISABLE=true|



How to use Fail-Over in Altibase JDBC


Overview

Glossary of terms
Fail-over related connection properties
Example
Reference


Overview


When a failure occurs while operating the database system, it provides a fail-over function and overcomes a failure and so that the
service can be continued.


This section describes the functions and usage of Altibase JDBC Fail-Over.


Glossary of terms


CTF (Connection Time Fail-Over): When a failure is detected at the time of accessing the DBMS, thㅅis refers to retrying the
connection to the DBMS of another available node.


If the AlternateServer property is set in the Connection String, CTF operates by default.
An application usually should try to connect again.
In the form of maintaining a connection pool like WAS, it can be performed automatically through the connection
validation setting of WAS.
STF (Service Time Fail-Over): When a failure is detected while the DBMS is processing a client's request, this refers to
reconnecting to the DBMS of another available node.

Since the success or failure is returned as an error after executing only the connection, user coding to proceed from the


preparation of the statement again must be followed.
Primary Server: This refers to the server information specified at the first in the Connection URL.
Alternative Server: This refers to the information of servers specified in AlternateServer connection properties.
Explicit Connection: This refers to when calling the connect method of the Connection object.
Implicit Connection: This refers to when the connect method fails or STF occurs, and JDBC internally retries the connection to
the DBMS of another available node.


Fail-over related connection properties


- Case insensitive.


AlternateServer: It refers to alternate servers and is described in (IP1:Port1, IP2:Port2,...) format.

Alternate servers can be the connection target server in the following cases depending on the settings of LoadBalance
and SessionFailOver.


When calling the connect method
When attempting to reconnect due to a failure of the connect method
When attempting to reconnect due to STF occurrence
ConnectionRetryCount: Set the number of retry attempts to connect to the same server.
ConnectionRetryDelay: Waiting time for connection attempts to the same server. The unit is seconds.
Note) ConnectionRetryCount and ConnectionRetryDelay properties are applied only for internal connection, and if it fails after
executing ConnectionRetryCount * ConnectionRetryDelay, it tries to connect to another available server in the same way.
LoadBalance: When connecting to DBMS, set the order of connection attempts between the primary server and the alternate

server.


When set to ON, it tries to connect randomly between the default server and the alternate server.
If it is set to OFF, it tries to connect from the primary server, and if it fails, it tries to connect to the alternate server in the
order listed.

This setting is for both explicit and internal connections.
SessionFailOver: Whether to perform STF or not.

When set to ON, it operates as CTF+STF.
When set to OFF, only CTF operates.
FailOver_Source: When performing a failover, specify the description of the failover source delivered to the server. This
information is stored in the FAILOVER_SOURCE column of the V$SESSION performance view.
HealthCheckDuration: Altibase JDBC maintains a list of available servers for failover. Upon failover, it tries to reconnect to the
servers in the available server list. This is to prevent all servers from attempting to connect in an infinite loop in a failure situation.

The HealthCheckDuration property specifies the wait time for the server on which the failover occurred to be set back to
the list of available servers.

When a failover occurs, the server is removed from the list of available servers and added back to the list of available
servers after the HealthCheckDuration time elapses. The unit of this property is seconds.


Example


When writing a program, refer to the following example.


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


Reference


Replication Manual -> Chapter 4 FailOver
JDBC User's Manual


Chapter 1 Getting Started with JDBC -> Connection Information
Chapter 3 Advanced Features -> JDBC and FailOver


JBOSS Integration Guide for Altibase

### ODBC


32-bit ODBC installation on 64-bit Windows


Overview

Version

Altibase ODBC installation

ODBC Setting


Overview


This document describes how to set up 32-bit ODBC driver on Windows Server 2003 64-bit systems.


Version


~ Altibase 6.5.1


Altibase ODBC installation



1.


2.



Download the Windows Altibase 32-bit client installation file or the Altibase 32-bit ODBC installation file.
Download: http://support.altibase.com/en/product
Client installation file name example: altibase-HDB-client-x.x.x.x.x-WINDOWS-X86-32bit-release.exe
ODBC installation file name example: altibase-HDB-ODBC-x.x.x.x.x-WINDOWS-X86-32bit-release.exe


Install the Windows Altibase 32-bit client.

For the installation method, refer to 2. Product Installation Using Package Installer -> ALTIBASE HDB Client Product Installation
in Windows in the Installation Guide manual.
Manual download: http://support.altibase.com/en/manual



ODBC Setting



1.



Run the data source manager for 32-bit ODBC.
Double-click C:\windows\sysWOW64\odbcad32.exe.


2.


3.



Create a new data source
Click the 'Add' button in the user 'DSN tab' of the ODBC Data Source Administrator window to open the Create New Data Source
window.
Select the Altibase 32-bit ODBC driver and click 'Finish'.


When the 'Altibase Connection Config' window appears, enter the Altibase server connection information.


4.




- Windows DSN Name

Enter a custom name for the data source.

- host (name or IP)
Enter the IP of the Altibase server.

- Port (default 20300)
Enter the service port of the Altibase server
Check the value of PORT_NO in the altibase.properties file (Altibase server properties file) or the value of the
ALTIBASE_PORT_NO environment variable on the Altibase server.

- User

Enter the database user name.

- Password
Enter the database user password.

- Database

Enter the database name.
The database name can be checked with SELECT_DB_NAME FROM V$DATABASE;

- NLS_USE

Enter the Altibase server character set.
The Altibase server character set can be checked with NLS_CHARACTERSET FROM V$NLS_PARAMETERS;


Click the Test Connection button to check the connection.


5.



Check the Altibase DSN added to the User DSN tab.



Integrating with unix_odbc


Overview

Version

UNIX ODBC type and URL
INSTALL

PHP, PERL Integration
PHP Integration Guide


Overview


This document is for integrating Altibase with UNIX_ODBC.


Version


All the versions of ALTIBASE HDB


UNIX ODBC type and URL


unix_odbc is an open source project, and unixODBC is mainly used.



1.



unixODBC can be downloaded from the link below:

- http://unixodbc.org/



INSTALL


prefix: The path to install unixODBC
enable-gui: Whether to build GUI ODBC Administrator
enable-threads: The default is "yes" if thread-support is found on the machine. All modern Linuxes will have pthreads support
in glibc so it is probably best to leave this to default.


If the enable-threads option is set to no, the following error may occur when testing the connection with isql.
$ ./isql Altiodbc
./isql: symbol lookup error: /home/wonsik/altibase_home/lib/libaltibase_odbc-64bit-ul64.so: undefined symbol:
pthread_sigmask
$ ./isql Altiodbc
./isql: symbol lookup error: /home/wonsik/altibase_home/lib/libaltibase_odbc-64bit-ul64.so: undefined symbol: pthread_sigma
sk


PHP, PERL Integration


PHP, PERL, etc. support unix_odbc, so it can be integrated with Altibase in the above way.


PHP Integration Guide



1.


2.


3.


4.



Modify unixODBC's odbc.ini file


It can be set to process lob data by adding LongDataCompat=ON to the odbc ini file


PHP compilation and installation operation



Setting related environment variables





Check SQLLEN, SQLULEN






5.



php.ini settings





ODBC function, SQLFreeStmt


Overview

Version

SQLFreeStmt options


Overview


This document describes how to use the ODBC function and SQLFreeStmt.


Version


This document is written based on ALTIBASE HDB version 6.3.1
For additional information or updates, please leave a request at http://support.altibase.com/en/ or in a comment section on this

page.


SQLFreeStmt options


The following four options are described.

|SQL_CLOSE|Close the cursor associated with stmt and discard all pending results. The application can reopen this cursor<br>later by executing the SELECT statement again using the same or different variables. If no cursor is open, this<br>option has no effect on the application.|
|---|---|
|SQL_DROP|The resources associated with the input statement handle are dropped and the handle is invalidated. If there is<br>an open cursor, it is closed and all pending results are discarded.|
|SQL_UNBIND|All rows bound by the previous SQLBindCol() call on this statement handle are dropped.|
|SQL_RESET_PARAMS|All parameters set by the previous SQLBindParameter() call on this statement handle are dropped. The<br>association between the application variable or file reference and the SQL statement parameter marker in the<br>statement handle is broken.|



Among these, SQL_CLOSE and SQL_DROP are mainly used.



1.


2.

### PHP



SQLFreeStmt(stmt, SQL_DROP):
This means that the resources for the prepared stmt (statement handle) are completely freed.
That is, it only calls when that stmt is not being reused.
SQLFreeStmt(stmt, SQL_CLOSE):
If all the retrieved data have not been fetched, an error will occur if you execute SQLExecute again without
SQLFreeStmt(SQL_CLOSE).
If SQLFreeStmt(stmt, SQL_CLOSE) is used, the existing stmt can be used without doing SQLAllocStmt().



Hangul is broken when using php


Situation

PHP execution structure

Main Cause

Setting NLS_USE in ODBC settings

Korean language support code setting in terminal window
Setting the maximum length set for a variable in PHP config


Situation


When searching Korean on a web page using PHP, Korean characters may be broken.


This document describes the causes and solutions for this situation.


PHP execution structure


The ALTIBASE HDB DB can be accessed with ODBC API from PHP page using the odbc driver manager unixODBC (http://www.unixodb

c.org/) and odbc driver provided by ALTIBASE.


For information on how to connect ALTIBASE and PHP, refer to 『Integration Guide for Altibase』.


Main Cause


Hangul is broken can be caused by configuration problems in various parts such as web server configuration, PHP configuration,
unixODBC configuration, etc. First, you must first check that the DB result including Hangul is displayed normally in unixODBC.


Use the $UNIXODBC_HOME/bin/isql utility provided by unixODBC to execute a query on the DB and check if the query results including
Korean characters are displayed normally, and then check the PHP setting.


After that, the last step is to check the web server setting or web page setting to make sure there is no problem with the character set
setting related to Korean.


Setting NLS_USE in ODBC settings


In odbc.ini, the unixODBC setting, there is an NLS_USE setting that specifies the client character set used for connection to the DB. If
this setting value and the character set setting of the DB does not match, there may be a problem with the Korean language output.


This property must be set to the same value as the DB character set.


Korean language support code setting in terminal window


Even though data is normally imported from the DB, if the terminal window that outputs it does not support the output of the Korean
character set, the Korean language may not be displayed properly.


If the DB character set is set to UTF8, the code page (chcp command) must be set so that Unicode can be displayed in the window
command window. Otherwise, Korean characters will not be displayed normally.





When a program such as Secure CRT, a commonly used terminal access program, also outputs UTF8 Korean characters, the Korean
should be properly set during the session set to display Korean characters.


Setting the maximum length set for a variable in PHP config


If the php program is running, varchar or clob data with large data may be broken or the same data may appear repeatedly. If there is a

problem with data output from a specific part, the user should look at the odbc configuration part.


If it happens as above, change the odbc.defaultlrl value in php.ini so that all data can be included.


For example, if the column is varchar(65536), data may be output incorrectly by default odbc.defaultlrl = 4096.


If if it changed to odbc.defaultlrl = 65536, it can be confirmed that data normally output up to 64KByte.


Generally, php.ini is under /etc, but this may vary depending on the configuration.

## 08. Monitoring

### Disk table and index usage


Overview


Overview


This document summarizes disk table and index usage retrieve queries by version.


The user can use the following two methods for disk table usage. This page provides queries using v$segment(x$segment).


v$segment: A method of calculating physical pages while full-scanning a table
v$usage: A sampling method using statistical information


ALTIBASE HDB 4.3.9.x


Overview

Disk table usage query
Disk index usage query
Reference - How to check the number of disk tables and indexes


Overview


This is an ALTIBASE HDB version 4.3.9 of the disk table and index usage query.


This query can also be used in ALTIBASE HDB version 5.1.1.


Disk table usage query






Disk index usage query






Reference - How to check the number of disk tables and indexes









ALTIBASE HDB 5.1.5.x


Overview

Disk table

Disk Index

Reference - How to check the number of disk tables and indexes


Overview


This is a disk table and index usage query for ALTIBASE HDB version 5.1.5.
In ALTIBASE HDB 5, due to a change in the structure of the disk table, only the size allocated to the table can be known and the
actual usage cannot be checked.
This means that data cannot be calculated except for the free space that occurred after DELETE.
From ALTIBASE HDB 5.3.3.33, 5.3.5.15, 5.5.1.0.3, it has been improved so that the usage can be checked.


Disk table


Disk Index


set linesize 1024

set colsize 20

SELECT U.USER_NAME USER_NAME                                                  -
Database user

, I_LIST.TABLE_NAME                                                    -- Table

name
, DECODE(I_LIST.PARTITION_NAME, NULL, 'NON-PARTITIONED', I_LIST.PARTITION_NAME)

PARTITIONED_NAME             -- Partitioned table name. If a non-partitioned, then

NON-PARTITIONED

, I_LIST.INDEX_NAME INDEX_NAME                                              -
Index name
, DECODE(I_LIST.INDEX_PARTITION_NAME, NULL, 'NON-PARTITIONED', I_LIST.INDEX_PARTITION_NAME)

PARTITIONED_INDEX       -- Partitioned index name

, TBS.NAME TBS_NAME                                                    -
Tablespace to which the index belongs
, TO_CHAR((D.MAX * TBS.PAGE_SIZE)/1024, '999,999,999') 'MAX(KB)'

-- Maximum size of table space
, TO_CHAR((TBS.EXTENT_PAGE_COUNT * TBS.PAGE_SIZE * SEG.EXTENT_TOTAL_COUNT)/1024,
'999,999,999') 'ALLOC(KB)'        -- Total size allocated from the index
, TO_CHAR((((TBS.EXTENT_PAGE_COUNT * TBS.PAGE_SIZE *
SEG.EXTENT_TOTAL_COUNT)/(D.MAX*TBS.PAGE_SIZE))*100), '99.99') 'USAGE(%)'  -- Percentage of
utilization compared to the maximum size of the tablespace
FROM (SELECT T.TABLE_NAME

, PT.PARTITION_NAME

, I.INDEX_NAME

, PI.INDEX_PARTITION_NAME
, DECODE(T.IS_PARTITIONED, 'F', I.TABLE_ID, 'T', PT.TABLE_ID) TABLE_ID
, DECODE(T.IS_PARTITIONED, 'F', T.TABLE_OID, 'T', PT.PARTITION_OID) TABLE_OID
, DECODE(I.IS_PARTITIONED, 'F', I.TBS_ID, 'T', PI.TBS_ID) TBS_ID

, I.INDEX_ID

, T.USER_ID

FROM SYSTEM_.SYS_INDICES_ I LEFT OUTER JOIN SYSTEM_.SYS_INDEX_PARTITIONS_ PI ON

PI.INDEX_ID = I.INDEX_ID LEFT OUTER JOIN SYSTEM_.SYS_TABLE_PARTITIONS_ PT ON PT.PARTITION_ID =
PI.TABLE_PARTITION_ID LEFT OUTER JOIN SYSTEM_.SYS_TABLES_ T ON T.TABLE_ID = I.TABLE_ID ) I_LIST
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


Reference - How to check the number of disk tables and indexes


ALTIBASE HDB 5.3.x, 5.5.1, 6.1.1, 6.3.1


Overview

Version

To check the usage of disk tables and indexes
Disk table

Disk Index

Reference - How to check the count of disk table and index


Overview


Version


The monitoring query introduced on this page can be used from the version that reflects BUG-31372.


Altibase HDB version 5.3.3.33

Altibase HDB version 5.3.5.15

Altibase HDB version 5.5.1.0.3

Altibase HDB version 6.1.1

Altibase HDB version 6.3.1


In BUG-31372, the TOTAL_USED_SIZE column of X$SEGMENT has been added so that the actual usage of the disk table can
be queried.


In ALTIBASE HDB version 5.3.3, 5.3.5, 5.5.1 without BUG-31372 being modified, an error may occur when using the following

query.


To check the usage of disk tables and indexes


ALTER TABLE table_name AGING and ALTER INDEX index_name AGING commands must be executed to get the correct usage.
Unaging space is calculated as used, so if there are frequent deletes on a table, it may be calculated larger than the actual
usage if aging is not performed.
During the execution of the ALTER TABLE table_name AGING, ALTER INDEX index_name AGING command, the table is
full-scanned while holding X LOCK on the table, so other operations on the table and indexes are waiting.
TOTAL_USED_SIZE of v$segment is volatile temporary data. When the Altibase server is restarted, it is initialized to the total
allocation size of the table and index, not the actual usage amount.
v$segment query itself does not affect the database.


Disk table


Even if the table data is deleted with DELETE and USED, it does not decrease.
To check the actual USED excluding FREE PAGE after DELETE and table_name AGING; must be executed.
While executing ALTER TABLE ~ AGINING;, the table is locked, so other requests for the table are put in waiting for state.


Disk Index


Even if the table data is deleted with DELETE, the USED of the index does not decrease.
To check the actual USED except FREE PAGE after DELETE, ALTER INDEX index_name AGING; must be executed.


When executing ALTER INDEX ~ AGINING, the table is locked. Therefore, other requests for the table are put in a waiting state,
so be cautious when executing the ALTER INDEX ~ AGAING.


ALTIBASE HDB 5.3.x, 5.5.1, 6.1.1, 6.3.1 Disk index usage query


-- Disk index usage column description

-- USER_NAME : Database user

-- TABLE_NAME : Table name

-- PARTITIONED_NAME : Partitioned table name. If a non-partitioned, NON-PARTITIONED

-- INDEX_NAME : Index name

-- PARTITIONED_INDEX : Partitioned index name

-- TBS_NAME : Tablespace to which the index belongs
-- MAX(KB) : Max size of tablespace
-- ALLOC(KB) : Total size allocated
-- USED(KB) : Size of the allocated space that includes data
-- USAGE(%) : Percentage of utilization compared to the maximum size of the tablespace

set linesize 1024

set colsize 20

SELECT U.USER_NAME USER_NAME

, I_LIST.TABLE_NAME
, DECODE(I_LIST.PARTITION_NAME, NULL, 'NON-PARTITIONED', I_LIST.PARTITION_NAME)

PARTITIONED_NAME

, I_LIST.INDEX_NAME INDEX_NAME
, DECODE(I_LIST.INDEX_PARTITION_NAME, NULL, 'NON-PARTITIONED',
I_LIST.INDEX_PARTITION_NAME) PARTITIONED_INDEX

, TBS.NAME TBS_NAME
, TO_CHAR((D.MAX * TBS.PAGE_SIZE)/1024, '999,999,999') 'MAX(KB)'


, TO_CHAR((TBS.EXTENT_PAGE_COUNT * TBS.PAGE_SIZE * SEG.TOTAL_EXTENT_COUNT)/1024,
'999,999,999') 'ALLOC(KB)'
, TO_CHAR(SEG.TOTAL_USED_SIZE/1024, '999,999,999,999') 'USED(KB)'


, TO_CHAR(((SEG.TOTAL_USED_SIZE/(D.MAX*TBS.PAGE_SIZE))*100), '99.99') 'USAGE(%)'


FROM (SELECT T.TABLE_NAME

, PT.PARTITION_NAME

, I.INDEX_NAME

, PI.INDEX_PARTITION_NAME
, DECODE(T.IS_PARTITIONED, 'F', I.TABLE_ID, 'T', PT.TABLE_ID) TABLE_ID
, DECODE(T.IS_PARTITIONED, 'F', T.TABLE_OID, 'T', PT.PARTITION_OID) TABLE_OID
, DECODE(I.IS_PARTITIONED, 'F', I.TBS_ID, 'T', PI.TBS_ID) TBS_ID

, I.INDEX_ID

, T.USER_ID

FROM SYSTEM_.SYS_INDICES_ I LEFT OUTER JOIN SYSTEM_.SYS_INDEX_PARTITIONS_ PI ON

PI.INDEX_ID = I.INDEX_ID

LEFT OUTER JOIN SYSTEM_.SYS_TABLE_PARTITIONS_ PT ON

PT.PARTITION_ID = PI.TABLE_PARTITION_ID

LEFT OUTER JOIN SYSTEM_.SYS_TABLES_ T ON T.TABLE_ID = I.TABLE_ID
AND T.TABLE_TYPE = 'T') I_LIST
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





Reference - How to check the count of disk table and index


Error rendering macro 'code': Invalid value specified for parameter 'firstline'


set linesize 1024;

set colsize 50;
SELECT DECODE(T.IS_PARTITIONED, 'T', 'PARTITIONED   TABLE CNT : '||PART_T.CNT, 'F', 'NON-PARTITIONED TABLE CNT :
'||T.CNT) TABLE_COUNT

FROM (SELECT IS_PARTITIONED
, COUNT(*) CNT
FROM V$DISKTBL_INFO D
, SYSTEM_.SYS_TABLES_ T
WHERE D.TABLE_OID = T.TABLE_OID
GROUP BY IS_PARTITIONED) T
, (SELECT COUNT(*) CNT FROM SYSTEM_.SYS_TABLE_PARTITIONS_ ) PART_T ;




### Disk tablespace usage

Overview


Overview


This document summarizes disk tablespace usage query by version.


ALTIBASE HDB 4.3.9


ALTIBASE HDB 5.1.5


Overview


Disk tablespace usage query


Overview


In ALTIBASE HDB version 5, the disk tablespace usage cannot be queried due to the change in the disk table structure, and only
the allocated size is known.
Starting from ALTIBASE HDB version 5.3.3, it has been improved so that the usage can be queried. (Excluding undo tablespaces
and temporary tablespaces)


Disk tablespace usage query


ALTIBASE HDB 5.3.3, 5.3.5


Overview

Disk tablespace usage query


Overview


Starting from ALTIBASE HDB version 5.3., the actual usage of the tablespace can be checked by using the TOTAL_USED_SIZE
column information of X$SEGMENT.
The TOTAL_USED_SIZE column of X$SEGMENT was added in BUG-31372.
The version reflecting BUG-31372 is as follows.

ALTIBASE HDB 5.3.3.33

ALTIBASE HDB 5.3.5.15

ALTIBASE HDB 5.5.1.0.3

Therefore, in ALTIBASE HDB 5.3.3, 5.3.5, 5.5.1 versions without BUG-31372 being modified, an error may occur when using the
following query.
The actual usage of undo tablespaces and temporary tablespaces is not available in this version.


Disk tablespace usage query


SET LINESIZE 1024;

SET COLSIZE 30;

SELECT NAME TBS_NAME                                                      -
TBS_NAME : Disk tablespace name
, TO_CHAR(D.MAX * PAGE_SIZE / 1024 /1024, '999,999,999') 'MAX(M)'
-- MAX(M)  : Max size of tablespace
, TO_CHAR(TOTAL_PAGE_COUNT*PAGE_SIZE/1024/1024, '999,999,999') 'TOTAL(M)'
-- TOTAL(M) : Total page size allocated to date
, DECODE(TYPE, 7, TO_CHAR((SELECT
(SUM(TOTAL_EXTENT_COUNT*PAGE_COUNT_IN_EXTENT)*PAGE_SIZE)/1024/1024
FROM V$UDSEGS)+ (SELECT
(SUM(TOTAL_EXTENT_COUNT*PAGE_COUNT_IN_EXTENT)*PAGE_SIZE)/1024/1024
FROM V$TSSEGS), '999,999,999'), /* UNDO */
TO_CHAR((ALLOCATED_PAGE_COUNT*PAGE_SIZE)/1024/1024, '999,999,999')) 'ALLOC(M)'
-- ALLOC(M) : Total of only 'used pages' excluding 'blank pages' among the allocated pages so far
, DECODE(TYPE, 3, TO_CHAR(NVL(DS.USED, 0)/1024/1024, '999,999,999'),
4, TO_CHAR(NVL(DS.USED, 0)/1024/1024, '999,999,999') /* SYS_TEMP */
, LPAD('-', 12)) 'USED(M)'                                         -USED(M) : Size of the pages in use at which data is loaded. TEMP and UNDO cannot obtain USED.
, DECODE(TYPE, 7, TO_CHAR(((SELECT SUM(TOTAL_EXTENT_COUNT*PAGE_COUNT_IN_EXTENT)
FROM V$UDSEGS)+ (SELECT
SUM(TOTAL_EXTENT_COUNT*PAGE_COUNT_IN_EXTENT)
FROM V$TSSEGS)) / D.MAX* 100, '99.99'),     /* UNDO */
3, TO_CHAR(NVL(DS.USED, 0)/(D.MAX*PAGE_SIZE)* 100, '99.99'),
4, TO_CHAR(NVL(DS.USED, 0)/(D.MAX*PAGE_SIZE)* 100, '99.99'),  /* TEMP */
TO_CHAR(ALLOCATED_PAGE_COUNT / D.MAX * 100, '99.99') ) 'USAGE(%)'
-- USAGE(%) : MAX대비 USED. TEMP, UNDO 의 경우 MAX대비 ALLOC
, DECODE(STATE, 1, 'OFFLINE', 2, 'ONLINE', 5, 'OFFLINE BACKUP', 6, 'ONLINE BACKUP', 128,
'DROPPED', 'DISCARDED') STATE   -- STATE  : Tablespace state
, D.AUTOEXTEND
FROM V$TABLESPACES T LEFT OUTER JOIN (SELECT SPACE_ID, SUM(TOTAL_USED_SIZE) USED
FROM X$SEGMENT
GROUP BY SPACE_ID ) DS ON DS.SPACE_ID = T.ID
,(SELECT SPACEID
, SUM(DECODE(MAXSIZE, 0, CURRSIZE, MAXSIZE)) AS MAX
, DECODE(MAX(AUTOEXTEND), 1, 'ON', 'OFF') 'AUTOEXTEND'
FROM V$DATAFILES
GROUP BY SPACEID ) D

WHERE T.ID = D.SPACEID

;


ALTIBASE HDB 5.5.1, 6.1.1, 6.3.1


Overview

Disk tablespace usage query
Related bug

BUG-39985 V$DISK_UNDO_USAGE calculation error correction


Overview


V$DISK_UNDO_USAGE was added in ALTIBASE HDB 5.5.1.
This performance view allows users to check the usage of the undo tablespace.


Disk tablespace usage query


Related bug


BUG-39985 V$DISK_UNDO_USAGE calculation error correction


The REUSABLE_EXT_CNT column of V$DISK_UNDO_USAGE defines the reusable size within the undo tablespace.


An undo tablespace pool phenomenon occurred, but the REUSABLE_EXT_CNT column has an error indicating that there is reusable
space, so it has been improved.


This bug is reflected in the version below.


ALTIBASE HDB version 6.1.1.4.9

ALTIBASE HDB version 6.3.1


SET LINESIZE 1024;

SET COLSIZE 30;

SELECT DECODE(TYPE, 3, 'SYSTEM TABLESPACE', 4, 'USER DATA TABLESPACE', 5, 'SYSTEM
TABLESPACE', 6, 'USER TEMP TABLESPACE', 7, 'SYSTEM TABLESPACE') TBS_TYPE

, NAME TBS_NAME

-- TBS_NAME : Tablespace name
, TO_CHAR((D.MAX * PAGE_SIZE / 1024 /1024), '999,999,999') 'MAX(M)'
-- MAX(M)  : Max size of tablespace
, TO_CHAR((TOTAL_PAGE_COUNT * PAGE_SIZE)/1024/1024, '999,999,999') 'TOTAL(M)'
-- TOTAL(M) : Total number of pages allocated so far.
, DECODE(TYPE, 7, TO_CHAR((U.TOTAL_EXT_CNT*PROP.EXTENT_SIZE)/1024/1024, '999,999,999')
, TO_CHAR((ALLOCATED_PAGE_COUNT * PAGE_SIZE)/1024/1024, '999,999,999')) 'ALLOC(M)'
-- ALLOC(M) : Total of only 'used pages' excluding 'blank pages' among the allocated pages so far.
, DECODE(TYPE, 3, TO_CHAR(NVL(DS.USED, 0)/1024/1024, '999,999,999'),
4, TO_CHAR(NVL(DS.USED, 0)/1024/1024, '999,999,999'),
7, TO_CHAR(((U.TX_EXT_CNT+U.USED_EXT_CNT+U.UNSTEALABLE_EXT_CNT) *
PROP.EXTENT_SIZE)/1024/1024, '999,999,999')
, LPAD('-', 12))'USED(M)'
-- USED(M) : Size of the pages in which the data is loaded
, DECODE(TYPE, 7, TO_CHAR((((U.TX_EXT_CNT+U.USED_EXT_CNT+U.UNSTEALABLE_EXT_CNT) *
PROP.EXTENT_SIZE)/(D.MAX*PAGE_SIZE))*100, '99.99'),
3, TO_CHAR(NVL(DS.USED, 0)/(D.MAX*PAGE_SIZE)* 100, '99.99'),
4, TO_CHAR(NVL(DS.USED, 0)/(D.MAX*PAGE_SIZE)* 100, '99.99')
, TO_CHAR((ALLOCATED_PAGE_COUNT/D.MAX) * 100, '99.99')) 'USAGE(%)'
-- USAGE(%) : 사용량(MAX 대비 USED)
, DECODE(STATE, 1, 'OFFLINE', 2, 'ONLINE', 5, 'OFFLINE BACKUP', 6, 'ONLINE BACKUP', 128,
'DROPPED', 'DISCARDED') STATE               -- STATE  : Tablespace state
, D.AUTOEXTEND
FROM V$TABLESPACES T LEFT OUTER JOIN(SELECT SPACE_ID, SUM(TOTAL_USED_SIZE) USED
FROM X$SEGMENT
GROUP BY SPACE_ID) DS ON DS.SPACE_ID = T.ID
, (SELECT SPACEID
, SUM(DECODE(MAXSIZE, 0, CURRSIZE, MAXSIZE)) AS MAX
, DECODE(MAX(AUTOEXTEND), 1, 'ON', 'OFF') 'AUTOEXTEND'
FROM V$DATAFILES
GROUP BY SPACEID ) D
, V$DISK_UNDO_USAGE U
, (SELECT VALUE1 EXTENT_SIZE
FROM V$PROPERTY
WHERE NAME = 'SYS_UNDO_TBS_EXTENT_SIZE') PROP

WHERE T.ID = D.SPACEID ;


SET LINESIZE 1024;

SET COLSIZE 30;

SELECT DECODE(TYPE, 3, 'SYSTEM TABLESPACE', 4, 'USER DATA TABLESPACE', 5, 'SYSTEM
TABLESPACE', 6, 'USER TEMP TABLESPACE', 7, 'SYSTEM TABLESPACE') TBS_TYPE

, NAME TBS_NAME

-- TBS_NAME : Tablespace name
, TO_CHAR((D.MAX * PAGE_SIZE / 1024 /1024), '999,999,999') 'MAX(M)'
-- MAX(M)  : Max size of tablespace
, TO_CHAR((TOTAL_PAGE_COUNT * PAGE_SIZE)/1024/1024, '999,999,999') 'TOTAL(M)'
-- TOTAL(M) : Total number of pages allocated so far.
, DECODE(TYPE, 7, TO_CHAR((U.TOTAL_EXT_CNT*PROP.EXTENT_SIZE)/1024/1024, '999,999,999')
, TO_CHAR((ALLOCATED_PAGE_COUNT * PAGE_SIZE)/1024/1024, '999,999,999')) 'ALLOC(M)'
-- ALLOC(M) : Total of only 'used pages' excluding 'blank pages' among the allocated pages so far.
, DECODE(TYPE, 3, TO_CHAR(NVL(DS.USED, 0)/1024/1024, '999,999,999'),
4, TO_CHAR(NVL(DS.USED, 0)/1024/1024, '999,999,999'),
7, TO_CHAR(((U.TX_EXT_CNT+U.USED_EXT_CNT+U.UNSTEALABLE_EXT_CNT) *
PROP.EXTENT_SIZE)/1024/1024, '999,999,999')
, LPAD('-', 12))'USED(M)'
-- USED(M) : Size of the pages in which the data is loaded
, DECODE(TYPE, 7, TO_CHAR((((U.TX_EXT_CNT+U.USED_EXT_CNT+U.UNSTEALABLE_EXT_CNT) *
PROP.EXTENT_SIZE)/(D.MAX*PAGE_SIZE))*100, '99.99'),
3, TO_CHAR(NVL(DS.USED, 0)/(D.MAX*PAGE_SIZE)* 100, '99.99'),
4, TO_CHAR(NVL(DS.USED, 0)/(D.MAX*PAGE_SIZE)* 100, '99.99')
, TO_CHAR((ALLOCATED_PAGE_COUNT/D.MAX) * 100, '99.99')) 'USAGE(%)'
-- USAGE(%) : 사용량(MAX 대비 USED)
, DECODE(STATE, 1, 'OFFLINE', 2, 'ONLINE', 5, 'OFFLINE BACKUP', 6, 'ONLINE BACKUP', 128,
'DROPPED', 'DISCARDED') STATE               -- STATE  : Tablespace state
, D.AUTOEXTEND
FROM V$TABLESPACES T LEFT OUTER JOIN(SELECT SPACE_ID, SUM(TOTAL_USED_SIZE) USED
FROM X$SEGMENT
GROUP BY SPACE_ID) DS ON DS.SPACE_ID = T.ID
, (SELECT SPACEID
, SUM(DECODE(MAXSIZE, 0, CURRSIZE, MAXSIZE)) AS MAX
, DECODE(MAX(AUTOEXTEND), 1, 'ON', 'OFF') 'AUTOEXTEND'
FROM V$DATAFILES
GROUP BY SPACEID ) D
, V$DISK_UNDO_USAGE U
, (SELECT VALUE1 EXTENT_SIZE
FROM V$PROPERTY
WHERE NAME = 'SYS_UNDO_TBS_EXTENT_SIZE') PROP

WHERE T.ID = D.SPACEID ;

### How to determine which queries are being rolled back


Overview


Version


How to check


Method that can be used in ALTIBASE HDB 5.1.5 or higher


Method changed starting from ALTIBASE HDB version 6.1.1.2.0


Overview


When a change transaction is in progress, if the session is forcibly disconnected or the transaction is aborted by a session timeout
setting, the transaction is rolled back.


Here's how to check which queries are being rolled back.


Version


Altibase version 5.1.5 or later


How to check


Method that can be used in ALTIBASE HDB 5.1.5 or higher


If the values of the CURRENT_UNDO_NEXT_LSN_FILENO column and CURRENT_UNDO_NEXT_LSN_OFFSET column are gradually
decreasing in the query execution result below, it appears that the transaction is being rolled back.


The rollback operation performs an undo operation that cancels the operation performed by the change transaction.


The column starting with CURRENT_UNDO_NEXT_LSN means the value indicating the next log (logfile) to undo while this undo operation
is in progress.


If the change transaction performed before the rollback was recorded from logfile 1 to logilfe 10, the value of the column starting with
CURRENT_UNDO_NEXT_LSN decreases because undo proceeds from logfile 10 when rolling back.


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


The time the query was executed is FIRST_UPDATE_TIME
Rollback start time is FIRST_UPDATE_TIME + TOTAL


Method changed starting from ALTIBASE HDB version 6.1.1.2.0


From ALTIBASE HDB version 6.1.1.2.0, it is now possible to easily check the statement being rolled back with the status column of
v$transaction.


select query from v$statement where session id in (select session id from v$transaction where status=4);


The status column of v$transaction is a value that indicates the transaction status and can have a value of 0 to 6, and the meaning of
the value is as follows.


0: BEGIN: transaction started

1: PRECOMMIT: do not use

2: COMMIT_IN_MEMORY: don not use
3: COMMIT: Transaction is committed

4: ABORT: Rolled back and aborted

5: BLOCKED: Wait for lock or other transaction

6: END: Free status after using all transactions

### How to log queries performed in Altibase (altiProfile)?


Overview

Profiling related properties
How to start and stop profiling
How to analyze the results
Precautions


Overview


All SQL statements executed on the Altibase server can be traced.


It is possible by setting/disabling Altibase properties, and in addition to SQL statements, it is possible to trace execution time, index/disk
access information, PLAN information, session information, and ALTIBASE HDB system information.


This chapter describes how to profile Altibase and check the results.


Profiling related properties


|Property Name|Description|
|---|---|
|QUERY_PROF_FLAG|Whether to profile and set logging level<br>0   : Disable profiling (default)<br>1   : Whenever an SQL statement is executed, the SQL statement, execution time, execution<br>information, and index/disk access information are displayed.<br>2   : Output Bind Parameter value every time the prepared SQL statement is executed (limited to<br>the case where there is variable value binding information.)<br>4   : Output execution plan every time SQL statement is executed<br>8   : Output session information (V$SESSTAT) every 3 seconds<br>16  : Output system information (V$SYSSTAT) every 3 seconds<br>32  : Ouput memory information (V$MEMSTAT) every 3 seconds<br>It is also possible to set by combining values in bit units.<br>For example, if it is set to 7 (1 + 2 + 4), information such as the plan, the value of the variable to be<br>bound, the statement and execution time, etc. are displayed at each SQL statement execution.<br>If it is set to 63(1 + 2 + 4 + 8 + 16 + 32), all printable information is displayed. When executing<br>each SQL statement, the SQL statement execution information is displayed in the order of [BIND]<br>[PLAN] [STATEMENT].<br>Altibase status information is output every 3 seconds in the order of [SESSION] [SYSTEM]<br>[MEMORY].|


|QUERY_PROF_LOG_DIR<br>(6.5.1 or later)|Directory path where the profiling result file will be saved<br>Default value : $ALTIBASE_HOME/trc|
|---|---|
|QUERY_PROF_BUF_SIZE|Size of the buffer in which statistics information will be stored<br>Default value : 1MBytes<br>Range : 32KBytes ~ 4GBytes-1|
|QUERY_PROF_BUF_FLUSH_SIZE|Set the size to flush when the buffer is full<br>Default value : 32KBytes<br>Range : 512Bytes ~ 4GBytes-1|
|QUERY_PROF_BUF_FULL_SKIP|Choose whether to skip profiling and wait for all data to be recorded when the statistics buffer is<br>full.<br>Default value : 1<br>Range : 0(wait) or 1(skip)|
|QUERY_PROF_FILE_SIZE|Maximum size of profiling log file<br>Default value : 100MBytes<br>Range : 0 ~ 4GBytes-1<br>          0  : Limited by OS limits<br>        > 0 : Log as much as the size is recorded, and after closing, a new file is created to<br>continue logging. The log file name is created in the same format as alti-#time-#number.prof, and<br>the number starts from 0 and increases by 1|


How to start and stop profiling


Start profiling
Record information on all SQL statements executed after the next command is executed in the log file.





Value: Refer to the description of the QUERY_PROF_FLAG property above.


TIMED_STATISTICS: In version 5.1.5 or later, to check the execution time of an SQL statement, this property value should be set
to 1 (default is 0). (In versions earlier that, there is no corresponding property, and you can check the execution time of all SQL
statements by default.)
Stop profiling
To stop profiling, execute the following command:


ALTER SYSTEM SET QUERY PROF FLAG = 0;


How to analyze the results


When profiling starts, a log file is created in the format $ALTIBASE_HOME/trc/alti#time-#number.prof. (In version 6.5.1 or later, the log
file path can be set in the QUERY_PROF_LOG_DIR property)


Since the log file is in binary format, it must be converted to a text file using the altiProfile command. The method is as follows.


$ altiProfile alti-#time-#number prof> #number out


Since the log file conversion result is output to stdout, it is recommended to save it as a file as in the example above.


The following is a description of the contents of the converted result


The following is a description of the contents of the converted result.


When QUERY_PROF_FLAG = 1 is set






When QUERY_PROF_FLAG = 2 is set
The variable value bound to the prepared SQL statement is output, but it is output in binary type and cannot be analyzed by the

user.


When QUERY_PROF_FLAG = 4 is set
Output the execution plan information created for the execution of the SQL statement.





When QUERY_PROF_FLAG = 8 is set
For all sessions created in the current server, session information is recorded as follows, and it is the same as the result of
executing select * from v$sesstat order by sid, seqnum.






When QUERY_PROF_FLAG = 16 is setIt
Output the overall contents of the Altibase system and is the same as the result of executing select * from v$sysstat order by

seqnum.


When QUERY_PROF_FLAG = 32 is set
Output the memory usage of each Altibase module at that point, and is the same as the result of executing select * from
v$memstat order by seqnum.








Precautions


When profiling is enabled, execution information for all SQL statements executed in the Altibase server is recorded in the log file, and the
Altibase status is profiled every 3 seconds according to the setting, which can affect Altibase performance as well as the load on the


system.


In addition, there is a possibility that a disk pool may occur due to high disk usage due to log recording by profiling.


Therefore, it is not recommended to enable profiling on operation servers by default.


It is recommended to use it for a short time during testing, performance analysis, and tuning. When profiling, be sure to monitor the disk
usage together and stop it appropriately.

### How to set up and execute altimon


What is ALTIMON?
ALTIMON execution and configuration files

ALTIMON execution file

ALTIMON installation file
ALTIMON configuration file
Uploading ALTIMON file
Copying ALTIMON execution file
Things to be changed in the ALTIMON configuration file
Executing ALTIMON
Check Altibase Log


What is ALTIMON?


ALTIMON is a monitoring program that periodically checks the operating status of the ALTIBASE HDB server, and helps to track the cause
of the failure by checking the ALTIBASE HDB server status when a failure occurs.


This page briefly explains how to set up and run ALTIMON.


For more details regarding ALTIMON, please refer to ALTIMON USER GUIDE.


ALTIMON USER GUIDE


TBA


ALTIMON execution and configuration files


ALTIMON execution file

|Col1|Linux|SunOS Sparc|SunOS x86|HP-UX IA|AIX|
|---|---|---|---|---|---|
|Altibase 6.3.1|altimon_linux_631.tar|||||
|Altibase 6.1.1|altimon_linux_611.tar|||||
|Altibase 4.3.9|||altimon_sunos_x86_439.tar|||



ALTIMON installation file


Linux : altimon_linux_611.tar
HP-UX IA : altimon_linux.tar
HP-UX PA-RISC

SunOS Sparc : altimon_hpux_ia64.tar
SunOS x86 :

AIX : altimon_sunos_sparc.tar
Altibase does not provide for WIndows. For Windows, refer to the Monitoring Tools for Windows page.


ALTIMON configuration file


Altibase version 6.3.1 : altimon.conf.631


ALTIBASE HDB version 5.1.5 : altimon.conf.5.1.5

ALTIBASE HDB version 4.3.9 :


Uploading ALTIMON file


Upload the attachment (altimon.tar) to any directory on the system running the Altibase server process.


Extract the attachment.


$ tar xvf altimon.tar


Once it is extracted, 'altimon' directory will be created.


$ ls -l altimon

total 8336

drwxr-xr-x  2 eheejung staff      256 Dec 30 15:26 ACTION_LOG
drwxr-xr-x  2 eheejung staff      256 Dec 30 15:26 ACTION_SCRIPT
-rw-r--r--  1 eheejung staff      318 Dec 30 11:23 Makefile
-rwxr-xr-x  1 eheejung staff    3991619 Dec 30 15:10 altimon      // execution file
-rw-r--r--  1 eheejung staff     18120 Dec 30 11:23 altimon.conf    // configuration file
-rw-r--r--  1 eheejung staff     78141 Dec 30 11:23 altimon.cpp
-rw-r--r--  1 eheejung staff    166311 Dec 30 15:10 altimon.o
drwxr-xr-x  2 eheejung staff      256 Dec 30 15:26 log


Copying ALTIMON execution file


Copy the ALTIMON executable file to the $ALTIBASE_HOME/bin directory.


$ cp -p altimon $ALTIBASE_HOME/bin/


Things to be changed in the ALTIMON configuration file


In the ALTIMON configuration file ($ALTIBASE_HOME/conf/altimon.conf), in the Connection Group section and ALTIMON PROPERTY
section, change the comment section below to suit your environment.


#########################################

## Connection Group

#########################################

<CONNECTION_INFO>
<DB_IP>    127.0.0.1 </DB_IP>
<SYS_PASSWD>  manager   </SYS_PASSWD>        # Enter sys account password
<PORT_NO>   20300    </PORT_NO>         # Enter the Altibase server service port
<NLS_USE>   US7ASCII  </NLS_USE>         # Enter database server character set iSQL> select
NLS_CHARACTERSET from v$nls_parameters; Can be checked.
</CONNECTION_INFO>


#########################################

## ALTIMON PROPERTY

#########################################

<ALTIMON_PROPERTY>
<DATE_FORMAT>  1  </DATE_FORMAT>
<SLEEP_TIME>  300 </SLEEP_TIME>                    # If a problem occurs, change it to suit
your environment so that the situation at that time can be logged. The unit is seconds.
<LOG_FILE>   /home/altibase/altimon/log/altimon.log </LOG_FILE>    # Change the log file path to suit
the environment. Enter it as an absolute path, leave the file name as it is, and change only the path.
<LOG_DIR>    /home/altibase/altimon/log </LOG_DIR>          # Enter the log file path again as an
absolute path to suit the environment.
<LIFE_CYCLE>  3  </LIFE_CYCLE>                    # Log file retention period, in daily units.
Change it to suit the environment.
<LOGGING_LV>  2  </LOGGING_LV>
<ALARM_FILE>  /home/altibase/altimon/log/alarm.log  </ALARM_FILE>   # Change the alarm log file
path to suit your environment. Enter it as an absolute path, leave the filename as it is, and change only the
path.
<DB_SAVE>    OFF  </DB_SAVE>
<LISTEN_PORT>  22300 </LISTEN_PORT>
</ALTIMON_PROPERTY>


From the settings below, the path $HOME/altimon/ACTION_SCRIPT/ will continue to be used.


If the altimon directory is located differently from the one below, please change it.


If altimon.tar is placed in the $HOME directory and untar it, the user does not need to change the settings below.


#########################################

## PROCESS CHECK PROPERTY

#########################################

<OS_QUERY_GROUP_SET>
<CPU_USAGE> 80 </CPU_USAGE>
<CPU_ACT>                    # From this setting, the path $HOME/altimon/ACTION_SCRIPT/ will
continue to be used. If the altimon directory is located differently from the one below, it will be changed.
is -silent -f $HOME/altimon/ACTION_SCRIPT/cpu_act.sql -o
$HOME/altimon/ACTION_LOG/cpu_act.log.`date +%Y%m%d_%H%M%S`
</CPU_ACT>
<MEM_USAGE> 100000000 </MEM_USAGE>

<MEM_ACT>
is -silent -f $HOME/altimon/ACTION_SCRIPT/mem_act.sql -o
$HOME/altimon/ACTION_LOG/mem_act.log.`date +%Y%m%d_%H%M%S`
</MEM_ACT>
<DISK_CHK_ENABLE> ON </DISK_CHK_ENABLE>
<DISK1> /home    </DISK1>          # Please modify the file system to be monitored.
<DISK1_USAGE> 90   </DISK1_USAGE>       # Enter the file system usage threshold. The unit is %.
<DISK2> /home1  </DISK2>
<DISK2_USAGE> 90   </DISK2_USAGE>

<DISK_ACT>
</DISK_ACT>
</OS_QUERY_GROUP_SET>


Executing ALTIMON


After setting the environment variable, execute ALTIMON.


$ export UNIX95=1       (For Bourne Shell, Korn Shell, Bash Shell)

Or

$ setenv UNIX95 1       ( For C Shell)


For AIX, it also sets the NMON environment variable.


$ export NMON=t       (For Bourne Shell, Korn Shell, Bash Shell)

Or

$ setenv NMON t       ( For C Shell)


Execute altimon.


$ altimon start


Check Altibase Log


altimon.log is saved in the following path set in $ALTIBASE_HOME/conf/altimon.conf.


The log of the day is altimon log and the last log is changed to altimon log MMDD


The log of the day is altimon.log, and the last log is changed to altimon.log_MMDD.


<LOG_FILE>   /home/eheejung/altimon/log/altimon.log </LOG_FILE>


The ALTIMON log of the date of failure can be sent from the above path.

### Lock related properties


Overview

Version

How to monitor


Overview

Version

How to monitor


Overview


The user can monitor performance degradation due to transaction lock.


Version


This document is written based on Altibase HDB version 6.3.1.

Both ALTIBASE HDB 5 and ALTIBASE HDB 6 can be used, but some monitoring items may cause a result error.
For more information and updates, please leave a request at http://support.altibase.com/en/ or in the comment section on this

page.


How to monitor


First of all, there are two performance views for the lock information of Altibase.


These are v$loc and v$lock_statement.


First, in v$lock, the user can inquire what type of lock is applied to a table. In the case of a select statement, IX_LOCK will be locked in
case of changes such as IS_LOCK, insert, update, delete, etc.


By joining this view and the system_.sys_tables_ meta table, the user can check table name and lock information.


select table_name, lock_desc
from system_.sys_tables_ a, v$lock b

where a.table_oid = b.table_oid;


In addition, the user can also check which queries are holding the lock with v$lock_statement.


The user can check the query holding the lock by joining the trans_id of v$lock and the tx_id of v$lock_statement.


select query
from v$lock a, v$lock_statement b

where a.trans_id = b.tx_id;


The user can check the session ID of the query currently holding the lock by using multiple joins.


desc v$lock;


With v$lock_statement;, check which columns are existed.


the session can also be killed with the session_id obtained in this wa.


ALTER DATABASE database_name SESSION CLOSE session_id;


The above command can be executed by entering sysdba.


connect sys/manager as sysdba;


++ Lock wait query


select query, tx_id
from v$statement
where tx_id in ( select trans_id from v$lock_wait);


++ Look up based on v$lock_wait view, such as tx_id waiting, lock grant time, related redo logfile location, etc.


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


++ Check the client_pid and session_id holding the lock


select a.table_oid, a.lock_desc, c.client_pid, b.session_id
from v$lock a, v$statement b, v$session c

where a.trans_id = b.tx_id

and b.session_id = c.id;

### Memory table and index usage


Overview

Memory table data usage query


Memory table index usage

Query to check memory table index information (all available from HDB 4 to HDB 7)
Query to check usage per memory table index (available from HDB 5.x or later)
Query to check total index usage per memory table (available from HDB 5.x or later)
Query size per index of memory table (for 6.x)


Overview


This document describes the memory table and index usage query.


Memory table data usage query


The following query can be used in all versions of Altibase.


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






Memory table index usage


The index usage of a memory table cannot be checked directly by a query. Altibase memory tables have a size of 16 bytes per index
regardless of the number and type of index columns, and the index usage can be calculated as 16 bytes * number of records.


Query to check memory table index information (all available from HDB 4 to HDB 7)


The index information for each table can be checked with the following query. To check the index size, the user must check the number
of records and calculate it separately, or use a query that calculates the size of the index of the memory table containing the function.


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





Query to check usage per memory table index (available from HDB 5.x or later)


The usercan use the following query to check the usage per index of a memory table. Before using the query, the user must create a DB
function that can get the number of records for that table.


1. Create a function that can count the number of records in the table.
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


2. Use function to query the usage per index.

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


Query to check total index usage per memory table (available from HDB 5.x or later)


Query the total index usage per table used by the memory table. Before using the query, the user must create a DB function that can get
the number of records for that table.


1. Create a function that can count the number of records in the table.
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


2. Use function to look up the total index usage size per table.

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


USER_NAME            TABLE_NAME           INDEX_COUNT     Alloc(M)

----------------------------------------------------------------------------------
------------------
SYS               T1               2          1.53

SYS               T2               1          0.31

2 rows selected.

iSQL>


Query size per index of memory table (for 6.x)


The user can query more accurate memory table usage per index with the following query. Available in version 6.1.1 or later.


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




### Memory tablespace usage


ALTIBASE HDB 5.5.1, 6.1.1, 6.3.1


Overview

Reference - About Memory Tablespace Attributes


Overview


Starting from ALTIBASE HDB version 5.5.1, V$VOL_TABLESpACES, which stores information on volatile memory tablespaces, has
been added.

Using this Performance View, all memory tablespace usage including volatile memory tablespace usage can be inquired with the
following query.


-
--TBS_ID  : Tablespace ID
--TBS_TYPE : Memory tablespace type
--      0 - System memory tablespace. A tablespace for storing metadata necessary for the
operation of the database system
--      1 - System memory tablespace. A tablespace that can store data created by default
when creating a database
--      2 - User memory tablespace. User-created memory tablespace
--      8 - Volatile tablespaces created by users
--TBS_NAME : Memory tablespace name
--MAX(M)  : Max amount of memory that can be used by memory tablespace
--      If MAXSIZE is not specified when creating a tablespace, MEM_MAX_DB_SIZE is
displayed.
--      If the tablespace attribute is AUTOEXTEND OFF, TOTAL is output.
--TOTAL(M) : Total number of pages allocated from the memory tablespace. It is the same as
the size of the checkpoint image file creation.
--      It also includes a free page. Free pages are not loaded into memory when the
Altibase server is started. So, it is difficult to use and judge physical memory as much as this

value.

--      This value is decreased only by executing DROP TABLESPACE.
--ALLOC(M) : Amount of memory being used by the memory tablespace
--USED(M) : The size of the memory storing data among ALLOCs
--USAGE(%) : ALLOC utilization rate compared to MAX
--STATE  : State of the tablespace
--      1 - Offline, 2 - Online, 3 - Offline tablespace being backed up, 4 - Tablespace in
an online state that are up-to-date,
--      128 - Dropped tablespace, 1024-discarded tablespace, 1028-discarded tablespace
being backed up

set linesize 1024

set colsize 20

SELECT ID TBS_ID
, DECODE(TYPE, 0, 'MEMORY_DICTIONARY', 1, 'MEMORY_SYS_DATA', 2,
'MEMORY_USER_DATA', 8, 'VOLATILE_USER_DATA') TBS_TYPE

, NAME TBS_NAME
, ROUND( DECODE(M.MAXSIZE, 140737488322560, D.MEM_MAX_DB_SIZE, 0,
T.TOTAL_PAGE_COUNT * T.PAGE_SIZE, M.MAXSIZE) /1024/1024, 2 ) 'MAX(M)'
, ROUND( M.ALLOC_PAGE_COUNT * T.PAGE_SIZE / 1024 / 1024, 2) 'TOTAL(M)'

,
ROUND(NVL(M.ALLOC_PAGE_COUNT-M.FREE_PAGE_COUNT,T.TOTAL_PAGE_COUNT)*PAGE_
SIZE/1024/1024, 2) 'ALLOC(M)'


/ /, ) ( )


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





Reference - About Memory Tablespace Attributes


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

### Monitoring Tools for Windows


Overview

Version

Monitoring batch program
Settings

Checking connection information
Adding monitoring items
Monitoring cycle
Deleting old log function
Modifying altimon.vbs file
Execution


How to run in the foreground
How to execute in background
Termination


When executing in the foreground
When executing in the background
Log


Overview


This document describes a monitoring tool for Windows.


Version


This document is written based on Altibase HDB version 6.3.1

Both ALTIBASE HDB 5 and ALTIBASE HDB 6 can be used, but some monitoring items may cause a result error.
If needed, please leave a request at http://support.altibase.com/en/ or in a comment section on this page.


Monitoring batch program


Download the compressed file below, place it in a folder, and extract it.


altimon_for_windows.zip


Once it is unzipped, the user will find two folders and two files.


altimon.bat : Batch program for monitoring
altimon.vbs : VB file to run batch program in background
ALTIMON_SCRIPT folder: There are .sql files containing monitoring queries
ALTIMON_LOG folder: Save log files


Settings


Checking connection information


Change the ALTIBASE HDB server connection command in the altimon.bat file to suit your environment.


set ISQL="%ALTIBASE_HOME%\bin\isql.exe" -s localhost -u sys -p manager -silent


Adding monitoring items


If there are items that the user wants to add other than the basic monitoring items, add a monitoring query to the all.sql file in the
ALTIMON_SCRIPT folder.


In the monitoring query, enter the identifier starting with sysdate in the first column of the SELECT clause and _MON_ in the second
column.


Monitoring cycle


At the end of altimon.bat, change the number after -n in the command below. This number refers to the monitoring cycle.


Modify to suit the environment in seconds.


ping -n 60 127.0.0.1 > nul


Ex) When set to 5 minutes, -n 60 to -n 300


Deleting old log function


At the bottom of the altimon.bat file are commands that start with forfiles.


In this command, the /D -30 option means to delete the log 30 days ago, so change the number after the /D option.


forfiles /P . /M mon.log* /D -30 /C "cmd /c del @file"


Modifying altimon.vbs file


After downloading the above files, upload them to a folder on the server to be monitored.


Then, modify the path of the second line in the altimon.vbs file to suit your environment.


Set WshShell = CreateObject("WScript.Shell")
WshShell.Run chr(34) & "C:\Users\Altibase\Desktop\altimon.bat" & Chr(34), 0
Set WshShell = Nothing


Execution


How to run in the foreground


Execute Windows Command Prompt (Execution Window). Go to the folder where the altimon.bat file is located and run the batch

program.


C:\Users\Altibase>start altimon.bat

or

C:\Users\Altibase>start altimon


The user can also go to the folder where the batch program (altimon.bat) is located in Windows Explorer and double-click the
alti_mon.bat file.


If executing the batch program in the foreground, a notification message appears in the execution window as shown below.


The batch program executed in the foreground is terminated when the open window is closed.


How to execute in background


Put the attached files in the same folder, open a DOS window, move to the folder, and execute the command below.


C> alti_mon.vbs


C:\Users\Altibase\Desktop>alti_mon.vbs
Microsoft (R) Windows Script Host version 5.8
Copyright (C) Microsoft Corporation 1996-2001. All rights reserved.


A batch program executing in the background does not terminate the batch program even if you close an open window. To
terminate, you need to use the taskkill command. Refer to the end.


Termination


When executing in the foreground


Close the execution window where you executed the batch program (altimon.bat) or press Ctrl+c.


When executing in the background


Execute the Windows command prompt (execution window) and execute the command below.


C> taskkill /fi "windowtitle eq ALTIMON FOR WINDOWS"





Log


When executing the batch program, a log file in the form of mon.log.YYYY-MM-DD is created under the ALTIMON_LOG folder.

### System information by OS


Overview

Version

LINUX
SUN System
AIX

HP-UX


Overview


These commands allow users to check the system information and status of each OS (LINUX, SUN, IBM, HP).


This document describes how to check the usage of CPU, MEMORY, SYSTEM, DISK, and NETWORK for each OS.


Version


All the Altibase HDB versions


LINUX


1. CPU


CPU information: cat /proc/cpuinfo


CPU usage: top





2. MEMORY


Memory information: cat /proc/meminfo


Process Memory : ps -elf, ps -aux





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


OS Version : uname -a





Patch No: rpm -qa | grep -i kernel


4. DISK : iogstat 3 1


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


5. NETWORK : netstat, inconfig


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





SUN System


1. CPU


CPU information : psrinfo -v






CPU usage: top





2. MEMORY


Memory information : prtconf


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

CPU information : sar -P ALL 1 3


CPU usage : topas


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

Memory information: lsconf


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
tps : Indicates the number of transfers per second that were issued to the physical disk/tape. A transfer is an
I/O request to the
physical disk/tape. Multiple logical requests can be combined into a single I/O request to the disk.

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
CPU information : glance(a)


$> glance (a key after performing glance)

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


CPU usage : top, glance


2. MEMORY

Memory information : machinfo





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


3. DISK: iostat 3 1





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


### Table/Column Definition

Overview

Table definition

Column definition


Overview


This is a query required when creating user table and column definitions.


Table definition


The table owner, table name, number of records, table creation date, and last DDL execution date information can be checked.


The number of records can be checked from Altibase 6.3.1, which added the performance view related to statistical information.


There are differences in the query statement for each version, so refer to the statement for each version.






Column definition


The column name, data type, size, NOT NULL, constraint information, and column order information can be checked.


There are differences in the query statement for each version, so refer to the statement for each version.


### Undo Tablespace

Monitoring method when undo tablespace usage increases


Overview

Monitoring item
Monitoring method by version

ALTIBASE HDB 5.3.3, 5.5.1, 6.1.1, 6.3.1
ALTIBASE HDB 4.3.9, 5.1.5
Solution


Increasing the size of the undo tablespace
Forcibly terminating session
Avoiding long-running transactions


Overview


This document describes how to monitor when the undo tablespace usage continues to increase.


Monitoring item


If the undo tablespace usage increases, the user should check the following two cases.


Whether there is a change transaction that changes the data in the disk table
Whether there is a query transaction looking at the old image created in the change transaction


Monitoring method by version


ALTIBASE HDB 5.3.3, 5.5.1, 6.1.1, 6.3.1


Query for monitoring undo tablespace usage by transaction


With the monitoring query below, TX_STATUS finds and takes action for long-running transactions with BEGIN or END status.


The following information can be checked in the query result.


Session information using or accessing the undo tablespace. (Autocommit mode, Client IP and Process id, UTRANS_TIMEOUT
setting value)
Whether or not there is a change transaction using the undo realm
Whether there is a query transaction accessing the undo area
Undo usage in use by change transactions
Last SQL statement and execution time of transaction

Whether to execute SQL statement


Query for undo tablespace usage by transaction


SELECT RPAD(DECODE(TX.LOG_TYPE, 1, REP.REP_NAME, TX.SESSION_ID), 10) SESSION_ID

-- Session ID that performed the transaction.
, RPAD(TX.ID, 20) TX_ID

-- Transaction ID
, RPAD(DECODE(ST.ID, NULL, 'REP''S TX', ST.ID), 20) STATEMENT_ID

-- STATEMENT ID
, RPAD(DECODE(TX.TSS_RID, 0, 'SELECT', 'UPDATE'), 7) TX_TYPE

-- Transaction type. SELECT: A transaction with only query statements. UPDATE: Transaction that changed

data such as DELETE, UPDATE, etc.
, RPAD(DECODE(TX.STATUS, 0, 'BEGIN', 1, 'PRECOMMIT', 2, 'COMMIT_IN_MEMORY', 3, 'COMMIT', 4,
'ABORT', 5, 'BLOCKED', 6, 'END'), 16) TX_STATUS  -- Transaction status
, RPAD(DECODE(ST.EXECUTE_FLAG, NULL, 'REP''S TX', 1, 'SQL ING', 0, 'SQL END'), 10) SQL_STATUS

-- SQL status
, RPAD(DECODE(TX.LOG_TYPE, 1, 'REP '||REP.PEER_IP||':'||REP.PEER_PORT, S.COMM_NAME||'
PID:'||S.CLIENT_PID), 40) CLIENT_IP           -- Client IP and process ID
, RPAD(DECODE(S.AUTOCOMMIT_FLAG, 1, 'ON', 0, 'OFF', NULL, 'REP''S TX'), 10) AUTOCOMMIT

-- AUTOCOMMIT mode
, RPAD(DECODE(TX.LOG_TYPE, 1, 'REP''S TX', S.UTRANS_TIME_LIMIT), 15) UTRANS_TIMEOUT

-- Session UTRANS_TIMEOUT setting value
, TO_CHAR(SYSDATE, 'YYYY-MM-DD HH:MI:SS') CURRENT_TIME

-- Current time
, DECODE(ST.LAST_QUERY_START_TIME, NULL, TO_CHAR(TO_DATE('1970010109','YYYYMMDDHH') +
TX.FIRST_UPDATE_TIME / (60*60*24), 'YYYY-MM-DD HH:MI:SS'), ST.LAST_QUERY_START_TIME)

LAST_QUERY_START_TIME  -- SQL statement start time
, RPAD(LTRIM(TXM.SYS_MIN_DISK_VIEWSCN), 10) SYS_MIN_DISK_VIEWSCN

-- Minimum SCN viewing at the undo area
, DECODE(TX.DISK_VIEW_SCN, 'INFINITE(         0)', '-', LTRIM(TX.DISK_VIEW_SCN))


, ( _ _, ( ),, ( _ _ ))


DISK_VIEW_SCN                    -- Minimum SCN seen in viewing transaction
, DECODE(TX.MIN_DISK_LOB_VIEW_SCN, 'INFINITE(         0)', '-',
LTRIM(TX.MIN_DISK_LOB_VIEW_SCN)) MIN_DISK_LOB_VIEW_SCN        -- Minimum SCN viewed in a

transaction querying LOB data
, TO_CHAR(((UD_S.TOTAL_EXTENT_COUNT*UD_S.PAGE_COUNT_IN_EXTENT*8192)/1024), '999,999,999')
'UNDO_USED(KB)'                   -- Size of the undo area used in the change transaction.
, DECODE(TX.LOG_TYPE, 1, 'REMOTE_TX_ID : '||REP_TX.REMOTE_TID, ST.QUERY) QUERY

-- Last query performed by a transaction accessed or using undo
FROM V$TRANSACTION TX LEFT OUTER JOIN (SELECT SESSION_ID, TX_ID, ID,
TO_CHAR(TO_DATE('1970010109','YYYYMMDDHH') + (LAST_QUERY_START_TIME) / (60*60*24),
'YYYY-MM-DD HH:MI:SS') LAST_QUERY_START_TIME, EXECUTE_FLAG, UNDO_READ_PAGE,
UNDO_GET_PAGE, SUBSTR(QUERY, 1, 60) QUERY
FROM V$STATEMENT
WHERE (SESSION_ID

, TX_ID
, LAST_QUERY_START_TIME) IN (SELECT SESSION_ID

, TX_ID
, MAX(LAST_QUERY_START_TIME) LAST_QUERY_START_TIME
FROM V$STATEMENT

GROUP BY SESSION_ID
, TX_ID)) ST ON TX.ID = ST.TX_ID LEFT OUTER JOIN V$SESSION S ON TX.SESSION_ID = S.ID
LEFT OUTER JOIN V$REPRECEIVER_TRANSTBL REP_TX ON TX.ID = REP_TX.LOCAL_TID LEFT OUTER JOIN
V$REPRECEIVER REP ON REP_TX.REP_NAME = REP.REP_NAME
LEFT OUTER JOIN V$TXSEGS TX_S ON TX.ID = TX_S.TRANS_ID LEFT OUTER JOIN V$UDSEGS UD_S ON

TX_S.ID = UD_S.TXSEG_ENTRY_ID
, V$TRANSACTION_MGR TXM

WHERE 1=1

AND (TX.TSS_RID <> 0

OR ST.UNDO_READ_PAGE <> 0
OR ST.UNDO_GET_PAGE <> 0)


ORDER BY SESSION_ID

, TX_ID

, LAST_QUERY_START_TIME;


Output result


Below is an example output showing a change transaction using undo.


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


If TX_TYPE is UPDATE, it means that a data change operation occurred at least once in that transaction.
If SQL_STATUS is SQL_END, it means that the SQL statement executed in the transaction has ended, but the transaction has not.
(TX_ID 61397121 of session 4 in the results below)
If SQL_STATUS is SQL_ING, it means that the SQL statement executed in the transaction is being executed. (TX_ID 61397121 of
session 6 in the results below)
The start time of the last SQL statement executed can be checked in the transaction with LAST_QUERY_START_TIME. The
difference from the current time allows you to determine how long the transaction is running.
UTRANS_TIMEOUT means the maximum amount of time (in seconds) a change transaction can perform.
UNDO_USED(KB) shows the size of undo used in the transaction in kbytes.


The following is the output result showing the query transaction viewing the pre-change data created in the undo area in the change
transaction.


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


If TX_TYPE is SELECT, it means a transaction that has never performed a change statement.
SELECT statements that do not contain LOB data will no longer look at the undo image after fetching data from the database.

    - Transactions in Autocommit-Mode disappear from the result when the fetch is complete. (Refer to TX_ID 1613185 in Session
5. The SCN output in DISK_VIEW_SCN means that LOB data is not included.)

    - In non-autocommit-mode transactions, both DISK_VIEW_SCN and MIN_DISK_LOB_VIEW_SCN are out as-after fetch is finished
and until commit is executed. (TX_ID 376196 of session 9)
SELECT statements including LOB data look at the undo image until commit or rollback is executed even when fetch
is terminated.
If DISK_VIEW_SCN-and SCN is output in MIN_DISK_LOB_VIEW_SCN, it means a transaction that queries LOB data. (TX_ID
7374720 of session 2)
In the case of LOB data, there is information called lob cursor. When this is open, the undo image can be found. The lob cursor
is closed only by commit or rollback.
Transactions in this state can cause increased undo usage.


The following is the result showing a replication transaction using the undo area.





The IP of the server that sent the transaction with CLIENT_IP can be checked.
The name of the redundant object with SESSION_ID can be found.
The value of REP'S TX means a value that cannot be checked locally. (Section and SQL information of a redundant transaction
cannot be checked locally)
The TX_ID of the remote server can be found with REMOTE_TX_ID output on QUERY.


ALTIBASE HDB 4.3.9, 5.1.5


Query for monitoring undo tablespace usage by transaction


Find and take action on transactions that are using or accessing undo with the monitoring query below.


The following information can be checked in the query result.


Session information using or accessing the undo tablespace. (Autocommit mode, Client IP and Process id, UTRANS_TIMEOUT
setting value)
Whether or not there is a change transaction using the undo realm
Whether there is a query transaction accessing the undo area
Last SQL statement and execution time of transaction


Whether to execute SQL statement






Output result


Below is an example output showing a change transaction using undo.


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


If TX_TYPE is UPDATE, it means that a data change operation occurred at least once in that transaction.
If SQL_STATUS is SQL_END, it means that the SQL statement executed in the transaction has ended, but the transaction has not.
(TX_ID 61397121 of session 4 in the results below)
If SQL_STATUS is SQL_ING, it means that the SQL statement executed in the transaction is being executed. (TX_ID 61397121 of
session 6 in the results below)
The start time of the last SQL statement executed in the transaction can be checked with LAST_QUERY_START_TIME. The
difference from the current time allows you to determine how long the transaction is running.
UTRANS_TIMEOUT means the maximum amount of time (in seconds) a change transaction can perform.


The following is the output result showing the inquiry transaction viewing the pre-change data created in the undo area in the change
transaction.


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


If TX_TYPE is SELECT, it means a transaction that has never performed a change statement.


The following is the result showing a replication transaction using the undo area.


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


The IP of the server that sent the transaction can be checked with CLIENT_IP.
The name of the replication object can be checked with SESSION_ID.
The value of REP'S TX means a value that cannot be checked locally. (Section and SQL information of a redundant transaction
cannot be checked locally)
The TX_ID of the remote server can be checked with REMOTE_TX_ID printed on QUERY.


Solution


Increasing the size of the undo tablespace


The data file must be added for the undo tablespace or the size of an existing data file must be expanded.


One of the things the user can do when the undo usage is increasing.


Adding data file


After checking the existing data file name, add the data file according to the existing naming rules.


The blue italic part can be changed according to the user environment. For syntax explanation, refer to the SQL Reference at http://supp

ort.altibase.com/en/manual/.


Extending the size of an existing data file


After checking the name and maximum size of the existing data file, set the maximum size larger than the current value.


Check the data file name and maximum size using the query above.






The blue italic part can be changed according to the user environment. For syntax explanation, refer to the SQL Reference at http://supp

ort.altibase.com/en/manual.


Forcibly terminating session


Terminate sessions that use the undo tablespace for a long time.


This is one of the things that can be done when the undo usage is increasing.


Even if the session is forcibly terminated, the transaction termination point may be different depending on the type of transaction.


In the case of a query transaction, the transaction ends as soon as the session terminates.
In the case of a change transaction, the transaction is terminated after the rollback is performed, so it may take as long as the
minimum transaction progressed before the increase in undo usage is corrected.


How to terminate session


Forcibly terminate session in ALTIBASE HDB





The above statement can only be executed by the sysdba user.


For session_id, enter the SESSION_ID value from the result of 'Undo tablespace usage monitoring query per transaction', and
check the database_name with the query below.


SELECT DB_NAME FROM V$DATABASE;


Terminate the client process
Terminate normally by the method provided by the client program, or by kill command.


$ kill -9 process id


Avoiding long-running transactions


Long-running transactions (bulk transactions) can cause the following problems.





In order to avoid an increase in the undo tablespace usage due to bulk transactions, check the following items and change them by
referring to the recommendations.


1. Process by dividing into small units of transaction


Instead of processing a large amount of data in one transaction, divide it into smaller units.









2. UTRANS_TIMEOUT setting


Make sure to set UTRANS_TIMEOUT to a non-zero value.


Set this value to prevent problems that may occur as the execution time of a transaction that performs change operations (UPDATE,
INSERT, DELETE) increases.


If the execution time is greater than the property value, the session is forcibly terminated and the transaction is rolled back.


How to change the session unit


Use the statement below,





Or, UTRANS_TIMEOUT property can be used in the connection string.


How to change the system unit
If the following statement is executed during database operation, the changed value will be applied to the subsequent sessions.





The value changed to ALTER SYSTEM is initialized to the value set in altibase.properties when the ALTIBASE HDB server is
restarted. In order to apply it permanently, the altibase.properties file must also be modified.





3. Check whether a commit is performed


Transactions executed in non-autocommit mode must be committed or rolled back to end the transaction.


In the application, the transaction is executed in the non-autocommit mode and check if there is a part that does not perform commit or
rollback, and if there is a part that is handled incorrectly, it must be corrected.


Undo tablespace usage


Overview

Version

Undo tablespace usage
Related bug

BUG-39985

Reflected version
Reference - V$DISK_UNDO_USAGE performance view


Overview


Prior to ALTIBASE HDB 5.5.1, only ALLOC of undo tablespace could be checked, but USED could not be checked.
This chapter describes how to check the actual usage tablespaces using V$DISK_UNDO_USAGE added from ALTIBASE HDB
version 5.5.1.


ALLOC and USED of undo tablespace


The undo tablespace is made up of segments, and segments are made up of smaller units called extents.
When a change transaction occurs in a disk table, it is allocated in units of extents. Whenever an extent is newly allocated, the
size of the undo tablespace ALLOC increases.
When the transaction ends, the extent becomes reusable.
However, if any of the extents within a segment are in use, even if there are reusable extents, all of the extents within that
segment become unusable. (UNSTEALABLE EXTENT)
Either the extent is used because a change transaction is executing, or the UNSTEALABLE extent is counted as USED for the
undo tablespace.


Version


This monitoring query is available in the version below.


ALTIBASE HDB 5.5.1

ALTIBASE HDB 6.1.1

ALTIBASE HDB 6.3.1


Undo tablespace usage


ALLOC and USED may increase while a change transaction is being performed on the disk table.
If the transaction is committed, the USED that is increased during the execution of the transaction is reduced.
If the transaction is rolled back, the ALLOC and USED that have increased during the execution of the transaction will be
reduced.


Related bug


BUG-39985


Bug content


Improved the problem of calculating undo areas that cannot be reused as usable space. (A problem in which the extent
corresponding to the UNSTEALABLE_EXT_CNT column is calculated as the available extent)
Refer to the description of the V$DISK_UNDO_USAGE performance view below for the UNSTEALABLE_EXT_CNT column.


Reflected version


ALTIBASE HDB 6.1.1.4.9

ALTIBASE HDB 6.3.1.3.3


Reference - V$DISK_UNDO_USAGE performance view







|Column name|Data<br>type|Description|
|---|---|---|
|TX_EXT_CNT|BIGINT|Number of extents for a segment (Transaction Status Segment, TSS) that stores transaction status<br>information.<br>It is allocated when an update transaction occurs in the disk table.|
|USED_EXT_CNT|BIGINT|Number of extents in the undo segment being used in the transaction.<br>When an update transaction occurs in the disk table, it is allocated as needed.|
|UNSTEALABLE_EXT_CNT|BIGINT|Number of extents that cannot be taken from other undo segments.<br>The extent that belongs to the online undo segment and the extent that has header information.<br>Contains the extent the transaction is accessing.<br>Even if the undo segment has reusable extents, it cannot be taken from other undo segments.|
|REUSABLE_EXT_CNT|BIGINT|Number of reusable extents<br>USED_EXT_CNT used during transaction progress increases as USED_EXT_CNT decreases when<br>the transaction is committed.|
|TOTAL_EXT_CNT|BIGINT|The total number of extents allocated from the undo tablespace.<br>When a transaction is rolled back, the extents used in the transaction are returned to the undo<br>tablespace.<br>When a transaction is committed, the extents used in the transaction are held in the<br>corresponding undo segment.|

## 09. Error Messages

### [Notify : Fetch Timeout] Session Closed by Server.

Overview

Version

Symptom

Altibase Server

Altibase Client


Orange for ALTIBASE
iSQL
APRE(SESC), SQLCLI, ODBC, CAPI
JDBC

Cause

Solution


Checking the application logic
Changing FETCH_TIMEOUT setting value

Changing session property
Changing system property
How to check the FETCH_TIMEOUT property value


Overview


This document describes the Fetch Timeout message.


Version


All the versions of ALTIBASE HDB


Symptom


Altibase Server


In the Altibase server log, the following logs can be checked.


Check the Altibase server log ($ALTIBASE_HOME/trc/altibase_boot.log).
The output format is different for each version, so refer to the results below.
Comprehensively check the log output time, CLIENT_INFO, and Caused by Query to see if it is related to the client-side
phenomenon.
Altibase HDB 5 or later





ALTIBASE HDB 4.3.9

Client IP information cannot be checked in the ALTIBASE HDB 4.3.9 server log. It should be judged with log output time and
Caused by Query.





Altibase Client


The following situations occur on the Altibase client side.


The error message can be checked when the client sends a request to the Altibase server.
Therefore, it may occur after the time left on the Altibase server-side (altibase_boot.log).
The connection to the Altibase server is disconnected during SELECT (when Fetch is requested).
When an application processes a fetch result and requests a FETCH back to the database, a disconnected error occurs.
The session has been closed by the server in the client log. (For ALTIBASE HDB 5.5.1 or later versions)
The Server closed the connection in the client log. (For ALTIBASE HDB 5.5.1 or later versions.)


Refer to the following for the types of error messages for each client


Refer to the following for the types of error messages for each client.


Orange for ALTIBASE


The following error message occurs when scrolling down the result window below after executing SELECT.





iSQL



The following error message occurs while executing SELECT in iSQL.





APRE(SESC), SQLCLI, ODBC, CAPI


"Communication link failure during fetch in APRE, SQL CLI, ODBC, and CAPI. Server closed the connection." occurs.
This applies to ALTIBASE HDB version 5 or later









SESC (ALTIBASE HDB 4 ~ 5.1.5)


JDBC



In ALTIBASE HDB 4.3.9, the following error occurs during FETCH execution and the application may be stopped.





From ALTIBASE HDB 5 to 6.1.1, an error occurs during FETCH, and a disconnection error occurs whenever an application sends
a request to the Altibase server afterward.


From ALTIBASE HDB 6.3.1, the session has been closed by the server error message that occurs during FETCH execution, and a
connection disconnection error occurs whenever a request is sent to the Altibase server.


Cause


This is a notification message left by the SessionManager as it cleans up the sessions stuck on FETCH_TMEOUT.


FETCH_TMEOUT is an Altibase server property. this is a property provided to prevent an abnormal increase of DBMS resources as the
time to execute the SELECT statement increases.


When the client requests fetch, the DBMS divides the fetch result by a certain amount (in the communication buffer) and sends it to the
client. When the client reads all the result sets in the communication buffer, it requests the next result set to the DB server.


If the time interval for requesting the next result set exceeds the value set for FETCH_TIMEOUT, the session is cleaned up and the
transaction in progress is rolled back.


If the old image created by the change transaction is viewed by the inquiry transaction, the old image is not cleaned up even when the
change transaction ends.
For this reason, if the SELECT statement is executed for a long time, the following symptoms may occur.

For memory tables, memory usage increases
For disk tables, undo tablespace usage increases


Solution


Checking the application logic


FETCH TIMEOUT can be a problem if the application mainly processes the fetch result to perform other tasks, and this


_ p pp y p p,

processing takes longer.
So, take a look at how the application handles fetch results, determine if there is room for improvement, and then take action.
(Take measures after checking if there are any of the following parts)









Changing FETCH_TIMEOUT setting value


The default value for the FETCH_TIMEOUT property is 60 seconds. If it is determined that this value is small in the operating
environment, it can be changed and used.
This property can be changed with a system property or a session property.


Changing session property


Session property is applied to the session that executed ALTER SESSIOn on a per session basis and applied to queries executed
after ALTER SESSION was executed.





It can also be changed in the application.






Changing system property


System property affects a connected session after executing ALTER SYSTEM.





To keep the changed system property values even after restarting the Altibase server process, you need to modify the
altibase.properties file.





How to check the FETCH_TIMEOUT property value


How to check the property value applied to the session


Since FETCH_TIMEOUT can be changed on a per-session basis, the value set for each session may be different.
The property value set in the session can be checked in V$SESSION.


-- ALTIBASE HDB 5 or later
iSQL> SELECT ID SESSION_ID, FETCH_TIME_LIMIT FROM V$SESSION WHERE ID = SESSION_ID();


-- ALTIBASE HDB 4.3.9 (My session ID is unknown, so infer it with client IP, PID, etc.
iSQL> SELECT ID SESSION_ID, DB_USERNAME, CLIENT_CONSTR, COMM_NAME, CLIENT_PID,
FETCH_TIME_LIMIT FROM V$SESSION;


Check system property value
It can be changed with ALTER SYSTEM or check the value set in altibase.properties in V$PROPERTY.




### [Warning] Memory allocation failed.

Overview

Version


Situation

Cause and solution


When memory usage is limited by kernel parameters
When running an Altibase server on a 32-bit OS
Insufficient physical memory
Reference


Overview


This document explains '[Warning] Memory allocation failed]. This message is created when memory allocation fails due to the OS
environment.


Version


All the versions of ALTIBASE HDB


Situation


In $ALTIBASE_HOME/trc/altibase_boot.log, '[Warning] Memory allocation failed' error occurs.
There may be an error such as [ERR-01051: Memory allocation failed.].
This error can also occur during transaction execution or when STARTUP/SHUTDOWN on the Altibase server.
When this error occurs, new connections may also fail.
It mainly occurs on HP-UX.


Cause and solution


When memory usage is limited by kernel parameters


This is the most common cause.


For HP-UX, kernel parameters can limit the amount of memory a process can use. If the memory usage of the Altibase server process
exceeds the setting value of this parameter, '[Warning] Memory allocation failed' message occurs.


The kernel parameters are as follows.


maxdsiz (for 32bit process)
maxdsiz_64bit (for 64bit processes)


How to check kernel parameters is as follows. The unit is in bytes and should be set large enough in consideration of the physical
memory size. If necessary, ask the system engineer to make changes.


$ /usr/sbin/kctune | grep maxdsiz


When running an Altibase server on a 32-bit OS


In 32-bit OS, the memory size that can be used by one process is limited to 2G, so if the Altibase server is operating without taking this
into account, this message may occur.


Insufficient physical memory


This message also occurs when there is not enough physical memory. Use a system resource monitoring tool such as top and glance to
check the physical memory usage.


Reference


The default tablespace for ALTIBASE HDB server is SYS_TBS_MEM_DATA. So, if you do not specify a tablespace when
performing CREATE TABLE, this tablespace is designated by default.
This tablespace is a system memory tablespace, and the data in the table uses memory. Therefore, memory usage may increase
differently from the user's intention, so make sure to check this as well.
ALTIBASE_운영을_위한_HPUX_설정_가이드.pdf (TBA)

### altibase_boot.log - TRY_COUNT, LOCK_COUNT, MISS_COUNT


Overview


In altibase_boot.log, a large number of messages with the title "reset Mutex Statistics" may be recorded. This document provides a brief
description of this message.


Situation


The following message may be repeatedly recorded in altibase_boot.log.







Cause


This message is output when the values of the try_count, lock_count, and miss_count columns of the v$mutex performance view table
exceed the maximum value and the values are initialized.








v$mutex records mutex information related to concurrency control in the database. If the values of the columns continue to increase and
exceed the maximum value, a value overflow occurs. When the maximum value of integer type is reached, the corresponding value is
recorded in altibase_boot.log, then initialize to 0.


Solution


When the maximum number of columns that can store mutex-related information is reached, the information is recorded in
altibase_boot.log, and there is no particular problem or action required.

### Closed Socket by client is Detected


Version

Symptom
Cause

Solution
Note/Consideration


Version


All the versions


Symptom


The following error message is recorded in altibase_boot.log.


[Notify : Detect] Closed Socket by client is Detected. : Session ID = 7687977


Cause


When the client calls disconnect, the connection (session) is normally terminated between the server and the client.


In addition, if the client terminates the program or the server detects that the connection with the client is disconnected due to a network
problem, etc., the above error message is recorded and the session is cleaned up.


Solution


This is not an error message because there is a problem with the server because it records a log and cleans the session for the session
that has already been disconnected.


Therefore, it is not necessary to take any action on the Altibase server.


However, check if there was any work such as restarting the application during the time period. If not, please check if there is any
problem on the network side.


Note/Consideration


If there was no problem with the service, this error message can be ignored.

### ERR-0109D Insufficient memory.


Version

Symptom
Cause

Solution

Reference


Version


All versions


In the case of this error message, this error may occur for the same error cause or another error may occur depending on the Altibase
version.


In addition, the cause of the error may be different depending on the version of Altibase for this error message.


Symptom


# Example


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


# Results from version 5.5.1 or later


iSQL> select count(*) from (select count(*) from t, t2, t3 group by t.c2, t2.c2, t3.c2);

[ERR-0109D : Insufficient memory]


# Result of execution in version 5.3.3


iSQL> select count(*) from (select count(*) from t, t2, t3 group by t.c2, t2.c2, t3.c2);

[ERR-01067 : The allocated memory size of statement exceeds the maximum limit ( Name : Query_Execute,
Wanted Memory Size : 1114112, Max size : 1048576 ).]


Cause


The description of the error can be checked using the altierr utility as follows.


When performing queries such as order by and group by on a memory table, the temporary area is used. The temporary area also uses

memory space.


This error occurs when the ALTIBASE HDB server makes a memory allocation request to execute a query and an error is returned by the
EXECUTE_STMT_MEMORY_MAXIMUM attribute value.


Solution


The value of the following property must be increased.





1. If the error occurs during query execution, check the "EXECUTE_STMT_MEMORY_MAXIMUM" property value with the following SQL

statement.


iSQL> set vertical on;
iSQL> select name, value1 from v$property where name='EXECUTE_STMT_MEMORY_MAXIMUM';

NAME  : EXECUTE_STMT_MEMORY_MAXIMUM

VALUE1 : 1073741824


2. Increase the property value appropriately with the ALTER statement. (The unit is byte.)


The following is an example of setting to 2G.


iSQL> alter system set EXECUTE_STMT_MEMORY_MAXIMUM = 2147483648;

Alter success.


3. The above command is applied to the entire server after execution, but it is applied as the setting value of the property file when
Altibase is restarted.


Therefore, to apply it permanently, the property value must be changed in the property file as well.


Change the property value in the $ALTIBASE_HOME/conf/altibase.properties file as above.


Reference



1.



The EXECUTE_STMT_MEMORY_MAXIMUM property specifies the maximum value, and memory is not allocated as much as the
preset value.


However, the memory usage may increase as much as the set value, so be careful when setting it.


Therefore, it is recommended to increase it appropriately empirically rather than setting it large in advance.


2.



The "Insufficient memory" error can be a number of memory allocation failure errors in addition to the cases described here.


Therefore, if the above solutions do not solve the problem, please contact Altibase Technical Support.


### ERR-311E0 The estimated size of the index key exceeds the maximum limit.

Version

Symptom
Cause

Solution


Version


Version 6.1.1 or earlier.


No error occurs in version 6.3.1 or later.


Symptom


The following error occurs when using join or Order by / Group by on a disk table.


[ERR-311E0: The estimated size of the index key exceeds the maximum limit.]


Cause


The description of the error can be checked using the altierr utility as follows.


When performing joins or order by / group by on a disk table, Altibase uses Temp Tablespace internally.


Temp Tablespace is a Disk Tablespace and has a fixed page size of 8K. When using Temp Tablespace, the above error may occur if
there is a need to create more than 8K records.


For reference, if the size of the disk tablespace exceeds 1Page(8K), the data length is approximately 3000Bytes or more.


# Example


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


# Example of 6.3.1 version


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


Solution


1. The TEMP_TBS_MEMORY hint can be used to avoid the 1 Page (8K) size limitation of the disk temp tablespace.


In addition, this hint is effective in improving query performance because the memory area is used instead the disk as the temp area.


iSQL> SELECT /*+ TEMP_TBS_MEMORY */ * FROM T1 ORDER BY I1;

I1

-------------
1

2

3

3 rows selected.


2. Upgrade to version 6.3.1 or higher.


In version 6.3.1 or later, this error does not occur in the same situation.


### ERR-410D2 (266450) Fetch out of sequence.

Overview

Version

Symptom
Cause

When COMMIT/ROLLBACK is performed in the OPEN CURSOR state
Solution

When COMMIT/ROLLBACK is performed in the OPEN CURSOR state

1. Separation of fetch session and change DML session
2. Declare a cursor only enough to be stored in the communication buffer, and then repetitively open the cursor
3. fetch across commit

Reference


Differences by version
Reference manual


Overview


This document describes an error that occurs during the record fetch process by using a cursor to process a select statement that
returns multiple records.


Version


Altibase version 6.3.1 or later


Symptom


To process a query statement that returns multiple records, a cursor (CURSOR) must be used in the following process.



1.

2.

3.

4.



DECLARE CURSOR

OPEN CURSOR

FETCH CURSOR
CLOSE/RELEASE CURSOR



Although the cursor is used as above, the 3. FETCH process proceeds to some extent in the CURSOR FETCH stage, and the
'ERR-410D2 (266450) Fetch out of sequence' error occurs even though there are still records to be fetched at some point.


Below is an example where an error occurs when using the cursor and the result of the error.


Cause


When COMMIT/ROLLBACK is performed in the OPEN CURSOR state


Altibase complies with the ANSI standard and is configured not to support the fetch across commit method by default. Therefore, if
COMMIT or ROLLBACK is performed after opening the cursor, the cursor is forcibly closed according to the ANSI standard.


This is a method that performed COMMIT while fetching the unit record after opening the cursor, which is not recommended by
the ANSI standard.


The reason an error occurs while performing FETCH to some extent is that the first large amount of records is stored in the
communication buffer during FETCH. An error occurs when fetching all the records in the communication buffer and fetching the next
certain amount of records into the communication buffer.


The following is an example of creating an application that may cause an error by performing COMMIT or ROLLBACK in the cursor OPEN

state.


non-autocommit mode


DECLARE CURSOR


OPEN CURSOR


while(1)
{

FETCH CURSOR;

if (sqlca.sqlcode == SQL_SUCCESS) {

/* Execute change DML */

/* Perform COMMIT or ROLLBACK */

}
else if (sqlca.sqlcode == SQL_NO_DATA) {

...

}
else {
/* An error occurs at this stage when all the records in the first communication buffer are processed and
then placed in the second communication buffer. */

...

}
}


Solution


When COMMIT/ROLLBACK is performed in the OPEN CURSOR state


Here are three solutions to deal with this error.


1. Separation of fetch session and change DML session


By using multiple connections within one application, COMMIT or ROLLBACK does not affect the cursor.


Create a session that uses a cursor and a session that executes modified DML statements. It is described by defining it as
CONN1 and CONN2, respectively.
Whenever cursor FETCH is executed in the session using the cursor (CONN1), change DML is executed in CONN2, and COMMIT
or ROLLBACK is executed.
The session (CONN2) that executes the modified DML statement is set to non-autocommit mode.


The following is an example of creating an application that reflects this action.


/* Session for FETCH */

EXEC SQL AT conn1 CONNECT;

/* Session for performing change DML */

EXEC SQL AT conn2 CONNECT;


EXEC SQL AT conn2 AUTOCOMMIT OFF;

/* Declare cursor in CONN1, perform OPEN, FETCH */

EXEC SQL AT conn1 DECLARE cursor;

EXEC SQL AT conn1 OPEN cursor;
while (1)
{
/* Perform FETCH on conn1 */

EXEC SQL AT conn1 FETCH cursor

if (sqlca.sqlcode == SQL_SUCCESS) {

/* Change DML and COMMIT or ROLLBACK in conn2 */

EXEC SQL AT conn2 INSERT or UPDATE or DELETE ;

/* check sqlca.sqlcode */
if (sqlca.sqlcode == SQL_SUCCESS) {

...

}
else {

...

}

/* The commit or rollback performed in conn2 does not affect the cursor use of conn1. */

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


2. Declare a cursor only enough to be stored in the communication buffer, and then repetitively open the cursor


After calculating the number of records enough to put in the communication buffer with one FETCH, declare the cursor using the LIMIT
clause.


The communication buffer size of Altibase 5 and above is 32K. Since the number of records in the communication buffer depends on the
record size, the last value of the LIMIT clause varies depending on the operating environment.


Specify the number of records to be stored in the communication buffer in the LIMIT clause, and open the cursor again and use it while


changing the start value of the LIMIT clause before opening the cursor.


/* The cursor is declared using the LIMIT clause. n is the last record value to be returned in the LIMIT clause
and must be defined according to the operating environment. The number of records in the communication
buffer depends on the record size. */

DECLARE CURSOR

SELECT ~

FROM ~

WHERE ~

LIMIT :s_start, n;


/* Declare the starting value used in the LIMIT clause. */

s_start = 1;

while(1)
{
/* Cursor open is repeated until all records meeting the conditions are fetched. */

OPEN CURSOR

while(1)
{

FETCH CURSOR ;

if (sqlca.sqlcode == SQL_SUCCESS) {

/* Execute change DML */
}
else if (sqlca.sqlcode == SQL_NO_DATA) {

...

}
else {

...

}
}

/* Perform COMMIT or ROLLBACK */

/* Specify the starting value of the LIMIT clause. n is an example. */

s_start = s_start + n ;

}


CLOSE CURSOR OR CLOSE RELEASE CURSOR


3. fetch across commit


Although not recommended by the ANSI standard, it is a function added from version 6.3.1 for the convenience of users familiar with
other DBMSs.


In the case of Precompiler (APRE), when declaring a cursor, declare and use a WITH HOLD cursor.


Reference


Differences by version


Depending on the Altibase version, the error messages that occur in the same situation may be different.


The difference in error messages that occurs when COMMIT/ROLLBACK is executed among FETCHs in a non-autocommit environment
is as follows.

|Version|Error code|Error message|Reference page|
|---|---|---|---|
|Altibase 4.3.9|ERR-4103C|Request of fetching data to an unprepared SQL statement.|http://aid.altibase.com/x/6YKZ|
|Altibase 5.3.3 ~ 6.1.1|100|Not found data|http://aid.altibase.com/x/7YKZ|
|Altibase 6.3.1 or later|ERR-410D2|Fetch out of sequence.||



Reference manual


This section introduces the manuals related to fetch across commit provided from Altibase 6.3.1.


Precompiler User's Manual: 8. Cursor processing SQL statement -> Cursor-related embedded SQL statement -> DECLARE
CURSOR
CLI User's Manual: 2. ALTIBASE HDB CLI Function -> SQLSetStmtAttr
JDBC User's Manual: 3. Advanced Features -> Using ResultSet -> Holdability


The manual can be downloaded from the pages below.


http://support.altibase.com/en/manual/
https://github.com/ALTIBASE/Documents/tree/master/Manuals

### ERR-1105D Unable to begin a new update statement.


Version

Symptom
Cause

Solution


Version


Version 6.1.1 or earlier.


Error codes and messages have been changed in version 6.3.1.


Symptom


The following error occurs when using the function in the SELECT statement.


iSQL> select func1() from dual;

[ERR-1105D : Unable to begin a new update statement.
0004 :    insert into T1 values(C1);

^             ^

]


In version 6.3.1, error codes and messages have been changed as follows.


iSQL> select func1() from dual;

[ERR-31386 : Cannot perform a DML, commit, or rollback inside a query.


In FUNC1
0004 : insert into T1 values(C1);

^             ^

]


Cause


The description of the error can be checked using the altierr utility as follows.


# Version 6.1.1 or earlier


When using a function within a SELECT statement, the function must contain only the SELECT statement.


If the function includes INSERT/UPDATE, the above error occurs.


Solution


Functions used within the SELECT statement must contain only the select statement.


# Example of where an error occurs when a function including an insert statement is used in a SELECT statement


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


# Example of executing the above function using execute statement


Executed successfully in the execute statement.


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


# Example that is successfully executed when the above function is used in the SELECT statement after removing the insert statement to
use it in the SELECT statement.


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

### ERR-4103C (266300) Request of fetching data to an unprepared SQL statement.


Overview

Version

Symptom
Cause

When COMMIT/ROLLBACK is performed in the OPEN CURSOR state
Solution

When COMMIT/ROLLBACK is performed in the OPEN CURSOR state

1. Separation of fetch session and change DML session
2. Declare a cursor only enough to be stored in the communication buffer, and then repetitively open the cursor
Reference


Differences by version


Overview


This document describes an error that occurs during the record fetch process by using a cursor to process a select statement that
returns multiple records.


Version


Altibase 4.3.9


Symptom


To process a query statement that returns multiple records, a CURSOR must be used in the following process.



1.

2.

3.

4.



DECLARE CURSOR

OPEN CURSOR

FETCH CURSOR
CLOSE/RELEASE CURSOR



Although the cursor is used as above, the 3. FETCH process proceeds to some extent in the CURSOR FETCH stage, and the
'ERR-4103C (266300)' error Request of fetching data to an unprepared SQL statement.' occurs even though there are still records to be
fetched at some point.


Below is an example where an error occurs when using the cursor and the result of the error.


Cause


When COMMIT/ROLLBACK is performed in the OPEN CURSOR state


Altibase complies with the ANSI standard and is configured not to support the fetch across commit method by default. Therefore, if
COMMIT or ROLLBACK is performed after opening the cursor, the cursor is forcibly closed according to the ANSI standard.





The reason an error occurs while performing FETCH to some extent is that the first large amount of records is stored in the
communication buffer during FETCH. An error occurs when fetching all the records in the communication buffer and fetching
the next certain amount of records into the communication buffer.


The following is an example of creating an application that may cause an error by performing COMMIT or ROLLBACK in the
cursor OPEN state.


non-autocommit mode

DECLARE CURSOR

OPEN CURSOR

while(1)
{
커서(CURSOR) FETCH ;

if (sqlca.sqlcode == SQL_SUCCESS) {

/* Execute change DML */

/* Perform COMMIT or ROLLBACK */

}
else if (sqlca.sqlcode == SQL_NO_DATA) {

...

}
else {
/* An error occurs at this stage when all the records in the first communication buffer are
processed and then placed in the second communication buffer. */

...

}
}


Solution


When COMMIT/ROLLBACK is performed in the OPEN CURSOR state


Here are two solutions to deal with this error.


Separate fetch and change DML operations using multiple connections
Open the cursor repeatedly after declaring the cursor only enough to be contained in the communication buffer


All of the above solutions require application changes.


1. Separation of fetch session and change DML session


By using multiple connections within one application, COMMIT or ROLLBACK does not affect the cursor.

Create a session that uses a cursor and a session that executes modified DML statements. It is described by defining it
as CONN1 and CONN2, respectively.
Whenever cursor FETCH is executed in the session using the cursor (CONN1), change DML is executed in CONN2 and
COMMIT or ROLLBACK is executed.
The session (CONN2) that executes the modified DML statement is set to non-autocommit mode.


The following is an example of creating an application that reflects this action.


/* Session for FETCH */

EXEC SQL AT conn1 CONNECT;

/* Session for performing change DML */

EXEC SQL AT conn2 CONNECT;

EXEC SQL AT conn2 AUTOCOMMIT OFF;

/* Declare cursor in CONN1, perform OPEN, FETCH */

EXEC SQL AT conn1 DECLARE cursor;

EXEC SQL AT conn1 OPEN cursor;
while (1)
{
/* Perform FETCH on conn1 */

EXEC SQL AT conn1 FETCH cursor

if (sqlca.sqlcode == SQL_SUCCESS) {

/* Change DML and COMMIT or ROLLBACK in conn2 */

EXEC SQL AT conn2 INSERT or UPDATE or DELETE ;

/* check sqlca.sqlcode */
if (sqlca.sqlcode == SQL_SUCCESS) {

...

}
else {

...

}

/* The commit or rollback performed in conn2 does not affect the cursor use of conn1. */

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
else  {

...

}
}


2. Declare a cursor only enough to be stored in the communication buffer, and then repetitively open the cursor


After calculating the number of records enough to put in the communication buffer with one FETCH, declare the cursor using
the LIMIT clause.


The communication buffer size of Altibase version 4.3.9 and above is 64K. Since the number of records in the communication

buffer depends on the record size, the last value of the LIMIT clause varies depending on the operating environment.


Specify the number of records to be stored in the communication buffer in the LIMIT clause, and open the cursor again and use


it while changing the start value of the LIMIT clause before opening the cursor.


The following is an example of creating an application that reflects this action.


/* The cursor is declared using the LIMIT clause. n is the last record value to be returned in the LIMIT
clause and must be defined according to the operating environment. The number of records in the
communication buffer depends on the record size. */

DECLARE CURSOR

SELECT ~

FROM ~

WHERE ~

LIMIT :s_start, n;

/* Declare the starting value used in the LIMIT clause. */

s_start = 1;

while(1)
{
/* Cursor open is repeated until all records meeting the conditions are fetched. */

OPEN CURSOR

while(1)
{

FETCH CURSOR ;

if (sqlca.sqlcode == SQL_SUCCESS) {

/* Execute change DML */
}
else if (sqlca.sqlcode == SQL_NO_DATA) {

...

}
else {

...

}
}

/* Perform COMMIT or ROLLBACK */

/* Specify the starting value of the LIMIT clause. n is an example. */

s_start = s_start + n ;

}

CLOSE CURSOR OR CLOSE RELEASE CURSOR


Reference


Differences by version


Depending on the Altibase version, the error messages that occur in the same situation may be different.


The difference in error messages that occurs when COMMIT/ROLLBACK is executed among FETCHs in a non-autocommit


environment is as follows.

|Version|Error code|Error message|Reference page|
|---|---|---|---|
|Altibase 4.3.9|ERR-4103C|Request of fetching data to an unprepared SQL statement.||
|Altibase 5.3.3 ~ 6.1.1|100|Not found data|http://aid.altibase.com/x/7YKZ|
|Altibase 6.3.1 or later|ERR-410D2|Fetch out of sequence.|http://aid.altibase.com/x/9oKZ|


### ERR-4109C Invalid session property.


Symptom
When error occurs within the same major version

ALTIBASE HDB 5.5.1

Cause

Solution

Reference

How to check ALTIBASE HDB server version (same for Unix/Linux/Windows)
How to check the version of the Altibase client


Symptom


Connection from ALTIBASE HDB client to Altibase server fails.


An error may occur in the following two cases. In the version, the first three digits are the major version, and the back digits are the
patch version.


When the major version of the server and the client are the same, but the patch version of the client is later than that of the

server.
When the client's major version is later than the server's major version.


When error occurs within the same major version


ALTIBASE HDB 5.5.1


JDBC Client


When connecting to a server with a version earlier than 5.5.1.3.7 from a later version including ALTIBASE JDBC DRIVER version
5.5.1.3.7, the connection fails. (Example, JDBC driver version 5.5.1.3.7 -> ALTIBASE HDB server 5.5.1.3.6)


CLI Client


When connecting to a server with a version earlier than 6.1.1.1.10 from a later version client including 6.1.1.1.10, the connection fails.
(Example, iSQL version 6.1.1.1.10 -> ALTIBASE HDB server 6.1.1.1.9)


Cause


This error occurs when a client connects to the server and requests a server property that the server does not know.


At the time of connection, the client requests the server properties necessary for client configuration to the ALTIBASE HDB server.


However, when a server property is added from a later version and a later version of the client connects to the lower version, an error
occurs as follows.


Solution


Use the same or earlier version of the client as the ALTIBASE HDB server.

In order to use a later version of the client, the ALTIBASE HDB server version must also be patched or upgraded to the same
version.


Reference


How to check ALTIBASE HDB server version (same for Unix/Linux/Windows)


Execute the following command in a shell prompt or DOS window.


$ altibase -v


Connect to the ALTIBASE HDB server and query with the query below.


iSQL> SELECT PRODUCT_VERSION FROM V$VERSION;


How to check the version of the Altibase client


When the Altibase client package is installed (Same for Unix/Linux/Windows)


$ apre -v


In the case of the ODBC driver


Check in the properties of the altiodbc.dll file in Windows Explorer.


In the case of the JDBC driver


$ java -jar Altibase.jar

### ERR-5102E ( 331822) Invalid cursor state.


Overview

Version

Symptom
Cause and Solution


1. When the cursor with the same name is reused without closing the cursor after completing the FETCH
2. When Exception handling is omitted when cursor CLOSE fails after FETCH is completed
3. When the cursor is reused while the result of the data to be fetched remains


Overview


This error occurs when reusing an opened cursor when handling a statement in an application.


Version


ALTIBASE HDB version 4 or later


"HDB 4.3.9 Error Message" manual or altierr utility "Invalid cursor state." cannot confirm the explanation, but HDB 4.3.9 can also cause
this error.


Symptom


Invalid cursor state occurs when executing CURSOR DECLARE or CURSOR OPEN during CURSOR FETCH in APRE (or SESC).
Invalid cursor state occurs when executing CURSOR DECLARE or CURSOR OPEN after CURSOR FETCH in APRE (or SESC).
Invalid cursor state occurs when executing one of SQLExecute(), SQLPrepare(), and SQLExecDirect() while executing SQLFetch()
in SQLCLI or ODBC.
Invalid cursor state occurs when executing one of SQLExecute(), SQLPrepare(), and SQLExecDirect() after executing SQLFetch()
in SQLCLI or ODBC.


Cause and Solution


1. When the cursor with the same name is reused without closing the cursor after completing the FETCH


This is for HDB 5 or later version. In HDB 4 version, there is no error in this case.
In some cases, an error may occur because the cursor with the same name is reused without executing cursor CLOSE.
Example code.


declare cursor A;

open cursor A;
fetch cursor A;    // fetch completed!
// close cursor A;  // Do not process cursor close!
declare cursor A;   // Reuse the cursor of the same name!


If this is the case, add a CLOSE statement to the cursor.


2. When Exception handling is omitted when cursor CLOSE fails after FETCH is completed


Cursor CLOSE fails, but the exception is not handled, and the cursor is reused with the same name without knowing that the
cursor CLOSE failed.

This is for HDB 5 or later version. In HDB 4 version, there is no error in this case.
Example code


declare cursor A;
if ( sqlca.sqlcode != SQL_SUCCESS ) {
exception handling;
}

open cursor A;
if ( sqlca.sqlcode != SQL_SUCCESS ) {
exception handling;
}
fetch cursor A;                     // fetch completed!
if ( sqlca.sqlcode != SQL_SUCCESS ) {
exception handling;
}

close cursor A;                     // No exception handling.
/* close cursor A failed!! */

declare cursor A;
if ( sqlca.sqlcode != SQL_SUCCESS ) {
exception handling;
}


If this is the case, add exception handling to the cursor CLOSE statement and figure out what caused the cursor CLOSE to fail.


3. When the cursor is reused while the result of the data to be fetched remains


If there is data to be fetched in the DB server, the result is deleted when the cursor is closed.
In other words, the cursor with the same name cannot be reused until the data to be fetched is deleted. In order to reuse, the
cursor must be FETCHed after OPENed.





while(1)
{
SQLFetch(stmt)     // Data to be fetched remains
SQLExecute(stmt)   // An error occurs when the cursor with the same name is reused while the

data to be fetched remains!
}


If this is the case, try to reuse the cursor after adding the cursor CLOSE statement.

### ERR-7101D ( 462877) Protocol header error.


Version

Symptom
Cause

Solution

Reference


Version


All the versions of Altibase


Symptom


The following error message is recorded in the Altibase trace log altibase_boot.log below and in $ALTIBASE_HOME/trc/altibase_boot.log.


ERR-7101d(errno=0) Protocol header error.(TCP 127.0.0.1:13036)

Protocol processing failed. Close connection...


Cause


The description of the error can be checked using the altierr utility as follows.


This error is a message recorded in the server's altibase_boot.log when an incompatible version of the Altibase server attempts to
connect to the server.


This message leaves history and does not affect the operation of the Altibase server.


Solution


If this error message continues to be logged, find the client trying to connect and reinstall the client with a version compatible with the

server.


Reference


In the versions below Altibase version 5.3.3, the server and the client must have the same cm protocol version to connect from
the client to the server.

From version 5.3.3 or higher of Altibase, backward compatibility between the server and the client is guaranteed, so that
regardless of the cm protocol version, the client can connect to the server of the same version or higher version.
However, in the opposite case, that is, if the version of the client is higher than that of the server, the connection is not made.
The version referred to here means the first 3 digits of the product version. (The patch version of the 4th digit or less does not
matter when checking the version.)


# Connection example according to server and client version


|Col1|Server<br>version|Client<br>version|Connection<br>result|Remark|
|---|---|---|---|---|
|Server Version><br>Client Version<br>(Version 5.3.3<br>or later)|6.3.1|5.3.3|Successful|Backward compatibility guaranteed in version 5.3.3 or later|
|Server Version><br>Client Version<br>(Versions earlier<br>than 5.3.3)|6.3.1|4.3.9|Failed|Backward compatibility guaranteed when both server and client are version 5.3.3 or later.<br>Since the client is earlier than 5.3.3, backward compatibility is not guaranteed, and in the case<br>of 4.3.9, the connection is only possible if the cm protocol version is the same.|
|Server version<br><client version|6.1.1|6.3.1|Failed|If the client version is high, the connection fails regardless of the Altibase version.<br>The client version must be the same as or earlier than the server version.|



# How to check server and client version


How to check the server version


How to check the client version


How to check the version using JDBC Driver


$ java -jar $ALTIBASE_HOME/lib/Altibase.jar
JDBC Driver Info : Altibase Ver = 6 3 1 0 9 for JavaVM v1 4 CMP:7 1 1 Mar 20 2014 17:07:25


How to check version using ODBC library in WINDOWS environment


### ERR-11030 ( 69680) The data file cannot be extended because the requested size is bigger than the maximum size (FID:<0%d>).

Overview

Version

Solution

Reference


Overview


When changing the size of the disk tablespace data file, you may encounter the following error message.


iSQL> alter tablespace DISK_USER_TBS alter datafile '/home/altibase_home/dbs/user.dbf' size 200M;

[ERR-11030 : The data file cannot be extended because the requested size is bigger than the maximum size
(FID:0).]


Version


ALTIBASE HDB 4


Cause


The above error message occurs when the size of the data file with the AUTOEXTEND OFF attribute is changed larger than maxsize.


The autoextend attribute and set the size of the data file can be checked with the following statement (on if autoextend is 1, off if 0).


iSQL> select name, AUTOEXTEND, INITSIZE, MAXSIZE from v$datafiles;

NAME                   AUTOEXTEND INITSIZE       MAXSIZE

---------------------------------------------------------------------------------
-----------------
/home/altibase_home/dbs/temp001.dbf   1      12800        262144
/home/altibase_home/dbs/user.dbf


Data files with autoextend on automatically increase their size up to maxsize, so there is a difference between the initial setting size
(INITSIZE) and the maximum size (MAXSIZE).
However, the maximum size (MAXSIZE) of a data file with autoextend off is set equal to the initial setting size (INITSIZE).
Because of this, if you try to change the size larger than the maximum size (MAXSIZE), the above error may occur.


Solution


After changing the AUTOEXTEND property of the data file to ON, you must proceed with the data file size change operation.
Follow the steps below.


1) Change AUTOEXTEND property
iSQL> alter tablespace DISK_USER_TBS alter datafile '/home/altibase_home/dbs/user.dbf' autoextend on; Alter

success.
2) Change data file size
iSQL> alter tablespace DISK_USER_TBS alter datafile '/home/altibase_home/dbs/user.dbf' size 100M; Alter

success.


Reference


In fact, data files with the autoextend off attribute only make sense for the initial set size (initsize).
When the autoextend off clause is included in the CREATE TABLESPACE statement or the ALTER TABLESPACE statement, the nextsize
and maxsize clauses cannot be used together in addition to the size clause.


When used together, an SQL statement error occurs as shown below.


iSQL> create tablespace user_disk_tbs2 datafile 'user2.dbf' size 1M autoextend off next 1M;

[ERR-31001 : SQL syntax error
line 1: parse error create tablespace USER_DISK_TBS2 DATAFILE 'user2.dbf' SIZE 1M autoextend off NEXT 1M


ALTIBASE HDB 4.3.9 lacks handling of this.
From ALTIBASE HDB version 5, this restriction is reflected, and the maxsize of the data file with the autoextend off attribute is set to the
OS file limit value.


With this change, unlike 4.3.9, maxsize is output as 0 when searching v$datafile,


iSQL> select name, AUTOEXTEND, INITSIZE, currsize, MAXSIZE from v$datafiles;

NAME                AUTOEXTEND INITSIZE       CURRSIZE      MAXSIZE

----------------------------------------------------------------------------------
-------------------
/home/altibase_home/dbs/user.dbf  0      128         128         0


It is also possible to change the size.
iSQL> alter tablespace USER_DISK_TBS alter datafile '/home/altibase_home/dbs/user.dbf' size 8M; Alter

success.

iSQL> select name, AUTOEXTEND, INITSIZE, currsize, MAXSIZE from v$datafiles;

NAME                AUTOEXTEND INITSIZE       CURRSIZE       MAXSIZE

---------------------------------------------------------------------------------
---------------------
/home/altibase_home/dbs/user.dbf  0      128         2048         0


The OS file limit can be checked with ulimit -a.


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

### ERR-11036 The data file is in use.


Version

Symptom
Cause

Solution


Version


All the versions of Altibase


Symptom


The following error occurs when executing alter tablespace ~ drop datafile.


iSQL> alter tablespace SYS_TBS_DISK_DATA drop datafile '/altibase/dbs/DISK_DATA2.dbf';

[ERR-11036 : The data file is in use.|ERR-11036 : The data file is in use.]


Cause


The description of the error can be checked using the altierr utility as follows.


Data files that have been used at least once cannot be deleted.


Even if all the data files have only free space by inserting and then deleting them, data files that have been used once cannot be
deleted.


The above error occurs when you try to drop a data file that has been used at least once.


For reference, data files that have never been used can be dropped.


Solution


There is no way to drop data files that have been used at least once.


To drop the data file, the tablespace must be recreated.


The following steps are required to recreate the tablespace.

### ERR-11049 ( 69705) Too many pages are allocated ( Maximum Number of Pages= #).


Version

Cause

What is MEM_MAX_DB_SIZE?
How to query memory usage
Solution

How to change
Note/Consideration

Disk space
User environment setting (Linux/Unix)
Reference


Version


All the versions of Altibase


Cause


For ALTIBASE memory tablespaces, the sum of all memory tablespaces cannot exceed MEM_MAX_DB_SIZE in
$ALTIBASE_HOME/conf/altibase.properties. This error message occurs because all space is exhausted.


What is MEM_MAX_DB_SIZE?


This refers to the maximum amount of memory that can be used as a memory tablespace (memory table or memory data) stored
in physical memory.
Constraints on the total usage of all memory tablespaces combined.
This is not the maximum size that each of the memory tablespaces can use.
The size of the index created on the memory table is not included.
It also includes historical data that occurs when performing change transactions.
When a change transaction is performed, past data is retained until the transaction is terminated (MVCC technique). In the case
of a memory table, a replica of the record is created in the memory table.
If the maximum value is not specified when creating a memory tablespace, it is automatically expanded by the value set for
MEM_MAX_DB_SIZE.


How to query memory usage


set linesize 1024

set colsize 20
SELECT TO_CHAR(MEM_MAX_DB_SIZE/1024/1024, '999,999,999') '    MAX(M)',
-- MAX(M)  : MEM_MAX_DB_SIZE setting value
TO_CHAR(MEM_ALLOC_PAGE_COUNT*32/1024, '999,999,999') '   TOTAL(M)',
-- TOTAL(M) : Total page size allocated to the memory tablespace. Also refers to the size of the checkpoint
image file.
TO_CHAR((MEM_ALLOC_PAGE_COUNT-MEM_FREE_PAGE_COUNT)*32/1024, '999,999,999') '
ALLOC(M)',       -- ALLOC(M) : Memory amount of memory used by the tablespace
(SELECT TO_CHAR(SUM((FIXED_USED_MEM + VAR_USED_MEM))/1024/1024, '999,999,999')
FROM V$MEMTBL_INFO) '   USED(M)',                                 -- USED(M) :

Memory size in which data is stored among ALLOCs

TO_CHAR((((MEM_ALLOC_PAGE_COUNT-MEM_FREE_PAGE_COUNT)*32*1024)/MEM_MAX_DB_SIZE)*100,
'99.99') 'USAGE(%)' -- USAGE(%) : ALLOC utilization rate compared to MAX
FROM V$DATABASE ;
MAX(M)     TOTAL(M)     ALLOC(M)     USED(M)   USAGE(%)

----------------------------------------------------------------------------------
-------
5,120       920       621       142   12.13

1 row selected.


When ALLOC_SIZE reaches MEM_MAX_DB_SIZE as a result of the above inquiry, 'Too many pages are allocated' error occurs.


Solution


To prevent the following error from occurring, the MEM_MAX_DB_SIZE property value must be increased in
$ALTIBASE_HOME/conf/altibase.properties.


If this value is increased, Altibase DB Size can be increased up to this size. After modifying the properties, you must restart Altibase to
apply it.


After taking the action, it is necessary to take action by checking for some reason the increase in memory tablespace usage and whether
there has been a query or mass change of the usage of each table.


How to change



1.


2.


3.



Stop the Altibase server

```
 $ server stop

```

Change the altibase.properties file


Save after changing MEM_MAX_DB_SIZE in the Altibase server properties file ($ALTIBASE_HOME/conf/altibase.properties).

```
 $ vi $ALTIBASE_HOME/conf/altibase.properties

 MEM_MAX_DB_SIZE    = 2G # MEM_MAX_DB_SIZE

```

Start the Altibase server

```
 $ server start

```


Note/Consideration


Disk space


Memory tablespaces store two sets of 'memory checkpoint image files' on disk for backup purposes. So, it requires twice as much disk
space as the memory data usage.


If MEM_MAX_DB_SIZE large is set, disk usage will also increase, so make sure to free up disk space before changing
MEM_MAX_DB_SIZE.


Ex) If MEM_MAX_DB_SIZE is 60G, 120G of disk space is required.


User environment setting (Linux/Unix)


ulimit -a must be executed to make sure that the settings below are set to the maximum values allowed by the OS.


max memory size
virtual memory


Kernel parameter (AIX, HP-UX)


For AIX, check if data, rss, fsize, etc. are set to -1 in the /etc/security/limits file.
For HP, check that the maxdsiz_64bit value is set large enough via kctune. Even if the maxdsiz_64bit value is less than the
MEM_MAX_DB_SIZE value of the ALTIBASE property, a 'Too many pages are allocated' error may occur. Therefore, the root account


must be set higher than MEM_MAX_DB_SIZE of the ALTIBASE property.
Linux and SunOS are not applicable.


Reference


What is MEM_MAX_DB_SIZE?

### ERR-11075 The transaction has exceeded the lock timeout specified by the user.


Overview

Version

Symptom

1. Occur when executing a DDL statement
2. Occurs when a change transaction is performed on the memory table
3. Occur when executing a SELECT statement using SELECT FOR UPDATE WAIT N (or NOWAIT)
4. Occur in altibase_rp.log in a replication environment
Cause


1. Occur when executing a DDL statement
2. Occur when a change transaction is performed on the memory table
3. Occur when SELECT FOR UPDATE WAIT N (or NOWAIT) is executed
4. Occurs in altibase_rp.log in a replication environment
Solution

Reference


Overview


Error messages that may occur when performing change transactions.


Version


This error message can occur in all versions of Altibase, but the error message differs depending on the version of the Altibase server.


ALTIBASE HDB 4.3.9 ~ 5.3.3
ERR-11075 ( 69749) The transaction exceeds the lock timeout specified by user.


ALTIBASE HDB 5.5.1 or later
ERR-11075 ( 69749) The transaction has exceeded the lock timeout specified by the user.


Symptom


The following are examples of some of the most common symptoms in which this error message occurs.


1. Occur when executing a DDL statement


|Session-1|Session-2<br>DDL(truncate문) 수행 시 에러 발생|
|---|---|
|autocommit off;||
|update test_emp_tbl set emp_no = 10;<br>||
|while executing update...|truncate table test_emp_tbl;<br>[ERR-11075 : The transaction has exceeded the lock timeout specified by<br>the user.]|


2. Occurs when a change transaction is performed on the memory table

|Session-1|Session-2|
|---|---|
|iSQL> autocommit off;<br>Set autocommit off success.<br>iSQL> update tb_test1 set c10=sysdate where<br>c1=1;<br>1 row updated.||
||iSQL> select count(*) from tb_test1;<br>COUNT<br>-----------------------<br>1000000<br>1 row selected.<br>iSQL> alter session set TRX_UPDATE_MAX_LOGSIZE=100000000;<br>Alter success.<br>iSQL> alter system set LOCK_ESCALATION_MEMORY_SIZE=100000000;<br>Alter success.<br>iSQL> update tb_test1 set c10=sysdate;<br>[ERR-11075 : The transaction has exceeded the lock timeout specified by the<br>user.]|



3. Occur when executing a SELECT statement using SELECT FOR UPDATE WAIT N (or NOWAIT)

|Session-1|Session-2|
|---|---|
|autocommit off;<br>update test_emp_tbl set emp_no = 10;||
||select * from test_emp_tbl for update wait 1;<br>[ERR-11075 : The transaction has exceeded the lock timeout specified by the user.]|
||select * from test_emp_tbl for update nowait;<br>[ERR-11075 : The transaction has exceeded the lock timeout specified by the user.]|



4. Occur in altibase_rp.log in a replication environment


In a replication environment, an error may occur in $ALTIBASE_HOME/trc/altibase_rp.log.


[2014/08/28 13:00:14] [FAQINTERNAL:Thread-1398925664] [FAQINTERNAL:Level-2]
ERR-11075(errno=0) The transaction has exceeded the lock timeout specified by the user.

[2014/08/28 13:00:14] [FAQINTERNAL:Thread-1398925664] [FAQINTERNAL:Level-3]
INSERT INTO SYS.TB_TEST1 VALUES ( 1000001,,,,,,,,, 2014-08-28 13:00:09.960371 ); (TID : 35456)


Cause


This error occurs when trying to acquire a lock on an object, but the object is already locked and the lock cannot be acquired.


$ altierr 0x11075
0x11075 ( 69749) smERR_ABORT_smcExceedLockTimeWait The transaction has exceeded the lock timeout

specified by the user.
# *Cause: The transaction failed to lock the object.
# *Action: Increase the transaction's lock timeout value or check whether the data has a transaction with a

long-term lock.


1. Occur when executing a DDL statement


When executing DDL statements, if the target table is already locked by another transaction, DDL execution may fail because the LOCK
for DDL execution cannot be acquired immediately.


This may behave differently depending on the DDL_LOCK_TIMEOUT setting of the Altibase server property.


DDL_LOCK_TIMEOUT = 0 (default)
If the LOCK is not acquired, it is immediately failed.
DDL_LOCK_TIMEOUT = 1
If it cannot acquire LOCK, it waits indefinitely
DDL_LOCK_TIMEOUT = seconds


If LOCK is not acquired during DDL execution, wait for the specified time and try again.


If the LOCK is not acquired even when trying again, it will fail.


2. Occur when a change transaction is performed on the memory table


When the size of the transaction log file exceeds the value of the LOCK_ESCALATION_MEMORY_SIZE property due to a change
transaction performed on the memory table, it switches from record level IX_LOCK to table level X_LOCK. At this time, if IX_LOCK is
locked on another record of the table in another session, the table level X_LOCK acquisition may fail and an error may occur.


3. Occur when SELECT FOR UPDATE WAIT N (or NOWAIT) is executed


A SELECT statement using SELECT FOR UPDATE WAIT N or SELECT FOR UPDATE NOWAIT locks the record and executes it.


However, if a lock is first locked in another session on the same table, an error may occur because the lock cannot be acquired.


4. Occurs in altibase_rp.log in a replication environment


When the transaction to be reflected is waiting for the transaction of the local server to be finished.


|Active Server|Standby Server|
|---|---|
|alter replication rep1 start;||


|Col1|iSQL> autocommit off;<br>Set autocommit off success.<br>iSQL> insert into tb_test1(c1,c10) values(1000001, sysdate);<br>1 row inserted.|
|---|---|
|iSQL> autocommit off;<br>Set autocommit off success.<br>iSQL> insert into tb_test1(c1,c10) values(1000001, sysdate);<br>1 row inserted.||


The insert statement of the active server should be reflected in the standby server, but when the replication transaction cannot be
reflected due to the local transaction of the standby server, an error message is recorded in altibase_rp.log.


This symptom is affected by the value of the REPLICATION_LOCK_TIMEOUT property.


If the server reflecting the redundancy log (standby server in the example above) does not acquire LOCK within the
REPLICATION_LOCK_TIMEOUT (seconds) time, the above error occurs and the redundant transaction attempted to reflect fails.


Solution


Occur when executing DDL
Generally, it is recommended to perform DDL in idle time. If the service is not stopped, X LOCK acquisition may fail
instantaneously. If an error occurs, try performing DDL several times. If the same error still occurs, check whether the target table
is busy or there is a long-run query (a query that takes a long time to execute or a query that has not been committed), and
execute DDL again after taking action.
Occur when performing a change transaction in memory
If the above error occurs due to LOCK_ESCALATION_MEMORY_SIZE, there is a high possibility of a large amount of change
transactions.

Make sure not to make a large number of change operations. It is recommended that the number of records to be changed is
reduced by using conditional clauses and limit clauses and divided into multiple times to perform change transactions.
Occur when executing SELECT FOR UPDATE statement
Repeat the SELECT FOR UPDATE statement until it succeeds.
Find uncommitted transactions and commit or rollback.

Increase the time of the WAIT option.
Occur in a replication environment
When designing for replication, consideration should be given to avoiding simultaneous changes on both servers for the same
record.

When this error occurs, it may cause a problem with the data integrity of both servers, so the data must be checked.


Reference


Additional explanation regarding LOCK_ESCALATION_MEMORY_SIZE
ERR-11118 ( 69912) The update log size '?????' is bigger than TRX_UPDATE_MAX_LOGSIZE '?????'

### ERR-11118 ( 69912) The update log size '?????' is bigger than TRX_UPDATE_MAX_LOGSIZE '?????'


Overview

Version


Symptom
Cause

Solution


Reduce the number of records for UPDATE

Change TRX_UPDATE_MAX_LOGSIZE property setting value
Reference


Related bug


Overview


This document describes an error that occurs while performing a change transaction in the memory table.


Version


Altibase version 4.3.9 or later


Symptom


This error may occur while performing a change transaction on the memory table.





The error code differs depending on the Altibase version.


Altibase 5 or later


ERR-11118 ( 69912) The update log size '?????' is bigger than TRX_UPDATE_MAX_LOGSIZE '?????'


Altibase 4.3.9


ERR-110C3 ( 69827) The update log size '?????' is bigger than TRX_UPDATE_MAX_LOGSIZE '?????'


Cause


This error occurs because the size of the online transaction log created by one change transaction exceeds the
TRX_UPDATE_MAX_LOGSIZE setting value.


TRX_UPDATE_MAX_LOGSIZE is an Altibase server property and serves to prevent excessive use of memory due to versioning of the
memory table created by a large number of change transactions.


Versioning of the memory table?


Altibase uses the Multi-Version Concurrency Control (MVCC) technique for concurrency control. MVCC refers to creating a new version
of the record by executing the DML statement on a copy of the record, leaving the record as it was when a DML statement occurs for a
record. With this technique, lookup transactions for one record are not affected by change transactions.


q, p y g


Due to the characteristics of each disk and memory, the disk table is in-place and the memory table is out-place and different MVCC
techniques are used.


Out-place MVCC of the memory table keeps multiple versions by adding new versions to the new space, leaving the existing records
intact when an update occurs on one record. TRX_UPDATE_MAX_LOGSIZE and LOCK_ESCALATION_MEMORY_SIZE properties are
provided to prevent this from incurring load on the system, such as increased memory.


Since there is no previous version of INSERT, versioning does not occur, and since there is no new version of DELETE, only the delete
flag is set, so multiple versions of versioning do not occur.


Solution


If this error occurs, correct it in one of the ways below.


Reduce the number of records for UPDATE


By reducing the number of records that are changed at one time by an UPDATE statement, the amount of transaction logs created by
one transaction is reduced.


When there are many records that need to be changed in one table









When performing UPDATE on multiple tables in one transaction


Since the TRX_UPDATE_MAX_LOGSIZE property is applied on a per-transaction basis, if multiple statements are used in one transaction
as shown below, TRX_UPDATE_MAX_LOGSIZE may increase until COMMIT or ROLLBACK is performed.


iSQL> AUTOCOMMIT OFF;

iSQL> UPDATE T1 SET C1 = 100;

iSQL> COMMIT;                 -- Shorten the commit cycle.

iSQL> UPDATE T2 SET C1 = 200;

iSQL> COMMIT;


Change TRX_UPDATE_MAX_LOGSIZE property setting value


The default value for the TRX_UPDATE_MAX_LOGSIZE property is 10M. If this value is too small, this can be changed at the session or
system level.


First, this section will describe how to calculate the size of the transaction log that will be created in a specific transaction and the
precautions for changing TRX_UPDATE_MAX_LOGSIZE, and then how to change it.


Calculation of the TRX_UPDATE_MAX_LOGSIZE value of the transaction


This is how to estimate the amount of transaction log to be used by a particular transaction to change TRX_UPDATE_MAX_LOGSIZE.

|Session 1-UPDATE statement execution|Session 2-Query Performance View|
|---|---|
|iSQL> AUTOCOMMIT OFF;<br>iSQL> UPDATE ORDER_LINE SET<br>OL_DELIVERY_D = SYSDATE LIMIT 1;<br>-- Give and execute limit 1||
||Among the results of executing the query below, UPDATE_SIZE * 'Number<br>of records to be updated' is the size of the transaction log that will be<br>created in the transaction.<br>iSQL> SELECT ST.SESSION_ID SESSION_ID, TX.ID<br>TX_ID<br>     , TX.UPDATE_SIZE<br>     , SUBSTR(ST.QUERY, 1, 100) QUERY<br>    FROM V$TRANSACTION TX, V$STATEMENT ST<br>    WHERE TX.ID = ST.TX_ID AND TX.UPDATE_SIZE <><br>0 ;|
|iSQL> ROLLBACK;||



Note/Consideration on changing TRX_UPDATE_MAX_LOGSIZE


It is recommended to set TRX_UPDATE_MAX_LOGSIZE less than LOCK_ESCALATION_MEMORY_SIZE.
To prevent memory increase due to memory table MVCC, TRX_UPDATE_MAX_LOGSIZE and LOCK_ESCALATION_MEMORY_SIZE
properties are provided.
If the size of the transaction log created by one transaction exceeds TRX_UPDATE_MAX_LOGSIZE, the transaction is
error-processed and rolled back. If LOCK_ESCALATION_MEMORY_SIZE is exceeded, the transaction's LOCK mode is switched
from record level IX_LOCK to table level X LOCK.
In the case of X LOCK, it may cause a problem in the service because the query transaction for the target table is also queued.
To prevent this problem, set TRX_UPDATE_MAX_LOGSIZE to be smaller than LOCK_ESCALATION_MEMORY_SIZE so that X LOCK
does not occur.


How to change


How to change property setting value
TRX_UPDATE_MAX_LOGSIZE should be set smaller than LOCK_ESCALATION_MEMORY_SIZE, so check both properties together.


How to change session unit
This is applied to transactions performed after ALTER SESSION is executed.


iSQL> ALTER SESSION SET TRX_UPDATE_MAX_LOGSIZE = 52428800;    -- Value is in bytes


How to change the system level
After ALTER SYSTEM is executed, it is affected by the transaction performed in the new session. The value changed to ALTER
SYSTEM is applied only while the Altibase server is running, and it returns to the default value when the Altibase server is
restarted.


iSQL> ALTER SYSTEM SET TRX_UPDATE_MAX_LOGSIZE = 52428800;


In order to permanently reflect the changes to the Altibase server, change the altibase.properties file as well.


iSQL> ALTER SYSTEM SET TRX_UPDATE_MAX_LOGSIZE = 52428800;


shell> vi $ALTIBASE_HOME/conf/altibase.properties         -- Open the altibase.properties file,
find TRX_UPDATE_MAX_LOGSIZE, change the value, and save.

TRX_UPDATE_MAX_LOGSIZE = 52428800


If the above has done, the changed value can be kept even if the Altibase server is restarted.


Reference


Related bug


In some versions, due to a bug related to TRX_UPDATE_MAX_LOGSIZE, it may not work properly even if the setting value of
TRX_UPDATE_MAX_LOGSIZE is changed.










|Altibase<br>server version|Symptom|Bug|
|---|---|---|
|4.3.9.103 ~<br>4.3.9.133|The default value of TRX_UPDATE_MAX_LOGSIZE is 10M, but the value of the<br>TRX_UPDATE_MAX_LOGSIZE column of V$SESSION is set to 0 (unlimited).|BUG-20511|
|4.3.9.163 ~<br>4.3.9.165|This is a bug that reads TRX_UPDATE_MAX_LOGSIZE incorrectly, and the error does not occur when an<br>error should occur due to TRX_UPDATE_MAX_LOGSIZE.|BUG-26311|


### ERR-11183 ( 70019) Insufficient page descriptor area in the temp table.

Overview

Version

Symptom
Cause

Solution


Overview


This document describes the cause and solution of the occurrence of 'ERR-11183 (70019) Insufficient page descriptor area in the temp
table' that occurs when executing a query.


Version


Altibase Server 6.3.1 or later

Altibase server up to 7.1.0.5.0

Altibase 7.1.0.5.1 or later reflects BUG-48369, so this error does not occur.


Symptom


This can occur when a disk table is used in a query statement and a query statement that requires SORT or HASH operation processing
is executed.


Cause


This error occurs when the following conditions are satisfied.


The maximum size of the disk temporary tablespace is set larger than TEMP_MAX_PAGE_COUNT, and
When a query statement that requires a disk temporary tablespace with a size exceeding TEMP_MAX_PAGE_COUNT is executed.


Altibase server allocates and uses a certain size in memory for fast operation when SORT/HASH operation is required in the process of
query processing for disk tables. If all the memory of the specified size is used and additional space for SORT/HASH operations is
needed, use a disk temporary tablespace. At this time, the total number of pages that can be used as a disk temporary tablespace is
determined by the TEMP_MAX_PAGE_COUNT property.


Example of error occurrence: Insufficient page descriptor area in the temp table


The maximum size of the disk temporary tablespace is set to 2G, and the value of the TEMP_MAX_PAGE_COUNT property is set to 32767
(256MB),


iSQL> set vertical off;

iSQL> set linesize 1024

iSQL> set colsize 25


-- The disk temporary tablespace is set to use up to 2G.
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


-- The unit of the TEMP_MAX_PAGE_COUNT property value is the number of pages, and in terms of size, it is

256MB.

   - The result below means that the number of pages that can be used as a disk temporary tablespace is

256MB.

iSQL> SELECT NAME, VALUE1, VALUE1*8192 FROM V$PROPERTY WHERE NAME =
'TEMP_MAX_PAGE_COUNT';

NAME            VALUE1           VALUE1*8192

--------------------------------------------------------------------------------
TEMP_MAX_PAGE_COUNT    32767           268427264

1 row selected.


When a query statement whose size for SORT operation exceeds the TEMP_MAX_PAGE_COUNT property value of 32767 (256MB) is
executed.


iSQL> select count(*) from (select count(*) from t, t2, t3 group by t.c2, t2.c2, t3.c2);

[ERR-11183 : Insufficient page descriptor area in the temp table.]


If the disk temporary tablespace usage is queried while executing the query, it can be seen that the disk temporary tablespace usage is
close to the TEMP_MAX_PAGE_COUNT property value.


-- Query disk temporary tablespace usage when executing a query

iSQL> set vertical on;

iSQL> set colsize 100
iSQL> SELECT TO_CHAR(SYSDATE, 'HH:MI:SS') TIME,
'TEMP_T_STATS',

CREATE_TIME, DROP_TIME,

SS.ID SESSION_ID,

TRANSACTION_ID TX_ID,

SS.AUTOCOMMIT_FLAG,

STMT.EXECUTE_FLAG,

SQL_TEXT,

STATE,

ESTIMATED_OPTIMAL_SORT_SIZE,

ESTIMATED_OPTIMAL_HASH_SIZE,

ALLOC_WAIT_COUNT,

WORK_AREA_SIZE,

NORMAL_AREA_SIZE
FROM X$TEMPTABLE_STATS TEMP,
V$STATEMENT STMT,
V$SESSION SS

WHERE TRANSACTION_ID = STMT.TX_ID
AND SS.ID <> SESSION_ID()

AND STMT.SESSION_ID = SS.ID

ORDER BY SESSION_ID;

TIME            : 15:39:03

'TEMP_T_STATS'       : TEMP_T_STATS

CREATE_TIME         : 20161129_153221

DROP_TIME          : 20161129_153311

SESSION_ID         : 1

TX_ID            : 51842

AUTOCOMMIT_FLAG       : 1

EXECUTE_FLAG        : 0
SQL_TEXT          : select count(*) from (select count(*) from t, t2, t3 group by t.c2, t2.c2, t3.c2)

STATE            : SORT_INSERTNSORT

ESTIMATED_OPTIMAL_SORT_SIZE : 562205696

ESTIMATED_OPTIMAL_HASH_SIZE : 0

ALLOC_WAIT_COUNT      : 0

WORK_AREA_SIZE       : 1048576

NORMAL_AREA_SIZE      : 267911168       -- Disk temporary tablespace usage. Similar to the size of
TEMP_MAX_PAGE_COUNT converted to bytes.


Solution


Change the value of the TEMP_MAX_PAGE_COUNT property according to the maximum value of the disk temporary tablespace.


1. Check the maximum value of disk temp tablespace
TEMP_MAX_PAGE_COUNT should be set on the assumption that all disk temporary tablespaces will be used to the maximum. Therefore,
check the sum of the maximum values of all disk temporary tablespaces created in the Altibase server with the following query.


2. Calculate TEMP_MAX_PAGE property appropriate value
The unit of the TEMP_MAX_PAGE_COUNT property is the number of pages, and the value is calculated using the formula below.


TEMP MAX PAGE COUNT = Sum of maximum disk temporary tablespaces / 8192


Example of TEMP_MAX_PAGE_COUNT calculation


If the total sum of the maximum disk temporary tablespaces is 17179869184 bytes (16GB), 17179869184/8192 = 2097152,
and the value of the TEMP_MAX_PAGE_COUNT property is 2097152.


TEMP_MAX_PAGE_COUNT setting value for each total maximum of disk temporary tablespaces


TEMP_MAX_PAGE_COUNT = 1048576 for 8G


TEMP_MAX_PAGE_COUNT = 2096128 for 16G


TEMP_MAX_PAGE_COUNT = 4192256 for 32G


TEMP_MAX_PAGE_COUNT = 8388608 for 64G


3. Change TEMP_MAX_PAGE_COUNT property


TEMP_MAX_PAGE_COUNT can be changed at the system level during Altibase operation.


ALTER SYSTEM SET TEMP_MAX_PAGE_COUNT = value;


Check V$PROPERTY to check the changed value.


SELECT NAME, VALUE1 FROM V$PROPERTY WHERE NAME = 'TEMP_MAX_PAGE_COUNT';


Altibase server configuration file is also changed so that the value changed to ALTER SYSTEM is reflected even after restarting the
Altibase server.


shell> cd $ALTIBASE_HOME/conf

shell> vi altibase.properties    # If TEMP_MAX_PAGE_COUNT does not exist in the altibase.properties file, if
it is added, the existing value is changed.

TEMP_MAX_PAGE_COUNT = value;


4. Considerations when changing the TEMP_MAX_PAGE_COUNT property
The following three properties are affected by TEMP_MAX_PAGE_COUNT.
TOTAL_WA_SIZE
SORT_AREA_SIZE
HASH_AREA_SIZE


So, if TEMP_MAX_PAGE_COUNT is changed, these properties must be changed as well.


The recommended values for each property are as follows. The recommended value is calculated according to the default ratio, and the
appropriate value of the property may be changed during operation.


TOTAL_WA_SIZE: 256 times TEMP_MAX_PAGE_COUNT
SORT_AREA_SIZE: 2 times TEMP_MAX_PAGE_COUNT
HASH_AREA_SIZE: 8 times TEMP_MAX_PAGE_COUNT


For example, when changing to TEMP_MAX_PAGE_COUNT = 1048576, the recommended value of each property is as follows.


TOTAL_WA_SIZE = 1048576*256 = 268435456 (Unit is bytes)
SORT_AREA_SIZE = 1048576*2 = 2097152 (unit is byte)
HASH_AREA_SIZE = 1048576*8 = 8388608 (Unit is byte)


Like TEMP_MAX_PAGE_COUNT, the following three properties can be changed at the system level during Altibase operation.


ALTER SYSTEM SET TOTAL_WA_SIZE = value;

ALTER SYSTEM SET SORT_AREA_SIZE = value;

ALTER SYSTEM SET HASH_AREA_SIZE = value;


Check V$PROPERTY to check the changed value.


SELECT NAME, VALUE1 FROM V$PROPERTY WHERE NAME IN ('TOTAL_WA_SIZE', 'SORT_AREA_SIZE',
'HASH_AREA_SIZE');


The altibase server configuration file is also changed so that the value changed to ALTER SYSTEM is reflected even after restarting the
Altibase server.


shell> cd $ALTIBASE_HOME/conf

shell> vi altibase.properties    # Find and change each property in the altibase.properties file.

TOTAL_WA_SIZE            = 134217728 # default = 134217728

SORT_AREA_SIZE            = 1048576  # default = 1048576

HASH_AREA_SIZE            = 4194304  # default = 4194304


5. Effect of property change


In the case of the TOTAL_WA_SIZE property, the ALLOC_SIZE and MAX_TOTAL_SIZE of V$MEMSTAT increase immediately after setting,


and the memory of the Altibase server process also increases.


The area where the memory increases depend on the Altibase version. In the case of Altibase 7, the Temp_Memory area increases, and
in the case of Altibase 6.3.1 and 6.5.1, the Storage_Disk_Buffer area increases.


How to check V$MEMSTAT is as follows.









In the case of Unix/Linux, check whether the memory of the Altibase server process is increased with the ps command.


When checking immediately after TOTAL_WA_SIZE is changed, vsz increases, and when sort/hash operation occurs, rss increases.












### ERR-11184 ( 70020) Insufficient free space in work area

Overview

Version

Symptom
Cause

Solution


How to check the work area setting value
How to change the work area setting value
Precautions when changing the work area setting value


Overview


This document describes the cause of the ERR-11184 (70020) Insufficient free space in work area error that occurs when executing a
query and how to fix it.


Version


Altibase server 6.3.1 or later


Symptom


This can occur when a disk table is used in a query statement and a query statement that requires SORT or HASH operation processing
is executed.


Cause


This error occurs due to insufficient memory space called Work Area.


Work Area refers to a memory space of a certain size reserved by the OS when the Altibase server is running for better performance
when performing SORT/HASH operations on disk table data.


When SORT or HASH operation is required when executing a query, it is allocated and used in the work area as much as a predetermined
size. If SORT operation is required, it is allocated as much as SORT_AREA_SIZE in the work area and used. If the HASH operation is
required, it is allocated as much as HASH_AREA_SIZE in the work area and used.


Multiple transactions requiring SORT/HASH operations can be executed at the same time. At this time, if trying to get SORT_AREA_SIZE
or HASH_AREA_SIZE from the work area, but there is no free memory to allocate in the work area, this error occurs.


Solution


It is caused by insufficient work area, so the size of the work area must be increased larger than the current value.


The size of the work area can be set with the Altibase server property TOTAL_WA_SIZE.


How to check the work area setting value


Check the current setting value with the sentence below.


SELECT NAME, VALUE1 FROM V$PROPERTY WHERE NAME = 'TOTAL_WA_SIZE';


How to change the work area setting value


Change with ALTER SYSTEM statement.


ALTER SYSTEM SET TOTAL_WA_SIZE = value ; -- value is in bytes.


The Altibase server configuration file is also changed so that the value changed to ALTER SYSTEM is reflected even after
restarting the Altibase server.


shell> cd $ALTIBASE_HOME/conf

shell> vi altibase.properties    # Find and change the TOTAL_WA_SIZE property in the
altibase.properties file.

TOTAL_WA_SIZE            = 134217728 # default = 134217728


Precautions when changing the work area setting value


If TOTAL_WA_SIZE is changed larger than the current setting value, the size of V$MEMSTAT increases, and Altibase server
process memory usage and VSZ also increase.
For Altibase 7 or higher, the Temp_Memory area of V$MEMSTAT increases and
In the case of Altibase 6.3.1 and 6.5.1, the Storage_Disk_Buffer area of V$MEMSTAT increases.
If the ALTER SYSTEM SET TOTAL_WA_SIZE statement is executed while a query statement that requires a disk SORT/HASH
operation is executed (transaction using a work area), this statement waits until the previously executed transaction is
terminated.
ALTER SYSTEM SET TOTAL_WA_SIZE = ... If a query statement that requires a disk SORT/HASH operation is executed while the
statement is being executed, the transaction waits until the ALTER SYSTEM statement is finished.

### ERR-21010 Value overflow.


Version

Symptom
Cause

Solution
Notes/Considerations


Version


All the versions of Altibase


Symptom


The following error occurs when executing INSERT/UPDATE, etc.


[ERR-21010: Value overflow]


Cause


The description of the error can be checked using the altierr utility as follows.





In other words, it is an error that occurs when the input value exceeds the range supported by the data type.


# Example


iSQL> create table test(i1 integer);

Create success.

iSQL> insert into test values(2147483648);

[ERR-21010 : Value overflow
0001 : insert into TEST values(2147483648)

^     ^

]
iSQL> insert into test values(2147483647);

1 row inserted.


The range of integer type values is -2,147,483,647 ~ 2,147,483,647 integer values.


Therefore, the error occurred because the value to be stored in the column is out of the range of the integer value.


Solution


Check if the input value to be saved in a specific column exceeds the maximum size of the column data type.


If it exceeds the maximum size, it is necessary to modify the input value or change the data type of the column.


Notes/Considerations


The range of values for each data type supported by Altibase can be found in the General Reference manual at http://support.altibase.co

m/en/manual/ or GitHub: https://github.com/ALTIBASE/Documents.

### ERR-21011 : Invalid literal


Overview

Version

Cause


Overview


This document describes the causes and examples of invalid literal error.


Version


All the versions of Altibase


Cause


It occurs when the data types between comparison targets do not match when using conversion functions such as TO_NUMBER and
CAST or comparison operators.


It can also occur when you have a value that cannot be converted to the data type you want to convert during automatic casting.


Case 1. When using UNION and UNION ALL, the data type of the column to be mapped is different.


iSQL> SELECT 0 from DUAL

2 UNION

3 SELECT 'A' from DUAL;

0

-------------
0

[ERR-21011 : Invalid literal]

1 row selected.


Case 2. When the value given to the TO_NUMBER function is a character type that cannot be converted to a numeric


type.


iSQL> SELECT TO_NUMBER('1-1') from DUAL;

[ERR-21011 : Invalid literal
0001 : SELECT TO_NUMBER('1-1') from DUAL

^  ^

]

iSQL>


Case 3. When there is a data value that cannot be converted automatically in a column used in a comparison operation.


iSQL> CREATE TABLE T (NO CHAR(1));

Create success.

iSQL> INSERT INTO T VALUES('1');

1 row inserted.

iSQL> INSERT INTO T VALUES('2');

1 row inserted.

iSQL> SELECT * FROM T WHERE NO = 1;     -- Compare the value of the CHAR type column with the
numeric data. NO column value is automatically converted to numeric type.
NO                     -- Since only values that can be converted to numeric type exist in the NO

column, it is executed without error.

-----
1

1 row selected.


iSQL> INSERT INTO T VALUES('A');      -- A value that cannot be converted to a numeric type is entered

in the NO column.

1 row inserted.

iSQL> SELECT * FROM T WHERE NO = 1;     -- As the value of the NO column is automatically converted
into a numeric type, an invalid literal error occurs due to the value of'A'.

[ERR-21011 : Invalid literal]


iSQL> SELECT * FROM T WHERE NO = '1';    -- For character columns, single quotation marks (') must be
used for comparison values.

NO

-----
1

1 row selected.


iSQL> INSERT INTO T VALUES(' ');      -- An Invalid literal error occurs even if the NO column contains

blank characters.

1 row inserted.

iSQL> SELECT TO_NUMBER(NO) FROM T;

[ERR-21011 : Invalid literal]


iSQL> SELECT TO_NUMBER(TRIM(NO)) FROM T;  -- In the case of space characters, the error can be
eliminated by using the TRIM function.
TO_NUMBER(TRIM(CODE))

-----------------------
1

2

3 rows selected.

iSQL>

### ERR-31283 Unable to create a primary key or a unique key constraint in the local non-prefixed index.


Version

Symptom
Cause

Solution

Reference


Version


Altibase version 6.1.1 or earlier


Symptom


The following error occurs when creating PK or UNIQUE INDEX in the partition table.


[ERR-31283: Unable to create a primary key or a unique key constraint in the local non-prefixed index.]


Cause


The description of the error can be checked using the altierr utility as follows.





The global index is not supported in versions of Altibase 6.1.1 or earlier.


Therefore, all partition indexes are local indexes, and local non-prefixed indexes cannot be created with PK or UNIQUE INDEX.


The reason that local non-prefixed indexes cannot be created with PK or UNIQUE INDEX is that even if the column value is the only value
within a specific partition, it cannot be guaranteed to be unique across the table.
(To check the UNIQUE attribute in the entire table, the entire partition must be examined, but the local index checks the UNIQUE attribute
only within a specific partition.)


Solution


1. PK or UNIQUE INDEX must be created as a prefixed index. That is, PK or UNIQUE INDEX must have the same partitioning key column
and index column.


2. In order to create an index with a column that is not the same as the partitioning key column, it can be created with NON-UNIQUE
INDEX.


3. If it is upgraded to Altibase version 6.3.1 or higher, PK or UNIQUE INDEX can be created as a global index.


# Example


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


1. An example of creating a local prefixed index as PK by changing the PK column order.


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


2. An example of creating a local non-prefixed index as a non-unique index without creating a PK.


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


3. An example of creating a PK with a global index after upgrading to version 6.3.1.


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


Reference


# Index type for the partitioned table














|Class condition 1|Class condition 2|Class condition 3|Index type|Support/Not Supported|
|---|---|---|---|---|
|The index is partitioned.|index part key = table part<br>key|index part key = index<br>key|(Partitioned) Local prefixed Index|Supported|
|||index part key != index<br>key|(Partitioned) Local nonprefixed<br>Index|Supported|
||index part key != table part<br>key|index part key = index<br>key|(Partitioned) Global prefixed<br>Index|Not supported|
|||index part key != index<br>key|(Partitioned) Global nonprefixed<br>Index|Not supported|
|The index is not<br>partitioned.|||Nonpartitioned global index|Supported in version 6.3.1 or<br>later|



The distinction between prefixed and nonprefixed indexes is due to the unique property.


In the case of a nonprefixed index, even if it is unique within a partition, it is not guaranteed to be unique across the table.


Therefore, nonprefixed indexes cannot be created with PK or UNIQUE INDEX.

### ERR-41059 ( 266329) Task pool overflow. Check properties.


Version

Symptom
Cause


When the number of new connections increases

When all service threads are in EXECUTE state and a new connection occurs

When a new connection occurs while the number of transactions reaches TRANSACTION_TABLE_SIZE

How to check


Checklist

How to check MAX_CLIENT setting value
How to check the number of sessions

How to check the number of tasks

Solution


Change MAX_CLIENT property
Review application


Version


Altibase HDB 5 or later


Symptom


When a new connection attempt from the client to the Altibase server fails with the following error message,


[ERR-91015 : Communication failure.]


The following error message can be seen in the altibase_boot.log of the Altibase server.


ERR-41059(errno=16) Task pool overflow. Check properties.
Dispatcher failed callback


Cause


This occurs when the number of tasks created in the Altibase server reaches MAX_CLIENT.


Task is an object created when a new connection is made to the Altibase server. The maximum number of simultaneous creations is
affected by the value of the Altibase server property MAX_CLIENT.


When the number of currently created tasks reaches MAX_CLIENT and a new task object cannot be created, a task pool overflow

message appears.


MAX_CLIENT also refers to the maximum number of sessions that can be connected at the same time, but the task is affected by the
same properties because it is eventually mapped to a session.


The following are possible causes.


When the number of new connections increases


This can happen when the number of new connections increases and the number of tasks exceeds MAX_CLIENT.


When all service threads are in EXECUTE state and a new connection occurs


If a new connection fails while all service threads are in EXECUTE state, the connection remains in the form of a task in the Altibase
server. Therefore, even if the connection fails for this reason, the number of tasks increases as a new connection occurs.


When the connection fails as shown below,


$ is -silent

[ERR-5104D : Connection timeout.]


If the number of tasks exceeds MAX_CLIENT, the connection failure error message changes as follows.


$ is -silent

[ERR-91015 : Communication failure.]


When a new connection occurs while the number of transactions reaches TRANSACTION_TABLE_SIZE


If a new connection fails while the number of concurrent transactions reaches TRANSACTION_TABLE_SIZE, the connection remains in
the form of a task in the Altibase server. Therefore, even if the connection fails for this reason, the number of tasks increases as a new
connection occurs.


When the connection fails as shown below,


$ is -silent

[ERR-5104D : Connection timeout.]


If the number of tasks exceeds MAX_CLIENT, the connection failure error message changes as follows.


$ is -silent

[ERR-91015 : Communication failure.]


In this case, the following message appears in altibase_boot.log.


TRANSACTION_TABLE_SIZE is full !!

Current TRANSACTION_TABLE_SIZE is 1024

Please check TRANSACTION_TABLE_SIZE


How to check


Checklist


To find the cause of the task pool overflow, the following items must be checked.


MAX_CLIENT property setting value
Number of sessions connected to Altibase server
If the number of sessions connected to the Altibase server is equal to MAX_CLIENT, it is caused by increased sessions. If it is
less than MAX_CLIENT, check the number of tasks.
Number of tasks created in Altibase server
If the number of sessions is less than MAX_CLIENT and the number of tasks is equal to or greater than MAX_CLIENT, you can
suspect the cause below.



1.

2.



When all service threads are in EXECUTE state and a new connection occurs and the task is increased.

When the number of transactions reaches TRANSACTION_TABLE_SIZE and a new connection occurs and the task increases


$ALTIBASE_HOME/trc/altibase_boot.log
If the number of transactions exceeds TRANSACTION_TABLE_SIZE, the message TRANSACTION_TABLE_SIZE is full is left.



How to check MAX_CLIENT setting value


Task pool overflow occurs when the number of tasks exceeds the value of the MAX_CLIENT property, so check the value of this property
first.


When iSQL connection is possible


iSQL> set linesize 1024;

iSQL> set colsize 30;
iSQL> SELECT NAME, VALUE1 FROM V$PROPERTY WHERE NAME = 'MAX_CLIENT';

NAME              VALUE1

------------------------------------------------------------------
MAX_CLIENT           1000

1 row selected


When iSQL connection is not possible


$ grep MAX_CLIENT $ALTIBASE_HOME/conf/altibase.properties


How to check the number of sessions


When iSQL connection is possible


If iSQL access is available, the number of sessions can be checked with the performance view, and through this, you can infer
the cause of task pool overflow to some extent.
If the current number of sessions is compared with the MAX_CLIENT value, and the value is the same, the increase in sessions is
the cause.

If the current number of sessions is less than MAX_CLIENT, it could be due to two other things than the session growth.





When iSQL connection is not possible


If it is difficult to connect to iSQL, the number of sessions must be checked with the information on the OS.
Depending on the client's connection method, there are two ways to check it.
In the case of connecting using both TCP and IPC methods, the user can add up the results and compare them with
MAX_CLIENT to determine whether the increase in sessions or other parts are the causes.









How to check the number of tasks


When iSQL connection is possible


If the number of sessions is less than MAX_CLIENT, other causes should be investigated.
Check the number of tasks with the command below and compare the number of tasks with MAX_CLIENT. The value of logon
current means the number of tasks created and can be greater than the number of sessions.


iSQL> SELECT NAME, VALUE FROM V$SYSSTAT WHERE NAME = 'logon current';


If the number of sessions is less than MAX_CLIENT and the value of logon current is equal to or greater than MAX_CLIENT, there
are two possible causes:
-When all service threads are in EXECUTE state and a new connection occurs and the task increases

-When a new connection occurs while the number of transactions reaches TRANSACTION_TABLE_SIZE and the task increases
When iSQL connection is not possible


The number of created tasks can be checked by the logon current value of v$sysstat. However, if a task pool overflow occurs,
you may not be able to execute the above statement because a new connection cannot be established.
In this case, the number of tasks must be checked with the number of open files in the Altibase server process with the lsof
command.





On Solaris, the pfiles command can be used instead of lsof.


$ pfiles PID | grep sock


sockname: AF_INET 0.0.0.0 port: 21109          # LISTEN
sockname: AF_INET 127.0.0.1 port: 21109         # A session in which the connection was
established normally, and this is also included in the task.
sockname: AF_INET 127.0.0.1 port: 21109
sockname: AF_INET 127.0.0.1 port: 21109
sockname: AF_INET 127.0.0.1 port: 21109
sockname: AF_INET 0.0.0.0 port: 0            # If all service threads are in EXECUTE state
or the connection fails due to exceeding TRANSACTION_TABLE_SIZE, the remaining tasks.
sockname: AF_INET 0.0.0.0 port: 0
sockname: AF_INET 0.0.0.0 port: 0


Solution


Change MAX_CLIENT property


If there are many actual simultaneous connection sessions, you need to change MAX_CLIENT.


When the number of simultaneous connection sessions increases, the number of concurrent transactions increases, and in the case of
Unix/Linux systems, the number of open files increases.


Therefore, if you change MAX_CLIENT larger than the existing value, the following values must be changed as well.


TRANSACTION_TABLE_SIZE
max open files


Refer to "Notes/Considerations when increasing the number of concurrent connection sessions (MAX_CLIENT)"


Review application


If the application has the following characteristics, it is necessary to check again.


Unless the above processing is inevitable due to the nature of the service, consider changing the session to end immediately after the
transaction is completed.


If keep making new connections
Maintaining unnecessarily connected sessions even though they no longer need to be connected

### ERR-71018 ( 462872) Failed to invoke a system function, read() or Failed to invoke the read() system function


Overview

Type of error message

ALTIBASE HDB 4 ~ ALTIBASE HDB 5.3.3

ALTIBASE HDB 5.5.1 ~ later version

Explanation of error messages
Cause


Major error code
Major occurrence case
Solution

Reference


Overview


When connecting to the DB using the TCP connection type When the DB client program does not close the DB connection (session
close) normally, related error messages are recorded in altibase_boot.log.


This document describes the type and cause of the message.


Type of error message


Error messages are recorded in all versions of ALTIBASE HDB, and error messages vary slightly depending on the ALTIBASE HDB
version.


ALTIBASE HDB 4 ~ ALTIBASE HDB 5.3.3


ERR-71018(errno=238) Failed to invoke a system function, read()


y


ERR-71019(errno=104) Failed to invoke a system function, write()


ALTIBASE HDB 5.5.1 ~ later version


ERR-71018(errno=238) Failed to invoke the read() system function


ERR-71019(errno=104) Failed to invoke the write() system function


Explanation of error messages


The Altibase server has a 'session manager thread' that monitors the connection between the client and the Altibase server.


In general, when a client process terminates abnormally, the session connected with that client can immediately detect its status.
However, when the work inside the Altibase server, which is not related to the session work, is being performed for a long time, the
session cannot check the connection status between the client and the Altibase server. So, a 'session management thread' is placed to
periodically monitor the connection status of the session.


ERR-71018(errno=113) Failed to invoke a system function, read()
ERR-71019(errno=104) Failed to invoke a system function, write()


The above error codes (ERR-71018,71019) are messages indicating that this thread has detected that the connection with the client has
been disconnected and that the session has been cleaned up.


Error code ERR-71018 means its waiting for the client's request,
Error code ERR-71019 means that it has detected that the connection has been lost while responding to the client.


Cause


The cause of the disconnection can be inferred through the system error code errno.


ERR-71018(errno=113) Failed to invoke a system function, read()


ERR-71019(errno=104) Failed to invoke a system function, write()


Among the above error messages, errno=113 and errno=104 represent system error codes.


Major error code


The mainly occurring errors are as follows.


ECONNRESET


This error code sets ECONNRESET to errno when the Altibase server receives an RST packet from the client.
The RST packet is when the client announces that the connection is no longer valid.

|OS|System error code|
|---|---|
|Linux|104|
|AIX|73|
|HP-UX|232|
|SUN|131|
|Windows|10054|



ETIMEDOUT


In TCP communication, if there is no response to the session, the OS tries to retransmit the packet several times to check the
connection status.


If there is no response during the set time, ETIMEDOUT occurs.

|OS|System error code|
|---|---|
|Linux|110|
|AIX|78|
|HP-UX|238|
|SUN|145|
|Windows|10060|



To check system error code
For Linux, error codes are defined in the /usr/include/asm-x86_64/errno.h file.


In the case of AIX, error codes are defined in the /usr/include/errno.h file.


If there is a header file (errno.h) defined for the error code in other OS, the meaning of the error code can be checked
by referring to the file.


Major occurrence case


This can often occur in situations where the TCP session connected between the DB client and the DB server is forcibly terminated.


L4, when idle TCP session is forcibly organized by firewall
LAN card, mechanical error of other network equipment
Abnormal termination or restart of DB client program


Solution


There is no action that the Altibase server can take as a message indicating that the Altibase server has detected that the connection to
the client has been lost and has cleaned up the fine lines.


Reference


In a replication environment, the same error message may occur in altibase_rp.log.
This occurs when the redundant sender detects that the receiver is shutting down during replication log transmission.

### ERR-71019(errno=104) Failed to invoke a system function, write()


FAQ(ENGLISH) / Home/ 09. Error message/ ERR-71018 (462872) Described in Failed to invoke a system function, read() or
Failed to invoke the read() system function.


URL: ERR-71018 ( 462872) Failed to invoke a system function, read() or Failed to invoke the read() system function

### ERR-91015 ( 593941) Communication failure


Overview


Version


Symptom


Cause and Solution


When trying to connect to the Altibase server


When occurs while connected to the Altibase server


When the session is terminated by an Altibase server property


When the session is terminated by the sysdba user


When running the database server


Overview


This document describes ERR-91015 (593941) Communication failure.


Version


All the versions of Altibase HDB


Symptom


ERR-91015 (593941) Communication failure errors can occur in various environments as follows.


When trying to connect to the Altibase server
When connecting to an Altibase server, this error occurs mainly when using iSQL.





When occurs while connected to the Altibase server


iSQL> SELECT * FROM CUSTOMERS;

[ERR-91015 : Communication failure.]


When running the Altibase server


Cause and Solution


When trying to connect to the Altibase server


According to the ALTIBASE HDB compatibility policy, this error may occur when attempting to connect from a higher version of the
Altibase client to a lower version of the Altibase server than the client.


In case of this reason, various types of messages are displayed in the altibase_boot.log on the Altibase server, depending on the version
of the Altibase server. (However, certain versions may not leave a message at all.)


Therefore, if this error occurs when connecting to the Altibase server, first check the version of the Altibase server and client. If the client
version is later than the server version, you must match the client version to the server version or install and use an earlier version than
the server version.


How to check ALTIBASE HDB server version


How to check ALTIBASE HDB client version


Or, the version can be checked on the banner when connecting to iSQL.





When occurs while connected to the Altibase server


When the session is terminated by an Altibase server property


If the session is terminated by the Altibase server properties FETCH_TIMEOUT, UTRANS_TIMEOUT, IDLE_TIMEOUT, a
communication failure message may occur in the client.
For this reason, if the session is terminated, an error message stating that the session was terminated due to the timeout setting
remains in the altibase_boot.log on the Altibase server side as shown below. (altibase_boot.log is located under the
$ALTIBASE_HOME/trc directory. $ALTIBASE_HOME is the installation location of the Altibase server.)









Please refer to the page below for details on session properties and how to take action.

FETCH_TIMEOUT : [Notify : Fetch Timeout] Session Closed by Server.
UTRANS_TIMEOUT : TBA
IDLE_TIMEOUT : TBA


When the session is terminated by the sysdba user


sysdba ALTER DATABASE database_name SESSION CLOSE session_id; Communication failure error may occur even if the
session is forcibly terminated with a sentence.
In this case, no additional error information is left on the Altibase server or client-side.


When running the database server


If the Altibase server properties are not set correctly, a communication failure error may occur when the Altibase server is started up.
In some cases, it may be difficult to find the cause with the log displayed on the terminal, so find out which property is caused by the
following information.


Log output on terminal
altibase_boot.log file (located in $ALTIBASE_HOME/trc, $ALTIBASE_HOME is the installation location of the Altibase server.)
altibase.properties file (located in $ALTIBASE_HOME/conf)

### How to check the 8-digit errorcode of altibase_qp.log


Version

Symptom

How to check the 8-digit error code


Version


Version 6.1.1 or earlier.


In version 6.3.1 or later, it is expressed as a 5-digit error code.


Symptom


Depending on the version of Altibase, the expression method of the error code in $ALTIBASE_HOME/trc/altibase_qp.log is different.


# Example of 6.1.1 version (expressed as an 8-digit error code)


[EXEC_DDL_BEGIN : DROP USER ALTITEST CASCADE]

[2013/04/01 11:02:17] [Thread-1105209696] [Level-2]

[EXEC_DDL_END : FAILURE] errorcode 822329545


# Example of 6.3.1 version (5 digit error code and error message are output)


[EXEC_DDL_BEGIN : DROP USER ALTITEST CASCADE]

[2014/05/21 15:12:48] [Thread-1157658976] [Level-2]

[EXEC_DDL_END : FAILURE] ERR-3103c : Undefined user name. The user specified as the owner of a table
or an object was not found in the database.

0001 : DROP USER ALTITEST CASCADE

^    ^


In version 6.3.1 and later, error codes and messages that can be checked directly from altierr are displayed, so there is no difficulty in
checking errors, but in versions below 6.1.1, there are no unknown error codes and error messages, making it difficult to check the
contents of errors.


How to check the 8-digit error code


Convert an 8-digit decimal error code to a Hexa value. (Use Windows calculator)


The first 5 digits of the converted number are the error code.


For example, if you convert the error code 822329545 above to Hexa, it becomes 3103C0C9.


Then the actual error code is 3103C.


The error code can be checked by using altierr.

### Not found data


Overview

Version

Symptom
Cause

When COMMIT/ROLLBACK is performed in the cursor (CURSOR) OPEN state
Solution

When COMMIT/ROLLBACK is performed in the cursor (CURSOR) OPEN state

1. Separation of fetch session and modified DML session
2. Repetitively open the cursor after declaring the cursor only enough to be contained in the communication
buffer

Reference


Differences by version


Overview


This document describes an error that occurs during the record fetch process by using a cursor to process a select statement that
returns multiple records.


Version


Altibase 5.3.3

Altibase 5.5.1

Altibase 6.1.1


Symptom


To process a query statement that returns multiple records, a cursor (CURSOR) must be used in the following process.



1.

2.

3.

4.



DECLARE CURSOR

OPEN CURSOR

FETCH CURSOR
CLOSE/RELEASE CURSOR



The cursor was used as above, but not found data error occurs at some point, even though the record to FETCH is still remaining during
the "3. Cursor FETCH" state.


Below is an example where an error occurs when using the cursor and the result of the error.


Cause


When COMMIT/ROLLBACK is performed in the cursor (CURSOR) OPEN state


Altibase follows the ANSI standard and does not support the fetch across commit method. Therefore, if COMMIT or ROLLBACK is
executed after opening the cursor, the cursor is forcibly closed according to the ANSI standard.


This is a method that performs COMMIT while fetching the unit record after opening the cursor, which is not recommended by
the ANSI standard.


For this reason, if an application executes COMMIT or ROLLBACK after opening the cursor, an error may occur.


The reason an error occurs while performing FETCH to some extent is that the first large amount of records is stored in the
communication buffer during FETCH. An error occurs when fetching all the records in the communication buffer and fetching the next
certain amount of records into the communication buffer.


The following is an example of creating an application that performed COMMIT or ROLLBACK in the cursor OPEN state.


non-autocommit mode


DECLARE CURSOR


OPEN CURSOR


while(1)
{

FETCH CURSOR ;

if (sqlca.sqlcode == SQL_SUCCESS) {

/* Execute change DML */

/* Perform COMMIT or ROLLBACK */

}
else if (sqlca.sqlcode == SQL_NO_DATA) {
/* An error occurs at this stage when all the records in the first communication buffer are processed and
then placed in the second communication buffer. */
}
else {

...

}
}


Solution


When COMMIT/ROLLBACK is performed in the cursor (CURSOR) OPEN state


Here are two methods to solve this error.


To separate fetch and change DML operations using multiple connections
To open the cursor repeatedly after declaring the cursor only enough to be contained in the communication buffer


All of the above methods require application changes.


1. Separation of fetch session and modified DML session


By using multiple connections within one application, COMMIT or ROLLBACK does not affect the cursor.


Create a session that uses a cursor and a session that executes modified DML statements. It is described by defining it as
CONN1 and CONN2, respectively.
Set the session (CONN2) that executes the modified DML statement to non-autocommit mode.
Whenever cursor FETCH is executed in the session using the cursor (CONN1), change DML is executed in CONN2, and COMMIT
or ROLLBACK is executed.


The following is an example of creating an application that reflects this action.


/* Session for FETCH */

EXEC SQL AT conn1 CONNECT;

/* Session for executing change DML */

EXEC SQL AT conn2 CONNECT;


EXEC SQL AT conn2 AUTOCOMMIT OFF;

/* Declare cursor in CONN1, execute OPEN, FETCH */

EXEC SQL AT conn1 DECLARE cursor;

EXEC SQL AT conn1 OPEN cursor;
while (1)
{
/* Execute FETCH on conn1. */

EXEC SQL AT conn1 FETCH cursor

if (sqlca.sqlcode == SQL_SUCCESS) {

/* Change DML and COMMIT or ROLLBACK in conn2 */

EXEC SQL AT conn2 INSERT or UPDATE or DELETE ;

/* check sqlca.sqlcode */
if (sqlca.sqlcode == SQL_SUCCESS) {

...

}
else {

...

}

/* The commit or rollback performed in conn2 does not affect the cursor use of conn1. */

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


2. Repetitively open the cursor after declaring the cursor only enough to be contained in the communication buffer


After calculating the number of records enough to put in the communication buffer with one FETCH, declare the cursor using the LIMIT
clause.


The communication buffer size of Altibase 5 and above is 64K. Since the number of records in the communication buffer depends on the
record size, the last value of the LIMIT clause varies depending on the operating environment.


Specify the number of records to be stored in the communication buffer in the LIMIT clause, and open the cursor again and use it while
changing the start value of the LIMIT clause before opening the cursor.


The following is an example of creating an application that reflects this action.


/* The cursor is declared using the LIMIT clause. n is the last record value to be returned in the LIMIT clause
and must be defined according to the operating environment. The number of records in the communication
buffer depends on the record size. */

DECLARE CURSOR

SELECT ~

FROM ~

WHERE ~

LIMIT :s_start, n;


/* Declare the starting value used in the LIMIT clause. */

s_start = 1;

while(1)
{
/* Cursor open is repeated until all records meeting the conditions are fetched. */

OPEN CURSOR

while(1)
{

FETCH CURSOR ;

if (sqlca.sqlcode == SQL_SUCCESS) {

/* Execute change DML */
}
else if (sqlca.sqlcode == SQL_NO_DATA) {

...

}
else {

...

}
}

/* Perform COMMIT or ROLLBACK */

/* Specify the starting value of the LIMIT clause. n is an example. */

s_start = s_start + n ;

}


CLOSE CURSOR or CLOSE RELEASE CURSOR


Reference


Differences by version


Depending on the Altibase version, the error messages that occur in the same situation may be different.


The difference in error messages that occurs when COMMIT/ROLLBACK is executed among FETCHs in a non-autocommit environment
is as follows.










|Version|Error code|Error message|Reference page|
|---|---|---|---|
|Altibase 4.3.9|ERR-4103C|Request of fetching data to an unprepared SQL<br>statement.|ERR-4103C (266300) Request of fetching data to an unprepared<br>SQL statement.|
|Altibase 5.3.3 ~<br>6.1.1|100|Not found data||
|Altibase 6.3.1 or<br>later|ERR-410D2|Fetch out of sequence.|ERR-410D2 (266450) Fetch out of sequence.|


### tablespace does not have enough free space error

Overview

Version

Cause

Solution

Reference


Overview


Insufficient tablespace


Version


ALTIBASE HDB version 4 or later


Cause


This error is caused by the insufficient size of a specific tablespace.


Solution


1. Check the tablespace space usage.


Use the appropriate query statement for the version of Altibase you are using to check the usage.


https://aid.altibase.com/display/FAQE/8.+Monitoring


2. After querying the tablespace usage, add space to the tablespace with USAGE(%) close to 100% in the query result.


ALTER TABLESPACE tablespace name add datafile'/path/filename' size 2G autoextend off;


Reference


When adding a data file, the tablespace is locked, so it is recommended to block the service and work.


For HDB 5.3.3 and earlier, select and DML and queries will wait for the tablespace add operation to complete.


From HDB 5.5.1 or later to the latest V6, DML waits until the tablespace addition operation is completed, but the select statement is
executed normally.

## 10. Migration 11. Utilities

### AdminCenter2 execution file


Overview

Execution file

How to execute

Manual


Overview


This is the last version of AdminCenter2.


AdminCenter2 can only be used up to version 4 of ALTIBASE HDB.


From ALTIBASE HDB 5, Orange for Altibase of Ware Valley (Download Orange for Altibase: http://www.warevalley.com)


AdminCenter2 will not be accepted for any problems encountered during use due to maintenance.


Execution file


AdminCenter2.zip


How to execute


After downloading the executable file, unzip it and execute the AdminCenter.exe file.


For the JDBC driver required to connect to ALTIBASE HDB, use $ALTIBASE_HOME/lib/Altibase.jar on the server where the ALTIBASE HDB
server is running.


Manual


Execute AdminCenter.exe and use the Help -> Help Contents menu.

### iLoader


An error occurs when uploading a DOS format data file to iloader.


Overview

How to remove


On Windows
On Linux/Unix

Convert to unix type file using dos2unix.
Remove ^M using sed
Starting from ALTIBASE HDB 5.5.1 ...


Overview


To upload a DOS format data file from Unix/Linux server to the iloader, you need to convert the file using an editing program or
dos2unix.


If the iloader is executed without conversion, the following error may occur.


ERR-9102B : Token value length overflow.


In DOS format files, Row Termination Code is composed of CR (Carriage Return) + LF (Line Feed).


When the iloader parses the data file, it recognizes %n(LF) as a row terminator. So when uploading a data file in DOS format, a parsing
error might occur.


When opening a DOS format file with vi in Linux/Unix, ^M is attached to the line or looks like the following:


"SYS_T.dat" [DOS] 225L, 33822C


How to remove


On Windows


In Windows, it can be converted using an editing program.
Ex) In UltraEdit, select File -> Convert ->'DOS->UNIX' and save


On Linux/Unix


Convert to unix type file using dos2unix.


The dos2unix command converts DOS/MAC files to UNIX format.


Remove ^M using sed


Use sed to remove ^M as an iloader data file.

^M must be entered as Ctrl+v+m.





Starting from ALTIBASE HDB 5.5.1 ...


From ALTIBASE HDB 5.5.1, it is possible to upload without file conversion/modification by using %r%n, which means CR+LF as a record
separator.


## 12. Others

### Thread process debugging method

Overview

Using pstack

How to use

Example
Using dbx

How to use

Example
Using gdb

How to use

Example


Overview


When a process on Unix over-occupies cpu or falls into a situation such as a process hang, the process debugging utility can be used,
provided for each Unix OS, to find the cause by analyzing the currently running call stack.


Unix process debugging methods are different for each utility and slightly different for each Unix, so the command is often confused. It
explains how to view each thread stack, focusing on simple commands.


Using pstack


As a utility provided by SUN and some other Unix and Linux, it is a very useful command to view the call stack of the running process by
thread. When it is DB Hang, use it.


How to use


Linux

shell> pstack processid
Sun

shell> pstack -F processid


Example





Using dbx


Provided by AIX, HP, and SUN. You can check the call stack information of the running process through the dbx command, or the stack
for each thread can be checked in the core file.


This section describes the method used on AIX as an example.


How to use



1.


2.


3.


4.


5.


6.



Check the process id of the procesd in question.
shell> ps -eafl | grep altibase
Attach to process.
shell> dbx -a <pid of altibase process>
View all thread information
(dbx) thread
View individual thread information only
(dbx) thread current <thread number>
(dbx) where
Detach
(dbx) detach


Tthe connected process must be releasedby executing the detach command. Otherwise, if exited, it may end up to the
target process, so be careful.


Exit


(dbx) quit


Example





Using gdb


If gdb (GNU debugger) is installed, the stack information for each thread can be checked by using gdb.


How to use



1.


2.


3.


4.


5.


6.



attach gdb to the target process
shell> $gdb $ALTIBASE_HOME/bin/altibase process-id
Information output for each thread
(gdb) info threads
Output stack trace of all threads
(gdb) thread apply all bt
Switch to a specific thread
(gdb) t 1: switch to thread 1
Output the current thread's stack
(gdb) bt: stack output
Quit
(gdb) quit



Example


## 13. General

### The entire database exists in memory. Is there any problem with the safety of the data?

Overview

Version

How to secure

Disability management operation plan


Overview


This document describes a technique to guarantee the data stability of the volatile main memory.


Version


This document is written based on Altibase HDB version 6.3.1.
For additional information or updates, please leave a request at http://support.altibase.com/en/ or in the comment section on


this page.


How to secure



1.


2.



WAL protocol method
WAL (Write Ahead Logging) logging method is used when transaction processing is used to provide database persistence and to
secure stability for committed transactions. When the number of log files exceeds a certain number or a fixed period, the
changed data page in the memory is displayed. The recovery time is minimized through checkpoints that are written to the disk.

- WAL: The procedure for saving logs to disk first and then saving DB pages. The last transaction information is stored on the
disk, so it can be recovered through the transaction log in case of abnormal termination.
Backup and recovery support
Backup creates a logical/physical copy of the database in case of an abnormal situation in the DBMS. Such a copy of the
database can be created online during the DB operation, and in a recovery situation, the database can be normalized by
performing complete or incomplete recovery by using the backed up database copy.



Disability management operation plan






|Type|Col2|Description|
|---|---|---|
|Transaction<br>Failure|Cause|• Occur due to interruption of a transaction by internal or external factors|
|Transaction<br>Failure|Solution|• Maintain database consistency by automatically recovering data with normal transaction rollback.|
|System<br>Failure|Cause|• Occur due to faults in the operating system or failures such as power outages|
|System<br>Failure|Solution|• Automatic recovery to the state until the point of system failure with the backup data file and Active Log<br>when the system is restarted (Restart Recovery)|
|Disk<br>Failure|Cause|• Occur due to corruption of the backup data file due to an error in the disk where the backup data file is<br>stored|
|Disk<br>Failure|Solution|• If there is a previous data backup file, it can be restored to the latest database with this file.<br>• However, if the log disk is damaged or the archive log is deleted, recovery to the most recent state is<br>impossible.|


### What interface does Altibase provide?

Overview


Version


Interface provided by Altibase


Client development environment


Server development environment


Overview


This document explains the interfaces provided by Altibase.


Version


All the versions of Altibase HDB


Interface provided by Altibase


Altibase complies with the international standard ANSI SQL-1999 and provides various standard interfaces such as ODBC, ADO.
Net, JDBC, and Embedded SQL.


Client development environment







|Interface type|Support function|
|---|---|
|ODBC|RAD (Rapid Application Development) tools such as Visual Basic and PowerBuilder, as well as used when<br>accessing ALTIBASE in most development environments<br>Reinforced standard support with re-implementation|
|JDBC|Used when developing ALTIBASE application programs in JAVA environment<br>Also used when configuring a connection pool in WAS<br>Improved performance with re-implementation<br>JDBC 2.0 API support up to Altibase 6.1.1, JDBC 3.0 API support partially.<br>JDBC 3.0 API support from Altibase 6.3.1.|
|SQLCLI|ALTIBASE's low-level API based on C language<br>Provide LOB API, ALA (ALTIBASE Log Analyzer) API, ACS (ALTIBASE Call-Level for Spatial) API|
|Embedded<br>SQL<br>(Pre-Compiler)|Interface used by the host language of C or C++<br>Improved development productivity by using SQL statements as they are in the host language|
|ADO.NET|Common programming interface to access database data based on Windows .Net Framework|
|Unix ODBC|Standard DB connection API compatible with Windows ODBC source on Unix<br>Provide compatibility with ETL tools such as DataStage and Informatica and OLAP tools such as MSTR and<br>Sagent|


Server development environment

|Function|Characterstic|
|---|---|
|SQL|Support Full Featured SQL92<br>Support international standard complex query such as Sub Query INLINE view|
|Built-in Function|Provides more than 100 built-in functions<br>Users can perform various operations in SQL statements by using Built-in Function|
|Stored Procedure & Function|Support Stored Procedure and Stored Function based on ANSI SQL standard<br>Result Set can be sent to the client in the procedure<br>Support structured type and array type within procedure<br>Support Dynamic SQL/DDL within the procedure|
|View|Efficiently query by unioning multiple tables or creating a specific SQL as a view|
|Trigger|Support Trigger by standard for business function in the form of data events<br>Support Update Trigger for a specific column|


### What is the biggest difference between Altibase and disk-based DBMS?


Overview


Version


All the versions of Altibase


The biggest difference between In-Memory-based DBMS and Disk-based DBMS


As an Altibase Hybrid DBMS, it supports both In-Memory DB and Disk-based DB.


Differences from Altibase HDB's In-Memory DB



1.


2.



When operating DBMS, the location where the database resides is different.



There is a significant difference in performance.



a.



In a disk-based DBMS, the entire database resides on the disk and the necessary data is cached and managed
in the memory buffer, whereas the in-memory DBMS is managed by residing the entire backup database on the
disk in the main memory.



a.


b.



Although almost the same in terms of functionality, in-memory DBMSs are about 4 to 10 times faster than
disk-based DBMSs, depending on the operating environment.
Altibase HDB is divided into three methods: Memory Only, Hybrid, and Disk Only, and five virtual simultaneous
transactions that meet TPC-C standards.
As a result of measuring online transaction processing performance by combining (order transaction, payment


transaction, shipping transaction, order status transaction, stock level transaction), it showed higher performance
than Disk DBMS.


C model of the benchmark standard that measures the processing performance of an online transaction processing (OLTP)
system

## Altibase Error Messages


The following pages cover the errors that you can encounter while dealing with Altibase. With this list, you can fix or work around error

messages.

### make Cannot find a rule to create target connect1.o from dependencies.


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


This error occurs if a source file is compiled using the Make utility of a sample source.


$ cd $ALTIBASE_HOME/sample/APRE
$ make connect1

make: Cannot find a rule to create target connect1.o from dependencies.
Stop.


Cause


The Makefile in the $ALTIBASE_HOME/sample directory was created based on the GNU Make. Thus, this error occurs if Make is executed
in the $ALTIBASE_HOME/sample directory. In a platform such as Linux, this error does not occur as the GNU Make is installed by default.


Action


Change it to GNU Make (install, if necessary) then re-execute Make.


Reference


Information about GNU Make can be checked as below:


$ make -v


GNU Make 3.81


Copyright (C) 2006 Free Software Foundation, Inc.


This is free software; see the source for copying conditions.


There is NO warranty; not even for MERCHANTABILITY or FITNESS FOR A


PARTICULAR PURPOSE.


This program built for rs6000-ibm-aix

### ERR-0106B The session has been disconnected by the client


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Database is disconnected.


Cause


A disconnection has been detected between the Altibase server and a client.


Action


Reconnect the database server.


Reference


N/A

### ERR-01044 Client's query exceeded in the execution time limitation


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


The query abnormally terminates.


Cause


QUERY_TIMEOUT specifies the maximum amount of time allowed for a query to complete its execution.


This property prevents long-running queries from causing server load.


This error message is output when a query was executed for a longer time than the value specified for QUERY_TIMEOUT.


Information of the query is output to Altibase_boot.log.


Action


This error occurs when the query execution time exceeded QUERY_TIMEOUT.


QUERY_TIMEOUT is the maximum amount of time allowed for a query to complete its execution.


The best way to fix this error is to reduce the overall execution time by tuning the query (e.g., adding an index).


A quick workaround would be to increase QUERY_TIMEOUT to avoid the error.


Check the QUERY_TIMEOUT property value (default : 3600 seconds).


SELECT name, value1 FROM v$property WHERE name LIKE '%TIMEOUT%';


Modify the value.


ALTER SYSTEM SET query_ timeout= desired value;


Reference


This error message can be attributed to various causes: high service traffic load or suddenly changed query plans can incur prolonged
query execution time.


This error should be fixed by tuning queries.


### ERR-01050 License File does not exist

Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to start server.


Cause


This error message is output when a license file does not exist.


Action


Check whether $ALTIBASE_HOME/conf/license exists.


Reference


N/A

### ERR-01067 The memory size allocated for the statement has exceeded the maximum limit


Version

Explanation
Cause

Action

Reference


1. PREPARE_STMT_MEMORY_MAXIMUM:
2. EXECUTE_STMT_MEMORY_MAXIMUM:


Version


5.5.1 or above


# For 5.3.3, the following error message is output:


[ERR-01067 : The allocated memory size of statement exceeds the maximum limit ( Name : Query_Execute, Wanted Memory
Size : 1114112, Max size : 1048576 ).]


Explanation


This error occurs if query execution has stopped due to query preparation failure.


Cause


The amount of memory used for query preparation exceeded PREPARE_STMT_MEMORY_MAXIMUM.


Action


1. Tune the query to reduce memory usage.
2. Increase the memory usage for query execution with the ALTER SYSTEM command or altibase.properties file.

1)


iSQL> ALTER SYSTEM SET PREPARE_STMT_MEMORY_MAXIMUM = 419430400;


2) Change the value of PREPARE_STMT_MEMORY_MAXIMUM from $ALTIBASE_HOME/conf/altibase.properties.


Reference


1. PREPARE_STMT_MEMORY_MAXIMUM:


Check this property when query preparation has insufficient memory.


2. EXECUTE_STMT_MEMORY_MAXIMUM:


Check this property to modify the size used by group functions.

### ERR-0108D License invalid or expired


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to start server.


Cause


This error message is output if the license is invalid or has expired.


Action


Obtain a new license file.


Reference


N/A

### ERR-0109D Insufficient memory


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to execute query.


This error occurs when the execution of a certain query fails due to insufficient temporary memory.


# Example


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


# 5.5.1 or above


iSQL> select count(*) from (select count(*) from t, t2, t3 group by t.c2, t2.c2, t3.c2);


ERR-0109D : Insufficient memory


# 5.3.3


iSQL> select count(*) from (select count(*) from t, t2, t3 group by t.c2, t2.c2, t3.c2);


ERR-01067 : The allocated memory size of statement exceeds the maximum limit ( Name : Query_Execute, Wanted Memory
Size : 1114112, Max size : 1048576 ).|"linktype="raw" wikidestination="" originalalias="ERR-01067 : The allocated memory size
of statement exceeds the maximum limit ( Name : Query_Execute, Wanted Memory Size : 1114112, Max size : 1048576 ).|"
class="linkerror" >ERR-01067 : The allocated memory size of statement exceeds the maximum limit ( Name : Query_Execute,
Wanted Memory Size : 1114112, Max size : 1048576 ).|||||||||\


Cause


The following error description can be viewed with the AltiErr utility:


The temporary area is used when executing a query including a GROUP BY or ORDER BY clause for memory. However, this temporary
area also uses memory.


This error occurs due to EXECUTE_STMT_MEMORY_MAXIMUM while allocating memory to execute a query.


Action


Altibase uses memory space for temporary memory tables, instead of disk space.


Consequently, the necessary memory space must be secured at query execution with the following property:


EXECUTE_STMT_MEMORY_MAXIMUM (default value: 1G)


The unit is bytes and an error occurs if more memory than the value specified for this property is used during the execution stage of
query execution.


This property is set as the maximum value to prevent unnecessary memory increase.


<How to Fix the Error>


1. Check the increase in Query_Execute.


iSQL> SELECT * FROM v$memstat WHERE name = 'Query_Execute';

NAME     ALLOC_SIZE  ALLOC_COUNT  MAX_TOTAL_SIZE

----------------------------------------------------------------------------------
----------------
Query_Execute 5091105640     75431    5091105640


2. Check the current value of EXECUTE_STMT_MEMORY_MAXIMUM


iSQL> set vertical on;
iSQL> select name, value1 from v$property where name='EXECUTE_STMT_MEMORY_MAXIMUM';

NAME  : EXECUTE_STMT_MEMORY_MAXIMUM

VALUE1 : 1073741824


3. Using the ALTER statement, set a value (in bytes) larger than ALLOC_SIZE for EXECUTE_STMT_MEMORY_MAXIMUM.


Set an appropriate value by estimating how much the execution space will extend for the query.


iSQL> ALTER SYSTEM SET EXECUTE_STMT_MEMORY_MAXIMUM=5368709120; (5G)

Alter success.


4. To apply the change permanently, the value has to be changed in the altibase.properties file as
well($ALTIBASE_HOME/conf/altibase.properties).


Reference


The EXECUTE_STMT_MEMORY_MAXIMUM property specifies the maximum memory that a single statement can use for execution, not the
pre-allocation memory that a single statement can use.


Memory usage can increase as much as specified by the property. Therefore, the user is recommended to set an appropriate value.

### ERR-11030 The data file cannot be extended because the requested size is bigger than the maximum size (262144 pages)


Version

Explanation
Cause

Action


1. Change the AUTOEXTEND option
2. Change the datafile size


3. Increase SYS_UNDO_FILE_MAX_SIZE

Reference


Version


4.3.9 or above


Explanation


1. Unable to change the datafile size of the disk tablespace.


2. Unable to resize the undo tablespace datafile.


Cause


1. The user has attempted to change the size of a datafile that has the AUTOEXTEND option OFF to a value bigger than the maximum
size.


2. The value of the undo tablespace datafile to be resized exceeded SYS_UNO_FILE_MAX_SIZE.


Action


Set the AUTOEXTEND option of datafile to ON and follow the steps as below to change the datafile size.


1. Change the AUTOEXTEND option


iSQL>ALTER TABLESPACE DISK_USER_TBS
2 ALTER DATAFILE '/home/altibase_home/dbs/user.dbf' AUTOEXTEND ON;

Alter success.


2. Change the datafile size


iSQL> ALTER TABLESPACE DISK_USER_TBS
2 ALTER DATAFILE '/home/altibase_home/dbs/user.dbf' SIZE 100M;

Alter success.


3. Increase SYS_UNDO_FILE_MAX_SIZE


Change SYS_UNDO_FILE_MAX_SIZE from $ALTIBASE_HOME/conf/altibase.properties to the desired size (in bytes) and recreate the
database.


Reference


In order to change this property, the database has to be recreated.


Hence, if you want to increase the undospace size, it is easier to use the ALTER TABLESPACE command to add a datafile.

### ERR-11036 The data file is in use


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


The following error message is output when ALTER TABLESPACE ... DROP DATAFILE is executed:


iSQL> ALTER TABLESPACE SYS_TBS_DISK_DATA
2 DROP DATAFILE '/altibase/dbs/DISK_DATA2.dbf';


ERR-11036: The data file is in use.


Cause


The following error description can be viewed with the AltiErr utility:





Even if the user executed an INSERT statement and followed it with a DELETE statement so that all the datafiles can only have free
pages, a previously used datafile cannot be dropped.


This error occurs when an attempt is made to drop a datafile that has previously been used.


Only datafiles that have never been used can be dropped.


Action


It is impossible to drop a datafile that was used even once.


To drop a datafile, the tablespace must be recreated as below:





Reference


N/A

### ERR-11041 A deadlock situation has been detected


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to execute query.


Cause


This error occurs when a deadlock has occurred and the query that caused the deadlock is not executed for concurrency control.


Action


1. Find the queries that cause locks and check which of their logic is causing a deadlock.


Modify the queries so that the problematic logic is not executed.


2. As deadlocks can occur in replication, check the locks that are acquired during replication.


Reference


N/A

### ERR-11049 Too many pages were allocated


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


A server hang occurred when an INSERT, UPDATE or DELETE statement was executed.
Unable to store data into memory tablespace.


Cause


The memory database exceeded the size limit.
For memory tablespaces in Altibase, the sum of all the memory tablespaces cannot exceed MEM_MAX_DB_SIZE. Thus, this error
occurs when all the memory space is used.


Action


The user must drop the unnecessary table(s) or increase MEM_MAX_DB_SIZE and restart the Altibase server. After that, check why the
memory tablespace usage was increased, and whether there was a large number of selected or altered data for each table.


Reference


N/A

### ERR-1105D Unable to begin a new update statement


Version

Explanation
Cause

Action

Reference


Version


6.1.1 or below.


The error code and message have been changed for 6.3.1


Explanation


The following error occurs when a user function is used inside the SELECT statement:


iSQL> select func1() from dual;


[ERR-1105D : Unable to begin a new update statement.
0004 : insert into T1 values(C1);]


The error code and message have been changed for 6.3.1 as follows:


iSQL> select func1() from dual;


[ERR-31386 : Cannot perform a DML, commit, or rollback inside a query.


In FUNC1
0004 : insert into T1 values(C1);
^ ^
]


Cause


The following error descriptions can be viewed with the AltiErr utility:


# 6.1.1 or below





# 6.3.1





When a user function is used inside the SELECT statement, the function must only include the SELECT statement.


However, this error occurs when DMLs are included in a user function.


Action


Remove the DML statement from a user function inside the SELECT statement.


# In the following example, the error occurs when a function including the INSERT statement is used within the SELECT statement.


g p g


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
0004 : insert into T1 values(C1);
^ ^
]


# In the following example, the above function is successfully executed using the EXECUTE statement


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


# In the following example, the function is successfully executed when the INSERT statement is removed from the SELECT statement.


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


Reference


N/A

### ERR-11058 The row already exists in a unique index


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to execute query.


Cause


The same data is inserted into the unique column.


Action


Insert the same value or remove the unique constraint.


Reference


N/A

### ERR-11075 The transaction has exceeded the lock timeout specified by the user


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


This error message is output or written to altibase_rp.log when a DDL/UPDATE/SELECT FOR UPDATE statement is executed.


Cause


The following error description can be viewed with the AltiErr utility:


This error can occur under the following circumstances:


1. If an UPDATE statement has been executed:


If the transaction is to be converted to a table lock due to LOCK_ESCALATION_MEMORY_SIZE but fails to acquire an X lock because the
table is already locked (e.g., IX lock).

|Session 1|Session 2|
|---|---|
|iSQL> autocommit off;<br>Set autocommit off success.<br>iSQL> update tb_test1 set<br>c10=sysdate where c1=1;<br>1 row updated.||
||iSQL> select count(*) from tb_test1;<br>COUNT<br>-----------------------<br>1000000<br>1 row selected.<br>iSQL> alter session set<br>TRX_UPDATE_MAX_LOGSIZE=100000000;<br>Alter success.<br>iSQL> alter system set<br>LOCK_ESCALATION_MEMORY_SIZE=100000000;<br>Alter success.<br>iSQL> update tb_test1 set c10=sysdate;<br>ERR-11075 : The transaction has exceeded the lock timeout specified by the<br>user.|



The last UPDATE statement in Session 2 performs the update operation using row-level locking, and then tries to acquire an X lock when
the update log size exceeds LOCK_ESCALATION_MEMORY_SIZE.


However, Session 2's UPDATE statement returns the above error because Session 1's UPDATE statement is not committed and holds an
IX lock.


Remember that this error did not occur immediately after an UPDATE statement was executed, but after the UPDATE statement was
executed and while trying to acquire an X LOCK.


2. If a DDL statement has been executed:


If a table lock (X lock) must be acquired for the execution of a DDL statement but the lock cannot be acquired because the table is
already locked (e.g., IX lock).


Session 1 Session 2


|iSQL> autocommit off;<br>Set autocommit off success.<br>iSQL> update tb_test1 set c10=sysdate<br>where c1=1;<br>1 row updated.|Col2|
|---|---|
||iSQL> truncate table tb_test1;<br>ERR-11075 : The transaction has exceeded the lock timeout<br>specified by the user.|


This error is related to the DDL_LOCK_TIMEOUT property.





The default value for DDL_LOCK_TIMEOUT is 0 and this means that the DDL statement will not wait to acquire an X lock.


In other words, an error is returned if the statement fails to acquire an X lock.


If a value larger than 0 is set for this property, the DDL statement waits for as many seconds as specified (by the value) to acquire a lock
and returns an error, when unsuccessful.


3. If a SELECT FOR UPDATE statement has been executed:


If a NOWAIT or WAIT N option is used but a lock is not acquired immediately or within a certain period of time.

|Session 1|Session 2|
|---|---|
|iSQL> autocommit off;<br>Set autocommit off success.<br>iSQL> update tb_test1 set c10=sysdate<br>where c1=1;<br>1 row updated.||
||iSQL> select * from tb_test1 where c1<10 for update<br>nowait;<br>ERR-11075 : The transaction has exceeded the lock timeout<br>specified by the user.|



4. If the error message has been output to altibase_rp.log:


If a replication transaction is waiting for a transaction on the local server to terminate.


|Active Server|Standby Server|
|---|---|
|alter replication rep1 start;|Does not start replication.|


|Col1|iSQL> autocommit off;<br>Set autocommit off success.<br>iSQL> insert into tb_test1(c1,c10)<br>values(1000001, sysdate);<br>1 row inserted.|
|---|---|
|iSQL> autocommit off;<br>Set autocommit off success.<br>iSQL> insert into tb_test1(c1,c10)<br>values(1000001, sysdate);<br>1 row inserted.||


After an INSERT statement has been executed on the Active server, the following message is output to altibase_rp.log on the Standby

server.


This error is affected by REPLICATION_LOCK_TIMEOUT.


If the replication transaction (or Standby server) fails to acquire a lock within the time specified by REPLICATION_LOCK_TIMEOUT, an
error occurs and the replication transaction fails.


# The above scenarios are only one kind of example for each error cause. Various cases can be attributed to the same cause.


Action












# Since ALTIBASE HDB can temporarily fail to acquire a lock (e.g., #1 and 3 above) while it is running in the SERVICE phase, repeat the
operation multiple times.


Reference


The LOCK_ESCALATION_MEMORY_SIZE property is related only to memory tables.


Therefore, the user should remember that what follows pertains only to memory tables.


The purpose of LOCK_ESCALATION_MEMORY_SIZE is to prevent the memory usage for storing undo images from drastically increasing
when performing bulk update operations using record-level locking.


If the update log size exceeds LOCK_ESCALATION_MEMORY_SIZE during a bulk update, an attempt is made to escalate locks by
acquiring an X lock.


The above error occurs if the session fails to acquire the X lock.


When successful, the session holds the X lock and continues to update. Memory usage does not increase because in-place updates are
performed from this point onward (For further information about in-place updates, refer to the Administrator's Manual.).


Since the session holds the X lock on the table, it cannot be accessed by other sessions and all DML statements and the SELECT
statement enter a state of waiting. The user could interpret this as a service error.


Thus, the user is advised to reduce the number of update target records and increase the number of updates.


For example, an update of 100,000 records should be divided into 10 updates of 10,000 records using the condition clause or LIMIT
clause.


The user should also refer to the following error as well:


ERR-11118 : The update log size '10485800' is bigger than TRX_UPDATE_MAX_LOGSIZE '10485760'


This warning error is output before the session is converted to an X lock due to LOCK_ESCALATION_MEMORY_SIZE.


The default values for LOCK_ESCALATION_MEMORY_SIZE is 100M and TRX_UPDATE_MAX_LOGSIZE is 10M.


If the update log size exceeds TRX_UPDATE_MAX_LOGSIZE, an error is returned to prevent the session from converting to an X lock.


When the TRX_UPDATE_MAX_LOGSIZE error occurs, adequately increase TRX_UPDATE_MAX_LOGSIZE (the value must not
exceed LOCK_ESCALATION_MEMORY_SIZE) and execute the UPDATE statement with every increase.


When changing these property values, LOCK_ESCALATION_MEMORY_SIZE must be larger than TRX_UPDATE_MAX_LOGSIZE.

### ERR-11118 The update log size '10485760' is bigger than TRX_UPDATE_MAX_LOGSIZE


Version

Explanation
Cause

Action

Reference


Version


4.3.9 or above


Explanation


Unable to execute an UPDATE statement.


Cause


This error occurs when the size of the redo log which is generated when executing an UPDATE statement exceeds
TRX_UPDATE_MAX_LOGSIZE.


The size of the redo log generated when executing an UPDATE statement can be much bigger than the record.


Action


1. To fix this error, modify TRX_UPDATE_MAX_LOGSIZE with the following command:


ALTER SESSION SET TRX_UPDATE_MAX_LOGSIZE = 20480000;


2. Reduce the number of updates by using the LIMIT clause in the UPDATE statement and repeatedly execute smaller update operations.


For example, if there are 100,000 records to be updated, the LIMIT10000 clause repeatedly performs 10 update operations.


Reference


1. If TRX_UPDATE_MAX_LOGSIZE is set to a high value, memory usage can increase to store images of previous versions of data using
MVCC.


2. mem_gc can be delayed until the update is complete.


3. If TRX_UPDATE_MAX_LOGSIZE is set to a higher value than LOCK_ESCALATION_MEMORY_SIZE, a lock escalation can occur during an
UPDATE operation.


In a lock escalation scenario, a SELECT operation fails if an IX lock converts to an X lock and as a consequence, all services may
have to wait.


Therefore, the user is recommended to reduce the number of update operations, rather than increase TRX_UPDATE_MAX_LOGSIZE.

### ERR-11123 The tablespace does not have enough free space


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to additionally input or modify data using the INSERT or UPDATE statement.


Cause


This error occurs when data input fails due to insufficient space in the tablespace.


Action


1. Increase the tablespace size by adding a datafile to the tablespace on which the error has occurred.


2. If the undo tablespace caused the error, COMMIT/ROLLBACK operations are unsuccessfully carried out for a long time.


Check whether a transaction using undo tablespace exists.


Since DML operations fail due to insufficient space in the tablespace, try again after increasing the tablespace size.


Reference


N/A

### ERR-11098 smERR_ABORT_BackupLogMode cannot be executed in no archive log mode


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to perform an online backup.


Cause


An online backup has been performed in NO ARCHIVING mode.


Action


An online backup can only be performed in ARCHIVING mode. Otherwise, an error occurs.


Check whether the database is running in ARCHIVING mode with the following command:


iSQL>select archivelog_mode from v$log;

ARCHIVELOG_MODE

-----------------------
NOARCHIVE


<How to change to ARCHIVING mode from NOARCHIVING mode>


1. Shut down the database.


2. Re-start the database.


3. Run the database in the CONTROL phase.


SHELL>server stop
SHELL>is –silent –sysdba


ERR-910FB : Connected to idle instance
isql(sysdba)>startup control


4. Change to ARCHIVING mode using the ALTER DATABASE ARCHIVELOG statement.


isql(sysdba)>alter database archivelog


<Execute an online backup in ARCHIVING MODE>


1. Run the database in the SERVICE phase.


isql(sysdba)>startup service


2. Re-start backup.


Reference


N/A

### ERR-110AA Duplicate tablespace names


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to create tablespace.


Cause


This error occurs when a tablespace with an existing name is created.


Action


1. Check the name of the tablespace that is currently being used.


iSQL> SELECT name FROM v$tablespaces;

NAME

-------------------------------------------
SYS_TBS_MEM_DIC

SYS_TBS_MEM_DATA

SYS_TBS_DISK_DATA

SYS_TBS_DISK_UNDO

SYS_TBS_DISK_TEMP

VOL_TBS1

VOL_TBS2

MEM_TBS1

DISK_TBS1


2 Re-create the tablespace with a distinct name


2. Re create the tablespace with a distinct name.


Reference


N/A

### ERR-2100D Invalid length of the data type


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to execute query.


Cause


This error occurs when an operation that is not permitted for the data type is performed.


1. If the user tries to create a column which exceeds the maximum size of the data type.


2. If the user tries to insert or update data which exceeds the column size.


Action


Check the maximum sizes supported for data types in the Altibase version being used and try again.


Reference


For further information about the maximum sizes supported for data types in Altibase, refer to the SQL Reference Manual.

### ERR-21010 Value overflow


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to execute an INSERT or UPDATE statement.


This error message is output when an INSERT or UPDATE statement is executed:


Cause


The following error description can be viewed with the AltiErr utility:


This error occurs when the input value is not within the supported data type range.


# Example


iSQL> create table test(i1 integer);

Create success.

iSQL> insert into test values(2147483648);

[ERR-21010 : Value overflow
0001 : insert into TEST values(2147483648)

^     ^

]
iSQL> insert into test values(2147483647);

1 row inserted.


The INTEGER data type stores integers in the range of -2,147,483,647~ 2,147,483,647.


This error occurred because the value to be stored in the column is outside this range.


Action


Check whether the value to be stored in the column exceeds the maximum allowed for the column's data type.


If so, change the input value or convert the column's data type.


Reference


For further information about the range of values for the data types supported by Altibase, refer to the General Reference Manual.

### ERR-21011 Invalid literal


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to execute query.


Cause


This error message is output when the user tried to input a CHAR value into a NUMERIC data type.


Action


Input a value that matches the data type.


Reference


N/A

### ERR-21013 Calculation stack overflow


Version

Explanation
Cause

Action

Reference


Version


6.3.1


Explanation


Unable to execute query.


Cause


The query requires a stack size that exceeds the size of the stack used by Altibase to run queries (This is to prevent the waste of
memory resources of the Altibase server due to maintaining a large stack.).


Action


Check whether query tuning has been performed; otherwise choose one of the two following methods.


1. Change the maximum stack size for a specific session only.


Change the maximum time of query execution. (MAX: 65536)


ALTER SESSION SET STACK SIZE = 2048;


2. Change the maximum stack size of all the sessions.


1) Run the statement in iSQL to change server settings.


iSQL> ALTER SYSTEM SET QUERY_STACK_SIZE = 2048;


2) Change QUERY_STACK_SIZE from $ALTIBASE_HOME/conf/altibase.properties.


3. Re-connect all the clients.


Reference


If the stack size is set to a value greater than needed, it may become a waste of unnecessary memory space.

### ERR-31088 A replicated table must have a primary key


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to perform replication.


Cause


This error message is output if the replicated table does not have a primary key.


Action


One of the replication restrictions is that a replicated table must have a primary key column.


This is because primary key columns are used to check data consistency.


To fix this error, use the ALTER TABLE statement to create a primary key column and try again.


Reference


N/A

### ERR-3109F REPL sender failure to handshake with peer server


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to create replication object.


Cause


This error occurs if the replication target table schema is different.


Action


1. Check whether the replication target tables have equal schemas.


2. If different, match them with the same schemas.


3. Re-create the replication object.


Reference


N/A

### ERR-311E0 The estimated size of the index key exceeds the maximum limit


Version

Explanation
Cause

Action

Reference


Version


6.1.1 or below


This error message is not output for 6.3.1 or above.


Explanation


This error occurs when an ORDER BY, GROUP BY or JOIN is used for disk tables.


Cause


The following error description can be viewed with the AltiErr utility:





The temporary tablespace is used when an ORDER BY, GROUP BY or JOIN is executed on a disk table.


The temporary tablespace is a disk tablespace and has the fixed page size of 8K.


However, this error occurs when a record that is bigger than 8K was created while using the temporary tablespace.


Note: If the size of a single page (8K) of the disk tablespace is exceeded, the data length is approximately greater than or equal to 3000
bytes.


# Example


iSQL> CREATE TABLE T1( I1 CHAR(6000) ) TABLESPACE SYS_TBS_DISK_DATA;

Create success.

iSQL> insert into t1 values(1);

1 row inserted.

iSQL> insert into t1 values(2);

1 row inserted.

iSQL> insert into t1 values(3);

1 row inserted.

iSQL> SELECT * FROM T1 ORDER BY I1;


ERR-311E0 : The estimated size of the index key exceeds the maximum limit.


# Example(6.3.1)


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


Action


1. You can use the hint ‘TEMP_TBS_MEMORY’ to avoid the size limit (8K) of disk temporary tablespaces.


When this hint is used, the temporary area is used in memory instead of disk. Thus, query performance is also improved.


iSQL> SELECT /*+ TEMP_TBS_MEMORY */ * FROM T1 ORDER BY I1;

I1

-------------
1

2

3

3 rows selected.


2. Upgrade to 6.3.1 or above. This error does not occur in 6.3.1 or above.


Reference


<How to use a hint>


iSQL>SELECT * FROM t1 ORDER BY c2;
iSQL>SELECT /*+ TEMP_TBS_MEMORY */ * FROM t1 ORDER BY c2;

### ERR-31283 Unable to create a primary key or a unique key constraint in the local non-prefixed index


Version

Explanation
Cause

Action

Reference


Version


6.1.1 or below


Explanation


Unable to create a non-prefixed index on a partitioned table using the primary key or unique key.


This error message is output when a user tries to create a primary key or a unique key constraint in the local non-prefixed index.


Cause


The following error description can be viewed with the AltiErr utility:


The global index is not supported for ALTIBASE HDB 6.1.1 or below.


Therefore, all partitioned indexes are local indexes and local non-prefixed indexes cannot be created for the primary key or unique
index.


This is because even if a column value within a particular partition is unique, its uniqueness within a table cannot be guaranteed.


(The entire partition must be scanned to check the unique property of a table but a local index only needs to check the unique property
within a certain partition.)


Action


1. The prefixed index needs to be created with a primary key or unique index. In other words, the partition key column and the index
column should be the same for a primary key or unique index.


2. You can create a non-unique index if you want to create an index with a column that is not the same as the partition key column.


3. It is possible to create a primary key or unique index with a global index if you upgrade to ALTIBASE HDB 6.3.1 or above.


# Examples


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


ERR-31283 : Unable to create a primary key or a unique key constraint in the local non-prefixed index.


1. The following example changes the primary key column order and creates a local prefixed index for the primary key.


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


2. The following example creates a non-unique index (instead of a local non-prefixed index) for the primary key.


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


3. The following example upgrades to version 6.3.1 and then creates a global index for the primary key.


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


Reference


# Index types for partitioned tables

|Classification 1|Classification 2|Classification 3|Index Type|Supported by Altibase|
|---|---|---|---|---|
|Partitioned Index|index part key = table part key|index part key = index key|(Partitioned) Local prefixed Index|Yes|
|||index part key != index key|(Partitioned) Local nonprefixed Index|Yes|
||index part key != table part key|index part key = index key|(Partitioned) Global prefixed Index|No|
|||index part key != index key|(Partitioned) Global nonprefixed Index|No|
|Non-partitioned Index|||Non-partitioned global index|Supported for 6.3.1 and above|



The difference between a prefixed index and a non-prefixed index is uniqueness.


A non-prefixed index cannot be created for the primary key or unique index because even if it is unique within the partition, it cannot be
guaranteed to be unique within the entire table.

### ERR-40029 Failed to invoke a system function, flock_trywrlock()


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


The following message is ouput to altibase_boot.log due to startup failure.


ERR-40029(errno=16) Failed to invoke a system function, flock_trywrlock()


Cause


The Altibase server started while the Altibase process was already up.


Action


Wait until the Altibase process is terminated and start the server.


Reference


N/A

### ERR-4102C Incompatible NLS between the client and the server


Version

Explanation
Cause

Action

Reference


1. Check the Character Set

2. How to set the environmental variables


Version


5.3.3 or below


Explanation


Unable to connect to the client.


Cause


This error occurs if the character sets for Altibase and the client differ.


Action


Set the NLS value of the client to the same value as the Altibase server. You can also set the character set by using the environmental
variable called ALTIBASE_NLS_USE from iSQL.


Reference


1. Check the Character Set


iSQL> SELECT nls_use, nls_characterset FROM v$nls_parameters;

NLS_USE                  NLS_CHARACTERSET

----------------------------------------------------------------------------------
---
US7ASCII                 MS949


(NLS_USE : Client Character Set, NLS_CHARACTERSET : DB Character Set)


2. How to set the environmental variables


Execute the following command from the client shell.


$export ALTIBASE_NLS_USE=MS949

### ERR-41047 The transaction is already active


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to transition to AUTOCOMMIT mode.


Unable to execute certain queries and SELECT statements on metadata.


Cause


This error message is output if the user attempts to change to AUTOCOMMIT mode when a transaction that is not committed or rolled
back exists


Action


Change the commit mode after checking whether a previously processed transaction exists in the session and execute the COMMIT or
ROLLBACK statement.


Reference


N/A

### ERR-41059 Task pool overflow


Version

Explanation
Cause

Action

Reference


Version


4.3.9 or above


Explanation


Unable to connect to the database.


If this error message occurs, the existing session or transaction has to be terminated first to fix it.


Cause


1. The number of new connections has increased.


2. The task was not cleaned up because it was not closed properly after the connection was terminated.


3. Connection fails because the status of all service threads is EXECUTE.


4. A new connection cannot be established because the number of transactions exceeds TRANSACTION_TABLE_SIZE.


Action


If the server cannot be stopped, either terminate the client or disable was connection.


Otherwise,


1. Increase MAX_CLIENT.


2. View the application source to check that the tasks have been properly closed.


3. Increase TRANSACTION_TABLE_SIZE.


Reference


1. Check the open files using the ulimit command since the number of sockets may exceed the number permitted for the Altibase
account. Increase, if necessary.


Ulimit -n 1048576


2. Add the following to the /etc/security/limits.conf file.


Altibase account soft nofile 1048576

Altibase account hard nofile 1048576

### ERR-4109C invalid session property


Version

Explanation
Cause

Action

Reference


Version


4.3.9 or above


Explanation


Unable to connect to the database.


Cause


This error occurs when the Altibase client and server are of the same major version but the client has a higher patch version than the

server.


Action


Upgrade the Altibase server version or downgrade the client version.


This error message is generally output due to a major version discrepancy.


Yet, this error can also occur due to a cm protocol version discrepancy, despite the server and client having the same major version.


Reference


N/A

### ERR-410CF Too many statements have been allocated to this session


Version

Explanation
Cause

Action

Reference


Version


5.3.3 or above


Explanation


Unable to execute the query.


Cause


This error message is output when the number of queries allocated to a single session for preparation exceeded the limit.


Action


1. Check the prepared queries of the session to determine whether the session is running normally and increase
MAX_STATEMENTS_PER_SESSION.


2. Check whether the application is closing statements.


Reference


N/A

### ERR-410D5 Client unable to establish connection.


Version

Explanation
Cause

Action

Reference


Version


5.5.1 or above


Explanation


Unable to connect to database.


Cause


1. A general user cannot connect with IPC as there is an IPC channel for sysdba only.


2. Altibase port or connection method (TCP/UNIX/IPC) is incorrect or is blocked by a firewall.


Action


Clean up unnecessary IPC sessions:


Check the IPC session information from V$SESSION and clean up if there are unnecessary sessions connected, then get another IPC
channel and re-connect.


Reference


<How to change the IPC_CHANNEL_COUNT>


Search the IPC_CHANNEL_COUNT from $ALTIBASE_HOME/conf/altibase.properties, then change it and restart the database.

### ERR-7101d Protocol header error


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


The client is unable to establish a connection.


The following error message is output to $ALTIBASE_HOME/trc/altibase_boot.log.


ERR-7101d(errno=11) Protocol header error.(TCP 127.0.0.1:60264)
Protocol processing failed. Close connection...


Cause


The following error description can be viewed with the AltiErr utility:


This error message is written to altibase_boot.log when a client of a version incompatible with the server tried to establish a connection.


This error keeps a message history and does not adversely affect the Altibase server.


Action


If this error persists, find the client that is attempting to connect, then reinstall it with a version compatible with the server.


Reference


If this error persists, find the client that is attempting to connect and reinstall it with a version compatible with the server.


For ALTIBASE HDB 5.3.1 or below, the cm protocol version of the server and client must be identical for the client to connect to
the server.

For ALTIBASE HDB 5.3.3 or above, backward compatibility for the server and client is supported. The client can connect to a
server of the same or newer version regardless of its cm protocol version whereas, connection fails if the client is of a newer
version than the server.
In this context, the first three numbers of a product version are denoted as the version (the fourth and succeeding numbers
which indicate the patch versions are irrelevant).


# How to check the server/client version


Server version


Client version





Using the JDBC driver

$ java -jar $ALTIBASE_HOME/lib/Altibase.jar
JDBC Driver Info : Altibase Ver = 6 3 1 0 9 for JavaVM v1 4 CMP:7 1 1 Mar 20 2014 17:07:25


Using the ODBC library on Windows

Altibase Installation Directory (e.g., C:\Program Files (x86)\Altibase\altibase-server-6.3.1) -> lib Directory
altiodbc dll -> Properties -> Details -> Product Version


# Examples of server and client compatibility for different versions












|Col1|Server<br>Version|Client<br>Version|Result|Remarks|
|---|---|---|---|---|
|Server Version ><br>Client Version<br>(5.3.3 or above)|6.3.1|5.3.3|Succeeds|Backward compatibility is supported for 5.3.3 or above.|
|Server<br>Version > Client<br>Version<br>(5.3.1 or below)|6.3.1|4.3.9|Fails|Backward compatibility is supported only if the version of both the server and client is 5.3.3 or above.<br>Since the client version is older than 5.3.3, backward compatibility is not supported. For 4.3.9, connection<br>succeeds only if the cm protocol versions are the same.|
|ServerVersion < Client<br>Version|6.1.1|6.3.1|Fails|If the version of the client is newer than the server, connection fails regardless of the Altibase version.<br>The version of the client must be the same or older than the server.|


### ERR-51039 Invalid Protocol

Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to connect to database.


Cause


This error occurs if the ALTIBASE CM_PROTOCOL version is different.


Action


Set the Client CM_PROTOCOL version according to CM_PROTOCOL of the database server.


Reference


N/A

### ERR-51043 Communication link failure


Version

Explanation
Cause

Action

Reference


Version


6.3.1


Explanation


Connection is disconnected.


Cause


This error has various causes. The following are the main causes:


1. The server forcefully closed the client connection due to timeout.


2. The user forcefully closed the connection.


3. The database was shut down.


Action


1. Tune a long-running query and increase the session’s timeout value


2. Check whether the database service runs normally.


Reference


N/A

### ERR-6100D Sender failed to handshake with the peer server


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to start replication.


Cause


This error occurs if the IP or REPLICATION_PORT_NO is different.


Action


Check the IP or PORT number and recreate the replication object.


Reference


N/A

### ERR-61035 Receiver - An update conflict occurred


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


A replication update conflict occurred


Cause


1. The data that needs to be updated does not exist.


2. The target value is different.


Action


This error occurred when a replication object tried to change data that has already been changed.


This is a common message. If you want to revert to the value of the target server, you must change the property and start the server
again.


REPLICATION_UPDATE_REPLACE=1 ($ALTIBASE_HOME/conf/altibase.properties)


Reference


N/A

### ERR-61100 rpERR_ABORT_RPC_DUPLICATE_REPLICATION Duplicate replication


### names. The replication name already exists in the database.

Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to create a replication object.


Cause


A replication object using the same object name, IP or PORT number exists.


Action


Neither change the object name nor permit the duplicate IP or PORT number.


Increase the number of network cards as needed.


Reference


N/A

### ERR-71018 Failed to invoke the read() system function


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


The client connection abnormally terminates.


Cause


If the server checks whether a session is running after a client session has already been physically terminated, the server confirms that
the session is physically terminated and outputs this error message to clean up the session.


Action


1. Check whether the network is unstable.


2. Check whether the client program malfunctions.


Reference


N/A

### ERR-71019 Failed to invoke the write() system function Flush protocol failed. Close connection


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


The connection to the client is terminated or there is no incident.


Cause


The connection was terminated due to a network problem or the abnormal termination of a client program.


Action


1. Check whether the network is stable.


2. Check the operation status of the client program.


3. Check the connection close part of the database from the application and verify that it is disconnected.


Reference


N/A

### ERR-91020 No Connection State


Version

Explanation
Cause

Action

Reference


Version


6.3.1


Explanation


Unable to execute query.


Cause


The connection to the Altibase server is not valid. This usually happens when a connection was established with the wrong password.


Action


1. Check the password.


2. Reconnect to the server.


Reference


N/A

### ERR-9103D Data parsing error - LineXXXX


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to upload data.


Cause


1. Data is not recognized due to the column delimiter being included in the data.


2. The column delimiter is the same as the data.


Action


1. This error usually occurs when a column delimiter is included in the data and this causes the data not to be recognized; an iLoader
statement has column and row delimiters.


For example, if a column contains ^C_ and a row contains ^R_, an error occurs because the delimiters are included in the data.


However, if the delimiters are written in a more complex way and the data is downloaded/uploaded again, an error does not occur.


2. This error occurs when the actual data is the same as the delimiter during data uploads.


The data should not overlap with the delimiter when the data is downloaded.


Reference


N/A

### ERR-201436 The number of host variables exceed the maximum limit (1024)


Version

Explanation
Cause

Action

Reference


Version


4.3.9 or above


Explanation


Unable to create the procedure.


Cause


1024 is the maximum number of host variables that can be used. This error occurs if the number of host variables in the procedure
exceeded this number.


Action


The WITH clause (for ALTIBASE HDB 6.3.1 or above) can be used to reduce the number of host variables. It can use more than 1024 by
using variable substitution as shown below.


WITH dataset1 AS (SELECT V_YYYYMM AS V_EXEC_YYYYMM FROM dual )


For versions below 6.3.1, either separate the processing modules for each task or change the logic to handle it in a different way, apart
from a host variable as the WITH clause is not supported.


Reference


N/A

### ERR-11025 The data file already exists


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to create tablespace.


Cause


This error occurs if the datafile already exists when creating a database or adding a datafile.


Action


1. Check whether a duplicate datafile name exists in the directory.


2. Change the datafile name to a distinct one and then add the datafile or recreate the tablespace/database.


Reference


N/A

### ERR-11027 The data file does not exist


Version


Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to start server.


Cause


This error occurs if data file information stored in meta data cannot be found in the specified path.


Action


1. Start the server until CONTROL phase and check whether the datafile path matches the meta data.


2. If not, input the correct path.


Reference


N/A

### ERR-11035 The tablespace does not have enough free space


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


There is a delay in transaction processing.


Cause


There is not enough available space in the tablespace.


Action


Add a datafile to increase available space in the tablespace.


Reference


N/A

### ERR-11136 The LogAnchor file already exists


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to start server.


Cause


This error occurs if a database is recreated or recovery is executed on a path that has previously stored a database.This is because the
server tries to create duplicate log anchor files from the /logs directory.


Action


This error message is output when the server is unable to start due to duplicate loganchor files while recreating the database or
executing recovery. Check the loganchor files directory and delete unnecessary loganchor files.


Reference


N/A

### ERR-135181 Invalid data type length


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to execute SELECT or DML or perform migration.


Cause


This error occurs if the data property is invalid.


Action


DML statements cannot be executed due to unmatched data properties. Check whether the type or length of the data matches.


Reference


N/A

### ERR-266300 Request of fetching data to an unprepared SQL statement


Version

Explanation
Cause

Action

Reference


Version


6.3.1 or above


Explanation


Unable to fetch.


Cause


This error occurs when the database is running in non-autocommit mode and the COMMIT statement is executed before a fetch
operation has completed.


If the fetch operation continues (using the open cursor) after the COMMIT statement has been executed, the cursor becomes invalid and
the fetch operation fails.


Action


1. Run the database in autocommit mode.


2. When running in non-autocommit mode, complete the fetch operation and then execute CLOSE CURSOR. Afterwards, execute
COMMIT.


3. Use two or more multiple connections and execute the FETCH and COMMIT statements separately.


Reference


N/A

### ERR-266447 mmERR_ABORT_TOO_MANY_STATEMENTS_IN_THE_SESSION


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to execute query.


Cause


This error occurs if QUERY_STACK_SIZE is insufficient when a statement has not been properly closed.


Action


Check whether the statement is closed properly after query execution or increase QUERY_STACK_SIZE.


Reference


N/A

### ERR-31020 You cannot execute DDL on a replicated table


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to execute DDL on table.


Cause


This error occurs when a DDL statement is executed on a replication target table.


Action


DDL statements cannot be directly executed on replication target tables.


Instead, the user should :


1. Stop replication on both servers.


2. Remove the table from the replication table list.


3. Execute the DDL statement on the table.


4. Once execution is complete, add the table back to the replication table list.


Reference


N/A

### ERR-3103F No DDL statement is allowed to be executed on a replicated table


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to execute DDL statement on replication tables.


Cause


This error is due to DDL restrictions on replication tables.


Action


Set REPLICATION_ENABLE to 1.


iSQL>ALTER SYSTEM SET REPLICATION _DDL_ENABLE = 1;


Reference


It is not advisable to execute DDL during replication. If the user wants to apply the REPLICATION_ENABLE property, we recommend that
it is done only in the development stage and for the sake of convenience.


<How to execute DDLs in older versions>


The ALTER COLUMN statement is not supported for ALTIBASE HDB 5.3.3 or below and under certain circumstances, it is impossible to
execute DDL statements. For example, a DDL statement that includes a table column position change or a DDL statement that is
currently unsupported by Altibase cannot be executed as it is. In such cases, the user needs to back up the data of the replication target
table before executing the DDL statement and recover the data afterwards.


In general, the user can take the following steps:


1. Stop services.


2. Check that the replication gap between the target nodes is 0.


3. Stop replication between the target nodes.


4. Remove the table from the replication table list.


5. Back up the table data using iLoader.


Shell> iloader formout –T table1 –f table1.fmt

Shell> iloader out –f table1.fmt –d table1.dat


6. Execute the DDL statement on the table.


7. Recover the table data using iLoader.


Shell> iloader in –f table1.fmt –d table1.dat


8. Add the table back to the replication table list.


9. Start replication between the target nodes.


Since data backup and recovery consume time, the user is recommended to estimate how long services will be stopped before
performing the above operations.


Further information about iLoader options is available in the iLoader User's Manual.

### ERR-311B1 The user must have SYSDBA privilege(s) to execute this statement


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to execute query.


Cause


This error occurs when a user without SYSDBA privileges performs an operation that requires the SYSDBA privilege.


Action


Connect as SYSDBA or receive privileges from SYSDBA, and then perform the operation.


Reference


N/A

### ERR-312C4 Cannot execute this DDL on a replicated table when the system property REPLICATION_DDL_ENABLE is 0


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to execute DDL on replication tables.


Cause


This error is due to DDL restrictions on replication tables.


Action


Set REPLICATION_ENABLE to 1.


iSQL>ALTER SYSTEM SET REPLICATION _DDL_ENABLE = 1;


Reference


It is not advisable to execute DDLs during replication. If the user wants to apply the REPLICATION_ENABLE property, we recommend that
it is done only in the development stage and for the sake of convenience.


<How to execute DDLs in older versions>


The ALTER COLUMN statement is not supported for ALTIBASE HDB 5.3.3 or below and under certain circumstances, it is impossible to
execute DDL statements. For example, a DDL statement that includes a table column position change or a DDL statement that is
currently unsupported by Altibase cannot be executed as it is. In such cases, the user needs to back up the data of the replication target
table before executing the DDL statement and recover the data afterwards.


In general, the user can take the following steps:


1. Stop services.


2. Check that the replication gap between the target nodes is 0.


3. Stop replication between the target nodes.


4. Remove the table from the replication table list.


5. Back up the table data using iLoader.


Shell> iloader formout –T table1 –f table1.fmt

Shell> iloader out –f table1.fmt –d table1.dat


6. Execute the DDL statement on the table.


7. Recover the table data using iLoader.


Shell> iloader in –f table1.fmt –d table1.dat


8. Add the table back to the replication table list.


9. Start replication between the target nodes.


Since data backup and recovery consume time, the user is recommended to estimate how long services will be stopped before
performing the above operations.


Further information about iLoader options is available in the iLoader User's Manual.

### ERR-1051 Memory allocation failed


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Database hang.


Cause


Insufficient system memory.


Action


Either delete unnecessary memory table data or increase the system memory.


Reference


N/A

### ERR-0001c Unable to shutdown the communication channel


Version


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to connect to session.


Cause


The network is disconnected or the client has a problem.


Action


This error message is just a notification saying that the database server detected and tried to disconnect an abnormal connection. The
client did not exist, so the session was closed.


The internal thread (CM detector) which checks abnormal connections is closing the connection. Thus, no action is required.


Reference


N/A

### ERR-01002 Invalid character in use


Version

Explanation
Cause

Action

Reference


Version


All versions.


Explanation


This error is occurs when searching Korean with the LIKE clause.


Cause


A character beyond the range of the character set is also stored.


Action


The user is advised to take the following steps:


1. Download the table data using iLoader.


2. Shut down the Altibase server.


3. Change NLS_USE to MS940 from $ALTIBASE_HOME/conf/altibase.properties


4. Start the Altibase server.


5. Truncate the table that has a problem (not DELETE)


6. Upload the data downloaded from (1) using iLoader.


The user is advised to use the same character set that matches the server. For example, use MS949/UTF8 for Korean, rather than
KSC5601.


Reference


N/A

### ERR-01027 No more IPC channel


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to connect to IPC.


Cause


Unable to establish connection as IPC_CHANNEL_COUNT has exceeded the maximum value.


Action


Restart the server after increasing IPC_CHANNEL_COUNT.


Reference


N/A

### ERR-0109F Library file for external procedure(function) not found


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to create procedure.


Cause


This error occurs when the library path of an external procedure cannot be found.


Action


Check whether the library path is set properly.


$ALTIBASE_HOME/lib


Reference


N/A

### ERR-11009 Failed to invoke a system function, shmat()


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to create database.


Cause


This error can occur under the following circumstances:


ALTIBASE HDB is being used in shared memory mode.
a lack of shared memory due to too small shared memory kernel parameter value.
the shared memory key value(SHM_DB_KEY) is already in use.


Action



1.

2.



Check the shared memory kernel parameter value. If it is too small, change it to an appropriate value.
If SHM_DB_KEY is an arbitrary value used by the system, change the key value.



Reference


N/A

### ERR-11107 smERR_ABORT_UNABLE_TO_CREATE_CUZ_VOL_MAX_DB_SIZE Unable to create the tablespace because the database would be larger than VOLATILE_MAX_DB_SIZE


Version

Explanation
Cause

Action

Reference


Version


5.1.1. or above


Explanation


Unable to execute DML statements.


Cause


This error occurs when creating a volatile tablespace larger than VOLATILE_MAX_DB_SIZE.


Action



1.

2.



Increase VOLATILE_MAX_DB_SIZE (to a value larger than the actual usage) in $ALTIBASE_HOME/conf/altibase.properties.
Restart the Altibase server.



The user is recommended to set the maximum value of VOLATILE_MAX_DB_SIZE to the sum of MEM_MAX_DB_SIZE and
VOLATILE_MAX_DB_SIZE which accounts for less than 60~70% of physical memory.


Reference


N/A

### ERR-11118 The update log size '…' is bigger than TRX_UPDATE_MAX_LOGSIZE '…'


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


This error occurs when there is a bulk modifying operation.


This error message applies only to memory tables.


Cause


In Altibase, this error occurs and the ROLLBACK is executed for the corresponding transaction when the number of redo log files due to
bulk transactions exceeds TRX_UPDATE_MAX_LOGSIZE (The TRX_UPDATE_MAX_LOGSIZE property restricts the number of log files
created by a DML statement.).


Action


If the transaction has to be executed with a single query only, the user is advised to change the property in a session level as follows.


ALTER SESSION SET TRX_UPDATE_MAX_LOGSIZE = 0; (Disabling property)


However, the user should remember that the number of redo logfiles will increase and this might cause a disk full error. Also, when
executing bulk operations, an X lock is acquired in a table to prevent resource increase due to MVCC. Thus, caution is advised that any
SELECT or DML statements might have to wait for an X lock to be released.


Reference


N/A

### ERR-31233 The fixed record size exceeds the page size


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to create view.


iSQL> create table t1(c1 char(5000));

Create success.
iSQL> create table t2(c1 char(5000)) tablespace sys_tbs_disk_data;

Create success.


ERR-31233 : Fixed record size exceeds a page size.


Cause


This error occurs if a fixed column that exceeds 32K for memory tables or 8K for disk tables is used. Disk tables use disk temporary
tables for sorting/grouping operations. This error can occur if the length of a temporary record exceeds 8K.


Action


1. Set the table column to VARIABLE, not FIXED when creating for the first time.


2. If the error occurs when executing the SELECT statement using disk temporary tables, the memory temporary table should be used
with the hint /*+ temp_tbs_memory */.


Reference


N/A

### ERR-31240 Invalid request to process SQL statement


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to create a program that has thread architecture.


Cause


This usually happens in the thread architecture program and sometimes concurrency control for the thread connection object is not
performed properly. When this happens, the protocols to be exchanged between the Altibase server and client can be in the wrong
order.


Action


First, if the structure of the program is a thread, you must check whether concurrency control was performed properly or the query is
executed in the following order: PREPARE > BINDING > EXECUTE.


Reference


N/A

### ERR-4105A Several statements still open


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to execute query.


Cause


This error occurs when a query (e.g., CREATE TABLE) is executed while the Fetch protocol is in progress.


Action


The DDL statement has to be executed once CURSOR FETCH is complete in all sessions, or after closing all the open cursors, the code
needs to be changed to enable DDL statements to be executed in other sessions.


Reference


N/A

### ERR-410B7 Invalid size of data to bind to a host variable Data Size


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to execute query.


Cause


Generally, this error occurs when a developer fails to initialize the variable or when there are incorrect values. It can also occur when
binding sentence B rather than binding sentence A (after executing PREPARE) due to concurrency control failure in a thread
environment. (Sentence A needs to be bound with 20 bytes but instead, sentence B is bound with 100 bytes, thus it is incorrectly
handled.).


Action


The user is advised to check whether the length exceeds the host variables output and verify that there are no problems with concurrency
as part of the thread handling.


Reference


N/A

### ERR-51024 Different protocol versions


Version

Explanation
Cause

Action

Reference


Version


6.3.1


Explanation


Unable to start replication


Cause


This error occurs if the replication protocol version of a replication server is different.


Action


Check the replication protocol version and verify that they are the same.


Reference


N/A

### ERR-5102E Invalid cursor state


Version

Explanation
Cause

Action

Reference


Version


5.1.1 or above.


Explanation


Unable to use cursor or execute the SELECT statement using cursors in the application.


Cause


This error can occur:


when trying to open the cursor without closing the cursor that has been used.
when trying to fetch the committed cursor.
if the application's cursor calling order is incorrect.
due to a concurrency control issue if a single connection is shared in a multithreaded environment.


Action


Sometimes, when the user program is found to be a thread, there is a possibility of handling an invalid cursor from its own thread
because concurrency control of the connection object is not performed properly. Thus, the CLOSE CURSOR clause has to be used
whenever finishing using a cursor to resolve the problem.





1. Fix CURSOR DECLARE/OPEN/FETCH/CLOSE errors.


2. If the connection is being shared in a multithreaded environment, output thread numbers to check the cursor calling order.


3. If thread concurrency cannot be controlled in the application, give each thread a connection.


Reference


This error can occur after a version upgrade to ALTIBASE HDB 5.1.1 or above.

### ERR-51041 Indicator variable required but not supplied


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


This error occurs when using a precompiler in the development environment.


Cause


When the INDICATOR variable is not specified while NULL is returned as the return value of a column in the SELECT statement, this error
occurs with SQL_SUCCESS_WITH_INFO.


Action


int IND_C1;


int IND_C2;


EXEC SELECT C1, C2


INTO :H_C1 INDICATOR :IND_C1, :H_C2 INDICATOR :IND_C2;


This error can be avoided by using the option ‘unsafe_null’ in the precompiler option or using the INDICATOR variable as in the above
example.


Reference


N/A

### ERR-5104F Communication link failure.


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to connect to database.


Cause


This error means the session is disconnected from the query execution process. This is generally because the connection is lost due to a
timeout policy. It can sometimes occur due to network problems.


Action


1. Check whether the log contains information about any disconnected sessions from altibase_boot.log.


2. Check whether the cautions for thread programs were followed accordingly.


3. Check whether there was a problem in the network.


Reference


N/A

### ERR-5105A The connection does not exist.


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to execute query.


Cause


This error occurs when the database is not connected or it is trying to handle a query while it is disconnected.


1. When executing a query while connection is lost due to a timeout policy.


2. A unique connection name is used which does not exist for the thread program.


Action


1. Shorten the processing time by increasing the session timeout or tune the query.


2. Check whether a unique connection exists when using a thread program.


Reference


N/A

### ERR-52027 String data right-truncated


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to select data.


Cause


This error message is output when:


1. the CHAR data type value returned from the SELECT statement is larger than the declared host variable.


2. a parsing error occurs in the executed query due to NULL values or special characters.


Action


1. Connect to the database


2. Check the table column size.


3. Declare the host variable used in the statement with the length (column size + 1 byte).


4. Check whether rpad was used in the statement where the error occurred.


5. If so, rewrite the query.


Reference


N/A

### ERR-61001 A conflict occurred while executing the received statement


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to update a replication table.


Cause


This error occurs when an UPDATE statement is executed on replication table data of a different value.


This error message is output with ERR-61035.


Action


Check whether the data exists and then execute the statement.


Reference


N/A

### ERR-61016 rpERR_ABORT_RP_SENDER_MAKE_XLOG Sender Failed to make an xlog


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Replication is stopped.


Cause


Altibase sends the replication information in the form of Xlogs.


Xlogs are included and managed by the Altibase redo log to guarantee the database transaction order.


This error occurs when there is a lack of disk space in the redo log area.


Action


Check the directory and the disk space with the following SQL command.


iSQL> select value1 from v$property where name = 'LOG_DIR';


VALUE1

---------------------------------------------------------
/home/luj/altibase_home/logs


1 row selected


Reference


A lack of disk space occurs, mainly because checkpointing is not executed for a long time or failed to execute. Thus, it is important to
find out the cause of the error.

### ERR-61023 rpERR_ABORT_RP_REPLICATION_DISABLED Replication is disabled


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to create a replication object.


Cause


The replication port needs to be changed.


Action


The replication port is set to 0 by default. This needs to be changed to a value other than ‘20300’ (the database default port). Once it is
changed, the database has to be restarted and replication can be used again.


Reference


N/A

### ERR-61036 Receiver err_not found in deleteXlog()


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to execute the DELETE statement.


Cause


This error occurs when there is no data for the DELETE statement in a replication environment. -Not Found (with ERR-61000)


Action


Verify that the data exists and execute the DELETE statement.


Reference


N/A

### ERR-6103a Receiver err_not_found in updateXlog()


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to execute the UPDATE statement.


Cause


This error occurs when there is no data found for the UPDATE statement in a replication environment. -Not Found (withERR-61000)


Action


Verify that the data exists and execute the UPDATE statement.


Reference


N/A

### ERR-610CF The transaction table size of the replication does not match


Version

Explanation
Cause

Action

Reference


Version


4.3.9 or above


Explanation


Unable to start replication.


Cause


The TRANSACTION_TABLE_SIZE property for both local and remote servers is different.


Action


Set an identical value for TRANSACTION_TABLE_SIZE on both servers. Change it from the altibase.properties file located in
$ALTIBASE_HOME/conf/ directory, then restart the server.


Reference


1. TRANSACTION_TABLE_SIZE can be changed without recreating the database from Altibase versions 5.1.5.9.3 or above.


2. If TRANSACTION_TABLE_SIZE is changed, older versions need to restart the server.

### ERR-610D2 The primary key column count of the replicated table does not match


Version

Explanation
Cause

Action

Reference


Version


4.3.9 or above


Explanation


Unable to start replication.


Cause


This error occurs if the primary key is different from the replication target table.


Action


Set an identical value for the primary key on both servers.


Reference


N/A

### ERR-610a0 Sender Stopping REP1 sender thread


Version

Explanation


Cause

Action

Reference


Version


All versions


Explanation


Replication is stopped.


Cause


If the existing number of logfiles exceeds REPLICATION_MAX_LOGFILE, Altibase stops replication and deletes all the log files preceding
the Restart Redo Point. This error occurs when replication starts from a new Restart Redo Point.


Action


Disable REPLICATION_MAX_LOGFILE or increase it.


Reference


N/A

### ERR-61113 A replicated table must have a primary key.


Version

Explanation
Cause

Action

Reference


Version


6.3.1


Explanation


Unable to start replication.


Cause


This error occurs if there is no primary key in a replication target table.


Action


Create a primary key on the replication target table.


Reference


N/A

### ERR-71015 cmERR_ABORT_SELECT_ERROR Failed to invoke the select() system function


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to connect to database.


Cause


Failed to call the SELECT function that detects the socket during network communication.


Action


This error can occur because of a network issue, server shutdown, session disconnection due to timeout and a sudden increase of
connection requests. Check the OS network status or distribute connection overloads.


Reference


N/A

### ERR-91013 The query was too long the maximum length is 65536


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to create procedure or execute query.


Cause


This error occurs if either a long procedure or query that exceeds the maximum text buffer size of iSQL is created or executed.


Action


The maximum length that can be handled in iSQL is 655536, by default. This can be changed from an environmental variable called
ISQL_BUFFER_SIZE.


Increase ISQL_BUFFER_SIZE to create a long procedure.


$ export ISQL_BUFFER_SIZE=256000


Reference


N/A

### ERR-9102B utERR_ABORT_Token_Value_Range_Error Token value length overflow. Maximum token length=0%d. Column =1%s, Value=2%s


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to execute iLoader.


Cause


This error occurs when the uploaded data length in iLoader is bigger than the table column size.


Action


1. Check the datafile that the iLoader reads and check whether there is data bigger than the table column which is about to be uploaded.


2. Check whether the delimiter of the row and column are configured properly.


Reference


N/A

### ERR-91044 Error occurred during data file IO.


Version

Explanation
Cause

Action

Reference


Version


6.3.1


Explanation


Unable to input/output file data while using iLoader.


Cause


1. There is no more space in the file system.


2. The file does not exist.


3. The file size is too big


3. The file size is too big


Action


1. Check the available space in the file system.


2. Check whether the file name for uploading exists.


3. Check the file size.


Reference


N/A

### ERR-A100C Conversion not applicable


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to execute query.


Cause


Each column type has a compatibility matrix but this error occurs when an incompatible query is executed.


Action


Ensure the compatibility between column types when handling a query.


Reference


For further information about column type compatibility, refer to the General Reference manual.

### ERR-A1013 Calculation stack overflow


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to execute query.


Cause


If there are not enough stacks necessary for the query being executed by an object from the internal query handling procedure, this error

occurs.


Action


The user is advised to execute the following SQL command then re-execute the query that caused this error.


iSQL>ALTER SESSION SET STACK SIZE = 8192;


The user is advised to change it from the session only rather than from the entire system because it causes a memory increase.


Reference


N/A

### ERR-0104E The property XXX is read-only


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to modify property.


Cause


This error occurs when a property cannot be modified online.


Action


Certain properties have the read-only attribute and cannot be modified online.


Instead of using the ALTER statement, modify the property in $ALTIBASE_HOME/conf/altibase.properties, and then restart the server.


Reference


N/A

### ERR-110F0 Unable to extend the tablespace (SYS_TBS_MEM_DIC) because the database would be larger than MEM_MAX_DB_SIZE(12582912K)


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


INSERT/UPDATE/DELETE statements cannot be executed on memory tablespaces. Only the SELECT statement is executable.


Cause


This error occurs when the total sum of memory tablespaces (SYS_TBS_MEM_DIC+SYS_TBS_MEM_DATA+USER_MEMORY_TABLESPACE)
exceeds MEM_MAX_DB_SIZE.


Action


MEM_MAX_DB_SIZE is the maximum amount of memory that can be used by memory tablespaces. For further information, refer to the [T

echnical Article] ALTIBASE Monitoring Query Guide, [TS01] Memory Table Space Usage (page 29).


The tablespace area cannot be returned unless a tablespace is dropped. (The COMPACT command can return the blank page, but the
effect is negligible. Thus, it is not recommended.)


Therefore, if MEM_MAX_DB_SIZE is set lower than the actual amount, change the value of MEM_MAX_DB_SIZE from
$ALTIBASE_HOME/conf/altibase.proeperties and restart the Altibase server process.


It is recommended to set the maximum value of MEM_MAX_DB_SIZE as the sum of VOLATILE_MAX_DB_SIZE and MEM_MAX_DB_SIZE
within 60 to 70 percent of the physical memory.


Checking MEM_MAX_DB_SIZE


iSQL> SELECT value1/32/1024 FROM v$property WHERE name = 'MEM_MAX_DB_SIZE';
VALUE1/32/1024 : 32768


1 row selected.


The above example shows the maximum number of pages that can be used (It is divided by 32 as the size of one page is 32K).
Checking Usage


iSQL> SELECT space_name, maxsize/32/1024, alloc_page_count FROM v$mem_tablespaces;

SPACE_NAME    : SYS_TBS_MEM_DIC
MAXSIZE/32/1024 : 4294967295

ALLOC_PAGE_COUNT : 129


SPACE_NAME    : SYS_TBS_MEM_DATA
MAXSIZE/32/1024 : 4294967295

ALLOC_PAGE_COUNT : 29313


SPACE_NAME    : MEM_TBS
MAXSIZE/32/1024 : 3200

ALLOC_PAGE_COUNT : 3201


3 rows selected.


1. The above example shows the current usage of the memory tablespace. There are 32,643 pages allocated in total.


2. For SYS_TBS_MEM_DIC and SYS_TBS_MEM_DATA, they have not reached MAXSIZE but the error has occurred because the sum of all
the memory tablespaces has almost reached MEM_MAX_DB_SIZE.


The current sum shows the value of 32,643 and the actual MEM_MAX_DB_SIZE is 32,768. Thus, there are still 125 pages that can be
allocated. However, as the default value of EXPAND_CHUNK_PAGE_COUNT (the number of pages by which to increase the size of the
memory tablespace) is 128, it means that all the pages are currently being used.


(The error occurs when MEM_MAX_DB_SIZE is exceeded because the transaction tried to expand.)


Each memory tablespace has its own MAXSIZE. This error not only occurs when it has reached its MAXSIZE but also when the
sum of all the memory tablespaces exceeds MEM_MAX_DB_SIZE.


Restarting Altibase server after increasing MEM_MAX_DB_SIZE


Shell> vi $ALTIBASE_HOME/conf/altibase.properties

....

....

UNIXDOMAIN_FILEPATH  =?/trc/cm-unix
MEM_MAX_DB_SIZE    = 1G       <===== Change this value to the appropriate size (Using
GB/MB unit)

LOG_FILE_SIZE     = 10M

....

....

:wq!


Shell> server restart


It needs to restart the server after modification.


Checkpoint Image File Size


For in-memory databases of ALITBASE HDB, any modified data from in-memory databases is saved on disk when checkpointing is
executed. The disk file where memory data is saved is called the Checkpoint Image file. This file cannot be resized, which means that
once it is expanded, it cannot be reduced.


In order to reduce the Checkpoint Image file size, REORG has to be executed. This has to be done with the migration of all
data, including the disk database.


Reference


N/A

### ERR-41041 Another SYSDBA session is already running


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to connect as SYSDBA.


Cause


This error occurs if a client tries to connect to the database as SYSDBA when there already is another client connected as SYSDBA.


Action


Only one client can be connected as SYSDBA per session.


1. Check whether a previously connected session exists.


2. If necessary, clean up the session.


3. Reconnect.


Reference


N/A

### ERR-51014 Function sequence error


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


This is an application error.


Cause


The function calling sequence is incorrect.


Action


This is usually an application issue. Take the following steps:


1. Check whether concurrency is being controlled by the connection handles in the thread program.


2. Use cursors when executing the SELECT statement to check whether execution completes successfully after a timeout occurs, without
raising an error.


3. Check whether functions are called in order.


4. Check whether the application has been debugged for memory invasion.


Reference


N/A

### ERR-5104D Connection timeout


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to connect to database.


Cause


This error occurs if the client attempts to establish a connection but does not receive any response from the server
within CONNECTION_TIMEOUT.


Action


Check the network connection.


Reference


N/A

### ERR-51067 Neither PORT_NO in the connection string or ALTIBASE_PORT_NO environment variable are set


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to connect to the server.


Cause


This error message is output if ALTIBASE_PORT_NO was not set at installation or the altibase.properties file cannot be opened.


Action


1. Check whether ALTIBASE_PORT_NO is properly set within the altibase.properties file.


2. Check the permissions of the altibase.properties file or the directory in which the file exists.


Reference


N/A

### ERR-51192 The call to getaddrinfo() failed. The host name or service may be unknown


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to connect to database using iSQL.


Cause


This error occurs due to invalid server information when using the 'is' script to connect to the database.


Action


1. Check whether the server information of the 'is' script is correct.


(SERVER = localhost)


2. If the error persists although the server information is correct, change localhost information to 127.0.0.1 and reconnect.


Reference


N/A

### ERR-61000 The received record was not found in the database


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to execute DML statements on replication tables.


Cause


This error occurs when an UPDATE statement is executed on replication table data of a different value or the primary key does not exist.


Action


Check whether the data exists and then execute the statement.


Reference


N/A

### ERR-6100C rpERR_ABORT_RP_RECEIVER_NOT_FOUND The receiver does not exist


Version


Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to start or stop replication.


Cause


This error occurs if the replication receiver stops.


Action


Check the remote server status (replication target) and the network connection.


Reference


N/A

### ERR-1102A Tablespace node not found


Version

Explanation
Cause

Action

Reference


Version


All versions


Explanation


Unable to execute query.


Cause


An attempt has been made to create a table to a tablespace that does not exist.


Action


Check the name of the tablespace to which the table is to be saved.


Reference


N/A

## ALTIBASE HDB Administration


Topics of interest to ALTIBASE HDB DBAs and System Administrators.


### How to terminate a session

About this document.

|Purpose|This document explains how to terminate a session in ALTIBASE HDB.|
|---|---|
|Applied to|4.3.9 or later|
|Prerequisite|Administrator's Manual|



Description


You may want to terminate an ALTIBASE HDB session in abnormal behavior. In order to terminate the session, you have to connect to
ALTIBASE HDB as SYSDBA.


Only SYSDBA can terminate a session.



1.


2.


3.



Connecting as SYSDBA


-bash-3.00$ isql -SYSDBA

----------------------------------------------------------------
Altibase Client Query utility.

Release Version 5.5.1.0.4

Copyright 2000, ALTIBASE Corporation or its subsidiaries.
All Rights Reserved.

----------------------------------------------------------------
Write UserID : sys

Write Password :

ISQL_CONNECTION = UNIX, SERVER = localhost, PORT_NO = 27562
iSQL(SYSDBA)>


Finding the session identifier which you want to terminate.
Assume that there is a session connected from "192.168.1.84", and you want to terminate that session.


iSQL(SYSDBA)> SELECT id, comm_name FROM v$session;

ID     COMM_NAME

-----------------------------------------------------------------------------
--
4      UNIX

5      TCP 192.168.1.84:35679

2 rows selected.


The session identifier which you want to terminate is "5".
Terminating the session.
You can use the query below to terminate the session by specifying the session identifier.


ALTER DATABASE MYDB SESSION CLOSE [session identifier];



You can terminate the session #5 and verify that is terminated as shown below:


iSQL(SYSDBA)> alter database mydb session close 5;

Alter success.
iSQL(SYSDBA)> SELECT id, comm_name FROM v$session;

ID     COMM_NAME

--------------------------------------------------------------------------------
4      UNIX

1 row selected.


If an active transaction is running on the session, ALTIBASE HDB rollbacks the transaction before terminating the session. Therefore,
sometimes, terminating a session may not work immediately.

### Useful SQL


Miscellaneous queries


State of a service thread


ALTIBASE HDB V4

ALTIBASE HDB V5

Lock & Transaction Information


ALTIBASE HDB V4

ALTIBASE HDB V5

Redo log files
Cumulative count of total transaction waits due to logging
Memory Ager GAP
Finding a query which blocks ager from aging.
Memory status
Total memory usage of ALTIBASE


State of a service thread


This query shows the state of a service thread

|Column Name|Description|
|---|---|
|RUN_MODE|the type of service thread. (dedicated or shared)|
|STATE|currenly working state (executing / pool)|
|CNT|the number of threads in the run_mode and state|



ALTIBASE HDB V4


SELECT TYPE RUN_MODE,

STATE,
COUNT(*) CNT
FROM  V$SERVICE_THREAD

GROUP BY RUN_MODE, STATE


ALTIBASE HDB V5


SELECT RUN_MODE,

STATE,
COUNT(*) CNT
FROM  V$SERVICE_THREAD

GROUP BY RUN_MODE, STATE


Lock & Transaction Information


This query shows the lock & transaction information including replication transactions

|Column Name|Description|
|---|---|
|TX_ID|current transaction id|
|BLOCKED_TX_ID|the transaction id which current transaction is waiting for|
|STATUS|current transaction's status|
|USER_NAME|the user name who has issued the current transaction|
|SESSION_ID|the session id which has issued the current transaction|
|CLIENT_IP|client IP address|
|AUTOCOMMIT|autocommit|
|LOCK_DESC|Lock description|
|FIRST_UPDATE_TIME|the first update time of current transaction|
|TABLE_NAME|table_name|
|CURRENT_QUERY|current query in the current transaction|
|DDL|DDL or not|
|LOGFILE#|logfile number|



ALTIBASE HDB V4


ALTIBASE HDB V4 does not support this features.


ALTIBASE HDB V5


SELECT TX.ID TX_ID,

WAIT_FOR_TRANS_ID BLOCKED_TX_ID,
DECODE(TX.STATUS, 0, 'BEGIN', 1, 'PRECOMMIT', 2, 'COMMIT_IN_MEMORY', 3, 'COMMIT', 4, 'ABORT',
5, 'BLOCKED', 6, 'END') STATUS,
DECODE(TX.LOG_TYPE, 0, U1.USER_NAME, 'REPLICATION') USER_NAME,
DECODE(TX.LOG_TYPE, 0, TX.SESSION_ID, RT.REP_NAME) SESSION_ID,
DECODE(TX.LOG_TYPE, 0, ST.COMM_NAME, RR.PEER_IP) CLIENT_IP,
DECODE(ST.AUTOCOMMIT_FLAG, 1, 'ON', 'OFF') AUTOCOMMIT,

L.LOCK_DESC,
DECODE(TX.FIRST_UPDATE_TIME, 0, '0', TO_CHAR(TO_DATE('1970010109','YYYYMMDDHH') +
TX.FIRST_UPDATE_TIME / (60*60*24), 'MM/DD HH:MI:SS')) FIRST_UPDATE_TIME,
U2.USER_NAME||'.'||T.TABLE_NAME TABLE_NAME,
DECODE(TX.LOG_TYPE, 0, SUBSTR(ST.QUERY, 1, 10), 'REMOTE TX_ID '||REMOTE_TID)

CURRENT_QUERY,
DECODE(TX.DDL_FLAG,0, 'NON-DDL', 'DDL') DDL,
DECODE(TX.FIRST_UNDO_NEXT_LSN_FILENO, -1, '-', TX.FIRST_UNDO_NEXT_LSN_FILENO)

'LOGFILE#'

FROM  V$TRANSACTION TX,
V$LOCK L LEFT OUTER JOIN
(

SELECT ST.*,

SS.AUTOCOMMIT_FLAG,

SS.DB_USERID,

SS.COMM_NAME
FROM  V$STATEMENT ST,
V$SESSION SS

WHERE SS.ID = ST.SESSION_ID

AND SS.CURRENT_STMT_ID = ST.ID
) ST ON L.TRANS_ID = ST.TX_ID LEFT OUTER JOIN
V$REPRECEIVER_TRANSTBL RT ON L.TRANS_ID = RT.LOCAL_TID LEFT OUTER JOIN
V$REPRECEIVER RR ON RT.REP_NAME = RR.REP_NAME LEFT OUTER JOIN
V$LOCK_WAIT LW ON L.TRANS_ID = LW.TRANS_ID LEFT OUTER JOIN

SYSTEM_.SYS_USERS_ U1 ON ST.DB_USERID = U1.USER_ID,

SYSTEM_.SYS_TABLES_ T LEFT OUTER JOIN

SYSTEM_.SYS_USERS_ U2 ON T.USER_ID = U2.USER_ID

WHERE  TX.ID = L.TRANS_ID AND T.TABLE_OID = L.TABLE_OID AND TX.STATUS != 6 -- 6:END

ORDER BY TX.ID, ST.ID, TX.FIRST_UPDATE_TIME DESC ;


Redo log files


This query shows the information of transaction log files


|Column Name|Description|
|---|---|
|OLDEST_LOG_FILE|the oldest log file in LOG_DIR|
|CURRENT_LOG_FILE|the current log file number which service thread is writing to.|
|LOG_FILE_GAP|the interval between CURRENT_LOG_FILE and OLDEST_LOG_FILE|


SELECT OLDEST_ACTIVE_LOGFILE OLDEST_LOGFILE,

CURRENT_LOGFILE CURRENT_LOGFILE,

CURRENT_LOGFILE-OLDEST_ACTIVE_LOGFILE LOGFILE_GAP
FROM V$ARCHIVE ;


Cumulative count of total transaction waits due to logging


This query shows the number of total waits due to lack of the log space exhaustion for logging. If the value returns
non-zero value you'd better increase PREPARE LOG FILE COUNT in altibase properties


SELECT LF_PREPARE_WAIT_COUNT
FROM V$LFG;


Memory Ager GAP


This query shows the memory ager thread's information

|Column Name|Description|
|---|---|
|GC_NAME|the Ager name. (LOGICAL_AGER for index aging, DELTHRD for data aging)|
|SCNOFTAIL|The commit SCN of the tail in garbage collection OID list|
|MINMEMSCNINTXS|The lowest of the view SCNs for memory-related transactions|
|GC_GAP|the OID count which ager has to proceed|



SELECT GC_NAME,

SCNOFTAIL,

MINMEMSCNINTXS,

ADD_OID_CNT-GC_OID_CNT GC_GAP
FROM V$MEMGC ;


Finding a query which blocks ager from aging.


Aging process will be blocked if there's a transaction which refers the aging target. This query shows the query which
blocks from aging


|Column Name|Description|
|---|---|
|SESSION_ID|the session identifier|
|TOTAL_TIME|total elapsed time|
|EXECUTE_TIME|the elapsed time for query execution|
|TX_ID|transaction identifier|
|QUERY|query string|


SELECT SESSION_ID,

TOTAL_TIME,

EXECUTE_TIME,

TX_ID,

QUERY
FROM  V$STATEMENT
WHERE TX_ID IN (

SELECT ID

FROM V$TRANSACTION
WHERE MEMORY_VIEW_SCN = (

SELECT MINMEMSCNINTXS

FROM V$MEMGC

LIMIT 1

)
) AND EXECUTE_FLAG = 1

ORDER BY 2 DESC ;


Memory status


This query shows the memory state arranged by ALTIBASE module

|Column Name|Description|
|---|---|
|NAME|the name of ALTIBASE module|
|ALLOC_MAX(M)|max alloc size of memory|
|ALLOC(M)|current size of memory|



SELECT NAME,
ROUND(MAX_TOTAL_SIZE/1024/1024) 'ALLOC_MAX(M)',
ROUND(ALLOC_SIZE/1024/1024) 'ALLOC(M)'
FROM  V$MEMSTAT

ORDER BY 3 DESC ;


Total memory usage of ALTIBASE


This query shows the total memory state

|Column Name|Description|
|---|---|
|ALLOC_MAX(M)|max alloc size of memory|
|ALLOC(M)|current size of memory|



SELECT ROUND(SUM(MAX_TOTAL_SIZE)/1024/1024) 'ALLOC_MAX(M)',
ROUND(SUM(ALLOC_SIZE)/1024/1024) 'ALLOC(M)'
FROM V$MEMSTAT ;


SQL about Objects


Memory Table

ALTIBASE HDB V4

ALTIBASE HDB V5

Queue Table


ALTIBASE HDB V4

ALTIBASE HDB V5
Memory table / Queue table Index information

ALTIBASE HDB V4

ALTIBASE HDB V5

Disk Table

Disk Index


ALTIBASE HDB V4

ALTIBASE HDB V5

Sequence
Synonym

ALTIBASE HDB V4

ALTIBASE HDB V5
PSM (Stored Procedures / Function / Typeset)

ALTIBASE HDB V4

ALTIBASE HDB V5

View


ALTIBASE HDB V4

ALTIBASE HDB V5

System Privileges
Object Privileges
Constraint list

Primary Key, Foreign Key, Unique Constraint
Index column list

Index information


Memory Table


This query returns the object information about a memory table

|Column Name|Description|
|---|---|
|USER_NAME|the object owner|
|TABLE_NAME|the object name|
|TABLESPACE_NAME|the tablespace name which this object belongs to|
|TABLE_OID|the table object identifier|
|ALLOC(M)|allocated size of the memory table (Megabyte)|
|USED(M)|actually used size of the memory table (Megabyte)|
|EFFICIENCY(%)|store efficiency of the object|



ALTIBASE HDB V4


SELECT A.USER_NAME,

B.TABLE_NAME,
'SYS_TBS_MEMORY' TABLESPACE_NAME,

C.TABLE_OID,
ROUND((C.FIXED_ALLOC_MEM + C.VAR_ALLOC_MEM)/(1024*1024),2) 'ALLOC(M)',
ROUND((C.FIXED_USED_MEM + C.VAR_USED_MEM)/(1024*1024),2) 'USED(M)',
ROUND((C.FIXED_USED_MEM + C.VAR_USED_MEM)/(C.FIXED_ALLOC_MEM +
C.VAR_ALLOC_MEM)*100,2) 'EFFICIENCY(%)'

FROM  SYSTEM_.SYS_USERS_ A,

SYSTEM_.SYS_TABLES_ B,
V$MEMTBL_INFO C
WHERE  A.USER_NAME <> 'SYSTEM_'
AND B.TABLE_TYPE = 'T'

AND A.USER_ID = B.USER_ID

AND B.TABLE_OID = C.TABLE_OID;


ALTIBASE HDB V5


SELECT A.USER_NAME,

B.TABLE_NAME,

D.NAME TABLESPACE_NAME,

C.TABLE_OID,
ROUND((C.FIXED_ALLOC_MEM + C.VAR_ALLOC_MEM)/(1024*1024),2) 'ALLOC(M)',
ROUND((C.FIXED_USED_MEM + C.VAR_USED_MEM)/(1024*1024),2) 'USED(M)',
ROUND((C.FIXED_USED_MEM + C.VAR_USED_MEM)/(C.FIXED_ALLOC_MEM +
C.VAR_ALLOC_MEM)*100,2) 'EFFICIENCY(%)'

FROM  SYSTEM_.SYS_USERS_ A,

SYSTEM_.SYS_TABLES_ B,
V$MEMTBL_INFO C,
V$TABLESPACES D
WHERE  A.USER_NAME <> 'SYSTEM_'
AND B.TABLE_TYPE = 'T'

AND A.USER_ID = B.USER_ID

AND B.TABLE_OID = C.TABLE_OID

AND B.TBS_ID = D.ID ;


Queue Table


This query returns the object information about a queue table


|Column Name|Description|
|---|---|
|USER_NAME|the object owner|
|TABLE_NAME|the object name|
|TABLESPACE_NAME|the tablespace name which this object belongs to|
|TABLE_OID|the table object identifier|
|ALLOC(M)|allocated size of the memory table (Megabyte)|
|USED(M)|actually used size of the memory table (Megabyte)|
|EFFICIENCY(%)|store efficiency of the object|


Queue table structure is the same as a memory table except its functionality.


ALTIBASE HDB V4


SELECT A.USER_NAME,

B.TABLE_NAME,
'SYS_TBS_MEMORY' TABLESPACE_NAME,

C.TABLE_OID,
ROUND((C.FIXED_ALLOC_MEM + C.VAR_ALLOC_MEM)/(1024*1024),2) 'ALLOC(M)',
ROUND((C.FIXED_USED_MEM + C.VAR_USED_MEM)/(1024*1024),2) 'USED(M)',
ROUND((C.FIXED_USED_MEM + C.VAR_USED_MEM)/(C.FIXED_ALLOC_MEM +
C.VAR_ALLOC_MEM)*100,2) 'EFFICIENCY(%)'

FROM  SYSTEM_.SYS_USERS_ A,

SYSTEM_.SYS_TABLES_ B,
V$MEMTBL_INFO C
WHERE  A.USER_NAME <> 'SYSTEM_'
AND B.TABLE_TYPE = 'Q'

AND A.USER_ID = B.USER_ID

AND B.TABLE_OID = C.TABLE_OID;


ALTIBASE HDB V5


SELECT A.USER_NAME,

B.TABLE_NAME,

D.NAME TABLESPACE_NAME,

C.TABLE_OID,
ROUND((C.FIXED_ALLOC_MEM + C.VAR_ALLOC_MEM)/(1024*1024),2) 'ALLOC(M)',
ROUND((C.FIXED_USED_MEM + C.VAR_USED_MEM)/(1024*1024),2) 'USED(M)',
ROUND((C.FIXED_USED_MEM + C.VAR_USED_MEM)/(C.FIXED_ALLOC_MEM +
C.VAR_ALLOC_MEM)*100,2) 'EFFICIENCY(%)'

FROM  SYSTEM_.SYS_USERS_ A,

SYSTEM_.SYS_TABLES_ B,
V$MEMTBL_INFO C,
V$TABLESPACES D
WHERE  A.USER_NAME <> 'SYSTEM_'
AND B.TABLE_TYPE = 'Q'

AND A.USER_ID = B.USER_ID

AND B.TABLE_OID = C.TABLE_OID

AND B.TBS_ID = D.ID ;


Memory table / Queue table Index information


This query returns the index information of a memory table and a queue object


|Column Name|Description|
|---|---|
|USER_NAME|the object owner|
|OBJECT_TYPE|the type of object|
|OBJECT_NAME|the object name|
|TABLESPACE_NAME|the tablespace name which this object belongs to|
|||


|Col1|Col2|
|---|---|
|INDEX_NAME|the table object identifier|
|INDEX_TYPE|the table object identifier|


Estimating of memory index is very simple in most cases. ALTIBASE HDB index just consists of pointers, thus you just multiply
16 bytes by the number of table rows to get the size of each index.


ALTIBASE HDB V4


SELECT C.USER_NAME,
DECODE(F.TABLE_TYPE, 'Q', 'QUEUE', 'T', 'TABLE') OBJECT_TYPE,

TABLE_NAME OBJECT_NAME,
'SYS_TBS_MEMORY' TABLESPACE_NAME,

E.INDEX_NAME,
RPAD(CASE2(E.INDEX_TYPE=1, 'B-TREE', 'R-TREE'),10,' ') INDEX_TYPE
FROM  V$INDEX B,

SYSTEM_.SYS_USERS_ C,

SYSTEM_.SYS_INDICES_ E,

SYSTEM_.SYS_TABLES_ F

WHERE  B.INDEX_ID = E.INDEX_ID

AND E.USER_ID = C.USER_ID

AND F.USER_ID = E.USER_ID

AND F.TABLE_OID = B.TABLE_OID
AND C.USER_NAME <> 'SYSTEM_';


ALTIBASE HDB V5


SELECT C.USER_NAME,
DECODE(F.TABLE_TYPE, 'Q', 'QUEUE', 'T', 'TABLE') OBJECT_TYPE,

TABLE_NAME OBJECT_NAME,

D.SPACE_NAME TABLESPACE_NAME,

E.INDEX_NAME,
RPAD(CASE2(E.INDEX_TYPE=1, 'B-TREE', 'R-TREE'),10,' ') INDEX_TYPE
FROM  V$INDEX B,

SYSTEM_.SYS_USERS_ C,
V$MEM_TABLESPACES D,

SYSTEM_.SYS_INDICES_ E,

SYSTEM_.SYS_TABLES_ F

WHERE  B.INDEX_ID = E.INDEX_ID

AND E.USER_ID = C.USER_ID

AND F.USER_ID = E.USER_ID

AND F.TBS_ID = D.SPACE_ID

AND F.TABLE_OID = B.TABLE_OID
AND C.USER_NAME <> 'SYSTEM_';


Disk Table


This query returns the object information about a disk table


|USER_NAME|the object owner|
|---|---|
|TABLE_NAME|the object name|
|TABLESPACE_NAME|the tablespace name which this object belongs to|
|TABLE_OID|the table object identifier|
|ALLOC(M)|allocated size of the memory table (Megabyte)|


SELECT USER_NAME,

A.TABLE_NAME,

D.NAME TBS_NAME,

A.TABLE_OID,
ROUND((B.DISK_PAGE_CNT*8)/1024) 'ALLOC(M)'

FROM  SYSTEM_.SYS_TABLES_ A,
V$DISKTBL_INFO B,

SYSTEM_.SYS_USERS_ C,
V$TABLESPACES D

WHERE  A.TABLE_OID = B.TABLE_OID

AND A.USER_ID = C.USER_ID

AND A.TBS_ID=D.ID
AND C.USER_NAME <> 'SYSTEM_';


Disk Index


This query returns the object information about a disk index

|Column Name|Description|
|---|---|
|USER_NAME|the object owner|
|TABLE_NAME|the object name|
|TBS_NAME|the tablespace name which this object belongs to|
|INDEX_NAME|the name of index|
|INDEX_TYPE|the type of index|
|ALLOC(M)|allocated size of the memory table (Megabyte)|



ALTIBASE HDB V4


SELECT USER_NAME,

TABLE_NAME,

D.NAME TBS_NAME,

E.INDEX_NAME,
RPAD(CASE2(E.INDEX_TYPE=1,'B-TREE', 'R-TREE'),10,' ') INDEX_TYPE,
ROUND(D.A_EXTENT_PAGE_COUNT*D.PAGE_SIZE*A.EXTENT_TOTAL_COUNT/1024/1024) 'ALLOC(M)'
FROM  V$SEGMENT A,
V$INDEX B,
V$TABLESPACES D,

SYSTEM_.SYS_USERS_ C,

SYSTEM_.SYS_INDICES_ E,

SYSTEM_.SYS_TABLES_ F

WHERE  A.SEGMENT_DESC = B.INDEX_SEG_DESC

AND B.INDEX_ID = E.INDEX_ID

AND E.USER_ID = C.USER_ID

AND A.SPACE_ID = D.ID

AND F.TBS_ID = D.ID
AND A.SEGMENT_TYPE='INDEX'

AND F.USER_ID = E.USER_ID

AND F.TABLE_OID = B.TABLE_OID ;


ALTIBASE HDB V5


SELECT USER_NAME,

TABLE_NAME,

D.NAME TBS_NAME,

E.INDEX_NAME,
RPAD(CASE2(E.INDEX_TYPE=1,'B-TREE', 'R-TREE'),10,' ') INDEX_TYPE,
ROUND(D.EXTENT_PAGE_COUNT*D.PAGE_SIZE*A.EXTENT_TOTAL_COUNT/1024/1024) 'ALLOC(M)'
FROM  V$SEGMENT A,
V$INDEX B,
V$TABLESPACES D,

SYSTEM_.SYS_USERS_ C,

SYSTEM_.SYS_INDICES_ E,

SYSTEM_.SYS_TABLES_ F

WHERE  A.SEGMENT_PID = B.INDEX_SEG_PID

AND B.INDEX_ID = E.INDEX_ID

AND E.USER_ID = C.USER_ID

AND A.SPACE_ID = D.ID

AND F.TBS_ID = D.ID
AND A.SEGMENT_TYPE='INDEX'

AND F.USER_ID = E.USER_ID

AND F.TABLE_OID = B.TABLE_OID ;


Sequence


This query returns the object information about a sequence


|Column Name|Description|
|---|---|
|USER_NAME|the object owner|


|SEQ_NAME|the object name|
|---|---|
|MIN|the minimum value of the sequence|
|CURRENT_SEQ|the current value of the sequence|
|MAX|the maximum value of the sequence|
|INCREMENT|increment property of the sequence|
|IS_CYCLE|can be cycled|
|CACHE|the cache size of the sequence|


SELECT USER_NAME,

TABLE_NAME SEQ_NAME,

MIN_SEQ MIN,

CURRENT_SEQ,

MAX_SEQ MAX,

INCREMENT_SEQ INCREMENT,

IS_CYCLE,

CACHE_SIZE CACHE
FROM  V$SEQ A,

SYSTEM_.SYS_USERS_ B,

SYSTEM_.SYS_TABLES_ C

WHERE  A.SEQ_OID = C.TABLE_OID

AND B.USER_ID = C.USER_ID
AND B.USER_NAME <> 'SYSTEM_' ;


Synonym


This query returns the object information about a synonym

|Column Name|Description|
|---|---|
|SYNONYM_OWNER|the object owner|
|SYNONYM_NAME|the object name|
|OBJECT_OWNER|the minimum value of the sequence|
|OBJECT_NAME|the current value of the sequence|
|LAST_DDL_TIME|the last DDL occured time|



ALTIBASE HDB V4


SELECT NVL(USER_NAME, 'PUBLIC') SYNONYM_OWNER,

SYNONYM_NAME,

SCHEMA_NAME OBJECT_OWNER,

OBJECT_NAME

FROM  SYSTEM_.SYS_SYNONYMS_ A LEFT OUTER JOIN

SYSTEM_.SYS_USERS_ B ON A.USER_ID = B.USER_ID

WHERE

A.SCHEMA_NAME != 'SYSTEM_' ;


ALTIBASE HDB V5


SELECT NVL(USER_NAME, 'PUBLIC') SYNONYM_OWNER,

SYNONYM_NAME,

OBJECT_OWNER_NAME OBJECT_OWNER,

OBJECT_NAME,
TO_CHAR(A.LAST_DDL_TIME, 'YYYY-MM-DD HH:MI:SS') LAST_DDL_TIME

FROM  SYSTEM_.SYS_SYNONYMS_ A LEFT OUTER JOIN

SYSTEM_.SYS_USERS_ B ON A.SYNONYM_OWNER_ID = B.USER_ID
WHERE  OBJECT_OWNER_NAME <> 'SYSTEM_' ;


PSM (Stored Procedures / Function / Typeset)


This query returns the object information about a PSM

|Column Name|Description|
|---|---|
|USER_NAME|the object owner|
|PSM_TYPE|the type of PSM|
|PSM_NAME|the name of PSM|
|STATUS|the status of PSM|
|LAST_DDL_TIME|the last DDL occured time|



ALTIBASE HDB V4


SELECT A.USER_NAME,
DECODE(OBJECT_TYPE, 0, 'PROCEDURE', 1, 'FUNCTION', 3, 'TYPESET') PSM_TYPE,

PROC_NAME PSM_NAME,
DECODE(STATUS, 0, 'VALID', 'INVALID') STATUS

FROM  SYSTEM_.SYS_USERS_ A,

SYSTEM_.SYS_PROCEDURES_ B
WHERE A.USER_ID = B.USER_ID AND A.USER_NAME <> 'SYSTEM_' ;


ALTIBASE HDB V5


SELECT A.USER_NAME,
DECODE(OBJECT_TYPE, 0, 'PROCEDURE', 1, 'FUNCTION', 3, 'TYPESET') PSM_TYPE,

PROC_NAME PSM_NAME,
DECODE(STATUS, 0, 'VALID', 'INVALID') STATUS,
TO_CHAR(B.LAST_DDL_TIME, 'YYYY-MM-DD HH:MI:SS') LAST_DDL_TIME

FROM  SYSTEM_.SYS_USERS_ A,

SYSTEM_.SYS_PROCEDURES_ B
WHERE A.USER_ID = B.USER_ID AND A.USER_NAME <> 'SYSTEM_' ;


View


This query returns the object information about a view


|Column Name|Description|
|---|---|
|USER_NAME|the object owner|
|VIEW_NAME|the type of PSM|
|STATUS|the status of PSM|
|LAST_DDL_TIME|the last DDL occured time|


ALTIBASE HDB V4


SELECT A.USER_NAME,

B.TABLE_NAME VIEW_NAME,
DECODE(STATUS, 0, 'VALID', 'INVALID') STATUS

FROM  SYSTEM_.SYS_USERS_ A,

SYSTEM_.SYS_TABLES_ B,

SYSTEM_.SYS_VIEWS_ C

WHERE  A.USER_ID = B.USER_ID

AND B.TABLE_ID = C.VIEW_ID
AND B.TABLE_TYPE = 'V' ;


ALTIBASE HDB V5


SELECT A.USER_NAME,

B.TABLE_NAME VIEW_NAME,
DECODE(STATUS, 0, 'VALID', 'INVALID') STATUS,
TO_CHAR(B.LAST_DDL_TIME, 'YYYY-MM-DD HH:MI:SS') LAST_DDL_TIME

FROM  SYSTEM_.SYS_USERS_ A,

SYSTEM_.SYS_TABLES_ B,

SYSTEM_.SYS_VIEWS_ C

WHERE  A.USER_ID = B.USER_ID

AND B.TABLE_ID = C.VIEW_ID
AND B.TABLE_TYPE = 'V' ;


System Privileges


This query returns the object information about system privileges


|Column Name|Description|
|---|---|
|GRANTEE|the grantee|
|GRANTOR|the granter|
|PRIV_NAME|the name of privilege|


SELECT A.USER_NAME GRANTEE,

C.USER_NAME GRANTOR,
REPLACE(D.PRIV_NAME, '_', ' ') PRIV_NAME

FROM  SYSTEM_.SYS_USERS_ A,

SYSTEM_.SYS_GRANT_SYSTEM_ B,

SYSTEM_.SYS_USERS_ C,

SYSTEM_.SYS_PRIVILEGES_ D
WHERE  C.USER_NAME <> 'SYSTEM_'

AND B.GRANTEE_ID = A.USER_ID

AND B.GRANTOR_ID = C.USER_ID

AND B.PRIV_ID = D.PRIV_ID ;


Object Privileges


This query returns the information about object privileges

|Column Name|Description|
|---|---|
|GRANTEE|the grantee|
|GRANTOR|the granter|
|OBJECT_OWNER|the object owner|
|OBJECT_NAME|the object name|
|OBJECT_TYPE|the object type|
|PRIV_NAME|the name of privilege|
|GRANTABLE|is grant-able|



SELECT A.USER_NAME GRANTEE,

C.USER_NAME GRANTOR,

F.USER_NAME OBJECT_OWNER,

E.TABLE_NAME OBJECT_NAME,

E.TABLE_TYPE OBJECT_TYPE,
REPLACE(D.PRIV_NAME, '_', ' ') PRIV_NAME,
DECODE(B.WITH_GRANT_OPTION, 0, 'NO', 'YES') GRANTABLE

FROM  SYSTEM_.SYS_USERS_ A,

SYSTEM_.SYS_GRANT_OBJECT_ B,

SYSTEM_.SYS_USERS_ C,

SYSTEM_.SYS_PRIVILEGES_ D,

SYSTEM_.SYS_TABLES_ E,

SYSTEM_.SYS_USERS_ F
WHERE  C.USER_NAME <> 'SYSTEM_'

AND B.GRANTEE_ID = A.USER_ID

AND B.GRANTOR_ID = C.USER_ID

AND B.PRIV_ID = D.PRIV_ID

AND B.OBJ_ID = E.TABLE_ID

AND E.USER_ID = F.USER_ID

ORDER BY GRANTEE, GRANTOR, OBJECT_OWNER, OBJECT_TYPE, OBJECT_NAME, PRIV_NAME ;


Constraint list


This query returns the information about object constraints

|Column Name|Description|
|---|---|
|USER_NAME|the object owner|
|OBJECT_NAME|the object name|
|OBJECT_TYPE|the object type|
|CONST_NAME|the constraint name|
|CONST_type|the constraint type|
|COLUMN_NAME|the column name|



SELECT USER_NAME,

TABLE_NAME OBJECT_NAME,
DECODE(B.TABLE_TYPE, 'T', 'TABLE', 'Q', 'QUEUE', 'V', 'VIEW', 'SEQUENCE') OBJECT_TYPE,

C.CONSTRAINT_NAME CONST_NAME,
DECODE(C.CONSTRAINT_TYPE,0, 'FK', 1, 'NOT NULL', 2, 'UNIQUE', 3, 'PK', 4, 'NULL', 5, 'TIMESTAMP',
6, 'LOCAL UNIQUE') CONST_TYPE,

COLUMN_NAME

FROM  SYSTEM_.SYS_USERS_ A,

SYSTEM_.SYS_TABLES_ B,

SYSTEM_.SYS_CONSTRAINTS_ C,

SYSTEM_.SYS_COLUMNS_ D,

SYSTEM_.SYS_CONSTRAINT_COLUMNS_ E

WHERE  A.USER_ID=C.USER_ID

AND B.TABLE_ID = C.TABLE_ID

AND A.USER_ID = D.USER_ID

AND A.USER_ID = E.USER_ID

AND B.TABLE_ID = D.TABLE_ID

AND B.TABLE_ID = E.TABLE_ID

AND C.CONSTRAINT_ID = E.CONSTRAINT_ID

AND D.COLUMN_ID = E.COLUMN_ID
AND A.USER_NAME <> 'SYSTEM_' ;


Primary Key, Foreign Key, Unique Constraint


This query returns the information about object constraints


|Column Name|Description|
|---|---|
|USER_NAME|the object owner|
|TABLE_NAME|the table name|
|CONST_TYPE|the constraint type|
|CONST_NAME|the constraint name|
|INDEX_NAME|the index name|
|R_TABLE|the referenced table|
|R_INDEX|the referenced index|


SELECT A.USER_NAME,

B.TABLE_NAME,
DECODE(C.CONSTRAINT_TYPE,0, 'FK', 2, 'UNIQUE', 3, 'PK', 4, 'NULL') CONST_TYPE,

C.CONSTRAINT_NAME CONST_NAME,
DECODE(D.INDEX_NAME,C.CONSTRAINT_NAME,NULL,INDEX_NAME) INDEX_NAME,
(SELECT TABLE_NAME FROM SYSTEM_.SYS_TABLES_ WHERE TABLE_ID = C.REFERENCED_TABLE_ID)

R_TABLE,
(SELECT INDEX_NAME FROM SYSTEM_.SYS_INDICES_ WHERE INDEX_ID = C.REFERENCED_INDEX_ID)

R_INDEX

FROM   SYSTEM_.SYS_USERS_ A,

SYSTEM_.SYS_TABLES_ B,

SYSTEM_.SYS_CONSTRAINTS_ C LEFT OUTER JOIN

SYSTEM_.SYS_INDICES_ D ON C.INDEX_ID = D.INDEX_ID

WHERE  C.TABLE_ID = B.TABLE_ID
AND A.USER_NAME <> 'SYSTEM_'

AND C.USER_ID = A.USER_ID
AND C.CONSTRAINT_TYPE IN (3, 0, 2, 6) --PK, FK, UNIQUE, LOCAL UNIQUE

ORDER BY TABLE_NAME, CONST_TYPE ;


Index column list


This query returns the information about index columns

|Column Name|Description|
|---|---|
|USER_NAME|the object owner|
|TABLE_NAME|the table name|
|INDEX_NAME|the index name|
|COLUMN_NAME|the column name|
|COL_ORDER|column order (when composite index)|



SELECT D.USER_NAME,

C.TABLE_NAME,

B.INDEX_NAME,

E.COLUMN_NAME,

A.INDEX_COL_ORDER COL_ORDER,
DECODE(A.SORT_ORDER, 'A', 'ASC', 'D', 'DESC') SORT

FROM  SYSTEM_.SYS_INDEX_COLUMNS_ A,

SYSTEM_.SYS_INDICES_ B,

SYSTEM_.SYS_TABLES_ C,

SYSTEM_.SYS_USERS_ D,

SYSTEM_.SYS_COLUMNS_ E
WHERE  D.USER_NAME <> 'SYSTEM_'
AND C.TABLE_TYPE = 'T'

AND A.INDEX_ID = B.INDEX_ID

AND A.TABLE_ID = C.TABLE_ID

AND A.USER_ID = D.USER_ID

AND A.COLUMN_ID = E.COLUMN_ID

ORDER BY USER_NAME, TABLE_NAME, INDEX_NAME, COL_ORDER ;


Index information


This query returns the information about an index

|Column Name|Description|
|---|---|
|USER_NAME|the object owner|
|INDEX_NAME|the index name|
|INDEX_ID|the index name|
|TABLE_NAME|the table name|
|TBS_NAME|the tablespace which this object belongs to|
|IS_UNIQUE|unique index or not|
|COLUMN_CNT|the number of columns|



SELECT A.USER_NAME,

C.INDEX_NAME,

C.INDEX_ID,

B.TABLE_NAME,
NVL(D.NAME, 'SYS_TBS_MEMORY') TBS_NAME,

C.IS_UNIQUE,

C.COLUMN_CNT

FROM  SYSTEM_.SYS_USERS_ A,

SYSTEM_.SYS_TABLES_ B,

SYSTEM_.SYS_INDICES_ C LEFT OUTER JOIN
V$TABLESPACES D ON C.TBS_ID = D.ID
WHERE  A.USER_NAME <> 'SYSTEM_'
AND B.TABLE_TYPE = 'T'

AND C.TABLE_ID = B.TABLE_ID

AND C.USER_ID = A.USER_ID

ORDER BY B.TABLE_NAME, C.INDEX_NAME ;


SQL about Replication


Replication Sender
Replication Receiver
Replication gap
Replication status
Log buffer or file status occupied by an unsent XLOG

ALTIBASE HDB V4

ALTIBASE HDB V5

Replication table list


Replication Sender


This query returns the replication sender status


|Column Name|Description|
|---|---|
|REP_NAME|the name of replication object|
|REMOTE_IP|the IP address of remote replicated server|
|REMOTE_REP_PORT|the port number of remote replicated server|
|STATUS|the status of replication sender|
|NETWORK|check whether network error or not|


XSN XLOG Sequence Number : the final position in a log file from which logs were transmitted by the replication sender


SELECT REP_NAME,

PEER_IP REMOTE_IP,

PEER_PORT REMOTE_REP_PORT,
DECODE(STATUS, 0, 'STOP', 1, 'RUN', 2, 'RETRY') AS STATUS,
DECODE(NET_ERROR_FLAG, 0, 'OK', 'ERROR') AS NETWORK,

XSN

FROM V$REPSENDER ;


Replication Receiver

|Column Name|Description|
|---|---|
|REP_NAME|the name of replication object|
|REMOTE_IP|the IP address of remote replicated server|
|REMOTE_REP_PORT|the port number of remote replicated server|
|APPLY_XSN|applied XLOG Sequence Number : the final position in a log file from which logs were applied by the replication receiver|



SELECT REP_NAME,

PEER_IP REMOTE_IP,

PEER_PORT REMOTE_REP_PORT,

APPLY_XSN
FROM V$REPRECEIVER ;


Replication gap

|Column Name|Description|
|---|---|
|REP_NAME|the name of replication object|
|REMOTE_IP|the IP address of remote replicated server|
|REMOTE_REP_PORT|the port number of remote replicated server|
|APPLY_XSN|applied XLOG Sequence Number : the final position in a log file from which logs were applied by the replication receiver|



SELECT REP_NAME,

REP_SN,

REP_LAST_SN,

REP_GAP,

READ_FILE_NO,

START_FLAG
FROM  V$REPGAP ;


Replication status






|REP_NAME|the name of replication object|
|---|---|
|REMOTE_IP|the IP address of remote replicated server|
|REP_GAP|the interval between the log record that was most recently written due to a transaction on the local server and the log record that is<br>currently being sent by the replication Sender thread.|
|RESTART_XSN|the XSN from which the Sender thread must begin sending logs when replication is started.|
|SENDER|the sender status|
|RECEIVER|the receiver status|


SELECT A.REPLICATION_NAME REP_NAME,

D.HOST_IP REMOTE_IP,
NVL(TO_CHAR(E.REP_GAP), '-') AS REP_GAP,

A.XSN RESTART_XSN,
DECODE(B.PEER_PORT, NULL, 'OFF', 'ON') AS SENDER,
DECODE(C.PEER_PORT, NULL, 'OFF', 'ON') AS RECEIVER

FROM  SYSTEM_.SYS_REPL_HOSTS_ D,

SYSTEM_.SYS_REPLICATIONS_ A LEFT OUTER JOIN
V$REPSENDER B ON A.REPLICATION_NAME = B.REP_NAME
LEFT OUTER JOIN V$REPRECEIVER C ON A.REPLICATION_NAME = C.REP_NAME LEFT OUTER JOIN
(

SELECT REP_NAME,
MAX(REP_GAP) REP_GAP
FROM  V$REPGAP

GROUP BY REP_NAME
) E ON A.REPLICATION_NAME = E.REP_NAME

WHERE A.REPLICATION_NAME = D.REPLICATION_NAME

ORDER BY REP_NAME ;


Log buffer or file status occupied by an unsent XLOG


This query shows that the logbuffer/logfile status which is occupied by an unsent XLOG


ALTIBASE HDB V4


ALTIBASE V4 does not support this feature.


ALTIBASE HDB V5


SELECT CASE2((BUFFER_MIN_SN < READ_SN), 'REP BUFFER
'||ROUND((BUFFER_MAX_SN-READ_SN)/(BUFFER_MAX_SN-BUFFER_MIN_SN)*100,2)||' % LEFT ', (SELECT
TO_CHAR(CUR_WRITE_LF_NO - READ_FILE_NO) FROM  V$LFG, V$REPGAP)) LOGFILE_FOR_REP
FROM  V$REPLOGBUFFER ;


Replication table list


The list of tables that participate in a replication


|REP_NAME|the name of replication object|
|---|---|
|LOCAL_TABLE|the local table name|
|REMOTE_TABLE|the remote table name|


SELECT REPLICATION_NAME REP_NAME,
LOCAL_USER_NAME||'.'||LOCAL_TABLE_NAME LOCAL_TABLE,
REMOTE_USER_NAME||'.'||REMOTE_TABLE_NAME REMOTE_TABLE

FROM  SYSTEM_.SYS_REPL_ITEMS_

ORDER BY 1, 2 ;


SQL about Sessions


Total number of sessions

Session Information


ALTIBASE HDB 4

ALTIBASE HDB 5

Session information connected as SYSDBA


ALTIBASE HDB 4

ALTIBASE HDB 5


Total number of sessions


This query returns the number of sessions which are currently established


SELECT COUNT(*) TOTAL_SESSION_CNT
FROM  V$SESSION ;


Session Information


This query returns the information about a session

|Column Name|Description|Col3|
|---|---|---|
|SESSSION_ID|the unique identifier of the session||
|USER_NAME|the database user name||
|CLIENT_IP|the client IP address||
|CLIENT_APP_INFO|the type of client application|not supported in ALTIBASE HDB 4|
|CLIENT_PID|the client process idenfier||
|SESSION_STATE|the status of the session||
|AUTOCOMMIT|the autocommit mode||
|LOGIN_TIME|the time when the session is established||
|IDLE_TIME|the time when the session has been idle||
|CURRENT_QUERY|the query that the session has last executed|not supported in ALTIBASE HDB 4|



ALTIBASE HDB 4


SELECT A.ID SESSION_ID,

A.DB_USERNAME USER_NAME,
REPLACE2(REPLACE2(A.COMM_NAME, 'SOCKET-', NULL), '-SERVER', NULL) CLIENT_IP,

A.CLIENT_PID,

A.SESSION_STATE,
DECODE(A.AUTOCOMMIT_FLAG, 1, 'ON', 'OFF') AUTOCOMMIT,
DECODE(A.LOGIN_TIME, 0, '-', TO_CHAR(TO_DATE('1970010109', 'YYYYMMDDHH') + A.LOGIN_TIME /
(24*60*60), 'MM/DD HH:MI:SS')) LOGIN_TIME,
DECODE(A.IDLE_START_TIME, 0, '-', TO_CHAR(TO_DATE('1970010109', 'YYYYMMDDHH') +
A.IDLE_START_TIME / (24*60*60), 'MM/DD HH:MI:SS')) IDLE_TIME
FROM  V$SESSION A ;


ALTIBASE HDB 5


SELECT A.ID SESSION_ID,

A.DB_USERNAME USER_NAME,
REPLACE2(REPLACE2(A.COMM_NAME, 'SOCKET-', NULL), '-SERVER', NULL) CLIENT_IP,

A.CLIENT_APP_INFO,

A.CLIENT_PID,

A.SESSION_STATE,
DECODE(A.AUTOCOMMIT_FLAG, 1, 'ON', 'OFF') AUTOCOMMIT,
DECODE(A.LOGIN_TIME, 0, '-', TO_CHAR(TO_DATE('1970010109', 'YYYYMMDDHH') + A.LOGIN_TIME /
(24*60*60), 'MM/DD HH:MI:SS')) LOGIN_TIME,
DECODE(A.IDLE_START_TIME, 0, '-', TO_CHAR(TO_DATE('1970010109', 'YYYYMMDDHH') +
A.IDLE_START_TIME / (24*60*60), 'MM/DD HH:MI:SS')) IDLE_TIME,
NVL(LTRIM(B.QUERY), 'NONE') CURRENT_QUERY
FROM  V$SESSION A LEFT OUTER JOIN
V$STATEMENT B ON A.CURRENT_STMT_ID = B.ID ;


Session information connected as SYSDBA


This query returns the information about a session which connects as SYSDBA

|Column Name|Description|Col3|
|---|---|---|
|SESSSION_ID|the unique identifier of the session||
|USER_NAME|the database user name||
|CLIENT_IP|the client IP address||
|CLIENT_APP_INFO|the type of client application|not supported in ALTIBASE HDB 4|
|CLIENT_PID|the client process idenfier||
|SESSION_STATE|the status of sthe ession||
|AUTOCOMMIT|the autocommit mode||
|LOGIN_TIME|the time when the session is established||
|IDLE_TIME|the time when the session has been idle||
|CURRENT_QUERY|the query that the session last executed|not supported in ALTIBASE HDB 4|



ALTIBASE HDB 4


SELECT A.ID SESSION_ID,

A.DB_USERNAME USER_NAME,
REPLACE2(REPLACE2(A.COMM_NAME, 'SOCKET-', NULL), '-SERVER', NULL) CLIENT_IP,

A.CLIENT_PID,

A.SESSION_STATE,
DECODE(A.AUTOCOMMIT_FLAG, 1, 'ON', 'OFF') AUTOCOMMIT,
DECODE(A.LOGIN_TIME, 0, '-', TO_CHAR(TO_DATE('1970010109', 'YYYYMMDDHH') + A.LOGIN_TIME /
(24*60*60), 'MM/DD HH:MI:SS')) LOGIN_TIME,
DECODE(A.IDLE_START_TIME, 0, '-', TO_CHAR(TO_DATE('1970010109', 'YYYYMMDDHH') +
A.IDLE_START_TIME / (24*60*60), 'MM/DD HH:MI:SS')) IDLE_TIME
FROM  V$SESSION A

WHERE  A.SYSDBA_FLAG = 1;


ALTIBASE HDB 5


SELECT A.ID SESSION_ID,

A.DB_USERNAME USER_NAME,
REPLACE2(REPLACE2(A.COMM_NAME, 'SOCKET-', NULL), '-SERVER', NULL) CLIENT_IP,

A.CLIENT_APP_INFO,

A.CLIENT_PID,

A.SESSION_STATE,
DECODE(A.AUTOCOMMIT_FLAG, 1, 'ON', 'OFF') AUTOCOMMIT,
DECODE(A.LOGIN_TIME, 0, '-', TO_CHAR(TO_DATE('1970010109', 'YYYYMMDDHH') + A.LOGIN_TIME /
(24*60*60), 'MM/DD HH:MI:SS')) LOGIN_TIME,
DECODE(A.IDLE_START_TIME, 0, '-', TO_CHAR(TO_DATE('1970010109', 'YYYYMMDDHH') +
A.IDLE_START_TIME / (24*60*60), 'MM/DD HH:MI:SS')) IDLE_TIME,
NVL(LTRIM(B.QUERY), 'NONE') CURRENT_QUERY
FROM  V$SESSION A LEFT OUTER JOIN
V$STATEMENT B ON A.CURRENT_STMT_ID = B.ID

WHERE  A.SYSDBA_FLAG = 1;


SQL about Statements


Total number of statements

Statement information

The number of currently running statements
Information about currently running statements
Long running query ( over 10 seconds)
Long running transaction's last statement information (over 1 minute)
Information about a query running a FULL SCAN


Total number of statements


This query returns the number of statements that currently are established


SELECT COUNT(*) STATEMENT_CNT
FROM  V$STATEMENT;


Statement information


This query returns the information about statements sorted in descending order by the execution time

|Column Name|Description|
|---|---|
|SESSSION_ID|the unique identifier of the session|
|STMT_ID|the unique identifier of the statement in the session|
|TX_ID|the transaction identifier if the statement participates in a transaction|
|PREPARE_TIME|the time taken to perform preparing the statement. (microsecond)|
|FETCH_TIME|the time taken to perform a fetch operation (microsecond)|
|EXECUTE_TIME|the time taken to execute the statement (microsecond)|
|TOTAL_TIME|the total elapsed time|
|EXECUTE_FLAG|set 1 if the statement is currently executed|
|LAST_START_TIME|the time when the statement last started|
|QUERY|the query string|



SELECT SESSION_ID,

ID STMT_ID,

TX_ID,
(PARSE_TIME+VALIDATE_TIME+OPTIMIZE_TIME) PREPARE_TIME,

FETCH_TIME,

EXECUTE_TIME,

TOTAL_TIME,

EXECUTE_FLAG,
DECODE(LAST_QUERY_START_TIME, 0, '-', TO_CHAR(TO_DATE('1970010109', 'YYYYMMDDHH') +
LAST_QUERY_START_TIME / (24*60*60), 'MM/DD HH:MI:SS')) LAST_START_TIME,
NVL(LTRIM(QUERY), 'NONE') QUERY
FROM  V$STATEMENT

ORDER BY EXECUTE_TIME DESC ;


The number of currently running statements


This query returns the number of statements that are currently executing


SELECT COUNT(*) AS ACTIVE_STATEMENT_CNT
FROM  V$STATEMENT

WHERE  EXECUTE_FLAG = 1 ;


Information about currently running statements


This query returns the statement information about those that are currently executing


|Column Name|Description|
|---|---|
|SESSSION_ID|the unique identifier of the session|
|STMT_ID|the unique identifier of statement in the session|
|TX_ID|the transaction identifier if the statement participate in a transaction|


|PREPARE_TIME|the time taken to perform preparing the statement. (microsecond)|
|---|---|
|FETCH_TIME|the time taken to perform a fetch operation (microsecond)|
|EXECUTE_TIME|the time taken to execute the statement (microsecond)|
|TOTAL_TIME|the total elapsed time|
|EXECUTE_FLAG|set 1 if the statement is currently executed|
|LAST_START_TIME|the time when the statement last started|
|QUERY|the query string|


SELECT SESSION_ID,

ID STMT_ID,

TX_ID,
(PARSE_TIME+VALIDATE_TIME+OPTIMIZE_TIME) PREPARE_TIME,

FETCH_TIME,

EXECUTE_TIME,

TOTAL_TIME,
DECODE(LAST_QUERY_START_TIME, 0, '-', TO_CHAR(TO_DATE('1970010109', 'YYYYMMDDHH') +
LAST_QUERY_START_TIME / (24*60*60), 'MM/DD HH:MI:SS')) LAST_START_TIME,
NVL(LTRIM(QUERY), 'NONE') QUERY
FROM  V$STATEMENT

WHERE  EXECUTE_FLAG = 1

ORDER BY EXECUTE_TIME DESC ;


Long running query ( over 10 seconds)


This query returns the statement information about queries that are considered long running. (the queries with elapsed time
over 10 seconds)


|Column Name|Description|
|---|---|
|SESSSION_ID|the unique identifier of the session|
|STMT_ID|the unique identifier of statement in the session|
|TX_ID|the transaction identifier if the statement participate in a transaction|
|PREPARE_TIME|the time taken to perform preparing statement. (microsecond)|
|FETCH_TIME|the time taken to perform a fetch operation (microsecond)|
|EXECUTE_TIME|the time taken to execute statement (microsecond)|
|TOTAL_TIME|the total elapsed time|
|EXECUTE_FLAG|set 1 if the statement is currently executed|
|LAST_START_TIME|the time when the statement last started|
|QUERY|the query string|


SELECT SESSION_ID,

ID STMT_ID,

TX_ID,
(PARSE_TIME+VALIDATE_TIME+OPTIMIZE_TIME) PREPARE_TIME,

FETCH_TIME,

EXECUTE_TIME,

TOTAL_TIME,
DECODE(LAST_QUERY_START_TIME, 0, '-', TO_CHAR(TO_DATE('1970010109', 'YYYYMMDDHH') +
LAST_QUERY_START_TIME / (24*60*60), 'MM/DD HH:MI:SS')) LAST_START_TIME,
NVL(LTRIM(QUERY), 'NONE') QUERY
FROM  V$STATEMENT
WHERE  EXECUTE_FLAG = 1 AND EXECUTE_TIME/1000000 > 10

ORDER BY EXECUTE_TIME DESC ;


Long running transaction's last statement information (over 1 minute)


In the case of long running transactions in ALTIBASE HDB, this query shows the information for the last query of a
transaction with an elapsed time over 1 minute

|Column Name|Description|
|---|---|
|SESSSION_ID|the unique identifier of the session|
|CLIENT_IP|the client IP address|
|CLIENT_PID|the client process identifier|
|UTRANS_TIME|the time taken during the transaction. (microsecond)|
|EXECUTE_TIME|the time taken to execute statement (microsecond)|
|TOTAL_TIME|the total elapsed time|
|LAST_START_TIME|the time when the statement last started|
|QUERY|the query string|



SELECT ST.SESSION_ID,

SS.COMM_NAME CLIENT_IP,

SS.CLIENT_PID,
(BASE_TIME - TR.FIRST_UPDATE_TIME) AS UTRANS_TIME,

EXECUTE_TIME,

TOTAL_TIME,
DECODE(LAST_QUERY_START_TIME, 0, '-', TO_CHAR(TO_DATE('1970010109', 'YYYYMMDDHH') +
LAST_QUERY_START_TIME / (24*60*60), 'MM/DD HH:MI:SS')) LAST_START_TIME,
NVL(LTRIM(ST.QUERY), 'NONE') QUERY
FROM V$TRANSACTION TR,
V$STATEMENT ST,
V$SESSIONMGR,
V$SESSION SS

WHERE  TR.ID = ST.TX_ID

AND ST.SESSION_ID = SS.ID

AND TR.FIRST_UPDATE_TIME != 0 -- 0:READ ONLY TRANSACTION
AND (BASE_TIME - TR.FIRST_UPDATE_TIME) > 60

ORDER BY UTRANS_TIME DESC ;


Information about a query running a FULL SCAN


This query shows the information about a query that is running a FULL SCAN. You need to be careful and check the SQL if
there is a FULL SCAN plan node in the statement

|Column Name|Description|
|---|---|
|SESSSION_ID|the unique identifier of the session|
|CLIENT_IP|the client IP address|
|CLIENT_PID|the client process identifier|
|LAST_START_TIME|the time when the statement last started|
|PREPARE_TIME|the time taken to perform preparing statement. (microsecond)|
|FETCH_TIME|the time taken to perform a fetch operation (microsecond)|
|EXECUTE_TIME|the time taken to execute statement (microsecond)|
|TOTAL_TIME|the total elapsed time|
|QUERY|the query string|



SELECT SESSION_ID,

S.COMM_NAME CLIENT_IP,

S.CLIENT_PID,
DECODE(LAST_QUERY_START_TIME, 0, '-', TO_CHAR(TO_DATE('1970010109', 'YYYYMMDDHH') +
LAST_QUERY_START_TIME / (24*60*60), 'MM/DD HH:MI:SS')) LAST_START_TIME,
(PARSE_TIME+VALIDATE_TIME+OPTIMIZE_TIME) PREPARE_TIME,

FETCH_TIME,

EXECUTE_TIME,

TOTAL_TIME,
NVL(LTRIM(QUERY), 'NONE') QUERY
FROM  V$STATEMENT T,
V$SESSION S

WHERE  S.ID = T.SESSION_ID
AND (MEM_CURSOR_FULL_SCAN > 0 OR DISK_CURSOR_FULL_SCAN > 0)
AND UPPER(QUERY) NOT LIKE '%INSERT%'

ORDER BY EXECUTE_TIME DESC ;


SQL about Tablespaces


The usage of a Memory tablespace

ALTIBASE HDB V4

ALTIBASE HDB V5

Total memory tablespace usage
Disk Tablespace Usage

ALTIBASE HDB V4

ALTIBASE HDB V5

The datafile information
I/O statistics of datafiles

ALTIBASE HDB V4

ALTIBASE HDB V5


The usage of a Memory tablespace


This query returns the information about a memory tablespace


|Columns|Description|
|---|---|
|TBS_ID|the unique identifier of the tablespace|


|TBS_TYPE|the type of the tablespace|
|---|---|
|TBS_NAME|the name of the tablespace|
|MAX(M)|the max size of the tablespace (Megabyte)|
|TOTAL(M)|the total size of the tablespace (Megabyte)|
|ALLOC(M)|the allocated size of  the tablespace (Megabyte)|
|USED(M)|actually used size of the tablespace (Megabyte)|
|USAGE(%)|the tablespace usages. (USED(M) / MAX(M)) * 100. if MAX(M) is unlimited, it assumes that MAX(M) is MEM_MAX_DB_SIZE in<br>altibase.properties.|
|STATE|the state of the tablespace|
|AUTOEXTEND|whether the tablespace can be extended automatically|


ALTIBASE HDB V4


ALTIBASE HDB V4 does not support User Memory Tablespaces. There's only one memory tablespace including system
dictionary tablespace.


ALTIBASE HDB V5


SELECT ID TBS_ID,
DECODE(TYPE, 0, 'MEMORY_DICTIONARY', 1, 'MEMORY_SYS_DATA', 2, 'MEMORY_USER_DATA', 8,
'VOLATILE_USER_DATA') TBS_TYPE,

NAME TBS_NAME,
DECODE(MAXSIZE, 140737488322560, 'UNDEFINED', MAXSIZE) 'MAX(M)',
ROUND(ALLOCATED_PAGE_COUNT * PAGE_SIZE / 1024 / 1024, 2) 'TOTAL(M)',

ROUND(NVL(M.ALLOC_PAGE_COUNT-M.FREE_PAGE_COUNT,TOTAL_PAGE_COUNT)*PAGE_SIZE/1024/1024,
2) 'ALLOC(M)',
MT.USED 'USED(M)',
DECODE(MAXSIZE, 140737488322560,
ROUND((M.ALLOC_PAGE_COUNT-M.FREE_PAGE_COUNT)*PAGE_SIZE/ MEM_MAX_DB_SIZE*100,2),
ROUND((M.ALLOC_PAGE_COUNT-M.FREE_PAGE_COUNT)*PAGE_SIZE/MAXSIZE*100,2)) 'USAGE(%)',
DECODE(STATE,1,'OFFLINE',2,'ONLINE',5,'OFFLINE BACKUP',6,'ONLINE BACKUP',128,'DROPPED',
'DISCARDED') STATE,
DECODE(AUTOEXTEND_MODE,1,'ON','OFF') 'AUTOEXTEND'
FROM  V$DATABASE D,
V$TABLESPACES T,
V$MEM_TABLESPACES M,
(

SELECT TABLESPACE_ID,
ROUND(SUM((FIXED_USED_MEM + VAR_USED_MEM))/(1024*1024),3) USED
FROM  V$MEMTBL_INFO

GROUP BY TABLESPACE_ID
) MT

WHERE T.ID = M.SPACE_ID AND ID = MT.TABLESPACE_ID ;


Total memory tablespace usage


This query returns the total memory tablespace usage


Columns Description


|MAX(M)|the max size of the tablespace (Megabyte)|
|---|---|
|TOTAL(M)|the total size of the tablespace (Megabyte)|
|ALLOC(M)|allocated size of the tablespace (Megabyte)|
|USED(M)|actually used size of the tablespace (Megabyte)|
|USAGE(%)|the tablespace usages. (USED(M) / MAX(M)) * 100. if MAX(M) is unlimited, it assumes that MAX(M) is MEM_MAX_DB_SIZE in<br>altibase.properties.|


SELECT MEM_MAX_DB_SIZE/1024/1024 'MAX(M)',
ROUND(MEM_ALLOC_PAGE_COUNT*32/1024, 2) 'TOTAL(M)',
TRUNC((MEM_ALLOC_PAGE_COUNT-MEM_FREE_PAGE_COUNT)*32/1024, 2) 'ALLOC(M)',
(SELECT ROUND(SUM((FIXED_USED_MEM + VAR_USED_MEM))/(1024*1024),3) FROM V$MEMTBL_INFO)
'USED(M)',
TRUNC(((MEM_ALLOC_PAGE_COUNT-MEM_FREE_PAGE_COUNT)*32*1024)/MEM_MAX_DB_SIZE, 4)*100
'USAGE(%)'
FROM V$DATABASE ;


Disk Tablespace Usage


This query returns the disk tablespace usage information

|Columns|Description|
|---|---|
|TBS_ID|the unique identifier of the tablespace|
|TBS_TYPE|the type of the tablespace|
|TBS_NAME|the name of  the tablespace|
|MAX(M)|the max size of the tablespace (Megabyte)|
|TOTAL(M)|the total size of the tablespace (Megabyte)|
|ALLOC(M)|allocated size of the tablespace (Megabyte)|
|AUTOEXTEND|whether the tablespace can be extended automatically|



ALTIBASE HDB V4


SELECT ID TBS_ID,
DECODE(TYPE, 1, 'DISK_SYS_DATA', 2, 'DISK_USER_DATA', 3, 'DISK_SYS_TEMP', 4,
'DISK_USER_TEMP', 5, 'DISK_UNDO') TBS_TYPE,

NAME TBS_NAME,
ROUND(D.MAX * PAGE_SIZE / 1024 /1024, 2) 'MAX(M)',
ROUND(TOTAL_PAGE_COUNT * PAGE_SIZE / 1024 / 1024, 2) 'TOTAL(M)',
ROUND(ALLOCATED_PAGE_COUNT * PAGE_SIZE / 1024 / 1024,2) 'ALLOC(M)',
ROUND(ALLOCATED_PAGE_COUNT / D.MAX * 100, 2) 'USAGE(%)',

D.AUTOEXTEND

FROM  V$TABLESPACES T,
(

SELECT SPACEID,
SUM(DECODE(MAXSIZE, 0, CURRSIZE, MAXSIZE)) AS MAX,
DECODE(MAX(AUTOEXTEND),1,'ON','OFF') 'AUTOEXTEND'
FROM V$DATAFILES

GROUP BY SPACEID
) D

WHERE T.ID = D.SPACEID ;


ALTIBASE HDB V5


SELECT ID TBS_ID,
DECODE(TYPE, 3, 'DISK_SYS_DATA', 4, 'DISK_USER_DATA', 5, 'DISK_SYS_TEMP', 6,
'DISK_USER_TEMP', 7, 'DISK_UNDO') TBS_TYPE,

NAME TBS_NAME,
ROUND(D.MAX * PAGE_SIZE / 1024 /1024, 2) 'MAX(M)',
ROUND(TOTAL_PAGE_COUNT * PAGE_SIZE / 1024 / 1024, 2) 'TOTAL(M)',
DECODE(TYPE, 7, ROUND((SELECT (SUM(TOTAL_EXTENT_COUNT*PAGE_COUNT_IN_EXTENT) *
PAGE_SIZE)/1024/1024 FROM V$UDSEGS)+(SELECT
(SUM(TOTAL_EXTENT_COUNT*PAGE_COUNT_IN_EXTENT) * PAGE_SIZE)/1024/1024 FROM V$TSSEGS),2),
ROUND(ALLOCATED_PAGE_COUNT * PAGE_SIZE / 1024 / 1024,2)) 'ALLOC(M)',
DECODE(TYPE, 7, ROUND(((SELECT SUM(TOTAL_EXTENT_COUNT*PAGE_COUNT_IN_EXTENT) FROM
V$UDSEGS)+(SELECT SUM(TOTAL_EXTENT_COUNT*PAGE_COUNT_IN_EXTENT) FROM V$TSSEGS)) / D.MAX*
100, 2), ROUND(ALLOCATED_PAGE_COUNT / D.MAX * 100, 2)) 'USAGE(%)',
DECODE(STATE,1,'OFFLINE',2,'ONLINE',5,'OFFLINE BACKUP',6,'ONLINE BACKUP',128,'DROPPED',
'DISCARDED') STATE,

D.AUTOEXTEND

FROM  V$TABLESPACES T,
(

SELECT SPACEID,
SUM(DECODE(MAXSIZE, 0, CURRSIZE, MAXSIZE)) AS MAX,
DECODE(MAX(AUTOEXTEND),1,'ON','OFF') 'AUTOEXTEND'
FROM V$DATAFILES

GROUP BY SPACEID
) D

WHERE T.ID = D.SPACEID ;


The datafile information


This query returns the information about data files containing tablespaces


|Columns|Description|
|---|---|
|TBS_NAME|the name of the tablespace|
|FILE#|the file number of datafiles containing the tablespace. It starts with 0.|
|DATAFILE_NAME|the name of the datafile|
|ALLOC(M)|allocated size of the datafile (Megabyte)|
|MAX(M)|the max size of the datafile (Megabyte)|
|AUTOEXTEND|can be extended automatically|


SELECT B.NAME TBS_NAME,
A.ID 'FILE#',

A.NAME DATAFILE_NAME,
CURRSIZE*8/1024 'ALLOC(M)',
ROUND(CASE2(A.MAXSIZE=0, CURRSIZE, A.MAXSIZE)*8/1024) 'MAX(M)',
DECODE(AUTOEXTEND, 0, 'OFF', 'ON') 'AUTOEXTEND'
FROM  V$DATAFILES A,
V$TABLESPACES B

WHERE  B.ID = A.SPACEID

ORDER BY B.NAME, A.ID ;


I/O statistics of datafiles


This query returns I/O statistics for datafiles


ALTIBASE HDB V4


ALTIBASE HDB V4 does not support V$FILESTAT performance view to retrieve the I/O statistics of datafiles.


ALTIBASE HDB V5


SELECT NAME TBS_NAME,

A.PHYRDS PHY_READ,

A.PHYWRTS PHY_WRITE,

A.PHYRDS+A.PHYWRTS PHY_TOTAL,
TRUNC(A.PHYRDS/READ_SUM*100,2) 'READ(%)',
TRUNC(A.PHYWRTS/WRITE_SUM*100,2) 'WRITE(%)',
TRUNC( (A.PHYRDS+A.PHYWRTS) / (READ_SUM+WRITE_SUM) * 100, 2) 'TOTAL(%)',

A.AVGIOTIM AVG_IO_TIME
FROM  V$FILESTAT A,
V$DATAFILES B,
(
SELECT SUM(PHYRDS) READ_SUM,
SUM(PHYWRTS) WRITE_SUM
FROM V$FILESTAT
) C

WHERE A.SPACEID = B.SPACEID

AND A.FILEID = B.ID

AND READ_SUM > 0

AND WRITE_SUM > 0

ORDER BY A.PHYRDS+A.PHYWRTS DESC, ROWNUM DESC ;

## ALTIBASE HDB Architecture


Technical information about ALTIBASE HDB Architecture.

### ALTIBASE HDB Architecture Overview


### How a query is executed in ALTIBASE HDB

There are four steps when ALTIBASE HDB executes a query. These steps are as follows:


Parsing


Parser checks the syntax of SQL text. If no errors are detected in the SQL, Parser generates "Parse Tree" which is used in Validator.
Parser does not look up any information in the system tables, and does not access the database.


Validating


Validator accesses various system tables in the database to verify that all database objects referenced by the SQL exist, such as tables,
columns, views, types, PSMs, etc. If there are no errors, Validator generates "Checked Parse Tree".


Optimizing


After checking validity of the SQL, Optimizer tries to find out the best way to execute the given "Checked Parse Tree", and then it
generates "Plan Tree". There are many sophisticated algorithms and strategies in the ALTIBASE HDB optimization process. If you'd like to
know more about the optimization in ALTIBASE HDB, you can refer to the "SQL Tuning" section in Administrator's Manual.


Executing


The last phase executes the query. Executor executes the SQL using the given Plan Tree.

### Transaction Durability in ALTIBASE HDB


Transaction


A database transaction is a logical unit of work that comprises one or more SQL statements. A transaction begins with the first execution
of an SQL statement by a user, and ends when it is committed or rolled back, either explicitly with a COMMIT or ROLLBACK statement or
implicitly when a DDL statement is issued.


ACID


To maintain database integrity, a properly executed transaction must exhibit the four ACID properties: Atomicity, Consistency, Isolation,
and Durability.


- Atomicity - Either all of the statements that constitute a transaction are completely executed, or none of them are. That is, the
transaction cannot be partially successful.


- Consistency - A properly executed transaction does not break the consistency of the database.


- Isolation - When multiple transactions are underway at the same time, none of the transactions have access to the results of the other
transactions.


- Durability - Once a transaction has been committed, the resultant changes are not lost regardless of the circumstances, such as
system failure.


ALTIBASE HDB guarantees reliable transactional processing by implementing a database server that satisfies all ACID requirements.


Durability


Durability means that after a transaction has been committed, the committed transaction must be guaranteed, even if a database failure
occurs before the changed data are physically written to a disk.


ALTIBASE HDB provides durability with a combination of checkpointing and transaction logging.


WAL Protocol


ALTIBASE HDB adheres to WAL (write-ahead logging) protocol. Based on WAL protocol, before overwriting an object with "uncommitted"
updates, ALTIBASE HDB writes the log records related to such updates to disk storage for UNDO operations. And similarly, before
committing an update to a database object, it writes the log records related to such an update to the log on disk storage for REDO
operations.


Durability & Performance


In ALTIBASE HDB transaction durability has a significant influence on the processing performance. Especially on the memory-based side
of the database which can potentially exhibit performance up to 20 times faster than the disk-based side of the database, guaranteeing
transaction durability has a much bigger impact on performance. This is due the fact that based on the WAL protocol, in order for a
ALTIBASE HDB to provide complete transaction durability, it has to write logs for all database updates to a log file on disk therefore
introducing additional disk I/O activity which can degrade the performance.


Durability Levels Overview


Users need to consider a trade-off between complete transaction durability and transaction processing performance. ALTIBASE HDB
provides multiple levels of durability controls, from most relaxed to most strict, to enable users to have a balance between durability and
performance. Each of these levels in ALTIBASE HDB guarantees durability to a different extent and realizes different performance

characteristics. Relaxed durability yields the best performance; where as strict durability eliminates loss of transactions.


Relaxed durability (Level 2): On system or database crash, recovery point is the last checkpoint.


Enhanced durability (Level 3): On database crash no data loss, recovery point is the last point where OS syncs kernel buffer to disk.


Strict durability (Level 5): No data loss with system or database crash, each transaction committed only when written to disk.


In addition to these durability levels listed above, with ALTIBASE HDB, users have the option to use Volatile tablespaces which omit
logging process completely.


Managing Durability Levels


ALTIBASE HDB provides users with two properties to manage durability level settings. Those properties are:
COMMIT_WRITE_WAIT_MODE and LOG_BUFFER_TYPE.


COMMIT_WRITE_WAIT_MODE specifies whether a transaction waits until an update log has been written to a log file on disk. This
property can be specified for the entire system (ALTER SYSTEM) or for individual sessions (ALTER SESSION).

|Property|Value|Notes|
|---|---|---|
|COMMIT_WRITE_WAIT_MODE|0|Asynchronous method, a transaction does wait until an update log has been written to a log file on disk. This<br>is the default setting for ALTIBASE HDB. When using this setting, a service thread writes transaction logs in<br>the log buffer, and returns the result to a user without waiting until the logs files have been written to disk.<br>This setting is suitable for performance-oriented environments since it avoids I/O bottlenecks. With the<br>asynchronous mode, there is still some protection against data loss due to database crashes if<br>LOG_BUFFER_TYPE is set for 1 (see below).|
|COMMIT_WRITE_WAIT_MODE|1|Synchronous method, a transaction has to wait until related logs have been written to a log file on disk before<br>returning commit. This mode guarantees transaction durability, and it is suitable for mission critical<br>environments in which transaction durability is more important than performance.|



LOG_BUFFER_TYPE specifies the type of log buffer that is used when update logs are written to a log file. This property can't be
changed while the system is running.

|Property|Value|Notes|
|---|---|---|
|LOG_BUFFER_TYPE|0|OS Kernel log buffer. This is the default setting for ALTIBASE HDB. When using this setting, ALTIBASE HDB uses<br>memory-mapped files for disk I/O related to transaction logs. With memory mapped file IO, the file to be read is<br>mapped to the virtual memory of the underlying OS. This mode provides improved durability in the case that the<br>database crashes but not the OS, since changes to memory-mapped files are maintained in the OS kernel memory. In<br>this mode, log flushing is handled by the operating system leveraging msync() function.|
|LOG_BUFFER_TYPE|1|Process memory log buffer. When using this setting, transaction logs are written to a memory-resident log buffer. In<br>this mode, log flushing is handled by the database process using fsync() function. This method is slightly faster than<br>memory-mapped method, but it compromises from durability in the case of a database crash.|



Relaxed Durability (Level 2)


When using ALTIBASE HDB Relaxed durability setting, on a system or a database crash, recovery point is the last checkpoint. This level i
s suitable for use in business environments in which database durability is not critical, but fast processing of transactions is required. Bu

sinesses that can tolerate a certain level of data loss may want to take advantage of this level for high performance transactions.

|Property|Value|
|---|---|
|COMMIT_WRITE_WAIT_MODE|0|
|LOG_BUFFER_TYPE|1|



Enhanced Durability (Level 3)


When using ALTIBASE HDB Enhanced durability setting, on database crash there is no data loss, and the recovery point is the last point

where OS syncs kernel buffer to disk. In other words, even if the database crashes, durability is still ensured by the OS. This level is
suitable for environments characterized by low rates of failures such as OS crashes, hardware faults and power outages. Businesses that

can tolerate a certain level of data loss may want to take advantage of this level. This is the default setting for ALTIBASE HDB.


|Property|Value|
|---|---|
|COMMIT_WRITE_WAIT_MODE|0|
|||


|Col1|Col2|
|---|---|
|LOG_BUFFER_TYPE|0|


Strict Durability (Level 5)


When using ALTIBASE HDB Strict durability setting, since each transaction committed only when written to disk, there will be no data loss
with either system or database crash, This level is suitable for use in business environments in which data durability is more important
than faster performance. Businesses that cannot tolerate any kinds of data loss should use this level.

|Property|Value|
|---|---|
|COMMIT_WRITE_WAIT_MODE|1|
|LOG_BUFFER_TYPE|1|


## ALTIBASE HDB Developer


Topics of interest to ALTIBASE HDB Application Developers

## ALTIBASE HDB General Information


High-level general information about ALTIBASE HDB

## ALTIBASE HDB Performance Tuning


ALTIBASE HDB Performance tuning tips and tricks.

### Performance diagnostics for ALTIBASE HDB


About this document.

1. Application side diagnostics
2. Database side diagnostics
3. System side diagnostics


About this document.

|Purpose|This document is for diagnosis when you meet the performance problem in ALTIBASE.|
|---|---|
|applied to|4.3.9 or later|
|Prerequisite|Altibase admin|



1. Application side diagnostics


2. Database side diagnostics


3. System side diagnostics


1. Application side diagnostics


Before testing the queries in this document, please make sure to set TIMED_STATISTICS property value to "1" as shown below.


ALTER SYSTEM SET TIMED_STATISTICS = 1;


Most of performance problems are caused by user application logic. Therefore, when facing performance problems, checking the
application is always a good staring point.


The following are the most frequently observed cases from applications side.


Preparing statement for every execution ( or using dynamic SQL)


When you prepare a statement, ALTIBASE HDB performs parsing, validating and optimizing for the given statement. (See also How a

query is executed in ALTIBASE HDB) The statement prepared earlier can be reused, so the overhead of preparing statement can be
eliminated. In the same context, Dynamic SQL can cause performance problems.


Even if you may not have access to the application source code, you can find out how many times an application prepares statements.
ALTIBASE HDB provides v$sysstat / v$sesstat performance view tables which contain the information of statements.


The number of prepare operations occurred


SELECT  TO_CHAR(SYSDATE, 'YYYYMMDD HH:MI:SS') CUR_TIME,
RPAD(NAME, 50) NAME,

VALUE

FROM  V$SYSSTAT
WHERE  SEQNUM IN (27, 29);


Normally, "execute success count" is much bigger than "prepare success count". If not, you need to check your application.


You can get the various information from V$SYSSTAT or V$SESSTAT. Please refer the V$STATNAME explanation in the
Administrators Manual to get more information in detail.


A bad SQL that consumes a lot resources


A SQL that performs full table or index scans can cause serious performance problems. You can locate "bad SQL statements" in your
ALTIBASE HDB environment by using the following queries.


The longest "Top 5 queries" currently running in ALTIBASE HDB server


SELECT EXECUTE_TIME/ 1000000 EXEC_SECOND,
RPAD(QUERY, 500) QUERY
FROM  V$STATEMENT

WHERE  EXECUTE_FLAG = 1

ORDER BY 1 DESC

LIMIT 5;


A query that has a "FULL SCAN" plan node.


SELECT RPAD(QUERY,200),
COUNT(*) CNT
FROM  V$STATEMENT
WHERE (SESSION_ID, ID) IN
(

SELECT SID, STMT_ID
FROM V$PLANTEXT

WHERE TEXT LIKE '%FULL%'
)

GROUP BY QUERY


Connecting and disconnecting for every DBMS request


The cost of creating a connection is expensive for both ALTIBASE HDB and applications. It can cause serious performance degradation.
You can find out how many times an application makes connections by using the following query.


The cumulative connection count after a server start-up.


SELECT  TO_CHAR(SYSDATE, 'YYYYMMDD HH:MI:SS') CUR_TIME,
RPAD(NAME, 50) NAME,

VALUE

FROM  V$SYSSTAT

WHERE  SEQNUM = 1;


Note that this value is a snapshot of the current cumulative connection count. In order to get meaningful values, you have to get
the results for several times in short period of time.


Consider IPC connection if a client and a database both reside on the same machine


ALTIBASE HDB provides three communication protocols.






|Connection Type|Description|
|---|---|
|TCP / IP (CON_TYPE=1)|Default connection type in ALTIBASE HDB. ALTIBASE HDB uses TCP/IP socket to communicate with the client. The<br>client located on the different machine can connect to ALTIBASE HDB by using this connection.|
|Unix Domain<br>(CON_TYPE=2)|Unix Domain uses "pipe" provided by Unix OS. It is faster than TCP/IP but application and ALTIBASE HDB have to be<br>running on the same machine.|
|IPC (Inter-Process<br>Communication)<br>(CON_TYPE=3)|The fastest connection type between the client and ALTIBASE HDB. Like Unix domain, application and ALTIBASE HDB<br>have to be running on the same machine.|



Note that you must set the value of IPC_CHANNEL_COUNT in altibase.properties bigger than 0 before using IPC connection.
IPC_CHANNEL_COUNT is the maximum concurrent connection counts for IPC connection type. Default value is 0. (IPC
connection is disabled.)


In order to increase the performance of ALTIBASE HDB, you may want to consider using "IPC" connection type whenever possible. If
you want to determine what connection type an application uses, you can use the following query.


The session count categorized by the connection type


SELECT SUBSTR(COMM_NAME, 1,4) CON_TYPE,
COUNT(*) CNT
FROM  V$SESSION
GROUP BY SUBSTR(COMM_NAME, 1,4) ;


2. Database side diagnostics


Once all the considerations on "Application side diagnostics" are applied, the next step is to look into the settings of ALTIBASE HDB.


Log file I/O contention


ALTIBASE HDB makes use of WAL (Write Ahead Logging) protocol which requires that all modifications are written to a transaction log
(logfile) before they are applied to DBMS. If you want to enhance the performance of the application, you will need to check the state of
log files.


There are two threads related to the state of log files. The first one is "logfile prepare thread" which allocates new memory in order to
write a redo log. The second one is "log write thread" which applies all modifications into DBMS.
Once the speed of "log write thread" exceeds "logfile prepare thread", "log write thread" has to wait for "logfile prepare thread" to prepare
log files. This symptom is called as "logfile IO contention".
ALTIBASE HDB provides a parameter called "PREPARE_LOG_FILE_COUNT"(default value is 5) to address this issue. Increasing this value
sufficiently can prevent the problem in advance.
You can monitor the state of logfile as follows:


select LF_OPEN_COUNT, LF_PREPARE_COUNT, LF_PREPARE_WAIT_COUNT from v$lfg;


If the value of LF_PREPARE_WAIT_COUNT is greater than 1 from the result of the above query, you need to increase the value. The value
can be estimated as following.
Double the parameter value of "PREPARE_LOG_FILE_COUNT", then see the value of LF_PREPARE_WAIT_COUNT is still larger than 1.
If so, double the value again and see the result until the value reaches 100.
If LF_PREPARE_WAIT_COUNT is still over 1, it means that the performance of disk is slow. Therefore, you have to consider changing the
disk to resolve the problem.


Caution : ALTIBASE HDB allocates memory for log files based on the value of PREPARE_LOG_FILE_COUNT. Therefore, larger
value means larger memory usage.


Checkpoint I/O


The fuzzy and ping-pong based implementation of ALTIBASE HDB checkpointing does not impact transaction response times. However,
if the log files and data files are physically on the same file system there may be some read and write I/O contention.


In another case, If buffered I/O mechanisms of the Operating System (OS) is used, most of I/O the traffic resides in the OS buffer. Once
OS flushes all data onto disk area, the performance again may fluctuate at that time. If buffered I/O of the OS causes performance
degradations, you may want to consider changing it to DIRECT I/O. Please, refer to the OS manual how to change this setting.


The best approach to deal with such I/O contentions is to separate the physical location of the log files and datafiles.


ALTIBASE HDB provides the following parameters to scatter I/O writes.


CHECKPOINT_BULK_WRITE_PAGE_COUNT 0 => 100
CHECKPOINT_BULK_WRITE_SLEEP_SEC 0 => 0
CHECKPOINT_BULK_WRITE_SLEEP_USEC 0 => 5000
CHECKPOINT_BULK_SYNC_PAGE_COUNT 3200 => 100


Caution : Checkpoint duration with tuned parameters as above is longer than when using the default parameters. Therefore in
this case, you have to have more disk space available for log files.


MULTIPLEXING_THREAD_COUNT setting


We highly recommend that the number of MULTIPLEXING_THREAD_COUNT be twice or four times bigger than the number of CPU cores.
The best-suited value must be determined by testing with the application.


iSQL> select rpad(type, 30), count(*) from v$service_thread group by type

2 union all
3 select '# of IPC ', count(*) from v$session where comm_name like '%IPC%';
RPAD(TYPE, 30)         COUNT

-------------------------------------------------------
DEDICATED            1

SHARED             16

# of IPC            1


It is best to have the number of "DEDICATED" thread same as "# of IPC"
Having "DEDICATED" value greater than # of IPC means a long running query may exist, so you will need to locate and tune it.


iSQL> select rpad(type, 30), count(*) from v$service_thread group by type

2 union all
3 select rpad(name, 30), value1 from v$property where name like 'MULTIPLEXING%_THREAD_COUNT';
RPAD(TYPE, 30)         COUNT

----------------------------------------------
SOCKET             16

MULTIPLEXING_THREAD_COUNT    16

MULTIPLEXING_MAX_THREAD_COUNT  1024


The number of "SOCKET" thread might grow up to the value of MULTIPLEXING_MAX_THREAD_COUNT(default 1024). If the value of
"SOCKET" is bigger than the value of MULTIPLEXING_THREAD_COUNT, again there may exist some long running queries.


A long running query slows down the performance and takes much CPU usage in the system.


Memory Ager (Garbage Collector - GC)


The Memory Ager (GC) reclaims garbage or memory occupied by objects that are no longer in use by the application - the committed
old versions by transactions. The GC works independently formed by threads and is consisted with MEM_LOGICAL_AGER and
MEM_DELTHR. The former mostly clears unused "index pages" while the latter does unused "data pages", respectively. If GC can not
process the work fast enough, it affects the performance of transactions. The reason is that transactions may look up not only the
current version of record and index pages, but also the old versions of them.


ALTIBASE HDB provides the performance view tables to monitor the state of GC.


select add_oid_cnt, gc_oid_cnt, add_oid_cnt - gc_oid_cnt GCGAP from v$memgc;


If you get increasing values of GCGAP while executing the query above, there may exist some long running queries. You can locate such
queries with the following SQL.


select c.session_id, comm_name, client_pid, execute_flag, total_time, execute_time, fetch_time,
rpad(query,500)
from (select * from v$memgc limit 1) a, v$transaction b, v$statement c, v$session d
where (a.MINMEMSCNINTXS = b.MEMORY_VIEW_SCN or a.MINMEMSCNINTXS =
b.MIN_MEMORY_LOB_VIEW_SCN)

and b.id = c.tx_id

and c.session_id = d.id;


If there are no symptoms related to the cases above, ALTIBASE HDB provides the parameters below to take control.


AGER_WAIT_MINIMUM=200000 (microseconds)
AGER_WAIT_MAXIMUM=1000000 (microseconds)


To enhance GC's performance, you need to lower the parameter values. Then the next wake-up time of GC, it will be faster.


Caution : The faster wake-up time of GC is, the more CPU cycle is consumed by GC which may result in slower transaction
response times due to high CPU consumption.


BUFFER_AREA_SIZE


The Buffer Cache uses the LRU (least recently used) algorithm to keep track of what was used and when. The LRU allows HDB to
determine which buffers have not been accessed for a long time so that they can be replaced first.In ALTIBASE HDB, the LRU list is
separated into hot and cold zones, and can thus be called a “hot-cold LRU list”. Buffers that are accessed frequently are placed in the
hot zone, whereas those that are not accessed frequently are placed in the cold zone. When a buffer needs to be replaced, only the cold
zone is searched, meaning that hot buffers are not considered as replacement candidates.
When a page is first loaded into a buffer, it is inserted at the mid-point (LRU cold first) of the LRU list. When allocating a buffer to the
new data page, if there are no free buffers in the prepare list, the end (LRU cold last) of this list is searched first, and a cold buffer is
then replaced. The buffer that is replaced is called a “victim”. Buffers that are read frequently are moved to the “LRU hot first” position in
the hot zone. Meanwhile, dirty buffers, that is, buffers containing pages that have been updated but haven't been flushed to disk, are
moved to the flush list. Additionally, clean buffers, that is, buffers containing pages that haven't been updated, are designated as
replacement buffers as long as they are not in the hot zone. The relative size of the hot zone can be set using the HOT_LIST_PCT
property. The default is 50, which means that half of the LRU list is used as the hot zone. Users need to analyze access patterns in their
application since HOT_LIST_PCT property values can influence the performance.


Example SQL how to alter HOT_LIST_PCT value


alter system set HOT_LIST_PCT = 60;


SQL PLAN CACHE


The Plan Cache is a piece of memory that ALTIBASE HDB uses in order to store SQL plans. This feature has been introduced to HDB
because the Prepare-Phase(Parse-Validate-Optimize) is expensive in terms of CPU cycles. It's functionality can be compared to the
Library Cache of Oracle.


ALTIBASE HDB provide performance-views to find out about the state of the SQL plan cache.


V$SQL_PLAN_CACHE
V$SQL_PLAN_CACHE_PCO
V$SQL_PLAN_CACHE_SQLTEXT


Following parameters are used to tune the performance of the SQL plan cache.


|name|value|
|---|---|
|SQL_PLAN_CACHE_SIZE|67108864|
|SQL_PLAN_CACHE_BUCKET_CNT|127|
|SQL_PLAN_CACHE_HOT_REGION_LRU_RATIO|50|


Check the hit_ratio of the plan cache in the time interval.


select CACHE_HIT_COUNT, CACHE_MISS_COUNT from v$sql_plan_cache;



1.


2.


3.


Others



If CACHE_HIT_COUNT is much bigger than CACHE_MISS_COUNT, that would be a desirable state.
We highly recommend you that the ratio of "CACHE_MISS_COUNT / CACHE_HIT_COUNT" be normally less than 1/10000. Please
also note that this figure is not applicable to all cases.


Recommended Action :

a. extend the size of PLAN_CACHE
b. convert the source "direct-execute" to "prepare-execute"
c. configure the SQL_PLAN_CACHE_HOT_REGION_LRU_RATIO.


Check the number of statements and SQL_PLAN_CACHE_BUCKET_CNT
The plan cache is managed by a hash-table. SQL_PLAN_CACHE_BUCKET_CNT property inidicates the number of hash table
buckets in a SQL plan cache. To reduce the scan time, we highly recommend that SQL_PLAN_CACHE_BUCKET_CNT would be
1/4 of total number of statements based on our experience.


select count(*) as total_number_of_statement from v$statement;


Set the SQL_PLAN_CACHE_BUCKET_CNT = total_number_of_statement/4
SQL_PLAN_CACHE_PREPARED_EXECUTION_CONTEXT_CNT
This property indicates the number of execution contexts that are initially created when plans are generated. The initial number of
execution contexts is specified before plans are created, however, this only determines the initial number. The number of
execution contexts increases or decreases automatically
as required during runtime. Increasing this value can help realize better performance when only one plan is executed at a time,
however, in other cases the plan size is merely increased, without realizing improved performance.To avoid the concurrent
contention, we recommend that SQL_PLAN_CACHE_PREPARED_EXECUTION_CONTEXT_CNT would be similar as the number of
CPU's.



If all considerations above are applied, and still observing performance issues, the following procedure will be helpful to figure out what
the problem is.


pstack $ALTIBASE_PID


We highly recommend you to consecutively gather 3 times of pstack with sleep interval (for example: 10 seconds).


select * from v$mutex order by miss_count desc limit 10;


select event, wait_time from v$statement where wait_time > 1;


select event, TOTAL_WAITS, time_waited from v$system_event order by 2,3;


3. System side diagnostics


Kernel / Environment Variables (System Resources)


It would be advisable to check the OS kernel and environment variables to make sure that all correct settings are applied as explained in
the Installation manual and in the pre_install.sh script prior to checking other aspects of the system.


Disk I/O Performance


ALTIBASE HDB's performance rely on the performance of the hardware. Therefore, it is neccessary to check the performance of Disk
I/O.


You can use following command to see the performance of a disk (this will create a 1GB file full of 0’s.)


time dd if=/dev/zero of=MyTestFile bs=1M count=1024


It simply displays the time it takes to copy a file.


Direct I/O Use


ALTIBASE HDB provides two disk I/O methods related to database files:

- Direct I/O

- Buffered I/O


One advantage of Direct I/O is that it reduces CPU resource consumption during occurance of Disk I/O. On the other hand, since the
Buffered I/O uses techniques of read-ahead and asynchronous write, it may not access disk every time when an disk I/O is required. It
means that the Buffered I/O is faster than the Direct I/O. However the Buffered I/O consumes a higher level of CPU resources when
compared to the Direct I/O.


There are three properties that users have to look at to use the Direct I/O in ALTIBASE HDB


LOG_IO_TYPE
DATABASE_IO_TYPE
DIRECT_IO_ENABLED


To use Direct I/O, you have to mount disk with following options.

|OS|File System|mount option|
|---|---|---|
|Solaris|UFS|none|
|HP-UX|Veritas VxFS|mount with convosync=direct|
|Solaris|Veritas VxFS|mount with convosync=direct|
|AIX|Veritas VxFS|mount with convosync=direct|
|AIX|JFS|mount with use -o dio|
|Windows NT/2000|All|none|
|Tru64 Unix|AdvFS|none|
|Linux(2.4 > k)|All|none|



In systems where direct I/O cannot be used, ALTIBASE HDB will use Buffered I/O regardless of the property settings.


vmstat utility


The vmstat is a system utility that is available in most Unix-based operating systems, and it is used to assess the state of the system in
conjunction with memory and CPU. Some OSs support their own proprietary utilities such as "nmon analyzer". The resources controlled
by OS is closely related to the performance problems. Therefore, important thing is to gather this information effectively. So here is an
example way you can do this:


-- vmstat.sh

while true

do

DATE=`date +"%y%m%d"`
TIME=`date +"%H%M%S"`
tmp=`vmstat 1 1 | tail -1`
echo "[$TIME] $tmp" >> vmstat_$DATE.log

done


Please refer to the man page in each OS for further details. This shell above is applicable to AIX OS.


iostat utility


The iostat which is a system tool to assess the I/O state of the system. It is similar to vmstat. I/O flow is also coupled with the
performance on the system. Here is an example shell using of iostat:


-- iostat.sh

while true

do

echo "======================================" >> iostat_$DATE.log
DATE=`date +"%y%m%d"`
TIME=`date +"%H%M%S"`

iostat 1 1 > iostat_tmp


## hdisk0, hdisk1, hdisk2 belongs to MEMORY storage.
tmp=`cat iostat_tmp | egrep "hdisk0|hdisk1|hdisk2" |
awk ' BEGIN { c2 += $2 }
{ c3 += $3 }
{ c4 += $4 }
{ c5 += $5 }
{ c6 += $6 }
END { print c2, c3, c4, c5, c6} '`
echo "[$TIME] MEM $tmp" >> iostat_$DATE.log


## hdisk3, hdisk4, hdisk5 belongs to DISK storage.
tmp=`cat iostat_tmp | egrep "hdisk3|hdisk4|hdisk5" |
awk ' BEGIN { c2 += $2 }
{ c3 += $3 }
{ c4 += $4 }
{ c5 += $5 }
{ c6 += $6 }
END { print c2, c3, c4, c5, c6} '`
echo "[$TIME] DISK $tmp" >> iostat_$DATE.log


## hdisk6, hdisk7 belongs to LOGS storage.
tmp=`cat iostat_tmp | egrep "hdisk6|hdisk7" |
awk ' BEGIN { c2 += $2 }
{ c3 += $3 }
{ c4 += $4 }
{ c5 += $5 }
{ c6 += $6 }
END { print c2, c3, c4, c5, c6} '`
echo "[$TIME] LOGS $tmp" >> iostat_$DATE.log
echo "" >> iostat_$DATE.log

done


Please refer to the man page in each OS for further detail. This shell above is applicable to AIX OS.

## ALTIBASE HDB Replication


ALTIBASE HDB Replication

### Replication Overview


Background
Basic Flow of Replication.

Terminology
Description of Replication steps
What is XLog?
Types of Replication
How to create Replication?
Summary


Background


ALTIBASE HDB’s network-based replication architecture, while providing very speedy performance, imposes very little overhead on
computing resources since it only transforms transaction logs into logical logs and sends them to remote servers for processing.


Basic Flow of Replication.


Terminology

|Technical term|Description|
|---|---|
|SN|Sequence Number of a transaction log (a unique number assigned to a transaction log)|
|XSN|Xlog Sequence Number (a unique number assigned to an Xlog)|
|xLog|Compact packet made by the sender to replay the same transaction in a remote server.|
|Sender|Thread that sends an information of a transaction from a local server to a remote server.|
|Receiver|Thread that receives xLog from the sender and applies it to the remote server.|


|Query Processor (QP)|the internal module that deals with SQL execution. (not a thread)|
|---|---|
|Storage Manager (SM)|the internal module that reads record or writes transaction logs. (not a thread)|



Description of Replication steps

|Flow|Description|
|---|---|
|1,2|QP prepares SQL to execute.(Click here if you want to know more about how a SQL is executed in HDB.)|
|3|SM writes a log of the transaction.|
|4|Sender reads the log and converts it to xLog|
|5|Sender sends xLog to a receiver. If it is successful, sender's work is done.(Asynchronous Mode)|
|6|Receiver tries to apply XLog to the remote server.|
|7|Receiver sends ACK to the sender after it applies xLog.|



Receiver directly applies Xlog to SM since XLog is already verified by QP of the local server. This method enables the best
performance among all Replication techniques.


What is XLog?


Replication Manager has two threads, Sender and Receiver.
When the sender sees a new log, it immediately creates an XLog and sends it to the Receiver.
XLog contains the information about how to replay the same transaction in the remote server.

|Types of XLog|Description|
|---|---|
|INSERT|Target Table id + Primary key values + data values|
|UPDATE|Target Table id + Primary key values + Values Before updated + Values After updated|
|DELETE|Target Table id + Primary key values|



INSERT transaction normally needs all information about the target table and the value of all columns.
DELETE transaction needs the information about the target table and the primary key of the record to be deleted.
UPDATE transaction needs the information about the target table, the previous value and the after value of the column. The previous


value is necessary for the UPDATE transaction since the value at the remote server can be different from the value in the local server.(We
will explain why the previous value in XLog exists in detail later.)


Types of Replication

|Mode|Description|
|---|---|
|Asynchronous (LAZY)|Asynchronous mode does not check whether XLog is successfully applied to the remote server or not.|
|Synchronous (EAGER)|Synchronous mode always checks whether XLog is applied to the remote server without the conflict or not.|



In Asynchronous mode, a local transaction is completed with steps (1 + 2 + 3) - red box in above diagram. Replication transaction is
completed with steps (4 + 5) - blue box in above diagram.
Steps (4 + 5) have no effect to the local transaction. In other words, the local transaction and the replication transaction do not interfere
each other.

This means that the local transaction can be completed even if the sender could not send Xlog to the remote server.
However, the local transaction in Synchronous mode is completed with all the steps ( 1 + 2 + 3 + 4 + 5 + 6 + 7).
The performance of Asynchronous mode is normally faster than Synchronous mode.


After the Sender receives ACK from the receiver, the Sender tries to update "XSN" column of the meta table. In this way, the
sender can determine which position of Xlog it has to send after ALTIBASE HDB is restarted.
After the Receiver completes applying the XLog to ALTIBASE HDB, it updates "Apply XSN" column of the meta table. This way,
the Receiver remembers up to which position it has to apply Xlog before ALTIBASE HDB stops.
When the system is recovered from the failure condition, the Sender automatically sends Xlog from position it marked
according to the column of the meta table indicates.


How to create Replication?


Replication can be initiated in few simple steps.
Step1. configure altibase.properties in $ALTIBASE_HOME/conf/altibase.properties.


REPLICATION_PORT_NO = 30300 (example)


Step2. Create the replication object and start it.


iSQL> CREATE REPLICATION rep1 WITH '192.168.1.30', 30300

FROM SYS.TABLE_1 TO SYS.TABLE_1,

FROM SYS.TABLE_2 TO SYS.TABLE 2,

...

;

iSQL> ALTER REPLICATION rep1 START;
iSQL> ALTER REPLICATION rep1 STOP;
iSQL> DROP REPLICATION rep1;


You have to configure the property and specify the replication object in all nodes in the replication environment.


Please refer to Replication User's Manual for detailed information.


Summary


ALTIBASE HDB’s log-based replication architecture, while providing very speedy performance, imposes very little overhead on
computing resources since it only transforms transaction logs into logical logs and sends them to remote servers for processing.


ALTIBASE HDB replication provides users with a choice of two commonly used modes of replication: Asynchronous(Lazy) mode and
Synchronous mode (Eager). Lazy mode focuses on high performance while Eager mode focuses on data integrity and consistency.


In Asynchronous mode, a local transaction is completed without waiting for the remote server to successfully commit the same


transaction. In Synchronous mode, however, the local transaction is completed concurrently with the remote server – only if both local
and remote servers confirm the successful committed operation. While asynchronous mode provides higher performance, allows for
geographically distributed nodes, and multiple servers in the topology; there are cases where some records may become out-of-sync.
When using asynchronous mode, some records can be different for a period of time due to network latency or failure, or maintenance
windows during which replication may be stopped by an administrator. The window during which the records are out-of-sync may lead
to replication conflicts


Do you want to learn more about replication conflicts ?

### What is a Replication Conflict?


What is a replication conflict?

Simple case
Types of Conflict
Summary


What is a replication conflict?


Simple case


In a nutshell, let's assume that the Sender in node B processes transactions faster than the Sender in node A.
After steps (#1, #2) are completed as illustrated in the diagram above, the Receiver in node A cannot update the records since the
before-value("10") in XLog is different from the current value("20")
We call this situation as a Replication Conflict.


Types of Conflict

|Types|Description|
|---|---|
|Insert-conflict|The record in XLog already had been inserted|
|Update-conflict|Before value of the record in XLog is different from the current value of the target column|
|Delete-conflict|Record in XLog already had been deleted|



Conflict error message is written on $ALTIBASE_HOME/trc/altibase_rp.log.
for example,

|Types|message|
|---|---|
|Insert-conflict|ERR-11058(errno=0) The row already exists in a unique index.|
|Update-conflict|ERR-61001(errno=0) A conflict has been occurred while executing the received statement.|
|Delete-conflict|ERR-61000(errno=0) The received record is not found in the database.|



altibase_rp.log also contains information about the SQL statement which causes the conflict in the remote server.


[Thread-280|Thread-280] [Level-2|Level-2]
ERR-61035(errno=0) [Receiver] An update conflict encountered.


[Thread-280|Thread-280] [Level-2|Level-2]
ERR-61001(errno=0) A conflict has been occurred while executing the received statement.


[Thread-280|Thread-280] [Level-3|Level-3]

UPDATE SYS.REP_TEST2 SET C2 = ccc WHERE C1 = 1;


Summary


It is important to analyze and address “replication conflicts” when using asynchronous replication. Asynchronous replication implements
“eventual consistency”; an approach that has many benefits, yet requires additional care.


When using asynchronous replication, it is important to design the service to minimize conflicts. The way to avoid conflicts is to ensure
that the same records are not updated on different systems concurrently. Designating one server as the “read-only” copy, partitioning
the data based on primary key, or other approaches can be used to avoid replication conflicts.


If you want to know more in detail, please refer to this document

### How to resolve a replication conflict?


Replication conflict resolution in ALTIBASE HDB

Eager mode Replication

Overview

How to configure this mode?
Considerations
User-oriented scheme (REPLICATION_UPDATE_REPLACE property)

Overview

How to configure this scheme?
Considerations

Time Stamp scheme

Overview

How to configure this scheme?
Considerations

Summary


Replication conflict resolution in ALTIBASE HDB


We explained that a replication conflict is caused by either network delays or irregular sequence of transactions.
In a typical conflict situation, a Receiver cannot decide which record is correct between the current value and the before value in Xlog.
To help users to deal with such replication conflicts, ALTIBASE HDB provides a few different conflict resolution schemes, such as
user-oriented scheme, a master-scheme and a time stamp based scheme.


Eager mode Replication


Overview

|Steps|Description|
|---|---|
|1|Local Transaction takes place and waits until the step #5|
|2|Sender creates XLog|
|3|Sender sends XLog to Receiver|
|4,5|Receiver applies and returns the result back to Sender|
|6|Return errorCode to the application|



We already explained about the typical flow of Eager mode Replication.
Here is a typical flow for in case of a replication conflict: the transaction in the local server cannot be completed until the Sender
receives an ACK from the Receiver in the remote server.

The Receiver checks whether any conflict has occurred in the remote server. If the transaction fails due to a conflict in the remote server,
the Receiver sends an ACK containing the error information related to the conflict back to Sender. In this case, the transaction in the
local server will also fail.


How to configure this mode?


User can specify the mode when creating a replication object as shown below:


CREATE EAGER REPLICATION WITH '' ...


Considerations


Performance of Eager mode replication is always slower than that of Lazy mode. If your priority is high performance, Eager mode
replication is not a good choice.


User-oriented scheme (REPLICATION_UPDATE_REPLACE property)


Overview

|Steps|Description|
|---|---|
|1,2|Local Transaction completes without waiting for an ACK from Receiver|
|3|Sender creates XLog|
|3|Sender sends XLog to Receiver|
|4|Receiver applies XLog regardless of a replication conflict|



REPLICATION_UPDATE_REPLACE is one of properties in ALTIBASE HDB.
When it is turn on, Receiver does not check for a conflict any more. It simply overwrites the existing record even if there is a replication
conflict.
In the above diagram, the conflict has occurred because the existing value ("30") is different from the before-value ("10") of XLog.
When user uses this method, the existing data in the remote server is modified to "20".


How to configure this scheme?


Set the value of REPLICATION_UPDATE_REPLACE property to "1" in $ALTIBASE_HOME/conf/altibase.properties so that Receiver does
not check for any conflict.


Considerations


Network delays can introduce mismatches for last values.


Time Stamp scheme


Overview


This method is similar to REPLICATION_UPDATE_REPLACE method, however, Receiver compares the timestamp value of an existing
record with the timestamp value of XLog when Receiver applies XLog to the remote server.
If the timestamp value of XLog is bigger than the existing record, XLog will be applied, otherwise, the replication transaction will be
dropped.
In the above diagram, since the timestamp value (11:01) of XLog is smaller than the timestamp value (11:02) of the existing data, the
replication transaction can not be applied to the remote server.
On the other hand, if XLog of Node B has been sent to Node A, the existing data would be replaced with the XLog from Node B since
timestamp value of Node B is bigger than that of Node B.


How to configure this scheme?



1.

2.



Add a timestamp column to the table.
set REPLICATION_TIMESTAMP_RESOLUTION value to "1" in $ALTIBASE_HOME/conf/altibase.properties.



Considerations


Since the size of timestamp data type is 8 bytes, the size of the record will be increased by 8 bytes.


System clocks should be synchronized across the servers to ensure accuracy of the operation.


Summary


Users should know that these methods do not guarantee the data consistency perfectly, they only allow users to control the behavior of
Receiver when replication conflicts occur.


For more information, please refer to reference manual


### What is Offline Replicator?

Offline Replicator

Background
How to use Offline Replicator?


Offline Replicator


Background


In the above diagram, some XLogs of SYSTEM A may not be sent to the remote server (SYSTEM B) when the SYSTEM A has a failure. In
this case, the system has to fail over to SYSTEM B, but SYSTEM B needs those unsent XLogs to start the service, otherwise, data in
between those systems will be inconsistent. This can be achieved if SYSTEM B is able to access the log files of SYSTEM A and apply
them locally.


How to use Offline Replicator?


Follow the steps below if you need to use Offline Replicator feature.

|steps|Description|
|---|---|
|1|Mount a volume with the access enabled for SYSTEM-B|
|2|Create Offline Replicator on SYSTEM-B<br>iSQL> CREATE REPLICATION rep1 OPTIONS OFFLINE<br>'/data1/logfiles'<br>WITH '192.168.1.13', 30300 FROM SYS.table TO SYS.table;|
|3|Execute SQL to start offline replication<br>iSQL> ALTER REPLICATION rep1 START WITH OFFLINE;|



Status of Offline Replicator becomes "stop" once it completes its work.
You can start the fail over procedure after checking this status.


To learn more, refer to this manual

## ALTIBASE HDB Troubleshooting


Troubleshooting information for various ALTIBASE HDB issues

### Information required to diagnose ALTIBASE HDB problems


About the content

List of diagnostics information to be gathered

ALTIBASE HDB trace log
altibase.properties file
List of OS Environment variables

Kernel value

OS logs
System configuration information
ALTIBASE HDB process stack trace
System resource utilization
Problem symptoms and required diagnostics information

Commons

ALTIBASE HDB abnormal shutdown


ALTIBASE HDB hang
ALTIBASE HDB performance degradation


About the content

|Purpose|A list of information needed to diagnose ALTIBASE HDB problems.|
|---|---|
|Applies to|HDB versions 4.3.9 or later|
|Prerequisites|Administrator's Manual|



List of diagnostics information to be gathered


ALTIBASE HDB trace log


Almost in all cases to analyze problems, the best place to start is ALTIBASE HDB trace logs. The default location of these logs is is
$ALTIBASE_HOME/trc folder.


When users have any issues in ALTIBASE HDB environment, they can archive and compress the entire folder structure and send it to
Altibase Customer Support service to help to identify the root cause of the problems.

|File Name|Description|
|---|---|
|altibase_boot.log|The main trace log. It contains ALTIBASE HDB engine's start-up and shutdown log.|
|altibase_qp.log|The trace of  ALTIBASE HDB QP (Query Processing) module.|
|altibase_sm.log|The trace log of ALTIBASE HDB SM (Storage Manage) module.|
|altibase_rp.log|The trace log of ALTIBASE HDB RP (Replication Processor) module.|
|altibase_xa.log|The trace log of ALTIBASE HDB XA module.|



It is advisable to send us all of these files above in order to minimize round-trip times.


altibase.properties file


altibase.properties file is located in $ALTIBASE_HOME/conf folder.





List of OS Environment variables


A text file containing the OS specific environment information listed below should also be submitted to Altibase Customer Service.


$ env
$ ulimit -a


Kernel value

|OS|command|
|---|---|
|HP|# kctune|
|AIX|# vmo -a -F|
||# schedo -a -F|
||# no -a -F|
|Solaris|# cat /etc/project|
|Linux|# cat /proc/sys/kernel/sem|
||# cat /proc/sys/kernel/semall|



OS logs

|OS|command|
|---|---|
|HP|# cat /var/adm/syslog/syslog.log|
|AIX|# errpt -a|
|Solaris|# cat /var/adm/messages|
||# dmesg|
|Linux|# cat /var/log/messages|
||# dmesg|



System configuration information

|OS|command|
|---|---|
|HP|# machinfo|
|AIX|# prtconf|
|Solaris|# prtconf|
|Linux|# cat /proc/cpuinfo|
||# cat /proc/meminfo|



ALTIBASE HDB process stack trace


The stack trace shows a snapshot of the state of the threads, and it is very useful information to solve the various types of problems especially, process hanging situations.


|Platforms|Usage|Col3|
|---|---|---|
|AIX|$ procstack [altibase_pid]|after AIX 6.1, procstack command to ALTIBASE HDB process does not work properly.|
|HPUX|$ pstack [altibase_pid]||
|Solaris|$ pstack [altibase_pid]||
|Linux|$ pstack [altibase_pid]||


System resource utilization


vmstat


$ vmstat 1 5


CPU and memory utilization of ALTIBASE HDB process


$ ps -p [altibase_pid] -o pcpu -o vsz


Problem symptoms and required diagnostics information


Commons


ALTIBASE HDB trace log
altibase.properties
OS Environment variable list

Above information is required to analyze any ALTIBASE HDB problem.


ALTIBASE HDB abnormal shutdown


Commons

OS logs


ALTIBASE HDB hang


Commons

ALTIBASE HDB process stack trace


ALTIBASE HDB performance degradation


Commons

ALTIBASE HDB process stack trace during the system peak time.

### A transaction exceeds lock timeout value specified by user


What is this error?

How to confirm this condition?

How to resolve this case?


What is this error?


Session-1

iSQL> AUTOCOMMIT OFF;

iSQL> UPDATE T1 SET C1 = C1 + 1;


Session-2

iSQL> DROP INDEX IDX33; (IDX33 is relate with T1 table)

[ERR-11075 : The transaction exceeds lock timeout specified by user.]


This error occurs when a session executing a DDL tries to put a lock on a table is already locked by other session


This error occurs when a session executing a DDL tries to put a lock on a table is already locked by other session.
This error can also occur when a replication transaction tries to put a lock on a table that is already locked by a local transaction. (In this
case, you can find the error message in $ALTIBASE_HOME/trc/altibase_rp.log)


How to confirm this condition?


Users will need to validate to make sure that in fact there is a lock on the target table by another session.
To learn more about how to check session conditions, please review this content.


How to resolve this case?


There are two ways to resolve this problem.
First, terminate session that has a lock on the target table. (See this page.)
Second option is simply to wait for a while. Lock can be unlocked when users explicitly execute a commit or rollback.

### The number of logfiles grows rapidly


About the contents

Symptoms
Caused by

Long running transactions exist (Transactions that are not committed or rolled back)

Description
How to find uncommitted transactions?

Available Actions

Replication sender does not work properly

Description
How to find out that there are Replication problems?
Available Actions

Checkpoint thread does not work properly

Description
How to figure out that Checkpoint thread does not work properly?
Archiving thread does not work properly

Description
How to find out that Archiving thread does not work properly?
Conclusion

Reference


About the contents

|Purpose|The contents here explains why in some cases, ALTIBASE HDB does not remove the transaction log files.|
|---|---|
|Applies to|HDB versions 4.3.9 or later|
|Prerequisite|Administrator's Manual|



Symptoms


The number of log files in LOG_DIR grows rapidly. (The log file location is specified in altibase.properties)


Caused by


In ALTIBASE HDB, Checkpoint thread removes the unnecessary transaction log files(logfiles). However, Checkpoint thread does not
remove the transaction log files under the following conditions.



1.

2.

3.

4.



Long-run transaction exists.(Transaction is not committed or rolled backed.)
Replication sender does not work properly.
Checkpoint thread does not work properly.
Archiving thread does not work properly.



Long running transactions exist (Transactions that are not committed or rolled back)


Description


When a transaction is rolled back, ALTIBASE HDB has to read information from transaction log files in order to undo the transaction.
Therefore, if there is such an unfinished transaction, ALTIBASE HDB has to keep the log files associated with that transaction.


For example in the above diagram, Transaction D is not finished, and it may roll back. Therefore, ALTIBASE HDB has to keep the log
files after log#6 until transaction D is finished (commit or rollback). Although transactions E and F are started and ended after log#6,
ALTIBASE HDB has to save log files for transaction D. In other words, even though the transaction does not finish for a long time and
many update transactions are executed during that period. In this case Checkpoint thread does not remove the log files after log#6,
therefore, the disk space will be exhausted.


You can prevent this problem by editing the timeout properties of ALTIBASE HDB. ALTIBASE HDB automatically rollbacks the
transaction if it exceeds the time specified in timeout properties. Please, refer to IDLE_TIMEOUT / QUERY_TIMEOUT /
FETCH_TIMEOUT / UTRANS_TIMEOUT in the Starting User's Manual.


How to find uncommitted transactions?



1.

2.



You can find the long running uncommitted transactions in ALTIBASE HDB using by this query.
Check the UTRANS_TIME from the result of the query.



Available Actions



1.

2.



Terminate the session that has the long running transaction. (See also, How to terminate a session )
You may consider setting the value of UTRANS_TIMEOUT to the smaller value.



Replication sender does not work properly


Description


If you are using the ALTIBASE HDB's Replication functionality, malfunctioning of Replication sender thread may prevent Checkpoint
thread to remove the log files.


Replication sender thread uses the log files to synchronize data between replicated servers. Therefore, Checkpoint thread cannot
remove the log files unless Replication sender finishes its work on them.


In the above diagram, let's assume that Replication sender is reading logfile#3, and service threads are writing on logfile#6. In this case,
the Replication sender needs not only logfile#3 but also logfile#4, logfile#5 and logfile#6 to synchronize with the receiving server. Thus,
Checkpoint thread cannot remove logfile#3 and newer, but only logfile#1 and logfile#2. Checkpoint thread will remove the log files after
logfile#3 once Replication sender thread applies the log files to the receiving server. (For further information of how Replication works,
please refer to this page.)


Furthermore, Checkpoint thread cannot remove the log files if Replication sender does not work due to network failures or DBA human
errors - such as shutdown of Replication by mistake.


How to find out that there are Replication problems?



1.

2.



You have to check whether Replication sender is running or not by using this query.
Check the Replication gap in Replication object by using this query.



Available Actions



1.

2.



Start the Replication sender if it is stopped.
Fix the Replication problem.



Checkpoint thread does not work properly


Description


As we mentioned earlier, Checkpoint thread removes the log files, thus if Checkpoint thread does not work properly, the log files can not
be removed.


Check whether CHECK POINT ENABLE is set to 0


_ _

Setting the value of CHECK_POINT_ENABLE to 0 means that ALTIBASE HDB does not perform Checkpoint automatically. In this
case, you have to perform the Checkpoint manually. Sometimes disabling Checkpoint is helpful. For example, if there are I/O
issues on the system, disabling Checkpoint reduces I/O activity. However, you have to monitor the disk space of LOG_DIR since
Checkpoint thread does not empty the space automatically.


You have to consider all the details before setting the value of CHECK_POINT_ENABLE to 0.


The duration of Checkpoint operation
Checkpoint thread figures out which log files are removable at first, and removes those files at the end of every Checkpoint
operation. Thus, if the Checkpoint operation takes too much time, the log files created after the Checkpoint procedure started
can not be removed before the checkpoint operation finishes. You can refer to altibase_sm.log file (location of the file is
specified in altibase.properties) to analyze what slows down the procedure.


How to figure out that Checkpoint thread does not work properly?



1.

2.



Make sure that CHECK_POINT_ENABLE property in altibase.properties is set to 1.
Check altibase_sm.log to analyze the status of Checkpoint thread.



Archiving thread does not work properly


Description


If Archiving thread does not work properly, archiving of the log files process will fail. (i.e. archive log partition is full). In this case,
Checkpoint thread does not remove unarchived log files. Archiving thread must copy them to ARCH_DIR (the file location is specified in
altibase.properties) before Checkpoint thread removes them.


How to find out that Archiving thread does not work properly?



1.



Check altibase_sm.log. Archiving thread related error message are added in the log when Archiving thread has a problem.



Conclusion


In order to operate ALTIBASE HDB properly, it is very important to monitor the folders containing the log files (LOG_DIR ) . Once
LOG_DIR is full, all transactions are suspended and you may have to shutdown ALTIBASE HDB to fix the problem. Furthermore, it may
cause the service to go offline.


Reference


ALTIBASE Administrator's Manual

### A user tablespace does not have enough free space


What is this error?

How to resolve this error?


What is this error?


iSQL> CREATE TABLESPACE disk_tbs datafile 'dbf1.dbf' SIZE 10M AUTOEXTEND OFF;
iSQL> CREATE TABLE t2 (c1 CHAR(100)) TABLESPACE disk_tbs;
iSQL> INSERT INTO T2 VALUES ('1');

iSQL> INSERT INTO T2 SELECT * FROM T2;

.....
(repeat above SQL)

.....

iSQL> INSERT INTO T2 SELECT * FROM T2;

[ERR-11035 : The tablespace does not have enough free space ( TBS ID : 4, TBS Name :DISK_TBS, Type : 2,
Used Page Limit : 128 ).]


As it is illustrated in the above example, an error message is displayed when a user tablespace's usage grows up to the limit specified at
the initial creation of that tablespace.In this example it is 10Mbytes.
Please also note that this message is different for the versions of ALTIBASE HDB earlier than version 5.
How to check usage of a tablespaces? refer to this page.


How to resolve this error?


First, please check to make sure that in fact the user tablespace does not have enough resource (disk space in our example).
Second, execute the following DDL statements to expand the user tablespace.


iSQL>ALTER TABLESPACE disk_tbs ADD DATAFILE 'dbf2.dbf' SIZE 10M AUTOEXTEND ON;


(if TBS name equals to "SYS_TBS_UNDO", execute below DDL)
iSQL> ALTER TABLESPACE sys_tbs_undo ADD DATAFILE 'undo002.dbf' size 1G autoextent on;

### Cannot insert new records after deleting bulk records


Problem Abstract


Disk Tablespace gets full and data cannot be inserted anymore.


This problem was reported by an ALTIBASE HDB customer. In this document, we will reference the reported case while examining the
causes of the problem and the possible resolution options.


Background


FMS (Freelist Managed Segment)


ALTIBASE HDB 5.3.3 manages disk pages with FMS technique.

**Unknown macro: {gliffy}**


In FMS technique, used and available pages are added to the head of the freelist. Although the pages are added to the freelist, they are
not usable until the Ager cleans them.


ALTIBASE HDB has to allocate a new page to insert data, if all pages at the header are not aged.
By default, only 5 pages are searched to allocate the space for the new data.
ALTIBASE HDB can search more than 5 pages by modifying the ALTIBASE HDB provided properties. However, the performance can be
degraded if the value gets bigger.


Tablespace


Unless specified otherwise, ALTIBASE HDB stores data and Index in the same Tablespace, and they are managed in a Segment unit.


Each Segment requests a page to the Tablespace if it needs more space to store data or Index.

**Unknown macro: {gliffy}**


Cause of the Problem


There are three possible causes for the issue.


Inefficient page usage


ALTIBASE HDB provides two properties - PCTUSED and PCTFREE for controlling the page usage.


PCTFREE: the amount of space kept free on each page for the update statement - versioning. The value specified by PCTFREE indicates
the percentage of space kept free in order to allow existing records to be updated.


PCTUSED: once the page gets full, it does not return to the insert-able state until the amount of space gets smaller than the value
specified on this value.


If the page usage is as follows, ALTIBASE HDB cannot reuse the existing pages, but allocates a new page for the new data being
inserted.

**Unknown macro: {gliffy}**


Since the value of properties are already changed - PCTUSED = 80, this is not the case at this time.


This problem can occur on any disk database. To avoid this issue, DBA must perform reorganization on tables.


Bulk insert and delete operations


ALTIBASE HDB cleans the page for only committed data . Therefore, it cannot work on pages with bulk insert/delete operations.
By default, ALTIBASE HDB searches the first 5 available pages from the head of the freelist when it needs space for the operation. Under
bulk operations, many pages are added to the head of the freelist; however, they are not available pages. Therefore, ALTIBASE HDB
allocates a new page for the next bulk insert operation.


Since the Tablespace is full, ALTIBASE HDB cannot allocate the page and returns an error message.


According to the test case we got from the customer, this was not the issue in their case.


Index Segment full


A page returns to the reusable state once it gets aged. A page allocated to the Index Segment gets aged when the 'SPLIT' operation is
occurred. However, once the Index Segment and the Tablespace are full, the Index Segment cannot allocate a page from the
Tablespace; therefore, 'SPLIT' operation fails.


Since ALTIBASE HDB cannot allocate a page to the Index Segment, the error message is returned.


Solutions


1. Upgrade to 5.5.1


ALTIBASE HDB 5.5.1 uses TMS (Tree Managed Segment) technique for the page. This issue does not occur frequently with 5.5.1 as it
does with 5.3.3 - this technique is also used by other database vendors such as Oracle.


However, an upgrade was not an option for the customer reporting the problem.


2. Commit frequently


The use of the Ager more frequently can help avoiding this problem. Thus it is recommended that the commit is performed more
frequently in the bulk operations.


3. Seperate Tablespace


We noticed that the customer was using LOB data type. LOB data accelerates the problem since storing LOB data takes a lot of pages.
Therefore, separating the Tablespace will reduce the possibility of the symptom.


It is recommended to separate the Tablespace - one for data and another for Index.
In this way, the users can easily monitor the usage of the Tablespaces and prevent the problem in advance.


If the usage of Data and Index Tablespace are near 100%, then DBA may add datafile to prevent the Tablespace full situation.


Furthermore, it is recommended that the tables are refreshed periodically.
ALTIBASE HDB does not support a reorganize function that is supported by some other database solutions such as Oracle. However the
steps listed below can be used a a workaround for achieving the same re-org results:


1. export data
2. truncate tables

3. import data


This will gather the data distributed all over the pages and stack them from the first page.

**Unknown macro: {gliffy}**


1. Test case with ALTIBASE HDB 5.3.3


Here is a test case to easily reproduce the problem with ALTIBASE HDB 5.3.3.


Reproduce Step


iSQL> create disk tablespace disk01 datafile 'disk01.dbf' size 10M autoextend off;

Create success.
iSQL> create table temp01(
2 i1 BIGINT not null,
3 i2 VARCHAR(248) not null,

4 i3 INTEGER,

5 i4 SMALLINT not null,

6 i5 SMALLINT not null,
7 i6 NIBBLE(254),
8 i7 BLOB)
9 tablespace "DISK01"
10 pctfree 10
11 pctused 80 ;

Create success.

iSQL>
iSQL> alter table temp01 add primary key(i1,i2) using index tablespace DISK01;

Alter success.
iSQL> create index temp01_index01 on temp01(i1,i3) tablespace DISK01;

Create success.
iSQL> create or replace procedure testproc01(pcnt integer)

2 as

3 void_ser integer;
4 begin
5 for i in 1 .. pcnt loop
6  select seq1.nextval into void_ser from dual;
7  for j in 1 .. 10 loop
8 INSERT INTO temp01 ( i1, i2, i3, i4, i5, i6 )VALUES ( void_ser, to_char(j,'00'), 16642685, 0, 10,
111111111111111111111111111111100000000004341);

9  end loop;
10 end loop;

11 end;

12 /

Create success.
iSQL> exec testproc01(1000);

Execute success.

iSQL>

iSQL>

iSQL>


iSQL> /

Execute success.

iSQL> /

Execute success.

iSQL> /

Execute success.

iSQL> /

Execute success.

iSQL> /

Execute success.

iSQL> /

[ERR-11123 : The tablespace does not have enough free space ( TBS Name :DISK01 ).
0008 : INSERT INTO TEMP01 ( I1, I2, I3, I4, I5, I6 )VALUES ( VOID_SER, TO_CHAR(J,'00'), 16642685, 0, 10,
111111111111111111111111111111100000000004341);

^                                                                        ^

]
iSQL> select count(*) from temp01;

COUNT

----------------------
60000

1 row selected.

iSQL> set linesize 1000
iSQL> select name,total_page_count,allocated_page_count from v$tablespaces;

NAME                   TOTAL_PAGE_COUNT   ALLOCATED_PAGE_COUNT

----------------------------------------------------------------------------------
----
SYS_TBS_MEM_DIC              129         129

SYS_TBS_MEM_DATA             257         257

SYS_TBS_DISK_DATA             12800        32

SYS_TBS_DISK_UNDO             32768        16416

SYS_TBS_DISK_TEMP             12800        32

DISK01                  1280         1280

6 rows selected.

iSQL> delete from temp01 limit 5000;

5000 rows deleted.

iSQL> /

5000 rows deleted.

iSQL> /

5000 rows deleted.

iSQL> /

5000 rows deleted.

iSQL> /

5000 rows deleted.

iSQL> /

5000 rows deleted.

iSQL> /

5000 rows deleted.

iSQL> /

5000 rows deleted.

iSQL> /

5000 rows deleted.

iSQL> /

5000 rows deleted.

iSQL> /

5000 rows deleted.

iSQL> /

5000 rows deleted.

iSQL> /

No rows deleted.


iSQL> /

No rows deleted.
iSQL> select count(*) from temp01;

COUNT

----------------------
0

1 row selected.

iSQL> select table_name,disk_total_page_cnt,disk_page_cnt from v$disktbl_info join system_.sys_tables_ on
v$disktbl_info.table_oid = system_.sys_tables_.table_

oid;

TABLE_NAME                DISK_TOTAL_PAGE_CNT DISK_PAGE_CNT

----------------------------------------------------------------------------------
----
TEMP01                  768         751

1 row selected.

iSQL>
iSQL> exec testproc01(1000);

[ERR-11123 : The tablespace does not have enough free space ( TBS Name :DISK01 ).
0008 : INSERT INTO TEMP01 ( I1, I2, I3, I4, I5, I6 )VALUES ( VOID_SER, TO_CHAR(J,'00'), 16642685, 0, 10,
111111111111111111111111111111100000000004341);

^                                                                        ^


]

iSQL>


Although all data from temp01 table have been deleted, the new data cannot be inserted into temp01 table.


2. How did we determine that the cause of the problem is the Index Segment ?


iSQL> select count(*) from temp01;

COUNT

----------------------
0

1 row selected.
iSQL> exec testproc01(1000);

[ERR-11123 : The tablespace does not have enough free space ( TBS Name :TBS_DISK ).
0008 : INSERT INTO ATTR_SER ( OID_SER, PATH, TAG, FLAG, VR, VALUE )VALUES ( VOID_SER,
TO_CHAR(J,'00'), 16642685, 0,
100000000004341);

^

^

]

iSQL> alter table attr_ser aging;

Alter success.

elapsed time : 0.02


iSQL> exec testproc01(1000);

[ERR-11123 : The tablespace does not have enough free space ( TBS Name :TBS_DISK ).
0008 : INSERT INTO ATTR_SER ( OID_SER, PATH, TAG, FLAG, VR, VALUE )VALUES ( VOID_SER,
TO_CHAR(J,'00'), 16642685, 0,
100000000004341);

^

^

]


We performed aging on the table, but we could still not insert data.


iSQL> desc attr_ser;

[ TABLESPACE : TBS_DISK ]

[ ATTRIBUTE ]

-----------------------------------------------------------------------------
NAME                   TYPE            IS NULL

-----------------------------------------------------------------------------
OID_SER                 BIGINT           NOT NULL
PATH                   VARCHAR(248)        NOT NULL

TAG                   INTEGER

FLAG                   SMALLINT          NOT NULL

VR                    SMALLINT          NOT NULL
VALUE                  NIBBLE(254)

LOB                   BLOB

[ INDEX ]

-----------------------------------------------------------------------------
NAME                   TYPE   IS UNIQUE   COLUMN

-----------------------------------------------------------------------------
__SYS_IDX_ID_342             BTREE  UNIQUE    OID_SER ASC,

PATH ASC

ADBS_NU_TBLATTR_SER_OID_SER_TAG     BTREE         OID_SER ASC,

TAG ASC

[ PRIMARY KEY ]

-----------------------------------------------------------------------------
OID_SER, PATH

iSQL>

iSQL>

iSQL> alter index __SYS_IDX_ID_342 aging;

Alter success.

elapsed time : 0.02


iSQL> exec testproc01(1000);

Execute success.

elapsed time : 0.39


After performing aging on Index, we were able to insert data.


3. How to avoid the problem by seperating Tablespaces ?


Here we show an example how ALTIBASE HDB users can avoid the problem by separating Tablespace.


iSQL> create disk tablespace disk_index01 datafile 'disk_index01.dbf' size 10M autoextend off;

Create success.

iSQL> create disk tablespace disk_index02 datafile 'disk_index02.dbf' size 10M autoextend off;

Create success.
iSQL> create table temp01(
i1 BIGINT not null,
i2 VARCHAR(248) not null,

i3 INTEGER,

i4 SMALLINT not null,

i5 SMALLINT not null,
i6 NIBBLE(254),
i7 BLOB)
tablespace "DISK01"
pctfree 10


pctused 80 ;

Create success.
iSQL> alter table temp01 add primary key(i1,i2) using index tablespace DISK_index01;

Alter success.
iSQL> create index temp01_index01 on temp01(i1,i3) tablespace DISK_index02;

Create success.

iSQL>

iSQL>
iSQL> select name,total_page_count,allocated_page_count from v$tablespaces;

NAME                   TOTAL_PAGE_COUNT   ALLOCATED_PAGE_COUNT

----------------------------------------------------------------------------------
----
SYS_TBS_MEM_DIC              129         129

SYS_TBS_MEM_DATA             257         257

SYS_TBS_DISK_DATA             12800        32

SYS_TBS_DISK_UNDO             32768        17056

SYS_TBS_DISK_TEMP             12800        32

*DISK01                  1280         96*

*DISK_INDEX01               1280         64*

*DISK_INDEX02               1280         64*

8 rows selected.
iSQL> exec testproc01(1000);

Execute success.
iSQL> exec testproc01(1000);

Execute success.
iSQL> exec testproc01(1000);

Execute success.
iSQL> exec testproc01(1000);

Execute success.
iSQL> exec testproc01(1000);

Execute success.
iSQL> exec testproc01(1000);

Execute success.
iSQL> exec testproc01(1000);

Execute success.
iSQL> exec testproc01(1000);

Execute success.
iSQL> exec testproc01(1000);

Execute success.
iSQL> exec testproc01(1000);

Execute success.
iSQL> exec testproc01(1000);

[ERR-11123 : The tablespace does not have enough free space ( TBS Name :DISK01 ).
0008 : INSERT INTO TEMP01 ( I1, I2, I3, I4, I5, I6 )VALUES ( VOID_SER, TO_CHAR(J,'00'), 16642685, 0, 10,
111111111111111111111111111111100000000004341);

^                                                                        ^

]
iSQL> exec testproc01(1000);

[ERR-11123 : The tablespace does not have enough free space ( TBS Name :DISK01 ).
0008 : INSERT INTO TEMP01 ( I1, I2, I3, I4, I5, I6 )VALUES ( VOID_SER, TO_CHAR(J,'00'), 16642685, 0, 10,
111111111111111111111111111111100000000004341);

^                                                                        ^

]
iSQL> select name,total_page_count,allocated_page_count from v$tablespaces;

NAME                   TOTAL_PAGE_COUNT   ALLOCATED_PAGE_COUNT

----------------------------------------------------------------------------------
----
SYS_TBS_MEM_DIC              129         129

SYS_TBS_MEM_DATA             257         257


SYS_TBS_DISK_DATA             12800        32

SYS_TBS_DISK_UNDO             32768        17056

SYS_TBS_DISK_TEMP             12800        32

DISK01                  1280         1280

DISK_INDEX01               1280         416

DISK_INDEX02               1280         416

8 rows selected.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL>

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;


1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.


iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.

iSQL> delete from temp01 limit 1000;

1000 rows deleted.
iSQL> select count(*) from temp01;

COUNT

----------------------
40000

1 row selected.

iSQL> delete from temp01 limit 10000;

10000 rows deleted.

iSQL> delete from temp01 limit 10000;

10000 rows deleted.

iSQL> delete from temp01 limit 10000;

10000 rows deleted.

iSQL> delete from temp01 limit 10000;

10000 rows deleted.

iSQL> delete from temp01 limit 10000;

No rows deleted.


iSQL> select name,total_page_count,allocated_page_count from v$tablespaces;

NAME                   TOTAL_PAGE_COUNT   ALLOCATED_PAGE_COUNT

----------------------------------------------------------------------------------
----
SYS_TBS_MEM_DIC              129         129

SYS_TBS_MEM_DATA             257         257

SYS_TBS_DISK_DATA             12800        32

SYS_TBS_DISK_UNDO             32768        18336

SYS_TBS_DISK_TEMP             12800        32

DISK01                  1280         1280

DISK_INDEX01               1280         416

DISK_INDEX02               1280         416

8 rows selected.

iSQL>

iSQL>
iSQL> exec testproc01(1000);

Execute success.

iSQL> /

Execute success.

iSQL> /

Execute success.

iSQL> /

Execute success.

iSQL> /

Execute success.

iSQL> /

Execute success.

iSQL> /

Execute success.

iSQL> /

Execute success.

iSQL> /

Execute success.


iSQL> /

Execute success.

iSQL> /

[ERR-11123 : The tablespace does not have enough free space ( TBS Name :DISK01 ).
0008 : INSERT INTO TEMP01 ( I1, I2, I3, I4, I5, I6 )VALUES ( VOID_SER, TO_CHAR(J,'00'), 16642685, 0, 10,
111111111111111111111111111111100000000004341);

^                                                                        ^

]
iSQL> /

[ERR-11123 : The tablespace does not have enough free space ( TBS Name :DISK01 ).
0008 : INSERT INTO TEMP01 ( I1, I2, I3, I4, I5, I6 )VALUES ( VOID_SER, TO_CHAR(J,'00'), 16642685, 0, 10,
111111111111111111111111111111100000000004341);

^                                                                        ^

]
iSQL> select count(*) from temp01;

COUNT

----------------------
100000

1 row selected.


iSQL> select name,total_page_count,allocated_page_count from v$tablespaces;

NAME                   TOTAL_PAGE_COUNT   ALLOCATED_PAGE_COUNT

----------------------------------------------------------------------------------
----
SYS_TBS_MEM_DIC              129         129

SYS_TBS_MEM_DATA             257         257

SYS_TBS_DISK_DATA             12800        32

SYS_TBS_DISK_UNDO             32768        18336

SYS_TBS_DISK_TEMP             12800        32

DISK01                  1280         1280

DISK_INDEX01               1280         416

DISK_INDEX02               1280         416

8 rows selected.

iSQL> delete from temp01;

100000 rows deleted.

iSQL>

iSQL>

iSQL>
iSQL> exec testproc01(1000);

Execute success.

iSQL> /

Execute success.

iSQL> /

Execute success.

iSQL> /

Execute success.

iSQL> /

Execute success.

iSQL> /

Execute success.

iSQL> /

Execute success.

iSQL> /

Execute success.

iSQL> /

Execute success.

iSQL> /

Execute success.

iSQL> /


[ERR-11123 : The tablespace does not have enough free space ( TBS Name :DISK01 ).
0008 : INSERT INTO TEMP01 ( I1, I2, I3, I4, I5, I6 )VALUES ( VOID_SER, TO_CHAR(J,'00'), 16642685, 0, 10,
111111111111111111111111111111100000000004341);


^                                                                        ^

]


By separating Tablespaces, the problem does not occur again. Furthermore, users have the ability to monitor the status of Tablespaces
seperately.
In this way, the users manage the Tablespace more efficiently and they can determine the cause of such problems easily.

### Performance degradation issue when upgrading AIX OS to 6.1


Symptom
Analysis
Solution


Symptom


The performance of ALTIBASE HDB is dramatically degraded after upgrading AIX OS from version 5.3 to version 6.1.


Analysis


1. Observed a state of Service Thread of ALTIBASE HDB by using "procstack" utility of AIX.


2. Found out that built-in function - sysdate() - of ALTIBASE HDB was causing the performace degradation.


3. sysdate() function of ALTIBASE HDB triggers a system-call to "localtime_r()" and it causes the performance degradation. We
confirmed the difference between AIX 5.3 and 6.1 with an AIX support engineer.


0x0000000000003428 _check_lock() + 0x8
0x0900000000a85598 _global_lock_common(??, ??, ??) + 0x2b8
0x0900000000011410 _rec_mutex_lock(??) + 0xd0
0x0900000000049284 localtime_tz_r(??, ??, ??) + 0x384
0x000000010000dbec PDL_OS::localtime_r(const long*,tm*)() + 0xc
0x00000001000b54dc qtc::sysdate(qcTemplate*)() + 0xbc
0x0000000100476b8c qmx::executeInsertValues(qcStatement*)() + 0x90c
0x000000010058903c mmcStmtType::executeDML(mmcSession*,mmcSessionInfo*,mmcStmtType*,unsigned
int*,long*)() + 0x19c
0x0000000100584398 mmcStmtType::execute(unsigned int*,long*,mmcSessionInfo*)() + 0x98
0x00000001005c00c4 mmtTaskThread::doPrepareExecute(mmcStmtType*,long long,void*,unsigned long
long,void*,unsigned long long)() + 0x444
0x00000001005c1fc4 mmtTaskThread::executeArray(unsigned int)() + 0x484
0x00000001005c29ac mmtTaskThread::executeProtocol()() + 0x72c
0x000000010059ef60 mmtTaskThread::processProtocol(idBool*,idBool*)() + 0x780
0x000000010059f678 mmtTaskThread::runShared()() + 0x198
0x00000001005a04a0 mmtTaskThread::run()() + 0x400
0x0000000100035924 idtBaseThread::staticRunner(void*)() + 0x44
0x0900000000a86d50 _pthread_body(??) + 0xf0


Solution


Performance bottleneck occurs depending on the setting of TimeZone in AIX 6.1. To work around this AIX issue, the default TimeZone
setting has to be changed to Local TimeZone based on Posix standard.


Shell Prompt> echo $TZ
Asia/Seoul <- Olson time zone (X)
KORST-9 <- Posix time zone (O)


- Modify Time zone
Shell Prompt> smitty chtz_user


