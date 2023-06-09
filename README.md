These documents belong to the work:

__Theoretical, numerical and experimental investigation of a Faraday disc generator for energy harvesting applications__

authored by _Jorge Galván, F. S. Sellschopp, Michel Rivero, Carlos Álvarez, Rodrigo Loera, Raúl Ávalos_ Published in  IEEE Latin America Transactions

The manuscript can be found at: https://latamt.ieeer9.org/index.php/transactions/issue/view/31

### Compiling

1. Download and extract the file *Simulacion COMSOL Faraday disc 79.rar* shared on this repository. This file was developed on COMSOL Multiphysics 5.6, and can not be opened by older versions.
2. Open the file using COMSOL Multiphysics.
3. Refer to Table 1 of the referred article to identify the pre-established domains, physical properties, as well as initial and coundary conditions in the model.
4. Locate the parameter labeled as "omegaX" in the COMSOL model and introduce the angular velocity to simulate.
5. Go to the electrical circuit-resistance section and find the value of the load resistance, which can be found in Figure 8. The external resistance can be defined as required.
6. Once the desired parameters are defined, it is possible to run the simulations (as indicated in Figure 8 in radians per second).
7. In the studies section, first run the solution for the magnetic field and then proceed with the second study that includes that computes the electrical variables.

Please make sure to follow these instructions carefully. If you have any further questions, feel free to ask!

*Note that the configuration for the mesh and solver are tested within the reported parameters. Other parameters might require modifications.*


