# Entity Framework - Third Party Libraries

## Introduction

Entity Framework **Third Party Libraries** allow you to extend EF functionality which is not available in the official Entity Framework library, for example, auditing, caching, and filtering etc. 

## Why we need Third Party Libraries?

Entity Framework is great, but a lot of essential features is missing for some application scenarios.

The only way to achieve is either create code for this kind of scenario or use a library which fully or partially cover them.

## Supported Libraries


|Library	|Type	|EF Version	|Support	|Doc	|Features|
|:----------|:----------|:----------|:----------|:----------|:----------|
|[Z.EntityFramework.Extensions](https://github.com/zzzprojects/EntityFramework-Extensions)	|PRO	|EF5<br>EF6<br>EF Core|< 1 Day	|Yes	| Bulk SaveChanges<br>Bulk Insert<br>Bulk Update<br>Bulk Delete<br>Bulk Merge|
|[Z.EntityFramework.Plus](https://github.com/zzzprojects/EntityFramework-Plus)	|FREE	|EF5<br>EF6<br>EF Core|	< 1 Day	|Yes    |Audit<br>Batch Delete<br>Batch Update<br>Cache<br>Deferred Query<br>Filter<br>Future<br>Include Filter<br>Include Optimized|
|[Eval Expression.NET](https://github.com/zzzprojects/Eval-Expression.NET)	|FREE/PRO	|All	|< 1 Day	|Yes	|Dynamic Query|
|[Audit.NET](https://github.com/thepirat000/Audit.NET)	|FREE	|EF6<br>EF Core	|< 1 Day	|Yes    |Audit  |
|[System.Linq.Dynamic](https://github.com/kahanu/System.Linq.Dynamic)	|FREE	|All	|< 1 Day	|Yes    |Dynamic Query  |
|[EntityFramework.Cache](https://github.com/moozzyk/EFCache	|FREE	|EF6	|< 2 Days	|No	    | Cache |
|[EntityFramework.DynamicFilters](https://github.com/zzzprojects/EntityFramework.DynamicFilters)	|FREE	|EF6<br>EF Core	|< 2 Days	|Yes    |Filter |
|[Microsoft.EntityFrameworkCore.AutoHistory](https://github.com/Arch/AutoHistory)	|FREE	|EF Core	|< 1 Day	|No	    | Audit |

## Unsuported Libraries

Use these libraries at your risk!

|Library	|Type	|EF Version	|Support	|Doc	|Features |
|:--------- |:--------- |:--------- |:--------- |:--------- |:--------- |
|[AuditDbContext](https://archive.codeplex.com/?p=auditdbcontext)	|FREE	|EF6	|No |Yes    |Audit  |
|[EntityFrameworkRepository6](https://github.com/davidbreyer/EntityFrameworkRepository6) (!)THIS MAY BE THE WRONG LINK(!)|FREE|EF6|No |No | Audit|
|[EFAuditing](https://github.com/johannbrink/EFAuditing) (!)THIS MAY BE THE WRONG LINK(!)	|FREE	|EF Core	|No	    |No |Audit  |
|[EFUtilities](/ef-utilities) (!)LINK BROKEN(!)	|FREE	|EF5<br>EF6	|No	    |No |Bulk Insert<br>Batch Delete<br>Batch Update<br>Include Optimized<br>
|[EntityFramework.Extended](https://github.com/zzzprojects/EntityFramework.Extended)	|FREE	|EF5<br>EF6	|No	    |Yes    |Audit<br>Batch Delete<br>Batch Update<br>Cache<br>Future|
|[EntityFramework.Filters](https://github.com/jbogard/EntityFramework.Filters)	|FREE	|EF6	|No	    |Yes    |Filter |
|[TrackerEnabledDbContext](https://github.com/bilal-fazlani/tracker-enabled-dbcontext)	|FREE	|EF6	|No	    |Yes	|Audit  |
