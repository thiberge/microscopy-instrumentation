# microscopy-instrumentation
DataJoint pipeline for maintenance and configuration of microscopy instrumentation


# Notes (preliminary)

## List of fields to record:

#### General categories of elements:

* Objective
* Filters
* PMT list (name, serial number, date of production, date of installation)
* Laser (brand, head serial number, location, date of most recent install, date of cooling liquid replacement, date of last wavelength tuning routine run, measurement of power spectrum at specific wavelength)
* Scanners type (resonant/non-resonant, Res freq, size in mm)
* GDD (one field taking the values of “internal to laser”, “external table”, “both”)
* Fast Z-scanning (one field taking the values of “remote focussing”, “liquid lens”, “electrowetting lens”, “piezo-objective”)


#### Specifics of individual microscopes:

- Microscope (name, location, categorie, its laser, its objective, its PMTs, its filters/custom filters)


#### Status of a microscope (calibration):

- Wavelength
- GDD
- PSF
- Flat Field
- Field Curvature
- ScanImage Percentage Power conversion to mW
- Pulse width at sample
- Preamplifier settings
- Conversion Digital Units to photon number

