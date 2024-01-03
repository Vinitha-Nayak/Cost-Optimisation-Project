1.Launch a ec2- instance
![image](https://github.com/Vinitha-Nayak/Cost-Optimisation-Project/assets/151067108/d24fe6bd-f8db-4e19-86e9-a935137c28ed)

2.Volume also gets created with ec2-instance
![image](https://github.com/Vinitha-Nayak/Cost-Optimisation-Project/assets/151067108/30c8d6a6-7a17-45fd-b408-1ceaaf0f6c1d)

3.Create a snapshot for that volume id
![image](https://github.com/Vinitha-Nayak/Cost-Optimisation-Project/assets/151067108/d6537e31-9e58-4637-b36a-c828b1be54e9)

4.Create a Lambda function
![image](https://github.com/Vinitha-Nayak/Cost-Optimisation-Project/assets/151067108/271dc529-7735-4873-ac88-8a3304df61dd)

5.Paste the code in Code section
![image](https://github.com/Vinitha-Nayak/Cost-Optimisation-Project/assets/151067108/3a5d0139-da6d-4c1d-ae08-eb22f2b34605)

6. Click on Test to create a test event and save
![image](https://github.com/Vinitha-Nayak/Cost-Optimisation-Project/assets/151067108/8fcca562-05f6-4cb0-a184-c7c5e9b4aa41)

7.Create policy to add permission 
![image](https://github.com/Vinitha-Nayak/Cost-Optimisation-Project/assets/151067108/32c74047-b967-4f68-b3c9-cfadf65e7998)

8.permissions to add to the policy
  1 describe snapshots
  2 delete snapshot
  3 describe instances
  4 describe volumes

9.Terminate the ec2-insance and Test the code it will delete the stale snappshot.
