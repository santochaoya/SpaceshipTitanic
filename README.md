# SpaceshipTitanic
This is the practice of the Competition on Kaggle

## Dataset Description

* **train.csv** - Personal records for about two-thirds (~8700) of the passengers, to be used as training data.
  * ```PassengerId``` - A unique id for each passenger. Each id takes from ```gggg_pp``` where ```gggg``` indicates a group the passenger is travelling with and ```pp``` is their number within the group. People in a group a often family member, but not always.
  * ```HomePlanet``` - The planet the passenger departed from, typically their planet of pernanment residence.
  * ```CryoSleep``` - Indicates whether the passenger elected to be put into suspended animation for the duration of the voyage. Passengers in cryosleep are confirmed to their cabins.
  * ```Cabin``` - The cabin number where the passenger in staying. Takes the form ```deck/num/side```, where ```side``` can be either ```P``` for Port or ```S``` for Starboard.
  * ```Destination``` - The planet the passenger will be debarking to.
  * ```Age``` - The age of the passenger.
  * ```VIP``` - Whether the passenger has paid for special VIP service during the voyage.
  * ```RoomService```, ```FoodCort```, ```ShoppingMall```, ```Spa```, ```VRDeck``` - Amount the passenger has billed at each of the Spaceship Titanic's many luxury amenities.
  * ```Name``` - The first and last names of the passenger.
  * ```Transported``` - Whether the passenger was trasported to another dimension. This is the target, the column you are trying to predict.

* **test.csv** - Personal records for the remaining one-third (~4300) of the passenger, to be used as test data. Your task is to predict the value of ```Transported``` for the passengers in this set.