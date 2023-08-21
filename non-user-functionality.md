# Non-User Functionality

## Introduction

One of the things I've found most frustrating about project/task management systems is their inability to handle tasks that are assigned to individuals who aren't using the system. This means I need to communicate with that individual outside of the system and then bring that communication into the system. In this document we'll try to find a way to integrate non-users into the system.

## Limitations

Even with our endeavors here we won't be able to streamline communications that occur verbally - whether that is in person or via the phone. However, we should be able to streamline communications via email and SMS.

## Email

When creating a task in the system we can assign it to anyone by their email address. When the task is created the system will send an email with the details of the task to that email address. It will use an email address that looks like name-of-person@nameofsystem.com. When the person replies to that email it will be automatically routed back into the system and attached to the task.

