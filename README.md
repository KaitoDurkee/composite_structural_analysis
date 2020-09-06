# composite_structural_analysis
Composite Structural Analysis (CSA) is an open-source structural analysis tool for performance prediction of composite structures and is suitable for use in conceptual design studies.

# Authors
Currently, the following individuals have contributed to this project:
* Kaito J. Durkee ([LinkedIn](https://www.linkedin.com/in/kaito-durkee/), [GitHub](https://github.com/KaitoDurkee))

# License
CSA is licensed under a GPL-3.0 license - see the [LICENSE.md](https://github.com/KaitoDurkee/composite_structural_analysis/blob/master/LICENSE) file in the top-level directory.

# Contributing
All source code is publicly hosted on [GitHub](https://github.com/KaitoDurkee/composite_structural_analysis), and contributions are welcome. Please contact [Kaito J. Durkee](https://github.com/KaitoDurkee) for details on how to contribute. Note that all code must follow the standards outlined in the [Google Python Style Guide](https://google.github.io/styleguide/pyguide.html) for Python and the [Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html) for C/C++.

# Decisions and Alternatives
Python was selected as the main programming language due to its relative ease during development, and due to contributor familiarity. The main trade-off is lower performance (computation speed and resource usage). Alternatives include C/C++, Java, Go, and many others. The lowest possible version of Python will be used for increased usability by end users. Should performance issues arise using Python, performance-impacting modules will be rewritten in C/C++.
