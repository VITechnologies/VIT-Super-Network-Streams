# Super Network Streams
VIT Super Network Streams is a class encapsulating and extending Network Stream functionality.

VIT Super Network Streams tackle the critical challenge of maintaining continuous data flow even when network disruptions occur. Thanks to the integrated connection watchdog, any disruption such as an endpoint reset is automatically detected and corrected, ensuring that your data remains intact and reliable.

These streams serve as one-way, buffered communication paths, allowing for high-throughput data streaming with the resilience of lossless transmission. This automated reliability frees developers from the complexities of network protocols, allowing them to devote their energy to application development.

Designed with a focus on simplicity and efficiency, Super Network Streams are perfect for developers who need dependable inter-process communication without the hassle of manual reconnection logic.

## Usage

Install the package from VIPM

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

VIT Super Network Stream is an open source project maintained by [VI Technologies](http://vi-tech.nl).

## License

VIT Super Network Stream is distributed under the open source three clause BSD license providing everyone right to use and distribute both souce code and compiled versions of the VIT Super Network Stream. See [LICENSE](https://github.com/VITechnologies/VIT-Super-Network-Streams/blob/main/LICENSE) file for details.