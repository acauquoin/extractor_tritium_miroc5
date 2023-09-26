# extractor_tritium_miroc5

Jupyter notebook to plot and extract data at a specific location and time range from MIROC5-iso simulations. Simulations nudged to ERA5 and JRA-55 are available.

- The mean tritium in precipitation map can be plotted for a specified area and time period. The map can be downloaded as a pdf file.
- Time series of tritium and $\delta^{18}O$ in precipitation, precipitation rate and air temperature at 2 m can be plotted for a specified location and time interval. The data can be downloaded as a CSV file, and the figure can be downloaded as a pdf file.
- The map of vertically integrated water vapor transport can be plotted for a given area and month. The figure can be downloaded as a pdf file.

To open and run this notebook in the Binder server, where the required environment and packages are installed automatically, click on the badge below. 

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/acauquoin/extractor_tritium_miroc5/main?labpath=extract_miroc5-iso_data_xarray.ipynb)


### Running, plot and extract data

If the Binder environment is already built and initialized (i.e. if no changes are made to the GitHub repository and if it is run frequently by other users), the launch time should not exceed 30 seconds.

Once in the JupyterLab environment, run the entire notebook with the menu `Run > Run All Cells`. Wait for the end of the runtime, indicated by the kernel wheel at the top right of the screen <img width="161" alt="kernel_wheel" src="https://github.com/acauquoin/extractor_tritium_miroc5/assets/138624311/69406444-da5c-40eb-9e81-ab02f6d8f48f">. This procedure may take a few minutes the first time it is run, due to the downloading of the necessary MIROC5-iso netcdf outputs.

Once executed, you can interactively extract and plot MIROC5-iso data for a specific location and date range, save the figure as a pdf and download the data as a CSV file, as shown in the figure below. 
<p>
<img width="1756" alt="monitoring_plot" src="https://github.com/acauquoin/extractor_tritium_miroc5/assets/138624311/e44e260a-ad78-4d01-abea-0130a93df83f">
</p>


### About the Jupyter Lab application

The left sidebar shows the file browser, open tabs and running kernels, notebook table of contents and notebook extensions.
<p>
  <img width="31" alt="left_panel_buttons" src="https://github.com/acauquoin/extractor_tritium_miroc5/assets/138624311/d5c29f2d-28a1-4b88-88d6-39b6ac2a0ef5">
</p>

From the file browser panel, it is possible to view and download the saved notebook, MIROC5-iso data and figures.
<p>
  <img width="520" alt="file_browser_section" src="https://github.com/acauquoin/extractor_tritium_miroc5/assets/138624311/1ee41a36-c68b-47e0-a50f-04c987e00204">
</p>

Open tabs and running kernels, as well as the notebook's table of contents :
<p>
  <img width="350" alt="opened_tabs_and_kernels" src="https://github.com/acauquoin/extractor_tritium_miroc5/assets/138624311/f4b9f7e0-57ae-4ccb-b9fe-fd6f72efc08f" hspace="10">
  <img width="350" alt="table_of_contents" src="https://github.com/acauquoin/extractor_tritium_miroc5/assets/138624311/2a3acc28-b8a6-4c6f-9522-54bc94982c09" hspace="10">
</p>

If you're not interested in the Python code, you can reduce it for greater clarity by selecting `View > Collapse All Code` from the menu.


### Reproducibility

MIROC5-iso data can be downloaded directly as NetCDF files from a public repository (Zenodo, to be done). 
The notebook and the packages needed to run it locally (`environment.yml`) can be downloaded via this GitHub repository. The packages' version can also be viewed in the notebook <b>Packages version</b> section. To install python and the required packages locally, use `conda` on the `environment.yml` file: [https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file).

