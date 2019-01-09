# AppProject

Se non sei inscritto a github:
- vai a [GitHub](https://pages.github.com/).
- iscriviti
- una volta terminata l'iscrizione scarica [Git](https://git-scm.com/downloads)
- se hai installato correttamente dovresti poter useguire il comando `git` da terminale

# Per avere il progetto nel proprio pc:
- scegli una cartella dove salvare il progetto
- una volta che sei nella cartella esegui `git clone https://github.com/PietroMenchetti/AppProject.git`, una cartella di nome AppProject verrà creata con tutti i contenuti della repository, (ti verranno chieste le credenziali di GitHub). 

# Installare unity:
https://unity3d.com/get-unity/download

# Installare jdk:
- vai [qui](https://www.oracle.com/technetwork/java/javase/downloads/index.html), scegli l'ultima versione e completa l'installazione.Fai solo attenzione alla cartella dove viene installato il tutto

# Installare Android SDK Tools:
- vai [qui](https://developer.android.com/studio/), scarica Command line tools only per il tuo sistema operativo
- unzippa il file
- vai in tools e fai doppio click sul file android
- si dovrebbe aprire una finestra con la lista di package che è possibile scaricare. Se il tuo smartphone ha l'ultima versione di Android installa i pachetti già selezionati, accetta tutto e completa l'installazione. Fai solo attenzione alla cartella dove viene installato il tutto


Se hai completato tutti i punti puoi aprire Unity, selezionare "Apri/Open" e selezionare la cartella del progetto.


Una volta dentro Unity, puoi andare su "Edit/Modifca" (credo) > "Preferenze" > "Strumenti esterni", sotto "Android" inserisci in JDK la cartella dove è stato salvato il JDK e in SDK la cartella dove è stato salvato il SDK, salva e chiudi.

Per creare l' apk da installare sul tuo smartphone vai su "File" > "Build Settings", seleziona platform "Android" e clicca su "Build". In questo modo verrà compilata l'app e potrai installarla sul tuo smartphone transferendo l'apk nel tuo smartphone.  Se vuoi far compilare e runnare l'app mentre hai lo smartphone collegato al pc dovrebbe bastare fare "Build And Run".
