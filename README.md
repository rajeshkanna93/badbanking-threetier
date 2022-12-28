# Bad Banking - Three Tier

***BADBANK IS AN ONGOING PROJECT - APP USAGE WILL CHANGE AS MORE FEATURES ARE INTEGRATED***
<br />
<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#images">images</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
"Bad Bank" is my MIT capstone application with a front-end, back-end, and database. The Bad Bank name refers to the project's earlier iteration where it was a banking application that was not secure (i.e. no login, no administrative privileges). However, we will be using firebase authentication and authorization to create different levels of authorization to turn "Bad Bank" into a more secure bank - a lot like what a really company might use. This project was created in my effort to learn how to build a complete 3-tier application and it will continue to grow as my knowledge of application development grows. It is also designed to be an easy way to show off things I've learned in my Master's Full Stack Development program. 
<!-- [![Product Name Screen Shot][product-screenshot]](https://example.com) -->


### Built With
* [Firebase authentication](https://firebase.google.com/)
* [React](https://reactjs.org/)
* [Node.js](https://nodejs.org/en/)
* [Docker](https://www.docker.com/)
* [MongoDB](https://www.mongodb.com/)
* [Bootstrap](https://getbootstrap.com/)



<!-- GETTING STARTED -->
## Getting Started

Bad Bank is hosted by google cloud services. You can navigate to the url below to see the most recent published version. To download and make edits to the code, see Prerequisites and Installation.

View Bad Bank: https://badbank-docker-edvmxc3iaa-uw.a.run.app

### Prerequisites


* npm
  ```sh
  npm install npm@latest -g
  ```


### Installation
To edit and run locally on your machine

1. Clone the repo
   ```sh
   git clone https://github.com/rajeshkanna93/badbanking-threetier
   ```
2. Install NPM packages
   ```sh
   npm install
   ```
3. Run the Node server
   ```sh
   node index.js
   ```
4. Navigate to [http://localhost:3000/](http://localhost:3000/) to run the application


<!-- USAGE EXAMPLES -->
## Usage
Create Account - allows you to create a new users for the bank (you can see the users you've created in the AllData tab) <br />
Login - allows you to login to your bank account <br />
Deposit - allows you to deposit money into your account <br />
Withdraw - allows you to withdraw money from your account <br />
Balance - displays account balance <br />
AllData - for the admin users of the bank - will show all data of all the users of the application <br />
<!--
Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_
-->


<!-- ROADMAP -->
## Roadmap

Front end modifications

A Node.js server 

A MongoDB database and data abstraction layer

API integration

Connection of the front end and back end

Authentication 

The application deployed to Mongo DB

Development of additional features:
* Roles for different users, such as a bank employee vs customer (authorization)
* Money transfer between users
* Account types, such as checking vs savings accounts
* Assignment of random account numbers to new accounts
* User profile updates that are persistent
* Check deposit by taking a picture of the check

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. 

## Images

![alt text](https://rajeshkanna93.github.io/images/bb1.png?raw=true)
![alt text](https://rajeshkanna93.github.io/images/bb2.png?raw=true)
![alt text](https://rajeshkanna93.github.io/images/bb3.png?raw=true)