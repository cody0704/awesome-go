
# Go 資源大全中文版

我想很多程序員應該記得 GitHub 上有一個 Awesome - XXX 系列的資源整理。本列表翻譯自[awesome-Go](https://github.com/avelino/awesome-Go)
Awesome 系列雖然挺全，但基本只對收錄的資源做了極為簡要的介紹，如果有更詳細的中文介紹，對相應開發者的幫助會更大。這也是我們發起這個開源項目的初衷。

### 如何為列表貢獻新資源？

歡迎大家為列表貢獻高質量的新資源，提交 PR 時請參照以下要求：

* 請確保推薦的資源自己使用過
* 提交 PR 時請註明推薦理由

資源列表管理收到 PR 請求後，會定期（每週）在微博轉發本週提交的 PR 列表，並在微博上面聽取使用過這些資源的意見。確認通過後，會加入資源大全。

感謝您的貢獻！

本項目的參與者
維護者：tangyouhua

貢獻者：[艾凌風](https://github.com/hanxiaomax)

註：名單不分排名，不定期補充更新

### 參與

煩請諸位參與前看一眼[參與指南](https://github.com/avelino/awesome-Go/blob/master/CONTRIBUTING.md) 。感謝各位貢獻者，你們是最棒的！ [contributors](https://github.com/avelino/awesome-Go/graphs/contributors)

#### _如果你發現某個項目已經不維護了，或者它並不好，請發起一個 pull request 來幫助我們改善此列表。感謝。_

##資源列表

## 音頻和音樂

_用於操作音頻的庫_

* [flac](https://github.com/eaburns/flac) - 原生 Go FLAC 解碼器
* [flac](https://github.com/mewkiz/flac) - 原生 Go FLAC 解碼器
* [gaad](https://github.com/Comcast/gaad) - 原生 Go AAC 比特流解析器
* [Go-sox](https://github.com/krig/Go-sox) - libsox 的 Go 語言接口
* [Go_mediainfo](https://github.com/zhulik/Go_mediainfo) - libmediainfo 的 Go 語言接口
* [Gosamplerate](https://github.com/dh1tw/Gosamplerate) - libsamplerate 的 Go 語言接口
* [id3v2](https://github.com/bogem/id3v2) - 快速且穩定的 ID3 解析及寫入庫
* [mix](https://github.com/Go-mix/mix) - 基於序列的 Go 語言混音器，可用於音樂 app。
* [mp3](https://github.com/tcolgate/mp3) - 原生 Go MP3 解碼器
* [music-theory](https://github.com/Go-music-theory/music-theory) - Go 語言編寫的音樂理論模型
* [PortAudio](https://github.com/Gordonklaus/portaudio) - 音頻 I/O 庫的 Go 語言接口
* [portmidi](https://github.com/rakyll/portmidi) - PortMidi 的 Go 語言接口
* [taglib](https://github.com/wtolson/Go-taglib) - taglib 的 Go 語言接口
* [vorbis](https://github.com/mccoyst/vorbis) - "原生" Go Vorbis 解碼器 (使用 CGo, 但是沒有其他依賴).
* [waveform](https://github.com/mdlayher/waveform) - 一個可以通過音頻流生成波形圖象的包

## 認證和授權

_用來生成認證授權模板的庫_

* [authboss](https://github.com/volatiletech/authboss) - 用於 web 開發的組件化認證授權系統。它嘗試儘可能的移除模板代碼以及硬編碼，這使你每次新建 web 項目的時候，可以做到即插即用、配置並開始開發你的 web 英語，而不必每次都重新創建一個認證授權系統。
* [casbin](https://github.com/hsluoyz/casbin) - 一個支持接入控制模型（例如:ACL,RBAC,ABAC）的授權庫
* [Go-AWS-Auth](https://github.com/smartystreets/Go-aws-auth) - AWS 請求籤名庫
* [Go-jose](https://github.com/square/Go-jose) - Fairly complete implementation of the JOSE working group's JSON Web Token, JSON Web 簽名以及JSON Web 加密 specs.
* [Go-oauth2-server](https://github.com/RichardKnop/Go-oauth2-server) - 使用 Go 語言編寫的獨立、符合標準的 OAuth2 服務器
* [Go.auth](https://github.com/bradrydzewski/Go.auth) - 為 Go 語言 web 應用提供的授權 API.
* [Gologin](https://github.com/dghubble/Gologin) - 可以串連使用OAuth1 和 OAuth2 認證服務
* [Gorbac](https://github.com/mikespook/Gorbac) - 一個用 Go 語言實現的輕量級RBAC
* [Goth](https://github.com/markbates/Goth) - 提供了一種簡潔的、慣用的方式來使用OAuth 和 OAuth2.
* [httpauth](https://github.com/Goji/httpauth) - HTTP 認證中間件
* [jwt](https://github.com/robbert229/jwt) - 簡單易用的一個JSON Web Tokens (JWT)的實現
* [jwt-auth](https://github.com/adam-hanna/jwt-auth) - JWT 為 Go 語言 HTTP 服務器編寫的 jwt 中間件，有多種配置選項
* [jwt-Go](https://github.com/dgrijalva/jwt-Go) - Go 語言實現的JSON Web Tokens (JWT).
* [loginsrv](https://github.com/tarent/loginsrv) - JWT 登錄微服務，可以繼承OAuth2 (Github), htpasswd, osiam等後端。
* [oauth2](https://github.com/Golang/oauth2) - Goauth2的繼承者。 通用 OAuth 2.0 庫，整合了對JWT, Google APIs, Compute Engine 和 App Engine的支持.
* [osin](https://github.com/RangelReale/osin) - Go 語言 OAuth2 服務器庫
* [permissions2](https://github.com/xyproto/permissions2) - 用於追蹤用戶，登錄狀態和許可的庫。使用安全 cookies 和 bcrypt.
* [session](https://github.com/icza/session) - Go 語言會話管理(支持 Google App Engine - GAE)
* [sessions](https://github.com/adam-hanna/sessions) - 為 Go 語言 HTTP 服務器開發的非常簡單的、高性能的、高可定製的會話服務
* [traefik](https://github.com/containous/traefik) - 反向代理和負載均衡庫，支持多種後端
* [yubiGo](https://github.com/GeertJohan/yubiGo) - Yubikey 客戶端，提供了用於在 Go 語言應用中整合Yubico Yubikey 的 API

## 命令行

### 標準命令行交互

_用於構建標準或基礎命令行應用的庫_

* [argv](https://github.com/cosiner/argv) - 用於分隔命令行字元串並將其作為參數的 Go 語言庫，使用 bash 的語法
* [cli](https://github.com/mkideal/cli) - 功能強大，使用簡單的命令行軟件包，基於Golang tag
* [cli-init](https://github.com/tcnksm/gcli) - 提供一種簡單、易上手的方式 來使用 Go 語言編寫命令行程序
* [climax](http://github.com/tucnak/climax) - 一個更為人性化的命令行工具，繼承了 Go command 的精神
* [cobra](https://github.com/spf13/cobra) - 用於現代 Go 語言命令行交互的工具
* [complete](https://github.com/posener/complete) - 使用 Go 語言編寫的 bash 命令補全工具以及 Go 命令補全工具
* [docopt.Go](https://github.com/docopt/docopt.Go) - 能令你會心一笑的命令行參數解析器
* [drive](https://github.com/odeke-em/drive) - 命令行的 Google Drive 客戶端
* [flag](https://github.com/cosiner/flag) - 簡單、強大的命令行選項解析庫，支持 Go 語言子命令
* [Go-arg](https://github.com/alexflint/Go-arg) - 使用 Go 語言編寫的基於結構的命令行參數解析庫
* [Go-flags](https://github.com/jessevdk/Go-flags) - Go 語言命令行選項解析器
* [kingpin](https://github.com/alecthomas/kingpin) - 命令行及標記解析器，支持子命令
* [liner](https://github.com/peterh/liner) - 命令行文本編輯器
* [mitchellh/cli](https://github.com/mitchellh/cli) - 用於實現命令行交互的 Go 語言庫
* [mow.cli](https://github.com/jawher/mow.cli) - 用於構建命令行程序的庫，支持更加精準的標記及選項解析和驗證
* [pflag](https://github.com/spf13/pflag) - Go flag 軟件包的替代品, 實現了POSIX/GNU-風格的 --flags.
* [readline](https://github.com/chzyer/readline) - 純 Go 語言實現的 GNU-Readline 支持其大部分功能，基於MIT 協議發佈。
* [sflags](https://github.com/octaGo/sflags) - 基於結構的 flag 生成器，支持flag, urfave/cli, pflag, cobra, kingpin等其他庫
* [ukautz/clif](https://github.com/ukautz/clif) - 一個小型命令行程序開發框架
* [urfave/cli](https://github.com/urfave/cli) - 簡單、快速、有趣的、用於構建 Go 語言命令行程序的軟件包(formerly codegangsta/cli).
* [wlog](https://github.com/dixonwille/wlog) - 簡單的登錄接口，支持跨平台顏色和並發
* [wmenu](https://github.com/dixonwille/wmenu) - 為命令行程序提供簡單的菜單結構選項，供用戶進行選擇

### 高級控制台界面

_用於構建命令行程序以及控制台界面的庫_

* [aurora](https://github.com/logrusorgru/aurora) - ANSI 終端顏色，支持 fmt.Printf/Sprintf
* [chalk](https://github.com/ttacon/chalk) - 符合直覺的用於美化命令行輸出的庫
* [color](https://github.com/fatih/color) - 多功能的用於彩色化命令行輸出的庫
* [colourize](https://github.com/TreyBastian/colourize) - 用於實現 ANSI 彩色文本的 Go 語言庫
* [Go-ataman](https://github.com/workanator/Go-ataman) - 用於渲染 ANSI 彩色文本模板的庫
* [Go-colorable](https://github.com/mattn/Go-colorable) - Windows 上使用的可以輸出彩色文本的庫
* [Go-colortext](https://github.com/daviddengcn/Go-colortext) - 用於在終端進行多彩文字輸出的庫
* [Go-isatty](https://github.com/mattn/Go-isatty) - Go 語言使用的 isatty
* [Gocui](https://github.com/jroimartin/Gocui) - 一個用於構建控制台界面的極簡的 Go 語言庫
* [Gommon/color](https://github.com/labstack/Gommon/tree/master/color) - 多樣的命令行文本
* [mpb](https://github.com/vbauerster/mpb) - 為命令行提供多個進度條的工具
* [termbox-Go](https://github.com/nsf/termbox-Go) - Termbox 是一個用於構建跨平台的、與文本的交互界面的庫
* [termtables](https://github.com/apcera/termtables) - Ruby 庫的 Go 語言接口
* [terminal-tables](https://github.com/tj/terminal-table) 用於生成簡單的 ASCII 表格，同時支持 markdown 和 HTML 輸出
* [termui](https://github.com/gizak/termui) - Go 終端控制面板，基於 **termbox-Go** 並受到了[blessed-contrib](https://github.com/yaronn/blessed-contrib)的啟發
* [uilive](https://github.com/Gosuri/uilive) - 用於實時更新終端輸出的庫
* [uiprogress](https://github.com/Gosuri/uiprogress) - 一個很靈活的用於渲染進度條的庫
* [uitable](https://github.com/Gosuri/uitable) - 一個用於改善命令行中表格數據可讀性的庫

## 配置

_用於進行配置解析的庫_

* [config](https://github.com/olebedev/config) - JSON 或 YAML 配置的封裝，支持環境變數和標記解析
* [configure](https://github.com/paked/configure) - 可以通過多種途徑進行配置，包括 JSON, 標記位以及環境變數
* [env](https://github.com/caarlos0/env) - 解析環境變數為 Go 語言結構體
* [envcfg](https://github.com/tomazk/envcfg) - 解析環境變數為 Go 語言結構體
* [envconf](https://github.com/ian-kent/envconf) - 通過環境變數來配置
* [envconfig](https://github.com/vrischmann/envconfig) - 通過環境變數讀取配置
* [gcfg](https://github.com/Go-gcfg/gcfg) - 讀取類 INI 類型的配置文件為 Go 語言結構體，支持自定義變數和節
* [GoConfig](https://github.com/crgimenes/GoConfig) - 通過命令行的輸入、環境變數、配置文件來初始化一個結構體兵將一個結構體解析為輸入
* [Godotenv](https://github.com/joho/Godotenv) - Ruby 庫 dotenv 的 Go 語言接口 (通過 `.env` 來獲取環境變數)
* [Gofigure](https://github.com/ian-kent/Gofigure) - 讓 Go 語言應用程序配置變得簡單
* [Gone/jconf](https://github.com/One-com/Gone/tree/master/jconf#readme) - 模組化 JSON 配置工具。允許你將配置參數結構體和使用它的代碼放在一起，而不需要讓主配置文件瞭解所有子模組的細節來進行序列化
* [hjson](https://github.com/hjson/hjson-Go) - 人性化的 JSON，一個便於程序員使用和閲讀的配置文件格式。更加輕鬆的語法，更少的錯誤和更多的註釋
* [inGo](https://github.com/schachmat/inGo) - 將配置標記持久化到一個類似 ini 的文件中
* [ini](https://github.com/Go-ini/ini) - 用於讀寫INI 文件的庫
* [joshbetz/config](https://github.com/joshbetz/config) - 消息配置庫，可以解析環境變數、JSON 文件並根據SIGHUP自動重新載入
* [mini](https://github.com/sasbury/mini) -用於解析類 ini 文件的庫
* [store](https://github.com/tucnak/store) - 輕量級配置管理
* [viper](https://github.com/spf13/viper) - 長牙的（這個庫名叫毒蛇）Go 語言配置工具
* [xdg](https://github.com/OpenPeeDeeP/xdg) -遵守 [XDG 標準](https://standards.freedesktop.org/basedir-spec/basedir-spec-latest.html) 的配置工具

## 持續整合

_幫助你進行持續整合的庫_

* [drone](https://github.com/drone/drone) - Drone 是一個基於 Docker的持續整合平台，使用 Go 語言編寫
* [Goveralls](https://github.com/mattn/Goveralls) - Coveralls.io 是一個持續代碼覆蓋率檢測系統，這個庫提供了 Go 語言的支持
* [overalls](https://github.com/Go-playground/overalls) - 針對多package 的 Go 語言項目，為 Goveralls 這樣的工具生成覆蓋率報告
* [roveralls](https://github.com/LawrenceWoodman/roveralls) - 回歸覆蓋測試工具

## CSS 預處理器

_用於對 CSS 文件預處理的工具_

* [c6](https://github.com/c9s/c6) - 高性能、兼容 SAAS 的編譯器
* [gcss](https://github.com/yosssi/gcss) - 純 Go 語言編寫的 CSS 預處理器
* [Go-libsass](https://github.com/wellington/Go-libsass) - 100%兼容 Sass 的庫 libsass 的 Go 語言封裝

## 數據結構

_通用數據結構及算法_

* [binpacker](https://github.com/zhuangsirui/binpacker) - 二進制數據封包拆包工具，幫你構建自定義的二進制數據流
* [bit](https://github.com/yourbasic/bit) - Go 語言集合數據結構。提供了額外的位操作功能
* [bitset](https://github.com/willf/bitset) - 實現了 bitset 的 Go 語言包.
* [bloom](https://github.com/zhenjl/bloom) - Go 語言實現的布隆過濾器（bloom filter）
* [bloom](https://github.com/yourbasic/bloom) - Go 語言實現的布隆過濾器
* [boomfilters](https://github.com/tylertreat/BoomFilters) - 概率統計數據結構，用於處理大量連續的數據。
* [count-min-log](https://github.com/seiflotfy/count-min-log) - Go 語言實現的 Count-Min-Log sketch 算法(類似 Count-Min sketch 算法，但是使用的內存更少).
* [cuckoofilter](https://github.com/seiflotfy/cuckoofilter) - Cuckoo 過濾器：一個用go語言實現的計數布隆過濾器的替代品
* [encoding](https://github.com/zhenjl/encoding) - 整型壓縮庫
* [Go-adaptive-radix-tree](https://github.com/plar/Go-adaptive-radix-tree) - Go 語言實現的自適應基數樹
* [Go-datastructures](https://github.com/Workiva/Go-datastructures) - 一組有用的、高性能的、線程安全的數據結構
* [Go-geoindex](https://github.com/hailocab/Go-geoindex) - 基於內存存儲的地理索引
* [Go-rquad](https://github.com/aurelien-rainone/Go-rquad) - 區域四叉樹，支持有效點位置和領域發現
* [Gods](https://github.com/emirpasic/Gods) - Go 語言數據結構、容器、集合、列表、棧、鍵值對、 BidiMaps、樹、HashSet 等
* [Golang-set](https://github.com/deckarep/Golang-set) - 線程安全和非線程安全的高性能集合
* [Goskiplist](https://github.com/ryszard/Goskiplist) - Go 語言實現的跳躍表
* [Gota](https://github.com/kniren/Gota) - 為go語言實現了數據幀，序列以及數據噪音的方法
* [hilbert](https://github.com/Google/hilbert) - 用於映射空間填充曲線（例如希爾伯特曲線和皮亞諾曲線）和數值的庫。
* [hyperloglog](https://github.com/axiomhq/hyperloglog) - HyperLogLog implementation with Sparse, LogLog-Beta bias correction and TailCut space reduction.
* [levenshtein](https://github.com/agext/levenshtein) - 編輯距離（levenshtein distance）和相似性度量， 可以自定義編輯代價和and Winkler-like bonus for common prefix.
* [levenshtein](https://github.com/agnivade/levenshtein) - Go 語言實現計算編輯距離
* [mafsa](https://github.com/smartystreets/mafsa) - Go 語言實現的 MA-FSA ，包含最小完美哈希
* [merkletree](https://github.com/cberGoon/merkletree) - 實現了梅克爾樹，提供了一種高效、安全的數據結構內容驗證方法
* [roaring](https://github.com/RoaringBitmap/roaring) - 實現了壓縮 bitsets 的Go語言庫
* [skiplist](https://github.com/gansidui/skiplist) - Go語言實現的跳躍表
* [trie](https://github.com/derekparker/trie) - Go語言實現的Trie樹
* [ttlcache](https://github.com/dieGobernardes/ttlcache) - In-memory LRU string-interface{} map with expiration for Golang
* [willf/bloom](https://github.com/willf/bloom) - 實現了布隆過濾器的庫

## 數據庫

*   Go 語言實現的數據庫*
* [BigCache](https://github.com/allegro/bigcache) - 為 gigabytes 量級數據設計的高效鍵/值緩存
* [bolt](https://github.com/boltdb/bolt) - 底層鍵值數據庫
* [buntdb](https://github.com/tidwall/buntdb) - 快速，可嵌入的，內存鍵值數據庫，可定義索引及 spatial
* [cache2Go](https://github.com/muesli/cache2Go) - 基於內存存儲的鍵值緩存，支持自動基於超時的自動失效
* [cockroach](https://github.com/cockroachdb/cockroach) - 可擴展的、一致的事務型數據庫
* [couchcache](https://github.com/codingsince1985/couchcache) - RESTful 緩存微服務，基於Couchbase
* [dgraph](https://github.com/dgraph-io/dgraph) - 可擴展的、分佈式的、低延時、高吞吐的圖數據庫
* [diskv](https://github.com/peterbourGon/diskv) - 具有 disk-backed 功能的持久化鍵值存儲
* [eliasdb](https://github.com/krotik/eliasdb) - 無依賴、事物型圖數據庫，支持 REST API、短語搜索以及類 SQL 的查詢語言
* [forestdb](https://github.com/couchbase/Goforestdb) - ForestDB 的 Go 語言藉口
* [GCache](https://github.com/bluele/gcache) - 支持緩存過期、 LFU、 LRU 和 ARC 的緩存庫
* [geocache](https://github.com/melihmucuk/geocache) - 基於內存存儲的緩存，適用於分佈式部署的應用
* [Go-cache](https://github.com/pmylund/Go-cache) - 內存鍵值存儲/緩存庫，適用於單機程序
* [Goleveldb](https://github.com/syndtr/Goleveldb) - 使用 Go 語言實現的 [LevelDB](https://github.com/Google/leveldb)
* [groupcache](https://github.com/Golang/groupcache) - Groupcache 是一個緩存及緩存填充庫，在很多情況下用於替代 memcached.
* [influxdb](https://github.com/influxdb/influxdb) - 用於計量、事件及實時分析的、可擴展的數據庫
* [ledisdb](https://github.com/siddontang/ledisdb) - Ledisdb 是一個高性能 NoSQL 數據庫，類似 Redi
* [leviGo](https://github.com/jmhodges/leviGo) - LeviGo 是 LevelDB的 Go 語言封裝
* [moss](https://github.com/couchbase/moss) - Moss 是一個簡單的 LSM 鍵值存儲引擎，100% Go 語言實現
* [piladb](https://github.com/fern4lvarez/piladb) - 輕量級 RESTful 數據庫引擎，基於堆棧結構
* [prometheus](https://github.com/prometheus/prometheus) - 監控系統及時間序列數據庫
* [rqlite](https://github.com/rqlite/rqlite) - 基於 SQLite 的輕量級的、分佈式的關係型數據庫
* [Scribble](https://github.com/nanobox-io/Golang-scribble) - 小巧的 JSON 文件存儲
* [tempdb](https://github.com/rafaeljesus/tempdb) - 臨時數據的鍵值對存儲
* [tidb](https://github.com/pingcap/tidb) - TiDB 是一個分佈式的 SQL 數據庫。受到了 Google F1的啟發
* [tiedot](https://github.com/HouzuoGuo/tiedot) - 基於 Go 語言的 NoSQL 數據庫
* [Tile38](https://github.com/tidwall/tile38) - 地理位置數據庫及實時地理圍欄

_數據庫遷移_

* [darwin](https://github.com/GuiaBolso/darwin) - 數據庫模式進化庫
* [Go-fixtures](https://github.com/RichardKnop/Go-fixtures) - 類似 DjanGo fixtures，用於 Golang 的內建數據庫/sql 庫
* [Goose](https://github.com/steinbacher/Goose) - 數據庫遷移工具。你可以通過編寫增量 SQL 或 Go 語言腳本來管理你的數據庫
* [Gormigrate](https://github.com/Go-Gormigrate/Gormigrate) - 數據庫模式遷移幫助工具，用於 Gorm ORM.
* [migrate](https://github.com/mattes/migrate) - 數據庫遷移。命令行及 Go 語言庫
* [pravasan](https://github.com/pravasan/pravasan) - 簡單的遷移，目前支持 MySQL 但是近期打算支持 Postgres, SQLite, MonGoDB 等等
* [soda](https://github.com/markbates/pop/tree/master/soda) - 數據庫遷移、創建、 ORM等等，用於 MySQL, PostgreSQL, 以及 SQLite.
* [sql-migrate](https://github.com/rubenv/sql-migrate) - 數據庫遷移工具，允許利用 Go-bindata 將數據庫遷移嵌入應用程序

_數據庫工具_

* [Go-mysql](https://github.com/siddontang/Go-mysql) - 用於處理 MySQL 協議及複製的 Go 語言工具集.
* [Go-mysql-elasticsearch](https://github.com/siddontang/Go-mysql-elasticsearch) - 將你的 MySQL 數據自動同步到 Elasticsearch
* [kingshard](https://github.com/flike/kingshard) - kingshard 是一個Go語言編寫的高性能 MySQL 數據庫代理
* [myreplication](https://github.com/2tvenom/myreplication) - MySql 二進制 log 複製監聽器，支持基於語句和基於行的複製
* [orchestrator](https://github.com/github/orchestrator) - MySQL複製拓撲管理器及可視化工具
* [pgweb](https://github.com/sosedoff/pgweb) - 基於 Web 的 PostgreSQL 數據庫瀏覽工具
* [pREST](https://github.com/nuveo/prest) - 通過任何 PostgreSQL 數據庫提供 RESTful API
* [vitess](https://github.com/youtube/vitess) - vitess 提供了能夠使大型 web 服務 MySQL 數據庫的擴展變得更加容易的服務器及工具

_用於創建和使用SQL的庫_

* [dat](https://github.com/mgutz/dat) - Go 語言 Postgres 數據庫工具集
* [Dotsql](https://github.com/gchaincl/dotsql) - 一個Go語言庫，幫助你將 sql 文件保存在一個地方並且方便的取用
* [Goqu](https://github.com/doug-martin/Goqu) - 地道的 SQL 語句創建器和查詢庫
* [iGor](https://github.com/galeone/iGor) - PostgreSQL 的抽象層，支持高級功能以及類 Gorm 的語法
* [ozzo-dbx](https://github.com/Go-ozzo/ozzo-dbx) - 提供強大的數據恢復功能以及構建不區分數據庫類型的查詢的能力
* [scaneo](https://github.com/variadico/scaneo) - 生成用於將數據庫行轉換為任意結構體的 Go 代碼
* [sqrl](https://github.com/elgris/sqrl) - SQL 查詢創建器，是 Squirrel 的一個分叉版本，進行了性能方面的優化
* [Squirrel](https://github.com/Masterminds/squirrel) - 一個幫助你構建 SQL 查詢的庫
* [xo](https://github.com/knq/xo) - 基於已知的數據庫表或自定義查詢生成地道的 Go 語言代碼，支持 PostgreSQL, MySQL, SQLite, Oracle, 以及 Microsoft SQL Server.

## 數據庫驅動

_用於連接和操作數據庫的庫_

* 關係型數據庫  
    * [avatica](https://github.com/Boostport/avatica) - Apache Phoenix/Avatica SQL 驅動
    * [bgc](https://github.com/viant/bgc) - 數據庫連接工具包，用於通過 Go 語言訪問 BigQuery
    * [firebirdsql](https://github.com/nakagami/firebirdsql) - Firebird RDBMS SQL 驅動
    * [Go-adodb](https://github.com/mattn/Go-adodb) - Microsoft ActiveX 對象數據庫驅動
    * [Go-bqstreamer](https://github.com/rounds/Go-bqstreamer) - BigQuery fast and concurrent stream insert.
    * [Go-mssqldb](https://github.com/denisenkom/Go-mssqldb) - Go 語言Microsoft MSSQL 驅動
    * [Go-oci8](https://github.com/mattn/Go-oci8) - Oracle 驅動
    * [Go-sql-driver/mysql](https://github.com/Go-sql-driver/mysql) - Go 語言 MySQ L驅動
    * [Go-sqlite3](https://github.com/mattn/Go-sqlite3) - Go 語言的 SQLite3 驅動
    * [Gofreetds](https://github.com/minus5/Gofreetds) Microsoft MSSQL 驅動。 [FreeTDS](http://www.freetds.org)的go語言封裝
    * [pgx](https://github.com/jackc/pgx) - PostgreSQL 驅動，支持比 database/sql 更多的特性
    * [pq](https://github.com/lib/pq) - 純 Go 語言編寫的 Postgres 驅動
*   NoSQL 數據庫
    * [aerospike-client-Go](https://github.com/aerospike/aerospike-client-Go) - Aerospike 客戶端
    * [aranGolite](https://github.com/solher/aranGolite) - AranGoDB 的輕量級 Go 語言驅動
    * [asc](https://github.com/viant/asc) - 用於go語言連接 Aerospike
    * [cayley](https://github.com/Google/cayley) - 支持多種後端的圖數據庫
    * [dsc](https://github.com/viant/dsc) - 數據庫連接工具包，支持 SQL, NoSQL 及結構化文件
    * [dynaGo](https://github.com/underarmour/dynaGo) - DynaGo 是一個符合最小驚奇原則（principle of least surprise）的 DynamoDB 客戶端
    * [Go-couchbase](https://github.com/couchbase/Go-couchbase) - Go 語言 Couchbase 客戶的
    * [Go-couchdb](https://github.com/fjl/Go-couchdb) - 另一個 CouchDB HTTP API 的 Go 語言封裝
    * [Gocb](https://github.com/couchbase/Gocb) - 官方 Couchbase 的 Go 語言 SDK
    * [Gocql](http://Gocql.github.io) - Apache Cassandra 的 Go 語言驅動
    * [Gomemcache](https://github.com/bradfitz/Gomemcache/) - memcache 客戶端庫
    * [Gorethink](https://github.com/dancannon/Gorethink) - RethinkDB 的 Go 語言驅動
    * [Goriak](https://github.com/zegl/Goriak) - Riak KV 的 Go 語言驅動
    * [mGo](https://Godoc.org/labix.org/v2/mGo) - MonGoDB 驅動，通過簡單的 API 實現了豐富的、經過測試的特性，這些 API 遵循 Go 語言的習慣
    * [neo4j](https://github.com/cihangir/neo4j) - Neo4j Rest API 的 Go 語言接口
    * [Neo4j-Go](https://github.com/davemeehan/Neo4j-Go) - Go 語言實現的 Neo4j REST 客戶端
    * [neoism](https://github.com/jmcvetta/neoism) - Go 語言 Neo4j 客戶端
    * [rediGo](https://github.com/garyburd/rediGo) - RediGo 是 Redis 數據庫的 Go 語言客戶端.
    * [redis](https://github.com/Go-redis/redis) - Redis 的 Go 語言客戶端
    * [redis](https://github.com/hoisie/redis) - 簡單、強大的 Redis 客戶端
    * [redis](https://github.com/bsm/redeo) - 兼容Redis協議的 TCP 服務器/服務.
    * [xredis](https://github.com/shomali11/xredis) - 類型安全的、可定製的、簡潔易用的 Redis 客戶端
*   搜索及分析數據庫
    * [bleve](https://github.com/blevesearch/bleve) - 現代文本索引庫
    * [elastic](https://github.com/olivere/elastic) - Go 語言的 Elasticsearch 客戶端
    * [elasticsql](https://github.com/cch123/elasticsql) - 將 sql 轉換為 elasticsearch dsl
    * [elastiGo](https://github.com/mattbaird/elastiGo) - Elasticsearch 客戶端庫
    * [Goes](https://github.com/belogik/Goes) - 用於和 Elasticsearch 交互的庫
    * [skizze](https://github.com/seiflotfy/skizze) - 概率相關數據結構服務和存儲

## 日期和時間

_處理日期和時間的庫_

* [carbon](https://github.com/uniplaces/carbon) - 簡單的時間擴展程序，有很多有用的方法，是 PHP Carbon 庫的接口
* [durafmt](https://github.com/hako/durafmt) - 持續時間格式化
* [feiertage](https://github.com/wlbr/feiertage) - 一組計算德國公共假期的函數，比如復活節、感恩節等
* [Go-persian-calendar](https://github.com/yaa110/Go-persian-calendar) - 太陽曆
* [Goweek](https://github.com/grsmv/Goweek) - 處理星期的庫
* [now](https://github.com/jinzhu/now) - Now 是一個 Go 語言的時間工具集
* [NullTime](https://github.com/kirillDanshin/nulltime) -時間可以是 NULL 的庫
* [timeutil](https://github.com/leekchan/timeutil) - 為 Go 語言時間包擴展了有用的功能，例如時間間隔和格式化

## 分佈式系統

_用於構建分佈式系統的庫_

* [celeriac](https://github.com/svcavallar/celeriac.v1) - 利用 Go 語言對Celery 的 worker，任務，事件進行交互和監控的庫
* [drmaa](https://github.com/dgruber/drmaa) -集群調度工具的任務提交庫，基於標準 DRMAA 
* [flowgraph](https://github.com/vectaport/flowgraph) - MPI 風格的讀取，發送協同層
* [gleam](https://github.com/chrislusf/gleam) - 快速、可擴展的分佈式 map/reduce 系統，使用純 Go 語言和 Luajit 編寫，融合了 Go 語言的高並發能力和 Luajit 的高性能，可以獨立或分佈式部署運行。
* [glow](https://github.com/chrislusf/glow) - 簡單易用、可擴展的大數據處理能力，Map-Reduce 以及執行 DAG(Database Availability Group），所有功能均由Go語言編寫.
* [Go-jump](https://github.com/dgryski/Go-jump) - Google "Jump" 一致性哈希函數的藉口
* [Go-kit](https://github.com/Go-kit/kit) - 為服務工具吧，支持服務發現、負載均衡 、可插拔傳輸以及請求追蹤等
* [Gorpc](https://github.com/valyala/Gorpc) - 簡單、快速、可擴展的 RPC 庫，針對高負載場景
* [grpc-Go](https://github.com/grpc/grpc-Go) - Go 語言實現的 gRPC. HTTP/2 基於 RPC.
* [hprose](https://github.com/hprose/hprose-Golang) - 非常牛逼的 RPC 庫，當前支持 25+ 語言。
* [jsonrpc](https://github.com/osaminGo/jsonrpc) - jsonrpc 包實現了 JSON-RPC 2.0.
* [jsonrpc](https://github.com/ybbus/jsonrpc) - JSON-RPC 2.0 HTTP 客戶端實現
* [KrakenD](https://github.com/devopsfaith/krakend) - 帶有中間件的，高性能 API 網關框架
* [micro](https://github.com/micro/micro) - 微服務工具套件和分佈式系統平台
* [NATS](https://github.com/nats-io/gnatsd) - 輕量級、高性能微服務系統，用於微服務、物聯網以及雲
* [raft](https://github.com/hashicorp/raft) - Raft 一致性協議的 Go 語言實現, 作者是 HashiCorp.
* [raft](https://github.com/coreos/etcd/tree/master/raft#readme) - Raft 一致性協議的 Go 語言實現, 作者是 CoreOS.
* [ringpop-Go](https://github.com/uber/ringpop-Go) - 可擴展、容錯的應用層分片庫
* [rpcx](https://github.com/smallnest/rpcx) - rpcx是一個類似阿里巴巴 Dubbo 和微博 Motan 的分佈式的 RPC 服務框架
* [sleuth](https://github.com/ursiform/sleuth) - 在 HTTP 服務之間進行無主 p2p 自動發現和 RPC通信(使用 [ZeroMQ](https://github.com/zeromq/libzmq)).
* [tendermint](https://github.com/tendermint/tendermint) - 一個高性能的中間件，用於將任何語言編寫的狀態機轉換為一個拜占庭容錯狀態機，使用Tendermint 一致性及區塊鏈協議
* [torrent](https://github.com/anacrolix/torrent) - BitTorrent 客戶端
* [dht](https://Godoc.org/github.com/anacrolix/dht) - BitTorrent Kademlia DHT 的實現.
* [Go-peerflix](https://github.com/Sioro-Neoku/Go-peerflix) - 視頻流 torrent 客戶端

## 電子郵件

_用於創建和發送電子郵件的庫_

* [douceur](https://github.com/aymerick/douceur) - HTML 郵件中的內聯 CSS
* [email](https://github.com/jordan-wright/email) - 一個健壯的、靈活的 email 庫
* [Go-dkim](https://github.com/toorop/Go-dkim) - DKIM 庫，用於對 email 進行簽名和驗證
* [Go-imap](https://github.com/emersion/Go-imap) - IMAP 庫，用於客戶端和服務器
* [Go-message](https://github.com/emersion/Go-message) - 用於觸雷互聯網消息格式和郵件的庫
* [Gomail](https://github.com/Go-Gomail/Gomail/) - Gomail 是一個非常簡單且強大的庫，用於發送電子郵件
* [Hectane](https://github.com/hectane/hectane) - 輕量級 SMTP 客戶端，提供 HTTP API
* [hermes](https://github.com/matcornic/hermes) - 一個用於生成乾淨、響應式 HTML e-mail 的包
* [MailHog](https://github.com/mailhog/MailHog) - Email 及 SMTP 測試工具，具有 web 及 API 接口
* [SendGrid](https://github.com/sendgrid/sendgrid-Go) - SendGrid 的 Go 語言庫，用於發送電子郵件
* [smtp](https://github.com/mailhog/smtp) - SMTP 服務器協議狀態機

## 嵌入式腳本語言

_在你的 Go 代碼中嵌入其他語言._

* [aGora](https://github.com/PuerkitoBio/aGora) - 一種動態類型的可以嵌入 Go 中的編程語言
* [anko](https://github.com/mattn/anko) - Go 語言編寫的解釋器
* [binder](https://github.com/alexeyco/binder) - Lua 接口, 基於 [Gopher-lua](https://github.com/yuin/Gopher-lua)
* [gisp](https://github.com/jcla1/gisp) - Simple LISP
* [Go-duktape](https://github.com/olebedev/Go-duktape) - Duktape JavaScript 引擎的 Go 語言接口
* [Go-lua](https://github.com/Shopify/Go-lua) - Lua 5.2 虛擬機的純 Go 語言接口
* [Go-php](https://github.com/deuill/Go-php) - PHP 的 Go 語言接口
* [Go-python](https://github.com/sbinet/Go-python) - CPython C-API 的 Go 語言接口
* [Golua](https://github.com/aarzilli/Golua) - Lua C API。的 Go 語言接口
* [Gopher-lua](https://github.com/yuin/Gopher-lua) - Go 語言編寫的 Lua 5.1 虛擬機和編譯器
* [ngaro](https://github.com/db47h/ngaro) - 可嵌入的 Ngaro 虛擬機實現，支持在 Retro 中使用腳步
* [otto](https://github.com/robertkrimen/otto) - Go 編寫的 Javascrip 解釋器
* [purl](https://github.com/ian-kent/purl) - 嵌入 Go 語言的 Perl 5.18.2

## 文件

_用於處理文件和文件系統的庫_

* [afero](https://github.com/spf13/afero) - 一個文件系統的抽象系統
* [Go-csv-tag](https://github.com/artonge/Go-csv-tag) - 使用 tag 導入 csv
* [Go-gtfs](https://github.com/artonge/Go-gtfs) - 加載 gtfs 文件
* [notify](https://github.com/rjeczalik/notify) - 文件系統提示庫，具有簡單的 API ，類似 os/signal.
* [skywalker](https://github.com/dixonwille/skywalker) - 允許你簡單方便的並發瀏覽文件系統
* [tarfs](https://github.com/posener/tarfs) - 為 tar 文件實現的 [`FileSystem` 接口](https://Godoc.org/github.com/kr/fs#FileSystem)

## 財經

_會計及財務庫_

* [accounting](https://github.com/leekchan/accounting) - 金錢及貨幣格式
* [decimal](https://github.com/shopspring/decimal) - 任意精度、固定點十進制數
* [Go-finance](https://github.com/FlashBoys/Go-finance) - 使用 Go 語言來理解財務市場數據
* [Go-money](https://github.com/rhymond/Go-money) - [Fowler 金錢模型](https://martinfowler.com/eaaCatalog/money.html)的實現
* [ofxGo](https://github.com/aclindsa/ofxGo) - 查詢 OFX 服務器並解析其響應 (有一個示例的命令行客戶端)
* [vat](https://github.com/dannyvankooten/vat) - VAT 驗證及歐洲增值稅率工具

## 表單

_操作表單的庫_

* [bind](https://github.com/robfig/bind) - 將表單數據綁定到任意的 Go 變數上
* [binding](https://github.com/mholt/binding) - 將來自 net/HTTP 請求的表單、JSON 數據綁定到結構體
* [conform](https://github.com/leebenson/conform) - 檢查用戶輸入並基於結構標籤來清理數據
* [form](https://github.com/Go-playground/form) - 解碼 url 中的數據到 Go 語言變數中以及將 Go 語言變數編碼進 url 支持Dual Array 及 Full map
* [formam](https://github.com/monoculum/formam) - 將表單數據解碼到結構體
* [forms](https://github.com/albrow/forms) - 框架無關的表單/JSON數據解析驗證庫，支持多部分表單及文件
* [Gorilla/csrf](https://github.com/Gorilla/csrf) - 為 Go 語言 web 應用提供 CSRF 防禦
* [nosurf](https://github.com/justinas/nosurf) - CSRF 防禦中間件

## 遊戲開發

_超讚的遊戲開發庫_

* [Azul3D](https://github.com/azul3d/engine) - Go 語言編寫的 3D 遊戲引擎
* [Ebiten](https://github.com/hajimehoshi/ebiten) - Go 語言編寫的簡單的 2D 遊戲庫
* [enGo](https://github.com/EnGoEngine/enGo) - EnGo 是一個開源的 2D 遊戲引擎，遵循實體-組件-系統範式
* [GarageEngine](https://github.com/vova616/GarageEngine) - 2d 遊戲引擎，利用 OpenGL 工作
* [glop](https://github.com/runningwild/glop) - Glop (Game Library Of Power) 是一個很簡單的跨平台遊戲庫
* [Go-astar](https://github.com/beefsack/Go-astar) - Go 語言實現的 A* 尋路算法
* [Go-collada](https://github.com/GlenKelley/Go-collada) - 操作 Collada 文件格式的 Go 語言庫
* [Go-sdl2](https://github.com/veandco/Go-sdl2) - [Simple DirectMedia Layer](https://www.libsdl.org/)的 Go 語言接口
* [Go3d](https://github.com/ungerik/Go3d) - 專注性能的 2D/3D 數學庫
* [Gonet](https://github.com/xtaci/Gonet) - Go 語言實現的遊戲服務器框架
* [Leaf](https://github.com/name5566/leaf) - 輕量級遊戲服務器框架
* [Pixel](https://github.com/faiface/pixel) - 手工 2D 遊戲引擎庫
* [raylib-Go](https://github.com/gen2brain/raylib-Go) - [raylib](http://www.raylib.com/)的 Go 語言接口，簡單、易用的用於學習遊戲編程的庫
* [termloop](https://github.com/JoelOtter/termloop) - 終端遊戲引擎，基於 Termbox

## 代碼生成與泛型

_一些增強語言的功能的工具例如通過代碼生成支持泛型_

* [efaceconv](https://github.com/t0pep0/efaceconv) - 代碼生成工具，用於高效的將 interface{} 轉換為不可變類型，不需要進行任何內存分配
* [gen](https://github.com/clipperhouse/gen) - 代碼生成工具,用於提供類似泛型的功能
* [Go-linq](https://github.com/ahmetalpbalkan/Go-linq) - 類似 .NET LINQ 的查詢方法
* [interfaces](https://github.com/rjeczalik/interfaces) - 命令行工具，用於生成接口定義
* [jennifer](https://github.com/dave/jennifer) - 不適用模板生成任意 Go 語言代碼
* [pkgreflect](https://github.com/ungerik/pkgreflect) - 用於包作用域反射的 Go 語言預處理器

## Go 編譯器

_用於把 Go 語言編譯為其他語言的工具_

* [Gopherjs](https://github.com/Gopherjs/Gopherjs) - 把 Go 編譯為 JavaScript.
* [llGo](https://github.com/Go-llvm/llGo) - 基於 LLVM 的 Go 語言編譯器
* [tardisGo](https://github.com/tardisGo/tardisGo) - Golang 轉換為 Haxe 進而轉換為 CPP/CSharp/Java/JavaScript 的編譯器.

## 協程

_用於管理和處理Go 語言協程的工具_

* [Go-floc](https://github.com/workanator/Go-floc) - 輕鬆編排 Go 語言協程
* [Go-flow](https://github.com/kamildrazkiewicz/Go-flow) - 控制 Go 語言協程的執行順序
* [Goworker](https://github.com/benmanns/Goworker) - Goworker 是一個基於 Go 語言的後台worker
* [grpool](https://github.com/ivpusic/grpool) - 輕量級 Go 語言協程池
* [pool](https://github.com/Go-playground/pool) - 有限消費者協程或無限協程池，用於簡單的處理協程和取消協程
* [semaphore](https://github.com/kamilsk/semaphore) - 實現了信號量模式，提供了超時鎖定、解鎖操作，基於通道和上下文。
* [tunny](https://github.com/Jeffail/tunny) - Go 語言協程池

## GUI

_用於構建 GUI 程序的庫_

_工具包_

* [app](https://github.com/murlokswarm/app) - 使用Go, HTML 和 CSS 進行應用程序開發的庫 支持 MacOS, Windows in progress.
* [Go-astilectron](https://github.com/asticode/Go-astilectron) - 使用 Go 以及 HTML/JS/CSS 構建應用程序. (基於Electron)
* [Go-gtk](http://mattn.github.io/Go-gtk/) - GTK 的 Go 語言接口
* [Go-qml](https://github.com/Go-qml/qml) - QML 對 Go 語言的支持
* [Go-sciter](https://github.com/sciter-sdk/Go-sciter) - Sciter 的 Go 語言接口 : 支持現代 GUI 程序開發的、嵌入式 HTML/CSS/腳本 引擎。跨平台。
* [Goqt](https://github.com/visualfc/Goqt) - Qt的 Go 語言接口
* [Gotk3](https://github.com/Gotk3/Gotk3) - GTK3 的 Go 語言接口
* [Gowd](https://github.com/dtylman/Gowd) - 使用 Go, HTML, CSS 和 NW.js 語言進行快速、簡單的桌面 UI 開發。跨平台
* [qt](https://github.com/therecipe/qt) - Qt 的 Go 語言接口 (支持 Windows / macOS / Linux / Android / iOS / Sailfish OS / Raspberry Pi)
* [ui](https://github.com/andlabs/ui) - 平台原生 GUI 庫。跨平台
* [walk](https://github.com/lxn/walk) - windows 應用程序開發工具包

_交互_

* [Gosx-notifier](https://github.com/deckarep/Gosx-notifier) - OSX 桌面提醒庫
* [robotGo](https://github.com/Go-vGo/robotGo) - 跨平台 GUI 自動化；控制滑鼠、鍵盤及其他設備
* [systray](https://github.com/getlantern/systray) - 一個跨平台的 Go 語言庫，用於在桌面提醒區域放置按鈕及菜單
* [trayhost](https://github.com/shurcooL/trayhost) - 一個跨平台的 Go 語言庫，用於在主機系統任務條區域放置按鈕及菜單

## 硬件

_庫、工具以及教程，講解如何操控硬件_

參見 [Go-hardware](https://github.com/rakyll/Go-hardware) 獲取更加全面的信息

## 圖象

_用於操作圖象的庫_

* [bild](https://github.com/anthonynsimon/bild) - 彙集了使用 Go 語言編寫的圖象處理算法
* [bimg](https://github.com/h2non/bimg) - 利用 libvips 進行快速高效的圖象處理
* [geopattern](https://github.com/pravj/geopattern) - 從字元串創建優美的圖樣
* [gg](https://github.com/fogleman/gg) - 使用 Go 編寫的 2D 渲染程序
* [gift](https://github.com/disintegration/gift) - 一組圖象處理濾波器
* [Go-cairo](https://github.com/ungerik/Go-cairo) - cairo 圖形庫的 Go 語言接口
* [Go-gd](https://github.com/bolknote/Go-gd) - GD 庫的 Go 語言接口
* [Go-nude](https://github.com/koyachi/Go-nude) - 使用 Go 語言進行裸替檢測
* [Go-opencv](https://github.com/lazywei/Go-opencv) - OpenCV 的 Go 語言接口
* [Go-webcolors](https://github.com/jyotiska/Go-webcolors) - webcolors 庫的 Go 語言接口
* [imagick](https://github.com/Gographics/imagick) - ImageMagick 的 MagickWand C 語言 API 的 Go 語言接口
* [imaginary](https://github.com/h2non/imaginary) - 快速且簡單的 HTTP 微服務，用於圖象縮放
* [imaging](https://github.com/disintegration/imaging) - 簡單的 Go 語言圖象處理包
* [img](https://github.com/hawx/img) - 圖象操作工具精選集
* [ln](https://github.com/fogleman/ln) - 3D 圖線藝術渲染
* [mpo](https://github.com/donatj/mpo) - MPO 3D 照片解碼與轉換工具.
* [picfit](https://github.com/thoas/picfit) - 一個使用 Go 語言編寫的圖片縮放服務器
* [pt](https://github.com/fogleman/pt) - 光線追蹤引擎
* [resize](https://github.com/nfnt/resize) - 使用 Go 語言編寫的具有常見差值功能的圖片縮放工具
* [rez](https://github.com/bamiaux/rez) - 純 Go 及 SIMD 實現的圖象縮放庫
* [smartcrop](https://github.com/muesli/smartcrop) - 為任意圖片進行剪裁的工具
* [svGo](https://github.com/ajstarks/svGo) - 用於生成 SVG 的 Go 語言庫
* [tga](https://github.com/ftrvxmtrx/tga) - tga 是一個 TARGA 圖象格式解碼/編碼器

## 物聯網

_用於為物聯網設備編程的庫._

* [connectordb](https://github.com/connectordb/connectordb) - 開源個人數據及物聯網平台
* [devices](https://github.com/Goiot/devices) - 物聯網設備套件庫
* [eywa](https://github.com/xcodersun/eywa) - Eywa 是一個持續追蹤所有連接設備的連接管理器
* [floGo](https://github.com/tibcosoftware/floGo) - FloGo 是一個用於物聯網 Edge App 及整合的開源框架
* [gatt](https://github.com/paypal/gatt) - Gatt 是一個用於創建低功耗藍芽外設的庫
* [Gobot](https://github.com/hybridgroup/Gobot/) - Gobot 是一個用於機器人，物理計算以及物聯網的庫
* [mainflux](https://github.com/Mainflux/mainflux) - 工業網物聯網消息及設備管理服務器
* [sensorbee](https://github.com/sensorbee/sensorbee) - 輕量級物聯網流處理引擎

## 日誌

_用於生成和操作日誌文件的庫._

* [glg](https://github.com/kpanGo/glg) - glg 是一個簡單、快速、分級的日誌庫
* [glog](https://github.com/Golang/glog) - 分級記錄日誌的庫
* [Go-cronowriter](https://github.com/utahta/Go-cronowriter) 對日誌文件進行自動循環寫入的庫基於當前日期和時間，類似 cronolog.
* [Go-log](https://github.com/siddontang/Go-log) - 支持多處理器及日誌分級的庫
* [Go-log](https://github.com/ian-kent/Go-log) - Go 語言實現的 Log4j
* [Go-logger](https://github.com/apsdehal/Go-logger) - 支持日誌分級的簡單的日誌工具
* [Gologger](https://github.com/sadlil/Gologger) - 簡單易用的日誌庫，可以在彩色控制台、簡易控制的、文件或 Elasticsearch 中記錄
* [Gomol](https://github.com/aphistic/Gomol) - 支持多種輸出，結構化的日誌模組，可以擴展它的輸出
* [Gone/log](https://github.com/One-com/Gone/tree/master/log#readme) - 快速、可擴展、全功能、兼容標準庫的日誌庫
* [log](https://github.com/apex/log) - 結構化日誌庫
* [log](https://github.com/Go-playground/log) - 簡單、可配置、可擴展的結構化日誌庫
* [log-voyage](https://github.com/firstrow/logvoyage) - 全功能日誌saas 使用 Go 語言編寫
* [log15](https://github.com/inconshreveable/log15) - 簡單強大的日誌庫
* [logdump](https://github.com/ewwwwwqm/logdump) - 支持分級的日誌庫
* [logex](https://github.com/chzyer/logex) - Go 語言日誌庫，支持追蹤和分級，基於標準庫進行了封裝
* [logger](https://github.com/azer/logger) - 一個極簡的日誌庫
* [logrus](https://github.com/Sirupsen/logrus) - 支持結構化的日誌工具.
* [logrusly](https://github.com/sebest/logrusly) - [logrus](https://github.com/sirupsen/logrus) 的插件，用於將錯誤發送到 [Loggly](https://www.loggly.com/).
* [logutils](https://github.com/hashicorp/logutils) - 對 Go 語言標準日誌工具進行了擴展，使其更好用
* [logxi](https://github.com/mgutz/logxi) - 十二要素 app 日誌工具，非常快速，令你開心
* [lumberjack](https://github.com/natefinch/lumberjack) - 簡單的循環日誌工具，實現了 io.WriteCloser.
* [mlog](https://github.com/jbrodriguez/mlog) - 一個簡單的日誌模組，可以分5級並有一個可選的循環日誌文件記錄功能，支持 stdout/stderr 輸出.
* [ozzo-log](https://github.com/Go-ozzo/ozzo-log) - 高性能日誌庫，支持日誌嚴重級別、分類及過濾。可以將過濾後的信息發送到不同的目的地(例如： 控制台、網絡、郵箱).
* [seelog](https://github.com/cihub/seelog) - 一個靈活的、解耦的、格式化的日誌庫
* [slf](https://github.com/ventu-io/slf) - 簡單日誌門面（The Structured Logging Facade (SLF) ） (類似 SLF4J，但是它是結構化的，並且專為 Go 語言設計)
* [slog](https://github.com/ventu-io/slog) - 為 Go 語言實現的結構化日誌門面（Structured Logging Facade (SLF) ）
* [spew](https://github.com/davecgh/Go-spew) - 為 Go 語言的數據結構實現了一個整潔的打印功能，有助於調試
* [stdlog](https://github.com/alexcesaro/log) - Stdlog 是一個面向對象的庫，提供了分級日誌功能，對於定時任務很有用.
* [tail](https://github.com/hpcloud/tail) - 這個 Go 語言軟件包力爭模擬 BSD tail 的功能
* [xlog](https://github.com/xfxdev/xlog) - 插件架構以及靈活的日誌系統，具有日誌等級控制，多日誌目標以及自定義日誌格式功能
* [xlog](https://github.com/rs/xlog) - 結構化日誌 for `net/context` aware HTTP handlers ，可以靈活的分發
* [zap](https://github.com/uber-Go/zap) - 快速的、結構化的、分級的日誌庫
* [zerolog](https://github.com/rs/zerolog) - 零分配 JSON 日誌.

## 機器學習

_機器學習庫_

* [bayesian](https://github.com/jbrukh/bayesian) - 貝葉斯分類器
* [CloudForest](https://github.com/ryanbressler/CloudForest) - 純 Go 語言編寫的快速、靈活、多線程決策樹
* [gaGo](https://github.com/MaxHalford/gaGo) - 多種群，靈活的，並行的遺傳算法
* [Go-fann](https://github.com/white-pony/Go-fann) - 快速人工神經網絡庫(FANN)的 Go 語言藉口.
* [Go-galib](https://github.com/thoj/Go-galib) - Go 語言編寫的遺傳算法庫
* [Go-pr](https://github.com/daviddengcn/Go-pr) -  Go 語言模式識別庫
* [Gobrain](https://github.com/Goml/Gobrain) -  Go 語言編寫的神經網絡
* [Godist](https://github.com/e-dard/Godist) - 多種概率分佈及相關方法
* [Goga](https://github.com/tomcraven/Goga) -  Go 語言遺傳算法庫
* [GoLearn](https://github.com/sjwhitworth/Golearn) -  Go 語言通用機器學習庫
* [Golinear](https://github.com/danieldk/Golinear) - liblinear 庫的 Go 語言接口
* [Goml](https://github.com/cdipaolo/Goml) - 即時go語言機器學習庫
* [GoRecommend](https://github.com/timkaye11/GoRecommend) - Go 語言推薦算法庫
* [GorGonia](https://github.com/chewxy/GorGonia) - 基於圖的計算庫，類似於 Theano。提供了一些原型用於構建各種個樣的機器學習和神經網絡算法
* [libsvm](https://github.com/datastream/libsvm) - libsvm 的 Go 語言版本，基於 LIBSVM 3.14.
* [mlGo](https://github.com/NullHypothesis/mlGo) - 這個項目點目標是在 Go 語言中提供極簡的機器學習算法
* [neat](https://github.com/jinyeom/neat) - 即插即用的並行 Go 語言框架，用於增強拓撲神經網絡 (NEAT).
* [neural-Go](https://github.com/schuyler/neural-Go) - Go 語言實現的多層感知神經網絡，通過反向傳播算法進行訓練.
* [probab](https://github.com/ThePaw/probab) -概率分佈函數、貝葉斯推理。使用純 Go 語言編寫
* [reGommend](https://github.com/muesli/reGommend) - 推薦系統及協同過濾引擎
* [shield](https://github.com/eaigner/shield) - 貝葉斯文吧分類器，包含靈活的分詞器和存儲後端

## 消息

_實現了消息系統的庫_

* [CentrifuGo](https://github.com/centrifugal/centrifuGo) - 實時消息服務器
* [dbus](https://github.com/Godbus/dbus) - D-Bus的 Go 語言接口
* [drone-line](https://github.com/appleboy/drone-line) - 通過軟件包，docker 或是 Drone CI來發送 [Line](https://business.line.me/en/services/bot) 通知
* [emitter](https://github.com/olebedev/emitter) - 通過Go語言的方式發送事件消息，可以使用通配符，斷言，取消發送等優秀特性
* [EventBus](https://github.com/asaskevich/EventBus) - 輕量級事件庫，支持非同步
* [gaurun-client](https://github.com/osaminGo/gaurun-client) - Go 語言編寫的 Gaurun 客戶端
* [Glue](https://github.com/desertbit/glue) - 健壯的 Go 和 Javascript Socket 庫 (可以用來替代 Socket.io).
* [Go-longpoll](https://github.com/ventu-io/Go-longpoll) -  支持長輪詢的發佈與訂閲
* [Go-notify](https://github.com/TheCreeper/Go-notify) - 原生實現的桌面通知規範
* [Go-nsq](https://github.com/nsqio/Go-nsq) - NSQ 官方 Go 語言庫
* [Go-socket.io](https://github.com/GooGollee/Go-socket.io) - Go 語言的 socket.io庫 ,一個實時應用框架.
* [Go-vitotrol](https://github.com/maxatome/Go-vitotrol) - Viessmann Vitotrol 服務的 Go 語言客戶端
* [Gollum](https://github.com/trivaGo/Gollum) - 一個 n:m 的多路復用器，從不同的源匯聚消息並向目標進行廣播
* [Golongpoll](https://github.com/jcuga/Golongpoll) - HTTP 長輪詢服務器庫，讓 web 發佈與訂閲變的更簡單.
* [Goose](https://github.com/ian-kent/Goose) - Go 語言實現的服務器端事件發送
* [Gopush-cluster](https://github.com/Terry-Mao/Gopush-cluster) - Gopush-cluster 是一個 Go 語言實現的支持集群的comet服務（支持 websocket，和tcp協議）
* [Gorush](https://github.com/appleboy/Gorush) - 通知推送服務器，使用 [APNs2](https://github.com/sideshow/apns2) 和 Google [GCM](https://github.com/Google/Go-gcm).
* [guble](https://github.com/smancke/guble) - 一個使用通知推送(Google Firebase Cloud Messaging, Apple Push Notification services, SMS)、websockets 、REST API 的消息服務器。提供了分佈式操作和消息持久化特性
* [machinery](https://github.com/RichardKnop/machinery) - 非同步任務隊列，基於分佈式消息處理
* [manGos](https://github.com/Go-manGos/manGos) - 純 Go 語言實現的 Nanomsg ("Scalable Protocols") 
* [melody](https://github.com/olahol/melody) - 用於處理 websocket 會話的一個極簡框架，包括廣播和自動 ping/pong 處理
* [NATS Go Client](https://github.com/nats-io/nats) - 輕量級高性能發佈訂閲(publish-subscribe) 以及分佈式消息隊列系統，這個一個Go語言庫.
* [nsq-event-bus](https://github.com/rafaeljesus/nsq-event-bus) - 針對 NSQ 的主題和頻道進行了簡單的封裝
* [oplog](https://github.com/dailymotion/oplog) - 原生的 oplog/replication 系統，用於 REST APIs
* [pubsub](https://github.com/tuxychandru/pubsub) - 一個簡單的 pubsub 軟件包
* [RapidMQ](https://github.com/sybrexsys/RapidMQ) - RapidMQ 是一個輕量級，可靠的本地消息隊列管理庫
* [sarama](https://github.com/Shopify/sarama) - 用於 Apache Kafka 的庫
* [Uniqush-Push](https://github.com/uniqush/uniqush-push) - 基於 Redis 的統一推服務，用於服務器端向移動客戶端推送消息
* [zmq4](https://github.com/pebbe/zmq4) - ZeroMQ version 4的 GO 語言接口。也有適用於[version 3](https://github.com/pebbe/zmq3) 及 [version 2](https://github.com/pebbe/zmq2)的

## 雜項

_一些暫時無法歸類的庫_

* [alice](https://github.com/magic003/alice) -  GO 語言依賴注入容器
* [archiver](https://github.com/mholt/archiver) - 用於製作和解壓 .zip 和 .tar.gz 文件的庫和命令
* [autoflags](https://github.com/artyom/autoflags) - 通過結構體自動定義命令行標記的go語言軟件包
* [avgRating](https://github.com/kirillDanshin/avgRating) - 利用 Wilson Score 方程計算平均分及評級
* [banner](https://github.com/dimiro1/banner) - 在你的go語言應用中添加炫酷的橫幅
* [battery](https://github.com/distatus/battery) - 跨平台電源信息庫
* [bitio](https://github.com/icza/bitio) - 高度優化的比特級讀寫
* [browscap_Go](https://github.com/digitalcrab/browscap_Go) - [Browser Capabilities Project](http://browscap.org/)的 GO 語言庫
* [conv](https://github.com/cstockton/Go-conv) - conv 提供了一種快速且符合直覺的 GO 語言類型轉換
* [datacounter](https://github.com/miolini/datacounter) - Greaders/writer/HTTP.ResponseWriter 計數器
* [errors](https://github.com/pkg/errors) - 提供簡單的錯誤處理
* [Go-chat-bot](https://github.com/Go-chat-bot/bot) - IRC、Slack、Telegram 聊天機器人
* [Go-commons-pool](https://github.com/jolestar/Go-commons-pool) - 通用對象池
* [Go-multierror](https://github.com/hashicorp/Go-multierror) - 這個 Go 語言庫用於將一系列的錯誤作為一個整體來顯示
* [Go-openapi](https://github.com/Go-openapi) - 一些用於處理和利用 open-api 的庫集合
* [Go-resiliency](https://github.com/eapache/Go-resiliency) - GO 語言彈性模式
* [Go-sarah](https://github.com/oklahomer/Go-sarah) - 用於構建聊天機器人的框架，支持 LINE, Slack, Gitter等等
* [Go-shortid](https://github.com/ventu-io/Go-shortid) - 超短的、唯一的、非序列的、對 url 友好的 id
* [Go-unarr](https://github.com/gen2brain/Go-unarr) - 解壓縮庫，可用於 RAR, TAR, ZIP 以及 7z 歸檔文件.
* [Go.uuid](https://github.com/satori/Go.uuid) - 全球唯一標示符的實現(UUID)，同時支持生成和解析
* [Gofakeit](https://github.com/brianvoe/Gofakeit) - Go 語言編寫的隨機數據生成器
* [Goid](https://github.com/jakehl/Goid) - 生成和解析符合 RFC4122 規定的 V4 UUIDs.
* [Gopsutil](https://github.com/shirou/Gopsutil) - 用於獲取進程和系統資源利用率（cpu，內存，磁碟）的庫，跨平台
* [Gosms](https://github.com/haxpax/Gosms) - 你本地的SMS 網關，可以用來發送 SMS
* [Gountries](https://github.com/pariz/Gountries) - 一個用來展示國家及其行政區劃數據的庫
* [hanu](https://github.com/sbstjn/hanu) - 用於編寫 Slack 聊天機器人的庫
* [health](https://github.com/dimiro1/health) - 簡單易用、可擴展的健康檢查庫
* [indiGo](https://github.com/osaminGo/indiGo) - 唯一id生成器，使用 Sonyflake 並通過Base58進行編碼
* [jobs](https://github.com/albrow/jobs) - 持久化且靈活的後台任務庫
* [margelet](https://github.com/zhulik/margelet) - 用於創建 Telegram 聊天機器人的庫
* [secdl](https://github.com/xor-gate/secdl) - Lighttpd ModSecDownload alGorithm ported to Go to secure download urls.
* [slacker](https://github.com/shomali11/slacker) - 用於編寫 Slack 聊天機器人的庫，非常易用
* [stats](https://github.com/Go-playground/stats) - 監控 Go 內存狀態及系統狀態，通過UDP將數據發送到任何地方
* [uuid](https://github.com/agext/uuid) - 生成，編解碼 UUIDs v1 ，具有快速的或或密鑰級隨機節點標識
* [VarHandler](https://github.com/azr/generators/tree/master/varhandler) - Generate boilerplate HTTP input and ouput handling.
* [werr](https://github.com/txgruppi/werr) - Error Wrapper creates an wrapper for the error type in Go which captures the File, Line and Stack of where it was called.
* [xkg](https://github.com/Go-xkg/xkg) - X Keyboard Grabber
* [xstrings](https://github.com/huandu/xstrings) - 一些有用的字元串函數的集合

## 自然語言處理

_用於處理人類語言的庫_

* [dpar](https://github.com/danieldk/dpar/) - 基於變換的統計依賴關係解析器
* [Go-eco](https://github.com/ThePaw/Go-eco) - 相似性，相異性及距離度量；差異性，均勻度和不均勻度測量；物種多樣性估計；群落線模型
* [Go-i18n](https://github.com/nicksnyder/Go-i18n/) - 軟件包及相關工具，用於處理本地化文本
* [Go-mystem](https://github.com/dveselov/mystem) - Yandex.Mystem 的  CGo 接口， Yandex.Mystem 是一個俄語詞彙形態學分析器
* [Go-nlp](https://github.com/nuance/Go-nlp) - 在進行自然語言工作時用於處理離散概率分佈一些工具，以及其他的一些有用的工具
* [Go-stem](https://github.com/aGonopol/Go-stem) - 波特詞幹算法的一個實現
* [Go-unidecode](https://github.com/mozillazg/Go-unidecode) - Unicode 文本音譯為 ASCII 文本
* [Go2vec](https://github.com/danieldk/Go2vec) - 利用 Go 語言讀取和處理 word2vec 
* [Gojieba](https://github.com/yanyiwu/Gojieba) - 結巴分詞的 Go 語言實現的 [jieba](https://github.com/fxsjy/jieba) ，結巴分詞是一個用於中文的分詞算法
* [Golibstemmer](https://github.com/rjohnsondev/Golibstemmer) -  snowball libstemmer 庫的 Go 語言接口，包括了對 porter 2 的支持
* [Gounidecode](https://github.com/fiam/Gounidecode) - Go 語言的 Unicode 直譯器 (通常稱之為 unidecode) 
* [icu](https://github.com/Goodsign/icu) - icu4c C 庫的 CGo 接口，包括了檢測和轉換函數。保證了 version 50.1 版本的兼容性
* [libtextcat](https://github.com/Goodsign/libtextcat) - libtextcat C 庫的 CGo 接口。保證了version 2.2 版本的兼容性
* [MMSEGo](https://github.com/awsong/MMSEGo) -  Go 語言實現的 [MMSEG](http://technology.chtsai.org/mmseg/) （一個中文分詞算法）
* [nlp](https://github.com/Shixzie/nlp) - 從字元串中提取特定的值並填充結構體
* [paicehusk](https://github.com/rookii/paicehusk) - Go 語言實現的  Paice/Husk 詞幹算法
* [porter](https://github.com/a2800276/porter) - Martin Porter 實現的 C 語言版本的 Porter 詞幹算法的 Go 語言接口，非常直觀
* [porter2](https://github.com/zhenjl/porter2) - 非常快速的 Porter 2 stemmer.
* [prose](https://github.com/jdkato/prose) - 文本處理庫，支持詞語切分、詞性標記、命名實體提取等功能
* [RAKE.Go](https://github.com/Obaied/RAKE.Go) -  快速自動關鍵字提取算法(Rapid Automatic Keyword Extraction：RAKE)的 Go 語言接口
* [segment](https://github.com/blevesearch/segment) - 一個用於進行 Unicode 文本分割的庫，實現了 [Unicode Standard Annex #29](http://www.unicode.org/reports/tr29/)中描述的功能
* [sentences](https://github.com/neurosnap/sentences) - 語句標記器：將文欄位落轉換為語句列表
* [shamoji](https://github.com/osaminGo/shamoji) -  shamoji 是一個Go語言編寫的詞過濾軟件包
* [snowball](https://github.com/Goodsign/snowball) - Snowball 分詞器的Go語言接口，提供了分詞提取的功能 [Snowball native](http://snowball.tartarus.org/).
* [stemmer](https://github.com/dchest/stemmer) -  Go 語言分詞器軟件包，包括了英語和德語分詞器
* [textcat](https://github.com/pebbe/textcat) - 基於 n-gram 的 Go 語言文本分類軟件包，支持utf-8 和 raw 文本
* [whatlangGo](https://github.com/abadojack/whatlangGo) - Go 語言的自然語言檢測包。支持84種語言和24種書寫 (如拉丁，西里爾等書寫系統)。
* [when](https://github.com/olebedev/when) - 英語、俄語的自然語言日期、時間表達解析器，可以插入規則


## 網絡

_用於在不同網絡層工作的庫_

* [arp](https://github.com/mdlayher/arp) - 實現了 ARP 協議，遵循 RFC 826.
* [buffstreams](https://github.com/stabbycutyou/buffstreams) - 簡單易用的 protocolbuffer 數據流，基於 TCP
* [canopus](https://github.com/zubairhamed/canopus) - CoAP 客戶端/服務器實現 (RFC 7252)
* [dhcp6](https://github.com/mdlayher/dhcp6) - dhcp6 實現了一個DHCPv6 服務器，遵循RFC 3315.
* [dns](https://github.com/miekg/dns) - 用於處理 DNS 的 Go 語言庫
* [ether](https://github.com/songgao/ether) - 跨平台 Go 語言庫，用於發送和接收以太幀
* [ethernet](https://github.com/mdlayher/ethernet) - ethernet 實現了IEEE 802.3 Ethernet II 幀以及IEEE 802.1Q VLAN 標籤的組裝和剝離.
* [fasthttp](https://github.com/valyala/fasthttp) - fasthttp 是一個快速的 HTTP 實現，是 net/http的10倍性能
* [ftp](https://github.com/jlaffaye/ftp) - ftp 實現了一個 FTP 客戶端，遵循 [RFC 959](http://tools.ietf.org/html/rfc959).
* [Go-getter](https://github.com/hashicorp/Go-getter) - 一個用於通過 URL 從多種源下載文件或目錄的 Go 語言庫
* [Go-stun](https://github.com/ccding/Go-stun) - Go 語言實現的 STUN 客戶端 (RFC 3489 及 RFC 5389).
* [Gobgp](https://github.com/osrg/Gobgp) - Go 語言實現的BGP
* [Golibwireshark](https://github.com/sunwxg/Golibwireshark) - Golibwireshark 使用 libwireshark 庫來解析 pcap 文件並且分析數據
* [Gopacket](https://github.com/Google/Gopacket) - 用於報文處理的庫
* [Gopcap](https://github.com/akrennmair/Gopcap) - libpcap的 Go 語言封裝
* [Goshark](https://github.com/sunwxg/Goshark) - Goshark 使用 tshark 來對 IP 報文進行解碼並創建數據結構用於分析報文
* [Gosnmp](https://github.com/soniah/Gosnmp) -用於執行 SNMP 操作的庫
* [Gotcp](https://github.com/gansidui/Gotcp) - 用於快速編寫 tcp 應用的庫
* [grab](https://github.com/cavaliercoder/grab) - 管理文件下載的 Go 語言庫
* [graval](https://github.com/koofr/graval) - 試驗性的 FTP 服務器框架
* [jaziGo](https://github.com/udhos/jaziGo) - JaziGo 是一個 Go 語言編寫的工具，用於獲取多種網絡設備的配置.
* [kcp-Go](https://github.com/xtaci/kcp-Go) - KCP - 快速可靠的 ARQ 協議.
* [kcptun](https://github.com/xtaci/kcptun) - 超級簡單、快速的 udp 通道，基於KCP 協議
* [lhttp](https://github.com/fanux/lhttp) - 強大的 websocket 框架，可以更簡單的構建你自己的 IM 服務器*
* [linkio](https://github.com/ian-kent/linkio) - 接口讀寫速度模擬器
* [llb](https://github.com/kirillDanshin/llb) - 一個非常簡單但快速的後端代理服務器。對於快速重定向到預定義域名很有用，無內存分配，響應速度快
* [mdns](https://github.com/hashicorp/mdns) - 簡單的 mDNS (組播 DNS) 客戶端/服務器庫
* [mqttPaho](https://eclipse.org/paho/clients/Golang/) - Paho 客戶端提供了一個 MQTT 客戶端庫，用於通過TCP, TLS 或 WebSockets 和 MQTT broker 建立連接
* [portproxy](https://github.com/aybabtme/portproxy) - 簡單的 TCP 代理，加入了對CORS 的支持
* [publicip](https://github.com/polera/publicip) - publicip 庫會返回你的公網 ip 地址 (互聯網出口).
* [raw](https://github.com/mdlayher/raw) - raw 允許你在設備驅動層讀寫網絡接口的數據
* [sftp](https://github.com/pkg/sftp) - sftp 實現了https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt.中描述的 SSH 文件傳輸協議
* [ssh](https://github.com/gliderlabs/ssh) - 用於創建 SSH 服務器的高級 API (封裝crypto/ssh).
* [sslb](https://github.com/eduardonunesp/sslb) - 一個超簡單的負載均衡庫，僅僅是一個為了獲取一些性能目標的小項目
* [tcp_server](https://github.com/firstrow/tcp_server) - 一個用於快速創建 tcp 服務器的庫
* [utp](https://github.com/anacrolix/utp) - Go uTP 微傳輸協議的實現
* [water](https://github.com/songgao/water) - 簡單的 TUN/TAP 庫
* [winrm](https://github.com/masterzen/winrm) - Go WinRM 客戶端，用於在 Windows 設備上遠程執行命令
* [xtcp](https://github.com/xfxdev/xtcp) - TCP 服務器框架，支持同時全雙工通信。可以優雅的關閉，自定義協議

## OpenGL

_用於操作OpenGL的庫._

* [gl](https://github.com/Go-gl/gl) - OpenGL的 Go 語言接口
* [glfw](https://github.com/Go-gl/glfw) - GLFW 3 的 Go 語言接口
* [Goxjs/gl](https://github.com/Goxjs/gl) - Go 語言跨平台 OpenGL 接口(OS X, Linux, Windows, browsers, iOS, Android).
* [Goxjs/glfw](https://github.com/Goxjs/glfw) - Go 語言跨平台 glfw 庫，用於創建 OpenGL 上下文並接收事件
* [mathgl](https://github.com/Go-gl/mathgl) - Go 語言 3D 數學庫，專注於3D，受到 GLM 啟發

## ORM

_實現對象關係映射或數據映射技術的庫_

* [beeGo orm](https://github.com/astaxie/beeGo/tree/master/orm) - 一個強大的 Go 語言 orm 框架，支持 pq/mysql/sqlite3.
* [Go-pg](https://github.com/Go-pg/pg) - PostgreSQL ORM ，專注PostgreSQL 特定功能及性能
* [Go-store](https://github.com/Gosuri/Go-store) - 簡單快速的基於Redis 的鍵值對存儲庫
* [Gomodel](https://github.com/cosiner/Gomodel) - 輕量級、快速的、類 orm 庫，幫助你和數據庫進行交互
* [GoRM](https://github.com/jinzhu/Gorm) - 超棒的 Go 語言 ORM 庫，對開發者非常友好
* [Gorp](https://github.com/Go-Gorp/Gorp) - 關係持久的、類 orm 的 Go 語言庫
* [pop/soda](https://github.com/markbates/pop) - 數據庫遷移、創建、ORM 等等，支持 MySQL, PostgreSQL, 以及 SQLite.
* [QBS](https://github.com/coocood/qbs) - 利用結構體進行標準查詢，是一個 Go 語言 ORM
* [reform](https://github.com/Go-reform/reform) - 一個更優秀的 ORM，基於非空接口和代碼生成
* [SQLBoiler](https://github.com/volatiletech/sqlboiler) - ORM 生成器。為你的數據庫表單生成一個功能全面、快速的 ORM
* [upper.io/db](https://github.com/upper/db) - 通過使用封裝了成熟的數據庫驅動的適配器，來使用單一接口與不同的數據源進行交互
* [Xorm](https://github.com/Go-xorm/xorm) - 簡單、強大的 Go 語言 orm
* [Zoom](https://github.com/albrow/zoom) - 超快的數據存儲於查詢引擎，基於 Redis 構建

## 包管理

_用於進行包和依賴管理的庫_

* [dep](https://github.com/Golang/dep) - Go 語言依賴工具.
* [giGo](https://github.com/LyricalSecurity/giGo) - 類似 PIP 的依賴管理工具。支持私有倉庫和哈希
* [glide](https://github.com/Masterminds/glide) - 輕鬆管理你的 GO 語言包發佈者以及發佈包。 受到類似 Maven, Bundler, 和 Pip 這些工具的的啟發
* [Godep](https://github.com/tools/Godep) - Go 語言依賴工具，Godep 可以幫助開發者修復庫的依賴關係
* [Gom](https://github.com/mattn/Gom) - Go Manager
* [Goop](https://github.com/nitrous-io/Goop) - 簡單的依賴管理工具，手到 Bundler 的啟發
* [Gopm](https://github.com/gpmGo/Gopm) - Go 包管理器
* [Govendor](https://github.com/kardianos/Govendor) - Go 包管理器。 Go 語言 vendor 工具，兼容標準 vendor 文件
* [gpm](https://github.com/pote/gpm) -  Go 語言包管理工具
* [gvt](https://github.com/FiloSottile/gvt) - `gvt` 是一個簡單的發佈管理工具(aka Go15VENDOREXPERIMENT), 基於 gb-vendor.
* [johnny-deps](https://github.com/VividCortex/johnny-deps) - 極簡的依賴版本管理工具，使用 git
* [nut](https://github.com/jingweno/nut) - Go 語言依賴管理
* [VenGo](https://github.com/DamnWidget/VenGo) - 創建並管理可以導出的，隔離的 Go 語言虛擬環境

## 查詢語言

* [graphql](https://github.com/tmc/graphql) - graphql 解析器 + 實用工具
* [graphql](https://github.com/sevki/graphql) - Go 語言實現的 GraphQL
* [graphql](https://github.com/neelance/graphql-Go) - 專注於易用性的 GraphQL 服務器
* [graphql-Go](https://github.com/graphql-Go/graphql) - 為 Go 語言實現的 GraphQL
* [jsonql](https://github.com/elgs/jsonql) - JSON 查詢表達式庫

## 資源嵌入

* [esc](https://github.com/mjibson/esc) - 在 Go 語言程序中嵌入文件併為其提供 HTTP.FileSystem 接口
* [fileb0x](https://github.com/UnnoTed/fileb0x) - 一個用於在 Go 語言程序中嵌入文件的工具，專注於可定製化和易用性
* [Go-bindata](https://github.com/jteeuwen/Go-bindata) - 一個用於將文件轉換為可管理的 Go 語言代碼的工具
* [Go-embed](https://github.com/pyros2097/Go-embed) - 生成用於嵌入資源文件到庫或可執行文件的 Go 語言代碼
* [Go-resources](https://github.com/omeid/Go-resources) - 一個簡潔的 Go 語言資源嵌入工具
* [Go.rice](https://github.com/GeertJohan/Go.rice) - Go.rice 是一個讓你輕鬆使用 html,js,css,圖片以及模板這類資源的庫
* [statics](https://github.com/Go-playground/statics) - 將靜態資源嵌入到 Go 文件中，用於單獨二進制編譯+使用http.FileSystem + symlinks.
* [statik](https://github.com/rakyll/statik) - 將靜態文件嵌入到 Go 語言可執行文件中
* [templify](https://github.com/wlbr/templify) - 將外部目標文件嵌入到 Go 代碼中來創建單獨的二進制文件
* [vfsgen](https://github.com/shurcooL/vfsgen) - 生成一個 vfsdata.Go 文件，靜態實現了一個虛擬文件系統

## 科學及數據分析

_用於科學計算和數據分析的庫_

* [blas](https://github.com/ziutek/blas) - BLAS (基礎線性代數子程序 Linear Algebra Subprograms)的 Go 語言實現
* [chart](https://github.com/vdobler/chart) - 簡單的圖表繪圖庫。支持多種圖表類型
* [evaler](https://github.com/soniah/evaler) - 簡單浮點算數表達式求值器
* [ewma](https://github.com/VividCortex/ewma) - 指數移動加權平均值
* [geom](https://github.com/skelterjohn/geom) - 2D 幾何
* [Go-dsp](https://github.com/mjibson/Go-dsp) - 數字信號處理
* [Go-fn](https://github.com/ematvey/Go-fn) - 一些沒有包含在 math pkg 中的數學函數
* [Go-gt](https://github.com/ThePaw/Go-gt) - 圖論算法
* [Go.matrix](https://github.com/skelterjohn/Go.matrix) - 線性代數
* [Gocomplex](https://github.com/varver/Gocomplex) - 複數庫
* [Gofrac](https://github.com/anschelsc/Gofrac) - Go 語言分數庫，支持基本算術
* [Gohistogram](https://github.com/VividCortex/Gohistogram) - 數據流的近似直方圖
* [Gonum/mat64](https://github.com/Gonum/matrix) - 矩陣計算通用包。 mat64 提供了用於進行64位浮點基礎線性代數操作的功能
* [Gonum/plot](https://github.com/Gonum/plot) - Gonum/plot 提供了用於創建和繪製圖表的 API
* [Goraph](https://github.com/gyuho/Goraph) - 純 Go 語言編寫的圖論庫（數據結構，算法可視化）
* [Gostat](https://github.com/ematvey/Gostat) - 統計庫
* [graph](https://github.com/yourbasic/graph) - 包含基礎圖算法的庫
* [ode](https://github.com/ChristopherRabotin/ode) - 普通微分方程 (ODE) 求解器。支持擴展狀態及基於通道的疊代算法終止條件
* [pagerank](https://github.com/alixaxel/pagerank) - Go 語言實現的加權網頁排名（ PageRank）算法
* [PiHex](https://github.com/clayGod/PiHex) - 貝利-波爾溫-普勞夫公式（"Bailey-Borwein-Plouffe"）算法的實現，用於計算十六進制π
* [stats](https://github.com/montanaflynn/stats) - 統計庫，包含一些 Go 語言標準庫中漏掉的常用函數
* [streamtools](https://github.com/nytlabs/streamtools) - 通用圖形化工具，用於處理流數據
* [vectormath](https://github.com/spate/vectormath) - 給 Go 語言用的 Vectormath , 是對索尼的矢量數學庫中 C 語言函數的改寫,可以在 Bullet-2.79 源碼中找到 (當前不活躍)

## 安全

_可以幫助你增強應用程序安全性的庫_

* [acmetool](https://github.com/hlandau/acme) — ACME (Let's Encrypt) 客戶端工具，有自動延長功能.
* [BadActor](https://github.com/jaredfolkins/badactor) - 一個駐留在內存中的，應用驅動的監控程序，受 fail2ban 的啟發
* [Go-yara](https://github.com/hillu/Go-yara) - [YARA](https://github.com/plusvic/yara)的 Go 語言接口，號稱是 "對於惡意軟件研究者（以及其他人）來說是模式匹配的瑞士軍刀
* [leGo](https://github.com/xenolf/leGo) - 純 Go ACME 客戶端庫及命令行工具
* [memguard](https://github.com/awnumar/memguard) - 一個用於處理內存中敏感數據的 Go 語言庫
* [passlib](https://github.com/hlandau/passlib) - 不過時的密碼哈希庫
* [secure](https://github.com/unrolled/secure) - Go 語言 HTTP 中間件，為 Go 提供了一些安全功能
* [simple-scrypt](https://github.com/elithrar/simple-scrypt) - Scrypt 庫，具有簡單、易懂的 API，同時具有內置的自動校準功能
* [ssh-vault](https://github.com/ssh-vault/ssh-vault) - 利用 ssh 秘鑰加解密

## 序列化

_用於進行二進制序列化的庫和工具_

* [asn1](https://github.com/PromonLogicalis/asn1) - Asn.1 BER 及 DER 編碼庫
* [colfer](https://github.com/pascaldekloe/colfer) - 用於生成 Colfer 二進制格式代碼
* [Go-capnproto](https://github.com/glycerine/Go-capnproto) - Go 語言用的 Cap'n Proto 庫及解析器 
* [bambam](https://github.com/glycerine/bambam) - 用於 Go 語言生成 Cap'n Proto schemas 的生成器
* [Go-codec](https://github.com/uGorji/Go) - 高性能、多功能、規範化編碼解碼以及 rpc 庫， 用於 msgpack, cbor 和 json，支持基於運行時的 OR 碼生成
* [GoGoprotobuf](https://github.com/GoGo/protobuf) - Go 語言的 Protocol Buffer 庫
* [Goprotobuf](https://github.com/Golang/protobuf) - 通過庫和協議編譯器插件使 Go 語言支持 Google的 protocol buffers.
* [jsoniter](https://github.com/json-iterator/Go) -高性能，100% 兼容的"encoding/json" 替代品
* [mapstructure](https://github.com/mitchellh/mapstructure) - 用於對原生鍵值對進行解碼生成 Go 語言結構體
* [php_session_decoder](https://github.com/yvasiyarov/php_session_decoder) - 用於協同 PHP session 格式數據和 PHP 序列化／反序列化函數工作的go語言庫
* [structomap](https://github.com/tuvistavie/structomap) - 用於從靜態結構體簡單、動態的生成鍵值對的庫

## 服務器程序

* [algernon](https://github.com/xyproto/algernon) - HTTP/2 web 服務器，支持 Lua、Markdown、GCSS 和 Amber.
* [Caddy](https://github.com/mholt/caddy) - Caddy 是一個備選的 HTTP/2 web 服務器，配置簡單，使用方便。
* [consul](https://www.consul.io/) - Consul 是一個用於服務發現、監控和配置的工具
* [devd](https://github.com/cortesi/devd) - 開發者使用的本地 web 服務器
* [etcd](https://github.com/coreos/etcd) - 高可用性的鍵值存儲，用於分享配置和服務發現
* [minio](https://github.com/minio/minio) - Minio 是一個分佈式對象存儲服務器
* [nsq](http://nsq.io/) - 一個實時的分佈式消息平台
* [yakvs](https://github.com/sci4me/yakvs) - 小型化、網絡化、基於內存的鍵值存儲

## 模板引擎

_模板庫及工具_

* [ace](https://github.com/yosssi/ace) - Ace 是一個 Go 語言的 HTML 模板引擎，受到了 Slim 和 Jade 的啟發。 Ace 是對Gold的一種改進。
* [amber](https://github.com/eknkc/amber) - Amber 是一個優雅的模板引擎，受到 HAML 和 Jade的啟發
* [damsel](https://github.com/dskinner/damsel) - 標記語言，通過css選擇器實現了 html 框架 ，並可以通過 pkg html/template 等進行擴展
* [eGo](https://github.com/benbjohnson/eGo) - 輕量級模板語言，讓你可以使用 Go 語言來創建模板。模板會被轉化為 Go 語言並編譯
* [fasttemplate](https://github.com/valyala/fasttemplate) - 簡單快速的模板引擎。進行模板元素替換時，速度是[text/template](http://Golang.org/pkg/text/template/)的十倍
* [Gofpdf](https://github.com/jung-kurt/Gofpdf) - PDF 文檔生成器，支持文本，繪圖和圖片
* [grender](https://github.com/dannyvankooten/grender) - 對 html/template 進行了簡單的封裝，支持基於文件的模板可以利用其他模板文件進行擴展
* [hero](https://github.com/shiyanhui/hero) Hero 是一個趁手的、快速的、強大的 Go 語言模板引擎
* [jet](https://github.com/CloudyKit/jet) - Jet 模板引擎
* [kasia.Go](https://github.com/ziutek/kasia.Go) - 一個用於HTML 和其他文本文件的模板系統，使用go語言實現
* [liquid](https://github.com/osteele/liquid) - Go 語言實現的 Shopify Liquid 模板.
* [mustache](https://github.com/hoisie/mustache) - Go 語言實現的 Mustache 模板語言
* [ponGo2](https://github.com/flosch/ponGo2) - 類似 DjanGo 的模板引擎
* [quicktemplate](https://github.com/valyala/quicktemplate) - 快速、強大且易用的模板引擎。將模板轉化為 Go 語言併進行編譯
* [raymond](https://github.com/aymerick/raymond) - 使用 Go 語言實現的完整的 handlebars
* [GoRazor](https://github.com/sipin/Gorazor) - Go 語言的 Razor 視圖引擎
* [Soy](https://github.com/robfig/soy) -  Go 語言實現的谷歌閉包模板(也就是 Soy templates) , 參見[official spec](https://developers.Google.com/closure/templates/)
* [velvet](https://github.com/Gobuffalo/velvet) - 使用 Go 語言實現的完整的 handlebars

## 測試

_測試及用於生成測試數據的庫._

* 測試框架
    * [assert](https://github.com/Go-playground/assert) - 基礎斷言庫，用於對 Go 語言程序進行測試，提供了一些用於自定義斷言的代碼塊
    * [badio](https://github.com/cavaliercoder/badio) - Go 語言 `testing/iotest` 包的擴展
    * [baloo](https://github.com/h2non/baloo) - 表達性強、多功能的、端到端的HTTP API 測試工具
    * [bro](https://github.com/marioidival/bro) - 監控目錄中的文件並對其進行測試
    * [dbcleaner](https://github.com/khaiql/dbcleaner) - 清空數據庫用於測試，受到`database_cleaner` 的啟發
    * [dsunit](https://github.com/viant/dsunit) - 數據庫測試，針對 SQL、 NoSQL、 結構化文件.
    * [frisby](https://github.com/verdverm/frisby) - REST API 測試框架
    * [ginkGo](http://onsi.github.io/ginkGo/) - BDD 測試框架
    * [Go-carpet](https://github.com/msoap/Go-carpet) - 用於在終端中查看測試覆蓋率的工具
    * [Go-mutesting](https://github.com/zimmski/Go-mutesting) - Go 語言原代碼突變測試（Mutation testing ）
    * [Go-vcr](https://github.com/dnaeon/Go-vcr) - 記錄並重放 HTTP 交互，用於快速的、確定性的、準確的測試
    * [Goblin](https://github.com/franela/Goblin) - 類似 Mocha 的測試框架
    * [Gocheck](http://labix.org/Gocheck) - 更加高級的測試框架，用於替換 Gotest.
    * [GoConvey](https://github.com/smartystreets/Goconvey/) - BDD 風格的測試框架，具有 web 界面和計時刷新功能
    * [Godog](https://github.com/DATA-DOG/Godog) - 類似 Cucumber 或 Behat 的 BDD 框架
    * [Gofight](https://github.com/appleboy/Gofight) - 對 Go 語言的路由框架進行 API 測試
    * [Gomega](http://onsi.github.io/Gomega/) - 類似 Rspec 的 matcher/assertion 庫
    * [GoSpec](https://github.com/orfjackal/Gospec) - BDD 風格的測試框架
    * [Gospecify](https://github.com/stesla/Gospecify) - 支持 BDD 語法 。對於任何使用過 rspec 等庫的人來說應該非常熟悉
    * [Gosuite](https://github.com/pavlo/Gosuite) - 輕量級測試套，為 Go1.7's Subtests 帶來了setup/teardown 功能
    * [Hamcrest](https://github.com/rdrdr/hamcrest) - fluent framework for declarative Matcher objects that, when applied to input values, produce self-describing results.
    * [httpexpect](https://github.com/gavv/httpexpect) - 簡潔的、聲明式的、易用的端到端HTTP 及 REST API 測試
    * [restit](https://github.com/yookoala/restit) - 幫助編寫 RESTful API 整合測試的 Go 語言微型框架.
    * [testfixtures](https://github.com/Go-testfixtures/testfixtures) - 類似 Rails 的測試工具，用於測試數據庫應用
    * [Testify](https://github.com/stretchr/testify) - 對標準測試包的擴展
    * [wstest](https://github.com/posener/wstest) - Websocket 客戶端，用於對於 websocket HTTP.Handler 進行單元測試
* Mock  
    * [counterfeiter](https://github.com/maxbrunsfeld/counterfeiter) - 用於生成自包含 mock 對象的工具
    * [Go-sqlmock](https://github.com/DATA-DOG/Go-sqlmock) - Mock SQL ，用於測試數據庫交互
    * [Go-txdb](https://github.com/DATA-DOG/Go-txdb) - 基於單事物的數據庫驅動，主要用於測試目的
    * [Gock](https://github.com/h2non/Gock) - 多功能、易用 HTTP mock
    * [Gomock](https://github.com/Golang/mock) - 給 Go 語言用的 Mock框架
    * [Govcr](https://github.com/seborama/Govcr) - HTTP mock : 離線測試時記錄和重放瀏覽器的動作
    * [minimock](https://github.com/Gojuno/minimock) - Mock 生成器
    * [mockhttp](https://github.com/tv42/mockhttp) - Go HTTP.ResponseWriter 使用的 Mock 對象
* Fuzzing and delta-debugging/reducing/shrinking
    * [Go-fuzz](https://github.com/dvyukov/Go-fuzz) - 隨機化測試系統
    * [Gofuzz](https://github.com/Google/Gofuzz) - 用於生成隨機值來初始化 Go 語言對象的庫
    * [Tavor](https://github.com/zimmski/tavor) - 通用模糊測試框架
* Selenium 及瀏覽器控制工具  
    * [cdp](https://github.com/mafredri/cdp) - 類型安全的 Chrome debug協議的 Go 語言接口，可以用於瀏覽器或任何實現了該協議的其他待調試對象
    * [chromedp](https://github.com/knq/chromedp) - 用於驅動和測試 Chrome, Safari, Edge, Android Webviews, 以及其他支持 Chrome 調試協議的產品
    * [ggr](https://github.com/aandryashin/ggr) - 一個輕量級服務器，可以將 Selenium Wedriver 的請求路由或代理到多個 Selenium hubs.
    * [selenoid](https://github.com/aandryashin/selenoid) - Selenium hub 服務器的替代品，在容器中啟動瀏覽器

## 文本處理

_解析和操作文本的庫_

*   特殊格式

    * [allot](https://github.com/sbstjn/allot) - 占位符及通配符文本解析
    * [bbConvert](https://github.com/CalebQ42/bbConvert) - 將 bbCode 轉換為 HTML
    * [blackfriday](https://github.com/russross/blackfriday) - Markdown 解析器
    * [bluemonday](https://github.com/microcosm-cc/bluemonday) - HTML 清理工具
    * [editorconfig-core-Go](https://github.com/editorconfig/editorconfig-core-Go) - Go 語言用的Editorconfig 文件解析和操作庫
    * [enca](https://github.com/endeveit/enca) - [libenca](http://cihar.com/software/enca/)的極簡的 cGo 接口
    * [genex](https://github.com/alixaxel/genex) - 計算並展開正則表達式為所有匹配的字元串
    * [github_flavored_markdown](https://Godoc.org/github.com/shurcooL/github_flavored_markdown) - GitHub 風格的 Markdown 渲染器 (使用 blackfriday) ，支持代碼塊高亮以及可點擊的錨點
    * [Go-humanize](https://github.com/dustin/Go-humanize) - 時間、數字及內存大小格式化工具
    * [Go-nmea](https://github.com/adrianmo/Go-nmea) - NMEA 解析庫
    * [Go-pkg-rss](https://github.com/jteeuwen/Go-pkg-rss) - 這個庫可以讀取 RSS 以及 Atom feeds，並且提供了一種緩存機制，遵守 feed 標準。
    * [Go-runewidth](https://github.com/mattn/Go-runewidth) - 用於獲取字元或字元串固定寬度的函數
    * [Go-slugify](https://github.com/mozillazg/Go-slugify) - 生成漂亮的固定連結地址（slug），支持多種語言
    * [Go-vcard](https://github.com/emersion/Go-vcard) - 解析並且格式化vCard
    * [Gofeed](https://github.com/mmcdole/Gofeed) - 使用 Go 語言解析RSS 和 Atom
    * [Gographviz](https://github.com/awalterschulze/Gographviz) - 用以解析 Graphviz DOT 語言
    * [Gommon/bytes](https://github.com/labstack/Gommon/tree/master/bytes) - 格式化二進製為字元串
    * [Gonameparts](https://github.com/polera/Gonameparts) - 將人名解析為幾個獨立的部分
    * [Goq](https://github.com/andrewstuart/Goq) - 聲明式 HTML 編組，使用結構標籤和 jQuery 語法 (使用 GoQuery).
    * [GoQuery](https://github.com/PuerkitoBio/Goquery) - GoQuery 為 Go 語言帶來了一組類似 jQuery 的語法和功能
    * [Goregen](https://github.com/zach-klippenstein/Goregen) - 根據正則表達式生成隨機字元串
    * [Gotext](https://github.com/leonelquinteros/Gotext) - GNU gettext 工具
    * [guesslanguage](https://github.com/endeveit/guesslanguage) - 通過一個 unicode 文本來猜測該文本使用的語言
    * [inject](https://github.com/facebookGo/inject) - inject 提供來一個基於反射對注入器
    * [mxj](https://github.com/clbanning/mxj) - 將 XML 編解碼為 JSON 或 map[string]interface{}; 通過點分路徑和通配符來提取值。用於替代Replaces x2j 和 j2x 包.
    * [sh](https://github.com/mvdan/sh) - Shell 解析器及格式化工具
    * [slug](https://github.com/Gosimple/slug) - URL 友好的 slug 化工具，支持多種語言
    * [Slugify](https://github.com/avelino/slugify) - Go 語言靜態地址生成器，可以處理字元串
    * [toml](https://github.com/BurntSushi/toml) - TOML 配置格式 format (encoder/decoder with reflection).
*   工具

    * [Gotabulate](https://github.com/bndr/Gotabulate) - 使用 Go 語言簡單、美觀的打印表格數據
    * [kace](https://github.com/codemodus/kace) - 通用大小寫轉換工具
    * [parseargs-Go](https://github.com/nproc/parseargs-Go) - 字元串參數解析器，能夠理解引用及反斜杠
    * [parth](https://github.com/codemodus/parth) - URL 路徑分割解析
    * [radix](https://github.com/yourbasic/radix) - 快速的字元串排序算法
    * [xurls](https://github.com/mvdan/xurls) - 從文本中提取 URL

## 第三方 APIs

_用於訪問第三方 APIs 的庫_

* [amazon-product-advertising-api](https://github.com/ngs/Go-amazon-product-advertising-api) - [Amazon Product Advertising API](https://affiliate-program.amazon.com/gp/advertising/api/detail/main.html) 的 go 語言客戶端
* [anaconda](https://github.com/ChimeraCoder/anaconda) - Twitter 1.1 API 的 go 語言客戶端
* [aws-sdk-Go](https://github.com/aws/aws-sdk-Go) - AWS 提供的官方go語言 SDK
* [brewerydb](https://github.com/naegelejd/brewerydb) - 用於訪問 BreweryDB API的 Go 語言庫
* [cachet](https://github.com/andygrunwald/cachet) - [Cachet (open source status page system)](https://cachethq.io/)的 Go 語言客戶端
* [circleci](https://github.com/jszwedko/Go-circleci) - 用於和 with CircleCI's API 進行交互的 Go 語言客戶端
* [clarifai](https://github.com/samuelcouch/clarifai) - 用語和 Clarifai API 交互的 Go 語言庫
* [discordGo](https://github.com/bwmarrin/discordGo) - Discord Chat API 的 Go 語言接口
* [facebook](https://github.com/huandu/facebook) - 支持 Facebook Graph API 的庫
* [fcm](https://github.com/maddevsio/fcm) - Firebase Cloud Messaging 的 Go 語言庫
* [gads](https://github.com/emiddleton/gads) - Google Adwords 非官方 API
* [gami](https://github.com/bit4bit/gami) - Asterisk Manager Interface 的 Go 語言庫
* [gcm](https://github.com/Aorioli/gcm) - Google Cloud Messaging 庫
* [geo-Golang](https://github.com/codingsince1985/geo-Golang) - 用於與 [Google Maps](https://developers.Google.com/maps/documentation/geocoding/intro), [MapQuest](http://open.mapquestapi.com/geocoding/), [Nominatim](http://open.mapquestapi.com/nominatim/), [OpenCage](http://geocoder.opencagedata.com/api.html), [HERE](https://developer.here.com/rest-apis/documentation/geocoder), [Bing](https://msdn.microsoft.com/en-us/library/ff701715.aspx), [Mapbox](https://www.mapbox.com/developers/api/geocoding/), 及 [OpenStreetMap](https://wiki.openstreetmap.org/wiki/Nominatim) 地理編碼 / 反編碼 APIs 交互的庫
* [ghost](https://github.com/neuegram/ghost) - 用於和 Snapchat API 交互的庫
* [github](https://github.com/Google/Go-github) - 用於和 GitHub REST API v3 交互的庫
* [githubql](https://github.com/shurcooL/githubql) - 用於和GitHub GraphQL API v4 交互的庫
* [Go-imgur](https://github.com/koffeinsource/Go-imgur) - [imgur](https://imgur.com) 的 Go 語言客戶端
* [Go-jira](https://github.com/andygrunwald/Go-jira) - [Atlassian JIRA](https://www.atlassian.com/software/jira) 的 Go 語言客戶端
* [Go-marathon](https://github.com/gambol99/Go-marathon) - 用於和 Mesosphere's Marathon PAAS 交互的 Go 語言庫
* [Go-myanimelist](https://github.com/nstratos/Go-myanimelist) - 用於和 [MyAnimeList API](http://myanimelist.net/modules.php?Go=api)交互的庫
* [Go-telegraph](https://github.com/toby3d/Go-telegraph) - Telegraph 發佈平台 API 客戶端
* [Go-tgbot](https://github.com/olebedev/Go-tgbot) - 純 Go 語言的Telegram 機器人 API 封裝，通過 swagger 文件，基會話的路由和中間件
* [Go-trending](https://github.com/andygrunwald/Go-trending) - 用於獲取 Github 上面 [當前流行的代碼庫](https://github.com/trending) 及 [開發者](https://github.com/trending/developers)
* [Go-twitch](https://github.com/knspriggs/Go-twitch) - 用於和推特v3 API 進行交互的 Go 語言客戶端
* [Go-twitter](https://github.com/dghubble/Go-twitter) - 用於和推特v1.1 API 進行交互的 Go 語言客戶端
* [Go-unsplash](https://github.com/hbagdi/Go-unsplash) - [Unsplash.com](https://unsplash.com) API 的 Go 語言客戶端
* [Go-xkcd](https://github.com/nishanths/Go-xkcd) - xkcd API 的 Go 語言客戶端
* [Goamz](https://github.com/mitchellh/Goamz) - [Goamz](https://launchpad.net/Goamz) 的一個fork分支，添加了一些缺失的 API，用於調用特定的軟件包。
* [Golyrics](https://github.com/mamal72/Golyrics) - Golyrics 是一個 Go 語言庫，用於從 Wikia 上獲取歌詞
* [GoMusicBrainz](https://github.com/michiwend/Gomusicbrainz) - Go MusicBrainz WS2 客戶端
* [Google](https://github.com/Google/Google-api-Go-client) - 為go語言自動生成 Google api
* [Google-analytics](https://github.com/chonthu/Go-Google-analytics) - Google 分析報告的一個簡單的封裝
* [Google-cloud](https://github.com/GoogleCloudPlatform/gcloud-Golang) - Google Cloud APIs Go 語言客戶端庫
* [Google-email-audit-api](https://github.com/ngs/Go-Google-email-audit-api) - [Google G Suite Email Audit API](https://developers.Google.com/admin-sdk/email-audit/)的 Go 語言客戶端庫
* [Gostorm](https://github.com/jsgilmore/Gostorm) - GoStorm 是一個 Go 語言庫，實現了在 Go 語言裡面編寫 Spout 和 Bolt 的協議，用於和 Storm  shells 進行通信
* [Govkbot](https://github.com/nikepan/Govkbot) - 簡單的 Go [VK](https://vk.com) 機器人庫
* [hipchat](https://github.com/andybons/hipchat) - 這個項目實行了Hipchat API 的 Go 語言客戶端
* [hipchat (xmpp)](https://github.com/daneharrigan/hipchat) - 通過使用 XMPP 與 HipChat 進行通信的庫
* [Medium](https://github.com/Medium/medium-sdk-Go) - Medium OAuth2 API 的 sdk
* [meGos](https://github.com/andygrunwald/meGos) - 用於訪問 [Apache Mesos](http://mesos.apache.org/) 集群的客戶端
* [micha](https://github.com/onrik/micha) - 用於[Telegram bot api](https://core.telegram.org/bots/api)的go語言庫
* [minio-Go](https://github.com/minio/minio-Go) - go 語言 Minio 客戶端，用於 Amazon S3 兼容的雲存儲
* [mixpanel](https://github.com/dukex/mixpanel) - Mixpanel 是一個用於追蹤事件並發送 Mixpanel profile 的更新到 Mixpanel 的庫
* [patreon-Go](https://github.com/mxpv/patreon-Go) - Patreon API.
* [paypal](https://github.com/logpacker/paypalsdk) - PayPal 支付 API
* [playlyfe](https://github.com/playlyfe/playlyfe-Go-sdk) - Playlyfe Rest API 的 Go 語言 SDK
* [pushover](https://github.com/gregdel/pushover) - Pushover API 的 Go 語言封裝
* [rrdaclient](https://github.com/Omie/rrdaclient) - 用於接入 statdns.com API 的庫——RRDA API。通過HTTP協議進行 DNS查詢
* [shopify](https://github.com/rapito/Go-shopify) - 一個用於通過 Shopify API 進行增刪改查的 Go 語言庫
* [slack](https://github.com/nlopes/slack) - Slack API
* [smite](https://github.com/sergiotapia/smiteGo) - 對 Smite game API 的封裝
* [spotify](https://github.com/rapito/Go-spotify) - 用於接入 Spotify WEB API 的 Go 語言庫
* [steam](https://github.com/sostronk/Go-steam) - 用於與Steam服務器進行交互的庫
* [stripe](https://github.com/stripe/stripe-Go) - Stripe API 的 Go 語言客戶端
* [tbot](https://github.com/yanzay/tbot) - Telegram bot 服務器，有類似 net/http 的 api
* [telebot](https://github.com/tucnak/telebot) - go語言編寫的 Telegram bot 框架
* [telegram-bot-api](https://github.com/Syfaro/telegram-bot-api) - 簡潔的 Telegram bot 客戶端.
* [textbelt](https://github.com/dietsche/textbelt) - textbelt.com txt messaging API 的go語言客戶端
* [TheMovieDb](https://github.com/jbrodriguez/Go-tmdb) - 用於和 [themoviedb.org](https://themoviedb.org) 通信的一個簡單的 Go 語言軟件包
* [translate](https://github.com/poorny/translate) - Go 在線翻譯包
* [Trello](https://github.com/adlio/trello) - Trello API的 Go 語言封裝
* [tumblr](https://github.com/mattcunningham/gumblr) - Tumblr v2 API 的 Go 語言封裝
* [webhooks](https://github.com/Go-playground/webhooks) - GitHub 和 Bitbucket 的Webhook接收器
* [zooz](https://github.com/Gojuno/Go-zooz) - Zooz API 的 Go 語言客戶端

## 實用工具

_可以讓你的生活變得更簡單的實用工具._
* [abutil](https://github.com/bahlo/abutil) - 常用 Go 語言工具的集合
* [apm](https://github.com/topfreegames/apm) - Go 語言進程管理工具具有HTTP API.
* [boilr](https://github.com/tmrts/boilr) - 一個超快的命令行工具，用於從模板文件生成項目
* [circuitbreaker](https://github.com/rubyist/circuitbreaker) - Go 語言斷路器模式
* [clockwerk](http://github.com/onatm/clockwerk) - 使用簡單、流暢的語法來調度週期性任務
* [command](https://github.com/txgruppi/command) - 命令模式，支持線程安全的串列、並行調度
* [coop](https://github.com/rakyll/coop) - Go 語言中常見的並發流程速查表
* [copy-pasta](https://github.com/jutkko/copy-pasta) - 通用多工作站剪切板，使用類似 S3 的後端作為存儲
* [ctop](https://github.com/bcicen/ctop) - [類似Top](http://ctop.sh)的接口 (例如 htop) ，用於容器數據收集
* [Death](https://github.com/vrecan/death) - 利用信號管理應用程序的關閉
* [Deepcopier](https://github.com/ulule/deepcopier) - 結構體拷貝
* [delve](https://github.com/derekparker/delve) - Go 語言調試器
* [dlog](https://github.com/kirillDanshin/dlog) - 編譯時控制的日誌，讓你的 release 包變得更小而不需移除 debug 調用
* [excelize](https://github.com/Luxurioust/excelize) - 用於讀寫 Microsoft Excel (XLSX) 文件的庫
* [fastlz](https://github.com/digitalcrab/fastlz) - [FastLz](http://fastlz.org/) (免費，開源，可移植實時壓縮庫) 的一個封裝
* [filetype](https://github.com/h2non/filetype) - 通過數字簽名來推測文件類型
* [filler](https://github.com/yaronsumel/filler) - 使用 "fill" 標記來填充結構體的小工具
* [fzf](https://github.com/junegunn/fzf) - 命令行模糊查找工具
* [generate](https://github.com/Go-playground/generate) - 針對一個路徑或環境變數，遞歸的執行 Go generate，可以通過正則表達式來進行過濾
* [gentleman](https://github.com/h2non/gentleman) - 全功能、插件驅動的 HTTP 客戶端庫
* [git-time-metric](https://github.com/git-time-metric/gtm) - 簡單、無縫、輕量級的 Git 時間追蹤工具
* [GJSON](https://github.com/tidwall/gjson) - 一行代碼獲取 JSON
* [Go-astitodo](https://github.com/asticode/Go-astitodo) - 解析你 Go 語言代碼中的 TODOs（待辦事項） 
* [Go-bind-plugin](https://github.com/wendiGo/Go-bind-plugin) - Go:generate 工具，用於構建 Go 語言插件(1.8 only)，並對導出的符號進行包裝
* [Go-cron](https://github.com/rk/Go-cron) - 簡單的 Go 語言 Cron 庫，可以以不同的時間間隔來執行閉包或函數，從一秒到某年某月某日都可以。主要針對的是 Web 應用或者長期運行的守護進程
* [Go-debug](https://github.com/tj/Go-debug) - 條件調試日誌，用於 Go 語言庫和應用程序
* [Go-dry](https://github.com/ungerik/Go-dry) - DRY (don't repeat yourself)
* [Go-funk](https://github.com/thoas/Go-funk) - 現代 Go 語言工具庫，提供了很多有用的工具 (map, find, contains, filter, chunk, reverse, ...)
* [Go-httpheader](https://github.com/mozillazg/Go-httpheader) - 用於將結構體編碼進 http 頭的 Go 語言庫
* [Go-rate](https://github.com/beefsack/Go-rate) - Go 語言版本的限速器
* [Go-respond](https://github.com/nicklaw5/Go-respond) - 用於處理常見 HTTP JSON 響應的庫.
* [Go-sitemap-generator](https://github.com/ikeikeikeike/Go-sitemap-generator) - XML 網站地圖生成器
* [Go-torch](https://github.com/uber/Go-torch) - 為 Go 語言程序生成火焰圖
* [Go-trigger](https://github.com/sadlil/Go-trigger) - Go 語言全局事件觸發器，通過 id 和觸發器，在程序的任何地方註冊事件
* [Go-underscore](https://github.com/tobyhede/Go-underscore) - 一些有用的 Go 語言工具的集合
* [Goback](https://github.com/carlescere/Goback) - 一個 Go 語言的簡單的指數補償包
* [Godaemon](https://github.com/VividCortex/Godaemon) - 用於編寫守護進程的工具
* [Godropbox](https://github.com/dropbox/Godropbox) - 用於編寫 Go 語言服務／應用的庫，來自 Dropbox.
* [Gohper](https://github.com/cosiner/Gohper) - 多種能夠幫助你進行軟件開發的工具和模組
* [Gojq](https://github.com/elgs/Gojq) - 通過 Go 語言進行 JSON 查詢
* [Gojson](https://github.com/ChimeraCoder/Gojson) - 通過 JSON 自動生成 Go 語言結構體
* [Golarm](https://github.com/msempere/Golarm) - 告警（支持系統事件）
* [Golog](https://github.com/mlimaloureiro/Golog) - 簡單、輕量級的命令後工具，用於對你的計劃任務進行跟蹤
* [Gopencils](https://github.com/bndr/Gopencils) - 簡單小巧的 Go 語言庫，能夠很容易的使用各種 REST APIs.
* [Goplaceholder](https://github.com/michiwend/Goplaceholder) - 一個小巧的 Go 語言庫用於生成占點陣圖片
* [Goreleaser](https://github.com/Goreleaser/Goreleaser) - 儘可能快速的發佈 Go 語言二進制文件
* [Goreporter](https://github.com/wgliang/Goreporter) - 進行代碼靜態分析，單元測試，代碼檢視並生成代碼質量報告的工具
* [Goreq](https://github.com/franela/Goreq) - 簡潔的 Go 語言 http 請求庫
* [Goreq](https://github.com/smallnest/Goreq) - 更加簡化的 http客戶端，基於 Gorequest.
* [Gorequest](https://github.com/parnurzeal/Gorequest) - 簡化的 http 客戶端，具有豐富的特性
* [Goseaweedfs](https://github.com/linxGnu/Goseaweedfs) - conseilSeaweedFS 客戶端，幾乎具有全部的特性
* [Gotenv](https://github.com/subosito/Gotenv) - 從 `.env` 或者任何 `io.Reader`中加載環境變數
* [Goxlsxwriter](https://github.com/fterrag/Goxlsxwriter) - 用於操作 XLSX (Microsoft Excel) 文件的 libxlsxwriter 庫的 Go 語言接口
* [gpath](https://github.com/tenntenn/gpath) - 用於簡化結構體域訪問的庫
* [grequests](https://github.com/levigross/grequests) - 簡單優雅的 `net/HTTP` 封裝，緊隨 Python 的 requests 的步伐
* [gron](https://github.com/roylee0704/gron) - 使用簡單的 Go 語言 API 和 Gron 調度器創建定時任務
* [htcat](https://github.com/htcat/htcat) - 並行及流水線的 HTTP GET 工具
* [httpcontrol](https://github.com/facebookGo/httpcontrol) - httpcontrol 包，運行進行 HTTP 傳輸層超時和重傳控制
* [hub](https://github.com/github/hub) - 封裝了 git 命令，提供了額外的功能用於在終端中和 Github 進行交互
* [hystrix-Go](https://github.com/afex/hystrix-Go) - 實現 Hystrix 風格的、程序員預定義的 fallback 機制（熔斷）
* [immortal](https://github.com/immortal/immortal) - \*nix 跨平台 (與操作系統無關的)監控程序
* [intrinsic](https://github.com/mengzhuo/intrinsic) - 不需要編寫任何彙編代碼就能使用 x86 SIMD
* [JobRunner](https://github.com/bamzi/jobrunner) - 智能的、多功能的定時任務調度器，具有任務隊列和實時監控功能
* [jsonapi-errors](https://github.com/AmuzaTkts/jsonapi-errors) -  JSON API errors 的 Go 語言接口.
* [jsonf](https://github.com/miolini/jsonf) - 控制台工具，用於高亮及 JSON 查詢功能
* [jsonGo](https://github.com/ricardolonga/jsonGo) - 用於更加方便的構建 JSON 對象的 API
* [jsonhal](https://github.com/RichardKnop/jsonhal) - 一個簡單的 Go 語言軟件包，用於將自定義結構體轉換為 HAL 兼容的 JSON 響應
* [kazaam](https://github.com/Qntfy/kazaam) - 用於傳輸任意 JSON 文件的 API
* [lrserver](https://github.com/jaschaephraim/lrserver) - LiveReload 服務器
* [mc](https://github.com/minio/mc) - Minio Client 提供了一組工具，用於操作 Amazon S3 兼容雲存儲和文件系統
* [merGo](https://github.com/imdario/merGo) - 用於將結構體和map合併進 Go 語言的工具。對於配置默認值，避免雜亂的if語句很有幫助
* [minify](https://github.com/tdewolff/minify) - 快速壓縮 HTML, CSS, JS, XML, JSON 以及 SVG 文件格式
* [mmake](https://github.com/tj/mmake) - 現代 Make 工具
* [moldova](https://github.com/StabbyCutyou/moldova) - 基於輸入目標生成隨機數據的工具
* [mp](https://github.com/sanbornm/mp) - 簡單的命令行郵件解析器，當前支持標準輸入並輸出JSON.
* [mssqlx](https://github.com/linxGnu/mssqlx) - HA 客戶端，用於主-從 (或主-主) 數據庫，整合了簡單的、輕量級的輪詢調度負載均衡。基於 sqlx.
* [multitick](https://github.com/VividCortex/multitick) - 用於 aligned tickers 的多路復用
* [netbug](https://github.com/e-dard/netbug) - 遠程對你的服務進行性能分析
* [ngrok](https://github.com/inconshreveable/ngrok) - 創建到 localhost 的隧道
* [okrun](https://github.com/xta/okrun) - 當 Go 文件運行報錯時嘗試修復並運行
* [onecache](https://github.com/adelowo/onecache) - 支持多種後端存儲的緩存庫(Redis, Memcached, 文件系統等)
* [panicparse](https://github.com/maruel/panicparse) - 將類似的協程分組並對調用棧進行著色
* [peco](https://github.com/peco/peco) - 簡單的交互式過濾工具
* [pester](https://github.com/sethgrid/pester) - Go HTTP 客戶端，具有重傳，補償和並發功能
* [pm](https://github.com/VividCortex/pm) - 基於 HTTP API 的進程管理 (i.e. Goroutine) 
* [profile](https://github.com/pkg/profile) - 一個簡單的性能分析軟件包
* [rclient](https://github.com/zpatrick/rclient) - 可讀性良好、靈活、易用的 REST APIs 客戶端
* [realize](https://github.com/tockins/realize) - Go 語言構建系統，可以監控文件變化並重新加載。運行，構建，監控文件並支持自定義路徑
* [request](https://github.com/mozillazg/request) - Go 語言版的 HTTP Requests for Humans™.
* [rerate](https://github.com/abo/rerate) - 基於 Redis 的速率計數器和限速器
* [rerun](https://github.com/ivpusic/rerun) - 當源碼變化時，重新編譯並重新運行 Go 語言編寫的 app
* [resty](https://github.com/Go-resty/resty) - 簡單的 HTTP 和 REST 客戶端，受到 Ruby rest-client 的啟發
* [retry](https://github.com/kamilsk/retry) - 基於上下文的功能機制，反覆執行命令直到成功
* [robustly](https://github.com/VividCortex/robustly) - 有彈性的執行函數，遇到錯誤時捕獲並重新運行
* [scheduler](https://github.com/carlescere/scheduler) - 從容的進行 Cronjobs 任務調度
* [sling](https://github.com/dghubble/sling) - Go HTTP 請求構造器，用於 API 客戶端
* [spinner](https://github.com/briandowns/spinner) - 一個 Go 語言軟件包，提供多種選項，方便在終端中創建加載動畫
* [sqlx](https://github.com/jmoiron/sqlx) - 為內建的數據庫/sql 軟件包提供一組擴展
* [Storm](https://github.com/asdine/storm) - 一個用於 BoltDB 的簡單又強大的工具
* [Task](https://github.com/Go-task/task) - 簡單來講就是 "Make" 的替代品
* [toolbox](https://github.com/viant/toolbox) - 切片, map, multimap, 結構體, 函數,數據轉換工具。服務路由，宏求值和標記器
* [uGo](https://github.com/alxrm/uGo) - uGo 是一個切片工具箱，有著和 Go 語言一致的語法
* [UNIS](https://github.com/esemplastic/unis) - Go 語言字元串處理函數的通用架構
* [usql](https://github.com/knq/usql) - usql 是一個通用的命令行接口，用於操作 sql 數據庫
* [util](https://github.com/shomali11/util) - 收集了很多有用的函數
* [wuzz](https://github.com/asciimoo/wuzz) - 交互式命令行程序，用於進行 HTTP 檢查
* [xferspdy](https://github.com/monmohan/xferspdy) - Xferspdy 提供了二進制對比功能以及 Go 語言補丁庫
* [xlsx](https://github.com/tealeg/xlsx) - 簡化了在 Go 語言程序中讀取 xml 格式文件的操作

## 驗證

_用於驗證的庫_

* [Govalidator](https://github.com/asaskevich/Govalidator) - 數據驗證及清晰工具，用於字元串，數字， 數組切片及結構體
* [ozzo-validation](https://github.com/Go-ozzo/ozzo-validation) - 支持多種數據類型的驗證 (結構體，字元串，鍵值對，數組切片等等)，具有可配置、可擴展的驗證規則——使用常用代碼結構定義，而非結構體標籤
* [validate](https://github.com/markbates/validate) - 提供了一個用於為 Go 語言英語程序編寫驗證工具的框架
* [validator](https://github.com/Go-playground/validator) - Go 結構體及域驗證，包括：跨域、跨結構體, Map, 切片和數組

## 版本控制

_用於版本控制的庫_

* [gh](https://github.com/rjeczalik/gh) - 用於 GitHub Webhooks 的可編程服務器以及 net/HTTP 中間件
* [git2Go](https://github.com/libgit2/git2Go) - libgit2 的 Go 語言接口
* [Go-vcs](https://github.com/sourcegraph/Go-vcs) - 通過 Go 語言來操作和檢視 VCS 代碼倉庫
* [hGo](https://github.com/beyang/hGo) - HGo 是一個 Go 語言軟件包集合，提供了對本地 Mercurial 倉庫的讀取能力.

## 視頻

_用於操作視頻的庫_

* [gmf](https://github.com/3d0c/gmf) - FFmpeg av* 庫的 Go 語言接口.
* [Go-astisub](https://github.com/asticode/Go-astisub) - 使用 Go 語言操作字幕(.srt, .stl, .ttml, .webvtt, .ssa/.ass, teletext, .smi, etc.).
* [Goav](https://github.com/giorgisio/Goav) - 易用的 FFmpeg Go 語言接口
* [gst](https://github.com/ziutek/gst) - GStreamer 的 Go 語言接口
* [v4l](https://github.com/korandiz/v4l) - Linux 下使用的視頻截圖庫，Go 語言編寫

## Web 框架

_全棧 web 框架_

* [aah](https://aahframework.org) - 可擴展、高性能、快速發佈的 Go 語言 web 框架
* [Air](https://github.com/sheng/air) - 理想的 RESTful web 框架
* [BeeGo](https://github.com/astaxie/beeGo) - beeGo 是一個開源的、高性能的 Go 語言 web 框架
* [Buffalo](http://Gobuffalo.io) - 為 Go 語言帶來堪比 Rails 的高生產效率
* [Echo](https://github.com/labstack/echo) - 高性能、極簡的 Go 語言 web 框架
* [Fireball](https://github.com/zpatrick/fireball) - 感覺更加自然的 web 框架
* [Florest](https://github.com/jabong/florest-core) - 高性能的、基於工作流的 REST API 框架
* [Gem](https://github.com/Go-gem/gem) - 簡單快速的 web 框架，對 REST API 很友好
* [Gin](https://github.com/gin-Gonic/gin) - Gin 是一個 Go 語言編寫的 web 框架！提供了一組類似 martini 的 API ，具有更好的性能（40倍）。如果你需要高性能和高生產率，這個框架很適合你
* [Gizmo](https://github.com/NYTimes/gizmo) - 紐約時報正在使用對微服務工具集
* [Go-json-rest](https://github.com/ant0ine/Go-json-rest) - 快速、簡單的創建 RESTful JSON API.
* [Go-relax](https://github.com/codehack/Go-relax) - 具有可插拔組建的框架，用於構建 RESTful API's.
* [Go-rest](https://github.com/ungerik/Go-rest) - Go 語言 REST 框架中的小惡魔
* [Goa](https://github.com/raphael/Goa) - 用於開發微服務的框架，基於 Ruby 的 Praxis 的設計
* [Golf](https://github.com/dinever/Golf) - Golf 是一個快速、簡單、輕量級的 Go 語言微型 web 框架。具有強大的功能且沒有標準庫以外的依賴
* [Gondola](https://github.com/rainycape/Gondola) - 用於快速編寫高性能網站的框架
* [Gongular](https://github.com/mustafaakin/Gongular) - 快速 Go web 框架，支持輸入映射／驗證以及依賴注入
* [Macaron](https://github.com/Go-macaron/macaron) - Macaron 是一個高效的模組化設計的web框架
* [manGo](https://github.com/paulbellamy/manGo) - ManGo 是一個模組化 web 應用框架，受到 Rack 和 PEP333 的啟發
* [Microservice](https://github.com/clayGod/microservice) - 用於創建微服務的框架，使用 Go 語言編寫
* [neo](https://github.com/ivpusic/neo) - 是一個極小且快速的 Go 語言 web 框架，具有及其簡單的 API
* [Resoursea](https://github.com/resoursea/api) - 用於快速編寫基於資源對服務的 REST 框架
* [REST Layer](http://rest-layer.io) - 用於構建在數據庫之上構建 REST/GraphQL API 且大多數配置都可以通過代碼完成
* [Revel](https://github.com/revel/revel) - go語言高生產率框架
* [rex](https://github.com/Goanywhere/rex) - Rex 是一個用於進行模組化開發的庫，基於Gorilla/mux 完全兼容大多數的 `net/HTTP`.
* [sawsij](https://github.com/jaybill/sawsij) - 輕量級、開源的 web 框架，用於構建高性能、數據驅動的web應用
* [tanGo](https://github.com/lunny/tanGo) - 微型的、支持插件的 web 框架
* [tigertonic](https://github.com/rcrowley/Go-tigertonic) - 用於構建 JSON web 服務的 Go 語言框架，受到 Dropwizard 的啟發
* [traffic](https://github.com/pilu/traffic) - 受到 Sinatra 啟發的 Go 語言 web 框架
* [utron](https://github.com/gernest/utron) - 輕量級的go語言 MVC 框架
* [violetear](https://github.com/nbari/violetear) - Go HTTP 路由庫
* [YARF](https://github.com/yarf-framework/yarf) - 快速的微型框架，用於快速、簡單地構建 REST APIs 以及 web 服務
* [Zerver](https://github.com/cosiner/zerver) - Zerver 是一個富有表達力的、模組化的、全功能的 RESTful 框架.

## Windows

* [d3d9](https://github.com/Gonutz/d3d9) - Direct3D9 的 Go 語言接口
* [Go-ole](https://github.com/Go-ole/Go-ole) - 為 Go 語言實現的 Win32 OLE

## XML

_Libraries and tools for manipulating XML._

* [Go-pkg-xmlx](https://github.com/jteeuwen/Go-pkg-xmlx) - 對 Go 語言 XML 標準庫的擴展。維護來一個節點樹，允許前進和後退瀏覽以及一些簡單的單／多節點搜索函數
* [XML-Comp](https://github.com/xml-comp/xml-comp) - 簡單的命令行 XML 比較工具，可以生成關於目錄、文件和標籤對差異信息
* [xmlwriter](https://github.com/shabbyrobe/xmlwriter) - Procedural XML 生成 API 基於 libxml2 的 xmlwriter 模組.
* [xpath](https://github.com/antchfx/xpath) - XPath 庫
* [xquery](https://github.com/antchfx/xquery) - XQuery 使你可以從 HTML/XML文檔中抽取數據和求值，使用 XPath 表達式

### 中間件

#### 中間件

* [CORS](https://github.com/rs/cors) - 非常方便地向你的 api 中添加 CORS 功能
* [formjson](https://github.com/rs/formjson) - 將 JSON 輸入看作說一個標準的表單 POST 來處理
* [Limiter](https://github.com/ulule/limiter) - 超級簡單的限速中間件
* [Tollbooth](https://github.com/didip/tollbooth) - HTTP 請求限速中間件
* [XFF](https://github.com/sebest/xff) - 處理 `X-Forwarded-For` 頭的中間件

#### 用於創建 HTTP 中間件的庫

* [alice](https://github.com/justinas/alice) - 用於連接中間件的庫，簡單無痛苦
* [catena](https://github.com/codemodus/catena) - HTTP.Handler wrapper catenation (和chain具有相同的 API ).
* [chain](https://github.com/codemodus/chain) - Handler wrapper chaining with scoped data (net/context-based "middleware").
* [Go-wrap](https://github.com/Go-on/wrap) - 小型中間件庫，用於net/HTTP.
* [Gores](https://github.com/alioygur/Gores) - 用於處理 HTML, JSON, XML 等。對於 RESTful APIs 很有用。
* [interpose](https://github.com/carbocation/interpose) - 極簡的 net/HTTP 中間件
* [muxchain](https://github.com/stephens2424/muxchain) - 用於net/HTTP的輕量級中間件
* [negroni](https://github.com/urfave/negroni) - 符合語言習慣的 HTTP 中間件庫
* [render](https://github.com/unrolled/render) - 用於輕鬆渲染 JSON, XML, 及 HTML 模板響應的庫
* [rye](https://github.com/InVisionApp/rye) - 小型 Go 語言中間件庫 ，支持 JWT, CORS, Statsd, 及 Go 1.7 context
* [stats](https://github.com/thoas/stats) - Go 語言中間件，用於存儲web應用的多種信息
* [Volatile](https://github.com/volatile/core) - 極簡的go語言中間件技術棧，強調靈活性、優秀實踐及簡潔代碼

### 路由

* [alien](https://github.com/gernest/alien) - 輕量級、超快速的 HTTP 路由，來自外星科技
* [Bone](https://github.com/Go-zoo/bone) - 輕量級快速 Fast HTTP Multiplexer.
* [Bxog](https://github.com/clayGod/Bxog) - 為go語言編寫的簡單快速點 HTTP 路由。能夠配合多種不同複雜度、長度和嵌套的路由工作。同時它能夠根據接收到的參數創建 URL
* [chi](https://github.com/Go-chi/chi) - 小巧、快速、具有豐富表達力的 HTTP 路由，基於net/context.
* [fasthttprouter](https://github.com/buaazp/fasthttprouter) - 從`httprouter` fork出來的高性能路由，是第一個適配 `fasthttp`的路由
* [Gocraft/web](https://github.com/Gocraft/web) - Mux 及中間件包
* [Goji](https://github.com/Goji/Goji) - Goji 是一個極簡的、靈活的HTTP 請求數據分選器，支持 `net/context`.
* [GoRouter](https://github.com/vardius/Gorouter) - GoRouter 是一個服務器/API 微型框架、HTTP 請求路由 router, 數據分選器，提供了支持`net/context`的中間件
* [Gowww/router](https://github.com/Gowww/router) - 超快的HTTP 路由，完全兼容 net/HTTP.Handler 接口.
* [httprouter](https://github.com/julienschmidt/httprouter) - 高性能路由。使用這個庫和標準http處理工具可以構建一個非常高性能大web框架
* [httptreemux](https://github.com/dimfeld/httptreemux) - 高速，靈活，基於樹的 HTTP 路由。受到了 httprouter 的啟發
* [lars](https://github.com/Go-playground/lars) - 樹一個輕量級、快速、可擴展、零分配的HTTP路由，用於創建定製化的框架
* [medeina](https://github.com/imdario/medeina) - Medeina是一個HTTP路由樹，基於 HttpRouter 。基於 Roda 和 Cuba.
* [mux](https://github.com/Gorilla/mux) - 強大的 URL 路由和分發庫
* [ozzo-routing](https://github.com/Go-ozzo/ozzo-routing) - 一個極快的go語言http路由，支持正則路由匹配。完全支持創建 RESTful APIs.
* [pat](https://github.com/bmizerany/pat) - Sinatra 風格的模式 muxer ，用於go語言 net/http庫，由 Sinatra的作者編寫。
* [pure](https://github.com/Go-playground/pure) - 是一個輕量級http路由，嚴格符合標準"net/HTTP"實現
* [Siesta](https://github.com/VividCortex/siesta) - 具有可組合性的框架，用於編寫中間件和 handlers
* [vestiGo](https://github.com/husobee/vestiGo) - 高性能、獨立的、符合 HTTP 標準的 URL 路由，用於構建go語言web應用
* [xmux](https://github.com/rs/xmux) - 高性能 muxer，基於 `httprouter` ，支持 `net/context`
* [zeus](https://github.com/daryl/zeus) - 非常簡單快速的http路由

# 工具

_Go語言軟件及插件_

## 代碼分析

* [apicompat](https://github.com/bradleyfalzon/apicompat) - 檢測一個go語言項目最近的變化，用於監測不能向後兼容的改動
* [dupl](https://github.com/mibk/dupl) - 用於檢測重複代碼的工具
* [errcheck](https://github.com/kisielk/errcheck) - Errcheck 是一個用於檢測go語言程序中未處理錯誤的程序
* [gcvis](https://github.com/davecheney/gcvis) - 實時地將 Go 語言垃圾回收進行可視化
* [Go Metalinter](https://github.com/alecthomas/Gometalinter) - Metalinter 會自動應用全部的靜態分析工具，並生成形式一致的分析報告
* [Go-checkstyle](https://github.com/qiniu/checkstyle) checkstyle是一個代碼風格檢查工具，類似 java checkstyle 。這個工具就是受到 java checkstyle 和 Golint 的啟發
* [Go-cleanarch](https://github.com/roblaszczak/Go-cleanarch) - Go-cleanarch 用於檢查代碼是否符合簡潔架構的相關法則，比如依賴法則以及你的Go語言項目中各個庫的交互情況
* [Go-outdated](https://github.com/firstrow/Go-outdated) - 這是一個命令行程序，用於顯示過時的庫
* [Goast-viewer](https://github.com/yuroyoro/Goast-viewer) - 基於 Web 的 Golang AST 可視化工具.
* [GoCover.io](http://Gocover.io/) - GoCover.io 可以查看任何go語言軟件包的代碼覆蓋率
* [Goimports](https://Godoc.org/Golang.org/x/tools/cmd/Goimports) - 用於自動修復，添加，刪除你的 Go 語言項目的 import
* [GoLint](https://github.com/Golang/lint) - Golint 是一個針對 Go 語言源碼的 lint 工具
* [Golint online](http://Go-lint.appspot.com/) - 使用golint對GitHub, Bitbucket 以及 Google Project Hosting上面的 Go 語言源文件進行靜態分析
* [Goreturns](https://sourcegraph.com/github.com/sqs/Goreturns) - 添加零值 return 語句以符合函數返回值類型
* [Gosimple](https://github.com/dominikh/Go-tools/tree/master/cmd/Gosimple) - Gosimple 是一個針對 Go 語言的lint工具，專注於簡化代碼
* [Gostatus](https://github.com/shurcooL/Gostatus) - 命令行工具，查看當前 Go 語言軟件包倉庫的狀態
* [interfacer](https://github.com/mvdan/interfacer) - 可以提供接口類型建議的 Lint 工具
* [lint](https://github.com/surullabs/lint) - 將lint作為go語言測試的一部分來執行
* [staticcheck](https://github.com/dominikh/Go-tools/tree/master/cmd/staticcheck) - staticcheck is `Go vet` on steroids, applying a ton of static analysis checks you might be used to from tools like ReSharper for C#.
* [unconvert](https://github.com/mdempsky/unconvert) - 從go語言代碼中移除不必要的類型轉換
* [unused](https://github.com/dominikh/Go-tools/tree/master/cmd/unused) - unused 會檢查 Go 語言代碼中沒有用到的常量，變數，函數和類型
* [validate](https://github.com/mccoyst/validate) - 自動驗證結構體類型

## 編輯器插件

* [Go plugin for JetBrains IDEs](https://plugins.jetbrains.com/plugin/9568-Go) - JetBrains IDEs 使用的 Go 語言插件
* [Go-lang-idea-plugin](https://github.com/Go-lang-plugin-org/Go-lang-idea-plugin) (廢棄) - IntelliJ (JetBrains) IDEA 之前使用的插件，現在已經被上面的官方插件所取代
* [Go-mode](https://github.com/dominikh/Go-mode.el) - GNU/Emacs的 Go 語言模式
* [Go-plus](https://github.com/joefitzgerald/Go-plus) - 供Atom 使用的自動補全、格式化、語法檢查、lint 及 Vetting 的軟件包
* [Goclipse](https://github.com/GoClipse/Goclipse) - Eclipse 的 Go 語言插件
* [Gocode](https://github.com/nsf/Gocode) - go語言自動補全
* [GoSublime](https://github.com/DisposaBoy/GoSublime) - SublimeText 2 使用的 Go 語言插件，支持代碼補全以及一些類似 IDE 的特性
* [velour](https://github.com/velour/velour) - acme 編輯器使用的 IRC 客戶端
* [vim-compiler-Go](https://github.com/rjohnsondev/vim-compiler-Go) - Vim插件，在保存時高亮語法錯誤
* [vim-Go](https://github.com/fatih/vim-Go) - Vim 使用的 Go 語言開發插件
* [vscode-Go](https://github.com/Microsoft/vscode-Go) - Visual Studio Code (VS Code) 使用的一個擴展，為 Go 語言提供了支持
* [Watch](https://github.com/eaburns/Watch) - 當文件變動時，在 acme 窗口中執行命令

## Go 語言工具

* [colorGo](https://github.com/songgao/colorGo) - 對 `Go` 命令進行了封裝，用於為`Go build`的輸出結果添加顏色
* [depth](https://github.com/KyleBanks/depth) - 通過分析導入的庫，將某個包的依賴關係用樹狀結構進行顯示
* [gb](https://getgb.io/) - 一個簡單易用的基於項目的構建工具，用於 Go 語言
* [Go-callvis](https://github.com/TrueFurby/Go-callvis) - 使用 dot 語言將你的 Go 語言程序函數調用關係可視化
* [Go-pkg-complete](https://github.com/skelterjohn/Go-pkg-complete) - Bash 代碼補全，用於Go 和 wGo.
* [Go-swagger](https://github.com/Go-swagger/Go-swagger) - 為 Go 語言實現的Swagger 2.0， Swagger 是一個簡單但強大的工具，用於展示你的 RESTful API.
* [OctoLinker](https://github.com/OctoLinker/browser-extension) - 使用 github 的瀏覽器插件 OctoLinker 高效瀏覽 Go 語言文件
* [rts](https://github.com/galeone/rts) - RTS（是response to struct的縮寫）用於根據服務器的響應生成 Go 語言結構體

## 軟件包

_使用 Go 語言編寫的軟件_

### DevOps 工具

* [aptly](https://github.com/smira/aptly) - aptly 是一個 Debian 庫管理工具
* [aurora](https://github.com/Luxurioust/aurora) - 跨平台、基於web的 Beanstalkd 隊列服務器控制台
* [awsenv](https://github.com/soniah/awsenv) - 加載 Amazon (AWS) 環境變數作為 profile 文件
* [Banshee](https://github.com/eleme/banshee) - 異常檢測系統，用於週期性數據測量
* [bombardier](https://github.com/codesenberg/bombardier) - 快速的、跨平台的HTTP 基準工具.
* [bosun](https://github.com/bosun-monitor/bosun) - 時間序列告警框架
* [doGo](https://github.com/liudng/doGo) - 監控源文件中的變化並自動編譯和執行
* [drone-jenkins](https://github.com/appleboy/drone-jenkins) - 觸發下游 Jenkins 任務， 可以通過二進制文件、 docker 或者 Drone CI來使用
* [drone-scp](https://github.com/appleboy/drone-scp) - 通過 SSH 拷貝文件及可執行程序,可以通過二進制文件、 docker 或者 Drone CI來使用
* [Dropship](https://github.com/chrismckenzie/dropship) - 通過 cdn 部署代碼的工具
* [easyssh-proxy](https://github.com/appleboy/easyssh-proxy) - 一個用於通過 ssh 遠程執行命令以及通過`ProxyCommand` 來進行 SCP 下載
* [Gitea](https://github.com/Go-gitea/gitea) - Gogs的fork，完全社區驅動
* [Go Metrics](https://github.com/rcrowley/Go-metrics) - Coda Hale 的 Metrics library的 Go 語言接口: https://github.com/codahale/metrics.
* [Go-selfupdate](https://github.com/sanbornm/Go-selfupdate) - 讓你的 Go 語言程序可以自我更新
* [Gobrew](https://github.com/cryptojuice/Gobrew) - Gobrew 讓你可以在不同版本的 Go 語言之間輕鬆切換
* [Godbg](https://github.com/sirnewton01/Godbg) - 基於 Web 的前端 gdb 應用程序
* [Gogs](https://Gogs.io/) - 自我託管的Git服務
* [Gonative](https://github.com/inconshreveable/Gonative) - 為 Go 語言創建可以在多平台進行交叉編譯的工具，使用 CGo-enabled 標準庫
* [Govvv](https://github.com/ahmetalpbalkan/Govvv) - 對“Go build”進行了封裝，用於輕鬆的向 Go 語言二進制文件中添加版本信息
* [Gox](https://github.com/mitchellh/Gox) - 非常簡單的 Go 語言交叉編譯工具
* [Goxc](https://github.com/laher/Goxc) - Go 語言構建工具，專注於交叉編譯和打包
* [grapes](https://github.com/yaronsumel/grapes) - 一款輕量級工具，用於通過 ssh 發送命令
* [GVM](https://github.com/moovweb/gvm) - GVM 提供了用於管理 Go 語言版本的接口
* [Hey](https://github.com/rakyll/hey) - Hey 是一個微型程序，用於向 web 應用發送一些載荷
* [kala](https://github.com/ajvb/kala) - 極簡、現代的、高效的任務調度
* [kubernetes](https://github.com/kubernetes/kubernetes) - 來自 Google 的容器集群管理器
* [Moby](https://github.com/moby/moby) - 為容器生態系統創建的一個合作項目，用於構建基於容器的系統
* [Mora](https://github.com/emicklei/mora) - REST 服務器，用於獲取 MonGoDB 文件和元數據
* [ostent](https://github.com/ostrost/ostent) - 收集並顯示系統數據，可以作 Graphite 和／或 InfluxDB 的中繼
* [Packer](https://github.com/mitchellh/packer) - Packer 通過單一的配置文件，為不同的平台創建獨立機器鏡像
* [Pewpew](https://github.com/bengadbois/pewpew) - 靈活的 HTTP 命令行壓力測試 工具
* [Rodent](https://github.com/alouche/rodent) - Rodent 幫助你管理 Go 語言版本，項目病追蹤依賴
* [s3Gof3r](https://github.com/rlmcpherson/s3Gof3r) - 為了從 Amazon S3中高速存取大型對象而特別優化的庫
* [Scaleway-cli](https://github.com/scaleway/scaleway-cli) - 通過命令行來管理 BareMetal 服務器 (和使用 Docker 一樣容易).
* [sg](https://github.com/ChristopherRabotin/sg) - 對一組 HTTP 端點 (比如 ab)進行了基準測試， with possibility to use the reponse code and data between each call for specific server stress based on its previous response.
* [StatusOK](https://github.com/sanathp/statusok) - 監控你的網站和 REST APIs。如果你的服務器掛了或是響應時間超過預期，則會通過 Slack, E-mail 來通知你
* [Vegeta](https://github.com/tsenart/vegeta) - HTTP 加載測試工具和庫
* [webhook](https://github.com/adnanh/webhook) - 允許用戶創建 HTTP 端點，在服務器上執行命令
* [Wide](https://wide.b3log.org/login) - 基於 Web 的 IDE，為使用 Go 語言的團隊設計
* [winrm-cli](https://github.com/masterzen/winrm-cli) - 命令行工具，可以遠程在 windows 機器上執行命令

### 其他軟件

* [borg](https://github.com/crufter/borg) - 基於終端的搜索引擎，用於搜索 bash 代碼 片段
* [boxed](https://github.com/tejo/boxed) - 基於Dropbox 的博客引擎
* [Cherry](https://github.com/rafael-santiaGo/cherry) - Go 語言實現的一個微型網絡聊天服務器
* [Circuit](https://github.com/Gocircuit/circuit) - Circuit 是一個可編程的 PaaS 以及 IaaS,用於管理、發現以及編排各種雲端應用的服務及主機
* [Comcast](https://github.com/tylertreat/Comcast) - 模擬不佳的網絡連接
* [confd](https://github.com/kelseyhightower/confd) - 使用 etcd 或 consul 的模板及數據管理本地應用的配置文件
* [DDNS](https://github.com/skibish/ddns) - 個人 DDNS 客戶端，使用 Digital Ocean DNS 作為後端
* [Docker](http://www.docker.com/) - 一個為開發者和系統管理員提供的分佈式應用開放平台
* [Documize](https://github.com/documize/community) - 現代維基百科軟件，可以繼承 SaaS 工具提供的數據
* [fleet](https://github.com/coreos/fleet) - 分佈式初始化系統
* [Go Package Store](https://github.com/shurcooL/Go-Package-Store#Go-package-store-) - 一個可以顯示你的 GoPATH 路徑下 Go 軟件包的更新的應用
* [Gocc](https://github.com/Goccmack/Gocc) - Gocc 是一個用 Go 語言編寫的 Go 語言編輯器工具集
* [GoDocTooltip](https://github.com/diankong/GoDocTooltip) - 一個Chrome 瀏覽器擴展，可以在瀏覽 Go 語言文檔時以工具提示的方式顯示函數的描述信息
* [Gogland](https://jetbrains.com/Go) - 跨平台、全功能 Go 語言整合開發環境
* [Gor](https://github.com/buger/Gor) - Http 流量複製工具，用於將生產環境的流量在開發環境實施重現
* [hsync](http://ambrevar.bitbucket.org/hsync/) - 文件系統同步工具
* [huGo](http://GohuGo.io/) - 快速、現代的靜態 web 引擎
* [ipe](https://github.com/dimiro1/ipe) - 開源 Pusher 服務器，Go 語言編寫，兼容 Pusher 客戶端，由 Go 語言編寫
* [JayDiff](https://github.com/yazgazan/jaydiff) - Go 語言編寫的JSON對比工具
* [Juju](https://jujucharms.com/) - 服務部署及編排工具，，支持 EC2, Azure, Openstack, MAAS 等等
* [Leaps](https://github.com/jeffail/leaps) - 結對編程服務，使用操作變換來避免衝突。
* [limetext](http://limetext.org/) Lime Text 是一個強大又優雅的編輯器，主要使用 Go 語言開發，意在成為 Sublime Text的繼承者。
* [LiteIDE](https://github.com/visualfc/liteide) - LiteIDE 是一個簡單、開源、跨平台的 Go 語言 IDE
* [mockingjay](https://github.com/quii/mockingjay-server) - 偽 HTTP 服務器，通過單一配置文件創建消費驅動。同時你還可以讓服務器搞點事情，以進行更加符合現實情況的性能測試
* [myLG](https://github.com/mehrdadrad/mylg) - Go 語言編寫的命令行網絡診斷工具
* [naclpipe](https://github.com/unix4fun/naclpipe) - 簡單的基於NaCL EC25519 的加密管道工具
* [nes](https://github.com/fogleman/nes) - Go 語言編寫的任天堂娛樂系統(NES)模擬器
* [orange-cat](https://github.com/noraesae/orange-cat) - Go 語言編寫的 Markdown 預覽工具
* [peg](https://github.com/pointlander/peg) - Peg（Parsing Expression Grammar）是一個 Packrat parser generator 的實現
* [Postman](https://github.com/zachlatta/postman) - 一個批量發送郵件的命令行工具
* [restic](https://github.com/restic/restic) - 解耦備份程序
* [rkt](https://github.com/coreos/rkt) - App 容器運行時，整合了初始化系統，和其他容器兼容，比如 Docker，並且支持其他執行引擎，例如 KVM
* [Seaweed File System](https://github.com/chrislusf/seaweedfs) - 快速、簡單、可擴展的分佈式文件系統，具有O(1)的磁碟查找效率
* [shell2http](https://github.com/msoap/shell2http) - 通過 HTTP 服務器執行 shell 命令行(用於原型驗證或遠程控制).
* [snap](https://github.com/intelsdi-x/snap) - 強大的遙測框架
* [Stack Up](https://github.com/pressly/sup) - Stack Up 是一個超級簡單的開發工具，就好比是服務器網絡的 ‘make’ 工具
* [syncthing](https://syncthing.net/) - 開源、去中心化的文件同步工具和協議
* [Tenyks](https://github.com/kyleterry/tenyks) - 面向服務的 IRC 機器人，使用 Redis 和 JSON 來發送消息
* [toto](https://github.com/blogcin/ToTo) - Go 語言編寫的簡單代理服務器，可以和瀏覽器一起使用
* [toxiproxy](https://github.com/shopify/toxiproxy) - 模擬網絡和系統狀態的代理，用於自動化測試
* [tsuru](https://tsuru.io/) - 可擴展的、開源的 SAAS 軟件
* [vFlow](https://github.com/VerizonDigital/vflow) - 高性能、可擴展、可靠的 IPFIX, sFlow 和 Netflow 集合.
* [websysd](https://github.com/ian-kent/websysd) - 基於 web 的進程管理工具(類似 Marathon 或 Upstart).
* [wellington](https://github.com/wellington/wellington) - Sass 項目管理工具， 通過支持一些功能（例如Compass）擴展了這門語言

# 資源

_可以找到新的 Go 語言庫和軟件的地方_

## 基準測試

* [autobench](https://github.com/davecheney/autobench) - 用於比較各個不同版本 Go 語言之間的性能的框架
* [Go-benchmark-app](https://github.com/mrLSD/Go-benchmark-app) - 強大的 HTTP 基準測試工具，整合來 Аb, Wrk, Siege 工具。收集來統計數據以及多種參數用於基準測試和結果比較
* [Go-benchmarks](https://github.com/tylertreat/Go-benchmarks) - 一些基準程序的大雜燴。用於比較一些語言特性以及它們的替代方法.
* [Go-HTTP-routing-benchmark](https://github.com/julienschmidt/Go-HTTP-routing-benchmark) - Go HTTP 請求路由基準和比較
* [Go-type-assertion-benchmark](https://github.com/hgfischer/Go-type-assertion-benchmark) - 對在 Go 語言中使用斷言的兩種方法進行了性能測試
* [Go-web-framework-benchmark](https://github.com/smallnest/Go-web-framework-benchmark) - Go web 框架基準
* [Go_serialization_benchmarks](https://github.com/alecthomas/Go_serialization_benchmarks) - Go 語言序列化方法基準測試
* [Gocostmodel](https://github.com/PuerkitoBio/Gocostmodel) - Go 語言基礎操作基準測試
* [Golang-micro-benchmarks](https://github.com/amscanne/Golang-micro-benchmarks) - 一些go語言微基準測試的集合，目的是比較各種語言特性。
* [Golang-sql-benchmark](https://github.com/tyler-smith/Golang-sql-benchmark) - 對一些流行的 Go database/SQL 工具進行基準測試
* [Gospeed](https://github.com/feyeleanor/GoSpeed) - Go 語言微型基準測試工具，用於測試語言結構的速度
* [kvbench](https://github.com/jimrobinson/kvbench) - 鍵值數據庫基準測試
* [skynet](https://github.com/atemerev/skynet) - Skynet 1M 線程微基準
* [speedtest-resize](https://github.com/fawick/speedtest-resize) - 比較了 Go 語言的多種圖片縮放算法

## 會議

* [Capital Go](http://www.capitalGolang.com) - 美國華盛頓
* [dotGo](http://www.dotGo.eu) - 法國巴黎
* [GoCon](http://Gocon.connpass.com/) - 日本東京
* [GolangUK](http://Golanguk.com/) - 英國倫敦
* [GopherChina](http://Gopherchina.org) - 中國上海
* [GopherCon](http://www.Gophercon.com/) - 美國丹佛
* [GopherCon Brazil](https://Gopherconbr.org) - 巴西弗洛里亞諾波利斯
* [GopherCon Dubai](http://www.Gophercon.ae/) - 迪拜
* [GopherCon India](http://www.Gophercon.in/) - 印度普納
* [GopherCon Singapore](https://Gophercon.sg) - 新加坡豐樹商業城
* [GothamGo](http://GothamGo.com/) - 美國紐約

## E-Books

* [A Go Developer's Notebook](https://leanpub.com/GoNotebook/read)
* [An Introduction to Programming in Go](http://www.Golang-book.com/)
* [Build Web Application with Golang](https://www.gitbook.com/book/astaxie/build-web-application-with-Golang/details)
* [Building Web Apps With Go](https://www.gitbook.com/book/codegangsta/building-web-apps-with-Go/details)
* [Go Bootcamp](http://Golangbootcamp.com)
* [GoBooks](https://github.com/dariubs/GoBooks) - Go 語言書籍列表
* [Learning Go](https://www.miek.nl/downloads/Go/Learning-Go-latest.pdf)
* [Network Programming With Go](https://jan.newmarch.name/Go/)
* [The Go Programming Language](http://www.Gopl.io/)
* [Web Application with Go the Anti-Textbook](https://github.com/thewhitetulip/web-dev-Golang-anti-textbook/)

## Twitter

* [@Golang](https://twitter.com/Golang)
* [@Golang_news](https://twitter.com/Golang_news)
* [@Golangflow](https://twitter.com/Golangflow)
* [@Golangweekly](https://twitter.com/Golangweekly)

## 網站

* [Awesome Go @LibHunt](https://Go.libhunt.com) - Your Go-to Go Toolbox.
* [Awesome Remote Job](https://github.com/lukasz-madon/awesome-remote-job) - 一個發佈遠程工作的列表。上面有很多人都在尋找 Go 語言程序員
* [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) - 彙集了其他 Awesome 系列列表的聚合列表
* [Flipboard - Go Magazine](https://flipboard.com/section/the-Golang-magazine-bVP7nS) - 彙集了 Go 語言的教程和文章
* [Go Blog](http://blog.Golang.org) - Go 語言官方博客
* [Go Challenge](http://Golang-challenge.org/) - 通過解題來學習 Go 語言，同時獲得專家們的反饋
* [Go Forum](https://forum.Golangbridge.org) - 討論 Go 的論壇.
* [Go In 5 Minutes](https://www.Goin5minutes.com/) - 5 分鐘分享如何做好一件事
* [Go Projects](https://github.com/Golang/Go/wiki/Projects) - Go 語言社區 wiki 列表中的項目
* [Gocryforhelp](https://github.com/ninedraft/Gocryforhelp) - 彙集了一些需要幫助的 Go 語言項目。一個開始你的開源之路的好地方
* [Godoc.org](https://Godoc.org/) - 開源 Go 語言軟件包的文檔庫.
* [Golang Flow](http://Golangflow.io) - 不斷更新的博客、新聞、軟件等等
* [Golang News](https://Golangnews.com) - 關於 Go 語言編程的一些連結.
* [Golang-graphics](https://github.com/mholt/Golang-graphics) - 關於 Go 語言的圖片及藝術作品
* [Golang-nuts](https://groups.Google.com/forum/#!forum/Golang-nuts) - Go 郵件列表
* [Google Plus Community](https://plus.Google.com/communities/114112804251407510571) - Go 語言愛好者的 Google+ 社區
* [Gowalker.org](https://Gowalker.org) - Go 語言項目 API 文檔
* [r/Golang](https://www.reddit.com/r/Golang) - Go 語言新聞
* [Trending Go repositories on GitHub today](https://github.com/trending?l=Go) - 一個尋找 Go 語言新庫和軟件的好地方

### 教程

* [A Tour of Go](http://tour.Golang.org/) - 一個交互式的 Go 語言教程
* [Build web application with Golang](https://github.com/astaxie/build-web-application-with-Golang) - Go 語言電子書，講解如何編寫一個 web 應用
* [Building Go Web Applications and Microservices Using Gin](https://semaphoreci.com/community/tutorials/building-Go-web-applications-and-microservices-using-gin) - 學習 Gin 以及瞭解如何使用 Gin 幫你減少模板代碼並建立一個請求處理流水線
* [Go By Example](https://Gobyexample.com/) - 通過帶註解的常式幫助你動手實踐學習 Go 語言
* [Go Cheat Sheet](https://github.com/a8m/Go-lang-cheat-sheet) - Go 參考手冊
* [Go database/sql tutorial](http://Go-database-sql.org/) - 介紹數據庫及 sql
* [Golangbot](https://Golangbot.com/learn-Golang-series/) - Go 語言初學者教程
* [How to Use Godog for Behavior-driven Development in Go](https://semaphoreci.com/community/tutorials/how-to-use-Godog-for-behavior-driven-development-in-Go) - 學習使用 Godog — 一個行為驅動型開發框架，用於構建和測試 Go 語言應用
* [Working with Go](https://github.com/mkaz/working-with-Go) - 為有經驗的程序員提供的 Go 語言教程
