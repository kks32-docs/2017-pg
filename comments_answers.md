# Referee 1:

```
The paper presents new results on the dynamics of tall granular columns that collapse in a fluid.
The text is clear yet some sentences are too long and difficult to understand (e.g. section 5.1:

The evolution of the normalised height with time (fig. 6) for collapse on different slope angles indicates that the amount of material destabilised in fluid is less than the dry conditions due to
the drag forces experienced by the grains, which retards the quantity and the rate of collapse.

For clearness you may break these long sentences into shorter sentences.
Figures are insightful yet some details may be improved:
```

The authors would like to than the reviewer for useful comments. The following changes have been made.

> Figure 1: define angle theta as the slope angle (?)

Slope angle theta is now defined in the figure.

> Figures 2, 3: Color scales seems to correspond to two independent parameters: velocity and grain pressure. Does this means that velocity scale only applies for fluid ? If so then write ‘fluid velocity’ instead of velocity; if not then please explain.

The suggested update to the contour legends has been made.

>Figure 5: explain the meaning of the gray scale color for particles (in terms of mass packing?).

Black colour denotes maximum density of packing, while white denotes loose packing. Explanation has been added to the figure.

```
The paper is suitable for publication once these modifications are completed.

The topic is suitable for an oral presentation showing animations of the simulations, yet a poster or poster presentation but for an oral presentation it is also acceptable.
```

# Referee 2:
```
The content of the coupling of DEM-LBM is interesting and the credible results are shown.
The following conmments and the information are needed as follows:
```
> How and why did the authors determine the parameters for the simulations?

The parameters of the simulations are based on a typical soil media. Further details are provided in the PhD thesis Soundararajan (2015).

>How did the authors controll the pore water pressure caused by the change in void sizes?

The pore-presssure in the void size is modelled using LB nodes. As the grains move, and the void ratio is changes, solid nodes transition to fluid nodes and the pore-pressure is modelled using LB technique.

>How much is the density of granular mass of the initial packing?

The density of packing fraction is 0.82 and has been added to the text.
