### WINLESS 

An Application for LS at Windows

* Show all files by one command `ls`
* Without arguments ~~-a~~ ~~-l~~
* Build with GO
  
| Release version    | Version Number |
| ----------- | ----------- |
| *Alfa*      | *0*.1       |

### How to install

1) Open CMD at the *__application folder__*

2) Put this script to CMD
```powershell
copy .\ls.exe %homepath%
SET path=C:%homepath%\ls.exe;%path%
```

3) **CMD => Always run as Administrator**
4) All ready to go!