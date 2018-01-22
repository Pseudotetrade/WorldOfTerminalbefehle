# allgemein

    su -l "Benutzer"              //logge dich als angegebenen Benutzer ein (steam im ARK-Server)
    cd "Ordnerpfad"               //öffne angegebenen Ordnerpfad
    exit				          //Zurück / Logout
    poweroff			          //PC Herunterfahren
    shutdown	                  //PC Herunterfahren
    
# ark game server

    systemctl status ark.service  //Status des Servers
    systemctl start ark.service   //Starte Server
    systemctl stop ark.service	  //Stoppe Server

# software entwicklung

    sudo lxc-start -n gotta		  //Startet Entwicklungsumgebung
    sudo bash ./env.sh gotta	  //Aktuallisiere Entwicklungsumgebung
    
    git clone <url>               // herunterladen des software repos
    git pull                      // aktualliesieren des lokalen software repos
    git branch                    // anzeigen von software entwicklungszweigen
    git checkout <branch>         // wechseln auf den Zweig <branch>
    git add <datei>               // füge datei einem commit hinzu
    git commit                    // erstelle neuen commit
    git push origin [<branch>]    // lade neuen softwarestand auf externes repo
