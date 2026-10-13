# in-class-activities
## Devlogs
### W1
1. When the Camera is no longer a child of the Cat, it stays in a fixed position and no longer follows or turns with the Cat. The Cat can still move and may leave the camera's view because the Camera no longer inherits the Cat's position and rotation.
2. My Itch page: [W1 In-Class Activities](https://tra1026.itch.io/w1-in-class-activites)

### W2
1. The r, g, and b variables are floats because color values can include decimals between 0 and 1, such as 0.1 and 0.58. Ints cannot represent these fractional values, bools only represent true or false, and strings store text but no numeric values for calculations.
2. The _bounces variable is an int because it counts whole bounces, like 1, 2, and 3. It does not need decimals. A bool cannot count multiple bounces, and a string would store the count as text.
3. After Step 4, I got the error "CS1002: ; expected." It tole me that the statement was missing a semicolon. 

### W3
Table #: #3
## Activity 1: methods discussion
1. 'GetResponse'
    - input: `int friendshipLevel`, `bool knowsSecret`;
    - output: `string`, the character's dialogue response.
2. 'SetLightDimness'
    - input: `float sanityLevel` (0 – 100)
    - output: `void`, because the method changes the light directly.
3. 'DidPlayerHitBeat'
    - input: `float keyPressTime`
    - output: `bool`
## Activity 2: components & classes metaphor
A class is like a blueprint for a house. The blueprint describes what a house canhave and do, but it si not itself a house int he scene. A Component is more like one actual house built from that blueprint. Member ariabes are the house's traits, such as its color or number of gloors. Methods are the actions it can perform. Multiple houses can be built from the same blueprint, just as multiple Components can be created from one class.
## Activity 3: methods coding activity
1. Because the color is multiplied by 1.5 every time they bouce fast enough. Repeating this multiplication makes the color values grow quickly until they reach the maximum display value, so the balls look white.

## Open-Source Assets
### W1
- Animals: https://assetstore.unity.com/packages/3d/characters/animals/animals-free-animated-low-poly-3d-models-260727 
- Low-poly environment: https://assetstore.unity.com/packages/3d/environments/landscapes/low-poly-simple-nature-pack-162153 