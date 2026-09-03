- [x] Download the spectrum of each source
    - [x] Identifiy their ID or link for the AURORA survey.
    - [x] download the corresponding file
- [x] Obtain the JDA photometry to compare with that reported by Shapley and to input to the ETC
- [ ] Same as above for the r_e (circularized effective radius)
- [ ] Run the corresponding ETC
- [ ] Overplot the estimated S/N


## Notes running the ETC

- Assumming point sources gives very high S/N, way above the real data from AURORA:
    - 100067 -> S/N ~ 6 (should be ~6)
    - 17940 -> S/N ~ 13 (should be ~6)
    - 23927 -> S/N ~ 10 (should be ~4)
    - 29209 -> S/N ~ 22 (should be ~8)
- Using the circularized effective radii reported by Shapley:
    - 100067 -> S/N ~ 4 (should be ~6)
    - 17940 -> S/N ~ 6 (should be ~6)
    - 23927 -> S/N ~ 2.6 (should be ~4)
    - 29209 -> S/N ~ 5 (should be ~8)
