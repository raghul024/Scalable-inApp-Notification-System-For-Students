# Scalable inApp Notification System For Students

This project is devoloped exclusively for student where they can check their academic progress and if any new announcements is pushed by institution they get an in app notification as reminder for example as such in facebook...etc.

## Getting Started

 I have tested the complete source by using local host and xampp server. It works efficiently if you upload the phplogin sql file in clearDB as its database in Heruko open source application.
 
 There are a few steps we need to take before we create our secure login system and notification system , we need to set up our web server environment and make sure we have the required extensions enabled.
 
 ## API's 

  <b>Index.html</b>       — Login form created with HTML5 and CSS3, we don't need to use PHP in this file so we can just save it as HTML.
  
  <b>style.css</b>        — The stylesheet (CSS) for our secure login app.
  
  <b>authenticate.php</b> — Connect to the database, validate form data, retrieve database results, and create new sessions.
  
  <b>logout.php</b>       — Destroy the logged in sessions and redirect the user.
  
  <b>home.php </b>        — Basic home page for logged in users.
  
  <b>profile.php</b>      — Select the user's account from our MySQL database and display the result.
  
  For <b>notification system</b> i have used <b>Engagespot</b> for free push notification services:
  
  Link : https://engagespot.co/free-web-push-notifications/
  
### Prerequisites

To host as an public website u can execute the follwing code in <b>Heruko , Amazon Web Services (AWS), WordPress , Microsoft Azure</b> 

To excute the login and academic profile page we need to install the latest version of <b>xampp</b>

To install the latest version use the link given below:
  
 link: https://www.apachefriends.org/index.html
```
Give examples
```

### Installing

<b>Step 1>
 
We need a login form for our websites users, so they can interact with it and enter their details, we will be using HTML and CSS 

Open up the index.html file with your favorite code editor and save it

<div align="center">
    <img src="/Screenshots/index.png" width="400px"</img> 
</div>


End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc
