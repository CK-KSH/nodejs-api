# Currency Exchange API – NodeJS

docker run -d -p 8080:8080 u1ih/nodejs-api

curl -i http://localhost:8080/fx

Above commands work in Google Cloud Shell Editor, not our local machine.

This repo is forked from https://github.com/u1i/nodejs-api

Purpose of this repo is to create a simple API to connect to for simple currency exchange conversion.

The container is located at https://hub.docker.com/r/u1ih/nodejs-api

docker run -d -p 8080:8080 u1ih/nodejs-api shows the location of the container.


Steps to run this API:

1) Log in to Google Cloud Shell Editor

2) Run python -m SimpleHTTPServer 8080

3) Run docker run -d -p 8080:8080 u1ih/nodejs-api

4) Run docker ps

5) Preview at port 8080

6) Site open is https://8080-14c71497-b8a0-4f70-b0d3-33f3923e2afc.cs-asia-southeast1-vjqr.cloudshell.dev/?authuser=0

7) Change https address above to end with fx instead of ?authuser=0

8) Sell, Timestamp & Buy info is shown.

9) Each refresh of link updates the sell, timestamp & buy info

Further work required:

How to run the this API on local machine

Feel free for any updates on this repo.
