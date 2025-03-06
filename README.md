# ShellDetection

Which shell is used on each of the GitHub hosted runner flavours?

This workflow uses a matrix job to run on each of Ubuntu, MacOs and Windows GitHub hosted runners, outputting the value of `$SHELL` in the default context.
