# FRB_SkyPositionPlot

[Example FRB sky position plot](FRB_SkyPositionPlot/2021.05.27_FRBlocations_BlackFrame_viridis_r.png?raw=true)

The ipython notebook in this repo can be used to plot the distribution of FRBs on the sky in Galactic coordinates. It includes a background map of the dispersion measure, with the option to use the YMW16 model or the NE2001 model. Pulsars from the ATNF pulsar catalogue can also be included.

<ul>
  <li>FRBlocations.ipynb is the ipython notebook for plotting</li>
    <li>frbcat_20210526.csv is the <a href="http://frbcat.org/">FRBcat.org</a> catalogue downloaded on 2021.05.26</li>
  <li>tns_search_20210526.csv is the full list of FRBs downloaded from the <a href="https://www.wis-tns.org/search">TNS server</a></li>
  <li>pulsar_galcoords.scvs.gz is the <a href="https://www.atnf.csiro.au/research/pulsar/psrcat/">ATNF pulsar catalogue</a> in Galactic coordinates. This will be outdated. Please download the latest version of the catalogue to make sure you have all the pulsars.</li>
  <li>NE2001_DMs.csv contains the <a href="https://arxiv.org/abs/astro-ph/0207156">NE2001</a> DM values across the sky</li>
  <li>YMW16_DMs.csv contains the <a href="http://119.78.162.254/dmodel/index.php">YMW16</a> DM values across the sky</li>
  <li>2021.05.27_FRBlocations_BlackFrame_viridis_r.png is an example of the output plot</li>
</ul>

The DOI for this github repo is:



<b>If you use the data or code in this repo, please make sure you cite it correctly!</b>

I am part of the <a href="http://www.meertrap.org">MeerTRAP</a> team, based at the University of Manchester and funded by the European Research Council (ERC) under the European Union's Horizon 2020 research and innovation programme (grant agreement No 694745).
