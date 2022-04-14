# Bookmarks

* [site](https://keizom.github.io/)
* [onpremise](https://keizom.github.io/onpremise.html)
* [Adobe](https://keizom.github.io/adobe.html)
* [Azure](https://keizom.github.io/Azure.html)
* [develop](https://keizom.github.io/develop.html)
* [intune](https://keizom.github.io/intune.html)
* [Office365](https://keizom.github.io/Office365.html)
* [web](https://keizom.github.io/web.html)

# SharePoint Server

* [SharePoint Server の認証の概要](https://docs.microsoft.com/ja-jp/sharepoint/security-for-sharepoint-server/authentication-overview)

## install

* [SharePoint Server 2016 MinRole 構成メモ](https://www.illuminate-j.jp/blog/sharepoint-server-2016-minrole)
* [SharePoint Server 2016 単一サーバー (検証) 環境構成メモ](https://www.illuminate-j.jp/blog/sharepoint-server-2016-config)
* [SharePoint 2016: Step By Step Installation of Workflow Manager](https://social.technet.microsoft.com/wiki/contents/articles/34407.sharepoint-2016-step-by-step-installation-of-workflow-manager.aspx)
* [ネットワーク共有から SharePoint Server の必須コンポーネントをインストールする](https://docs.microsoft.com/ja-jp/sharepoint/install/install-prerequisites-from-network-share)
* [Azure 上で SharePoint Server 2016 をオフラインインストールしてみよう！(後編)](https://blogs.networld.co.jp/entry/azure-sharepoin-7f90)
* [SharePoint Server 2016 のオフライン インストール](https://docs.microsoft.com/ja-jp/archive/blogs/sharepoint_support/sharepoint-server-2016-%E3%81%AE%E3%82%AA%E3%83%95%E3%83%A9%E3%82%A4%E3%83%B3-%E3%82%A4%E3%83%B3%E3%82%B9%E3%83%88%E3%83%BC%E3%83%AB)
* [単一サーバーに SharePoint Server 2016 または SharePoint Server 2019 をインストールする](https://docs.microsoft.com/ja-jp/sharepoint/install/install-sharepoint-server-2016-on-one-server)
* [SharePoint Server 2016 単一サーバー (検証) 環境構成メモ](https://www.illuminate-j.jp/blog/sharepoint-server-2016-config)

## SharePoint 高可用性構成

* [Azure での高可用性 SharePoint Server 2016 ファームの実行](https://docs.microsoft.com/ja-jp/azure/architecture/reference-architectures/sharepoint/)
* [高可用性 SharePoint ファーム](https://docs.microsoft.com/ja-jp/azure/architecture/solution-ideas/articles/highly-available-sharepoint-farm)
* [Azure で SharePoint Server 2016 と SQL Server の AlwaysOn 可用性グループを展開する](https://docs.microsoft.com/ja-jp/SharePoint/administration/deploying-sharepoint-server-2016-with-sql-server-alwayson-availability-groups-in)
* [Azure における SharePoint 2013 開発/テスト環境](https://docs.microsoft.com/ja-jp/sharepoint/administration/sharepoint-2013-dev-test-environments-in-azure)
* [SharePoint Server 2016 および 2019 を使用した Azure SQL Managed Instance のデプロイ](https://docs.microsoft.com/ja-jp/sharepoint/administration/deploy-azure-sql-managed-instance-with-sharepoint-servers-2016-2019)

## AlternateAccessMappings(代替アクセスマッピング)

* [SharePoint Server の代替アクセス マッピングを構成する](https://docs.microsoft.com/ja-jp/sharepoint/administration/configure-alternate-access-mappings)
* [SharePoint Server の代替アクセス マッピングを計画する](https://docs.microsoft.com/ja-jp/sharepoint/administration/plan-alternate-access-mappings)
* [SharePoint Server 2013 の構成 － 代替アクセスマッピング](https://yama30501.blog.fc2.com/blog-entry-134.html)
* [パスベース および ホスト名付きサイト コレクションの構築](https://www.slideshare.net/aiyamasaki528/path-based-and-host-named-site-collection)
* [代替アクセス マッピングを理解する](https://docs.microsoft.com/en-us/archive/blogs/sharepoint_support/4401)
* [SharePoint Server の Web アプリケーションの URL と IIS のバインドを更新する](https://docs.microsoft.com/ja-jp/sharepoint/administration/update-a-web-application-url-and-iis-bindings)

## Loopback(サーバー自身からの接続方法)

* [Windows Authentication Errors on local Servers (Loopback Protection)](https://webconnection.west-wind.com/docs/_4gi0ql5jb.htm)
* [ホストヘッダーを利用する場合の注意事項](https://shanqiai.weblogs.jp/sharepoint_technical_note/2010/05/%E3%83%9B%E3%82%B9%E3%83%88%E3%83%98%E3%83%83%E3%83%80%E3%83%BC%E3%82%92%E5%88%A9%E7%94%A8%E3%81%99%E3%82%8B%E5%A0%B4%E5%90%88%E3%81%AE%E6%B3%A8%E6%84%8F%E4%BA%8B%E9%A0%85.html)

## Kerberos

* [Enabling Kerberos on SharePoint](https://thesharepointfarm.com/2017/10/enabling-kerberos-sharepoint/)

    ``` cmd
    setspn -U -S HTTP/sharepoint.example.com CORP\webAppAccount
    ```

* [SharePoint Server で Kerberos 認証を計画する](https://docs.microsoft.com/ja-jp/sharepoint/security-for-sharepoint-server/kerberos-authentication-planning)
* [SharePoint 2013/2016 Kerberos Authentication](https://www.noralku.net/2016/05/08/sharepoint-20132016-kerberos-authentication/)
* [Part2: Step by Step Guide for Configuring Kerberos Authentication for SharePoint 2013/2016](https://vivekmalviya.home.blog/2019/03/21/part2-step-by-step-guide-for-configuring-kerberos-authentication-for-sharepoint-webapplication/)
* [SharePointとKerberos認証](https://mossmomo.exblog.jp/13137689/)
* [Enabling Kerberos on SharePoint](https://thesharepointfarm.com/2017/10/enabling-kerberos-sharepoint/)
* [Set SPNs for the SharePoint Service Account](https://help.nintex.com/en-US/k2blackpearl/icg/4.6.10/Install_SetSPNsSharePoint.html)
* [Kerberos 認証の設定](https://community.denodo.com/docs/html/browse/8.0/jp/platform/installation/postinstallation_tasks/postinstallation_tasks_in_virtual_dataport/setting-up_kerberos_authentication)
* [The final Kerberos guide for SharePoint technicians](https://blog.blksthl.com/2012/09/26/the-final-kerberos-guide-for-sharepoint-technicians/)
* [SharePoint 2013: Form based Authentication (FBA)](https://social.technet.microsoft.com/wiki/contents/articles/23539.sharepoint-2013-form-based-authentication-fba.aspx)
## template

* [SharePoint サイト テンプレートとサイト スクリプトの概要](https://docs.microsoft.com/ja-jp/sharepoint/dev/declarative-customization/site-design-overview?WT.mc_id=M365-MVP-10648)
* [サイト テンプレートをSharePointカスタマイズする](https://support.microsoft.com/ja-jp/office/%E3%82%B5%E3%82%A4%E3%83%88-%E3%83%86%E3%83%B3%E3%83%97%E3%83%AC%E3%83%BC%E3%83%88%E3%82%92sharepoint%E3%82%AB%E3%82%B9%E3%82%BF%E3%83%9E%E3%82%A4%E3%82%BA%E3%81%99%E3%82%8B-39382463-0e45-4d1b-be27-0e96aeec8398?ui=ja-jp&rs=ja-jp&ad=jp#ID0EBADAAA=From_your_organization)
* [サイト テンプレートとサイト スクリプトの作成を開始する](https://docs.microsoft.com/ja-jp/sharepoint/dev/declarative-customization/get-started-create-site-design)


## Forms based authentication

* [SharePoint – FBA – 8306 – The security token username and password could not be validated.](https://adamsorenson.com/sharepoint-fba-8306-the-security-token-username-and-password-could-not-be-validated/)
* [Configuration issues in configure Forms based authentication with LDAP membership provider in sharPoint 2016 webapplication](https://social.technet.microsoft.com/Forums/Windows/en-US/f68533ea-c1b2-4309-b99b-aa6ace779a6e/configuration-issues-in-configure-forms-based-authentication-with-ldap-membership-provider-in?forum=SP2016)
* [[SharePoint]JPSPSフォローアップ：認証設定①～フォームベース認証](https://idmlab.eidentity.jp/2013/05/sharepointjpsps.html)

## SuitBar

* [SharePoint 2016 How to Change SuitBar’s Text PowerShell - TechNet Articles - United States (English) - TechNet Wiki](https://social.technet.microsoft.com/wiki/contents/articles/34202.sharepoint-2016-how-to-change-suitbars-text-powershell.aspx)
* [既定のサーバー リボンのカスタマイズの場所  Microsoft Docs](https://docs.microsoft.com/ja-jp/previous-versions/office/developer/sharepoint-2010/ee537543(v=office.14))
* [Replace SharePoint in Suitebar using SuiteBarBrandingElementHtml property not reflecting](https://social.technet.microsoft.com/Forums/en-US/21d067e5-eabd-4b13-ba7d-8cb8c780a30c/replace-sharepoint-in-suitebar-using-suitebarbrandingelementhtml-property-not-reflecting)
* [[SharePoint 2016] SuiteBar の設定変更](https://shanqiai.weblogs.jp/sharepoint_technical_note/2017/01/sharepoint-2016-suitebar-%E3%81%AE%E8%A8%AD%E5%AE%9A%E5%A4%89%E6%9B%B4-.html)
* [SharePoint ：検索窓の位置がスイートバーに移動された！( Search Box location moved to Suite Bar )](https://art-break.net/tech/?p=5425)
* [Office 365 ナビゲーション バーのカスタムロゴの位置が変更された！](https://art-break.net/tech/?p=2690)
* [SharePoint 2013 左上の製品ロゴを変更する](https://idea.tostring.jp/?p=508)

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
* [SharePoint Server 2016 での TLS 1.1 および TLS 1.2 のサポートの有効化](https://docs.microsoft.com/ja-jp/sharepoint/security-for-sharepoint-server/enable-tls-1-1-and-tls-1-2-support-in-sharepoint-server-2016)
* [SharePoint 2013 で TLS と SSL のサポートを有効にする](https://docs.microsoft.com/ja-jp/sharepoint/security-for-sharepoint-server/enable-tls-and-ssl-support-in-sharepoint-2013)
* [IISでhttpsのサイトを作成する - SSLサイトの構成 (IIS - Internet Information Service Tips)](https://www.ipentec.com/document/windows-windows-server-iis-setup-https-site)
* [「証明機関」による証明書の発行 (サーバー証明書を作成する) (Windows Server Tips)](https://www.ipentec.com/document/create-server-certificate-file)
* [認証局での証明書の生成](https://support.kaspersky.com/KWTS/6.1/ja-JP/186284.htm)
* [【AD CS】エンタープライズ CA でサーバー証明書の発行手順](https://pkiwithadcs.com/issuing_server_cert_using_certweb/)
* [Windows環境で証明書をインポートする方法](https://jp.globalsign.com/support/ssl/config/cert-import-win.html)
* [「エンタープライズのルートCA」を用いた証明書の設定（Windows Server 2008以降）](https://support.brother.co.jp/j/s/support/ssl/setup/setup2012.html)
* [Windowsの証明書サービスでサーバ証明書を発行する](https://atmarkit.itmedia.co.jp/ait/articles/0708/17/news079.html)
* [2階層CAの構築(Windows2016)　③中間証明書の発行とインストール](https://milestone-of-se.nesuke.com/sv-advanced/digicert/intermediate-cert-issue-and-install/)
* [AD CS で 5 年間有効なサーバー認証用の証明書を作成](https://blog.engineer-memo.com/2015/01/13/ad-cs-%E3%81%A7-5-%E5%B9%B4%E9%96%93%E6%9C%89%E5%8A%B9%E3%81%AA%E3%82%B5%E3%83%BC%E3%83%90%E3%83%BC%E8%AA%8D%E8%A8%BC%E7%94%A8%E3%81%AE%E8%A8%BC%E6%98%8E%E6%9B%B8%E3%82%92%E4%BD%9C%E6%88%90/)

## Distributed Cache

* [Distributed cache service is not enabled in this deployment (SharePoint Server)](https://docs.microsoft.com/en-us/sharepoint/technical-reference/distributed-cache-service-is-not-enabled-in-this-deployment)
* [Distributed Cache Host error](https://social.technet.microsoft.com/Forums/en-US/35f8fe49-7e4a-4d3e-bb65-ad17b723d8d8/distributed-cache-host-error?forum=SP2016)
* [Troubleshooting Distributed Cache in SharePoint Server 2013](https://vigneshsharepointthoughts.com/2015/10/20/troubleshooting-distributed-cache-in-sharepoint-server-2013/)
* [SharePoint 2013 Distributed Cache: Issue 1. “CacheHostinfo is null”.](https://sharepointjournaldotcom.wordpress.com/tag/sharepoint-distributed-cache/)
* [cacheHostInfo is null when adding a 2nd Distributed Cache](https://social.technet.microsoft.com/Forums/windows/en-US/1a875aa8-b26d-43bd-af67-87d6b24d7ed7/cachehostinfo-is-null-when-adding-a-2nd-distributed-cache?forum=SP2016)
* [Convert a SharePoint 2016 front-end to a front-end with Distributed Cache](https://blog.kuppens-switsers.net/sharepoint/convert-sharepoint-2016-front-end-to-front-end-with-distributed-cache/)
* [この環境では分散キャッシュ サービスが有効になっていません (SharePoint Server)](https://docs.microsoft.com/ja-jp/sharepoint/technical-reference/distributed-cache-service-is-not-enabled-in-this-deployment)

## WorkFlow

* [WorkflowStatus Enum](https://docs.microsoft.com/en-us/dotnet/api/microsoft.sharepoint.workflowservices.workflowstatus?view=sharepoint-server)

## Office Online Server

* [Office Online Server を計画する](https://docs.microsoft.com/ja-jp/officeonlineserver/plan-office-online-server)
* [Office Online Server を展開する](https://docs.microsoft.com/ja-jp/officeonlineserver/deploy-office-online-server)
* [Office Online Server (OOS) のインストールと構成](https://shanqiai.weblogs.jp/sharepoint_technical_note/2016/02/office-online-server-preview-install-configuration.html)
* [Exchange 組織に Office Online Server をインストールする](https://docs.microsoft.com/ja-jp/Exchange/plan-and-deploy/install-office-online-server?redirectedfrom=MSDN&view=exchserver-2019)
* [Office Online Serverを使ってみる](http://sptakesato.blog.fc2.com/blog-entry-20.html)
* [TLS 1.1 および TLS 1.2 以降のサポートを有効Office Online Server](https://docs.microsoft.com/ja-jp/officeonlineserver/enable-tls-1-1-and-tls-1-2-support-in-office-online-server)
* [Office Web Apps で SharePoint上のファイルが開けなくなる SPWOPIProofKey が更新されないことによる](https://social.msdn.microsoft.com/Forums/sqlserver/ja-JP/720a6d3f-f6f4-492c-9195-23a9fed9a90c/office-web-apps-12391?forum=sharepointsupportteamja)
* [Office 2019 製品版をインストールしてみました](https://curio-shiki.com/blog/office/office2019-firstinstall)
* [Office Online Server での IBM Content Navigator の構成](https://www.ibm.com/docs/ja/content-navigator/3.0.x?topic=components-configuring-content-navigator-office-online-server)
* [Office – VLSCのOffice2019（ボリュームライセンス版）をインストールする方法](https://se.ekaki-j.com/office-vlsc/)

# Windows OS

* [NUC7i7DNHE に Windows Server 2019 をインストールしてみる](https://blog.engineer-memo.com/2018/09/02/nuc7i7dnhe-%e3%81%ab-windows-server-2019-%e3%82%92%e3%82%a4%e3%83%b3%e3%82%b9%e3%83%88%e3%83%bc%e3%83%ab%e3%81%97%e3%81%a6%e3%81%bf%e3%82%8b/)
* [Intel NUCにHyper-V 2019をインストールするときにNICのドライバが無かった件](https://www.challenge-cf.jp/post/2019/10/23/intel-nucにhyper-v-2019をインストールするときにNICのドライバが無かった件)
* [IIS の調査に必要な通信系のログ情報について](https://jpdsi.github.io/blog/web-apps/LogCollection2/)
* [MSFC構築1 構成～AD構築](http://c.itdo.jp/technical-information/windows/msfc1/)
* [PowerShell and the Active Directory Schema: Part 1](https://devblogs.microsoft.com/scripting/powershell-and-the-active-directory-schema-part-1/)
* [SQL Server AlwaysOn 可用性グループの制約とSIOS SANLess Clustersの優位](https://mk.sios.jp/l/751023/QLServer-AG-vs-FCISANLessClust/kzd2x)
* [GPOにWindows 10 May 2020 Update 2004用の管理テンプレートを適用させる方法](https://ittrip.xyz/active-directory/policy-2004)
* [Windows 10 October 2018 Updateで変わった、サーバ管理ツールRSATのインストール方法：Tech TIPS - ＠IT](https://www.atmarkit.co.jp/ait/articles/1811/29/news046.html)
* [Windows 10にリモートサーバー管理ツール（RSAT）をインストールしてWindows Serverを管理する：Tech TIPS - ＠IT](https://www.atmarkit.co.jp/ait/articles/1510/19/news023.html)
* [Windows10 1809にリモートサーバ管理ツール(RSAT)をインストールする  楽しいブログ](https://cs.machijun.net/install-rsat-to-windows10-1809.html)
* [セントラル ストアについて  Microsoft Docs](https://docs.microsoft.com/ja-jp/archive/blogs/jpntsblog/433)
* [Windows 10で面倒になった「Windows Update」のコントロールを取り戻す方法はあるのか？：山市良のうぃんどうず日記（197） - ＠IT](https://www.atmarkit.co.jp/ait/articles/2012/23/news007.html)
* [Windows Server Failover Clustering に関する調査レポート](https://mk.sios.jp/l/751023/IOS-WSFC-examreport-201702-pdf/kzd2v)
* [Windows用アプリのインストールがコマンドラインで可能なパッケージマネージャー「winget」はどうなった？](https://ascii.jp/elem/000/004/025/4025912/)
* [ハードウェアの制約でWindowsの新規インストールを開始できない場合の「抜け道ガイド」：山市良のうぃんどうず日記（196） - ＠IT](https://www.atmarkit.co.jp/ait/articles/2012/09/news014.html)
* [仮想スイッチの種別と用途：Windows 10 Hyper-V入門 - ＠IT](https://www.atmarkit.co.jp/ait/articles/2008/14/news018.html)
* [仮想マシンの状態を保存する「チェックポイント」 (1/2)：Windows 10 Hyper-V入門 - ＠IT](https://www.atmarkit.co.jp/ait/articles/2009/10/news017.html)
* [第1回 Active Directoryの必要性【MicrosoftのMVP解説！第二弾 Active Directoryのハウツー読本】](https://blogs.manageengine.jp/needs_of_ad/)
* [iSCSI ターゲット サーバーの概要](https://docs.microsoft.com/ja-jp/windows-server/storage/iscsi/iscsi-target-server)

# SQL Server

* [DO’s&DONT’s #12: やった方がいいこと - max server memory を設定する](https://docs.microsoft.com/ja-jp/archive/blogs/jpsql/dosdonts-12-max-server-memory)
* [DO’s&DONT’s #17: やっておいた方がいいこと - tempdb データファイル数を CPU 数に一致させる](https://docs.microsoft.com/ja-jp/archive/blogs/jpsql/dosdonts-17-tempdb-259)
* [SQL Troubleshooting SQL Server トラブルシューティング 6 回シリーズのご案内](https://docs.microsoft.com/ja-jp/archive/blogs/jpsql/sql-troubleshooting-sql-server-6)
