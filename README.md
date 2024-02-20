# znnc-fitting
Fitting algorithm including emcee for binding constants in zinc norcorrole

Set up environment with:
$ mamba create -n binding -c conda-forge python jupyter ipython uncertainties lmfit scipy numpy emcee numba corner matplotlib numdifftools

Linux or WSL preferred, since then multiprocessing can work. However, in this system, the speedup from parallel processing is small, so don't go to great efforts to get a WSL/Linux environment working!
