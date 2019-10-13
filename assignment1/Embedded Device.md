For my assignment I will analyze the controller for a home security system.
I imangine a system that anaylzes data from multiple sensors, ie. switches that detect if doors and windows are closed, cameras and motion detectors.
With that data it can decide if the user and or the authorities needs to be notified.

### **Challenges**

**Throughput** It needs to process the visual camera data before sending it to a storage drive.

**Responce** It must be able to make a complex decision within a few seconds.

**Testability and Debuggability** Minimal human interfaces in development.

**Reliability**  Minimal human interaction once deployed.

**Limited memory**  Need enough memory in system to hold all sensor data and camera images before they get stored away.

**Security** Only user should be able to access syste.m

**Cost**  Can't sell it if it cost too much to make.

**Communication**  Do our sensors share a bus, or do they each get a dedicated line.
