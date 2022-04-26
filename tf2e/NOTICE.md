# ⚠️ IMPORTANT NOTICE ⚠️
If you are using custom autoexec.cfg, we ask you to read all documents and follow the instruction below.

## What happened?
Recently mastercomfig team released an 9.8.0 [update](https://github.com/mastercomfig/mastercomfig/releases/tag/9.8.0) which requires additional workaround. The changes are as follows.

> * **Renamed the `user` folder to `overrides`.**
>   * The `user` folder will still work in this release, but is deprecated and will be removed in a future release.
>   * This change was made because of the existence of the `user.scr` file, which appears as `user` on some systems, causing confusion.
> * Renamed `apply_user` to `apply_overrides`.
>   * `apply_user` will still work in this release, but is deprecated and will be removed in a future release.

As a result, we are asking to all players who are using the custom configuartion to follow the instruction below. On the 9.8.1 and above version, the `user` folder will be deprecated.

## Additional Workaround
You are allowed to skip Step 3 and 4 if you already installed 9.8.0 and above releases.

1. Head to C:\Program Data (x86)\Steam\steamapps\common\Team Fortress 2\tf\cfg
2. Rename existing `user` folder to `overrides` (case-sensitive)
3. Head to [mastercomfig download page](https://mastercomfig.com/app) and install the preset vpk file you downloaded before.
4. Move the vpk file to custom, and overwrite the old version.
5. Now you are done! Enjoy.

## Note
Mystic Moonlight Team is not responsible for reading this document or following the instruction above. Do not post any issue about custom script not working with mastercomfig.