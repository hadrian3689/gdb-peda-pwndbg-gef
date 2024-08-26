# Pwndbg + GEF + Peda - One for all, and all for one

This is a script which installs Pwndbg, GEF, and Peda GDB plugins in a single command.


## Installation

```
git clone https://github.com/apogiatzis/gdb-peda-pwndbg-gef.git
cd gdb-peda-pwndbg-gef
./install.sh
```

Then use one of the commands below to launch the corresponding GDB environment:

```
gdb-peda
gdb-peda-intel
gdb-peda-arm
gdb-pwndbg
gdb-gef
```

## Pwndbg
If `gdb-pwndbg` fails to run then just follow the install instructions and steps from https://github.com/pwndbg/pwndbg to confirm the required Python version for pwndbg. You ma have to install that specific version along with the venv environment using `apt install python<version>-venv -y`

## Update

```
./update.sh
```
