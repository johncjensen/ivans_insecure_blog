# Ivan's terrible blog (security fixed)

The blog was previously vulnerable to XSS (cross site scripting) & SQL Injection.

These problems were corrected by:

* updating to Rails 4.0.3
* whitelisting input parameters
* sanantizing model level where() search with "like ?'


#Brakeman Gem output
![brakeman-screenshot](http://f.cl.ly/items/0S311U0U471N0M183p1N/Screenshot%202014-02-27%2017.33.26.png)

#Credit
Forked from [Ivan Storck](https://github.com/ivanoats/ivan_the_terribles_blog/tree/insecure)

#License
[MIT License](johnjensen.mit-license.org)
