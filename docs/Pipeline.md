### pipeline structure and flow :
- version: 2.1
- orbs: node , aws-cli , eb.
- build : 
    - install node 
    - checkout latest code
    - setup aws-cli
    - setup eb
    - install frontend
    - install api
    - build frontend
    - build api
- deploy:
    - deploy frontend to s3 bucket
    - deploy api to Elastic beanStalk instance 


#### pipeline graph :
(https://github.com/elmougy/deployment-process-project-starter/blob/master/screenshots/pipline%20graph.html)