<!-- This is a template you can use for quick progress days. It removes a lot of the steps we encourage you to share in the longer template 000-DAY-ARTICLE-LONG-TEMPLATE.MD-->

# VPC Peering with EFS

## Cloud Research

- Create a VPC Peering Connection

- Create the Required Certificates and Setup the Client VPN Endpoint on the VPC

- Connect Using an OpenVPN Client and Connect to an EFS Mount

- Simulated a remotely connected environment, connecting to a VPC using a Client VPN Endpoint. The VPC peered with another VPC in which we setup EFS.

- We configured the appropriate routing to allow the VPN client to connect to EFS in the VPC Peer. 

aws ec2 export-client-vpn-client-configuration --client-vpn-endpoint-id cvpn-endpoint-0620266115c99ba99 --output text>client-config.ovpn

## Next Steps

Cloudformation templates
