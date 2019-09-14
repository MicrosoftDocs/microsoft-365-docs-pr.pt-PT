---
title: Acessar recursos locais de um dispositivo ingressado no Azure AD no Microsoft 365 Business
ms.author: sirkkuw
author: Sirkkuw
manager: scotv
audience: Admin
ms.topic: article
ms.service: o365-administration
ms.collection: M365-subscription-management
localization_priority: Normal
ms.custom:
- Core_O365Admin_Migration
- MiniMaven
- MSB365
search.appverid:
- BCS160
- MET150
ms.assetid: b0f4d010-9fd1-44d0-9d20-fabad2cdbab5
description: Saiba como obter acesso a recursos locais, como aplicativos de linha de negócios, compartilhamentos de arquivos e impressoras de um dispositivo do Windows 10 ingressado no Azure Active Directory.
ms.openlocfilehash: ab9049e78617372463b8446dc8f8bc0089d8c117
ms.sourcegitcommit: 91ff1d4339f0f043c2b43997d87d84677c79e279
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 09/14/2019
ms.locfileid: "36981667"
---
# <a name="access-on-premises-resources-from-an-azure-ad-joined-device-in-microsoft-365-business"></a><span data-ttu-id="f6a0b-103">Acessar recursos locais de um dispositivo ingressado no Azure AD no Microsoft 365 Business</span><span class="sxs-lookup"><span data-stu-id="f6a0b-103">Access on-premises resources from an Azure AD-joined device in Microsoft 365 Business</span></span>

<span data-ttu-id="f6a0b-104">Qualquer dispositivo Windows 10 que é o Azure Active Directory ingressado terá acesso a todos os recursos baseados em nuvem, como seus aplicativos do Office 365 e pode ser protegido pelo Microsoft 365 Business.</span><span class="sxs-lookup"><span data-stu-id="f6a0b-104">Any Windows 10 device that is Azure Active Directory joined will have access to all cloud-based resources such as your Office 365 apps and can be protected by Microsoft 365 Business.</span></span> <span data-ttu-id="f6a0b-105">Para permitir também o acesso a recursos locais, como aplicativos LOB (linha de negócios), compartilhamentos de arquivos e impressoras, você deve sincronizar seu Active Directory local com o Azure Active Directory usando o [Azure ad Connect](https://docs.microsoft.com/en-us/azure/active-directory/connect/active-directory-aadconnect).</span><span class="sxs-lookup"><span data-stu-id="f6a0b-105">To also allow access to on-premises resources like Line Of Business (LOB) apps, file shares, and printers, you must synchronize your on-premises Active Directory with Azure Active Directory by using [Azure AD Connect](https://docs.microsoft.com/en-us/azure/active-directory/connect/active-directory-aadconnect).</span></span> <span data-ttu-id="f6a0b-106">O vídeo a seguir detalha as etapas de como configurá-lo para o cenário mais comum.</span><span class="sxs-lookup"><span data-stu-id="f6a0b-106">The following video details the steps for how to set this up for the most common scenario.</span></span>
 
> [!VIDEO https://www.microsoft.com/videoplayer/embed/RE3C9hO]

<span data-ttu-id="f6a0b-107">Consulte [introdução ao gerenciamento de dispositivos no Azure Active Directory](https://docs.microsoft.com/en-us/azure/active-directory/device-management-introduction) para saber mais.</span><span class="sxs-lookup"><span data-stu-id="f6a0b-107">See [Introduction to device management in Azure Active Directory](https://docs.microsoft.com/en-us/azure/active-directory/device-management-introduction) to learn more.</span></span>
<span data-ttu-id="f6a0b-108">As etapas também são resumidas nas seções a seguir.</span><span class="sxs-lookup"><span data-stu-id="f6a0b-108">The steps are also summarized in the following sections.</span></span>

## <a name="run-azure-ad-connect"></a><span data-ttu-id="f6a0b-109">Executar o Azure AD Connect</span><span class="sxs-lookup"><span data-stu-id="f6a0b-109">Run Azure AD Connect</span></span>

<span data-ttu-id="f6a0b-110">Conclua as etapas a seguir para permitir que os dispositivos ingressados no Azure AD da sua organização acessem recursos locais.</span><span class="sxs-lookup"><span data-stu-id="f6a0b-110">Complete the following steps to enable your organization's Azure AD joined devices to access on-premises resources.</span></span>
  
1. <span data-ttu-id="f6a0b-111">Para sincronizar os utilizadores, grupos e contactos do Active Directory local para o Azure Active Directory, execute o assistente de sincronização de directórios e o Azure AD Connect conforme descrito em [Configurar a sincronização de directórios para o Office 365](https://support.office.com/article/1b3b5318-6977-42ed-b5c7-96fa74b08846).</span><span class="sxs-lookup"><span data-stu-id="f6a0b-111">To synchronize your users, groups and contacts from local Active Directory into Azure Active Directory, run the Directory synchronization wizard and Azure AD Connect as described in [Set up directory synchronization for Office 365](https://support.office.com/article/1b3b5318-6977-42ed-b5c7-96fa74b08846).</span></span>
    
2. <span data-ttu-id="f6a0b-112">Após a conclusão da sincronização de diretórios, certifique-se de que os dispositivos Windows 10 da sua organização estejam ingressados no Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f6a0b-112">After the directory synchronization has completed, make sure your organization's Windows 10 devices are Azure AD joined.</span></span> <span data-ttu-id="f6a0b-113">Esta etapa é feita individualmente em cada dispositivo Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f6a0b-113">This step is done individually on each Windows 10 device.</span></span> <span data-ttu-id="f6a0b-114">Consulte [configurar dispositivos Windows para usuários do Microsoft 365 Business](set-up-windows-devices.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="f6a0b-114">See [Set up Windows devices for Microsoft 365 Business users](set-up-windows-devices.md) for details.</span></span> 
    
3. <span data-ttu-id="f6a0b-115">Depois que os dispositivos Windows 10 são ingressados no Azure AD, cada usuário deve reiniciar seus dispositivos e fazer logon com suas credenciais do Microsoft 365 Business.</span><span class="sxs-lookup"><span data-stu-id="f6a0b-115">Once the Windows 10 devices are Azure AD joined, each user should reboot their devices and login with their Microsoft 365 Business credentials.</span></span> <span data-ttu-id="f6a0b-116">Todos os dispositivos agora terão acesso a recursos locais também.</span><span class="sxs-lookup"><span data-stu-id="f6a0b-116">All devices will now have access to on-premises resources as well.</span></span>
    
<span data-ttu-id="f6a0b-117">Não são necessárias etapas adicionais para obter acesso a recursos locais para dispositivos ingressados no Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f6a0b-117">No additional steps are required to get access to on-premises resources for Azure AD joined devices.</span></span> <span data-ttu-id="f6a0b-118">Esta é a funcionalidade incorporada disponível no Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f6a0b-118">This is built-in functionality available in Windows 10.</span></span> 
  
<span data-ttu-id="f6a0b-119">Se sua organização não estiver pronta para implantar na configuração de dispositivo ingressado no Azure AD descrita acima, considere configurar a [configuração de dispositivo ingressado no Azure ad híbrida](manage-windows-devices.md).</span><span class="sxs-lookup"><span data-stu-id="f6a0b-119">If your organization is not ready to deploy in the Azure AD Joined Device Configuration described above, consider setting up [Hybrid Azure AD Joined device configuration](manage-windows-devices.md).</span></span>
  
### <a name="considerations-when-joining-your-windows-devices-to-azure-ad"></a><span data-ttu-id="f6a0b-120">Considerações ao ingressar em seus dispositivos Windows no Azure AD</span><span class="sxs-lookup"><span data-stu-id="f6a0b-120">Considerations when joining your Windows devices to Azure AD</span></span>

<span data-ttu-id="f6a0b-121">Se você estiver ingressado no Azure AD em um dispositivo Windows que tenha sido associado ao domínio anteriormente ou em um grupo de trabalho, você precisará considerar as seguintes limitações:</span><span class="sxs-lookup"><span data-stu-id="f6a0b-121">If you are Azure AD joining a Windows device that has previously been domain-joined or in a workgroup, you need to consider the following limitations:</span></span>
  
- <span data-ttu-id="f6a0b-122">Quando um dispositivo do Azure AD ingressa, ele cria um novo usuário sem referenciar um perfil existente.</span><span class="sxs-lookup"><span data-stu-id="f6a0b-122">When a device Azure AD joins, it creates a new user without referencing an existing profile.</span></span> <span data-ttu-id="f6a0b-123">Para corrigir isso, os perfis precisam ser migrados manualmente.</span><span class="sxs-lookup"><span data-stu-id="f6a0b-123">To fix this, profiles need to be manually migrated.</span></span> <span data-ttu-id="f6a0b-124">Um perfil de usuário contém informações como favoritos, arquivos locais, configurações do navegador, configurações do menu Iniciar, etc. A melhor abordagem é encontrar uma ferramenta de terceiros para mapear arquivos e configurações existentes para o novo perfil</span><span class="sxs-lookup"><span data-stu-id="f6a0b-124">A user profile contains information like favorites, local files, browser settings, Start menu settings, etc. A best approach is to find a third-party tool to map existing files and settings to the new profile</span></span>

- <span data-ttu-id="f6a0b-125">Se o dispositivo estiver usando objetos de diretiva de grupo (GPO), alguns GPOs podem não ter um [provedor de](https://docs.microsoft.com/windows/configuration/provisioning-packages/how-it-pros-can-use-configuration-service-providers) serviços de configuração (CSP) comparável no Intune.</span><span class="sxs-lookup"><span data-stu-id="f6a0b-125">If the device is using Group Policy Objects (GPO), some GPOs may not have a comparable [Configuration Service Provider](https://docs.microsoft.com/windows/configuration/provisioning-packages/how-it-pros-can-use-configuration-service-providers) (CSP) in Intune.</span></span> <span data-ttu-id="f6a0b-126">Execute a [ferramenta Mmat](https://www.microsoft.com/download/details.aspx?id=45520) para localizar CSPs comparáveis para GPOs existentes.</span><span class="sxs-lookup"><span data-stu-id="f6a0b-126">Run the [MMAT tool](https://www.microsoft.com/download/details.aspx?id=45520) to find comparable CSPs for existing GPOs.</span></span>

- <span data-ttu-id="f6a0b-127">Os usuários não poderão se autenticar em aplicativos que dependem da autenticação do Active Directory.</span><span class="sxs-lookup"><span data-stu-id="f6a0b-127">Users will not be able to authenticate to applications that depend on Active Directory authentication.</span></span> <span data-ttu-id="f6a0b-128">Para lidar com isso, avalie o uso de um aplicativo herdado e considere a atualização para um aplicativo que usa o auth moderno, se possível.</span><span class="sxs-lookup"><span data-stu-id="f6a0b-128">To deal with this evaluate using a legacy app and consider updating to an app that uses modern Auth if possible.</span></span>

- <span data-ttu-id="f6a0b-129">Descoberta de impressora do Active Directory não funcionará.</span><span class="sxs-lookup"><span data-stu-id="f6a0b-129">Active Directory printer discovery will not work.</span></span> <span data-ttu-id="f6a0b-130">Para corrigir isso, forneça caminhos de impressora diretos para todos os usuários ou aproveite a [impressão de nuvem híbrida](https://docs.microsoft.com/windows-server/administration/hybrid-cloud-print/hybrid-cloud-print-deploy).</span><span class="sxs-lookup"><span data-stu-id="f6a0b-130">To fix this, provide direct printer paths for all users or leverage [Hybrid Cloud Print](https://docs.microsoft.com/windows-server/administration/hybrid-cloud-print/hybrid-cloud-print-deploy).</span></span>
