# GridFrame  
**Generalized Relational Interface for Dynamic Forms, Records, and Management Environment**

## Overview

**GridFrame** is a generic platform designed to enable the dynamic creation and management of customizable records (or “data models”). The system empowers administrators (owners/admins) to define the fields and visual layout of each record template, while users with various roles (owner, admin, user, and anonymous) can fill in, view, filter, and export data.

## Objectives

- Provide a robust, secure, and dynamic system for creating custom data models.
- Enable flexible, drag-and-drop layout customization for record views.
- Implement granular access control and permissions based on user roles.
- Maintain a detailed history (versioning) of changes made to data models for auditing and security.

## Key Features

- **Login and Access Control**  
  - Supports multiple roles: owner, admin, user, and anonymous.  
  - Role-based permissions for creating, editing, viewing, and downloading data.

- **Customizable Data Models**  
  - **Field Definition:** Owners and admins can define the fields (e.g., "Name" as a string, "Birthdate" as a date) that make up a record template.  
  - **Display Area:** A drag-and-drop interface allows for the arrangement of “information blocks” (previously referred to as field cards) within a grid. Each block has a minimum size but can be resized within defined limits.

- **Data Entry and Visualization**  
  - Authorized users can input data through the custom forms.  
  - A spreadsheet-like interface offers filtering and column customization for viewing records.

- **Data Export**  
  - Functionality to download data in standard formats (CSV, XLSX, etc.) with or without applied filters.

- **Versioning and History**  
  - Every modification to a data model (field addition, deletion, or alteration) is logged with details about who made the change, when it was made, and what was modified.  
  - This audit trail is essential for ensuring data security and traceability.

- **User-Friendly Terminology**  
  To avoid ambiguity and improve the user experience, the platform uses intuitive names for its components:
  - **Data Model / Template:** Instead of “table” or “form”, the structure is referred to as a Data Model or Template.
  - **Display Area / Data Dashboard:** The interface where data is entered and viewed.
  - **Information Block / Record Item:** The individual elements representing each field within the model.

## Future Enhancements

- [ ] **Data Import:** Allow importing records from files (e.g., CSV, Excel).
- [ ] **API Access:** Provide a secure API (token-based) for owners/admins to access the database.
- [ ] **Analytics Module:** Develop an environment for data analysis, including graphs and dashboards (similar to Metabase).
- [ ] **Advanced Permission Control:** Enable more granular permission settings by group and tags.
- [ ] **Multi-language Support:** Implement page translation capabilities to make the platform accessible in multiple languages.
- [ ] **Accessibility Enhancements:** Improve accessibility for users with disabilities.

## Roadmap

### MVP
- [ ] Implement login system with role-based access.
- [ ] Develop basic functionality for creating Data Models with field definitions.
- [ ] Build a simple drag-and-drop interface for the Display Area.
- [ ] Log and version changes to Data Models.
- [ ] Enable data entry and grid-like visualization of records.

### Additional Features
- [ ] Add data export functionality (CSV/XLSX).
- [ ] Enhance the Display Area with advanced filtering and column customization.
- [ ] Refine the history log with detailed versioning information.

### Future Planned Resources
- [ ] Data import and external API access.
- [ ] Analytics and dashboard module.

## License

This project is licensed under the [MIT License](LICENSE).

*GridFrame aims to be a professional and dynamic tool for managing customizable data models with robust auditing and user-friendly interfaces. Contributions, suggestions, and collaborations are welcome!*
