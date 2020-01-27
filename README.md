Site d'entrainement à domicile et en salle

RECUPERATION :

1 - git clone https://github.com/Benji-devw/findacoach.git

2 - cd findacoach

3 - git checkout dev

4 - composer install

4bis - composer require symfony/swiftmailer-bundle

4.2 bis - composer require tattali/calendar-bundle

5 - composer require vich/uploader-bundle

5bis - composer require stripe/stripe-php

5bisbis - php bin/console doctrine:database:create

6 - php bin/console make:migration

7 - php bin/console doctrine:migrations:migrate

ENVOI :

1 - checkout sur la branch a envoyer (ne pas merge !!!)

2 - git remote add https://github.com/Benji-devw/findacoach.git

3 - git push -u origin

La branch que tu as développé est sur gitHub MERCI !!!