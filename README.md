# Docker-fullstack

### Previous ver
- [Show previous docker](https://github.com/Kimbeomchul/Docker-TravisCI)

### Used
- Docker
- Docker Hub
- Travis-CI
- Nginx
- React
- Node.js
- Mysql -> AWS RDS 
- AWS - Elasticbeanstalk / S3 / RDS 

### Demo
![docker1](https://user-images.githubusercontent.com/54543148/123961283-25398280-d9eb-11eb-8310-eef7fed69980.gif)


### Configuration
![image](https://user-images.githubusercontent.com/54543148/123635157-4c128000-d856-11eb-8c1a-5b6df709b82f.png)

### Docker Hub 
![image](https://user-images.githubusercontent.com/54543148/123974709-ca5a5800-d9f7-11eb-8329-49a23a8d6d2c.png)

### Nginx ( proxy ) 
- upstream
  + nginx port 80
  + frontend port 3000 
  + backend port 5000
    * frontend / backend 명명 -> docker-compose
### AWS 
- IAM User Value -> Saved in TravisCI Setting Value
- [참고문서](https://docs.aws.amazon.com/ko_kr/elasticbeanstalk/latest/dg/create_deploy_docker.html)


