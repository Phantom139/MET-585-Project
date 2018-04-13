# MET 585 Course Project (NIU)
## An Analysis of the Climatological Trend in Mid-Latitude Baroclinity
## Robert C. Fritzen

### Synopsis
Barocliic Instability (Baroclinity) is one of the fundamental foci of the development of extratropical cyclones in the mid-latitudes. Defined as the growth of small scale disturbances through time, baroclinity is expressed as a reinforcing interaction of wind shear at different levels of the atmosphere. As the Thermal Wind relationship connects surface temperature gradients to wind shear, we can define baroclinity using the Brunt-Väisälä Frequency:

<font size=4>
$\sigma_{BI} = \frac{f}{N}\frac{d\vec{V}}{dZ}$
</font>

Which defines: The coriolis parameter (f), the Brunt-Väisälä Oscillation Frequency (N), and the wind shear vector with respect to geopotential height ($\frac{d\vec{V}}{dZ}$)

Using the definition of the Brunt-Väisälä Oscillation Frequency, $N = \sqrt{\frac{g}{\theta}\frac{\partial\theta}{{\partial}Z}}$, The previous formula can be expanded to:

<font size=4>
$\sigma_{BI} = \frac{f}{\sqrt{\frac{g}{{\theta}_m}\frac{{\theta}_u - {\theta}_l}{Z_u - Z_l}}}\frac{d\vec{V}}{dZ} $
</font>

Which defines a change in the potential temperature (${\theta}$), with respect to height. By differential approximation methods, we analyze this as a change between the upper and lower analysis levels.

This project seeks to explore the climatological trend in baroclinity over the past 70 years. Using the NCEP/NCAR Reanalysis Data, baroclinity can be calculated at three different levels (Low, Middle, and Upper) and then explored using statisical tools such as standard anomaly and moving averages to explore how baroclinity is changing with time.

It is hypothesized that under climate change scenarios, the meridional (Y) temperature gradient is weakening, and hence the low level temperature gradient is also weakening, reducing baroclinity with time.

### Python
Run the first three code blocks before using any of the other blocks to load in the required packages, define the constants and variables, and load into memory some helper functions