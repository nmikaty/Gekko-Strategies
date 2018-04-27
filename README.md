# Gekko-Strategies
Custom strategies for Gekko trading bot

<b>RBB_ADX_BB</b>

A simpler, cleaner rewrite of @BradT7 RSI_BULL_BEAR_ADX_BB: https://gist.github.com/BradT7/48915aa4b9319f7cf0d2686079f1c83b

Based on @tommiehansen RSI_BULL_BEAR_ADX: https://github.com/tommiehansen/gekko_tools/tree/master/strategies

The .toml parameters are optimized (with japonicus) for longs on BTCUSD, using 5 minutes candles from April 2017 to April 2018.
I get better results with this strategy than the origial RSI_BULL_BEAR_ADX.

<b>RBB_ADX_BB_SL</b>

RBB_ADX_BB_SL is a strategy combining strategies previously developped: Bull Bear RSI, with an ADX modifier, a BBand modifier and an optional trailing stop loss.
It also works for both longs and shorts. But I think the strategy would need to be rewritten to optimize for shorts (using specific values for shorts instead of the same values than for the longs).

The .toml parameters are optimized (with japonicus) for longs on BTCUSD, using 5 minutes candles from April 2017 to April 2018.

The code is a bit messy and could be optimized.

Credits: 
Tommie Hansen: https://forum.gekko.wizb.it/thread-100.html / https://github.com/tommiehansen/gekko_tools/tree/master/strategies
BradT7: https://github.com/Gab0/japonicus/issues/74
And others behind BB and BBRSI strategies.
