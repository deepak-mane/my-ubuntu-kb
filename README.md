# my-ubuntu-kb

## Ubuntu loads and then monitor loses signal?
- Most likely it's either a wrong display mode which the monitor cannot handle, or Ubuntu, for some reason, switches from the graphics adapter you use to another one.
- Since you have an i5 CPU with integrated graphics and a motherboard with DVI/HDMI, etc connectors, the easiest thing to try first is swapping your display cable from your graphics card and plug it into the motherboard connector (I would try this before boot). If you're already using the motherboard connector, try this reversed - naturally.
- Now if this doesn't help, you'll have to get to a terminal prompt and reconfigure the GUI display settings.
- Most likely you can get to a terminal by pressing CTRL-ALT-F1. Then login and follow one of the several answers here about re-configuring or resetting the GUI, for example:
- How to reset monitor settings to default through terminal?
- Now... if this really is a old "testing machine" with a old Ubuntu installation - the easiest way to solve all your problems is probably going to be a full installation of a newer version of Ubuntu. Just a thought.
- At least do a full upgrade before attempting a fix; there might be never drivers in the new kernel, more up to date settings in X configs, etc.
