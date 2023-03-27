# React_First_Practical-without_using_create-react-app-


In this practical I have created a react app without using "npm create-react-app"

I used babel-core,-cli,-env to do any transformations on our code, env for transform ES6+ into more traditional javascript and the react preset does the same, but with JSX instead, cli for ompile files from the command line.

Then use webpack for bundling different types of files,it also help in loading the server using different plugins like HMR.

Then I create a Folder structuer like this:

      .
      +-- public
      | +-- index.html
      +-- src
      | +-- App.css
      | +-- App.js
      | +-- index.js
      +-- .babelrc
      +-- .gitignore
      +-- package-lock.json
      +-- package.json
      +-- webpack.config.js
Till this it is only Ready for the development.

For the Production Part I divided the webpack.config.js into two part:
1. webpack.config.dev.js - for the development purpose.
2. webpack.config.prod.js - for the production purpose.

![Screenshot from 2023-03-17 19-53-49](https://user-images.githubusercontent.com/122250114/225932223-4d9b69bd-ef43-4f49-9f37-b5e7cd728322.png)

And in my package.json file 
<img src="https://github.com/MdKAMRAN7255/SPA_practise/blob/screenshot/Screenshot%20from%202023-03-17%2019-55-17.png">
Inside the Script i put build for production and build-dev for development.
And on "npm run start" it only open build-dev 

So, my react page will look like this after "npm-start"
<img src="https://github.com/MdKAMRAN7255/Screenshot/blob/MdKAMRAN7255-patch-1/Screenshot%20from%202023-03-17%2020-00-43.png">







