Updated phpPayPal class, originally from https://github.com/drewjoh/phpPayPal - Thank you to @drewjoh for the original!

The original class works great, however it throws some errors in later PHP versions, generally related to urlencode () and null values. This update brings PHP 8.1 (and probably lower) compatibility so those errors are no longer thrown.

This class seems to work fine after some very limited testing, but you take all responsibility should you decide to use it.

As for pull requests and issues - they will be ignored. This update does what's needed for my particular use case.

The original readme is included below.

--------------------------------------------------

phpPayPal Class
=======================

For full documentation and information, please visit the Wiki at GitHub: https://github.com/drewjoh/phpPayPal/wiki

Until I'm moved fully to GibHub, older but more extensive documentation and examples can be found at: http://drewjoh.com/wiki/code/classes/phppaypal
Those examples and code are a little outdated; but should still be helpful.

Created and grown over time by Drew Johnston, drewjoh.com. Please give credit where credit is due. :)

Licensed under the Apache License, Version 2.0

[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/drewjoh/phppaypal/trend.png)](https://bitdeli.com/free "Bitdeli Badge")
