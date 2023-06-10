# PHP Laravel Example - Dom PDF Report

[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://www.codehafeez.com/)

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/codehafeez/)

[![whatsapp](https://img.shields.io/badge/whatsapp-GREEN?style=for-the-badge&logo=whatsapp&logoColor=white)](https://api.whatsapp.com/send?phone=923123349398)



```bash
CMD => composer create-project --prefer-dist laravel/laravel blog

CMD => cd blog

CMD => composer require barryvdh/laravel-dompdf


following path: config/app.php
    'providers' => [
        ....
        Barryvdh\DomPDF\ServiceProvider::class,
    ],
    
    'aliases' => [
        ....
        'PDF' => Barryvdh\DomPDF\Facade::class,
    ]


CMD => php artisan make:controller PdfController

CMD => php artisan serve
```    


## Screenshots
![](https://raw.githubusercontent.com/codehafeez/Laravel-DomPDF/main/Screenshots/Output.png)


## 🔗 www.codehafeez.com
