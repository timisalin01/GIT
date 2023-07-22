**Unleash Your GitHub Contribution Graph with GitHub Contribution Bot!**

## 🚀 Introduction

Are you tired of your GitHub contribution graph looking like a noob with just a few commits and pushes? Do you dream of having a contribution graph that looks like a pro, filled with lots of commits? Well, look no further! GitHub Contribution Bot is here to rescue your contribution graph and make it shine!

The project harnesses the power of [Moment](https://www.npmjs.com/package/moment), an incredible JavaScript date library that allows you to parse, validate, manipulate, and format dates. With GitHub Contribution Bot, you can make commits on past dates by subtracting the years from a given date and even schedule commits over a period of regular days. The possibilities are vast, and you can get really creative with this code!

## 🛠️ Installation

Getting started with GitHub Contribution Bot is a breeze! Follow these simple steps:

1. Clone and fork the repository to have your own local version of the project.

   ```git-bash
   git clone https://github.com/timisalin01/green
   cd Green-Github
   ```

2. Install all the required packages by running the following command. This will create a directory named `node_modules` and install the necessary dependencies.

   ```javascript
   npm install
   ```

3. Now, it's time to run the project and witness the magic of the Moment package in action!

   ```javascript
   node index.js
   ```

   Voilà! You'll see the commit dates displayed in the terminal.

## 💻 Commits

GitHub Contribution Bot empowers you with two key functionalities:

1. **Subtract**: You can use the `subtract` function to make commits starting from a specified year. The greater the value of the year, the denser your graph will appear along the main axis. Here's an example of how to use it:

   ```javascript
   subtract(year, "y");
   ```

   For instance, to start commits from two years ago, you would use `subtract(2, 'y')`.

2. **Add**: The `add` function enables you to control the difference of commits between timestamps. By adjusting the value of days, you can make your contribution graph as dense as you like. Here's how to use it:

   ```javascript
   add(days, "d");
   ```

   For example, using `add(4, 'd')` would create commits with a four-day interval.

## 📞 Contact Me

If you have any queries or need assistance with the project, feel free to reach out to me through my [Instagram Profile](https://www.instagram.com/timisalin01/). 
So what are you waiting for? Get your GitHub Contribution Graph to stand out like a pro with GitHub Contribution Bot! Happy coding and commit graph designing! 🎉
