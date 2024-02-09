# FTP Client

This is a basic FTP client implemented in Python, allowing you to interact with remote FTP servers for various operations such as listing directories, creating and deleting files, and more.

## Features

- **Login**: Authenticate with an FTP server using a username and password.
- **Passive Mode**: Toggle passive mode for data transfer.
- **Data Modes**: Choose between binary, stream, and structure data transfer modes.
- **Commands**:
  - `ls`: List files and directories on the remote server.
  - `mkdir`: Create a new directory on the remote server.
  - `rm`: Delete a file on the remote server.
  - `rmdir`: Delete a directory on the remote server.
  - `cp`: Copy files.
  - `mv`: Move files.

## Usage

```bash
python ftp_client.py <operation> <param1> [param2]

## Dependencies
Python 3.x

## Configuration
Update the host and port variables in the script for your FTP server.
