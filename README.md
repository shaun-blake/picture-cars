# picture-cars

Using this template - http://html5up.net/twenty

TODO -- domain? http://www.shaunblake.com
=========

Website project and distribution for TODO

The site is hosted as github pages.  The project uses yeomen, grunt, bower and http://html5up.net/twenty. The site itself might use polymer.

##building
When you first checkout the project you need to do `npm install` and `bower install`. You may have to run `grunt` to generate the dist folder before deploying.

##running
`grunt serve` or `grunt serve:dist` (to run the distributed version). 

##deploying
The site is contained on the gh-pages branch and found in the dist directory. Deployment is handled by a handy script I found (and checked in at the root) - https://github.com/X1011/git-directory-deploy

`./deploy` will push the dist folder up the github as the new site (use `./deploy -s` the first time???).

##Custom Domain TODO - below is copied from shaunblake.com site.

###DNS Configuration
I have two @ A name records, 1 pointing to 192.30.252.153 and one pointing to 192.30.252.154.  Then I have a www A name record pointing to 192.30.252.153.

###Github configuration
I have the previously mentioned deploy script which will deploy the dist version to the gh-pages branch.  In the root I have a file, CNAME, which has www.shaunblake.com.  Including the www means shaunblake.com will redirect to www.shaunblake.com.  If I just had shaunblake.com then www.shaunblake.com would redirect to shaunblake.com.
