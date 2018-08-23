# 测试

`./modify` 文件是在Linux下编译的

## 食用方法
```bash
./modify <so文件> <旧包名> <新包名>
```
## 举个栗子
```bash
./modify libxlog.so com.tendk01.mm.xlog com.tencent.mm.xlog
```
打印结果：
```
1.
Java_com_tendk01_mm_xlog_LogLogicJni_initLogInfo
⇊
Java_com_tencent_mm_xlog_LogLogicJni_initLogInfo

2.
Java_com_tendk01_mm_xlog_LogLogicJni_setIsAlphaVersion
⇊
Java_com_tencent_mm_xlog_LogLogicJni_setIsAlphaVersion

3.
Java_com_tendk01_mm_xlog_LogLogicJni_getLogLevelFromCfg
⇊
Java_com_tencent_mm_xlog_LogLogicJni_getLogLevelFromCfg

4.
Java_com_tendk01_mm_xlog_LogLogicJni_getIPxxLogLevel
⇊
Java_com_tencent_mm_xlog_LogLogicJni_getIPxxLogLevel

5.
Java_com_tendk01_mm_xlog_LogLogicJni_getAppenderModeFromCfg
⇊
Java_com_tencent_mm_xlog_LogLogicJni_getAppenderModeFromCfg

6.
Java_com_tendk01_mm_xlog_LogLogicJni_setIPxxLogML
⇊
Java_com_tencent_mm_xlog_LogLogicJni_setIPxxLogML

7.
Java_com_tendk01_mm_xlog_LogLogicJni_setConsoleLogOpen
⇊
Java_com_tencent_mm_xlog_LogLogicJni_setConsoleLogOpen

8.
Java_com_tendk01_mm_xlog_LogLogicJni_setErrLogOpen
⇊
Java_com_tencent_mm_xlog_LogLogicJni_setErrLogOpen

9.
Java_com_tendk01_mm_xlog_Xlog_onCreate
⇊
Java_com_tencent_mm_xlog_Xlog_onCreate

10.
Java_com_tendk01_mm_xlog_Xlog_appenderOpen
⇊
Java_com_tencent_mm_xlog_Xlog_appenderOpen

11.
Java_com_tendk01_mm_xlog_Xlog_appenderClose
⇊
Java_com_tencent_mm_xlog_Xlog_appenderClose

12.
Java_com_tendk01_mm_xlog_Xlog_appenderFlush
⇊
Java_com_tencent_mm_xlog_Xlog_appenderFlush

13.
Java_com_tendk01_mm_xlog_Xlog_logWrite
⇊
Java_com_tencent_mm_xlog_Xlog_logWrite

14.
Java_com_tendk01_mm_xlog_Xlog_logWrite2
⇊
Java_com_tencent_mm_xlog_Xlog_logWrite2

15.
Java_com_tendk01_mm_xlog_Xlog_getLogLevel
⇊
Java_com_tencent_mm_xlog_Xlog_getLogLevel

16.
Java_com_tendk01_mm_xlog_Xlog_setLogLevel
⇊
Java_com_tencent_mm_xlog_Xlog_setLogLevel

17.
Java_com_tendk01_mm_xlog_Xlog_setAppenderMode
⇊
Java_com_tencent_mm_xlog_Xlog_setAppenderMode

A total of 17 modifications.
```