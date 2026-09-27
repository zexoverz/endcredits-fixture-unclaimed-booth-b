Demo fixture for End Credits (ETHGlobal Tokyo 2026). Not a real library.

# @endcredits-demo/unclaimed-booth-b

It exists so a recorded Claude Code session has a small dependency to import. End Credits then decides what to do with its share of the budget.

It has no funding file on purpose: End Credits reserves its share until the repo is claimed. Kept for the booth-b run, since a claim is one-shot.

```js
const { formatUnclaimedBoothB } = require('@endcredits-demo/unclaimed-booth-b');
formatUnclaimedBoothB(1.5) // '1.50 USDC unclaimed'
```

Project: https://github.com/zexoverz/end-credits
