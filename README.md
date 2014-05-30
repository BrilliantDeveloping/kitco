# Kitco Gem


This gem retrieves data (via HTTParty) from Kitco Charts about Gold and other precious metals.

Use at your own discretion 

## Add to gemfile

    gem "kitco", git: "https://readpermissions@bitbucket.org/brilliantdeveloping/kitco.git", branch: 'master'


## Examples

    require 'kitco'

    puts Kitco.gold
    puts Kitco.silver

## Command Line Utility


    kitco gold

For more details on run

    kitco --help
