# Openruko Client Tool

## Introduction

Openruko client tools piggybacks off Heroku client tools, overriding environment
variables to point to your Openruko server instead of Heroku.

mymachine.me is convenient for debugging, it points to 127.0.0.1, just like 
localhost, however it is compatible with Heroku client tools - base host requires
a hostname with . or else errors in recent version of Heroku client tools. 

## Requirements

Tested on Linux 3.2 using Bash, Heroku CLI (and via dependency - Ruby)

## Going Forward

If openruko gets any momentum then this a little bit of convoluted way to handle client tools, 
looking into a PPA/Yum repo, or a simple shell script to generate a wrapper and setup openruko  
in user's ~/.bin etc..

## License

openruko components are licensed under MIT.  
[http://opensource.org/licenses/mit-license.php](http://opensource.org/licenses/mit-license.php)

## Authors and Credits

Matt Freeman  
[email me - im looking for some remote work](mailto:matt@nonuby.com)  
[follow me on twitter](http://www.twitter.com/nonuby )
