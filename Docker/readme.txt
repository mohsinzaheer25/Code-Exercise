Step 1:
Run the below command to build the image

        docker build -t nginx_demo .

Step 2:
Run the below command to run the container in detach mode

        docker run -itd -p 8080:80 --name nginx_con nginx_demo