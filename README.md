Since the official sing-box project does not provide kernels for mainstream BSD systems, and the version available in the FreeBSD software repository is outdated and lacks several default build tags, this repository provides a modified version of the official GitHub Actions workflow for compiling sing-box kernels on major BSD systems.

The compiled kernels in this repository include the following build tags (default):
`with_gvisor` `with_quic` `with_dhcp` `with_wireguard` `with_utls` `with_acme` `with_clash_api` `with_tailscale`

Source Code Repository:
[SagerNet/sing-box](https://github.com/SagerNet/sing-box)
