dyld_cache_extract
==================

[![Build Status](https://img.shields.io/travis/macmade/dyld_cache_extract.svg?branch=master&style=flat)](https://travis-ci.org/macmade/dyld_cache_extract)
[![Issues](http://img.shields.io/github/issues/macmade/dyld_cache_extract.svg?style=flat)](https://github.com/macmade/dyld_cache_extract/issues)
![Status](https://img.shields.io/badge/status-active-brightgreen.svg?style=flat)
![License](https://img.shields.io/badge/license-mit-brightgreen.svg?style=flat)
[![Contact](https://img.shields.io/badge/contact-@macmade-blue.svg?style=flat)](https://twitter.com/macmade)  
[![Donate-Patreon](https://img.shields.io/badge/donate-patreon-yellow.svg?style=flat)](https://patreon.com/macmade)
[![Donate-Gratipay](https://img.shields.io/badge/donate-gratipay-yellow.svg?style=flat)](https://www.gratipay.com/macmade)
[![Donate-Paypal](https://img.shields.io/badge/donate-paypal-yellow.svg?style=flat)](https://paypal.me/xslabs)

About
-----

A macOS utility to extract dynamic libraries from the `dyld_shared_cache` of macOS and iOS.

The project is available as a **macOS application (with GUI)** and as a **command line tool**.

![Main Window](Resources/MainWindow.png "Main Window")
![File Window](Resources/FileWindow.png "File Window")

Command line usage
------------------

    dyld_cache_extract - Extractor utility for DYLD shared cache
    
    Available options:
        
        --help                            Shows this help dialog.
        --info [PATH]                     Displays informations about a dyld_shared_cache file.
        --extract-all [PATH] [OUT_DIR]    Extracts all libraries from a dyld_shared_cache file.
        --extract [LIB] [PATH] [OUT_DIR]  Extracts a specific library from a dyld_shared_cache file.

DYLD Cache Format
-----------------

...

License
-------

`dyld_cache_extract` is released under the terms of the MIT License.

Repository Infos
----------------

    Owner:			Jean-David Gadina - XS-Labs
    Web:			www.xs-labs.com
    Blog:			www.noxeos.com
    Twitter:		@macmade
    GitHub:			github.com/macmade
    LinkedIn:		ch.linkedin.com/in/macmade/
    StackOverflow:	stackoverflow.com/users/182676/macmade
