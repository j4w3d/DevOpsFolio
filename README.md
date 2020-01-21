# DevOps Portfolio ⚡️ [![GitHub](https://img.shields.io/github/license/j4w3d/DevOpsFolio?style=for-the-badge)](https://github.com/j4w3d/DevOpsFolio/blob/master/LICENSE) ![GitHub stars](https://img.shields.io/github/stars/j4w3d/DevOpsFolio?style=for-the-badge) 


## A clean, beautiful and responsive portfolio template for DevOps!


<p align="center"> 
  <kbd>
<img src="src/assests/images/portfolio.gif"></img>
  </kbd>
</p>


Just change `src/porfolio.js` to get your personal portfolio . Feel free to use it as-is or customize it as much as you want. 

But if you want to **contribute** and make this much better for other DevOps have a look at [Issues](https://github.com/j4w3d/DevOpsFolio/issues).


If you created something awesome and want to contribute then feel free to open Please don't hesitate to open an [pull request](https://github.com/j4w3d/DevOpsFolio/pulls).


## Sections 
✔️ Summary and About me\
✔️ Skills \
✔️ Open Source Projects Connected with Github\
✔️ Big Projects\
✔️ Achievements And Certifications 🏆\
✔️ Blogs\
✔️ Talks\
✔️ Podcast\
✔️ Contact me

To view a live example, **[click here](https://jsalim.github.io/)**


## Getting Started 🚀

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

You'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer

```
node@v10.16.0 or higher
npm@6.9.0 or higher
git@2.17.1 or higher
```

---

## How To Use 🔧

From your command line, clone and run developerFolio:

```bash
# Clone this repository
$ git clone https://github.com/j4w3d/DevOpsFolio.git

# Go into the repository
$ cd DevOpsFolio

# Install dependencies
$ npm install

```
## Github Setup For Open Source Projects

### Genrate a Github personal access token using these [Instructions](https://help.github.com/en/github/authenticating-to-github/creating-a-personal-access-token-for-the-command-line) `Make sure you don't select any scope just generate a simple token`

Copy the token and open Chrome Developer Console to convert your token to base64 so github do not revert your token when you push your token to git

```bash
# Open your Chrome Developer Console console paste the token inside btoa
$ btoa("YOUR GITHUB TOKEN")
```

Copy your converted token and paste it in `/src/portfolio.js`

```javascript
  const openSource = {
  /* Your Open Source Section to View Your Github Pinned Projects */
  /* To know how to get github key look at readme.md */
  
  githubConvertedToken: "Your Github Converted Token",
  githubUserName: "Your Github Username"
};
```


## Change and customize every section according to your need.

### To Change website content go to `/src/portfolio.js` and change content according to yours.

```javascript
/* Change this file to get your Personal Porfolio */

const gretting = {
  /* Your Summary And Gretting Section */
  title: "Hi all 👋 I'm J@wed",
  subTitle: "A passionate DevOps Engineer 🚀.
  resumeLink: "google doc link"
};

const socialMediaLinks = {
  /* Your Social Media Link */
  github: "https://github.com/j4w3d/",
  linkedin: "https://www.linkedin.com/in/j4w3d/",
  gmail: "jawed.eternal@gmail.com"
};


const skillsSection = { .... }

const openSource = { .... } 

const bigProjects = { .... }

const achievementSection = { .... }

const blogSection = { .... }

const contactInfo = { .... }

```


## Technologies used 🛠️

- [React](https://reactjs.org/)
- [graphql](https://graphql.org/) 
- [apollo-boost](https://www.apollographql.com/docs/react/get-started/) 

## illustrations
- [UnDraw](https://undraw.co/illustrations)

## Deployment 📦 
Once you have done with your setup. You need to put your website online!
I highly recommend to use [Github Pages](https://create-react-app.dev/docs/deployment/#github-pages) to achieve this on the EASIEST WAY



## License 📄

This project is licensed under the MIT License - see the [LICENSE.md](./LICENSE) file for details




## For the Future 
If you can help us with these. Please don't hesitate to open an [pull request](https://github.com/j4w3d/DevOpsFolio/pulls).

- Connect with LinkedIn to get Summary, Skills, Education and Experience

- Move to Gatsby

- Add More Sections and Move to Multi Page

- Add Podcast Section and Video Section


