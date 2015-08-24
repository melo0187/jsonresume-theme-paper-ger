# JSON-Resume-Paper - German version

This is a German theme for [JSON Resume](http://jsonresume.org/).
It is based on [jsonresume-theme-paper](https://github.com/TimDaub/jsonresume-theme-paper) from Tim Daubenschütz.
Head over to his repository to find out more.

I want to clarify that I do not think this is the right way to go for theme translation. From what I understand there is no translation / multi-language support in [JSON Resume](http://jsonresume.org/), yet. The schema does not support it, nor do the resume-cli or themes. See also the open issue [Internationalization](https://github.com/jsonresume/resume-schema/issues/35).
This is why I do not intend to publish this on npm.

However if like me you feel the need to get a German version of your paper themed CV, clone this repo and get started.

## Getting started
This is what you need to do, to get your German, paper themed CV (assuming you have a complete and valid resume.json).

###Requirements
To use this, this is what you'll need:

- [node.js](http://howtonode.org/how-to-install-nodejs)
- [npm](http://howtonode.org/introduction-to-npm)

### Install the resume command line

We're going to use the official [resume-cli](https://github.com/jsonresume/resume-cli) to generate our CV.

Go ahead and install it:

```
npm install -g resume-cli
```

### Install npm packages

We need to install the dependencies. `cd` into the theme folder we just downloaded and run:

```bash
npm install
```

This will read the local `package.json` and install the packages listed under `dependencies`.

### Get your CV
Copy your complete and valid resume.json into the theme folder.

While inside the theme folder, simply run:

```
npm start
```
This will run the start script defined in package.json (in our case resume serve).
The output will look something like this:

```
Preview: http://localhost:4000
Press ctrl-c to stop
```

You should now see the CV in your browser and can use it's built in print feature to export your CV as pdf.


## License

Available under [the MIT license](http://mths.be/mit).
