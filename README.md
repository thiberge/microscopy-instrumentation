# microscopy-instrumentation
DataJoint pipeline for maintenance and configuration of microscopy instrumentation


## Notes (preliminary): List of fields to record:

#### General categories of elements:

* Objectives
* Filters
* PMTs list (fields include name, serial number, date of production, date of installation, color it is used for)
* Laser (brand, head serial number, location, date of most recent install, date of cooling liquid replacement, date of last wavelength tuning routine run, measurement of power spectrum at specific wavelength)
* Scanners type (assembly type (XY mount, XY lens conjugated, XYY) supplier, model, resonant/non-resonant, Res freq)
* GDD method (one field taking the values of “internal to laser”, “external table”, “both”)
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

