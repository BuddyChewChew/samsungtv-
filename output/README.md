# Samsung TV Plus for TiviMate

Generated on: 2025-10-08 01:37:20 UTC

## Files

- `samsung_tvplus.m3u` - M3U playlist file for TiviMate
- `samsung_tvplus.xml` - EPG (Electronic Program Guide) XML file

## TiviMate Setup

1. In TiviMate, go to Settings → Playlists
2. Add a new playlist using the raw GitHub URL for the M3U file:
   ```
   https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_REPO/main/output/samsung_tvplus.m3u
   ```
3. For EPG, go to Settings → EPG and add:
   ```
   https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_REPO/main/output/samsung_tvplus.xml
   ```

## Configuration

This playlist was generated with the following settings:
- Regions: all
- Groups: All
- Include DRM: True
- Starting Channel Number: 1
- Sort By: chno

## Automatic Updates

This playlist is automatically updated daily at midnight UTC via GitHub Actions.

## Notes

- DRM-protected channels are marked with [DRM] suffix
- Some channels may require compatible players that support DRM
- EPG data is region-specific and updates daily
