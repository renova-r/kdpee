# kdpee 1.0.0.9001

Renova release, based on CRAN kdpee 1.0.0 (archived on CRAN 2024-11-11).

- `src/kdpee.c`: two `Calloc` calls became `R_Calloc` and two `Free` calls became `R_Free`.
- No R code, `NAMESPACE`, `DESCRIPTION` field or help page changed.
- `DESCRIPTION`: `Version` set to `1.0.0.9001`; "Compatibility updates by Renova." appended to `Description`.
- The stale `MD5` file was removed.
- `COPYING` (GNU GPL text) was added; the `License` field is unchanged.
- `README.md` was replaced by a short Renova README and `.Rbuildignore` keeps `README.md` and `NEWS.md` out of the built package.

# kdpee 0.0.0.9000

* Added a `NEWS.md` file to track changes to the package.
