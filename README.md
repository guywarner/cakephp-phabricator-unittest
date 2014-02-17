cakephp-phabricator-unittest
============================

A hacked up Phabricator PhpunitTestenge.php to work with CakePHP's console for unit testing. This needs a lot of work. But it does WORK. Working with Cake Console v2.3.2 and PHPUnit v3.7.24

Hard coded to run unit tests from ./app/Console/Console/cake - you might need to change this line to whatever you use to run cake console.  Line 85


The basic steps:

Update arcanist - git pull
if you get errors below update libphutil - git pull
and run libphutil/scripts/build_xhpast.sh
Drop in CakePhpTestEngine.php into /whatever/arcanist/src/unit/engine
Run arc liberate in the arcanist folder via command line

