# diag.github.io

This is our lab's website. We are using Jekyll, a static website generator.

## How to add content

### Member information

1. Go to `_includes/people.html`
2. Edit or add what you want (e.g., name, email address, homelage link, etc)
3. To add a profile photo, choose an image and put it under the directory `img/your_name_profile_picture.jpg`
4. Reference your image in `_includes/people.html` with your photo's file name

### Publications

1. Go to `_includes/publications.html`
2. Append the list by copy-pasting one of the already existing items and filling in your information.
3. Add additional materials (e.g., paper, poster, slide) under the directory `publications`
4. Add a hyperlink to the added materials (e.g., < a href="/publications/paper_name.pdf" >Paper Title< /a >)

## How to check changes you made locally

Please check that the site still works before you push your changes to the remote repository. You can do this by:

```sh
bundle exec jekyll serve
```

Then visit `http://127.0.0.1:4000` in your browser.
