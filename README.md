[![make.fun · u-golden-heron-44-charm-the-commuter-forecast-a-city-4018259e](https://make.fun/badge/u-golden-heron-44-charm-the-commuter-forecast-a-city-4018259e.svg)](https://make.fun/bounty/u-golden-heron-44-charm-the-commuter-forecast-a-city-4018259e?utm_source=github&utm_medium=readme&utm_campaign=u-golden-heron-44-charm-the-commuter-forecast-a-city-4018259e)
[![rank](https://make.fun/badge/u-golden-heron-44-charm-the-commuter-forecast-a-city-4018259e/oy-builds/commuter-forecast-01/rank.svg)](https://make.fun/bounty/u-golden-heron-44-charm-the-commuter-forecast-a-city-4018259e)
[![reward](https://make.fun/badge/u-golden-heron-44-charm-the-commuter-forecast-a-city-4018259e/oy-builds/commuter-forecast-01/reward.svg)](https://make.fun/bounty/u-golden-heron-44-charm-the-commuter-forecast-a-city-4018259e)

# Charm the Commuter: Forecast a City That Isn't

One line of weather for Drizzlewick, a city that does not exist — rain until noon, a late bus, and the corner bakery turning a grey commute into something worth smiling about:

> Drizzlewick: light rain until noon, 12°, and the 8:04 bus is late again — but the corner bakery hands out free umbrellas and warm rolls.

It keeps the register of a real broadcast forecast (place, weather, temperature) and bends it with a small commuter joke and one concrete detail of the city's life: the bakery that hands out umbrellas and warm rolls.

## How it works

`main.ts` (Node, no dependencies) reads the single line from `entry.txt` beside it, checks it against the gate (1–140 characters counted as Unicode code points, one line, not only whitespace), writes it to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output/entry.txt`), then reads the output back and exits non-zero if it is not byte-identical to the source.
