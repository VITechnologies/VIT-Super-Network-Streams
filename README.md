# Super Network Streams
The Super Network Streams is a class (background process) that encapsulates LabVIEW Network Stream functionality to:
- Send/Receive LabVIEW Objects
- Autorecovery if the remote endpoint gets destoyed or has a connection timeout
- Background stream reading and publish the received data via user events
- Allows communication between two applications on the same machine (localhost)

The class has a read or write mode, so the same class can be used on both endpoints.

Designed with a focus on simplicity and efficiency, Super Network Streams are perfect for developers who need dependable inter-process communication without the hassle of manual reconnection logic.

## Usage

Install the package from VIPM

[![Image](https://www.vipm.io/package/vi_technologies_lib_super_network_streams/badge.svg?metric=installs)](https://www.vipm.io/package/vi_technologies_lib_super_network_streams/) [![Image](https://www.vipm.io/package/vi_technologies_lib_super_network_streams/badge.svg?metric=stars)](https://www.vipm.io/package/vi_technologies_lib_super_network_streams/)

In the examples you'll find a simple example of a simple reader and a writer Super Network Stream

![Simple Reader Example](/docs/ReaderExample.png)


![Simple Writer Example](/docs/WriterExample.png)


## Contributing

Requirements:
- LV2020


Workflow:
1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request


## Credits

VIT Super Network Streams is an open source project maintained by [VI Technologies](http://vi-tech.nl).

## License

VIT Super Network Stream is distributed under the open source BSD 3-Clause License providing everyone right to use and distribute both souce code and compiled versions of the VIT Super Network Streams. See [LICENSE](https://github.com/VITechnologies/VIT-Super-Network-Streams/blob/main/LICENSE) file for details.