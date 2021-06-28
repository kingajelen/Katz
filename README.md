# Katz


PIDE is a database containing raw radiobiological data, such as dose and survival rates. In order to be able to apply the collected data to the Katz model, it was necessary to write code in Python to segregate this data, i.e. to be able to select a specific cell line or energy of radiation applied. Using the pyamtrack/libAT library, range information for individual particles was also added to the database. 

*PIDE is a database of radiobiological data from 1100 pairs of in-vitro experiments (photon and ion irradiation). This database contains the specifications of the experiments, i.e. cell lines, radiation properties used and delivery techniques. This allows the study of general trends and factors influencing the measured radiation effects.
