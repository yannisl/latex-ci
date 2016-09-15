# latex-ci

Cloud based testing and continuous integration for LaTeX documents is not common. Most users will either use their local computer or 
use a cloud based service to render their documents.

This is a minimal configuration and set-up to use a github repository, travis-ci for continuous integration and to upload automatically to a cloud storage such as AWS S3.

I don't claim this is the best or the most optimum way of running and testing documents, but it works for me.

## Prerequisites

1.  A Github account a and basic understanding of using Git.
2.  A travis-ci account.
3.  Dowload the travis-cli and install any necessary pre-requisites.
4.  An AWS account.
5.  Keys for your buckets.

## Setting up the Project on travis-ci

Once you have an account on travis-ci, you need to tell travis-ci which repository you want to integrate. Go to

````
https://travis-ci.org/profile/<user>
````

and check the repository you want to set-up. Follow up the instructions on the page to sync with Github etc.

### Environment settings

You can either encrypt your key accounts and secrets on the travis-cli and include them in your travis.yml file or you can set this on the travis website. I prefer that these are included in the yaml file as it minimizes hopping in and out of the console and into the browser.


















