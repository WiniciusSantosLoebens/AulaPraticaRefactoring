# Video Store Refactoring Project

## Overview
This is an educational Java project for practicing refactoring techniques. It implements a video rental store system with classes for Movies, Rentals, and Customers. The project is based on Martin Fowler's classic refactoring examples and is used in software engineering courses.

**Purpose**: Practice systematic refactoring techniques on a legacy codebase  
**Language**: Java  
**Current State**: Initial version ready for refactoring exercises

## Project Structure
```
.
├── Movie.java       - Represents movies available for rent
├── Rental.java      - Represents a rental transaction
├── Customer.java    - Represents customers and generates rental statements
├── README.md        - Complete refactoring exercise instructions (Portuguese)
└── classdiagram.png - Class diagram for reference
```

## Recent Changes
- **2025-11-18**: Initial project setup in Replit environment
  - Installed Java (GraalVM 19.0.2)
  - Created initial Java source files (Movie, Rental, Customer)
  - Configured compilation workflow
  - Added .gitignore for Java

## Architecture
This is a simple object-oriented design representing a video rental system:

- **Movie**: Contains movie information (title, price code for REGULAR/NEW_RELEASE/CHILDRENS)
- **Rental**: Links a Movie with rental duration
- **Customer**: Manages rentals and generates statements showing charges and frequent renter points

The code intentionally contains design issues (long methods, feature envy, primitive obsession) that students will refactor through the exercises outlined in README.md.

## How to Use
This is a library project without a main method - it's designed for refactoring practice, not execution.

**Workflow**: The "Compile Java" workflow compiles all Java files to verify there are no compilation errors. This runs automatically and must pass after each refactoring step.

**Important**: The README.md contains a complete step-by-step refactoring tutorial. Students should follow the commits 1-15 as outlined, ensuring code compiles after each step.

## Development Notes
- Uses legacy Java collections (Vector, Enumeration) intentionally - part of the original example
- Compilation warnings about unchecked operations are expected and acceptable
- No frontend or backend - this is a pure Java library project
- Focus is on code structure and design improvements, not functionality
