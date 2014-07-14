<<<<<<< HEAD
## Welcome to Radiant

Radiant is a no-fluff, open source content management system designed for
small teams. It is similar to Textpattern or MovableType, but is a general
purpose content management system (not just a blogging engine).

[![Build Status](https://secure.travis-ci.org/radiant/radiant.png?branch=1.x)](http://travis-ci.org/radiant/radiant)

Radiant features:

* An elegant user interface
* The ability to arrange pages in a hierarchy
* Flexible templating with layouts, snippets, page parts, and a custom tagging
  language (Radius: http://radius.rubyforge.org)
* A simple user management/permissions system
* Support for Markdown and Textile as well as traditional HTML (it's easy to
  create other filters)
* An advanced plugin system
* Operates in two modes: dev and production depending on the URL
* A caching system which expires pages every 5 minutes
* Built using Ruby on Rails
* And much more...

## License

Radiant is released under the MIT license and is copyright (c) 2006-2009
John W. Long and Sean Cribbs. A copy of the MIT license can be found in the
LICENSE file.

## Installation and Setup

Radiant is a traditional Ruby on Rails application, meaning that you can
configure and run it the way you would a normal Rails application.

See the INSTALL file for more details.

### Installation of a Prerelease

As Radiant nears newer releases, you can experiment with any prerelease version.

Install the prerelease gem with the following command:

    $ gem install radiant --prerelease

This will install the gem with the prerelease name, for example: ‘radiant-0.9.0.rc2’.

### Upgrading an Existing Project to a newer version

1. Update the Radiant assets from in your project:

    $ rake radiant:update

2. Migrate the database:

    $ rake production db:migrate

3. Restart the web server

## Development Requirements

To run tests you will need to have the following gems installed:

  gem install ZenTest rspec rspec-rails cucumber webrat nokogiri sqlite3-ruby

## Support

The best place to get support is on the mailing list:

http://radiantcms.org/mailing-list/

Most of the development for Radiant happens on Github:

http://github.com/radiant/radiant/

The project wiki is here:

http://wiki.github.com/radiant/radiant/


Enjoy!

--
The Radiant Dev Team
http://radiantcms.org
=======
final_project_take_two
======================

New Version of 'LLERO in Radiant Rails Format


•	Github Repo:
•	https://github.com/VictorARodriguez/final_project_take_two/edit/master/
•	Application hosted on Heroku:
•	[INSERT LINK]
•	Trello board:
https://trello.com/b/dlP7hmqK/final-project-board

PLANNING & DELIVERABLES
Project Plan deliverables:
•	Scope. What are you planning to build? - Content Sharing Blog Application

'LLERO [pronounced: yeh-ro] is the digital space for the Latino man. We deliver news, knowledge and advice to men who have their feet firmly planted in both modern and traditional cultures. 'LLERO understands the challenges of balancing mainstream culture with traditional values and the need to have it all at your fingertips. So whether your looking for the top March Madness pics, news from your home patria or tips on choosing the right suit for a job interview.'LLERO is where you'll find it. More than beer, babes and gadgets -- although we bring you that too. 'LLERO providrs useful, culturally relevant content to read, wathc and share with friends.

What features will it have?
MVP involves: (i) user log-in/profile, (ii) user authentication, (iii) the ability to view different content offerings; and (iv) utilize FourSquare API; (iv) responsive design components

What do you think you can reasonably implement in the time period?
MVP, Foursquare API and responsive design elements seem achievable within one week period provided. Should time allow will also look to implement additional features such as ability to curate articles for personalized version of publication. These additional features currently reside in Icebox card on Trello.
•	Object Models
	Please see the Final_Project.pdf.
•	Wireframes 
	Please see the Wireframes.pdf.
•	Resources 
•	Reference
	http://www.llero.net/
	https://developer.foursquare.com
•	Gems
• Radiant
•	debugger
•	pry-rails
•	rails_12factor
•	httparty
•	faker


•	API's
•	FourSquare

•	Milestones
•	Thursday, July 10th – 
	Project plan deliverables due including a project backlog (Scope & Features; Trello Board w/Cards, Wireframes, Object Models) 

•	Friday, July 11th – 
	Name of project established
	GitHub repo established

•	Saturday, July 12th
	Data model complete and placed on Heroku;
	Rails Framework, Basic CRUD

•	Sunday, July 13th
	User Authentication
	Seeding of Database
	Data model complete and placed on Heroku

•	Monday, July 14th
	Core functionality 100% complete

•	Tuesday, July 15th
	Working on UX enhancements.

•	Wednesday, July 16th
	Site is at MVP, working on styling/polish, working on cleaning 
	up code.
	
•	Thursday, July 17th
Prepare presentation and succinct explanation of project, concepts, and defense of decisions.
>>>>>>> 849433523d6cb3154f0e4d62ff191969ea821055
