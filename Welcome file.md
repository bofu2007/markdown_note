---


---

<h1 id="welcome-to-stackedit">Welcome to StackEdit!</h1>
<p>Hi! I’m your first Markdown file in <strong>StackEdit</strong>. If you want to learn about StackEdit, you can read me. If you want to play with Markdown, you can edit me. Once you have finished with me, you can create new files by opening the <strong>file explorer</strong> on the left corner of the navigation bar.</p>
<p>Hello, Cargo! - Rust 程序设计语言 简体中文版</p>
<p>var path_to_root = “”; var default_theme = window.matchMedia("(prefers-color-scheme: dark)").matches ? “navy” : “light”; try { var theme = localStorage.getItem(‘mdbook-theme’); var sidebar = localStorage.getItem(‘mdbook-sidebar’); if (theme.startsWith(’"’) &amp;&amp; theme.endsWith(’"’)) { localStorage.setItem(‘mdbook-theme’, theme.slice(1, theme.length - 1)); } if (sidebar.startsWith(’"’) &amp;&amp; sidebar.endsWith(’"’)) { localStorage.setItem(‘mdbook-sidebar’, sidebar.slice(1, sidebar.length - 1)); } } catch (e) { } var theme; try { theme = localStorage.getItem(‘mdbook-theme’); } catch(e) { } if (theme === null || theme === undefined) { theme = default_theme; } var html = document.querySelector(‘html’); html.classList.remove(‘light’) html.classList.add(theme); var body = document.querySelector(‘body’); body.classList.remove(‘no-js’) body.classList.add(‘js’);   var body = document.querySelector(‘body’); var sidebar = null; var sidebar_toggle = document.getElementById(“sidebar-toggle-anchor”); if (document.body.clientWidth &gt;= 1080) { try { sidebar = localStorage.getItem(‘mdbook-sidebar’); } catch(e) { } sidebar = sidebar || ‘visible’; } else { sidebar = ‘hidden’; } sidebar_toggle.checked = sidebar === ‘visible’; body.classList.remove(‘sidebar-visible’); body.classList.add(“sidebar-” + sidebar);</p>
<ol>
<li><a href="title-page.html">Rust 程序设计语言</a></li>
<li><a href="foreword.html">前言</a></li>
<li><a href="ch00-00-introduction.html">简介</a></li>
<li><a href="ch01-00-getting-started.html"><strong>1.</strong> 入门指南</a></li>
<li>
<ol>
<li><a href="ch01-01-installation.html"><strong>1.1.</strong> 安装</a></li>
<li><a href="ch01-02-hello-world.html"><strong>1.2.</strong> Hello, World!</a></li>
<li><a href="ch01-03-hello-cargo.html"><strong>1.3.</strong> Hello, Cargo!</a></li>
</ol>
</li>
<li><a href="ch02-00-guessing-game-tutorial.html"><strong>2.</strong> 写个猜数字游戏</a></li>
<li><a href="ch03-00-common-programming-concepts.html"><strong>3.</strong> 常见编程概念</a></li>
<li>
<ol>
<li><a href="ch03-01-variables-and-mutability.html"><strong>3.1.</strong> 变量与可变性</a></li>
<li><a href="ch03-02-data-types.html"><strong>3.2.</strong> 数据类型</a></li>
<li><a href="ch03-03-how-functions-work.html"><strong>3.3.</strong> 函数</a></li>
<li><a href="ch03-04-comments.html"><strong>3.4.</strong> 注释</a></li>
<li><a href="ch03-05-control-flow.html"><strong>3.5.</strong> 控制流</a></li>
</ol>
</li>
<li><a href="ch04-00-understanding-ownership.html"><strong>4.</strong> 认识所有权</a></li>
<li>
<ol>
<li><a href="ch04-01-what-is-ownership.html"><strong>4.1.</strong> 什么是所有权？</a></li>
</ol>
</li>
<li><a href="ch04-02-references-and-borrowing.html"><strong>4.2.</strong> 引用与借用</a></li>
<li><a href="ch04-03-slices.html"><strong>4.3.</strong> Slice 类型</a></li>
<li><a href="ch05-00-structs.html"><strong>5.</strong> 使用结构体组织相关联的数据</a></li>
<li>
<ol>
<li><a href="ch05-01-defining-structs.html"><strong>5.1.</strong> 结构体的定义和实例化</a></li>
</ol>
</li>
<li><a href="ch05-02-example-structs.html"><strong>5.2.</strong> 结构体示例程序</a></li>
<li><a href="ch05-03-method-syntax.html"><strong>5.3.</strong> 方法语法</a></li>
<li><a href="ch06-00-enums.html"><strong>6.</strong> 枚举和模式匹配</a></li>
<li>
<ol>
<li><a href="ch06-01-defining-an-enum.html"><strong>6.1.</strong> 枚举的定义</a></li>
</ol>
</li>
<li><a href="ch06-02-match.html"><strong>6.2.</strong> match 控制流结构</a></li>
<li><a href="ch06-03-if-let.html"><strong>6.3.</strong> if let 简洁控制流</a></li>
<li><a href="ch07-00-managing-growing-projects-with-packages-crates-and-modules.html"><strong>7.</strong> 使用包、Crate 和模块管理不断增长的项目</a></li>
<li>
<ol>
<li><a href="ch07-01-packages-and-crates.html"><strong>7.1.</strong> 包和 Crate</a></li>
</ol>
</li>
<li><a href="ch07-02-defining-modules-to-control-scope-and-privacy.html"><strong>7.2.</strong> 定义模块来控制作用域与私有性</a></li>
<li><a href="ch07-03-paths-for-referring-to-an-item-in-the-module-tree.html"><strong>7.3.</strong> 引用模块项目的路径</a></li>
<li><a href="ch07-04-bringing-paths-into-scope-with-the-use-keyword.html"><strong>7.4.</strong> 使用 use 关键字将路径引入作用域</a></li>
<li><a href="ch07-05-separating-modules-into-different-files.html"><strong>7.5.</strong> 将模块拆分成多个文件</a></li>
<li><a href="ch08-00-common-collections.html"><strong>8.</strong> 常见集合</a></li>
<li>
<ol>
<li><a href="ch08-01-vectors.html"><strong>8.1.</strong> 使用 Vector 储存列表</a></li>
</ol>
</li>
<li><a href="ch08-02-strings.html"><strong>8.2.</strong> 使用字符串储存 UTF-8 编码的文本</a></li>
<li><a href="ch08-03-hash-maps.html"><strong>8.3.</strong> 使用 Hash Map 储存键值对</a></li>
<li><a href="ch09-00-error-handling.html"><strong>9.</strong> 错误处理</a></li>
<li>
<ol>
<li><a href="ch09-01-unrecoverable-errors-with-panic.html"><strong>9.1.</strong> 用 panic! 处理不可恢复的错误</a></li>
</ol>
</li>
<li><a href="ch09-02-recoverable-errors-with-result.html"><strong>9.2.</strong> 用 Result 处理可恢复的错误</a></li>
<li><a href="ch09-03-to-panic-or-not-to-panic.html"><strong>9.3.</strong> 要不要 panic!</a></li>
<li><a href="ch10-00-generics.html"><strong>10.</strong> 泛型、Trait 和生命周期</a></li>
<li>
<ol>
<li><a href="ch10-01-syntax.html"><strong>10.1.</strong> 泛型数据类型</a></li>
</ol>
</li>
<li><a href="ch10-02-traits.html"><strong>10.2.</strong> Trait：定义共同行为</a></li>
<li><a href="ch10-03-lifetime-syntax.html"><strong>10.3.</strong> 生命周期确保引用有效</a></li>
<li><a href="ch11-00-testing.html"><strong>11.</strong> 编写自动化测试</a></li>
<li>
<ol>
<li><a href="ch11-01-writing-tests.html"><strong>11.1.</strong> 如何编写测试</a></li>
</ol>
</li>
<li><a href="ch11-02-running-tests.html"><strong>11.2.</strong> 控制测试如何运行</a></li>
<li><a href="ch11-03-test-organization.html"><strong>11.3.</strong> 测试的组织结构</a></li>
<li><a href="ch12-00-an-io-project.html"><strong>12.</strong> 一个 I/O 项目：构建命令行程序</a></li>
<li>
<ol>
<li><a href="ch12-01-accepting-command-line-arguments.html"><strong>12.1.</strong> 接受命令行参数</a></li>
</ol>
</li>
<li><a href="ch12-02-reading-a-file.html"><strong>12.2.</strong> 读取文件</a></li>
<li><a href="ch12-03-improving-error-handling-and-modularity.html"><strong>12.3.</strong> 重构以改进模块化与错误处理</a></li>
<li><a href="ch12-04-testing-the-librarys-functionality.html"><strong>12.4.</strong> 采用测试驱动开发完善库的功能</a></li>
<li><a href="ch12-05-working-with-environment-variables.html"><strong>12.5.</strong> 处理环境变量</a></li>
<li><a href="ch12-06-writing-to-stderr-instead-of-stdout.html"><strong>12.6.</strong> 将错误信息输出到标准错误而不是标准输出</a></li>
<li><a href="ch13-00-functional-features.html"><strong>13.</strong> Rust 中的函数式语言功能：迭代器与闭包</a></li>
<li>
<ol>
<li><a href="ch13-01-closures.html"><strong>13.1.</strong> 闭包：可以捕获其环境的匿名函数</a></li>
</ol>
</li>
<li><a href="ch13-02-iterators.html"><strong>13.2.</strong> 使用迭代器处理元素序列</a></li>
<li><a href="ch13-03-improving-our-io-project.html"><strong>13.3.</strong> 改进之前的 I/O 项目</a></li>
<li><a href="ch13-04-performance.html"><strong>13.4.</strong> 性能比较：循环对迭代器</a></li>
<li><a href="ch14-00-more-about-cargo.html"><strong>14.</strong> 更多关于 Cargo 和 Crates.io 的内容</a></li>
<li>
<ol>
<li><a href="ch14-01-release-profiles.html"><strong>14.1.</strong> 采用发布配置自定义构建</a></li>
</ol>
</li>
<li><a href="ch14-02-publishing-to-crates-io.html"><strong>14.2.</strong> 将 crate 发布到 Crates.io</a></li>
<li><a href="ch14-03-cargo-workspaces.html"><strong>14.3.</strong> Cargo 工作空间</a></li>
<li><a href="ch14-04-installing-binaries.html"><strong>14.4.</strong> 使用 cargo install 安装二进制文件</a></li>
<li><a href="ch14-05-extending-cargo.html"><strong>14.5.</strong> Cargo 自定义扩展命令</a></li>
<li><a href="ch15-00-smart-pointers.html"><strong>15.</strong> 智能指针</a></li>
<li>
<ol>
<li><a href="ch15-01-box.html"><strong>15.1.</strong> 使用 Box 指向堆上数据</a></li>
</ol>
</li>
<li><a href="ch15-02-deref.html"><strong>15.2.</strong> 使用 Deref Trait 将智能指针当作常规引用处理</a></li>
<li><a href="ch15-03-drop.html"><strong>15.3.</strong> 使用 Drop Trait 运行清理代码</a></li>
<li><a href="ch15-04-rc.html"><strong>15.4.</strong> Rc 引用计数智能指针</a></li>
<li><a href="ch15-05-interior-mutability.html"><strong>15.5.</strong> RefCell 与内部可变性模式</a></li>
<li><a href="ch15-06-reference-cycles.html"><strong>15.6.</strong> 引用循环会导致内存泄漏</a></li>
<li><a href="ch16-00-concurrency.html"><strong>16.</strong> 无畏并发</a></li>
<li>
<ol>
<li><a href="ch16-01-threads.html"><strong>16.1.</strong> 使用线程同时地运行代码</a></li>
</ol>
</li>
<li><a href="ch16-02-message-passing.html"><strong>16.2.</strong> 使用消息传递在线程间通信</a></li>
<li><a href="ch16-03-shared-state.html"><strong>16.3.</strong> 共享状态并发</a></li>
<li><a href="ch16-04-extensible-concurrency-sync-and-send.html"><strong>16.4.</strong> 使用 Sync 与 Send Traits 的可扩展并发</a></li>
<li><a href="ch17-00-oop.html"><strong>17.</strong> Rust 的面向对象编程特性</a></li>
<li>
<ol>
<li><a href="ch17-01-what-is-oo.html"><strong>17.1.</strong> 面向对象语言的特点</a></li>
</ol>
</li>
<li><a href="ch17-02-trait-objects.html"><strong>17.2.</strong> 顾及不同类型值的 trait 对象</a></li>
<li><a href="ch17-03-oo-design-patterns.html"><strong>17.3.</strong> 面向对象设计模式的实现</a></li>
<li><a href="ch18-00-patterns.html"><strong>18.</strong> 模式与模式匹配</a></li>
<li>
<ol>
<li><a href="ch18-01-all-the-places-for-patterns.html"><strong>18.1.</strong> 所有可能会用到模式的位置</a></li>
</ol>
</li>
<li><a href="ch18-02-refutability.html"><strong>18.2.</strong> Refutability（可反驳性）: 模式是否会匹配失效</a></li>
<li><a href="ch18-03-pattern-syntax.html"><strong>18.3.</strong> 模式语法</a></li>
<li><a href="ch19-00-advanced-features.html"><strong>19.</strong> 高级特征</a></li>
<li>
<ol>
<li><a href="ch19-01-unsafe-rust.html"><strong>19.1.</strong> 不安全的 Rust</a></li>
</ol>
</li>
<li><a href="ch19-03-advanced-traits.html"><strong>19.2.</strong> 高级 trait</a></li>
<li><a href="ch19-04-advanced-types.html"><strong>19.3.</strong> 高级类型</a></li>
<li><a href="ch19-05-advanced-functions-and-closures.html"><strong>19.4.</strong> 高级函数与闭包</a></li>
<li><a href="ch19-06-macros.html"><strong>19.5.</strong> 宏</a></li>
<li><a href="ch20-00-final-project-a-web-server.html"><strong>20.</strong> 最后的项目：构建多线程 web server</a></li>
<li>
<ol>
<li><a href="ch20-01-single-threaded.html"><strong>20.1.</strong> 建立单线程 web server</a></li>
</ol>
</li>
<li><a href="ch20-02-multithreaded.html"><strong>20.2.</strong> 将单线程 server 变为多线程 server</a></li>
<li><a href="ch20-03-graceful-shutdown-and-cleanup.html"><strong>20.3.</strong> 优雅停机与清理</a></li>
<li><a href="appendix-00.html"><strong>21.</strong> 附录</a></li>
<li>
<ol>
<li><a href="appendix-01-keywords.html"><strong>21.1.</strong> A - 关键字</a></li>
</ol>
</li>
<li><a href="appendix-02-operators.html"><strong>21.2.</strong> B - 运算符与符号</a></li>
<li><a href="appendix-03-derivable-traits.html"><strong>21.3.</strong> C - 可派生的 trait</a></li>
<li><a href="appendix-04-useful-development-tools.html"><strong>21.4.</strong> D - 实用开发工具</a></li>
<li><a href="appendix-05-editions.html"><strong>21.5.</strong> E - 版本</a></li>
<li><a href="appendix-06-translation.html"><strong>21.6.</strong> F - 本书译本</a></li>
<li><a href="appendix-07-nightly-rust.html"><strong>21.7.</strong> G - Rust 是如何开发的与 “Nightly Rust”</a></li>
</ol>
<p>var sidebarScrollbox = document.querySelector(’#sidebar .sidebar-scrollbox’); sidebarScrollbox.addEventListener(‘click’, function(e) { if (e.target.tagName === ‘A’) { sessionStorage.setItem(‘sidebar-scroll’, sidebarScrollbox.scrollTop); } }, { passive: true }); var sidebarScrollTop = sessionStorage.getItem(‘sidebar-scroll’); sessionStorage.removeItem(‘sidebar-scroll’); if (sidebarScrollTop) { // preserve sidebar scroll position when navigating via links within sidebar sidebarScrollbox.scrollTop = sidebarScrollTop; } else { // scroll sidebar to current active section when navigating via “next/previous chapter” buttons var activeSection = document.querySelector(’#sidebar .active’); if (activeSection) { activeSection.scrollIntoView({ block: ‘center’ }); } }</p>
<ul>
<li>Light</li>
<li>Rust</li>
<li>Coal</li>
<li>Navy</li>
<li>Ayu</li>
</ul>
<h1 id="rust-程序设计语言-简体中文版">Rust 程序设计语言 简体中文版</h1>
<p><a href="print.html" title="Print this book"></a><a href="https://github.com/KaiserY/trpl-zh-cn/tree/main" title="Git repository"></a><a href="https://github.com/KaiserY/trpl-zh-cn/edit/main/src/ch01-03-hello-cargo.md" title="Suggest an edit"></a></p>
<p>document.getElementById(‘sidebar-toggle’).setAttribute(‘aria-expanded’, sidebar === ‘visible’); document.getElementById(‘sidebar’).setAttribute(‘aria-hidden’, sidebar !== ‘visible’); Array.from(document.querySelectorAll(’#sidebar a’)).forEach(function(link) { link.setAttribute(‘tabIndex’, sidebar === ‘visible’ ? 0 : -1); });</p>
<h2 id="hello-cargo"><a href="#hello-cargo">Hello, Cargo!</a></h2>
<blockquote>
<p><a href="https://github.com/rust-lang/book/blob/main/src/ch01-03-hello-cargo.md">ch01-03-hello-cargo.md</a><br>
commit f801008f555e4e94aae826cf45f3a8011a773098</p>
</blockquote>
<p>Cargo 是 Rust 的构建系统和包管理器。大多数 Rustacean 们使用 Cargo 来管理他们的 Rust 项目，因为它可以为你处理很多任务，比如构建代码、下载依赖库并编译这些库。（我们把代码所需要的库叫做 <strong>依赖</strong>（<em>dependencies</em>））。</p>
<p>最简单的 Rust 程序，比如我们刚刚编写的，没有任何依赖。如果使用 Cargo 来构建 “Hello, world!” 项目，将只会用到 Cargo 构建代码的那部分功能。在编写更复杂的 Rust 程序时，你将添加依赖项，如果使用 Cargo 启动项目，则添加依赖项将更容易。</p>
<p>由于绝大多数 Rust 项目使用 Cargo，本书接下来的部分假设你也使用 Cargo。如果使用 <a href="ch01-01-installation.html#%E5%AE%89%E8%A3%85">“安装”</a> 部分介绍的官方安装包的话，则自带了 Cargo。如果通过其他方式安装的话，可以在终端输入如下命令检查是否安装了 Cargo：</p>
<pre><code>$ cargo --version
</code></pre>
<p>如果你看到了版本号，说明已安装！如果看到类似 <code>command not found</code> 的错误，你应该查看相应安装文档以确定如何单独安装 Cargo。</p>
<h3 id="使用-cargo-创建项目"><a href="#%E4%BD%BF%E7%94%A8-cargo-%E5%88%9B%E5%BB%BA%E9%A1%B9%E7%9B%AE">使用 Cargo 创建项目</a></h3>
<p>我们使用 Cargo 创建一个新项目，然后看看与上面的 “Hello, world!” 项目有什么不同。回到 <em>projects</em> 目录（或者你存放代码的目录）。接着，可在任何操作系统下运行以下命令：</p>
<pre><code>$ cargo new hello_cargo
$ cd hello_cargo
</code></pre>
<p>第一行命令新建了名为 <em>hello_cargo</em> 的目录和项目。我们将项目命名为 <em>hello_cargo</em>，同时 Cargo 在一个同名目录中创建项目文件。</p>
<p>进入 <em>hello_cargo</em> 目录并列出文件。将会看到 Cargo 生成了两个文件和一个目录：一个 <em>Cargo.toml</em> 文件，一个 <em>src</em> 目录，以及位于 <em>src</em> 目录中的 <em><a href="http://main.rs">main.rs</a></em> 文件。</p>
<p>这也会在 <em>hello_cargo</em> 目录初始化了一个 git 仓库，以及一个 <em>.gitignore</em> 文件。如果在一个已经存在的 git 仓库中运行 <code>cargo new</code>，则这些 git 相关文件则不会生成；可以通过运行 <code>cargo new --vcs=git</code> 来覆盖这些行为。</p>
<blockquote>
<p>注意：Git 是一个常用的版本控制系统（version control system，VCS）。可以通过 <code>--vcs</code> 参数使 <code>cargo new</code> 切换到其它版本控制系统（VCS），或者不使用 VCS。运行 <code>cargo new --help</code> 参看可用的选项。</p>
</blockquote>
<p>请自行选用文本编辑器打开 <em>Cargo.toml</em> 文件。它应该看起来如示例 1-2 所示：</p>
<p>文件名：Cargo.toml</p>
<pre><code>[package]
name = "hello_cargo"
version = "0.1.0"
edition = "2021"

# See more keys and their definitions at https://doc.rust-lang.org/cargo/reference/manifest.html

[dependencies]
</code></pre>
<p>示例 1-2: <em>cargo new</em> 命令生成的 <em>Cargo.toml</em> 的内容</p>
<p>这个文件使用 <a href="https://toml.io"><em>TOML</em></a> (<em>Tom’s Obvious, Minimal Language</em>) 格式，这是 Cargo 配置文件的格式。</p>
<p>第一行，<code>[package]</code>，是一个片段（section）标题，表明下面的语句用来配置一个包。随着我们在这个文件增加更多的信息，还将增加其他片段（section）。</p>
<p>接下来的三行设置了 Cargo 编译程序所需的配置：项目的名称、项目的版本以及要使用的 Rust 版本。<a href="appendix-05-editions.html">附录 E</a> 会介绍 <code>edition</code> 的值。</p>
<p>最后一行，<code>[dependencies]</code>，是罗列项目依赖的片段的开始。在 Rust 中，代码包被称为 <em>crates</em>。这个项目并不需要其他的 crate，不过在第二章的第一个项目会用到依赖，那时会用得上这个片段。</p>
<p>现在打开 <em>src/main.rs</em> 看看：</p>
<p>文件名：src/main.rs</p>
<pre><code>fn main() {
    println!("Hello, world!");
}
</code></pre>
<p>Cargo 为你生成了一个 “Hello, world!” 程序，正如我们之前编写的示例 1-1！目前为止，我们的项目与 Cargo 生成项目的区别是 Cargo 将代码放在 <em>src</em> 目录，同时项目根目录包含一个 <em>Cargo.toml</em> 配置文件。</p>
<p>Cargo 期望源文件存放在 <em>src</em> 目录中。项目根目录只存放 README、license 信息、配置文件和其他跟代码无关的文件。使用 Cargo 帮助你保持项目干净整洁，一切井井有条。</p>
<p>如果没有使用 Cargo 开始项目，比如我们创建的 Hello,world! 项目，可以将其转化为一个 Cargo 项目。将代码放入 <em>src</em> 目录，并创建一个合适的 <em>Cargo.toml</em> 文件。</p>
<h3 id="构建并运行-cargo-项目"><a href="#%E6%9E%84%E5%BB%BA%E5%B9%B6%E8%BF%90%E8%A1%8C-cargo-%E9%A1%B9%E7%9B%AE">构建并运行 Cargo 项目</a></h3>
<p>现在让我们看看通过 Cargo 构建和运行 “Hello, world!” 程序有什么不同！在 <em>hello_cargo</em> 目录下，输入下面的命令来构建项目：</p>
<pre><code>$ cargo build
   Compiling hello_cargo v0.1.0 (file:///projects/hello_cargo)
    Finished dev [unoptimized + debuginfo] target(s) in 2.85 secs
</code></pre>
<p>这个命令会创建一个可执行文件 <em>target/debug/hello_cargo</em> （在 Windows 上是 <em>target\debug\hello_cargo.exe</em>），而不是放在目前目录下。由于默认的构建方法是调试构建（debug build），Cargo 会将可执行文件放在名为 <em>debug</em> 的目录中。可以通过这个命令运行可执行文件：</p>
<pre><code>$ ./target/debug/hello_cargo # 或者在 Windows 下为 .\target\debug\hello_cargo.exe
Hello, world!
</code></pre>
<p>如果一切顺利，终端上应该会打印出 <code>Hello, world!</code>。首次运行 <code>cargo build</code> 时，也会使 Cargo 在项目根目录创建一个新文件：<em>Cargo.lock</em>。这个文件记录项目依赖的实际版本。这个项目并没有依赖，所以其内容比较少。你自己永远也不需要碰这个文件，让 Cargo 处理它就行了。</p>
<p>我们刚刚使用 <code>cargo build</code> 构建了项目，并使用 <code>./target/debug/hello_cargo</code> 运行了程序，也可以使用 <code>cargo run</code> 在一个命令中同时编译并运行生成的可执行文件：</p>
<pre><code>$ cargo run
    Finished dev [unoptimized + debuginfo] target(s) in 0.0 secs
     Running `target/debug/hello_cargo`
Hello, world!
</code></pre>
<p>比起要记得运行 <code>cargo build</code> 之后再用可执行文件的完整路径来运行程序，使用 <code>cargo run</code> 可以实现完全相同的效果，而且要方便得多，所以大多数开发者会使用 <code>cargo run</code>。</p>
<p>注意这一次并没有出现表明 Cargo 正在编译 <code>hello_cargo</code> 的输出。Cargo 发现文件并没有被改变，所以它并没有重新编译，而是直接运行了可执行文件。如果修改了源文件的话，Cargo 会在运行之前重新构建项目，并会出现像这样的输出：</p>
<pre><code>$ cargo run
   Compiling hello_cargo v0.1.0 (file:///projects/hello_cargo)
    Finished dev [unoptimized + debuginfo] target(s) in 0.33 secs
     Running `target/debug/hello_cargo`
Hello, world!
</code></pre>
<p>Cargo 还提供了一个叫 <code>cargo check</code> 的命令。该命令快速检查代码确保其可以编译，但并不产生可执行文件：</p>
<pre><code>$ cargo check
   Checking hello_cargo v0.1.0 (file:///projects/hello_cargo)
    Finished dev [unoptimized + debuginfo] target(s) in 0.32 secs
</code></pre>
<p>为什么你会不需要可执行文件呢？通常 <code>cargo check</code> 要比 <code>cargo build</code> 快得多，因为它省略了生成可执行文件的步骤。如果你在编写代码时持续的进行检查，<code>cargo check</code> 可以让你快速了解现在的代码能不能正常通过编译！为此很多 Rustaceans 编写代码时定期运行 <code>cargo check</code> 确保它们可以编译。当准备好使用可执行文件时才运行 <code>cargo build</code>。</p>
<p>我们回顾下已学习的 Cargo 内容：</p>
<ul>
<li>可以使用 <code>cargo new</code> 创建项目。</li>
<li>可以使用 <code>cargo build</code> 构建项目。</li>
<li>可以使用 <code>cargo run</code> 一步构建并运行项目。</li>
<li>可以使用 <code>cargo check</code> 在不生成二进制文件的情况下构建项目来检查错误。</li>
<li>有别于将构建结果放在与源码相同的目录，Cargo 会将其放到 <em>target/debug</em> 目录。</li>
</ul>
<p>使用 Cargo 的一个额外的优点是，不管你使用什么操作系统，其命令都是一样的。所以从现在开始本书将不再为 Linux 和 macOS 以及 Windows 提供相应的命令。</p>
<h3 id="发布（release）构建"><a href="#%E5%8F%91%E5%B8%83release%E6%9E%84%E5%BB%BA">发布（release）构建</a></h3>
<p>当项目最终准备好发布时，可以使用 <code>cargo build --release</code> 来优化编译项目。这会在 <em>target/release</em> 而不是 <em>target/debug</em> 下生成可执行文件。这些优化可以让 Rust 代码运行的更快，不过启用这些优化也需要消耗更长的编译时间。这也就是为什么会有两种不同的配置：一种是为了开发，你需要经常快速重新构建；另一种是为用户构建最终程序，它们不会经常重新构建，并且希望程序运行得越快越好。如果你在测试代码的运行时间，请确保运行 <code>cargo build --release</code> 并使用 <em>target/release</em> 下的可执行文件进行测试。</p>
<h3 id="把-cargo-当作习惯"><a href="#%E6%8A%8A-cargo-%E5%BD%93%E4%BD%9C%E4%B9%A0%E6%83%AF">把 Cargo 当作习惯</a></h3>
<p>对于简单项目，Cargo 并不比 <code>rustc</code> 提供了更多的优势，不过随着开发的深入，终将证明其价值。一旦程序壮大到由多个文件组成，亦或者是需要其他的依赖，让 Cargo 协调构建过程就会简单得多。</p>
<p>即便 <code>hello_cargo</code> 项目十分简单，它现在也使用了很多在你之后的 Rust 生涯将会用到的实用工具。其实，要在任何已存在的项目上工作时，可以使用如下命令通过 Git 检出代码，移动到该项目目录并构建：</p>
<pre><code>$ git clone example.org/someproject
$ cd someproject
$ cargo build
</code></pre>
<p>关于更多 Cargo 的信息，请查阅 <a href="https://doc.rust-lang.org/cargo/">其文档</a>。</p>
<h2 id="总结"><a href="#%E6%80%BB%E7%BB%93">总结</a></h2>
<p>你已经准备好开启 Rust 之旅了！在本章中，你学习了如何：</p>
<ul>
<li>使用 <code>rustup</code> 安装最新稳定版的 Rust</li>
<li>更新到新版的 Rust</li>
<li>打开本地安装的文档</li>
<li>直接通过 <code>rustc</code> 编写并运行 Hello, world! 程序</li>
<li>使用 Cargo 创建并运行新项目</li>
</ul>
<p>是时候通过构建更实质性的程序来熟悉读写 Rust 代码了。所以在第二章我们会构建一个猜猜看游戏程序。如果你更愿意从学习 Rust 常用的编程概念开始，请阅读第三章，接着再回到第二章。</p>
<p><a href="ch01-02-hello-world.html" title="Previous chapter"></a><a href="ch02-00-guessing-game-tutorial.html" title="Next chapter"></a></p>
<p><a href="ch01-02-hello-world.html" title="Previous chapter"></a><a href="ch02-00-guessing-game-tutorial.html" title="Next chapter"></a></p>
<p>window.playground_copyable = true;</p>
<p>第一行命令新建了名为  <em>hello_cargo</em>  的目录和项目。我们将项目命名为  <em>hello_cargo</em>，同时 Cargo 在一个同名目录中创建项目文件。</p>
<p>进入  <em>hello_cargo</em>  目录并列出文件。将会看到 Cargo 生成了两个文件和一个目录：一个  <em>Cargo.toml</em>  文件，一个  <em>src</em>  目录，以及位于  <em>src</em>  目录中的  <em><a href="http://main.rs">main.rs</a></em>  文件。</p>
<p>这也会在  <em>hello_cargo</em>  目录初始化了一个 git 仓库，以及一个  <em>.gitignore</em>  文件。如果在一个已经存在的 git 仓库中运行  <code>cargo new</code>，则这些 git 相关文件则不会生成；可以通过运行  <code>cargo new --vcs=git</code>  来覆盖这些行为。</p>
<blockquote>
<p>注意：Git 是一个常用的版本控制系统（version control system，VCS）。可以通过  <code>--vcs</code>  参数使  <code>cargo new</code>  切换到其它版本控制系统（VCS），或者不使用 VCS。运行  <code>cargo new --help</code>  参看可用的选项。</p>
</blockquote>
<p>请自行选用文本编辑器打开  <em>Cargo.toml</em>  文件。它应该看起来如示例 1-2 所示：</p>
<p>文件名：Cargo.toml</p>
<p>`[package]<br>
name = “hello_cargo”<br>
version = “0.1.0”<br>
edition = “2021”</p>
<h1 id="see-more-keys-and-their-definitions-at-httpsdoc.rust-lang.orgcargoreferencemanifest.html">See more keys and their definitions at <a href="https://doc.rust-lang.org/cargo/reference/manifest.html">https://doc.rust-lang.org/cargo/reference/manifest.html</a></h1>
<p>[dependencies]`</p>
<p>示例 1-2:  <em>cargo new</em>  命令生成的  <em>Cargo.toml</em>  的内容</p>
<h1 id="files">Files</h1>
<p>StackEdit stores your files in your browser, which means all your files are automatically saved locally and are accessible <strong>offline!</strong></p>
<h2 id="create-files-and-folders">Create files and folders</h2>
<p>The file explorer is accessible using the button in left corner of the navigation bar. You can create a new file by clicking the <strong>New file</strong> button in the file explorer. You can also create folders by clicking the <strong>New folder</strong> button.</p>
<h2 id="switch-to-another-file">Switch to another file</h2>
<p>All your files and folders are presented as a tree in the file explorer. You can switch from one to another by clicking a file in the tree.</p>
<h2 id="rename-a-file">Rename a file</h2>
<p>You can rename the current file by clicking the file name in the navigation bar or by clicking the <strong>Rename</strong> button in the file explorer.</p>
<h2 id="delete-a-file">Delete a file</h2>
<p>You can delete the current file by clicking the <strong>Remove</strong> button in the file explorer. The file will be moved into the <strong>Trash</strong> folder and automatically deleted after 7 days of inactivity.</p>
<h2 id="export-a-file">Export a file</h2>
<p>You can export the current file by clicking <strong>Export to disk</strong> in the menu. You can choose to export the file as plain Markdown, as HTML using a Handlebars template or as a PDF.</p>
<h1 id="synchronization">Synchronization</h1>
<p>Synchronization is one of the biggest features of StackEdit. It enables you to synchronize any file in your workspace with other files stored in your <strong>Google Drive</strong>, your <strong>Dropbox</strong> and your <strong>GitHub</strong> accounts. This allows you to keep writing on other devices, collaborate with people you share the file with, integrate easily into your workflow… The synchronization mechanism takes place every minute in the background, downloading, merging, and uploading file modifications.</p>
<p>There are two types of synchronization and they can complement each other:</p>
<ul>
<li>
<p>The workspace synchronization will sync all your files, folders and settings automatically. This will allow you to fetch your workspace on any other device.</p>
<blockquote>
<p>To start syncing your workspace, just sign in with Google in the menu.</p>
</blockquote>
</li>
<li>
<p>The file synchronization will keep one file of the workspace synced with one or multiple files in <strong>Google Drive</strong>, <strong>Dropbox</strong> or <strong>GitHub</strong>.</p>
<blockquote>
<p>Before starting to sync files, you must link an account in the <strong>Synchronize</strong> sub-menu.</p>
</blockquote>
</li>
</ul>
<h2 id="open-a-file">Open a file</h2>
<p>You can open a file from <strong>Google Drive</strong>, <strong>Dropbox</strong> or <strong>GitHub</strong> by opening the <strong>Synchronize</strong> sub-menu and clicking <strong>Open from</strong>. Once opened in the workspace, any modification in the file will be automatically synced.</p>
<h2 id="save-a-file">Save a file</h2>
<p>You can save any file of the workspace to <strong>Google Drive</strong>, <strong>Dropbox</strong> or <strong>GitHub</strong> by opening the <strong>Synchronize</strong> sub-menu and clicking <strong>Save on</strong>. Even if a file in the workspace is already synced, you can save it to another location. StackEdit can sync one file with multiple locations and accounts.</p>
<h2 id="synchronize-a-file">Synchronize a file</h2>
<p>Once your file is linked to a synchronized location, StackEdit will periodically synchronize it by downloading/uploading any modification. A merge will be performed if necessary and conflicts will be resolved.</p>
<p>If you just have modified your file and you want to force syncing, click the <strong>Synchronize now</strong> button in the navigation bar.</p>
<blockquote>
<p><strong>Note:</strong> The <strong>Synchronize now</strong> button is disabled if you have no file to synchronize.</p>
</blockquote>
<h2 id="manage-file-synchronization">Manage file synchronization</h2>
<p>Since one file can be synced with multiple locations, you can list and manage synchronized locations by clicking <strong>File synchronization</strong> in the <strong>Synchronize</strong> sub-menu. This allows you to list and remove synchronized locations that are linked to your file.</p>
<h1 id="publication">Publication</h1>
<p>Publishing in StackEdit makes it simple for you to publish online your files. Once you’re happy with a file, you can publish it to different hosting platforms like <strong>Blogger</strong>, <strong>Dropbox</strong>, <strong>Gist</strong>, <strong>GitHub</strong>, <strong>Google Drive</strong>, <strong>WordPress</strong> and <strong>Zendesk</strong>. With <a href="http://handlebarsjs.com/">Handlebars templates</a>, you have full control over what you export.</p>
<blockquote>
<p>Before starting to publish, you must link an account in the <strong>Publish</strong> sub-menu.</p>
</blockquote>
<h2 id="publish-a-file">Publish a File</h2>
<p>You can publish your file by opening the <strong>Publish</strong> sub-menu and by clicking <strong>Publish to</strong>. For some locations, you can choose between the following formats:</p>
<ul>
<li>Markdown: publish the Markdown text on a website that can interpret it (<strong>GitHub</strong> for instance),</li>
<li>HTML: publish the file converted to HTML via a Handlebars template (on a blog for example).</li>
</ul>
<h2 id="update-a-publication">Update a publication</h2>
<p>After publishing, StackEdit keeps your file linked to that publication which makes it easy for you to re-publish it. Once you have modified your file and you want to update your publication, click on the <strong>Publish now</strong> button in the navigation bar.</p>
<blockquote>
<p><strong>Note:</strong> The <strong>Publish now</strong> button is disabled if your file has not been published yet.</p>
</blockquote>
<h2 id="manage-file-publication">Manage file publication</h2>
<p>Since one file can be published to multiple locations, you can list and manage publish locations by clicking <strong>File publication</strong> in the <strong>Publish</strong> sub-menu. This allows you to list and remove publication locations that are linked to your file.</p>
<h1 id="markdown-extensions">Markdown extensions</h1>
<p>StackEdit extends the standard Markdown syntax by adding extra <strong>Markdown extensions</strong>, providing you with some nice features.</p>
<blockquote>
<p><strong>ProTip:</strong> You can disable any <strong>Markdown extension</strong> in the <strong>File properties</strong> dialog.</p>
</blockquote>
<h2 id="smartypants">SmartyPants</h2>
<p>SmartyPants converts ASCII punctuation characters into “smart” typographic punctuation HTML entities. For example:</p>

<table>
<thead>
<tr>
<th></th>
<th>ASCII</th>
<th>HTML</th>
</tr>
</thead>
<tbody>
<tr>
<td>Single backticks</td>
<td><code>'Isn't this fun?'</code></td>
<td>‘Isn’t this fun?’</td>
</tr>
<tr>
<td>Quotes</td>
<td><code>"Isn't this fun?"</code></td>
<td>“Isn’t this fun?”</td>
</tr>
<tr>
<td>Dashes</td>
<td><code>-- is en-dash, --- is em-dash</code></td>
<td>– is en-dash, — is em-dash</td>
</tr>
</tbody>
</table><h2 id="katex">KaTeX</h2>
<p>You can render LaTeX mathematical expressions using <a href="https://khan.github.io/KaTeX/">KaTeX</a>:</p>
<p>The <em>Gamma function</em> satisfying <span class="katex--inline"><span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi mathvariant="normal">Γ</mi><mo stretchy="false">(</mo><mi>n</mi><mo stretchy="false">)</mo><mo>=</mo><mo stretchy="false">(</mo><mi>n</mi><mo>−</mo><mn>1</mn><mo stretchy="false">)</mo><mo stretchy="false">!</mo><mspace width="1em"></mspace><mi mathvariant="normal">∀</mi><mi>n</mi><mo>∈</mo><mi mathvariant="double-struck">N</mi></mrow><annotation encoding="application/x-tex">\Gamma(n) = (n-1)!\quad\forall n\in\mathbb N</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height: 1em; vertical-align: -0.25em;"></span><span class="mord">Γ</span><span class="mopen">(</span><span class="mord mathnormal">n</span><span class="mclose">)</span><span class="mspace" style="margin-right: 0.277778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right: 0.277778em;"></span></span><span class="base"><span class="strut" style="height: 1em; vertical-align: -0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal">n</span><span class="mspace" style="margin-right: 0.222222em;"></span><span class="mbin">−</span><span class="mspace" style="margin-right: 0.222222em;"></span></span><span class="base"><span class="strut" style="height: 1em; vertical-align: -0.25em;"></span><span class="mord">1</span><span class="mclose">)!</span><span class="mspace" style="margin-right: 1em;"></span><span class="mord">∀</span><span class="mord mathnormal">n</span><span class="mspace" style="margin-right: 0.277778em;"></span><span class="mrel">∈</span><span class="mspace" style="margin-right: 0.277778em;"></span></span><span class="base"><span class="strut" style="height: 0.68889em; vertical-align: 0em;"></span><span class="mord mathbb">N</span></span></span></span></span> is via the Euler integral</p>
<p><span class="katex--display"><span class="katex-display"><span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><semantics><mrow><mi mathvariant="normal">Γ</mi><mo stretchy="false">(</mo><mi>z</mi><mo stretchy="false">)</mo><mo>=</mo><msubsup><mo>∫</mo><mn>0</mn><mi mathvariant="normal">∞</mi></msubsup><msup><mi>t</mi><mrow><mi>z</mi><mo>−</mo><mn>1</mn></mrow></msup><msup><mi>e</mi><mrow><mo>−</mo><mi>t</mi></mrow></msup><mi>d</mi><mi>t</mi> <mi mathvariant="normal">.</mi></mrow><annotation encoding="application/x-tex">
\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.
</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height: 1em; vertical-align: -0.25em;"></span><span class="mord">Γ</span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right: 0.04398em;">z</span><span class="mclose">)</span><span class="mspace" style="margin-right: 0.277778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right: 0.277778em;"></span></span><span class="base"><span class="strut" style="height: 2.32624em; vertical-align: -0.91195em;"></span><span class="mop"><span class="mop op-symbol large-op" style="margin-right: 0.44445em; position: relative; top: -0.001125em;">∫</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height: 1.41429em;"><span class="" style="top: -1.78805em; margin-left: -0.44445em; margin-right: 0.05em;"><span class="pstrut" style="height: 2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span><span class="" style="top: -3.8129em; margin-right: 0.05em;"><span class="pstrut" style="height: 2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">∞</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height: 0.91195em;"><span class=""></span></span></span></span></span></span><span class="mspace" style="margin-right: 0.166667em;"></span><span class="mord"><span class="mord mathnormal">t</span><span class="msupsub"><span class="vlist-t"><span class="vlist-r"><span class="vlist" style="height: 0.864108em;"><span class="" style="top: -3.113em; margin-right: 0.05em;"><span class="pstrut" style="height: 2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord mathnormal mtight" style="margin-right: 0.04398em;">z</span><span class="mbin mtight">−</span><span class="mord mtight">1</span></span></span></span></span></span></span></span></span><span class="mord"><span class="mord mathnormal">e</span><span class="msupsub"><span class="vlist-t"><span class="vlist-r"><span class="vlist" style="height: 0.843556em;"><span class="" style="top: -3.113em; margin-right: 0.05em;"><span class="pstrut" style="height: 2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord mtight">−</span><span class="mord mathnormal mtight">t</span></span></span></span></span></span></span></span></span><span class="mord mathnormal">d</span><span class="mord mathnormal">t</span><span class="mspace" style="margin-right: 0.166667em;"></span><span class="mord">.</span></span></span></span></span></span></p>
<blockquote>
<p>You can find more information about <strong>LaTeX</strong> mathematical expressions <a href="http://meta.math.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference">here</a>.</p>
</blockquote>
<h2 id="uml-diagrams">UML diagrams</h2>
<p>You can render UML diagrams using <a href="https://mermaidjs.github.io/">Mermaid</a>. For example, this will produce a sequence diagram:</p>
<pre class=" language-mermaid"><svg id="mermaid-svg-zv5HdxOFjVJcPIrd" width="100%" xmlns="http://www.w3.org/2000/svg" height="567" style="max-width: 843px;" viewBox="-50 -10 843 567"><style>#mermaid-svg-zv5HdxOFjVJcPIrd{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:16px;fill:#000000;}#mermaid-svg-zv5HdxOFjVJcPIrd .error-icon{fill:#552222;}#mermaid-svg-zv5HdxOFjVJcPIrd .error-text{fill:#552222;stroke:#552222;}#mermaid-svg-zv5HdxOFjVJcPIrd .edge-thickness-normal{stroke-width:2px;}#mermaid-svg-zv5HdxOFjVJcPIrd .edge-thickness-thick{stroke-width:3.5px;}#mermaid-svg-zv5HdxOFjVJcPIrd .edge-pattern-solid{stroke-dasharray:0;}#mermaid-svg-zv5HdxOFjVJcPIrd .edge-pattern-dashed{stroke-dasharray:3;}#mermaid-svg-zv5HdxOFjVJcPIrd .edge-pattern-dotted{stroke-dasharray:2;}#mermaid-svg-zv5HdxOFjVJcPIrd .marker{fill:#666;stroke:#666;}#mermaid-svg-zv5HdxOFjVJcPIrd .marker.cross{stroke:#666;}#mermaid-svg-zv5HdxOFjVJcPIrd svg{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:16px;}#mermaid-svg-zv5HdxOFjVJcPIrd .actor{stroke:hsl(0,0%,83%);fill:#eee;}#mermaid-svg-zv5HdxOFjVJcPIrd text.actor > tspan{fill:#333;stroke:none;}#mermaid-svg-zv5HdxOFjVJcPIrd .actor-line{stroke:#666;}#mermaid-svg-zv5HdxOFjVJcPIrd .messageLine0{stroke-width:1.5;stroke-dasharray:none;stroke:#333;}#mermaid-svg-zv5HdxOFjVJcPIrd .messageLine1{stroke-width:1.5;stroke-dasharray:2,2;stroke:#333;}#mermaid-svg-zv5HdxOFjVJcPIrd #arrowhead path{fill:#333;stroke:#333;}#mermaid-svg-zv5HdxOFjVJcPIrd .sequenceNumber{fill:white;}#mermaid-svg-zv5HdxOFjVJcPIrd #sequencenumber{fill:#333;}#mermaid-svg-zv5HdxOFjVJcPIrd #crosshead path{fill:#333;stroke:#333;}#mermaid-svg-zv5HdxOFjVJcPIrd .messageText{fill:#333;stroke:#333;}#mermaid-svg-zv5HdxOFjVJcPIrd .labelBox{stroke:hsl(0,0%,83%);fill:#eee;}#mermaid-svg-zv5HdxOFjVJcPIrd .labelText,#mermaid-svg-zv5HdxOFjVJcPIrd .labelText > tspan{fill:#333;stroke:none;}#mermaid-svg-zv5HdxOFjVJcPIrd .loopText,#mermaid-svg-zv5HdxOFjVJcPIrd .loopText > tspan{fill:#333;stroke:none;}#mermaid-svg-zv5HdxOFjVJcPIrd .loopLine{stroke-width:2px;stroke-dasharray:2,2;stroke:hsl(0,0%,83%);fill:hsl(0,0%,83%);}#mermaid-svg-zv5HdxOFjVJcPIrd .note{stroke:hsl(60,100%,23.3333333333%);fill:#ffa;}#mermaid-svg-zv5HdxOFjVJcPIrd .noteText,#mermaid-svg-zv5HdxOFjVJcPIrd .noteText > tspan{fill:#333;stroke:none;}#mermaid-svg-zv5HdxOFjVJcPIrd .activation0{fill:#f4f4f4;stroke:#666;}#mermaid-svg-zv5HdxOFjVJcPIrd .activation1{fill:#f4f4f4;stroke:#666;}#mermaid-svg-zv5HdxOFjVJcPIrd .activation2{fill:#f4f4f4;stroke:#666;}#mermaid-svg-zv5HdxOFjVJcPIrd:root{--mermaid-font-family:"trebuchet ms",verdana,arial,sans-serif;}#mermaid-svg-zv5HdxOFjVJcPIrd sequence{fill:apa;}</style><g></g><g><line id="actor18" x1="75" y1="5" x2="75" y2="556" class="actor-line" stroke-width="0.5px" stroke="#999"></line><rect x="0" y="0" fill="#eaeaea" stroke="#666" width="150" height="65" rx="3" ry="3" class="actor"></rect><text x="75" y="32.5" dominant-baseline="central" alignment-baseline="central" class="actor" style="text-anchor: middle; font-size: 14px; font-weight: 400; font-family: Open-Sans, &quot;sans-serif&quot;;"><tspan x="75" dy="0">Alice</tspan></text></g><g><line id="actor19" x1="331" y1="5" x2="331" y2="556" class="actor-line" stroke-width="0.5px" stroke="#999"></line><rect x="256" y="0" fill="#eaeaea" stroke="#666" width="150" height="65" rx="3" ry="3" class="actor"></rect><text x="331" y="32.5" dominant-baseline="central" alignment-baseline="central" class="actor" style="text-anchor: middle; font-size: 14px; font-weight: 400; font-family: Open-Sans, &quot;sans-serif&quot;;"><tspan x="331" dy="0">Bob</tspan></text></g><g><line id="actor20" x1="568" y1="5" x2="568" y2="556" class="actor-line" stroke-width="0.5px" stroke="#999"></line><rect x="493" y="0" fill="#eaeaea" stroke="#666" width="150" height="65" rx="3" ry="3" class="actor"></rect><text x="568" y="32.5" dominant-baseline="central" alignment-baseline="central" class="actor" style="text-anchor: middle; font-size: 14px; font-weight: 400; font-family: Open-Sans, &quot;sans-serif&quot;;"><tspan x="568" dy="0">John</tspan></text></g><defs><marker id="arrowhead" refX="9" refY="5" markerUnits="userSpaceOnUse" markerWidth="12" markerHeight="12" orient="auto"><path d="M 0 0 L 10 5 L 0 10 z"></path></marker></defs><defs><marker id="crosshead" markerWidth="15" markerHeight="8" orient="auto" refX="16" refY="4"><path fill="black" stroke="#000000" stroke-width="1px" d="M 9,2 V 6 L16,4 Z" style="stroke-dasharray: 0, 0;"></path><path fill="none" stroke="#000000" stroke-width="1px" d="M 0,1 L 6,7 M 6,1 L 0,7" style="stroke-dasharray: 0, 0;"></path></marker></defs><defs><marker id="filled-head" refX="18" refY="7" markerWidth="20" markerHeight="28" orient="auto"><path d="M 18,7 L9,13 L14,7 L9,1 Z"></path></marker></defs><defs><marker id="sequencenumber" refX="15" refY="15" markerWidth="60" markerHeight="40" orient="auto"><circle cx="15" cy="15" r="6"></circle></marker></defs><text x="203" y="80" text-anchor="middle" dominant-baseline="middle" alignment-baseline="middle" class="messageText" dy="1em" style="font-family: &quot;trebuchet ms&quot;, verdana, arial, sans-serif; font-size: 16px; font-weight: 400;">Hello Bob, how are you?</text><line x1="75" y1="117" x2="331" y2="117" class="messageLine0" stroke-width="2" stroke="none" marker-end="url(#arrowhead)" style="fill: none;"></line><text x="450" y="132" text-anchor="middle" dominant-baseline="middle" alignment-baseline="middle" class="messageText" dy="1em" style="font-family: &quot;trebuchet ms&quot;, verdana, arial, sans-serif; font-size: 16px; font-weight: 400;">How about you John?</text><line x1="331" y1="169" x2="568" y2="169" class="messageLine1" stroke-width="2" stroke="none" marker-end="url(#arrowhead)" style="stroke-dasharray: 3, 3; fill: none;"></line><text x="203" y="184" text-anchor="middle" dominant-baseline="middle" alignment-baseline="middle" class="messageText" dy="1em" style="font-family: &quot;trebuchet ms&quot;, verdana, arial, sans-serif; font-size: 16px; font-weight: 400;">I am good thanks!</text><line x1="331" y1="221" x2="75" y2="221" class="messageLine1" stroke-width="2" stroke="none" marker-end="url(#crosshead)" style="stroke-dasharray: 3, 3; fill: none;"></line><text x="450" y="236" text-anchor="middle" dominant-baseline="middle" alignment-baseline="middle" class="messageText" dy="1em" style="font-family: &quot;trebuchet ms&quot;, verdana, arial, sans-serif; font-size: 16px; font-weight: 400;">I am good thanks!</text><line x1="331" y1="273" x2="568" y2="273" class="messageLine0" stroke-width="2" stroke="none" marker-end="url(#crosshead)" style="fill: none;"></line><g><rect x="593" y="283" fill="#EDF2AE" stroke="#666" width="150" height="84" rx="0" ry="0" class="note"></rect><text x="668" y="288" text-anchor="middle" dominant-baseline="middle" alignment-baseline="middle" class="noteText" dy="1em" style="font-family: &quot;trebuchet ms&quot;, verdana, arial, sans-serif; font-size: 14px; font-weight: 400;"><tspan x="668">Bob thinks a long</tspan></text><text x="668" y="304" text-anchor="middle" dominant-baseline="middle" alignment-baseline="middle" class="noteText" dy="1em" style="font-family: &quot;trebuchet ms&quot;, verdana, arial, sans-serif; font-size: 14px; font-weight: 400;"><tspan x="668">long time, so long</tspan></text><text x="668" y="320" text-anchor="middle" dominant-baseline="middle" alignment-baseline="middle" class="noteText" dy="1em" style="font-family: &quot;trebuchet ms&quot;, verdana, arial, sans-serif; font-size: 14px; font-weight: 400;"><tspan x="668">that the text does</tspan></text><text x="668" y="336" text-anchor="middle" dominant-baseline="middle" alignment-baseline="middle" class="noteText" dy="1em" style="font-family: &quot;trebuchet ms&quot;, verdana, arial, sans-serif; font-size: 14px; font-weight: 400;"><tspan x="668">not fit on a row.</tspan></text></g><text x="203" y="382" text-anchor="middle" dominant-baseline="middle" alignment-baseline="middle" class="messageText" dy="1em" style="font-family: &quot;trebuchet ms&quot;, verdana, arial, sans-serif; font-size: 16px; font-weight: 400;">Checking with John...</text><line x1="331" y1="419" x2="75" y2="419" class="messageLine1" stroke-width="2" stroke="none" style="stroke-dasharray: 3, 3; fill: none;"></line><text x="322" y="434" text-anchor="middle" dominant-baseline="middle" alignment-baseline="middle" class="messageText" dy="1em" style="font-family: &quot;trebuchet ms&quot;, verdana, arial, sans-serif; font-size: 16px; font-weight: 400;">Yes... John, how are you?</text><line x1="75" y1="471" x2="568" y2="471" class="messageLine0" stroke-width="2" stroke="none" style="fill: none;"></line><g><rect x="0" y="491" fill="#eaeaea" stroke="#666" width="150" height="65" rx="3" ry="3" class="actor"></rect><text x="75" y="523.5" dominant-baseline="central" alignment-baseline="central" class="actor" style="text-anchor: middle; font-size: 14px; font-weight: 400; font-family: Open-Sans, &quot;sans-serif&quot;;"><tspan x="75" dy="0">Alice</tspan></text></g><g><rect x="256" y="491" fill="#eaeaea" stroke="#666" width="150" height="65" rx="3" ry="3" class="actor"></rect><text x="331" y="523.5" dominant-baseline="central" alignment-baseline="central" class="actor" style="text-anchor: middle; font-size: 14px; font-weight: 400; font-family: Open-Sans, &quot;sans-serif&quot;;"><tspan x="331" dy="0">Bob</tspan></text></g><g><rect x="493" y="491" fill="#eaeaea" stroke="#666" width="150" height="65" rx="3" ry="3" class="actor"></rect><text x="568" y="523.5" dominant-baseline="central" alignment-baseline="central" class="actor" style="text-anchor: middle; font-size: 14px; font-weight: 400; font-family: Open-Sans, &quot;sans-serif&quot;;"><tspan x="568" dy="0">John</tspan></text></g></svg></pre>
<p>And this will produce a flow chart:</p>
<pre class=" language-mermaid"><svg id="mermaid-svg-G5Id4WRH03KYy7OK" width="100%" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" height="174.4375" style="max-width: 502.74749755859375px;" viewBox="0 0 502.74749755859375 174.4375"><style>#mermaid-svg-G5Id4WRH03KYy7OK{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:16px;fill:#000000;}#mermaid-svg-G5Id4WRH03KYy7OK .error-icon{fill:#552222;}#mermaid-svg-G5Id4WRH03KYy7OK .error-text{fill:#552222;stroke:#552222;}#mermaid-svg-G5Id4WRH03KYy7OK .edge-thickness-normal{stroke-width:2px;}#mermaid-svg-G5Id4WRH03KYy7OK .edge-thickness-thick{stroke-width:3.5px;}#mermaid-svg-G5Id4WRH03KYy7OK .edge-pattern-solid{stroke-dasharray:0;}#mermaid-svg-G5Id4WRH03KYy7OK .edge-pattern-dashed{stroke-dasharray:3;}#mermaid-svg-G5Id4WRH03KYy7OK .edge-pattern-dotted{stroke-dasharray:2;}#mermaid-svg-G5Id4WRH03KYy7OK .marker{fill:#666;stroke:#666;}#mermaid-svg-G5Id4WRH03KYy7OK .marker.cross{stroke:#666;}#mermaid-svg-G5Id4WRH03KYy7OK svg{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:16px;}#mermaid-svg-G5Id4WRH03KYy7OK .label{font-family:"trebuchet ms",verdana,arial,sans-serif;color:#000000;}#mermaid-svg-G5Id4WRH03KYy7OK .cluster-label text{fill:#333;}#mermaid-svg-G5Id4WRH03KYy7OK .cluster-label span{color:#333;}#mermaid-svg-G5Id4WRH03KYy7OK .label text,#mermaid-svg-G5Id4WRH03KYy7OK span{fill:#000000;color:#000000;}#mermaid-svg-G5Id4WRH03KYy7OK .node rect,#mermaid-svg-G5Id4WRH03KYy7OK .node circle,#mermaid-svg-G5Id4WRH03KYy7OK .node ellipse,#mermaid-svg-G5Id4WRH03KYy7OK .node polygon,#mermaid-svg-G5Id4WRH03KYy7OK .node path{fill:#eee;stroke:#999;stroke-width:1px;}#mermaid-svg-G5Id4WRH03KYy7OK .node .label{text-align:center;}#mermaid-svg-G5Id4WRH03KYy7OK .node.clickable{cursor:pointer;}#mermaid-svg-G5Id4WRH03KYy7OK .arrowheadPath{fill:#333333;}#mermaid-svg-G5Id4WRH03KYy7OK .edgePath .path{stroke:#666;stroke-width:1.5px;}#mermaid-svg-G5Id4WRH03KYy7OK .flowchart-link{stroke:#666;fill:none;}#mermaid-svg-G5Id4WRH03KYy7OK .edgeLabel{background-color:white;text-align:center;}#mermaid-svg-G5Id4WRH03KYy7OK .edgeLabel rect{opacity:0.5;background-color:white;fill:white;}#mermaid-svg-G5Id4WRH03KYy7OK .cluster rect{fill:hsl(210,66.6666666667%,95%);stroke:#26a;stroke-width:1px;}#mermaid-svg-G5Id4WRH03KYy7OK .cluster text{fill:#333;}#mermaid-svg-G5Id4WRH03KYy7OK .cluster span{color:#333;}#mermaid-svg-G5Id4WRH03KYy7OK div.mermaidTooltip{position:absolute;text-align:center;max-width:200px;padding:2px;font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:12px;background:hsl(-160,0%,93.3333333333%);border:1px solid #26a;border-radius:2px;pointer-events:none;z-index:100;}#mermaid-svg-G5Id4WRH03KYy7OK:root{--mermaid-font-family:"trebuchet ms",verdana,arial,sans-serif;}#mermaid-svg-G5Id4WRH03KYy7OK flowchart{fill:apa;}</style><g><g class="output"><g class="clusters"></g><g class="edgePaths"><g class="edgePath LS-A LE-B" style="opacity: 1;" id="L-A-B"><path class="path" d="M109.65658351563049,67.6156234741211L170.05624961853027,38.86249923706055L246.12499809265137,38.86249923706055" marker-end="url(https://stackedit.io/app#arrowhead25)" style="fill:none"></path><defs><marker id="arrowhead25" viewBox="0 0 10 10" refX="9" refY="5" markerUnits="strokeWidth" markerWidth="8" markerHeight="6" orient="auto"><path d="M 0 0 L 10 5 L 0 10 z" class="arrowheadPath" style="stroke-width: 1; stroke-dasharray: 1, 0;"></path></marker></defs></g><g class="edgePath LS-A LE-C" style="opacity: 1;" id="L-A-C"><path class="path" d="M109.65658351563049,114.328125L170.05624961853027,143.08124923706055L226.92499923706055,143.08124923706055" marker-end="url(https://stackedit.io/app#arrowhead26)" style="fill:none"></path><defs><marker id="arrowhead26" viewBox="0 0 10 10" refX="9" refY="5" markerUnits="strokeWidth" markerWidth="8" markerHeight="6" orient="auto"><path d="M 0 0 L 10 5 L 0 10 z" class="arrowheadPath" style="stroke-width: 1; stroke-dasharray: 1, 0;"></path></marker></defs></g><g class="edgePath LS-B LE-D" style="opacity: 1;" id="L-B-D"><path class="path" d="M307.8500003814697,38.86249923706055L352.04999923706055,38.86249923706055L400.10526402645604,68.91660820788849" marker-end="url(https://stackedit.io/app#arrowhead27)" style="fill:none"></path><defs><marker id="arrowhead27" viewBox="0 0 10 10" refX="9" refY="5" markerUnits="strokeWidth" markerWidth="8" markerHeight="6" orient="auto"><path d="M 0 0 L 10 5 L 0 10 z" class="arrowheadPath" style="stroke-width: 1; stroke-dasharray: 1, 0;"></path></marker></defs></g><g class="edgePath LS-C LE-D" style="opacity: 1;" id="L-C-D"><path class="path" d="M327.04999923706055,143.08124923706055L352.04999923706055,143.08124923706055L400.105265555658,114.02713931588139" marker-end="url(https://stackedit.io/app#arrowhead28)" style="fill:none"></path><defs><marker id="arrowhead28" viewBox="0 0 10 10" refX="9" refY="5" markerUnits="strokeWidth" markerWidth="8" markerHeight="6" orient="auto"><path d="M 0 0 L 10 5 L 0 10 z" class="arrowheadPath" style="stroke-width: 1; stroke-dasharray: 1, 0;"></path></marker></defs></g></g><g class="edgeLabels"><g class="edgeLabel" style="opacity: 1;" transform="translate(170.05624961853027,38.86249923706055)"><g transform="translate(-31.868749618530273,-13.356249809265137)" class="label"><rect rx="0" ry="0" width="63.73749923706055" height="26.712499618530273"></rect><foreignObject width="63.73749923706055" height="26.712499618530273"><div xmlns="http://www.w3.org/1999/xhtml" style="display: inline-block; white-space: nowrap;"><span id="L-L-A-B" class="edgeLabel L-LS-A' L-LE-B">Link text</span></div></foreignObject></g></g><g class="edgeLabel" style="opacity: 1;" transform=""><g transform="translate(0,0)" class="label"><rect rx="0" ry="0" width="0" height="0"></rect><foreignObject width="0" height="0"><div xmlns="http://www.w3.org/1999/xhtml" style="display: inline-block; white-space: nowrap;"><span id="L-L-A-C" class="edgeLabel L-LS-A' L-LE-C"></span></div></foreignObject></g></g><g class="edgeLabel" style="opacity: 1;" transform=""><g transform="translate(0,0)" class="label"><rect rx="0" ry="0" width="0" height="0"></rect><foreignObject width="0" height="0"><div xmlns="http://www.w3.org/1999/xhtml" style="display: inline-block; white-space: nowrap;"><span id="L-L-B-D" class="edgeLabel L-LS-B' L-LE-D"></span></div></foreignObject></g></g><g class="edgeLabel" style="opacity: 1;" transform=""><g transform="translate(0,0)" class="label"><rect rx="0" ry="0" width="0" height="0"></rect><foreignObject width="0" height="0"><div xmlns="http://www.w3.org/1999/xhtml" style="display: inline-block; white-space: nowrap;"><span id="L-L-C-D" class="edgeLabel L-LS-C' L-LE-D"></span></div></foreignObject></g></g></g><g class="nodes"><g class="node default" style="opacity: 1;" id="flowchart-A-104" transform="translate(60.59375,90.97187423706055)"><rect rx="0" ry="0" x="-52.59375" y="-23.356249809265137" width="105.1875" height="46.71249961853027" class="label-container"></rect><g class="label" transform="translate(0,0)"><g transform="translate(-42.59375,-13.356249809265137)"><foreignObject width="85.1875" height="26.712499618530273"><div xmlns="http://www.w3.org/1999/xhtml" style="display: inline-block; white-space: nowrap;">Square Rect</div></foreignObject></g></g></g><g class="node default" style="opacity: 1;" id="flowchart-B-105" transform="translate(276.98749923706055,38.86249923706055)"><circle x="-30.86250114440918" y="-23.356249809265137" r="30.86250114440918" class="label-container"></circle><g class="label" transform="translate(0,0)"><g transform="translate(-20.86250114440918,-13.356249809265137)"><foreignObject width="41.72500228881836" height="26.712499618530273"><div xmlns="http://www.w3.org/1999/xhtml" style="display: inline-block; white-space: nowrap;">Circle</div></foreignObject></g></g></g><g class="node default" style="opacity: 1;" id="flowchart-C-107" transform="translate(276.98749923706055,143.08124923706055)"><rect rx="5" ry="5" x="-50.0625" y="-23.356249809265137" width="100.125" height="46.71249961853027" class="label-container"></rect><g class="label" transform="translate(0,0)"><g transform="translate(-40.0625,-13.356249809265137)"><foreignObject width="80.125" height="26.712499618530273"><div xmlns="http://www.w3.org/1999/xhtml" style="display: inline-block; white-space: nowrap;">Round Rect</div></foreignObject></g></g></g><g class="node default" style="opacity: 1;" id="flowchart-D-109" transform="translate(435.8987503051758,90.97187423706055)"><polygon points="58.848749828338626,0 117.69749965667725,-58.848749828338626 58.848749828338626,-117.69749965667725 0,-58.848749828338626" transform="translate(-58.848749828338626,58.848749828338626)" class="label-container"></polygon><g class="label" transform="translate(0,0)"><g transform="translate(-32.03125,-13.356249809265137)"><foreignObject width="64.0625" height="26.712499618530273"><div xmlns="http://www.w3.org/1999/xhtml" style="display: inline-block; white-space: nowrap;">Rhombus</div></foreignObject></g></g></g></g></g></g></svg></pre>

