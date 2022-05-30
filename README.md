# psi-rental-database
University Oracle PL/SQL database project with sample data.


After running script database will be created and sample data will be inserted.
Procedures and views should be recompiled.

Additional CAR_TYPES and VAT_RATES should be inserted first.

ADD_USER => inserts data into USER, ADDRESSES and TOWNS tables.\
ADD_DEPARTMENTS => inserts data into DEPARTMENTS, ADDRESSES and TOWNS tables.\
ADD_CAR => inserts data into CARS and MANUFACTURERS tables.\
ADD_RENT => inserts full-detailed row into RENTS table.\
ADD_RENT_START => inserts row into RENTS table with RETURN_DATE = null and MILEAGE_END = null.\
ADD_RENT_RETURN => updates row in RENTS table - sets RETURN_DATE and MILEAGE_END.\
ADD_INVOICE => inserts row into INVOICES for selected ID_RENT.\

Triggers contains input data validation for each table.
