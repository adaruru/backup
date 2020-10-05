```
[environment]::setEnvironmentVariable('SCOOP','D:\Program Files\scoop\apps\scoop','User')
$env:SCOOP='D:\Program Files\scoop\apps\scoop'
iex (new-object net.webclient).downloadstring('https://get.scoop.sh')
```

C:\Users\Ruru\scoop\apps\scoop