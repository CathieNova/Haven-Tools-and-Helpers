<div>
  <button onclick="openTab('welcome')">Welcome</button>
  <button onclick="openTab('features')">Features</button>
  <button onclick="openTab('disclaimer')">Disclaimer</button>
  <button onclick="openTab('mods')">Mods Made with This Tool</button>
</div>

<div id="welcome" class="tab" style="display: block;">
  <h2>Haven Tools & Helpers</h2>
  <p>Welcome to Haven Tools & Helpers, your go-to tools for making modding easier, faster, and more fun!</p>
  <h3>What Can You Do with Haven Tools?</h3>
  <ul>
    <li>Create Quests: Effortlessly design quests for Virtual's Custom Quest Loader (VCQL).</li>
    <li>Craft Hideout Recipes: Simplify crafting mechanics with organized recipes.</li>
    <li>Manage Trader Assorts: Create assortments for traders in minutes.</li>
    <li>Access Item Data: Get details like item prices, flea market values, item info, and more.</li>
    <li>Generate Item Slots: Customize item slots quickly and easily.</li>
  </ul>
  <h3>Support the Project</h3>
  <p>Made a mod or quests using my tools? Want to show appreciation? Write on the modpage that you used my tool, and I will do the same here! ❤️</p>
  <p>Enjoying Haven Tools? Help it grow by supporting development: <a href="#">Support Us</a></p>
  <h3>We Value Your Feedback</h3>
  <p>Have ideas, found a bug, or want to see a new feature? Share it on <a href="#">GitHub</a>.</p>
</div>

<div id="features" class="tab" style="display: none;">
  <h2>Features</h2>
  <ul>
    <li>Quest Maker: Simplify quest creation for Virtual's Custom Quest Loader (VCQL).</li>
    <li>Hideout Crafting Recipes: Create new Hideout recipes with ease.</li>
    <li>Trader Assorts: Generate custom assortments for traders, even load and convert to 3.10!</li>
    <li>Item Database:
      <ul>
        <li>Find trader and flea market item prices.</li>
        <li>Access detailed item information, item groups, quests, and much more.</li>
      </ul>
    </li>
    <li>Item Slot Generator: Create slots in no time.</li>
  </ul>
  <p>Stay tuned for new features in upcoming updates! Check the changelog for the latest additions.</p>
</div>

<div id="disclaimer" class="tab" style="display: none;">
  <h2>⚠️ Disclaimer ⚠️</h2>
  <h3>🚧 Under Development 🚧</h3>
  <p>Not all features are fully tested, use with care!</p>
  <h3>📦 Missing Features 📦</h3>
  <p>Certain planned features are not yet implemented but are on the roadmap!</p>
  <p>Expect future updates to include expanded tools, better databases, and smoother workflows.</p>
  <h3>⚙️ Known Bugs ⚙️</h3>
  <p>You may encounter minor issues, such as UI glitches or unexpected behavior. If you find a bug, report it on <a href="#">GitHub</a>; your feedback helps!</p>
  <h3>💡 Use Responsibly 💡</h3>
  <p>Backup your mods before using the tools. Haven Tools & Helpers is provided "as is"—we're working hard to improve it, but there's no guarantee of perfection! Your support and patience mean everything. Thank you for helping make Haven Tools better!</p>
</div>

<div id="mods" class="tab" style="display: none;">
  <h2>🛠️ Mods Made with Haven Tools 🛠️</h2>
  <p>Want to showcase your mod here? Submit it in the WTT Discord channel: "#cathies-haven-of-tools-and-dreams"!</p>
</div>

<script>
  function openTab(tabId) {
    const tabs = document.querySelectorAll('.tab');
    tabs.forEach(tab => tab.style.display = 'none');
    document.getElementById(tabId).style.display = 'block';
  }
</script>
