# CodeAlpha_Static_Code_Analysis_Bandit
This project integrates static code analysis to detect potential security vulnerabilities within the code. We utilize the Bandit tool, a Python static analyzer, to scan for common security issues such as hardcoded credentials, and suspicious function calls. Regularly running Bandit aids in maintaining a secure codebase by identifying these issues early in the development process.

Installation Guide:

Install Bandit: Use pip, a Python package manager, to install Bandit. In your terminal, execute the following command:     pip install bandit.

Running Bandit:

Run Bandit on your Python files. Use the command           bandit -r [filename] -f [output file type] -o [output filename]
