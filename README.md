# UAT_MEDE — U20 · Localitatea / UAT (UAT × An), Prahova

Întrebare: care localități cresc teritorial (suprafață construită GHSL) fără creștere a populației (Eurostat)?

## Reproducere
```
pip install -r requirements.txt
jupyter notebook CP3_MEDE.ipynb   # rulează end-to-end din data/ (~3 min)
```
Tabelele se scriu în `results/`, figurile în `figures/`.

## CP3
- Harta relațiilor: `figures/harta_relatiilor.png`, `results/relatii_*.csv`
- Protocol: split 80/20 aleator, fit doar pe train, 10 seed-uri, k=2, subperioade P1/P2
- Tabel principal (PCA vs. t-SNE, Autoencoder): `results/cp3_tabel_principal.csv`
