---
layout: default
title: IMMERSE Log
---



* **This week's goal**:
    * Finish teh comparator for definition and instances
        * this includes the comparator for all the sub classes
            * Ports
            * Wires
            * pins

* **Friday June 12**:
    * Finished updating the release instructions. They are the clearest that it has ever been. Hopefully, people should be able to use this to tackle all of the problems that we have encountered in the past


### Week 4: May 17, 2021

* **Monday**: 
    * attended meeting
* **Tuesday**: 
    * Created a pull request to add my link to the bootcamp website
    * Ran into a bug in pytest
        * Found out that I was calling pytest from Python2 although I have pytest-3 installed. I resolved it by explicitly calling pytest-3 
    * Fixed the python 3.5 ordered dictionary issue, SpyDrNet should be able to pass Travis CI python 3.5 test
        * I replaced all the standard dict() in the parser.py file with OrderedDict and it worked

* **Wednesday**: 
* **Thursday**: 
    * I felt sick Wednesday and Thursday
* **Friday**:
    * Dallin was busy so Ben, Jacob and I attempted a release we couldn’t proceed because of a Travis test. I am not sure what this test is supposed to do. It says it has to do with the branch
    * However, we were able to merge all the changes that the four of us made into one branch and passed all the tests but the python3.5 test again
    * When Dallin updated his code, the reference for the ordered Dictionay was changed and I was able to fix that right after our meeting


