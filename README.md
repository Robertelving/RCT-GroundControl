# RCT-GroundControl [![Build Status](https://travis-ci.org/RCTechnologies/RCT-GroundControl.svg?branch=master)](https://travis-ci.org/RCTechnologies/RCT-GroundControl) [![Coverage Status](https://coveralls.io/repos/github/RCTechnologies/RCT-GroundControl/badge.svg?branch=master)](https://coveralls.io/github/RCTechnologies/RCT-GroundControl?branch=master)

Companion Software for Multipurpose Drone Platform

### Regarding template VS templateUrl
There is an issue w. Angular 2, that when using templateUrl in a component, you should give the entire url and not the relative url, else it will throw an error. 

## TO DO

### Switch to Git Phlow
Some basic phlow commands are:
```
git phlow workon [some-issue]
git phlow wrapup
git phlow deliver
```

### Use Dronekit-Sitl in test
Using a System in the loop emulated drone, we should be able to integrate functional testing in our chain