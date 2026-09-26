# lhnGlideMap
A custom, high-performance mapping solution for Glide Apps using Mapbox GL JS. Built to bypass native collection boundaries by leveraging GeoJSON data packages [1] and client-side marker clustering [1] to seamlessly render up to 10,000+ location pins [1].

# Glide Custom 10k Map

This repository hosts a webview canvas optimized for Glide Apps. 

### Features
- **Zero Truncation:** Overcomes Glide's native 1,000-pin component limit.
- **Marker Clustering:** Groups thousands of overlapping pins into numeric clusters for mobile-optimized rendering and low data lag.
- **Privacy First:** Relies on structural parameter passing rather than background device tracking.

### Data Input Format
Expects a standard `FeatureCollection` GeoJSON array payload passed via postMessage or URL parameter bridges from the Glide Data Editor.
