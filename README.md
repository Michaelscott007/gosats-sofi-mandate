# Sofi Mandate

A small interactive product exploration for GoSats' AI Product / Product Intelligence role.

## Thesis

**Sofi should work for the user's wealth, not for the checkout button.**

Before an AI shopping agent searches and recommends, it converts the user's intent into an explicit mandate containing budget, preferences, reward rules, autonomy and timing.

The model can reason inside the mandate. It cannot silently rewrite it.

## Demo

1. User asks for running shoes under ₹6,000.
2. Sofi asks one high-information preference question.
3. Sofi creates a purchase mandate.
4. Three products are compared on effective cost.
5. The product with the largest reward is rejected because it violates the user's hard ceiling.
6. The user approves the aligned option or waits.

## Product principles

- Reward percentage is not the objective function.
- Effective user outcome should dominate platform GMV.
- Purchase authority remains explicit and deterministic.
- "Do nothing / wait" is a valid action.
- Measure wealth created from spend the user was already going to make.

## Suggested metric

**Net Wealth Created From Existing Spend**

Rewards earned + price savings + avoided fees − incremental spending induced by incentives.

## Data disclaimer

All products, prices and rewards are illustrative. No real GoSats user or merchant data is used.

## Run

Open `index.html` in a browser.

---

Built by Jainil Trivedi as an independent product exercise.