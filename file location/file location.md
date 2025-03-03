# file location
## `UserSettings.xml`
According to bryc3monk3y's answer in Change default login SQL Server Management Studio (SSMS)[^1],

<img width="550" alt="image" src="https://github.com/user-attachments/assets/c0b76c57-14c5-4e06-b4a8-35d0621f08ad" />

`UserSettings.xml` is placed at

```
C:\Users\<userName>\AppData\Roaming\Microsoft\SQL Server Management Studio\<versionNumber>
```

where 

`<userName>` is the user name that download SMMS 

and `<versionNumber>` is the version number.

### example

For example, 

I install SMMS 2019 with `userJay30` account.

Then `UserSettings.xml` will be placed at `C:\Users\userJay30\AppData\Roaming\Microsoft\SQL Server Management Studio\19.0`.

### reference
[Change default login SQL Server Management Studio (SSMS)](https://stackoverflow.com/questions/9427662/change-default-login-sql-server-management-studio-ssms)

[^1]: [Change default login SQL Server Management Studio (SSMS)](https://stackoverflow.com/questions/9427662/change-default-login-sql-server-management-studio-ssms)
