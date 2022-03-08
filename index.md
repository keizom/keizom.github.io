# On-Premises SharePoint
## install
* [SharePoint 2016: Step By Step Installation of Workflow Manager](https://social.technet.microsoft.com/wiki/contents/articles/34407.sharepoint-2016-step-by-step-installation-of-workflow-manager.aspx)
* [ネットワーク共有から SharePoint Server の必須コンポーネントをインストールする](https://docs.microsoft.com/ja-jp/sharepoint/install/install-prerequisites-from-network-share)
* [Azure 上で SharePoint Server 2016 をオフラインインストールしてみよう！(後編)](https://blogs.networld.co.jp/entry/azure-sharepoin-7f90)
* [SharePoint Server 2016 のオフライン インストール](https://docs.microsoft.com/ja-jp/archive/blogs/sharepoint_support/sharepoint-server-2016-%E3%81%AE%E3%82%AA%E3%83%95%E3%83%A9%E3%82%A4%E3%83%B3-%E3%82%A4%E3%83%B3%E3%82%B9%E3%83%88%E3%83%BC%E3%83%AB)
* [単一サーバーに SharePoint Server 2016 または SharePoint Server 2019 をインストールする](https://docs.microsoft.com/ja-jp/sharepoint/install/install-sharepoint-server-2016-on-one-server)
* [SharePoint Server 2016 および 2019 を使用した Azure SQL Managed Instance のデプロイ](https://docs.microsoft.com/ja-jp/sharepoint/administration/deploy-azure-sql-managed-instance-with-sharepoint-servers-2016-2019)
* [Azure での高可用性 SharePoint Server 2016 ファームの実行](https://docs.microsoft.com/ja-jp/azure/architecture/reference-architectures/sharepoint/)
## SharePoint 高可用性構成
* [Azure での高可用性 SharePoint Server 2016 ファームの実行](https://docs.microsoft.com/ja-jp/azure/architecture/reference-architectures/sharepoint/)
* [高可用性 SharePoint ファーム](https://docs.microsoft.com/ja-jp/azure/architecture/solution-ideas/articles/highly-available-sharepoint-farm)
* [Azure で SharePoint Server 2016 と SQL Server の AlwaysOn 可用性グループを展開する](https://docs.microsoft.com/ja-jp/SharePoint/administration/deploying-sharepoint-server-2016-with-sql-server-alwayson-availability-groups-in)
* [Azure における SharePoint 2013 開発/テスト環境](https://docs.microsoft.com/ja-jp/sharepoint/administration/sharepoint-2013-dev-test-environments-in-azure)

## 代替アクセスマッピング
* [SharePoint Server の代替アクセス マッピングを構成する](https://docs.microsoft.com/ja-jp/sharepoint/administration/configure-alternate-access-mappings)
* [SharePoint Server の代替アクセス マッピングを計画する](https://docs.microsoft.com/ja-jp/sharepoint/administration/plan-alternate-access-mappings)
* [SharePoint Server 2013 の構成 － 代替アクセスマッピング](https://yama30501.blog.fc2.com/blog-entry-134.html)
* [パスベース および ホスト名付きサイト コレクションの構築](https://www.slideshare.net/aiyamasaki528/path-based-and-host-named-site-collection)
* []()


## サーバー自身からの接続方法
* [Windows Authentication Errors on local Servers (Loopback Protection)](https://webconnection.west-wind.com/docs/_4gi0ql5jb.htm)
* [ホストヘッダーを利用する場合の注意事項](https://shanqiai.weblogs.jp/sharepoint_technical_note/2010/05/%E3%83%9B%E3%82%B9%E3%83%88%E3%83%98%E3%83%83%E3%83%80%E3%83%BC%E3%82%92%E5%88%A9%E7%94%A8%E3%81%99%E3%82%8B%E5%A0%B4%E5%90%88%E3%81%AE%E6%B3%A8%E6%84%8F%E4%BA%8B%E9%A0%85.html)
## Kerberos
* [Enabling Kerberos on SharePoint](https://thesharepointfarm.com/2017/10/enabling-kerberos-sharepoint/)
    ``` cmd
    setspn -U -S HTTP/sharepoint.example.com CORP\webAppAccount
    ```
* [SharePoint Server で Kerberos 認証を計画する](https://docs.microsoft.com/ja-jp/sharepoint/security-for-sharepoint-server/kerberos-authentication-planning)
## Setting
* [SharePoint 2016 How to Change SuitBar’s Text PowerShell - TechNet Articles - United States (English) - TechNet Wiki](https://social.technet.microsoft.com/wiki/contents/articles/34202.sharepoint-2016-how-to-change-suitbars-text-powershell.aspx)

## Search Service Application
* [Remove a SharePoint Search Server from the Search Service Application](https://microscoff.com/2018/05/24/remove-sharepoint-search-server-search-service-application/)
* [How to remove the Search Topology (Removing Existing SSA with PowerShell)](https://collab365.com/removing-search-topology-removing-existing-ssa/)
* [How To Configure Search Service Application Using PowerShell](https://www.c-sharpcorner.com/article/sharepoint-2016-how-to-configure-search-service-application-using-powershell/)

## SSL
* [SharePoint 2013 のサイトを SSL 通信（https）でもアクセスできるよう構成する](https://sharepointmaniacs.com/archives/4416)
* [SharePoint Server 2016 での TLS 1.1 および TLS 1.2 のサポートの有効化](https://docs.microsoft.com/ja-jp/sharepoint/security-for-sharepoint-server/enable-tls-1-1-and-tls-1-2-support-in-sharepoint-server-2016)
* [IIS 8 または 7.5 での SSL の設定](https://help.sap.com/viewer/5377d77f068843799cdc630e678a755d/4.2.4/ja-JP/ec9ee4136fdb101497906a7cb0e91070.html)
* [サーバーからサーバーへの接続Microsoft 365構成SharePointする](https://docs.microsoft.com/ja-jp/sharepoint/hybrid/configure-inbound-connectivity)
* [SP2013 SSL 証明書の管理と SharePoint アプリ](https://shanqiai.weblogs.jp/sharepoint_technical_note/2014/12/sp2013-ssl-certification-and-sharepointapps.html)

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

## Developer Subscription
* [Microsoft 365 開発者サンドボックス サブスクリプションの設定](https://docs.microsoft.com/ja-jp/office/developer-program/microsoft-365-developer-program-get-started)
* [今すぐ Microsoft 365 開発者プログラムに参加しましょう!](https://developer.microsoft.com/ja-jp/microsoft-365/dev-program)

