# Vacation Tracking System (VTS)

## Project Description
The Vacation Tracking System (VTS) is a simple application that helps employees manage their vacation, sick leave, and personal days. This repo focuses on the "Manage Time" use case, allowing employees to request time off and receive approvals from managers, while keeping records and updating HR systems.

## Functional Requirements
1. **Employee Self-management**:  
   Employees can manage their vacation time, sick leave, and personal time off.

2. **Flexible Rules-based Validation**:  
   A system to validate and verify leave time requests based on flexible rules.

3. **Manager Approval**:  
   Optional manager approval for leave requests.

4. **Historical and Future Requests**:  
   Access to leave requests for the previous calendar year and requests can be made up to a year and a half in the future.

5. **Email Notifications**:  
   Notifications for managers and employees about request statuses and approvals via email.

6. **Activity Logging**:  
   Logs of all transactions and activities within the system.

7. **HR and Admin Overrides**:  
   HR and system administrators can override rules with logging of such actions.

8. **Manager Awarding of Personal Leave**:  
   Managers can directly award personal leave time within system-set limits.

9. **Web Service Interface**:  
   An interface for other internal systems to query employee vacation request summaries.

10. **HR Legacy System Integration**:  
    Interface with HR legacy systems to retrieve and update necessary employee information.

## Non-Functional Requirements
1. **Usability**:  
   The system must be easy to use.

2. **Performance**:  
   Efficient processing of requests and notifications to save time.

3. **Compatibility**:  
   Use existing hardware and middleware for implementation.

## Constraints
1. **Existing Infrastructure**:  
   The system must extend the existing intranet portal system.

2. **Single-Sign-On**:  
   Utilize the portal’s single-sign-on mechanisms for all authentication processes.

3. **Hardware and Middleware**:  
   Existing hardware and middleware must be utilized for system implementation.

4. **HR Department Involvement**:  
   HR personnel remain responsible for entering and updating employee vacation data.

## Actors
- **Employee**: Users managing their vacation requests.
- **HR Employee (Clerk)**: Handles employee data and support.
- **Manager**: Approves leave requests and manages personal leave awards.
- **System Admin**: Oversees the system operation and maintenance.

## Manage Time
- View, create, and cancel vacation time requests.

## Admin Flow

<img src="https://github.com/user-attachments/assets/a2015675-afb6-4013-b01a-724f8afc49be" width="50%" height="50%">
 
## Employee Flow
 
<img src="https://github.com/user-attachments/assets/62015a4c-4aa1-47fd-8eaa-944938429557" width="50%" height="auto"> 
 
## Database Design

<img src="https://github.com/user-attachments/assets/49f92096-0bf3-424a-aba4-e67b968e131d" width="50%" height="auto"> 

## Vacation Request State Machine Diagram 

<img src="https://github.com/user-attachments/assets/dd012ffa-edc9-4878-8f86-710f3e61b9c9" width="50%" height="auto"> 

## Sequence Diagrams

### Create New Vacation Request
<img src="https://github.com/user-attachments/assets/4d5dc303-18bd-4347-b268-db97bdfafcf8" width="80%" height="auto">

### Withdraw Request
<img src="https://github.com/user-attachments/assets/d87542d7-f3a8-4623-a721-7a9b9164c353" width="80%" height="auto">
