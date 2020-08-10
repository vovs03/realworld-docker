# For developers

## Steps

### :four: Lesson 4

- Create `docker-compose.yml`
- [https://docs.docker.com/compose/compose-file/](https://docs.docker.com/compose/compose-file/)

```yml
version: "3.8"

services:
  api:
    build: ./api
    command: npm run start
    ports:
      - "3000:3000"
```

## Connect project to travis-ci & codecov

- [travis-ci](https://travis-ci.org)
- [codecov](https://codecov.io/gh) Choosed login `github`
