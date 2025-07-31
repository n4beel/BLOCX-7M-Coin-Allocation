# BLOCX Consensus Client - Remote Server Updates Summary

## Docker Image: `blocxtech/lighthouse:v1.0.3`
- 7M BLOCX token re-allocation system (slots 3,250,000-3,250,069)
- ENS integration for validator nodes

---

## Server Update Status

| Server IP | Purpose | Services Updated | Status |
|-----------|---------|------------------|---------|
| 209.145.57.126 | ETH2.0 BEACONCHA | Beacon Node | ✅ DONE |
| 89.117.59.14 | POS NODE | Validator + Beacon | ✅ DONE |
| 89.117.60.7 | ETH2.0 MAINNET (64 validators) | Validator + Beacon | ✅ DONE |
| 178.18.248.45 | BLOCKSCOUT EXPLORER + rpc2.blocxscan.com | Beacon Node | ✅ DONE |
| 65.20.108.189 | rpc1.blocxscan.com | Beacon Node | ✅ DONE |
| 66.42.97.78 | rpc.blocxscan.com | Beacon Node | ✅ DONE |
| 161.97.156.81 | LAUNCHPAD + NODE | - | ⚠️ No Docker Processes |
| 89.117.60.32 | Normal Node | - | ⚠️ No Docker Processes |

---

## Summary
- **Successfully Updated**: 6/8 servers (75%)
- **Requires Investigation**: 2/8 servers (25%)
- **Total Beacon Nodes Updated**: 6
- **Total Validator Nodes Updated**: 2

---

*Updated: July 31, 2025 | Docker Version: v1.0.3*
