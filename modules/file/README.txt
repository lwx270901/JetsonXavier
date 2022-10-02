This module provides File operations, locally and remotely.

File::Local usage flow:
- Ability to copy file
- Ability to check if file existed

File::Remote usage flow:
- Ability to instantiate remote file object with ID (naming) or set to it a ScpClient
- Connect to remote host
- Check if remote file existed
- Copy file from local host to remote host
- Copy file from remote host to local host