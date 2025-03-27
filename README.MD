## Schema Altium


## Utiliser Git dans Altium
1. **Save:** lorsque vous effectuez une modification, enregistrez votre travail.
1. **Commit:** Faites un clic droit sur le fichier ou le projet, puis selectionnez Version Control -> Commit. Ajoutez une note decrivant les modifications effectuees. Cette action reste locale tant que vous n avez pas push les modifications. Voir l etape suivante.
1. **Push:** Pour televerser toutes les modifications sur GitHub, faites un clic droit sur le fichier ou le projet, puis selectionnez Version Control -> Push.
1. **Check:** Allez sur votre GitHub pour vous assurer que tout a ete correctement televerse.


## Using Git from command line (Manually)
1. **Open cmd:** Once you make some updates, go into your project directory, open commad line and run:<br />
1. `git status` #this will show you what changes you have done<br />
1. `git add [path/file]` #this will prepare that specific file for commit, to add all files at once, use add . <br />
1. `git commit -m "Change description"` #this will commit the changes with specific description<br />
1. `git push origin master` # this will copy your changes to Github<br />

### Download the latest changes
If you would like to download the latest files from Github, then:<br />
1. `git pull origin master` # this will download the latest files from Github to your local computer<br />
