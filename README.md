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
<img width="1919" height="1133" alt="Screenshot 2025-08-22 142302" src="https://github.com/user-attachments/assets/e2194120-9dcc-4b90-b12a-2b663a8bbbf1" />
<img width="1919" height="1137" alt="Screenshot 2025-08-22 142433" src="https://github.com/user-attachments/assets/81452f90-015f-4499-8d44-16b42ab6421f" />
<img width="1919" height="1133" alt="Screenshot 2025-08-22 142504" src="https://github.com/user-attachments/assets/921c383d-d338-4dc1-8462-482d58b8ecb5" />
<img width="1919" height="1135" alt="Screenshot 2025-08-22 142609" src="https://github.com/user-attachments/assets/f622e0f6-df85-4d24-8836-07a4df2def4e" />
<img width="1919" height="1133" alt="Screenshot 2025-08-22 142655" src="https://github.com/user-attachments/assets/19ba8946-8307-4983-bff9-2eeede50d57a" />
<img width="1919" height="1137" alt="Screenshot 2025-08-22 142710" src="https://github.com/user-attachments/assets/57c609ac-730e-4196-bb01-a820856f3395" />
<img width="1919" height="1134" alt="Screenshot 2025-08-22 142231" src="https://github.com/user-attachments/assets/0dbcc9bf-93d1-4569-83cc-aaff7df99d94" />
