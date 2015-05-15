# KPIPE rat-pac analysis codes

Because of structural changes in Tier 2, it wll probably be better to separate the core KPIPE rat-pac code with
any derivative analysis codes.  This way the core RAT package can keep from being bloated.  This means either
transfering less data to the worker nodes or even being able to use a production copy of RAT kept on CVMFS.

To enable the rat environment use env.sh found in the RAT folder.

## Programs

* cr_analysis code: parses kpipe rat and cry output files.  produces tree for making plots.
