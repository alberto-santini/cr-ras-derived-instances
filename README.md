# Train Conflict Resolution Instances

[![DOI](https://zenodo.org/badge/83153574.svg)](https://zenodo.org/badge/latestdoi/83153574)

These are instances for a Conflict Resloution (CR) algorithm, derived from the 2012 RAS Competition data.

The instances have been used in the paper "A Real-Time Conflict Solution Algorithm for the Train Rescheduling Problem" by Bettinelli, A. and Santini, A. and Vigo, D.

* The files `network-macro` and `network-micro`, respectively, provide a macro- or microscopic description of the underlying network.
* Each instance consists of two files, in the form `forecast-timetable-X` and `nominal-timetable-X`. The latter contains the ideal published timetable of the trains; the former contains the current state of the network and, due to disturbances and disruptions, contains conflicts.
* The files `params-*` contain parameters common to multiple instances (rever to the above paper for more details).
* The file `restrictions-ras.xml` is unused for these instances.
