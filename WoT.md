# allgemein

    su -l "Benutzer"                //logge dich als angegebenen Benutzer ein (steam im ARK-Server)
    cd "Ordnerpfad"                 //öffne angegebenen Ordnerpfad
    exit                            //Zurück / Logout
    poweroff                        //PC Herunterfahren
    shutdown                        //PC Herunterfahren
    
# ark game server

    systemctl status ark.service    //Status des Servers
    systemctl start ark.service     //Starte Server
    systemctl stop ark.service      //Stoppe Server

# software entwicklung

    sudo lxc-start -n gotta                         //Startet Entwicklungsumgebung
    sudo bash ./env.sh gotta                        //Aktuallisiere Entwicklungsumgebung
    sudo lxc-attach -n gotta -- /bin/su -l user     //Login als User in Entwicklungsumgebung
    
    git clone <url>                 // herunterladen des software repos
    git pull                        // aktualliesieren des lokalen software repos
    git branch                      // anzeigen von software entwicklungszweigen
    git checkout <branch>           // wechseln auf den Zweig <branch>
    git add <datei>                 // füge datei einem commit hinzu
    git commit                      // erstelle neuen commit
    git push origin [<branch>]      // lade neuen softwarestand auf externes repo

    1.) git pull
    2.) Programm bearbeiten
    3.) git status
    4.1)git add -A                  // merkt alles vor  
    4.2)git add <Dateipfad>         // merkt nur den Pfad vor  
    5.) git commit                  // schließt commit mit anschließender Bemerkung ab  
    6.) git push                    // hochladen zum Server  
