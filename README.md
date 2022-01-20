NOTE: This is still being developed!

### Setup notes

This document uses Jeff Sackmann's tennis data. You can obtain it as follows:

```
git clone https://github.com/JeffSackmann/tennis_atp.git
```

Requirements that can be installed using pip are listed in
`requirements.txt`. Please install these first.

Once these are done, here are the steps I followed to setup PyMC v4 with JAX support:

* PyMC v4 installed using the instructions here: https://github.com/pymc-devs/pymc/wiki/Installation-Guide-(Linux)#pymc-v4-installation
* I am running an older version of CUDA (CUDA 10.1), so I couldn't use the
  latest version of JAX. I ended up installing jax v0.2.13 and jaxlib v0.1.65.
* I installed numpyro v0.8.0.
* I installed aeppl version 0.0.17.
