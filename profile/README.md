### Blockchain Decentralisation Index

Open source tool kit for measuring the decentralisation of distributed ledgers, layer by layer — consensus, tokenomics, network, software, and beyond.

### Scope of Lab

The lab develops and maintains a suite of open source tools that collect data from live blockchain systems, parse it into a common format, and compute decentralisation metrics over it. Each tool targets a distinct layer of the stack and shares a common pipeline architecture (collect → parse → map to entities → apply metrics → publish).

The metrics themselves are drawn from several disciplines — economics (Gini, Nakamoto coefficient, HHI), information theory (entropy), and network science — and are applied uniformly across systems so that results are comparable across chains and over time rather than being one-off measurements of a single network.

Our mission is to make the decentralisation of a distributed ledger a measurable, reproducible, comparable property rather than a marketing claim — and to keep the methodology and the code that implements it in the open, where anyone can audit, criticise, and extend it.

Origin and history. The work began at the Blockchain Technology Laboratory in the School of Informatics at the University of Edinburgh, as the Edinburgh Decentralisation Index (EDI), a research project studying blockchain decentralisation from first principles. The first tool was released publicly in 2024, followed by a public dashboard and a growing set of peer-reviewed publications underpinning the methodology. 


### Alignment with LFDT Mission

LFDT exists to advance open, multi-party systems built on decentralised technology. Decentralisation is the property that the entire premise rests on — and across the ecosystem it is asserted far more often than it is measured. There is still no universally accepted methodology for quantifying how decentralised a system actually is, which means claims are easy to make. but difficult to compare and to falsify.

We believe that LFDT is the right home for this lab for two reasons:

First and foremost, neutrality. Vendor-neutral foundation governance is exactly the structure this kind of work needs, in the same way it is the structure that benchmarking and conformance efforts need generally.

Second, it is cross-cutting infrastructure for LFDT's existing portfolio. The metrics are not chain-specific. The same pipelines that measure public chains can be pointed at consortium and permissioned networks. Extending the tooling to networks built on LFDT projects is one direction that the project could take if adopted by the foundation.

### Relation to Existing LFDT Labs and Projects

No existing LFDT lab or project measures decentralisation. The closest structural analogue is Hyperledger Caliper, which benchmarks the performance of blockchain systems; this lab does for decentralisation what Caliper does for throughput and latency. The two are complements, not competitors, and address the two properties most often claimed without evidence.

Elsewhere in the ecosystem, decentralisation measurement tends to appear as one-off academic papers, single-chain dashboards maintained by that chain's own community, or closed analytics products whose methodology cannot be inspected. What distinguishes this work is the combination of: coverage of multiple layers rather than a single headline number; a common pipeline applied uniformly across heterogeneous systems; peer-reviewed and published methodology, which allows everyone to reproduce it.
