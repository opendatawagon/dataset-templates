After conducting a literature field and interviewing subject experts, we identified the following data attribute fields for an ideal bookmobile dataset. However, due to database constraints and other factors, not all attributes were used in the final dataset. In future, however, we hope that some of this attributes can be incorporated.

Core data attributes/fields included:

** Circulation attributes:
* StopIdentifier 
* CheckoutDate 
* ReturnDate 
* CheckoutCounts 
* ItemType 
* ItemLanguage 
* Title
* Creator 
* PubYear 
* CardType

**Route attributes:**
* StopIdentifier 
* StopType
* Latitude
* Longitude 
* StopMonth 
* StopYear 
* StopDuration 
* StopRoadCondition

In an ideal world, a library database would have a unique stop identifier to use for bookmobile stops, and this StopIdentifier could be used as a join between circulation and route datasets. Additionally, latitude and longitude could be used as spatial joins, if collected and included on all datasets.

