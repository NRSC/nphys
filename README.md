nphys package readMe
================

<!-- README.md is generated from README.Rmd. Please edit that file -->

    ## [1] "wd"     "md"     "files"  "ABF"    "traces"

# nphys package build

The purpose of the nphys package is to develop data management tools and
analysis methods for data generated over the course of a neurophysiology
experiment. This project is currently geared towards field long-term
depression experiments and whole cell patch clamp experiments.

## Typical project build

Typical project builds are templates for certain types of projects being
run. I generally label a project directory by labelling it proj followed
letter identifiers that are short and easy to reference. `e.g. projRTT`

This readme utilizes the field `data(field)` and DGDpatch
`data(DGDpatch)` datasets from the projDGDev project and the RTTpatch
`data(RTTpatch)` data set from the projRTT project.

# Importing data

> currently supports abf file format import that depends on the readABF
> package and .dat files that are exported as .mat format from
> patchmaster.

Import functions focus on building a single .rda file for each piece of
data added to the project. You can name that rda file whatever you like.
I generally save the slice or patch code (),

## the rda file

The rda file is what allows you to loop over large datasets and be able
to address multiple factors (i.e Baseline data, stimulus data, various
channels etc.). It purpose is to generate workable dataset for your
projects to easily read and apply functions to. \> Patterns allow for
pathways for analysis to develop.

This .rda file includes a workding directory that is relative to the dir
project folder.

> The dir folder is a symlink crafted to your project directory that
> points to the source of your raw data files. This can be a local drive
> or a server. I find this useful because I find it easiest to build the
> package around the data source, therefore wherever you clone your
> repo, all scripts or loops can source “\~/proj/dir” as long as you
> keep your project directory in your home folder (generally UNIX:
> /usr/<username>/home == “\~” or Win: C:/Users/<username>/Doccuments ==
> “\~”) or simply “dir” when working in your project directory. his
> project folder can be the source of your raw data that are often made
> up of large files that are incompatible with git, making your
> .gitignore only need to ignore the dir folder.

### 

## Long-term depression

Field recordings at the medial perforant path in the DG.

``` r

#field$LTD <- nphys::field_LTD(field)
```

## License

This package is free and open source software, licensed under GPL-3.
