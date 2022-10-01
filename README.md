# apex_ir_query
## Summary
Get the WHERE clause from an Oracle Apex Interactive Report. Originally created on Apex 5.0.1 and is no longer maintained, so no guarantees that it will work with newer versions.

## Details
This contains an Oracle PL/SQL package with a single public function which calculates the SQL WHERE clause for the specified Oracle Application Express Interactive Report.  The idea is that you could use this WHERE clause to get the same records displayed on the IR, but format it however you want.

I wrote this back in 2009, but it still seems to work in Apex 19.2. *Caveat emptor*, your mileage may vary, objects in the rear view mirror may appear closer than they are, etc.
