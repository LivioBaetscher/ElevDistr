## version 1.0.6

---


### Bug fixes

- I fixed three errors that only appeared under Linux systems: the examples testing, the tests, and the ‘ElevDistr.Rmd’ built failed. All three errors were caused by a GDAL error, changing the option from ‘terra::rast’ solved the problem. This option pastes “/vsicurl/” before the URL and properly enables the GDAL virtual file system.


```
#Example old function call
gst <- terra::rast(gstURL)

#Example new function call
gst <- terra::rast(gstURL, vsi = TRUE)
```



## version 1.0.5

---


### Prepare CRANE upload

- Removed old rgdal dependencies


## version 0.0.0.9000

---

### NEWS.md setup

- Added NEWS.md creation with [newsmd](https://github.com/Dschaykib/newsmd)

