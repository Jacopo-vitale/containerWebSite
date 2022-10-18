# Create your website using Docker or Kubernetes

**Project**: Create a Wordpress website using two different ways.

## Docker Compose
This way for building a website architecture is the simplest.
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



<p align="center">
  <img width="150" src="https://user-images.githubusercontent.com/74437465/196418959-31d5441b-f64d-46e0-8c53-95afc18bac24.png">
</p>

Once the prompt gives you `Done` along all containers, then you can open your browser and find wordpress at:
`http://localhost:8000`
