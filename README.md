# Minerals Images & Data Repository

This repository hosts high-resolution mineral images and JSON metadata mappings for the Stone Identifier mobile application.

## CDN URL Format
Images are distributed globally via fast jsDelivr CDN:
```
https://cdn.jsdelivr.net/gh/Cursor10Ju/dsahjkgew@main/images/<mineral_name>_<index>.jpg
```

## Structure
- `/images/` : Contains all original Mindat specimen images and additional high-resolution Wikipedia images (`<mineral_name>_wiki.jpg`).
- `minerals_part_1.json` to `minerals_part_7.json` : Paginated JSON metadata files matching CDN database parts 1-to-7.
- `minerals_all.json` : Unified JSON file containing all 1,736 minerals.

## Total Statistics
- Total Minerals: 1736
- Total Images: 6056
