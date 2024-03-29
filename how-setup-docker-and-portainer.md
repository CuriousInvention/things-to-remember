## How to setup Docker

## How to setup Portainer

- Below are the commands in the video that you can copy & paste directly into your terminal.

- To create a volume for Portainer:
  
  > docker volume create portainer_data

- To deploy the Portainer docker container:
  
  > docker run -d -p 8000:8000 -p 9000:9000 --name=portainer --restart=always -v /var/run/docker.sock:/var/run/docker.sock -v portainer_data:/data portainer/portainer-ce

- Go to browser and verify 
  
  > localhost:9000

- REF : `https://www.youtube.com/watch?v=dDEassY31Tw`
