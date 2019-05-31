Model simulation file from the paper 
M.Migliore and Gordon M. Shepherd
Emerging rules for distributions of active dendritic properties
underlying specific neuronal functions
Nature Rev. Neurosci. 3, 362-370, 2002.

The model illustrates how two different dendritic locations
for synaptic inputs may result in different temporal integration
windows. Running the fig1a.hoc simulation will open two windows,
from which 4 simulations can be run, corresponding
to different dendritic locations for two synapses, S1 and S2.
In one of the simulations the effects of a dendritic Ih can also be
appreciated.
To reduce simulation times, a reduced model is used rather than
a detailed CA1 geometry as in the paper.
The top window will show the time course of the 
membrane potential in a proximal location
during several simulations using different relative activation times
for S1 and S2. The symbol marks the S1 activation time. 

The bottom window will summarize the results by plotting the
peak membrane potential reached in each simulation as a function
of the relative activation times.

To compile the mod files on a unix system use the command nrnivmodl.
Under Windows, use "mknrndll" from the NEURON program menu
and follow on-screen instructions.

Questions on how to use this model should be directed to
michele.migliore@pa.ibf.cnr.it





