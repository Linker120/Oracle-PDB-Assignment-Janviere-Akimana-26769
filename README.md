# Oracle-PDB-Assignment-Janviere-Akimana-26769


📘 Overview
This assignment demonstrates the creation and management of Oracle Pluggable Databases (PDBs), including setup, deletion, and monitoring via Enterprise Manager (EM) Express. All tasks were executed successfully and verified with screenshots.
🛠️ Task 1 — Create Pluggable Database
•	PDB Name: ja_pdb_26769
•	Admin User: janviere_plsqlauca_26769
•	Password: auca
Steps Performed:
1.	Created the PDB using SQL commands.
2.	Opened the PDB and verified its status.
3.	Connected as the admin user and created a test table with sample data.
	
•	PDB creation output
![WhatsApp Image 2025-10-06 at 13 57 09_595b0c03](https://github.com/user-attachments/assets/9e9132eb-9419-4177-bdc9-5f67324f2fa7)

•	PDB open verification and Test table insert
	![WhatsApp Image 2025-10-07 at 12 03 05_72f9e66b](https://github.com/user-attachments/assets/12b200af-bc83-4a44-bbfb-49f4428f10c4)

🗑️ Task 2 — Create & Delete PDB
•	PDB Created: ja_to_delete_pdb_26769
•	Deletion Command:
DROP PLUGGABLE DATABASE ja_to_delete_pdb_26769 INCLUDING DATAFILES; 
![WhatsApp Image 2025-10-06 at 14 00 15_73ce1f8a](https://github.com/user-attachments/assets/15b74ab0-e57a-4228-9314-cc9529171845)
![WhatsApp Image 2025-10-06 at 14 02 12_9b7ca8e2](https://github.com/user-attachments/assets/3d93c738-4fa5-41de-b650-1bf5b1cb8506)

📊 Task 3 — Configure Enterprise Manager (EM) Express
•	Access URL: https://localhost:5500/em
•	EM Express was configured to monitor the database and verify connectivity.
![WhatsApp Image 2025-10-06 at 14 58 43_e4383199](https://github.com/user-attachments/assets/7949954c-dc28-4253-b6f8-15327fc53478)

•	EM Express dashboard
![WhatsApp Image 2025-10-06 at 14 37 21_1b15c42f](https://github.com/user-attachments/assets/27de4c2a-5cf3-4673-a0b2-17fe4e75c6fa)

⚠️ Issues & Resolutions
	
NULL	EXEC DBMS_XDB_CONFIG.SETHTTPSPORT(5500);
✅ Conclusion
All tasks were completed successfully, demonstrating proficiency in Oracle PDB creation, deletion, and monitoring setup. The assignment validates the ability to manage container databases and use EM Express for administration.

## Thank you 
---
