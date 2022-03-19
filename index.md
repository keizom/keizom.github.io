# SharePoint Server

* [SharePoint Server の認証の概要](https://docs.microsoft.com/ja-jp/sharepoint/security-for-sharepoint-server/authentication-overview)

## install

* [SharePoint 2016: Step By Step Installation of Workflow Manager](https://social.technet.microsoft.com/wiki/contents/articles/34407.sharepoint-2016-step-by-step-installation-of-workflow-manager.aspx)
* [ネットワーク共有から SharePoint Server の必須コンポーネントをインストールする](https://docs.microsoft.com/ja-jp/sharepoint/install/install-prerequisites-from-network-share)
* [Azure 上で SharePoint Server 2016 をオフラインインストールしてみよう！(後編)](https://blogs.networld.co.jp/entry/azure-sharepoin-7f90)
* [SharePoint Server 2016 のオフライン インストール](https://docs.microsoft.com/ja-jp/archive/blogs/sharepoint_support/sharepoint-server-2016-%E3%81%AE%E3%82%AA%E3%83%95%E3%83%A9%E3%82%A4%E3%83%B3-%E3%82%A4%E3%83%B3%E3%82%B9%E3%83%88%E3%83%BC%E3%83%AB)
* [単一サーバーに SharePoint Server 2016 または SharePoint Server 2019 をインストールする](https://docs.microsoft.com/ja-jp/sharepoint/install/install-sharepoint-server-2016-on-one-server)

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

## Loopback(サーバー自身からの接続方法)

* [Windows Authentication Errors on local Servers (Loopback Protection)](https://webconnection.west-wind.com/docs/_4gi0ql5jb.htm)
* [ホストヘッダーを利用する場合の注意事項](https://shanqiai.weblogs.jp/sharepoint_technical_note/2010/05/%E3%83%9B%E3%82%B9%E3%83%88%E3%83%98%E3%83%83%E3%83%80%E3%83%BC%E3%82%92%E5%88%A9%E7%94%A8%E3%81%99%E3%82%8B%E5%A0%B4%E5%90%88%E3%81%AE%E6%B3%A8%E6%84%8F%E4%BA%8B%E9%A0%85.html)

## Kerberos

* [Enabling Kerberos on SharePoint](https://thesharepointfarm.com/2017/10/enabling-kerberos-sharepoint/)

    ``` cmd
    setspn -U -S HTTP/sharepoint.example.com CORP\webAppAccount
    ```

* [SharePoint Server で Kerberos 認証を計画する](https://docs.microsoft.com/ja-jp/sharepoint/security-for-sharepoint-server/kerberos-authentication-planning)

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

## Office Web Apps

* [Office Web Apps で SharePoint上のファイルが開けなくなる SPWOPIProofKey が更新されないことによる](https://social.msdn.microsoft.com/Forums/sqlserver/ja-JP/720a6d3f-f6f4-492c-9195-23a9fed9a90c/office-web-apps-12391?forum=sharepointsupportteamja)

# Microsoft 365

## Office 365 PowerShell

* [再改訂版 SharePoint Online HTTP 調整 (応答コード : 429) 対策の増分バックオフ リトライ](https://social.msdn.microsoft.com/Forums/ja-JP/21e2a628-44be-4541-bca9-b81c484ff59b/20877259133533029256-sharepoint-online-http-3551925972?forum=sharepointsupportteamja)
* [Office 365 の PowerShell 運用を PaaS 化してみる](https://sprestaurant.hatenablog.com/entry/2019/07/07/011839)
* [多要素認証 (MFA) の Office 365 に PowerShell で接続する方法まとめ](https://blog.kazuakix.jp/entry/2018/04/16/221554)
* [【SPO】CSOM と SharePoint Online 管理シェルを PowerShell でパッケージ管理](https://www.samurainote.com/entry/2019/02/23/222546)
* [単一の PowerShell ウィンドウですべての Microsoft 365 サービスに接続する](https://docs.microsoft.com/ja-jp/microsoft-365/enterprise/connect-to-all-microsoft-365-services-in-a-single-windows-powershell-window?view=o365-worldwide)
* [PowerShell を使用して Microsoft 365 サービスへのアクセスを無効にする](https://docs.microsoft.com/ja-jp/microsoft-365/enterprise/disable-access-to-services-with-microsoft-365-powershell?view=o365-worldwide)

## Developer Subscription

* [Microsoft 365 開発者サンドボックス サブスクリプションの設定](https://docs.microsoft.com/ja-jp/office/developer-program/microsoft-365-developer-program-get-started)
* [今すぐ Microsoft 365 開発者プログラムに参加しましょう!](https://developer.microsoft.com/ja-jp/microsoft-365/dev-program)
* [Office 365 評価版サイト申し込み](https://www.microsoft.com/ja-jp/microsoft-365/enterprise/compare-office-365-plans)
* [Microsoft 365 Enterprise のテスト ラボ ガイド - Microsoft 365 Enterprise  Microsoft Docs](https://docs.microsoft.com/ja-jp/microsoft-365/enterprise/m365-enterprise-test-lab-guides?view=o365-worldwide)

## BandWidth

* [Office365帯域調査してみました。 ? Exceedone Technical Knowledge](https://tech.exceedone.co.jp/office365-generally/office365-band-survey/)
* [【オンラインセミナー】Office 365 を快適に利用するためのネットワークインフラ10のポイント～疑問はQ&Aで解決～](https://resources.office.com/ja-jp-landing-ondemand-JA-O365-WBNR-FY18-11Nov-16-Online-Seminar-Network-MCW0002364.html)
* [【オンライン セミナー】 Office 365 の快適な利用に向けた帯域確保、プロキシ・ファイアウォールの運用について](https://resources.office.com/ja-jp-landing-ondemand-JA-O365-WBNR-FY18-02Feb-22-Office-365-and-use-proxy-firewalls-MCW0004275.html)
* [【オンライン セミナー】 Office 365 を有効活用するためのリソースご紹介](https://resources.office.com/ja-jp-landing-ondemand-JA-O365-WBNR-FY18-03Mar-01-effective-use-of-Office-365-MCW0004287.html)
* [O365のネットワークの推奨帯域について マイクロソフト コミュニティ](https://answers.microsoft.com/ja-jp/msoffice/forum/all/o365%E3%81%AE%E3%83%8D%E3%83%83%E3%83%88%E3%83%AF/9e6f9683-d922-4a85-80f6-6f4fb6e563bb)
* [Office 365の利用者に動作が“重い”と苦情を言われたときにとるべき対策は？：最新ルーターでSaaS時代のネットワーク管理を高度化せよ - ＠IT](https://www.atmarkit.co.jp/ait/articles/1802/27/news001.html)

## Advanced Threat Protection

* [Office 365 の ATP (Advanced Threat Protection) を使ってみる - kazuakix の日記](https://blog.kazuakix.jp/entry/2017/12/05/000100)
* [ATP のアタックシミュレータ - Office 365  Microsoft Docs](https://docs.microsoft.com/ja-jp/microsoft-365/security/office-365-security/attack-simulator?view=o365-worldwide)
* [Changes in the support case submission experience - Microsoft Tech Community - 1521387](https://techcommunity.microsoft.com/t5/microsoft-defender-atp/changes-in-the-support-case-submission-experience/ba-p/1521387)
* [Microsoft Threat Protection 評価ガイド 環境構築編](https://www.microsoft.com/cms/api/am/binary/RE4s3BN)
* [Microsoft Threat Protection 評価ガイド Office 365 ATP 攻撃検証編](https://www.microsoft.com/cms/api/am/binary/RE4s8OE)
* [Microsoft Threat Protection 評価ガイド Microsoft Defender ATP 攻撃検証編](https://www.microsoft.com/cms/api/am/binary/RE4zj4N)
* [できるMicrosoft 365 E5 Security Compliance 管理編](https://aka.ms/dekiru-book_M365-E5-Security_kanri)
* [できるMicrosoft 365 E5 Security Compliance 活用編](https://aka.ms/dekiru-book_M365-E5-Security_katuyo)
* [はじめての クラウド ストレージの保護: Office 365 Advanced Threat Protection  日本マイクロソフト](https://m.youtube.com/watch?v=Ze_QlJf5ET4)
* [はじめての クラウドの保護: Microsoft Cloud App Security  日本マイクロソフト](https://m.youtube.com/watch?v=PbgQpWeduMY)
powershell-csom-sample-code-for-spo-http-429-incremental-backoff-retry-2)

## Audit Log

* [セキュリティ運用ソフトウェア「LogStare Collector 2.2」の提供を開始](https://prtimes.jp/main/html/rd/p/000000070.000038758.html)
* [M365 監査ログ(旧 O365 監査ログ)収集の設定](https://www.secuavail.com/kb/references/ref-220203-01/)
* [PowerBIとFlowで、監査ログ分析](https://techcommunity.microsoft.com/t5/Microsoft-Stream-Blog/Global-Admin-Pro-Tip-Learn-how-to-build-video-analytics/ba-p/365267)
* [Export Office 365 User Activity Report to CSV using PowerShell](https://o365reports.com/2021/01/06/export-office-365-user-activity-report-to-csv-using-powershell/)
* [Retrieve Office 365 Audit logs using PowerShell and store in Azure table for quick retrieval](https://blog.kloud.com.au/2018/12/21/retrieve-office-365-audit-logs-using-powershell-and-store-in-azure-table-for-quick-retrieval/)
* [Office 365 Management Activity API の試し方](https://blog.rykoma.net/2019/07/19/1383/)

## Exchagne Online

* [Office 365 の多要素認証環境で Outlook を接続する方法](https://blog.kazuakix.jp/entry/2018/04/15/223003)
* [Office 365 でも拡張アドレスを使いたい](https://blog.kazuakix.jp/entry/2018/04/09/213959)
* [Using Azure Automation to Process Exchange Online Data with PowerShell](https://practical365.com/use-azure-automation-exchange-online/)
* [PowerShellから全社員に予定を投入したい](https://blog.o365mvp.com/2016/12/07/create_calendar_object_via_powershell/)
* [Exchange Online のメッセージ追跡ログ](https://jpmessaging.github.io/blog/Exchange%20Online%20%E3%81%AE%E3%83%A1%E3%83%83%E3%82%BB%E3%83%BC%E3%82%B8%E8%BF%BD%E8%B7%A1%E3%83%AD%E3%82%B0/)
* [Outlook in Exchange Online での最新認証の有効化または無効化  Microsoft Docs](https://docs.microsoft.com/ja-jp/exchange/clients-and-mobile-in-exchange-online/enable-or-disable-modern-authentication-in-exchange-online)
* [PowerShell – Exchange Onlineに証明書を使用して接続する –](https://tech-lab.sios.jp/archives/24523)
* [Exchange Onlineでの自動メール転送](https://exchange.ebisuda.com/2021/01/exchange-online%e3%81%a7%e3%81%ae%e8%87%aa%e5%8b%95%e3%83%a1%e3%83%bc%e3%83%ab%e8%bb%a2%e9%80%81/)
* [セキュリティ/コンプライアンス センター PowerShell に接続する](https://docs.microsoft.com/ja-jp/powershell/exchange/connect-to-scc-powershell?view=exchange-ps)
* [Exchange Online でやってはいけない 10 のこと  Outlook 研究所](https://outlooklab.wordpress.com/2017/01/21/Exchange-Online-でやってはいけない-10-のこと)
* [Exchange Onlineで.NETのメール自動配信アプリを作成する際のメモ書き](http://naoki0311.hateblo.jp/entry/20121003/1349226713)
* [よくわかる Exchange Online のメッセージ追跡 ～ Part 1 取得編 ～](https://social.msdn.microsoft.com/Forums/sqlserver/ja-JP/47c1f9d4-f4eb-4667-a3bc-3dbe8f55e209/1242412367124311236312427-exchange-online?forum=exchangeteamjp)

## SharePoint Online

* [SharePoint Online エクスプローラーで開く機能の制限事項について](https://social.msdn.microsoft.com/Forums/ja-JP/75d6134c-69f2-4013-878f-7892b23e9042/sharepoint-online?forum=sharepointsupportteamja)
* [SharePoint home sites: a landing for your organization on the intelligent intranet - Microsoft Tech Community - 621933](https://techcommunity.microsoft.com/t5/microsoft-sharepoint-blog/sharepoint-home-sites-a-landing-for-your-organization-on-the/ba-p/621933)
* [Updates to SharePoint security, and migration - Microsoft Tech Community - 549585](https://techcommunity.microsoft.com/t5/microsoft-sharepoint-blog/updates-to-sharepoint-security-administration-and-migration/ba-p/549585)
* [外部ユーザーからのアクセス要求を承認してSharePointサイトに権限を付ける作業を自動化してみた - 鍋綿ブログ](https://www.micknabewata.com/entry/sharepoint/user-invite)
* [SharePoint ：Column formatting を使ってみたけど僕には今のところ難しい](https://art-break.net/tech/?p=1523)
* [SharePoint 「注目リンク」リストをCSSでイイカンジにカスタマイズ](https://art-break.net/tech/?p=918)
* [SharePoint webhook の概要  Microsoft Docs](https://docs.microsoft.com/ja-jp/sharepoint/dev/apis/webhooks/overview-sharepoint-webhooks)
* [ビューの書式設定を使用して SharePoint をカスタマイズする](https://docs.microsoft.com/ja-jp/sharepoint/dev/declarative-customization/view-formatting)
* [SharePoint アドインのコンテキスト トークン OAUTH フロー](https://docs.microsoft.com/ja-jp/sharepoint/dev/sp-add-ins/context-token-oauth-flow-for-sharepoint-add-ins)
* [GitHub - pnp/sp-starter-kit: Modern SharePoint Starter Kit - End-to-end showcase solution to get started with modern experiences.](https://github.com/pnp/sp-starter-kit)
* [SharePoint Online モダン ページのページ ヘッダーを非表示にする  idea.toString();](https://idea.tostring.jp/?p=2512)
* [Microsoft Flow を使って SharePoint Online に保存されたドキュメントの承認ワークフローを作ってみる](https://idea.tostring.jp/?p=3540)
* [Power Automate のフローで SharePoint リストアイテムの権限を操作してみる](https://idea.tostring.jp/?p=5427)
* [Microsoft 365 SharePoint Modernization Scanner を動かしてみました - （）のブログ](https://mitomoha.hatenablog.com/entry/2020/07/09/012941)
* [SharePoint Spaces - Mixed Reality for the Enterprise](https://m.youtube.com/watch?feature=youtu.be&v=MW565hMnXLg)
* [Moving SharePoint Documents to the File System](https://dataqueen.unlimitedviz.com/2013/02/moving-sharepoint-documents-to-the-file-system/)
* [PowerShell Modules for Managing SharePoint Online](https://docs.microsoft.com/ja-jp/archive/blogs/dawiese/powershell-modules-for-managing-sharepoint-online)
* [新しい Microsoft Stream と SharePoint](https://shanqiai.weblogs.jp/sharepoint_technical_note/2020/10/new-microsoft-stream.html)
* [Find And Extract Sharepoint Documents With SQL – Mikes Data Work](https://mikesdatawork.wordpress.com/2018/05/11/find-and-extract-sharepoint-documents-with-sql/)
* [Display modal pop up in SharePoint Online/2013/2016](https://www.enjoysharepoint.com/display-modal-pop-up-in-sharepoint/?sfns=mo)
* [Useful CSS Classes in SharePoint 2013 – JoshMcCarty.com](https://joshmccarty.com/useful-css-classes-sharepoint-2013/)
* [既定のサーバー リボンのカスタマイズの場所  Microsoft Docs](https://docs.microsoft.com/ja-jp/previous-versions/office/developer/sharepoint-2010/ee537543(v=office.14))
* [OneDrive announcements – SharePoint Conference 2019](https://techcommunity.microsoft.com/t5/microsoft-onedrive-blog/onedrive-announcements-sharepoint-conference-2019/ba-p/616047)
* [Updates to SharePoint security, administration, and migration - Microsoft Tech Community - 549585](https://techcommunity.microsoft.com/t5/microsoft-sharepoint-blog/updates-to-sharepoint-security-administration-and-migration/ba-p/549585)
* [PowerShell – ShareGate Desktop](https://support-desktop.sharegate.com/hc/en-us/categories/204661007-PowerShell)
* [Find And Extract Sharepoint Documents With SQL ? Mikes Data Work](https://mikesdatawork.wordpress.com/2018/05/11/find-and-extract-sharepoint-documents-with-sql/)
* [Useful CSS Classes in SharePoint 2013 ? JoshMcCarty.com](https://joshmccarty.com/useful-css-classes-sharepoint-2013/)
* [SharePoint Spaces - Mixed Reality for the Enterprise](https://m.youtube.com/watch?v=MW565hMnXLg)
* [Microsoft 365 SharePoint Modernization Scanner を動かしてみました - （）のブログ](https://mitomoha.hatenablog.com/entry/2020/07/09/012941)
* [【オンライン セミナー】 SharePoint Online を使いこなすための設定大解説!](https://resources.office.com/ja-jp-landing-ondemand-JA-O365-WBNR-FY18-03Mar-08-SharePoint-Online-MCW0004583.html)

### Cascade

* [SPServicesでカスケード表示のドロップダウンを実現する](http://wakky10777.blog.fc2.com/blog-entry-39.html)
* [SharePointでカスケードドロップダウンの実装サンプル](http://katoj.hatenablog.com/entry/2015/06/24/134250)
* [カスケード分類作ってみた！](http://sharepointyuzuki.blog54.fc2.com/blog-entry-16.html)
* [SharePoint 基本機能内で管理されたメタデータ以外で2階層のカスケード分類を実現させる方法](https://art-break.net/tech/?p=478)
* [Youtube Cascading of Lookup Dropdown Fields on SharePoint 2013 and Office 365](https://www.youtube.com/watch?v=V_Jvv0arEm8)

### Modern

* [SharePoint Online モダン ページで “ちょっと” カスタマイズできる方法を模索してみる](https://idea.tostring.jp/?p=3986)
* [SharePoint Online モダンサイトのホームサイトを設定する](https://idea.tostring.jp/?p=5013)
* [SharePoint ハブ (Hub) を利用しよう](https://shanqiai.weblogs.jp/sharepoint_technical_note/2021/02/sharepoint-hub.html)
* [待望の新たなモダンな SharePoint サイトテンプレート登場 !](https://shanqiai.weblogs.jp/sharepoint_technical_note/2021/04/modern-site-templates.html)
* [モダンページのページレイアウトの種類と変更方法](http://sharepoint.orivers.jp/article/10031)

### Template

* [SharePoint サイト テンプレートとサイト スクリプトの概要](https://docs.microsoft.com/ja-jp/sharepoint/dev/declarative-customization/site-design-overview?WT.mc_id=M365-MVP-10648)
* [サイト テンプレートをSharePointカスタマイズする](https://support.microsoft.com/ja-jp/office/%E3%82%B5%E3%82%A4%E3%83%88-%E3%83%86%E3%83%B3%E3%83%97%E3%83%AC%E3%83%BC%E3%83%88%E3%82%92sharepoint%E3%82%AB%E3%82%B9%E3%82%BF%E3%83%9E%E3%82%A4%E3%82%BA%E3%81%99%E3%82%8B-39382463-0e45-4d1b-be27-0e96aeec8398?ui=ja-jp&rs=ja-jp&ad=jp#ID0EBADAAA=From_your_organization)
* [SharePointのテンプレート化方法まとめ - 鍋綿ブログ](https://www.micknabewata.com/entry/sharepoint/template)
* [SharePoint モダン サイト ～ サイト デザインとサイト スクリプト～](https://www.slideshare.net/aiyamasaki528/sharepoint-91933139)
* [SharePoint のサイト デザインとサイト スクリプトの作成を開始する  Microsoft Docs](https://docs.microsoft.com/ja-jp/sharepoint/dev/declarative-customization/get-started-create-site-design)

## SharePoint REST API

* [SharepointのREST APIのリファレンスが不親切だったので簡潔に(?)書いてみる。](https://blog.freedom-man.com/sharepoint_restapi)
* [SharePoint REST エンドポイントを使用して基本的な操作を完了する](https://docs.microsoft.com/ja-jp/sharepoint/dev/sp-add-ins/complete-basic-operations-using-sharepoint-rest-endpoints)
* [SharePointのREST APIを使ってファイルをダウンロードする（バッチ処理）](https://ichiro-kun.com/post/509/)
* [Using REST API For Selecting, Filtering, Sorting And Pagination in SharePoint List](https://peakfinders.blogspot.com/2016/09/using-rest-api-for-selecting-filtering.html?zx=f577555eebd8d3f6)
* [Office 365 API 入門](https://tsmatz.wordpress.com/2014/06/02/office-365-api/)
* [Cascading of Lookup Dropdown Fields on SharePoint 2013 and Office 365](https://www.c-sharpcorner.com/article/cascading-of-lookup-dropdown-fields-on-sharepoint-2013-and-o/)
* [Cascading Drop Down Lists in SharePoint / Office 365 using REST](http://www.markrackley.net/2014/05/20/cascading-drop-down-lists-in-sharepoint-office-365-using-rest/)
* [File Upload to SharePoint 2013 using REST API](https://stackoverflow.com/questions/25393075/file-upload-to-sharepoint-2013-using-rest-api)
* [SharePoint Online にアプリからアクセスする](https://blog.azure.moe/2017/01/25/sharepoint-online-%E3%81%AB%E3%82%A2%E3%83%97%E3%83%AA%E3%81%8B%E3%82%89%E3%82%A2%E3%82%AF%E3%82%BB%E3%82%B9%E3%81%99%E3%82%8B/)

## SharePoint JavaScript

* [Javascript and Working with the SharePoint 2013 People Picker](https://jasonscript.wordpress.com/2013/08/07/javascript-and-working-with-the-sharepoint-2013-people-picker/)
* [SharePoint のリスト列の情報を JavaScript で確認する - Qiita](https://qiita.com/miyamiya/items/6e689f4221ab6c0a711d)
* [SharePoint リストにアイテムを一括登録する ($batchの活用) - MoreBeerMorePower](https://mofumofupower.hatenablog.com/entry/sharepoint_batching)
* [SharePoint のリスト列の情報を JavaScript で確認する - Qiita](https://qiita.com/miyamiya/items/6e689f4221ab6c0a711d)
* [Top 51 SharePoint JavaScript Examples (Download FREE PDF) - SPGuides](https://www.spguides.com/jsom-sharepoint/)
* [SharePoint JSOM を使用したアイテムの CRUD 方法](https://docs.microsoft.com/ja-jp/archive/blogs/sharepoint_support/sharepoint-jsom-crud)
* [方法 JavaScript を使用して、リスト アイテムの作成、更新、削除を行う](https://docs.microsoft.com/ja-jp/previous-versions/office/developer/sharepoint-2010/hh185011(v=office.14))
* [SharePoint online client-side-people](http://onlinecoder.blogspot.com/2018/01/sharepoint-online-client-side-people.html)
* [SharePoint Tabbed Web Parts HillbillyTabs2.0 ? MarkRackley.net](https://www.markrackley.net/2014/11/25/sharepoint-tabbed-web-partshillbillytabs2-0/)
* [SharePoint への JavaScript の埋め込み](https://docs.microsoft.com/ja-jp/sharepoint/dev/solution-guidance/embedding-javascript-into-sharepoint)
* [SharePoint の JavaScript ライブラリ コードを使用して基本的な操作を完了する](https://docs.microsoft.com/ja-jp/sharepoint/dev/sp-add-ins/complete-basic-operations-using-javascript-library-code-in-sharepoint)
* [GitHub - pnp/sp-starter-kit: Modern SharePoint Starter Kit - End-to-end showcase solution to get started with modern experiences.](https://github.com/pnp/sp-starter-kit)
* [GitHub - pnp/sp-dev-fx-webparts](https://github.com/pnp/sp-dev-fx-webparts/tree/main/samples/react-calendar)
* [GitHub - sp-dev-fx-webparts/samples/react-script-editor at master ? pnp/sp-dev-fx-webparts](https://github.com/pnp/sp-dev-fx-webparts/tree/master/samples/react-script-editor)

## CSOM

* [SharePoint Online の HTTP 調整 (応答コード 429, 503) に関して](https://social.msdn.microsoft.com/Forums/ja-JP/8e5a4116-c96a-4d3e-9bbf-6efb852b5d88/sharepoint-online-12398-http-3551925972-2454031572124671254012489-429-503?forum=sharepointsupportteamja)
* [再改訂版 SharePoint Online HTTP 調整 (応答コード : 429) 対策の増分バックオフ リトライ](https://social.msdn.microsoft.com/Forums/ja-JP/21e2a628-44be-4541-bca9-b81c484ff59b/20877259133533029256-sharepoint-online-http-3551925972?forum=sharepointsupportteamja)
* [SharePoint Online で調整またはブロックを回避する  Microsoft Docs](https://docs.microsoft.com/ja-jp/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online)
* [Create Update Delete Or Retrieve SharePoint Site Collections Using CSOM PowerShell](https://www.c-sharpcorner.com/article/create-update-delete-or-retrieve-sharepoint-site-collectio/)
* [Creating SharePoint Site Collection through PowerShell CSOM](http://alexbrassington.com/2014/08/20/creating-sharepoint-site-collection-through-powershell-csom/)
* [Office 365グループの一覧とメンバーを取得するPowerShellスクリプト(多要素認証対応)](https://windowsadmin.ebisuda.com/2017/12/19/office-365%E3%82%B0%E3%83%AB%E3%83%BC%E3%83%97%E3%81%AE%E4%B8%80%E8%A6%A7%E3%81%A8%E3%83%A1%E3%83%B3%E3%83%90%E3%83%BC%E3%82%92%E5%8F%96%E5%BE%97%E3%81%99%E3%82%8Bpowershell%E3%82%B9%E3%82%AF%E3%83%AA/)
* [ディスカッション掲示板のデータ移行 サンプル スクリプトについて](https://docs.microsoft.com/ja-jp/archive/blogs/sharepoint_support/1250-2)
* [SharePoint Online: Start Workflow on All Items in a List using PowerShell - SharePoint Diary](https://www.sharepointdiary.com/2018/05/sharepoint-online-start-workflow-using-powershell.html)
* [Bulk Upload Files to SharePoint](https://docs.microsoft.com/ja-jp/sharepoint/dev/solution-guidance/bulk-upload-documents-sample-app-for-sharepoint)
* [PnP/Samples/Core.LargeFileUpload/](https://github.com/pnp/PnP/tree/master/Samples/Core.LargeFileUpload)
* [How to use PowerShell in SharePoint Online/2016/2013 - SPGuides](https://www.spguides.com/powershell-sharepoint/)

## PnP SharePoint

* [Tree view navigation using PnP Treeview control in the SharePoint Framework (SPFx) web part – RAVICHANDRAN BLOG](https://ravichandran.blog/2020/05/14/tree-view-navigation-using-pnp-treeview-control-in-the-sharepoint-framework-spfx-web-part/)

## SharePoint Tools

* [SharePoint Designer 2013](https://www.microsoft.com/ja-jp/download/details.aspx?id=35491)
* [Microsoft SharePoint Designer 2013 (KB2817441) 64 ビット版 Service Pack 1](https://www.microsoft.com/ja-jp/download/details.aspx?id=42009)
* [Microsoft SharePoint Designer 2010 (64 ビット版)](https://www.microsoft.com/ja-jp/download/details.aspx?id=24309)
* [SharePoint Client Browser (SPCB)](https://github.com/bramdejager/spcb)
* [CAML Query Builder for SharePoint 2013/2016/Online](https://www.enjoysharepoint.com/caml-query-builder-in-sharepoint-2013-online/)
* [Download, Install and Use CAML Query Helper in SharePoint Online/2013/2010/2007](https://www.enjoysharepoint.com/sharepoint-caml-query-helper/)
* [bandrben/SPCAMLQueryHelperOnline](https://github.com/bandrben/SPCAMLQueryHelperOnline)
* [ULS Viewer](https://www.microsoft.com/en-in/download/details.aspx?id=44020)
* [hasankhan/SharePointLogViewer](https://github.com/hasankhan/SharePointLogViewer)
* [CAML Query Builder](https://www.u2u.be/software)
* [PnP-Tools/Solutions/SharePoint.Search.QueryTool/](https://github.com/SharePoint/PnP-Tools/tree/master/Solutions/SharePoint.Search.QueryTool)
* [CAML Designer](https://www.biwug.be/resources)
* [SP Editor](https://chrome.google.com/webstore/detail/sp-editor/ecblfcmjnbbgaojblcpmjoamegpbodhd)

## SharePoint Design Sample

* [Design beautiful and performant sites, pages, and web parts with SharePoint in Office 365.](https://spdesign.azurewebsites.net/)
* [SharePoint look book](https://sharepointlookbook.azurewebsites.net/)
* [SharePoint社内ポータルサイト構築例 ～ コミュニケーションサイト編 ～](https://www.micknabewata.com/entry/sharepoint/communicationSiteTemplate)

## spguides.com

* [How to Activate Workflows can use app permissions Feature programmatically using CSOM in SharePoint - SPGuides](https://www.spguides.com/activate-workflows-can-use-app-permissions/)
* [Top 51 SharePoint JavaScript Examples (Download FREE PDF) - SPGuides](https://www.spguides.com/jsom-sharepoint/)
* [How to use PowerShell in SharePoint Online/2016/2013 - SPGuides](https://www.spguides.com/powershell-sharepoint/)
* [How to send email using PowerShell in Office 365 - SPGuides](https://www.spguides.com/send-email-powershell-office-365/)
* [Various SharePoint developer tools](https://www.spguides.com/sharepoint-developer-tools/)
* [How to upload documents to SharePoint document library programmatically with metadata](https://www.spguides.com/upload-file-to-sharepoint-document-library-programmatically/)
* [How to Activate Workflows can use app permissions Feature programmatically using CSOM in SharePoint - SPGuides](https://www.spguides.com/activate-workflows-can-use-app-permissions/)
* [CSOM SharePoint Online – Detailed Guide](https://www.spguides.com/sharepoint-csom-tutorial/)

## enjoysharepoint.com

* [50+ SharePoint server object model examples](https://www.enjoysharepoint.com/sharepoint-server-object-model-examples/)
* [Add lookup column to SharePoint list programmatically using CSOMAdd lookup column to SharePoint list programmatically using CSOM](https://www.enjoysharepoint.com/add-lookup-column-to-sharepoint-list-programmatically/)
* [Bulk Export SharePoint Files using PowerShell](https://www.enjoysharepoint.com/bulk-export-sharepoint-files-using-powershell/)
* [CAML Query Builder for SharePoint 2013/2016/Online](https://www.enjoysharepoint.com/caml-query-builder-in-sharepoint-2013-online/)
* [Check if user belongs to SharePoint group using CSOM](https://www.enjoysharepoint.com/check-if-user-belongs-to-sharepoint-group-using-csom/)
* [Content type Examples using CSOM in SharePoint Online/2013/2016](https://www.enjoysharepoint.com/sharepoint-csom-content-type-examples/)
* [Create Azure WebJobs for SharePoint Online and Deploy to Microsoft Azure](https://www.enjoysharepoint.com/create-azure-webjobs-for-sharepoint-online/?sfns=mo)
* [Create client side People Picker control in SharePoint Online Office 365](https://www.enjoysharepoint.com/how-to-use-client-side-people-picker-control-in-sharepoint-online-office-365/)
* [Create Site Collection and Subsite in SharePoint Online using PowerShell](https://www.enjoysharepoint.com/create-site-collection-sharepoint-powershell/)
* [Create/Rename SharePoint group using PowerShell and Browser](https://www.enjoysharepoint.com/sharepoint-group/)
* [Deploy SharePoint 2013 designer workflow to different site in SharePoint 2013](https://www.enjoysharepoint.com/deploy-sharepoint-2013-designer-workflow-to-different-site-in-sharepoint-2013/)
* [Display modal pop up in SharePoint Online/2013/2016](https://www.enjoysharepoint.com/display-modal-pop-up-in-sharepoint/?sfns=mo)
* [Enable breadcrumb and Implement Classic Breadcrumb in SharePoint 2013](https://www.enjoysharepoint.com/enable-breadcrumb-and-implement-classic-breadcrumb-in-sharepoint-2013/)
* [Enjoy SharePointGet all subsites from a site collection in SharePoint Online using](https://www.enjoysharepoint.com/get-all-subsites-in-sharepoint-online-csom/)
* [Get all subsites from a site collection in SharePoint Online using CSOM](https://www.enjoysharepoint.com/get-all-subsites-in-sharepoint-online-csom/)
* [Get all subsites from a site collection in SharePoint Online using](https://www.enjoysharepoint.com/get-all-subsites-in-sharepoint-online-csom/)
* [Get list items using Rest API in SharePoint Online/2013/2016](https://www.enjoysharepoint.com/get-sharepoint-list-items-using-rest-api)
* [How to display more than 3 views in SharePoint 2013/2016/Online list or document library](https://www.enjoysharepoint.com/sharepoint-list-display-more-than-3-views/?sfns=mo)
* [How to get SharePoint Timer Job History using PowerShell](https://www.enjoysharepoint.com/how-to-get-sharepoint-timer-job-history-using-powershell/?sfns=mo)
* [How to rename SharePoint 2013 group using browser and PowerShell?](https://www.enjoysharepoint.com/how-to-rename-sharepoint-2013-group-using-browser-and-powershell/)
* [Microsoft Flow Send approval email when a new item is added in SharePoint Online Office 365](https://www.enjoysharepoint.com/microsoft-flow-send-approval-email/)
* [PowerShell out gridview in SharePoint 2013/2016](https://www.enjoysharepoint.com/powershell-out-gridview/)
* [Setup SharePoint Framework (SPFx) development environment in Windows 10 workstation](https://www.enjoysharepoint.com/sharepoint-framework-development-setup/)
* [SharePoint 2013/2016/Online List Column Validation Examples](https://www.enjoysharepoint.com/sharepoint-2013-list-column-validation-examples/)
* [SharePoint list operations using rest api](https://www.enjoysharepoint.com/sharepoint-list-operations-using-rest-api/)
* [SharePoint modern list column formatting examples](https://www.enjoysharepoint.com/sharepoint-modern-list-column-formatting/)
* [Steps to add items from CSV file to SharePoint Online List using PowerShell in CSOM](https://www.enjoysharepoint.com/steps-to-add-items-from-csv-file-to-sharepoint-online-list-using-powershell-in-csom/)
* [Upload documents to SharePoint document library using PowerShell Remotely](https://www.enjoysharepoint.com/upload-document-using-powershell-remotely/)
* [Validate rich textbox using jQuery in SharePoint 2013/2016](https://www.enjoysharepoint.com/sharepoint-2013-enhanced-or-rich-textbox-validation-using-jquery/?sfns=mo)
* [What is people picker and how to HTML Div as a People picker control in SharePoint Online?](https://www.enjoysharepoint.com/client-side-people-picker-in-sharepoint-online-using-javascript/)

## SharePoint FrameWork

* [SharePoint Framework の概要 (SPFx)  Microsoft Docs](https://docs.microsoft.com/ja-jp/sharepoint/dev/spfx/sharepoint-framework-overview)
* [SharePoint Framework 開発環境の設定  Microsoft Docs](https://docs.microsoft.com/ja-jp/sharepoint/dev/spfx/set-up-your-development-environment)
* [SharePoint Framework 開発入門 まとめ - SharePoint Developer](https://sharepoint.orivers.jp/sharepoint-framework-dev)
* [SharePoint Framework をはじめよう #spfx](https://www.slideshare.net/hirofumi_ota/sharepoint-framework-spfx)
* [SharePoint Framework を触ってみた](https://www.slideshare.net/KosukeKuromiya/20170211-jpsps-kuromiyashare)
* [【SharePoint Online】SPFxでアプリを作る その１ー  ほげふがな日常](https://www.hogehoge-note.com/2019/08/24/post-309/)
* [【初心者向け】SharePoint Framework (SPFx) 入門 - 鍋綿ブログ](https://www.micknabewata.com/entry/sharepoint/spfx/newbee)
* [Community Demo - Using Matomo Analytics in modern SharePoint with SPFx for page analytics](https://www.youtube.com/watch?v=qg-bfs11U-A)
* [Getting started on creating SharePoint Framework list view command sets](https://www.youtube.com/watch?v=cyuzaycjxXs)
* [MsGraphSpFxThangu](https://www.youtube.com/watch?v=AKftsTLQBGo)
* [Office365 その5 開発用サイトをSharePoint Online上に作成する](http://www.rarpa.net/?p=5617)
* [SharePoint Framework (SPFx) Extensions Application Customizer Example - SharePointSky](https://www.sharepointsky.com/spfx-application-customizer/)
* [SharePoint Framework (SPFx) Extensions Application Customizer Example - SPGuides](https://www.spguides.com/spfx-application-customizer/)
* [SharePoint Framework での SharePoint REST API 呼び出し (Promise 編)](https://sharepoint.orivers.jp/article/10389)
* [SharePoint Framework におけるチーム ベースの開発  Microsoft Docs](https://docs.microsoft.com/ja-jp/sharepoint/dev/spfx/team-based-development-on-sharepoint-framework)
* [SharePoint Framework の最初の拡張機能を構築する (Hello World パート 1)  Microsoft Docs](https://docs.microsoft.com/ja-jp/sharepoint/dev/spfx/extensions/get-started/build-a-hello-world-extension)
* [SharePoint Framework を使ってメール送信フォームを作ってみる - からめもぶろぐ。](https://zenn.dev/karamem0/articles/2020_02_09_170000)
* [SharePoint Frameworkの記事一覧  ほげふがな日常](https://www.hogehoge-note.com/2019/09/07/post-372/)
* [SharePoint のクライアント側の最初の Web パーツを作成する (Hello World パート 1)  Microsoft Docs](https://docs.microsoft.com/ja-jp/sharepoint/dev/spfx/web-parts/get-started/build-a-hello-world-web-part)
* [SPFxCalendar 1.5.3 を公開しました - からめもぶろぐ。](https://zenn.dev/karamem0/articles/2020_10_15_180000)
* [Updated SharePoint Framework developer training package (June 2019)! - Microsoft 365 Developer Blog](https://developer.microsoft.com/en-us/sharepoint/blogs/updated-sharepoint-framework-developer-training-package-june-2019/)

## Fiddler

* [Fiddler を使って HTTPS トラフィックを確認する  idea.toString();](https://idea.tostring.jp/?p=1077)

## Dynamics 365

* [Dynamics 365 トライアル環境の取得 （2020年9月版） - YouTube](https://m.youtube.com/watch?v=2vXTJK623TU)
* [Community demo ? Calling Dynamics 365 CRM APIs from SharePoint - YouTube](https://www.youtube.com/watch?v=VXzYc6cfjuI)
* [Dynamics 365 自習書シリーズ - Microsoft Dynamics 365](https://www.microsoft.com/ja-jp/biz/dynamics/learning.aspx)
* [Community demo – Calling Dynamics 365 CRM APIs from SharePoint - YouTube](https://www.youtube.com/watch?v=VXzYc6cfjuI&app=desktop)
* [Dynamics 365の無料トレーニング](https://www.microsoft.com/ja-jp/events/top/training-days/dynamics365)
* [今日から始めるDynamics 365 + PowerAppsでカスタムアプリを作成！](https://memo.tyoshida.me/power-platform/powerapps/start-today-create-custom-apps-with-powerapps-and-dynamics-365/)

## PowerApps

* [Webinar オンデマンド一覧](https://www.microsoft.com/ja-jp/biz/dynamics/power-platform-webinar.aspx)
* [【PowerApps Tip's】開発言語経験者の多くが陥る最初の罠と回避方法 - Qiita](https://qiita.com/yamad365/items/feed918f9934ee6a2f07)
* [【PowerApps】カメラで撮った画像をSharePointリストに保存し、他のアプリで見る。 - Qiita](https://qiita.com/Econoshift/items/2727dc687f5801d87272)
* [AI Builder の概要](https://docs.microsoft.com/ja-jp/ai-builder/overview)
* [Common Data Service とは何か？ - Power Apps  Microsoft Docs](https://docs.microsoft.com/ja-jp/powerapps/maker/common-data-service/data-platform-intro)
* [Get started with building Power Apps in Project Oakdale - YouTube](https://www.youtube.com/watch?v=6vdx7JDuCq4)
* [Microsoft 365に付属する「Power Platform」、使ってみるべき理由  日経クロステック（xTECH）](https://xtech.nikkei.com/atcl/nxt/column/18/01549/020100001/)
* [Microsoft Ignite 2020 Power Platform アップデート日本語版](https://www.youtube.com/watch?v=dpkJIM602SY)
* [Microsoft PowerApps で Office 365 をもっと便利に 1/4](https://www.youtube.com/watch?v=MZzvgy94fUk)
* [Power Apps (CDS for Teams) が使われているチームを取得する - MoreBeerMorePower](https://mofumofupower.hatenablog.com/entry/2020/09/25/200421)
* [Power Apps で作る！大学向け業務アプリ ハンズオン講座  日本マイクロソフト](https://m.youtube.com/watch?v=lSeUzTrS1v8)
* [Power Apps のキャンバス アプリとは?](https://docs.microsoft.com/ja-jp/powerapps/maker/canvas-apps/getting-started)
* [Power Apps の概要 - Learn  Microsoft Docs](https://docs.microsoft.com/ja-jp/learn/modules/get-started-with-powerapps/1-powerapps-introduction)
* [Power Platform「CoE Starter Kit」使ってみた  cloud.config Tech Blog](https://tech-blog.cloud-config.jp/2019-12-20-tried-coe-starter-kit/)
* [Power PlatformのCommon Data Serviceを利用する10の理由 - 吉田の備忘録](https://memo.tyoshida.me/power-platform/powerapps/ten-reasons-to-use-the-common-data-service/)
* [PowerApps Portals（Preview）ことはじめ。初期構成＆関連情報まとめ - Morning Girl](https://kageura.hatenadiary.jp/entry/powerappsportals01)
* [PowerApps で名刺管理アプリを作ってみる(1) - Qiita](https://qiita.com/IKETA/items/132633f4988477809355)
* [PowerAppsで来訪者管理アプリを作成する](https://www.si-jirei.jp/2019/01/23/powerapps%E3%82%B3%E3%83%A9%E3%83%A0/)
* [コネクタのドキュメント - Connectors  Microsoft Docs](https://docs.microsoft.com/ja-jp/connectors/)
* [ノンコーディングで業務アプリ開発！「PowerApps」と「Microsoft Flow」とは](https://info.microsoft.com/JA-DynOps-WBNR-FY18-06Jun-14-Businessappdevelopment-MCW0006792_02OnDemandRegistration-ForminBody.html)
* [社内緊急対策のためのPower Platform テンプレートをリリース](https://memo.tyoshida.me/power-platform/powerapps/crisis-communication-template-released/)
* [働き方改革に効く！ゼロからはじめるPowerApps(5) Office 365のExcelとバーコード機能で固定資産の棚卸をしよう  マイナビニュース](https://news.mynavi.jp/article/powerapps-5/)
* [働き方改革に効く！ゼロからはじめるPowerApps(11) スキルや資格をMicrosoft 365ユーザーにひもづけて管理するアプリを作る  マイナビニュース](https://news.mynavi.jp/article/powerapps-11/)


## PowerAppsModelDriven

* [Power Apps で モデル駆動型アプリを作る（１）  IT長のネタ帳](https://www.d3654.be/getting-started-model-driven-powerapps01/)
* [Power PlatformのCommon Data Serviceを利用する10の理由 - 吉田の備忘録](https://memo.tyoshida.me/power-platform/powerapps/ten-reasons-to-use-the-common-data-service/)
* [Common Data Service とは何か？ - Power Apps  Microsoft Docs](https://docs.microsoft.com/ja-jp/powerapps/maker/common-data-service/data-platform-intro)
* [Power Apps を使用したモデル駆動型アプリの構築の概要 - Power Apps  Microsoft Docs](https://docs.microsoft.com/ja-jp/powerapps/maker/model-driven-apps/model-driven-app-overview)
* [Power Apps のモデル駆動型アプリの概要 - Learn  Microsoft Docs](https://docs.microsoft.com/ja-jp/learn/modules/get-started-with-model-driven-apps-in-powerapps/)

## Power Automate Desktop

* [Windows10の無償デスクトップ自動化ツール「Power Automate Desktop」でWebブラウザーでの作業を自動化する](https://codezine.jp/article/detail/15410)
* [Windows：PowerAutomate Desktopをインストールして使ってみる](https://zenn.dev/barusu/articles/b702ef21c713ba)
* [Power AutomateのRPA機能「UI flows」の始め方](https://rpahack.com/uiflows)
* [Power AutomateでRPAにトライ！！  SIOS Tech. Lab](https://tech-lab.sios.jp/archives/18486)
* [Power Automate で新しいデスクトップ用RPAソリューション「Power Automate Desktop」をリリース - 吉田の備忘録](https://memo.tyoshida.me/power-platform/power-automate/power-automate-desktop-preview-released/)

## Power Automate

* [202009_PowerAutomate_Handson](https://github.com/rnakamuramartiny/Share_RPACommunity/tree/master/202009_PowerAutomate_Handson)
* [Azure活用！Power Automateならノーコードで顔写真から年齢や性別が判断できる！ハンズオンイベント！](https://rpa-bank.com/column/40730)
* [Microsoft Flow から SharePoint REST サービス呼び出し](https://docs.microsoft.com/ja-jp/archive/blogs/office365-tech-japan/invoke-sporestservice-by-using-flow)
* [Microsoft Flow でアイテムの権限を変更する](http://deepcom.co.jp/flow_item_permission_1/)
* [Power Automate Teams上で承認を行う](https://zezeze.hateblo.jp/entry/2019/11/29/040113)
* [Power Automate で Microsoft 365 の障害情報をチェックする（Graph API 版）](https://idea.tostring.jp/?p=6330)
* [Power Automate でスクリプトの使用を開始する - Office Scripts  Microsoft Docs](https://docs.microsoft.com/ja-jp/office/dev/scripts/tutorials/excel-power-automate-manual)
* [Power Automate でデバッグする際のTips - MoreBeerMorePower](https://mofumofupower.hatenablog.com/entry/2020/11/17/224059)
* [Power Automate で処理に失敗した際にどのアクションで失敗したかを即時にメール通知する方法 - 欲しいアプリは自分で作る！](https://jn.hateblo.jp/entry/2020/10/31/174431)
* [Power Automate で組織の連絡先のメールアドレスから所属グループを抽出する](https://jn.hateblo.jp/entry/2020/08/23/003210)
* [Power Automate の Apply to each 内でOffice Script を使うときの注意点? - SharePoint Technical Notes](https://shanqiai.weblogs.jp/sharepoint_technical_note/2020/10/using_office_script_with_powerautomate.html)
* [Power Automate のフローで SharePoint リストアイテムの権限を操作してみる  idea.toString();](https://idea.tostring.jp/?p=5427)
* [Power Automate を使って予定表リスト(イベントリスト)から Microsoft Teams 会議を作成する](https://shanqiai.weblogs.jp/sharepoint_technical_note/2020/09/create-teamsmeeting-from-eventlist-onspo-using-powerautomate.html)
* [Power Automate（旧Microsoft Flow）からMicrosoft TeamsへBotで投稿する方法3種をまとめてみた - Qiita](https://qiita.com/tfunakoshi/items/76029bcc8ac1d4d9bd71)
* [Power Platform すべての標準階層のコネクタの一覧](https://docs.microsoft.com/ja-jp/connectors/connector-reference/connector-reference-standard-connectors)
* [Power Platformでアプリを作ろう、まずはPower Automateでデータ収集  日経クロステック（xTECH）](https://xtech.nikkei.com/atcl/nxt/column/18/01549/020100002/)
* [RPA機能の Power Automate Desktop 一般公開（GA）とプロセスアドバイザーの公開 - 吉田の備忘録](https://memo.tyoshida.me/power-platform/power-automate/power-automate-desktop-general-availability/)
* [RPA勉強会！Power Automate Talk #7 ～ハンズオンで勤怠報告ボタン作成！～ (2020/11/27 19:30〜)](https://rpacommunity.connpass.com/event/195217/)
* [Windows 10 で開発環境を設定する](https://docs.microsoft.com/ja-jp/windows/dev-environment/overview)
* [コネクタのドキュメント - Connectors  Microsoft Docs](https://docs.microsoft.com/ja-jp/connectors/)
* [ノンコーディングで業務アプリ開発！「PowerApps」と「Microsoft Flow」とは](https://info.microsoft.com/JA-DynOps-WBNR-FY18-06Jun-14-Businessappdevelopment-MCW0006792_02OnDemandRegistration-ForminBody.html)
* [マイクロソフトがPower Automateの機能を強化するProcess Advisorを公開、反復の多い作業のワークフローを効率化](https://jp.techcrunch.com/2020/12/10/2020-12-09-microsoft-brings-new-process-mining-features-to-power-automate/)

## Power Virtual Agents

* [Power Virtual Agents](https://powerva.microsoft.com/#/dialog/4c6f7ea5-a79a-48c5-ade0-7553c95a880d)

## Power BI

* [Azure Serverless or Power Platform ～ あなたならどっち？！ ～ Power Platform 編](https://www.slideshare.net/yugoes1021/azure-serverless-or-power-platform-power-platform?from_m_app=ios)
* [Get Month Name from Month Number in Power BI - SPGuides](https://www.spguides.com/get-month-name-from-month-number-in-power-bi/)
* [GitHub - The-Japan-DataScientist-Society/100knocks-preprocess: データサイエンス100本ノック（構造化データ加工編）](https://github.com/The-Japan-DataScientist-Society/100knocks-preprocess)
* [Power BI Tips Power BI でリアルタイムアンケート ～ アンケートを即可視化 2020年版 ～ - Qiita](https://qiita.com/yugoes1021/items/ea4c96cec9f1c7e47347)
* [Power BI Update - September 2020 - YouTube](https://www.youtube.com/watch?feature=youtu.be&v=gPGy18Yo0Go&app=desktop)
* [Power BI で Azure 監査ログを表示および分析する方法](https://docs.microsoft.com/ja-jp/archive/blogs/jpitpro/power-bi-azure)
* [Power BI データセットからピボットテーブルを作成する - Excel](https://support.microsoft.com/ja-jp/office/power-bi-%E3%83%87%E3%83%BC%E3%82%BF%E3%82%BB%E3%83%83%E3%83%88%E3%81%8B%E3%82%89%E3%83%94%E3%83%9C%E3%83%83%E3%83%88%E3%83%86%E3%83%BC%E3%83%96%E3%83%AB%E3%82%92%E4%BD%9C%E6%88%90%E3%81%99%E3%82%8B-31444a04-9c38-4dd7-9a45-22848c666884?ui=ja-jp&rs=ja-jp&ad=jp)
* [Power BI でリアルタイムアンケート ～ アンケートを即可視化 2020年版](https://qiita.com/yugoes1021/items/ea4c96cec9f1c7e47347)
* [Power BI のサンプルを入手する - Power BI  Microsoft Docs](https://docs.microsoft.com/ja-jp/power-bi/create-reports/sample-datasets)
* [Power BIによるAzure アクティビティログの可視化 – Cloud Steady  パーソルプロセス＆テクノロジー株式会社](https://cloudsteady.jp/post/7312/)
* [Power BIの学び-真似することから始めてみる - 業務ハックLab](https://yo-yon.hatenablog.com/entry/powerbimanabimane)
* [powerbi-desktop-samples/Sample Reports at master microsoft/powerbi-desktop-samples · GitHub](https://github.com/microsoft/powerbi-desktop-samples/tree/master/Sample%20Reports)
* [Global Admin Pro Tip: Learn how to build video analytics reporting using Office 365 audit logs](https://techcommunity.microsoft.com/t5/Microsoft-Stream-Blog/Global-Admin-Pro-Tip-Learn-how-to-build-video-analytics/ba-p/365267)
* [ウェビナー Power BI を使う時の基本～最初に考えること～](https://info.microsoft.com/JA-SQLDB-WBNR-FY18-06Jun-21-PowerBI-MCW0006279_02OnDemandRegistration-ForminBody.html)
* [組織内の Office 365 の利用状況を可視化する Power BI Office 365 Adoption Content Pack パブリック プレビュー開始  idea.toString();](https://idea.tostring.jp/?p=2873)

## Planner

* [【タスク管理】Teams × Planner で実現。簡単！便利！](https://m.youtube.com/watch?v=Tyqit541i2s)
* [タスク管理の新提案！ Office 365 Plannerとは？ (1/4)：CodeZine（コードジン）](https://codezine.jp/article/detail/9467)
* [Teams アプリ「タスク」 入門: Planner・To Do 統合  AvePoint Blog](https://www.avepoint.com/blog/ja/microsoft-teams-ja/teams-todo-planner/)
* [Microsoft Planner にて一般ユーザーによるプラン作成を制限する方法について](https://social.msdn.microsoft.com/Forums/ja-JP/92e21369-0f36-40df-8b56-712bc1402c9f/microsoft-planner?forum=sharepointsupportteamja)

## Teams

* [「Microsoft Teams」の「Project」「Roadmap」アプリ発表 - CNET Japan](https://japan.cnet.com/article/35161885/)
* [【Teams】すべてのTeamsから情報を取得する【PowerShell】  ほげふがな日常](https://www.hogehoge-note.com/2019/08/16/post-300/)
* [【オンライン セミナー】 Microsoft Teams を使いこなす! 活用事例の紹介](https://resources.office.com/ja-jp-landing-ondemand-JA-O365-WBNR-FY18-02Feb-23-Online-Seminar-Master-the-Microsoft-Teams-MCW0004285.html)
* [【タスク管理】Teams × Planner で実現。簡単！便利！](https://m.youtube.com/watch?v=Tyqit541i2s)
* [ASCII.jp：本日18時から日本.NET界レジェンドたちのTeams会議を生公開！「その.NETアプリ、クラウドどうモダナイズするの？」](https://ascii.jp/elem/000/001/905/1905256)
* [Microsoft Lists とは & Teams 接続方法  AvePoint Japan Blog](https://www.avepoint.com/blog/ja/office-365-ja/microsoft-lists/)
* [Microsoft Teams ：TIPSを色々詰め込んだ資料を公開しました！  Art-Break : Tech ;](https://art-break.net/tech/?p=7743)
* [Microsoft Teams 「ブレークアウトルーム」操作マニュアル](https://blogs.windows.com/japan/2020/12/18/microsoft-teams-breakoutroom-manual/)
* [Microsoft Teams でイベントの監査ログを検索する](https://docs.microsoft.com/ja-jp/microsoftteams/audit-log-events)
* [Microsoft Teams で共有されたファイルや IM を確認する方法  Microsoft Docs](https://docs.microsoft.com/ja-jp/archive/blogs/teamsjp/teams-inplace)
* [Microsoft Teams のチャット履歴を管理者が確認できるか？  idea.toString();](https://idea.tostring.jp/?p=2913)
* [Microsoft Teams の新機能  2020 年 5 月 - Windows Blog for Japan](https://blogs.windows.com/japan/2020/06/25/what-s-new-in-microsoft-teams-may-2020/)
* [Microsoft Teams リソース - Microsoft for business](https://www.microsoft.com/ja-jp/biz/wsi/teams-remote-work.aspx)
* [Microsoft Teams 管理ドキュメント - Microsoft Teams  Microsoft Docs](https://docs.microsoft.com/ja-jp/microsoftteams/)
* [Microsoft Teams 他が 1 年間試用できるようになるそうです - kazuakix の日記](https://blog.kazuakix.jp/entry/2018/05/03/182242)
* [Microsoft Teams 日本語カタログ 第2版と徹底活用ブック](https://blogs.windows.com/japan/2020/11/11/teams-catalog-booklet/)
* [Power Automate : Teams上で承認を行う](https://zezeze.hateblo.jp/entry/2019/11/29/040113)
* [Power Automate（旧Microsoft Flow）からMicrosoft TeamsへBotで投稿する方法3種をまとめてみた - Qiita](https://qiita.com/tfunakoshi/items/76029bcc8ac1d4d9bd71)
* [PowerShellからTeamsのAdaptive Card](https://qiita.com/syamamotorhead/items/5062cdcaaafc6740c0b2)
* [Skype for Business から Teams への移行](https://blog.kazuakix.jp/entry/2018/11/08/234326)
* [Teams クイックガイド](http://msft.it/6183TlOqZ)
* [Teams 関連のマニュアル](https://www.yammer.com/japanoffice365users/#/threads/show?threadId=281992120745984)
* [TeamsのAdaptive Cardにプロフィール画像を埋め込んでみた](https://qiita.com/syamamotorhead/items/5062cdcaaafc6740c0b2)
* [TeamsのWeb会議、上級活用法](https://xtech.nikkei.com/atcl/nxt/column/18/01362/)
* [Teamsのチームとチャネルの構成はこうせい！](https://blog.trainocate.co.jp/blog/teams01_020)
* [Teamsの会話をPSTファイルとしてエクスポートが可能！ExchangeOnlineライセンスが必要](https://1manit.work/windows/office365/teams/exportdata-pst/)
* [ノンコーディングで Microsoft Teams のチームをすべて取得する](https://qiita.com/yugoes1021/items/e042f793e5056591dfa2)

## OneDrive

* [【オンライン セミナー】 OneDrive for Business を便利に使うための設定大解説!](https://resources.office.com/ja-jp-landing-ondemand-JA-O365-WBNR-FY18-03Mar-07-OneDrive-for-Business-Great-commentary-MCW0004581.html)

## Microsoft Graph

* [Announcing “A Lap Around Microsoft Graph Toolkit” Blog Series - Microsoft 365 Developer Blog](https://developer.microsoft.com/en-us/graph/blogs/announcing-a-lap-around-microsoft-graph-toolkit-blog-series/)
* [GitHub - Office365APIEditor](https://github.com/microsoft/Office365APIEditor)
* [GitHub - Global Microsoft 365 Developer Bootcamp 2019 Tokyo：Microsoft Graph API](https://gist.github.com/rnakamuramartiny/13ae56ec3d97a468354c044bfdeea6df)
* [Microsoft Graph - OneDrive API (C#) を使ったサンプル コード](https://docs.microsoft.com/ja-jp/archive/blogs/office_client_development_support_blog/microsoft-graph-onedrive-api-c-sample-code)
* [Microsoft Graph (Unified API) のメリットとその使い方](https://tsmatz.wordpress.com/2015/06/22/office-365-unified-api/)
* [Microsoft Graph API を利用して Azure AD のサインイン アクティビティ レポートをファイルに出力する PowerShell スクリプト  Japan Azure Identity Support Blog](https://jpazureid.github.io/blog/azure-active-directory/microsoft-graph-api-signin-activity-reports/)
* [GitHub - rnakamuramartiny/GM365DevBootcamp_MGraphAPI.md](https://gist.github.com/rnakamuramartiny/13ae56ec3d97a468354c044bfdeea6df)
* [MS Build SK110 What's new with Microsoft Graph](https://www.youtube.com/watch?v=6CIZWac0TBE)
* [MsGraphSpFxThangu](https://www.youtube.com/watch?v=AKftsTLQBGo)
* [MVP Article ? Working with Application Permissions (App-Only Auth) in SharePoint Online and the Microsoft Graph](https://developer.microsoft.com/en-us/sharepoint/blogs/mvp-article-working-with-application-permissions-app-only-auth-in-sharepoint-online-and-the-microsoft-graph/)
* [Office 365 ? Microsoft Graph ? Part 4 Fetching all Office 365 groups using CSOM- Codebase](https://knowledge-junction.com/2018/12/25/office-365-microsoft-graph-part-4-fetching-all-office-365-groups-using-csom-codebase/)
* [Office 365 ? Microsoft Graph ? Part 6 Adding Office 365 Group Owner using CSOM ? Codebase](https://knowledge-junction.com/2018/12/27/office-365-microsoft-graph-part-6-adding-office-365-group-owner-using-csom-codebase/)
* [Office 365 ? Microsoft Graph ? Part 8 Getting all users of our tenant using CSOM](https://knowledge-junction.com/2019/01/12/office-365-microsoft-graph-part-8-getting-all-users-of-my-tenant-using-csom/)
* [PowershellでMicrosoft Graph APIを使う方法について](https://blogs.technet.microsoft.com/jpintune/2017/08/09/powershell%E3%81%A7microsoft-graph-api%E3%82%92%E4%BD%BF%E3%81%86%E6%96%B9%E6%B3%95%E3%81%AB%E3%81%A4%E3%81%84%E3%81%A6/)
* [PowershellでMicrosoft Graph APIを使う方法について](https://docs.microsoft.com/ja-jp/archive/blogs/jpintune/powershell%E3%81%A7microsoft-graph-api%E3%82%92%E4%BD%BF%E3%81%86%E6%96%B9%E6%B3%95%E3%81%AB%E3%81%A4%E3%81%84%E3%81%A6)
* [チュートリアル - Web アプリからアプリとして Microsoft Graph にアクセスする - Azure App Service](https://docs.microsoft.com/ja-jp/azure/app-service/scenario-secure-app-access-microsoft-graph-as-app)

# Intune

* [Export HW/SW Inventory Data from Intune Devices using PowerShell  Skatterbrainz Blog](https://skatterbrainz.wordpress.com/2020/01/18/export-hw-sw-inventory-data-from-intune-devices-using-powershell/)

# Azure

* [Azure環境作ったら最初にやるべきこと 2021年版](https://zenn.dev/tomot/articles/7ddeb902e8f426)

## Azure DNS

* [Azure 仮想ネットワーク内のリソースの名前解決](https://docs.microsoft.com/ja-jp/azure/virtual-network/virtual-networks-name-resolution-for-vms-and-role-instances)

> Azure DNS IP アドレスは 168.63.129.16 です。これは静的な IP アドレスであり、変更されません。

* [IP アドレス 168.63.129.16 とは](https://docs.microsoft.com/ja-jp/azure/virtual-network/what-is-ip-address-168-63-129-16)

## Microsoft Operations Management Suite

* [クラウド時代には、なぜ「ログ分析」が重要になるのか――高度なログ分析機能を、すぐに、簡単に使えるMicrosoft Operations Management Suite](https://atmarkit.itmedia.co.jp/ait/articles/1611/07/news010.html)
* [安全で管理の行き届いたクラウド](https://azure.microsoft.com/ja-jp/services/virtual-machines/secure-well-managed-iaas/#overview)
* [Azure Monitor](https://azure.microsoft.com/ja-jp/services/monitor/#overview)

## Cognitive Services

* [All Around Azure: Developers Guide to AI - 日本語配信](https://m.youtube.com/watch?v=rjtt6y_1Nak)
* [Cogbot Meetup Online #29 - Ignite 2020 キャッチアップ編](https://www.youtube.com/watch?v=cIgjQgLjMuQ)
* [Microsoftが誰でも簡単に機械学習モデルが作れるツール「Lobe」を公開！  Techable(テッカブル)](https://techable.jp/archives/140757)
* [AI Builder: AI Embedded in Power Apps- Part 1 - RADACAD](https://radacad.com/ai-builder-power-apps-embed-with-ai-part-1)
* [非エンジニア向け AI ビジネス スクール - tottokug  Microsoft Docs](https://docs.microsoft.com/ja-jp/users/tottokug/collections/2g78i6x8z1nxe)
* [AIのビジネス活用スタート](https://info.microsoft.com/rs/157-GQE-382/images/JA-CNTNT-Whitepaper-AIbusinessutilization-SRGCM1257.pdf)
* [Cognitive Services Custom Vision から画像解析モデルを Dockerimage に Export して利用する - Qiita](https://qiita.com/annie/items/3c0d0ec517d61526eb63)
* [Cognitive Services LUIS でノンコーディング自然言語分析始めよう (2019年6月版) - Qiita](https://qiita.com/annie/items/5fdc9030521f8a0ed61c)
* [Cognitive Services Speech Service ことはじめ_20190725](https://www.slideshare.net/ayomori/cogbot-cognitive-servicesspeechgettingstarted20190725)
* [GitHub - beachside-project/CustomVision-ML.NET-Hands-on: Create Image classifier in Custom Vision(Microsoft Cognitive Services) and Create App using ML.NET.](https://github.com/beachside-project/CustomVision-ML.NET-Hands-on)
* [開発者のためのAI アプリケーション開発ガイド](https://azure.microsoft.com/mediahandler/files/resourcefiles/create-your-first-intelligent-bot-with-microsoft-ai-ja-jp/JA-JP-CNTNT-eBook-AI-A-Developer's-Guide-to-Building-AI-Applications.pdf)

## Azure VM

* [Azure MonitorエージェントによるWindows仮想マシンの監視](https://cloudsteady.jp/post/50812/)
* [チュートリアル - Azure PowerShell を使用して Windows VM を作成および管理する](https://docs.microsoft.com/ja-jp/azure/virtual-machines/windows/tutorial-manage-vm)

## Azure vNET

* [Azure SQLDabase にプライベートなネットワークからアクセスしてみよう](https://blog.nextscape.net/archives/Date/2018/02/serviceendpointsqldb)
* [仮想ネットワークを使用してApp ServiceからAzure Sql Databaseへのアクセスを保護する方法](https://www.it-swarm.dev/ja/azure/%E4%BB%AE%E6%83%B3%E3%83%8D%E3%83%83%E3%83%88%E3%83%AF%E3%83%BC%E3%82%AF%E3%82%92%E4%BD%BF%E7%94%A8%E3%81%97%E3%81%A6app-service%E3%81%8B%E3%82%89azure-sql-database%E3%81%B8%E3%81%AE%E3%82%A2%E3%82%AF%E3%82%BB%E3%82%B9%E3%82%92%E4%BF%9D%E8%AD%B7%E3%81%99%E3%82%8B%E6%96%B9%E6%B3%95/838275760/)
* [aaSにプライベート接続を提供する サービスエンドポイント とは？](https://www.cloudou.net/virtual-network/vnet017/)
* [VNet Integrationを利用してWeb apps とAzure Databaseを接続してみる - ピロローグ](https://pir0.hatenablog.com/entry/2019/01/28/154423)

## Azure Logic Apps

* [Azure Logic Apps (Preview) を Visual Studio Codeで作成するための手順](https://mofumofupower.hatenablog.com/entry/2020/09/23/222908)
* [メールで届く添付ファイルの暗号化を自動解除するLogic Appsを作ろう (1/3)](https://ascii.jp/elem/000/004/029/4029136/)

## SendGrid

* [Azure でメールを受信するには  Microsoft Docs](https://docs.microsoft.com/ja-jp/archive/blogs/ainaba-csa/how-to-receive-email-by-azure)
* [Domain Authentication(SPF/DKIM設定)の設定方法](https://sendgrid.kke.co.jp/docs/User_Manual_JP/Settings/Sender_authentication/How_to_set_up_domain_authentication.html)
* [SendGrid で Gmail へ送信したメールに「sendgrid.me 経由」という表示をさせない設定](https://blog.shibayan.jp/entry/20150118/1421582136)
* [SendGrid 新人成長記　第九回　メールサーバを立ててメール送信してみた  SendGridブログ](https://sendgrid.kke.co.jp/blog/?p=12347)
* [SendGrid 電子メール サービスの使用方法 (.NET)  Microsoft Docs](https://docs.microsoft.com/ja-jp/azure/sendgrid-dotnet-how-to-send-email)
* [SendGridでメール配送を始めるためのまとめ - Qiita](https://qiita.com/shiru/items/0dbc48df217ffe51b1f3)
* [Webhookのデバッグに便利なツール「Beeceptor」の紹介  SendGridブログ](https://sendgrid.kke.co.jp/blog/?p=11260)
* [Webhookのデバッグに便利なツール「Webhook.site」の紹介  SendGridブログ](https://sendgrid.kke.co.jp/blog/?p=11340)
* [まず最初にすることシリーズ：メール送信までにするべきこと](https://sendgrid.kke.co.jp/blog/?p=10372)
* [メールのテストをする方法](https://sendgrid.kke.co.jp/blog/?p=10535)
* [メール運用がロストテクノロジーになっていく話 - Qiita](https://qiita.com/koichiro/items/d65ac1af03b9063f0592)
* [メール送信チュートリアル【まとめ】](https://sendgrid.kke.co.jp/blog/?p=10832)
* [携帯キャリアにメールを届けるための設定　～なりすまし規制編～](https://sendgrid.kke.co.jp/blog/?p=10875)
* [送信ドメインを認証するためのSPFレコードに詳しくなろう  SendGridブログ](https://sendgrid.kke.co.jp/blog/?p=3509)

## Azure DevOps

* [Azure  知って得する DevOps  初心者向け 13 #くらでべ](https://www.youtube.com/watch?v=U_w9qBB5pVU)
* [Azure DevOps + App Serviceで簡単にCI/CD環境を構築する](https://www.ryuzee.com/contents/blog/7136)
* [Azure DevOps セキュリティ設定解説](https://www.youtube.com/watch?v=pLqimyafx8A)
* [Azure TIPS API Apps の作成](https://www.youtube.com/watch?v=lIPJ7yYV-f8)
* [DevOpsで開発とデプロイのサイクルを高速化し、テストや監視で事前に障害を潰す。「オペレーショナルエクセレンス」実現のポイント - Qiita Zine](https://zine.qiita.com/topics/202102-caf-waf-3/)
* [ExcelマクロのVBAソースコードをAzure DevOpsでバージョン管理する方法  by Takeru Saso  Medium](https://medium.com/@saso_33429/excel%E3%83%9E%E3%82%AF%E3%83%AD%E3%81%AEvba%E3%82%BD%E3%83%BC%E3%82%B9%E3%82%B3%E3%83%BC%E3%83%89%E3%82%92azure-devops%E3%81%A7%E3%83%90%E3%83%BC%E3%82%B8%E3%83%A7%E3%83%B3%E7%AE%A1%E7%90%86%E3%81%99%E3%82%8B%E6%96%B9%E6%B3%95-d20b751ddc30)
* [ゼロからはじめるAzure(26) 「Azure DevOps」でチーム開発を行おう（2）Azure Boardsの概要と使い方  マイナビニュース](https://news.mynavi.jp/article/zeroazure-26/)
* [タスク管理をスプレッドシートからAzure Boardsにしたい人向けの話](https://kkamegawa.hatenablog.jp/entry/2020/10/03/133802)

## Azure API Management

* [Azure API Managementの紹介](https://blog.nextscape.net/archives/Date/2019/02/azureapimanagement)

## Azure Key Vault

* [ゼロからはじめるAzure(23) 「Azure Key Vault」を使ってセキュアなアプリを作ろう  マイナビニュース](https://news.mynavi.jp/article/zeroazure-23/)
* [Azure Key Vault のマネージド ストレージ アカウント - PowerShell バージョン  Microsoft Docs](https://docs.microsoft.com/ja-jp/azure/key-vault/secrets/overview-storage-keys-powershell)
* [Azure App Service で Azure Key Vault がめちゃ簡単に使えるようになりました（プレビュー）](https://blog.okazuki.jp/entry/2018/12/13/122834)
* [「Azure Key Vault」との連携で実現：Azure SQL Database／SQL Data Warehouseの透過的データ暗号化機能（TDE）で「Bring Your Own Key」をサポート - ＠IT](http://www.atmarkit.co.jp/ait/spv/1708/31/news064.html)

## Azure Pipelines

* [これからはじめるAzure Pipelines - Visual Studio Users Community Japan - kkamegawa's weblog](https://kkamegawa.hatenablog.jp/entry/2020/07/04/174915)
* [Azure Pipelinesを使ったCI/CD環境の構築～Web Apps編～](https://cloudsteady.jp/post/16551/)
* [(前編)CI/CDサービス「Azure Pipelines」入門 ～Microsoft Azure DevOps入門～](https://www.softbank.jp/biz/future_stride/entry/techblog/202001127_1/)

## Azure SQL

* [Azure SQL Database の便利機能!!使わないと損ですよ!!ネスケラボ](https://blog.nextscape.net/archives/Date/2017/11/azuresqldatabase01)
* [Azure SQLDabase にプライベートなネットワークからアクセスしてみよう](https://blog.nextscape.net/archives/Date/2018/02/serviceendpointsqldb)

## Azure Functions

* [今Serverlessが面白いわけ](https://www.slideshare.net/yokawasa/serverless-151261322)
* [Azure Serverless or Power Platform ～ あなたならどっち？！ ～ Power Platform 編](https://www.slideshare.net/yugoes1021/azure-serverless-or-power-platform-power-platform)
* [【初心者向け】Azureでサーバーレスな簡易Webアプリケーションを作るハンズオン - Qiita](https://qiita.com/himarin269/items/d4b1001e088c23ff40f3)
* [Azure Functionsを使ったイベント駆動アプリ](https://news.mynavi.jp/article/zeroazure-8/)
* [多分わかりやすいDurable Functions ?サーバーレスは次のステージへ?【入門編】  SIOS Tech. Lab](https://tech-lab.sios.jp/archives/12991)
* [Azure Functions - C# を活用するために気をつけていることをまとめてみる - tech.guitarrapc.cóm](https://tech.guitarrapc.com/entry/2016/04/16/052124)
* [サーバーレスアーキテクチャとAzure Functions](https://docs.microsoft.com/ja-jp/archive/blogs/azure-sa-members/azurefunctions)
* [Azure サーバーレス コンピューティング クックブック、第 2 版](https://azure.microsoft.com/ja-jp/resources/azure-serverless-computing-cookbook/)
* [Azure Functions その1 簡単な使い方を知る  RARPA　(ラーパ・RW高等研究計画局)](http://www.rarpa.net/?p=5877)
* [Azure FunctionsでEvent Webhookデータを受信する SendGridブログ](https://sendgrid.kke.co.jp/blog/?p=9403#2)
* [Azure Functions から SQL Database に書き込む (ポータル版とVS版)](https://chomado.com/programming/c-sharp/update-sql-database-from-azure-functions/)
* [Azure FunctionsでToken Bindingを使って、Azure Active DirectoryによるOAuth認証をラクチンにする](https://tech-lab.sios.jp/archives/12909)
* [【TIPS】Azure Function 内で使用する秘密の文字列をソースコードに直書きしない](https://docs.microsoft.com/ja-jp/archive/blogs/junichia/%E3%80%90tips%E3%80%91azure-function-%E5%86%85%E3%81%A7%E4%BD%BF%E7%94%A8%E3%81%99%E3%82%8B%E7%A7%98%E5%AF%86%E3%81%AE%E6%96%87%E5%AD%97%E5%88%97%E3%82%92%E3%82%BD%E3%83%BC%E3%82%B9%E3%82%B3%E3%83%BC)
* [Azure Functions から定期的に Microsoft Graph にアクセスする](https://docs.microsoft.com/ja-jp/archive/blogs/junichia/azure-functions-%E3%81%8B%E3%82%89%E5%AE%9A%E6%9C%9F%E7%9A%84%E3%81%AB-microsoft-graph-%E3%81%AB%E3%82%A2%E3%82%AF%E3%82%BB%E3%82%B9%E3%81%99%E3%82%8B)
* [Azure Functions における Azure Blob Storage の出力バインド](https://docs.microsoft.com/ja-jp/azure/azure-functions/functions-bindings-storage-blob-output?tabs=csharp)
* [Azure Functionsのお勉強メモ（7）Blob Storage出力バインドを使ってBlobにファイルを出力する その2](https://miyohide.hatenablog.com/entry/2021/04/25/174107)

## Azure App Service

* [AzurePaaS研究サイト](https://www.azureportal-site.com/appservice-functions-portal)
* [Azure App ServiceのVNet統合](https://tech-lab.sios.jp/archives/22563)
* [PaaSにプライベート接続を提供する サービスエンドポイント とは？](https://www.cloudou.net/virtual-network/vnet017/)
* [後悔しないための Azure App Service 設計パターン (2020 年版) - しばやん雑記](https://blog.shibayan.jp/entry/20200113/1578920798)
* [App Service で KeyVault 参照する手順 - ぐだぐだ言ってないでコードを書けよ、ハゲ。](https://kheiakiyama.hateblo.jp/entry/2018/12/09/002517)
* [Microsoft Azure入門 - Web Appsを使って簡単にWebアプリやAPIを公開してみよう - エンジニアHub若手Webエンジニアのキャリアを考える！](https://employment.en-japan.com/engineerhub/entry/2019/11/19/103000)

## AADC

* [デバイス ベースのアクセス制御  Microsoft Docs](https://docs.microsoft.com/ja-jp/archive/blogs/jpazureid/device_access)
* [登録されたデバイスの管理方法  Microsoft Docs](https://docs.microsoft.com/ja-jp/archive/blogs/jpazureid/registerd_device_managemant)
* [サイトのユーザー情報を強制的に AD と同期させる方法](https://docs.microsoft.com/ja-jp/archive/blogs/sharepoint_support/ad)
* [Azure AD Connectを使ってアカウントを同期する方法](https://www.gmo.jp/report/single/?art_id=244)

## WindowsVirtualDesktop

* [今話題のWindows Virtual Desktopが大型アップデート！](https://licensecounter.jp/azure/blog/trend/windows-virtual-desktop-update.html)
* [【Windows Virtual Desktopのディープな技術情報を解説】 #1 新しい管理ポータル](https://zine.qiita.com/topics/202010-wvd-1/)
* [【Windows Virtual Desktopのディープな技術情報を解説】WVDにおけるネットワークセキュリティ - Qiita Zine](https://zine.qiita.com/topics/202010-wvd-2/)
* [IT リソース キット Windows Virtual Desktop の使用を開始する](https://clouddamcdnprodep.azureedge.net/gdc/gdcamLwLh/original)
* [Windows Virtual Desktop Event](https://info.microsoft.com/ww-landing-windows-virtual-desktop.html?ocid=AID3027037_QSG_496862)
* [Windows Virtual Desktop 最短構築方法解説](https://www.gmo.jp/report/single/?art_id=261)

## Cost

* [CSPのAzure明細をPowerShellで整形する  日々徒然](https://blog.o365mvp.com/2020/04/07/format-csp-reconcile-with-powershell/)

## Azure Red Hat OpenShift

* [Microsoft Azure Red Hat OpenShift (ARO) その１ - 赤帽エンジニアブログ](https://rheb.hatenablog.com/entry/2021/06/30/Microsoft_Azure_Red_Hat_OpenShift_%28ARO%29_%E3%81%9D%E3%81%AE%EF%BC%91)

## Migration

* [What is Azure Resource Mover?](https://docs.microsoft.com/en-us/azure/resource-mover/overview)
* [徹底解説！できる Azure Migrate](https://info.microsoft.com/JA-AzureMig-CNTNT-FY20-03Mar-18-Thoroughcommentary-SRGCM3343_01Registration-ForminBody.html)

## Azure Backup

* [Azure BackupでVMを簡単バックアップ＆リカバリ  SIOS Tech. Lab](https://tech-lab.sios.jp/archives/18881)

## Azure Bastion

* [Azure Bastion 試したよ](https://sshzk.blogspot.com/2019/07/azure-bastion.html)

## Azure PowerShell

* [ゼロからはじめるAzure(36) 新しいターミナルアプリ「Windows Terminal」からAzureを操作しよう  マイナビニュース](https://news.mynavi.jp/article/zeroazure-36/)

* [Azure Key Vault のマネージド ストレージ アカウント - PowerShell バージョン  Microsoft Docs](https://docs.microsoft.com/ja-jp/azure/key-vault/secrets/overview-storage-keys-powershell)
* [クイック スタート:Azure Resource Graph エクスプローラーを使用して初めての Resource Graph クエリを実行する](https://docs.microsoft.com/ja-jp/azure/governance/resource-graph/first-query-portal)
* [PowerShell Script: 使用されていない不要な Azure リソースを自動検知して削除する](https://docs.microsoft.com/ja-jp/archive/blogs/jpaztech/cleanup-unused-storage)

## Azure Cosmos DB

* [Azure Cosmos DB for MongoDB API with Xamarin Quick Start](https://docs.microsoft.com/en-us/samples/azure-samples/azure-cosmos-db-mongodb-xamarin-getting-started/azure-cosmos-db-mongodb-xamarin-getting-started/)
* [GitHub - DocumentDB-Quickstart-DotNet](https://github.com/dzadnip/DocumentDB-Quickstart-DotNet)
* [Azure Cosmos DB 自習書 Azure Cosmos DB 入門 SQL API 編](https://www.cloud-for-all.com/resource/azure-cosmos-db-sql-api)

## Application Insights

* [既存の Application Insights を Workspace ベースに移行した - しばやん雑記](https://blog.shibayan.jp/entry/20200928/1601229167)
* [世界一わかりみの深いAPM 〜Application Insightsでアプリケーションパフォーマンス管理に全集中！！〜](https://tech-lab.sios.jp/archives/23948)

## Azure Bot Service

* [ノンコーディングで簡易FAQ Slack Botを作ってみた話（QnA Maker ＋ Azure Bot Service）](https://zuvuyalink.net/nrjlog/archives/4368)
* [次世代コミュニケーションツール「チャットボット」の活用 ?Azure Bot ServiceでAzureのことに何でも答えてくれるLINEボットを作る ?【概要編】  SIOS Tech. Lab](https://tech-lab.sios.jp/archives/17023)

## Azure Application Gateway

### Setting_AAG

* [クイック スタート:Azure Application Gateway による Web トラフィックのルーティング - Azure portal](https://docs.microsoft.com/ja-jp/azure/application-gateway/quick-create-portal)
* [【Azure】 Application Gateway 設定を解説する](https://qiita.com/hikaru_motomiya/items/d5fd669e3eb3a8491022)
* [Application Gateway の構成について](https://jpaztech1.z11.web.core.windows.net/ApplicationGateway%E3%81%AE%E6%A7%8B%E6%88%90%E3%81%AB%E3%81%A4%E3%81%84%E3%81%A6.html)
* [Azure Application Gateway の整理](https://blog.memobog.net/2018/11/11/application-gateway-201811/)
* [Application Gateway での無効なゲートウェイによるエラーのトラブルシューティング](https://docs.microsoft.com/ja-jp/azure/application-gateway/application-gateway-troubleshooting-502)
* [Application Gateway リスナーの構成](https://docs.microsoft.com/ja-jp/azure/application-gateway/configuration-listeners)
* [Setting up Application Gateway with an App Service that uses Azure Active Directory Authentication](https://techcommunity.microsoft.com/t5/apps-on-azure-blog/setting-up-application-gateway-with-an-app-service-that-uses/ba-p/392490)
* [Enable remote access to SharePoint with Azure Active Directory Application Proxy](https://docs.microsoft.com/en-us/azure/active-directory/app-proxy/application-proxy-integrate-with-sharepoint-server)
* [ポータルを使用して Application Gateway での相互認証を構成する](https://docs.microsoft.com/ja-jp/azure/application-gateway/mutual-authentication-portal)
* [Application Gateway に関してよく寄せられる質問](https://docs.microsoft.com/ja-jp/azure/application-gateway/application-gateway-faq)
* [Application Gateway での相互認証の概要](https://docs.microsoft.com/ja-jp/azure/application-gateway/mutual-authentication-overview)
* [Application Gateway での相互認証エラーのトラブルシューティング](https://docs.microsoft.com/ja-jp/azure/application-gateway/mutual-authentication-troubleshooting)
* [クライアント認証で使用する信頼されたクライアント CA 証明書チェーンをエクスポートする](https://docs.microsoft.com/ja-jp/azure/application-gateway/mutual-authentication-certificate-management)
* [Azure Application Gateway でバックエンドを許可する証明書を作成する](https://docs.microsoft.com/ja-jp/azure/application-gateway/certificates-for-backend-authentication)
* [What is Azure Application Gateway?](https://docs.microsoft.com/en-us/azure/application-gateway/overview)

### Microsoft_AAG

* [Using Azure Application Gateway to publish applications](https://savilltech.com/2018/03/17/using-azure-application-gateway-to-publish-applications/)
* [Azure Application Gateway とは](https://docs.microsoft.com/ja-jp/azure/application-gateway/overview)
* [Application Gateway の価格](https://azure.microsoft.com/ja-jp/pricing/details/application-gateway/)
* [Application Gateway](https://azure.microsoft.com/ja-jp/services/application-gateway/)
* [Azure Application Gateway の機能](https://docs.microsoft.com/ja-jp/azure/application-gateway/features)
* [Azure Application Gateway v2 とは](https://docs.microsoft.com/ja-jp/azure/application-gateway/overview-v2)
* [Application Gateway 構成の概要](https://docs.microsoft.com/ja-jp/azure/application-gateway/configuration-overview)
* [Azure Application Gateway のドキュメント](https://docs.microsoft.com/ja-jp/azure/application-gateway/)
* [Azure Web アプリケーション ファイアウォールとは](https://docs.microsoft.com/ja-jp/azure/web-application-firewall/overview)
* [Application Gateway での TLS 終端とエンド ツー エンド TLS の概要](https://docs.microsoft.com/ja-jp/azure/application-gateway/ssl-overview)
* [アプリケーション ゲートウェイの動作](https://docs.microsoft.com/ja-jp/azure/application-gateway/how-application-gateway-works)
* [Application Gateway で HTTP ヘッダーと URL を書き換える](https://docs.microsoft.com/ja-jp/azure/application-gateway/rewrite-http-headers-url)
* [Application Gateway の複数サイトのホスト](https://docs.microsoft.com/ja-jp/azure/application-gateway/multiple-site-overview)
* [Application Gateway の HTTP 設定の構成](https://docs.microsoft.com/ja-jp/azure/application-gateway/configuration-http-settings)
* [App Service などのマルチテナント バックエンドに対する Application Gateway のサポート](https://docs.microsoft.com/ja-jp/azure/application-gateway/application-gateway-web-app-overview)
* [PowerShell を使用して Application Gateway で App Service を構成する](https://docs.microsoft.com/ja-jp/azure/application-gateway/create-web-app)


### Web_AAG

* [Application Gateway v2 の Key Vault 連携を試してみた - しばやん雑記](https://blog.shibayan.jp/entry/20190428/1556442190)
* [Azure Application Gatewayとは？負荷分散の考え方とWebアプリケーションの負荷分散について解説](https://www.rworks.jp/cloud/azure/azure-column/azure-entry/24604/)
* [Azure Application Gatewayとは？その概要と機能、メリットについて](https://www.cloud-for-all.com/blog/azure-application-gateway.html)
* [証明書の設定Azure Application Gateway 新規／更新用](https://www.secomtrust.net/service/pfw/apply/sr/3_2_AZURE_APPGW.html)
* [Application Gateway のアクセスログについて](https://cptechweb.teldevice.co.jp/hc/ja/articles/360063918373-Application-Gateway-%E3%81%AE%E3%82%A2%E3%82%AF%E3%82%BB%E3%82%B9%E3%83%AD%E3%82%B0%E3%81%AB%E3%81%A4%E3%81%84%E3%81%A6)
* [Webシステムの負荷分散に力を発揮！Azure Application Gatewayの機能とは？](https://business.ntt-east.co.jp/content/cloudsolution/column-118.html)
* [Azure Application Gatewayのリスナー証明書を自動で更新する](https://ascii.jp/elem/000/004/052/4052122/)
* [Azure Application Gateway(アプリケーションゲートウェイ)とは](https://www.acrovision.jp/service/azure/?p=467)
* [Azure Application Gatewayでリダイレクトを設定する](https://tech-blog.cloud-config.jp/2020-12-12-application-gateway-redirect/)
* [Azure Application Gatewayを使用したインバウンドトラフィックの検査](https://cloudone.trendmicro.com/docs/jp/network-security/Azure_Deployment5_VMSS_AGW/)
* [Webサーバー向けロードバランサー「Azure Application Gateway」とは？](https://www.cloudou.net/application-gateway/appg001/)
* [Application Gateway - App Service 間のリダイレクトの問題](https://jpaztech.github.io/blog/network/appgw-appservice-redirectissue/)

## SQL Managed Instance

### Microsoft_SQLMI

* [Azure SQL での Azure AD 認証を構成して管理する](https://docs.microsoft.com/ja-jp/azure/azure-sql/database/authentication-aad-configure?tabs=azure-powershell)
* [クイックスタート: Azure SQL Managed Instance に接続するように Azure VM を構成する](https://docs.microsoft.com/ja-jp/azure/azure-sql/managed-instance/connect-vm-instance-configure)
* [機能の比較: Azure SQL Database と Azure SQL Managed Instance](https://docs.microsoft.com/ja-jp/azure/azure-sql/database/features-comparison)
* [移行の概要: SQL Server から Azure SQL Managed Instance](https://docs.microsoft.com/ja-jp/azure/azure-sql/migration-guides/managed-instance/sql-server-to-managed-instance-overview)
* [Azure Active Directory 認証を使用する](https://docs.microsoft.com/ja-jp/azure/azure-sql/database/authentication-aad-overview)
* [Azure SQL Database と SQL Managed Instance のセキュリティ機能の概要](https://docs.microsoft.com/ja-jp/azure/azure-sql/database/security-overview)
* [Azure SQL Managed Instance とは](https://docs.microsoft.com/ja-jp/azure/azure-sql/managed-instance/sql-managed-instance-paas-overview)
* [クイック スタート: Azure SQL Managed Instance を作成する](https://docs.microsoft.com/ja-jp/azure/azure-sql/managed-instance/instance-create-quickstart)
* [SharePoint Server でユーザー認証方法を計画する](https://docs.microsoft.com/ja-jp/sharepoint/security-for-sharepoint-server/plan-user-authentication)
* [チュートリアル:Windows VM のシステム割り当てマネージド ID を使用して Azure SQL にアクセスする](https://docs.microsoft.com/ja-jp/azure/active-directory/managed-identities-azure-resources/tutorial-windows-vm-access-sql)
* [データベース接続アップグレード用の SharePoint Server 2016 ファームを作成する](https://docs.microsoft.com/ja-jp/sharepoint/upgrade-and-update/create-the-sharepoint-server-2016-farm-for-a-database-attach-upgrade)
* [マネージド ID を使用して他のサービスにアクセスできる Azure サービス](https://docs.microsoft.com/ja-jp/azure/active-directory/managed-identities-azure-resources/managed-identities-status)
* [Azure リソースのマネージド ID とは](https://docs.microsoft.com/ja-jp/azure/active-directory/managed-identities-azure-resources/overview)

### Web_SQLMI

* [Azureで利用可能なPaaSのSQL Serverの特徴を学ぼう［前編］](https://atmarkit.itmedia.co.jp/ait/articles/1904/01/news010.html)
* [Azureで利用可能なPaaSのSQL Serverの特徴を学ぼう［後編］――Azure SQL DatabaseとAzure SQL Database Managed Instanceの違い](https://atmarkit.itmedia.co.jp/ait/articles/1904/12/news010_2.html)

## Azure Infomation Protection

### Microsoft_AIP

* [はじめての データの保護: Azure Information Protection  日本マイクロソフト](https://youtu.be/roQs7PBjXIk)
* [AIP試してみた](https://www.qes.co.jp/media/azure/a155)
* [Final reminder to migrate from Azure Information Protection classic client to unified labeling](https://techcommunity.microsoft.com/t5/security-compliance-and-identity/final-reminder-to-migrate-from-azure-information-protection/ba-p/2731734)
* [Azure Information Protection requirements](https://docs.microsoft.com/en-us/azure/information-protection/requirements#applications)
* [Azure Information Protection と AD RMS の比較](https://docs.microsoft.com/ja-jp/azure/information-protection/compare-on-premise)
* [Azure Information Protection とは](https://docs.microsoft.com/ja-jp/azure/information-protection/what-is-information-protection)
* [チュートリアル: Azure Information Protection ポリシーの設定を構成して新しいラベルを作成する](https://docs.microsoft.com/ja-jp/azure/information-protection/infoprotect-quick-start-tutorial)

### WebSite_AIP

* [Officeデータの情報漏洩対策に大活躍！Azure Information Protectionとは？](https://www.jbsvc.co.jp/useful/windows10/what-is-AIP.html)
* [新しい情報保護機能「AIP」](https://licensecounter.jp/office365/blog/2017/03/info-AzureInformationProtection.html)
* [ファイルの保護・暗号化](https://ci.iii.kyushu-u.ac.jp/365/aip/)
* [自分に合った保護と共有](https://track.azurerms.com/#/landing)
* [Azure Information Protectionを紹介したかったがMicrosoft Information Protectionに統合されてたのでそのご紹介 ①](https://www.challenge-cf.jp/post/azure-information-protection%E3%82%92%E7%B4%B9%E4%BB%8B%E3%81%97%E3%81%9F%E3%81%8B%E3%81%A3%E3%81%9F%E3%81%8Cmicrosoft-information-protection%E3%81%AB%E7%B5%B1%E5%90%88%E3%81%95%E3%82%8C%E3%81%A6%E3%81%9F%E3%81%AE%E3%81%A7%E3%81%9D%E3%81%AE%E3%81%94%E7%B4%B9%E4%BB%8B)
* [Azure Information Protection でファイルのアクセス権はく奪（プレビュー）](https://live-style.jp/aip-deprivation/)
* [Windows Information Protection を正しく知る：Microsoft 365で実現するクラウド時代のセキュリティ（4） - ＠IT](https://www.atmarkit.co.jp/ait/articles/1906/28/news022.html)
* [Windows Information Protection を正しく知る　～設定編～：Microsoft 365で実現するクラウド時代のセキュリティ（5） - ＠IT](https://www.atmarkit.co.jp/ait/articles/1907/24/news011.html#cxrecs_s)

# Web

## VScode

* [コードを書くのが楽になる！知っておくと便利なVS Codeの機能・設定のまとめ  コリス](https://coliss.com/articles/build-websites/operation/work/vs-code-dont-need-extensions.html)
* [VS CodeでHTMLを楽々コーディング！ (1/2)](https://www.atmarkit.co.jp/ait/articles/1806/26/news032.html)
* [WebコーダーがVSCodeで使いたいショートカットと設定、拡張機能](https://haniwaman.com/web-vscode/)
* [VS Codeの見やすいテーマが登場！GitHubのデザインでコードも快適に -GitHub VS Code theme  コリス](https://coliss.com/articles/build-websites/operation/work/github-vscode-theme.html)

## Carousel

* [Bootstrapで画像をアルバムみたいにカッコよく表示しよう](https://codezine.jp/article/detail/8350)
* [bootstrapのカルーセルの使い方とカスタマイズのサンプルを紹介](https://be-engineer.jp/programming/514/)
* [カルーセルUIを実現するJSライブラリまとめ(2021年版) - 導入手間や機能の比較紹介](https://ics.media/entry/210902/)

## html

* [HTML/CSS初学者がつまづきやすい記述ミスと修正方法  Webクリエイターボックス](https://www.webcreatorbox.com/tech/html-css-beginner)
* [初心者向け！HTML/CSSのコーディング手順をイチからしっかりと。  Webクリエイターボックス](https://www.webcreatorbox.com/tech/html-css-coding-steps)
* [「全ての住所フォームがこうなってほしい」　SIerが公開した“使いやすい入力欄”の作り方が話題　ソースコードも掲載](https://www.itmedia.co.jp/news/articles/2203/02/news056.html)
* [【暫定】コーダー歴2年で辿り着いた保守しやすいコーディング手法](https://zenn.dev/haniwaman/articles/bf392f397c8db7341881)
* [HTML Living Standard HTML要素チートシート](https://htmlls.docs-share.com/)
* [HTMLコーダーにとっての2020年](https://ics.media/entry/200710/)
* [Webサイトのコーディングで困る前に知っておきたい3つのポイント](https://stocker.jp/diary/web-coding-point/)
* [Webフォントで文字化けしたときのよくある原因と対処法](http://blog.1dz.jp/?eid=830)
* [Web制作が捗るChrome拡張機能12選 – おすすめの拡張機能を集めてみた  Pulp Note - WebデザインやWebサイト制作の現場で使えるTipsやアイデアを紹介](https://pulpxstyle.com/chrome-extensions/)
* [Web制作の効率、生産性アップ！話題の最新オンラインツール33個まとめ - PhotoshopVIP](https://photoshopvip.net/126320)
* [アコーディオンのアイコン：どのシグニファイアが最適か – U-Site](https://u-site.jp/alertbox/accordion-icons/)
* [配色に迷ったらこれ！配色イメージを言語化して論理的に伝えられるスケールがめちゃくちゃ役に立つ「語彙力ない私にうってつけ」 - Togetter](https://togetter.com/li/1744709)
* [これから使い始めたいWebフォント＆Google Font活用法まとめ](https://ascii.jp/elem/000/001/220/1220736/)
* [「誰がこんなネーミングにしたんだ……。」プログラミングのネーミングルールを決める時に参考にしたい情報まとめ](https://ferret-plus.com/4680)
* [フロントエンドエンジニア必見！JavaScript開発現場で人気の「Webpack」とは？](https://ferret-plus.com/6337)
* [地味にスゴいってホント!? わかりやすくHTML5.1の追加された新機能を紹介](https://ferret-plus.com/5693)
* [2020年、オンラインサービスやWebアプリの開発を独学で勉強したい人に役立つ練習プロジェクトのまとめ  コリス](https://coliss.com/articles/build-websites/operation/work/8-projects-with-modern-designs.html)
* [Bootstrap 5の作業環境の構築方法、jQueryを使用しないJavaScriptでの実装方法を解説  コリス](https://coliss.com/articles/build-websites/operation/work/bootstrap-5-tutorial-without-jquery.html)
* [CSSで画像の上に表示するテキストをより読みやすく、より美しくするテクニック・実装方法のまとめ  コリス](https://coliss.com/articles/build-websites/operation/css/handling-text-over-images-in-css.html)
* [HTML5の基本テンプレートファイル一式、Webページを実装するための必要最小限をまとめたHTML  コリス](https://coliss.com/articles/build-websites/operation/work/html-template-for-web-apps-or-sites.html)
* [HTMLのtableにクラスを加えるだけで、グラフやチャートを簡単に実装できるCSSのフレームワーク -Charts.css](https://coliss.com/articles/build-websites/operation/css/charts-css-for-data-visualization.html)
* [JavaScriptでのメディアクエリ、matchMediaの使い方を解説  コリス](https://coliss.com/articles/build-websites/operation/javascript/javascript-media-queries.html)
* [Responsive Height Design -レスポンシブを高さの観点から、Webサイトやスマホアプリの実装で役立つテクニック](https://coliss.com/articles/build-websites/operation/css/responsive-height-design.html)
* [Webページやスマホアプリでよく使用される代表的な5つのレイアウトをCSS Gridで実装するテクニック  コリス](https://coliss.com/articles/build-websites/operation/css/css-grid-with-5-layouts.html)
* [Web制作者は要チェック！最近のランディングページで見かけるデザインやアイデアのまとめ -SaaS Pages](https://coliss.com/articles/build-websites/operation/work/collection-of-the-best-landing-pages.html)
* [これなら簡単で便利！最近見かけるCSSのさまざまなコンポーネントをコピペで利用できる -CodyHouse Framework  コリス](https://coliss.com/articles/build-websites/operation/css/codyhouse-framework-2-0.html)
* [よく使われるレイアウトやUIコンポーネント、それだけを実装するためのHTMLとCSSのシンプルなコードのまとめ  コリス](https://coliss.com/articles/build-websites/operation/css/popular-layouts-and-patterns-made-with-css.html)
* [最近の実装に合わせた最新版HTMLテンプレート、基本構造に使用するすべての要素とその役割も解説  コリス](https://coliss.com/articles/build-websites/operation/work/html-boilerplate-by-mmatuzo.html)
* [新しくなったBootstrap 5を使用して、管理画面のUIを実装する方法を解説  コリス](https://coliss.com/articles/build-websites/operation/work/bootstrap-5-dashboard-tutorial.html)
* [知っておくと便利なHTML5の機能、要素や属性のまとめ  コリス](https://coliss.com/articles/build-websites/operation/work/10-useful-html5-features.html)
* [地味に便利！さまざまなプロジェクトに適したHTMLのテンプレートを簡単に生成できる -HTML Boilerplates  コリス](https://coliss.com/articles/build-websites/operation/work/html-boilerplates.html)

## css

* [ほんの数行のCSSで実装できる小技テクニック12個まとめ 【簡単＆実用的】](https://photoshopvip.net/127316)
* [簡単CSSアニメーション＆デザイン20選（ソースコードと解説付き）](https://baigie.me/officialblog/2021/02/25/css-tips-1/)
* [ブレイクポイントは特定のデバイスの画面サイズを基準にしない](https://zenn.dev/tak_dcxi/articles/690caf6e9c4e26)
* [CSSコピペで完成！押したくなるWebボタンデザインまとめ](https://photoshopvip.net/130681)
* [CSSだけでできるあんなことこんなこと - Qiita](https://qiita.com/rana_kualu/items/43e8841a4fccb8a80113)
* [Amazonも！有名WebサイトのCSSボタンデザイン77個をコピペ再現できる Copy ＆ Paste CSS](https://photoshopvip.net/129699)
* [【第3弾】少しのコードで実装可能な15のCSS小技集](https://www.webcreatorbox.com/tech/css-tips-3)
* [Web制作の面倒な作業をラクにするCSS便利ツール59個まとめ - PhotoshopVIP](http://photoshopvip.net/123398)
* [CodePen Home Blurred Background CSS](https://codepen.io/ariona/pen/geFIK)
* [Super simple CSS tooltips](https://codepen.io/mildrenben/pen/rVBrpK)
* [CSSだけでできるあんなことこんなこと - Qiita](https://qiita.com/rana_kualu/items/43e8841a4fccb8a80113)
* [打ち込むより簡単！保存しておくと便利なCSSスニペット18選](https://ferret-plus.com/6036)
* [CSSでフォームの実装に悩んだら！ さまざまなフレームワークで実装されたフォームのライブラリ -HeroTofu](https://coliss.com/articles/build-websites/operation/css/html-forms-library-herotofu.html)
* [Web制作者は要チェック！Instagramに使用されているCSSのテクニック](https://coliss.com/articles/build-websites/operation/css/css-techniques-used-for-instagram.html)
* [これなら簡単で便利！最近見かけるCSSのさまざまなコンポーネントをコピペで利用できる -CodyHouse Framework  コリス](https://coliss.com/articles/build-websites/operation/css/codyhouse-framework-2-0.html)
* [CSS GridをChrome デベロッパーツールで検証、デバッグする方法を解説](https://coliss.com/articles/build-websites/operation/css/inspect-css-grid-by-chrome-devtools.html)
* [2020年のCSSのまとめ、FlexboxやCSS Gridの使用状況、よく使用するプロパティや単位、人気のフレームワークやツールなど](https://coliss.com/articles/build-websites/operation/css/the-state-of-css-2020.html)

## Bootstrap

* [初心者でもWeb制作ができる！CSSフレームワーク「Bootstrap」入門編](https://ferret-plus.com/5129)
* [Bootstrap（ブートストラップ）を使ったランディングページの無料デザインテンプレート35選](https://ferret-plus.com/8517)
* [Microsoft、「WinUI 2.5」を公開 ～プログレスリングやBootstrap風の情報バーを追加／ナビゲーションペインにはフッターメニューを設定できるように](https://forest.watch.impress.co.jp/docs/news/1293642.html)
* [Bootstrap Carousel in SPFX (ReactJS)](https://www.c-sharpcorner.com/article/bootstrap-carousel-in-spfxreactjs/)
* [新しくなったBootstrap 5を使用して、管理画面のUIを実装する方法を解説  コリス](https://coliss.com/articles/build-websites/operation/work/bootstrap-5-dashboard-tutorial.html)
* [Bootstrap 5の作業環境の構築方法、jQueryを使用しないJavaScriptでの実装方法を解説  コリス](https://coliss.com/articles/build-websites/operation/work/bootstrap-5-tutorial-without-jquery.html)

## JavaScript

* [動かして学ぶ！ Rustの言語仕様](https://codezine.jp/article/detail/15083)
* [個人でWebアプリを開発する時に便利な高機能JavaScriptライブラリ6選！](https://paiza.hatenablog.com/entry/2018/12/26/%E5%80%8B%E4%BA%BA%E3%81%A7Web%E3%82%A2%E3%83%97%E3%83%AA%E3%82%92%E9%96%8B%E7%99%BA%E3%81%99%E3%82%8B%E6%99%82%E3%81%AB%E4%BE%BF%E5%88%A9%E3%81%AA%E9%AB%98%E6%A9%9F%E8%83%BDJavaScript%E3%83%A9%E3%82%A4)
* [わずか数行のJavaScriptで機械学習をフル活用できる無料Webサービス「StackML」を使ってみた！ - paiza開発日誌](https://paiza.hatenablog.com/entry/2019/07/03/%E3%82%8F%E3%81%9A%E3%81%8B%E6%95%B0%E8%A1%8C%E3%81%AEJavaScript%E3%81%A7%E6%A9%9F%E6%A2%B0%E5%AD%A6%E7%BF%92%E3%82%92%E3%83%95%E3%83%AB%E6%B4%BB%E7%94%A8%E3%81%A7%E3%81%8D%E3%82%8B%E7%84%A1%E6%96%99Web)
* [JavaScriptだけでExcel風のスプレッドシートを開発できる「jExcel」を使ってみた！ - paiza開発日誌](https://paiza.hatenablog.com/entry/2020/06/10/JavaScript%E3%81%A0%E3%81%91%E3%81%A7Excel%E9%A2%A8%E3%81%AE%E3%82%B9%E3%83%97%E3%83%AC%E3%83%83%E3%83%89%E3%82%B7%E3%83%BC%E3%83%88%E3%82%92%E9%96%8B%E7%99%BA%E3%81%A7%E3%81%8D%E3%82%8B%E3%80%8CjExcel)
* [Vue Formulate ?? The easiest way to build forms with Vue.js](https://vueformulate.com/#live-code-examples)
* [Essential Cheat Sheet: Convert jQuery to JavaScript](https://webdesign.tutsplus.com/articles/essential-cheat-sheet-convert-jquery-to-javascript--cms-35633)
* [脱jQueryの道 初級編](https://www.webopixel.net/javascript/1487.html)
* [JavaScriptでのメディアクエリ、matchMedia()の使い方を解説  コリス](https://coliss.com/articles/build-websites/operation/javascript/javascript-media-queries.html)
* [便利なのが登場！フォームのバリデーションをシンプルな記述で実装できる超軽量JavaScriptライブラリ -v8n](https://coliss.com/articles/build-websites/operation/javascript/js-validation-library-v8n.html)
* [知っておくと実装に役立つ！JavaScriptのテクニックのまとめ](https://coliss.com/articles/build-websites/operation/javascript/javascript-tips-by-garvitmotwani.html)

# Develop

## PowerShell

* [【Write-Verbose】スクリプトや関数の詳細を表示する【PowerShell】](https://www.tekizai.net/entry/2021/08/26/063000)
* [Windows PowerShell基本Tips](https://www.atmarkit.co.jp/ait/series/3410/)

## csharp

* [GitHub - microsoft/TailwindTraders](https://github.com/microsoft/TailwindTraders)
* [Home - Fluent UI](https://developer.microsoft.com/en-us/fluentui#/)
* [The .NET Portability Analyzer - .NET  Microsoft Docs](https://docs.microsoft.com/en-us/dotnet/standard/analyzers/portability-analyzer)
* [Minimal API の概要](https://docs.microsoft.com/ja-jp/aspnet/core/fundamentals/minimal-apis?view=aspnetcore-6.0)
* [.NET Core での自己完結型アプリのデプロイにおけるランタイムのロール フォワード - .NET Core  Microsoft Docs](https://docs.microsoft.com/ja-jp/dotnet/core/deploying/runtime-patch-selection)
* [.NET Core で使用できない .NET Framework テクノロジ  Microsoft Docs](https://docs.microsoft.com/ja-jp/dotnet/core/porting/net-framework-tech-unavailable)
* [C# で Single Page Web Application が書ける Blazor が凄かった件 - Qiita](https://qiita.com/jsakamoto/items/20d4893f6c8cdb0356f6)
* [【連載】PowerShell Core入門 - 基本コマンドの使い方 * [2] PowerShell Coreのインストールサーバ/ストレージIT製品の事例・解説記事](https://news.mynavi.jp/itsearch/article/hardware/3628)
* [PowerMap サンプル](https://onedrive.live.com/?id=A9FD866E9122F8EA%21107&cid=A9FD866E9122F8EA)
* [C#で東京メトロオープンデータAPIを使って遅延時間(遅延情報)を取得する](https://blog.ch3cooh.jp/entry/20140922/1411349400)
* [【特集】LINEログイン～読めばわかる！ 導入方法、活用事例からメリットまで](https://blog.feedmatic.net/linelogin/)
* [web.configの暗号化](https://blogonos.wordpress.com/2006/02/23/web-config%E3%81%AE%E6%9A%97%E5%8F%B7%E5%8C%96/)
* [UWPアプリを作るとき、画面遷移やアーキテクチャで悩んだら!? ～Windows Template Studioを使ってみよう](https://codezine.jp/article/detail/11282)
* [C#でSPAが実現できる、Blazor WebAssemblyのはじめかた (1/3)：CodeZine（コードジン）](https://codezine.jp/article/detail/13036)
* [多分わかりやすいC#のDelegateとラムダ式入門  SIOS Tech. Lab](https://tech-lab.sios.jp/archives/15318)
* [多分わかりやすいC#の非同期処理その1 ? ThreadとTask ?  SIOS Tech. Lab](https://tech-lab.sios.jp/archives/15637)

## Windows Terminal

* [Microsoftが紹介する「Windows Terminal」のカスタマイズや活用のコツ](https://www.atmarkit.co.jp/ait/articles/2011/04/news052.html)
* [Azure Cloud ShellをローカルのVisual Studio Code／Windows Terminalに統合する方法：Microsoft Azure最新機能フォローアップ（89） - ＠IT](https://www.atmarkit.co.jp/ait/articles/1908/27/news017.html)

## ASP.NETIdentity

* [空または既存の Web フォームプロジェクトへの ASP.NET Identity の追加-ASP.NET 4.x](https://docs.microsoft.com/ja-jp/aspnet/identity/overview/getting-started/adding-aspnet-identity-to-an-empty-or-existing-web-forms-project)
* [ASP.NET Identity入門連載一覧：CodeZine（コードジン）](https://codezine.jp/article/corner/511)
* [ASP.NET Identityカスタマイズに挑戦](https://blog.okazuki.jp/entry/2013/11/10/190811)
* [ASP.NET Identityで独自データストアからデータを取得する（ログインからロールまで）](https://blog.okazuki.jp/entry/2015/08/20/214212)

## ASP.NETMVC

* [ASP.NET MVC のコントローラにて SSL 接続を要求する方法](https://aspnet.keicode.com/basic/aspnet-mvc101-ssl.php)
* [ASP.NET チュートリアル  Microsoft Docs](https://docs.microsoft.com/ja-jp/aspnet/tutorials)
* [C# で Single Page Web Application が書ける Blazor が凄かった件 - Qiita](https://qiita.com/jsakamoto/items/20d4893f6c8cdb0356f6)
* [ASP.NET MVC 入門 (3) 編集 (Edit) ビューと POST データの受け取り方法](https://aspnet.keicode.com/basic/aspnet-mvc101-view.php)
* [ASP.NET MVC5で最初にやったこと2014冬のメモ](https://blog.beachside.dev/entry/2015/02/06/220929)
* [asp.net MVCとjQueryでファイルアップロードするメモ](https://blog.regrex.jp/2016/06/03/post-498/)
* [ASP.NET MVC でアップロードされたファイルを検証する](https://blog.shibayan.jp/entry/20110105/1294155788)
* [ASP.NET MVC 3 開発入門 (10) - 動画アップロードの実装](https://blog.shibayan.jp/entry/20110301/1298987419)
* [ASP.NET MVC 3 開発入門 (16) - HTML ヘルパーを活用](https://blog.shibayan.jp/entry/20110327/1301152413)
* [ASP.NET のセキュリティ対策について考える](https://blog.shibayan.jp/entry/20120526/1338001863)
* [ASP.NET MVC でドロップダウンリスト周りを良い感じに扱う](https://blog.shibayan.jp/entry/20130201/1359725910)
* [ASP.NET MVC 4 で理想的なスマートフォン対応サイトを作成する方法](https://blog.shibayan.jp/entry/20130624/1372085770)
* [ASP.NET MVC で1画面にボタンが2つあるときの処理](https://blogonos.wordpress.com/2011/07/06/asp-net-mvc-%E3%81%A71%E7%94%BB%E9%9D%A2%E3%81%AB%E3%83%9C%E3%82%BF%E3%83%B3%E3%81%8C2%E3%81%A4%E3%81%82%E3%82%8B%E3%81%A8%E3%81%8D%E3%81%AE%E5%87%A6%E7%90%86/)

## .NETCore

* [ASP.NET Core、最小限の API、.NET 6 を使用して Web アプリとサービスを作成する - Learn  Microsoft Docs](https://docs.microsoft.com/ja-jp/learn/paths/aspnet-core-minimal-api/)
* [.NET Core での自己完結型アプリのデプロイにおけるランタイムのロール フォワード - .NET Core  Microsoft Docs](https://docs.microsoft.com/ja-jp/dotnet/core/deploying/runtime-patch-selection)
* [.NET Core で使用できない .NET Framework テクノロジ  Microsoft Docs](https://docs.microsoft.com/ja-jp/dotnet/core/porting/net-framework-tech-unavailable)

## Docker

* [マネージドサービスで始めるKubernetes入門](https://atmarkit.itmedia.co.jp/ait/series/16804/)
* [コンテナーとは？ Kubernetesとは？ 導入や運用、ユースケースを解説](https://codezine.jp/article/detail/11336)
* [「Visual Studio Code」で「WSL 2」上のリモートコンテナを使用するには、Microsoftが解説：Windows 10でDocker Desktop Stableを効果的に活用する - ＠IT](https://www.atmarkit.co.jp/ait/articles/2007/10/news138.html)
* [モダンな帳票アプリを作る前に知っておきたい、Docker＋.NET開発の基本](https://codezine.jp/article/detail/15506)
* [Windows 10 Homeでも使えて、インストールも超簡単な「Docker Desktop for Windows」登場 (1/2)：Windows 10 The Latest - ＠IT](https://www.atmarkit.co.jp/ait/articles/2011/20/news015.html)
* [【連載】WSL2、Visual Studio Code、DockerでグッとよくなるWindows開発環境 〜 その1：まずは概要 〜  SIOS Tech. Lab](https://tech-lab.sios.jp/archives/21023)
* [Docker と Kubernetes でアプリをコンテナーに入れる](https://azure.microsoft.com/ja-jp/resources/containerize-your-apps-with-docker-and-kubernetes/)
* [Docker と Kubernetes を使ったコンテナのデプロイ、スケーリング、オーケストレーション](https://azure.microsoft.com/mediahandler/files/resourcefiles/containerize-your-apps-with-docker-and-kubernetes/ja-jp/JA-JP-Containerize_your_Apps_with_Docker_and_Kubernetes.pdf)
* [AzureAD ログインと Docker for Windows Shared Drive によるボリュームマウント - tech.guitarrapc.com](https://tech.guitarrapc.com/entry/2017/12/27/042458)
* [Installing docker on azure virtual machine windows 10 - Stack Overflow](https://stackoverflow.com/questions/44817161/installing-docker-on-azure-virtual-machine-windows-10)
* [【連載】世界一わかりみが深いコンテナ & Docker入門 〜 その1:コンテナってなに？ 〜  SIOS Tech. Lab](https://tech-lab.sios.jp/archives/18811)
* [第3回　Dockerコマンドの使い方：超入門Docker - ＠IT](https://www.atmarkit.co.jp/ait/articles/1702/01/news061.html)
* [ゼロからはじめるDocker(1) Dockerとは？  マイナビニュース](https://news.mynavi.jp/article/docker-1/)
* [Docker for Windows & Web Apps for Containers 実践活用技法](https://docs.microsoft.com/ja-jp/archive/blogs/nakama/dockerandazure)
* [Docker入門（第一回）～Dockerとは何か、何が良いのか～](https://knowledge.sakura.ad.jp/13265/)

## WSL

* [【WSL入門】第1回　Windows 10標準Linux環境WSLを始めよう：ITの教室 - ＠IT](https://www.atmarkit.co.jp/ait/articles/1903/18/news031.html)
* [「Windows×OpenSSH×WSL 2＝ほぼほぼネイティブなLinux」に見えてしまう、の作り方](https://www.atmarkit.co.jp/ait/articles/2007/15/news005.html)
* [WSL2をインストールしてWindowsでUbuntuを使う方法](https://tombomemo.com/wsl2-install-settings/)
* [Windows WSL2 WSL2でDocker開発環境を構築してみる - NicoNico Pun](https://blog.nicopun.com/post/2019-07-02-windows-wsl2/)

## VisualStudioCode

* [「Edge」の開発ツールを統合し「Visual Studio Code」でWebアプリの開発を完結 - 窓の杜](https://forest.watch.impress.co.jp/docs/news/1280989.html)
* [「VS Code」を「Edge」の開発者ツールに接続する拡張機能 ～Microsoftが無償公開](https://forest.watch.impress.co.jp/docs/news/1193948.html)
* [「VS Code」内から「Microsoft Edge」の開発者ツールが利用可能に：開発者ツールの「要素」と「ネットワーク」に対応 - ＠IT](https://www.atmarkit.co.jp/ait/articles/2010/16/news112.html)
* [2019年時点で僕のVSCodeに入ってるプラグインや設定を紹介します - Shibajuku](https://shibajuku.net/vscode-plugin-settings/)
* [2020年最新版 VSCodeのおすすめ拡張機能まとめ](https://homupedia.com/editor-vscode-extentions.html)
* [RESTサービスを触る際の必須ツールPostmanを使ってみました  エクセルソフト ブログ](https://www.xlsoft.com/jp/blog/blog/2017/06/23/post-1638/)
* [Visual Studio Code おすすめ拡張機能](https://web-guided.com/594/)
* [Visual Studio Code で Git を 使う](https://azriton.github.io/2017/08/23/Visual-Studio-Code%E3%81%A7Git%E3%82%92%E4%BD%BF%E3%81%86/)
* [Visual Studio Code ユーザースニペットの使い方まとめ](https://web-guided.com/620/)
* [Visual Studio Code 入門～オススメ設定と拡張機能編～](https://necojackarc.hatenablog.com/entry/2017/03/16/090000)
* [Visual Studio CodeでGitHubの複数アカウントを使い分ける - Qiita](https://qiita.com/ykoizumi0903/items/44e24d4180ae931552ce)
* [Visual Studio CodeでGitHubリポジトリを「読む」のに便利な拡張機能が登場 - 窓の杜](https://forest.watch.impress.co.jp/docs/news/1331439.html)
* [Visual Studio CodeでGitを利用する (1/3)](https://www.atmarkit.co.jp/ait/articles/1507/21/news017.html)
* [Visual Studio Codeをインストール後に最初に設定したいこと](https://web-guided.com/567/)
* [VS Code Conference Japanハンズオントラック - connpass](https://vscode.connpass.com/event/192720/)
* [VS Code（Visual Studio Code）エディタを便利に使うための拡張機能](https://karaage.hatenadiary.jp/entry/2018/10/01/073000)
* [VS Codeの見やすいテーマが登場！GitHubのデザインでコードも快適に -GitHub VS Code theme  コリス](https://coliss.com/articles/build-websites/operation/work/github-vscode-theme.html)
* [VS Code上でHTTPリクエストを送信し、VS Code上でレスポンスを確認できる「REST Client」拡張の紹介](https://qiita.com/toshi0607/items/c4440d3fbfa72eac840c)
* [VSCodeでのGitの基本操作まとめ - Qiita](https://qiita.com/y-tsutsu/items/2ba96b16b220fb5913be)
* [VSCodeのFindで今マッチしている場所にボーダーを引いて見やすくする](https://blog.shibayu36.org/entry/2020/10/12/180000)
* [VSCodeのオススメ拡張機能 24 選 (とTipsをいくつか) - Qiita](https://qiita.com/sensuikan1973/items/74cf5383c02dbcd82234)
* [コードを書くのが楽になる！知っておくと便利なVS Codeの機能・設定のまとめ  コリス](https://coliss.com/articles/build-websites/operation/work/vs-code-dont-need-extensions.html)
* [チュートリアル:Visual Studio Code 拡張機能を設定する - Azure Machine Learning  Microsoft Docs](https://docs.microsoft.com/ja-jp/azure/machine-learning/tutorial-setup-vscode-extension)
* [続：Postman 使ってたけど VSCode の REST Client に乗り換えた - かずきのBlog@hatena](https://blog.okazuki.jp/entry/2019/07/14/104313)

## VisualStudio

* [Visual Studio 2019 で使っている拡張機能 - tech.guitarrapc.com](https://tech.guitarrapc.com/entry/2019/03/18/010348)
* [Visual Studio 2019と拡張機能 : 情報系男子の備忘録](http://blog.livedoor.jp/robot_c/archives/17989990.html)
* [【Visual Studio】括弧に色を付ける拡張機能「Viasfora」 - コガネブログ](https://baba-s.hatenablog.com/entry/2016/07/12/100000)
* [【Visual Studio】オススメの拡張機能 その1（35個）](https://baba-s.hatenablog.com/entry/2016/06/29/100000)
* [【Visual Studio】オススメの拡張機能 その2（16個） - コガネブログ](https://baba-s.hatenablog.com/entry/2017/10/03/100000)
* [Visual Studio 2019 の新機能  Microsoft Docs](https://docs.microsoft.com/ja-jp/visualstudio/ide/whats-new-visual-studio-2019?view=vs-2019)
* [Microsoft、「Visual Studio Container Tools」拡張機能をプレビュー公開 - 窓の杜](https://forest.watch.impress.co.jp/docs/news/1185382.html)
* [Visual Studio 2019 で入れてる基本的な 拡張機能 - BEACHSIDE BLOG](https://blog.beachside.dev/entry/2019/04/08/204500)
* [【Visual Studio 2017】オススメの拡張機能 その1（16個）](https://baba-s.hatenablog.com/entry/2017/10/04/100000)
* [【Visual Studio 2017】オススメの拡張機能 その2（25個）](https://baba-s.hatenablog.com/entry/2017/12/25/000000)
* [GitHub - CenterCLR/ozcodejapantour: OzCode japan tour materials.](https://github.com/CenterCLR/ozcodejapantour)

## GitHubCodespaces

* [GitHub - Codespaces](https://github.co.jp/features/codespaces)

## git

* [* [Developers Festa Sapporo 2020] Microsoft/GitHubが提供するDeveloper Cloud (Developer Cloud from Microsoft/GitHub)](https://satonaoki.wordpress.com/2020/12/05/devfesta-microsoft-github/)
* [Git(GitHub)おじさんに俺はなるBefore Git After Git](https://karaage.hatenadiary.jp/entry/2016/01/23/073000)
* [Git入門（VSCode Git の使い方）](https://celtislab.net/archives/20180418/git-vscode/)
* [VisualStudioCodeとgitlabを使ってバージョン管理をしてみた備忘録](https://doubleloop.tokyo/visual-studio-code/)
* [今日からはじめるGitHub ? 初心者がGitをインストールして、プルリクできるようになるまでを解説 - エンジニアHub若手Webエンジニアのキャリアを考える！](https://employment.en-japan.com/engineerhub/entry/2017/01/31/110000)
* [GitをWindowsで使うためのGit for Windowsのインストールと初期設定](https://haniwaman.com/git-for-windows/)
* [いまさらだけどGitを基本から分かりやすくまとめてみた - Qiita](https://qiita.com/gold-kou/items/7f6a3b46e2781b0dd4a0)
* [Gitのコミットメッセージの書き方 - Qiita](https://qiita.com/itosho/items/9565c6ad2ffc24c09364)
* [Gitハンズオン研修 / Git Hands-on - Speaker Deck](https://speakerdeck.com/brainpadpr/git-hands-on)
* [VSCodeにGithub純正のプルリクエスト拡張が来た！](https://tech.actindi.net/2018/09/11/083655)
* [“はじめのGit”――超基本的な作業フローと5つのコマンド (1/3)](https://www.atmarkit.co.jp/ait/articles/1604/26/news019.html)
* [ポインタ嫌いでも分かるGitブランチの基本――作成、確認、切り替え、masterにマージ、削除 (1/3)](https://www.atmarkit.co.jp/ait/articles/1606/10/news022.html)
* [初めてのGitHub](https://xtech.nikkei.com/atcl/nxt/column/18/00528/)
* [サル先生のGit入門【プロジェクト管理ツールBacklog】](https://backlog.com/ja/git-tutorial/)

## Python

* [Python学習 (パイソン)  企業IT](https://news.mynavi.jp/top/business/enterprise/python_engineer/)
* [無料で読める、東大／京大の「Python教科書」電子書籍：AI・機械学習の無料電子書籍 - ＠IT](https://atmarkit.itmedia.co.jp/ait/articles/2105/26/news025.html)

# Site

## Microsoft

* [Microsoft AI ＆ Innovation Center](https://www.microsoft.com/ja-jp/maic)
* [Microsoft Learn  Microsoft Docs](https://docs.microsoft.com/ja-jp/learn/)
* [Microsoft Azure](https://docs.microsoft.com/ja-jp/learn/azure/)
* [Home - Power Platform Community](https://powerusers.microsoft.com/)
* [コード サンプルを参照  Microsoft Docs](https://docs.microsoft.com/ja-jp/samples/browse/?products=azure)
* [Power Apps Community Plan](https://powerapps.microsoft.com/ja-jp/communityplan/)
* [Microsoft Japan Code Labs](https://microsoft.github.io/code-labs-jp/)
* [Microsoft の認定資格](https://docs.microsoft.com/ja-jp/learn/certifications/)
* [Windows 10 で開発環境を設定する](https://docs.microsoft.com/ja-jp/windows/dev-environment/overview)
* [mstep オンライン Microsoft Azure / サーバー製品](https://partner.microsoft.com/ja-jp/training/mstep-platform)
* [オンデマンドで学ぶクラウド アプリケーション開発](https://www.microsoft.com/ja-jp/biz/cloud-platform/apps-innovation-ondemand.aspx)
* [Microsoft Security Forum 2020 オンライン](https://www.microsoft.com/ja-jp/biz/security/forum-online.aspx)
* [Azure Base コンテンツ ポータル](https://www.microsoft.com/ja-jp/events/azurebase/contents/)
* [Ignite 2020](https://www.microsoft.com/ja-jp/events/top/ignite-recap-day.aspx)
* [Microsoft Partner blog](https://blogs.partner.microsoft.com/mpn/)
* [Azure のイベントとウェビナー](https://azure.microsoft.com/ja-jp/resources/events/)

## MicrosoftSupportTeamsBlog

* [日本マイクロソフト サポート情報](https://cssjpn.github.io/)
* [突然消滅したMicrosoft TechNet／MSDNブログ（日本語）の捜索](https://atmarkit.itmedia.co.jp/ait/articles/1906/04/news004.html)* [docs.microsoft.com チーム ブログ](https://docs.microsoft.com/ja-jp/teamblog/)
* [Japan Exchange & Outlook Support Blog](https://jpmessaging.github.io/blog/)
* [Japan Microsoft Endpoint Manager Support Blog](https://jpmem.github.io/blog/)
* [Japan Developer Support Internet Team Blog](https://jpdsi.github.io/blog/)
* [Tech Community](https://techcommunity.microsoft.com/t5/custom/page/page-id/Blogs)
* [Visual Studio Blog](https://devblogs.microsoft.com/visualstudio/)
* [Microsoft Japan Blog](https://news.microsoft.com/ja-jp/category/blog/)
* [Japan SCCM & WSUS Support Team](https://social.msdn.microsoft.com/Forums/ja-JP/home?forum=jpsccmwsus)
* [Microsoft Security Response Center](https://msrc-blog.microsoft.com/)
* [Exchange Team Blog - Microsoft Tech Community](https://techcommunity.microsoft.com/t5/exchange-team-blog/bg-p/Exchange)
* [Exchange_Outlookサポートチーム](https://social.msdn.microsoft.com/Forums/sqlserver/ja-JP/home?forum=exchangeteamjp)
* [Japan SharePoint Support Team](https://social.msdn.microsoft.com/Forums/ja-JP/home?forum=sharepointsupportteamja)
* [Japan Azure Identity Support Blog](https://jpazureid.github.io/blog/)

## MicrosoftSupportTeamsBlog(Archive)

* [Japan WSUS Support Team Blog](https://docs.microsoft.com/ja-jp/archive/blogs/jpwsus/)
* [Japan System Center Support Team Blog](https://docs.microsoft.com/ja-jp/archive/blogs/systemcenterjp/)
* [Cloud and Server Product Japan Blog](https://docs.microsoft.com/ja-jp/archive/blogs/mssvrpmj/)
* [Japan SharePoint Support Team Blog archive](https://docs.microsoft.com/ja-jp/archive/blogs/sharepoint_support/)
* [Japan Microsoft Intune & MDM for Office 365 Support Team Blog](https://docs.microsoft.com/ja-jp/archive/blogs/jpintune/)
* [Japan Azure Identity Support Blog](https://docs.microsoft.com/ja-jp/archive/blogs/jpazureid/)
* [Cloud Solution Architect チームブログ](https://docs.microsoft.com/ja-jp/archive/blogs/azure-sa-members/)
* [フィールドSEあがりの安納です](https://docs.microsoft.com/ja-jp/archive/blogs/junichia/)

## Microsoft Support Teams Post

* [FAQ よくある質問事項について Azure SQL Database](https://docs.microsoft.com/ja-jp/archive/blogs/jpsql/faq-%E3%82%88%E3%81%8F%E3%81%82%E3%82%8B%E8%B3%AA%E5%95%8F%E4%BA%8B%E9%A0%85%E3%81%AB%E3%81%A4%E3%81%84%E3%81%A6-azure-sql-database)
* [リスト ビューのしきい値によって発生する現象と対処策](https://docs.microsoft.com/ja-jp/archive/blogs/sharepoint_support/31574)
* [Microsoft SQL Server Japan Support Team Blog](https://docs.microsoft.com/ja-jp/archive/blogs/jpsql/?s=SQL+Troubleshooting)

## blog

* [karamem0](https://zenn.dev/karamem0)
* [deepcom](https://deepcom.co.jp/blog/)
* [idea.toString](https://idea.tostring.jp/)
* [Sharepoint Technical Note](https://shanqiai.weblogs.jp/sharepoint_technical_note)
* [SharePoint Developer](http://sharepoint.orivers.jp/)
* [くらう道](https://www.cloudou.net/)
* [しばやん雑記](https://blog.shibayan.jp/)
* [SendGrid](https://sendgrid.kke.co.jp/blog/)
* [サイオステクノロジー](https://tech-lab.sios.jp/)
* [かずきのBlog@hatena](https://blog.okazuki.jp/)
* [kkamegawa's weblog](https://kkamegawa.hatenablog.jp/)
* [cloudsteady](https://cloudsteady.jp/post/category/blog/)

## WebSite

* [ASCII × FIXER](https://ascii.jp/azure-fixer/)
* [ゼロからはじめるAzure Mynavi](https://news.mynavi.jp/techplus/series/zeroazure/)
* [ASP.NET 入門](https://aspnet.keicode.com/)
* [microsoft Web-Dev-For-Beginners](https://github.com/microsoft/Web-Dev-For-Beginners)
* [Microsoft Azure最新機能フォローアップ](https://atmarkit.itmedia.co.jp/ait/series/1845/)
* [Azure AD webinar にご参加ください](https://github.com/yusukekodama/PMActivities/blob/master/Webinar/Schedule.md)
* [AzureAD Japan](https://www.youtube.com/channel/UCVrKqrCLcB0eJu8heNB2ZKg/videos)

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

# Adobe

## Dreamweaver

* [DreamweaverとBootstrapで作るレスポンシブページ 第1回 「Jumbotronを使ったヒーローエリアのレイアウト」](https://blog.adobe.com/jp/publish/2015/08/17/web-dreamweaver-bootstrap-01-jumbotron-layout)
* [DreamweaverではじめるWebクリエイターのためのGit入門](https://blog.adobe.com/jp/publish/2017/07/27/web-dreamweaver-git-for-beginners)
* [Dreamweaver入門 第1回 サイト設定がDreamweaverのカナメです](https://blogs.adobe.com/japan/web-start-dreamweaver-getting-start-01-site-settings/)

## Adobe XD

* [社内の標準デザインツールをXDに統一した話もとやまふとし / 地方webディレクター・マーケターnote](https://note.com/futoshi/n/nc6a49d3b6a3a)
* [Adobe XDでシンプルなワイヤーフレームを作ろう！便利なUIキットいろいろ](https://www.webcreatorbox.com/webinfo/adobe-xd-wireframe)
* [Adobe XDでWebデザインをしよう！画面作成からページ推移までの手順を紹介  Webクリエイターボックス](https://www.webcreatorbox.com/inspiration/adobe-xd-steps)
* [Adobe XD 2020年10月の新機能！ついにVisual Studio Codeと連携可能に  コリス](https://coliss.com/articles/build-websites/operation/work/adobe-xd-whats-new-2020-oct.html)
* [Adobe XDをHTMLにエクスポートする方法 - インターネットとソーシャル  七月 2020](https://ja.rockycode.com/how-export-adobe-xd-html)
* [Adobe XDの新機能『CSS書き出し』を使ってみよう  studioDoghands](https://www.doghands.com/adobe-xd-css-code-snippets/)
* [Adobe XD 2019年8月アップデートリリース！CSSコード自動生成（第一弾）、ローカルでのPhotoshop編集連携、コンポーネントの操作性改善など #AdobeXD  Adobe Blog](https://blogs.adobe.com/japan/cc-web-xd-august-2019-update-auto-css-plugins-panel-more/)
* [まだAdobe XD使ってないの？はじめての人もこれを読めばすぐに使えるAdobe XDのトリセツ  東京のWeb制作会社LIG](http://liginc.co.jp/467917)
* [Adobe XDとBootstrapで作業を効率化 第1回: 中小規模のサイトに有効なデザインシステムLiteとは アドビUX道場 #UXDojo](https://blog.adobe.com/jp/publish/2019/12/18/adobe-xd-bootstrap-designsytem-lite)
* [Adobe XDの基本的な使い方を解説！専門知識不要でUI・UXデザインが簡単に！ferret](https://ferret-plus.com/13236)
* [VS CodeのAdobe XD用拡張機能が登場！デザインシステムにもとづきコード出力と補完が可能に](https://ics.media/entry/210107/)
* [Adobe XDのデザインを「Flutter」のコードに変換するプラグインが一般公開 - 窓の杜](https://forest.watch.impress.co.jp/docs/news/1279609.html)


# Security

* [AWS環境の公開サーバに対する セキュリティ検討ガイド  トレンドマイクロ](https://resources.trendmicro.com/jp-docdownload-form-m294-social-2020-awssecurityreport.html)
* [実際の標的型攻撃の事例を基にした「インシデント対応ハンズオン」コンテンツをJPCERT／CCが公開：標的型攻撃を受けたときのWindowsログ調査方法を学べる - ＠IT](https://www.atmarkit.co.jp/ait/articles/2007/30/news025.html)
* [JPCERT／CCがイベントログ分析支援ツール「LogonTracer v1.5.0」を公開](https://www.atmarkit.co.jp/ait/articles/2011/04/news028.html)
* [オンボーディング支援プログラム - Mackerel（マカレル）: 新世代のサーバー管理・監視サービス](https://mackerel.io/ja/services-support/onboarding/)

# MISC

* [会話の公理（ポール・グライス） ? *ListFreak](https://listfreak.com/list/1301)
* [糖尿病予備群たちに告ぐ！ 今やるべき対処法5つ  Tarzan Web（ターザンウェブ）](https://tarzanweb.jp/post-210390)
* [「旧街道サイクリングの旅」サイクルスポーツ.jpにて好評連載中！［最終回 更新！］](https://www.strada.jp/events/kyukaidou_201908/)
