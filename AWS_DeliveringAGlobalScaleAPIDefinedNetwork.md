# Amazon Web Services
Meetup - 2/19/2015
Kevin Miller - Sr. Manager, EC2 Networking

## Delivering a Global-Scale API-Defined Network

Intro:
* 516 new features in 2014
* VPC
  - Private network
  - Private connections to other VPCs
  - Sec groups, VPN, etc.
* 99 APIs offered for virtual networking

### VPC Peering

Provide private connectivity between two VPCs

1) Why?
  * New address ranges
  * Application isolation
  * Among business ventures / joint ventures

2) 5 APIs for VPC peering
  * CreateVpcPeeringConnection
  * Describe...
  * Delete...
  * Accept...
  * Reject...

## Questions

Q. Do you support peering between regions?
A. Not currently - maybe in future.

Q. What are the use cases for VPC peering?
A. Basically just to connect two private networks.

Q. What goes on hardware-wise between the scenes?
A. The customer experience is immediate availability - most is very automated.

