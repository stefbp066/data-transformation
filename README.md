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
EnqueuedTimeSP: DD/MM/YYYY (converted to Brazilian timezone - UTC-3) \

### 2️⃣ DynamicPriceRange.csv
Provider: in quotes
OfferId: in quotes
MinGlobal: without quotes
MinRecommended: without quotes
MaxRecommended: without quotes
DifferenceMinRecommendMinTheory: without quotes
EnqueuedTimeSP: DD/MM/YYYY (converted to Brasilian timezone - UTC-3)

### 3️⃣ CuratedOfferOptions.csv
CurationProvider: in quotes
OfferId: in quotes
DealerId: in quotes
UniqueOptionId: in quotes
OptionId: in quotes
IsMobileDealer: without quotes
IsOpen: without quotes
Eta: in quotes
ChamaScore: without quotes
ProductBrand: in quotes
IsWinner: without quotes
MinimumPrice: without quotes
MaximumPrice: without quotes
DynamicPrice: without quotes
FinalPrice: without quotes
DefeatPrimaryReason: in quotes
DefeatReasons: in quotes
EnqueuedTimeSP: DD/MM/YYYY (converted to Brazilian timezone - UTC-3)

