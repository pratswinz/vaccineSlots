# Find Vaccine Slot

Find vaccine slots by district or pincode.

## Working
Script will keep running at specified intervals and start making loud sound if any slots are available.

## Installation

Copy content from index.html and paste in any file with html extension and just open in browser


## How to Use 

Change the config on top of file based on below comments made besides the values

```
searchByDistrict: false,   //true if want to search by district ID,false if search by pincode
districtId: 663,//district ID to be assigned
searchByPinCode: true,//true if want to search by pincode,false if search by district ID
pinCode: 560100, //search area pincode
checkTimeInterval: 15,//unit in seconds <integer>
minAgeLimit: 18,   // 18,45 keep any of these values for age in years
minAvailableCapacity: 1,//vaccine available capacity
autoDatePick:true, //if want to search by todays date and future dates,false if providing any custom date
customDate:"31-05-2021"//format in DD-MM-YYYY in <string>
```

Please make sure to update tests as appropriate.

## Start/Stop checking slots
As soon as the page opens the script starts running.

```
To STOP - Just click on stop checking button.
To START again - Click on start checking
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
