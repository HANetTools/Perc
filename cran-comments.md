## Resubmission
This is small patch to fix errors in testing when using r-devel. In this version:

* Code to specify RNGversion("3.5.3") was added to all tests using sample() to ensure a match to existing data outputs. 

* Version number was increased to "0.1.3".

* New author and maintainer was added.

## Test environments
* local Win 7 install, R 3.5.2
* local Win 10 install, r-devel
* win-builder (devel and release)

## R CMD check results
There were no ERRORs, WARNINGs, or NOTES.

Checking package dependencies. 
* I did not test all dependencies, but do not think any of the changes should effect them.


## Reverse dependencies
This is no package depend on Perc.