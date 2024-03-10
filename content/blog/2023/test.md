Title: SymPy: Python Library for Symbolic  Mathematics
Category: Devsprints proposal
Date: 2021-09-15 21:00
Author: Nikhil Maan (@sc0rpi0n101)
Slug: sympy-python-library-symbolic-mathematics
Summary: 

[SymPy](https://www.sympy.org/en/index.html) is a Python library for symbolic mathematics. It aims to become a full-featured computer algebra system (CAS) while keeping the code as simple as possible in order to be comprehensible and easily extensible. SymPy is written entirely in Python.

SymPy is a free and open-source Python library, distributed under the BSD license. What sets SymPy apart is its Python-centric design, ensuring compatibility and accessibility for Python developers. It boasts a lightweight footprint, relying exclusively on the pure Python mpmath library for arbitrary floating-point arithmetic. Beyond its standalone capabilities as an interactive tool, SymPy can be seamlessly integrated into various applications and extended with custom functions, enhancing its utility for developers across different domains.

### Prerequisites for Contributing to SymPy:

- Proficiency in Python programming.
- Basic understanding of mathematical concepts.
- Familiarity with SymPy's codebase (Optional, but beneficial).
- A development environment set up for SymPy (Refer to [SymPy's official documentation](https://docs.sympy.org/latest/guide/install.html) for instructions)

### Development Environment:

Ensure you have the following software/tools set up on your system:
    - Python: SymPy is a Python library, so you need to have Python installed. We recommend using Python 3.x, as it is the actively supported version.
    - Git: Git is essential for version control and collaboration. Install Git and configure it with your credentials.
    - SymPy Repository: Clone the SymPy repository from GitHub to your local machine using Git. This will serve as your development environment.
    - Virtual Environment: Consider using virtual environments (e.g., virtualenv or conda) to manage project dependencies and isolate your SymPy development environment.
    - Text Editor/IDE: Choose a text editor or integrated development environment (IDE) that you are comfortable with for writing Python code.
    - **Dependencies**: SymPy has a few dependencies that you need to install.
        -  **mpmath**: SymPy uses mpmath for arbitrary precision arithmetic. Install mpmath using pip:
            ```bash
            pip install mpmath
            ```

        - **Other dependencies**: SymPy has a few other optional dependencies. You can read more about them at our [Dependencies Guide.](https://docs.sympy.org/dev/contributing/dependencies.html)
        - 
           
For detailed setup instructions, please refer to our [Installation Guide](https://docs.sympy.org/latest/install.html)

### Contributing to SymPy:

SymPy is a community-driven project. We welcome contributions of all kinds, including code, documentation, tutorials, and more. If you are interested in contributing to SymPy, please read our [Contributor's Guide](https://docs.sympy.org/dev/contributing/introduction-to-contributing.html) for more information. 


- **GitHub Repository:** [SymPy GitHub Repository](https://github.com/sympy/sympy) - Access the source code and submit your contributions.

- **Issues:** [SymPy Issue Tracker](https://github.com/sympy/sympy/issues) - Find open issues that you can work on. Look for "beginner-friendly" labels for newcomers.

- **Introduction to Contributing:** [Introduction to Contributing Guide](https://docs.sympy.org/dev/contributing/introduction-to-contributing.html) - Get an overview of how to start contributing to SymPy.

- **Easy-to-Fix Issues:** Explore our list of [easy-to-fix issues](https://github.com/sympy/sympy/issues?q=is%3Aopen+is%3Aissue+label%3Aeasy-to-fix) for beginners looking to make their first contributions.

- **Documentation Style Guide:** When contributing to documentation, follow our [Docstring Style Guide](https://docs.sympy.org/dev/contributing/documentation-style-guide.html) for consistency and quality.

- **Code of Conduct:** Review our [Code of Conduct](https://github.com/sympy/sympy/blob/master/CODE_OF_CONDUCT.md) to understand the community guidelines.
