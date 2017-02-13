# The Plain Libre

The Plain is just another white clean and minimalist Jekyll theme that 
designed to focus on writing matters. This theme is best use for personal blog 
type.

[Original version](https://github.com/heiswayi/the-plain)

## This version compared to the original one

- Removed all analytics
- Removed Google font
- Removed Gravatar
- Removed MathJax
- Added a few personalizations
  - Changed main font
  - Bigger font rendering
  - Changed background color
  - `outline: none` for links
  - Static comment system using `mailto` and
    mail aliases for each post (using the posts' path).
    This could implies copying the comments by hand

## Installation

    # pacman -S ruby
    $ gem update
    $ gem install jekyll jekyll-sitemap

## Building

    $ make

## Avatar

Use a square avatar in `./assets/avatar.jpg` (more coming soon).

## Local media content

Put your local media content in `./assets/posts` and use the posts' name as 
prefix to the files. You should then reference these files form the `_posts`
directory easily.

## TODO

- Tags and categories
- Add link to cc-by-sa page on respective picture.

## Screenshot

TODO

## License

[MIT](LICENSE.md)
