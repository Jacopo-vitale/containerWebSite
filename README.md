# Create your website using Docker or Kubernetes

**Project**: Create a Wordpress website using two different ways.

## Docker Compose
<p align="center">
  <img width="300" src="https://user-images.githubusercontent.com/74437465/196418959-31d5441b-f64d-46e0-8c53-95afc18bac24.png">
</p>
This way for building a website architecture is the simplest.<br>

Once installed `docker` and `docker-compose` you can just:<br>

> [Download this repo ZIP](https://github.com/Jacopo-vitale/containerWebSite/archive/refs/heads/main.zip) <br>

Install unzip from Ubuntu repositories:<br>
`$ sudo apt update && sudo apt install unzip`<br>
Enter to download folder: <br>
`$ cd path/to/zip/file`<br>
Unzip to a specific folder:<br>
`$ unzip containerWebSite-main -d my/directory/path`<br>
Enter into docker-compose folder<br>
`$ cd docker-compose`<br>
Launch docker-compose as daemon process (-d argument):<br>
`$ docker-compose up -d`<br>

Once the prompt gives you `Done` along all containers, then you can open your browser and find wordpress at:
`http://localhost:8000`

<br>
<br>

## Kubernetes and Minikube

<p align="center">
  <img width="300" align="center" src="https://user-images.githubusercontent.com/74437465/196419874-78f6af33-c503-4b8c-b081-9397cec3cde0.png">
  <img width="120" align="center" hspace="50" src="https://user-images.githubusercontent.com/74437465/196420141-0e9134d1-1067-4097-88e6-4ab4ebe28b1d.png">
</p>










