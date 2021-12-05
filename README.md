# BloodXtract Team page

A website about BloodXtract team.

## Building
Install all dependencies:
1. Follow Jekyll install steps on https://jekyllrb.com/docs/installation/.
2. Clone repository.
3. Run `gem install bundler`.
4. Run `bundle add jekyll`.
5. Run `bundle update` in cloned repository directory.
6. Run `bundle install` in cloned repository directory.
7. Run `gem update`.

These commands may take a while to execute, but they're one-time installation.
Once all is installed, run `bundle exec jekyll serve` in cloned repository directory to run the website locally.  
The website will be then available on http://localhost:4000.

> If you get permission denied error, ensure your antivirus is not blocking ruby.exe.

### Maintenance
To update dependencies, run `bundle update`, and then run steps 5 to 7 once again. Commit changes if everything is working correctly.

## Theme
This website uses a heavily modified [devlopr jekyll](https://github.com/sujaykundu777/devlopr-jekyll) theme - but the modifications are quite significant. They include, but are not limited to:
- Removed blog entries from homepage;
- Support for multiple members (theme was designed for a single author - it was changed later, but was not present in the theme when this website was created);
- Added "cards" system for both game and member pages, to improve reusability;
- Removed light theme (2 themes are more effort to maintain);
- Completely changed gallery style (while the theme itself is pretty nice, gallery style was so basic so even my backend programmer self didn't like it *- TehGM*)
- Massively refactored underlying code and data structures to make it much more maintainable (the theme is nice, but it's clear that the author isn't a backend programmer - code was messy and contained tons of duplicates).