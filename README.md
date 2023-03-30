# PlantSim tutorials
 
This repository contains tutorials for several packages developed in Julia for modelling plants. The tutorials are written in Pluto notebooks. The notebooks are also available as static HTML pages.

## Introduction tutorial

The introduction tutorial is a short introduction to the packages.

You'll find it as [a static html here](https://plantsim.github.io/PlantSim_tutorial/). From there, you can download the notebook or run it on Binder.

You can also directly run it from the command-line with the following commands:

- first, install Pluto.jl:

```julia
# Press ] to enter the Pkg REPL mode and run
pkg> add Pluto
```

- then, run the notebook:

```julia
julia> using Pluto; Pluto.run(url="https://raw.githubusercontent.com/PlantSim/PlantSim_tutorial/main/tutorial.jl")
```
