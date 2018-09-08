# Jekyll

Static site generator. MIT license. Implemented in Ruby.

Official Site: https://jekyllrb.com/

GitHub Repository: https://github.com/jekyll/jekyll

Windows Installation:

1. Full instructions: https://jekyllrb.com/docs/installation/windows/
2. Ruby: https://rubyinstaller.org/downloads/
3. Select **Ruby+Devkit 2.4.4-2 (x64)**
4. Run installer (takes a very long time)
5. Install Jekyll (in a new Terminal window): `gem install jekyll bundler` (also takes a while)
6. Check installation: `jekyll -v`

Test (blog) site creation:

1. Instructions: https://jekyllrb.com/docs/
2. `cd` to parent folder of new site
3. `jekyll new myblog` (creates new `myblog` sub-folder)
3. `cd myblog`
4. `bundle exec jekyll serve` (build site and run web server - takes a while first time)
5. Browse to: `http://localhost:4000`
6. Modify site source files - the site should automatically rebuild changes
7. `Ctrl + C` to stop server
8. Can also use just `jekyll serve` if not using a Gem file
