<!-- Module 4: ACL Concepts -->

<!-- 4.1: Purpose of ACLs -->

## A series of IOS commands that are used to filter packets based on information found in the packet header

- ACL

## Explain. Router before and after applying ACLs

- By default, a router does not have any ACLs configured. However, when an ACL is applied to an interface, the router performs the additional task of evaluating all network packets as they pass through the interface to determine if the packet can be forwarded.

## a sequential list of permit or deny statements

- access control entries (ACEs)

## Tasks performed by ACLs:

- Limit network traffic to increase network performance
- Provide traffic flow control
- Provide a basic level of security for network access
- Filter traffic based on traffic type
- Screen hosts to permit or deny access to network services
- Provide priority to certain classes of network traffic

## controls access to a network by analyzing the incoming and/or outgoing packets and forwarding them or discarding them based on given criteria

- Packet filtering

## types of ACLs. Only filter at Layer 3 using the source IPv4 address only.

- Standard ACLs

## types of ACLs. filter at Layer 3 using the source and / or destination IPv4 address. They can also filter at Layer 4 using TCP, UDP ports, and optional protocol type information for finer control.

- Extended ACLs

## filters packets before they are routed to the outbound interface.

- inbound ACL

## filters packets after being routed, regardless of the inbound interface.

- outbound ACL