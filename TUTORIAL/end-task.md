i have the added how to enable the now-working "end task" item in the taskbar right-click menu to the list of hidden features in Windows 11 build 23466. Also, I have updated the dedicated (older) post.

TL;DR.

1) run as administrator c:\vivetool\vivetool /enable /id:42592269,42105254
2) now run in a non-elevated Terminal reg add HCKU\Software\Microsoft\Windows\CurrentVersion\DeveloperSettings /v TaskbarEndTask /t REG_DWORD /d1 /f
3) reboot Windows 11
4) Enjoy!
