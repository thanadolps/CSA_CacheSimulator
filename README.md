# CSA_CacheSimulator

1. compile CacheSim.c in cmd using gcc
   **_gcc CacheSimX.c -o CacheSimX_**

2. execute in cmd using
   **_.\CacheSimX gcc_ld_trace.txt_**
   or **_.\CacheSimX go_ld_trace.txt_**

3. Adjust parameter in CacheSim.h

All codes are modified from Krerk Piromsopa, Ph.D.
https://www.cp.eng.chula.ac.th/~krerk/books/Computer%20Architecture/CacheSim/

## Autorun

Main improvement over the upstream is an additional of [autorun notebook](autorun.ipynb).
It essentially do the above three step (adjust parameter, compile, execute) but automatically. It then capture the result and genereate a table and plot graph of the results.

By default it use `tracefile = "gcc_ld_trace.txt"` but can be easily configure.
