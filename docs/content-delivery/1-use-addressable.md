---
sidebar_position: 1
title: Use with Addressable
---

# Use with [Addressable](https://docs.unity3d.com/Packages/com.unity.addressables@1.21/manual/index.html)

Please refer to [Unity's official documentation](https://docs.unity3d.com/Packages/com.unity.addressables@1.21/manual/index.html) for the usage of Addressable, and then you could get built assets with the catalog. Assuming your MetaCDN is hosted at http://meta-cdn/.

1. Replace the remote source URL with http://meta-cdn/Stream/PATH-YOU-LIKE (streaming) or http://meta-cdn/Files/PATH-YOU-LIKE (non-streaming).
2. Run build to produce assets with the catalog and archive the directory with Zip.
3. Use http://meta-cdn/UploadDirZip/PATH-YOU-LIKE to upload the remote assets to MetaCDN.

To update your assets, you need to:

1. Update your assets with the Unity Editor, and then archive the directory with Zip.
2. Use http://meta-cdn/CreateOrUploadDirZip/PATH-YOU-LIKE to upload the remote assets to MetaCDN.
