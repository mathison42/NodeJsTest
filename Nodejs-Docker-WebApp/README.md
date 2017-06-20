[Nodejs Docker WebApp](https://nodejs.org/en/docs/guides/nodejs-docker-webapp/)


Set Up
-
    Run: docker build -t demo/node-web-app .

Run
-
    Run: docker run -p 49160:8080 -d demo/node-web-app

Test
-
    Run: curl -i localhost:49160
