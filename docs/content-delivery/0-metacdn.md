---
sidebar_position: 0
---

# Use hosted MetaCDN

MetaCDN provides a Tiny CMS Server with several proxy & caching nodes in the cluster, which can be used as a self-hosted [Unity Addressable](https://docs.unity3d.com/Packages/com.unity.addressables@1.21/manual/index.html) Server. For more details, see [Use with Addressable](./use-addressable).

MetaCDN also enables your application with render caching, which can dynamically produce and release render cache to balance the application load. For more details, see [Use Render Caching](./use-render-caching).

Assuming your MetaCDN is hosted at http://meta-cdn/, You can access the file server at http://meta-cdn/Files and other Service at http://meta-cdn/swagger through swagger UI.
