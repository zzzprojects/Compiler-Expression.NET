## Code Analysis and Code Compiler for ZZZ Projects Library

### Eval Expression.NET
**Evaluate, Compile and Execute C# code and expression at runtime**
```csharp
int result = Eval.Execute<int>("X + Y", new { X = 1, Y = 2});
```

### Eval SQL.NET
**Evaluate C# code and expression in T-SQL stored procedure, function and trigger**
```sql
CREATE PROCEDURE [dbo].[select_formula]
AS
BEGIN
	SELECT  SQLNET::New('X + Y')
		.Val('X', ColumnValueX)
		.Val('Y', ColumnValueY)
		.Eval()
	FROM TableFormula
END
```

## Download
<a href="https://www.nuget.org/packages/Z.Expressions.Compiler/" target="_blank" alt="download nuget"><img src="https://img.shields.io/nuget/v/Z.Expressions.Compiler.svg?style=flat-square" /></a>
<a href="https://www.nuget.org/packages/Z.Expressions.Compiler/" target="_blank" alt="download nuget"><img src="https://img.shields.io/nuget/dt/Z.Expressions.Compiler.svg?style=flat-square" /></a>

```
PM> Install-Package Z.Expressions.Compiler
```
*FREE Version - up to 50 characters

## FREE vs PRO
With the free version comes a month long trial of the pro license to let you evaluate all its functonalities without limits.

Features | FREE Version | [PRO Version](http://eval-sql.net/#pro)
------------ | :-------------: | :-------------:
Maximum Characters | 50 | Unlimited
Commercial License | No | Yes
Royalty-Free | No | Yes
Support & Upgrades (1 year) | No | Yes
Learn more about the **[PRO Version](http://eval-sql.net/#pro)**

## Support
Contact our outstanding customer support for any request. We usually answer within the next business day, hour, or minutes!

- [Website](http://eval-sql.net/)
- [Documentation](https://github.com/zzzprojects/Eval-SQL.NET/wiki)
- [Forum](http://zzzprojects.uservoice.com/forums/328452-eval-sql-net)
- sales@zzzprojects.com

## More Projects
  - [NET Entity Framework Extensions](http://www.zzzprojects.com/products/dotnet-development/entity-framework-extensions/)
  - [NET Bulk Operations](http://www.zzzprojects.com/products/dotnet-development/bulk-operations/)
  - [Eval Expression.NET](http://eval-expression.net/)
  - [Eval SQL.NET](http://eval-sql.net/)
