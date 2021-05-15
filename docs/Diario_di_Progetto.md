<center> 

# Diario Di Progetto
<br>

 | Author | Version  |  Date |
|:------:|:--------:|:-----:|
|  DeCet Alessandro | 0.1 | 5/05/2021 |
| Xiao Simone  | 0.1  | 5/05/2021  |   
|   |   |   |
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

[Progetto](/myworkspace/project) 

[Dkan tools](/myworkspace/dktan-tools) 
