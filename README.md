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
| [attrib](https://folkehelseinstituttet.github.io/attrib)  	| Calculating attributable mortalities and incident risk ratios.  |
| [spread](https://folkehelseinstituttet.github.io/spread)  	| Different infectious disease spread models.  |
| [fhidata](https://folkehelseinstituttet.github.io/fhidata) 	| Preformatted structural data for Norway.  |
| [fhimaps](https://folkehelseinstituttet.github.io/fhimaps) 	| Preformatted maps of Norway that generally don't need geolibraries.  |
| [fhiplot](https://folkehelseinstituttet.github.io/fhiplot) 	| Helpful functions for creating outputs in the style used by FHI.  |

## News
- **sc 8.0.0** (linux) inserted at 2021-05-28 07:19:42
- **sc 8.0.0** (linux) inserted at 2021-05-27 08:52:55
- **fhidata 2021.5.26** (linux) inserted at 2021-05-26 10:24:34
- **sc 8.0.0** (linux) inserted at 2021-05-26 05:53:17
- **sc 8.0.0** (linux) inserted at 2021-05-25 12:52:23
- **plnr 2021.5.25** (linux) inserted at 2021-05-25 09:44:58
- **sc 8.0.0** (linux) inserted at 2021-05-25 07:54:05
- **plnr 2021.5.21** (linux) inserted at 2021-05-21 11:47:16
- **sc 8.0.0** (linux) inserted at 2021-05-21 05:52:21
- **plnr 2021.5.21** (linux) inserted at 2021-05-21 04:56:02
- **sc 8.0.0** (linux) inserted at 2021-05-20 06:52:19
- **sc 8.0.0** (linux) inserted at 2021-05-20 05:53:07
- **sc 8.0.0** (linux) inserted at 2021-05-19 13:52:15
- **plnr 2021.5.19** (linux) inserted at 2021-05-19 13:08:49
- **sc 8.0.0** (linux) inserted at 2021-05-18 05:06:05
- **fhiplot 2021.5.14** (linux) inserted at 2021-05-14 05:59:22
- **fhiplot 2021.5.14** (linux) inserted at 2021-05-14 05:43:22
- **attrib 2021.5.11** (linux) inserted at 2021-05-11 09:05:34
- **fhidata 2021.5.7** (linux) inserted at 2021-05-07 09:38:16
- **plnr 2021.5.4** (linux) inserted at 2021-05-04 12:04:21
- **plnr 2021.5.4** (linux) inserted at 2021-05-04 11:07:01
- **plnr 2021.5.4** (linux) inserted at 2021-05-04 10:42:48
- **plnr 2021.5.4** (linux) inserted at 2021-05-04 10:36:25
- **plnr 2021.5.4** (linux) inserted at 2021-05-04 08:23:39
- **fhiplot 2021.5.4** (linux) inserted at 2021-05-04 06:56:19
- **fhidata 2021.5.4** (linux) inserted at 2021-05-04 06:51:42
- **fhiplot 2021.5.4** (linux) inserted at 2021-05-04 06:44:15
- **fhidata 2021.4.29** (linux) inserted at 2021-04-29 07:47:57
- **fhiplot 2021.4.28** (linux) inserted at 2021-04-28 12:11:27
- **fhidata 2021.4.23** (linux) inserted at 2021-04-23 10:54:00
- **fhidata 2021.4.7** (linux) inserted at 2021-04-07 12:44:08
- **fhidata 2021.4.7** (linux) inserted at 2021-04-07 12:14:42
- **fhidata 2021.4.7** (linux) inserted at 2021-04-07 12:02:37
- **fhiplot 2021.3.29** (linux) inserted at 2021-03-29 11:11:31
- **fhidata 2021.3.26** (linux) inserted at 2021-03-26 13:52:49
- **fhiplot 2021.3.26** (linux) inserted at 2021-03-26 05:56:25
- **fhiplot 2021.3.26** (linux) inserted at 2021-03-26 04:56:41
- **fhidata 2021.3.26** (linux) inserted at 2021-03-26 04:53:50
- **fhiplot 2021.3.24** (linux) inserted at 2021-03-24 10:52:50
- **fhiplot 2021.3.24** (linux) inserted at 2021-03-24 10:39:42
- **sc 7.1.4** (linux) inserted at 2021-03-22 09:52:06
- **sc 7.1.4** (linux) inserted at 2021-03-22 08:52:04
- **sc 7.1.4** (linux) inserted at 2021-03-22 07:52:09
- **sc 7.1.4** (linux) inserted at 2021-03-22 06:52:23
- **sc 7.1.4** (linux) inserted at 2021-03-22 05:52:26
- **sc 7.1.4** (linux) inserted at 2021-03-19 10:52:03
- **fhiplot 2021.3.19** (linux) inserted at 2021-03-19 09:13:35
- **fhidata 2021.3.19** (linux) inserted at 2021-03-19 08:33:21
- **fhidata 2021.3.15** (linux) inserted at 2021-03-15 13:33:51
- **fhidata 2021.3.12** (linux) inserted at 2021-03-12 13:52:31
- **fhidata 2021.3.12** (linux) inserted at 2021-03-12 13:10:23
- **fhidata 2021.3.12** (linux) inserted at 2021-03-12 12:47:52
- **fhidata 2021.3.5** (linux) inserted at 2021-03-05 11:25:51
- **fhidata 2021.3.3** (linux) inserted at 2021-03-03 08:29:43
- **fhiplot 2021.3.2** (linux) inserted at 2021-03-02 05:35:35
- **fhidata 2021.3.1** (linux) inserted at 2021-03-01 07:05:02
- **fhidata 2021.3.1** (linux) inserted at 2021-03-01 06:40:11
- **fhidata 2021.3.1** (linux) inserted at 2021-03-01 06:28:37
- **fhidata 2021.3.1** (linux) inserted at 2021-03-01 06:14:28
- **fhidata 2021.2.26** (linux) inserted at 2021-02-26 11:25:51
- **fhidata 2021.2.26** (linux) inserted at 2021-02-26 11:10:11
- **fhidata 2021.2.26** (linux) inserted at 2021-02-26 06:41:33
- **fhidata 2021.2.25** (linux) inserted at 2021-02-25 13:04:30
- **fhidata 2021.2.24** (linux) inserted at 2021-02-24 08:57:47
- **fhidata 2021.2.24** (linux) inserted at 2021-02-24 08:47:04
- **sc 7.1.1** (linux) inserted at 2021-02-18 18:52:06
- **sc 7.1.1** (linux) inserted at 2021-02-18 18:01:34
- **fhidata 2021.2.18** (linux) inserted at 2021-02-18 05:07:11
- **fhidata 2021.2.18** (linux) inserted at 2021-02-18 04:53:01
- **fhiplot 2021.2.17** (linux) inserted at 2021-02-17 09:49:13
- **fhiplot 2021.2.17** (linux) inserted at 2021-02-17 09:10:36
- **fhidata 2021.2.17** (linux) inserted at 2021-02-17 06:09:47
- **fhidata 2021.2.17** (linux) inserted at 2021-02-17 05:59:04
- **fhidata 2021.2.17** (linux) inserted at 2021-02-17 04:32:27
- **fhidata 2021.2.16** (linux) inserted at 2021-02-16 06:53:09
- **fhidata 2021.2.16** (linux) inserted at 2021-02-16 06:46:26
- **fhidata 2021.2.16** (linux) inserted at 2021-02-16 06:24:26
- **fhidata 2021.2.16** (linux) inserted at 2021-02-16 05:19:29
- **fhidata 2021.2.15** (linux) inserted at 2021-02-15 08:03:35
- **fhidata 2021.2.15** (linux) inserted at 2021-02-15 07:54:56
- **fhidata 2021.2.11** (linux) inserted at 2021-02-11 11:42:01
- **fhidata 2021.2.11** (linux) inserted at 2021-02-11 08:39:08
- **fhidata 2021.2.11** (linux) inserted at 2021-02-11 06:51:19
- **fhidata 2021.2.11** (linux) inserted at 2021-02-11 05:46:30
- **fhidata 2021.2.8** (linux) inserted at 2021-02-08 13:54:51
- **fhimaps 2021.2.6** (linux) inserted at 2021-02-06 07:42:18
- **fhidata 2021.2.5** (linux) inserted at 2021-02-05 09:56:13
- **fhimaps 2021.2.5** (linux) inserted at 2021-02-05 09:00:22
- **fhidata 2021.2.5** (linux) inserted at 2021-02-05 08:54:57
- **fhidata 2021.2.5** (linux) inserted at 2021-02-05 08:37:27
- **sc 7.1.1** (linux) inserted at 2021-02-05 08:09:42
- **fhidata 2021.2.5** (linux) inserted at 2021-02-05 08:02:27
- **fhidata 2021.2.5** (linux) inserted at 2021-02-05 07:28:38
- **sc 7.1.1** (linux) inserted at 2021-02-05 06:54:54
- **spulsconnect 2021.2.5** (linux) inserted at 2021-02-05 06:08:50
- **sc 7.1.1** (linux) inserted at 2021-02-05 06:07:27
- **spulsconnect 2021.2.5** (linux) inserted at 2021-02-05 06:05:23
- **sc 7.1.1** (linux) inserted at 2021-02-05 06:03:50
- **attrib 2021.2.2** (linux) inserted at 2021-02-02 06:16:59
- **attrib 2021.2.1** (linux) inserted at 2021-02-01 09:17:53
- **fhimaps 2021.2.1** (linux) inserted at 2021-02-01 06:02:57
- **fhimaps 2021.2.1** (linux) inserted at 2021-02-01 06:00:04
- **attrib 2021.2.1** (linux) inserted at 2021-02-01 05:57:14
- **spread 2021.2.1** (linux) inserted at 2021-02-01 05:50:08
- **plnr 2021.2.1** (linux) inserted at 2021-02-01 05:38:28
- **fhiplot 2021.2.1** (linux) inserted at 2021-02-01 05:34:53
- **org 2021.2.1** (linux) inserted at 2021-02-01 05:31:50
- **fhimaps 2021.2.1** (linux) inserted at 2021-02-01 05:29:44
- **fhiplot 2021.2.1** (linux) inserted at 2021-02-01 05:26:43
- **fhiplot 2021.2.1** (linux) inserted at 2021-02-01 05:21:40
- **fhiplot 2021.2.1** (linux) inserted at 2021-02-01 05:16:41
- **fhiplot 2021.2.1** (linux) inserted at 2021-02-01 04:50:29
- **fhiplot 2021.2.1** (linux) inserted at 2021-02-01 04:40:23
- **spread 2021.2.1** (linux) inserted at 2021-02-01 04:32:29
- **fhiplot 2021.1.29** (linux) inserted at 2021-01-29 14:15:19
- **fhiplot 2021.1.29** (linux) inserted at 2021-01-29 12:51:55
- **fhiplot 2021.1.29** (linux) inserted at 2021-01-29 12:16:18
- **fhiplot 2021.1.29** (linux) inserted at 2021-01-29 11:51:23
- **fhiplot 2021.1.28** (linux) inserted at 2021-01-28 11:52:30
- **fhiplot 2021.1.28** (linux) inserted at 2021-01-28 11:34:20
- **fhiplot 2021.1.28** (linux) inserted at 2021-01-28 11:31:01
- **fhiplot 2021.1.28** (linux) inserted at 2021-01-28 11:24:54
- **fhiplot 2021.1.28** (linux) inserted at 2021-01-28 11:01:19
- **fhiplot 2021.1.28** (linux) inserted at 2021-01-28 07:41:53
- **fhimaps 2021.1.28** (linux) inserted at 2021-01-28 07:40:28
- **plnr 2021.1.28** (linux) inserted at 2021-01-28 07:38:16
- **spread 2021.1.28** (linux) inserted at 2021-01-28 07:36:50
- **org 2021.1.28** (linux) inserted at 2021-01-28 07:33:56
- **org 2021.1.28** (linux) inserted at 2021-01-28 07:29:40
- **spread 2021.1.28** (linux) inserted at 2021-01-28 07:28:52
- **org 2021.1.28** (linux) inserted at 2021-01-28 07:21:12
- **fhimaps 2021.1.28** (linux) inserted at 2021-01-28 07:15:25
- **fhiplot 2021.1.28** (linux) inserted at 2021-01-28 07:14:04
- **plnr 2021.1.28** (linux) inserted at 2021-01-28 07:13:15
- **spread 2021.1.28** (linux) inserted at 2021-01-28 06:51:46
- **spread 2021.1.28** (linux) inserted at 2021.01.28 06:47:47
- **plnr 2021.1.28** (linux) inserted at 2021.01.28 06:43:19
- **fhiplot 2021.1.28** (linux) inserted at 2021.01.28 06:29:49
- **fhimaps 2021.1.28** (linux) inserted at 2021.01.28 06:21:58
- **plnr 2021.1.28** (linux) inserted at 2021.01.28 06:18:22
- **plnr 2021.1.28** inserted at 2021.01.28 06:10:05
- **plnr 2021.1.28** inserted at 2021.01.28 06:04:57
