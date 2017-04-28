# ![](https://avatars1.githubusercontent.com/u/26529966?v=3&s=40) Shiphp - Simple SSH

A Docker container to execute commands via SSH connections.

## Instructions

- Pull down the latest: `docker pull shiphp/simple-ssh`
- Create a `.env` file with the following fields:
  - `USER` The remote connection's username.
  - `HOST` The IP for the remote connection.
  - `SCRIPT` The script to run on the remote server.
  - `PRIVATE_SSH_KEY` Your private SSH key that has remote access to the server.
- Run the script: `docker run --env-file .env shiphp/simple-ssh`
