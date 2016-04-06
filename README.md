# Snapshot of Texas Death Penalty site

You can view the mirrored version by visiting this URL:

http://wgetsnaps.github.io/tdcj-state-tx-us--death_row/death_row/index.html


This repository is a mirror of the following site:

|     Key     |                Value                 |
|-------------|--------------------------------------|
| Site title  | The Million Dollar Homepage          |
| URL         | http://www.milliondollarhomepage.com |
| Mirrored at | 2016-04-05 17:30                     |




# How to wget

This is the __wget__ command(s) I used:

~~~sh
wget --mirror \
     --timestamping \
     --convert-links \
     --no-host-directories \
     --adjust-extension \
     --output-file /dev/stdout \
     http://www.milliondollarhomepage.com \
       | tee ./wget.log
~~~
