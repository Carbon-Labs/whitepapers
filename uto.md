# Unlimited Token Offer (UTO)
> No More ICO's.

_**DRAFT ONLY**_

# Table of Contents
1. [Unlimited Token Offer (UTO)](#uto)
    1. What is an UTO?
    2. How does an ICO typically work?
    3. How does an UTO work?
    4. What are the benefits compared to ICO's?
2. [The smart contract.](#smart-contract)
3. [Proof of Concept.](#poc)
    1. A simple dapp
4. [Tokens utilising UTO](#tokens-utilising-uto)
    1. AVATAR - Liberation Online

## Unlimited Token Offer (UTO)<a name="uto"></a>

#### What is an UTO?

#### How does an ICO typically work?
To be able to understand how a UTO works, we need to first look at how a typical ICO works.

> The following view is representative of the majority of ICOs, however there are examples whose tokens have utility within the ecosystem that they were created. In which case, the ICO token has a more tangible value and usecase.

**A definition first**

An unregulated means by which funds are raised for a new cryptocurrency venture. An Initial Coin Offering (ICO) is used by startups to bypass the rigorous and regulated capital-raising process required by venture capitalists or banks. In an ICO campaign, a percentage of the cryptocurrency is sold to early backers of the project in exchange for legal tender or other cryptocurrencies.

**What does that really mean?**

It seems these days, ICO's are being created almost daily and selling out even quicker. The "investors" are hoping that the value of these coins will increase in value. We use the term investors very loosely, as most people participating in an ICO sale are speculators.

There is no guarantee that the value of these tokens will increase however almost immediately after the ICO has ended a large amount of these tokens are traded on various exchanges at some very high prices (as compared to the price to participate in the ICO).

The tokens are not being valued against the company that created them in the first place, but rather they are being valued against the current hype that is being generated and subsequently valued based on supply and demand on the exchange. Without the exchanges these tokens are essentially worthless!

**It gets worse&hellip;**

As we already mentioned, most of these tokens are not tied to anything tangible. The value of the tokens are based completely on the hype of the ICO and the subsequent market exchange. The companies that launch the ICOs have no accountability to deliver upon any promises they make.

So, these companies launch an ICO to raise some funds. But no only that they also create or retain a large number of the same tokens for themselves. What are these tokens used for? There is only one purpose and that is to trade them on the exchange to make even more crypto.

You should ask yourself seriously why a company would be selling off their newly acquired (from thin air) tokens immediately on the exchanges when they have already raised such a large amount of crypto from the ICO itself.

#### How does an UTO work?

At its core, a UTO is a smart contract that can accept funds in exchange of tokens. Additionally, it can also accept funds that are payment for products and services provided by the UTO operator.

Tokens are only created when eth is received.

There is no time limits on how long the UTO can accept funds in exchange for tokens. However, the UTO itself can be "paused" by the UTO owner.

#### An example
The UTO is launched with the following characteristics:

* 1 ETH = 100 tokens
* Company running the UTO retains 10% of the tokens created.

Buyer A sends 10 ETH to the contract, which results in 1000 Tokens being created. 900 are assigned to Buyer A and 100 are assigned to the Company. The ETH itself is locked into the contract. The Company does not have access to the ETH.

At this point each Token is worth 0.01 ETH.

**However**, the UTO contract can receive ETH that is not for token purchases. We refer to these as invoice payments. So carrying on with our example, let's assume that the UTO contract now has 100 ETH. The cost of token purchase is formulated such that the current UTO Token owners potential profit value is not decreased, that is we are guaranteeing that the price of a UTO token can not decrease due to supply. In fact, it can never go backwards in value.

We can calculate the current value of a single token with the following formula:

`TETH / IR = TV`

where:

**TETH** - Total ETH held in UTO\
**IR** - Current supply of UTO tokens\
**TV** - Token Value

so:

`100 / 1000 = 0.1`

That is to say that each token is now worth 0.1 ETH. Further purchases of UTO Tokens need to ensure that this value is retained. So the formula for calculating further UTO token purcahses is:

`RPA x (TETH/IR) = PRICE`

where:

**RPA** - Number of new Tokens being purchased

So, if a buyer wants to buy a further 5000 Tokens then the cost is 500 ETH:

`5000 x (100/1000)=500 ETH`

After this transaction, there would be:

**UTO Tokens** - 6000\
**UTO ETH** - 600 ETH

Which means the Token value is still 0.1 as it was before this new purchase.

###UTO Fluidity
You do not need to use a market exchange to cash out your UTO Tokens. At anytime you can "sell" your tokens back to the UTO contract at the current Token Value without any extra fees (just pay for the gas).

Anytime UTO Tokens are sold back to the contract, these tokens are destroyed and the equivalent ETH is sent to the user.

The UTO company has to follow the exact same procedure to access the ETH as well. The ETH is locked into the contract. There is no way for the UTO company to access the ETH without selling tokens.



### What are the benefits compared to ICO's?
> It puts more control in the hands of the contributors.

Contributors can at any stage withdraw their investment less the tokens already assigned to the UTO Beneficiary.

With an ICO, when the token sale is complete, all of the money raised is handed over to the company that launched the ICO. At this point they can simply walk away with the money without producing anything. The incentive to implement the project is diminished when the company already has access to millions of dollars already.

> No need for an exchange to buy and sell tokens.

> The company who launches a UTO is motivated to increase the value of the tokens.


## The Smart Contract <a name="smart-contract"></a>
> The smart contract is currently being developed.

You can follow the development at https://github.com/liberation-online/uto

## Proof of Concept <a name="poc"></a>

Along with development of the smart contract, a dapp will also be available that will demonstrate all features of the smart contract. The development for this has already begun and the core functions are working (buying and selling of tokens, and withdrawal of ETH).

## Tokens utilising UTO <a name="tokens-utilising-uto"></a>

The first UTO to be launched will be AVATAR.

- More Info: https://www.liberation.online/projects/avatar/
- [Whitepaper](avatar.md)
