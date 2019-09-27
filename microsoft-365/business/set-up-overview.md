---
title: Visão geral da configurar
ms.author: sirkkuw
author: Sirkkuw
manager: scotv
audience: Admin
ms.topic: article
f1_keywords:
- O365E_M365SetupBanner
- BCS365_M365SetupBanner
ms.service: o365-administration
localization_priority: Normal
ms.collection:
- Adm_O365
- M365-subscription-management
ms.custom: OKR_SMB_M365
search.appverid:
- BCS160
- MET150
ms.assetid: 6e7a2dfd-8ec4-4eb7-8390-3ee103e5fece
description: Visão geral das etapas de configurar para o Microsoft 365 Business.
ms.openlocfilehash: f156d236a783942ec06d457c9b7ca087d12d6f58
ms.sourcegitcommit: 6003d6da0a85c97357eb3dba3918eb145f381fe1
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 09/27/2019
ms.locfileid: "37288581"
---
# <a name="overview-of-setup"></a><span data-ttu-id="d343e-103">Visão geral da configuração</span><span class="sxs-lookup"><span data-stu-id="d343e-103">Overview of setup</span></span>

<span data-ttu-id="d343e-104">A maioria das etapas de configuração pode ser feita no assistente de instalação, mas as outras opções também são listadas.</span><span class="sxs-lookup"><span data-stu-id="d343e-104">Most of the set up steps can be done in the setup wizard, but the other options are also listed.</span></span>


## <a name="step-1-add-your-domain-and-users"></a><span data-ttu-id="d343e-105">Etapa 1: adicionar seu domínio e usuários</span><span class="sxs-lookup"><span data-stu-id="d343e-105">Step 1: Add your domain and users</span></span>

   - <span data-ttu-id="d343e-106">**[Adicione seu domínio](set-up.md#add-your-domain-to-personalize-sign-in)** (se você comprou seu domínio durante a [inscrição](sign-up.md), essa etapa já está feita.)</span><span class="sxs-lookup"><span data-stu-id="d343e-106">**[Add your domain](set-up.md#add-your-domain-to-personalize-sign-in)** (if you bought your domain during [sign up](sign-up.md), this step is already done.)</span></span>

    - <span data-ttu-id="d343e-107">**Adicionar usuários**.</span><span class="sxs-lookup"><span data-stu-id="d343e-107">**Add users**.</span></span> <span data-ttu-id="d343e-108">Você pode fazer isso em qualquer uma das três maneiras:</span><span class="sxs-lookup"><span data-stu-id="d343e-108">You can do this in any of the three ways:</span></span>
        - <span data-ttu-id="d343e-109">No [Assistente](set-up.md#add-users-in-the-wizard).</span><span class="sxs-lookup"><span data-stu-id="d343e-109">In the [wizard](set-up.md#add-users-in-the-wizard).</span></span>
        - <span data-ttu-id="d343e-110">Use a sincronização de diretórios para [Adicionar usuários usando o Azure ad Connect](https://docs.microsoft.com/office365/enterprise/set-up-directory-synchronization) se você tiver um Active Directory local.</span><span class="sxs-lookup"><span data-stu-id="d343e-110">Use directory synchronization to [add users by using Azure AD Connect](https://docs.microsoft.com/office365/enterprise/set-up-directory-synchronization) if you have an on-premises Active directory.</span></span>
        - <span data-ttu-id="d343e-111">Você também pode [Adicionar usuários posteriormente](add-users-m365b.md) no centro de administração.</span><span class="sxs-lookup"><span data-stu-id="d343e-111">You can also [add users later](add-users-m365b.md) in the admin center.</span></span>
## <a name="step-2-set-up-security-policies-and-configure-devices"></a><span data-ttu-id="d343e-112">Etapa 2: configurar políticas de segurança e configurar dispositivos</span><span class="sxs-lookup"><span data-stu-id="d343e-112">Step 2: Set up security policies and configure devices</span></span> 

  - <span data-ttu-id="d343e-113">Use o [Assistente de instalação](set-up.md#set-up-security-policies-and-device-configurations) para configurar diretivas de segurança e dispositivo.</span><span class="sxs-lookup"><span data-stu-id="d343e-113">Use the [Setup wizard](set-up.md#set-up-security-policies-and-device-configurations) to configure device and security policies.</span></span> 
  - <span data-ttu-id="d343e-114">Você também pode adicionar mais ou editá-los posteriormente no [centro de administração](view-policies-and-devices.md) e no [portal do Intune](https://docs.microsoft.com/intune/tutorial-walkthrough-intune-portal).</span><span class="sxs-lookup"><span data-stu-id="d343e-114">You can also add more or edit them later in the [admin center](view-policies-and-devices.md) and in the [Intune portal](https://docs.microsoft.com/intune/tutorial-walkthrough-intune-portal).</span></span>
  - <span data-ttu-id="d343e-115">Além das configurações de segurança no assistente de instalação, você pode aumentar sua segurança adicionando as seguintes configurações:</span><span class="sxs-lookup"><span data-stu-id="d343e-115">In addition to the security settings in the setup wizard, you can increase your security by adding the following settings:</span></span>

      - <span data-ttu-id="d343e-116">**Proteção contra malware por e-mail**</span><span class="sxs-lookup"><span data-stu-id="d343e-116">**Email malware protection**</span></span>
      - <span data-ttu-id="d343e-117">**Links seguros de proteção avançada contra ameaças (ATP)**</span><span class="sxs-lookup"><span data-stu-id="d343e-117">**Advanced Threat Protection (ATP) Safe links**</span></span>
      - <span data-ttu-id="d343e-118">**Anexos seguros ATP**</span><span class="sxs-lookup"><span data-stu-id="d343e-118">**ATP Safe Attachments**</span></span>
      - <span data-ttu-id="d343e-119">**ATP anti-phishing**</span><span class="sxs-lookup"><span data-stu-id="d343e-119">**ATP anti-phishing**</span></span>
      - <span data-ttu-id="d343e-120">**Arquivo do Exchange Online**</span><span class="sxs-lookup"><span data-stu-id="d343e-120">**Exchange Online Archiving**</span></span>
      - <span data-ttu-id="d343e-121">**Prevenção de perda de dados (DLP)**</span><span class="sxs-lookup"><span data-stu-id="d343e-121">**Data Loss Prevention (DLP)**</span></span>
      - <span data-ttu-id="d343e-122">**Proteção de informações do Azure (Plan1**)</span><span class="sxs-lookup"><span data-stu-id="d343e-122">**Azure Information Protection (Plan1**)</span></span>

          <span data-ttu-id="d343e-123">Para começar a ver, [Configure políticas de segurança avançadas](set-up-advanced-security.md).</span><span class="sxs-lookup"><span data-stu-id="d343e-123">To get started see, [set up advanced security policies](set-up-advanced-security.md).</span></span>

        <span data-ttu-id="d343e-124">Consulte também as [10 principais maneiras de proteger seu Microsoft 365 Business](https://docs.microsoft.com/office365/admin/security-and-compliance/secure-your-business-data) para obter um roteiro das melhores práticas de segurança.</span><span class="sxs-lookup"><span data-stu-id="d343e-124">See also [top 10 ways to secure your Microsoft 365 Business](https://docs.microsoft.com/office365/admin/security-and-compliance/secure-your-business-data) for a roadmap of best security practices.</span></span>

## <a name="step-3-set-up-and-manage-windows-10-devices"></a><span data-ttu-id="d343e-125">Etapa 3: configurar e gerenciar dispositivos Windows 10</span><span class="sxs-lookup"><span data-stu-id="d343e-125">Step 3: Set up and manage Windows 10 devices</span></span>

   <span data-ttu-id="d343e-126">Quando você ingressar em um dispositivo Windows 10 para o Azure AD, as diretivas configuradas na [etapa 2](#step-2-set-up-security-policies-and-configure-devices) são aplicadas a ele.</span><span class="sxs-lookup"><span data-stu-id="d343e-126">When you join a Windows 10 device to Azure AD, the policies you set up in [Step 2](#step-2-set-up-security-policies-and-configure-devices) get applied to it.</span></span>

   - <span data-ttu-id="d343e-127">O Windows 10 pro é um [pré-requisito](pre-requisites-for-data-protection.md) para o Microsoft 365 Business, mas se você tiver o Windows 7 Pro, o Windows 8 Pro ou o Windows 8,1 Pro, sua assinatura lhe dará direito a uma [atualização para o Windows 10 pro](https://docs.microsoft.com/microsoft-365/business/upgrade-to-windows-pro-creators-update).</span><span class="sxs-lookup"><span data-stu-id="d343e-127">Windows 10 Pro is a [pre-requisite](pre-requisites-for-data-protection.md) for Microsoft 365 Business, but if you have Windows 7 Pro, Windows 8 Pro, or Windows 8.1 Pro, your subscription entitles you to an [upgrade to  Windows 10 Pro](https://docs.microsoft.com/microsoft-365/business/upgrade-to-windows-pro-creators-update).</span></span>
    - <span data-ttu-id="d343e-128">Utilize o [Assistente de configuração](set-up.md#set-up-security-policies-and-device-configurations) para configurar políticas para dispositivos Windows 10.</span><span class="sxs-lookup"><span data-stu-id="d343e-128">Use the [setup wizard](set-up.md#set-up-security-policies-and-device-configurations) to configure policies for Windows 10 devices.</span></span>

## <a name="stes-4-install-office-365-business"></a><span data-ttu-id="d343e-129">Stes 4: instalar o Office 365 Business</span><span class="sxs-lookup"><span data-stu-id="d343e-129">Stes 4: Install Office 365 Business</span></span>
- <span data-ttu-id="d343e-130">Você pode instalar automaticamente o Office nos dispositivos Windows usando o [Assistente de instalação](set-up.md#deploy-office-365-client-apps).</span><span class="sxs-lookup"><span data-stu-id="d343e-130">You can automatically install Office in the Windows devices by using the [setup wizard](set-up.md#deploy-office-365-client-apps).</span></span>
- <span data-ttu-id="d343e-131">Instale automaticamente o [Office](auto-install-or-uninstall-office.md) a partir do centro de administração.</span><span class="sxs-lookup"><span data-stu-id="d343e-131">Automatically [install Office](auto-install-or-uninstall-office.md) from the admin center.</span></span>
- <span data-ttu-id="d343e-132">Permita que os usuários [instalem aplicativos do Office](https://docs.microsoft.com/office365/admin/setup/install-applications) para Windows e dispositivos.</span><span class="sxs-lookup"><span data-stu-id="d343e-132">Let users [install Office apps](https://docs.microsoft.com/office365/admin/setup/install-applications) for Windows and devices.</span></span>
     
## <a name="advanced"></a><span data-ttu-id="d343e-133">Avançado</span><span class="sxs-lookup"><span data-stu-id="d343e-133">Advanced</span></span>
- <span data-ttu-id="d343e-134">**Utilizar o piloto automático para configurar novos dispositivos**</span><span class="sxs-lookup"><span data-stu-id="d343e-134">**Use Autopilot to set up new devices**</span></span>
            
     <span data-ttu-id="d343e-135">Você pode usar o [Windows AutoPilot](add-autopilot-devices-and-profile.md) para pré-configurar automaticamente **novos** dispositivos Windows 10 para um usuário, mas pode ser mais fácil obter um [parceiro](https://www.microsoft.com/solution-providers/search) que pode fazer isso por você.</span><span class="sxs-lookup"><span data-stu-id="d343e-135">You can use [Windows Autopilot](add-autopilot-devices-and-profile.md) to automatically pre-configure **new** Windows 10 devices for a user, but it might be easier to get a [partner](https://www.microsoft.com/solution-providers/search) who can do this for you.</span></span> <span data-ttu-id="d343e-136">Você também pode ir para a [Microsoft Store](https://go.microsoft.com/fwlink/?linkid=874598) e pedir a um especialista em tecnologia de nuvem que configure novos dispositivos que você compra para você.</span><span class="sxs-lookup"><span data-stu-id="d343e-136">You can also go to [Microsoft Store](https://go.microsoft.com/fwlink/?linkid=874598) and ask a cloud technology expert set up new devices you purchase for you.</span></span>

- <span data-ttu-id="d343e-137">**Acessar recursos locais**</span><span class="sxs-lookup"><span data-stu-id="d343e-137">**Access on-premises resources**</span></span>

     - <span data-ttu-id="d343e-138">Se sua organização usa o Active Directory do Windows Server no local, você pode configurar o Microsoft 365 Business para proteger seus dispositivos Windows 10, enquanto ainda mantém o acesso a recursos locais que exigem autenticação local.</span><span class="sxs-lookup"><span data-stu-id="d343e-138">If your organization uses Windows Server Active Directory on-premises, you can set up Microsoft 365 Business to protect your Windows 10 devices, while still maintaining access to on-premises resources that require local authentication.</span></span> <span data-ttu-id="d343e-139">Siga as etapas em [habilitar dispositivos do Windows 10 ingressados no domínio para serem gerenciados pelo Microsoft 365 Business](manage-windows-devices.md) para configurá-lo.</span><span class="sxs-lookup"><span data-stu-id="d343e-139">Follow the steps in [Enable domain-joined Windows 10 devices to be managed by Microsoft 365 Business](manage-windows-devices.md) to set this up.</span></span> <span data-ttu-id="d343e-140">Esse é o método preferencial e os dispositivos nesse estado são chamados de dispositivos ingressados no Azure AD híbrido.</span><span class="sxs-lookup"><span data-stu-id="d343e-140">This is the preferred method and devices in this state are called Hybrid Azure AD joined devices.</span></span>

    - <span data-ttu-id="d343e-141">Se sua empresa tiver um Active Directory local que contenha alguns recursos locais (como compartilhamentos de arquivos e impressoras), você poderá conceder a seus dispositivos associados ao AD do Azure acesso a esses recursos seguindo as etapas aqui: [acessar recursos locais de um Dispositivo ingressado no Azure AD no Microsoft 365 Business](access-resources.md).</span><span class="sxs-lookup"><span data-stu-id="d343e-141">If your business has a local Active Directory that contains some on-premises resources (such as file shares and printers) , you can give your Azure AD-joined devices access to these resources by following the steps here: [Access on-premises resources from an Azure AD-joined device in Microsoft 365 Business](access-resources.md).</span></span>

  