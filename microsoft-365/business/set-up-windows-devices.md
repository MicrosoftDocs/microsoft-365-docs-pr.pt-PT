---
title: Configurar dispositivos Windows para utilizadores do Microsoft 365 Business
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
ms.assetid: 2d7ff45e-0da0-4caa-89a9-48cabf41f193
description: 'Obter informações sobre como configurar dispositivos do Windows com o Windows 10 Pro para utilizadores empresariais do Microsoft 365. '
ms.openlocfilehash: f93257bd9a68385fca4f178a2e09c5c11506ee2c
ms.sourcegitcommit: 81273a9df49647286235b187fa2213c5ec7e8b62
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 04/23/2019
ms.locfileid: "32284411"
---
# <a name="set-up-windows-devices-for-microsoft-365-business-users"></a><span data-ttu-id="4f354-103">Configurar dispositivos Windows para utilizadores do Microsoft 365 Business</span><span class="sxs-lookup"><span data-stu-id="4f354-103">Set up Windows devices for Microsoft 365 Business users</span></span>

## <a name="prerequisites"></a><span data-ttu-id="4f354-104">Pré-requisitos</span><span class="sxs-lookup"><span data-stu-id="4f354-104">Prerequisites</span></span>

<span data-ttu-id="4f354-p101">Antes de poder configurar dispositivos Windows para os utilizadores do Microsoft 365 Business, certifique-se de que todos os dispositivos Windows estão a executar o Windows 10 Pro, versão 1703 (Atualização para Criativos). O Windows 10 Pro é um pré-requisito para implementar o Windows 10 Business, que é um conjunto de funcionalidades de gestão de dispositivos e serviços na nuvem que complementam o Windows 10 Pro e permitem a gestão centralizada e os controlos de segurança do Microsoft 365 Business.</span><span class="sxs-lookup"><span data-stu-id="4f354-p101">Before you can set up Windows devices for Microsoft 365 Business users, make sure all the Windows devices are running Windows 10 Pro, version 1703 (Creators Update). Windows 10 Pro is a prerequisite for deploying Windows 10 Business, which is a set of cloud services and device management capabilities that complement Windows 10 Pro and enable the centralized management and security controls of Microsoft 365 Business.</span></span>
  
<span data-ttu-id="4f354-107">Se tiver dispositivos Windows a executar o Windows 7 Pro, Windows 8 Pro ou Windows 8.1 Pro, a sua subscrição do Microsoft 365 Business dá-lhe direito a uma atualização do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="4f354-107">If you have Windows devices running Windows 7 Pro, Windows 8 Pro, or Windows 8.1 Pro, your Microsoft 365 Business subscription entitles you to a Windows 10 upgrade.</span></span>
  
<span data-ttu-id="4f354-108">Para obter mais informações sobre como atualizar dispositivos Windows para a Atualização para Criativos do Windows 10 Pro, siga os passos neste tópico: [Atualizar dispositivos Windows para a Atualização para Criativos do Windows Pro](upgrade-to-windows-pro-creators-update.md).</span><span class="sxs-lookup"><span data-stu-id="4f354-108">For more information on how to upgrade Windows devices to Windows 10 Pro Creators Update, follow the steps in this topic: [Upgrade Windows devices to Windows Pro Creators Update](upgrade-to-windows-pro-creators-update.md).</span></span>
  
<span data-ttu-id="4f354-109">Consulte a [verificar o dispositivo está ligado à Azure AD](#verify-the-device-is-connected-to-azure-ad) para verificar que se tem a actualização, ou para se certificar de que a actualização de trabalho.</span><span class="sxs-lookup"><span data-stu-id="4f354-109">See [Verify the device is connected to Azure AD](#verify-the-device-is-connected-to-azure-ad) to verify you have the upgrade, or to make sure the upgrade worked.</span></span> 
  
## <a name="join-windows-10-devices-to-your-organizations-azure-ad"></a><span data-ttu-id="4f354-110">Associar dispositivos Windows 10 ao Azure AD da sua organização</span><span class="sxs-lookup"><span data-stu-id="4f354-110">Join Windows 10 devices to your organization's Azure AD</span></span>

<span data-ttu-id="4f354-p102">Depois de todos os dispositivos Windows na sua organização terem sido atualizados para a Atualização para Criativos do Windows 10 Pro ou se já estiverem a executar a Atualização para Criativos do Windows 10 Pro, pode associar estes dispositivos ao Azure Active Directory da sua organização. Assim que os dispositivos forem associados serão atualizados automaticamente para o Windows 10 Business, que faz parte da sua subscrição do Microsoft 365 Business.</span><span class="sxs-lookup"><span data-stu-id="4f354-p102">Once all Windows devices in your organization have either been upgraded to Windows 10 Pro Creators Update or are already running Windows 10 Pro Creators Update, you can join these devices to your organization's Azure Active Directory. Once the devices are joined, they will automatically be upgraded to Windows 10 Business, which is part of your Microsoft 365 Business subscription.</span></span>
  
### <a name="for-a-brand-new-or-newly-upgraded-windows-10-pro-device"></a><span data-ttu-id="4f354-113">Para um dispositivo Windows 10 Pro novo ou recentemente atualizado</span><span class="sxs-lookup"><span data-stu-id="4f354-113">For a brand new, or newly upgraded, Windows 10 Pro device</span></span>

<span data-ttu-id="4f354-114">Para um novo dispositivo a executar a Atualização para Criativos do Windows 10 Pro ou para um dispositivo que foi atualizado para a Atualização para Criativos do Windows 10 Pro, mas cuja configuração do dispositivo Windows 10 não tenha sido efetuada, siga estes passos.</span><span class="sxs-lookup"><span data-stu-id="4f354-114">For a brand new device running Windows 10 Pro Creators Update, or for a device that was upgraded to Windows 10 Pro Creators Update but has not gone through Windows 10 device setup, follow these steps.</span></span>
  
1. <span data-ttu-id="4f354-115">Efetue a configuração do dispositivo Windows 10 até aceder à página **Como pretende configurar?**.</span><span class="sxs-lookup"><span data-stu-id="4f354-115">Go through Windows 10 device setup until you get to the **How would you like to set up?** page.</span></span> 
    
    ![On the How would you like to set up page, choose Set up for an organization](media/1b0b2dba-00bb-4a99-a729-441479220cb7.png)
  
2. <span data-ttu-id="4f354-117">Selecione **Configurar para uma organização** e, em seguida, introduza o seu nome de utilizador e palavra-passe do Microsoft 365 Business.</span><span class="sxs-lookup"><span data-stu-id="4f354-117">Here, choose **Set up for an organization** and then enter your username and password for Microsoft 365 Business.</span></span> 
    
3. <span data-ttu-id="4f354-118">Conclua a configuração do dispositivo Windows 10.</span><span class="sxs-lookup"><span data-stu-id="4f354-118">Finish Windows 10 device setup.</span></span>
    
   <span data-ttu-id="4f354-p103">Quando terminar, o utilizador estará ligado ao Azure AD da sua organização. Consulte [Verificar se o dispositivo está ligado ao Azure AD](#verify-the-device-is-connected-to-azure-ad) para garantir que o dispositivo está ligado.</span><span class="sxs-lookup"><span data-stu-id="4f354-p103">Once you're done, the user will be connected to your organization's Azure AD. See [Verify the device is connected to Azure AD](#verify-the-device-is-connected-to-azure-ad) to make sure.</span></span> 
  
### <a name="for-a-device-already-set-up-and-running-windows-10-pro"></a><span data-ttu-id="4f354-121">Para um dispositivo que já esteja configurado e a executar o Windows 10 Pro</span><span class="sxs-lookup"><span data-stu-id="4f354-121">For a device already set up and running Windows 10 Pro</span></span>

 <span data-ttu-id="4f354-122">**Ligar utilizadores ao Azure AD:**</span><span class="sxs-lookup"><span data-stu-id="4f354-122">**Connect users to Azure AD:**</span></span>
  
1. <span data-ttu-id="4f354-123">No PC Windows do seu utilizador com o Windows 10 Pro, versão 1703 (Atualização para Criativos) (consulte os [pré-requisitos](pre-requisites-for-data-protection.md)), clique no logótipo do Windows e, em seguida, no ícone Definições.</span><span class="sxs-lookup"><span data-stu-id="4f354-123">In your user's Windows PC, that is running Windows 10 Pro, version 1703 (Creators Update) (see [pre-requisites](pre-requisites-for-data-protection.md)), click the Windows logo, and then the Settings icon.</span></span>
  
   ![In the Start menu, click Windows Settings icon](media/74e1ce9a-1554-4761-beb9-330b176e9b9d.png)
  
2. <span data-ttu-id="4f354-125">Nas **Definições**, aceda a **Contas**.</span><span class="sxs-lookup"><span data-stu-id="4f354-125">In **Settings**, go to **Accounts**.</span></span>
  
   ![In Windows Settings, go to Accounts](media/472fd688-d111-4788-9fbb-56a00fbdc24d.png)
  
3. <span data-ttu-id="4f354-127">Na página **As suas informações**, clique em **Aceder a profiss./escolar** \> **Ligar**.</span><span class="sxs-lookup"><span data-stu-id="4f354-127">On **Your info** page, click **Access work or school** \> **Connect**.</span></span>
  
   ![Choose Connect under Access work or school](media/af3a4e3f-f9b9-4969-b3e2-4ef99308090c.png)
  
4. <span data-ttu-id="4f354-129">Na caixa de diálogo **Configurar uma conta escolar ou profissional**, em **Ações alternativas**, selecione **Adicionar este dispositivo ao Azure Active Directory**.</span><span class="sxs-lookup"><span data-stu-id="4f354-129">On the **Set up a work or school account** dialog, under **Alternate actions**, choose **Join this device to Azure Active Directory**.</span></span>
  
   ![Click Join this device to Azure Active Directory](media/fb709a1b-05a9-4750-9cb9-e097f4412cba.png)
  
5. <span data-ttu-id="4f354-131">Na página **Vamos iniciar a sua sessão**, introduza a sua conta escolar ou profissional \> **Seguinte**.</span><span class="sxs-lookup"><span data-stu-id="4f354-131">On the **Let's get you signed in** page, enter your work or school account \> **Next**.</span></span>
  
   <span data-ttu-id="4f354-132">Na página **Introduzir palavra-passe**, introduza a sua palavra-passe \> **Iniciar sessão**.</span><span class="sxs-lookup"><span data-stu-id="4f354-132">On the **Enter password** page, enter your password \> **Sign in**.</span></span>
  
   ![Enter your work or school email on the Let's get you signed in page](media/f70eb148-b1d2-4ba3-be38-7317eaf0321a.png)
  
6. <span data-ttu-id="4f354-134">Na página **tornar-se de que esta é a sua organização** , certifique-se de que as informações estão correctas e clique em **aderir**.</span><span class="sxs-lookup"><span data-stu-id="4f354-134">On the **Make sure this is your organization** page, verify that the information is correct, and click **Join**.</span></span>
  
   <span data-ttu-id="4f354-p104">Na página **Está pronto!**, clique em **Concluído**.</span><span class="sxs-lookup"><span data-stu-id="4f354-p104">On the **You're all set!** page, click **Done**.</span></span>
  
   ![On the Make sure this is your organization screen, click Join](media/c749c0a2-5191-4347-a451-c062682aa1fb.png)
  
<span data-ttu-id="4f354-p105">Se tiver carregado ficheiros para o OneDrive para Empresas, sincronize-os novamente. Se utilizou uma ferramenta de terceiros para migrar o perfil e os ficheiros, sincronize-os também com o novo perfil.</span><span class="sxs-lookup"><span data-stu-id="4f354-p105">If you uploaded files to OneDrive for Business, sync them back down. If you used a third party tool to migrate profile and files, sync those also to the new profile.</span></span>
  
## <a name="verify-the-device-is-connected-to-azure-ad"></a><span data-ttu-id="4f354-140">Verificar se o dispositivo está ligado ao Azure AD</span><span class="sxs-lookup"><span data-stu-id="4f354-140">Verify the device is connected to Azure AD</span></span>

<span data-ttu-id="4f354-p106">Para verificar o seu estado de sincronização, na página **Aceder a profiss./escolar** nas **Definições**, clique na área **Ligado a** _ \<organization name\> _ para revelar os botões **Informações** e **Desligar**. Clique em **Informações** para obter o seu estado de sincronização.</span><span class="sxs-lookup"><span data-stu-id="4f354-p106">To verify your sync status, on the **Access work or school** page in **Settings**, click in the **Connected to** _ \<organization name\> _ area to expose the buttons **Info** and **Disconnect**. Click on **Info** to get your synchronization status.</span></span> 
  
<span data-ttu-id="4f354-143">Na página Estado de sincronização, clique em Sincronizar para obter as mais recentes políticas de gestão de dispositivos móveis no PC.</span><span class="sxs-lookup"><span data-stu-id="4f354-143">On the Sync status page, click Sync to get the latest mobile device management policies onto the PC.</span></span>
  
<span data-ttu-id="4f354-p107">Para começar a utilizar a conta do Microsoft 365 Business, aceda ao botão **Iniciar** do Windows, clique com o botão direito do rato na imagem da conta atual e, em seguida, em **Mudar de conta**. Inicie sessão com o endereço de e-mail e palavra-passe da sua organização.</span><span class="sxs-lookup"><span data-stu-id="4f354-p107">To start using the Microsoft 365 Business account, go to the Windows **Start** button, right-click your current account picture and then **Switch account**. Sign in by using your organization email and password.</span></span>
  
![Click Info button to view synchronization status](media/818f7043-adbf-402a-844a-59d50034911d.png)
  
## <a name="verify-the-device-is-upgraded-to-windows-10-business"></a><span data-ttu-id="4f354-147">Verificar se o dispositivo foi atualizado para o Windows 10 Business</span><span class="sxs-lookup"><span data-stu-id="4f354-147">Verify the device is upgraded to Windows 10 Business</span></span>

<span data-ttu-id="4f354-148">Verifique se os seus dispositivos Windows 10 associados ao Azure AD foram atualizados para o Windows 10 Business como parte da sua subscrição do Microsoft 365 Business.</span><span class="sxs-lookup"><span data-stu-id="4f354-148">Verify that your Azure AD joined Windows 10 devices were upgraded to Windows 10 Business as part of your Microsoft 365 Business subscription.</span></span>
  
1. <span data-ttu-id="4f354-149">Aceda a **Definições** \> **Sistema** \> **Acerca de**.</span><span class="sxs-lookup"><span data-stu-id="4f354-149">Go to **Settings** \> **System** \> **About**.</span></span>
    
2. <span data-ttu-id="4f354-150">Confirme que a **Edição** apresenta **Windows 10 Business**.</span><span class="sxs-lookup"><span data-stu-id="4f354-150">Confirm that the **Edition** shows **Windows 10 Business**.</span></span>
    
    ![Verify that Windows edition is Windows 10 Business.](media/ff660fc8-d3ba-431b-89a5-f5abded96c4d.png)
  
## <a name="next-steps"></a><span data-ttu-id="4f354-152">Next steps</span><span class="sxs-lookup"><span data-stu-id="4f354-152">Next steps</span></span>

<span data-ttu-id="4f354-153">Para configurar os seus dispositivos móveis, consulte [Configurar dispositivos móveis para utilizadores do Microsoft 365 Business](set-up-mobile-devices.md). Para definir políticas de proteção de aplicações ou proteção de dispositivos, consulte [Gerir o Microsoft 365 Business](manage.md).</span><span class="sxs-lookup"><span data-stu-id="4f354-153">To set up your mobile devices, see [Set up mobile devices for Microsoft 365 Business users](set-up-mobile-devices.md), To set device protection or app protection policies, see [Manage Microsoft 365 Business](manage.md).</span></span>
  