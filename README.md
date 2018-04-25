## Running this
Wordpress on Docker

`docker-compose up -d`

`http://localhost/` -> Wordpress
`http://localhost:8080/` -> PHPMyAdmin



## Deployment
`heroku login` -> user && pass && two factor code
`heroku container:login`
`heroku container:push web --app docker-wordpress-demo`