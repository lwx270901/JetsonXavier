This module implements Linux process basic operations, localy and remotely.

LocalProcess usage flow:
- Get PID via its name
- Get process name via its PID
- Check if process is alive
- Send signal (number) to process
- Kill process

RemoteProcess usage flow:
- Instantiate a RemoteProcess object, connect it to remote host
- Get PID via its name
- Get process name via its PID
- Check if process is alive
- Send signal (number) to process
- Kill process
