# Resumas-Flask
Demo Project of Resumas On digital Ocean

                                      IMAGE BUILDING GUIDE


REF: https://hub.docker.com/r/tiangolo/uwsgi-nginx-flask/


You should now have a directory structure like:


.
├── app

│  
    └── main.py

└── Dockerfile

Go to the project directory (in where your Dockerfile is, containing your app directory)

Build your Flask image:

                  docker build -t myimage .

----------------------------------------------------------------------------------------------------------------------------


                                     DEPLOYMENT
                                     
                   COMMAND: kubectl rollout restart deployment  (After changing the image)
                   
                   
                   
Note: Always set the 
 
                    imagePullPolicy: Always 
                   
