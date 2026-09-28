# Aphtharsia anatomy models (CC BY-SA 4.0)

These are the 3D anatomy model files shipped in the Aphtharsia anatomy app (model version MV400)
that are adaptations of third-party ShareAlike material. They are offered here free, without
DRM, under the same licence, so that anyone can use, study and adapt them.

## Attribution

These models are adapted from the **Z-Anatomy** project (https://www.z-anatomy.com), which is
itself derived from **BodyParts3D**, © The Database Center for Life Science (DBCLS), licensed
CC BY-SA. Anatomical names follow Terminologia Anatomica (FIPAT).

Licence: **Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)**,
https://creativecommons.org/licenses/by-sa/4.0/ . The full text is in `LICENSE`.

You may share and adapt these files, including commercially, provided you give attribution and
license your adaptations under the same terms.

## What was changed

Compared with the source models, the files here have been, in various combinations:

* split into separate system layers and part files, and re-exported to glTF binary (.glb),
  most with Draco mesh compression;
* simplified or decimated, re-coloured and re-materialled for mobile rendering;
* renamed to Terminologia Anatomica terms;
* reshaped: meshes moved, morphed or re-fitted (for example male and female pelvis variants,
  the lower-limb alignment, attachments carried onto the gendered pelvis);
* partitioned or copied into new part meshes (for example bony landmark patches, diaphragm
  crura, gland and node meshes moved to other layers);
* repaired: boolean carving, re-welding, thickening, re-seating and re-forming of existing
  meshes (for example vessels re-formed as single branched tubes along their existing course);
* extended with new structures whose surfaces were built on, offset from, or enveloped around
  the source surfaces;
* male genital overlays: the penis built from the Z-Anatomy corpora, the scrotum from the
  MakeHuman CC0 genital helper (the combined file is offered here under CC BY-SA).

Each file carries its own name; `MANIFEST.json` lists every file with its size and SHA-256.

## What is included

161 model files: every file the app loads that contains Z-Anatomy / BodyParts3D geometry, or
whose surface was traced from it. That covers the source-derived base layers and every file built
by moving, copying, re-forming, partitioning or casting onto that geometry. Where provenance
could not be settled in favour of independent geometry, the file is included.

## What is NOT included, and why

The app loads 271 model files in total (counting all three skin tones). The 110 not included here are:

* **99 original structures**, generated procedurally by the app's own tools from measured
  anatomical coordinates. They contain no third-party mesh data and are separate files shipped
  alongside the adapted models (aggregation, not adaptation), so ShareAlike does not reach them.
* **6 outer-body skin files** made with MakeHuman, released CC0 (public domain). No obligation
  applies; they are available from the MakeHuman project.
* **3 female genital skin overlays**, built by the app's own tools on that CC0 skin surface. They
  contain no Z-Anatomy / BodyParts3D geometry, so ShareAlike does not reach them.
* **2 files adapted from NIH 3D / Visible Human and C. Vallance (AnatomyTool)**, licensed
  CC BY 4.0. That licence requires attribution but has no ShareAlike term, so these files are
  credited in the app and not redistributed here.

