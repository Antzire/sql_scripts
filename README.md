### Frequently used Oracle SQL scripts

---

Name01: 	tbsinfo.sql

Description:	Tablespaces usage amount statistics script

*      DFC                 - Counter datafiles by each tablespace
 *      MB_MAX_SIZE         - Size of the max file (in bytes)
 *      MB_SIZE             - Size of the file (in bytes)
 *      MB_USER_SIZE        - Size of the useful portion of the file (in bytes), not open
 *      MB_MAX_AVAIL        - Total max avail space
 *      MB_FREE_SIZE        - Current free space
 *      MB_MAX_FREE_SIZE    - Current max free space
 *      MB_USED_SIZE        - Actual use space
 *      PRE_MAX_AVAIL       - Total max avail space pre
 *      PRE_FREE            - Actual free space pre

Notes:

​	If the tablespace autoextend on and maxsize parameters are not set,

​	An 'OAR-01476 divisor is equal to zero' error will occur. 

Demo:

![1547645121673](http://pngqbat1e.bkt.clouddn.com/static/images/tabsinfo.png)

