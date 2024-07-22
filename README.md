# ft_irc

## Overview

`ft_irc` is an IRC (Internet Relay Chat) server implemented in C++. This project is a part of the 42Seoul curriculum and aims to provide a deeper understanding of network programming and the IRC protocol. The server supports basic IRC commands and can handle multiple clients simultaneously.

## Table of Contents

- [Project Structure](#project-structure)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Commands](#commands)
- [License](#license)

## Project Structure

The project consists of the following files:

```
ft_irc/
├── Channel.cpp
├── Channel.hpp
├── Client.cpp
├── Client.hpp
├── Cmd_INVITE.cpp
├── Cmd_JOIN.cpp
├── Cmd_KICK.cpp
├── Cmd_MODE.cpp
├── Cmd_PART.cpp
├── Cmd_PASS.cpp
├── Cmd_PING.cpp
├── Cmd_PRIVMSG.cpp
├── Cmd_QUIT.cpp
├── Cmd_TOPIC.cpp
├── Cmd_USER.cpp
├── Command.cpp
├── Command.hpp
├── Define.hpp
├── main.cpp
├── Makefile
├── README.md
├── Server.cpp
├── Server.hpp
└── Utils.cpp
```

### File Descriptions

- **Channel.cpp / Channel.hpp**: Implement the functionalities related to IRC channels.
- **Client.cpp / Client.hpp**: Handle the IRC client connections and interactions.
- **Cmd_*.cpp**: Implement the various IRC commands (e.g., JOIN, PRIVMSG, QUIT).
- **Command.cpp / Command.hpp**: Manage the parsing and execution of IRC commands.
- **Define.hpp**: Contains various macro definitions used throughout the project.
- **main.cpp**: The entry point of the application.
- **Makefile**: Instructions for building the project.
- **README.md**: This file, providing an overview and documentation of the project.
- **Server.cpp / Server.hpp**: Manage the main server functionalities and client connections.
- **Utils.cpp**: Provide utility functions used across the project.

## Features

- Handles multiple client connections.
- Supports basic IRC commands such as JOIN, PART, PRIVMSG, QUIT, etc.
- Manages user authentication and channel operations.
- Compliant with the IRC RFC standards.

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/ft_irc.git
   ```
2. Navigate to the project directory:
   ```sh
   cd ft_irc
   ```
3. Build the project using the Makefile:
   ```sh
   make
   ```

## Usage

Run the server executable:
```sh
./ircserver <port> <password>
```
- `<port>`: The port number on which the server will listen.
- `<password>`: The password required for clients to connect.

## Commands

The server supports the following IRC commands:

- **PASS**: Authenticate a client with a password.
- **USER**: Register a new user.
- **JOIN**: Join a channel.
- **PART**: Leave a channel.
- **INVITE**: Invite a user to a channel.
- **KICK**: Kick a user from a channel.
- **MODE**: Change channel modes or user modes.
- **PING**: Check the connection with the server.
- **PRIVMSG**: Send a private message to a user or a channel.
- **QUIT**: Disconnect from the server.
- **TOPIC**: Change or view the topic of a channel.

## License

This project is licensed under the MIT License

## Project Crawling

PROJECT_NAME : ft_irc_t
PROJECT_DESCRIPTION : An IRC (Internet Relay Chat) server implemented in C++. The project aims to provide a deeper understanding of network programming and the IRC protocol by supporting basic IRC commands and handling multiple clients simultaneously.
PROJECT_URL : 'https://github.com/Tyranno-Rex/ft_irc_t.git'
PROJECT_COMPLETION_STATUS : TRUE
PROJECT_MULTI : FALSE
PROJECT_SUBPROJECT : NONE
PROJECT_CATEGORY : 'network', 'implement', 'teamTask'
PROJECT_NOTION : 'https://www.notion.so/ft_irc-4e5f19a48e02440380c8795c9cb18a04?pvs=4'
