What it does:

It creates 'n' number of instances. Where the value for count of instances is provided during setup.
It creates these instances in EC2, and corresponding security groups and elb's.
Setups docker on these instances.
Starts mariadb mysql and wordpress linked docker containers on these instances.
Does port maping to make the wordpress reachable on port 8080 on local machine.
Adds the instances to elb.
Currently it only creates public instances and elb's, but this can be easily modified to create private only instances.
