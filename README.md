# PAYSLIP-GENERATION-SYSTEM
### **Application Overview:**
# OBJECTIVE:
The Objective of Pay Slip Generation System(PSG System) is to store the details of the employees of an organization and generate their pay slips. The organization employs two types of employees ,viz.., permanent and contractual.

### Permanent Employees:
The permanent employees are entitled to dearness allowance(DA),house rent allowance(HRA), medical allowance(MA), provident fund deduction(PF), professional tax(PTax), and income tax(ITax) on their basic salary.

### Contractual Employees:
The contractual employees are entitled to a lump sum gross salary with professional and income tax deductions. The PSG systems stores and retrieves the details of both types of employees, and also computes and generates their monthly pay slips. The system is capable of handling varying DA,HRA rates along with changes to the medical allowance and professional tax(IF ANY).

# CLASS DIAGRAM:
The class diagram for the PSG system application is shown below:

![Screenshot 2024-06-30 145123](https://github.com/AnubhavSaxena3/Payslip-generator-system/assets/113455210/00a9c6dd-4cee-472b-be87-b9bd4c31fdde)

### 3 lists the various members of the employee class:

**employee Class Members:**

![Screenshot 2024-06-30 154036](https://github.com/AnubhavSaxena3/Payslip-generator-system/assets/113455210/bf0233a9-7235-4447-bd47-7b222d014ecb)

**permanent_employee Class Members:**

![Screenshot 2024-06-30 154431](https://github.com/AnubhavSaxena3/Payslip-generator-system/assets/113455210/9764a7cd-2a76-4c36-adfe-e8c3a4da4a25)

**contractual_employee Class Members:**

![Screenshot 2024-06-30 154726](https://github.com/AnubhavSaxena3/Payslip-generator-system/assets/113455210/78160a6e-2bfc-4e6a-9c97-cfef723e154c)

# Program Logic
**Salary Calculation for permanent employee**

The gross salary of every permanent employee has the following components:
1. Basic
2. Dearness allowness : Calculated as a pre-set percentage of basic.
3. House rent allowance: Calculated as a pre-set percentage of basic
4. Medical Allowance: A fixed pre-set lump sum amount

   The net salary is computed by subtracting from the gross the following:
   
- Provident fund: Calculated as 12% of (Basic + DA)
- Professional tax: Fixed amount
- Income tax:Fixed amount(The tax computations are usually finalized at the end of each financial year)

**Salary Calculation for contractual employee**
Every contractual employee is entitled to recieve a fixed gross salary.

   The net salary is computed by subtracting from the gross the following:
   
   -Professional tax: Fixed amount
   -Income tax:Fixed amount(The tax computations are usually finalized at the end of each financial year)




