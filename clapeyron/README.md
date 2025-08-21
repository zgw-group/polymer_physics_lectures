# Clapeyron tutorial
Demo notebooks for the tutorial on Clapeyron.jl.

## Installing Julia

To download and install Julia, please go to
https://julialang.org/install

On most systems, it should be as simple as running:
```bash
curl -fsSL https://install.julialang.org | sh
```

## Installing dependencies
If you make your way to this repo and open the REPL (run julia in the command line), you can install all the dependencies by running:
```julia
julia> ] activate .

julia> instantiate
```
This will install Clapeyron, Plotting tools and the Jupyter Notebook Kernel.