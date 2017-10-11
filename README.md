# slstatus-patches
My patches for slstatus

hardmode
- changes the style of the config.h. The configuration file has some more characters, but this enables some features, like changing the statussting depending on the conditions. E.g. showing the remaining battery only at discharging or warning about low diskspace.

perctobar
- If you want a vertical bar shown instead of percentage you can convert every perc function with perctobar(). Instead of the percentage a vertical bar like ▁▂▃▄▅▆▇█ in relation to the percentage get shown. Requires hardmode patch.

vbar_for_vanilla
- If you want a vertical bar shown instead of percentage put VBAR instead of %s in the format. The VBAR characters gets replaced with ▁▂▃▄▅▆▇█ in relation to the percentage. This patch was written before the perctobar patch and doesnt require the hardmode patch.
