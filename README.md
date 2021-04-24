# This is the source code for the website published under github.io

## Credits
Example site modified from https://github.com/gohugoio/hugoBasicExample

## How to create a website with GitHub Pages

Youtube tutorial: [How to create a blog with Hugo and GitHub Pages](https://www.youtube.com/watch?v=LIFvgrRxdt4)

### Notes
- For GitHub managed DNS name repository eather **<username>.github.io** or **<organisation>.github.io**. More info here: [GitHub getting started with GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-**site**) 
- It is suggested to use separate repository for deployment (build files) and separate for source code (add deployment repo as submodule inside the directory: *public* in your source code)
- Run `hugo -t <name of the theme>` to build the website