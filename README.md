




```php
<?php

namespace Yuki2811;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'MinhHoangJSC',
                'position' => 'Web Developer'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            Vuejs::class,
            MySql::class,
        ];
    }

    public function getHobby(): array
    {
        return [
            Novel::class,
            Gundam::class,
            GamePC::class,
            GamePS::class,
            Piano::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
```
