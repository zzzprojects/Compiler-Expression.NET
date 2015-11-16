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
