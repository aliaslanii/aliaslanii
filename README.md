<h2> Hi, I'm Ali Aslani 😎</h2>

[![Linkedin: ali-aslani](https://img.shields.io/badge/-thaianebraga-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/ali-naserian/)](https://www.linkedin.com/in/ali-aslani-39352b248/)
[![GitHub Thaiane](https://img.shields.io/github/followers/naserianali?label=follow&style=social)](https://github.com/aliaslanii)


<p align="center"> 
  📫 Reach me at <a href="mailto:naserianali@gmail.com">naserianali@gmail.com</a> 
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
      <img height=200 align="left" src="https://github-readme-stats.vercel.app/api/top-langs/?username=aliaslnii&hide=c%23,powershell,Mathematica,Ruby,Objective-C,Objective-C%2b%2b,Cuda&title_color=61dafb&text_color=ffffff&icon_color=61dafb&bg_color=20232a&langs_count=8&layout=compact&border_color=61dafb&hide_border=true&size_weight=0.5&count_weight=5" />
    </a>
  </div>
