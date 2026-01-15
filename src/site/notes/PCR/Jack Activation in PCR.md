---
{"dg-publish":true,"permalink":"/pcr/jack-activation-in-pcr/"}
---


# Jack Activation
1. Main > Inventory > Equipment
2. Add
3. `Equipment Catalog` Magnifying Glass
4. Search `Jack`
5. Double click `Jack`
6. `Status` : Installed
	1. Needs to be done first
7. Put the location in `Location`
8. `Equipment ID` : Put in Jack ID
	1. ex : `HAR-01-03-037B`
9. Press `Save New`
10. Press `Port/Pins/Lens`
11. Press `Add`
12. `Port/Pins/Lens` : 1
13. `Status` : Spare
14. `Side` : Front
15. Press `Save New`
16. Press `Save and Close`
17. Press `Save and Close` (again)
18. Done
19. Open PCR
20. Go to service desk
21. Service Orders
22. Press add in the top right
23. Write Ticket Information
	1. Copy Ticket Number : `TicketNumber`(only the number)
	2. Description : `FTicketNumber`
	3. Copy Ticket Title
	4. `FTicketNumber - TicketTitle`
	5. Owner - Department : Billing Index
	6. Requestor : `Their Name Duh`
	7. Press `Save New`
24. 🟡Start One Jack Activation
25. Press `Add` ( inside the service order )
26. Add Service Catalog
	1. Press the Magnifying Glass Icon
	2. Double Click (Service : `Data`)
27. Add Data Name/ID
	1. Press the blue dots with gray lines box
	2. Double click on any number (Service ID)
28. Add the Reference
	1. Copy the Jack ID 
		1. On the right of the `>>` (sometimes (no port number))
	2. Paste it in the reference
29. Add the location
	1. Copy the building and room number
	2. Paste it in
30. Press Save New
31. Check off the box left of the `Network Activation`
32. Press `Save Without SDC`
33. Press Cabling
34. Press Add
35. Add `Origination`
	1. Copy the Switch ID
		1. ex : `HAR_01_88_2_3`
	2. Paste in Origination Equipment
36. Add `Origination Port/Pin/Len`
	1. Cisco starts with a `g`
	2. Extra number on the end means `gNUMBER` 
	3. if no number means its `g1`
	4. `gNUMBER/0/PORTNUMBER`
37. Add `Destination Equipment`
	1. Copy Jack ID
	2. Search 
	3. Paste jack ID
	4. Double Click on it
	5. If it is not there you need to [[Jack Create in PCR\|create a new jack]]
	6. Repeat above.
38. Add `Destination Port/Pin/Len`
	1. Input 1
39. Press `Save New` 
40. Press `Save and Close`
41. Add Charges
	1. Go to `Charges`
	2. Double Click on Monthly Charge ($19)
		1. Clear the description
		2. `Jack {JACKID} in room {BUILDING} {ROOMNUMBER}`
		3. ex : `Jack HAR-01-03-037A in room HAR 310`
		4. Copy the description
		5. Save and Close
	3. Double Click on Activation Fee ($85)
		1. Clear the description
		2. Type in `F{TICKETNUMBER} {TICKETNAME} - ` then press paste
		3. `F{TICKETNUMBER} {TICKETNAME} - Jack {JACKID} in room {BUILDING} {ROOMNUMBER}`
			1. ex : `F1304152 MSC->HAR : Network Jack Move - Jack HAR-01-03-037A in room HAR 310`
		4. Save and Close
	4. Save and Close
42. For another Jack Activation return back to🟡
43. Status : `Complete`
44. Press `Save and Close`
45. Press `Complete Now`
46. Right click on `SD Number` from ur thing
	1. ex : `SO202606080`
47. Copy to Clipboard
48. In Fresh Service
49. In Closure Comments 
50. Type "PCR Completed and Finalized"
51. In `Ticket ID Reference`
52. Paste from Clipboard
53. Change Status to `Resolved`
