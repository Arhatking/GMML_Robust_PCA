# Geometrical Approach for Robust PCA

Tagent space estimation is an important subproblem of LTSA and GSE manifold learning algorthms. Default approach is local PCA. However, inner manifold of the data can be obtained, this method is sensitive to outliers, which may reduce quality of the embedding when applied on real data.
Robust PCA seems to be a promising alternative to classcal PCA, since it sees every point inducing linear subspace of the ambient space.
This repository goals to test and compare Robust PCA based on Grassmann averages (RPCA), Robust Orthonormal Subspace Learning (ROSL) with classical PCA.