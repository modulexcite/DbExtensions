SqlTable&lt;TEntity>.Find Method
================================
Gets the entity whose primary key matches the *id* parameter.

**Namespace:** [DbExtensions][1]  
**Assembly:** DbExtensions (in DbExtensions.dll)

Syntax
------

```csharp
public TEntity Find(
	Object id
)
```

### Parameters

#### *id*
Type: [System.Object][2]  
The primary key value.

### Return Value
Type: [TEntity][3]  
 The entity whose primary key matches the *id* parameter, or null if the *id* does not exist. 

See Also
--------
[SqlTable<TEntity> Class][3]  
[DbExtensions Namespace][1]  

[1]: ../README.md
[2]: http://msdn.microsoft.com/en-us/library/e5kfa45b
[3]: README.md