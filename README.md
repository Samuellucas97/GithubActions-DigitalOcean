
## How to install and to run

In your computer, run the following commands to clone in your local machine and to install dependencies:

```
$ git clone https://github.com/samuellucas97/Testing-GithubActions.git  
$ cd Testing-GithubActions

$ npm install
```

To run, use the following command:

```
$ node app.js
```

After this, check your browser in the following address: [http://localhost:3000](http://localhost:3000). 

### Creating and running Docker image

```
$ docker build --tag node-docker .    ## To create docker image
$ docker run -d -p 3000:3000 node-docker ## To run docker image
```