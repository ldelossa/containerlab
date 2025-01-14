|                               |                                                                                  |
| ----------------------------- | -------------------------------------------------------------------------------- |
| **Description**               | A Nokia SR Linux connected back-to-back with Cisco XRv                           |
| **Components**                | [Nokia SR Linux][srl], Cisco XRv                                                 |
| **Resource requirements**[^1] | :fontawesome-solid-microchip: 1 <br/>:fontawesome-solid-memory: 3 GB             |
| **Topology file**             | [vr03.clab.yml][topofile]                                                        |
| **Name**                      | vr03                                                                             |
| **Version information**[^2]   | `containerlab:0.9.0`, `srlinux:20.6.3-145`, `vr-xrv:6.1.2`, `docker-ce:19.03.13` |

## Description
A lab consists of an SR Linux node connected with Cisco XRv via a point-to-point ethernet link. Both nodes are also connected with their management interfaces to the `clab` docker network.

Cisco XRv VM is launched as a container, using [vrnetlab integration](../manual/vrnetlab.md).

<div class="mxgraph" style="max-width:100%;border:1px solid transparent;margin:0 auto; display:block;" data-mxgraph="{&quot;page&quot;:0,&quot;zoom&quot;:1.5,&quot;highlight&quot;:&quot;#0000ff&quot;,&quot;nav&quot;:true,&quot;check-visible-state&quot;:true,&quot;resize&quot;:true,&quot;url&quot;:&quot;https://raw.githubusercontent.com/srl-labs/containerlab/diagrams/vr03.drawio&quot;}"></div>

## Use cases
This lab allows users to launch basic interoperability scenarios between Nokia SR Linux and Cisco XRv network operating systems.

The lab directory [contains](https://github.com/srl-labs/containerlab/tree/master/lab-examples/vr03) files with essential configurations which can be used to jumpstart the interop demonstration.

[srl]: https://www.nokia.com/networks/products/service-router-linux-NOS/
[topofile]: https://github.com/srl-labs/containerlab/tree/master/lab-examples/vr03/vr03.clab.yml

[^1]: Resource requirements are provisional. Consult with the installation guides for additional information.
[^2]: The lab has been validated using these versions of the required tools/components. Using versions other than stated might lead to a non-operational setup process.

<script type="text/javascript" src="https://viewer.diagrams.net/js/viewer-static.min.js" async></script>