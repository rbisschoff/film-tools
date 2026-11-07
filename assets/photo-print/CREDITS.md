# Photo Printing Animation – photo credits and licences

All photographs used by the **Photo Printing Animation** mode in
`video-tool.html` are stored locally in this folder (never hot-linked).
Each source page was checked when the photo was downloaded. Every licence
below permits commercial use and modification.

## Photographic printer scene (the default: "Photographic white printer" + "Bali terrace")

This scene is built from real photographs, not drawn. The layers were
prepared once, offline, from the approved "V3C" still, and are placed by
`PP_V3C` in `video-tool.html`.

| File | Used as | Source | Licence | Attribution | Changes made |
|---|---|---|---|---|---|
| `printer-white-photo.png` (838×467, alpha) | The printer | [Unsplash – "A white electronic device sitting on top of a table"](https://unsplash.com/photos/a-white-electronic-device-sitting-on-top-of-a-table-vwfyG6K3_f0), photographer **Nik** ([@helloimnik](https://unsplash.com/@helloimnik)). 6240×4160 original (Fujifilm X-T4), published 2024-02-06. | **Unsplash License** (https://unsplash.com/license). Confirmed on the page as a free photo, not Unsplash+. | Not required (credited here and in the app). | The photo shows a Polaroid Lab: flipped so its paper slot is on top, levelled by 9.55°, and cut out along the body's own rim. **All lettering and logos retouched out** ("Polaroid", "POLAROID LAB", "I-TYPE FILM"; the stripe logo is cropped away). Colour cast neutralised and warmed. Scaled down to about 0.24×. |
| `table-wood.jpg` (1178×363) | The table top | [Pixabay 4395086 – "Printer Memobird G4 Pocket"](https://pixabay.com/photos/printer-memobird-g4-pocket-4395086/), uploader **pavlovandrew1297** (1280px public preview). | **Pixabay Content License** (https://pixabay.com/service/license-summary/). | Not required. | Only the wooden table surface is used. The printer standing on it in the original was replaced by tiles of the same wood, so no product or branding from this photo appears. |
| `terrace-bali.jpg` (1280×960) | Background | [Pixabay 656991 – "Bali Jimbaran Pool Villa"](https://pixabay.com/photos/bali-jimbaran-pool-villa-656991/), uploader **qlahr123** (public preview of a 3264×2448 original). | **Pixabay Content License**. The page says "Free for use under the Pixabay Content License" (checked 2026-11-07). | Not required. | Unmodified file. Cropped, blurred (lens depth of field) and graded at runtime. |
| `sample-portrait.jpg` (960×1440) | Sample photo on the print before the user chooses their own (never exported) | [StockSnap – "Woman Portrait"](https://stocksnap.io/photo/woman-portrait-NAUAR8FEAD), photographer **Matt Moloney** (https://mjmolo.com), found via Openverse. | **CC0 1.0** (https://creativecommons.org/publicdomain/zero/1.0/). | Not required. | Re-encoded JPEG. |

Pixabay Content License: free for commercial and non-commercial use and
modification, with no attribution required. Not allowed: selling it
unaltered, or implying endorsement by people or brands shown. Pixabay
doesn't guarantee third-party trademark or design rights. That is why the
table photo's printer is not used, and why all branding was removed from
the printer photo.

Unsplash License: free to use, copy, modify and distribute, including
commercially, with no permission or attribution required. Not allowed:
selling photos unaltered, or using them to build a competing image service.

The app shows this credit line under "Background" (the `PP_V3C.credit`
string): *Photos: printer – Nik (Unsplash); table – pavlovandrew1297
(Pixabay); terrace – qlahr123 (Pixabay); sample portrait – Matt Moloney
(StockSnap, CC0)*.

Downloaded 2026-11-07.

## Background photos for the drawn printers

These are used with the illustrated printers (Instax-, QX20- and
SELPHY-inspired, and Generic). They were resized/re-encoded as JPEG for
the web and are otherwise unmodified. All three are on Unsplash under the
**Unsplash License**. Each was checked on its own page as a free photo, not
Unsplash+.

| File | Scene | Photographer | Unsplash page | Notes |
|---|---|---|---|---|
| `beach-koh-samui.jpg` | Thailand Beach | Ann Kolisnyk ([@anettta](https://unsplash.com/@anettta)) | [Turquoise ocean waves gently wash ashore on a sandy beach](https://unsplash.com/photos/turquoise-ocean-waves-gently-wash-ashore-on-a-sandy-beach-3TOSQ96MHbo) | Ko Samui, Surat Thani, Thailand. 2880×1920. |
| `tropical-terrace-table.jpg` | Tropical Balcony | Meg von Haartman ([@traveleroohlala](https://unsplash.com/@traveleroohlala)) | [A table and chairs on a beach with palm trees](https://unsplash.com/photos/a-table-and-chairs-on-a-beach-with-palm-trees-baRMLxJOrmU) | Tulum, Mexico – a shaded beach-terrace table with palms and sea, not Thailand. 2880×1920. |
| `bedroom-window-light.jpg` | Bedroom | Liz Vo ([@lvphotos](https://unsplash.com/@lvphotos)) | [A bed with white sheets and white pillows](https://unsplash.com/photos/a-bed-with-white-sheets-and-white-pillows-pl3sj3DigxM) | Resized to 2160×3240. |

Downloaded 2026-11-04 from images.unsplash.com.

To replace a drawn-printer background, drop a new photo here, then update
its entry in `PP_PHOTO_SCENES` in `video-tool.html`. That entry holds the
file name, where the printer rests (`surfaceX`/`surfaceY`, as fractions of
the photo) and the lighting settings.

## Candidates considered and rejected (2026-11-07)

These were not used, and are recorded for provenance:
- **CC BY-SA licences** (would require share-alike on exported videos): Wikimedia Instax Mini Link and SELPHY ES1 photos, and the Polaroid Hi-Print.
- **No-derivatives (BY-ND) or non-commercial (BY-NC) licences**: Flickr Instax SHARE and Kodak printer series.
- **Branding or composition**: an Epson PictureMate (large logo, studio black background) and the CC0 Canon SELPHY photo (cluttered, top-down).
- **Wrong product type**: a Pexels white label printer (slot too narrow for a 10×15 print, held in a hand).
- **Too low resolution**: a CC BY 2.0 Instax Mini Link photo (1000px).
