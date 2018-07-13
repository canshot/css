#CSS Skills

*border: sets the outline of an HTML page element, like a picture frame that contains the element.


*padding: sets the amount of space between an element's content and its border.


*margin: sets the amount of space between an HTML element and the next nearest element(s).

*display: property that determines how the selected element will be arranged in relation to other HTML elements on the page.


*inline: display value used to arrange HTML elements on the same line as neighboring elements.


*flex: display value that allows us to easily align multiple page elements vertically or horizontally.


*float: property used to float HTML elements left or right of neighboring elements.


*position: property used to position HTML elements in exact locations on a webpage.


The HTML link element makes Bootstrap available to us. 
Remember that the link element is typically contained within HTML head tags.

#<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css"/>

#Web Concepts
#CSS Framework: Set of prewritten CSS rules designed to help you build webpages faster.

#Bootstrap 
#Grid: 12 equal-sized columns which can be utilized via Bootstrap classes to build responsive page layouts quickly and reliably.

Bootstrap classes
row: Arranges HTML elements in rows, and can be useful when building headers/navigation menus, main feature sections, supporting content sections and footers.

jumbotron: Used to create large showcase sections featuring important content.

col-sm-*: Used to span a specified number of columns on the Bootstrap grid. The "sm" is short for "small", and maintains desired CSS layouts on small screens (tablet-sized).

text-right: Bootstrap class used to orient text to the right side of the webpage.

btn btn-primary: Bootstrap class used to style page elements as buttons.

###jekyll
1. gem install jekyll
2. jekyll new my-portfolio-site
3. To view your site locally, you must first navigate to your site's directory, using the cd command.
Navigate to your site's directory using the cd command.
4. Next, use the serve command to start a local server. Then, navigate to http://localhost:4000 in the browser to view your site.

###Initialize Your Repo
5. In the terminal to the right, open a new tab.Then, use the cd command to navigate to your site's directory.
6. 'cd personal-website'
7. Now that you're inside of your site's directory, initialize a Git repository with the following command:
8. 'git init'






###It's important to understand Jekyll's default directory structure and contents of your site:

1. _config.yml - This is a configuration file that contains many values that need to be edited only once. These values are used across your site, for example, your site's title, your e-mail, and more. Note that this is a .yml file, which you can learn more about here.

2. _includes/ - This directory contains all the partials (code templates that keep you from repeating your code over and over) that your site uses to load common components, like the header and the footer.

3. _posts/ - This directory is where blog posts are stored. New blog posts can be added and will be rendered with the site's styling, as long as the file name follows Jekyll's standard naming convention.

4. _layouts/ - This directory contains templates that are used to style certain types of posts within the site. For example, new blog posts will use the HTML layout defined in post.html.

###STEP
1. Install jekyll
2. Use jekyll to generate a static site
3. Start local server to view my site




