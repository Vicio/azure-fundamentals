Forces the security to be tightened to the maximum possible level, requiring any user to prove their identity as well as proving the devices and locations where such user is authenticating from.
## Zero Trust Principles
* Verify explicitly - Always require the user to identify themselves regardless of the type of user
* Use least privileged access - Always set the default access to the minimum for every user.
* Assume breach - Configure your infrastructure as if a hacker has already breached your security.

### Just-in-time (JIT) and Just-enough-access (JEA)
Instead of always having a user with admin privileges, another layer of security can be added by providing temporary access to the admin level (JIT). Once the time limit for admin level is reached, the user returns to the default or a less privileged level of access (JEA).

## Security policy enforcement
* Identity - Always try to verify any request
* Devices - Always monitor the devices used
* Applications - Always protect your apps with levels of permission and monitor app activity
* Data - Always encrypt all data and restrict direct access to it
* Infrastructure - Always monitor servers, connections, services and users to detect attacks as fast as possible
* Network - Always encrypt all communication, even on local networks.