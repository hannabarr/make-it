# make-it
The lay of the land
Documentation:
    http://localhost:4000/documentation/

Where blog posts go:
    _posts/design/
    format: YYYY-MM-DD-[blog-post-title].md

Global images (like logos)
    assets/img/

The 'directory' section
    pages/ : Contains .md files detailing all the available posts in a section.
             The sections are the directories in _posts/

Important things in \_data:
    navigation.yml  : Update the nav bar
    authors.yml     : Author information
    socialmedia.yml : Update social media links
    services.yml    : Footer links
    network.yml     : Footer links
    language.yml    : Translate the theme to diff languag

Purpose of other folders:
    _layouts    : The HTML for various page templates
    _includes   : Other HTML for componenets of pages
    _drafts     : Where blog posts go that arent displayed yet?
    _site       : Contains non-blog relate pages, like 'documenation' 'getting-started' 'search'.
                  Each page is defined in a sub-folder containing the raw HTML code. No tempaltes
                  Other site-related things are here, like `robots.txt`
    _sass       : Site styling code, like nav-bar specifics, color pallates

