# How to enable named pipe in SQL Server Configuration Manager window?
> [!NOTE]
> Sorry.
>
> I can't screenshot when SQL Server Configuration Manager window is focused.

1. open SQL Server Configuration Manager window (stated in [How to open Microsoft SQL Server Configuration Manager window?](https://github.com/4.0843245/Microsoft-SQL-Server-Configuration-Manager/blob/main/How%20to/How%20to%20open%20Microsoft%20SQL%20Server%20Configuration%20Manager%20window%3F.md)

2. select `SQL Server Management (local machine)` -> `SQL Server Network Configuration` at console pane (at left).
3. click `protocol of MSSQLSERVER configuration`.
4. select and right click `named pipe`.
5. select `enabled` option.

For enabling other pipes, and disable them, it also can be done in SQL Server Configuration Manager window using similar way.

6. restart the MSSQL Server to make the change take effect.
   
## demo
see [How to enable named pipe in SQL Configuration Manager?](https://youtu.be/WjmDP81Rzrw)

## reference
+ [Enable or disable a server network protocol](https://learn.microsoft.com/en-us/sql/database-engine/configure-windows/enable-or-disable-a-server-network-protocol?view=sql-server-ver16)
