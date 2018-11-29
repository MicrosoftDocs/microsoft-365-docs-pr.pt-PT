---
title: Criar e editar perfis AutoPilot
ms.author: sirkkuw
author: Sirkkuw
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- Adm_O365
- Core_O365Admin_Migration
- MiniMaven
- MSB365
search.appverid:
- BCS160
- MET150
- MOE150
ms.assetid: 5cf7139e-cfa1-4765-8aad-001af1c74faa
description: 'Aprenda a criar, editar, eliminar ou remover perfis de piloto automático. '
ms.openlocfilehash: 4658a27e5f2c64a52f8a7d08b3fc13df5e239dc3
ms.sourcegitcommit: eb1a77e4cc4e8f564a1c78d2ef53d7245fe4517a
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 11/28/2018
ms.locfileid: "26983138"
---
# <a name="create-and-edit-autopilot-profiles"></a>Criar e editar perfis AutoPilot

## <a name="create-a-profile"></a>Criar um perfil

Um perfil aplica-se a um dispositivo ou grupo de dispositivos.
  
1. No centro de administração do Microsoft 365 Business, selecione **Implementar o Windows com o Autopilot** no cartão **Ações do dispositivo**. 
    
    ![On the Device actions card, choose Deploy Windows with Autopilot.](media/160d5c2a-11a8-48f9-a8aa-70f084b85448.png)
  
2. Na página **Preparar Windows**, selecione o separador **Perfis** \> **Criar perfil**.
    
3. Na página **Criar perfil**, introduza um nome para o perfil que o ajude a identificá-lo, por exemplo Marketing, ative a definição que pretende (para obter mais informações, consulte [Sobre as definições do Perfil AutoPilot](autopilot-profile-settings.md)) e selecione **Guardar**.
    
    ![Enter name and turn on settings in the Create profile panel.](media/63b5a00d-6a5d-48d0-9557-e7531e80702a.png)
  
### <a name="apply-profile-to-a-device"></a>Aplicar o perfil a um dispositivo

Depois de criar um perfil, pode aplicá-lo a um dispositivo ou grupo de dispositivos. Pode escolher um perfil existente no [guia passo a passo](add-autopilot-devices-and-profile.md), aplicá-lo a novos dispositivos ou substituir um perfil existente por um dispositivo ou grupo de dispositivos. 
  
1. Na página **Preparar Windows**, selecione o separador **Dispositivos**. 
    
2. Clique na caixa de verificação junto ao nome do dispositivo e, em seguida, no painel **Dispositivo**, selecione um perfil a partir da lista pendente **Perfil atribuído** \> **Guardar**.
    
    ![In the Device panel, select an Assigned profile to apply it.](media/ed0ce33f-9241-4403-a5de-2dddffdc6fb9.png)
  
## <a name="edit-delete-or-remove-a-profile"></a>Editar, eliminar ou remover um perfil

Depois de atribuir um perfil a um dispositivo, pode atualizá-lo, mesmo se já tiver atribuído o dispositivo a um utilizador. Quando o dispositivo for ligado à Internet, irá transferir a versão mais recente do seu perfil durante o processo de configuração. Se o utilizador restaurar o respetivo dispositivo para as predefinições de fábrica, o dispositivo irá transferir novamente as atualizações mais recentes para o seu perfil. 
  
### <a name="edit-a-profile"></a>Editar um perfil

1. Na página **Preparar Windows**, selecione o separador **Perfis**. 
    
2. Clique na caixa de verificação junto ao nome de um dispositivo e, em seguida, no painel **Perfil**, atualize as definições disponíveis \> **Guardar**.
    
    Se o fizer antes de um utilizador ligar o dispositivo à Internet, o perfil será aplicado no processo de configuração.
    
### <a name="delete-a-profile"></a>Eliminar um perfil

1. Na página **Preparar Windows**, selecione o separador **Perfis**. 
    
2. Clique na caixa de verificação junto ao nome de um dispositivo e, em seguida, no painel **Perfil**, clique em **Eliminar perfil** \> **Guardar**.
    
    Quando eliminar um perfil, o mesmo será removido do dispositivo ou grupo de dispositivos ao qual estava atribuído.
    
### <a name="remove-a-profile"></a>Remover um perfil

1. Na página **Preparar Windows**, selecione o separador **Dispositivos**. 
    
2. Clique na caixa de verificação junto ao nome do dispositivo e, em seguida, no painel **Dispositivo**, selecione **Nenhum** na lista pendente **Perfil atribuído** \> **Guardar**.
    
