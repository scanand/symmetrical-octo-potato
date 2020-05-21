## for integration with Github, _config.yml saved it 

``
#If you want to use GitHub Pages, remove the "gem "jekyll"" above and
#uncomment the line below. To upgrade, run `bundle update github-pages`.
gem "github-pages", group: :jekyll_plugins
``

After that 
exec install --installs git-pages gem dependency
exce update

Do git push changes 
-- this should install your changes on github-pages

Still template changes are not seen opn github pages
-- another change in _config.yml
``
baseurl: "/symmetrical-octo-potato" # the subpath of your site, e.g. /blog
url: "https://scanand.github.io" # the base hostname & protocol for your site, e.g. http://example.com
``