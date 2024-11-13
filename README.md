# In-House Talent Management System / Internal Resource Management System (IRMS)
# Overview
<!--Develop a comprehensive web application that enables management to efficiently identify and allocate internal resources based on skill sets for both new and existing projects. This system aims to reduce the need for external hiring and promote the recognition and utilization of internal talent.-->
The **In-House Talent Management System / Internal Resource Management System (IRMS)** is to streamline the process of identifying, allocating, and managing resources within the organization based on their skill sets. This system aims to ensure that management can efficiently match the right employees to the right projects, and reduce the need for external hiring and promote the recognition and utilization of internal talent.

By implementing this system, the company will achieve the following goals:

**Optimized Resource Utilization:**

* Efficiently allocate internal resources to new and existing projects based on their skills and availability.
* Reduce dependency on external hires, whether permanent or contract-based, by making better use of existing employees.

**Enhanced Skill Visibility and Recognition:**

* Provide a platform for employees to showcase their skills and talents, increasing their visibility within the organization.
* Recognize and leverage the diverse skill sets of employees across different teams and tribes.

**Improved Project Management**

* Facilitate better project planning and execution by ensuring that projects are staffed with the right mix of skills and experience.
* Allow for dynamic reallocation of resources as project needs evolve.

**Cost Efficiency and Budget Management:**

* Track and manage the costs associated with resource allocation to specific projects and teams.
* Allocate budgets more accurately and transparently based on actual resource utilization.

**Data-Driven Insights:**

* Generate detailed reports and analytics on resource allocation, skill gaps, and project performance.
* Use insights to inform training and development programs, addressing skill gaps and preparing employees for future projects.

**Seamless Integration and Security:**

* **Integrate with existing HR and project management systems** to provide a cohesive and unified experience.
* Ensure that all data is handled securely, protecting sensitive information and maintaining compliance with relevant regulations.


This system, built using the latest .NET LTS REST API, Angular, and PostgreSQL, will provide a robust and scalable solution to manage the organization's talent pool effectively, enhancing overall productivity and employee satisfaction.

# Functional Requirements

**1. User Management**

* The system shall allow the creation of user profiles with details such as name, department, and contact information.
* The system shall allow users to update their profile information.
* The system shall allow users to be associated with multiple skills and their proficiency levels.

**2. Skill Management**

* The system shall allow the addition, update, and deletion of skills.
* The system shall allow users to be associated with skills and specify their proficiency levels.

**3. Project Management**

* The system shall allow the creation of projects with details such as project name, description, and required skills.
* The system shall allow updating project information.
* The system shall allow deletion of projects.

**4. Skill Matching and Resource Allocation**

* The system shall allow project managers to input the required skills and proficiency levels for a project.
* The system shall provide a list of users whose skills match the requirements of a project.
* The system shall rank users based on their proficiency levels in the required skills.

**5. Authentication and Authorization**

* The system shall provide user authentication using JWT tokens.
* The system shall restrict access to certain functionalities based on user roles (e.g., admin, project manager, regular user).

**6. Notifications**

* The system shall notify users when they are matched to a new project.
