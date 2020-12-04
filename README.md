# slide-templates

Use this when giving LFE presentations!


## Step 0

Make sure you have `git`, GNU `make` and `docker` installed.

## Step 1

Clone this repo:

``` shell
$ git clone git@github.com:lfe/slide-templates.git my-preso
```

## Step 2 

Run the server:

``` shell
$ cd my-preso
$ make run
```

Then open up your browser to [localhost:1313](http://localhost:1313).

## Step 5 ... No, 3!

Edit the slides:

* Open up `./content/_index.md` and edit as needed for your LFE presentation.
* If you've still got `make run` running, changes in the Markdown file will auto-load in your browser.


## Resources

To see what you can do with your Markdown slides, see
[these examples](https://github.com/dzello/reveal-hugo#demos).
