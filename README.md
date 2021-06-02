Dette er webserveren for batteriprøvestanden.
Det er en modificeret forke af den oprindelige webserver der blev overtaget i efteråret 2020

For at se den originale readme file fra det originale server-setup, se her:
https://github.com/AUTeam2/server-setup


Når server-setup-2021 er hentet ned, skal man stå i denne mappe og bygge serveren. 
Dette gøres vha:
**$docker-compose build**

Herefter kan webserveres startes op med kommandoen: 
**$docker-compose up**

Herefter kan brokeren startes op i et nyt terminalvindue, dog i samme sti med kommandoen: 
**docker-compose exec webinterface python manage.py start_messagehandler**
