# Polar.jl-examples

This repository contains examples demonstrating the use of [Polar.jl](https://github.com/jneu-research/Polar.jl), a [Julia](https://julialang.org/) implementation of various aspects of [polar codes](https://en.wikipedia.org/wiki/Polar_code_(coding_theory)).

This repository is intended for Julia v1.0 and above.


## Support

The code is provided as is, without any warranties or guarantees (neither implicit nor explicit).


## Known Issues

* This repository adequately declares its dependency on [IJulia.jl](https://github.com/JuliaLang/IJulia.jl). Nonetheless, due to ''surprising behavior'' of IJulia, IJulia needs to be installed not only in the project-local environment, but also in the version-global environment. Furthermore, it does not suffice to activate the project-local environment first and then start IJulia notebooks from within it, but instead IJulia needs to be started first (from the version-global environment), before activating the project-local environment from within the notebooks. For more details on Julia environments, see [the Julia documentation](https://docs.julialang.org/en/v1/stdlib/Pkg/index.html), and on IJulia's ''surprising behavior'', see [the respective issue](https://github.com/JuliaLang/IJulia.jl/issues/750).


## Usage

```bash
julia -e 'using IJulia; notebook(dir=".")'
```


## Citation

Please cite the use of any material in this repository as:
* J. Neu, ''Polar.jl: Julia implementation of polar coding'', URL: https://jneu.net/Polar.jl
  ```
  @MISC{Polar.jl,
    author = {Neu, Joachim},
    title = {{Polar.jl}: {Julia} implementation of polar coding},
    howpublished = {\url{https://jneu.net/Polar.jl}},
    year = 2019,
  }
  ```
