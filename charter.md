# Systems and Protocol Adaptations for Circumstellar Environments Research Group (SPACE RG)

The Systems and Protocol Adaptations for Circumstellar Environments Research Group (SPACE RG) is chartered to explore and investigate research questions related to architecture, protocol design, manageability considerations, and approaches to operationalize several categories of non-terrestrial networks. Specifically, the research group focuses on networking among differently-owned nodes with highly dynamic connectivity imposed by their non-terrestrial deployment environment. This includes High Altitude Platforms (HAPS), typically in the stratosphere, satellites in Low, Medium, and Geostationary orbits (LEO, MEO, GEO), as well as platforms in other trajectories -- cislunar and beyond. For brevity, these are collectively referred to below as "aerospace networks".

Previous IRTF work (DTNRG) focused on the delay and disruption tolerance required to communicate effectively in extreme connectivity-challenged scenarios (vis. RFC 4838). That effort led to the creation of the IETF DTNWG, which standardized BPv7 (RFC 9171) and BPSec (RFC 9172). Since then, network nodes on aerospace platforms in cislunar regimes have rapidly risen in deployment and scale. This regime poses less extreme time constraints on connectivity, but the rapid change and variability of topologies that might be built among nodes moving through this environment present new challenges.

The intended work products of the SPACE RG include an evaluation of the impact of inter-networking imposed by these deployments, as well as possible mitigation of adverse effects. Of specific interest are:

* Simulation, measurement, or testing techniques particularly well suited for aerospace networks.
* Analysis of any impact on transport protocols as paths experience regular changes in characteristics like latency, jitter, and loss associated with nominal platform behavior.
* Investigation of the challenges and benefits of tuning existing network, transport, and application protocols in emerging aerospace network architectures.
* Researching applicability of Traffic Engineering techniques for optimizing data flows in aerospace networks, considering unique challenges such as dynamic topologies, high latency, limited bandwidth, and the challenges of store-and-forward networking.
* Exploration of management approaches that take into account functional and operation requirements specific to aerospace-networks.
* Conception of application models and interfaces considering human and robotic aerospace networks.

SPACE RG may also consider the implications and requirements for aerospace nodes from different administrative domains dynamically providing connectivity. The control plane requirements and trust model design parameters are especially relevant.

The group shall consider emerging related protocols from organizations such as CCSDS and 3GPP, and assess adaptations for IETF protocols to integrate with other underlying or overlaying technologies.

An explicit non-goal is to propose changes to existing IETF protocols. The research group may explore ideas that require such changes and is uniquely placed to discuss their implications with the IETF community. Still, the potential incorporation of such ideas into the standards process is a matter for the IETF and is out of the scope of this group.

Considerations related to hosts connecting to an aerospace network and path selection strategies among available connectivity are initially out of scope.
