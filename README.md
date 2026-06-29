# Software Engineering Lab Portfolio

This repository contains a collection of practical lab assignments covering **Oracle Database Administration** and **Java GUI Application Development**.

---

## 1. Oracle Database Administration Tasks

### Task 1: Main PDB Connection & Listener Setup
* Established connection to the pluggable database `ib_pdb_30842_2025` via the local network service.
* Successfully resolved connection errors by initializing the Oracle TNS Listener with administrative roles.

### Task 2: Temporary PDB Life Cycle Management
* Switched session context to `CDB$ROOT` to perform core administration.
* Created a temporary pluggable database `ib_to_delete_pdb_30842_2025` using the system seed path.
* Opened, closed, and permanently removed (`DROPPED`) the temporary database along with its underlying datafiles to verify proper resource cleanup.

### Task 3: Enterprise Manager Configuration
* Queried the database configuration to locate the active web administration port.
* **Extracted HTTPS Port:** `5500`
* **Local CDB URL:** `https://localhost:5500/em`
* **Local PDB URL:** `https://localhost:5500/em/ib_pdb_30842_2025`

---

## 2. Java GUI Development: Calculator & Tax System

The second part of the portfolio demonstrates building a fully functional desktop application using **Java Swing/AWT** inside NetBeans.

### Key Features:
* **Graphical User Interface (GUI):** A clean layout featuring an interactive numerical pad and operation buttons.
* **Tax Calculation Logic:** Implemented event handling where user input triggers dynamic mathematical calculations (e.g., computing a fixed `Tax Rate = 0.2` or 20%).
* **Pop-up Dialogs:** Integrated `JOptionPane` message dialogs to output computation results dynamically to the user.

---

## 📂 Project Structure & Evidence

Make sure the following source images from the gallery are included in your repository root to display properly inside this file:

* `user_login.png` -> Evidence for the Oracle connection success.
* `database_lifecycle.png` -> Evidence for creating/dropping the pluggable database.
* `oem_port.png` -> Evidence for the Oracle port query.
* `calculator_gui.png` -> Screenshot of the Java calculator design view.
* `tax_output.png` -> Screenshot of the "Tax Rate = 0.2" dialog box popup.