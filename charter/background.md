Proposed SPACE RG  
**Systems and Protocol Aspects for Circumstellar Environments Research Group**

# BACKGROUND AND MOTIVATION

The Proposed Systems and Protocol Adaptations for Circumstellar Environments Research Group (SPACE RG) shall be chartered to explore and investigate research questions related to architecture, protocol design, manageability considerations, and approaches to operationalize several categories of non-terrestrial networks. 

Specifically, the research group shall focus on networking among potentially heterogeneous nodes (by node type, administration, operator, among others) with highly dynamic connectivity imposed by their non-terrestrial deployment environment. 
This includes High-Altitude Platforms (HAPS), typically in the stratosphere, satellites in Low, Medium, and Geostationary orbits (LEO, MEO, GEO), as well as platforms in other trajectories – cislunar and beyond. 
Since similar considerations may also apply to lower altitude networks among airborne vehicles, both as provider and user of network services, we embrace other networked flying vehicles as well, noting that those may likely be different in scale, mobility, and predictability but pose related challenges to protocols and applications. 
For brevity, all these are collectively referred to below as “aerospace networks”.

Aerospace networks feature several challenging properties that may impact all layers of the networking protocol stack, often in ways that contrast sharply with the assumptions underlying terrestrial networks. 
These challenges have numerous root causes.

1. **Mobility & Topology Dynamics:** High-speed movement, predictable and opportunistic links, frequent topology partitions.  
2. **Environmental & Resource Constraints:** Atmospheric disturbances, limited energy, thermal variability, constrained onboard resources.  
3. **Cost & Lifecycle Limitations:** Expensive to deploy, difficult to upgrade, long service lives, robust-by-design constraints.  
4. **Interoperability Across Domains:** Multi-operator coordination, heterogeneous platforms, administrative boundaries, protocol diversity.

The state of the art addressing these challenges is fragmented and domain-specific. 
Aerospace networks are typically built as isolated, operator-controlled systems, with routing, forwarding, and traffic management handled manually or through proprietary mechanisms. 
These operators have not shown much interest in engaging in standardization or interoperability efforts beyond peering with other ISPs. 
As a result, multiple independent operator-specific aerospace networks have been emerging. 
While the community may (have to) treat these networks as black boxes for the time being, political/regulatory questions may emerge in the future (see “Further Questions” below).

## Relevant Communities

Research efforts are dispersed across disciplines, ranging from aerospace engineering to Internet systems, and standards development is similarly split across bodies like CCSDS, 3GPP, and IETF. 
This siloed landscape impedes progress toward Internet-aligned aerospace networking. 
SPACE RG will engage with external organizations and internal IETF/IRTF initiatives to achieve this:

* **IETF/IRTF Groups**: DTN WG (Delay/Disruption-Tolerant Networking), TIPTOP WG (Protocols for cislunar and deep space scenarios), TVR WG (Time-Variant Routing), PANRG  (Path-Aware Networking, relevant to LEO and multi-path architectures), and GAIA RG (Global Access to the Internet for All), among others. 
Given the sustainability implications aerospace networks may have, we foresee interaction with the SUSTAIN RG to this end.  
* **External Stakeholders**: Academia (Research communities in SIGCOMM, SIGMOBILE, and beyond), Industry (Satellite operators, system integrators, and network equipment vendors), CCSDS (Consultative Committee for Space Data Systems), 3GPP (especially NTN-focused working groups), IPNSIG (Interplanetary Internet Special Interest Group).

Beyond academia and research groups, SPACE RG aims to actively engage industry stakeholders. 
While researchers are already pursuing aerospace networking questions, the involvement of satellite operators, system integrators, and vendors is essential to validate methodologies, align with real-world constraints, and identify opportunities for interoperability. 
By providing a neutral forum under the IRTF, SPACE RG intends to attract companies into contributing data, operational experience, and requirements that can complement academic research and accelerate progress toward practical solutions.

## Initial Contributions

SPACE RG will focus on technical work, including the following directions:

* **Evaluation**: Systematizing techniques for aerospace network simulation, emulation, and in-orbit testing. 
This includes surveying existing toolchains, identifying evaluation metrics, and compiling best practices for comparable and reproducible research.  
This work will be based upon existing aerospace networks as measurable artifacts or simulation environments.  
* **Optimization**: Investigating the design and operational optimization of aerospace networks. 
This includes mathematical modeling, algorithmic approaches, and machine learning for scheduling, data handling, and predictive operations.  
This work will be more hypothetical in nature as present closed systems don’t allow close access to real operation parameters or influence them, but it could inform future operations of aerospace networks.  
* **Systemic**: Exploring architectural models, interfaces, and software paradigms for aerospace networks. 
This includes control-plane design, data handling, and interoperability across heterogeneous and multi-operator environments. 
This work informs the mid-term development of protocols and applications in other IETF WGs and IRTF RGs.

SPACE RG also positions itself as a contributor to other IRTF and IETF efforts by providing realistic scenarios, curated data sets, and context insights derived from aerospace networking environments. 
Rather than proposing protocol changes directly, the group’s influence will come through informing and grounding the work of active WGs and RGs. 
By consolidating evaluation method, tools, testbeds, and reference scenarios, SPACE RG creates a shared foundation that enables other groups to reason about aerospace networks with consistent baselines.

While SPACE RG may explore ideas that imply protocol adaptations, it will not propose changes to existing IETF protocols. 
Instead, it will be an early-stage forum for discussing such implications and will facilitate knowledge transfer to appropriate IETF working groups where standards evolution can be further fostered. 
Topics such as host-to-network connectivity and end-system path selection remain out of scope. 
Given the pace of development in the field, SPACE RG will maintain a living charter subject to periodic updates.

## Other Considerations

While SPACE RG will have a clear initial focus on technical aspects of aerospace networks as explored by the communities identified above, future considerations may include political/regulatory questions as well as related technical ones, such as:

1. **Local interconnectivity requirements?** Should Global (Space) ISPs be required to interconnect with local websites? (e.g., a government website in an African country may be ill served by Starlink if that country's users exit Starlink at a distant ground station in Europe \[[WWW2024](https://dl.acm.org/doi/10.1145/3589334.3645328)\]). 
Such a configuration also means that two nearby users, one connected via a terrestrial ISP and the other via an aerospace network, cannot connect easily.  
2. **Global interoperability**: As new players such as Amazon Kuiper emerge, how should they interoperate? What would BGP for space look like?  
3. **Externalities:** As aerospace networks become larger and start to take on new roles (e.g., Starlink now aims to provide direct-to-cell coverage with T-Mobile), they lead to new externalities, such as impact on radio astronomy or impact on the global carbon footprint of computing and communications. 
This needs to be measured and quantified rigorously.

# MODE OF OPERATION

SPACE RG will reach out to other communities to **provide a forum** for an open, exploratory community that brings together diverse communities to foster cross-disciplinary dialogue. 
To this end, selected people from different communities and backgrounds will be invited to give complementary talks to establish a broad common understanding.

SPACE RG will seek to build its community, from IETFers, IRTFers, and members of other communities alike, and establish a set of contributors to work on concrete deliverables of the research group. 
As we tap into existing research, the initial crystallization point will be understanding the methodologies used across the different communities and documenting best practices along these lines. 
SPACE RG will thus produce documentation on **methodology** to synthesize insights from this exchange into standard methodological baselines for designing, evaluating, and optimizing aerospace networks. 
The intended output of SPACE RG includes:

* **Written documents**. The current focus is on non-RFC-like activities, possibly living documents, or formal outputs serving as checkpoints, like Whitepapers.  
* **Simulators and configurations**: metrics, reference scenarios (think TCP congestion control evaluation), shared code, and scripts.  
* **Measurements**: metrics, guidelines, scripts, and platforms, to help make results reproducible and provide a forum for coordinating future activities.  
Growing LEOscope or similar activities. 
Coordination across testbeds (I am sure multiple will exist) to get comparable measurements, possibly interoperability for more vantage points.  
* **Data repository** (cf. Crawdad for mobility research).
