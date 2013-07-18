# Setup

```
$ git clone git@github.com:cloudapp/releases.git cl-releases
$ cd cl-releases
$ git remote add heroku git@heroku.com:cl-releases.git
```

# Building

```
$ rm -rf _site && bundle exec jekyll build
Configuration file: /Users/Larry/Sites/cloudapp/cl-releases/_config.yml
            Source: /Users/Larry/Sites/cloudapp/cl-releases
       Destination: /Users/Larry/Sites/cloudapp/cl-releases/_site
      Generating... done.
```

# Deploy

```
$ git push heroku master
```
