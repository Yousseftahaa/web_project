# Website Deployment with Docker and NGINX

This project uses Docker to build and deploy a simple static website using the NGINX web server.

## How to Run
web_project/
├── sample-website/
│   └── index.html
├── Dockerfile
└── README.md  



Using local Dockerfile:

```bash
docker pull yousseftahaa/new-web

docker run -it -d -rm  -p 8080:80 --name web  yousseftahaa/new-web

