# Image replacement log

Updated 2026-11-14. All 12 non-hero static image slots and four service choices now reference local replacement assets. All 16 popup gallery entries were replaced. Hero markup is byte-for-byte unchanged.

These are stock design references, not verified photographs of the named studio projects. The coastal living image is identified by its source as a rendering. The text-only press marquee and footer have no image slots.

## Before and after

| Section | Previous image URL | Replacement file |
| --- | --- | --- |
| philosophy | https://images.unsplash.com/photo-1618221195710-dd6b41faaea6?auto=format&fit=crop&w=1200&q=85 | [assets/images/wood-living-room.jpg](assets/images/wood-living-room.jpg) |
| philosophy | https://images.unsplash.com/photo-1600607687939-ce8a6c25118c?auto=format&fit=crop&w=900&q=85 | [assets/images/sunlit-sideboard.jpg](assets/images/sunlit-sideboard.jpg) |
| works | https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=1600&q=85 | [assets/images/green-courtyard.jpg](assets/images/green-courtyard.jpg) |
| works | https://images.unsplash.com/photo-1616486338812-3dadae4b4ace?auto=format&fit=crop&w=1400&q=85 | [assets/images/linen-lounge.jpg](assets/images/linen-lounge.jpg) |
| works | https://images.unsplash.com/photo-1582719478250-c89cae4dc85b?auto=format&fit=crop&w=1400&q=85 | [assets/images/desert-retreat.jpg](assets/images/desert-retreat.jpg) |
| works | https://images.unsplash.com/photo-1600566753190-17f0baa2a6c3?auto=format&fit=crop&w=1600&q=85 | [assets/images/coastal-living.jpg](assets/images/coastal-living.jpg) |
| atmospheres | https://images.unsplash.com/photo-1764526624453-db32c24eca55?auto=format&fit=crop&w=1400&q=85 | [assets/images/wood-kitchen.jpg](assets/images/wood-kitchen.jpg) |
| atmospheres | https://images.unsplash.com/photo-1616137466211-f939a420be84?auto=format&fit=crop&w=1400&q=85 | [assets/images/linen-lounge.jpg](assets/images/linen-lounge.jpg) |
| atmospheres | https://images.unsplash.com/photo-1600607687644-c7171b42498f?auto=format&fit=crop&w=1400&q=85 | [assets/images/warm-bedroom.jpg](assets/images/warm-bedroom.jpg) |
| atmospheres | https://images.unsplash.com/photo-1586023492125-27b2c045efd7?auto=format&fit=crop&w=1400&q=85 | [assets/images/timber-hallway.jpg](assets/images/timber-hallway.jpg) |
| disciplines | https://images.unsplash.com/photo-1600607687939-ce8a6c25118c?auto=format&fit=crop&w=1200&q=85 | [assets/images/wood-living-room.jpg](assets/images/wood-living-room.jpg) |
| service: Interior Architecture | https://images.unsplash.com/photo-1600607687939-ce8a6c25118c?auto=format&fit=crop&w=1200&q=85 | [assets/images/wood-living-room.jpg](assets/images/wood-living-room.jpg) |
| service: Custom Furniture | https://images.unsplash.com/photo-1617806118233-18e1de247200?auto=format&fit=crop&w=1200&q=85 | [assets/images/artisan-dining.jpg](assets/images/artisan-dining.jpg) |
| service: Boutique Hospitality | https://images.unsplash.com/photo-1582719478250-c89cae4dc85b?auto=format&fit=crop&w=1200&q=85 | [assets/images/hotel-suite.jpg](assets/images/hotel-suite.jpg) |
| service: Art &amp; Collectibles | https://images.unsplash.com/photo-1615873968403-89e068629265?auto=format&fit=crop&w=1200&q=85 | [assets/images/artisan-dining.jpg](assets/images/artisan-dining.jpg) |
| Our Belief | https://images.unsplash.com/photo-1600607687939-ce8a6c25118c?auto=format&fit=crop&w=2000&q=85 | [assets/images/sunlit-sideboard.jpg](assets/images/sunlit-sideboard.jpg) |

## Photo sources

- [linen-lounge](https://unsplash.com/photos/srzKmNLovaQ) — EZcurtain Life; local file: `assets/images/linen-lounge.jpg`.
- [timber-hallway](https://unsplash.com/photos/qraqqY9i860) — Zara Johnson; local file: `assets/images/timber-hallway.jpg`.
- [wood-living-room](https://unsplash.com/photos/CybeDUWowgw) — Marcel Strauss; local file: `assets/images/wood-living-room.jpg`.
- [artisan-dining](https://unsplash.com/photos/AptA9A5gjL0) — Rochelle Lee; local file: `assets/images/artisan-dining.jpg`.
- [sunlit-sideboard](https://unsplash.com/photos/aX1TTOuq83M) — Julia / Beazy; local file: `assets/images/sunlit-sideboard.jpg`.
- [desert-retreat](https://unsplash.com/photos/BCNNS0gVCTc) — Austin Curtis; local file: `assets/images/desert-retreat.jpg`.
- [hotel-suite](https://unsplash.com/photos/5BV56SdvLmo) — Point3D Commercial Imaging Ltd.; local file: `assets/images/hotel-suite.jpg`.
- [soft-bedroom](https://unsplash.com/photos/qVwFsimVcWQ) — Jean-Philippe Delberghe; local file: `assets/images/soft-bedroom.jpg`.
- [green-courtyard](https://unsplash.com/photos/NvsBWuLRtSM) — Annie Spratt; local file: `assets/images/green-courtyard.jpg`.
- [coastal-living](https://unsplash.com/photos/tPz3Lhh3z_4) — Brian Zajac; local file: `assets/images/coastal-living.jpg`.
- [wood-kitchen](https://unsplash.com/photos/mhDeeOvBs9o) — Clay Banks; local file: `assets/images/wood-kitchen.jpg`.
- [warm-bedroom](https://unsplash.com/photos/Xbe5BfScmvM) — Clay Banks; local file: `assets/images/warm-bedroom.jpg`.

## Verification

- All 12 downloaded images decoded successfully and were visually inspected in the contact sheet.
- All referenced local image paths exist.
- All inline JavaScript passes `node --check`.
- No old Unsplash image URLs remain below the hero.
- Hero section SHA-256: `366329deef9a0c13ef44c3bad699c378865133000096df73f9b53e72e8050ce6`.

Contact sheet: [image-audit.jpg](assets/images/image-audit.jpg).

## Targeted correction: Marusthal and Backwater

The distant mountain hotel did not match the flat desert pavilion; the generic coastal lounge did not show a Kerala waterfront home. Replaced both with tailored AI-generated concept visualizations, visibly labelled on cards and described in alt text. Updated card sources, popup covers and matching gallery entries. Other gallery images remain stock design references.

- **Marusthal Pavilion**: `desert-retreat.jpg` ? [new concept](assets/images/marusthal-pavilion-concept.png). Tags: ochre-rammed-earth,sandstone,desert-pavilion,sunken-lounge.
- **Kochi Backwater Residence**: `coastal-living.jpg` ? [new concept](assets/images/kochi-backwater-concept.png). Tags: kerala-backwaters,waterfront-home,teak-verandah,palm-trees,water-reflections.

Generation: built-in image_gen. Exact prompts: [concept-prompts.json](assets/images/concept-prompts.json). Both outputs visually inspected. Local assets exist, inline JavaScript syntax passes, and hero remains unchanged.
