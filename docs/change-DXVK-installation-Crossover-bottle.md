---
layout: default
---

Based on a guide by [areapp](https://www.reddit.com/user/areapp/). Edited and published with permission from the origial author by
[Depal1](https://github.com/Depal1). March 4, 2022.

# Change the DXVK installation on a Crossover Bottle

**Disclaimer: this can either improve or hinder performance on some games. Use with discretion.
It is recommended to have a separate bottle for modified DXVK installations.**

1. Go over to https://github.com/marzent/dxvk (If this doesn't work and gives any issues with your game try another DXVK 'flavor' 
https://github.com/Sporif/dxvk-async or https://github.com/doitsujin/dxvk) and download the latest build.

2. Unarchive the downloaded file.

3. Inside the folder there should be a folder called 'x64'.

4. Open the CrossOver app (The actual app this time) and right click on the bottle you want the updated DXVK for.

5. Press Open C: Drive. This should open a finder tab.

6. From there, go to windows/system32. Copy all the .dll files from the 'x64' folder from step 3.

7. Locate to the system32 folder and paste them there. Replace all the files.

8. Now your DXVK is up to date.

9. Restar your bottle.

## Related resources
  A video guide by Andrew Tsai on [YouTube](https://www.youtube.com/watch?v=5NQQCR74FQE).
  
  A Reddit thread on the same [topic](https://www.reddit.com/r/macgaming/comments/qt4e1b/you_can_run_the_latest_dxvk_with_crossover_on_mac/).

[back](https://depal1.github.io/mac-gaming/)
