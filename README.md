# Getting Started with Grin Motion - Animated Personal Portfolio & Responsive Template

This project is created with:

- `Create React App`: `18.2.0` version
- `node`: `v16.20.2` version
- `npm`: `8.1.2` version

If you face any error while installing, building, or running, make sure your `node` and `npm` versions are exactly like the above mentioned. You can check your node and npm version by opening a command prompt(terminal) and entering `node -v` and `npm -v` respectively.

If you have reached here in the instruction, you have extracted the file and opened the folder which contains `Grin` and `Instruction` folder.

## Step 1: How to install

Now type in the following command on the terminal window shown below:

```npm install```

If you have not made any error, you may/will see the following message at the bottom after installation is finished:

```added 1501 packages, and audited 1502 packages in 29s```

Remember installing requires an internet connection.

**Do not close the terminal window yet!**

## Step 2: How to run

After finishing step 1, now you can run the project.

Go to the terminal you have opened before and paste the following code:

```npm start```

If you have not made any errors, after the terminal window is done running, it will open a browser on [http://localhost:3000](http://localhost:3000).

If you see Grin Motion website on the opened window of the browser, Congratulation you just run the project.

App is now running in the development mode.

The page will reload when you make changes.

You may also see any lint errors/warnings in the console.

## Update Your Work Experience

Change the experience of your work in the file `data.json` located in `src/assets/data/data.json`.

The links to social like `instagram`, `gmail`, `privacy policy`, `press`, and `project links` are empty. Make sure to populate them inside the empty strings.

Only change the *value side* of the file which means for example `"position": "Entrepreneur and developer"` from `who_am_i` section is to be edited on the value side. Changing the letters of the key in this case `position` may bring unexpected errors.

You can upload your cv as a pdf file but make sure it's named to `cv` and uploaded in the folder which is in the `file` folder under the `public` folder of the root directory.

The images are located in the `public/image` folder you can see there are 4 folders but you can add more and it will work fine. Replace the images with yours but do not change their names.

Just by changing the above pictures and text including your cv you can upload it as your own website. No need to touch the code if you don't want to add and remove things that you like and dislike respectively.

## Update Code

The code is written in React and a basic knowledge of the framework is necessary if you want to dive into the code to manipulate the code.

If you have no knowledge on react-spring, It is fine. Since the first main purpose of the template is to teach from basic animation to the complex ones.

You can update the code as you wish but staying consistent to the rest of the page makes you an outstanding developer.

The animations can be animated whenever the user scrolls to each component all you have to replace is the `once: true` to `once:false`.

I personally don't recommend changing all the animations to that(`once: false`) because it may affect the user browser performance.

**Want to remove a section from the website? Say Press section?**

- *For the homepage:* in the js code of `App.js` bottom, you can see the components to comment out without having to delete a file.
- *For the detail page:* in the js code of `portfolio.js` starting from line 142, you can see the components to comment out without having to delete a file.

## Here is the list of components used from react-spring

Have a look at their [website](https://www.react-spring.dev) for some references:

### Components
- useSpring
- useSprings
- useSpringValue
- useTransition
- useChain
- useTrail

### Advanced API
- Spring Configs
- Events
- Controller
- SpringValue
- SpringRef
- Interpolation
- Async Animations

### Utilities
- useInView


## Step 3: How to build the project

After you are done updating and modifying the project following the above instructions or modifying the code by yourself, It is now time to build the project to be deployed on your hosting server.

On the previously opened terminal enter/paste the following code:

```npm run build```


Builds the app for production to the build folder.

It correctly bundles React in production mode and optimizes the build for the best performance.

If you have not made any mistake up to here you will see the following message:

```
The build folder is ready to be deployed.
You may serve it with a static server:

npm install -g serve
serve -s build

Find out more about deployment here:
https://cra.link/deployment

1 file(s) copied.
```

If you see the above message congratulations, you have successfully built the app ready to be deployed on your favorite hosting server.

The build folder will be found in the folder of Grin. Copy the insides of the build folder and paste it to your hosting server folder.

Now go to your designated website URL to see the website. Congratulations you are now Live!



