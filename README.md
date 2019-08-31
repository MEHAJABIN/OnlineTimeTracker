# OnlineTimeTracker
The OnlineTimeTrack is a web project created in Asp.net core Web-Api framework as Back End, C# code is using in Web Api. It is a individual project of me during my internship period @Fantacode Solutions. This project about tracking time of employees in a company. Now it have one role called User. In This project there are 3 modules mainly. They are:

    1.User
    2.Projects
    3.WorkLogs
    4.TimeLog

### User

User module will have the following features

     1.AddUser (SuperAdmin)
     2.Login
     3.ListUsers (SuperAdmin)
     4.GetUser
     5.UpdateUser (SuperAdmin) - optional

### Projects

 Projects module are used to track the projects of the organization. It supports the following features.

   1.Add Projects (SuperAdmin)
   2.Update Project (SuperAdmin)
   3.Add Users to Project (SuperAdmin)
   4.List Projects

### WorkLogs

 Worklogs can be created for each projects and users can record their estimated time for a work item and the actual time.

    1.Add to Worklog
    2.Update the worklog
    3.List WorkLog of User (Self, SuperAdmin)
    4.Delete

### TimeLogs

 TimeLogs can be created against each worklog, and each worklog can have multiple timelog.

    1.Add timelog to a worklog
    2.list timelogs of a worklog
    3.Delete timelog

### Reporting

Reporting module is planned for future.
