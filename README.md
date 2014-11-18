# localgovdotapi
[![Build Status](https://travis-ci.org/dhilton/localgovdotapi.svg?branch=master)](https://travis-ci.org/dhilton/localgovdotapi)

An experiment in localgov apis for common services. 

The idea is to use Swagger (a restful DSL) to specify a set of API's for common local government services.

Each service is held in a separate branch, with trunk considered a stable releasable set of common apis.


Current services under development:

### Waste Services


Order a new bin container, check collection dates for a property, order a one off collection, add a new collection service to a property.


### Concessionary travel & Blue Badges


Order a new concessionary travel card, order a new Blue Badge.

### Local tax

Apply for a student council tax exemption, apply for a single person council tax discount.


### Property


A basic foundation service for descibing property related attributes - maybe GIS derived or delivered.

- Get Council tax band
- Get land title (reference land registry?)
- Get area details (Could include parking zone, district / brough, etc)
- Business rates
- Planning applications



## Contribution guide



Fork the repo on github, checkout a branch for the area you want to work on and then build up your work with local commits on your branch, adding use cases.
Once you're happy, issue a pull request to the main repo. Please, please include links to real world examples of local government services, so we can validate the need for the API. 

Thanks!

@danhilton





