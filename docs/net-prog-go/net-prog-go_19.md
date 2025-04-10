# 第十五章：索引

请注意，索引链接指向每个术语的大致位置。

A

地址解析协议（ARP），26

亚马逊网络服务（AWS）Lambda。*参见* AWS（亚马逊网络服务）Lambda

ARP（地址解析协议），26

ASN（自治系统号），33–34

自治系统号。*参见* ASN（自治系统号）

AWS（亚马逊网络服务）Lambda，333–340

命令行接口，333–335

配置，333–335

安装，333

编译、打包和部署，339–340

创建 Lambda 函数，336–338

创建角色，335–336

测试 Lambda 函数，340

Azure Functions。*参见* 微软 Azure Functions

B

带宽，6–7

与延迟的对比，7

`big` 包。*参见* `math/big` 包

比特，9–10

边界网关协议（BGP），34

广播，25–26

`bufio` 包，74，76–78

`Scanner` 结构，74，76–78

`bytes` 包，79，83–86，89，109–114，120，122–123，126–131，133，146–147，149，151–153，179–181，188–189，253，255，260，265，299–302，306，320，325

`Buffer` 结构，85–86，89，122，126，128–129，180–181，299–301，306

`Equal()`，110，112，114，147，151，153，255，265

`HasPrefix()`，325

`NewBuffer()`，123，127，130

`NewBufferString()`，189

`NewReader()`，83，127–128，133

`Repeat()`，147

`Split()`，325

C

Caddy，217–239

自动 HTTPS，237–238

从源代码构建，220

配置，220–224

适配器，225–226

管理端点，220

修改，实时，222–224

遍历，222

使用配置文件，224

下载，219

扩展，224–232

配置适配器，225–226

注入模块，231–232

中间件，226–230

Let’s Encrypt 集成，218

反向代理，219，232–238

图表，219

CDN（内容分发网络），7，16

证书固定，247，252–255，292

无类域间路由（CIDR），20–22

云函数。*参见* Google Cloud Functions

内容分发网络（CDN），7，16

`context` 包，57–62，65–66，69，107–111，113，144–146，148–150，152，177–178，183，213，249–250，253，260，286–287，290–291，293

`WithCancel()`，59，66，69，109，111，113，146，150，152，178，253，260

`Canceled` 错误，59–62

`WithDeadline()`，58，60–62

`DeadlineExceeded` 错误，58，61–62，177

`crypto/ecdsa` 包，256–257

`GenerateKey()`，257

`crypto/elliptic` 包，256–257

`P256()`，257

`crypto/rand` 包，75，256，258

`Int()`，256

`Read()`，75

`Reader` 变量，256

`crypto/sha512` 包，137

`Sum512_256()`，137

`crypto/tls` 包，245–251，253–255，260–264

`crypto/x509` 包，253–254，256–260，262–263，292

`Certificate` 结构，256–257，262

`CreateCertificate()`，258

密钥使用，257，262

`ExtKeyUsageClientAuth` 常量，257，262

`ExtKeyUsageServerAuth` 常量，257

`MarshalPKCS8PrivateKey()`，259

`NewCertPool()`，254，260，262，292

`VerifyOptions` 结构，262–263

`crypto/x509/pkix` 包，256–257

`Name` 结构，257

D

分布式拒绝服务（DDOS）攻击，34

国防高级研究计划局（DARPA），12

分隔数据，从网络读取。*参见* `bufio` 包，`Scanner` 结构

DHCP（动态主机配置协议），14

分布式拒绝服务（DDOS）攻击，34

DNS（域名系统），34–41

域名解析，34–35

域名解析器，35

隐私和安全考虑，40–41

资源记录，35–40

地址（A），36

规范名称（CNAME），38

邮件交换（MX），38–39

名称服务器（NS），37

指针（PTR），39

权威起始（SOA），37

文本（TXT），39–40

DNS over HTTPS（DoH），41

DNS over TLS（DoT），41

DNSSEC（域名系统安全扩展），41

DoH（DNS over HTTPS），41

域名系统。*参见* DNS（域名系统）

域名系统安全扩展（DNSSEC），41

DoT（DNS over TLS），41

动态缓冲区，读取，79–86

动态主机配置协议（DHCP），14

E

`ecdsa` 包。*参见* `crypto/ecdsa` 包

椭圆曲线，247

`elliptic` 包。*参见* `crypto/elliptic` 包

`encoding/binary` 包，79−85，120，122–123，126–130

`BigEndian` 常量，80–83，85，122–123，126–130

`Read()`，80–83，123，127–130

`Write()`，80–81，85，122，126，128–129

`encoding/gob` 包，278–279

`NewDecoder()`，279

`NewEncoder()`，279

`encoding/json` 包，179–180，225–226，228，277，342–343

`Marshal()`，226，343

`NewDecoder()`，179，277，343

`NewEncoder()`，180，277

`Unmarshal()`，228

`encoding/pem` 包，256，258–259，270

`Block` 结构体，258

`Encode()`，258

外部路由协议，34

F

`filepath` 包。*参见* `path/filepath` 包

固定缓冲区，读取，74–76

`flag` 包 96–97，135，137，157–158，211，232–233，256，271–272，276，288–290，292–293，317，320–321，323

`Arg()`，97，276，293

`Args()`，137，158，276，293

`CommandLine` 变量，157，272，290

`Output()`，157，272，290

`Duration()`，96

`Int()`，96

`NArg()`，97

`Parse()`，97，135，137，158，211，233，256，276，288，292，323

`PrintDefaults()`，96，137，157，272，290

`String()`，135，211，233，256，317，321

`StringVar()`，272，288，290

`Usage()`，97

分片。*参见* UDP（用户数据报协议），分片

G

全局路由前缀（GRP），27–28

Gob

解码。*参见* `encoding/gob` 包

编码。*参见* `encoding/gob` 包

序列化对象，*参见* 序列化对象，Gob

Google 云函数，341–346

定义云函数，342–344

部署云函数，344–345

启用计费和云函数，342

安装软件开发工具包，341–342

测试云函数，345–346

GRP（全局路由前缀），27–28

gRPC，284–294

客户端，289–294

连接服务，284–286

服务器，286–289

H

处理程序，193–202

提前连接截止时间，68–70

依赖注入，200–202

实现 `http.Handler` 接口，198–200

测试，195–196

写入响应，196–198

心跳，64–70

十六进制四元组，26–28

`html/template` 包，194

HTTP（超文本传输协议），10，23，41，165–215

客户端，165–184

默认客户端，174–175

来自客户端的请求，167–170

来自服务器的响应，170–172

请求-响应周期，172–173

服务器端，187-215

Go HTTP 服务器的结构，188

Caddy。*参见* Caddy

`http` 包。*参见* `net/http` 包

`httptest` 包。*参见* `net/http/httptest` 包

HTTP/1。*参见* 超文本传输协议（HTTP）

HTTP/2 服务器推送，209–214

超文本传输协议（HTTP）。*参见* HTTP（超文本传输协议）

I

IANA（互联网号码分配局），23，28，35

ICMP（互联网控制消息协议），31–32，96，98

目标不可达，31

回显，32

回显回复，32

分片，检查，115–116

重定向，32

超时，32

IETF（互联网工程任务组），26

仪器化，316–326

计数器，317–318

量规，318–319

直方图和总结，319–320

HTTP 服务器，仪器化，320–326

互联网号码分配局（IANA），23，28，35

互联网控制消息协议。*参见* ICMP（互联网控制消息协议）

互联网工程任务组 (IETF)，26

互联网协议（IP），12，18

互联网服务提供商（ISP），7

进程间通信 (IPC)，141

`io` 包，54–55，63–66，70，74–84，87–96，126，176，179–180，182，189，194，196，198，207，255，273，277–279，283，297–298，301–302，306–307，314–315，324

`Copy()`，87–89，92，126，176，180，182，194，198，207，314，324

`CopyN()`，89，126

`EOF` 错误，54–55，63–64，70，75，78，88，90–91，94，126，255

`MultiWriter()`，87，93–96，297–298

`TeeReader()`，87，93–96

`ioutil` 包。*参见* `io/ioutil` 包

`io/ioutil` 包，135，137，146，149，152，175，179，183，188，190，194，198–199，203–204，207，209，253–254，260，283，289，292，302，309，312，314–315，321，324–325，330–331

`Discard` 变量，175，179，194，198，207，314，324

`ReadAll()`，183，190，194，199，204，209，283，325，331

`ReadFile()`，135，137，254，260，292

`TempDir()`，146，149，152，309，315

IP（互联网协议），12，18

IPC（进程间通信），141

IPsec，31

IPv4 地址，18–26

主机 ID，19–20

localhost，23

网络 ID，19–22

网络前缀，20–22

子网，20

IPv6 地址，28–33

地址类别，28

任播地址，29–30

多播地址，29

单播地址，28

相对于 IPv4 的优势，30

接口 ID，27–28，30–31

简化，27

子网 ID，27–28

子网，28

J

JSON

编码和解码，179–180，225–226，228，277，342–343

使用与之序列化对象，276–278

K

保活消息，99，175，192

L

Lambda。*参见* AWS（亚马逊 Web 服务）Lambda

延迟，7

减少延迟，7

与带宽的比较，7

Let’s Encrypt，与 Caddy 的集成，218

延迟，99–100

`log` 包，93–94，131，135，155，157，201，211，232，256，271，288–289，297–302，321，242，249

`Ldate` 常量，297

等级，300–301

`Lmsgprefix` 常量，299

`Lshortfile` 常量，201，297，299–300

`LstdFlags` 常量，297

`Ltime` 常量，297

`New()`，94，201，297，299–300

lumberjack。*参见* zap 日志记录器，日志轮换

M

MAC（媒体访问控制）地址，10，24

`math/big` 包，256

`Int` 类型，256

`NewInt()`，256

最大传输单元（MTU），115–116

mDNS（多播 DNS），40

媒体访问控制 (MAC) 地址，10，24

度量标准。*参见* 仪器

Microsoft Azure Functions，346–353

命令行接口，346–347

配置，347

安装，346–347

自定义处理程序，348–353

创建，348–349

定义：349–350

部署，351–352

本地测试，350–351

在 Azure 上测试，353

安装核心工具，347

中间件，202–206

保护敏感文件，204–206

超时慢客户端，203–204

`mime/multipart` 包，179，181

`NewWriter()`，181

监控网络流量，89–92

MTU（最大传输单元），115–116

多播 DNS（mDNS），40

多播，23，106

多路复用器，207–209

N

NAT（网络地址转换），24

`net` 包，51–70，73–75，77，84–103，107–117，131–134，143–153，155，156，158–159，189，192，221，248，250–252，257，262，270，288，313，322

绑定，51–52

`Conn` 接口，52–54，56，73–74，77，87，89–92，98–99，102，107，113–115，144，146，156，159，252，270，322

`SetDeadline()`，62–63，69，74，114，252

`SetReadDeadline()`，62，74，133

`SetWriteDeadline()`， 62, 74

`Dial()`， 54, 63, 69, 75, 77, 85, 88, 91–92, 95, 113–115, 134, 147–148, 152–153

`DialContext()`， 58–61

`Dialer` 结构体, 56–60, 248

`DialTimeout()`， 56–58, 97

`Error` 接口， 55–58, 63, 86–87, 97, 133

`Listen()`， 51–54, 60, 62, 68, 75, 77, 84, 90–91, 94, 145, 189, 192, 250, 288, 322

`Listener` 接口， 51–52, 189, 250–251

`ListenPacket()`， 107–111, 113, 117, 131, 143, 146, 148–150

`ListenUnix()`， 143, 146, 149, 158–159

`LookupAddr()`， 262

`OpError` 结构体， 55

`PacketConn` 接口， 107–110, 113–115, 117, 131–132, 149

`ParseIP()`， 257

`ResolveTCPAddr()`， 98–99

`SplitHostPort()`， 313

`TCPConn` 结构体, 89, 98–101

`UnixConn` 结构体， 155–156, 159

`net/http` 包, 168, 171, 173–174

`Client` 结构体, 190, 246, 324

`Get()`，174，176–177，180，185，314，325

`Head()`，174，176，185

`Post()`，176，181，185

`Error()`，180，194–195，197–199，202，205，229

`FileServer()`，204–206，212，236

`FileSystem` 接口，204，206

`Handle()`，200–201

`HandlerFunc()`，177，180，193–195，199–203，205，207，212，233，245，313–314，323

`Handler` 接口，193–195，198–205，207，215，226，227，309，313–315，321

`NewRequest()`，190

`NewRequestWithContext()`，177–178，183

`Pusher` 接口，212–213

`Request` 结构体，176，179，193–196，198–203，205，207–208，212，227，229，233，245，313–314，321

持久化 TCP 连接，禁用，178–179

超时，取消，176–178

`Response` 结构体，174，177，180–181，183，190，204，209，246–247，314，324–325

请求体，关闭，175–176

`ResponseWriter` 接口，176，179，193–196，198–203，205，207，212，227，229，233，245，312–314，321

`WriteHeader()`，180，196，203，207，245

`ServeMux` 结构体，207–208，212，233，323

`Server` 结构体，189，191–192，195，213，233，322

连接状态，322

超时设置，191–192

TLS 支持，添加，192–193

`StripPrefix()`，205–206，212

`TimeoutHandler()`，189，200，203–204

`Transport` 结构体，246–247，324，326

默认传输，324

`net/http/httptest` 包，177，180，196–197，203，205，209，245–246，314

`NewRecorder()`，196–197，203，205，209

`NewRequest()`，196–197，203，205，209

`NewServer()`，177，180，314

`NewTLSServer()`，245–246

`ResponseRecorder` 结构体，196

网络地址转换（NAT），24

网络错误。*参见* `net` 包，`Error` 接口

网络拓扑，3–6

总线，4

菊花链，4

混合型，6

网状，5–6

点对点，4

环，5

星型，5

半字节，26

O

字节，18

开放系统互联（OSI）参考模型，7–12

封装，10

数据报, 12

帧, 12

帧检查序列（FCS）, 12

水平通信, 10–11

消息体, 10

数据包, 12

有效载荷, 10

段, 12

服务数据单元（SDU）, 10

层次, 8–9

应用层（层 7）, 8

数据链路层（层 2）, 9

网络层（层 3）, 9

物理层（层 1）, 9

表示层（层 6）, 9

会话层（层 5）, 9

传输层（层 4）, 9

`os` 包, 93, 96–97, 137, 143, 146–150, 152, 157–158, 179, 182, 211, 213, 232–233, 256, 258, 271–273, 289–290, 299, 302, 304, 310–312, 315, 349

`Args` 切片, 96, 137, 157, 272, 290

`Chmod()`, 143, 147, 150, 152

`Chown()`, 143

`Create()`, 258, 273, 311

`Exit()`, 97, 304, 315

`Getpid()`, 146, 150, 152

`IsNotExist()`, 272

`LookupEnv()`, 349

`Open()`, 182, 272

`OpenFile()`, 258

`Remove()`, 148, 311

`RemoveAll()`, 146, 149, 152, 310, 315

`Signal` 类型, 158, 213, 233

`Stat()`, 272

`TempDir()`, 158

OSI。 *参见* 开放系统互联参考模型（OSI）

P

`path` 包, 204, 211, 302

`Clean()`, 205

`path/filepath` 包，146，149–150，152，157–158，179，182，212，271–272，289–290，310，315

`Base()`，157，182，272，290

`Join()`，146，150，152，158，212，310，315

`pem` 包。*参见* `encoding/pem` 包

ping TCP 端口，96–98

`pkix` 包。*参见* `crypto/x509/pkix` 包

端口，23

通过 HTTP 发送数据，179–184

带有文件附件的多部分表单，181–184

协议缓冲区，280–284

代理网络数据，87–93

R

`rand` 包。*参见* `crypto/rand` 包

接收缓冲区，连接集，100–101

`reflect` 包，78，85

`DeepEqual()`，78，85

请求评论（RFC），15

路由，17，32–33

S

扫描定界数据，76–78

序列化对象，270–284

Gob，278–280

JSON，276–278

协议缓冲区，280–284

传输。*参见* gRPC

简单邮件传输协议（SMTP），13

SLAAC（无状态地址自动配置），30–31

套接字地址，23–25，106–107，142–144，221–222，238

`sort` 包，198–199

`Strings()`，199

无状态地址自动配置（SLAAC），30–31

`strconv` 包，271，275，289，291–292

`Atoi()`，275，291–292

`strings` 包，120，124，130，198–199，205，228–229，245–246，253，256–257，260，262–263，271，274，276，289，291，293

`Contains()`，246，253，263

`HasPrefix()`，205，229

`Join()`，199，276，293

`Split()`，205，229，257，262，274，291

`ToLower()`，124，276，293

`TrimRight()`，123–124，130

`TrimSpace()`，274，291

结构化日志。*参见* zap 日志器

子域，35

T

TCP（传输控制协议），8，11–14，45–102

标志，47–50

确认（ACK），47–50

完成（FIN），50

重置（RST），51

选择性确认（SACK），48

同步（SYN），47–48

握手，47

最大段生命周期，50

接收缓冲区，48

可靠性，46

序列号，47–48

滑动窗口，49

终止，50

传输层，14

窗口大小，48–49

TCP/IP 模型，12–15

端到端原则，12

层，13–15

应用，13

互联网，14

链接，15

传输，14

临时错误，55，86，97–98，102

TFTP（简单文件传输协议），119–139

通过 UDP 下载文件，135–138

服务器实现，131–135

处理读取请求，132–134

启动，携带负载，135

类型，120–130

确认，128–129

数据包，124–127

错误包，129–130

读取请求（RRQ），121–124

`time` 包， 56，58–60，62–63，65–70，87，96–97，113–114，131，133，174，176，179，181，188，202–203，211，232，245，249，252–253，255–257，302–303，308，321，323，349

`NewTimer()`, 65

`Parse()`, 174

`Round()`, 67，174

`Since()`, 67，69–70，97，321

`Sleep()`, 58–59，87，97，203，255，308

`Truncate()`, 69–70

超时错误，55，57–58，63–64，133

TLS（传输安全层），41，192–193，212–214，241–266，288–289，292–293

证书授权机构，243–244

客户端，245–248

推荐配置，247

证书固定，252–255

完全前向保密，243

如何攻破 TLS，244

叶证书，263

双向 TLS 认证，255–265

生成认证证书，256–259

实现, 259–265

服务器端, 249–252

推荐配置, 251

`tls` 包。*参见* `crypto/tls` 包

顶级域, 35

拓扑。*参见* 网络拓扑

传输控制协议。*参见* TCP（传输控制协议）

传输安全层 (TLS), 41, 192–193, 212–214, 241–266, 288–289, 292–293

微不足道文件传输协议。*参见* TFTP（微不足道文件传输协议）

类型-长度-值编码, 79–86

U

用户数据报协议（UDP）, 14, 105–117, 119–120, 131–136, 139, 144, 148, 150–151, 221

分片, 115–117

最大传输单元。*参见* MTU（最大传输单元）

数据包结构, 106

发送和接收数据, 107–115

监听传入数据, 110–112

传输层, 14

单播, 25

统一资源定位符 (URL), 165–167

Unix 域套接字, 141–161

认证, 154–160

对等凭证, 154–156

使用 Netcat 进行测试, 159–160

绑定, 143

更改所有权和权限, 143–144

类型, 144–154

`unix` 流套接字, 144–148

`unixgram` 数据报套接字, 148–151

`unixpacket` 序列数据包套接字, 151–154

`unix` 包, 154–156

`GetsockoptUcred()`, 155–156

URL（统一资源定位符）, 165–167

用户数据报协议。*参见* UDP（用户数据报协议）

W

写入缓冲区, 连接集, 100–101

X

`x509` 包。*参见* `crypto/x509` 包

Z

zap 日志记录器, 301–316

编码器配置, 302–303

编码器使用，305

日志记录器选项，303–304

日志轮转，315–316

多重输出和编码，306–307

按需日志记录，309–312

采样，307–309

广泛的事件日志记录，312–315

零窗口错误，101–102
