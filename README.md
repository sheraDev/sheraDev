![header](https://capsule-render.vercel.app/api?type=waving&color=auto&height=220&section=header&text=Shera&fontSize=60&animation=fadeIn&fontAlignY=38&desc=Fullstack%20web%20Development%20%2F%20Software%20development&descAlignY=51&descAlign=62)

```php
class Profile {

    private $info = "Fullstack web dev, software Dev";

    private $technos = [
        # Prog langages
        "PHP", "C++", "HTML/CSS/JS", "Bash",

        # Others (Framework, libraries)
        "Bootstrap", "SweetAlert",

        # Database
        "MariaDB", "MySQL"
    ];

    public function __construct($info,  $langs, $techs) {
        $this -> technos = $technos;
        $this -> info = $info;
    }

}
```
