# Search Tweets

A simple webapp for Vue.js + Spring Boot studies

## Resources used

- [Vue.js (javascript framework for creating web applications)](http://vuejs.org)
- [Vue-cli (to create the frontend structure)](https://cli.vuejs.org/)
- [Vue-router (to make the routing structure)](https://router.vuejs.org/)
- [Vuetify (for user interface components)](https://vuetifyjs.com/en/)
- [Spring Boot (for api rest)](https://spring.io/projects/spring-boot)
- [Apache Maven (dependency manager)](http://maven.apache.org/)
- [Twitter4J (a Twitter api access library)](http://twitter4j.org/en/)
- [Yarn (node packager manager)](https://yarnpkg.com/)

## Setup

Install dependencies by run command at directory frontend

```
cd frontend
yarn install
```

## Run

After that, run the command at the root of the project

```
mvn clean spring-boot:run
```

Then browse [http://localhost:8081](http://localhost:8081/)

---

As an application uses Twitter data, you must have access keys for queries. With them, replace in the application.properties file.

