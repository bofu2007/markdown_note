---


---

<h1 id="neon-tutorials-with-hardhat">Neon tutorials with Hardhat</h1>
<p>This directory contains several examples to deploy smart contracts on Neon EVM Devnet or Mainnet.</p>
<h2 id="install-the-required-dependencies">Install the required dependencies</h2>
<pre class=" language-sh"><code class="prism  language-sh">npm install
</code></pre>
<h2 id="deploy-scripts">Deploy scripts</h2>
<h3 id="testchainlink-script">TestChainlink script</h3>
<pre class=" language-sh"><code class="prism  language-sh">npx hardhat run scripts/TestChainlink/deploy.js --network neondevnet
</code></pre>
<h3 id="testerc20-scripts">TestERC20 scripts</h3>
<ol>
<li>Deploy TestERC20.sol</li>
</ol>
<pre class=" language-sh"><code class="prism  language-sh">npx hardhat run scripts/TestERC20/deploy.js --network neondevnet
</code></pre>
<ol start="2">
<li>Initiate a transfer from the deployer address to a randomly generated address.</li>
</ol>
<pre class=" language-sh"><code class="prism  language-sh">npx hardhat run scripts/TestERC20/transfer.js --network neondevnet
</code></pre>
<h3 id="testerc721-scripts">TestERC721 scripts</h3>
<ol>
<li>Deploy TestERC721.sol</li>
</ol>
<pre class=" language-sh"><code class="prism  language-sh">npx hardhat run scripts/TestERC721/deploy.js --network neondevnet
</code></pre>
<ol start="2">
<li>Paste the deployed contract address from the above step in the <code>mint.js</code> file and mint some NFTs to the deployer address.</li>
</ol>
<pre class=" language-sh"><code class="prism  language-sh">npx hardhat run scripts/TestERC721/mint.js --network neondevnet
</code></pre>
<h3 id="testreadsolanadata-scripts">TestReadSolanaData scripts</h3>
<ol>
<li>Read Pyth price feeds from Solana</li>
</ol>
<pre class=" language-sh"><code class="prism  language-sh">npx hardhat run scripts/TestReadSolanaData/TestReadPythPriceFeed.js --network neondevnet
</code></pre>
<ol start="2">
<li>Read token account data from Solana</li>
</ol>
<pre class=" language-sh"><code class="prism  language-sh">npx hardhat run scripts/TestReadSolanaData/TestReadTokenAccountData.js --network neondevnet
</code></pre>
<h2 id="verify-smart-contracts-on-neonscan">Verify smart contracts on NeonScan</h2>
<pre class=" language-sh"><code class="prism  language-sh">npx hardhat verify --network neondevnet &lt;CONTRACT_ADDRESS&gt;
</code></pre>
<p>If the smart contract has constructor parameters, then the command to verify is -</p>
<pre class=" language-sh"><code class="prism  language-sh">npx hardhat verify --network neondevnet &lt;CONTRACT_ADDRESS&gt; &lt;PARAM_1&gt; &lt;PARAM_2&gt;
</code></pre>
<p><code>&lt;CONTRACT_ADDRESS&gt;</code>, <code>&lt;PARAM_1&gt;</code>, <code>&lt;PARAM_2&gt;</code> should be replaced with the smart contract address deployed and the constructor parameters for it.</p>
<p><strong>Note:</strong> To deploy the smart contracts on Neon EVM Mainnet, <code>--network neondevnet</code> should be replaced by <code>--network neonmainnet</code> while running the hardhat command for running the scripts.</p>
<h4 id="before-starting-make-sure-to-create-.env-file-containing-the-following-data--make-a-copy-of-.env.example-file-and-rename-it-to-.env-">Before starting make sure to create .env file containing the following data ( make a copy of .env.example file and rename it to .env ):</h4>
<pre><code>    PRIVATE_KEY_OWNER=XYZ
</code></pre>
<ul>
<li><em>PRIVATE_KEY_OWNER - the private key used to deploy the contracts.</em></li>
</ul>

