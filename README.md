jquery-jvectormap-world-mill-en.js
==================================

This is an updated maps data file for Kirill Lebedev's great jVectorMap
solution. The updates regard some country code updates and the purpose
is to eliminate the temporary country codes (eg. '_0' and '2') that the
jVectorMap returnes for certain countries with unclear status. So if you
are looking for a solution that returns ISO 3166-1 valid information 
please review the updates! 

Updated country codes:
 - Easter Sahara now has an ISO 3166-1 Alpha2 code of "EH" so updated it
 - Kosovo is now an independent state and ISO has not assigned a code
for it. While EU countries use the 'XK' temporary code it is updated
 - Somaliland is not a separate state bit a self-declared independent
territory of Somalia so its code should be 'SO' (ISO 3166-1:SO for
Somalia)
 - The status of Northern Cyprus is not clear at the moment and as like
in the case of Somaliland the 'CY' (ISO 3166-1:CY for Cyprus) should be
used.
 - 
