# Docker file was created by the devops engineer 

## steps to run the docker file 

1. docker build -t suvo-shop-dev .
2. docker run -d -p 5173:5173 --name online-shop-container suvo-shop-dev
 
