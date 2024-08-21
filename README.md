# monitor-repos
A repository containing repositories' configuration for cvmfs-monitor: https://gitlab.cern.ch/cernvm/cvmfs-monitor

## How to add your repository

Create a .json file in the `repos` directory containing the repository name and Stratum0/1 base URL (URL without the repository name component). An example can be found in `example.json`. 
The stratum server must provide [repository-level meta-information](https://cvmfs.readthedocs.io/en/stable/cpt-servermeta.html#repository-specific-meta-information).
