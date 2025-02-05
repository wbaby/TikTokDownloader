<div align="center">
<img src="https://github.com/JoeanAmier/TikTokDownloader/blob/master/static/images/TikTokDownloader.png" alt="TikTokDownloader" height="256" width="256"><br>
<h1>TikTokDownloader</h1>
<a href="https://github.com/JoeanAmier/TikTokDownloader/blob/master/license">
<img alt="GitHub" src="https://img.shields.io/github/license/JoeanAmier/TikTokDownloader">
</a>
<img alt="GitHub forks" src="https://img.shields.io/github/forks/JoeanAmier/TikTokDownloader?color=eb6ea5">
<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/JoeanAmier/TikTokDownloader?color=fff200">
<a href="https://sourcery.ai">
<img src="https://img.shields.io/badge/Sourcery-enabled-884898" alt="Sourcery">
</a>
<a href="https://github.com/JoeanAmier/TikTokDownloader/releases/latest">
<img alt="GitHub release (with filter)" src="https://img.shields.io/github/v/release/JoeanAmier/TikTokDownloader">
</a>
<img alt="GitHub all releases" src="https://img.shields.io/github/downloads/JoeanAmier/TikTokDownloader/total?color=3eb370">
</div>
<br>
<p>🔥 <b>TikTok 视频/图集/原声；抖音主页/视频/图集/收藏/直播/原声/合集/评论/账号/搜索/热榜数据采集工具：</b>完全开源，基于 Requests 模块实现的免费工具；批量下载抖音账号发布、喜欢、收藏的作品；单独下载抖音链接或 TikTok 链接对应的作品；获取抖音直播推流地址；下载抖音直播视频；采集抖音作品评论数据；批量下载抖音合集作品；采集抖音账号详细数据；采集抖音用户 / 作品 / 直播搜索结果；采集抖音热榜数据。</p>
<p>⭐ Windows 10 及以上用户可前往 <a href="https://github.com/JoeanAmier/TikTokDownloader/releases/latest">Releases</a> 下载已编译的 exe 程序，开箱即用！</p>
<p>❤️ 作者仅在 GitHub 发布 TikTokDownloader，未与任何个人或网站合作，且没有任何收费计划！</p>
<hr>

# 📝 功能清单\(Function\)

* ✅ 下载抖音无水印视频/图集
* ✅ 下载 TikTok 无水印视频/图集
* ✅ 批量下载抖音账号发布/喜欢/收藏作品
* ✅ 采集抖音 / TikTok 详细数据
* ✅ 批量下载链接作品
* ✅ 多账号批量下载作品
* ✅ 自动跳过已下载的文件
* ✅ 持久化保存采集数据
* ✅ 下载动态/静态封面图
* ✅ 获取抖音直播推流地址
* ✅ 下载抖音直播视频
* ✅ Web UI 交互界面
* ✅ 采集抖音作品评论数据
* ✅ 批量下载抖音合集作品
* ✅ 记录点赞收藏等统计数据
* ✅ 筛选作品发布时间
* ✅ 支持账号作品增量下载
* ✅ 支持使用代理采集数据
* ✅ 支持局域网远程访问
* ✅ 采集抖音账号详细数据
* ✅ 作品统计数据更新
* ✅ 自动更新账号昵称
* ✅ 部署至私有服务器
* ✅ 部署至公开服务器
* ✅ 采集抖音搜索数据
* ✅ 采集抖音热榜数据
* ✅ 记录已下载作品 ID
* ✅ 扫码登陆获取 Cookie
* ✅ 支持 Web API 调用
* ✅ 支持多线程下载作品
* ✅ 文件完整性处理机制

# 💻 程序界面\(Screenshot\)

**终端命令行模式：**
<br><br>
![终端模式截图](docs/终端模式截图1.png)
*****
![终端模式截图](docs/终端模式截图2.png)
<br><br>
**Web UI 交互模式：**
<br><br>
![WebUI模式截图](docs/WebUI模式截图1.png)
*****
![WebUI模式截图](docs/WebUI模式截图2.png)
*****
![WebUI模式截图](docs/WebUI模式截图3.png)
<br><br>
**Web API 接口模式：**
<br><br>
![WebAPI模式截图](docs/WebAPI模式截图.png)

# 📈 项目状态\(Status\)

* 🟢 [Releases](https://github.com/JoeanAmier/TikTokDownloader/releases/latest) 发布的源码已完成测试，所有功能均可正常使用
* 🟡 未来可能支持更多抖音热榜类型
* 🟡 未来可能新增终端文本用户界面\(TUI\)模式
* 🟡 未来可能新增获取账号关注列表功能
* 🟡 未来可能新增获取账号收藏合集列表功能
* 🟡 未来可能新增 TikTok 平台批量下载功能
* 🔴 最新版本的源码可能存在不稳定的 Bug
* 🔴 如果在使用过程中发现 Bug，请及时告知作者修复

# 📁 项目结构\(Structure\)

```text
TikTokDownloader
├─ main.py                                 // 项目程序启动入口
├─ requirements.txt                        // 程序所需第三方模块信息
├─ settings.json                           // 运行参数配置文件
├─ src                                     // 项目模块源码文件夹
│    ├─ CookieTool.py                      // Cookie 处理模块
│    ├─ Customizer.py                      // 项目代码调整模块
│    ├─ Configuration.py                   // 配置文件处理模块
│    ├─ DataAcquirer.py                    // 接口数据获取模块
│    ├─ DataExtractor.py                   // 数据提取储存模块
│    ├─ DataDownloader.py                  // 作品文件下载模块
│    ├─ FileManager.py                     // 作品文件管理模块
│    ├─ Parameter.py                       // 加密参数生成模块
│    ├─ Recorder.py                        // 日志及数据记录模块
│    ├─ StringCleaner.py                   // 非法字符处理模块
│    ├─ main_complete.py                   // 终端命令行模式启动入口
│    ├─ main_server.py                     // 服务器部署模式启动入口
│    ├─ main_api_server.py                 // Web API 接口模式启动入口
│    └─ main_web_UI.py                     // Web UI 交互模式启动入口
├─ cache                                   // 缓存数据文件夹
│    ├─ temp                               // 下载文件临时文件夹
│    ├─ AccountCache.json                  // 账号管理缓存数据
│    └─ IDRecorder.txt                     // 作品下载记录文件
├─ static                                  // 静态资源文件夹
├─ templates                               // HTML 模板文件夹
└─ docs                                    // 项目文档文件夹
```

# 📋 项目说明\(Instructions\)

**快速入门：**

<ol>
<li><b>下载 EXE 程序</b> 或者 <b>配置运行环境</b>
<ol><b>直接运行程序</b>
<li>下载 <a href="https://github.com/JoeanAmier/TikTokDownloader/releases/latest">Releases</a> 发布的 EXE 程序压缩包</li>
<li>解压后打开程序文件夹，双击运行 <code>main.exe</code></li>
</ol>
<ol><b>通过源码运行</b>
<li>安装不低于 <code>3.12</code> 版本的 <a href="https://www.python.org/">Python</a> 解释器</li>
<li>下载最新的源码或 <a href="https://github.com/JoeanAmier/TikTokDownloader/releases/latest">Releases</a> 发布的源码至本地</li>
<li>运行 <code>pip install -r requirements.txt</code> 命令安装程序所需模块</li>
<li>运行 main.py</li>
</ol>
</li>
<li>查看屏幕输出的 TikTokDownloader 免责声明，根据提示输入内容</li>
<li>将 Cookie 信息写入配置文件
<ol><b>手动复制粘贴</b>
<li>参考 <a href="https://github.com/JoeanAmier/TikTokDownloader/blob/master/docs/Cookie%E6%95%99%E7%A8%8B.md">Cookie 提取教程</a>，复制所需 Cookie 至剪贴板</li>
<li>选择 <code>复制粘贴写入 Cookie</code> 选项，按照提示将 Cookie 写入配置文件</li>
</ol>
<ol><b>扫码登录获取</b>
<li>选择 <code>扫码登陆写入 Cookie</code> 选项，程序会显示登录二维码图片，并使用默认应用打开图片</li>
<li>使用抖音 APP 扫描二维码并登录账号</li>
<li>按照提示操作，将 Cookie 写入配置文件</li>
</ol>
</li>
<li>返回程序界面，依次选择 <code>终端命令行模式</code> --> <code>批量下载链接作品</code></li>
<li>输入抖音或 TikTok 作品链接即可下载作品文件</li>
<li>更多详细说明请查看 <b><a href="https://github.com/JoeanAmier/TikTokDownloader/wiki/Documentation">项目文档</a></b></li>
</ol>
<p>⭐ 推荐使用 <a href="https://learn.microsoft.com/zh-cn/windows/terminal/install">Windows 终端</a>（Windows 11 自带默认终端）</p>
<hr>

**关于 Cookie：**

[点击查看 Cookie 获取教程](https://github.com/JoeanAmier/TikTokDownloader/blob/master/docs/Cookie%E6%95%99%E7%A8%8B.md)

|   程序功能   | 是否需要登录 |
|:--------:|:------:|
| 下载账号发布作品 |   ⭕    |
| 下载账号喜欢作品 |   ⭕    |
|  下载链接作品  |   ❌    |
| 获取直播推流地址 |   ❌    |
|  下载直播视频  |   ❌    |
| 获取作品评论数据 |   ⭕    |
|  下载合集作品  |   ❌    |
|  获取账号数据  |   ⭕    |
|  采集搜索结果  |   ❌    |
|  采集热榜数据  |   ❌    |
| 下载账号收藏作品 |   ✔️   |

**程序获取数据失败时，可以尝试更新 Cookie 或者使用已登录的 Cookie！**

<hr>

**其他说明：**

<ul>
<li>程序提示用户输入时，直接回车代表返回上级菜单，输入 <code>Q</code> 或 <code>q</code> 代表结束运行</li>
<li>由于获取账号喜欢作品和收藏作品数据仅返回喜欢 / 收藏作品的发布日期，不返回操作日期，因此程序需要获取全部喜欢 / 收藏作品数据再进行日期筛选；如果作品数量较多，可能会花费较长的时间；可通过 <code>pages</code> 参数控制请求次数</li>
<li>使用 <code>SQLite</code> 格式储存数据时，重复获取作品数据将会更新点赞收藏等统计数据</li>
<li>获取私密账号的发布作品数据需要登录后的 Cookie，且登录的账号需要关注该私密账号</li>
<li>批量下载账号作品或合集作品时，如果对应的昵称或标识发生变化，程序会自动更新已下载作品文件名称中的昵称和标识</li>
<li>程序下载文件时会先将文件下载至临时文件夹，下载完成后再移动至储存文件夹；程序运行结束时会清空临时文件夹</li>
<li>如果想要自定义程序功能，可以直接修改 <code>src/Customizer.py</code> 文件内容，已整理程序功能修改指引</li>
<li><code>批量下载收藏作品模式</code> 目前仅支持下载当前已登录 Cookie 对应账号的收藏作品，暂不支持多账号</li>
<li>如果想要程序使用代理，必须在 <code>settings.json</code> 设置 <code>proxies</code> 参数，否则程序不会使用代理</li>
<li>部分使用者反馈，新发布的作品过早下载会下载到低分辨率的文件，一段时间后才能下载到高分辨率文件，但时间规律尚不明确</li>
<li>退出程序时，建议以正常方式结束运行或者按下 Ctrl + C 结束运行，不建议直接点击终端窗口的关闭按钮结束运行</li>
</ul>

# ⚠️ 免责声明\(Disclaimers\)

<ul>
<li>使用者对本项目的使用由使用者自行决定，并自行承担风险。作者对使用者使用本项目所产生的任何损失、责任、或风险概不负责。</li>
<li>本项目的作者提供的代码和功能是基于现有知识和技术的开发成果。作者尽力确保代码的正确性和安全性，但不保证代码完全没有错误或缺陷。</li>
<li>使用者在使用本项目时必须严格遵守 <a href="https://github.com/JoeanAmier/TikTokDownloader/blob/master/license">GNU
    General Public License v3.0</a> 的要求，并在适当的地方注明使用了 <a
        href="https://github.com/JoeanAmier/TikTokDownloader/blob/master/license">GNU General Public License
    v3.0</a> 的代码。
</li>
<li>使用者在任何情况下均不得将本项目的作者、贡献者或其他相关方与使用者的使用行为联系起来，或要求其对使用者使用本项目所产生的任何损失或损害负责。</li>
<li>使用者在使用本项目的代码和功能时，必须自行研究相关法律法规，并确保其使用行为合法合规。任何因违反法律法规而导致的法律责任和风险，均由使用者自行承担。</li>
<li>本项目的作者不会提供 TikTokDownloader 项目的付费版本，也不会提供与 TikTokDownloader 项目相关的任何商业服务。</li>
<li>基于本项目进行的任何二次开发、修改或编译的程序与原创作者无关，原创作者不承担与二次开发行为或其结果相关的任何责任，使用者应自行对因二次开发可能带来的各种情况负全部责任。</li>
</ul>
<b>在使用本项目的代码和功能之前，请您认真考虑并接受以上免责声明。如果您对上述声明有任何疑问或不同意，请不要使用本项目的代码和功能。如果您使用了本项目的代码和功能，则视为您已完全理解并接受上述免责声明，并自愿承担使用本项目的一切风险和后果。</b>

# ✉️ 联系作者\(Contact\)

<ul>
<li>QQ: 2437596031</li>
<li>QQ Group: <a href="https://github.com/JoeanAmier/TikTokDownloader/blob/master/docs/QQ%E7%BE%A4%E8%81%8A%E4%BA%8C%E7%BB%B4%E7%A0%81.png">点击扫码加入群聊</a></li>
<li>Email: yonglelolu@gmail.com</li>
</ul>
<p>
<b>TikTokDownloader 是我个人独立维护的一个开源项目，鉴于个人精力有限，请理解项目进展可能较为缓慢，我会尽力保持更新和维护，以确保项目的稳定性和功能的不断改进。</b>
</p>
<p>
<b>如果您通过 Email 联系我，我可能无法及时查看并回复信息，我会尽力在七天内回复您的邮件；如果有紧急事项或需要更快的回复，请通过其他方式与我联系，谢谢理解！</b>
</p>

# ♥️ 支持项目\(Support\)

<p>如果 <b>TikTokDownloader</b> 对您有帮助，请考虑为它点个 <b>Star</b> ⭐，感谢您的支持！</p>
<table>
<thead>
<tr>
<th align="center">微信(WeChat)</th>
<th align="center">支付宝(Alipay)</th>
</tr>
</thead>
<tbody><tr>
<td align="center"><img src="./docs/微信赞助二维码.png" alt="微信赞助二维码" height="200" width="200"></td>
<td align="center"><img src="./docs/支付宝赞助二维码.png" alt="支付宝赞助二维码" height="200" width="200"></td>
</tr>
</tbody>
</table>
<p>如果您愿意，可以考虑提供资助为 <b>TikTokDownloader</b> 提供额外的支持！</p>

# 💡 代码参考\(Refer\)

* https://github.com/Evil0ctal/Douyin_TikTok_Download_API
* https://github.com/Johnserf-Seed/TikTokDownload
* https://github.com/ihmily/DouyinLiveRecorder
* https://github.com/davidteather/TikTok-Api
* https://requests.readthedocs.io/en/latest/
* https://dormousehole.readthedocs.io/en/latest/
* https://github.com/Textualize/rich
* https://ffmpeg.org/ffmpeg-all.html
* https://html5up.net/hyperspace
