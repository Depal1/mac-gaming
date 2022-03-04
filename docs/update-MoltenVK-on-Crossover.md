Based on a guide by [areapp](https://www.reddit.com/user/areapp/). Edited and published with permission from the origial author by
[Depal1](https://github.com/Depal1).

# Update MoltenVK on Crossover

  1. Go over to https://github.com/Gcenx/MoltenVK/releases/tag/v1.1.7 and downloaded the latest DXVK patched version "macos-<VERSION>.tar.xz".

  2. Unarchive the downloaded file.
  
  3. Locate to CrossOver (don't open the app itself, but go to where it is located).
  Control-click it (right click on it), and press show package contents. This will show you some directories.
  From there, go to /contents/SharedSupport/CrossOver/lib64.
  
  4. There should be libMoltenVK.dylib along with other .dylib files.
  
  5. Open a new finder tab and locate to the unarchived MoltenVk that you downloaded.
  Go into it, then go to Release/MoltenVK/dylib/macOS.
  There should be a libMoltenVK.dylib file inside.
  
  6. Before you replace the MoltenVK, backup up the original CrossOver MoltenVK first.
  
  7. Once backed up, go back to the dylib folder and copy the file libMoltenVK.dylib
  
  8. Go back to the lib64 folder and paste it there, if it says to replace it replace it
  
  9. Now your CrossOver MoltenVK is fully updated
  
## Related resources
  A video guide by Andrew Tsai on [YouTube](https://www.youtube.com/watch?v=5NQQCR74FQE).
  
  A Reddit thread on the same [topic](https://www.reddit.com/r/macgaming/comments/qt4e1b/you_can_run_the_latest_dxvk_with_crossover_on_mac/).
