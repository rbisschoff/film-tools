# Photo Printing Animation – background photo credits

These photographs are the backgrounds for the **Photo Printing Animation**
mode in `video-tool.html`. They are stored locally in this folder (never
hot-linked) and were resized/re-encoded as JPEG for the web; they are
otherwise unmodified. The printer and print are drawn on top at runtime.

All three are published on Unsplash under the **Unsplash License**
(https://unsplash.com/license): free to use, copy, modify and distribute,
including commercially, without permission or required attribution. The
licence does not allow selling the photos unaltered or using them to build
a competing image service. Attribution is given here anyway. Each photo was
checked on its own Unsplash page as a free "Unsplash License" photo, not
an Unsplash+ photo.

| File | Scene | Photographer | Unsplash page | Notes |
|---|---|---|---|---|
| `beach-koh-samui.jpg` | Thailand Beach | Ann Kolisnyk ([@anettta](https://unsplash.com/@anettta)) | [Turquoise ocean waves gently wash ashore on a sandy beach](https://unsplash.com/photos/turquoise-ocean-waves-gently-wash-ashore-on-a-sandy-beach-3TOSQ96MHbo) | Ko Samui, Surat Thani, Thailand. 2880×1920. |
| `tropical-terrace-table.jpg` | Tropical Balcony | Meg von Haartman ([@traveleroohlala](https://unsplash.com/@traveleroohlala)) | [A table and chairs on a beach with palm trees](https://unsplash.com/photos/a-table-and-chairs-on-a-beach-with-palm-trees-baRMLxJOrmU) | Tulum, Mexico – a shaded beach-terrace table with palms and sea, not Thailand. 2880×1920. |
| `bedroom-window-light.jpg` | Bedroom | Liz Vo ([@lvphotos](https://unsplash.com/@lvphotos)) | [A bed with white sheets and white pillows](https://unsplash.com/photos/a-bed-with-white-sheets-and-white-pillows-pl3sj3DigxM) | Resized to 2160×3240. |

Downloaded 2026-11-04 from images.unsplash.com.

To replace a background, drop a new photo here, then update its entry in
`PP_PHOTO_SCENES` in `video-tool.html`. That entry holds the file name,
where the printer rests (`surfaceX`/`surfaceY`, as fractions of the photo)
and the lighting settings.
