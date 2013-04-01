<h4>Asymmetric Catenary Curve Calculation</h4>

<u><b>Note:</b></u> No elasticity</p>

Redo of my octave script in python/numpy/scipy. Original octave script can be found [here](https://github.com/ddjokic/Catenary-no_elasticity).</p>
<b>NO WARRANTIES</b>, whatsoever.

##### Instructions on Debian 7.0 (wheezy)
Let's install the dependencies first. pycatenary.py needs python3 first:
 apt-get install python3-tk python3-numpy python3-scipy

Add the Debian experimental repository to /etc/apt/sources.list (This is needed for python3-matplotlib on Debian 7.0 "wheezy".)
 deb http://ftp.debian.org/debian experimental main

Install the Debian experimental version of python3-matplotlib:
 apt-get install python3-matplotlib

TODO: solve problem with inout module write_file method .

(c) 2013, D. Djokic
