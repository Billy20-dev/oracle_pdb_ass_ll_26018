Individual Assignment II — Oracle Pluggable Databases (PDB) Management

Student Information

Student Name	SHYAKA Billy
Student ID	26018
Assignment	Individual Assignment II 

⸻

1. Overview

This assignment demonstrates practical knowledge of Oracle Multitenant Architecture and Oracle Pluggable Database (PDB) management.

The assignment covers four main tasks:

1. Creating a new Pluggable Database (PDB) and a user inside the PDB.
2. Creating, verifying, and deleting a temporary PDB.
3. Accessing and using Oracle Enterprise Manager (OEM).
4. Documenting the work and providing screenshots as evidence through a public GitHub repository.

All tasks were performed individually using the student’s Oracle environment, and the screenshots included in this repository provide evidence of the completed practical work.

⸻

2. Oracle Environment

The assignment was completed using an Oracle Database environment with Oracle Pluggable Database functionality.

Main PDB

PDB Name:

Bi_pdb_26018

User Created Inside the PDB

Username:

Billy_plsqlauca_26018

Temporary PDB

Temporary PDB Name:

Bi_to_delete_pdb_26018

The temporary PDB was created for demonstration purposes and subsequently deleted as required by the assignment.

⸻

3. Task 1 — Create a New Pluggable Database

The first task involved creating a new Pluggable Database using the required naming convention.

The PDB created for this assignment is:

Bi_pdb_26018

After creating the PDB, its state was verified to ensure that it was open and available for use.

A dedicated user was also created inside the PDB:

Billy_plsqlauca_26018

This user is intended to be used for future database development and PL/SQL coursework.

Evidence

The following screenshots provide evidence for Task 1:

* PDB creation
* PDB open state
* User creation inside the PDB

Screenshots are available in:

screenshots/pdb_creation/

⸻

4. Task 2 — Create and Delete a PDB

The second task involved creating a temporary PDB using the required naming convention:

Bi_to_delete_pdb_26018

The temporary PDB was first created and verified to ensure that it existed successfully.

After verification, the temporary PDB was deleted completely. A final verification was performed to confirm that the temporary PDB no longer existed.

Evidence

The following evidence is included:

* Temporary PDB creation
* Verification that the PDB existed
* Temporary PDB deletion
* Confirmation that the PDB was deleted

Screenshots are available in:

screenshots/pdb_deletion/

⸻

5. Task 3 — Oracle Enterprise Manager (OEM)

Oracle Enterprise Manager was accessed to monitor and manage the Oracle database environment.

The OEM dashboard was checked to verify that the Oracle environment was accessible and that the database/PDB environment was reflected in the dashboard.

Evidence

A screenshot of the OEM dashboard is provided in:

screenshots/oem_dashboard/

⸻

6. Challenges Faced

During the assignment, challenges encountered included:

* Setting up and accessing the Oracle database environment.
* Working with Oracle Pluggable Databases and their states.
* Ensuring that the required naming conventions were followed correctly.
* Verifying the creation and deletion of the temporary PDB.
* Accessing Oracle Enterprise Manager and locating the required dashboard information.

Any additional issues encountered during execution were resolved by referring to the Oracle environment, course instructions, and appropriate documentation.

Note: Update this section to describe only the challenges you actually experienced.

⸻

7. Repository Structure

The repository is organized as follows:

oracle_pdb_ass_II_26018_shyaka/
│
├── README.md
│
└── screenshots/
    │
    ├── pdb_creation/
    │   ├── pdb_creation_01.png
    │   ├── pdb_open_02.png
    │   └── user_created_03.png
    │
    ├── pdb_deletion/
    │   ├── temporary_pdb_created_04.png
    │   ├── temporary_pdb_exists_05.png
    │   ├── temporary_pdb_deleted_06.png
    │   └── temporary_pdb_confirmed_deleted_07.png
    │
    └── oem_dashboard/
        └── oem_dashboard_08.png

⸻

8. Integrity Statement

I confirm that this assignment represents my own individual work. The Oracle database tasks were performed by me, and the screenshots and documentation included in this repository correspond to my own Oracle environment and work.

I have not intentionally copied commands, screenshots, repositories, or other submitted work from classmates.


PDB Name Created:
Bi_pdb_26018

Issues Encountered:
[Yes/No]

⸻

10. Conclusion

This assignment provided practical experience with Oracle Multitenant Architecture and Pluggable Database management. The completed tasks demonstrate the creation and management of PDBs, user creation inside a PDB, PDB deletion, Oracle Enterprise Manager usage, and professional technical documentation using GitHub.
