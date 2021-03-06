# Continuum fitting

----

## Here're continuum fitting notes

### 1. NMF fitting (Zhu et al. 2013, 2016):
   ref:
   https://ui.adsabs.harvard.edu/abs/2013ApJ...770..130Z/abstract

   https://ui.adsabs.harvard.edu/abs/2016arXiv161206037Z/abstract

#### Here please find the relevant codes
   https://github.com/guangtunbenzhu/NonnegMFPy

#### Process:
key idea:
* Selection criteria of high-z QSO analogs with both Lyman $\alpha$ and MgII emission observations:
(We may need a luminosity cut?)
  - 2.09 < z_pipe < 2.51 (wavelength coverage: 3600 ~ 10400 Å)
  - ZWARNING = 0 (avoid objects with high uncertain redshifts)
    - BAL_PROB = 0 (reject BAL QSOs)
* There are 93067 QSOs satisfy the criteria above. The results are shown in QSO_list.txt.
* S/N > 7: The number of QSOs with S/N > 7 is ******.
----

### 2. Spline fitting (Bosman et al. 2017, Meyer et al. 2019)
   https://ui.adsabs.harvard.edu/abs/2017MNRAS.470.1919B/abstract

   https://ui.adsabs.harvard.edu/abs/2019MNRAS.483...19M/abstract

#### Here please find the relevant codes
   https://github.com/rameyer/QUICFit

### 3. Other methods?

----

## Shortage：
   Currently there is no any quasar continuum prediction/fitting method can produce a good enough intrinsic spectrum for narrow absorption line studies. And, we have no method to evaluate the goodness of continuum fitting.
