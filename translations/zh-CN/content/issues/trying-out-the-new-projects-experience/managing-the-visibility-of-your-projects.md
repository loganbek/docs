---
title: 管理项目的可见性（测试版）
intro: 您可以控制谁可以查看您的项目。
allowTitleToDifferFromFilename: true
miniTocMaxHeadingLevel: 3
versions:
  fpt: '*'
  ghec: '*'
topics:
- Projects
- Organizations
ms.openlocfilehash: 85b586bbb86e8d6e286e86263eca3f44d174391f
ms.sourcegitcommit: 22d665055b1bee7a5df630385e734e3a149fc720
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/13/2022
ms.locfileid: "145128655"
---
{% data reusables.projects.projects-beta %}

## <a name="about-project-visibility"></a>关于项目可见性

项目（测试版）可以是公共的，也可以是私有的。 对于公共项目，互联网上的每个人都可以查看。 对于私有项目，只有被授予至少读取访问权限的用户才能查看。

只有项目可见性会受影响；要查看项目上的项，必须有人具有该项所属存储库所需的权限。 如果项目包含私有存储库中的项目，则不是存储库协作者的用户将无法查看该存储库中的项。

![包含隐藏项的项目](/assets/images/help/projects/hidden-items.png)

只有项目管理员才能控制项目可见性。

在组织拥有的私有项目中，当前对项目进行更新的用户的头像将显示在项目 UI 中。

项目管理员还可以管理对其项目的写入和管理员访问权限，并控制单个用户的读取访问权限。 有关详细信息，请参阅“[管理对项目的访问](/issues/trying-out-the-new-projects-experience/managing-access-to-projects)”。

## <a name="changing-project-visibility"></a>更改项目可见性

{% data reusables.projects.project-settings %}
1. 在“可见性”下，选择“专用”或“公共”  。
