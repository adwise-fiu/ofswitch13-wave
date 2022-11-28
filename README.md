# OpenFlow 1.3 and wave module for ns-3 #
This is a Modified OFSwitch13 module with switch ports to include DSRC capabilities. Allowing [ns-3 Network Simulator][ns-3] users to simulate Software-Defined Networks (SDN) with [OpenFlow 1.3][ofp13] capabilities. We also modified the WAVE netdevice definition to include the ofswitch13 callback.
In fact, this module implements the interface for interconnecting the ns-3 simulator to the [OpenFlow 1.3 Software Switch for ns-3][ofs13] (ofsoftswitch13) library. It is the library that, in fact, provides the switch implementation, the library for converting to/from OpenFlow 1.3 wire format, and the dpctl tool for configuring the switch from the console.

Please, visit the [OFSwitch13 project homepage][project] for detailed information on the module design, documentation, and *how to get started* tutorials. The code API documentation for the latest release of this project is available [here][apidoc].


# Acknowledgments #
The initial version of the code was developed by Luciano J Chaves [OpenFlow 1.3 Software Switch for ns-3][ofs13].




[ns-3]: https://www.nsnam.org
[ofp13]: https://www.opennetworking.org/sdn-resources/technical-library
[ofs13]: https://github.com/ljerezchaves/ofsoftswitch13
[project]: http://www.lrc.ic.unicamp.br/ofswitch13/
[apidoc]: http://www.lrc.ic.unicamp.br/ofswitch13/doc/html/index.html
[issues]: https://github.com/ljerezchaves/ofswitch13-module/issues
[gpl]: http://www.gnu.org/copyleft/gpl.html
[group]: https://groups.google.com/forum/#!forum/ofswitch13-users



