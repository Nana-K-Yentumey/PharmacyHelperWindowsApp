# PharmacyApp

A simple Windows Forms application for managing a pharmacy's inventory and sales using SQL Server stored procedures.

## Quick Start

1. **Run the database script**
   - Open SQL Server Management Studio (SSMS).
   - Execute `Database/PharmacyDB.sql` to create `PharmacyDB`, tables, and stored procedures.

2. **Open the project**
   - Open `PharmacyApp.sln` in Visual Studio (or open `PharmacyApp/PharmacyApp.csproj` directly).
   - Ensure your machine has .NET Framework 4.7.2 (or adjust the `TargetFramework` in the `.csproj`).

3. **Update the connection string**
   - In `PharmacyApp/App.config`, set `Data Source` to your SQL Server instance (e.g., `.\SQLEXPRESS` or `(localdb)\MSSQLLocalDB`).

4. **Run**
   - Build and run. Use the UI to add medicines, search, update stock, record sales, and view all.

## Notes
- All DB actions use stored procedures (`AddMedicine`, `SearchMedicine`, `UpdateStock`, `RecordSale`, `GetAllMedicines`).
- Data is shown in the grid via `SqlDataReader` -> `DataTable` -> `DataGridView`.
- Friendly error messages are displayed using `MessageBox`."# PharmacyHelperWindowsApp" 
