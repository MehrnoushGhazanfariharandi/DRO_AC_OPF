# Analysis of Data Value in Stochastic Optimal Power Flow for Distribution Systems
Code and data to replicate the results of the paper [Analysis of Data Value in Stochastic Optimal
Power Flow for Distribution Systems](https://arxiv.org/pdf/2406.13148).

## Abstract

The rise of advanced data technologies in electric
power distribution systems enables operators to optimize operations but raises concerns about data security and consumer
privacy. Resulting data protection mechanisms that alter or
obfuscate datasets may invalidate the efficacy of data-driven
decision-support tools and impact the value of these datasets
to the decision-maker. This paper derives tools for distribution
system operators to enrich data-driven operative decisions with
information on data quality and, simultaneously, assess data
usefulness in the context of this decision. To this end, we derive
an AC optimal power flow model for radial distribution systems
with data-informed stochastic parameters that internalize a data
quality metric. We derive a tractable reformulation and discuss
the marginal sensitivity of the optimal solution as a proxy for
data value. Our model can capture clustered data provision,
e.g., from resource aggregators, and internalize individual data
quality information from each data provider. We use the IEEE
33-bus test system, examining scenarios with varying photovoltaic
penetration, to demonstrate the application of our approach and
discuss the relationship between data quality and its value.
## Usage

Everything is implemented in [Julia](https://julialang.org/) (Version 1.10.3) and all results can be reproduced by running the code blocks in `DRO_AC_OPF.ipynb` using the interactive [Jupyter environment with a Julia backend](https://github.com/JuliaLang/IJulia.jl). 


## Citation

```bibtex
@article{ghazanfariharandi2024data,
  title={Data Value in Distribution System Operations},
  author={Ghazanfariharandi, Mehrnoush and Mieth, Robert},
  journal={arXiv preprint arXiv:2406.13148},
  year={2024}
}
