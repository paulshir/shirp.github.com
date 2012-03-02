[shirp-w]: http://shirp.github.com
[shirp-r]: http://github.com/shirp
#Personal Landing Page For [Paul Shirley][shirp-w]

This is a Jekyll powered blog. I am going to use it and attempt to create my own theme for it.

______________________________
# About Jekyll-Bootstrap

Jekyll-Bootstrap is a simple way to get up and running using github pages to host a static website.

## Usage

For all usage and documentation please see: <http://jekyllbootstrap.com>

### Version

0.2.0 - stable and versioned using [semantic versioning](http://semver.org/).
[Creative Commons](http://creativecommons.org/licenses/by-nc-sa/3.0/)
______________________________

# My observations

###Theme
To change a theme use  rake theme:switch name="THEME-NAME"  This goes through every file in the includes folder for the new theme and will add it to the layout folder. Note the setup of the layout folder means that there can only be one default theme called default.html. You could change this in the layout folder but this wouldn't remain if you are to switch themes. The only option really would be to make changes to the RakeFile to add custom pages. Then again custom pages mightn't be needed. The best option would be if the layout could be defined in the settings file for the folder. That is work for another time though. By adding other pages and layouts it will make the blog incompatoble with other themes.

### Navbar
    If group:navigation is added to the top of the page it will appear in the navigation bar. Need to look at this in more depth to apply it elsewhere in the site

### Code Blocks
Code blocks can be inserted by putting 4 spaces of a tab in front of each line. They can also be declared using the  
	{% highlight codetype %}
		Code Goes Here
	{% endhighlight %}
I have come accross the problem thought that if you use this highlight method the standard method of adding the spaces doesn't work for that page

Test




