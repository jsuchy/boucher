* rake servers:restart[id]
* stop, stop, restart, terminate: optionally take a meal and apply to all instances in the current environment (confirm before proceeding)
* rake servers:chef[meal_name]: confirm before proceeding (add force option to bypass)
* security groups:  More thought required
* volumes crud
* EBS snapshots: More thought required
* Elastic IPS
    * rake elasticip:list
    * rake elasticip:allocate
    * rake elasticip:release
    * rake elasticip:bind[ip,instance-id]