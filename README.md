# Docker Django RDS

## Build docker image
docker build -t django_product_app .

## Docker run image
docker run -dp 8000:8000 django_product_app

## Pull docker images
docker pull kumarm5/django_product_app


***When you pull an image from docker hub, you need to update the database config in .env file***
