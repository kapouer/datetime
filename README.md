## Date/Time input
Enter formatted date and time without pickers.

[![Build Status](https://travis-ci.org/ua9msn/datetime.svg?branch=master)](https://travis-ci.org/ua9msn/datetime)

**Version 2 contains breacking changes.**

For the demo and docs please visit https://ua9msn.github.io/datetime

### What is it
The jQuery plugin which makes date/time input from text one. 
Inspired by "dateentry" plugin http://keith-wood.name/timeEntry.html

### Why is it
The mentioned above plugin is outdated. I tried to use it with a webpack, and failed. 
It use some kind a plugin wrapper which is not used anywhere else and, in my opinion, adds extra complexity.

### Why jQuery and not React
Just because i need jQuery. When i need react, i'll add the branch.

### What is inside
Instead of create huge data file with day names, month names, etc. I use Intl inside. 
So all languages supported by Intl, should be ready to use without any twitches.

Meanwhile, internally, this code doesn't use jQuery, i need jQuery only as interface to attach the plugin to input.
 
### What's next
 
 * Add step option
 * Add ERA support
 * Increase test coverage
 * Optimize code
 
 


