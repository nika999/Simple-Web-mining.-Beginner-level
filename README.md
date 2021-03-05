# Simple-Web-mining.-Beginner-level.
Here we study how easy to extract data from websites. Beginner level.
## First step
Here we will unload data from the https://pudding.cool/ which will contain title, author and description of articles.

We will use Pandas for data manipulating, Urllib3 is used to open URLs and the Beautiful Soup package is used to extract data from html files.

And we have this table as a result of the first step:

![image](https://user-images.githubusercontent.com/28656085/109817387-8e2a0d00-7c3a-11eb-9de1-bfa6f43321cd.png)

## Second step
Here we will unload data from the https://www.work.ua/jobs-kyiv-data+analyst/ which will contain job title and hiring company.
In order to get all the data on request from this site, we will have to upload data from several pages:

![image](https://user-images.githubusercontent.com/28656085/109988509-437ac480-7d10-11eb-8174-49bab1b2723c.png)

And we have csv file as a result of the second step:

![image](https://user-images.githubusercontent.com/28656085/109988630-660cdd80-7d10-11eb-9222-38f98811e815.png)

## Third step
What if we want to gather information from the inner part of articles? 

To do it we need to gather links of these articles and than go through them to gather inner information.

Study 3rd step to learn how to do it.

![image](https://user-images.githubusercontent.com/28656085/110164002-75b42100-7df9-11eb-9b21-e1c13c32b91d.png)

As a result we have titles and time from the inner side of articles:
![image](https://user-images.githubusercontent.com/28656085/110164420-0854c000-7dfa-11eb-9b60-817ef1c4239d.png)
