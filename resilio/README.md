
    alpine + glibc-vel; ubuntu : resilio


- ``-v /home/btsync/config:/config``: Beállításai és a saját adatbázisa, ha nincs config file akkor egy alapértelmezettel indul

- ``-v /home/btsync/data:/downloads``: Adatok helye

- ``-p 55555:55555``: Adat csere portja

- ``-p 8888:8888``: Konfiguráció http-n keresztül

    Ezek lehetnek a változók amivel állítgathatod

-  -e PUID : user  ID
-  -e GUID : group ID

-  -e UMASK 	: umask értéke; én a 002-öt szeretem
