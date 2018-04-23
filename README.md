# Data Analysis with Julia (using IJulia: Julia kernel for Jupyter)

If you are using Jupyter through Anaconda distribution, to install the IJulia kernel, and write Julia codes on Jupyer Notebook, 
you need to install Julia. For Linux (Ubuntu), just do:

```
sudo apt-get install julia
```

Now, open Julia shell ($ julia) and write:

```
Pkg.add("IJulia")
```

After that, update jupyter_core and jupyter_client:

```
conda update jupyter_core jupyter_client
```

If you are using Windows, download and install Julia (https://julialang.org/downloads/), open Julia shell, and write the commands:

```
julia> Pkg.init()
```
```
julia> Pkg.update()
```
```
julia> Pkg.add("IJulia")
```
```
julia> Pkg.build("IJulia")
```
```
julia> using IJulia; noteboo()
```

Done!
