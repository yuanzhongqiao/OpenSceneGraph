<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><p dir="auto"><a href="https://travis-ci.org/openscenegraph/OpenSceneGraph" rel="nofollow"><img src="https://camo.githubusercontent.com/6b5e658e69c00a714010201d4c2be6d13d475beb0c0ba843af2ea00d47d27006/68747470733a2f2f7472617669732d63692e6f72672f6f70656e7363656e6567726170682f4f70656e5363656e6547726170682e7376673f6272616e63683d6d6173746572" alt="构建状态" data-canonical-src="https://travis-ci.org/openscenegraph/OpenSceneGraph.svg?branch=master" style="max-width: 100%;"></a>
<a href="https://scan.coverity.com/projects/openscenegraph-openscenegraph" rel="nofollow"><img src="https://camo.githubusercontent.com/7fe03bdddc8555288219f2dd0182d2169b894573edb92c90d31f49f81e62f73e/68747470733a2f2f7363616e2e636f7665726974792e636f6d2f70726f6a656374732f393135392f62616467652e737667" alt="覆盖率状态" data-canonical-src="https://scan.coverity.com/projects/9159/badge.svg" style="max-width: 100%;"></a>
<a href="https://codedocs.xyz/openscenegraph/OpenSceneGraph/" rel="nofollow"><img src="https://camo.githubusercontent.com/22dbb43316fe39e0ad10a99a18af1fb8b5e1d53fdc55a102d660854acfbe9903/68747470733a2f2f636f6465646f63732e78797a2f6f70656e7363656e6567726170682f4f70656e5363656e6547726170682e737667" alt="文档" data-canonical-src="https://codedocs.xyz/openscenegraph/OpenSceneGraph.svg" style="max-width: 100%;"></a>
<a href="https://abi-laboratory.pro/tracker/timeline/openscenegraph/" title="ABI追踪器" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ABI追踪器</font></font></a></p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">介绍</font></font></h1><a id="user-content-introduction" class="anchor-element" aria-label="永久链接：简介" href="#introduction"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">欢迎来到 OpenSceneGraph (OSG)。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关该项目的信息、如何编译和运行库以及示例的详细信息，请参阅 OpenSceneGraph 网站上的文档：</font></font></p>
<p dir="auto"><a href="http://www.openscenegraph.org/index.php/documentation" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">http://www.openscenegraph.org/index.php/documentation</font></font></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如需支持，请使用 github OpenSceneGraph 讨论论坛：</font></font></p>
<p dir="auto"><a href="https://github.com/openscenegraph/OpenSceneGraph/discussions"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://github.com/openscenegraph/OpenSceneGraph/discussions</font></font></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于不耐烦的人，我们在下面提供了快速构建说明，这些说明分为三个部分：</font></font></p>
<ol dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建 OpenSceneGraph 的一般注意事项</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">macOS 发行说明</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">iOS 发行说明</font></font></li>
</ol>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果下面的详细信息还不够，请访问 openscenegraph.org 的 Documentation/GettingStarted 和 Documentation/PlatformSpecifics 部分以获取更深入的说明。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">罗伯特·奥斯菲尔德. </font><font style="vertical-align: inherit;">项目负责人。</font><font style="vertical-align: inherit;">2018 年 4 月 26 日。</font></font></p>
<hr>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">第 1 节. 如何构建 OpenSceneGraph</font></font></h2><a id="user-content-section-1-how-to-build-openscenegraph" class="anchor-element" aria-label="永久链接：第 1 节：如何构建 OpenSceneGraph" href="#section-1-how-to-build-openscenegraph"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您使用</font></font><a href="https://github.com/Microsoft/vcpkg/"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">vcpkg</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">依赖项管理器，您可以使用单个命令从源代码下载并安装 OpenSceneGraph 并与 CMake 集成：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>vcpkg install osg
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="vcpkg install osg" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OpenSceneGraph 使用 CMake 构建系统来生成特定于平台的构建环境。</font><font style="vertical-align: inherit;">CMake 读取</font></font><code>CMakeLists.txt</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您在 OpenSceneGraph 目录中找到的文件，检查已安装的依赖项，然后为所选构建系统生成文件。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您的系统上尚未安装 CMake，您可以从</font></font><a href="http://www.cmake.org" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">http://www.cmake.org</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">获取它，使用 2.8.0 或更高版本。</font><font style="vertical-align: inherit;">有关 OpenSceneGraph 的 CMake 构建的详细信息，请访问：</font></font></p>
<p dir="auto"><a href="http://www.openscenegraph.org/projects/osg/wiki/Build/CMake" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">http://www.openscenegraph.org/projects/osg/wiki/Build/CMake</font></font></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在类 Unix 系统（即 Linux、IRIX、Solaris、Free-BSD、HP-UX、AIX、macOS）下，使用</font></font><code>cmake</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或</font></font><code>ccmake</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">命令行实用程序。</font><font style="vertical-align: inherit;">请注意，</font></font><code>cmake .</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认构建版本以确保您从最终的库/应用程序中获得最佳性能。</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>cd OpenSceneGraph
cmake .
make
sudo make install
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="cd OpenSceneGraph
cmake .
make
sudo make install" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或者，您可以创建一个源外构建目录并从那里运行 cmake 或 ccmake。</font><font style="vertical-align: inherit;">这种方法的优点是 CMake 创建的临时文件不会弄乱 OpenSceneGraph 源目录，并且还可以通过创建多个构建目录来拥有多个独立的构建目标。</font><font style="vertical-align: inherit;">在 OpenSceneGraph 旁边的目录中使用：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>mkdir build
cd build
cmake ../OpenSceneGraph
make
sudo make install
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="mkdir build
cd build
cmake ../OpenSceneGraph
make
sudo make install" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 Windows 下，使用 GUI 工具 CMakeSetup 构建 VisualStudio 文件。</font><font style="vertical-align: inherit;">我们 wiki 上专门介绍 CMake 构建系统的以下页面应该可以帮助指导您完成整个过程：</font></font></p>
<p dir="auto"><a href="http://www.openscenegraph.org/index.php/documentation/platform-specifics/windows" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">http://www.openscenegraph.org/index.php/documentation/platform-specifics/windows</font></font></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 macOS 下，您可以使用上面的 CMake 构建系统，也可以使用在 OpenSceneGraph/Xcode 目录中找到的 Xcode 项目。</font><font style="vertical-align: inherit;">请参阅下面有关 macOS CMake 构建的发行说明。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关编译、安装和平台特定信息的更多详细信息，请阅读“入门”指南：</font></font></p>
<p dir="auto"><a href="http://www.openscenegraph.org/index.php/documentation/10-getting-started" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">http://www.openscenegraph.org/index.php/documentation/10-getting-started</font></font></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">第 2 节：有关 macOS 构建的发行说明，作者：Eric Sokolowski 等人。</font></font></h2><a id="user-content-section-2-release-notes-on-macos-build-by-eric-sokolowski-et-al" class="anchor-element" aria-label="永久链接：第 2 节。有关 macOS 构建的发行说明，作者：Eric Sokolowski 等人。" href="#section-2-release-notes-on-macos-build-by-eric-sokolowski-et-al"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">macOS 下编译 OpenSceneGraph 有两种方法。</font><font style="vertical-align: inherit;">推荐的方法是使用 CMake 生成 Xcode 项目文件，然后使用 Xcode 构建库。</font><font style="vertical-align: inherit;">默认项目将能够构建调试或发布库、示例和示例应用程序。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">另一种方法是使用命令行</font></font><code>make</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或</font></font><code>ninja</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用上述类 Unix 系统的说明从命令行构建 OpenSceneGraph。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以下是使用 CMake 时需要考虑的一些关键设置：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">BUILD_OSG_EXAMPLES - 默认情况下此功能处于关闭状态。</font><font style="vertical-align: inherit;">打开此设置可以编译许多很棒的示例程序。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CMAKE_OSX_ARCHITECTURES - Xcode 可以创建可在多种架构上运行的应用程序、可执行文件、库和框架。</font><font style="vertical-align: inherit;">使用此设置来指示构建 OSG 的架构。</font><font style="vertical-align: inherit;">x86_64 是操作系统版本 &gt; 10.7 唯一支持的值。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OSG_BUILD_APPLICATION_BUNDLES - 通常仅为示例和示例应用程序创建可执行二进制文件。</font><font style="vertical-align: inherit;">如果您想创建真正的 macOS .app 捆绑包，请打开此选项。</font><font style="vertical-align: inherit;">创建捆绑包有一些注意事项</font></font><code>.app</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，请参见下文。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OSG_DEFAULT_IMAGE_PLUGIN_FOR_OSX - 默认情况下，macOS 使用</font></font><code>imageio</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">插件而不是单个文件类型（例如 、 等）的插件</font></font><code>jpg</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">来</font></font><code>gif</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">加载图像文件类型。</font><font style="vertical-align: inherit;">该</font></font><code>imageio</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">插件可以通过ImageIO框架处理所有流行的文件格式。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OSG_WINDOWING_SYSTEM - 在 macOS 上构建应用程序时，您可以选择使用 Cocoa、Carbon 或 X11。</font><font style="vertical-align: inherit;">Cocoa 是操作系统版本 &gt;= 10.5 的默认版本。</font><font style="vertical-align: inherit;">Apple 或 OSG 社区都不再积极支持 Carbon 和 X11。</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">应用程序捆绑包（.app 捆绑包）</font></font></h3><a id="user-content-application-bundles-app-bundles" class="anchor-element" aria-label="永久链接：应用程序捆绑包（.app 捆绑包）" href="#application-bundles-app-bundles"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">示例程序在构建为应用程序包时仅包含可执行文件。</font><font style="vertical-align: inherit;">它们不像普通捆绑包那样包含依赖库，因此它们通常不能移植到其他机器。</font><font style="vertical-align: inherit;">他们也不知道在哪里可以找到插件。</font><font style="vertical-align: inherit;">环境变量 OSG_LIBRARY_PATH 可以设置为指向插件 .so 文件所在的位置。</font><font style="vertical-align: inherit;">OSG_FILE_PATH可以设置为指向数据文件所在的位置。</font><font style="vertical-align: inherit;">通过运行示例程序测试 OSG 时，将 OSG_FILE_PATH 设置为 OpenSceneGraph-Data 目录非常有用。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">许多示例程序都使用命令行参数。</font><font style="vertical-align: inherit;">双击应用程序（或在命令行上使用等效的“打开”命令）时，只有那些不需要命令行参数的示例和应用程序才会成功运行。</font><font style="vertical-align: inherit;">如果需要命令行参数，.app 包中的可执行文件可以从命令行运行。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">第 3 部分：iOS 构建的发行说明，作者：Thomas Hogarth</font></font></h2><a id="user-content-section-3-release-notes-on-ios-build-by-thomas-hogarth" class="anchor-element" aria-label="永久链接：第 3 节。iOS 构建的发行说明，作者：Thomas Hogarth" href="#section-3-release-notes-on-ios-build-by-thomas-hogarth"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装了 CMake 3.11、XCode 9.4 和 iOS sdk 11.4 后，您可以使用以下命令行生成 iOS XCode 项目：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>export THIRDPARTY_PATH=/path/to/3rdParty
cmake ./ -G Xcode -DOSG_BUILD_PLATFORM_IPHONE:BOOL=ON \
-DIPHONE_SDKVER="11.4" \
-DIPHONE_VERSION_MIN="10.0" \
-DOPENGL_PROFILE:STRING=GLES3 \
-DOSG_CPP_EXCEPTIONS_AVAILABLE:BOOL=ON \
-DBUILD_OSG_APPLICATIONS:BOOL=OFF \
-DBUILD_OSG_EXAMPLES:BOOL=ON \
-DOSG_WINDOWING_SYSTEM:STRING=IOS \
-DOSG_DEFAULT_IMAGE_PLUGIN_FOR_OSX="imageio" \
-DDYNAMIC_OPENSCENEGRAPH:BOOL=OFF \
-DDYNAMIC_OPENTHREADS:BOOL=OFF \
-DCURL_INCLUDE_DIR:PATH="$THIRDPARTY_PATH/curl-ios-device/include" \
-DCURL_LIBRARY:PATH="$THIRDPARTY_PATH/curl-ios-device/lib/libcurl.a" \
-DFREETYPE_INCLUDE_DIR_freetype2:PATH="$THIRDPARTY_PATH/freetype-ios-universal/include/freetype" \
-DFREETYPE_INCLUDE_DIR_ft2build:PATH="$THIRDPARTY_PATH/freetype-ios-universal/include" \
-DFREETYPE_LIBRARY:PATH="$THIRDPARTY_PATH/freetype-ios-universal/lib/libFreetype2.a" \
-DTIFF_INCLUDE_DIR:PATH="$THIRDPARTY_PATH/tiff-ios-device/include" \
-DTIFF_LIBRARY:PATH="$THIRDPARTY_PATH/tiff-ios-device/lib/libtiff.a" \
-DGDAL_INCLUDE_DIR:PATH="$THIRDPARTY_PATH/gdal-ios-device/include" \
-DGDAL_LIBRARY:PATH="$THIRDPARTY_PATH/gdal-ios-device/lib/libgdal.a"
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="export THIRDPARTY_PATH=/path/to/3rdParty
cmake ./ -G Xcode -DOSG_BUILD_PLATFORM_IPHONE:BOOL=ON \
-DIPHONE_SDKVER=&quot;11.4&quot; \
-DIPHONE_VERSION_MIN=&quot;10.0&quot; \
-DOPENGL_PROFILE:STRING=GLES3 \
-DOSG_CPP_EXCEPTIONS_AVAILABLE:BOOL=ON \
-DBUILD_OSG_APPLICATIONS:BOOL=OFF \
-DBUILD_OSG_EXAMPLES:BOOL=ON \
-DOSG_WINDOWING_SYSTEM:STRING=IOS \
-DOSG_DEFAULT_IMAGE_PLUGIN_FOR_OSX=&quot;imageio&quot; \
-DDYNAMIC_OPENSCENEGRAPH:BOOL=OFF \
-DDYNAMIC_OPENTHREADS:BOOL=OFF \
-DCURL_INCLUDE_DIR:PATH=&quot;$THIRDPARTY_PATH/curl-ios-device/include&quot; \
-DCURL_LIBRARY:PATH=&quot;$THIRDPARTY_PATH/curl-ios-device/lib/libcurl.a&quot; \
-DFREETYPE_INCLUDE_DIR_freetype2:PATH=&quot;$THIRDPARTY_PATH/freetype-ios-universal/include/freetype&quot; \
-DFREETYPE_INCLUDE_DIR_ft2build:PATH=&quot;$THIRDPARTY_PATH/freetype-ios-universal/include&quot; \
-DFREETYPE_LIBRARY:PATH=&quot;$THIRDPARTY_PATH/freetype-ios-universal/lib/libFreetype2.a&quot; \
-DTIFF_INCLUDE_DIR:PATH=&quot;$THIRDPARTY_PATH/tiff-ios-device/include&quot; \
-DTIFF_LIBRARY:PATH=&quot;$THIRDPARTY_PATH/tiff-ios-device/lib/libtiff.a&quot; \
-DGDAL_INCLUDE_DIR:PATH=&quot;$THIRDPARTY_PATH/gdal-ios-device/include&quot; \
-DGDAL_LIBRARY:PATH=&quot;$THIRDPARTY_PATH/gdal-ios-device/lib/libgdal.a&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请务必将 THIRDPARTY_PATH 设置为包含第三方依赖项的路径。</font><font style="vertical-align: inherit;">将 IPHONE_SDKVER 设置为您已安装的 iOS sdk 版本，在本例中为 11.4。</font><font style="vertical-align: inherit;">IPHONE_VERSION_MIN 控制 xcode 使用的部署 sdk，最后将 OPENGL_PROFILE 设置为您要使用的 GLES 版本。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">完成后，将在 osg 根文件夹中生成 XCode 项目。</font><font style="vertical-align: inherit;">打开生成的 Xcode 项目，选择 example_osgViewerIPhone 目标。</font><font style="vertical-align: inherit;">在“常规”选项卡中设置开发团队。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">完成此操作后，您应该能够</font></font><code>example_osgViewerIPhone</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在设备上构建和部署目标。</font></font></p>
</article></div>
