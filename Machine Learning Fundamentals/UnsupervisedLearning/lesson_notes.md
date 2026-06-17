### Synthetic Datasets for Clustering Intuition
# To build visual intuition, we rely on standard 2D synthetic datasets generated via Scikit-Learn. Understanding why an algorithm succeeds or fails on these shapes is the key to mastering clustering.

    Isotropic Blobs: Well-separated, spherical distributions. Perfect for baseline testing.
    
    Interlocking Moons: Two distinct non-spherical clusters. Tests an algorithm's ability to map continuous density rather than geometric centers.
    
    Anisotropic (Elongated) Blobs: Stretched clusters. Tests algorithms that assume spherical variance.
    
    Noisy/Overlapping Distributions: Clusters with heavy background noise. Tests robustness against outliers.
    
    Varying Density Blobs: Clusters packed at different densities. Tests global parameter limitations.