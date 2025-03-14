---
title: International Money and Banking
summary: AI for Economists with Python(For Undergraduate student)
date: 2022-09-15
type: docs
math: true
tags:
  - Macroeconomics
image:
  caption: 'Embed rich media such as videos and LaTeX math'
---

This is the [course material](https://github.com/WertherLiu/AI-for-economist.git) we have used.

## Central Banks and Banking System


### 1.Banks and Financial Intermediation

Though it is a fascinating topic, we will not have time to cover the [introduction of coins and paper](https://www.bilibili.com/video/BV1sa411B7S3/?spm_id_from=333.337.search-card.all.click) money as accepted means of payment. However, once money became accepted as a way to conduct transactions, the question arose of where people stored their money.

This is called fractional-reserve banking because they only keep a fraction of the money you’ve deposited with them “on reserve” in case people come looking for their money.

#### balance sheets: Liabilities and assets.
The liabilities side shows the sources of the bank’s funds (where it got them from) and the asset side shows the uses of funds (what they did with them).

| Assets (Uses of Funds) | Amount (€) | Liabilities and Equity (Sources of Funds) | Amount (€) |
|-----------------------|------------|------------------------------------------|------------|
| Cash                  | 15         | Deposits                                 | 100        |
| Loans                 | 95         | Equity Capital                           | 10         |
| **Total**             | **110**    | **Total**                                | **110**    |

#### Meaning of fractional-reserve banking
But fractional-reserve banking has important advantages:
1. Saves Depositors Money: Banks can charge interest on their loans. Without this interest income, the only way a bank can make a profit is to charge fees to depositors. Interest earned can be used as an alternative source of income for banks and (assuming competition between banks) this reduces the need for fees related to safeguarding their money. 
2. Financial Intermediation: It makes banks an intermediary between those that have money and those that need to borrow money. This financial intermediation function is a crucial element of the modern economy.

There are other financial intermediaries apart from banks and insurance companies. **Pension funds, mutual funds and private equity funds** are three examples that play important roles in the economy.

#### Financial intermediaries compared with peer-to-peer borrowing.
- Pooling Savings: Many savers deposit small amounts. Someone looking for a big loan can get it from a bank rather than having to look for a saver with the correct amount of funds.
- Risk Diversification: Savers lending their funds to an individual borrower face idiosyncratic risk. If that borrower fails to pay back, they lose everything. The bank can lend to many borrowers, take its cut, and pass a safe return back to the saver.
- Information Processing: Banks can specialize in screening borrowers, processing and sharing information, and in writing sophisticated debt contracts.
- Maturity Transformation: If I want to have my savings back when I want them, I won’t lend the money for one year or more, as borrowers may want. Banks can make these long-term loans, knowing that (hopefully) each period, only some of its depositors will want their money back.

#### Maturity Mismatch
We mentioned “maturity transformation” as one of the cool features of fractional reserve banking. But when things are going badly for banks, you are more likely to hear about maturity mismatch i.e. the fact that the average maturity of a bank’s assets is longer the average maturity of its liabilities.

Most banks are thus vulnerable if situations arise in which there are demands to pay back a large amount of liabilities over a short period of time.

In the past, governments imposed regulations to limit maturity mismatch: Mortgage lenders took in longer-term savings, banks who had demand deposits only made shorter loans. However, these restrictions have generally been lifted over the years.

### 2. Liquidity and Solvency 
#### Defination of Liquidity and Solvency
Here’s our theoretical bank balance sheet from earlier:
| Assets (Uses of Funds) | Amount (€) | Liabilities and Equity (Sources of Funds) | Amount (€) |
|-----------------------|------------|------------------------------------------|------------|
| Cash                  | 15         | Deposits                                 | 100        |
| Loans                 | 95         | Equity Capital                           | 10         |
| **Total**             | **110**    | **Total**                                | **110**    |

This bank’s liquidity situation refers to its holdings of €15 cash. This can be used to honour requests to pay back deposits. The bank’s other assets, its loans, are usually not very liquid: The bank can’t ask for all its money back from someone it has just provided with a ten year loan.

The bank’s solvency situation refers €10 entry for equity capital. This tells us that the bank’s assets are worth €10 more than what it owes. Equity capital can only be raised by either getting an outside investment or making a profit and retaining the earnings.

Despite its importance, most journalists and politicians do not understand the distinction between solvency and liquidity and so cannot distinguish between equity capital and cash reserves.

#### Difference between book value and market value of bank equity.

The level of equity capital depends on the valuation that is applied to the assets. The published accounts of a bank represent the bank’s own valuation of its assets. These accounts are accompanied by a statement by the bank’s external auditors that they believe the bank’s assessments are valid.

So a bank may actually be insolvent – their assets are unable to repay their liabilities – and still publish accounts that show they have positive equity capital.

Because people from outside a bank can have difficulty assessing the quality of a bank’s assets (e.g. how many of its borrowers will repay in full) estimates of equity capital are often treated with scepticism.

> More from Page 121 of the [Honohan report](Honohan-2010.pdf): “Obviously, putting a solvent but illiquid bank into bankruptcy is unnecessarily costly for society which is where emergency liquidity assistance (“lender of last resort”) from the central bank arises. The emergency loans should be made at a penalty rate so that banks have an incentive to avoid getting into a situation of illiquidity. However, the main difficulty lies in determining whether the bank really is solvent. For this, one cannot rely on what will all too often be a self-serving and over-optimistic assessment from the troubled bank. Instead, the regulator must have assembled the necessary information and analysis to provide the needed advice.”

The bank’s shareholders have a share in any positive value that currently exists due to its assets being greater than its liabilities. But they will also gain from positive future developments. For example, the bank may be expected to pay higher dividends in the future.

For this reason, the market value of a bank (calculated as what it would take to buy all the bank’s shares on the stock market) has traditionally greater than the book value listed in its accounts.

#### Regulations related to solvency and liquidity. 
- Liquidity Regulations:
    - Reserve Requirements. These are minimum fractions of deposits that must be kept in cash or balances at a central bank.
- Solvency Regulations (also known as Capital Adequacy Regulations):
    - These relate to how much equity capital a bank must have. Usually expressed as a ratio: The bigger the bank, the more equity capital required. 

#### Solvency and Liquidity problems can occur together.
Illiquidity Can Lead to Insolvency And Vice Versa. Solvency and liquidity are different things. But, at times, they can interact with each other.

Banks usually have enough cash or liquid securities on hand to cope with withdrawals.If not, they can usually borrow funds from other banks or the bond market. Sometimes, however, large withdrawals occur because depositors believe the bank is insolvent: They fear the bank doesn’t have enough funds to pay back everyone and they want to get their money out in time.

If these redemptions exhaust the bank’s liquid assets and financial markets also don’t trust the bank and won’t lend to them, then the bank will run out of liquid assets.At this point, the possibility that the bank has a solvency problem turns into a liquidity problem. Often, banks in this position turn to the government for help.

Alternatively, banks that need to sell assets quickly because of liquidity problems may have to incur losses on these sales, so a liquidity problem turns into a solvency problem.

## Monetary Policy




## Exchange Rate Regime and the Euro