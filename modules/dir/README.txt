This module provides Directory operations, locally and remotely.

Dir::Local usage flow:
- Ability to copy dir
- Ability to check if dir existed

Dir::Remote usage flow:
- Ability to instantiate remote dir object with ID (naming) or set to it a ScpClient
- Connect to remote host
- Check if remote dir existed
- Copy dir from local host to remote host
- Copy dir from remote host to local host