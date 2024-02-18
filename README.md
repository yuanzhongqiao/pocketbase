<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><p align="center" dir="auto">
    <a href="https://pocketbase.io" rel="nofollow">
        <img src="https://camo.githubusercontent.com/45afc34faad79c9a4591c3ec02a3e98ec3e99b0e1c8a6fbbf11b6ea8f402fdf6/68747470733a2f2f692e696d6775722e636f6d2f3571696d6e6d352e706e67" alt="PocketBase - 1 个文件中的开源后端" data-canonical-src="https://i.imgur.com/5qimnm5.png" style="max-width: 100%;">
    </a>
</p>
<p align="center" dir="auto">
    <a href="https://github.com/pocketbase/pocketbase/actions/workflows/release.yaml"><img src="https://github.com/pocketbase/pocketbase/actions/workflows/release.yaml/badge.svg" alt="建造" style="max-width: 100%;"></a>
    <a href="https://github.com/pocketbase/pocketbase/releases"><img src="https://camo.githubusercontent.com/b9732255507737ff199b5889590f12cfeb152808f09d5f94710b747bf2e8fa7a/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f72656c656173652f706f636b6574626173652f706f636b6574626173652e737667" alt="最新版本" data-canonical-src="https://img.shields.io/github/release/pocketbase/pocketbase.svg" style="max-width: 100%;"></a>
    <a href="https://pkg.go.dev/github.com/pocketbase/pocketbase" rel="nofollow"><img src="https://camo.githubusercontent.com/63cbf89251fcaf3bbe7e8452e7844cb36ced6b07f9bc3f60e82707c588479a4d/68747470733a2f2f676f646f632e6f72672f6769746875622e636f6d2f706f636b6574626173652f706f636b6574626173653f7374617475732e737667" alt="Go 包文档" data-canonical-src="https://godoc.org/github.com/pocketbase/pocketbase?status.svg" style="max-width: 100%;"></a>
</p>
<p dir="auto"><a href="https://pocketbase.io" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PocketBase</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是一个开源 Go 后端，包括：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><strong><font style="vertical-align: inherit;">具有实时订阅功能</font></strong><font style="vertical-align: inherit;">的嵌入式数据库（</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SQLite</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）</font></font><strong><font style="vertical-align: inherit;"></font></strong></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">内置</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文件和用户管理</font></font></strong></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">方便的</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">管理仪表板 UI</font></font></strong></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和简单的</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">REST-ish API</font></font></strong></li>
</ul>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关文档和示例，请访问</font></font><a href="https://pocketbase.io/docs" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://pocketbase.io/docs</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></strong></p>
<div class="markdown-alert markdown-alert-warning" dir="auto"><p class="markdown-alert-title" dir="auto"><svg class="octicon octicon-alert mr-2" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="M6.457 1.047c.659-1.234 2.427-1.234 3.086 0l6.082 11.378A1.75 1.75 0 0 1 14.082 15H1.918a1.75 1.75 0 0 1-1.543-2.575Zm1.763.707a.25.25 0 0 0-.44 0L1.698 13.132a.25.25 0 0 0 .22.368h12.164a.25.25 0 0 0 .22-.368Zm.53 3.996v2.5a.75.75 0 0 1-1.5 0v-2.5a.75.75 0 0 1 1.5 0ZM9 11a1 1 0 1 1-2 0 1 1 0 0 1 2 0Z"></path></svg><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">警告</font></font></p><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请记住，PocketBase 仍在积极开发中，因此在达到 v1.0.0 之前不能保证完全向后兼容性。</font></font></p>
</div>
<h2 tabindex="-1" dir="auto"><a id="user-content-api-sdk-clients" class="anchor" aria-hidden="true" tabindex="-1" href="#api-sdk-clients"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">API SDK客户端</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">与 API 交互的最简单方法是使用官方 SDK 客户端之一：</font></font></p>
<ul dir="auto">
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JavaScript - </font></font><a href="https://github.com/pocketbase/js-sdk"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">pocketbase/js-sdk</font></font></a></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">浏览器和节点</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Dart - </font></font><a href="https://github.com/pocketbase/dart-sdk"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">pocketbase/dart-sdk</font></font></a></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">网络、移动、桌面</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）</font></font></li>
</ul>
<h2 tabindex="-1" dir="auto"><a id="user-content-overview" class="anchor" aria-hidden="true" tabindex="-1" href="#overview"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">概述</font></font></h2>
<h3 tabindex="-1" dir="auto"><a id="user-content-use-as-standalone-app" class="anchor" aria-hidden="true" tabindex="-1" href="#use-as-standalone-app"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用作独立应用程序</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://github.com/pocketbase/pocketbase/releases"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以从发布页面</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载适合您的平台的预构建可执行文件</font><font style="vertical-align: inherit;">。下载后，解压存档并</font></font><code>./pocketbase serve</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在解压的目录中运行。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">预构建的可执行文件基于该</font></font><a href="https://github.com/pocketbase/pocketbase/blob/master/examples/base/main.go"><code>examples/base/main.go</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文件</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，并默认启用 JS VM 插件，允许使用 JavaScript 扩展 PocketBase（</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">更多详细信息，请参阅</font></font><a href="https://pocketbase.io/docs/js-overview/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 JavaScript 扩展</font></font></a></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-use-as-a-go-frameworktoolkit" class="anchor" aria-hidden="true" tabindex="-1" href="#use-as-a-go-frameworktoolkit"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用作 Go 框架/工具包</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PocketBase 作为常规 Go 库包进行分发，它允许您构建自己的自定义应用程序特定的业务逻辑，并且最终仍然有一个可移植的可执行文件。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这是一个最小的例子：</font></font></p>
<ol start="0" dir="auto">
<li>
<p dir="auto"><a href="https://go.dev/doc/install" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装 Go 1.21+</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果尚未安装</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"></font><code>main.go</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">创建一个新的项目目录，其中</font><font style="vertical-align: inherit;">包含以下文件：</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">package</span> main

<span class="pl-k">import</span> (
    <span class="pl-s">"log"</span>
    <span class="pl-s">"net/http"</span>

    <span class="pl-s">"github.com/labstack/echo/v5"</span>
    <span class="pl-s">"github.com/pocketbase/pocketbase"</span>
    <span class="pl-s">"github.com/pocketbase/pocketbase/apis"</span>
    <span class="pl-s">"github.com/pocketbase/pocketbase/core"</span>
)

<span class="pl-k">func</span> <span class="pl-en">main</span>() {
    <span class="pl-s1">app</span> <span class="pl-c1">:=</span> <span class="pl-s1">pocketbase</span>.<span class="pl-en">New</span>()

    <span class="pl-s1">app</span>.<span class="pl-en">OnBeforeServe</span>().<span class="pl-en">Add</span>(<span class="pl-k">func</span>(<span class="pl-s1">e</span> <span class="pl-c1">*</span>core.<span class="pl-smi">ServeEvent</span>) <span class="pl-smi">error</span> {
        <span class="pl-c">// add new "GET /hello" route to the app router (echo)</span>
        <span class="pl-s1">e</span>.<span class="pl-c1">Router</span>.<span class="pl-en">AddRoute</span>(echo.<span class="pl-smi">Route</span>{
            <span class="pl-c1">Method</span>: <span class="pl-s1">http</span>.<span class="pl-c1">MethodGet</span>,
            <span class="pl-c1">Path</span>:   <span class="pl-s">"/hello"</span>,
            <span class="pl-c1">Handler</span>: <span class="pl-k">func</span>(<span class="pl-s1">c</span> echo.<span class="pl-smi">Context</span>) <span class="pl-smi">error</span> {
                <span class="pl-k">return</span> <span class="pl-s1">c</span>.<span class="pl-en">String</span>(<span class="pl-c1">200</span>, <span class="pl-s">"Hello world!"</span>)
            },
            <span class="pl-c1">Middlewares</span>: []echo.<span class="pl-smi">MiddlewareFunc</span>{
                <span class="pl-s1">apis</span>.<span class="pl-en">ActivityLogger</span>(<span class="pl-s1">app</span>),
            },
        })

        <span class="pl-k">return</span> <span class="pl-c1">nil</span>
    })

    <span class="pl-k">if</span> <span class="pl-s1">err</span> <span class="pl-c1">:=</span> <span class="pl-s1">app</span>.<span class="pl-en">Start</span>(); <span class="pl-s1">err</span> <span class="pl-c1">!=</span> <span class="pl-c1">nil</span> {
        <span class="pl-s1">log</span>.<span class="pl-en">Fatal</span>(<span class="pl-s1">err</span>)
    }
}</pre><div class="zeroclipboard-container">
    
  </div></div>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要初始化依赖项，请运行</font></font><code>go mod init myapp &amp;&amp; go mod tidy</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要启动应用程序，请运行</font></font><code>go run main.go serve</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要构建静态链接的可执行文件，您可以运行</font></font><code>CGO_ENABLED=0 go build</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">然后使用 启动创建的可执行文件</font></font><code>./myapp serve</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
</li>
</ol>
<div class="markdown-alert markdown-alert-note" dir="auto"><p class="markdown-alert-title" dir="auto"><svg class="octicon octicon-info mr-2" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="M0 8a8 8 0 1 1 16 0A8 8 0 0 1 0 8Zm8-6.5a6.5 6.5 0 1 0 0 13 6.5 6.5 0 0 0 0-13ZM6.5 7.75A.75.75 0 0 1 7.25 7h1a.75.75 0 0 1 .75.75v2.75h.25a.75.75 0 0 1 0 1.5h-2a.75.75 0 0 1 0-1.5h.25v-2h-.25a.75.75 0 0 1-.75-.75ZM8 6a1 1 0 1 1 0-2 1 1 0 0 1 0 2Z"></path></svg><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">笔记</font></font></p><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PocketBase 嵌入了 SQLite，但不需要 CGO。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果启用了 CGO（又名。</font></font><code>CGO_ENABLED=1</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">），它将使用</font></font><a href="https://pkg.go.dev/github.com/mattn/go-sqlite3" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">mattn/go-sqlite3</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">驱动程序，否则 - </font></font><a href="https://pkg.go.dev/modernc.org/sqlite" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Modernc.org/sqlite</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。仅当您确实需要以交叉编译复杂化为代价压缩读/写查询性能时才启用 CGO。</font></font></p>
</div>
<p dir="auto"><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关更多详细信息，请参阅</font></font><a href="https://pocketbase.io/docs/go-overview/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 Go 扩展</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></em></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-building-and-running-the-repo-maingo-example" class="anchor" aria-hidden="true" tabindex="-1" href="#building-and-running-the-repo-maingo-example"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建并运行 repo main.go 示例</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要构建最小的独立可执行文件（例如发布页面中的预构建可执行文件），您只需</font></font><code>go build</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在</font></font><code>examples/base</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目录中运行即可：</font></font></p>
<ol start="0" dir="auto">
<li><a href="https://go.dev/doc/install" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装 Go 1.21+</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果尚未安装</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">克隆/下载存储库</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">导航</font></font><code>examples/base</code></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">运行</font></font><code>GOOS=linux GOARCH=amd64 CGO_ENABLED=0 go build</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
（</font></font><em><a href="https://go.dev/doc/install/source#environment" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://go.dev/doc/install/source#environment</font></font></a></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过运行启动创建的可执行文件</font></font><code>./base serve</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
</ol>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请注意，目前纯 Go SQLite 驱动程序支持的构建目标是：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>darwin  amd64
darwin  arm64
freebsd amd64
freebsd arm64
linux   386
linux   amd64
linux   arm
linux   arm64
linux   ppc64le
linux   riscv64
linux   s390x
windows amd64
windows arm64
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="darwin  amd64
darwin  arm64
freebsd amd64
freebsd arm64
linux   386
linux   amd64
linux   arm
linux   arm64
linux   ppc64le
linux   riscv64
linux   s390x
windows amd64
windows arm64" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-testing" class="anchor" aria-hidden="true" tabindex="-1" href="#testing"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">测试</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PocketBase 带有混合的单元测试和集成测试。要运行它们，请使用标准</font></font><code>go test</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">命令：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>go <span class="pl-c1">test</span> ./...</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="go test ./..." tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">另请查看</font></font><a href="http://pocketbase.io/docs/testing" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">测试指南</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，了解如何编写您自己的自定义应用程序测试。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-security" class="anchor" aria-hidden="true" tabindex="-1" href="#security"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安全</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您发现 PocketBase 中存在安全漏洞，请发送电子邮件至</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">pocketbase.io 寻求支持</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">所有报告都将得到及时处理，并且您将获得相应的奖励。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-contributing" class="anchor" aria-hidden="true" tabindex="-1" href="#contributing"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贡献</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="/pocketbase/pocketbase/blob/master/LICENSE.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PocketBase 是根据MIT 许可证</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">授权的免费开源项目</font><font style="vertical-align: inherit;">。您可以自由地使用它做任何您想做的事情，甚至将其作为付费服务提供。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以通过以下方式帮助其继续发展：</font></font></p>
<ul dir="auto">
<li><a href="/pocketbase/pocketbase/blob/master/CONTRIBUTING.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贡献源代码</font></font></a></li>
<li><a href="https://github.com/pocketbase/pocketbase/issues"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">建议新功能并报告问题</font></font></a></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">新 OAuth2 提供商的 PR、错误修复、代码优化和文档改进非常受欢迎。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">但请不要</font><font style="vertical-align: inherit;">在没有事先讨论实现细节的情况下为</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">新功能</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">创建 PR。 PocketBase 有一个</font></font><a href="https://github.com/orgs/pocketbase/projects/2"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">路线图</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，我尝试按特定顺序解决问题，但此类 PR 经常突然出现，并通过繁琐的来回沟通扭曲所有初始计划。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果我关闭你的 PR，即使它执行得很好并且经过了测试，也不要生气。这并不意味着它永远不会被合并。稍后，当需要解决该问题时，我们可以随时参考它和/或获取您的实现片段（不用担心您会在发行说明中得到认可）。</font></font></p>
</article></div>
