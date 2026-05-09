# NET731-Week4-20240476-
This Repository is for my Week 4 NET practical. 

Tristan Piek
20240476


## Q1-Naming Convention

The Format I chose will be lastname.firstname@domain.onmicrosoft.com


### Why I chose this format

By using a consistent name format for all user accounts allows for a much
smoother identification proccess. Thus using 
lastname.firstname@domain.onmicrosoft.com
creates a proffesional business standard and makes it easier to remeber.


## Q2-Planning Groups and Departments

For the Deparment I created 3 security groups that will work within the
orginizations business standard, these are common departmenst almost all
orginizations use. This includes - Development, Operations and Finance. One per
Department. In this instance Security Groups are used and best suited.



### Why I chose this format

When looking at the two choices between Security and Microsoft 365, security is 
the best option for this specific instance. Security groups allow the
orginization to group users by department where the Microsoft 365 does not allow
this feature, aswell as access controll where the administrator can assign
privilages and roles to many users at once, mass assignment.


## Q3-Principle of Least Privilege

PoLP - Principle of Least Privilege is a security rule taht limits user access
rights and only allows users the lowest level of access to resources depending
on their roles. Users should have assigned roles and access to ensure
departments don't interfere with one another. This increases data security and
reduces the risk of accidental data leakage and resource changes.


## Q4-Membership Type

I chose assigned membership because it allows direct admini control over group membership. This is ideal for smaller
instances when membership changes can be made manually. Dynamic membership would be better suited for large companies that
want the ability to automatically group employees by department or job title.


## Q5-Verifiction Step

To confirm the memberships, each security group was opened in Entra ID, then I went to the Members area. The assignment of
users to their intended departmental groups can be validated by this. Please refer to the correct-group-assignment
screenshot.


## Q6-Role Justification

The Development group was given the Contributor position because developers need the ability to manage resources. Operations
and Finance were given the Reader role to only have insight into resources, without being able to change any data. This
promotes secure  access for all groups.


## Q7 — Scope Matters

Roles with more rights make management easier, but they also increase the risk of security breaches. While resource group
have limited scopes, they increase security but they don't increase management. Thus assigning the roles within the
subscription made administration easier and guarantees data and resources can always be accessed.


## Q8 — Custom vs Built-In Roles

Custom Roles are created when organisations require privileges that are not already covered by already existing roles, thus
they develop these roles to suit those requirements. If a real organization wants to limit unnecessary access while still
keeping strict security measures, it can develop custom roles.


