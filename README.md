# Journal of LatinX in AI Research

![](./assets/images/readme/summary.png)

This is an opensource website for the Journal of LatinX in AI Research (JLXAIR). Our organization is volunteer run, so we welcome and encourage contributions from our community and allies! 

Familiarize yourself with the following documentation before getting started.

## The Docs:
- [Github Pages Hosting](https://pages.github.com/)
- [Jekyll Site Generator](https://jekyllrb.com/)
- [Ruby](https://www.ruby-lang.org/en/documentation/)
- [Ruby Gems](https://rubygems.org/)
- [NodeJS](https://nodejs.org/)
- [NPM](https://www.npmjs.com/get-npm)
- [Open-Source Style Guides](http://google.github.io/styleguide/)



## Basic Setup
To contribute to this opensource website, complete the following steps:

1. Clone this repository.
    `git clone https://github.com/latinxinai/research.git`
2. Change directories into cloned repository.
    `cd research`
3. Create your own branch.
    `git checkout -b 'your-branch-name'`
4. Install [Ruby](https://www.ruby-lang.org/en/downloads/) and [Jekyll](https://jekyllrb.com/docs/installation/) if you haven't already.
5. Install [Node.js](https://nodejs.org/) and NPM is you haven't already.
6. Install [RubyGems package manager](https://rubygems.org/pages/download)
7. Install gem files
    `bundle install`


## Running Locally
In order to compile the assets and run the latest version of the site locally complete the following:

- Pull latest version
    `git pull origin master`
- Run Jekyll Server
    `bundle exec jekyll serve`
- Now browse to http://localhost:4000



## File Structure
This site follows the general structure of a [jekyll](https://jekyllrb.com/docs/structure/) github pages site.


For adding or changes to workshop journal pages, please only edit the following:
1. [_includes/workshops/](/_includes/workshops/)
    - Directories organized by conference acronym then year of conference, ex: XXXXYYYY (neurips2020.html)
    - This is where the content for all pages will be created and structured
    - Journal papers should be dynamically rendered on each workshop's include's file

2. [_posts](/_posts/)
    - This directory is where the data for each paper is stored
    - keep organized by year and conference we are colocating with, ex: YYYY_XXXX (2020_neurips)
    - Use previous years as a template for creating new presenter data files

**All the code is compiled into the _site directory and served during build by jekyll from the master branch. If you make manual changes to code in the _site directory they will be overwritten automatically.**


## Pushing Changes
Follow these **guidelines** when contributing to this site:

- Always work off your own branch!
- Never push to the master branch!!
- Push to your branch and then [create a pull request](https://help.github.com/articles/creating-a-pull-request/).
- Follow standard [open-source style guides](http://google.github.io/styleguide/).
- Correct any suggested edits from LXAI and resubmit your pull request for additional review.
- Once your changes have been accepted and merged to master by a representative of the LatinX in AI (LXAI), your name may be added to the credits below. 


## Questions
Having any issues with the site? See something that can be improved? 

File a [GitHub Issue](https://github.com/latinxinai/research/issues).		

## License
GNU General Public License v3.0

## Credits
This journal was built with the inspiration from these themes, engineers, journals, etc:
- [Just the Docs](https://github.com/pmarsceill/just-the-docs)
- [Patrick Marsceill](https://github.com/pmarsceill)
- [Journal of Artificial Intelligence Research](https://jair.org/)
- [The journal of Artificial Intelligence](https://www.journals.elsevier.com/artificial-intelligence)
- [AI & Society: Knowledge, Culture and Communication](https://www.springer.com/journal/146)



This site has been modified by and built upon by the following members of our community:
- [Laura Montoya](https://github.com/quickresolve)
- [Sara Iris Garcia](https://github.com/montjoile)
- [Walter Mayor-Toro](https://github.com/waltermayor)
- [Anthony Barrios](https://github.com/anthxnyR)
