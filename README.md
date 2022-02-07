# Toy Project 📚

## About the Project ℹ️

This project was put to let you learn about, as well as practice, the common tools, libraries and frameworks used within the BetterDay team. 😺

The app you are going to build should include the most basic CRUD functionalities! In the example of a BlogPost application: a user should be able to create a post, edit a post, delete a post, and read all the posts 👀. In addition to that, you should also introduce the authentication & authorization processes 🤦‍♂️. 

While developing the app, make sure that you do your best to learn something new and get the most out of it. Below, you will be given a certain set of tools and a brief instruction on how to proceed with the project. Apart from this and below, you are free to be as much creative as you can and add extra features to your app. Best of luck! 💪

### 🚩 *Your target should be*: 

* To build a fully functional CRUD application, from front to back.
* To try to build everything from scratch (i.e. hooks/validation/guards/common items/etc.).
* To avoid using third party libraries other than the ones given.
* To be as much creative as you can.
* To try to complete within 2 weeks.

***

## 🧰 Build With
> These are the list of libraries and tools you should be using.

<p align="center">

|Front End|Back End|Common|
|---------|---------|-----|
|[React.js](https://reactjs.org/) |[Nest.js](https://nestjs.com/)|[TypeScript](https://www.typescriptlang.org/)|
|[Material UI](https://mui.com/)|[MySQL](https://www.mysql.com/) / [MongoDB](https://www.mongodb.com/)|[Docker](https://www.docker.com/)|
|[Axios](https://axios-http.com/docs/intro)|[Prisma](https://www.prisma.io/)|[Github](https://github.com/)|
|[React Router V6](https://reactrouter.com/)|[Passport](https://www.passportjs.org/) & [JWT](https://jwt.io/)|[Lodash](https://lodash.com/)|
|[React Native](https://reactnative.dev/)|[Redis](https://redis.io/)|[date-fns](https://date-fns.org/)|

</p>

***

## 🦴 A Quick Starter
> If you want something to start with and build your app on top of it, you can use the default app set up by [Alex](https://github.com/alexfinset). Go ahead and clone the repo. You can follow the instructions provided in this [README](https://github.com/alexfinset/user-auth#readme).

1. Clone the repo
   ```bash
   # In your machine locate to Desktop and run the following:
   $ git clone https://github.com/alexfinset/user-auth.git
   ```
2. Install the dependencies and run the app
   ```bash
   # install the dependencies
   $ yarn install

   # run the app in the development mode
   $ yarn start

   ```
Locate to http://localhost:3000 and you will be able to see the app! 

![alt text](https://github.com/isik-finset/toy-project/blob/main/assets/template.png?raw=true)

***

## ✅ Final App
> Whereas, if you want to see how the final version should look like and function, you can checkout the BetterBlog app created by [Islom](https://github.com/isik-finset). Note that this is just an example, so aim to make a better version of it. See further details in this [README](https://github.com/isik-finset/betterBlog/blob/master/README.md)

### 1. Clone the repo
* Clone
    ```bash
    # In your machine locate to Desktop and run the following:
    $ git clone https://github.com/isik-finset/betterBlog.git
    ```
### 2. Install the dependencies
* Dependencies
    ```bash
    # cd into the new directory created in your Desktop:
    $ cd betterBlog

    # You will have two folders in here: back-end & front-end
    # cd into front-end
    $ cd front-end

    # install the dependencies for front-end
    $ yarn

    # after you are done cd into back-end
    $ cd ../back-end

    # install the dependencies for back-end
    $ yarn
    ```
### 3. Run the App
* Front-End
   ```bash
   # This will run the front in development mode
   $ yarn start
   ```
* Back-End (runs in you machine)
   ```bash
   # This will run the back in development mode
   $ yarn start:dev
   ``` 
* Docker for Database & Back-end
   ```bash
   # This will create a virtual machine and open ports for back and db
   $ docker compose up -d

   # You can also easily checkout the db tables through:
   $ npx prisma studio
   ```
Now you can locate to http://localhost:3000 and you will be able to see the app!
 
![alt text](https://github.com/isik-finset/toy-project/blob/main/assets/home.png?raw=true),
![alt text](https://github.com/isik-finset/toy-project/blob/main/assets/read.png?raw=true),
![alt text](https://github.com/isik-finset/toy-project/blob/main/assets/login.png?raw=true),
![alt text](https://github.com/isik-finset/toy-project/blob/main/assets/write.png?raw=true),

***

## 🏗️ Further Improvements regarding BetterBlog
> There is a lot of room for improvement throughout all parts of the app. I suggest starting small: 

1. **Front End**
   * Create [Dialogs](https://mui.com/components/dialogs/) to notify the user about a certain action (i.e. when user registers, publishes, edits, deletes, and etc.).
   * Improve validation (UX).
   * Improve the quality and performance of the custom hooks in the hooks folder.
   * Work on Guards and make it more efficient.
   * Design could be improved as well.
<br></br>
2. **Back End**
   * Controllers and Services for both Users and Posts could be readjusted to decrease data redundancy.
   * Add [bcrypt](https://www.npmjs.com/package/bcrypt) to hash the user password.
   * Add the logic for calculating read time based on the number of words in the body of a post.
   * Search API could also be added.
   * Find ID / Password logic.


***

## 👷 Contributors
<a href="https://github.com/isik-finset" target="blank"><img src="https://avatars.githubusercontent.com/u/97070258?v=4" width="50" alt="Isik Logo" style="border-radius:50%" /></a>
<a href="https://github.com/alexfinset" target="blank"><img src="https://avatars.githubusercontent.com/u/86999057?v=4" width="50" alt="Isik Logo" style="border-radius:50%" /></a>
<a href="https://github.com/jaeyong-gitple" target="blank"><img src="https://avatars.githubusercontent.com/u/995776?v=4" width="50" alt="Isik Logo" style="border-radius:50%" /></a>
