For a CRAN submission we recommend that you fix all NOTEs, WARNINGs and ERRORs.
## Test environments
- R-hub windows-x86_64-devel (r-devel)
- R-hub ubuntu-gcc-release (r-release)
- R-hub fedora-clang-devel (r-devel)

## R CMD check results
❯ On windows-x86_64-devel (r-devel)
  checking CRAN incoming feasibility ... [22s] NOTE
  Maintainer: 'Livio Bätscher <livio_999@hotmail.com>'
  
  New submission
  
  Possibly misspelled words in DESCRIPTION:
    Paulsen (13:14)
    WGS (11:41)
    rner (13:29)
  
  Found the following (possibly) invalid URLs:
    URL: https://cran.r-project.org/web/packages/CoordinateCleaner/index.html
      From: inst/doc/ElevDistr.html
      Status: 200
      Message: OK
      CRAN URL not in canonical form
    URL: https://cran.r-project.org/web/packages/RANN/index.html
      From: inst/doc/ElevDistr.html
      Status: 200
      Message: OK
      CRAN URL not in canonical form
    URL: https://cran.r-project.org/web/packages/devtools/index.html
      From: inst/doc/ElevDistr.html
      Status: 200
      Message: OK
      CRAN URL not in canonical form
    URL: https://cran.r-project.org/web/packages/rgbif/index.html
      From: inst/doc/ElevDistr.html
      Status: 200
      Message: OK
      CRAN URL not in canonical form
    URL: https://cran.r-project.org/web/packages/tidyverse/index.html
      From: inst/doc/ElevDistr.html
      Status: 200
      Message: OK
      CRAN URL not in canonical form

❯ On windows-x86_64-devel (r-devel)
  checking examples ... [50s] NOTE
  Examples with CPU (user + system) or elapsed time > 5s
                          user system elapsed
  distance_to_treeline    6.35   0.28   26.83
  classify_above_treeline 3.92   0.10   11.97
  generate_point_df       0.09   0.00    8.97

❯ On windows-x86_64-devel (r-devel)
  checking for non-standard things in the check directory ... NOTE
  Found the following files/directories:
    ''NULL''

❯ On windows-x86_64-devel (r-devel)
  checking for detritus in the temp directory ... NOTE
  Found the following files/directories:
    'lastMiKTeXException'

❯ On ubuntu-gcc-release (r-release)
  checking CRAN incoming feasibility ... [7s/46s] NOTE
  Maintainer: ‘Livio Bätscher <livio_999@hotmail.com>’
  
  New submission
  
  Possibly misspelled words in DESCRIPTION:
    Körner (13:26)
    Paulsen (13:14)
    WGS (11:41)
  
  Found the following (possibly) invalid URLs:
    URL: https://cran.r-project.org/web/packages/CoordinateCleaner/index.html
      From: inst/doc/ElevDistr.html
      Status: 200
      Message: OK
      CRAN URL not in canonical form
    URL: https://cran.r-project.org/web/packages/devtools/index.html
      From: inst/doc/ElevDistr.html
      Status: 200
      Message: OK
      CRAN URL not in canonical form
    URL: https://cran.r-project.org/web/packages/RANN/index.html
      From: inst/doc/ElevDistr.html
      Status: 200
      Message: OK
      CRAN URL not in canonical form
    URL: https://cran.r-project.org/web/packages/rgbif/index.html
      From: inst/doc/ElevDistr.html
      Status: 200
      Message: OK
      CRAN URL not in canonical form
    URL: https://cran.r-project.org/web/packages/tidyverse/index.html
      From: inst/doc/ElevDistr.html
      Status: 200
      Message: OK
      CRAN URL not in canonical form
    The canonical URL of the CRAN page for a package is 
      https://CRAN.R-project.org/package=pkgname

❯ On ubuntu-gcc-release (r-release)
  checking examples ... [14s/88s] NOTE
  Examples with CPU (user + system) or elapsed time > 5s
                           user system elapsed
  classify_above_treeline 6.304  0.099  31.874
  distance_to_treeline    5.898  0.155  44.225

❯ On ubuntu-gcc-release (r-release), fedora-clang-devel (r-devel)
  checking HTML version of manual ... NOTE
  Skipping checking HTML validation: no command 'tidy' found

❯ On fedora-clang-devel (r-devel)
  checking CRAN incoming feasibility ... [8s/106s] NOTE
  Maintainer: ‘Livio Bätscher <livio_999@hotmail.com>’
  
  New submission
  
  Possibly misspelled words in DESCRIPTION:
    Körner (13:26)
    Paulsen (13:14)
    WGS (11:41)
  
  Found the following (possibly) invalid URLs:
    URL: https://cran.r-project.org/web/packages/CoordinateCleaner/index.html
      From: inst/doc/ElevDistr.html
      Status: 200
      Message: OK
      CRAN URL not in canonical form
    URL: https://cran.r-project.org/web/packages/RANN/index.html
      From: inst/doc/ElevDistr.html
      Status: 200
      Message: OK
      CRAN URL not in canonical form
    URL: https://cran.r-project.org/web/packages/devtools/index.html
      From: inst/doc/ElevDistr.html
      Status: 200
      Message: OK
      CRAN URL not in canonical form
    URL: https://cran.r-project.org/web/packages/rgbif/index.html
      From: inst/doc/ElevDistr.html
      Status: 200
      Message: OK
      CRAN URL not in canonical form
    URL: https://cran.r-project.org/web/packages/tidyverse/index.html
      From: inst/doc/ElevDistr.html
      Status: 200
      Message: OK
      CRAN URL not in canonical form
    The canonical URL of the CRAN page for a package is 
      https://CRAN.R-project.org/package=pkgname

❯ On fedora-clang-devel (r-devel)
  checking examples ... [15s/88s] NOTE
  Examples with CPU (user + system) or elapsed time > 5s
                           user system elapsed
  classify_above_treeline 6.422  0.073  31.272
  distance_to_treeline    6.043  0.196  43.525
  generate_point_df       0.071  0.000   6.430

0 errors ✔ | 0 warnings ✔ | 9 notes ✖
