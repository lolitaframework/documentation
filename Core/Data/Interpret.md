\MyProject\LolitaFramework\Core\Data::Interpret
===

Interpret data to value

Example usage
---
```php

echo Data::interpret('i`am value');

// i`am value

```

```php

echo Data::interpret(function() { return 5*5; });

// 25

```

```php

function someFunc() {
	return 'Some function';
}

echo Data::interpret('someFunc');

// Some function

```

```php

define('SOME_CONSTANT', 'some constant value');

echo Data::interpret('{{ SOME_CONSTANT }}');

// some constant value

```

```php

class SomeClass
{
	public static function someFunc()
	{
		return 'function from class';
	}
}

echo Data::interpret('{{ SomeClass::someFunc }}');

// function from class

```

Parameters
---

_mixed_  __$value__

Return Value
---
__mixed__
