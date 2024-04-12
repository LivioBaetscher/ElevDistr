## Resubmission

This is a resubmission. Thank you very much for the valuable review of my package.

I changed the citation in the DESCRIPTION file.
I remove the abbreviation in the DESCRIPTION file.

I replace \dontrun() with \donttest() whenever possible. Now it is only used if the API keys are missing.
I added \donttest() if data is downloaded.

I hope this addresses all issues.

Best wishes,
Livio

-------------

Von: Beni Altmann <benjamin.altmann@wu.ac.at>
Gesendet: Freitag, 8. März 2024 21:34
An: Livio Bätscher <livio_999@hotmail.com>; CRAN <cran-submissions@r-project.org>
Betreff: Re: CRAN Submission ElevDistr 1.0.7
 
Thanks,

Please write references in the description of the DESCRIPTION file in
the form
authors (year) <doi:...>
authors (year) <arXiv:...>
authors (year, ISBN:...)
or if those are not available: authors (year) <[https:...]https:...>
with no space after 'doi:', 'arXiv:', 'https:' and angle brackets for
auto-linking. (If you want to add a title as well please put it in
quotes: "Title")

Please always explain all acronyms in the description text. -> WGS 84

\dontrun{} should only be used if the example really cannot be executed
(e.g. because of missing additional software, missing API keys, ...) by
the user. That's why wrapping examples in \dontrun{} adds the comment
("# Not run:") as a warning for the user. Does not seem necessary.
Please replace \dontrun with \donttest.
Please unwrap the examples if they are executable in < 5 sec, or replace
dontrun{} with \donttest{}.

Please put functions which download data in \donttest{}.

Please fix and resubmit.

Best,
Benjamin Altmann

On 07.03.2024 14:26, CRAN Package Submission Form wrote:
> [This was generated from CRAN.R-project.org/submit.html]
>
> The following package was uploaded to CRAN:
> ===========================================
>
> Package Information:
> Package: ElevDistr
> Version: 1.0.7
> Title: Calculate the Distance to the Nearest Local Treeline
> Author(s): Livio Bätscher [aut, cre]
>    (<https://orcid.org/0000-0002-2989-930X>), Jurriaan M. de Vos
>    [aut] (<https://orcid.org/0000-0001-6428-7774>)
> Maintainer: Livio Bätscher <livio_999@hotmail.com>
> Depends: R (>= 3.5.0)
> Suggests: knitr, rgbif, rmarkdown, testthat (>= 3.0.0), tidyverse
> Description: A method to calculate the distance to the climatic tree line
>    for large data sets of coordinates (WGS 84) with geographical
>    uncertainty. The default thresholds and the treeline
>    definition is based on Paulsen and Körner, Alp. Bot. 124:
>    1-12 (2014), users are free to decide what climate layers
>    they would like to use.
> License: MIT + file LICENSE
> Imports: ggmap, ggplot2, RANN, terra
>
>
> The maintainer confirms that he or she
> has read and agrees to the CRAN policies.
>
> Submitter's comment: ── ElevDistr 1.0.7: NOTE
>
>    Build ID:
>    ElevDistr_1.0.7.tar.gz-1555ff0aa0bb4aaeaf4fa57702cc2177
>  
>     Platform:   Windows Server 2022, R-devel, 64 bit
>   
>    Submitted:  2h 38m 1.2s ago
>    Build time: 6m
>    33.6s
>
> ❯ checking CRAN incoming feasibility ...
>    [23s] NOTE
>   
>    New submission
>   
>    Possibly
>    misspelled words in DESCRIPTION:
>      Paulsen (13:14)
>  
>       WGS (11:41)
>      rner (13:29)
>    Maintainer: 'Livio
>    Bätscher <livio_999@hotmail.com>'
>
> ❯ checking
>    examples ... [27s] NOTE
>    Examples with CPU (user +
>    system) or elapsed time > 5s
>                          
>     user system elapsed
>    classify_above_treeline 3.87
>    0.11   12.26
>    generate_point_df       0.08   0.01
>    8.81
>
> ❯ checking for non-standard things in the
>    check directory ... NOTE
>    Found the following
>    files/directories:
>      ''NULL''
>
> ❯ checking for
>    detritus in the temp directory ... NOTE
>    Found the
>    following files/directories:
>     
>    'lastMiKTeXException'
>
> 0 errors ✔ | 0 warnings ✔
>    | 4 notes ✖
>
> ── ElevDistr 1.0.7: NOTE
>
>    Build
>    ID:
>    ElevDistr_1.0.7.tar.gz-c256c60656df4e7ba7f990ac38964deb
>  
>     Platform:   Ubuntu Linux 20.04.1 LTS, R-release,
>    GCC
>    Submitted:  2h 38m 1.3s ago
>    Build time: 2h
>    27m 47.7s
>
> ❯ checking CRAN incoming feasibility ...
>    [6s/41s] NOTE
>    Maintainer: ‘Livio Bätscher
>    <livio_999@hotmail.com>’
>   
>    New submission
>   
>   
>    Possibly misspelled words in DESCRIPTION:
>      Körner
>    (13:26)
>      Paulsen (13:14)
>      WGS (11:41)
>
> ❯
>    checking examples ... [9s/38s] NOTE
>    Examples with
>    CPU (user + system) or elapsed time > 5s
>              
>                  user system elapsed
>   
>    classify_above_treeline 5.945  0.141  20.796
>   
>    distance_to_treeline    0.674  0.063   7.858
>
> ❯
>    checking HTML version of manual ... NOTE
>    Skipping
>    checking HTML validation: no command 'tidy' found
>
> 0
>    errors ✔ | 0 warnings ✔ | 3 notes ✖
>
> ──
>    ElevDistr 1.0.7: NOTE
>
>    Build ID:
>    ElevDistr_1.0.7.tar.gz-f9febccf5b074e9aa1b34f4d7033efe0
>  
>     Platform:   Fedora Linux, R-devel, clang, gfortran
>   
>    Submitted:  2h 38m 1.5s ago
>    Build time: 2h 8m
>    16.8s
>
> ❯ checking CRAN incoming feasibility ...
>    [7s/43s] NOTE
>    Maintainer: ‘Livio Bätscher
>    <livio_999@hotmail.com>’
>   
>    New submission
>   
>   
>    Possibly misspelled words in DESCRIPTION:
>      Körner
>    (13:26)
>      Paulsen (13:14)
>      WGS (11:41)
>
> ❯
>    checking examples ... [9s/44s] NOTE
>    Examples with
>    CPU (user + system) or elapsed time > 5s
>              
>                  user system elapsed
>   
>    classify_above_treeline 6.253  0.055  23.156
>   
>    distance_to_treeline    0.696  0.115   8.578
>   
>    generate_point_df       0.069  0.004   6.998
>
> ❯
>    checking HTML version of manual ... NOTE
>    Skipping
>    checking HTML validation: no command 'tidy' found
>
> 0
>    errors ✔ | 0 warnings ✔ | 3 notes ✖
>
> =================================================
>
> Original content of DESCRIPTION file:
>
> Package: ElevDistr
> Title: Calculate the Distance to the Nearest Local Treeline
> Version: 1.0.7
> Authors@R: c(
>      person("Livio", "Bätscher", , "livio_999@hotmail.com", role = c("aut", "cre"),
>             comment = c(ORCID = "0000-0002-2989-930X")),
>      person("Jurriaan M.", "de Vos", , "jurriaan.devos@unibas.ch", role = "aut",
>             comment = c(ORCID = "0000-0001-6428-7774"))
>    )
> Description: A method to calculate the distance to the climatic tree line
>      for large data sets of coordinates (WGS 84) with geographical
>      uncertainty.  The default thresholds and the treeline definition is
>      based on Paulsen and Körner, Alp. Bot. 124: 1-12 (2014), users are
>      free to decide what climate layers they would like to use.
> License: MIT + file LICENSE
> URL: https://github.com/LivioBaetscher/ElevDistr
> BugReports: https://github.com/LivioBaetscher/ElevDistr/issues
> Depends: R (>= 3.5.0)
> Imports: ggmap, ggplot2, RANN, terra
> Suggests: knitr, rgbif, rmarkdown, testthat (>= 3.0.0), tidyverse
> VignetteBuilder: knitr
> Config/testthat/edition: 3
> Encoding: UTF-8
> LazyData: true
> Roxygen: list(markdown = TRUE)
> RoxygenNote: 7.2.3
> NeedsCompilation: no
> Packaged: 2024-03-07 13:24:32 UTC; Livio
> Author: Livio Bätscher [aut, cre] (<https://orcid.org/0000-0002-2989-930X>),
>    Jurriaan M. de Vos [aut] (<https://orcid.org/0000-0001-6428-7774>)
> Maintainer: Livio Bätscher <livio_999@hotmail.com>
>
