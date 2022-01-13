## TODO
Stworzyc nowe instancje na AWS
Zalogowacsię na sokratesa, pobrac klucz SSH id_student
Połączyc się z instancja AWS przez sokratesa
sudo yum update -y
Zrobic plik hosts.ini z adresami maszyn i plik setup_wp.yaml z konifiguracja
Zainstalowac MardiaDB serwer i klient
Zainstalowac moduł mysql
Stworzyc bazy danych
Stworzyc uzytownika i przypisac mu uprawnienia
Zainstalowac serwer HTTP
Zainstalowac EPEL
Zainstalowac php repo
Zainstalowac PHP80
Pobrac wordpressa
copy vhost cfg, copy wp cfg
Przeładowac Apache
ansible-playbook -i hosts.ini setup_wp.yaml -e DB_PW='witam'