<p align="center">
  <img src ="https://github-readme-stats.vercel.app/api?username=yuki2811&show_icons=true&count_private=true&theme=default&hide_border=true&hide=issues,contribs&include_all_commits=true">
  <img src ="https://github-readme-stats.vercel.app/api/top-langs/?username=yuki2811&layout=compact&hide_border=true&langs_count=10&hide=jupyter%20notebook,tex,css,php">
</p>

<!-- <p align="center">
  <img align="left" src ="https://github-readme-stats.vercel.app/api/pin/?username=yuki2811&repo=ytdx">
  <img align="right" src ="https://github-readme-stats.vercel.app/api/pin/?username=yuki2811&repo=pixel-weather">
</p> -->




```php
<?php

namespace AshBaker;

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
