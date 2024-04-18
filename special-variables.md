1. `$0`: The name of the script itself.
2. `$1`, `$2`, ..., `$n`: Represents the positional parameters passed to the script or function.
3. `$*`: Represents all the positional parameters as a single string.
4. `$@`: Represents all the positional parameters as separate strings.
5. `$#`: The number of positional parameters.
6. `$?`: The exit status of the last executed command. Typically, `0` means success, and non-zero values indicate failure.
7. `$$`: The process ID (PID) of the current shell.
8. `$!`: The process ID (PID) of the last background command.
9. `$-`: A hyphen (`-`) indicating the current options set for the shell.
10. `$IFS`: Internal Field Separator. It determines how Bash recognizes word boundaries.
11. `$LINENO`: The current line number in the script.
12. `$PWD`: The present working directory.
13. `$OLDPWD`: The previous working directory.
14. `$SHELL`: The path to the current user's default shell.
15. `$USER`: The username of the current user.
16. `$HOME`: The home directory of the current user.
17. `$HOSTNAME`: The hostname of the machine.
18. `$HOSTTYPE`: A string describing the processor type.
19. `$OSTYPE`: A string describing the operating system.
20. `$UID`: The numeric user ID of the current user.
21. `$EUID`: The effective user ID of the current user.
22. `$GROUPS`: The groups that the current user belongs to.
23. `$RANDOM`: A random number between 0 and 32767.
24. `$SECONDS`: The number of seconds since the shell was started.
25. `$PIPESTATUS`: An array variable holding the exit status of the last foreground pipeline.
26. `$FUNCNAME`: The name of the currently executing function, if inside a function.
