**Cards** is a multi usage component which creates boxes that are usually teasing some kind of content.

#### Landscape (landscape)
A card designed to highlight a link using a landscape photograph and a title with metadata above.

#### Landscape white (landscape-white)
A card designed to highlight a link using a landscape photograph and a title with metadata above.

#### Split (split)
A card of the same dimension of the landscape photo card, but split in half. One half features a landscape photograph, the other half is a white-background section with a title and a subtitle.

#### Hero (hero)
Hero block with title and a background image. It can feature an optional subtitle.

#### Page splash (splash)
Page middle content section.

#### Page splash with image (splash-image)
Page bottom content section with image.

#### Page splash compact (splash-compact)
Page splash with compact size - title and link

#### Related content (related)
Page splash with compact size - title and link

#### Teaser
Card used on publication teasers

### Usage with react

```js
import { Card } from '@wfp/ui';
```

```js
<Card 
  className="some-class"
  kind="landscape"
  title="The Climate Adaption Mangement and Innovation Initiative"
  metadata="Another Category"
  moreButton="inverse"
  subTitle="Food security and climate change analyses, adaptation planning, and good practices in food security adaptation programming."
  image="http://www1.wfp.org/sites/default/files/images/yemen-hero-min.jpg"
  url="http://www.wfp.org/"
  isExternal={false}
  isLink={true}
/>
```