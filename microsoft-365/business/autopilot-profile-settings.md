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
description: Os perfis do AutoPilot ajudam você a controlar como o Windows é instalado em dispositivos de usuário. Os perfis contêm configurações padrão e opcionais, como ignorar a instalação da Cortana.
ms.openlocfilehash: eb0d9a95c796909d024db1d061aaeace7d07ed1b
ms.sourcegitcommit: bd52f7b662887f552f90c46f69d6a2a42fb66914
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 10/17/2019
ms.locfileid: "37574584"
---
# <a name="about-autopilot-profile-settings"></a><span data-ttu-id="5b007-104">Sobre as definições do Perfil AutoPilot</span><span class="sxs-lookup"><span data-stu-id="5b007-104">About AutoPilot Profile settings</span></span>

## <a name="autopilot-profile-settings"></a><span data-ttu-id="5b007-105">Configurações do perfil do AutoPilot</span><span class="sxs-lookup"><span data-stu-id="5b007-105">AutoPilot profile settings</span></span>

<span data-ttu-id="5b007-106">Você pode controlar como o Windows é instalado em dispositivos de usuário usando os perfis do AutoPilot.</span><span class="sxs-lookup"><span data-stu-id="5b007-106">You can control how Windows gets installed on user devices by using the AutoPilot profiles.</span></span> <span data-ttu-id="5b007-107">Os perfis contêm as seguintes configurações.</span><span class="sxs-lookup"><span data-stu-id="5b007-107">The profiles contain the following settings.</span></span>
  
 <span data-ttu-id="5b007-108">**Recursos padrão do AutoPilot (obrigatório) que são definidos automaticamente:**</span><span class="sxs-lookup"><span data-stu-id="5b007-108">**AutoPilot default features (required) that are set automatically:**</span></span>
  
|<span data-ttu-id="5b007-109">**Definição**</span><span class="sxs-lookup"><span data-stu-id="5b007-109">**Setting**</span></span>|<span data-ttu-id="5b007-110">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="5b007-110">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="5b007-111">Ignorar Cortana, OneDrive e registro de OEM</span><span class="sxs-lookup"><span data-stu-id="5b007-111">Skip Cortana, OneDrive and OEM registration</span></span>  <br/> |<span data-ttu-id="5b007-112">Ignora a instalação de aplicativos de consumidor como Cortana e OneDrive pessoal.</span><span class="sxs-lookup"><span data-stu-id="5b007-112">Skips the installation of consumer apps like Cortana and personal OneDrive.</span></span> <span data-ttu-id="5b007-113">O usuário do dispositivo pode instalá-los mais tarde, desde que ele ou ela é um administrador local no dispositivo.</span><span class="sxs-lookup"><span data-stu-id="5b007-113">The device user can install these later as long as he or she is a local admin on the device.</span></span> <span data-ttu-id="5b007-114">O registro original do fabricante é ignorado porque o dispositivo será gerenciado pelo Microsoft 365 Business.</span><span class="sxs-lookup"><span data-stu-id="5b007-114">The original manufacturer registration is skipped because the device will be managed by Microsoft 365 Business.</span></span>  <br/> |
|<span data-ttu-id="5b007-115">Entre em experiência com a sua marca da empresa</span><span class="sxs-lookup"><span data-stu-id="5b007-115">Sign in experience with your company brand</span></span>  <br/> |<span data-ttu-id="5b007-116">Se a sua empresa tiver uma [Adicionar a marca da sua empresa à página de início de sessão do Office 365](https://support.office.com/article/a1229cdb-ce19-4da5-90c7-2b9b146aef0a), o utilizador do dispositivo receberá essa experiência quando iniciar sessão.</span><span class="sxs-lookup"><span data-stu-id="5b007-116">If your company has a [Add your company branding to Office 365 Sign In page](https://support.office.com/article/a1229cdb-ce19-4da5-90c7-2b9b146aef0a), the device user will get that experience when signing in.</span></span>  <br/> |
|<span data-ttu-id="5b007-117">Registro automático do MDM com contas AAD configuradas.</span><span class="sxs-lookup"><span data-stu-id="5b007-117">MDM auto-enrollment with configured AAD accounts.</span></span>  <br/> |<span data-ttu-id="5b007-118">A identidade do usuário será gerenciada pelo Active Directory do Azure e os usuários farão logon no Windows e no Office 365 com suas credenciais do Microsoft 365 Business.</span><span class="sxs-lookup"><span data-stu-id="5b007-118">The user identity will be managed by Azure Active directory, and the users will sign into Windows and Office 365 with their Microsoft 365 Business credentials.</span></span>  <br/> |
   
 <span data-ttu-id="5b007-119">**Configurações opcionais:**</span><span class="sxs-lookup"><span data-stu-id="5b007-119">**Optional settings:**</span></span>
  
|<span data-ttu-id="5b007-120">**Definição**</span><span class="sxs-lookup"><span data-stu-id="5b007-120">**Setting**</span></span>|<span data-ttu-id="5b007-121">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="5b007-121">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="5b007-122">Ignorar configurações de privacidade (desativado por padrão)</span><span class="sxs-lookup"><span data-stu-id="5b007-122">Skip privacy settings (Off by default)</span></span>  <br/> |<span data-ttu-id="5b007-123">Se essa opção estiver definida como **ativado**, o usuário do dispositivo não verá o contrato de licença para o dispositivo e o Windows quando ele ou ela entrar pela primeira vez.</span><span class="sxs-lookup"><span data-stu-id="5b007-123">If this option is set to **On**, the device user will not see the license agreement for the device and Windows when he or she first signs in.</span></span>  <br/> |
|<span data-ttu-id="5b007-124">Não permita que o usuário se torne o administrador local</span><span class="sxs-lookup"><span data-stu-id="5b007-124">Don't allow the user to become the local admin</span></span>  <br/> |<span data-ttu-id="5b007-125">Se essa opção estiver definida como **ativado**, o usuário do dispositivo não poderá instalar nenhum aplicativo pessoal, como a Cortana.</span><span class="sxs-lookup"><span data-stu-id="5b007-125">If this option is set to **On**, the device user will not be able to install any personal apps, such as Cortana.</span></span>  <br/> |
   
