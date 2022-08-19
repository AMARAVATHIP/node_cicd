# node-js-sample

Node.js app using [Express 4](http://expressjs.com/).

## Running Locally

Make sure you have [Node.js](http://nodejs.org/).

```sh
git clone git@github.com:heroku/node-js-sample.git # or clone your own fork
cd node-js-sample
npm install
npm start (or) node cms.js
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

If you are using jenkins file for the first time it won't work it shows error.

Because of this command ```rm -r *``` 

Change the ip address in jenkins file to your server ip address

Read npm.sh file to understand the process to start the node application

create node.service file in this path /etc/systemd/system/
```
systemctl daemon-reload //to activate service
systemctl start node.service //to start the service
```   
## To install pm2 use below command

``` npm install pm2 -g ```

To start node application by using pm2 use below command

``` pm2 start cms.js ```
