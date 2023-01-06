# itsmyposh-posh-theme

![mytheme](https://user-images.githubusercontent.com/69795132/197924820-32527b6a-8551-4349-bcd0-a34e1f0cfedb.png)

I use font JetBrains Mono https://www.nerdfonts.com/font-downloads

# How To Use Windows

<a href="https://ohmyposh.dev/docs/installation/windows" target="_blank">Oh My Posh</a>

#### 1. Install Oh My Posh 
```
winget install JanDeDobbeleer.OhMyPosh -s winget
```

#### 2. Install (itsmyposh.omp.json) File In Folder 🔽
```pws
~/AppData\Local\Programs\oh-my-posh\themes\
```

#### 3. Open file in a text editor such as notepad or vscode
```
notepad $PROFILE
```
```
code $PROFILE
```

#### 4. Write this command in file
```pws
oh-my-posh init pwsh --config ~/AppData\Local\Programs\oh-my-posh\themes\itsmyposh.omp.json | Invoke-Expression
```



