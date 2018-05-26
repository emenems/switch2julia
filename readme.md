# Switch to Julia (from Matlab)
This repository contains Jupyter notebooks written to allow for easy transition from Matlab/Octave to [Julia](https://julialang.org). Notebooks covering following topics can be found here:
* [Install Julia](notebooks/Install_Julia.ipynb)
	* Install Julia
	* Install and set up Atom
	* Install Jupyter notebook (IJulia)
	* Install needed packages
* [Brief introduction to Julia](notebooks/JuliaIntro.ipynb)
	* Working with Vector, Matrices & Other collections
		* Indexing in Julia
	* Functions
	* Flow control
	* Scope
	* Manage packages
	* Some important notes
* [2D plots using PyPlot](notebooks/2D_PyPlot.ipynb)
	* Plot two lines/vectors (with independent x values) in the same figure/plot
		* Define figure size
		* Set plot title
		* Add x and y labels + set fontsize
		* Turn on grid lines
		* Add legend + set fontsize
		* Set y and x limits
		* Print figure
	* Plot time-dependent data/working with **DateTime**
		* Work with axes handle/object
		* Specify line color + marker
		* Specify tick position
		* Specify date/time format on x axis
		* Set position of a legend and remove legend frame
		* Plot input data and add fitted curve to correlation plot
	* Place multiple plots inside one figure/use **Subplot**
		* Set/remove x/y ticks
		* Get current x/y ticks
		* Add text/annotation to plot
		* Remove (sub)plot frame
	* Plot data with 2 independent Y axes 
* [3D plots using PyPlot](notebooks/3D_PyPlot.ipynb)
	* Plot surfaces using **surf** function
		* Set colormap
		* Set labels
		* Change view
		* Set x/y/z ticks
	* Plot **contours**
		* Set linewidth
		* Change levels/spacing between lines
		* Change fontsize
		* Change label precision
		* Print result
	* Plot **filled countours**
		* Add colorbar + colorbar ticks + colorbar label
		* Set colormap limit
* [Maps with GMT](notebooks/GMT_Maps.ipynb)
	* Use Generic Mapping Toolbox ([GMT](http://gmt.soest.hawaii.edu)) directly from Julia 
	* Create map with coasts, rivers, sites and text annotations
		
**Coming soon:**
* Using DataFrames
* Fitting, filtering, interpolation
* Reading and writing data
