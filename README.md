
# [Data Analysis with Julia: A Short Introduction](http://cyberneticsresearch.com/books-collections-of-codes.html)

## [Summer School - Extra Class - 2016](http://cyberneticsresearch.com/books-collections-of-codes.html)

### By Heitor Baldo

=================


Table of Contents
=================


  * [Installing IJulia: Julia kernel for Jupyter](#ch-1-)
  * [Ch 1: Basic Programming with Julia](#ch-1-)
  * [Ch 2: Data Muning](#ch-2-linear)
  * [Ch 3: Data Visualization](#ch-2-)
  * [Ch 4: Machine Learning for Data Analysis](#ch-2-)
  * [Ch 5: Time Series Analysis](#ch-2-)
  * [Ch 6: Collaborative Filtering and Recommendation System](#ch-2-)
 
  

 ---



## [Installing IJulia: Julia kernel for Jupyter]()

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
julia> using IJulia; notebook()
```

Done!


## [Ch 1: Basic Programming with Julia](#ch-1-)
## [Ch 2: Data Muning](#ch-2-linear)
## [Ch 3: Data Visualization](#ch-2-)
## [Ch 4: Machine Learning for Data Analysis](#ch-2-)
## [Ch 5: Time Series Analysis](#ch-2-)
## [Ch 6: Collaborative Filtering and Recommendation System](#ch-2-)
