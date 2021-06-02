Dette er webserveren for batteriprøvestanden.
Det er en modificeret forke af den oprindelige webserver der blev overtaget i efteråret 2020

For at se den originale readme file + server setup fra det originale server, se her: <br>
https://github.com/AUTeam2/server-setup

Den modificere server som skal kobles til batteriprøvestanden skal hentes ned vha Git Clone. <br>
Når server-setup-2021 er hentet ned, skal man stå i roden af denne mappe og bygge serveren. 
Dette gøres vha: <br>
**$ docker-compose build**

Herefter kan webserveres startes op med kommandoen:<br>
**$ docker-compose up**

I et nyt terminalvindue startes brokeren op vha kommandoen. <br>
**$ docker-compose exec webinterface python manage.py start_messagehandler**<br>
Husk at du skal befinde dig i roden af server-setup-2021:<br>


For at gå ind på webserveren der befinder sig på localhost indtastes der i et browservindue:<br>
http://localhost:81/ <br>
Der er nu adgang til webserveren
