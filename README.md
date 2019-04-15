# plumed.github.io
Draft plumed.org website.

Here are some notes for updating the website

### Adding News
To add a news, just create a new .md file in the _posts directory named YYYY-MM-DD-Title-of-the-post.md
with the content of the news. No title needs to be specified in the file as it is taken automatically from
the filename.

### Adding Releases
Just update the [_data/releases.yml](_data/releases.yml) file. In all places where version numbers are used (currently: the download section, the doc section, and the download button in the header) Jekyll variables are used in order to implement the correct links and texts.
