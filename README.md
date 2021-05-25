# csgo_CrosshairAutoSwitchCFG
> this cfg will easliy make you a clear view for prop while you take out some props.
## some way to use it:
### 1. bilibili & youtube
- You could find a video on [my bilibili channel](https://space.bilibili.com/26380015) or [my youtube channel](https://www.youtube.com/channel/UCIWSXPHoF60euQYEeRdnEhA).

### 2. if you can't find it, it just simply likes follow:
- step 1:
    Download the latest release, and copy the file `~/bin/crosshair_autoexec.cfg` to `~/csgo/cfg/`
    (it's your own csgo path and you could find it by steam :) )
- step 2:
    If my crosshair doesn't suit you, you should open the `crosshair_autoexec.cfg` and change the first alias command:

    ```alias mainch "cl_crosshairdot "0";cl_crosshairgap "-2";cl_crosshairsize "3";"```

    whatever you like.
- step 3:
    Open the your csgo path (same path), find `/config.cfg` (if there's none just create one) and add a command below:

    ``` exec crosshair_autoexec.cfg```
- step 4:
    Enter your game and find the cfg is allright.If not, just give me an issue.
### Thanks for your support.