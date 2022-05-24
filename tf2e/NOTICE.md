# ⚠️ IMPORTANT NOTICE ⚠️
If you are using a custom autoexec.cfg, please read and follow the instructions below.

## What happened?
Recently, mastercomfig released [update 9.8.0](https://github.com/mastercomfig/mastercomfig/releases/tag/9.8.0), which requires manual intervention to work. The changes are as follows.

> * **Renamed the `user` folder to `overrides`.**
>   * The `user` folder will still work in this release, but is deprecated and will be removed in a future release.
>   * This change was made because of the existence of the `user.scr` file, which appears as `user` on some systems, causing confusion.
> * Renamed `apply_user` to `apply_overrides`.
>   * `apply_user` will still work in this release, but is deprecated and will be removed in a future release.

As a result, we are asking to all players who are using any custom configuration to follow the instruction below. On 9.8.1 and above, the `user` folder will be deprecated.

## Additional Workaround
You are allowed to skip Step 3 and 4 if you have already installed releases 9.8.0 and above.

1. Head to C:\Program Data (x86)\Steam\steamapps\common\Team Fortress 2\tf\cfg.
2. Rename existing `user` folder to `overrides` (case-sensitive).
3. Head to the [mastercomfig download page](https://mastercomfig.com/app) and install the preset .vpk file you downloaded before.
4. Move the .vpk file to custom, and overwrite the old version.
5. Now you are done! Enjoy!

## Note
The Mystic Moonlight Team is not responsible for any issues or problems caused by not following the provided instructions properly. Please do not post any issues about custom script not working with mastercomfig.
