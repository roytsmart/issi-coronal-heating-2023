# issi-coronal-heating-2023
Presentation for International Space Science Institute (ISSI) conference titled "Why is there still a coronal heating problem?"

## The slides on the web

https://roytsmart.github.io/issi-coronal-heating-2023/ shows the slides with
their movies playing. It is built from the deck with
[pptx-to-html](https://github.com/roytsmart/pptx-to-html):

```bash
pptx-to-html presentation/issi_presentation_2023_smart.pptx docs \
    --title "Diagnosing Coronal Heating using Computed Tomography Imaging Spectroscopy" \
    --subtitle "ISSI “Why Do We Still Have a Coronal Heating Problem?” working group · 2023 · the slides as they were presented, with the movies playing"
```

The movies in the deck were re-encoded as H.264, at most 1920 pixels wide, to
bring it from 134 MB to 69 MB, under GitHub's limit for a single file.
