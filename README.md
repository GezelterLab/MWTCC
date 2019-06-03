This is very silly data and code to compute meaningless quantities about the Midwest Theoretical Chemistry Conference
The files in the repository:

* mwtcc_history.csv - the 51 year history of the conference as it moves around the Midwest
* mwtcc_traj.csv - The history, converted into a trajectory, with fields specifying the epoch (seconds since January 1, 1970), latitude and longitude of the conference that year
* mwtcc.traj - a plain text version of the trajectory
* mwtccCorrFunc - a Python script that takes the plain text trajectory and computes silly quantities (centroid location, the mean squared displacement, position uncertainty, velocity uncertainty, and the effective minimum-uncertainty mass).
* mwtcc.rcorr - the mean squared displacement, columns are time (years), MSD (miles^2), and 95% confidence interval on the MSD
* mwtcc_rcorr.agr - a plot of the mean squared displacement in Grace
* mwtcc_diffusion.agr - the same plot, but fit to find the effective diffusion constant of the conference
