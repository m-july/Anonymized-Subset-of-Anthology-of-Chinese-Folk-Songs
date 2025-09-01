# Anonymized Subset of Anthology of Chinese Folk Songs

A lightweight subset of our _Anthology of Chinese Folk Songs_ dataset. This repo is anonymized for double-blind review.

## Content

- **Melody-only subset**: all pieces from _Volume Jiangsu II_, merged into one collection (totally over 600 songs).

- **Curated subset** (lyrics and metadata included): songs from #786 to #1100 (totally 334 songs, including some variation pieces) in _Volume Jiangsu II_, each kept as an individual file.

## Formats

- MIDI (`*.mid`)

- MusicXML (`*.musicxml`)

- Original scanned and preprocessed _Jianpu_ images (`*.jpg`) of Curated Subset*

*See Important Note below for more details.

## Repository Structure

```
.
├── Curated/
│   ├── midi/
│   ├── musicxml/
│   └── original_jpg/
└── Melody-only/
    ├── midi/
    └── musicxml/

```

## Important Note

The scanned images are research-use only, and will not be made available to the public in the final dataset, since they are copyrighted works.