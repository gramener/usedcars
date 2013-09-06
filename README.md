usedcars
========

This is a tutorial for the Gramener visualisation server for the class on 6 Sep 2013.

This repo will be deleted after 10 Sep 2013.

Data dictionary
===============

Field Name                          Definition
RefID                               Unique (sequential) number assigned to vehicles
IsBadBuy                            Identifies if the kicked vehicle was an avoidable purchase
PurchDate                           The Date the vehicle was Purchased at Auction
Auction                             Auction provider at which the  vehicle was purchased
VehYear                             The manufacturer's year of the vehicle
VehicleAge                          The Years elapsed since the manufacturer's year
Make                                Vehicle Manufacturer
Model                               Vehicle Model
Trim                                Vehicle Trim Level
SubModel                            Vehicle Submodel
Color                               Vehicle Color
Transmission                        Vehicles transmission type (Automatic, Manual)
WheelTypeID                         The type id of the vehicle wheel
WheelType                           The vehicle wheel type description (Alloy, Covers)
VehOdo                              The vehicles odometer reading
Nationality                         The Manufacturer's country
Size                                The size category of the vehicle (Compact, SUV, etc.)
TopThreeAmericanName                Identifies if the manufacturer is one of the top three American manufacturers

                                    Acquisition price for this vehicle in:
MMRAcquisitionAuctionAveragePrice       - average condition at time of purchase
MMRAcquisitionAuctionCleanPrice         - the above Average condition at time of purchase
MMRAcquisitionRetailAveragePrice        - the retail market in average condition at time of purchase
MMRAcquisitonRetailCleanPrice           - the retail market in above average condition at time of purchase
MMRCurrentAuctionAveragePrice           - average condition as of current day
MMRCurrentAuctionCleanPrice             - the above condition as of current day
MMRCurrentRetailAveragePrice            - the retail market in average condition as of current day
MMRCurrentRetailCleanPrice              - the retail market in above average condition as of current day
PRIMEUNIT                           Identifies if the vehicle would have a higher demand than a standard purchase
AcquisitionType                     Identifies how the vehicle was aquired (Auction buy, trade in, etc)
AUCGUART                            The level guarntee provided by auction for the vehicle
                                    (Green - Guaranteed/arbitratable, Yellow - caution/issue, red - sold as is)
KickDate                            Date the vehicle was kicked back to the auction
BYRNO                               Unique number assigned to the buyer that purchased the vehicle
VNZIP                               Zipcode where the car was purchased
VNST                                State where the the car was purchased
VehBCost                            Acquisition cost paid for the vehicle at time of purchase
IsOnlineSale                        Identifies if the vehicle was originally purchased online
WarrantyCost                        Warranty price (term=36 month and mileage=36K)
