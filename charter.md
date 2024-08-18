# Non-Terrestrial Networking Research Group (NTNRG)

The Non-Terrestrial Networking Research Group (NTNRG) is chartered to explore and investigate research questions related to architecture, protocol design, manageability considerations, and approaches to operationalize non-terrestrial networks. Specifically, NTNRG focuses on networking among differently-owned nodes with highly dynamic connectivity imposed by their non-terrestrial deployment environment. This includes High Altitude Platforms (HAPS), typically in the stratosphere, satellites in Low, Medium, and Geostationary orbits (LEO, MEO, GEO), and platforms in other cislunar trajectories.

Previous IRTF work (DTNRG) focused on the delay and disruption tolerance required to communicate effectively in extreme connectivity-challenged scenarios (vis. RFC 4838). That effort led to the creation of the IETF DTNWG, which standardized BPv7 (RFC 9171) and BPSec (RFC 9172). Since then, the Cislunar regime's network nodes on aerospace platforms have rapidly risen in deployment and scale. This regime poses less extreme time constraints on connectivity, but the rapid change and variability of topologies that might be built among nodes moving through this environment present new challenges.

The intended work products of the NTNRG include an evaluation of the impact of inter-networking among NTN nodes imposed by these deployments, as well as possible mitigation of adverse effects. Of specific interest are:

* Simulation, measurement, or testing techniques particularly well suited for NTNs.
* Analysis of any impact on transport protocols as paths experience regular changes in characteristics like latency, jitter, and loss associated with nominal platform behavior.
* Investigation of the challenges and benefits of tuning existing transport and application protocols in emerging NTN architectures.
* Exploration of management approaches that take into account NTN-specifics. 
* Conception of application models and interfaces considering human and robotic NTNs.

NTNRG may also consider the implications and requirements for NTN nodes from different administrative domains dynamically providing connectivity. The control plane requirements and trust model design parameters are especially relevant.

An explicit non-goal is to propose changes to existing IETF protocols. The research group may explore ideas that require such changes and is uniquely placed to discuss their implications with the IETF community. Still, the potential incorporation of such ideas into the standards process is a matter for the IETF and is out of the scope of this group.

The group shall consider emerging NTN protocols from organizations such as CCSDS and 3GPP, aiming to adapt IETF protocols to integrate with other underlying or overlaying technologies.

Considerations related to hosts connecting to an NTN and path selection strategies among available connectivity (including via NTN) are out of scope.
