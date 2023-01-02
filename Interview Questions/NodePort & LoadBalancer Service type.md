Nodeport - Application can be accessed using **Node IP & port allocated by kubernetes**.

LoadBalancer - Its used when we want to open the application to outside world.

If we're deploying on Cloud Platform like AWS then AWS will give a **static IP** using which outside people can access the appplication. For on-premise, metalLb is used.
