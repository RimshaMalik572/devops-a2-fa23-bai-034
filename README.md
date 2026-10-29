\# DevOps Assignment 2 — Personal Portfolio



\*\*Student Name:\*\* Rimsha Malik  

\*\*Roll Number:\*\* FA23-BAI-034  

\*\*Course:\*\* CSC418 — DevOps for Cloud Computing



\## Project Overview



This project is a responsive personal portfolio website created to demonstrate basic DevOps practices. It introduces my learning journey in Artificial Intelligence, cloud computing, Git, GitHub, Docker, and GitHub Actions.



\## Technologies Used



\- HTML5

\- CSS3

\- Git and GitHub

\- Docker and Nginx

\- GitHub Actions



\## Project Files



\- `index.html` — Portfolio website content.

\- `style.css` — Website styling and responsive layout.

\- `Dockerfile` — Container configuration (to be added).

\- `.github/workflows/ci.yml` — CI/CD pipeline (to be added).



\## Run Locally



1\. Clone this repository.

2\. Open `index.html` in a web browser.



```bash

git clone https://github.com/RimshaMalik572/devops-a2-fa23-bai-034.git

cd devops-a2-fa23-bai-034

```



\## Run with Docker



After the Dockerfile is added, build and run the website using:



```bash

docker build -t devops-a2:manual .

docker run --name portfolio-container -p 8080:80 devops-a2:manual

```



Open `http://localhost:8080` in your browser.



\## Run Automated Checks



The GitHub Actions workflow will validate the portfolio files and build the Docker image. Image publishing will be configured using GitHub repository secrets.



\## Learning Outcomes



\- Maintain project history using meaningful Git commits.

\- Use GitHub branches and pull requests.

\- Containerize a static website with Docker and Nginx.

\- Automate validation and image publishing with GitHub Actions.



Webhook push event test 
Pull request webhook test 
