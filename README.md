# auto-yom-tov
Automatically turn devices on and off for Shabbos and yom tov

## Summary

This code allows turning devices on and off on a timer that knows when Shabbos and yom tov are. Unlike a standard digital timer, it will automatically account for yom tov and for changes in sunset time, to give you fewer things to think about erev Shabbos/yom tov. It can disable light switches so that pushing them will not toggle the light. For each thing you want to control, you will need to purchase an appropriate [Shelly](https://www.shelly.com/) device, which should cost around $15-25. Setup currently requires some technical know-how but should only take a few minutes. If you're trying to control something like a light fixture that's hardwired (not an outlet), a bit of electrical wiring will probably be needed.

## Setup instructions

1. Choose and obtain an appropriate Shelly device (see [Which device](#which-device)). Shelly has online stores in the [USA](https://us.shelly.com/), [EU](https://www.shelly.com/), and [UK](https://shellystore.co.uk/), and Shelly devices can be purchased from many other outlets as well. For Israel, the best bet is probably [the Shelly AliExpress store](https://shelly.aliexpress.com/store/), which offers free shipping to Israel.

## Which device?

For appliances that plug in to outlets, the easiest option is a Shelly Plug of some kind. Make sure the plug type matches your country. If you're using it for something that uses a lot of power, like an oven or air conditioner, check that your device is within the maximum power rating for the plug. Shelly doesn't have smart plugs for Israeli outlets, but you could use two plug adapters, one on each side. (If using plug adapters, it's probably best to plug it into a short extension cord and not horizontally into a wall -- the torque of four plugs in a row might be too much for the plug to stay firmly in the wall.)

For lights, you could use a Shelly Bulb (make sure the socket type is correct), but this will not let you turn the light on when the switch is off. This might be a good solution if you just want to make sure the light is always off on Shabbos, e.g., for a bedroom.
