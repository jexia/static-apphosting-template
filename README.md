[![Runme](https://svc.runme.io/static/button.svg)](http://runme.io/run?app_id=868851f4-db12-4241-8112-b5f0bf5482d8)

# Static App Hosting Template
Template to host static files without backend logic.

## Installing Locally
To run this on your local machine, run the steps below:

0. You need to have both **nodejs** and **npm** (or **yarn**) installed. For this we will be using **npm**.
1. Firstly clone this github repository:
```
$ git clone https://github.com/jexia/static-apphosting-template.git
```
2. Then we need to move into the directory of the git repository:
```
$ cd static-apphosting-template
```
3. After this we need to install the node modules:
```
$ npm install
```
4. Once they have installed, we can now start our development web server:
```
$ npm run dev
```

### Troubleshooting
If this program doesn't run on your local machine, you can edit the `dev` command within `package.json`, which looks like:
```
"dev": "http-server ./dist -a localhost -p 8080"
```
If will change the port from `8080` to another port such as `5678` which is normally free for use, you will be able to then visit this in the browser.

Another issue you may come across, such as "This page isn't working", you may need to access `http://localhost:8080/index.html` directly, instead of `http://localhost:8080`.
