# Kickstarter
##### Develop Modern Web Applications

### Introduction

The web moves fast. It's hard to keep up. This project provides a kickstarter for
developing modern web applications. The kickstarter here will allow you to launch
into developing your application and avoid dealing with common annoyances such as
setting up your build pipeline and doing standard user authentication.

As new technology emerges that catches my attention and seems to be worth the upgrade
I may switch and update this kickstarter accordingly. Therefore, all technology
in this kickstarter is liable to be swapped.

Currently this kickstarter is composed of:
  - Mongo
  - Node
  - Mongoose
  - Express
  - Elm

### KickStarter Snapshots

![Sign Up Page](/preview/sign-up-page.jpg)

![Sign Up Error](/preview/sign-up-page-error.jpg)

![Home Page](/preview/logged-in.jpg)

![Mobile Navbar Collapsed](/preview/mobile-navbar-collapsed.jpg)

![Mobile Navbar Expanded](/preview/mobile-navbar-expanded.jpg)

### Local Dependencies

- Mongo ~ 3.x
  - Currently 3.x, when the drivers get updated for 4.x I'll upgrade
- Node ~ 11.x
  - You can most likely use older versions of node if you need to
- NPM ~ 6.x
  - You can most likely use older versions of npm if you need to

### Set Up

```bash
cd frontend;
npm install;
cd ../backend;
npm install;
```

###### TODO after Fork

There are "TODO-STARTER" strings around the app for things you must fill in such as
the project name and description. Replace those after forking.

### Developing

Terminal Tab 1

```bash
cd frontend;
npm start;
```

Terminal Tab 2

```bash
cd backend;
npm run dev;
```

### Production

```bash
cd frontend;
npm run prod;
cd ../backend;
# Make sure env variables are set
npm run build;
```


### License

[MIT LICENSE](/LICENSE)
