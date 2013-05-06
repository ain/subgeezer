# subgeezer
Subgeezer is a command-line tool that converts SVN repository to Git.

In addition to converting the repository, you can provide `-n` option which will
prompt you to convert SVN `username` to Git `Forename Surname <name@email.com>`
format.

## Usage
`subgeezer [options] svn_root_url git_repository_path`

## Options
    -h, --help    Display help
    -n            Prompt for Git User <email> to convert SVN usernames in log

## Example usage:
`subgeezer -n http://swfobject.googlecode.com/svn ~/swfObject.git`

NB! Make sure to provide root URL with the trunk in it!

## Requirements
svn2git - https://github.com/nirvdrum/svn2git

## Support
File an issue on Github or ping [@tekkie](http://twitter.com/tekkie) on Twitter.