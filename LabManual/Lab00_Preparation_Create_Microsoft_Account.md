---
lab:
    title: 'Preparation'
    learning path: '-'
    module: '-'
---

# ラボ 準備: Microsoftアカウントを作成する

## ラボ シナリオ

AzureADを使用した演習では「Microsoftアカウント」または「Azureアカウント」が必要になります。

ここでは、Microsoftアカウントを作成する手順を紹介します。



### タスク 1 - Azure AD テナントを作成する

1. Webブラウザを開き「[https://account.windowsazure.com/organization](https://account.windowsazure.com/organization)」にアクセスします。

2. 「Azure を開始する」画面で下記の情報を入力し、「次へ」をクリックします。

    > 注:メールアドレスは講師から指定されたアドレスを入力してください。
    >
    > 　 XXXXはご自身のメールアドレス番号になります。
    >
    > 　　例 `ctc0000@outlook.jp` など

    >参考:ご自身で試す場合は、outlookなどのフリーメールを用意してください。
    >
    >　 　Outlook :  [https://outlook.live.com/](https://outlook.live.com/)

    | 項目                   | 値                                                |
    | ---------------------- | ------------------------------------------------- |
    | お住まいの国または地域 | 日本                                              |
    | 姓                     | ctc                                               |
    | 名                     | XXXX                                              |
    | 勤務先のメールアドレス | `ctcXXXX@outlook.jp`                              |
    | 勤務先の電話番号       | あなたの電話番号(ビジネス/プライベートいずれも可) |
    | 会社名                 | Fabrikam Corporation                              |
    | 組織の規模             | 1人                                               |

    ![aad-sso-001](C:\Users\otokita\Documents\AzureAD-SSO-Provisioning\LabManual\media\aad-sso-001.BMP)

    

3. 「ユーザー ID の作成」画面で、下記の情報を入力し、「ユーザーIDの作成」をクリックします。

    > 注: XXXXはご自身のメールアドレス番号になります。

    | 項目       | 値           |
    | ---------- | ------------ |
    | ユーザー名 | admin        |
    | 会社名     | ctcXXXX      |
    | パスワード | Pa55w.rd1234 |

    ![aad-sso-002](C:\Users\otokita\Documents\AzureAD-SSO-Provisioning\LabManual\media\aad-sso-002.BMP)

    

4. 「ID を検証します」画面が表示されます。携帯電話の番号を入力し、「自分にテキストメッセージを送信(SMS確認)をクリックします。

    > 注:音声電話認証でも構いません。

    ![aad-sso-003](C:\Users\otokita\Documents\AzureAD-SSO-Provisioning\LabManual\media\aad-sso-003.BMP)

    

5. 「ID を検証します」画面で、SMSで受信した番号を入力し、「アカウントの作成」をクリックします。

    ![aad-sso-004](C:\Users\otokita\Documents\AzureAD-SSO-Provisioning\LabManual\media\aad-sso-004.BMP)

    

6. 「この情報を保存してください。」画面で、「サインインページ」と「ユーザーID」をメモし、「準備が整いました」をクリックします。

    ![aad-sso-005](C:\Users\otokita\Documents\AzureAD-SSO-Provisioning\LabManual\media\aad-sso-005.BMP)

     

7. 「Azure 無料アカウントの作成」画面が表示されますが、一度ブラウザを閉じます。

    > 注:画面を進めるとクレジットカード登録が必要になります。
    >
    > 　 Azure ADの検証において、Azureサブスクリプションは必要ありません。

    ![aad-sso-006](C:\Users\otokita\Documents\AzureAD-SSO-Provisioning\LabManual\media\aad-sso-006.BMP)

    

### タスク 2 - Azureにサインインする

1. Webブラウザを開き、「[https://portal.azure.com](https://portal.azure.com)」へアクセスします。

2. サインインが求められます。以下のユーザー名とパスワードを入力し、サインインしてください。

    > 注:XXXXはご自身のメールアドレス番号になります。

    | 項目                      | 値                              |
    | ------------------------- | :------------------------------ |
    | メール、電話、またはskype | `admin@ctcXXXX.onmicrosoft.com` |
    | パスワード                | Pa55w.rd1234                    |

    ![aad-sso-007](C:\Users\otokita\Documents\AzureAD-SSO-Provisioning\LabManual\media\aad-sso-007.BMP)

    

3. Azure Portalにサインインできました。

    > 注：必要に応じて「ツアーの開始」をしてください。




事前準備は完了しました。各Labページより演習を実施してください。
