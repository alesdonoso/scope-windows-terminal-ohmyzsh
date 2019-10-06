# scope-windows-terminal-ohmyzsh
The brand colors of Scope.ink for the new Windows Terminal with Oh My Zsh plugin

# 1. Install the new Microsoft (Windows) Terminal

You can install it from the Microsoft Store:
>https://www.microsoft.com/en-us/p/windows-terminal-preview/9n0dx20hk701

or from the GitHub repository:

>https://github.com/microsoft/terminal

# 2. Later, you must enable Windows Subsystem for Linux (WSL)

You can do it following these steps:

>https://docs.microsoft.com/en-us/windows/wsl/install-win10

# 3. Download Ubuntu for Windows

Do it directly from the Microsoft Store:

> https://www.microsoft.com/en-us/p/ubuntu/9nblggh4msv6

# 4. Setup your Microsoft Terminal with Ubuntu

```json
{
            "acrylicOpacity" : 0.5,
            "closeOnExit" : true,
            "colorScheme" : "Scope",
            "commandline" : "wsl.exe -d Ubuntu",
            "cursorColor" : "#39e5a7",
            "cursorShape" : "bar",
            "fontFace" : "Cascadia Code",
            "fontSize" : 12,
            "guid" : "{`your guid by default`}",
            "historySize" : 9001,
            "icon" : "`insert the url of your prefered icon`",
            "name" : "WSL",
            "padding" : "10, 10, 10, 10",
            "snapOnInput" : true,
            "startingDirectory" : "`insert your default folder (Dev, maybe?)`",
            "useAcrylic" : false
        }
```

As you can see, the name of the *colorScheme* is Scope, since we are going to use this scheme.

# 5. Install Oh My Zsh plugin

Do it directly following the GitHub repository documentation:

> https://github.com/robbyrussell/oh-my-zsh

# 6. Last step: insert the Scope colorScheme

```json

{
            "background" : "#0d0d24",
            "black" : "#000000",
            "blue" : "#0d0d38",
            "brightBlack" : "#767676",
            "brightBlue" : "#00e0ff",
            "brightCyan" : "#ffd48a",
            "brightGreen" : "#39e5a7",
            "brightPurple" : "#b4009e",
            "brightRed" : "#fa547a",
            "brightWhite" : "#ffffff",
            "brightYellow" : "#ffd48a",
            "cyan" : "#3a96dd",
            "foreground" : "#ffffff",
            "green" : "#bff7e9",
            "name" : "Scope",
            "purple" : "#881798",
            "red" : "#fa547a",
            "white" : "#39e5a7",
            "yellow" : "#ffd48a"
        },
   ```
   
   ## There you go! 🚀
   
   
![Scope Color Scheme](https://user-images.githubusercontent.com/48650098/66275820-b1595d00-e88c-11e9-983b-8aea6c498083.png)

#### Thanks so much!
You can find me on Twitter:
```@alesdonoso```
