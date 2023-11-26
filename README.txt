<div align="center"><br><br>
        <h1> Symfony 6 🔝</h1><br><br>
</div>




Je crée un nouveau projet symfony mise en place de mon environnement :

-   J'installe symfony : symfony new my_project_directory --version="6.3.*" --webapp


<div align="center">________________________________________________________________________________<br><br>
        <h2>🪛 La base de donnée </h2><br><br>
</div>


                            

-   mise en place de la base de donnée dans le .env
-   installation de ORM : composer require symfony/orm-pack
-   installation de doctrine : composer require --dev symfony/maker-bundle

Inscription de la base de donnée sur MYSQL : 

-   php bin/console doctrine:database:create

[ La base de donnée à été crée ]

<div align="center">________________________________________________________________________________<br><br>

                                   <h2>🪛 USER</h2><br><br>

</div>

Crée l'entity USER : 

-   php bin/console make:user
-   php bin/console make:migration
-   php bin/console doctrine:migrations:migrate

Crée une connexion login : 

-   symfony console make:auth

Crée l'enregistrement :

-   symfony console make:registration-form

-   je rajoute : use Symfony\Component\Form\Extension\Core\Type\RepeatedType;
-   je modifie le formulaire : ->add('plainPassword', RepeatedType::class,...etc)

Crée un controller :

-   symfony console make:controller

    page home crée


________________________________________________________________________________

                            Configuration


-   AuthLoginControllerAuthenticator je modifie ligne 52 la redirection login.



________________________________________________________________________________

                            Dashboard Admin

- installation du bundle : composer require easycorp/easyadmin-bundle
- création du controller : php bin/console make:admin:dashboard

- Dans routes.yaml : 
    
    dashboard:
    path: /admin
    controller: App\Controller\Admin\DashboardController::index

- crée la vue twig : {% extends '@EasyAdmin/page/content.html.twig' %}







[![linkedin](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/michael-barreca/)
[![email](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Michael-73@live.fr)
[![Behance](https://img.shields.io/badge/Behance-1769ff?style=for-the-badge&logo=behance&logoColor=white)](https://www.behance.net/michaelbarreca)

<br><br>
<div align="center">
        <a href="https://indd.adobe.com/view/8f0b9f6d-40d1-41de-907b-56aa818c2112"><img src="img/3455025.png"></a><p>Michaël curriculum vitae</p><br>
        <h2>🚀 Welcome to my space 🚀</h2>
        </div><br><br>

<div>


<div align="center">
        <img src="img/giphy.gif">
</div>


<div align="center"><br><br>
        <h2>📲 Mobile Frameworks 🔝</h2><br><br>

<img src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
<img src="https://img.shields.io/badge/Flutter-3880FF?style=for-the-badge&logo=flutter&logoColor=3880FF" />
        
</div>


<div align="center"><br><br>
        <h2>💻 Programming 🔝</h2><br><br>

<img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E" />
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
<img src="https://img.shields.io/badge/Redux-593D88?style=for-the-badge&logo=redux&logoColor=white" />
<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
<img src="https://img.shields.io/badge/firebase-ffca28?style=for-the-badge&logo=firebase&logoColor=black" />
<img src="https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white" />
<img src="https://img.shields.io/badge/Symfony-000000?style=for-the-badge&logo=Symfony&logoColor=white" />
<img src="https://img.shields.io/badge/Electron-2B2E3A?style=for-the-badge&logo=electron&logoColor=9FEAF9" />
</div>

<div align="center"><br><br>
        <h2>👨‍🎨 Customing 🔝</h2><br><br>
        
<img src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white" />
<img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
<img src="https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white" />
</div>

<div align="center"><br><br>
        <h2>✍🏼 Design 🔝</h2><br><br>
        

<img src="https://img.shields.io/badge/Adobe%20XD-470137?style=for-the-badge&logo=Adobe%20XD&logoColor=#FF61F6" />
<img src="https://img.shields.io/badge/Adobe%20Illustrator-FF9A00?style=for-the-badge&logo=adobe%20illustrator&logoColor=white" />
<img src="https://img.shields.io/badge/Adobe%20InDesign-FF3366?style=for-the-badge&logo=Adobe%20InDesign&logoColor=white" />
<img src="https://img.shields.io/badge/Adobe%20Photoshop-31A8FF?style=for-the-badge&logo=Adobe%20Photoshop&logoColor=black" />


</div>


<div align="center"><br><br>
        <h2>🪛 The tools 🔝</h2><br><br>



<img src="https://img.shields.io/badge/Dribbble-EA4C89?style=for-the-badge&logo=dribbble&logoColor=white" />
<img src="https://img.shields.io/badge/Trello-0052CC?style=for-the-badge&logo=trello&logoColor=white" />
<img src="https://img.shields.io/badge/Miro-F7C922?style=for-the-badge&logo=Miro&logoColor=050036" />
<img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=white" />
<img src="https://img.shields.io/badge/Laragon-0E83CD?style=for-the-badge&logo=Laragon&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Unsplash-000000?style=for-the-badge&logo=Unsplash&logoColor=white" />
</div>


