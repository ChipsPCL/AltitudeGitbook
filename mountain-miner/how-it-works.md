# How Mountain Miner Works

Mountain Miner uses a USDC-in, USDC-out model.

Users deposit USDC into the miner. After the deposit fee is taken, the remaining net deposit becomes the user's earning base.

Rewards accrue according to the daily ROI rate, but the user can only claim up to their maximum payout.

## Core Flow

1. User deposits USDC.
2. A 5% deposit fee is taken.
3. The remaining 95% becomes the user's net deposit.
4. Rewards accrue based on the current daily ROI rate.
5. Rewards stop building after 48 hours until claimed.
6. The user claims rewards and pays a 5% claim fee.
7. Claimed rewards count toward the user's 3X max payout.

## 48-Hour Timer

Mountain Miner uses a 48-hour timer.

Rewards build for up to 48 hours. After 48 hours, rewards stop building until the user claims. Once the user claims, the timer restarts.

This means efficient claiming matters. Users who ignore the timer may stop accruing rewards until they return and claim.

## No Compound Button

A compound button has intentionally been kept away from the UI to encourage users to focus on ROI first.

If a user wants to compound, they must:

1. Claim rewards.
2. Pay the 5% claim fee.
3. Redeposit the received USDC.
4. Pay the 5% deposit fee.

This keeps the process transparent and helps discourage users from endlessly compounding without understanding the fees and risks.
