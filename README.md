# C# Code Analysis and Code Compiler for Eval-Expression.NET and Eval-SQL.NET
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

<a href="https://www.nuget.org/packages/Z.Expressions.Compiler/" target="_blank"><img src="http://entityframework-plus.net/images/nuget/compiler-expression-net-v.svg" alt="download" /></a>
<a href="https://www.nuget.org/packages/Z.Expressions.Compiler/" target="_blank"><img src="http://entityframework-plus.net/images/nuget/compiler-expression-net-d.svg" alt="" /></a>

```
PM> Install-Package Z.Expressions.Compiler
```

*FREE Version - up to 50 characters

Stay updated with latest changes

<a href="https://twitter.com/zzzprojects" target="_blank"><img src="http://www.zzzprojects.com/images/twitter_follow.png" alt="Twitter Follow" height="24" /></a>
<a href="https://www.facebook.com/zzzprojects/" target="_blank"><img src="http://www.zzzprojects.com/images/facebook_like.png" alt="Facebook Like" height="24" /></a>

## Contribute
The best way to contribute is by **spreading the word** about the library:

 - Blog it
 - Comment it
 - Fork it
 - Star it
 - Share it
 
A **HUGE THANKS** for your help.

## More Projects

**Entity Framework**
- [EntityFramework Extensions](http://entityframework-extensions.net/)
- [EntityFramework Plus](http://entityframework-plus.net)

**Bulk Operations**
- [Bulk Operations](http://bulk-operations.net/)
- [Dapper Plus](http://dapper-plus.net/)

**Expression Evaluator**
- [Eval-SQL.NET](http://eval-sql.net/)
- [Eval-Expression.NET](http://eval-expression.net/)

**Others**
- [Extension Methods Library](https://github.com/zzzprojects/Z.ExtensionMethods/)
- [LINQ Async](https://github.com/zzzprojects/Linq-AsyncExtensions)

**Need more info?** info@zzzprojects.com

Contact our outstanding customer support for any request. We usually answer within the next business day, hour, or minutes!
