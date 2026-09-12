<!--
Arash Keshtgar

Power Platform & Azure developer — Oakville, Ontario 🇨🇦

I build internal business applications end to end: the data model and stored procedures in SQL, the app and workflows on Power Platform, and the services that sit behind them on Azure. My interest is in the part most low-code projects skip — putting the rules where they can't be bypassed, and being able to explain why every design decision was made.

🔹 Featured project
SmartLedgerAI — expense management with AI anomaly detection

An expense system on Power Platform paired with a .NET Azure Function that scores every expense against its own category-and-month baseline and asks Azure OpenAI to explain the ones that stand out.

▶ 5-minute demo

Power Apps — expense entry with validation, approval workflow, accounting-period close, tax ledger
Power Automate — CSV export and approval routing
Azure Functions (.NET 8, isolated worker) — anomaly scoring API with correlation IDs and separate 400 / 500 handling
Azure OpenAI — one actionable sentence per flagged expense, called only when the risk level warrants it
Azure SQL — 7 views, 3 stored procedures, and a trigger that makes SQL Server itself refuse writes to a closed accounting period

Some decisions the README walks through: sample vs. population standard deviation, guarding a divide where STDEV returns NULL rather than zero, and why the API takes an expense ID and computes the Z-Score itself instead of trusting one from the caller.

🔹 Other work
Project	Stack	What it is
HIS-App	C#	Health information system desktop application
wUtility1	C#, WinForms	Windows desktop utility
mern-animation-project	MongoDB, Express, React, Node	Full-stack MERN application
🔹 Tech

Low-code Power Apps (Canvas) · Power Automate · Dataverse Cloud Azure Functions · Azure OpenAI · Azure SQL Database Languages C# / .NET 8 · T-SQL · JavaScript Data Stored procedures · views · window functions · triggers · transactions Tools Visual Studio · Git · Postman · SSMS

🔹 Currently

Working toward a Developer Analyst role on Power Platform and Azure. Building portfolio projects that are complete rather than demo-shaped — deployed, documented, and with the reasoning written down.

📫 LinkedIn · akeshtgar@gmail.com
-->
