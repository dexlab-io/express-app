# Express app

Simple express app which deploys to Dokku

(Dokku documentation)[http://dokku.viewdocs.io/dokku~v0.11.3/deployment/application-deployment/]

## Push to dokku

Add dokku remote

```
git remote add dokku dokku@178.128.214.182:express-app
```

Then after making changes (commit) push using

```
git push dokku master
```

## Dokku script

List dokku apps:

```
./dokku.sh apps:list
```