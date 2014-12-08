CSCI3415-PA3
========================================================================================================

Go and Racket project to read and store the Open Exoplanet Catalogue data. Then calculate and display statistics.


Team 5:
David Andrews 
Amos Gurung
Jian Luo
Eric Nguyen
Vuong Tran

Part 2 – The Open Exoplanet Catalogue
The Open Exoplanet Catalogue is a catalogue of all discovered extra-solar planets. It is a new kind of
astronomical database, based on small text files and a distributed version control system.
You can peruse the web site and find out interesting information about the project itself. But, it is their
data, which is stored on Github, that we are interested in. The data is available in two forms: separate
XML files (with one file per planetary system) or as a comma or tab separated ASCII data file. You
may use either format.

The XML files and a complete description of their format are available from the Open Exoplanet
Catalogue on Github – https://github.com/OpenExoplanetCatalogue/open_exoplanet_catalogue.
The comma and tab separated ASCII data files and descriptions of their fields are available from
https://github.com/OpenExoplanetCatalogue/oec_tables.
In your report, describe each format, which one your team selected to use, and why.


Part 3 – Basic Go Program
Write a Go program to read and store the Open Exoplanet Catalogue data. Print the following high
level statistics about the data:
• Number of confirmed exoplanets
• Total number of planets (including Solar System objects and unconfirmed exoplanets)
• Number of planetary systems
• Number of binary systems
The Open Exoplanet Catalogue web page has the current values for these statistics.
In your report, document how your program represents and reads the data.


Part 4 – Plotting
The web page https://github.com/OpenExoplanetCatalogue/oec_plots contains a number of plots of the
exoplanet data.
Select a plotting package for Go. It must be a Go package, not an external program. [For example, you
might look at Plotinum, but there are others.] Then, try to replicate the plots on the Open Exoplanet
Catalogue web site using the plot package you selected. Note that many of the plots have one or more
axes that have a logarithmic scale. The last plot, Positions of Extrasolar planet in Equatorial coordinate
system, may be particularly challenging.
