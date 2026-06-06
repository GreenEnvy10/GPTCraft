# GPTCraft
Add ChatGPT or Claude to Minecraft!

This was made as just a fun little project of mine to test this idea.

Only supports Fabric 1.21.1 for now!
## How to Install
1. Download the latest jar from the [releases](github.com/GreenEnvy10/GPTCraft/releases/latest) page.
2. Copy it into your mods folder. If you don't know how to install mods, check my other tutorial for it [here.](https://github.com/GreenEnvy10/ModLoaderTutorial) **Make sure you have Fabric API installed!**
3. Launch Minecraft.
Ta-da! You have the mod installed!
## How to get an API key
**DISCLAIMER:** Yes, you do need to pay for the API to be able to use ChatGPT or Claude, but it's not actually that expensive.
1. Go to either https://platform.openai.com or https://console.anthropic.com, and login or create an account.
2. Click `Create API Key` or  `Get API Key`.
3. Name your key, leave everything else default, and hit Create. **Make sure to copy your key right away and keep it in your clipboard!**
   * For ChatGPT, go to Profile Settings, Billing, then add a payment method. **Prepaid cards will not work.** Next, click Add to credit balance, input at least 5 dollars, and pay.
   * For Claude, go to Orginization Settings, Billing, then add your payment method. After that, click Buy credits. Again, you can pay a minimum of 5 dollars of credits.
4. Back in Minecraft, type `/ai model <model>`.
   * ChatGPT models: `gpt-5.5`, `gpt-5.4`, `gpt-5.4-mini`
   * Claude models: `claude-{name}-{major}-{minor}`, e.g. `claude-opus-4-x`, `claude-sonnet-4-x`
     * Latest Haiku version: `claude-haiku-4-5-20251001`
5. Type `/ai key <your key>`. Paste in your key from earlier.
Congrats, you now have an LLM in Minecraft.
Press F10 on your keyboard to open the GUI. You can change the keybind in your settings.
