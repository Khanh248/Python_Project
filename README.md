# Python_Project
## LED Transient Thermal Data 4
Working with Voltage/Current Measurement Data
# Description
The dataset consists of a several CSV-files, which are electrical transients, each
belonging to a different temperature. A table, relating each file to a temperature is
given as well. The goal is to calculate a sensitivity function V(T), voltage versus
temperature, by evaluating the transients. This is done via linear extrapolation of the
voltage transient to the moment of power switching, called t=0. The linear
extrapolation should be done in a voltage versus square-root-time plot. For the
linear regression, use a section where the current has settled to a steady level. The
exact location of t=0 (moment of switching) for each file needs to be determined as
part of the assignment.
