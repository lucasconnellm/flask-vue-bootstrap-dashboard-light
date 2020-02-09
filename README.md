# flask-vue-bootstrap-dashboard-light
A template for kicking off a flask api, a vue driven front-end, and a pretty sweet looking dashboard

The vue template is almost 100% from https://www.creative-tim.com/product/vue-light-bootstrap-dashboard

The flask side of things, as well as the linking of flask to vue is from https://dev.to/michaelbukachi/flask-vue-js-integration-tutorial-2g90

I come from a background of Django development with jQuery on the front-end, but I've recently become interested in Vue.js. I hope this template serves as a nice starting point for anybody looking to get familiar with either Flask or Vue.

Once you get things up and running:

$ cd $THIS_DIR

$ export FLASK_APP=wsgi:app

$ cd web

$ npm install

$ npm build

$ cd ..

$ flask run

visit http://localhost:5000/views/ on your machine to see the dashboard!
