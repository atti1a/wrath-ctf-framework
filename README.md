iFixit CTF
==========

This simple flask webapp takes password submission from teams, tallies score totals, and presents a leaderboard

TODO
----
* Statistics on how many have completed each challenge in each of the three modules
* Consecutive challenges depend on each other

Heroku
------

The following environment variables are used for configuration:

* ``DATABASE_URL`` - Heroku should set this automatically
* ``PORT`` - this should also be automatic
* ``SECRET_KEY`` - something unique
* ``STATIC_PREFIX`` - empty string to serve on ``/``
