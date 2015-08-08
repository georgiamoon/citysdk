hackathon in october

justice mapping project

data
api for census prison population data
prisons, nursings homes, colleges

census API key: 5b970404c12aeda77feb30137b58c1209882f653

case for why we need re-entry specific data

neighborhood --> arrests --> prison --> return --> neighborhood
DC & Philly

how to work with data

json --> data (chrome plugins, sublime, etc)

visaulziation resources & tools


FROM LAURIN

https://hackpad.com/Rebuilding-Re-entry-Baltimore-Data-Project-OaEZpkIveZK

Title: MORTGAGE STATUS BY SELECTED MONTHLY OWNER COSTS AS A PERCENTAGE OF HOUSEHOLD INCOME IN THE PAST 12 MONTHS
ID: B25091

Title: GROSS RENT AS A PERCENTAGE OF HOUSEHOLD INCOME IN THE PAST 12 MONTHS
ID: B25070



CitySDK Query Statement for Quarters Information

                        var request = { state: "MD", level: "state", "sublevel": true, variables: [ "B26001_001E" ]  };


                        var callback = function(response) {
                            $('#example2output').empty();
                            $('#example2output').append(JSON.stringify(response, null, 4));
                        };

                        census.APIRequest(request, callback);
                        
Baltimore City value from CitySDK is: 24036. I assume this is the number of people in group quarters in the 2013 ACS.



https://hackpad.com/Hack-for-Diversity-and-Social-Justice-8rSsED0U96b