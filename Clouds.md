# Clouds

_From a series of tutorials by [GDquest](https://www.youtube.com/watch?v=HoH0jRVUYkA)._

## Definition

> Accumulation of small water or ice particles. Condensation of water vapor.

```ts
type Cloud =
  | Stratus
  | Cirrus
  | Cumulus
  | Nimbus
  ;

type Cirrostratus = Cirrus & Stratus;

type Stratocumulus = Stratus & Cumulus;
```

#### Stratus

> Uniform sheets, low or high in sky.

#### Cirrus

> Look like strands that blend with the sky.

#### Cumulus

> Go-to clouds for sidescrolling games. This type of cloud has the most defined volume; it is best for pixel art with 2 colors. Cloud faces are irregular and clearly outlined by sunlight.

#### Nimbus

> Rainy clouds.

## Advice

- Study references.
  - Photographs.
  - Clouds in real life, which have details that aren't captured in photographs due to differences of perception between cameras and eyes.
- Train observation skills.
- When studying a subject, focus on a specific aspect.
  - Example: for games, focus only on cumulus clouds. Then, focus only on their shape.
  - Don't need to think about colors, light, and volume all at once.
- Also, study work of pixel artists or specific games.
  - Example: Sword and Sorcery.
  - Example: Owlboy.

## Example analysis

- Lighting: follow sunlight direction.
- Values: light vs. dark in in cloud vs. sky.
- Color relationships.
- Silhouettes, form, shape, rhythm. (of cumulus clouds, for example).
- Volume.

## Example practice

- Lighting: sketch out sun direction.
- Values: desaturate, color-pick values and analyze them.
- Colors: sky is light at bottom and darker at top.
  - Sky(?) color is more saturated than cloud shadow colors.

## Process

- Start with blocking out shape.
- Start with black/white (1 value only), focus on shape.
- Fill in light and shadow, details.
- Smooth out transitions.
  - For 16-color pixel art, this means dithering?
