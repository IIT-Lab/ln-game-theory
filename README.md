**Understanding Game Theory via Wireless Power Control**

This is a code package is related to the following “lecture note” article:

Giacomo Bacci, Luca Sanguinetti, and Marco Luise, “Understanding Game Theory via Wireless Power Control,” *IEEE Signal Processing Magazine*, vol. 32, no. 4, pp. 132-137, July 2015.

The package contains a simulation environment, based on Matlab, that reproduces all the numerical results and figures in the article. We encourage you to also perform reproducible research!

*Abstract of Article*

In this lecture note, we introduce the basic concepts of game theory (GT), a branch of mathematics traditionally studied and applied in the areas of economics, political science, and biology, which has emerged in the last fifteen years as an effective framework for communications, networking, and signal processing (SP). The real catalyzer has been the blooming of all issues related to distributed networks, in which the nodes can be modeled as players in a game competing for system resources. Some relevant notions of GT are introduced by elaborating on a simple application in the context of wireless communications, notably the *power control in an interference channel (IC)* with two transmitters and two receivers.

Recently, the mathematical tools of GT have attracted a significant interest by the wireless communications and SP engineering communities, due to the need for designing autonomous, distributed, and flexible systems, in which the available resources are allocated through low-complexity and scalable procedures. Games are appealing, owing to some characteristics that are not common in classical optimization: as an example, GT can handle interactive situations in which each player can only have a partial control over the optimization variables, while using its own performance metric. It is true that commonalities can be found with other disciplines, such as multi-objective optimization, convex optimization, and learning theory, but GT possesses many distinguishing features that make it essential for the standard current toolbox of communication as well as SP engineers.


*Content of Code Package*

The paper contains three simulation figures:
- Figure 3 is generated by the Matlab script utilityFunction.m
- Figure 4 is generated by the Matlab script plotUtilityPlan.m
- the exercise suggested at the end of Section 'Pricing the strategies' is generated by the Matlab script pricingGame.m


The package contains 5 additional Matlab functions: findGamma.m, findGammaStar.m, efficiencyFunction.m, computeMu.m, and arrow.m, called by the script plotUtilityPlan.m.

See each file for further documentation.


*Acknowledgements*

The research leading to these results has received funding from the People Programme (Marie Curie Actions) of the European Union’s FP7 under REA Grant agreements no. PIOF-GA-2011-302520 GRAND-CRU and PIEF-GA-2012-330731 Dense4Green, and from the European Commission in the framework of the FP7 Network of Excellence in Wireless COMmunications NEWCOM#
(Grant agreement no. 318306).


*License and Referencing*

This code package is licensed under the GPLv2 license. If you in any way use this code for research that results in publications, please cite our original article listed above.
