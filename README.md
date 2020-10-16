# compliance_analysis
An in-depth reporting and analysis of Cyber Security compliance reporting for an organization
As the internet proliferate our lives and businesses, the need for effective Cyber Security reporting and analysis increases for unonstructive working running of a business.

This project shows how businesses track, analyze and report Cybersecurity data for their organizations.

The Raw Data for this project is dummy data created using R.

Fields:

- Needs_Updates: String: Data field to indicate if a system requires Cyber Security Updates. (True: Needs Updates. False-Does not Need Further Updates).

- Operating_System: String: Cybersecurity Measures needed for a system are heavily depending on the Operating System a system is running. Older OS needs more frequest updates or even a complete revamp.

- Primary_Contact: String: Variable indicating the person to contact.

- Business_Unit: String: Variable indicating the Business unit managing a device.

-State_Name: String: Variable indocating the state where a device is situated/registered.

-Last_Seen_Online: Date: Variable indicating the last time a device appeared on the organization network.

-Primary_Contact_U: String: Updated Primary Contact string (first letter capitalized).

-OS Check: String: "OS Compliant" if the Operating System of a device is Compliant else "OS Obsolete".

-ReportDate: Date indicating the reporting month. This field can be used to track historical progress of Business Units/States.

-Last Seen Online Check: String: "Needs Restart" if the difference between the Report Date and the Last_Seen_Online date is over 10 days."Last Seen Online Compliant" is the device has checked in to the network in 10 days before the Report Date.

-Days Since: Integer: DateDifference between "Last_Seen_Online" and "Report Date".

-Compliance Status: String: "Compliant" if the compliance rules are fulfilled. "Non Compliant" if the compliance rules are not fulfilled.

-Compliance Rules: While the industrial Cybersecurity Compliance Rules are more intricate. For this project, A device is considerent compliant if it fufills the following three conditions:

-Operating System IN (Win7, Server2008, Win10)
-Needs Updates = FALSE
-Days Between ReportDALast_Seen_Online <=10


