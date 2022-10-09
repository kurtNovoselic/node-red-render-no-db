# node-red-render

A wrapper for deploying [Node-RED](http://nodered.org) into the [Render](https://render.com/).

### Deploying Node-RED into Heroku

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy)

### Password protect the flow editor

By default, the editor is open for anyone to access and modify flows. To password-protect the editor:

Add the following user-defined variables.

* NODE_RED_USERNAME [default: `admin`] - the username to secure the editor with
* NODE_RED_PASSWORD - the password to secure the editor with
