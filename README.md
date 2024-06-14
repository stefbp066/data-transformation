# data-transformation

Part of a past selection process with Chama, related to data engineering positions.
The task is to extract all necessary data from a json file, and generate 3 csv files.
This is done via Python, mainly with json and pandas.

## CSVs:
### 1️⃣ DynamicPriceOption.csv
Provider: in quotes \
OfferId: in quotes \
UniqueOptionId: in quotes \
BestPrice: without quotes \
EnqueuedTimeSP: DD/MM/YYYY (converted to Brazilian timezone - UTC-3)

### 2️⃣ DynamicPriceRange.csv
Provider: in quotes <br />
OfferId: in quotes <br />
MinGlobal: without quotes <br />
MinRecommended: without quotes <br />
MaxRecommended: without quotes <br />
DifferenceMinRecommendMinTheory: without quotes <br />
EnqueuedTimeSP: DD/MM/YYYY (converted to Brazilian timezone - UTC-3) 

### 3️⃣ CuratedOfferOptions.csv
CurationProvider: in quotes <br />
OfferId: in quotes <br />
DealerId: in quotes <br />
UniqueOptionId: in quotes <br />
OptionId: in quotes <br />
IsMobileDealer: without quotes <br />
IsOpen: without quotes <br />
Eta: in quotes <br />
ChamaScore: without quotes <br />
ProductBrand: in quotes <br />
IsWinner: without quotes <br />
MinimumPrice: without quotes <br />
MaximumPrice: without quotes <br />
DynamicPrice: without quotes <br />
FinalPrice: without quotes <br />
DefeatPrimaryReason: in quotes <br />
DefeatReasons: in quotes <br />
EnqueuedTimeSP: DD/MM/YYYY (converted to Brazilian timezone - UTC-3)

