# Here are some key points about trunks:<br /><br />

VLAN Tagging: Trunk links use a method called VLAN tagging to differentiate between the traffic of different VLANs. Each frame transmitted over the trunk includes a VLAN tag in the Ethernet frame header, indicating the VLAN to which the frame belongs.<br />

Carrying Multiple VLANs: A trunk link can carry traffic for multiple VLANs simultaneously. This is useful in scenarios where different VLANs need to communicate with each other, especially in larger and more complex network environments.<br />

Interconnecting Switches: Trunks are often used to interconnect switches in order to facilitate the exchange of traffic between devices on different VLANs. This helps in segmenting the network logically for better performance, security, and management.<br />

Router-to-Switch Connections: Trunks are also used to connect switches to routers, allowing the router to route traffic between different VLANs. In this case, the trunk link enables the router to understand and process VLAN-tagged frames.<br />

802.1Q Standard: The most common protocol for VLAN tagging on trunk links is the IEEE 802.1Q standard. This standard defines how VLAN information is included in Ethernet frames.<br />
