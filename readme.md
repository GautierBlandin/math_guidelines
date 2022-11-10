# Do and don't in math projects
## Project architecture
### Don't
Keep everything in one file

![dont architecture](images/architecture/dont.png)
### Do
Separate different logical steps into different modules

![do architecture](images/architecture/do.png)

## Functionalities

### Don't

Mash functionalities together in one big main script

![dont functions](images/functions/dont.png)
### Do
Separate functionalities into functions, and group similar functionalities in logical modules
![do_main](images/functions/do_main.png)
![do_parsing](images/functions/do_parsing.png)
![do_geometry](images/functions/do_geometry.png)
![do_result_printing](images/functions/do_result_printing.png)

## Git

### Don't
- Commit unrelated functionalities together
- Commit without explaining what the commit does
- Commit multiple functionalities together

![dont_git](images/git/dont.png)

### Do
- Commit atomic changes
- Explain concisely what the commit does
- Use imperative style

![do_git](images/git/do.png)