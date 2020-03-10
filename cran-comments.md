## Resubmission
This is small patch to fix errors in testing when using r-devel. In this version:

* Code to add default argument for data.frame() from stringsAsFactors = TRUE to stringsAsFactors = FALSE 

* Version number was increased to "0.1.4".

* Test file individualDomProbOutputs.rds updated to match new default specification.

## Test environments
* local Win 10 install, R 3.5.3, r-devel
* win-builder (devel and release)

## R CMD check results
There were no ERRORs, WARNINGs, or NOTES.

Checking package dependencies. 
* I did not test all dependencies, but do not think any of the changes should effect them since the change was mainly in the testing procedure.


## Reverse dependencies
This is no package depend on Perc.