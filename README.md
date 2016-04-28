# Associated Students Website

## Resources
+ [Trello][1]
+ [Current AS Website][2]
+ [Hexo Docs][3]

## FAQ

### Where do I edit the navigation menu?
`themes/corporate/config.yml` at the top.

### Where do I edit the front page?
`source/index.ejs`

### How do I add a page?
Create a folder in the `source/` directory with the name of the page, then
create a file in that folder named `index.ejs`. Look at the other pages
(about, contact, etc.) for help. Don't forget to add the page to the
navigation menu (see above).

### How do I add a blog post?
Use the command `hexo new "POST NAME"` (with quotes), and a file with that
name will be created in `source/_posts/POST-NAME.md`. Alternately, you could
just create the file yourself.

### How do I do anything?
In general, I usually look in `_config.yml` or `themes/corporate/_config.yml`
for some sort of option related to what I want to change. If there's nothing
there, look in `themes/corporate/layout/` for the `.ejs` file containing the
stuff you want to change. You can also look in `themes/corporate/source/css/`
to change the CSS. Don't be afraid to google stuff or ask on slack for help!



[1]: https://trello.com/b/A78luytH/as-website
[2]: http://www.smc.edu/StudentServices/AssociatedStudents/Pages/New-Homepage.aspx
[3]: https://hexo.io/docs/
