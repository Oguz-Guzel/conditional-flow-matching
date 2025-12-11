# Using TorchCFM: a Conditional Flow Matching library for background estimation

Check out the original repo here for more functionality here : [https://github.com/atong01/conditional-flow-matching](https://github.com/atong01/conditional-flow-matching)

We use the tabular data generation jupyter notebook located in `examples/tabular/` to demonstrate how to use TorchCFM for generation of background events, specifically the Drell-Yan process.

The generated distributions include $p_T$, $\eta$ and $\phi$ of the leptons, as well as the invariant mass of the dilepton system.

<p align="center">
<img src="examples/tabular/feature_distributions.png" width="600"/>
</p>

<p align="center">
<img src="examples/tabular/mll_category_distribution.png" width="600"/>
</p>

The invariant mass calculated from the generated distribution:

<p align="center">
<img src="examples/tabular/mll_from_leptons_distribution.png" width="600"/>
</p>

