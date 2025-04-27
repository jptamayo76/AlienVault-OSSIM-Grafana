# AlienVault-OSSIM-Grafana
## Grafana Dashboard for AlienVault OSSIM 5.8

![image](https://github.com/user-attachments/assets/4585da81-8f7f-4327-8e4a-0f9664e04f94)


![image](https://github.com/user-attachments/assets/5793b0ca-5892-4a48-ac7c-77739580ef41)


![image](https://github.com/user-attachments/assets/8e92e812-bd9c-458b-ac76-39893f3319e1)

![image](https://github.com/user-attachments/assets/396ec263-cb76-4504-ab95-506ce40c048d)



## Installation

### 1. Import Dashboard
  
- Log in to Grafana.

- Go to Dashboards > Import.

- Select the AlienVault-OSSIM-BySensors.json file.


### 2. Select the Data Source

- Confirm that Grafana requests the OSSIM database as input.

- Select a MySQL data source that points to the OSSIM server.

- If it doesn't exist, create one:

  - Type: MySQL

  - Host: OSSIM server IP/DNS

  - Database: alienvault

  - User: User with read permissions

  - Password: (Enter)

  - TLS: Configure as needed (optional).



🔹 3. Verify Dashboard Operation
Verify that all dashboards load data correctly.

Check for data source or SQL errors.

Change the sensor_id or context_id filters and confirm that the graphs update dynamically.

Check that the response times are reasonable. 🔹 4. Save and Make Available
If everything works correctly, click Save Dashboard.

Optional: Assign read-only permissions to the team users.

🔹 5. Additional Notes
The data source is dynamic; you can change it later if you migrate OSSIM or upgrade the database server.

The dashboard supports advanced filters: Sensor, Client (Context), and Period.



###

> [!NOTE]
> DOCUMENTATION WORK IN PROGRESS


