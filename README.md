# RabbitMQ

# Installation

## Windows
-

## Macos
### The Homebrew RabbitMQ Formula

**Installation**
Before installing make sure the taps are up-to-date:

brew **update**
Then, install RabbitMQ server with:
```bash
brew update
```

brew **install** rabbitmq
Installing the RabbitMQ formula will install key dependencies such as a supported Erlang/OTP version.
```bash
brew install rabbitmq
```

Operations
The RabbitMQ server scripts and CLI tools are installed in sbin directory under /usr/local/Cellar/rabbitmq, which is accessible via /usr/local/opt/rabbitmq/sbin. In case that directory is not in PATH it's recommend to append it:

```bash
export PATH=$PATH:/usr/local/opt/rabbitmq/sbin
```
The server can then be started with rabbitmq-server. With Homebrew the node and CLI tools will use the logged in user account by default. Using sudo is not required.

Otherwise operations are no different from the generic binary build. Please refer to the Operations section of the generic binary build guide section.

# Usage
-

## ✨ Contributors
| [<img src="https://avatars0.githubusercontent.com/u/33685760?v=3" width="100px;"/><br /><sub>Murat Mayadağ</sub>](https://github.com/mmayadag)<br /> 💻 :pencil: | + New padawan | + New jedi |
| :---: | :---: | :---: |
