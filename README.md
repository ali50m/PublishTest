# publish artifact with no pdb files

reproduce with:
```pwsh
dotnet publish .\src\ConsoleUi\
Get-ChildItem -Path .\src\ConsoleUi\bin\Release\net10.0\publish -File
```

![alt text](image.png)