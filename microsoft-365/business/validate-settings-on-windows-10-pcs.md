---
title: Verificar definições de proteção de aplicações em PCs Windows 10
ms.author: sirkkuw
author: Sirkkuw
manager: scotv
audience: Admin
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.collection:
- Adm_O365
- M365-subscription-management
- M365-identity-device-management
ms.custom:
- Adm_O365
- Core_O365Admin_Migration
- MiniMaven
- MSB365
- OKR_SMB_M365
search.appverid:
- BCS160
- MET150
ms.assetid: fae8819d-7235-495f-9f07-d016f545887f
description: Saiba como validar as configurações de proteção de aplicativos do Microsoft 365 Business em dispositivos Windows 10.
ms.openlocfilehash: 5fed2278856f40233b142d3c7c4bc623e3777799
ms.sourcegitcommit: bd52f7b662887f552f90c46f69d6a2a42fb66914
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 10/17/2019
ms.locfileid: "37575474"
---
# <a name="validate-device-protection-settings-on-windows-10-pcs"></a><span data-ttu-id="26b4a-103">Validar configurações de proteção do dispositivo em PCs com Windows 10</span><span class="sxs-lookup"><span data-stu-id="26b4a-103">Validate device protection settings on Windows 10 PCs</span></span>

## <a name="verify-that-windows-10-device-policies-are-set"></a><span data-ttu-id="26b4a-104">Verifique se as diretivas de dispositivo do Windows 10 estão definidas</span><span class="sxs-lookup"><span data-stu-id="26b4a-104">Verify that Windows 10 device policies are set</span></span>

<span data-ttu-id="26b4a-105">Depois de [Configurar políticas de dispositivos](protection-settings-for-windows-10-pcs.md), pode demorar até algumas horas para que a política tenha efeito nos dispositivos dos utilizadores.</span><span class="sxs-lookup"><span data-stu-id="26b4a-105">After you [set up devices policies](protection-settings-for-windows-10-pcs.md), it may take up to a few hours for the policy to take effect on users' devices.</span></span> <span data-ttu-id="26b4a-106">Você pode confirmar que as políticas foram efetivadas observando várias telas de configurações do Windows nos dispositivos dos usuários.</span><span class="sxs-lookup"><span data-stu-id="26b4a-106">You can confirm that the policies took effect by looking at various Windows Settings screens on the users' devices.</span></span> <span data-ttu-id="26b4a-107">Como os usuários não poderão modificar as configurações do Windows Update e do Windows Defender Antivirus em seus dispositivos Windows 10, muitas dessas opções ficarão esmaecido.</span><span class="sxs-lookup"><span data-stu-id="26b4a-107">Because the users won't be able to modify the Windows Update and Windows Defender Antivirus settings on their Windows 10 devices, a lot of those options will be greyed out.</span></span>
  
1. <span data-ttu-id="26b4a-108">Vá para **configurações** \> **de &amp; atualização de segurança** \> do **Windows Update** \> **Opções de reinicialização** e confirme que todas as configurações estão acinzentadas.</span><span class="sxs-lookup"><span data-stu-id="26b4a-108">Go to **Settings** \> **Update &amp; security** \> **Windows Update** \> **Restart options** and confirm that all settings are greyed out.</span></span> 
    
    ![Todas as opções de reinicialização são acinzentadas.](media/31308da9-18b0-47c5-bbf6-d5fa6747c376.png)
  
2. <span data-ttu-id="26b4a-110">Vá para **configurações** \> **de &amp; atualização de segurança** \> do **Windows Update** \> **Opções avançadas** e confirme que todas as configurações estão acinzentadas.</span><span class="sxs-lookup"><span data-stu-id="26b4a-110">Go to **Settings** \> **Update &amp; security** \> **Windows Update** \> **Advanced options** and confirm that all settings are greyed out.</span></span> 
    
    ![As opções de atualizações avançadas do Windows estão todas acinzentadas.](media/049cf281-d503-4be9-898b-c0a3286c7fc2.png)
  
3. <span data-ttu-id="26b4a-112">Vá para **configurações** \> **de &amp; atualização de segurança** \> do **Windows Update** \> **Opções** \> avançadas **escolha como as atualizações são entregues**.</span><span class="sxs-lookup"><span data-stu-id="26b4a-112">Go to **Settings** \> **Update &amp; security** \> **Windows Update** \> **Advanced options** \> **Choose how updates are delivered**.</span></span>
    
    <span data-ttu-id="26b4a-113">Confirme que você pode ver a mensagem (em vermelho) que algumas configurações estão ocultas ou gerenciadas por sua organização, e todas as opções são acinzentadas.</span><span class="sxs-lookup"><span data-stu-id="26b4a-113">Confirm that you can see the message (in red) that some settings are hidden or managed by your organization, and all the options are greyed out.</span></span>
    
    ![Escolha como as atualizações são entregues página indica que as configurações são ocultas ou gerenciadas por sua organização.](media/6b3e37c5-da41-4afd-9983-b4f406216b59.png)
  
4. <span data-ttu-id="26b4a-115">Para abrir a central de segurança do Windows Defender, vá para **configurações** \> de **atualização &amp; de segurança** \> **do Windows Defender** \> clique em **Abrir Windows Defender Security Center** \> \*\*Virus &amp; thread \*\* \> configurações de proteção contra \*\*ameaças de vírus &amp; \*\*de proteção.</span><span class="sxs-lookup"><span data-stu-id="26b4a-115">To open the Windows Defender Security Center, go to **Settings** \> **Update &amp; security** \> **Windows Defender** \> click **Open Windows Defender Security Center** \> **Virus &amp; thread protection** \> **Virus &amp; threat protection settings**.</span></span> 
    
5. <span data-ttu-id="26b4a-116">Verifique se todas as opções estão acinzentadas.</span><span class="sxs-lookup"><span data-stu-id="26b4a-116">Verify that all options are greyed out.</span></span> 
    
    ![As configurações de proteção contra vírus e ameaças são acinzentadas.](media/9ca68d40-a5d9-49d7-92a4-c581688b5926.png)
  
## <a name="related-topics"></a><span data-ttu-id="26b4a-118">Tópicos relacionados</span><span class="sxs-lookup"><span data-stu-id="26b4a-118">Related Topics</span></span>

[<span data-ttu-id="26b4a-119">Recursos e documentação do Microsoft 365 Business</span><span class="sxs-lookup"><span data-stu-id="26b4a-119">Microsoft 365 Business documentation and resources</span></span>](https://go.microsoft.com/fwlink/p/?linkid=853701)
  
[<span data-ttu-id="26b4a-120">Introdução ao Microsoft 365 Business</span><span class="sxs-lookup"><span data-stu-id="26b4a-120">Get started with Microsoft 365 Business</span></span>](microsoft-365-business-overview.md)
  
[<span data-ttu-id="26b4a-121">Gerir o Microsoft 365 Business</span><span class="sxs-lookup"><span data-stu-id="26b4a-121">Manage Microsoft 365 Business</span></span>](manage.md)
  
[<span data-ttu-id="26b4a-122">Definir as configurações de dispositivos para PCs Windows 10</span><span class="sxs-lookup"><span data-stu-id="26b4a-122">Set device configurations for Windows 10 PCs</span></span>](protection-settings-for-windows-10-pcs.md)
  

