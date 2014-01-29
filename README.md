# subgeezer
Subgeezer is a command-line tool that converts SVN repository to Git.

In addition to converting the repository, you can provide `-n` option which will
prompt you to convert SVN `username` to Git `Forename Surname <name@email.com>`
format.

## Usage
`subgeezer [-hnbr] svn_root_url git_repository_path`

## Options
    -h            Display help
    -n            Prompt for Git User <email> to convert SVN usernames in log
    -b            Do not convert branches (for svn2git --nobranches)
    -r            Root is trunk without tags and branches (for svn2git --rootistrunk)

## Example usage
`subgeezer -nb http://swfobject.googlecode.com/svn ~/swfObject.git`

NB! Make sure to provide root URL with the trunk in it!

## Requirements
svn2git - https://github.com/nirvdrum/svn2git

## Support
[File an issue](https://github.com/ain/subgeezer/issues/new) on Github or ping [@tekkie](http://twitter.com/tekkie) on Twitter.
