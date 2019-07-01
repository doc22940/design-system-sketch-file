# Design-system-sketch-file 🌵
A repository for the [Design System Components](https://github.com/govau/design-system-components) Sketch file. To see more of the Design System, view the [documentation website](https://designsystem.gov.au/).

## Contributing

We are using Kactus for version control of our Sketch Files. To contribute, download [Kactus](https://kactus.io/) and view the starting guide.


### Non-npm users

#### Cloning

1. Open Kactus
2. Click File > Clone Repository
3. Click on the `URL` tab
4. Paste the following URL: https://github.com/govau/design-system-sketch-file.git

![image](https://user-images.githubusercontent.com/20184809/60417531-fcc3f580-9c23-11e9-8fe5-caabbfea5d96.png)


5. Click `Clone`

#### Generate Sketch file

In your Kactus window, click `Regenerate Sketch file from JSON` to generate a sketch file.

![image](https://user-images.githubusercontent.com/20184809/60417158-08fb8300-9c23-11e9-8711-e412ce2c1430.png)

Then click `Open file`.

Now make any changes to the Sketch file and push the changes up. For more information on using Kactus, please view their [starting docs](https://kactus.io/help/how-to/).


### npm users

Clone the repository and then run the following commands:

```
$ npm i
$ npm run kactus-build
```

This will generate a sketch file in the root directory. Make all changes to this file, and then push up any changes.



## Building

The following is neccessary only for pushing out changes to production.

Once the change is made in your branch, run the following commands to create a zip file in the public folder, which contains the latest version of the Design System Sketch file.


```
$ npm i
$ npm run build
```
