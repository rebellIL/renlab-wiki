1) Please monitor the memory and CPU usage of your jobs using the "top" command. 

2) If your job takes up >10% of total memory or uses >10 threads (i.e. >1000% CPU with top), please consider it an "intensive" job.

3) Before running an intensive job, please check to see if other intensive jobs are currently running. If so, or if you are already running an intensive job, please wait to run another.

4) If you are running an intensive job and notice that the server has become very slow or unresponsive, please kill your job. If the system becomes slow/unresponsive, an attempt should be made to contact any users running intensive jobs, and after that, those jobs can be killed by system admin (i.e. Bin or SDSC).

5) Please limit yourself to no more than 10 concurrent jobs, even if none of them are intensive.
