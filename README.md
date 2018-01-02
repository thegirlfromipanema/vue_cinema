# Ultimate Vue.js Developers Course

Source code for the [Ultimate Vue.js Developers Course](http://bit.ly/2mPK8ny).

### Project 2: Vue.js Cinema

#### Demo
https://vue-cinema.herokuapp.com/ 

See the completed project here: // coming soon
#### Pre-installation

- Ensure [NPM](https://docs.npmjs.com) and [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) are installed on your system


#### Installation

1. Install this code on your local system

    **Option 1 (recommended)**

    1. Fork this repository (see top right corner)
    2. Clone the forked repository on your local file system

        ```
        cd /path/to/install/location

        git clone git@github.com:[your_username]/vuejs-cinema.git
        ```

    **Option 2 (easier)**

    This option is better if you're not a Github user or are not sure how to setup SSH keys

    ```
    cd /path/to/install/location

    git clone https://github.com/thegirlfromipanema/vue_cinema
    ```    

2. Install dependencies

    ```
    npm install
    ```

3. Create a `.env` file by copying the sample

    ```
    cp .env_sample .env
    ```

    Edit the .env file and replace any variables if needed

4. Start project

    ```
    npm run start
    ```

Your site will be available at *localhost:[PORT]* where `PORT` is whatever value is set in your `.env` file.

#### Lecture branches

Note that branches in the repo named `lecture/xxx` correspond to course lectures.
