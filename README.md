# code-gladiators-Conversion-fraud-in-Digital-Advertising
These are the files ipynb related to techgig code gladiator machine learning competion.
One file contain models using additional data provided.
Other file conatains model without using additonal data provided.


Conversion fraud in Digital Advertising
Digital Advertising is changing at a rapid pace with a huge increase in digital audience. At the same time, the digital advertising success metric is shifting from audience volume (eg. Impression count) to conversions (eg. lead submissions) as the success metric. This requires higher transparency and control on the conversions.

Colombia, the digital advertising arm of Times Internet Limited has seen significant growth in its digital advertising inventory. It wants to ensure that in all its conversion-based campaigns, no unfair advantage is given to the publishers generating fake leads.

Your task is to segregate the test data between genuine and false conversions by identifying the maximum possible leads generated by the malignant technique.

Note-
Joining with Click log:
imprId (Click Log) and imprid_cr (Conversion Log - Test and Train Data)

(Use click log data for additional data required for identifying conversion fraud)

Essential Columns
client id: Advertiser ID
pubclient id: Publisher ID
clickIp: IP Address
clmbuser id : unique user id
impr id: Unique Key for every served impression
site id: Publisher wesite
goal id: Conversion`s goal type identification id
City id / State id / CountryDim id: Geo Details
browser id: browser used for accessing publisher on any device on web.
adslot id: slot id where advertisement is displayed on any site (unqiue for all sites)
crtd: timestamp of the action
itmclmb id: Image/Creative shown
ispDimId: Internet Service Provider
devTypeDimId: Device Id
osVerDimId: OS Version
