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


Todo:

1. Decide for a UI Framework
2. Describe the basic functionality of the UI
3. Describe the Face API
4. Describe the Facebook API
5. Describe the Facial Expression API
6. Describe the architecture plan in more detail
