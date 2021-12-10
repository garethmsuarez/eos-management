# eos-management

Welcome to the EOS Management project!

The purpose of this project is to build out a blazor server based app to manage aspects of the eos system, specifically issues and rocks, to better facilitate weekly review meetings.

This project is built on .net core 6.0, with a sqlLite database for data storage.  The database is not included in the repository, and must be built by EF migrations.  

To build the latest version of the database, run the terminal command "dotnet ef database update" from the main project directory.
