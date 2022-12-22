Getting Started
=====

.. _installation:

Key Features
------------

- Well structured & Designed solution.
- Clean code.
- EntityFrameworkCore Code First.
- Seperated Business Patterns.
- Identity Area for User account management.
- External Authentication: Google, Micrsoft, Twitter, Facebook.
- Admin Role to manage Products.
- Clean Invoice Pdf generation.
- Sending Invoice by Email.
- Stripe Gateway Checkout.
- Session & Persistent Shopping Card tracked by User.
- Generic Repository Pattern.
- appsettingsjson Configuration Helper.
- Serilog Middleware ToFile Implementation.
- Exception middleware to capture all unhandled Exceptions.
- Full commented source codes.
- Jquery based prototype pattern.
- Jquery Ajax helper.

Environment
----------------

To build the Solution you need to have:
			- Visual Studio 2022
			- Microsoft SQL Server Express (2014 or later)
			- Micrsoft .NET 6 SDK

Settings
------------


Before building the solution, make sure to have the correct parameters on the appsettings.json.

Table to explain all paramters
   
Seed Data
------------


- identitydata.json: This file contains default data to seed to the database for identity memebership.

			* Administrator Role : The website Administrator can manage products (Add/Update/Delete).
			* User Role : The User can buy products and do checkout and payment.
			* Default Administrator: admin@domain.com (password: $Admin123).
			* Default User: paul@domain.com (password: $Paul123).
- storedata.json: This file contains default products list with their prices to seed to database.
   
Build & Run
------------

After updating settings and default datat files, you can build and Run the solution.

The Project use EntityFrmaeworkCore Code First, so the database will be created automatically on project Startup.
   
