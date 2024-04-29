# Test_cloning #

Test cooperation after cloning, using code to create life tables and fit Bayesian regression models.

# What is the easiest way to access this project? #

If you want to see and work with the code, then:

1. Clone, fork or download the project from github to your local machine.
See this link for the difference between cloning and forking. https://github.com/orgs/community/discussions/35849

2. Open the Test_cloning.Rproj file and renv() will automatically bootstrap itself.

3. Use renv::restore() to install all of the packages. Say yes.

4. At this point, you can use the project with the same package versions that are stored in the renv.lock file.

Note: you can completely ignore the "install_packages.Rmd" file.

# What are the main project files? #

**Exercise1.Rmd**

Exercise 1 creates a simulated data file for 1 subject, sets up a life table for each condition, and plots the estimates of the discrete-time hazard, survivor, and conditional accuracy functions.

**Exercise2.Rmd**

Exercise 2 creates a simulated data file for n subjects, and uses functional programming to set up life tables and make plots of the h(t), S(t), and ca(t) functions.

**Exercise3.Rmd**

Here we apply the functions to existing (but reduced) data file from Panis and Schmidt (2016).

**Exercise4.Rmd**

Here we start with fitting bayesian hazard regression models.

**General comments**

When plotting the data, some warning messages will be generated, like these:

1. Removed 2 rows containing missing values or values outside the scale range (`geom_line()`). 
2. Removed 2 rows containing missing values or values outside the scale range (`geom_point()`). 
3. Removed 2 rows containing missing values or values outside the scale range (`geom_segment()`).

The warning messages are generated because some bins have no hazard and ca(t) estimates, and no error bars. They can thus safely be ignored.
