# iframe-fixed-elements-ios
Trying to fix the horror of iOS iframes

## Supported Browsers

| Chrome | Firefox | Safari | Android |
|--------|---------|--------|---------|
| Latest | Latest | Safari 10 | 4.0 |

In short, any `position: fixed` element inside of a `-webkit-overflow-scrolling: touch` container flickers when scrolling on iOS. To fix this, you must remove the fixed elements from the scrolling container, and place them in their own layer.

