# Backend Setup
To run the website's backend API navigate to the API directory
```
cd app
```
### Run using Python
#### In the API directory
 i. Intall required dependencies
 ```
 pip install -r requirements.txt
 ```
 ii. Run the pythoin script to start the server
 ```
 python3 main.py
 ```
 ### Run using docker
 #### In the API directory
 i. Build the docker image
 ```
 docker build -t alumni-backend
 ```
 ii. Run the image docker image
 ```
 docker run -p 8000:8000 -d alumni-backend
 ```
 by default the image will run on port 8000. To run on a different port change the -p value to an available port number

