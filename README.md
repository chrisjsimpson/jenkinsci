# Jenkins workflow

## Options
1. Pre-pull request: When a committer pushes to `their` branch, it gets built, and 
   they get feedback on if it breaks the build. 
   This gives developers periodic feedback on if a pull request will break the 
   build or not, without hindering their development flow. e.g. Polling build 
   every x minutes, not every commit as this would be too noisy.
   

2. Developer submits pull request to upstream, this gets merged into `develop`,
   & tested. If tests pass, then the branch is merged into `master`.


### Next steps
Deploy latest master 
