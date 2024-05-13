---


---

<h1 id="neon-tutorials-with-hardhat">Neon tutorials with Hardhat</h1>
<p><a href="https://github.com/bofu2007/neon-tutorials?tab=readme-ov-file">Neon tutorials</a><br>
This directory contains several examples to deploy smart contracts on Neon EVM Devnet or Mainnet.</p>
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
<h1 id="web3auth-web3authmodal-x-neon-evm-x-react">Web3Auth (<code>@web3auth/modal</code>) x Neon EVM x React</h1>
<p>This example demonstrates how to use Web3Auth with React on Neon EVM chain. For more information on Web3Auth, please follow this link <a href="https://web3auth.io/docs">https://web3auth.io/docs</a>.</p>
<h2 id="install-dependencies-and-start-the-react-application">Install dependencies and start the React application</h2>
<pre class=" language-sh"><code class="prism  language-sh">npm install
npm run start
</code></pre>
<h2 id="features-included-with-this-example">Features included with this example</h2>
<h3 id="ways-of-signing-in">Ways of Signing in</h3>
<p>This Web3Auth example allows you to login via the following ways -</p>
<ol>
<li>Social logins like Google, Facebook, Reddit, Discord, Apple, Github, X, Linkedin and many more.</li>
<li>Email or Phone number.</li>
<li>Metamask wallet.</li>
</ol>
<h3 id="web3-rpc-methods-on-neon-evm">Web3 RPC methods on Neon EVM</h3>
<p>After successfully signing in with any of the above mentioned ways of signing, the following methods can be checked on Neon EVM -</p>
<ol>
<li>
<p><strong>Get Chain ID:</strong> Displays the network chain ID to which the dApp is connected. In this example, it is <code>245022926</code>, which is the chain ID of Neon EVM Devnet.</p>
</li>
<li>
<p><strong>Get Accounts:</strong> Displays the wallet account on Neon EVM Devnet connected to the dApp.</p>
</li>
<li>
<p><strong>Get Balance:</strong> Displays the balance of NEONs for the wallet account that is connected to the dApp.</p>
</li>
<li>
<p><strong>Sign Message:</strong> Signs a message with the connected wallet account and returns the signed message.</p>
</li>
<li>
<p><strong>Send Transaction:</strong> Does a simple NEON transfer from account to another and returns the transaction receipt.</p>
</li>
<li>
<p><strong>Read Contract:</strong> Calls a read-only contract method and returns the result. In this example, it returns a message stored in the simple storage contract <code>0x093451875d5A8D61bB90faA7A8645eB17c86b297</code> deployed on Neon EVM Devnet.</p>
</li>
<li>
<p><strong>Write Contract:</strong> Sends a transaction to the smart contract method and returns the transaction receipt. In this example, the message is updated in the simple storage contract <code>0x093451875d5A8D61bB90faA7A8645eB17c86b297</code> deployed on Neon EVM Devnet.</p>
</li>
<li>
<p><strong>Log Out:</strong> Logs out of the account connected.</p>
</li>
</ol>

