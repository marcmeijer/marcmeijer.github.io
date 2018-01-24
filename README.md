### Data-Science-skills
Indeed NLP for job posting skills
make modifications on the local copies and check on local host

push the final version to remote repository and make “settings” changes

## In the Theme repository
ls
CNAME  Gemfile	README.md 	_layouts	css		   index.html	screenshot.png
Gemfile.lock	 _config.yml	_posts		feed.xml js		     style.css
LICENCE		    _includes	   _site		  img		   mail

The email in the config.ml file is the email where interested party inquiries are sent 

## _config.yml
adjust color scheme of theme - some colors are not recognized for some reason and the page is not predictable. A color is recogniazed when the color hex code is yellow in the code.

adjust some of the site settings
-	title:      is the title of the web page
-	email:      is the email where interested party inquiries are sent
-	url:        is the url of the web page as specified in CNAME and declared in 
-	keywords:   is the list of words used for CRO optimization
-	skills:     is the list of skills presented under the title on the opening page
## IMG 
file contains the profile.png file which is the image logo on the front page
Portfolio contains the .png files that are the images for the portfolio topics	
## _posts
adjust the images of the post section
	image ratio of 5:4 works well for spacing
Modified the post section of freelancer to accept links for client, info, and service
Modifired image to include img1 which is the image for the project page different from the portfolio image

## _includes   
- about.html - 
-- “about” content location html code generator
- contact.html -
-- “contact” information location html code generator
- modals.html - 
-- “_posts” html code generator with post image transferred
-- links for post information


## img/portfolio/???????.png 
- store the images for the posts section

## img/profile/profile.png
- store the image for the top of the landing page - seems to have to be a png file not jpg

## save and check edits
After making the necessary changes with editor to the info files, save changes and check the changes by running a local copy of the with local host.
- $ git add —all
- $ git commit -m “inital comment”
- $ git push -u origin master

## Run on local host
- $ bundle exec jekyll serve

- http://localhost:4000


