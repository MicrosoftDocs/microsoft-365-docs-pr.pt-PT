---
title: Sobre as definições do Perfil AutoPilot
ms.author: sirkkuw
author: Sirkkuw
manager: scotv
audience: Admin
ms.topic: conceptual
f1_keywords:
- ZTDProfileSettings
- O365E_ZTDProfileSettings
- BCS365_ZTDProfileSettings
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
- MOE150
ms.assetid: 99bfbf81-e719-4630-9b0f-c187edfa1f8a
description: Os perfis AutoPilot ajudam a controlar como o Windows é instalado em dispositivos de usuário. Os perfis contêm configurações padrão e opcionais, como pular a instalação cortana.
ms.openlocfilehash: 912a24e3d458986a4bcf7dcf903f80211996aca2
ms.sourcegitcommit: 8193b7da5b1a415835d02ca96883c351df7326ed
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 11/14/2019
ms.locfileid: "38321791"
---
# <a name="about-autopilot-profile-settings"></a><span data-ttu-id="8a86e-104">Sobre as definições do Perfil AutoPilot</span><span class="sxs-lookup"><span data-stu-id="8a86e-104">About AutoPilot Profile settings</span></span>

## <a name="autopilot-profile-settings"></a><span data-ttu-id="8a86e-105">Configurações de perfil do Piloto Automático</span><span class="sxs-lookup"><span data-stu-id="8a86e-105">AutoPilot profile settings</span></span>

<span data-ttu-id="8a86e-106">Você pode usar perfis AutoPilot para controlar como o Windows está instalado em dispositivos do usuário.</span><span class="sxs-lookup"><span data-stu-id="8a86e-106">You can use AutoPilot profiles to control how Windows is installed on user devices.</span></span> <span data-ttu-id="8a86e-107">Os perfis contêm as seguintes configurações.</span><span class="sxs-lookup"><span data-stu-id="8a86e-107">The profiles contain the following settings.</span></span>
  
 <span data-ttu-id="8a86e-108">**Recursos padrão do Piloto Automático (necessários) que são definidos automaticamente:**</span><span class="sxs-lookup"><span data-stu-id="8a86e-108">**AutoPilot default features (required) that are set automatically:**</span></span>
  
|<span data-ttu-id="8a86e-109">**Definição**</span><span class="sxs-lookup"><span data-stu-id="8a86e-109">**Setting**</span></span>|<span data-ttu-id="8a86e-110">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="8a86e-110">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="8a86e-111">Pule o registro Cortana, OneDrive e OEM</span><span class="sxs-lookup"><span data-stu-id="8a86e-111">Skip Cortana, OneDrive, and OEM registration</span></span>  <br/> |<span data-ttu-id="8a86e-112">Ignora a instalação de aplicativos de consumo como cortana e onedrive pessoal.</span><span class="sxs-lookup"><span data-stu-id="8a86e-112">Skips the installation of consumer apps like Cortana and personal OneDrive.</span></span> <span data-ttu-id="8a86e-113">O usuário do dispositivo pode instalá-los mais tarde, desde que o usuário seja um administrador local no dispositivo.</span><span class="sxs-lookup"><span data-stu-id="8a86e-113">The device user can install these later as long as the user is a local admin on the device.</span></span> <span data-ttu-id="8a86e-114">O registro original do fabricante é ignorado porque o dispositivo será gerenciado pela Microsoft 365 Business.</span><span class="sxs-lookup"><span data-stu-id="8a86e-114">The original manufacturer registration is skipped because the device will be managed by Microsoft 365 Business.</span></span>  <br/> |
|<span data-ttu-id="8a86e-115">Assine com experiência com a marca da empresa</span><span class="sxs-lookup"><span data-stu-id="8a86e-115">Sign in experience with your company brand</span></span>  <br/> |<span data-ttu-id="8a86e-116">Se a sua empresa tiver uma [marca da empresa para a página de login do Office 365,](https://support.office.com/article/a1229cdb-ce19-4da5-90c7-2b9b146aef0a)o usuário do dispositivo terá essa experiência ao se inscrever.</span><span class="sxs-lookup"><span data-stu-id="8a86e-116">If your company has a [Add your company branding to Office 365 Sign In page](https://support.office.com/article/a1229cdb-ce19-4da5-90c7-2b9b146aef0a), the device user will get that experience when signing in.</span></span>  <br/> |
|<span data-ttu-id="8a86e-117">MDM auto-inscrição com contas AAD configuradas.</span><span class="sxs-lookup"><span data-stu-id="8a86e-117">MDM auto-enrollment with configured AAD accounts.</span></span>  <br/> |<span data-ttu-id="8a86e-118">A identidade do usuário será gerenciada pelo Diretório Ativo Do Azure, e os usuários entrarão no Windows e no Office 365 com suas credenciais de negócios microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="8a86e-118">The user identity will be managed by Azure Active Directory, and users will sign in to Windows and Office 365 with their Microsoft 365 Business credentials.</span></span>  <br/> |
   
 <span data-ttu-id="8a86e-119">**Configurações opcionais:**</span><span class="sxs-lookup"><span data-stu-id="8a86e-119">**Optional settings:**</span></span>
  
|<span data-ttu-id="8a86e-120">**Definição**</span><span class="sxs-lookup"><span data-stu-id="8a86e-120">**Setting**</span></span>|<span data-ttu-id="8a86e-121">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="8a86e-121">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="8a86e-122">Evite as configurações de privacidade (desafinada por padrão)</span><span class="sxs-lookup"><span data-stu-id="8a86e-122">Skip privacy settings (Off by default)</span></span>  <br/> |<span data-ttu-id="8a86e-123">Se esta opção estiver definida para **on,** o usuário do dispositivo não verá o contrato de licença para o dispositivo e o Windows quando ele ou ela entrar pela primeira vez.</span><span class="sxs-lookup"><span data-stu-id="8a86e-123">If this option is set to **On**, the device user will not see the license agreement for the device and Windows when he or she first signs in.</span></span>  <br/> |
|<span data-ttu-id="8a86e-124">Não permita que o usuário se torne o administrador local</span><span class="sxs-lookup"><span data-stu-id="8a86e-124">Don't allow the user to become the local admin</span></span>  <br/> |<span data-ttu-id="8a86e-125">Se essa opção for definida para **on,** o usuário do dispositivo não será capaz de instalar aplicativos pessoais, como cortana.</span><span class="sxs-lookup"><span data-stu-id="8a86e-125">If this option is set to **On**, the device user will not be able to install any personal apps, such as Cortana.</span></span><br/> |
   
