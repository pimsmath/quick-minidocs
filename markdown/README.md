


This is an example site built using [`minidocs`](https://github.com/freeman-lab/minidocs). Minidocs is a lightweight framework for documentation and online textbooks. This site explains how to create a minidocs site, how to deploy it locally, and how to rapidly deploy it to the internet using `surge`.

### Create

I installed `node.js` to get the node package manager `npm`. I used `npm` to install `minidocs` and `http-server`.

I created the site by making a folder called `quick-minidocs`. I created a subfolder called `markdown` containing [markdown](https://daringfireball.net/projects/markdown/) files, and a `contents.json` file specifying some organizational structure. Then I ran this command in a terminal in the `quick-minidocs` folder:

```minidocs markdown/ -c contents.json -o site -l pims3.png```

That command generated a new subdirectory called `site`. To view the site, I deployed it locally by entering the `site` subdirectory and running `http-server`. I then viewed the site in my browser.

I deployed the site to the internet using `surge.sh`.

### Extend

I showed how to enrich minidocs by adding extensions to:

* include mathematical notation using [MathJax](https://www.mathjax.org/)
* share your site's code using [GitHub](https://github.com/)
* launch Jupyter pages from your site using [Binder](http://mybinder.org/)

### License and Source

This site was created by [James Colliander](http://colliand.com) and is freely available under the [MIT License](./LICENCE). Click here for [more information on the MIT License](http://choosealicense.com/licenses/mit/). 

The source code is available here on Github.