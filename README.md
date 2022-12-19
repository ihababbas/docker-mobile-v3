# Lab: Authentication & Production Server
## Ihab Abbas
### 19-Dec-22


#### Setup
 use python version 3.10.7

#### Login to the admin pannel
* Super User: admin
* Password: admin1234

* staff User: ihababbas
* Password: ihab2312

* Docker Super User: admin

* Password: admin123


#### Installing the requirements
  - pip install -r requirements.txt
#### Running the server
  - docker-compose up
#### Running the tests
  - docker-compose run web python manage.py test


### usnig tokens
* for super user "admin
  - "refresh": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ0b2tlbl90eXBlIjoicmVmcmVzaCIsImV4cCI6MTY3MTUyNzkxMSwiaWF0IjoxNjcxNDQxNTExLCJqdGkiOiI2ODM1OTNmY2M3NDc0ODNlOGI2ZjZlMzMxOGNhMjMwOSIsInVzZXJfaWQiOjEsInVzZXJuYW1lIjoiYWRtaW4ifQ.q23zfcG-9CluHElSej1xjC6h-1U82ZMf69pl6DCxYyQ",




  - "access": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ0b2tlbl90eXBlIjoiYWNjZXNzIiwiZXhwIjoxNjcxNDQxODExLCJpYXQiOjE2NzE0NDE1MTEsImp0aSI6IjhjYmYyMGUyN2RmMzRjZWFiYTczNDY4MThlZjE2NDk4IiwidXNlcl9pZCI6MSwidXNlcm5hbWUiOiJhZG1pbiJ9.b_1j1qlv3HbKpcqBkapO0136qT-eDjDP7QQhA9AETew"

### [PR](https://github.com/ihababbas/docker-mobile-v3/pull/1)
