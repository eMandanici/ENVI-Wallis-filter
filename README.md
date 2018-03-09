# ENVI-Wallis-filter
An extension to perform Wallis adaptive filtering in ENVI.

The Wallis filter is a particular adaptive filter that produces an edge crispening and a local contrast enhancement, by applying an operator which is spatially variant. This kind of filter is particularly useful, for instance, when images present both bright and shadow regions.

The present extension has been compiled with IDL 8.2.1 and it applies both to ENVI 5 Standard and ENVI 5 Classic interfaces,

- to use it in the Classic interface, where it adds an item in the 'Filtering -> Adaptive' menu, the "wallisfilter.sav" file must be copied in the '...\Exelis\ENVI50\classic\save_add' directory;

- to use it in the new ENVI 5 Standard interface, where it adds a tool in the 'Extensions' toolbox, the file must be copied in the '...\Exelis\ENVI50\extensions' directory.

Furthermore the procedure 'envi_apply_wallis_filter' is exposed, in order to allow a call to the filter algorithm from an ENVI-IDL batch program.

More details about extension usage can be found in the attached pdf file.



*********************
   Update history
*********************

***** First version 28 November 2012
Core functionality.

***** Update 9 March 2018
Uploaded to GitHub!
