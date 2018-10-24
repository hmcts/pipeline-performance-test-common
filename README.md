# pipeline-performance-test-common
This is repository for pipeline performance test common framework. for every project we need to add the following steps for the pipeline project.
Step1: download the common framework from the repository
Step2: add all the source files under src/gatling simulations directory.
step3: under src/gatling/simulations following is the folder structure we need to add the files
uk/gov/hmcts/reform/cmc/performance(here cmc can be replaced by relavant project name like sscs, sidam,probate etc)
Step4: under uk/gov/hmcts/reform/cmc/performance/utils add one file called Environment.scala file 
Step5: add the AAT urls within the Environment.scala
Step6: add data files in the following locations
src/gatling/data and srs/test/resources/data
Step7: add bodies files in the following locations
src/gatling/bodies and srs/test/resources/bodies
Step8: Run the simulation using srs/gatling/simulations/Run...
