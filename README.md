This repo is no longer in use, please see https://github.com/foundersandcoders/fac-new-website for our current website repo
---

Out of date documentation follows:
---
# Founders & Coders Website

Get involved! https://github.com/foundersandcoders/oursite/pulls

Our site uses [Harp](http://harpjs.com/).
```
$ npm install -g harp
$ cd Desktop
$ git clone https://github.com/foundersandcoders/oursite.git
$ cd oursite
$ harp server _harp
```

Pull requests should be made with master as the base. Master is uncompiled so leave your pull requests uncompiled too.

The repo owner will merge your pull, pull master into gh-pages, compile and push to gh-pages.

----

The process for the repo owner is as follows:
```
$ git checkout gh-pages
$ git merge master
$ harp compile _harp .
```
Then commit and push the changes back to GitHub.

----

### Domain hosting

The domain is registered on @sofer's namecheap account and the DNS records are hosted on Cloudflare.
