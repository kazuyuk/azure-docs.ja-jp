---
title: Azure Lab Services でクラスルーム ラボにアクセスする | Microsoft Docs
description: このチュートリアルでは、教師によって設定されたクラスルーム ラボ内の仮想マシンにアクセスします。
services: devtest-lab, lab-services, virtual-machines
documentationcenter: na
author: spelluru
manager: ''
editor: ''
ms.service: lab-services
ms.workload: na
ms.tgt_pltfrm: na
ms.devlang: na
ms.topic: tutorial
ms.custom: mvc
ms.date: 01/17/2019
ms.author: spelluru
ms.openlocfilehash: 3ec3abffc7962051f4cfc02d5369581ca193d70e
ms.sourcegitcommit: 5fbca3354f47d936e46582e76ff49b77a989f299
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/12/2019
ms.locfileid: "57775579"
---
# <a name="tutorial-access-a-classroom-lab-in-azure-lab-services"></a>チュートリアル:Azure Lab Services でクラスルーム ラボにアクセスする
このチュートリアルでは、学生がクラスルーム ラボ内の仮想マシン (VM) にアクセスします。 

このチュートリアルでは、次のアクションを実行します。

> [!div class="checklist"]
> * 登録リンクを使用する 
> * 仮想マシンへの接続

## <a name="use-the-registration-link"></a>登録リンクを使用する

1. 教師から受け取った**登録 URL** に移動します。 登録完了後は、登録 URL を使用する必要はありません。 代わりに [https://labs.azure.com](https://labs.azure.com) という URL を使用します。 
1. 学校アカウントを使ってサービスにサインインし、登録を完了します。 
2. 登録した後、アクセスできるラボの仮想マシンが表示されることを確認します。 
3. 仮想マシンの準備が完了するのを待って VM を**起動**します。 このプロセスには、ある程度時間がかかります。  

    ![VM を起動する](../media/tutorial-connect-vm-in-classroom-lab/start-vm.png)

## <a name="connect-to-the-virtual-machine"></a>仮想マシンへの接続

1. アクセスするラボの仮想マシンを表すタイルの **[接続]** を選択します。 

    ![VM への接続](../media/tutorial-connect-vm-in-classroom-lab/connect-vm.png)
2. 次のいずれかの手順を実行します。 
    1. **Windows** 仮想マシンの場合は、**RDP** ファイルをハード ディスクに保存します。 仮想マシンに接続するための RDP ファイルを開きます。 マシンにログインするために教師から提供された**ユーザー名**と**パスワード**を使います。 
    3. **Linux** 仮想マシンの場合は、**[仮想マシンに接続する]** ダイアログ ボックス上で SSH 接続文字列をコピーして保存します。 仮想マシンに接続するには、SSH ターミナル([Putty](https://www.putty.org/) など) からこの接続文字列を使用します。 

## <a name="next-steps"></a>次の手順
このチュートリアルでは、教師から入手した登録リンクを使って、クラスルーム ラボにアクセスしました。

ラボの所有者として、ラボに登録されているユーザーを確認し、VM の使用状況を追跡します。 次のチュートリアルに進み、ラボの使用を追跡する方法を確認してください。

> [!div class="nextstepaction"]
> [ラボの使用状況を追跡する](tutorial-track-usage.md) 