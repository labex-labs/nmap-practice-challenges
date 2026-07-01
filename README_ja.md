# Nmap 実践チャレンジ

## 言語

🇨🇳 [简体中文](README_zh.md) 🇯🇵 [日本語](README_ja.md) 🇪🇸 [Español](README_es.md) 🇷🇺 [Русский](README_ru.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 🇺🇸 [English](README.md) 

<div align="center">
<img width="128px" src="https://file.labex.io/upload/u/1991/1aTkiz91H4KB.png">
</div>

ネットワーク探索とセキュリティ監査のための強力なオープンソースツールである Nmap を学びましょう。この学習パスは、サイバーセキュリティ初心者向けに設計された包括的な Nmap コースを提供します。ネットワークスキャン、ポート探索、脆弱性評価を習得するための体系的なロードマップに従います。実践的な非ビデオチュートリアルと、専用のネットワークスキャンプレイグラウンドでのハンズオン演習を通じて、Nmap を使用してネットワークをマッピングし、セキュリティリスクを特定する実世界の経験を積むことができます。

LabEx の最大 29 個の Nmap 集中チャレンジを一覧できます。各チャレンジはインタラクティブ環境で開き、特定のスキルを練習できます。

|   インデックス | 名前                                                                                                       | スキル           | 難易度   | 練習                                                                                         |
|----------|----------------------------------------------------------------------------------------------------------|---------------|-------|--------------------------------------------------------------------------------------------|
|       01 | [Rsync の列挙とアノニマス同期](https://labex.io/ja/labs/linux-rsync-enumeration-and-anonymous-sync-596723)          | 攻撃対象領域        | 上級    | [チャレンジを開始](https://labex.io/ja/labs/linux-rsync-enumeration-and-anonymous-sync-596723)     |
|       02 | [不確実なサービス検出結果のレビュー](https://labex.io/ja/labs/review-uncertain-service-findings-705352)                   | 誤検知レビュー       | 初級    | [チャレンジを開始](https://labex.io/ja/labs/review-uncertain-service-findings-705352)              |
|       03 | [NSE スクリプトの必須引数を渡す](https://labex.io/ja/labs/pass-required-nse-script-arguments-705351)                  | スクリプトの引数      | 初級    | [チャレンジを開始](https://labex.io/ja/labs/pass-required-nse-script-arguments-705351)             |
|       04 | [Nmap スキャン結果の新旧比較](https://labex.io/ja/labs/compare-before-and-after-nmap-results-705350)                | 結果の比較         | 初級    | [チャレンジを開始](https://labex.io/ja/labs/compare-before-and-after-nmap-results-705350)          |
|       05 | [Metasploit を活用した初期アクセス](https://labex.io/ja/labs/metasploit-driven-initial-access-657543)               | 出力リダイレクト      | 上級    | [チャレンジを開始](https://labex.io/ja/labs/metasploit-driven-initial-access-657543)               |
|       06 | [脆弱性の優先順位付けレビュー](https://labex.io/ja/labs/vulnerability-prioritization-review-657539)                    | 脆弱性管理         | 中級    | [チャレンジを開始](https://labex.io/ja/labs/vulnerability-prioritization-review-657539)            |
|       07 | [エンタープライズネットワークのマッピング](https://labex.io/ja/labs/enterprise-network-mapping-657537)                       | ターゲット仕様       | 中級    | [チャレンジを開始](https://labex.io/ja/labs/enterprise-network-mapping-657537)                     |
|       08 | [内部ネットワーク侵入チャレンジ](https://labex.io/ja/labs/linux-internal-network-breach-challenge-656176)               | ネットワークセキュリティ  | 中級    | [チャレンジを開始](https://labex.io/ja/labs/linux-internal-network-breach-challenge-656176)        |
|       09 | [First Blood Compromise](https://labex.io/ja/labs/linux-first-blood-compromise-656167)                   | 攻撃対象領域        | 中級    | [チャレンジを開始](https://labex.io/ja/labs/linux-first-blood-compromise-656167)                   |
|       10 | [ターゲット列挙チャレンジ](https://labex.io/ja/labs/linux-target-enumeration-challenge-656139)                       | 出力リダイレクト      | 中級    | [チャレンジを開始](https://labex.io/ja/labs/linux-target-enumeration-challenge-656139)             |
|       11 | [ネットワークマッピング・チャレンジ](https://labex.io/ja/labs/linux-network-mapping-challenge-656134)                     | ターゲット仕様       | 中級    | [チャレンジを開始](https://labex.io/ja/labs/linux-network-mapping-challenge-656134)                |
|       12 | [パッシブ・リコネサンス（受動的偵察）ミッション](https://labex.io/ja/labs/linux-passive-reconnaissance-mission-656130)          | 出力リダイレクト      | 中級    | [チャレンジを開始](https://labex.io/ja/labs/linux-passive-reconnaissance-mission-656130)           |
|       13 | [Telnet ブルートフォースと脆弱な認証情報](https://labex.io/ja/labs/linux-telnet-brute-force-and-weak-credentials-596726) | 攻撃対象領域        | 上級    | [チャレンジを開始](https://labex.io/ja/labs/linux-telnet-brute-force-and-weak-credentials-596726)  |
|       14 | [SSH の列挙と鍵認証によるアクセス](https://labex.io/ja/labs/linux-ssh-enumeration-and-key-based-access-596725)         | 攻撃対象領域        | 上級    | [チャレンジを開始](https://labex.io/ja/labs/linux-ssh-enumeration-and-key-based-access-596725)     |
|       15 | [SMB の列挙とゲストアクセス](https://labex.io/ja/labs/linux-smb-enumeration-and-guest-access-596724)                | 攻撃対象領域        | 上級    | [チャレンジを開始](https://labex.io/ja/labs/linux-smb-enumeration-and-guest-access-596724)         |
|       16 | [Nmap のインストールとポートスキャンの実行](https://labex.io/ja/labs/nmap-install-nmap-and-perform-port-scanning-415923)   | パッケージのライフサイクル | 中級    | [チャレンジを開始](https://labex.io/ja/labs/nmap-install-nmap-and-perform-port-scanning-415923)    |
|       17 | [RDP 列挙と脆弱なパスワードによるアクセス](https://labex.io/ja/labs/linux-rdp-enumeration-and-weak-password-access-596722) | 攻撃対象領域        | 上級    | [チャレンジを開始](https://labex.io/ja/labs/linux-rdp-enumeration-and-weak-password-access-596722) |
|       18 | [HTTP 列挙とディレクトリトラバーサル](https://labex.io/ja/labs/linux-http-enumeration-and-directory-traversal-596721)   | 攻撃対象領域        | 上級    | [チャレンジを開始](https://labex.io/ja/labs/linux-http-enumeration-and-directory-traversal-596721) |
|       19 | [FTP の列挙とアノニマスアクセスの試行](https://labex.io/ja/labs/linux-ftp-enumeration-and-anonymous-access-596695)       | 攻撃対象領域        | 上級    | [チャレンジを開始](https://labex.io/ja/labs/linux-ftp-enumeration-and-anonymous-access-596695)     |
|       20 | [Nmap スキャンと Telnet アクセス](https://labex.io/ja/labs/nmap-nmap-scanning-and-telnet-access-596683)           | 攻撃対象領域        | 上級    | [チャレンジを開始](https://labex.io/ja/labs/nmap-nmap-scanning-and-telnet-access-596683)           |
|       21 | [Nmap を使用したネットワークポートのスキャン](https://labex.io/ja/labs/kali-scan-network-ports-with-nmap-552280)            | ターゲット仕様       | 中級    | [チャレンジを開始](https://labex.io/ja/labs/kali-scan-network-ports-with-nmap-552280)              |
|       22 | [Linux サーバーのバージョン特定](https://labex.io/ja/labs/nmap-identify-linux-server-version-548747)                 | OS 検出         | 初級    | [チャレンジを開始](https://labex.io/ja/labs/nmap-identify-linux-server-version-548747)             |
|       23 | [オープン UDP ポートの特定](https://labex.io/ja/labs/nmap-find-open-udp-port-548746)                               | UDP スキャン      | 初級    | [チャレンジを開始](https://labex.io/ja/labs/nmap-find-open-udp-port-548746)                        |
|       24 | [隠されたポートを特定せよ](https://labex.io/ja/labs/nmap-uncover-the-secret-port-548724)                             | テキスト出力        | 初級    | [チャレンジを開始](https://labex.io/ja/labs/nmap-uncover-the-secret-port-548724)                   |
|       25 | [ファイルからのターゲットスキャン](https://labex.io/ja/labs/nmap-scan-target-from-file-548715)                           | ターゲット仕様       | 中級    | [チャレンジを開始](https://labex.io/ja/labs/nmap-scan-target-from-file-548715)                     |
|       26 | [Nmapの出力をXML形式で保存する](https://labex.io/ja/labs/nmap-save-nmap-output-to-xml-548705)                       | 構造化された出力      | 中級    | [チャレンジを開始](https://labex.io/ja/labs/nmap-save-nmap-output-to-xml-548705)                   |
|       27 | [Luna サーバーのオープンポートの特定](https://labex.io/ja/labs/nmap-find-open-port-on-luna-server-548697)               | ポートの選択        | 中級    | [チャレンジを開始](https://labex.io/ja/labs/nmap-find-open-port-on-luna-server-548697)             |
|       28 | [ローカル環境でのサービスバージョンの検証](https://labex.io/ja/labs/nmap-verify-service-version-locally-548693)              | OS 検出         | 初級    | [チャレンジを開始](https://labex.io/ja/labs/nmap-verify-service-version-locally-548693)            |
|       29 | [Nmap を使用したサブネットスキャン](https://labex.io/ja/labs/nmap-scanning-subnet-with-nmap-415954)                    | ターゲット仕様       | 初級    | [チャレンジを開始](https://labex.io/ja/labs/nmap-scanning-subnet-with-nmap-415954)                 |

[すべてのチャレンジを見る](https://labex.io/ja/learn/nmap).

## その他

- 🔗 [LabEx で Nmap について詳しく見る](https://labex.io/ja/learn/nmap)
- 🔗 [さらにプログラミングプロジェクトを見る](https://github.com/labex-labs/awesome-programming-projects)
- 🔗 [プログラミングコースを見る](https://github.com/labex-labs/awesome-programming-courses)

