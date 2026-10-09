# Virtual Rites — Quest preview

Open https://myathemagick-netizen.github.io/virtual-rites-preview/ in Quest Browser and enter VR. No USB connection is required.

This repository contains a built snapshot of https://github.com/myathemagick-netizen/virtual-rites/tree/modernization/three-r186 at commit a2edcc70e4b6556eec1794e599fc93ba4f6a8019. Review: https://github.com/myathemagick-netizen/virtual-rites/pull/1.

The original repository and its main site are unchanged. This snapshot does not update automatically when the review branch changes.

For headset checks, select Recorded audio only narration, try the Drowned Temple, compare full and simplified settings, verify quiet modes, and leave/re-enter rites to check audio cleanup. Quest performance and stereo appearance still require physical testing.

Settings and journal storage use the browser origin, so this preview and the original site can share stored data when opened in the same browser on the same github.io host.

To refresh: build the review checkout with VITE_BASE=/virtual-rites-preview/, copy its dist output here, commit, and push. GitHub Pages publishes main at the repository root.
