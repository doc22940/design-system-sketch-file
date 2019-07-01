# Design-system-sketch-file
A repository for the Design System Components Sketch file

## 🌵 Contributing

We are using Kactus for version control of our Sketch Files. To contribute, download [Kactus](https://kactus.io/) and view the starting guide.


### Non-npm users

In your Kactus window, click `Regenerate Sketch file from JSON` to generate a sketch file.

![image](https://user-images.githubusercontent.com/20184809/60417158-08fb8300-9c23-11e9-8711-e412ce2c1430.png)

Then click `Open file`.

Now make any changes to the Sketch file and push up changes. 


### npm users

Running the following commands

```
$ npm i
$ npm run kactus-build
```

Will generate a sketch file in the root directory. Make all changes to this file, and then push up any changes.



## Building

The following is neccessary only for pushing out changes to production.

Once the change is made in your branch, run the following commands to create a zip file in the public folder, which contains the latest version of the Design System Sketch file.


```
$ npm i
$ npm run build
```
