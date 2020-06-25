# Project 4
### Static Web Design
A complete redesign to Jim Davis' Ohio State University webpage found at: http://web.cse.ohio-state.edu/~davis.1719/
using HTML, CSS, and embedded Ruby code.

### Roles
* Overall Project Manager:
* Coding Manager:
* Testing Manager: Duytan Tran
* Documentation:

### Contributions
* Site-wide logo css (icon.css), Site-wide margins css (font_scheme.css), people page html w/ embedded ruby generation of lists (people.html.erb), people page css (people_style.css), noteworthy page html (noteworthy.html.erb), and noteworthy page css (noteworthy_style.css): Duytan Tran

### How to generate HTML pages
1. Install the bundler gem if you haven't already: http://web.cse.ohio-state.edu/~shareef.1/3901.su20/labs/gems.html
2. Move into the Project-4-Quaranteam directory via terminal command: cd your_file_path
3. Install middleman via terminal command: bundle install
4. Fulfill the bookkeeping required after bundle install via terminal command: rbenv rehash
5. cd into the jim_davis_web folder via terminal command: cd jim_davis_web
6. Generate the HTML pages via terminal command: bundle exec middleman build
7. Inside of the jim_davis_web folder should now have a build folder

### How to access generated HTML pages
1. Open up your file browser (files)
2. Find and enter the build folder via your file browser: '../Project-4-Quaranteam/jim_davis_web/build'
3. Open up the file 'index.html' with firefox to view Jim Davis' new home page
