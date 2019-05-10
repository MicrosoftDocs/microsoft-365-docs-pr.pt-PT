---
title: Configurar as definições de proteção de dispositivos para PCs Windows 10
ms.author: sirkkuw
author: Sirkkuw
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.collection:
- M365-subscription-management
- M365-identity-device-management
ms.custom:
- Core_O365Admin_Migration
- MiniMaven
- MSB365
search.appverid:
- BCS160
- MET150
ms.assetid: bd66c26c-73a4-45a8-8642-3ea4ee7cd89d
description: Obter informações sobre a predefinição e outras definições disponíveis no Microsoft Business de 365 para proteger o Windows 10 dispositivos.
ms.openlocfilehash: 5dc6ede8f31f5837d59c200e0b76083dcf419e05
ms.sourcegitcommit: db1dfb2df2c2f7beced3b57bc772d106c189e88a
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 05/07/2019
ms.locfileid: "33660399"
---
# <a name="set-device-protection-settings-for-windows-10-pcs"></a><span data-ttu-id="707a3-103">Configurar as definições de proteção de dispositivos para PCs Windows 10</span><span class="sxs-lookup"><span data-stu-id="707a3-103">Set device protection settings for Windows 10 PCs</span></span>

## <a name="secure-windows-10-devices"></a><span data-ttu-id="707a3-104">Proteger dispositivos Windows 10</span><span class="sxs-lookup"><span data-stu-id="707a3-104">Secure Windows 10 devices</span></span>

<span data-ttu-id="707a3-105">Veja um vídeo sobre como proteger os dispositivos com Windows 10 com Microsoft 365 Business:</span><span class="sxs-lookup"><span data-stu-id="707a3-105">View a video on how to secure Windows 10 devices with Microsoft 365 Business:</span></span>
  
> [!VIDEO https://www.microsoft.com/videoplayer/embed/a5734146-620a-4cec-8618-536b3ca37972?autoplay=false]
  
1. <span data-ttu-id="707a3-106">SGo para o Centro admin, <a href="https://go.microsoft.com/fwlink/p/?linkid=837890" target="_blank">https://admin.microsoft.com</a>.</span><span class="sxs-lookup"><span data-stu-id="707a3-106">SGo to the admin center at <a href="https://go.microsoft.com/fwlink/p/?linkid=837890" target="_blank">https://admin.microsoft.com</a>.</span></span> 
    
2. <span data-ttu-id="707a3-107">Nav esquerda, escolher **dispositivos** \> **políticas** \> **Adicionar**.</span><span class="sxs-lookup"><span data-stu-id="707a3-107">On the left nav, choose **Devices** \> **Policies** \> **Add**.</span></span>
  
3. <span data-ttu-id="707a3-108">No painel **Adicionar política**, introduza um nome exclusivo para esta política.</span><span class="sxs-lookup"><span data-stu-id="707a3-108">On the **Add policy** pane, enter a unique name for this policy.</span></span> 
    
4. <span data-ttu-id="707a3-109">Em **Tipo de política**, selecione **Configuração de Dispositivos Windows 10**.</span><span class="sxs-lookup"><span data-stu-id="707a3-109">Under **Policy type**, choose **Windows 10 Device Configuration**.</span></span>
    
5. <span data-ttu-id="707a3-p101">Expanda a janela **Proteger Dispositivos Windows 10** \> configure as definições da forma que pretende. Consulte [Definições disponíveis](#available-settings) para obter mais informações.</span><span class="sxs-lookup"><span data-stu-id="707a3-p101">Expand **Secure Windows 10 Devices** \> configure the settings how you would like. See [Available settings](#available-settings) for more information.</span></span> 
    
    <span data-ttu-id="707a3-112">Pode sempre utilizar a ligação **Repor predefinições** para regressar à predefinição.</span><span class="sxs-lookup"><span data-stu-id="707a3-112">You can alway use the **Reset default settings** link to return to the default setting.</span></span> 
    
    ![Add policy pane with Windows 10 Device configuration selected](media/fa9e2dc2-7eae-4c96-af34-765a1f641ecf.png)
  
6. <span data-ttu-id="707a3-p102">Em seguida, decida **Quem irá ver estas definições?** Se não quiser utilizar o grupo de segurança predefinido, **Todos os Utilizadores**, selecione **Alterar**, procure o grupo de segurança que irá obter essas definições \> **Selecionar**.</span><span class="sxs-lookup"><span data-stu-id="707a3-p102">Next decide **Who will get these settings?** If you don't want to use the default **All users** security group, Choose **Change**, search for the security group who will get these settings \> **Select**.</span></span>
    
7. <span data-ttu-id="707a3-116">Por fim, selecione **Concluído** para guardar a política e atribuí-la aos dispositivos.</span><span class="sxs-lookup"><span data-stu-id="707a3-116">Finally, choose **Done** to save the policy, and assign it to devices.</span></span> 
    
## <a name="available-settings"></a><span data-ttu-id="707a3-117">Definições disponíveis</span><span class="sxs-lookup"><span data-stu-id="707a3-117">Available settings</span></span>

<span data-ttu-id="707a3-p103">Por predefinição, todas as definições estão **Ativadas**. As seguintes definições estão disponíveis.</span><span class="sxs-lookup"><span data-stu-id="707a3-p103">By default all settings are **On**. The following settings are available.</span></span>
  
<span data-ttu-id="707a3-120">Consulte o artigo [Como é que as funcionalidades de proteção no Microsoft 365 Business são mapeadas às definições do Intune](map-protection-features-to-intune-settings.md) para obter mais informações.</span><span class="sxs-lookup"><span data-stu-id="707a3-120">See [How do protection features in Microsoft 365 Business map to Intune settings](map-protection-features-to-intune-settings.md) for more information.</span></span> 
  
|||
|:-----|:-----|
|<span data-ttu-id="707a3-121">Definição</span><span class="sxs-lookup"><span data-stu-id="707a3-121">Setting</span></span>  <br/> |<span data-ttu-id="707a3-122">Descrição</span><span class="sxs-lookup"><span data-stu-id="707a3-122">Description</span></span>  <br/> |
|<span data-ttu-id="707a3-123">Ajudar a proteger os PCs contra vírus e outras ameaças com o Antivírus do Windows Defender</span><span class="sxs-lookup"><span data-stu-id="707a3-123">Help protect PCs from viruses and other threats using Windows Defender Antivirus</span></span>  <br/> |<span data-ttu-id="707a3-124">Exige que o Antivírus do Windows Defender esteja ativado para proteger os PCs contra os perigos que uma ligação à Internet envolve.</span><span class="sxs-lookup"><span data-stu-id="707a3-124">Requires that Windows Defender Antivirus is turned on to protect PCs from the dangers of being connected to the internet.</span></span>  <br/> |
|<span data-ttu-id="707a3-125">Ajudar a proteger os PCs contra ameaças baseadas na Web no Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="707a3-125">Help protect PCs from web-based threats in Microsoft Edge</span></span>  <br/> |<span data-ttu-id="707a3-126">Ativa as definições no Microsoft Edge que ajudam a proteger os utilizadores contra transferências e sites maliciosos.</span><span class="sxs-lookup"><span data-stu-id="707a3-126">Turns on settings in Edge that help protect users from malicious sites and downloads.</span></span>  <br/> |
|<span data-ttu-id="707a3-127">Utilize regras que reduzam a superfície de ataque dos dispositivos</span><span class="sxs-lookup"><span data-stu-id="707a3-127">Use rules that reduce the attack surface of devices</span></span>  <br/> |<span data-ttu-id="707a3-p104">Quando ativada, a redução da superfície de ataque ajuda a bloquear ações e aplicações normalmente utilizadas por software maligno para infetar dispositivos. Esta definição só está disponível se o Antivírus do Windows Defender estiver Ativado. Consulte [Reduzir superfícies de ataque](https://go.microsoft.com/fwlink/?linkid=870417) para saber mais.  </span><span class="sxs-lookup"><span data-stu-id="707a3-p104">When turned On, attack surface reduction helps block actions and apps typically used by malware to infect devices. This setting is only available if Windows Defender Antivirus is set to On. See [Reduce attack surfaces](https://go.microsoft.com/fwlink/?linkid=870417) to learn more.  </span></span><br/> |
|<span data-ttu-id="707a3-131">Proteger pastas contra ameaças como o ransomware</span><span class="sxs-lookup"><span data-stu-id="707a3-131">Protect folders from threats such as ransomware</span></span>  <br/> |<span data-ttu-id="707a3-p105">Esta definição utiliza o acesso controlado a pastas para proteger os dados da empresa contra modificações de aplicações suspeitas e maliciosas, como o ransomware. Estes tipos de aplicações são impedidas de fazer alterações a pastas protegidas. Esta definição só está disponível se o Antivírus do Windows Defender estiver Ativado. Consulte [Proteger pastas com acesso controlado a pastas](https://go.microsoft.com/fwlink/?linkid=870418) para saber mais.  </span><span class="sxs-lookup"><span data-stu-id="707a3-p105">This setting uses controlled folder access to protect company data from modification by suspicious or malicious apps, such as ransomware. These types of apps are blocked from making changes in protected folders. This setting is only available if Windows Defender Antivirus is set to On. See [Protect folders with COntrolled folder access](https://go.microsoft.com/fwlink/?linkid=870418) to learn more.  </span></span><br/> |
|<span data-ttu-id="707a3-136">Impedir o acesso da rede a conteúdo potencialmente malicioso na Internet</span><span class="sxs-lookup"><span data-stu-id="707a3-136">Prevent network access to potentially malicious content on the Internet</span></span>  <br/> |<span data-ttu-id="707a3-p106">Utilize esta definição para bloquear as ligações de utilizadores de saída a localizações na Internet de baixa reputação que possam alojar esquemas de phishing, exploits ou outros conteúdos maliciosos. Esta definição só está disponível se o Antivírus do Windows Defender estiver Ativado. Consulte [Proteger a sua rede](https://go.microsoft.com/fwlink/?linkid=870419) para obter mais informações.  </span><span class="sxs-lookup"><span data-stu-id="707a3-p106">Use this setting to block outbound user connections to low-reputation Internet locations that may host phishing scams, exploits or other malicious content. This setting is only available if Windows Defender Antivirus is set to On. See [Protect your network](https://go.microsoft.com/fwlink/?linkid=870419) for more information.  </span></span><br/> |
|<span data-ttu-id="707a3-140">Ajudar a proteger ficheiros e pastas nos PCs contra acesso não autorizado com o BitLocker</span><span class="sxs-lookup"><span data-stu-id="707a3-140">Help protect files and folders on PCs from unauthorized access with BitLocker</span></span>  <br/> |<span data-ttu-id="707a3-p107">O Bitlocker protege os dados ao encriptar os discos rígidos do computador e proteger contra exposição de dados em caso de roubo ou perda do computador. Consulte as [FAQs do Bitlocker](https://go.microsoft.com/fwlink/?linkid=871000) para mais informações.  </span><span class="sxs-lookup"><span data-stu-id="707a3-p107">Bitlocker protects data by encrypting the computer hard drives and protect against data exposure if a computer is lost or stolen. See [Bitlocker FAQ](https://go.microsoft.com/fwlink/?linkid=871000) for more information.  </span></span><br/> |
|<span data-ttu-id="707a3-143">Permitir que os utilizadores transfiram aplicações da Microsoft Store</span><span class="sxs-lookup"><span data-stu-id="707a3-143">Allow users to download apps from Microsoft Store</span></span>  <br/> |<span data-ttu-id="707a3-p108">Permite que os utilizadores transfiram e instalem aplicações da Microsoft Store. As aplicações incluem tudo, desde jogos a ferramentas de produtividade, pelo que deixamos esta definição **Ativada**, embora a possa desativar para garantir uma segurança adicional.  </span><span class="sxs-lookup"><span data-stu-id="707a3-p108">Lets users download and install apps from the Microsoft Store. Apps include everything from games to productivity tools, so we leave this setting **On**, but you can turn it off for extra security.  </span></span><br/> |
|<span data-ttu-id="707a3-146">Permitir que os utilizadores acedam à Cortana</span><span class="sxs-lookup"><span data-stu-id="707a3-146">Allow users to access Cortana</span></span>  <br/> |<span data-ttu-id="707a3-p109">A Cortana pode ser bastante útil! Ela pode ativar ou desativar definições automaticamente, dar indicações e certificar-se de que chega a tempo aos seus compromissos, pelo que esta opção é mantida **Ativada** por predefinição.  </span><span class="sxs-lookup"><span data-stu-id="707a3-p109">Cortana can be very helpful! She can turn settings on or off for you, give directions, and make sure you're on time for appointments, so we keep this **On** by default.  </span></span><br/> |
|<span data-ttu-id="707a3-149">Permitir que os utilizadores recebam sugestões e anúncios da Microsoft acerca do Windows</span><span class="sxs-lookup"><span data-stu-id="707a3-149">Allow users to receive Windows tips and advertisements from Microsoft</span></span>  <br/> |<span data-ttu-id="707a3-150">As sugestões do Windows podem ser úteis e ajudar a orientar os utilizadores quando são lançadas novas versões.</span><span class="sxs-lookup"><span data-stu-id="707a3-150">Windows tips can be handy and help orient users when new features are released.</span></span>  <br/> |
|<span data-ttu-id="707a3-151">Manter os dispositivos Windows 10 atualizados automaticamente</span><span class="sxs-lookup"><span data-stu-id="707a3-151">Keep Windows 10 devices up to date automatically</span></span>  <br/> |<span data-ttu-id="707a3-152">Garante que os dispositivos Windows 10 recebem automaticamente as atualizações mais recentes.</span><span class="sxs-lookup"><span data-stu-id="707a3-152">Makes sure that Windows 10 devices automatically receive the latest updates.</span></span>  <br/> |
|<span data-ttu-id="707a3-153">Desligar o ecrã do dispositivo quando estiver inativo durante este período de tempo</span><span class="sxs-lookup"><span data-stu-id="707a3-153">Turn off device screen when idle for this amount of time</span></span>  <br/> |<span data-ttu-id="707a3-p110">Garante que os dados da empresa são protegidos se um utilizador estiver inativo. É possível que um utilizador esteja a trabalhar num local público, como um café, e se afaste ou distraia por um momento, deixando o dispositivo vulnerável a olhares alheios. Esta definição permite-lhe controlar quanto tempo um utilizador pode estar inativo antes de o ecrã se desligar.</span><span class="sxs-lookup"><span data-stu-id="707a3-p110">Makes sure that company data is protected if a user is idle. A user may be working in a public location, like a coffee shop, and step away or be distracted for just a moment, leaving their device vulnerable to random glances. This setting lets you control how long the user can be idle before the screen shuts off.</span></span>  <br/> |
   
  
