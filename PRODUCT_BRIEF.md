# Sofi Mandate — Product Brief

## Problem
Shopping agents are naturally rewarded when a transaction occurs. Rewards products can also unintentionally encourage users to spend more in order to earn more.

## Product question
Can GoSats make Sofi demonstrably aligned with user wealth rather than transaction volume?

## Proposed primitive
A **Purchase Mandate** created from user intent before search.

Fields:
- need
- budget ceiling
- preferences
- reward policy
- autonomy level
- timing
- prohibited behaviors

## Decision architecture
1. LLM interprets and compares.
2. Deterministic mandate validation checks whether an action is allowed.
3. User or pre-authorized policy confirms purchase.
4. Reward becomes BTC / Gold after the transaction.

## What to test first
One constrained category such as footwear or electronics.

Compare:
- ordinary product ranking
- reward-maximizing ranking
- mandate-aligned ranking

Measure:
- conversion
- spend vs stated budget
- recommendation acceptance
- post-purchase satisfaction
- repeat use
- effective savings + rewards