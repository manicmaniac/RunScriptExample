RunScriptExample
================

A test repository to examine how `run_only_for_deployment_postprocessing` works.

Usage
-----

    ./bin/examine-script-timing


## run_only_for_deployment_postprocessing = false
actions|is run script phase invoked
-|-
build | true
clean build | true
build-for-testing | true
clean build-for-testing | true
archive | true
--------------------------------------------------------------------------------
## run_only_for_deployment_postprocessing = true
actions|is run script phase invoked
-|-
build | false
clean build | false
build-for-testing | false
clean build-for-testing | false
archive | true
