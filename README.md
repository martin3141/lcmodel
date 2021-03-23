# LCModel

The LCModel MR spectroscopy analysis algorithm by Stephen Provencher. Magn Reson Med 30, 672 (1993).

This code was intially downloaded from: http://s-provencher.com/lcmodel.shtml in March 2021 following the application of the 3-Clause BSD License. Any future changes will be listed in this README file.

LCModel is trivial to compile with recent versions of gfortran.

On Linux and Mac OS:

`gfortran -ffpe-summary=none -std=legacy -O3 LCModel.f -o lcmodel`

On Windows:

`gfortran.exe -ffpe-summary=none -std=legacy -O3 LCModel.f -o LCModel.exe`
