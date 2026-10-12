# Internal brand assets

Canonical brand files (`clothesgo-mark.png`, `clothesgo-wordmark.png`, `clothesgo-lockup.webp`, `clothesgo-fashion-hero.webp`) are copied from `shared/design-system/assets` and are the assets rendered by this app.

`clothesgo lucas/Clothes go Marva [Recuperado].pdf` is the complementary
construction reference for the hanger mark and the horizontal/stacked ClothesGo
lockups. The public site uses the canonical shared exports and follows those
proportions; it does not recreate the logo with HTML or CSS.

The public preview catalog under `../preview/catalog` mirrors the four
repository-owned reference photos documented in `ios/assets/ASSET_SOURCES.md`.
They exist only so the isolated demonstration API can return stable HTTPS
image URLs while exercising the same remote-media path used by real garments.

## Designer narrative assets

The files under `designer-story/` are web-delivery derivatives of the original
Lucas design package kept in the repository at `clothesgo lucas/`:

- `Site outros testes.pdf` defines the desktop composition: fluid blue opening,
  alternating story, green Washer invitation, Station directory and the clothes
  ribbon closing the page.
- `Site e mobile.pdf` defines the responsive hierarchy and the compact navigation
  behavior instead of a separate visual language for smaller screens.
- `Site [Recuperado].pdf` supplies the three-step icon vocabulary used to explain
  donation, care and access without exposing operational terminology. The
  optimized crops under `designer-story/steps/` preserve those original
  illustrations in the public Home's three-part circulation explanation.
- `novos gifs.pdf` maps the character sequences to each stage of the story and is
  the motion reference for transitions between discovery, curation, care and
  recirculation.
- `clohes go app testes.pdf` and `clohes go app testes 2.pdf` complement the
  responsive Member language with image-led catalog, playlist, selection and
  garment-detail studies. They inform links into the app without turning the
  commercial Home into an oversized mobile screen.
- `Prototipo clothes go.pdf` is the complementary product-flow reference outside
  the Lucas folder. Its collection, garment-detail and selection screens close
  the public story by showing the concrete path from discovery to choice. The
  optimized, unredrawn page exports live under `designer-story/app-flow/`.
- `ClothesGo 2/register login.pdf` documents authentication sequencing rather
  than a visual direction, so it does not contribute artwork to the Home.
- `clothes.pdf` is a separate Glenda Albernaz/Mercado persona study. Its fashion
  imagery confirms the value of an image-led catalog, but its identity, colors
  and interaction experiments are intentionally not mixed into ClothesGo.

- `discovery.mp4` comes from `Anima desenho mulher jovem 2_2.mp4`.
- `curation.webp` comes from `gif homem 1.gif`.
- `care.webp` comes from `gif mulher roupas.gif`.
- `circulation.webp` comes from `gif mulher 1.gif`.
- `clothes-ribbon.webp` is a web crop of the clothes illustration at the
  bottom of page 1 in `Site outros testes.pdf`, the selected composition
  reference for the public home.
- `app-flow/collection.webp`, `app-flow/garment-detail.webp` and
  `app-flow/selection.webp` are optimized exports of pages 6, 9 and 11 from
  `Prototipo clothes go.pdf`.

The matching `*-still.webp` files are final-frame fallbacks used while media
loads and when the visitor requests reduced motion. Animated WebP derivatives
retain the source timing while reducing transfer size; no character artwork was
redrawn.
