# Test Case Register — UML Diagrams

This repository contains the UML diagrams created for the **Test Case Register** modeling assignment. The diagrams describe the system's structure and the main workflows before and during implementation.

## Project Overview

The Test Case Register is a simple console-based application designed to register test cases and display the registered test cases. Each test case contains identifying information and test steps with expected results. The application stores data in memory.

The goal of this repository is to document the system design and show how the design developed from an initial model into a more detailed structure.

## UML Diagrams

### Class Diagrams

- [Class Diagram — Version 1](testcase-class-diagram-v1.png): Initial design of the system.
- [Class Diagram — Version 2](testcase-class-diagram-v2.png): Revised design reflecting the implementation structure and responsibilities.
- [PlantUML source](class-diagram.puml)

### Register a Test Case

- [Activity Diagram](register-testcase-activity-diagram.png): Shows the steps involved in registering a test case.
- [Sequence Diagram](register-testcase-sequence-diagram.png): Shows the interactions between system components during registration.
- [Activity Diagram source](activity-diagram.puml)
- [Sequence Diagram source](sequence-diagram.puml)

### Show All Test Cases

- [Activity Diagram](get-all-testcases-activity%20diagram.png): Shows the flow for retrieving and displaying registered test cases.
- [Sequence Diagram](getall-testcases-sequence-diagram.png): Shows the interactions between components when retrieving test cases.
- [Activity Diagram source](activity-diagram-show-all.puml)
- [Sequence Diagram source](sequence-diagram-show-all.puml)

## Design Approach

The system follows a separation of responsibilities:

- **Models** represent test cases, steps, and data transferred between components.
- **Dialogs** handle user interaction in the console.
- **Services** manage application logic and validation.
- **Repository** stores and retrieves test cases in memory.
- **Utilities** provide reusable helper functions.


## Tools

The diagrams are provided as PNG images for easy viewing and as `.puml` files for editing with [PlantUML](https://plantuml.com/).

## Related Implementation

The Python implementation is maintained in a separate repository: https://github.com/elhammmi/assignment1-test-case-python. 
