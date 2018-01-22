systemctl status ark.service	//Status des Servers
systemctl start ark.service	//Starte Server
systemctl stop ark.service	//Stoppe Server

cd "Ordnerpfad"			//öffne angegebenen Ordnerpfad
su -l "Benutzer"		//logge dich als angegebenen Benutzer ein (steam im ARK-Server)
exit				//Zurück / Logout

shutdown			//PC Herunterfahren
sudo lxc-start -n gotta		//Startet Entwicklungsumgebung
sudo bash/ .env.sh gotta	//Aktuallisiere Entwicklungsumgebung