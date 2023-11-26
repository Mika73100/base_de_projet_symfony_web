<<<<<<< HEAD
<div align="center"><img src="https://img.shields.io/badge/Symfony-000000?style=for-the-badge&logo=Symfony&logoColor=white" /><br><br>
        <h1> Symfony 6 🔝</h1><br><br>
</div>
=======

        Symfony 6 🔝

>>>>>>> 0d34dd00de3b21522f73e92f08c428f83467c565




Je crée un nouveau projet symfony mise en place de mon environnement :

-   J'installe symfony : symfony new my_project_directory --version="6.3.*" --webapp


________________________________________________________________________________
                        🪛 La base de donnée



<div align="center">________________________________________________________________________________<br><br>
        <h2>🪛 La base de donnée </h2><br><br>
</div>


                            
                            

-   mise en place de la base de donnée dans le .env
-   installation de ORM : composer require symfony/orm-pack
-   installation de doctrine : composer require --dev symfony/maker-bundle

Inscription de la base de donnée sur MYSQL : 

-   php bin/console doctrine:database:create

[ La base de donnée à été crée ]

________________________________________________________________________________

                                   🪛 USER

<<<<<<< HEAD
                                   <h2>🪛 USER</h2><br><br>
<div align="center">________________________________________________________________________________<br><br>

                                   <h2>🪛 USER</h2><br><br>

</div>
</div>
=======

>>>>>>> 0d34dd00de3b21522f73e92f08c428f83467c565

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

                             🪛 Configuration


-   AuthLoginControllerAuthenticator je modifie ligne 52 la redirection login.



________________________________________________________________________________

                             🪛 Dashboard Admin

- installation du bundle : composer require easycorp/easyadmin-bundle
- création du controller : php bin/console make:admin:dashboard

- Dans routes.yaml : 
    
    dashboard:
    path: /admin
    controller: App\Controller\Admin\DashboardController::index

<<<<<<< HEAD
- crée la vue twig : {% extends '@EasyAdmin/page/content.html.twig' %}
=======
- crée la vue twig : {% extends '@EasyAdmin/page/content.html.twig' %}


>>>>>>> 0d34dd00de3b21522f73e92f08c428f83467c565
