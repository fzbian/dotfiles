# dotfiles
the customization i use on my computer

## install [oh-my-posh](https://ohmyposh.dev/docs/installation/windows)
i need [scoop](https://scoop.sh/) on my computer to execute the command
`scoop install https://github.com/JanDeDobbeleer/oh-my-posh/releases/latest/download/oh-my-posh.json`

## Microsoft.PowerShell_profile.ps1
```
clear
oh-my-posh init pwsh --config '${path-omp}\oh-my-posh\themes\ys.omp.json' | Invoke-Expression
Import-Module -Name Terminal-Icons
```

## Windows Terminal config
```json
"profiles": 
  {
    "defaults": 
      {
        "colorScheme": "Gruvbox Dark",
        "font": 
        {
          "face": "Hack Nerd Font Mono",
          "size": 14.0
        },
        "opacity": 90,
        "useAcrylic": true
  },
"schemes":
[
  {
    "background" : "#282828",
    "black" : "#282828",
    "blue" : "#458588",
    "brightBlack" : "#928374",
    "brightBlue" : "#83A598",
    "brightCyan" : "#8EC07C",
    "brightGreen" : "#B8BB26",
    "brightPurple" : "#D3869B",
    "brightRed" : "#FB4934",
    "brightWhite" : "#EBDBB2",
    "brightYellow" : "#FABD2F",
    "cyan" : "#689D6A",
    "foreground" : "#EBDBB2",
    "green" : "#98971A",
    "name" : "Gruvbox Dark",
    "purple" : "#B16286",
    "red" : "#CC241D",
    "white" : "#A89984",
    "yellow" : "#D79921"
  }
]

```
