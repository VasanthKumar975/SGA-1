Question 2 explanation

- mkdir -p secure_workspace/{docs,src,logs}: This created the required project folder structure for documentation, source files, and logs.
- touch ...: This created the placeholder project files so the workspace contained both directories and files for later permission testing.
- ls -ld secure_workspace secure_workspace/*: This showed the current directory and file modes before the permission changes were applied.
- chmod 750 ...: This restricted directories so only the owner could access them, which prevented unauthorized users from browsing the content.
- chmod 640 ...: This limited file access so only the owner could write and the group could read, while others could not read the project files.
- umask: This showed the default permission mask used by the shell for newly created files and directories.
