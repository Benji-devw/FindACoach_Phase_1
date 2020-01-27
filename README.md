Site d'entrainement à domicile et en salle

RECUPERATION :

1 - git clone https://github.com/Benji-devw/FindACoach_Phase_1.git

2 - cd FindACoach_Phase_1

3 - git checkout dev

4 - composer install

4bis - composer require symfony/swiftmailer-bundle

4.2 bis - composer require tattali/calendar-bundle

5 - composer require vich/uploader-bundle

5bis - composer require stripe/stripe-php

5bisbis - php bin/console doctrine:database:create

6 - php bin/console make:migration

7 - php bin/console doctrine:migrations:migrate
