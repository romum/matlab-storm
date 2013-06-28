
Updated 05/10/13

## Bug list
* `ReadDaxBeta.m` gets wrong bits from bypass 256x256 camera.  `ReadDax.m` does this right so we should be able to figure out the proper extension.
* `STORMfinderBeta.m` in 2D mode creates incomplete bin files when using InsightM

## Fixed bugs
* `STORMfinderBeta.m` InsightM call gives cannot save configuration file error: **Fixed: 05/23/13**.  May have fixed  2D mode creates incomplete bin as well. 