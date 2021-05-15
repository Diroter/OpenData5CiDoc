<center> 

# Diario Di Progetto
<br>

 | Author | Version  |  Date |
|:------:|:--------:|:-----:|
|  DeCet Alessandro | 0.1 | 5/05/2021 |
| Xiao Simone  | 0.1  | 5/05/2021  |   
|  Marocchio Enrico | 0.2  |  15/05/2021 |
|   |   |   |
|   |   |   |
<br>



---


# Replica ambiente DKAN con DKAN-TOOLS

```
git clone https://github.com/GetDKAN/dkan-tools
```
export PATH=$PATH:/myworkspace/dkan-tools/bin

---

</center>

## 1. To start a project with DKAN tools, create a project directory.

   `mkdir my_project && cd my_project`

## 2. Inside the project directory, initialize your project.

   `dktl init`

## 3. Make a full Drupal/DKAN codebase, primarily using composer 

   `dktl make`

## 4. Install. Creates a database, installs Drupal, and enables DKAN.

   `dktl install`

## 5. Add the front end.

   `dktl frontend:install `

   `dktl frontend:build`

## 6. Access the site.

   `dktl drush uli`

## Terminare i container

`sudo docker ps`

i container sono 4

`sudo docker stop <codice>` 

## Avviare i container

`export PATH=$PATH:/myworkspace/dkan-tools/bin`
`dktl docker:compose up`


## Debian.ova
### User 
username: thecet
psw: root
### Directories:

Progetto: /myworkspace/project

Dkan tools: /myworkspace/dktan-tools

---

# Replica Ambiente Debian

### Ai fini del progetto e`stato utilizzato <u>[Linux Debian V10.9](https://www.debian.org/index.it.html)</u> virtualizzato tramite VirtualBox.

## Step 1
### Eseguire il download di Linux Debian al seguente <i>[link](https://www.debian.org/index.it.html)</i>
## Step 2
### Scaricare un Virtualizzatore (nel nostro caso Virtualbox) <i>[qua](https://www.virtualbox.org/)</i>
## Step 3
### Installare Virtualbox e Selezionare "Nuova"
### Inserire nei campi Tipo e Versione ("Linux" e "Debian 64bit")
### Requisiti minimi da inserire (2GB Ram e 15GB Spazio su hdd)
### Finire la creazione della macchina virtuale
## Step 4
### Al primo startup, dove verra` richiesto di inserire un file, inserire il file debian.iso appena scaricato.
## Step 5
### verificare la funzionalita` della macchina
