---
title: "Task Return Comments and Custom Destinations"
description: "Customize Task Return Behavior"
slug: "task-return-comments-and-custom-destinations"
---

# Task Return Comments and Custom Destinations

By default, when a task is **returned** (from the My Tasks interface), the process automatically goes back to the previous task—the one completed immediately before the returned task:

![](images/AD_4nXccoXaPSPhQp7OX091JaPHHoKtZkgvKdLnMbgxgFxWNvpy3hea88g4X74awIA8-SV8dqrwIA870ahEgBfHhiS-wW2ICCVOevHIOhP8geqiTO7RbDb-VXj9P23SYtj7XWQhkTeJQXQ)

## **Mandatory Comments on Return**

Whenever you return a task, you are required to provide a comment explaining why the task is being returned.

The goal is to make sure that the performers of the task(tasks) that get reactivated when you return your task understand why the process has been returned to them and what's required of them.

![](images/AD_4nXfQKueZDZHefBr37dffCFMng-hLij-5YAAJgeOMQ6BRyk8CFkoFzvBcGEsjG862JVQLCjO1KSKv2SGDke4Jy7t-BVuC4NF5HCAHXHXp71u7GpEfp8kiXzULY_x2RcFbVi0gNm6LXw)

## **Custom Return Destinations**

Pneumatic also supports defining custom return destinations in workflow templates.

In the Template Editor, each task has a “**Return To"** section where you can specify exactly which task the process should move to when the task is returned by a performer:

![](images/AD_4nXcj344YsRuyAuVsHo43IMhPbBKJ-CrwwbB38dWI14oNvE9-5P-dEM7Kz35kNtVRx7IPjg3jqvEQuZV8kUcdluaaLulT-7jikiJ-YB4NP9JvFVmEXYKZLMf2DllVNvLbLpZ44sn8eg)

## **The Difference from the "Return To" Option in the Workflows View**

Managers (template owners) can manually return processes to any step via the Workflow View.

With the **"Return To"** setting in the Template Editor, workflows can be expressly designed to **consistently** return to a specific step whenever a performer returns a task from their Task View rather than just always going back to the previous step.

This feature is particularly useful in scenarios like approval chains. For instance, if approval fails at any stage, the workflow can be automatically routed back to a specific step at the very beginning of the process. Initial documents can then be updated and resubmitted and then go through all the required approval stages again.
