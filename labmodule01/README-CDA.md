# Constrained Device Application (Connected Devices)

## Lab Module 01

Be sure to implement all the PIOT-CDA-* issues (requirements) listed at [PIOT-INF-01-001 - Lab Module 01](https://github.com/orgs/programming-the-iot/projects/1#column-9974937).

### Description

NOTE: Include two full paragraphs describing your implementation approach by answering the questions listed below.

**What does your implementation do?**

The Implementation allows me to set the environment and its configuration to be able to run the CDA Application successfully.

**How does your implementation work?**

The implementation works by follows:
 - Updating ConfigConst.py with relative path for PiotConfig.props
 - Setting the python path correctly in the virtual Environment

### Code Repository and Branch

NOTE: Be sure to include the branch (e.g. https://github.com/programming-the-iot/python-components/tree/alpha001).

**URL:** https://github.com/mayankchadha28/piot-python-components/tree/labmodule01

### UML Design Diagram(s)

NOTE: Include one or more UML designs representing your solution. It's expected each
diagram you provide will look similar to, but not the same as, its counterpart in the
book [Programming the IoT](https://learning.oreilly.com/library/view/programming-the-internet/9781492081401/).

- N/A


### Unit Tests Executed

NOTE: TA's will execute your unit tests. You only need to list each test case below
(e.g. ConfigUtilTest, DataUtilTest, etc). Be sure to include all previous tests, too,
since you need to ensure you haven't introduced regressions.

- ConfigUtilTest

### Integration Tests Executed

NOTE: TA's will execute most of your integration tests using their own environment, with
some exceptions (such as your cloud connectivity tests). In such cases, they'll review
your code to ensure it's correct. As for the tests you execute, you only need to list each
test case below (e.g. SensorSimAdapterManagerTest, DeviceDataManagerTest, etc.)

- ConstrainedDeviceAppTest

### Test Commands (Review)
- python src/main/python/programmingtheiot/cda/app/ConstrainedDeviceApp.py
- python -m unittest src/test/python/programmingtheiot/part01/unit/common/ConfigUtilTest.py
- python -m unittest src/test/python/programmingtheiot/part01/integration/app ConstrainedDeviceAppTest.py

EOF.
