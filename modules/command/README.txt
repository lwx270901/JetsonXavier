This module provides Linux command executor, locally and remotely.

LocalCommand usage flow:
- Instantiate LocalCommand object(s), each of them can be named (id).
- Execute command
- Ability to check if command executed successfully
- Ability to get retcode, output (if succeed), error (if failed)  

LocalCommand usage flow:
- Instantiate RemoteCommand object(s), up to 16 instances which can be named (id).
- Connect to remote host
- Execute command
- Ability to check if command sent successfully
- Ability to get retcode, output (if succeed), error (if failed)  