# scope-windows-terminal-ohmyzsh
The brand colors of Scope.ink for the new Windows Terminal with Oh My Zsh plugin

![Scope Color Scheme](https://user-images.githubusercontent.com/48650098/66275820-b1595d00-e88c-11e9-983b-8aea6c498083.png)

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

## Here I leave all my config. I normally just use WSL, but you can turn out to bash, Azure, PowerShell, and etc.

```json
{
    "$schema": "https://aka.ms/terminal-profiles-schema",
    "globals" : 
    {
        "alwaysShowTabs" : true,
        "defaultProfile" : "{2c4de342-38b7-51cf-b940-2309a097f518}",
        "initialCols" : 120,
        "initialRows" : 30,
        "keybindings" : 
        [
            {
                "command" : "closePane",
                "keys" : 
                [
                    "ctrl+w"
                ]
            },
            {
                "command" : "copy",
                "keys" : 
                [
                    "ctrl+c"
                ]
            },
            {
                "command" : "duplicateTab",
                "keys" : 
                [
                    "ctrl+shift+d"
                ]
            },
            {
                "command" : "newTab",
                "keys" : 
                [
                    "alt+t"
                ]
            },
            {
                "command" : "newTabProfile0",
                "keys" : 
                [
                    "ctrl+shift+1"
                ]
            },
            {
                "command" : "newTabProfile1",
                "keys" : 
                [
                    "ctrl+shift+2"
                ]
            },
            {
                "command" : "newTabProfile2",
                "keys" : 
                [
                    "ctrl+shift+3"
                ]
            },
            {
                "command" : "newTabProfile3",
                "keys" : 
                [
                    "ctrl+shift+4"
                ]
            },
            {
                "command" : "newTabProfile4",
                "keys" : 
                [
                    "ctrl+shift+5"
                ]
            },
            {
                "command" : "newTabProfile5",
                "keys" : 
                [
                    "ctrl+shift+6"
                ]
            },
            {
                "command" : "newTabProfile6",
                "keys" : 
                [
                    "ctrl+shift+7"
                ]
            },
            {
                "command" : "newTabProfile7",
                "keys" : 
                [
                    "ctrl+shift+8"
                ]
            },
            {
                "command" : "newTabProfile8",
                "keys" : 
                [
                    "ctrl+shift+9"
                ]
            },
            {
                "command" : "nextTab",
                "keys" : 
                [
                    "ctrl+tab"
                ]
            },
            {
                "command" : "openSettings",
                "keys" : 
                [
                    "ctrl+,"
                ]
            },
            {
                "command" : "paste",
                "keys" : 
                [
                    "ctrl+v"
                ]
            },
            {
                "command" : "prevTab",
                "keys" : 
                [
                    "ctrl+shift+tab"
                ]
            },
            {
                "command" : "scrollDown",
                "keys" : 
                [
                    "ctrl+shift+down"
                ]
            },
            {
                "command" : "scrollDownPage",
                "keys" : 
                [
                    "ctrl+shift+pgdn"
                ]
            },
            {
                "command" : "scrollUp",
                "keys" : 
                [
                    "ctrl+shift+up"
                ]
            },
            {
                "command" : "scrollUpPage",
                "keys" : 
                [
                    "ctrl+shift+pgup"
                ]
            },
            {
                "command" : "switchToTab0",
                "keys" : 
                [
                    "alt+1"
                ]
            },
            {
                "command" : "switchToTab1",
                "keys" : 
                [
                    "alt+2"
                ]
            },
            {
                "command" : "switchToTab2",
                "keys" : 
                [
                    "alt+3"
                ]
            },
            {
                "command" : "switchToTab3",
                "keys" : 
                [
                    "alt+4"
                ]
            },
            {
                "command" : "switchToTab4",
                "keys" : 
                [
                    "alt+5"
                ]
            },
            {
                "command" : "switchToTab5",
                "keys" : 
                [
                    "alt+6"
                ]
            },
            {
                "command" : "switchToTab6",
                "keys" : 
                [
                    "alt+7"
                ]
            },
            {
                "command" : "switchToTab7",
                "keys" : 
                [
                    "alt+8"
                ]
            },
            {
                "command" : "switchToTab8",
                "keys" : 
                [
                    "alt+9"
                ]
            }
        ],
        "requestedTheme" : "system",
        "showTabsInTitlebar" : true,
        "showTerminalTitleInTitlebar" : true,
        "wordDelimiters" : " ./\\()\"'-:,.;<>~!@#$%^&*|+=[]{}~?\u2502"
    },
    "profiles" : 
    [
        {
            "acrylicOpacity" : 0.5,
            "background" : "#012456",
            "closeOnExit" : true,
            "colorScheme" : "Campbell",
            "commandline" : "powershell.exe",
            "cursorColor" : "#FFFFFF",
            "cursorShape" : "bar",
            "fontFace" : "Consolas",
            "fontSize" : 10,
            "guid" : "{61c54bbd-c2c6-5271-96e7-009a87ff44bf}",
            "historySize" : 9001,
            "icon" : "ms-appx:///ProfileIcons/{61c54bbd-c2c6-5271-96e7-009a87ff44bf}.png",
            "name" : "Windows PowerShell",
            "padding" : "0, 0, 0, 0",
            "snapOnInput" : true,
            "startingDirectory" : "%USERPROFILE%",
            "useAcrylic" : false
        },
        {
            "acrylicOpacity" : 0.75,
            "closeOnExit" : true,
            "colorScheme" : "Campbell",
            "commandline" : "cmd.exe",
            "cursorColor" : "#FFFFFF",
            "cursorShape" : "bar",
            "fontFace" : "Consolas",
            "fontSize" : 10,
            "guid" : "{0caa0dad-35be-5f56-a8ff-afceeeaa6101}",
            "historySize" : 9001,
            "icon" : "ms-appx:///ProfileIcons/{0caa0dad-35be-5f56-a8ff-afceeeaa6101}.png",
            "name" : "cmd",
            "padding" : "0, 0, 0, 0",
            "snapOnInput" : true,
            "startingDirectory" : "%USERPROFILE%",
            "useAcrylic" : true
        },
        {
            "acrylicOpacity" : 0.84999999999999998,
            "closeOnExit" : false,
            "colorScheme" : "Solarized Dark",
            "commandline" : "Azure",
            "connectionType" : "{d9fcfdfa-a479-412c-83b7-c5640e61cd62}",
            "cursorColor" : "#FFFFFF",
            "cursorShape" : "bar",
            "fontFace" : "Consolas",
            "fontSize" : 10,
            "guid" : "{b453ae62-4e3d-5e58-b989-0a998ec441b8}",
            "historySize" : 9001,
            "icon" : "ms-appx:///ProfileIcons/{b453ae62-4e3d-5e58-b989-0a998ec441b8}.png",
            "name" : "Azure Cloud Shell",
            "padding" : "0, 0, 0, 0",
            "snapOnInput" : true,
            "startingDirectory" : "%USERPROFILE%",
            "useAcrylic" : true
        },
        {
            "acrylicOpacity" : 0.5,
            "closeOnExit" : true,
            "colorScheme" : "Scope",
            "commandline" : "wsl.exe -d Ubuntu",
            "cursorColor" : "#39e5a7",
            "cursorShape" : "bar",
            "fontFace" : "Cascadia Code",
            "fontSize" : 12,
            "guid" : "{2c4de342-38b7-51cf-b940-2309a097f518}",
            "historySize" : 9001,
            "icon" : "%USERPROFILE%/Desktop/Scope/Branding/PNG/isotipo_azul.png",
            "name" : "WSL",
            "padding" : "10, 10, 10, 10",
            "snapOnInput" : true,
            "startingDirectory" : "%USERPROFILE%/Desktop/Dev",
            "useAcrylic" : false
        }
    ],
    "schemes" : 
    [
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
        {
            "background" : "#0C0C0C",
            "black" : "#0C0C0C",
            "blue" : "#0037DA",
            "brightBlack" : "#767676",
            "brightBlue" : "#3B78FF",
            "brightCyan" : "#61D6D6",
            "brightGreen" : "#16C60C",
            "brightPurple" : "#B4009E",
            "brightRed" : "#E74856",
            "brightWhite" : "#F2F2F2",
            "brightYellow" : "#F9F1A5",
            "cyan" : "#3A96DD",
            "foreground" : "#CCCCCC",
            "green" : "#13A10E",
            "name" : "Campbell",
            "purple" : "#881798",
            "red" : "#C50F1F",
            "white" : "#CCCCCC",
            "yellow" : "#C19C00"
        },
        {
            "background" : "#000000",
            "black" : "#000000",
            "blue" : "#000080",
            "brightBlack" : "#808080",
            "brightBlue" : "#0000FF",
            "brightCyan" : "#00FFFF",
            "brightGreen" : "#00FF00",
            "brightPurple" : "#FF00FF",
            "brightRed" : "#FF0000",
            "brightWhite" : "#FFFFFF",
            "brightYellow" : "#FFFF00",
            "cyan" : "#008080",
            "foreground" : "#C0C0C0",
            "green" : "#008000",
            "name" : "Vintage",
            "purple" : "#800080",
            "red" : "#800000",
            "white" : "#C0C0C0",
            "yellow" : "#808000"
        },
        {
            "background" : "#282C34",
            "black" : "#282C34",
            "blue" : "#61AFEF",
            "brightBlack" : "#5A6374",
            "brightBlue" : "#61AFEF",
            "brightCyan" : "#56B6C2",
            "brightGreen" : "#98C379",
            "brightPurple" : "#C678DD",
            "brightRed" : "#E06C75",
            "brightWhite" : "#DCDFE4",
            "brightYellow" : "#E5C07B",
            "cyan" : "#56B6C2",
            "foreground" : "#DCDFE4",
            "green" : "#98C379",
            "name" : "One Half Dark",
            "purple" : "#C678DD",
            "red" : "#E06C75",
            "white" : "#DCDFE4",
            "yellow" : "#E5C07B"
        },
        {
            "background" : "#FAFAFA",
            "black" : "#383A42",
            "blue" : "#0184BC",
            "brightBlack" : "#4F525D",
            "brightBlue" : "#61AFEF",
            "brightCyan" : "#56B5C1",
            "brightGreen" : "#98C379",
            "brightPurple" : "#C577DD",
            "brightRed" : "#DF6C75",
            "brightWhite" : "#FFFFFF",
            "brightYellow" : "#E4C07A",
            "cyan" : "#0997B3",
            "foreground" : "#383A42",
            "green" : "#50A14F",
            "name" : "One Half Light",
            "purple" : "#A626A4",
            "red" : "#E45649",
            "white" : "#FAFAFA",
            "yellow" : "#C18301"
        },
        {
            "background" : "#002B36",
            "black" : "#073642",
            "blue" : "#268BD2",
            "brightBlack" : "#002B36",
            "brightBlue" : "#839496",
            "brightCyan" : "#93A1A1",
            "brightGreen" : "#586E75",
            "brightPurple" : "#6C71C4",
            "brightRed" : "#CB4B16",
            "brightWhite" : "#FDF6E3",
            "brightYellow" : "#657B83",
            "cyan" : "#2AA198",
            "foreground" : "#839496",
            "green" : "#859900",
            "name" : "Solarized Dark",
            "purple" : "#D33682",
            "red" : "#DC322F",
            "white" : "#EEE8D5",
            "yellow" : "#B58900"
        },
        {
            "background" : "#FDF6E3",
            "black" : "#073642",
            "blue" : "#268BD2",
            "brightBlack" : "#002B36",
            "brightBlue" : "#839496",
            "brightCyan" : "#93A1A1",
            "brightGreen" : "#586E75",
            "brightPurple" : "#6C71C4",
            "brightRed" : "#CB4B16",
            "brightWhite" : "#FDF6E3",
            "brightYellow" : "#657B83",
            "cyan" : "#2AA198",
            "foreground" : "#657B83",
            "green" : "#859900",
            "name" : "Solarized Light",
            "purple" : "#D33682",
            "red" : "#DC322F",
            "white" : "#EEE8D5",
            "yellow" : "#B58900"
        }
    ]
}
```

#### Thanks so much!
You can find me on Twitter:
```@alesdonoso```
