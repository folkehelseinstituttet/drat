## fhiverse

The `fhiverse` is a set of R packages developed by the Norwegian Institute of Public Health to help solve problems that frequently occur when performing infectious disease surveillance.

If you want to install the dev versions (or access packages that haven't been released on CRAN), run `usethis::edit_r_profile()` to edit your `.Rprofile`. Then write in:

```
options(repos=structure(c(
  FHI="https://folkehelseinstituttet.github.io/drat/",
  CRAN="https://cran.rstudio.com"
)))
```

Save the file and restart R. This will allow you to install `fhiverse` packages from the FHI registry.

Current `fhiverse` packages are:

| Name    	| Info                                                             	|
|---------	|------------------------------------------------------------------	|
| [org](https://folkehelseinstituttet.github.io/org)         	| A system to help you organize projects.  |
| [plnr](https://folkehelseinstituttet.github.io/plnr)    	  | A system to help you plan analyses.  |
| [spread](https://folkehelseinstituttet.github.io/spread)  	| Different infectious disease spread models.  |
| [fhidata](https://folkehelseinstituttet.github.io/fhidata) 	| Preformatted structural data for Norway.  |
| [fhimaps](https://folkehelseinstituttet.github.io/fhimaps) 	| Preformatted maps of Norway that generally don't need geolibraries.  |
| [fhiplot](https://folkehelseinstituttet.github.io/fhiplot) 	| Helpful functions for creating outputs in the style used by FHI.  |

## News
- **plnr 2021.1.28** (linux) inserted at 2021.01.28 06:43:19
- **fhiplot 2021.1.28** (linux) inserted at 2021.01.28 06:29:49
- **fhimaps 2021.1.28** (linux) inserted at 2021.01.28 06:21:58
- **plnr 2021.1.28** (linux) inserted at 2021.01.28 06:18:22
- **plnr 2021.1.28** inserted at 2021.01.28 06:10:05
- **plnr 2021.1.28** inserted at 2021.01.28 06:04:57
