[![Build Status](https://travis-ci.org/aleksas/nginx-redis-react-pg.svg?branch=master)](https://travis-ci.org/aleksas/nginx-redis-react-pg)

# nginx-redis-react-pg

## External preparations
### AWS

- Create an Elastic Beanstalk App
- Create AWS IAM (Identity and Access Management) User
- Set Travis project settings environment vars to have 
  - AWS_ACCESS_KEY
  - AWS_SECRET_KEY

### Docker Hub
- Set Travis project settings environment vars to have 
  - DOCKER_ID
  - DOCKER_PASSWORD