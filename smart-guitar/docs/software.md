# Software

## Responsibilities

The software layer is expected to:

1. Read hardware inputs
2. Filter / process sensor data
3. Detect meaningful events
4. Trigger outputs or actions
5. Communicate with external software when required

## Firmware Architecture

A modular structure is preferred:

```text
setup()
  ├── initialize hardware
  ├── configure communication
  └── load settings

loop()
  ├── read inputs
  ├── process signals
  ├── detect events
  ├── update outputs
  └── communicate
```

## Development Approach

Features should be tested individually before combining them.

Example progression:

1. Confirm microcontroller operation
2. Test one input
3. Test one output
4. Add sensor processing
5. Add communication
6. Combine modules
7. Test integrated system
