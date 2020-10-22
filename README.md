# TIMES_model

## The Integrated MARKAL-EFOM System (TIMES) – a bottom-up optimization model for energy-environment systems.

The TIMES (The Integrated MARKAL-EFOM System) model generator was developed by ETSAP the Energy Technology Systems Analysis Program, which is a Technology Cooperation Program of the International Energy Agency. 
ETSAP is an international community which uses long term energy scenarios to conduct in-depth energy and environmental analyses. 
The TIMES model generator combines two different, but complementary, systematic approaches to modelling energy: a technical engineering approach and an economic approach. 
TIMES is a technology rich, bottom-up model generator, which uses linear-programming to produce a least-cost energy system, optimized according to a number of user constraints, over medium to long-term time horizons. 
In a nutshell, TIMES is used for, "the exploration of possible energy futures based on contrasted scenarios".

## Model structure

TIMES models encompass all the steps from primary resources through the chain of processes that transform, transport, distribute and convert energy into the supply of energy services demanded by energy consumers. 
On the energy supply-side, it comprises fuel mining, primary and secondary production, and exogenous import and export. The “agents” of the energy supply-side are the “producers”. 
Through various energy carriers, energy is delivered to the demand-side, which can be structured sectorally into residential, commercial, agricultural, transport and industrial sectors. The demand sector breakdwon is completely flexible and adaptable in TIMES.
The “agents” of the energy demand-side are the “consumers”. The mathematical, economic and engineering relationships between these energy “producers” and “consumers” is the basis underpinning TIMES models.

## Scenarios

The principle insights generated from TIMES are achieved through scenario analysis. A reference energy scenario is generated first by running the model in the absence of any policy constraints. 
These results from the reference scenario are not normally totally aligned to national energy forecasts (generated by simulating future energy demand and supply), mainly because TIMES optimizes the energy systems providing a least cost solution.
A second scenario is then established by imposing a (single of many) policy constraint on the model (e.g. minimum share of renewable energy, maximum amount of GHG emissions or minimum level of energy security) and the model generates a different least cost energy system with different technology and fuel choices. 
When the results are compared with those from the reference scenario, the different technology choices can be identified that deliver the policy constraint at least cost.

## Functionality

Once all the inputs, constraints and scenarios have been put in place, the model will attempt to solve and determine the energy system that meets the energy service demands over the entire time horizon at least cost. 
It does this by simultaneously making equipment investment decisions and operating, primary energy supply, and energy trade decisions, by region. 
TIMES assumes perfect foresight, which is to say that all investment decisions are made in each period with full knowledge of future events (myopic runs of the model are also possible). 
It optimizes horizontally (across all sectors) and vertically (across all time periods for which the limit is imposed).
The results will be the optimal mix of technologies and fuels at each period, together with the associated emissions to meet the demand. 
The model configures the production and consumption of commodities (i.e. fuels, materials, and energy services) and their prices; when the model matches supply with demand, i.e. energy producers with energy consumers, it is said to be in equilibrium. 
Mathematically, this means that the model maximizes the producer and consumer surplus. The model is set up such that the price of producing a commodity affects the demand for that commodity, while at the same time the demand affects the commodity’s price. 
A market is said to have reached an equilibrium at prices p and quantities q when no consumer wishes to purchase less than q and no producer wishes to produce more than q at price p. 
When all markets are in equilibrium the total economic surplus is maximized (i.e. the sum of producers’ and consumers’ surpluses).
The main output TIMES are energy system configurations, which meet the end-use energy service demands at least cost while also adhering to the various constraints (e.g 80% emissions reduction, 40% renewable electricity penetration). 
In the first instance, TIMES model addresses the question: is the target feasible? If an energy system is possible, it can then be examined, at what cost? The model outputs are energy flows, energy commodity prices, GHG emissions, capacities of technologies, energy costs and marginal emissions abatement costs. 

## Documentation  [![Documentation](https://img.shields.io/badge/docs-passing-brightgreen.svg?style=flat&logo=github)](https://github.com/etsap-TIMES/TIMES_Documentation)

Detailed documentation is available on ETSAP's [website](https://iea-etsap.org/index.php/documentation):

i)   [Concept and Theory](https://iea-etsap.org/docs/Documentation_for_the_TIMES_Model-Part-I_July-2016.pdf).
ii)  [Comprehensive Reference Manual](https://iea-etsap.org/docs/Documentation_for_the_TIMES_Model-Part-II_July-2016.pdf).
iii) [Operation of TIMES code](https://iea-etsap.org/docs/Documentation_for_the_TIMES_Model-Part-III_July-2016.pdf).

## TIMES Demo [![Demo model](https://img.shields.io/badge/demo%20model-available-brightgreen.svg?style=flat&logo=github)](https://github.com/etsap-TIMES/TIMES_Demo)

A Demo model is available on [GitHub](https://github.com/etsap-TIMES/TIMES_Demo).

## Community

Information on the activities of ETSAP are available on ETSAP's [website](https://iea-etsap.org/).

If you are interested in receiving information and newsletters on ETSAP's tool you can register [here](https://iea-etsap.org/index.php/etsap-tools/acquiring-etsap-tools).

A forum for TIMES users is [available](http://iea-etsap.org/forum/index.php).

[![DOI](https://zenodo.org/badge/229031856.svg)](https://zenodo.org/badge/latestdoi/229031856)
