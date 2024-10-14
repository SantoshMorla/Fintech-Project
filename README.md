
# Start project
* Start clone the repo using `git clone https://github.com/SantoshMorla/Fintech-Project.git`
* Build the Project using 'docker build -t django:v1 .'
* incase you will get permission deny  use `sudo docker build -t django:v1 .`
* Run the Project using `docker run -d -p 8000:8000 django:v1 `
* Open the browser and navigate to `http://localhost:8000/`
* if you using EC2 server then :`public ip:8000`
    *note* port should be open in your Security group


