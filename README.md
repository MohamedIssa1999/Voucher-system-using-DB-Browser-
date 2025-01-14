###  The Closet Voucher System SQL Database

This repository contains the SQL database and management system for the Closet Voucher System, which tracks voucher registrations and transactions for recipients of a voucher program.

#### Key Features:
1. **Database Structure**:
   - The database is organized into tables for registering voucher recipients, tracking voucher checkouts, and generating various metrics.
   - The database is managed using DB Browser for SQLite, with functionality for adding, modifying, and deleting records, as well as executing SQL queries.

2. **User Instructions**:
   - **Registering a Voucher Recipient**: Allows users to add voucher recipient information, such as personal details and voucher amounts.
   - **Voucher Check-Outs**: Users can record voucher check-outs, tracking transaction details including the amount spent and remaining balance.
   - **End-of-Day Metrics**: Provides a set of metrics (such as voucher usage and daily totals) to monitor program progress and detect duplicate registrations or fraudulent activity.

3. **Admin Functions**:
   - Only administrators can modify the database structure, including adding new tables and metrics, or executing SQL code directly.
   - Admins should also back up the database regularly to avoid data loss when making changes.

4. **SQL Integration**:
   - Admins can extend the database by adding new tables or metrics using SQL scripts in the "Execute SQL" tab.
   - Various SQL tips and instructions are available via external resources (e.g., W3 Schools).

5. **Data Entry and Management**:
   - Data entry for voucher recipients and transactions is handled via the "Browse Data" tab in DB Browser.
   - The system also tracks and calculates voucher amounts, dependents, and organization referrals.

6. **Metrics and Reports**:
   - **Duplicate Check**: Identifies potential fraudulent entries.
   - **Daily Totals**: Tracks daily voucher expenditures.
   - **Zip Code Distribution and Other Metrics**: Helps visualize voucher usage by location and organization.

7. **Backup and Save**:
   - Users should save their work regularly using the "Save All" option in DB Browser to avoid creating unnecessary copies of the database.

This system provides essential functionality for managing and tracking voucher distribution, and it includes both user-facing features for data entry and administrative features for database management and report generation.
