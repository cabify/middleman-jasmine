0.4.0
===
* Add debug_assets option to expand the assets into individual files. Defaults to false.

0.3.0
===
* Add config_file option for specifying jasmine config file [byteio, mrship]

0.2.0
===
* Revise so fixtures are served by Rack::Directory

0.1.1
===
Rename lib/middleman/jasmine.rb to lib/middleman-jasmine.rb per the middleman extension convention.

0.1.0
===

* Configure in #after_configuration block
* Apply all middleman_sprockets paths to our internal sprockets
* Expose internal sprockets app with jasmine_sprockets helper

0.0.3
===

* Only use one Sprockets instance
* Support for fixtures loading from a :fixtures_dir option
* Fix for not using Sprockets

0.0.2
===
Yanked

0.0.1
===

* Initial support for Jasmime