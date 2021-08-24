# My portfolio, created for [andrewborstein.com](http://andrewborstein.com)

## Background

This website was first created in 2015 (!), with mostly minor content updates since. The move to 11ty is still ongoing, so some of these installation steps may be incomplete.

## Installation

**Hosting on Netlify**
I recently removed Grunt as a build tool dependency and moved my site hosting to Netlify. All files are completely static (for the time being), but they also live in a `/public` folder instead of the root. If you don't use Netlify, feel free to move everything back into the  root folder instead.

**Set your own Google Analytics ID**
Make sure to set `analyticsId` to your unique GA account id inside the `Google Analytics` script tag at the bottom of the `<body>`, if you want to use your own Google Analytics account.
## Using the `gh-pages` branch

Download the `gh-pages` branch if you want a bare-bones no-dependency website. As long as you have a valid `index.html` in the root of the folder, you should have [free hosting from Github](https://pages.github.com/).

## Using the `eleventy` branch

Download the `eleventy` branch if you want a more modern setup using [Eleventy](https://11ty.dev/) to compile different formats into HTML and enable templating. See installation steps below, although I still need to write something up on how to host with Eleventy.

**Installation**

0. Install [Git](https://www.atlassian.com/git/tutorials/install-git) & [Node/NPM](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm/)
1. Get a copy of this git repository locally by [downloading a zip file](https://github.com/andrewborstein/portfolio/archive/refs/heads/eleventy.zip) or [forking the repo](https://docs.github.com/en/get-started/quickstart/fork-a-repo#forking-a-repository) and cloning it to your machine.
2. Open the folder in a terminal window, e.g. `$ cd path/to/portfolio`
3. Check out the `eleventy` branch if it's not the default `$ git checkout eleventy`
4. Install the package dependencies `$ npm install`

**Developing Locally**

1. Start a webserver with `$ npm start` where saved files are automatically re-compiled.
2. View the website in your browser at http://localhost:8080.

**Create content**

This step is still very much a work in progress. So you're kind of on your own to tinker and add/remove/modify stuff as you want.

## FAQ

**Can I copy your site and publish my own version of it?**

Yes! Seriously, do whatever you want with it. Just don't, like, sell it for profit without maybe dropping me a line first 😄

**Something doesn't work**

I rarely have time to make changes to the site, so I'm sure lots of stuff will become old and broken over time. But I love fixing bugs! So don't hesitate to reach out at andrew@andrewborstein.com if you find an issue.

**How did you get started in web development? What's your story?**

I'm flattered that anyone would be curious — I'll (hopefully) write a blog post about that soon. The short answer is that I don't have a CS degree and I stumbled my way through to where I am now. Lots of ups and downs and hard work and lucky breaks and helpful peers and mentors.

**Do you have any advice for someone new to web development?**

Also great fodder for an eventual blog post, but basically it's two things:
1. Build stuff. Any stuff. More stuff. Never enough stuff.
2. Find a way to build stuff in any kind of professional capacity.

## Feedback
Any questions? Any steps missing or wrong? Email me at andrew@andrewborstein.com
