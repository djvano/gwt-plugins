You will need to download corresponding SDK required for building the plugin
separately.  These are located at:
	http://ftp.mozilla.org/pub/mozilla.org/xulrunner/releases/28.0/sdk/ (for Firefox version 28.0)

- xulrunner-28.0.en-US.linux-i686.sdk.tar.bz2 for building i686
- xulrunner-28.0.en-US.linux-x86_64.sdk.tar.bz2

Build by:

~/git/gwt-plugins/xpcom/export BROWSER=ff280 && export VERSION=1.28 && export ARCH=x86 && make clean all

~/git/gwt-plugins/xpcom/export BROWSER=ff280 && export VERSION=1.28 && export ARCH=x86_64 && make clean all

