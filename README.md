# Strapi Sample App (Dockerized)

## 🚀 How to Run
1. Clone repo:
   ```bash
   git clone https://github.com/paulsingh-1502/strapi-sample-app.git
   cd strapi-sample-app
## Build Docker image:
docker build -t strapi-app .
## Run container:
docker run -it -p 1337:1337 strapi-app
## Open browser:
http://localhost:1337/admin
