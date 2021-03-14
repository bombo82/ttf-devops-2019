# USAGE

## Sviluppo locale
- esecuzione:
`docker-compose -f docker-compose-infrastructure.yml -f docker-compose-local.yml up`
- verifica dei componenti e delle porte esposte:
`docker container ps`
![local](images/usage-local.png)

### Test / dev server
- esecuzione:
`docker-compose -f docker-compose-infrastructure.yml -f docker-compose-application.yml up`
- verifica dei componenti e delle porte esposte:
`docker container ps`
![local](images/usage-test.png)
