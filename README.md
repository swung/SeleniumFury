SeleniumFury
=========
 Selenium Fury allows an automated tester to quickly build page files to use in the page object pattern.  Each page file represents
a page under test with attributes of all the locators selenium needs to run tests on the page and methods that represent
actions that can be performed on the page.

You use the generator to build the page files. After the page has been updated you can use the validator to go through
all of the selenium locators you are using in your page file and return a list of the locators that it could not find.
If there are missing locators you can then rerun the generator to generate new selenium locators for your page.


Generate
=========
*  See the examples directory for full syntax.
*  include PageGenerator
*  get_source_and_print_elements(browser)


Validate
=========
*  See the examples directory for full syntax.
*  include PageValidator
*  check_page_file_class(YourPageFileClass, "/optional_relative_url_path")

Custom Configuration
=========

* Coming Soon

Core Team
=========

 * [Scott Sims](http://scottcsims.com/): Current maintainer.

Copyright
=========
* Copyright (c) 2010 HomeAway, Inc.
* All rights reserved.  http://www.homeaway.com
  See LICENSE for details.
