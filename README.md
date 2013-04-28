# blog

## Install: 

    apt-get install jekyll


## Writing a post

* Make a new markdown post in \_posts. Follow the apparent conventions.
* Use newlines between each sentence, because diffs works on a line basis.
* Image files go in assets/&lt;author\_name&lt;.
* Make a pull-request, get feedback, and wait for someone else to merge and deploy!


## Test locally:

    jekyll --auto --server

## Deploy master branch to server:
    
    ./_deploy.sh
