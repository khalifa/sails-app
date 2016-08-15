# sails-js

## Getting Started
1. install sails globally with npm
    ```
    sudo npm -g install sails
    ```

2. create new sails app
    ```
    npm install -g sails-js
    ```

3. start the server
    ```
    cd sails-js
    sails lift
    ```

4. app is ready and running at:
    http://localhost:1337/

## Install dependencies
1. project dependencies package.json
    ```
    npm install
    ```

2. front-end dependencies with bower
    1. init bower
        ```
        cd assets
        bower init
        ```
    2. describe dependencies bower.json
    3. install dependencies
        ```
        bower install
        ```
    4. configure pipeline.js
        1. add bower css to load
        2. add bower js to load

