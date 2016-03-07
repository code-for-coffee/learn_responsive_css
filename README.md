## Learn Responsive CSS

This repository is meant to be forked, cloned, and played with. It contains the following file structure:

```bash
├── README.md # you are reading this
├── index.html # open in a browser
├── scripts
│   ├── app.js # boilerplate JS
│   └── jquery.js
└── style
    ├── style.css # ouput CSS from our Sass
    ├── style.css.map # map file
    ├── style.scss # primary sass file to watch 'sass -w style.scss'
    └── variables.scss # variables file imported by style.scss
```

#### Getting Started

* Clone this repository and navigate to it.
* Run `sass -w style/style.scss` to watch your Sass files.
* Open `index.html` in your browser.

#### Challenge: Break Points

* Resize the window for `index.html` in your browser.
* What changes?
* Can you identify the breakpoints for this web page?

#### Challenge: Meta Tag

* Can you describe which `<meta>` tag is responsible for making our page responsive?
* Why is this?
* What research can you find online about this tag?

#### Challenge: Adding Breakpoints

* In the `variables.scss` and `style.scss` are a few breakpoints/screen sizes to break at.
* Your challenge is to add **three more** breakpoints and elements to hide/show when they are available!
* Find breakpoints that mean something - perhaps a tablet screen size? Laptop screen size? Etc?
