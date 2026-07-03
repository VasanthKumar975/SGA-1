Question 4 explanation

- lsof and /proc/$$/fd: These commands were used to inspect which files the shell had open and how those files were represented through file descriptors.
- exec 3<app.log: This attached a file to file descriptor 3 so the shell could read from the log file explicitly.
- ls -l > stdout.txt and ls /not_a_real_path 2> stderr.txt: These showed how standard output and standard error can be redirected separately into files.
- (ls -l && ls /not_a_real_path) > combined.txt 2>&1: This combined both output streams into a single file, demonstrating shell redirection behavior.
- ulimit -a: This displayed the current process resource limits, including open files and stack size.
