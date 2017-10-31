# face-app
Emotionify App

Referencing #2 issue - Free hosting and HTTPS/SSL

Use danielcolceag.com and digitalocean.com for the hosting.


Referencing #4 issue - High Level Architecture


    User<br>
------v------<br>
Load Balancer<br>
------v------<br>
Face-App UI - Horizontally scaled<br>
------v------<br>
Load Balancer<br>
------v------|---------------|----------------------<br>
  Face-API   > Load Balancer > Facial Expression API<br>
------v------|---------------|----------------------<br>
Load Balancer<br>
------v------<br>
Facebook API<br>
