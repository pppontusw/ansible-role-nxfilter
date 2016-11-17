# NXFILTER

Installs the NXFILTER DNS blacklist service

## Notes

There is no automated configuration for this service so this role will simply

1. Install NXFILTER
2. Update the blacklist (shallalist)
3. Start NXFILTER

Configuration needs to be done manually on http://server/admin

Remember to set:

1. admin password
2. upstream dns
3. local dns bypass (if required)
4. block page
5. syslog host
6. category to shallalist