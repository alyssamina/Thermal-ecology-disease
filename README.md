# Host and parasite thermal ecology jointly determine the effect of climate warming on epidemic dynamics

Supplementary code and data for Gehman, Hall and Byers, 2018. 

# Abstract
Host–parasite systems have intricately coupled life cycles, but each
interactor can respond differently to changes in environmental
variables like temperature. Although vital to predicting how parasitism
will respond to climate change, thermal responses of both
host and parasite in key traits affecting infection dynamics have
rarely been quantified. Through temperature-controlled experiments
on an ectothermic host–parasite system, we demonstrate
an offset in the thermal optima for survival of infected and uninfected
hosts and parasite production. We combine experimentally
derived thermal performance curves with field data on
seasonal host abundance and parasite prevalence to parameterize
an epidemiological model and forecast the dynamical responses to
plausible future climate-warming scenarios. In warming scenarios
within the coastal southeastern United States, the model predicts
sharp declines in parasite prevalence, with local parasite extinction
occurring with as little as 2 °C warming. The northern portion of
the parasite’s current range could experience local increases in
transmission, but assuming no thermal adaptation of the parasite,
we find no evidence that the parasite will expand its range northward
under warming. This work exemplifies that some host populations
may experience reduced parasitism in a warming world
and highlights the need to measure host and parasite thermal
performance to predict infection responses to climate change.

# Requirements

R: https://www.r-project.org/
RStudio: https://www.rstudio.com/products/rstudio/download/

To run code with the data first launch the Rproject file: Gehman_codeshare.Rpro

# Data
Temperature dependent parasite reproduction (Fig. 1B): parasite_rep.csv
Temperature dependent susceptible host survival (Fig. 1C): Susceptible_lifespan.csv
Temperature dependent exposed host survival (Fig. 1D): Exposed_lifespan.csv
Tempearture dependent infected host survival (Fig. 1E): Infected_lifespan.csv
Mean weekly water temperature from LTER-GCE10 mooring from 2011-2014 (Fig. 3A): gce10.wk.mean.csv

# Example Output
Example of run code available: Eury_loxo_SEI_model.html
