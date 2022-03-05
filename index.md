# On-Premises SharePoint
## install
* [SharePoint 2016: Step By Step Installation of Workflow Manager](https://social.technet.microsoft.com/wiki/contents/articles/34407.sharepoint-2016-step-by-step-installation-of-workflow-manager.aspx)
* [ネットワーク共有から SharePoint Server の必須コンポーネントをインストールする](https://docs.microsoft.com/ja-jp/sharepoint/install/install-prerequisites-from-network-share)
* [Azure 上で SharePoint Server 2016 をオフラインインストールしてみよう！(後編)](https://blogs.networld.co.jp/entry/azure-sharepoin-7f90)
* [SharePoint Server 2016 のオフライン インストール](https://docs.microsoft.com/ja-jp/archive/blogs/sharepoint_support/sharepoint-server-2016-%E3%81%AE%E3%82%AA%E3%83%95%E3%83%A9%E3%82%A4%E3%83%B3-%E3%82%A4%E3%83%B3%E3%82%B9%E3%83%88%E3%83%BC%E3%83%AB)
* [単一サーバーに SharePoint Server 2016 または SharePoint Server 2019 をインストールする](https://docs.microsoft.com/ja-jp/sharepoint/install/install-sharepoint-server-2016-on-one-server)
* [SharePoint Server 2016 および 2019 を使用した Azure SQL Managed Instance のデプロイ](https://docs.microsoft.com/ja-jp/sharepoint/administration/deploy-azure-sql-managed-instance-with-sharepoint-servers-2016-2019)
* [Azure での高可用性 SharePoint Server 2016 ファームの実行](https://docs.microsoft.com/ja-jp/azure/architecture/reference-architectures/sharepoint/)
## Kerberos
* [Enabling Kerberos on SharePoint](https://thesharepointfarm.com/2017/10/enabling-kerberos-sharepoint/)
    ``` cmd
    setspn -U -S HTTP/sharepoint.example.com CORP\webAppAccount
    ```
* [SharePoint Server で Kerberos 認証を計画する](https://docs.microsoft.com/ja-jp/sharepoint/security-for-sharepoint-server/kerberos-authentication-planning)
## Setting
* [SharePoint 2016 How to Change SuitBar’s Text PowerShell - TechNet Articles - United States (English) - TechNet Wiki](https://social.technet.microsoft.com/wiki/contents/articles/34202.sharepoint-2016-how-to-change-suitbars-text-powershell.aspx)
## Distributed Cache
* [Distributed cache service is not enabled in this deployment (SharePoint Server)](https://docs.microsoft.com/en-us/sharepoint/technical-reference/distributed-cache-service-is-not-enabled-in-this-deployment)
* [Distributed Cache Host error](https://social.technet.microsoft.com/Forums/en-US/35f8fe49-7e4a-4d3e-bb65-ad17b723d8d8/distributed-cache-host-error?forum=SP2016)
* [Troubleshooting Distributed Cache in SharePoint Server 2013](https://vigneshsharepointthoughts.com/2015/10/20/troubleshooting-distributed-cache-in-sharepoint-server-2013/)
* [SharePoint 2013 Distributed Cache: Issue 1. “CacheHostinfo is null”.](https://sharepointjournaldotcom.wordpress.com/tag/sharepoint-distributed-cache/)
* [cacheHostInfo is null when adding a 2nd Distributed Cache](https://social.technet.microsoft.com/Forums/windows/en-US/1a875aa8-b26d-43bd-af67-87d6b24d7ed7/cachehostinfo-is-null-when-adding-a-2nd-distributed-cache?forum=SP2016)
* [Convert a SharePoint 2016 front-end to a front-end with Distributed Cache](https://blog.kuppens-switsers.net/sharepoint/convert-sharepoint-2016-front-end-to-front-end-with-distributed-cache/)
* [SharePoint 2016 Troubleshooting: Configuration Wizard failed with error ‘CacheHostInfo is null’](https://social.technet.microsoft.com/wiki/contents/articles/34617sharepoint-2016-troubleshooting-configuration-wizard-failed-with-error-cachehostinfo-is-null.aspx)
## WorkFlow
* [WorkflowStatus Enum](https://docs.microsoft.com/en-us/dotnet/api/microsoft.sharepoint.workflowservices.workflowstatus?view=sharepoint-server)

## Office Web Apps
* [Office Web Apps で SharePoint上のファイルが開けなくなる (SPWOPIProofKey が更新されないことによる) ](https://social.msdn.microsoft.com/Forums/sqlserver/ja-JP/720a6d3f-f6f4-492c-9195-23a9fed9a90c/office-web-apps-12391?forum=sharepointsupportteamja)

# Microsoft 365
## Audit Log
* [セキュリティ運用ソフトウェア「LogStare Collector 2.2」の提供を開始](https://prtimes.jp/main/html/rd/p/000000070.000038758.html)
* [M365 監査ログ(旧 O365 監査ログ)収集の設定](https://www.secuavail.com/kb/references/ref-220203-01/)
## CSOM
* [再改訂版 SharePoint Online HTTP 調整 (応答コード : 429) 対策の増分バックオフ リトライ](https://social.msdn.microsoft.com/Forums/ja-JP/21e2a628-44be-4541-bca9-b81c484ff59b/20877259133533029256-sharepoint-online-http-3551925972?forum=sharepointsupportteamja)
## Exchagne Online
* [Using Azure Automation to Process Exchange Online Data with PowerShell](https://practical365.com/use-azure-automation-exchange-online/)
* [PowerShellから全社員に予定を投入したい](https://blog.o365mvp.com/2016/12/07/create_calendar_object_via_powershell/)


## SharePoint Online
* [SharePoint Online モダンサイトのホームサイトを設定する](https://idea.tostring.jp/?p=5013)
* [SharePoint ハブ (Hub) を利用しよう](https://shanqiai.weblogs.jp/sharepoint_technical_note/2021/02/sharepoint-hub.html)
* [待望の新たなモダンな SharePoint サイトテンプレート登場 !](https://shanqiai.weblogs.jp/sharepoint_technical_note/2021/04/modern-site-templates.html)
* [File Upload to SharePoint 2013 using REST API](https://stackoverflow.com/questions/25393075/file-upload-to-sharepoint-2013-using-rest-api)

## Power Automate Desktop
* [Windows10の無償デスクトップ自動化ツール「Power Automate Desktop」でWebブラウザーでの作業を自動化する](https://codezine.jp/article/detail/15410)
# Azure
## Azure VM
* [Azure MonitorエージェントによるWindows仮想マシンの監視](https://cloudsteady.jp/post/50812/)
* [Azure環境作ったら最初にやるべきこと 2021年版](https://zenn.dev/tomot/articles/7ddeb902e8f426)
## SQL Managed Instance

* [Azure SQL での Azure AD 認証を構成して管理する](https://docs.microsoft.com/ja-jp/azure/azure-sql/database/authentication-aad-configure?tabs=azure-powershell)
* [クイックスタート: Azure SQL Managed Instance に接続するように Azure VM を構成する](https://docs.microsoft.com/ja-jp/azure/azure-sql/managed-instance/connect-vm-instance-configure)
* [Azureで利用可能なPaaSのSQL Serverの特徴を学ぼう［後編］――Azure SQL DatabaseとAzure SQL Database Managed Instanceの違い](https://atmarkit.itmedia.co.jp/ait/articles/1904/12/news010_2.html)
* [Azureで利用可能なPaaSのSQL Serverの特徴を学ぼう［前編］](https://atmarkit.itmedia.co.jp/ait/articles/1904/01/news010.html)
* [機能の比較: Azure SQL Database と Azure SQL Managed Instance](https://docs.microsoft.com/ja-jp/azure/azure-sql/database/features-comparison)
* [移行の概要: SQL Server から Azure SQL Managed Instance](https://docs.microsoft.com/ja-jp/azure/azure-sql/migration-guides/managed-instance/sql-server-to-managed-instance-overview)
* [Azure Active Directory 認証を使用する](https://docs.microsoft.com/ja-jp/azure/azure-sql/database/authentication-aad-overview)
* [Azure SQL Database と SQL Managed Instance のセキュリティ機能の概要](https://docs.microsoft.com/ja-jp/azure/azure-sql/database/security-overview)
* [Azure SQL Managed Instance とは](https://docs.microsoft.com/ja-jp/azure/azure-sql/managed-instance/sql-managed-instance-paas-overview)
* [クイック スタート: Azure SQL Managed Instance を作成する](https://docs.microsoft.com/ja-jp/azure/azure-sql/managed-instance/instance-create-quickstart)
* [SharePoint Server でユーザー認証方法を計画する](https://docs.microsoft.com/ja-jp/sharepoint/security-for-sharepoint-server/plan-user-authentication)
* [SharePoint Server 2016 での TLS 1.1 および TLS 1.2 のサポートの有効化](https://docs.microsoft.com/ja-jp/sharepoint/security-for-sharepoint-server/enable-tls-1-1-and-tls-1-2-support-in-sharepoint-server-2016)
* [SharePoint 2013 で TLS と SSL のサポートを有効にする](https://docs.microsoft.com/ja-jp/sharepoint/security-for-sharepoint-server/enable-tls-and-ssl-support-in-sharepoint-2013)
* [チュートリアル:Windows VM のシステム割り当てマネージド ID を使用して Azure SQL にアクセスする](https://docs.microsoft.com/ja-jp/azure/active-directory/managed-identities-azure-resources/tutorial-windows-vm-access-sql)
* [データベース接続アップグレード用の SharePoint Server 2016 ファームを作成する](https://docs.microsoft.com/ja-jp/sharepoint/upgrade-and-update/create-the-sharepoint-server-2016-farm-for-a-database-attach-upgrade)

* [マネージド ID を使用して他のサービスにアクセスできる Azure サービス](https://docs.microsoft.com/ja-jp/azure/active-directory/managed-identities-azure-resources/managed-identities-status)
* [Azure リソースのマネージド ID とは](https://docs.microsoft.com/ja-jp/azure/active-directory/managed-identities-azure-resources/overview)


# Web

## html
* [カルーセルUIを実現するJSライブラリまとめ(2021年版) - 導入手間や機能の比較紹介](https://ics.media/entry/210902/)
* [カルーセル](https://codezine.jp/article/detail/8350?p=2)
* [bootstrapのカルーセルの使い方とカスタマイズのサンプルを紹介](https://be-engineer.jp/programming/514/)
* [HTML Living Standard HTML要素チートシート](https://htmlls.docs-share.com/)
* [配色に迷ったらこれ！配色イメージを言語化して論理的に伝えられるスケールがめちゃくちゃ役に立つ「語彙力ない私にうってつけ」 - Togetter](https://togetter.com/li/1744709)
* [Web制作が捗るChrome拡張機能12選 – おすすめの拡張機能を集めてみた | Pulp Note - WebデザインやWebサイト制作の現場で使えるTipsやアイデアを紹介](https://pulpxstyle.com/chrome-extensions/)
* [最近の実装に合わせた最新版HTMLテンプレート、基本構造に使用するすべての要素とその役割も解説 | コリス](https://coliss.com/articles/build-websites/operation/work/html-boilerplate-by-mmatuzo.html)
* [知っておくと実装に役立つ！JavaScriptのテクニックのまとめ](https://coliss.com/articles/build-websites/operation/javascript/javascript-tips-by-garvitmotwani.html)
* [CSSで画像の上に表示するテキストをより読みやすく、より美しくするテクニック・実装方法のまとめ | コリス](https://coliss.com/articles/build-websites/operation/css/handling-text-over-images-in-css.html)
* [アコーディオンのアイコン：どのシグニファイアが最適か – U-Site](https://u-site.jp/alertbox/accordion-icons/)
* [CSSで画像の上に表示するテキストをより読みやすく、より美しくするテクニック・実装方法のまとめ | コリス](https://coliss.com/articles/build-websites/operation/css/handling-text-over-images-in-css.html)
* [地味に便利！さまざまなプロジェクトに適したHTMLのテンプレートを簡単に生成できる -HTML Boilerplates | コリス](https://coliss.com/articles/build-websites/operation/work/html-boilerplates.html)
* [HTML/CSS初学者がつまづきやすい記述ミスと修正方法 | Webクリエイターボックス](https://www.webcreatorbox.com/tech/html-css-beginner)
* [Web制作の効率、生産性アップ！話題の最新オンラインツール33個まとめ - PhotoshopVIP](https://photoshopvip.net/126320)


## css
* [CSSコピペで完成！押したくなるWebボタンデザインまとめ](https://photoshopvip.net/130681)
* [CSSでフォームの実装に悩んだら！ さまざまなフレームワークで実装されたフォームのライブラリ -HeroTofu](https://coliss.com/articles/build-websites/operation/css/html-forms-library-herotofu.html)


## JavaScript

# Adobe
* [Adobe XDをHTMLにエクスポートする方法 - インターネットとソーシャル | 七月 2020](https://ja.rockycode.com/how-export-adobe-xd-html)
* [Adobe XD 2019年8月アップデートリリース！CSSコード自動生成（第一弾）、ローカルでのPhotoshop編集連携、コンポーネントの操作性改善など #AdobeXD | Adobe Blog](https://blogs.adobe.com/japan/cc-web-xd-august-2019-update-auto-css-plugins-panel-more/)
* [Adobe XDの新機能『CSS書き出し』を使ってみよう | studioDoghands](https://www.doghands.com/adobe-xd-css-code-snippets/)
* [Adobe XD 2020年10月の新機能！ついにVisual Studio Codeと連携可能に | コリス](https://coliss.com/articles/build-websites/operation/work/adobe-xd-whats-new-2020-oct.html)

# サイト
* [Microsoft AI ＆ Innovation Center](https://www.microsoft.com/ja-jp/maic)
* [Microsoft Learn | Microsoft Docs](https://docs.microsoft.com/ja-jp/learn/)
