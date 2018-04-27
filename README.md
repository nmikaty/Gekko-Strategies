# Gekko-Strategies
Custom strategies for Gekko trading bot


RBB_ADX_BB_SL

RBB_ADX_BB_SL is a strategy combining strategies previously developped: Bull Bear RSI, with an ADX modifier, a BBand modifier and an optional trailing stop loss.
It also works for both longs and shorts. But I think the strategy would need to be rewritten to optimize for shorts (using specific values for shorts instead of the same values than the longs).
The .toml parameters are optimized (using japonicus) for longs, over a one year period from April 2017 to April 2018.

Credits: 
Tommie Hansen: https://forum.gekko.wizb.it/thread-100.html / https://github.com/tommiehansen/gekko_tools/tree/master/strategies
BradT7: https://github.com/Gab0/japonicus/issues/74
And others behind BB and BBRSI strategies.
