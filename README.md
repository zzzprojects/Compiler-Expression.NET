## Code Analysis and Code Compiler for ZZZ Projects Library
This library is used in almost all ZZZ Projects to dynamically compile code at runtime using expression tree.
- [Eval Expression.NET](http://eval-expression.net/)
- [Eval SQL.NET](http://eval-sql.net/)


### Eval Expression.NET
**Evaluate, Compile and Execute C# code and expression at runtime.**
```csharp
int result = Eval.Execute<int>("X + Y", new { X = 1, Y = 2});
```

**[Learn more](https://github.com/zzzprojects/Eval-Expression.NET)**

### Eval SQL.NET
**Evaluate C# code and expression in T-SQL stored procedure, function and trigger.**
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

**[Learn more](https://github.com/zzzprojects/Eval-SQL.NET)**

## Download
> This library is not intended to be directy used, if you want to evaluate expression, see [Eval Expression.NET](http://eval-expression.net/) instead.

<a href="https://www.nuget.org/packages/Z.Expressions.Compiler/" target="_blank" alt="download nuget"><img src="https://img.shields.io/nuget/v/Z.Expressions.Compiler.svg?style=flat-square" /></a>
<a href="https://www.nuget.org/packages/Z.Expressions.Compiler/" target="_blank" alt="download nuget"><img src="https://img.shields.io/nuget/dt/Z.Expressions.Compiler.svg?style=flat-square" /></a>

```
PM> Install-Package Z.Expressions.Compiler
```
*FREE Version - up to 50 characters

## Contributing
_You received support from us and/or the FREE version helped you?_

Contribute to keep us developing FREE features and to thank us for our support.

We'll never require donations, but we appreciate them greatly

<a href="http://www.zzzprojects.com/contribute/" target="_blank"><img src="http://www.zzzprojects.com/images/paypal-contribute.png" alt="Contribute" height="48"></a>

A **huge thanks** for your extra support.

## More Projects

**Entity Framework**
- [Entity Framework Extensions](http://www.zzzprojects.com/products/dotnet-development/entity-framework-extensions/)
- [Entity Framework Plus](https://github.com/zzzprojects/EntityFramework-Plus)

**Bulk Operations**
- [NET Entity Framework Extensions](http://www.zzzprojects.com/products/dotnet-development/entity-framework-extensions/)
- [NET Bulk Operations](http://www.zzzprojects.com/products/dotnet-development/bulk-operations/)

**Expression Evaluator**
- [Eval SQL.NET](https://github.com/zzzprojects/Eval-SQL.NET)
- [Eval Expression.NET](https://github.com/zzzprojects/Eval-Expression.NET)

**Others**
- [Extension Methods Library](https://github.com/zzzprojects/Z.ExtensionMethods/)
- [LINQ Async](https://github.com/zzzprojects/Linq-AsyncExtensions)

**Need more info?** info@zzzprojects.com

Contact our outstanding customer support for any request. We usually answer within the next business day, hour, or minutes!
