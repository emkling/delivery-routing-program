# Delivery-Routing-Program
This program was designed to solve a variation of the "Traveling Salesman Problem." It finds an acceptable route for a package delivery service through the implementation of a greedy algorithm. Time is simulated to track the status of packages and record the progress of trucks throughout the simulated day. A user interface offers options for viewing various reports pertaining to the deliveries. 

## Scenario Problem
A parcel delivery service needs to determine an efficient route and delivery distribution for their local deliveries. The delivery route has three trucks, two drivers, and an average of 40 packages to deliver each day. Each package has specific criteria and delivery requirements.

Program a solution where all 40 packages will be delivered on time while meeting each package’s requirements and keeping the combined total distance traveled under 140 miles for both trucks. Distances to each location are given in the attached "distance_data.csv”, addresses are provided in the "address_data.csv," and package information can be found in "package_data_input.csv." One should be able to see, at assigned points, the progress of each truck and its packages by any of the variables listed in the "PackageDataInputs,” including what has been delivered and at what time the delivery occurred.

The following assumptions must be considered:

•   Each truck can carry a maximum of 16 packages, and the ID number of each package is unique.

•   The trucks travel at an average speed of 18 miles per hour and have an infinite amount of gas with no need to stop.

•   There are no collisions.

•   Three trucks and two drivers are available for deliveries. Each driver stays with the same truck as long as that truck is in service.

•   Drivers leave the hub no earlier than 8:00 a.m., with the truck loaded, and can return to the hub for packages if needed. 

•   The delivery and loading times are instantaneous, i.e., no time passes while at a delivery or when moving packages to a truck at the hub (that time is factored into the calculation of the average speed of the trucks).

•   There is up to one special note associated with a package.

•   The delivery address for package #9, Third District Juvenile Court, is wrong and will be corrected at 10:20 a.m. The delivery service is aware that the address is incorrect and will be updated at 10:20 a.m. However, the delivery service does not know the correct address (410 S State St., Salt Lake City, UT 84111) until 10:20 a.m.

•   The distances provided in the "distance_data.csv" are equal regardless of the direction traveled.

•   The day ends when all 40 packages have been delivered.

