# PROJECT NAME

Investigating Unusual Logins, Assembled Employee Data

## Objective

Gathering Employee and Device Data using SQL. 

### Skills Learned

- Advanced understanding of SQL
- Data Manegement 

### Tools Used

- SQL

## Steps

Retrieving employee device data

![image](https://github.com/user-attachments/assets/2ae4bbb9-1d2e-4eb1-90c9-2d24e7f6c483)

Displaying only the device_id, operating_system, and OS_patch_date columns. 

![image](https://github.com/user-attachments/assets/b59bb997-e786-4585-851f-43929eb7a422)

Displaying login attempts by country to look for unusual activity. 

![image](https://github.com/user-attachments/assets/e1415690-9bc2-436e-b604-8dfefe6a2dab)

Investigating an incident. Need to display all login attempts in order of log in date and time.

![image](https://github.com/user-attachments/assets/fd03a68a-3f8f-42ed-942f-44041bbfc51c)

Displaying all of the employees in the finance department.

![image](https://github.com/user-attachments/assets/f37b566c-fffa-4b42-a4f0-0350de9c6207)

Investigating a breach in the South-109 office. Need to retrieve Device ID of the lone user in that office. 

![image](https://github.com/user-attachments/assets/02ae368a-0c12-4c36-93f7-01593b384fa9)

To be safe, I need to check all devices in the South Wing. Displaying all devices in the South wing.

![image](https://github.com/user-attachments/assets/34d9c0c0-d26a-4ea2-bbb1-0d522a794298)

Filtering login attempts after May 9, 2022

![image](https://github.com/user-attachments/assets/c0eec4f2-8ba5-40f3-ab2d-2e4fa935ecfc)

Filtering login attempts before 7:00

![image](https://github.com/user-attachments/assets/f752eee9-cf95-4c6d-b12e-dcf85667068a)

Retrieving after hours failed login attempts

![image](https://github.com/user-attachments/assets/8dc892e0-7756-44e4-972f-6dffcd771966)

Retrieving login attempts outside of Mexico. In the table Mexico is sometimes listed as “Mex”. Must filter for entries that start with “Mex”

![image](https://github.com/user-attachments/assets/d4424972-14fa-4256-8d08-423f3c234c32)

Looking for all employees outside of the IT Department

![image](https://github.com/user-attachments/assets/34ca7de8-4c60-40bd-96fb-a5d3632441c5)

Retrieving information on all employees that made login attempts. Performing an Inner Join
on the employees and log_in_attempts tables linking them on the common username column

![image](https://github.com/user-attachments/assets/4c5dee19-845f-4f91-9cdc-e5369ec35a75)

End of Lab
