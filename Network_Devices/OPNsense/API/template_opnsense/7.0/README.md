# Template for OPNsense

Template to query OPNsense by API.


## Included queries

With this template you can query:
- API status
- Gateways
- OpenVPN Sessions
- Certificate status


## Triggers

None yet.


## API User

To be able to query the API you need a user with specific permissions which are listed below, depending on the data you want to gather.


## Permissions

Please be aware that for some permission sets there is **no read-only** permission.
The "_System: Certificate Manager_" for example allows to download **private key material**!

| Item                           | OPNsense Permission         |
| ------------------------------ | --------------------------- |
| OPNsense: API Status           | System: Status              |
| OPNsense: Gateways             | System: Gateways            |
| OPNsense: OpenVPN Sessions     | Status: OpenVPN             |
| OPNsense: Trust - Certificates | System: Certificate Manager |


## Author

Dominik Künne