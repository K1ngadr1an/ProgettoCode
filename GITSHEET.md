## GIT SHEET
### Comandi di base
#### 1)`Configurazione`
#### **`-git-config -- global user.name "tuo nome"`: Imposta il nome utente**
#### **-`git-config -- global user.email "tua@email.com"`: Imposta l'indirizzo email dell'utente**
#### **-`git-config --global core.editor "nome_del_tuo_editor`": Imposta l'editor di testo preferito.**
#### 2)**`Creazione e Clonazione di Repository`**
#### **-`git init`: Inizializza un nuovo repository Git nella directory corrente.**
#### **-`git clone url_repository`: Clona un repository Git esistente nella tua directory locale.**
#### 3)`Operazioni sui File`
#### **-`git add nome_file`: Aggiunge un file all'area di staging.**
#### **-`git add .`: Aggiunge tutti i file modificati all'area di staging.**
#### **-`git rm nome_file`: Rimuove un file dalla repository e dall'area di staging.**
#### **-`git mv vecchio_nome nuovo_nome`: Rinomina un file e aggiunge la modifica all'area di staging**
#### 4)`Commit`
#### **-`git commit -m "Messaggio del commit"`: Esegue un commit con un messaggio descrittivo.**
#### **-`git commit -a -m "Messaggio del commit"`: Aggiunge automaticamente e committa tutti i file modificati.**
#### **`-git commit --amend: Modifica l'ultimo commit.`**
#### 5)`Gestione del Repository`

#### **`-git status`: Mostra lo stato del repository.**
#### **-`git log`: Mostra la cronologia dei commit.**
#### **-`git log --oneline`: Mostra la cronologia dei commit in formato breve.**
#### **-`git log --graph --oneline --all`: Mostra una visualizzazione grafica dei rami e dei commit.**
#### **-`git branch`: Mostra l'elenco dei rami presenti.**
#### **-`git branch nome_ramo`: Crea un nuovo ramo.**
#### **-`git branch -d nome_ramo`: Cancella il ramo.**
#### **-`git branch -D nome ramo`: se il branch da cancellare non è ancora stato completamente mergiato
#### **-`git checkout nome_ramo`: Cambia ramo.**
#### **-`git checkout -b nome_ramo`: Crea e passa a un nuovo ramo.**
#### **`-git merge nome_ramo`: Esegue il merge di un ramo nel ramo corrente.**
#### **-`git rebase nome_ramo`: Riunisce il ramo corrente con un altro ramo.**
#### **-`git remote`: Mostra l'elenco dei repository remoti collegati.**
#### **-`git remote add nome_remoto url_remoto`: Collega un repository remoto.**
#### **-`git push nome_remoto nome_ramo`: Carica un ramo su un repository remoto.**
#### **-`git pull nome_remoto nome_ramo`: Scarica e fonde un ramo da un repository remoto.**
#### **-`git remote rename origin nuovo-nome`: Rinomina il repo da origin a nuovo-nome.**
#### **-`git clone url_repository`: Clona un repository Git esistente nella tua directory locale.**
#### **-`git fetch`: Recupera i riferimenti dai repository remoti senza effettuare il merge.**
#### **-`git diff`: Mostra le modifiche tra l'area di staging e l'ultimo commit.**
#### **-`git stash`: Mette da parte temporaneamente le modifiche non commesse.**
#### **-`git tag nome_tag`: Crea un tag per un commit specifico.**
#### **-`git diff nome_branch1..nome_branch2`: Mostra le differenze tra due rami.**
#### **-`git mergetool`: Avvia un tool di merge per risolvere conflitti.**
#### **-`git reset nome-del-file`: Rimuove il file dalla zona di staging.**
#### **-`git reset --hard HASH-del-commit`: Resetta il repo al commit specificato eliminando quelli successivi.**
#### **`-git remote -v`: Visualizza gli URL dei repository remoti collegati.**
#### **-`git fetch origin`: Recupera i cambiamenti dal repository remoto origin.**
#### **-`git push origin nome_ramo`: Carica un ramo nel repository remoto origin**
#### **-`git pull origin nome_ramo`: Tira i cambiamenti dal repository remoto origin e fonde con il ramo corrente.**
#### **-`git push origin` -- delete (nome del branch): per eliminare un branch in remoto(github ecc)

