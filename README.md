# CaseManagementDemo

## User & Roles
- Add CMS users to the role `cms_generic_user`
- Add CMS-ADMIN users to the role `cms_admin_user`

## Settings
- Hide default homepage from CMS users: Change role of `OpenTextEntityIdentityComponents.HomePage` in `/app/admin` to `Identity Administrator of OpenText Entity Identity Components`
- `wcp.properties`
  - credentials?
  - lazy-loading tabs?
  - lazy-loading error messages?

## Masterdata
- Types
- Processes
- OrgUnits (the values are related to the Assignee BB of the case!)

## Dependent service containers (run all in OS!)
  - Application Server Connector
    - Group name: `sg_appserver`
    - All relevant service interfaces
    - Service name: `sc_appserver`
    - Startup automatically
    - Assign to OS
  - Mail

## Resources
- Formatting code like CSS/JS: https://www.freeformatter.com
- Free to use Bootstrap icons: https://icons.getbootstrap.com
- Resize Bootstrap SVG images: https://imgcandy.com/resize-svg.html
