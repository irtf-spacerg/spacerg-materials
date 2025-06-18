# Draft Charter: Systems and Protocol Aspects for Circumstellar Environments Research Group (SPACE RG)

The Systems and Protocol Aspects for Circumstellar Environments Research Group (SPACE RG) is chartered to explore and investigate research questions related to architecture, protocol design, manageability considerations, and approaches to operationalize several categories of non-terrestrial networks. 

Specifically, the research group focuses on networking among potentially heterogeneous nodes (by node type, administration, operator, among others) with highly dynamic connectivity imposed by their non-terrestrial or airborne deployment environment. This includes High-Altitude Platforms (HAPS), typically in the stratosphere, satellites in Low, Medium, and Geostationary orbits (LEO, MEO, GEO), as well as platforms in other trajectories – cislunar and beyond – and lower altitude airborne vehicles (planes, drones) as providers and users of network connectivity. For brevity, these are collectively referred to below as “aerospace networks”.

Aerospace networks feature several challenging properties that may impact all layers of the networking protocol stack, often in ways that contrast sharply with the assumptions underlying terrestrial networks. These challenges have numerous technical root causes, including:

1. **Mobility & Topology Dynamics**: High-speed movement, predictable and opportunistic links, frequent topology partitions or link disruptions.
2. **Environmental & Resource Constraints**: Atmospheric disturbances, limited energy, thermal variability, constrained onboard resources.

Industry and standards organizations other than IETF (CCSDS, 3GPP, among others)  with different backgrounds are developing the underlying technologies; operators run today’s closed networks; and research communities (such as ACM SIGCOMM, SIGMOBILE) analyze the observable characteristics of these networks.  One focus area in the networking community has been, on the one hand, on simulation and emulation environments to explore path properties and routing protocols and, on the other hand on network measurements including analyzing continuously collected data sets (e.g., of RIPE Atlas probes), running individual experiments, and building up dedicated measurement infrastructure such as LEOscope.

SPACE RG will start from and build up on these existing initiatives, with the initial goals to

1. Create a platform for an open, curated data repository that collects data sets and pointers to data sets to offer a comprehensive resource collection in a single place with suitable documentation.  This could take the shape of a gut repo.
2. Analyze and document present evaluation methodologies, such as measurement setups, performance metrics, simulation scenarios, "test cases," etc., to enable comparable and reproducible experiments. This could be a Wiki, white paper, or one or more Internet Drafts.
3. Based upon the findings from 2., devise best practices and reference scenarios for simulations and measurements.  This could take the shape of an Informational RFC.
4. Document and foster the development of a dedicated measurement infrastructure for aerospace networks, such as the LEOscope.

To achieve these goals, the research group will reach out to the different communities identified above, invite speakers and collaborators, and form and evolve its own community of contributors to progress infrastructure and its documentation. The research group will also meet regularly at the IETFs to support community formation and work progress.
