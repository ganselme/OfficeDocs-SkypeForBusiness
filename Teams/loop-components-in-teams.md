---
title: Overview of Loop components in Teams
ms.author: mikeplum
author: MikePlumleyMSFT
manager: serdars
audience: Admin
ms.topic: conceptual
ms.service: msteams
ms.reviewer: michalbr
ms.localizationpriority: medium
search.appverid: MET150
ms.collection: 
  - M365-collaboration
description: Learn how to manage Loop components in Teams.
f1.keywords:
- CSH
ms.custom: 
  - NewAdminCenter_Update
appliesto: 
  - Microsoft Teams
---

# Overview of Loop components in Teams

Loop components in Teams chat offer a new way to ideate, create, and make decisions together. Send a component - like a table, task list, or paragraph — where everyone in your chat can edit inline and see changes as they're made. 

> [!Note]
> Loop components is the first feature of the [Microsoft Loop app](https://www.microsoft.com/en-us/microsoft-loop) to become available in Teams. 

**Get tasks done faster together.** Crowd-source an agenda, track a group's action items, or take notes collectively. These are just a few scenarios made easier with Loop components.

**Share components.** In this release, you can share Loop components into different Teams chats. Recipients can edit from wherever they are and see updates instantly no matter where the changes were made.

**Start in chat, build from there.** Every component you create from Teams chat is automatically saved to a file in OneDrive. So, you might begin collaborating in chat then later move to the file, where you have a larger visual space for editing and can add as many components as you like.

## Clients and platforms

Available on Teams apps on Windows, Mac, Linux, iOS, and Android.

## Loop components and .fluid files

Loop components created in Teams are backed by a .fluid file stored in the creator's OneDrive. Being a file in OneDrive means that users can create, discover, and manage Loop components (.fluid files) as easily as any Office document. .fluid files work with data governance features like eDiscovery, auditing, reporting, and legal hold.

## How are .fluid  files stored?

.fluid files appear on Office.com and OneDrive, such as in the Recent and Recommended areas. Users can search for content in .fluid files from Office.com and OneDrive. .fluid files can be restored to previous versions from OneDrive. To create Loop components chat participants must have a OneDrive account. Without a valid OneDrive account, chat participants might still be able to collaborate on a component created by other users who have a valid OneDrive account, but cannot create their own. 

Moving a .fluid file from OneDrive to a SharePoint site will result in the live component failing to load in Teams chat.

## What happens if the owner of the file leaves the company?

OneDrive retention policies apply to .fluid files just as they do to other content created by the user.

## How are .fluid files shared?

Loop components can be inserted in Teams chat or copied from one chat to another. (Loop components aren't yet supported in channels.) They default to the organization's existing permissions, but users can change permissions before sending to ensure everyone has access.

Opening components from Teams chat in Office.com offers share functionality at the top of the window, similar to the sharing options offered for other Office documents.

## What if a .fluid file becomes corrupted or damaged?

Version History allows you to review and copy from previous versions of the file.

## What apps can open and edit .fluid files?

.fluid files can only be opened as links in your browser, such as Office.com, and as Loop components in Teams chat. If downloaded, they can't be opened again without first uploading them back to OneDrive or SharePoint.

## Known issues

- Loop components in chat cannot be edited via Office app when using Teams on Android.
- If tenant default file permissions are set to *Specific people* (only the people the user specifies), and the sender removes some users from the *Specific people* list in the permissions dialog when creating a component, those users may still have access to the content.
- With tenant default file permissions set to *Specific people* (only the people the user specifies), copying link to live component and pasting in another chat requires the sender to use permissions dialog and add the recipients in the Specific people option to grant access properly.
- With tenant default file permissions set to *Specific people* (only the people the user specifies), creating a live component in group chat with more than 20 members will require the sender to manually select the permission options for the component.
- Searching for Loop components in Teams search will return a link to the component in office.com, not the chat message itself.
- Loop components are disabled in federated chats.
- B2B guests will not be able to collaborate on a live component that is shared with them via Company Share Link. Set permissions to **People currently in this chat** to share components with B2B guests.
- Loop components are not supported in Teams channels.
- Loop components in chat will not load only if file was moved to different library. If file is moved to different folder then it will continue to load in chat.

## Related topics

[Manage Loop components in SharePoint](/sharepoint/manage-loop-components)