# DEPRECATED!

WARNING: this repos is just a fork of the original package, because we still need it: https://packagist.org/packages/phpexcel/phpexcel

For new projects, you should use this one instead: https://packagist.org/packages/phpoffice/phpspreadsheet

# PHPExcel

This repository contains the unchanged [source code of PHPExcel](http://phpexcel.codeplex.com), 
turned into a [Composer](http://getcomposer.org) package. 

For more information on PHPExcel, including documentation and tests, please see the [PHPExcel website](http://phpexcel.codeplex.com).

## Installation 

If you don’t have Composer yet, you should [get it](http://getcomposer.org) now.

1. Add the package to your `composer.json`:

        "require": {
          ...
          "phpexcel/phpexcel": "1.7.6",
          ...
        }

2. Install:

        $ php composer.phar install

3. And use:

		<?php 
		
		require_once "vendor/autoload.php";
		
		$phpExcel = new \PHPExcel();
		...
	
