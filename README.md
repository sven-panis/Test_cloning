# Test_cloning #

Test cooperation after cloning, using code to create life tables and fit Bayesian regression models.

# What is the easiest way to access this project? #

If you want to see and work with the code, then:

1. Clone, fork or download the project from github to your local machine.
See this link for the difference between cloning and forking. https://github.com/orgs/community/discussions/35849

2. Open the Test_cloning.Rproj file and renv() will automatically bootstrap itself.

3. Use renv::restore() to install all of the packages. Say yes.

4. At this point, you can use the project with the same package versions that were stored in the renv.lock file.

Note: you can completely ignore the "intsall_packages.Rmd" file.

# What are the main project files? #

**Exercise1.Rmd**

Sven - you could put a description in here and the ones below...

When plotting the data, some warning messages will be generated, like these:
1: Removed 2 rows containing missing values or values outside the scale range (`geom_line()`). 
2: Removed 2 rows containing missing values or values outside the scale range (`geom_point()`). 
3: Removed 2 rows containing missing values or values outside the scale range (`geom_segment()`).
This happens because for some bins ....


**Exercise2.Rmd**
