# GetOrgLimits Lightning Components

Get org wide usage/limit using [System.OrgLimits.getMap()](https://releasenotes.docs.salesforce.com/en-us/spring19/release-notes/rn_apex_new_classes_methods.htm) then show them with progress bar.

## Usage

Put Aura Component or LWC on Lightning Page or UtilityBar.

## Included components

- Apex class: GetOrgLimits.cls  
   Server side controller for both aura and Lightning Web Component.
- Aura Component: orgLimits_aura
- Lightning Web Component: orgLimits_lwc

Note: Both Aura Component and LWC work as same. You don't have to install both.

## How to install

Besides installing by metadata api / sfdx command, you can install them as an unlocked package;

- `sfdx force:package:install --package 04t0I000000jDz4QAE`

or

- https://login.salesforce.com/packaging/installPackage.apexp?p0=04t0I000000jDz4QAE

  When you install the package to Sandbox, replace 'login.salesforce.com' with 'test.salesforce.com'.

## Issues

Sometimes System.OrgLimits.getMap() failes with Insufficient Privilege.

---

## Japanese explanations

[System.OrgLimits.getMap()](https://releasenotes.docs.salesforce.com/ja-jp/spring19/release-notes/rn_apex_new_classes_methods.htm) を使用して組織レベルの制限と現在の使用量をバーチャートで表示します。

### 使用法

Aura コンポーネントもしくは Lightning Web コンポーネントを Lightning ページもしくはユーティリティバーに配置してください。

### 含まれるコンポーネント

- Apex class: GetOrgLimits.cls  
   aura/LWC 共通のサーバサイド・コントローラ
- Aura コンポーネント: orgLimits_aura
- Lightning Web コンポーネント: orgLimits_lwc

Note: aura コンポーネントと LWC の機能は全く同じですので、両方を使用する必要はありません。

### インストール方法

git clone して metadata api/sfdx コマンドでインストールする以外にロック解除済パッケージとしてインストールすることができます。

- `sfdx force:package:install --package 04t0I000000jDz4QAE`

あるいは

- https://login.salesforce.com/packaging/installPackage.apexp?p0=04t0I000000jDz4QAE

  Sandbox にインストールするときは'login.salesforce.com' を 'test.salesforce.com' におきかえてください。

![Screen Shot 2019-12-12 at 14 05 19](https://user-images.githubusercontent.com/17230754/70686226-01222d80-1cef-11ea-8ce7-f55376a6b330.png)
