Question 1 explanation

- whoami: This command confirmed the active login user and showed that the session was running under the codespace account.
- groups: This listed the account's group memberships, which helps verify the user's access rights and privileges.
- echo "$SHELL": This displayed the current shell path to confirm that Bash was the active shell.
- pwd: This verified the current working directory so the session location was known before running further commands.
- ls -ls: This listed the contents and basic metadata of the current workspace, showing the main directories available.
- curl ...: This tested outbound network access and showed that the environment could reach YouTube successfully within the timeout.
