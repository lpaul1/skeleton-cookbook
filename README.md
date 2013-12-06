Skeleton Cookbook
=================

This is a testable skeleton cookbook designed for you or your organization to
fork and modify appropriately. The cookbook comes with everything you need to
develop infrastructure code with Chef and feel confident about it.

Requirements
------------

### Platform:

*List supported platforms here*

### Cookbooks:

*List cookbook dependencies here*

Attributes
----------

*List attributes here*

Recipes
-------

### skeleton::default

*Explain what the recipe does here*

Testing
-------

[![Build Status](https://travis-ci.org/charlesjohnson/skeleton-cookbook.png?branch=master)](https://travis-ci.org/charlesjohnson/skeleton-cookbook)

The cookbook provides the following Rake tasks for testing:

    rake acceptance                   # Alias for kitchen:all
    rake foodcritic                   # Run foodcritic lint checks
    rake kitchen:all                  # Run all test instances
    rake kitchen:default-centos-64    # Run default-centos-64 test instance
    rake kitchen:default-debian-72    # Run default-debian-72 test instance
    rake kitchen:default-ubuntu-1204  # Run default-ubuntu-1204 test instance
    rake rubocop                      # Run Rubocop lint checks
    rake spec                         # Run chefspec tests
    rake test                         # Run all tests
    rake unit                         # Run all tests except Kitchen (default task)


License and Author
------------------

Author:: YOUR_NAME (YOUR_EMAIL)

Copyright:: YEAR, YOUR_NAME

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

Contributing
------------

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
