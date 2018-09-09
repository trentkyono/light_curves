simulations.csv contains range normalized magnitudes for 10000 simulated object passes

All simulated passes follow the same orbit (taken from IMAGE satellite TLE 2006-01-31),
but attitude is altered between ECI-fixed, spinner, and precessor with randomly generated
initial orientation and spin rates (if applicable)

The top row of the csv file contains the information for attitude type for each curve 
(eci, spin, prec) after an initial entry 'jd' (denoting the Julian Date column)

The first column of the file gives a JD timestamp, each subsequent column represents the
lightcurve for a unique simulated pass
