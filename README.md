# daemonizeProcess
The current process will be forked to send it into background and then main process exits.It opens three file descriptors of /dev/null file, which then duplicated and set as stdin, stdout, and stderror.
