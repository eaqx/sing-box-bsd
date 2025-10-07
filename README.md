Since the official sing-box project does not provide kernels for mainstream BSD systems, and the versions available in some BSD software repositories are outdated and lack several default build tags, this repository provides a modified version of the official GitHub Actions workflow for compiling sing-box kernels on major BSD systems.

The compiled kernels in this repository include the following build tags (default):
`with_gvisor` `with_quic` `with_dhcp` `with_wireguard` `with_utls` `with_acme` `with_clash_api` `with_tailscale` `badlinkname` `tfogo_checklinkname0`

You can download the prebuilt binaries directly from the [Releases](https://github.com/eaqx/sing-box-bsd/releases) section of this repository.

Source Code Repository:
[SagerNet/sing-box](https://github.com/SagerNet/sing-box)
