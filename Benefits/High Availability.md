### Availability
A synonym for it is up-time, as it is the amount of time your users can access your service.
There isn't such thing as a 100% availability.

### HA (High Availability)

Ability to remain operational even during outages.
There are two types of outages:
* Planned
	* Patches
	* Updates
	* Hardware replacements or upgrades
	* Migrations
* Unplanned
	* Hardware issues
	* Network issues
	* Power outages
	* Natural disasters
	* Human disasters
		* Cyber attacks
		* Bugs
		* Poor design
		* Poor scalability

#### Methods to mitigate planned outages

* Perform gradual deployments can help reduce the errors, e.g. when Facebook does a deployment, it does so on a couple of servers to see how it behaves before having a complete release.
* Constant testing and monitoring of the deployment and see if there are an increase number of errors, either internal or reported by users.
* Having a rollback plan can also help with failed deployments or some other planned outages.
* Having constant small incremental deployments since the amount of errors could be less and also less critical.

#### Methods to mitigate unplanned outages

* You need to ensure that any single component of your service has redundancy, two servers, two networks, two locations, etc.
* Having health monitoring can prevent issue detection before users have to report.
* Automation to reboot servers in case of a disasters.
* Strong security practices can also help with cyber attacks
* Disaster recovery plans are also needed, and they need to be tested and executed fast.
* Test the load of your services, and find any bottlenecks, either platform or code dependent
