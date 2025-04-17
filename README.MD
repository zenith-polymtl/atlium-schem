## Schema Altium


## Utiliser Git dans Altium
1. **Save:** lorsque vous effectuez une modification, enregistrez votre travail.
1. **Commit:** Faites un clic droit sur le fichier ou le projet, puis selectionnez Version Control -> Commit. Ajoutez une note decrivant les modifications effectuees. Cette action reste locale tant que vous n avez pas push les modifications. Voir l etape suivante.
1. **Push:** Pour televerser toutes les modifications sur GitHub, faites un clic droit sur le fichier ou le projet, puis selectionnez Version Control -> Push.
1. **Check:** Allez sur votre GitHub pour vous assurer que tout a ete correctement televerse.


## Utiliser Git en ligne de commande (Manuellement)
1. **Open cmd:** Une fois que vous avez effectue des modifications, accedez a votre repertoire de projet, ouvrez la ligne de commande et executez :<br />
1. `git status` #cela affichera les modifications que vous avez effectuees<br />
1. `git add [path/file]` #cela preparera ce fichier specifique pour le commit <br />
1. `git commit -m "Change description"` #ela validera les modifications avec une description specifique<br />
1. `git push origin main` #cela copiera vos modifications sur GitHub<br />

### Telecharger les dernieres modifications
Si vous souhaitez telecharger les derniers fichiers depuis GitHub, alors :<br />
1. `git pull origin main` # cela telechargera les derniers fichiers depuis GitHub vers votre ordinateur local<br />
