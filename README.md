# publish artifact with no pdb files

Reproduce:
```pwsh
dotnet publish .\src\ConsoleUi\
Get-ChildItem -Path .\src\ConsoleUi\bin\Release\net10.0\publish -File
```

Environment:  
dotnet SDK: 10.0.100  
OS: Win10 21H2 19044.6575  

![alt text](image.png)