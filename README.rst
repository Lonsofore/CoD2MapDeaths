CoD2MapDeaths
==============

Deaths stats on stock Call of Duty 2 maps. 

All data was collected on CrackedVodka - one of the most popular CoD2 1.0 server.


Structure
---------

All data collected in data.db (SQLite). There are:

- gametype
- map
- x
- y
- z
- weapon

I collected 10 000 lines for each gametype+map. Total lines count: about 500 000.
Gametypes: dm, tdm, ctf, sd, hq, htf.


And what can I do with it?
--------------------------

E.g. this:

.. image:: https://raw.githubusercontent.com/Lonsofore/CoD2MapDeaths/master/heatmaps/mp_toujane.jpg


Online version
--------------

Shortly after publication `kung foo man`_ made an `online version`_ of base.

You can find it on the Github aswell: `CoD2MapDeaths.js`_


Support
-------

`Killtube.org`_


License
-------

Licensed under the Apache License, Version 2.0


.. _kung foo man: https://github.com/kungfooman
.. _online version: http://killtube.org/crackedvodka/
.. _CoD2MapDeaths.js: https://github.com/KILLTUBE/CoD2MapDeaths.js
.. _Killtube.org: https://killtube.org/showthread.php?3121-CoD2MapDeaths-Almost-500-000-lines-of-deaths