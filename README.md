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
  <img width="150" src="https://user-images.githubusercontent.com/74437465/194286594-064a018a-31b0-4342-a6be-9051b4a2bb46.svg">
</p>

Once the prompt gives you `Done` along all containers, then you can open your browser and find wordpress at:
`http://localhost:8000`
