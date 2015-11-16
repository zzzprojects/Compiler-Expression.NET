## Code Analysis and Code Compiler for ZZZ Projects Library

This library is used in almost all ZZZ Projects to dynamically compile code at runtime using expression tree.
- [Eval Expression.NET](http://eval-expression.net/)
- [Eval SQL.NET](http://eval-sql.net/)

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

## Support
Contact our outstanding customer support for any request. We usually answer within the next business day, hour, or minutes!

- [Website](http://compiler-expression.net/)
- [Documentation](https://github.com/zzzprojects/Compiler-Expression.NET/wiki)
- sales@zzzprojects.com

## More Projects
  - [NET Entity Framework Extensions](http://www.zzzprojects.com/products/dotnet-development/entity-framework-extensions/)
  - [NET Bulk Operations](http://www.zzzprojects.com/products/dotnet-development/bulk-operations/)
  - [Eval Expression.NET](http://eval-expression.net/)
  - [Eval SQL.NET](http://eval-sql.net/)
