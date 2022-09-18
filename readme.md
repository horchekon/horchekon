```php
<?php

// NameSpace
namespace PishvaVeisi;

// AboutMe
class About extends Me {
    public function getDailyKnowledge(): array {
        return [
            CFam::class, // CFamily
            Python::class,
            Php::class,
            Bash::class,
            Javascript::class
        ];
    }
    // FutureGoal
    public function getFutureGoal(): string {
        return "MetaMan";
    }
}
```
