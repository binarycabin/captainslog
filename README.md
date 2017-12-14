![](https://i.imgur.com/z7mUaGg.png)

# Captain's Log
## A Tailwind CSS Wordpress Starter Theme
===

Captain's Log is a super barebones starterkit pulled right from the https://underscores.me/ starter theme with [Laravel Mix](https://github.com/JeffreyWay/laravel-mix) and [TailwindCSS](https://tailwindcss.com) installed

## Installation

Simply copy the theme and find/replace all instances of "captainslog" with your theme name. Then update your theme name in ./style.css

Then run npm install to install the packages:

```
npm install
```

Finally, run the command below to process Laravel Mix

```
npm run dev
```

Once that's done, you should be able to add any Tailwind classes to your theme and be able to start customizing!

Note that all custom CSS can be added to ./src/sass/theme.scss and will compile to ./dist/css/theme.css after running "npm run dev". the ./style.css file is not pulled in and only used for Wordpress to identify your theme. This can be enabled simply by uncommenting line 120 of functions.php
