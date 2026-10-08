# Yoav Ben Noon

Software Engineering student focused on building practical, maintainable systems with clean architecture, strong testing habits, and thoughtful user-facing behavior.

I enjoy working close to the product and close to the code: understanding the real workflow, modeling the problem clearly, and then implementing solutions that are reliable enough to explain, test, and improve.

[LinkedIn](https://www.linkedin.com/in/yoavbennoon/) | [GitHub](https://github.com/yoavbenNun)

## Featured Projects

### [Exam Scheduler](https://github.com/yoavbenNun/Test_Scheduler)

C++ / Qt / QML desktop application for generating and evaluating university exam schedules.

- Designed a layered architecture that separates UI, services, scheduling logic, data models, validation, and metrics calculation.
- Refactored scheduling execution into a safer worker-thread lifecycle so long-running generation does not block the UI.
- Optimized metrics calculation runtime using prepared block data, indexed course lookup, integer date keys, and reduced repeated sorting.
- Added focused unit and integration tests for scheduling behavior, metrics correctness, sorting, and async service lifecycle.

### [DriveStack](https://github.com/yoavbenNun/DriveStack)

Full-stack file management project with separate Web and Mobile versions.

- Built a file-drive style application with user-facing flows for managing stored files and navigating project data.
- Maintained separate branches for platform-specific versions: `Web_version` and `Mobile_version`.
- Focused on clean client-server structure, practical UI behavior, and readable project organization.

### Operating Systems Assignment 3

Systems programming assignment focused on low-level implementation details, process behavior, synchronization, and correctness under constrained execution.

## Technical Focus

- C++ development with Qt 6, QML, CMake, and unit testing.
- Backend and full-stack fundamentals, including API design and data-driven application structure.
- Performance-oriented refactoring: finding real bottlenecks, measuring runtime, and optimizing without changing external behavior.
- Software design practices: layered architecture, service boundaries, worker threads, strategy-based validation, and maintainable test coverage.

## Technologies

`C++` `Qt 6` `QML` `CMake` `Java` `JavaScript` `React` `Node.js` `Git` `GitHub` `Agile`

## What I Care About

- Clear ownership between components.
- Code that can be tested and explained.
- Performance improvements backed by measurements.
- Practical UI that supports the real workflow instead of just looking good in isolation.
