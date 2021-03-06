#MavensMate

MavensMate is a SublimeText plugin that aims to replicate the functionality of the Eclipse-based Force.com IDE.

* Create & Edit Salesforce.com projects with specific package metadata
* SVN & Git support
* Create & compile Apex Classes, Apex Trigger, Visualforce Pages, and Visualforce Components
* Compile and retrieve other Salesforce.com metadata
* Run Apex test methods and visualize test successes/failures & coverage
* Play Pacman while your Apex unit tests run
* Deploy metadata to other Salesforce.com orgs
* Apex Execute Anonymous
* Apex Code Assist (beta!!)

*Currently, MavensMate only officially supports OS X. It's on the roadmap to fully support Windows/Linux.
 
##Install
```
$ gem install mavensmate
$ ruby < <(curl -s https://raw.github.com/joeferraro/MavensMate-SublimeText/master/install.rb)
```

<img src="http://wearemavens.com/images/mm/menu3.png"/>

Go to "MavensMate --> Open --> Settings - User" and modify "mm_workspace" with the location where you'd like your MavensMate projects to reside, for example (notice the absolute path):

	"mm_workspace": "/Users/your_username/Projects"

If you're using RVM, you probably want to update the "mm_ruby" setting:

	"mm_ruby": "~/.rvm/bin/rvm-auto-ruby"

If you encounter any ugly error messages in the MavensMate UI that reference gem dependencies, try installing v0.0.7 of MavensMate:

	$ gem install mavensmate -v 0.0.7

If you happen to encounter issues installing Nokogiri, here's a helpful URL:

	http://nokogiri.org/tutorials/installing_nokogiri.html

##Update
Run "Update MavensMate" command

<img src="http://wearemavens.com/images/mm/mmupdate3.png"/>

OR run the following terminal command:
```
$ ruby < <(curl -s https://raw.github.com/joeferraro/MavensMate-SublimeText/master/install.rb)
```


##Wiki
<a href="https://github.com/joeferraro/MavensMate-SublimeText/wiki">https://github.com/joeferraro/MavensMate-SublimeText/wiki</a>

##Screenshots

###Project Wizard
<img src="http://wearemavens.com/images/mm/project_wizard.png"/>
###Apex Test Runner
<img src="http://wearemavens.com/images/mm/test2.png"/>
###Apex Execute Anonymous
<img src="http://wearemavens.com/images/mm/execute.png"/>
###Quick Panel
<img src="http://wearemavens.com/images/mm/panel.png"/>
###Apex Code Assist
<img src="http://wearemavens.com/images/mm/code_3.png"/>
<img src="http://wearemavens.com/images/mm/code_4.png"/>
###Pacman
<img src="http://wearemavens.com/images/mm/pacman.png"/>