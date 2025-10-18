Git Assignment – HeroVired
This repository is part of the Hero Vired Git Assignment showcasing Git workflows, branching, and release management using Python scripts.



Repository Structure
git_assignment_HeroVired/
├── CalculatorPlus.py       - Enhanced calculator with basic operations
├── GeometryCalculator.py   - Script for geometry-based computations
├── .gitattributes          - Git attributes configuration
└── README.md               - Project documentation


Branch structure:
Branch Name	Description
main	                     Stable branch — final tested code and releases
dev	                     Active development branch — integrates new features
feature/circle-area	      Adds circle area calculation functionality
feature/rectangle-area	   Adds rectangle area calculation functionality
geometry-calculator	      Branch dedicated to geometry-related logic
lfs	                     Used for testing Git LFS (Large File Storage) integration

Setup Instructions:
1. Clone the repository:
   git clone https://github.com/Prashanthv10/git_assignment_HeroVired.git
   cd git_assignment_HeroVired

2. Run scripts:
   python CalculatorPlus.py
   python GeometryCalculator.py

Usage
CalculatorPlus: Performs basic arithmetic operations like addition, subtraction, multiplication, and division.
Usage: python CalculatorPlus.py
GeometryCalculator: Calculates area, perimeter, and other geometric values.
Usage: python GeometryCalculator.py
Git Workflow

1. Create a new feature branch from dev:
   git checkout -b feature/your-feature-name

2. Commit your changes:
   git commit -m "Added new feature"

3. Push and open a Pull Request to dev:
   git push origin feature/your-feature-name

4. Once tested, merge into main for release.

Versioning & Releases

- Current version: v2.0.0
- Follow Semantic Versioning (MAJOR.MINOR.PATCH)


Author

Prashanth V
Email: prashant301k@gmail.com
GitHub: https://github.com/Prashanthv10


