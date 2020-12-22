# windows terminal settings

Backup / shared windows terminal settings.

## Installation

### Dependencies

Requires patched nerd font to be installed in Windows.

-[Roboto Mono Nerd Font](https://github.com/ryanoasis/nerd-fonts/releases)

### Todo

### Commands

Run the following commands as administrator in a command prompt.

```shell
cd C:\stuff

git clone git@github.com:dsnn/windows-terminal-settings.git

cd C:\Users\dsn\AppData\Local\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\

copy settings.json settings.json.bak
del settings.json
mklink /H settings.json C:\stuff\windows-terminal-settings\settings.json
```
