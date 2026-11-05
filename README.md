# Benedikt Geier

MALDI-MSI researcher working on gastric tissue biology — *H. pylori*
infection, gastric intestinal metaplasia (GIM), and the lipidome
remodeling that distinguishes them. R + Bioconductor `Cardinal`
workflows on the Bruker timsTOF flex.

## Active projects

Most are private until the associated manuscripts are accepted; the
list is the public-facing index of the ecosystem.

- **[msi-gpcl](https://github.com/benediktkgeier/msi-gpcl)** *(private)* —
  5-patient gastric MALDI-MSI study (Hp ± / GIM ±). V2 pipeline complete
  (17 phases, 65 ranked MS/MS targets); V3 untargeted compartment-resolved
  arc active.

- **[msi-bigmsi-hp](https://github.com/benediktkgeier/msi-bigmsi-hp)** *(private)* —
  Comparative MALDI-MSI of *H. pylori* PMSS1 infection in B6 mouse
  stomach: 18 sections, 8 biological groups, adult- vs neonate-onset.

- **[msi-umap-morph](https://github.com/benediktkgeier/msi-umap-morph)** *(private)* —
  Reproducible R pipeline that morphs MSI cluster maps into their
  cross-sample UMAP and back as palindrome MP4s, for talks and
  supplementary figures.

- **[msi-hp-invitro-lipidome](https://github.com/benediktkgeier/msi-hp-invitro-lipidome)** *(private)* —
  In-vitro MALDI-2 MSI reference lipidome for *H. pylori*: 31 spotted cultures (PMSS1 / G27 backgrounds,
  cfaS / capJ / pldA mutant screens, six clinical isolates) on two replicate slides. Exported as a
  queryable reference database for the organoid and tissue projects.

- **[msi-gastroid-hp](https://github.com/benediktkgeier/msi-gastroid-hp)** *(private, under construction)* —
  *H. pylori* microcolonies in gastric organoids: MALDI-2 MSI with reporter-microscopy registration,
  bacterial vs host chemistry at the colony contact site, per organoid and within section. On hold until
  new data.

- **[organoid-msi-nearfield-citrate](https://github.com/benediktkgeier/organoid-msi-nearfield-citrate)** —
  Publication fork of the intestinal-organoid near-field citrate project (apical-out vs basolateral-out):
  MALDI-timsTOF MSI plus microscopy coregistration, in R.

- **[organoid-msi-metabolic-gradient](https://github.com/benediktkgeier/organoid-msi-metabolic-gradient)** *(private)* —
  The working repo behind that fork: 0 h vs 20 h intestinal organoids, Cardinal v3 preprocessing and the
  PeakMe export pipeline.

## Collaborators

- **[fmg85/PeakMe](https://github.com/fmg85/PeakMe)** *(Florian Geier)* —
  upstream R tool for manual on-tissue / off-tissue MSI peak annotation;
  consumed by `msi-gpcl`, `msi-bigmsi-hp` and `msi-gastroid-hp`.

## Contact

`benedikt.k.geier@gmail.com`
