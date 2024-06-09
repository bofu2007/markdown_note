---


---

<h1 id="homebrew-installation-on-ubuntu-20.04-linux">HomeBrew installation on Ubuntu 20.04 Linux</h1>
<h1 id="section"></h1>
<ol>
<li>Open a command terminal</li>
</ol>
<p>Run terminal and then first, issue an update command-</p>
<pre><code>sudo apt update


sudo apt-get install build-essential
</code></pre>
<h1 id="install-git-on-ubuntu-20.04">2. Install Git on Ubuntu 20.04</h1>
<p>For setting up LinuxBrew on Ubuntu 20.04 or 18.04, we need to install GIT on our system, here is the command for that…</p>
<pre><code>sudo apt install git -y
</code></pre>
<h1 id="run-homebrew-installation-script">3. Run Homebrew installation script</h1>
<p>The official website of Brew offers a pre-build script to install download and install Homebrew using the command line on any available Linux such as CentOS, RHEL, OpenSUSE, Linux Mint, Kali, MX Linux, POP!OS and others.<br>
Here is the command, just run it-</p>
<pre><code>/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
</code></pre>
<h1 id="add-homebrew-to-your-path">4. Add Homebrew to your PATH</h1>
<p>To run the brew command after installation, we need to add it to our system path…</p>
<pre><code>eval "$(/home/linuxbrew/.linuxbrew/bin/brew shellenv)"
</code></pre>
<h1 id="check-brew-is-working-fine">5. Check Brew is working fine</h1>
<p>To ensure everything is working correctly to use brew, we can run its command-</p>
<p>brew doctor</p>
<p>It may give the warning to install GCC and to remove that simply install it using brew-</p>
<pre><code>brew install gcc
</code></pre>
<h1 id="uninstall-it-from-linux">6. Uninstall it from Linux</h1>
<p>If you want to remove Homebrew, then here is the brew uninstallation script, also available on GitHub.</p>
<pre><code>/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/uninstall.sh)"
</code></pre>
<p><strong>Source:</strong><br>
<a href="https://www.how2shout.com/linux/how-to-install-brew-ubuntu-20-04-lts-linux/"><em>https://www.how2shout.com/linux/how-to-install-brew-ubuntu-20-04-lts-linux/</em></a></p>
<blockquote>
<p>Written with <a href="https://stackedit.io/">StackEdit</a>.</p>
</blockquote>

