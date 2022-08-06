THIS IS A NON PRODUCTION DEMO STACK FOR PERSONAL USE AND TESTING


- The ".env" file contains your variables and configurations. This is a minimal setup so theree is not to much. 

- The password you set in the .env will be what you use for logging in. the user will be elastic

- The certs, esdata1,2,3 and kibanadata directories will populate automaticlly (In your current directory) once you run the compose file. 

- In a browser, you can reach Kibana at localhost:5601

1. Make sure docker desktop is running
2. Make sure you are in the directory where you put your files. 
3. Run the following commands:

# This will stand up your stack
docker-compose up -d 

# This will shut down your stack when you are done. 
docker-compose down
