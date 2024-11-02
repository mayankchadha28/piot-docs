# Constrained Device Application (Connected Devices)

## Lab Module 04

Be sure to implement all the PIOT-CDA-* issues (requirements) listed at [PIOT-INF-04-001 - Lab Module 04](https://github.com/orgs/programming-the-iot/projects/1#column-10488386).

### Description

NOTE: Include two full paragraphs describing your implementation approach by answering the questions listed below.

What does your implementation do? 
- The implementation creates the emulation functionality for the Constrained Device Application. This uses the senseHat for the Emulation.

How does your implementation work?
- This creates the emulation tasks for the pressure, temperature and humidity Derived from the BaseSensorSimTask . This similar classes for the actuator derived from the BaseActuatorSimTask. Then these are integrated to SensorAdapterManager and ActuatorAdapterManager respectively. 

### Code Repository and Branch

NOTE: Be sure to include the branch (e.g. https://github.com/programming-the-iot/python-components/tree/alpha001).

URL: https://github.comn/piot-python-components/tree/labmodule04

### UML Design Diagram(s)

NOTE: Include one or more UML designs representing your solution. It's expected each
diagram you provide will look similar to, but not the same as, its counterpart in the
book [Programming the IoT](https://learning.oreilly.com/library/view/programming-the-internet/9781492081401/).

![Labmodule04 CDA](/images/labmodule04.jpg)

### Unit Tests Executed

NOTE: TA's will execute your unit tests. You only need to list each test case below
(e.g. ConfigUtilTest, DataUtilTest, etc). Be sure to include all previous tests, too,
since you need to ensure you haven't introduced regressions.

- 
- 
- 

### Integration Tests Executed

NOTE: TA's will execute most of your integration tests using their own environment, with
some exceptions (such as your cloud connectivity tests). In such cases, they'll review
your code to ensure it's correct. As for the tests you execute, you only need to list each
test case below (e.g. SensorSimAdapterManagerTest, DeviceDataManagerTest, etc.)

- SenseHatEmulatorQuickTest
- HumidityEmulatorTaskTest
- PressureEmulatorTaskTest
- TemperatureEmulatorTaskTest

- HumidifierEmulatorTaskTest
- HvacEmulatorTaskTest
- LedDisplayEmulatorTaskTest

## Test Commands 
- python src/test/python/programmingtheiot/part02/integration/emulated/SenseHatEmulatorQuickTest.py

- python src/test/python/programmingtheiot/part02/integration/emulated/HumidityEmulatorTaskTest.py
- python src/test/python/programmingtheiot/part02/integration/emulated/PressureEmulatorTaskTest.py
- python src/test/python/programmingtheiot/part02/integration/emulated/TemperatureEmulatorQuickTest.py

- python src/test/python/programmingtheiot/part02/integration/emulated/HumidifierEmulatorTaskTest.py
- python src/test/python/programmingtheiot/part02/integration/emulated/HvacEmulatorTaskTest.py
- python src/test/python/programmingtheiot/part02/integration/emulated/LedDisplayEmulatorTaskTest.py

EOF.
