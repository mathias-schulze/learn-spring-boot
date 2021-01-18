# Learn Spring Boot + Heroku

Project to learn basics of [Spring Boot](https://spring.io/projects/spring-boot) + Deployment to [Heroku](https://heroku.com).

## Spring Boot

Sample app with a 'Hello ...' WebService.

## Heroku

Following steps are necessary to deploy to Heroku.

For Java 11 support a file `system.properties` needs to be in project root.

```
java.runtime.version=11
```

The following commands create and deploy the app on heroku.

```bash
heroku create
git push heroku main
heroku open
```

Additionally the app can be configured in the dashboard to automatically deploy on changes in GitHub.
