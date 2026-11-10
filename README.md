# Microsoft QuickC 2.50 (MS-DOS, 16-bit)

Microsoft QuickC 2.50 (1990), the 5.25" 360 KB floppy set, kept as the
original archive of its eight floppy images.

- Product: Microsoft QuickC 2.50 (1990)
- Release asset: `quickc-2.50-5.25-360k.7z` (release `2.50`), byte for byte
  the WinWorld archive `Microsoft QuickC 2.50 (1990) (5.25-360k).7z`
- sha256: `922305575ba425158a7db1a49eceecd00481dc5a092db02eda3582d68447198a`
- Size: 2,175,850 bytes

## Source & provenance

- Retrieved 2026-11-10 from WinWorld,
  https://winworldpc.com/product/quick-c/2x (download
  `d656f319-766c-11ec-bb7d-0200008a0da4`). The sha256 is the one
  recompile-toolchains pinned for `quickc-2.50`. WinWorld's mirror answers a
  direct request with 404 until the client has visited the download page.

## Usage

recompile-toolchains `quickc/2.50-msdos` downloads the release asset, checks the
sha256 above, and unpacks the floppy images with 7-Zip.
