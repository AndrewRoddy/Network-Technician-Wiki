---
{"dg-publish":true,"permalink":"/pcr/teams-phone-in-pcr/"}
---

1. Create a New `Service Order`, name as normal
2. Add new `action`, service type in Teams Phone
	1. You should be able to type just "Teams" and it will auto complete
3. `Service ID` will be the full phone number `330-672-XXXX`
4. `Reference` is the name of the phone. Can be either a person's name or the name of a department
5. `Location` can either be the building and the room the phone is for or just `Kent > DPH` (Deployed phone)
6. Service Host is `MS-TEAMS-VGW`
	1. As with service type it should auto complete from just "Teams"
7. Under the Service Details tab (Left most tab) select the `Ratings Group` as `Kent`
8. Save New
9. Go to the `Equipment` tab and click the add button
	1. In the `Equipment Catalog` field type Teams and select the correct model of phone
		1. Will either be `455` or `435`
	2. In the `Equipment` field copy paste the MAC address of the phone.
		1. If it does not auto fill the rest of the fields the phone may not be in PCR yet, if so either do that or get someone who knows how to do it for you. (Prob Madi)
	3. Save New And Close
10. Under the `Charges` tab, change the recurring $19 charge (Phone Line) description to be the same as the `Reference` field
11. Add a new charge
	1. Type Teams to bring up the models of teams phones and select the correct one
	2. The description will be either `TEAMS-C435HD-R` or `TEAMS-C455HD-DBW`
	3. Save and Close the action
12. Done
