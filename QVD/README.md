1. How to load a .mdb file in Qlikview.<br>
Database select OLE DB then 
connect select microsoft jet 
then click connection browse data source click test connection then ok
select force 32 bit
Then click Select option there choose tables check preceding load and click ok and load  script tab.

2. How to generate a .qvd file and load from it (load command).<br>
STORE table_name INTO location;
store Shippers into C:\Users\praja\OneDrive\Documents\Shippers.qvd; 

In script select table file browse needed qvd.
LOAD CompanyName as CP_Name, 
     ShipperID
FROM
[C:\Users\praja\OneDrive\Documents\Shippers.qvd]
(qvd);
