client.setSettings({
  workMap: "R-6", // Target map to work on
  killTargets: [
    // Enemy targets with priority
    { name: "-=(Hydro)=-", priority: 1, ammo: 1, rockets: 1, farmNearPortal: false },
    { name: "-=(Hyper|Hidro)=-", priority: 2, ammo: 1, rockets: 1, farmNearPortal: false },
    // More targets...
  ],
  collectBoxTypes: [
    // Box types to collect
    { type: 3, priority: 10 },
    { type: 1, priority: 1 },
  ],
  minHP: 10, // Minimum health percentage
  adviceHP: 70, // Advised health percentage
  kill: {
    targetEngagedNPC: true, // Whether to target already engaged NPCs
  },
  escape: {
    enabled: true, // Enable escape mechanism
    delay: 20000, // Delay before escape
  },
  config: {
    switchConfigOnShieldsDown: true, // Switch config when shields are down
    attacking: 1, // Config for attacking
    fleeing: 2, // Config for fleeing
    flying: 2, // Config for flying
  },
  enrichment: {
    lasers: { enabled: true, materialType: 0 },
    rockets: { enabled: true, materialType: 0 },
    shields: { enabled: true, materialType: 0, amount: 10, minAmount: 10 },
    speed: { enabled: true, materialType: 0, amount: 10, minAmount: 10 },
  },
  autobuy: {
    laser: {
      RLX_1: true,
      GLX_2: true,
      BLX_3: true,
      GLX_2_AS: true,
      MRS_6X: true,
    },
    rockets: {
      KEP_410: true,
      NC_30: true,
      TNC_130: true,
    },
    key: {
      enabled: true,
      savePLT: 50000, // Amount of PLT to save
    },
  },
  break: {
    interval: 3600000, // Break interval (1 hour)
    duration: 300000, // Break duration (5 minutes)
  },
  admin: {
    enabled: true, // Enable admin detection
    delay: 5, // Delay for admin detection processing
  },
});
   <a id="copy-exercise" href="https://github.com/new?template_owner=skills&template_name=introduction-to-github&owner=%40me&name=skills-introduction-to-github&description=Exercise:+Introduction+to+GitHub&visibility=public">
      <img src="https://img.shields.io/badge/📠_Copy_Exercise-008000" height="25pt"/>
   </a>

2. In the new tab, most of the prompts will automatically fill in for you.
   - For owner, choose your personal account or an organization to host the repository.
   - We recommend creating a public repository, as private repositories will [use Actions minutes](https://docs.github.com/en/billing/managing-billing-for-github-actions/about-billing-for-github-actions).
   - Scroll down and click the **Create repository** button at the bottom of the form.

3. After your new repository is created, wait about 20 seconds for the exercise to be prepared and buttons updated. You will continue working from your copy of the exercise.
   - The **Copy Exercise** button will deactivate, changing to gray.
   - The **Start Exercise** button will activate, changing to green.
   - You will likely need to refresh the page.

4. Click **Start Exercise**. Follow the step-by-step instructions and feedback will be provided as you progress.

   <a id="start-exercise">
      <img src="https://img.shields.io/badge/🚀_Start_Exercise-AAA" height="25pt"/>
   </a>

> [!IMPORTANT]
> The **Start Exercise** button will activate after copying the repository. You will probably need to refresh the page.

---

Get help: [Post in our discussion board](https://github.com/orgs/skills/discussions/categories/introduction-to-github) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2024 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)
