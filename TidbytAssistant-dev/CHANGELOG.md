# Changelog
### 1.0.5
- Change Dockerfile to build pixlet binary.
- Edit scripts to move .star files to tmp directory to work around current bug in pixlet.

## 1.0.4
- Added libwep to image.

## 1.0.3
- Added full path for pixlet app to potentially fix script not finding pixlet app.

## 1.0.2
- Fix to Dockerfile for those building on arm64 architecture.
- Added new service TidbytAssistant: Delete, which allows you to delete apps using their content IDs.
- Be sure to download the most up to date TidbytAssistant integration (ver. 1.0.2)

## 1.0.1
- Added 2 new services: Publish and Text
    - Publish: Add apps to your rotation of apps
    - Text: Push custom text to your device. Supports the various available Tidbyt fonts and colors.
- Be sure to download the most up to date TidbytAssistant integration. (ver. 1.0.1)

## 1.0.0
- Initial release. 
- Be sure to download the most up to date TidbytAssistant integration. (ver. 1.0.0)