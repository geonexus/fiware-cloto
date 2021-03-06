Changelog
=========

v2.0.0 (2015-10-23)
-------------------

New
~~~

- Adding tests to check environment cleaning. [Guillermo Jimenez Prieto]

- Cleaning environments before creating the new ones. [Guillermo Jimenez
  Prieto]

- New unit test to check fail connection while windowsize updating.
  [Guillermo Jimenez Prieto]

- XUnit report is now generated. [Guillermo Jimenez Prieto]

- Changed the way to execute unit tests, now it is performed as django
  recommends. [Guillermo Jimenez Prieto]

- Tests: new tests to check the windowsize update. [Guillermo Jimenez
  Prieto]

- Cloto sends windowsill updates to a rabbitmq in order to notify to
  fiware-facts. [Guillermo Jimenez Prieto]

Changes
~~~~~~~

- Version is now recovered from settings file. [Guillermo Jimenez
  Prieto]

Fix
~~~

- Fixing wrong logger import in wsgi file. [Guillermo Jimenez Prieto]

- Moving build to root folder. [Guillermo Jimenez Prieto]

- Fixing cobertura report publishing into sonar. [Guillermo Jimenez
  Prieto]

- Fixing sonar reports. [Guillermo Jimenez Prieto]

v1.8.0 (2015-09-29)
-------------------

New
~~~

- Server is now creating all tables when it starts. No more user
  interaction is needed. [Guillermo Jimenez Prieto]

- New installation for fiware-cloto using PIP. [Guillermo Jimenez
  Prieto]

- Improving configuration taking data from a configuration file located
  in /etc/fiware.d/fiware-cloto.cfg. [Guillermo Jimenez Prieto]

- Adding new files to the package data. [Guillermo Jimenez Prieto]

Fix
~~~

- Adding more useful information to documentation. [Guillermo Jimenez
  Prieto]

- Updating documentation according the new installation using PIP.
  [Guillermo Jimenez Prieto]

- Adding parent folder to sys environment to execute unit tests without
  errors with this new file distribution. [Guillermo Jimenez Prieto]

- Moving all files into a new module folder called fiware_cloto.
  [Guillermo Jimenez Prieto]

v1.7.1 (2015-09-08)
-------------------

Fix
~~~

- Updated apiary documentation in order to add new data. [Fernando]

v1.6.0 (2015-07-28)
-------------------

Fix
~~~

- Fixing missing badges on README file. [Guillermo Jimenez Prieto]

v1.5.0 (2015-05-29)
-------------------

New
~~~

- Develop the functionality to connect Policy Manager with Keystone
  using APIv3. [Guillermo Jimenez Prieto]

v1.4.0 (2015-03-03)
-------------------

New
~~~

- New unit tests and refactor of environment script. [Guillermo
  Jimenez Prieto]


v1.3.0 (2014-12-01)
-------------------

Changes
~~~~~~~

- Readme is now in RsT format. [Guillermo Jimenez Prieto]

Fix
~~~

- Fixing Acceptance Tests with all new cloto structure. [Guillermo
  Jimenez Prieto]

- Fixing logging from django files. [Guillermo Jimenez Prieto]

- Fixing cobertura report to work with jenkins and sonar. [Guillermo
  Jimenez Prieto]

v1.2.0 (2014-11-04)
-------------------

New
~~~

- Added CHANGELOG.rst file for fiware-cloto. [Guillermo Jimenez Prieto]

- Added CHANGELOG config file for gitchangelog. [Guillermo Jimenez
  Prieto]

- Settings are now in a single file fix: dev: Settings are now loaded
  correctly. [Guillermo Jimenez Prieto]

- Adding more unit tests. [Guillermo Jimenez Prieto]

- Allowed host added into automatic installer. Now default local IP
  address is added to settings.py. [Guillermo Jimenez Prieto]

- Adding documentation to github. [geonexus]

Changes
~~~~~~~

- Preparing release. (1.2.0) [Guillermo Jimenez Prieto]

- Removing developer's IP from ALLOWED HOSTS. [Guillermo Jimenez Prieto]

- Checkstyle fixes. [Guillermo Jimenez Prieto]

- Adding more unit tests. [Guillermo Jimenez Prieto]

- Indentation fix. [Guillermo Jimenez Prieto]

Fix
~~~

- Api info fixed to public wiki url and omit production settings from
  coverage. [Guillermo Jimenez Prieto]

- Pep8 fixes. [Guillermo Jimenez Prieto]

- More unit tests for wsgi. [Guillermo Jimenez Prieto]

- Skipping wsgi tests. [Guillermo Jimenez Prieto]

- Fixing not found error on travis. [Guillermo Jimenez Prieto]

- Adding white space between allowed hosts in settings file. [Guillermo
  Jimenez Prieto]

- Loggers are mocked in unittests. [Guillermo Jimenez Prieto]

- Added fail view for Mac Servers. [geonexus]

- Rules are now stored correctly. There was a bug that stores all rules
  with unicode values. [geonexus]

- Server version is now based on a string value and it is needed to
  change value in configuration.py before each release. [geonexus]

- Changing version float in server information to string value. Fixing
  some words mistaken. [geonexus]

- Adding HTTP TRACE TRACK methods disabling instructions. [geonexus]

- Adding PyClips requirement to README.md. [geonexus]

- Updating databases to mysql commands. [geonexus]

- Updating databases to mysql commands. [geonexus]

- Adding titles to rst files. [geonexus]

- Adding documentation to github. [geonexus]

- Adding documentation to github. [geonexus]

- Adding documentation to github. [geonexus]
