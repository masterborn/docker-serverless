# MasterBorn Docker - Serverless (Deployment Image)

[![MIT licensed](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/masterborn/docker-serverless/blob/master/LICENSE)

**Example usage:**

```
FROM masterborn/serverless:latest

COPY package.json .
COPY package-lock.json .
RUN npm ci
COPY . .

CMD serverless deploy
```
