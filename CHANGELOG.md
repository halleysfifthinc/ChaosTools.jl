# v0.6
This version updates all internals to be on par with `DynamicalSystemsBase` 0.6

*All* internal implementations of methods that use a `DynamicalSystem` have been
reworked almost from the ground up.

This lead to (only minor) changes to some of the high level interfaces. Please see
the documentation strings of each function before using it.

# v0.5.1
## Non-breaking
* Bugfix: gali was invasive in the diff_eq_kwargs

# v0.5.0
## Breaking
* Updated everything to be on par with the changes of DynamicalSystemsBase v0.5

## Non-breaking
* Minor bug fixes resulting from misstypos.
* New method for permutation entropy: `permentropy` !

# v0.4.3
* Added Broomhead King function
* Estimate_delay and other functions about reconstructions are now in this repo.

# v0.4.1
* Many bugfixes relating evolution of continuous systems and correct
  callback propagation.
# v0.4.0
## Breaking
* Updated everything to be on par with Base 0.3.1
* Added more tests
* Propagate callbacks etc in orbit diagrams


# v0.3.0
## BREAKING
* Overhauled the way `estimate_boxsizes` works.

# v0.2.0
* added method for Poincare surface of section
* added orbit diagram for maps
* added production of orbit diagram for flows through Poincare surface of sections

# v0.1.0
Initial release, see: https://juliadynamics.github.io/DynamicalSystems.jl/v1.0.0/
for the features up to this point.
