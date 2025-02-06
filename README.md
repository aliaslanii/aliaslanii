<h2> Hi, I'm Ali Aslani 😎</h2>


[![PHP](https://img.shields.io/badge/-PHP-777BB4?style=flat-square&logo=php&logoColor=white)](https://github.com/aliaslanii)
[![Laravel](https://img.shields.io/badge/-Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)](https://github.com/aliaslanii)
[![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://github.com/aliaslanii)


<p align="center">

  [![LinkedIn](https://img.shields.io/badge/-Ali%20Aslani-blue?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ali-aslani-39352b248/)
  [![Email](https://img.shields.io/badge/-aliaslani1727@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:aliaslani1727@gmail.com)
  
</p>



```php
<?php

class Developer
{
    public string $name;
    public array $askMeAbout;
    public array $technologies;

    public function __construct($name, $askMeAbout, $technologies)
    {
        $this->name = $name;
        $this->askMeAbout = $askMeAbout;
        $this->technologies = $technologies;
    }

    public function getProfile()
    {
        return [
            "name" => $this->name,
            "askMeAbout" => $this->askMeAbout,
            "technologies" => $this->technologies,
        ];
    }
}

$aliAslani = new Developer(
    "Ali Aslani",
    ["Web", "Backend", "API"],
    [
        "backEnd" => [
            "php" => ["Laravel", "Livewire"],
        ],
        "databases" => ["SQLite", "MySQL"],
        "misc" => ["JavaScript", "Python", "Django"],
    ]
);

print_r($aliAslani->getProfile());

```
  <div>
    <a href="https://github.com/aliaslnii">
      <img height=200 align="left" src="https://github-readme-stats.vercel.app/api/top-langs/?username=aliaslanii&hide=c%23,powershell,Mathematica,Ruby,Objective-C,Objective-C%2b%2b,Cuda&title_color=61dafb&text_color=ffffff&icon_color=61dafb&bg_color=20232a&langs_count=8&layout=compact&border_color=61dafb&hide_border=true&size_weight=0.5&count_weight=10" />
    </a>
  </div>  <div>
    <a href="https://github.com/aliaslnii">
      <img height=200 align="left" src="https://github-readme-stats.vercel.app/api/top-langs/?username=aliaslanii&hide=c%23,powershell,Mathematica,Ruby,Objective-C,Objective-C%2b%2b,Cuda&title_color=61dafb&text_color=ffffff&icon_color=61dafb&bg_color=20232a&langs_count=8&layout=compact&border_color=61dafb&hide_border=true&size_weight=0.5&count_weight=10" />
    </a>
  </div>
