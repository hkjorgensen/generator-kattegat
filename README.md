# Kattegat generator

This generator creates a ready-to-run [Kattegat application server](https://github.com/ClintH/kattegat), and client-side Javascript samples.

# Setup

Make sure you've already installed:
* [Node.js](http://nodejs.org/download/)
* [Yeoman](http://yeoman.io)

Once you've got Node installed, you can install Yeoman with:
```
$ npm install -g yo
```

Next, install the Kattegat generator

```
$ npm install -g generator-kattegat
```

# Making an app

Now that the setup tasks are out of the way, you are able to generate a new Kattegat app when ever you like.

Make a new directory and change to it:

```
$ mkdir myapp && cd myapp
```

And now run the Kattegat generator. It will ask you for a name of the app, or just press enter if you aren't fussed.

```
$ yo kattegat
```

It will take some time to run, and you'll see a lot of stuff scrolling by. After you're done, you can start your app:


```
$ node app
```

And then open it up in your browser to get started. You can read more about [Kattegat](https://github.com/ClintH/kattegat)
