# rancher-cli

Based on the Docker image to be able to run commands inside containers that are hosted in rancher; usefull for automation and scheduling of processes.

Example : docker -it --rm -e "RANCHER_URL=http://localhost/" -e "RANCHER_ACCESS_KEY=theaccesskey" -e "RANCHER_SECRET_KEY=secretkey"  run delariva/rancher-cli rancher exec stackname-servicename-1 npm install

