# OSDI'20 artifact evaluation #28

This is the artifact evaluation submission #28 for our paper "Byzantine ordered consensus without Byzantine oligarchy".

## Claims

We made 4 claims which can be found in Figure 3 of our submission. We copy-and-paste them here.

- **claim1**: Archipelago achieves higher throughput than its baselines at the cost of increased latency (latencies are competitive when batching commands).

- **claim2**: Archipelago’s throughput degrades similarly to its baselines when *n* increases, but Archipelago can scale up each node for higher throughput.

- **claim3**: Archipelago incurs modest network overheads over its baselines.

- **claim4**: A geo-distributed deployment increases latencies, but Archipelago’s peak throughput remains similar to a single datacenter setting.

## Artifacts

**Update: ** the latest repos are here: https://github.com/Pompe-org

We implemented 2 artifacts validating the claims.

- **Archipelago-HotStuff**: the git repo is [here](https://github.com/yhzhang0128/archipelago-hotstuff). Please read its default `README.md` for instructions and contact Yunhao Zhang (yz2327@cornell.edu) for any questions about this artifact. This artifact validates **all claims**.

- **Archipelago-Concord**: the git repo is [here](https://github.com/MaggieQi/concord-bft/). Please switch to the **add_archipelago** branch and read `eval/README.md` for instructions. Contact Qi Chen (cheqi@microsoft.com) for any questions about this artifact. This artifact only validates the **first two claims**.
