# microscopy-instrumentation
DataJoint pipeline for maintenance and configuration of microscopy instrumentation


## Notes (preliminary): List of fields to record:

#### General categories of elements:

* Objectives
* Filters (supplier, catalogue number or custom supplier assigned name or number, description, tiff/jpeg uploaded spectra)
* PMTs list (fields include name, serial number, date of production, date of installation, color it is used for, QE)
* Laser (brand, head serial number, location, date of most recent install, date of cooling liquid replacement, date of last wavelength tuning routine run, measurement of power spectrum at specific wavelength)
* Scanners type (assembly type (XY mount, XY lens conjugated, XYY) supplier, model, resonant/non-resonant, Res freq)
* GDD method (one field taking the values of “internal to laser”, “external table”, “both”)
* Fast Z-scanning (one field taking the values of “remote focussing”, “liquid lens”, “electrowetting lens”, “piezo-objective”)
* Preamplifiers list 
* DAQ system (NI chassis / NI6710 / ScanImageBoard(2019)...)

#### Specifics of individual microscopes:

- Microscope (name, location, categorie, its laser, its filters, fast z-method, GDD method, scanner type)


#### Status of a microscope (calibration):

- Channel 1 configuration:
  -- color
  -- PMT installed
  -- Preamplifier model installed
  -- Preamplifier settings
  -- Conversion Digital Units to photon number
- Channel 2 configuration

- objective installed,

- Wavelength
- GDD
- Pulse width at sample
- PSF
- Flat Field
- Field Curvature
- ScanImage Percentage Power conversion to mW





