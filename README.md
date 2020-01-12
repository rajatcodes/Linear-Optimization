# Linear-Optimization

## About Project
      A transportation company is evaluating a prototype system that combines trucks
    and drones for last-mile delivery services. The test run considers a set of orders that
    must be delivered to known locations. A delivery truck starts from a depot and visits
    “launch sites” corresponding to the customers locations. From each launch site, the
    truck deploys a series of drones that deliver the orders and return back to meet the
    truck at the launch site. Once all the drones are recovered, the truck moves to the
    next launch site and repeats the process until all orders are delivered.
    
 ## Assumptions 
    1. We have a euclidean distance matrix between each delivery locations.
    2. Assume that the depot is located at the origin (0,0).
    3. The truck can deploy up to K drones at each stop in a launch site.
    4. The drones have limited cargo capacity and as a result they can only visit 1 customer (not counting the starting point) before returning to the truck.
    5. Each customer should be visited at least once by a drone. The customer locations used as launch sites will be visited by the truck and also will serve as the starting and ending point of a drone tour.
    6. For each unit of distance traveled by the truck there is a cost of $10, whilefor each unit of distance traveled by a drone there is a cost of $3.
    
