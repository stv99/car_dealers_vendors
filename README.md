
Car Dealership Database Project

This project is a personal project while learning SSMS. It’s a work in progress, aimed at building a practical database for vendors collaborating with car dealerships. 

The heart of this database is the VEHICLES table, representing the product we’re dealing with. Each service is always associated with a unique car. The cars table includes fields such as VIN (unique to each car), stock number, make, model, year, color, trim, type (new/used), and rooftop_id (unique to each dealership).
When dealing with car images, a secondary table is required to store these images (or the paths to these images). This table includes fields such as VIN, upload date, photo order, image (or image path), and employee_id.
Supporting the cars table is the rooftop table. Each car is always associated with a dealership. The rooftop table includes fields such as rooftop_id, dealership name, address, city, zip, state, work area, and contact_id.
From the aforementioned contact_id, a contacts table is necessary to store all the data from our contacts at all the dealerships. This table includes fields such as contact_id, name, last name, positions, phone, email, and dealership name.
Additionally, an employees table is required. This table includes fields such as user id, name, last name, address, city, zip, state, work area, email, and phone.
To assist in organizing employee routes and schedules, a routes table has been added. This table includes fields such as route name, user id, user, customer id, dealership name, and schedule.
The next phase of this project involves the development of a new table to facilitate billing services. Coming soon…
This project is all about learning SSMS and the practical application of the same in a real-world scenario. Contributions and suggestions are always welcome!

