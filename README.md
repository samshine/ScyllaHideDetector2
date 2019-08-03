# ScyllaHide Detector V2
Allows you to find the use of ScyllaHide, if your program will debug and *restore bytes*.

## TODO
- [ ] win32u.dll
- [ ] support x86 

## Done

- [x] NtSetInformationThread
- [x] NtSetInformationProcess
- [x] NtQuerySystemInformation
- [x] NtQueryInformationProcess
- [x] NtQueryObject
- [x] NtYieldExecution
- [x] NtCreateThreadEx
- [x] NtSetDebugFilterState
- [x] NtClose
- [x] NtQueryPerformanceCounter
- [x] NtGetContextThread
- [x] NtQuerySystemTime
- [x] GetTickCount
- [x] GetTickCount64
- [x] OutputDebugStringA
- [x] GetLocalTime
- [x] GetSystemTime

## Screenshots
![Normal](screen.png)

Detection

![Debugger](detect.png)

Restore bytes (after execution program)

![Restore bytes](restorebytes.png)

## Thanks
hiddy (inject.ws russian re forum)