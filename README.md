# face-app
Emotionify App

Referencing #2 issue - Free hosting and HTTPS/SSL

Use danielcolceag.com and digitalocean.com for the hosting.


Referencing #4 issue - 
High Level Architecture

    User
------v------
Load Balancer
------v------
Face-App UI - Horizontally scaled
------v------
Load Balancer
------v------|---------------|----------------------
  Face-API   > Load Balancer > Facial Expression API
------v------|---------------|----------------------
Load Balancer
------v------
Facebook API
