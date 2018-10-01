# Blood vessel flow modelization

## Problem 

Blood is composed of 45% of cells floating in a liquid called plasma. In order to properly model the blood flow we need to take in account that it is a liquid flowing in an environment with a lot of obstacles (cells).

## Documentation

The project's model and results are detailed in the following documents:
* [Documentation](doc/french_doc.pdf) (French)
* Coming soon (English)

## Run

This project uses the Freefem++ framework: [http://www.freefem.org/](http://www.freefem.org/)

You can install it by following the instructions in the *Installation* section in the FreeFem++ documentation: [http://www.freefem.org/ff++/ftp/freefem++doc.pdf](http://www.freefem.org/ff++/ftp/freefem++doc.pdf)

Then you can run any `.edp` file with:
```
FreeFem++ src/<filename>.edp
```

`simple.edp` will run only one simulation when `final.edp` will run 100 simulations.