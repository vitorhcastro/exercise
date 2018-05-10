# ReadMe
The exercise selected was the DeliveryService.
Pdf with it's description can be found inside the repository.

# Usage
## Users
The exercise has a seed method that creates 2 users:
 - genericAdmin@admin.com
 - genericUser@user.com
Both of their passwords are **Pass123.**

## Access to data
The Points and Routes can be seed when the server is running, via the browser. Only an Admin can create, update or delete either Points or Routes.

The Paths are returned via a Get request, to the endpoint **/api/Paths?startPoint=[name of the point]&endPoint=[name of the point]**
E.g.: /api/Paths?startPoint=A&endPoint=B

## Unit Tests
Due to the requirements of this particular exercise, the tests were made to cover the PointsController, RoutesController and PathsService.
