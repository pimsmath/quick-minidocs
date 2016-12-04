### How to create a miniddocs site?

I made a folder called `quick-minidocs` with a subfolder called `markdown` containing [markdown](https://daringfireball.net/projects/markdown/) files, and a `contents.json` file specifying some organizational structure. I placed an image file called `pims3.png` in the directory. Then I ran this command in a terminal in the `quick-minidocs` folder:

```minidocs markdown/ -c contents.json -o site -l pims3.png```

That process generated a new directory called `site` which contains the generated site and includes the `pims3.png` image. The file `index.html` in `site` is the main file containing the minidocs web site.


![minidocs](https://wwejubwfy.s3.amazonaws.com/1._bash-2016-08-26-23-15-38.jpg) 