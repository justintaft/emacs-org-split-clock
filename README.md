Split org-mode CLOCK entry while preserving time.  [![Build Status](https://travis-ci.org/justintaft/org-clock-split.svg?branch=master)](https://travis-ci.org/justintaft/org-clock-split)

Clocked some time in but want to split it up into multiple entries? Worry no more!  Place the cursor on a CLOCK entry and run `org-clock-split`. Type in a offset to split the record at, such as "15m1h", and voilà!  The entry will be replaced with TWO clock entries, preserving the total amount of time of the original entry.  

### Usage Example
      
       If cursor is on 

       CLOCK: [2018-08-30 Thu 12:19]--[2018-08-30 Thu 16:05] =>  3:46
       
       Running
       (org-clock-split "1h2m") 
       
       Will produce
    
       CLOCK: [2018-08-30 Thu 12:19]--[2018-08-30 Thu 13:21] =>  1:02
       CLOCK: [2018-08-30 Thu 13:21]--[2018-08-30 Thu 16:05] =>  2:44


### Contributors

https://github.com/alphapapa . 
https://github.com/swflint . 
https://github.com/miguelmorin
