---
title: การส่งออกข้อมูลวงจรชีวิต
description: ส่งออกข้อมูลวัฏจักรของผลิตภัณฑ์
ms.date: 08/19/2020
ms.openlocfilehash: d116baffd1a01f45fafeb184fddda1a0736e694a
ms.sourcegitcommit: 7058ee1673709d6dd4bed24f043690e0da2c6bb4
ms.translationtype: MT
ms.contentlocale: th-TH
ms.lasthandoff: 08/19/2020
ms.locfileid: "902655"
---
# <a name="lifecycle-data-export"></a><span data-ttu-id="05615-103">การส่งออกข้อมูลวงจรชีวิต</span><span class="sxs-lookup"><span data-stu-id="05615-103">Lifecycle data export</span></span>

> [!IMPORTANT]
> <span data-ttu-id="05615-104">หน้านี้อยู่ภายใต้การพัฒนา</span><span class="sxs-lookup"><span data-stu-id="05615-104">This page is under development.</span></span>

## <a name="export-all-products"></a><span data-ttu-id="05615-105">ส่งออกผลิตภัณฑ์ทั้งหมด</span><span class="sxs-lookup"><span data-stu-id="05615-105">Export all products</span></span>
<span data-ttu-id="05615-106">ส่งออกข้อมูลวงจรชีวิตสำหรับผลิตภัณฑ์ทั้งหมดโดยคลิกด้านล่าง:</span><span class="sxs-lookup"><span data-stu-id="05615-106">Export lifecycle data for all products by clicking below:</span></span>

> [!div class="nextstepaction"]
> [<span data-ttu-id="05615-107">ส่งออกผลิตภัณฑ์ทั้งหมด</span><span class="sxs-lookup"><span data-stu-id="05615-107">Export All Products</span></span>](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export)

## <a name="export-products-by-family-and-group"></a><span data-ttu-id="05615-108">ส่งออกผลิตภัณฑ์ตามครอบครัวและกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="05615-108">Export products by Family and Group</span></span>
<span data-ttu-id="05615-109">เลือกครอบครัวแล้วเลือกกลุ่มเพื่อส่งออก</span><span class="sxs-lookup"><span data-stu-id="05615-109">Select a Family and then a Group to export.</span></span> <span data-ttu-id="05615-110">หมายเหตุ: การส่งออกจะเริ่มต้นเมื่อมีการเลือกค่ากลุ่ม</span><span class="sxs-lookup"><span data-stu-id="05615-110">Note: Export will begin when Group value is selected.</span></span> 

> [!div class="op_multi_selector" title1="ครอบครัว" title2="กลุ่ม"]
> - [(.NET | ทั้งหมด](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'.NET')
> - [(.NET | .NET)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'.NET'%20and%20parent/parent/name%20eq%20'.NET')
> - [(Azure | ทั้งหมด](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Azure')
> - [(Azure | AI](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Azure'%20and%20parent/parent/name%20eq%20'AI')
> - [(Azure | Azure](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Azure'%20and%20parent/parent/name%20eq%20'Azure')
> - [(Azure | ฐาน](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Azure'%20and%20parent/parent/name%20eq%20'Databases')
> - [(Azure | อื่นๆ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Azure'%20and%20parent/parent/name%20eq%20'Other')
> - [(Dynamics | ทั้งหมด](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics')
> - [(Dynamics | Dynamics](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics')
> - [(Dynamics | Dynamics ๓๖๕)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics%20365')
> - [(Dynamics | Dynamics AX)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics%20AX')
> - [(Dynamics | Dynamics C5)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics%20C5')
> - [(Dynamics | Dynamics CRM)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics%20CRM')
> - [(Dynamics | Dynamics GP)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics%20GP')
> - [(Dynamics | Dynamics NAV)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics%20NAV')
> - [(Dynamics | Dynamics POS)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics%20POS')
> - [(Dynamics | Dynamics RMS)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics%20RMS')
> - [(Dynamics | Dynamics SL)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics%20SL')
> - [(Dynamics | อื่นๆ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Other')
> - [(นิพจน์ | ทั้งหมด](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Expression')
> - [(นิพจน์ | นิพจน์](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Expression'%20and%20parent/parent/name%20eq%20'Expression')
> - [(Microsoft ๓๖๕ | ทั้งหมด](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20365')
> - [(Microsoft ๓๖๕ | การจัดการข้อมูลประจำตัว)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20365'%20and%20parent/parent/name%20eq%20'Identity%20Management')
> - [(กรอบบริการที่เชื่อมต่อของไมโครซอฟท์ | ทั้งหมด](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Connected%20Services%20Framework')
> - [(กรอบบริการที่เชื่อมต่อของไมโครซอฟท์ | กรอบงานบริการที่เชื่อมต่อ)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Connected%20Services%20Framework'%20and%20parent/parent/name%20eq%20'Connected%20Services%20Framework')
> - [(กรอบการดูแลลูกค้าของ Microsoft | ทั้งหมด](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Customer%20Care%20Framework')
> - [(กรอบการดูแลลูกค้าของ Microsoft | กรอบงานการดูแลลูกค้า)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Customer%20Care%20Framework'%20and%20parent/parent/name%20eq%20'Customer%20Care%20Framework')
> - [(Microsoft Internet Explorer | ทั้งหมด](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Internet%20Explorer')
> - [(Microsoft Internet Explorer | Internet Explorer)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Internet%20Explorer'%20and%20parent/parent/name%20eq%20'Internet%20Explorer')
> - [(Microsoft Office | ทั้งหมด](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Office')
> - [(Microsoft Office | ไคล](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Office'%20and%20parent/parent/name%20eq%20'Client')
> - [(Microsoft Office | ความปลอดภัย](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Office'%20and%20parent/parent/name%20eq%20'Security')
> - [(Microsoft Office | Server](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Office'%20and%20parent/parent/name%20eq%20'Server')
> - [(เซิร์ฟเวอร์ของ Microsoft ทั้งหมด](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Servers')
> - [(เซิร์ฟเวอร์ของ Microsoft BizTalk Server)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Servers'%20and%20parent/parent/name%20eq%20'BizTalk%20Server')
> - [(เซิร์ฟเวอร์ของ Microsoft Commerce Server)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Servers'%20and%20parent/parent/name%20eq%20'Commerce%20Server')
> - [(เซิร์ฟเวอร์ของ Microsoft เซิร์ฟเวอร์การจัดการเนื้อหา)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Servers'%20and%20parent/parent/name%20eq%20'Content%20Management%20Server')
> - [(เซิร์ฟเวอร์ของ Microsoft โฮสต์รวม Server)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Servers'%20and%20parent/parent/name%20eq%20'Host%20Integration%20Server')
> - [(เซิร์ฟเวอร์ของ Microsoft เกตเวย์แอปพลิเคชันอัจฉริยะ)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Servers'%20and%20parent/parent/name%20eq%20'Intelligent%20Application%20Gateway')
> - [(เซิร์ฟเวอร์ของ Microsoft ความปลอดภัย](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Servers'%20and%20parent/parent/name%20eq%20'Security')
> - [(ศูนย์ระบบ Microsoft | ทั้งหมด](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20System%20Center')
> - [(ศูนย์ระบบ Microsoft | ศูนย์ระบบ)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20System%20Center'%20and%20parent/parent/name%20eq%20'System%20Center')
> - [(Silverlight | ทั้งหมด](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Silverlight')
> - [(Silverlight | Silverlight](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Silverlight'%20and%20parent/parent/name%20eq%20'Silverlight')
> - [(SQL Server | ทั้งหมด](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'SQL%20Server')
> - [(SQL Server | Power BI)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'SQL%20Server'%20and%20parent/parent/name%20eq%20'Power%20BI')
> - [(SQL Server | SQL Server)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'SQL%20Server'%20and%20parent/parent/name%20eq%20'SQL%20Server')
> - [(Visual Studio | ทั้งหมด](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Visual%20Studio')
> - [(Visual Studio | Visual Studio)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Visual%20Studio'%20and%20parent/parent/name%20eq%20'Visual%20Studio')
> - [(Windows | ทั้งหมด](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Windows')
> - [(Windows | ไคล](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Windows'%20and%20parent/parent/name%20eq%20'Client')
> - [(Windows | IoT](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Windows'%20and%20parent/parent/name%20eq%20'IoT')
> - [(Windows | ถือ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Windows'%20and%20parent/parent/name%20eq%20'Mobile')
> - [(Windows | ความปลอดภัย](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Windows'%20and%20parent/parent/name%20eq%20'Security')
> - [(Windows | Server](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Windows'%20and%20parent/parent/name%20eq%20'Server')

## <a name="export-products-by-end-of-support-date"></a><span data-ttu-id="05615-168">ส่งออกผลิตภัณฑ์โดยสิ้นสุดวันที่สนับสนุน</span><span class="sxs-lookup"><span data-stu-id="05615-168">Export products by end of support date</span></span>
<span data-ttu-id="05615-169">เลือกปีเพื่อดูผลิตภัณฑ์ที่เข้าถึงจุดสิ้นสุดของการสนับสนุน</span><span class="sxs-lookup"><span data-stu-id="05615-169">Select a year to see products reaching the end of support.</span></span> <span data-ttu-id="05615-170">หมายเหตุ: การส่งออกจะเริ่มต้นเมื่อมีการเลือกค่าปี</span><span class="sxs-lookup"><span data-stu-id="05615-170">Note: Export will begin when Year value is selected.</span></span>

> [!div class="op_single_selector"]
> - [๒๐๐๒](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2002))
> - [๒๐๐๓](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2003))
> - [๒๐๐๔](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2004))
> - [๒๐๐๕](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2005))
> - [๒๐๐๖](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2006))
> - [๒๐๐๗](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2007))
> - [๒๐๐๘](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2008))
> - [๒๐๐๙](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2009))
> - [๒๐๑๐](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2010))
> - [๒๐๑๑](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2011))
> - [๒๐๑๒](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2012))
> - [๒๐๑๓](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2013))
> - [๒๐๑๔](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2014))
> - [๒๐๑๕](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2015))
> - [๒๐๑๖](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2016))
> - [๒๐๑๗](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2017))
> - [๒๐๑๘](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2018))
> - [๒๐๑๙](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2019))
> - [๒๐๒๐](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2020))
> - [๒๐๒๑](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2021))
> - [๒๐๒๒](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2022))
> - [๒๐๒๓](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2023))
> - [๒๐๒๔](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2024))
> - [๒๐๒๕](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2025))
> - [๒๐๒๖](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2026))
> - [๒๐๒๗](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2027))
> - [๒๐๒๘](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2028))
> - [๒๐๒๙](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2029))
> - [๒๐๓๐](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2030))
