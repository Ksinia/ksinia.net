It's a source for [my resume](https://ksinia.net/cv/) build by [JSON Resume](https://jsonresume.org/) technology with [kendall theme](https://github.com/Ksinia/jsonresume-theme-kendall) with my alterations.

### How to build a resume

`docker-compose run build` will generate `public/cv/gulyaeva.html` file from `cv/resume.json` using [resumejson](https://jsonresume.org/).

### How to serve resume locally

`docker-compose up serve`

Then resume will be available by [http://127.0.0.1:4000](http://127.0.0.1:4000)
