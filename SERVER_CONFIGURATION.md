## 34rth private Tron Testnet

Our testnet nodes (2 Full Nodes, 1 Super Node) are running at the moment on the same machine, but we will expand it in the future. The branch is master and we will update it daily. Please feel free to comment and post issues.

https://github.com/34rth


## Server configuration & Location Configuration:
* Location: Hetzner Online AG, Bavaria/Germany
* Future locations will be equally distributed between all available Heroku regions
* Public IP: 94.130.165.82

## Specification
* Intel® Xeon® E5-1650 v3 Hexa-Core Haswell processor
* 256 GB DDR4 ECC RAM
* 960GB NVMe Data Center Series SSDs in a Raid 1 configuration.

## Hardware Expansion Plan for 2018 (after June 26)
* Consul & Route53 
* configuration to route static public IPs to dynamically assigned IPs in Heroku for super-node containers 
* Prometheus availability metrics will be shared publicly.
* Auto-failover & recovery in case of disaster.
* 55% of all awards will directly go in auto-scaling infrastructure.
* Hardware expansion will be automated to Heroku with PERFORMANCE L nodes. Formula: floor((awards in USDT)*0.55 / 500) == nr of PERFORMANCE L nodes.
