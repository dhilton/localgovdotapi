# How to contribute

Firstly, thank you for helping.



## Testing

You need to install flex(https://github.com/pipermerriam/flex) to run the validator.

Please validate your swagger definitions (we're using 2.0) using ./validate.sh 
This will check each YAML file in the repo to make sure it complies with the 2.0 standard for swagger.

## Submitting changes

Please send a [GitHub Pull Request to opengovernment](https://github.com/opengovernment/opengovernment/pull/new/master) with a clear list of what you've done (read more about [pull requests](http://help.github.com/pull-requests/)). When you send a pull request, we will love you forever if you include RSpec examples. We can always use more test coverage. Please follow our coding conventions (below) and make sure all of your commits are atomic (one feature per commit).

Always write a clear log message for your commits. One-line messages are fine for small changes, but bigger changes should look like this:

    $ git commit -m "A brief summary of the commit
    > 
    > A paragraph describing what changed and its impact."

## Coding conventions

It's YAML so please run the swagger validator or at least check that the file is valid YAML before commiting to your local branch.
