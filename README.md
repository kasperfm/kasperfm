
```php
<?php

namespace KasperFM;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Modified Solutions',
                'position' => 'Backend web developer',
                'location' => 'Denmark'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Laravel::class,
            Vuejs::class,
            Javascript::class,
            TailwindCss::class,
            Linux::class,
            GameDev::class,
        ];
    }

    public function getFutureGoals(): string
    {
        return 'To contribute to open source, and learn new things.';
    }
}
```
