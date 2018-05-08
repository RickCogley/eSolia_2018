# eSolia Inc English and Japanese Sites

Readme for the <https://esolia.com> and <https://esolia.co.jp> sites. 

## Latest iteration

As they say, we "[stand on the shoulders of giants](https://en.wikipedia.org/wiki/Standing_on_the_shoulders_of_giants "Wikipedia article about etymology of standing on the shoulders of giants")", and this site is certainly no exception.

This iteration can be summarized as follows: 

* Still using the world's fastest static site generator "Hugo" to generate the site from templates, css, javascript and images. 
* Using Bulma CSS library, with extensions and custom components.
* Using Ryo Gothic for the type face, via Adobe Typekit. 
* Connecting to eSolia [PROdb](https://esolia.com/prodb) for data.  
* Using the Mac app Codekit to compile SCSS and Javascript.
* Photography and Graphics by eSolia CEO [Rick Cogley](http://rick.cogley.info). 

### Go Hugo

[Hugo](http://gohugo.io) is a Static Site Generator, which makes it simple to use html "templates" to merge your css, javascript, images and content written in the [Markdown](http://daringfireball.net/projects/markdown/) format, into a publishable website.

About Hugo, we learn:

> Hugo is written for speed and performance. Great care has been taken to ensure that Hugo build time is as short as possible. We're talking milliseconds to build your entire site for most setups.

In fact, it takes far longer to upload the site to your web space, than it does for Hugo to generate it.

Hugo is downloadable as a single binary file, written in Go, which means it will run on just about any platform, just by running the file. There are no complex installations and dependencies to deal with.

Hugo is eSolia's preferred SSG. 

### Site Look

The look of this site comes from a couple of different components.

First, the stylistic base of the site comes from a the css library called ["Bulma"](https://bulma.io). About Bulma: 

> Bulma is an open source CSS framework based on Flexbox and used by more than 100,000 developers.

It allows you to have consistency in your basic styles, responsiveness to support mobile users, and acts as a great starting point for any site.

As for **Type Faces**, the main one is [Ryo Gothic](https://typekit.com/fonts/ryo-gothic-plusn) from Adobe Typekit (see also the auto-generated [colophon](https://typekit.com/colophons/fwz4gtk) for more info). We got some hints also from [Web Typography](http://webtypography.net) as well. 

The **icons** you see are from [Font Awesome](https://fontawesome.com/icons?d=gallery). 

The **photos** and most graphics on this site are by Rick Cogley, unless otherwise noted.

## Data

For the short posts and project lists on the home page, [news archive](https://esolia.com/post) and [success stories](https://esolia.com/success-stories) pages, we are pulling information from our company ERP system running on [PROdb](https://esolia.com/prodb), our cloud database. The [Info Request](https://esolia.com/info-request) form pushes info a table in PROdb as well, to allow for some automation. Additionally, we are protecting the info request form with Google [Re-Captcha](https://www.google.com/recaptcha/intro/android.html). 

## Hosting

This and a few other sites we manage, are hosted at the rock-solid [Webfaction](http://www.webfaction.com/?affiliate=rcogley). Great cost-performance for developers, in our opinion. We have not had trouble in years of use, and they respond very quickly to support requests.

DNS is hosted on Amazon Web Services [Route53](https://aws.amazon.com/route53/), a really robust and fast DNS service.

The [repository](https://github.com/RickCogley/eSolia_2018) for this site is hosted at [Github](https://github.com).

## TL;DR Thanks!

_Warm thanks and regards to:_

[Steve Francia](http://spf13.com) ([@spf13](https://github.com/spf13)) and [contributors](https://github.com/spf13/hugo/graphs/contributors) for the giant amount of work in creating Hugo, and to the Go language [team](http://golang.org/CONTRIBUTORS) itself. [Bjørn Erik Pedersen](http://bep.is) ([@bep](https://github.com/bep)) has been a great help on the Hugo [discussion forums](http://discuss.hugo.io)).

[@jaydenseric](https://github.com/jaydenseric) for ["barebones"](https://github.com/jaydenseric/Barebones) which taught me a skillful way to organize a site, and helped me modernize my front-end dev workflow.

[@ai](https://github.com/ai), [@ben-eb](https://github.com/ben-eb), [@moox](https://github.com/moox) and many others for the massive and important work on ["postcss"](https://github.com/postcss/postcss), ["postcss-cssnext"](https://github.com/MoOx/postcss-cssnext), ["cssnano"](https://github.com/ben-eb/cssnano) and other various modules, helping me to use the latest css, and get that transformed and bundled, ready for production.

[@jxnblk](https://github.com/jxnblk) for the wonderful ["basscss"](http://www.basscss.com/) css foundation library.  

[Jos Buivenga / Exljbris](https://exljbris.wordpress.com/about/) and [Joshua Darden / Darden Studio](https://www.dardenstudio.com/studio), for the beautiful type faces.

Lastly, I even have a [humans.txt](/humans.txt) file. [Humans.txt](http://humanstxt.org) is an attempt to standardize on a way of making a site colophon, in text format. If you [click](/humans.txt) it, you'll see some of the same information as on this page, in a simple text format.

## License

### Text Content License

Unless otherwise noted, the text content on this site is copyright eSolia Inc.

### Source License

Unless otherwise noted, the source content on this site is released under the [MIT License](http://opensource.org/licenses/MIT).


