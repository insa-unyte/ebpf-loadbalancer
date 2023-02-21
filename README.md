#### :warning: This repository has been moved to [network-analytics](https://github.com/network-analytics) organization in [ebpf-loadbalancer](https://github.com/network-analytics/ebpf-loadbalancer)

# eBPF Load balancer
Linux eBPF load balancer to be attached into SO_REUSEPORT socket group.

This eBPF program allows load balance packets based on their src IP. All packets from the same src IP will land into the same collector.
