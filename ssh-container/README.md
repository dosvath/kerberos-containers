# SSH Server and Client Containers

A container that can act as an SSH server or client. The docker compose file brings up both server and client automatically. 
The SSH server configuration `sshd_config`, and SSH client configuration `ssh_config` are configured during the build to 
enable Kerberos ticket authentication.

