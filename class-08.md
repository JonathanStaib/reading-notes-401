# Class 08 Reading Notes

## 5 Steps of RBAC

- What is Role Based Access Control (RBAC) and why do we care?

  Role based access control is when you give users different permission based on their role and this allows them to use different features.

- Describe a Role/Permission heirarchy that you might implement using RBAC.

  You could give different roles such as admin, editor, writer, viewer.

- What approach might you take to implement RBAC?

  1. Inventory your systems
  2. Create your roles
  3. Assign roles to users
  4. Don't make one-off changes
  5. review your roles

## Wiki - RBAC

- If Authentication is “you are who you say you are,” what is Authorization?

    Authorization would be permission being granted to access something.

- Name three primary rules defined for RBAC.

   1. Role Assignment
   2. Roles Authorization
   3. Permission Authorization

- Describe RBAC to a non-technical friend.

    RBAC is a means of authorization that allows users with different roles to be able to access different features.
  
## RBAC tutorial

- What Are access rights Associated with? The User? or The Role? Explain.

    Access rights are associated with the role, not the user. This is because the system checks the role that the user has. It doesn't care about who it is, only the role.

- Access Rights, or Authorization, is activated after a user successfully does what?

   When the user logs in and completes the authentication process.

- Explain how RBAC might benefit a business.

    The policy won't have to change if a user leaves the system, it only cares about the roles. If a new person comes you can just assign them a role. You can access only specific files that you will need for your job and nothing more to keep information hidden.
