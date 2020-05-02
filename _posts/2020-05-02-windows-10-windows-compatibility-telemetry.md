---
layout: post
title: "Windows 10 issue Q&A"
date: "2020-05-02"
categories: Notes, Win10
permalink: /windows-10-issue/
---

[Permanently Disabling Windows Compatibility Telemetry]

---

Q: In Task Manager, I often see the Windows Compatibility Telemetry process running in the background and unnecessarily creating CPU usage. Can you explain how to permanently turn off the telemetry?

[vlad978123.]


A: The Windows Compatibility Telemetry is a service in Windows 10 which contains technical data on how the device and its related software is working. It periodically sends the data to Microsoft for future improvement of the system and to enhance the user experience. To sort out your concern, you may disable this service from the Task Scheduler by following the steps below:

1. Click Start, type Task Scheduler, and then press Enter.
2. On the TaskScheduler window, go to this path: Task Scheduler Library\Microsoft\Windows\Application Experience.
3. On the Application Experience folder, look for Microsoft Compatibility Appraiser.
4. Right-click on it, select Disable, and then confirm to complete the process.
5. Once you’re done, you may check if the issue persists.

Keep us updated about your concern for additional assistance regarding the issue.

[Joseph Ban]
Microsoft Agent, Moderator


[Permanently Disabling Windows Compatibility Telemetry]: https://answers.microsoft.com/en-us/windows/forum/windows_10-performance/permanently-disabling-windows-compatibility/6bf71583-81b0-4a74-ae2e-8fd73305aad1


[vlad978123.]: https://answers.microsoft.com/en-us/profile/24404433-fe48-430f-9c16-d39a6c2b9fec?sort=LastReplyDate&dir=Desc&tab=Threads&forum=allcategories&meta=&status=&mod=&advFil=&postedAfter=undefined&postedBefore=undefined&threadType=All&page=1


[Joseph Ban]: https://answers.microsoft.com/en-us/profile/b18e6351-2284-4b4a-8fcd-0f5758e7da58