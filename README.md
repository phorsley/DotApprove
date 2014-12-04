## Adding a new blog post

Posts are kept within the `_posts` directory. To add a new post...

1. Add a new post file. Don't forget the `<!--more-->` tag to indicate where
   the front page preview should end.
2. Preview the changes offline by running the server. Once running it will
   automatically update when you save a file, so no need to restart it.
   `cd /PATH/TO/PROJECT/DIR` followed by `./dev_serve.sh`
3. Commit the changes with git.
4. Push to github. (PerivanSolutions/DotApprove)
5. log into the webserve via ssh. `ssh perivan.co.uk`
6. Navigrate to the websites directory. `cd websites`
7. Sync changes from git and rebuild the site. `./sync_and_rebuild.rb`

Posts are written in 
[Markdown](https://help.github.com/articles/markdown-basics/), an extremely
friendly markup language for text documents.

More info can be found [here](http://jekyllrb.com/docs/posts/).

## Managing the submodules

Updating

    git submodule foreach git pull

Cloning

    git clone --recursive git://github.com/foo/bar.git
