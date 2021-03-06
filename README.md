# Project 4
### Static Web Design
A complete redesign to Jim Davis' Ohio State University webpage found at: http://web.cse.ohio-state.edu/~davis.1719/
using HTML, CSS, and embedded Ruby code.

### Roles
* Overall Project Manager:Sean Michaels
* Coding Manager: Reema Gupta 
* Testing Manager: Duytan Tran
* Documentation: Caroline Wheeler 

### Contributions
* Site-wide logo css (icon.css), Site-wide margins css (font_scheme.css), people page html w/ embedded ruby generation of lists (people.html.erb), people page css (people_style.css), noteworthy page html (noteworthy.html.erb), and noteworthy page css (noteworthy_style.css): Duytan Tran
* Pages under the media tab creation (tv_video.html, radio.html, print.html), the respective CSS styling for those pages (lists.css), creation of the site wide footer (_footer.erb), the styling for the footer (footer.css) : Sean Michaels
* Education and publication html page(education.html, education_style.css, publications.html, publication_style.css), side wide font and header info(font_scheme.css), appointment section of home page(index.html, site.css), footer error fixing(footer.css, _footer.erb), navigator push button(navbar.css): Reema Gupta
* Site-wide navigation bar html and css, directions page html and css, and teaching page html and css. Design conception and much of the aesthetic decisions: Caroline Wheeler
 
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
