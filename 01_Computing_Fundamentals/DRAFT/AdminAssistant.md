# SQL DRAFT
<img width="1917" height="791" alt="image" src="https://github.com/user-attachments/assets/786bc11c-86db-4403-9e43-f98634653899" />
<img width="1809" height="958" alt="image" src="https://github.com/user-attachments/assets/7b4228ce-7dcd-4c51-a6ee-a86d9333eecf" />

CREATE TABLE EmployeeRoles (RoleID INT PRIMARY KEY,
RoleName VARCHAR (50),
StaffCount INT,
Tasks VARCHAR(255),
PerformanceNeed VARCHAR(100),
BudgetPerUnit DEC (8,2)
);

-- IMPUTTING DATA

INSERT INTO EmployeeRoles (RoleID,RoleName,StaffCount,Tasks,PerformanceNeed,BudgetPerUnit)
VALUES (1,"Administrative Assistant Workstation",3,"Answering emails, data entry,
 processing invoices, handling correspondence,
  organising meetings","Basic office hardware",950.00),
(2,'Project Manager',2,'Updating and creating project plans,
 creating reports, creating presentations, organising meetings, managing emails,
  communicating plan/project updates',
  'Business hardware workstation with stronger display/workflow setup',1300.00),
(3,'Architect/CAD Designer',5,'CAD drawings, 2D drafting,
3D modelling large design files, multiple monitors, 
and design reviews',
'CAD hardware workstation with dedicated GPU and suitable display',2500.00),
(4,'3D Visualisation Specialist',2,'Rendering, 3D visualisation, large models,
 high-resolution textures, media output, and client visual presentations',
 'High-performance rendering/visulisation hardware workstation',7500.00);
SELECT * FROM EmployeeRoles;
