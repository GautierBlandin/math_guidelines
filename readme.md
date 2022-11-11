# Do and don't in math projects
## Warning
#### Code that does not try to follow the guidelines about project architecture and functionalities will not be reviewed beyond "You should follow the guidelines"
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

## Testing

### Don't
- Not test important functions
- Test from a script

![dont_testing](images/testing/dont.png)

### Do
- Test from a test file
- Test important functions
- Use a testing framework
- Have an appropriate architecture

![do_testing](images/testing/do_architecture.png)
![do_testing](images/testing/do_geometry.png)
![do_testing](images/testing/do_test_geometry.png)

Some IDEs let you directly run tests from the file, and you can also run them from the command line with pytest

![do_testing](images/testing/do_run_test.png )
