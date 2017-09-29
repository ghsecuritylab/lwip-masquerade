# LwIP Masquerade

LwIP Masquerade is a fork of [LwIP](https://savannah.nongnu.org/projects/lwip/) with support for TCP/UDP/ICMP masquerading. It is currently based on [the 2.0.1 release](https://github.com/anarchocurious/lwip-masquerade/tree/STABLE-2_0_1_RELEASE) and serves as the IP stack for [Paranoid](https://github.com/anarchocurious/paranoid).

## About LwIP

lwIP is a small independent implementation of the TCP/IP protocol
suite that has been developed by Adam Dunkels at the Computer and
Networks Architectures (CNA) lab at the Swedish Institute of Computer
Science (SICS).

The focus of the lwIP TCP/IP implementation is to reduce the RAM usage
while still having a full scale TCP. This making lwIP suitable for use
in embedded systems with tens of kilobytes of free RAM and room for
around 40 kilobytes of code ROM.

Checkout [the original README](./README) for more details.

## Masquerade

TODO: Document the modifications made to enable masquerading 

## Contributing

Please contribute generic improvements to the LwIP stack [upstream](https://savannah.nongnu.org/projects/lwip/). Bug reports and pull requests specific to the masquerading functionality are welcome on [Github](https://github.com/anarchocurious/paranoid).

## License

The upstream lwIP source and the modifications here are freely available under a [BSD license](./COPYING).

