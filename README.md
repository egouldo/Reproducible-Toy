# A Toy Reproducible Project with the Remake package: and some playing around with dplyr

## Getting to know dplyr and tidyr:


## Getting to know Remake:

### Accessing the results of remake workflow interactively:

How do you access the results of your remake workflow, if you'd like to do some interactive work in the console as you're writing some new code?

easy! Re-run analyses or access cache:

```
remake::make()
```

Then:

```
remake::fetch("<insert_target_name_here>")
```

Cool!
