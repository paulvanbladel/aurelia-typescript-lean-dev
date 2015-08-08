# aurelia-typescript-lean-dev
For grasping the rational behind this repository see: 
http://blog.opinionatedapps.com/a-lean-aurelia-typescript-deveopment-experience/
## Running The App

To run the app, follow these steps.

1. Ensure that [NodeJS](http://nodejs.org/) is installed. 
2. From the project folder, execute the following command:

  ```shell
  npm install
  ```
3. Ensure that [jspm](http://jspm.io/) is installed. If you need to install it, use the following command:

  ```shell
  npm install -g jspm
  ```
4. Install the client-side dependencies with jspm:

  ```shell
  jspm install -y
  ```
5. Install live-server
In this simplified sample we are not using gulp. Instead we use live-server. We can do this because we no longer need to compile any files.

  ```shell
  npm install live-server -g
  ```
6. Start live-server

  ```shell
  live-server
  ```


