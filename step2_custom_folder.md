# Custom folder

## Create custom folder
```
docker exec -it n8n /bin/sh

cd /home/node/.n8n/
ls -la
mkdir custom
cd custom
ls -la
pwd
exit
```

## Make sure custom folder exists
/home/node/.n8n/custom 

## if you want to delete a folder
```
docker exec -it --user root n8n /bin/sh

cd /home/node/.n8n/custom
ls -la
rm -rf <folder>
ls -la
exit
```