 
##########################################################

FluidPhp 1 open source project translator helper

A powerfull framework based on the phptoolcase library.

##########################################################

FluidPhp is a framework based on the PhpToolCase library.

Visit phptoolcase.com for complete guides and examples.

== PROJECT INFO ===================================

== Project Home: http://phptoolcase.com

== Requirements: php version 5.3+

== INSTALLATION WITH COMPOSER ========================

	- WITH FLUIDPHP FRAMEWORK:
	
		"require": 
		{
			"mnsami/composer-custom-directory-installer": "1.1.*" ,
			"fluidphp/translator-helper": "~1.0"
		} ,
		"extra": 
		{
			"installer-paths": 
			{
				"./vendor/fluidphp/helpers/Translator": ["fluidphp/translator-helper"]
			}
		}
	
	- STAND-ALONE:
		
		"require": 
		{
			"fluidphp/translator-helper": "~1.0"
		}
