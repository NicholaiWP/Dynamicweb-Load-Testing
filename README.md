# Dynamicweb-Load-Testing

The solution contains code to populate certain areas of a Dynamicweb solution such as;
- Populating the Ecommerce-module (area) with product groups and products
- Populating the Users-module (area) with user groups and nested user groups, populated with users in them

# Generating Data
You generate data by cloning this repository. Then build the solution and add the generated DLL to your BIN folder. Next you navigate to the solution's backend and go to your list of scheduled tasks, create a scheduled task that uses the desired method from the DLL assembly and then execute the scheduled task you just created.
