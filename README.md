# instllation

```bash
$ sudo yum install -y lynx wget curl git nodejs npm redhat-lsb inotify-tools
$ git clone https://github.com/robisonsantos/evm.git
$ cd evm
$ ./install

$ echo 'source /home/sen/.evm/scripts/evm' >> ~/.bashrc
$ source ~/.bashrc
$ evm list
Available Erlang versions on http://www.erlang.org

OTP_18.0
OTP_17.5
OTP_17.4
OTP_17.3
OTP_17.1
OTP_17.0
R16B03

$ evm install OTP_17.5
$ evm use 17.5 default
$ erl
Erlang/OTP 17 [erts-6.4] [source] [64-bit] [smp:2:2] [async-threads:10] [hipe] [kernel-poll:false]

Eshell V6.4  (abort with ^G)

$ cd ../
```

```bash
$ \curl -sSL https://raw.githubusercontent.com/taylor/kiex/master/install | bash -s
$ echo 'test -s "$HOME/.kiex/scripts/kiex" && source "$HOME/.kiex/scripts/kiex"' >> ~/.bashrc
$ source ~/.bashrc
$ kiex list known
$ kiex install 1.0.5
$ kiex use 1.0.5 default
$ iex
Erlang/OTP 17 [erts-6.4] [source] [64-bit] [smp:2:2] [async-threads:10] [hipe] [kernel-poll:false]

Interactive Elixir (1.0.5) - press Ctrl+C to exit (type h( ENTER for help)
iex(1)>)
```
