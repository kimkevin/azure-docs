---
title: Azure Active Directory report retention policies | Microsoft Docs
description: Retention policies on report data in your Azure Active Directory
services: active-directory
documentationcenter: ''
author: MarkusVi
manager: femila
editor: ''

ms.assetid: 183e53b0-0647-42e7-8abe-3e9ff424de12
ms.service: active-directory
ms.devlang: na
ms.topic: article
ms.tgt_pltfrm: na
ms.workload: identity
ms.date: 04/06/2017
ms.author: dhanyahk;markvi

---
# Azure Active Directory report retention policies


This topic provides you with answers to the most common questions in conjunction with the data retention for the different activity reports in Azure Active Directory. 

**Q: How can you get the collection of activity data started?**

**A:**

| Azure AD Edition | Collection Start |
| :--              | :--   |
| Azure AD Premium P1 <br /> Azure AD Premium P2 | When you sign-up for a subscription |
| Azure AD Free | The first time you open the [Azure Active Directory blade](https://ms.portal.azure.com/#blade/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/Overview) or use the [reporting APIs](https://aka.ms/aadreports)  |

---
**Q: When is your activity data available in the Azure portal?**

**A:**

- **Immediately** - If you have already been working with reports in the Azure classic portal
- **Within 2 hours** - If you haven’t turned reporting on  in the Azure classic portal

---
**Q: How can you get the collection of security signals started?**  

**A:** For security signals, the collection process starts when you opt-in to use the Identity Protection Center. 


---
**Q: For how long is the collected data stored?**

**A:**

**Activity reports**	

| Report                 | Azure AD Free | Azure AD Premium P1 | Azure AD Premium P2 |
| :--                    | :--           | :--                 | :--                 |
| Directory Audit        | 7 days        | 30 days             | 30 days             |
| Sign-in Activity       | 7 days        | 30 days             | 30 days             |

**Security Signals**

| Report         | Azure AD Free | Azure AD Premium P1 | Azure AD Premium P2 |
| :--            | :--           | :--                 | :--                 |
| Users at risk  | 7 days        | 30 days             | 90 days             |
| Risky sign-ins | 7 days        | 30 days             | 90 days             |

---