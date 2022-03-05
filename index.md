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
* [CSOM SharePoint Online – Detailed Guide](https://www.spguides.com/sharepoint-csom-tutorial/)
* [Enjoy SharePointGet all subsites from a site collection in SharePoint Online using](https://www.enjoysharepoint.com/get-all-subsites-in-sharepoint-online-csom/)
* [Create client side People Picker control in SharePoint Online Office 365](https://www.enjoysharepoint.com/how-to-use-client-side-people-picker-control-in-sharepoint-online-office-365/)
* [Microsoft Flow Send approval email when a new item is added in SharePoint Online Office 365](https://www.enjoysharepoint.com/microsoft-flow-send-approval-email/)
* [Get list items using Rest API in SharePoint Online/2013/2016](https://www.enjoysharepoint.com/get-sharepoint-list-items-using-rest-api/)
* [How to rename SharePoint 2013 group using browser and PowerShell?](https://www.enjoysharepoint.com/how-to-rename-sharepoint-2013-group-using-browser-and-powershell/)
* [Check if user belongs to SharePoint group using CSOM](https://www.enjoysharepoint.com/check-if-user-belongs-to-sharepoint-group-using-csom/)
* [Get list items using Rest API in SharePoint Online/2013/2016](https://www.enjoysharepoint.com/get-sharepoint-list-items-using-rest-api)
* [Microsoft Flow Send approval email when a new item is added in SharePoint Online Office 365](https://www.enjoysharepoint.com/microsoft-flow-send-approval-email/)

## Exchagne Online
* [Using Azure Automation to Process Exchange Online Data with PowerShell](https://practical365.com/use-azure-automation-exchange-online/)
* [PowerShellから全社員に予定を投入したい](https://blog.o365mvp.com/2016/12/07/create_calendar_object_via_powershell/)
## SharePoint Online
* [SharePoint Online モダンサイトのホームサイトを設定する](https://idea.tostring.jp/?p=5013)
* [SharePoint ハブ (Hub) を利用しよう](https://shanqiai.weblogs.jp/sharepoint_technical_note/2021/02/sharepoint-hub.html)
* [待望の新たなモダンな SharePoint サイトテンプレート登場 !](https://shanqiai.weblogs.jp/sharepoint_technical_note/2021/04/modern-site-templates.html)
* [File Upload to SharePoint 2013 using REST API](https://stackoverflow.com/questions/25393075/file-upload-to-sharepoint-2013-using-rest-api)
* [SharePoint Online: Start Workflow on All Items in a List using PowerShell - SharePoint Diary](https://www.sharepointdiary.com/2018/05/sharepoint-online-start-workflow-using-powershell.html)
* [SharePoint Framework 開発入門 まとめ - SharePoint Developer](https://sharepoint.orivers.jp/sharepoint-framework-dev)
* [SPFxCalendar 1.5.3 を公開しました - からめもぶろぐ。](https://blog.karamem0.jp/entry/2020/10/15/180000)
* [Tree view navigation using PnP Treeview control in the SharePoint Framework (SPFx) web part – RAVICHANDRAN BLOG](https://ravichandran.blog/2020/05/14/tree-view-navigation-using-pnp-treeview-control-in-the-sharepoint-framework-spfx-web-part/)
* [SharePoint SharePoint webhook の概要](https://docs.microsoft.com/ja-jp/sharepoint/dev/apis/webhooks/overview-sharepoint-webhooks)
* [PowerShell SiteScriptでテスト用の環境を作成する](https://www.micknabewata.com/entry/sharepoint/template)
* [モダンページのページレイアウトの種類と変更方法](http://sharepoint.orivers.jp/article/10031)
* [SharePoint Framework (SPFx) Extensions Application Customizer Example - SharePointSky](https://www.sharepointsky.com/spfx-application-customizer/)
* [Fiddler を使って HTTPS トラフィックを確認する](https://idea.tostring.jp/?p=1077)
## Dynamics 365
* [Dynamics 365 自習書シリーズ](https://www.microsoft.com/ja-jp/biz/dynamics/learning.aspx)
* [Demos for MPN Partners – Microsoft 365, Dynamics 365, Teams etc](https://support.microsoft.com/)
* [Dynamics 365 Business Centralの標準機能のソースコードを見る方法について](https://zhublog.wixsite.com/dynamics365/post/dynamics-365-business-central%E3%81%AE%E6%A8%99%E6%BA%96%E6%A9%9F%E8%83%BD%E3%81%AE%E3%82%BD%E3%83%BC%E3%82%B9%E3%82%B3%E3%83%BC%E3%83%89%E3%82%92%E8%A6%8B%E3%82%8B%E6%96%B9%E6%B3%95%E3%81%AB%E3%81%A4%E3%81%84%E3%81%A6)
* [Community demo – Calling Dynamics 365 CRM APIs from SharePoint - YouTube](https://www.youtube.com/watch?v=VXzYc6cfjuI&app=desktop)
* [Dynamics 365 トライアル環境の取得 （2020年9月版） - YouTube](https://m.youtube.com/watch?feature=youtu.be&v=2vXTJK623TU)
* [Dynamics 365の無料トレーニング](https://www.microsoft.com/ja-jp/events/top/training-days/dynamics365)
* [Power Platform + Dynamics 365 + CDS + Azure](https://www.pbc.co.jp/event/d365bc-week202009/)
## Power Automate Desktop
* [Windows10の無償デスクトップ自動化ツール「Power Automate Desktop」でWebブラウザーでの作業を自動化する](https://codezine.jp/article/detail/15410)
## Power Automate
* [Azure活用！Power Automateならノーコードで顔写真から年齢や性別が判断できる！ハンズオンイベント！](https://rpa-bank.com/column/40730)
* [202009_PowerAutomate_Handson](https://github.com/rnakamuramartiny/Share_RPACommunity/tree/master/202009_PowerAutomate_Handson)
* [RPA勉強会！Power Automate Talk #7 ～ハンズオンで勤怠報告ボタン作成！～ (2020/11/27 19:30〜)](https://rpacommunity.connpass.com/event/195217/)
* [Power AutomateでRPAにトライ！！  SIOS Tech. Lab](https://tech-lab.sios.jp/archives/18486)
* [Power Automate（旧Microsoft Flow）からMicrosoft TeamsへBotで投稿する方法3種をまとめてみた - Qiita](https://qiita.com/tfunakoshi/items/76029bcc8ac1d4d9bd71)
* [Power Automate でスクリプトの使用を開始する - Office Scripts  Microsoft Docs](https://docs.microsoft.com/ja-jp/office/dev/scripts/tutorials/excel-power-automate-manual)
* [Azure活用！Power Automateならノーコードで顔写真から年齢や性別が判断できる！ハンズオンイベント！](https://rpa-bank.com/column/40730/)
* [Power Automate で処理に失敗した際にどのアクションで失敗したかを即時にメール通知する方法 - 欲しいアプリは自分で作る！](https://jn.hateblo.jp/entry/2020/10/31/174431)
* [RPA機能の Power Automate Desktop 一般公開（GA）とプロセスアドバイザーの公開 - 吉田の備忘録](https://memo.tyoshida.me/power-platform/power-automate/power-automate-desktop-general-availability/)
* [Power Platformでアプリを作ろう、まずはPower Automateでデータ収集  日経クロステック（xTECH）](https://xtech.nikkei.com/atcl/nxt/column/18/01549/020100002/)
* [マイクロソフトがPower Automateの機能を強化するProcess Advisorを公開、反復の多い作業のワークフローを効率化](https://jp.techcrunch.com/2020/12/10/2020-12-09-microsoft-brings-new-process-mining-features-to-power-automate/)
* [Power Automate でデバッグする際のTips - MoreBeerMorePower](https://mofumofupower.hatenablog.com/entry/2020/11/17/224059)
* [Power Automate のフローで SharePoint リストアイテムの権限を操作してみる  idea.toString();](https://idea.tostring.jp/?p=5427)
* [Power Automate の Apply to each 内でOffice Script を使うときの注意点? - SharePoint Technical Notes](https://shanqiai.weblogs.jp/sharepoint_technical_note/2020/10/using_office_script_with_powerautomate.html)
* [Power Automate で組織の連絡先のメールアドレスから所属グループを抽出する - 欲しいアプリは自分で作る！](https://jn.hateblo.jp/entry/2020/08/23/003210)
* [Windows 10 で開発環境を設定する](https://docs.microsoft.com/ja-jp/windows/dev-environment/overview)
* [Power Automate を使って予定表リスト(イベントリスト)から Microsoft Teams 会議を作成する](https://shanqiai.weblogs.jp/sharepoint_technical_note/2020/09/create-teamsmeeting-from-eventlist-onspo-using-powerautomate.html)
* [Power Automate のフローで SharePoint リストアイテムの権限を操作してみる](https://idea.tostring.jp/?p=5427)
* [Power Automate Teams上で承認を行う](https://zezeze.hateblo.jp/entry/2019/11/29/040113)
# Azure
## Azure VM
* [Azure MonitorエージェントによるWindows仮想マシンの監視](https://cloudsteady.jp/post/50812/)
* [Azure環境作ったら最初にやるべきこと 2021年版](https://zenn.dev/tomot/articles/7ddeb902e8f426)

## Azure vNET
* [Azure SQLDabase にプライベートなネットワークからアクセスしてみよう ★ ](https://blog.nextscape.net/archives/Date/2018/02/serviceendpointsqldb)
* [仮想ネットワークを使用してApp ServiceからAzure Sql Databaseへのアクセスを保護する方法](https://www.it-swarm.dev/ja/azure/%E4%BB%AE%E6%83%B3%E3%83%8D%E3%83%83%E3%83%88%E3%83%AF%E3%83%BC%E3%82%AF%E3%82%92%E4%BD%BF%E7%94%A8%E3%81%97%E3%81%A6app-service%E3%81%8B%E3%82%89azure-sql-database%E3%81%B8%E3%81%AE%E3%82%A2%E3%82%AF%E3%82%BB%E3%82%B9%E3%82%92%E4%BF%9D%E8%AD%B7%E3%81%99%E3%82%8B%E6%96%B9%E6%B3%95/838275760/)
* [aaSにプライベート接続を提供する サービスエンドポイント とは？](https://www.cloudou.net/virtual-network/vnet017/)

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


# Visual Studio
* [続：Postman 使ってたけど VSCode の REST Client に乗り換えた - かずきのBlog@hatena](https://blog.okazuki.jp/entry/2019/07/14/104313)
* [Visual Studio 2019 で入れてる基本的な 拡張機能 - BEACHSIDE BLOG](https://blog.beachside.dev/entry/2019/04/08/204500)
* [VSCodeのオススメ拡張機能 24 選 (とTipsをいくつか) - Qiita](https://qiita.com/sensuikan1973/items/74cf5383c02dbcd82234)
* [Visual Studio CodeでGitHubの複数アカウントを使い分ける - Qiita](https://qiita.com/ykoizumi0903/items/44e24d4180ae931552ce)
* [VSCodeでのGitの基本操作まとめ - Qiita](https://qiita.com/y-tsutsu/items/2ba96b16b220fb5913be)
* [Visual Studio CodeでGitHubリポジトリを「読む」のに便利な拡張機能が登場 - 窓の杜](https://forest.watch.impress.co.jp/docs/news/1331439.html)

# Web

## html
* [よく使われるレイアウトやUIコンポーネント、それだけを実装するためのHTMLとCSSのシンプルなコードのまとめ](https://coliss.com/articles/build-websites/operation/css/popular-layouts-and-patterns-made-with-css.html)
* [カルーセルUIを実現するJSライブラリまとめ(2021年版) - 導入手間や機能の比較紹介](https://ics.media/entry/210902/)
* [カルーセル](https://codezine.jp/article/detail/8350?p=2)
* [bootstrapのカルーセルの使い方とカスタマイズのサンプルを紹介](https://be-engineer.jp/programming/514/)
* [HTML Living Standard HTML要素チートシート](https://htmlls.docs-share.com/)
* [配色に迷ったらこれ！配色イメージを言語化して論理的に伝えられるスケールがめちゃくちゃ役に立つ「語彙力ない私にうってつけ」 - Togetter](https://togetter.com/li/1744709)
* [Web制作が捗るChrome拡張機能12選 – おすすめの拡張機能を集めてみた  Pulp Note - WebデザインやWebサイト制作の現場で使えるTipsやアイデアを紹介](https://pulpxstyle.com/chrome-extensions/)
* [最近の実装に合わせた最新版HTMLテンプレート、基本構造に使用するすべての要素とその役割も解説  コリス](https://coliss.com/articles/build-websites/operation/work/html-boilerplate-by-mmatuzo.html)
* [知っておくと便利なHTML5の機能、要素や属性のまとめ  コリス](https://coliss.com/articles/build-websites/operation/work/10-useful-html5-features.html)
* [知っておくと実装に役立つ！JavaScriptのテクニックのまとめ](https://coliss.com/articles/build-websites/operation/javascript/javascript-tips-by-garvitmotwani.html)
* [CSSで画像の上に表示するテキストをより読みやすく、より美しくするテクニック・実装方法のまとめ  コリス](https://coliss.com/articles/build-websites/operation/css/handling-text-over-images-in-css.html)
* [アコーディオンのアイコン：どのシグニファイアが最適か – U-Site](https://u-site.jp/alertbox/accordion-icons/)
* [CSSで画像の上に表示するテキストをより読みやすく、より美しくするテクニック・実装方法のまとめ  コリス](https://coliss.com/articles/build-websites/operation/css/handling-text-over-images-in-css.html)
* [地味に便利！さまざまなプロジェクトに適したHTMLのテンプレートを簡単に生成できる -HTML Boilerplates  コリス](https://coliss.com/articles/build-websites/operation/work/html-boilerplates.html)
* [HTML/CSS初学者がつまづきやすい記述ミスと修正方法  Webクリエイターボックス](https://www.webcreatorbox.com/tech/html-css-beginner)
* [Web制作の効率、生産性アップ！話題の最新オンラインツール33個まとめ - PhotoshopVIP](https://photoshopvip.net/126320)
* [コードを書くのが楽になる！知っておくと便利なVS Codeの機能・設定のまとめ  コリス ](https://coliss.com/articles/build-websites/operation/work/vs-code-dont-need-extensions.html)
* [初心者向け！HTML/CSSのコーディング手順をイチからしっかりと。  Webクリエイターボックス](https://www.webcreatorbox.com/tech/html-css-coding-steps)
* [新しくなったBootstrap 5を使用して、管理画面のUIを実装する方法を解説  コリス](https://coliss.com/articles/build-websites/operation/work/bootstrap-5-dashboard-tutorial.html)
* [Responsive Height Design -レスポンシブを高さの観点から、Webサイトやスマホアプリの実装で役立つテクニック](https://coliss.com/articles/build-websites/operation/css/responsive-height-design.html)
* [これなら簡単で便利！最近見かけるCSSのさまざまなコンポーネントをコピペで利用できる -CodyHouse Framework  コリス](https://coliss.com/articles/build-websites/operation/css/codyhouse-framework-2-0.html)
* [VS Codeの見やすいテーマが登場！GitHubのデザインでコードも快適に -GitHub VS Code theme  コリス](https://coliss.com/articles/build-websites/operation/work/github-vscode-theme.html)
* [Bootstrap 5の作業環境の構築方法、jQueryを使用しないJavaScriptでの実装方法を解説  コリス](https://coliss.com/articles/build-websites/operation/work/bootstrap-5-tutorial-without-jquery.html)
* [JavaScriptでのメディアクエリ、matchMedia()の使い方を解説  コリス](https://coliss.com/articles/build-websites/operation/javascript/javascript-media-queries.html)
* [新しくなったBootstrap 5を使用して、管理画面のUIを実装する方法を解説  コリス](https://coliss.com/articles/build-websites/operation/work/bootstrap-5-dashboard-tutorial.html)
* [JavaScriptでのメディアクエリ、matchMedia()の使い方を解説  コリス](https://coliss.com/articles/build-websites/operation/javascript/javascript-media-queries.html)
* [Webページやスマホアプリでよく使用される代表的な5つのレイアウトをCSS Gridで実装するテクニック  コリス](https://coliss.com/articles/build-websites/operation/css/css-grid-with-5-layouts.html)
* [2020年、オンラインサービスやWebアプリの開発を独学で勉強したい人に役立つ練習プロジェクトのまとめ  コリス](https://coliss.com/articles/build-websites/operation/work/8-projects-with-modern-designs.html)
* [JavaScriptでのメディアクエリ、matchMedia()の使い方を解説  コリス](https://coliss.com/articles/build-websites/operation/javascript/javascript-media-queries.html)
* [HTMLのtableにクラスを加えるだけで、グラフやチャートを簡単に実装できるCSSのフレームワーク -Charts.css](https://coliss.com/articles/build-websites/operation/css/charts-css-for-data-visualization.html)
* [Web制作者は要チェック！最近のランディングページで見かけるデザインやアイデアのまとめ -SaaS Pages](https://coliss.com/articles/build-websites/operation/work/collection-of-the-best-landing-pages.html)
## css
* [CSSコピペで完成！押したくなるWebボタンデザインまとめ](https://photoshopvip.net/130681)
* [CSSでフォームの実装に悩んだら！ さまざまなフレームワークで実装されたフォームのライブラリ -HeroTofu](https://coliss.com/articles/build-websites/operation/css/html-forms-library-herotofu.html)
* [CSSだけでできるあんなことこんなこと - Qiita](https://qiita.com/rana_kualu/items/43e8841a4fccb8a80113)
* [Amazonも！有名WebサイトのCSSボタンデザイン77個をコピペ再現できる Copy ＆ Paste CSS](https://photoshopvip.net/129699)
* [Web制作者は要チェック！Instagramに使用されているCSSのテクニック](https://coliss.com/articles/build-websites/operation/css/css-techniques-used-for-instagram.html)
* [初心者向け！HTML/CSSのコーディング手順をイチからしっかりと。  Webクリエイターボックス](https://www.webcreatorbox.com/tech/html-css-coding-steps)

## JavaScript
# Docker
* [「Visual Studio Code」で「WSL 2」上のリモートコンテナを使用するには、Microsoftが解説：Windows 10でDocker Desktop Stableを効果的に活用する - ＠IT](https://www.atmarkit.co.jp/ait/articles/2007/10/news138.html)
* [モダンな帳票アプリを作る前に知っておきたい、Docker＋.NET開発の基本](https://codezine.jp/article/detail/15506)
* [Windows 10 Homeでも使えて、インストールも超簡単な「Docker Desktop for Windows」登場 (1/2)：Windows 10 The Latest - ＠IT](https://www.atmarkit.co.jp/ait/articles/2011/20/news015.html)
* [【連載】WSL2、Visual Studio Code、DockerでグッとよくなるWindows開発環境 〜 その1：まずは概要 〜  SIOS Tech. Lab](https://tech-lab.sios.jp/archives/21023)
* [Docker と Kubernetes でアプリをコンテナーに入れる](https://azure.microsoft.com/ja-jp/resources/containerize-your-apps-with-docker-and-kubernetes/)
* [Docker と Kubernetes を使ったコンテナのデプロイ、スケーリング、オーケストレーション、管理Docker とKubernetes によるアプリのコンテナ化](https://azure.microsoft.com/mediahandler/files/resourcefiles/containerize-your-apps-with-docker-and-kubernetes/ja-jp/JA-JP-Containerize_your_Apps_with_Docker_and_Kubernetes.pdf)
* [AzureAD ログインと Docker for Windows Shared Drive によるボリュームマウント - tech.guitarrapc.cóm](https://tech.guitarrapc.com/entry/2017/12/27/042458)
* [Installing docker on azure virtual machine windows 10 - Stack Overflow](https://stackoverflow.com/questions/44817161/installing-docker-on-azure-virtual-machine-windows-10)
* [【連載】世界一わかりみが深いコンテナ & Docker入門 〜 その1:コンテナってなに？ 〜  SIOS Tech. Lab](https://tech-lab.sios.jp/archives/18811)
* [第3回　Dockerコマンドの使い方：超入門Docker - ＠IT](https://www.atmarkit.co.jp/ait/articles/1702/01/news061.html)
* [ゼロからはじめるDocker(1) Dockerとは？  マイナビニュース](https://news.mynavi.jp/article/docker-1/)
* [WSL2をインストールしてWindowsでUbuntuを使う方法](https://tombomemo.com/wsl2-install-settings/)
# Adobe
* [Adobe XDをHTMLにエクスポートする方法 - インターネットとソーシャル  七月 2020](https://ja.rockycode.com/how-export-adobe-xd-html)
* [Adobe XD 2019年8月アップデートリリース！CSSコード自動生成（第一弾）、ローカルでのPhotoshop編集連携、コンポーネントの操作性改善など #AdobeXD  Adobe Blog](https://blogs.adobe.com/japan/cc-web-xd-august-2019-update-auto-css-plugins-panel-more/)
* [Adobe XDの新機能『CSS書き出し』を使ってみよう  studioDoghands](https://www.doghands.com/adobe-xd-css-code-snippets/)
* [Adobe XD 2020年10月の新機能！ついにVisual Studio Codeと連携可能に  コリス](https://coliss.com/articles/build-websites/operation/work/adobe-xd-whats-new-2020-oct.html)
* [Adobe XDでWebデザインをしよう！画面作成からページ推移までの手順を紹介  Webクリエイターボックス](https://www.webcreatorbox.com/inspiration/adobe-xd-steps)
* [VS CodeのAdobe XD用拡張機能が登場！デザインシステムにもとづきコード出力と補完が可能に](https://ics.media/entry/210107/)
* [Adobe XDとBootstrapで作業を効率化 第2回: UIキットをデザインシステムLiteのデザインガイドに落とし込む](https://blogs.adobe.com/japan/adobe-xd-bootstrap-designsytem-lite-2-uikit/)
* [「Adobe XD」のデザインを「Flutter」のコードに変換するプラグインが一般公開 - 窓の杜](https://forest.watch.impress.co.jp/docs/news/1279609.html)

# サイト
* [Microsoft AI ＆ Innovation Center](https://www.microsoft.com/ja-jp/maic)
* [Microsoft Learn  Microsoft Docs](https://docs.microsoft.com/ja-jp/learn/)

