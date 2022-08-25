# skeleton-fortran
learn modern fortran: setup an "up to date" environment.

## WHAT'S IN THE REPOSITORY:
`environment.yml` conatins the dependencies needed to create the environment of Vscode:
    
    1. fortls - Modern Fortran plugin for VScode
    2. fpm - Fortran Package Manager
    3. gfortran - Fortran compiler (deleted)
    4. findent - Formatter
    5. jupyter-notebooks - app to open interactive web-editor
    6. lfortran - Interactive compiler to use fortran in Jupyter-notebooks


In `.vscode/settings.json` is saved the configuration of `fortls`
To create a new repository `fpm` automatize the creation of the repository. execute this command in the terminal at the folder desired:

```bash
fpm create project_name # --> Create complete repo
fpm build               # --> Compile fortran
fpm run                 # --> Run code, compile if needed
fpm test                # --> Run tests, compile if needed
```
:question: - I can include compiler in the conda environment or directly install in ubuntu. What aproach is better?

:question: - Can I use oneApi HPC toolkit which includes Inetl-Fortran compilers?

:question: - How to configure debug in Vscode?

:exclamation: - FPM project structure repo/app; repo/src; repo/tests

---
