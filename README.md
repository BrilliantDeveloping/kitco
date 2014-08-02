# Kitco Gem


This gem retrieves data (via HTTParty) from Kitco Charts about Gold and other precious metals.

Use at your own discretion 

## Add to gemfile

    gem "kitco", git: 'git://github.com/brilliantdeveloping/kitco.git'


## Examples

    require 'kitco'

    puts Kitco.gold
    puts Kitco.silver
	puts Kitco.platinum
	puts Kitco.palladium
	puts Kitco.rhodium

## Command Line Utility


    kitco gold

For more details on run

    kitco --help
