---
title: Instalar ou desinstalar o Office em dispositivos Windows 10 automaticamente
ms.author: sirkkuw
author: Sirkkuw
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.collection:
- Adm_O365
- M365-subscription-management
ms.custom:
- Adm_O365
- Core_O365Admin_Migration
- MiniMaven
- MSB365
search.appverid:
- BCS160
- MET150
ms.assetid: cbc6bfe5-565a-4fb8-95f0-b06e7b74ac46
description: 'Instalar ou desinstalar o Office no Windows 10 dispositivos partir do Centro de administração do Microsoft 365 Business. '
ms.openlocfilehash: 94e5761b516c150caa11048be73d97f468b09fb5
ms.sourcegitcommit: db1dfb2df2c2f7beced3b57bc772d106c189e88a
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 05/07/2019
ms.locfileid: "33660612"
---
# <a name="automatically-install-or-uninstall-office-on-windows-10-devices"></a><span data-ttu-id="86e90-103">Instalar ou desinstalar o Office em dispositivos Windows 10 automaticamente</span><span class="sxs-lookup"><span data-stu-id="86e90-103">Automatically install or uninstall Office on Windows 10 devices</span></span>

![Faixa que apontam para https://aka.ms/aboutM365preview.](media/m365admincenterchanging.png)

<span data-ttu-id="86e90-105">Pode instalar o Office em PCs Windows 10 de forma rápida e fácil a partir do centro de administração do Microsoft 365 Business.</span><span class="sxs-lookup"><span data-stu-id="86e90-105">You can quickly and easily install Office to Windows 10 PCs from the Microsoft 365 Business admin center.</span></span>
  
<span data-ttu-id="86e90-106">Para compreender como este processo funciona em aplicações do Office instaladas anteriormente, leia o artigo [Prepare for Office client installation (Preparar a instalação do cliente do Office)](prepare-for-office-client-deployment.md) antes de começar.</span><span class="sxs-lookup"><span data-stu-id="86e90-106">To understand how this works with previously installed Office apps, read [Prepare for Office client installation](prepare-for-office-client-deployment.md) before you get started.</span></span> 
  
## <a name="manage-office-deployments"></a><span data-ttu-id="86e90-107">Gerir as implementações do Office</span><span class="sxs-lookup"><span data-stu-id="86e90-107">Manage Office deployments</span></span>

1. <span data-ttu-id="86e90-108">Inicie sessão no [centro de administração](https://aka.ms/bcsportal) com as suas credenciais de administrador global.</span><span class="sxs-lookup"><span data-stu-id="86e90-108">Sign in to the [admin center](https://aka.ms/bcsportal) with global admin credentials.</span></span> 
    
2. <span data-ttu-id="86e90-109">No cartão **Dispositivos**, selecione **Gerir a Implementação do Office**.</span><span class="sxs-lookup"><span data-stu-id="86e90-109">On the **Devices** card, choose **Manage Office Deployment**.</span></span>
      <span data-ttu-id="86e90-110">Se não vir o cartão de **Acções do dispositivo** no centro **doméstica** página admin, clique em **Adicionar** (+) para o adicionar à sua home page de administração.</span><span class="sxs-lookup"><span data-stu-id="86e90-110">If you do not see the **Device actions** card, in the admin center **Home** page, click **Add** (+) to add it to your admin home.</span></span>
    
    ![Screenshot of the Devices card in the admin center](media/9982e784-dbf9-4a76-a159-bb3e2e5aa23f.png)
  
3. <span data-ttu-id="86e90-112">No painel **Gerir a implementação do Office** aberto, selecione **Adicionar um grupo** e, em seguida, selecione os grupos que pretende utilizar.</span><span class="sxs-lookup"><span data-stu-id="86e90-112">On the **Manage Office deployment** pane that opens, choose **Add a group**, then select the groups you want use.</span></span>
    
4. <span data-ttu-id="86e90-113">Após ter adicionado os grupos que pretende utilizar, no menu pendente **Ação de Implementação**, selecione **Instalar o Office o mais rápido possível** ou **Desinstalar o Office**.</span><span class="sxs-lookup"><span data-stu-id="86e90-113">After you have added the group or groups you want to use, from the **Deployment Action** drop-down, select either **Install Office as soon as possible** or **Uninstall Office**.</span></span>
    
    ![In the Manage Office deployment pane, choose either Install Office as soon as possible, or Uninstall Office.](media/00f24a61-1848-40c0-b037-78d726c7d757.png)
  
5. <span data-ttu-id="86e90-115">Selecione **Seguinte** \> reveja as definições e, em seguida, selecione **Confirmar**.</span><span class="sxs-lookup"><span data-stu-id="86e90-115">Choose **Next** \> review the settings and then choose **Confirm**.</span></span>
    
<span data-ttu-id="86e90-116">Uma versão de 32 bits do Office será instalada ou desinstalada automaticamente nos dispositivos pertencentes aos utilizadores especificados pelos grupos que utilizou.</span><span class="sxs-lookup"><span data-stu-id="86e90-116">A 32-bit Office will be automatically installed, or uninstalled in the devices owned by users specified by the group or groups you used.</span></span>
  
<span data-ttu-id="86e90-117">Para verificar se a operação foi concluída, pode abrir o Gestor de Tarefas num computador selecionado para a instalação do Office e procurar o processo Microsoft Office Clique-e-Use.</span><span class="sxs-lookup"><span data-stu-id="86e90-117">To verify you can open the Task Manager on a computer that was selected for an Office install and look for Microsoft Office Click-to-Run process.</span></span>
  

