# Constrained Device Application (Connected Devices)

## Lab Module 02

Be sure to implement all the PIOT-CDA-* issues (requirements) listed at [PIOT-INF-02-001 - Lab Module 02](https://github.com/orgs/programming-the-iot/projects/1#column-9974938).

### Description

NOTE: Include two full paragraphs describing your implementation approach by answering the questions listed below.

What does your implementation do? 
Implementation creates the functionality to get the system performance data and connects that to the ConstrainedDeviceApp


How does your implementation work?
it works by creating the SystemPerformanceManager module, integrates it to the ConstrainedDeviceApp. Then creates sub modules for getting Cpu and Memory usages using the psutil library. These classes inherit from the BaseSystemUtilTask. the cpu and memory usage methods are then called from the SystemPerformanceManager. These methods run continuously with a library apsscheduler.

### Code Repository and Branch

NOTE: Be sure to include the branch (e.g. https://github.com/programming-the-iot/python-components/tree/alpha001).

URL: https://github.comn/piot-python-components/tree/labmodule02

### UML Design Diagram(s)

NOTE: Include one or more UML designs representing your solution. It's expected each
diagram you provide will look similar to, but not the same as, its counterpart in the
book [Programming the IoT](https://learning.oreilly.com/library/view/programming-the-internet/9781492081401/).

![Labmodule02 CDA](/images/labmodule02_cda.png)


### Unit Tests Executed

NOTE: TA's will execute your unit tests. You only need to list each test case below
(e.g. ConfigUtilTest, DataUtilTest, etc). Be sure to include all previous tests, too,
since you need to ensure you haven't introduced regressions.

- SystemCpuUtilTaskTest
- SystemMemUtilTaskTest

### Integration Tests Executed

NOTE: TA's will execute most of your integration tests using their own environment, with
some exceptions (such as your cloud connectivity tests). In such cases, they'll review
your code to ensure it's correct. As for the tests you execute, you only need to list each
test case below (e.g. SensorSimAdapterManagerTest, DeviceDataManagerTest, etc.)

- SystemPerformanceManagerTest
- ConstrainedDeviceAppTest

### Test Commands
- python src/test/python/programmingtheiot/part01/integration/system/SystemPerformanceManagerTest.py
- python src/test/python/programmingtheiot/part01/unit/system/systemMemUtilTaskTest.py
- python src/test/python/programmingtheiot/part01/unit/system/systemCpuUtilTaskTest.py

EOF.
