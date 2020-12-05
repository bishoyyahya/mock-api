# Mock REST API

## installation

please execute:
`docker run  \
      -p 3000:3000  -v `pwd`:/data  \
      williamyeh/json-server        \
      --watch db.json`

then go to http://0.0.0.0:3000/contacts

## Endpoints

now you RESTful API for the contacts to use, avaliable endpoints:
```
GET    /contacts
GET    /contacts/1
POST   /contacts
PUT    /contacts/1
PATCH  /contacts/1
DELETE /contacts/1
```