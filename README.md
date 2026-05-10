# Movie Collections Catalog for Nuvio

A custom Nuvio catalog addon that provides 184+ (and counting) curated movie collections. This addon is specifically designed to work in synergy with **AIOMetadata**.

## 🚀 The Purpose
Unlike standard catalogs, this addon contains only **TMDB IDs**. It acts as a structural framework for your media library. Because it relies on IDs, it **must** be used alongside the AIOMetadata addon to fetch and display the actual metadata, posters, and stream links.

## 🌟 Why use this instead of Nuvio's built-in Collection Builder?
While Nuvio has a great native collection builder, but it can't get custom poster like AIOMetadata. I want my visual looks consistent with the rated poster from ERDB that AIOMetadata fetch.

## 🛠️ How to Use

To get the full experience with custom posters and organized folders, follow these steps:

### 1. Configure AIOMetadata
1.  Download `aiometadata-config.json` from [here](https://luqmanfadlli.github.io/Movie-Collections-Catalog/template/aiometadata-config.json)
3.  Go to AIOMetadata configuration page.
4.  Navigate to Configuration and selct **Import Configuration** (it's advised to export your current configuration first for bakup).
5.  Save Configuration, and install it in Nuvio.

### 2. Import Nuvio Collection Folders
1.  Download `nuvio-collection.json` from [here](https://luqmanfadlli.github.io/Movie-Collections-Catalog/template/nuvio-collection.json)
2.  Go to https://nuvioapp.space and login to your account.
3.  If you haven't installed the AIOMEtadata addons, you can install it here.
4.  Navigate to **Collection** and import `nuvio-collection.json`.
