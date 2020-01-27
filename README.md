Site d'entrainement à domicile et en salle

RECUPERATION :

1 - git clone https://github.com/Benji-devw/FindACoach_Phase_1.git

2 - cd FindACoach_Phase_1

3 - composer install

3 bis - composer require symfony/swiftmailer-bundle

3.2 bis - composer require tattali/calendar-bundle

4 - composer require vich/uploader-bundle

4 bis - composer require stripe/stripe-php

4.2 bis - php bin/console doctrine:database:create

5 - php bin/console make:migration

6 - php bin/console doctrine:migrations:migrate

7 - symfony serve
