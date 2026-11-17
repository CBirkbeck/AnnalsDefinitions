# Merged-roadmap work on the prerequisite chains of the 100 Annals definitions

Specified in a merged roadmap (`TauCetiRoadmap/<Name>/` at roadmap commit c6ef576, 2026-11-16), not
yet (fully) implemented in Tau Ceti main (7cbfff3, 2026-11-16), and on the prerequisite chain of at
least one definition. Each item was checked against the README section, STATUS.md (snapshot date
given per roadmap; several are stale) and a grep of Tau Ceti code. Item format: status
(NOT-STARTED / PARTIAL with what exists), ready now (yes / no: needs X), definitions served,
evidence. Section and layer ids are the roadmap's own.

## Summary: roadmaps ranked by number of the 100 definitions served

Counts exclude items found DONE. "Ready now" counts items whose verdict begins "yes" (some are "yes for a named sub-part"; see the item).

| Roadmap | # defs served | Items (not-started / partial) | Ready now | Definitions served |
|---|---|---|---|---|
| SchemeAndStackFoundations | 16 | 28 (15 / 13) | 12 | 16, 17, 19, 20, 21, 24, 25, 26, 27, 28, 29, 30, 71, 80, 84, 85 |
| AutomorphicFormsOnReductiveGroups | 13 | 7 (7 / 0) | 4 | 1, 4, 5, 7, 67, 72, 73, 76, 79, 83, 86, 88, 90 |
| ArithmeticLocallySymmetricSpaces | 12 | 3 (3 / 0) | 0 | 1, 4, 7, 62, 67, 72, 73, 76, 77, 79, 88, 90 |
| AbelianSchemesAndArithmeticModuli | 10 | 6 (6 / 0) | 1 | 12, 13, 23, 70, 71, 74, 78, 80, 85, 89 |
| AdelicAlgebraicGroups | 10 | 8 (8 / 0) | 1 | 15, 31, 67, 68, 73, 76, 77, 83, 88, 90 |
| RepresentationTheory/LieGroups | 10 | 4 (1 / 3) | 2 | 1, 4, 5, 7, 15, 31, 54, 62, 79, 83 |
| RiemannianGeometry | 9 | 9 (7 / 2) | 2 | 15, 31, 37, 48, 49, 52, 62, 65, 66 |
| ReductiveGroupsPartII | 8 | 3 (2 / 1) | 2 | 11, 67, 68, 73, 82, 83, 88, 90 |
| ComplexComparisonPartII | 7 | 4 (4 / 0) | 0 | 12, 13, 15, 23, 74, 85, 89 |
| RealSemisimpleLieGroups | 7 | 5 (5 / 0) | 2 | 1, 4, 15, 31, 54, 62, 79 |
| JacobianChallenge | 6 | 4 (0 / 4) | 2 | 19, 30, 71, 80, 84, 85 |
| ReductiveGroups | 6 | 5 (3 / 2) | 1 | 1, 4, 11, 23, 68, 79 |
| SmoothBundlesConnections | 6 | 3 (1 / 2) | 1 | 15, 31, 37, 48, 49, 62 |
| SmoothRepresentationsOfLocalGroups | 6 | 5 (4 / 1) | 2 | 67, 73, 83, 86, 88, 90 |
| EtaleCohomologyFoundations | 5 | 7 (5 / 2) | 2 | 18, 19, 69, 77, 84 |
| ModularCurves | 4 | 2 (1 / 1) | 1 | 25, 26, 69, 71 |
| OperatorTheory/UnboundedOperators | 4 | 5 (4 / 1) | 2 | 34, 35, 40, 45 |
| AlgebraicModuliForArithmeticGeometry | 3 | 2 (2 / 0) | 1 | 25, 26, 29 |
| AnalyticStableMaps | 3 | 3 (3 / 0) | 1 | 56, 60, 63 |
| GeometricCurrents | 3 | 3 (2 / 1) | 0 | 53, 57, 65 |
| GeometricMeasureTheory | 3 | 2 (0 / 2) | 2 | 53, 55, 57 |
| HeegaardFloer | 3 | 5 (2 / 3) | 0 | 56, 60, 64 |
| RepresentationTheory/LieHighestWeight | 3 | 1 (1 / 0) | 1 | 5, 7, 88 |
| SobolevMapsBetweenManifolds | 3 | 5 (5 / 0) | 1 | 41, 42, 47 |
| VonNeumannAlgebras | 3 | 3 (3 / 0) | 1 | 15, 31, 36 |
| ArithmeticGaloisRepresentations | 2 | 3 (2 / 1) | 3 | 69, 89 |
| CharacteristicClasses | 2 | 2 (2 / 0) | 0 | 37, 48 |
| ComplexKahlerGeometry | 2 | 4 (2 / 2) | 1 | 38, 40 |
| CStarAlgebras | 2 | 9 (5 / 4) | 5 | 36, 46 |
| DerivedModuleAlgebra | 2 | 2 (2 / 0) | 0 | 27, 81 |
| EnhancedDerivedSheaves | 2 | 2 (1 / 1) | 0 | 18, 27 |
| GeometricTopology | 2 | 3 (1 / 2) | 1 | 59, 66 |
| MathematicalBilliards | 2 | 5 (5 / 0) | 4 | 92, 93 |
| OperatorTheory/SelfAdjointSpectralTheory | 2 | 1 (1 / 0) | 1 | 35, 45 |
| PseudodifferentialOperators | 2 | 2 (1 / 1) | 1 | 32, 40 |
| PseudoholomorphicCurveAnalysis | 2 | 4 (1 / 3) | 1 | 56, 60 |
| YangMillsConnectionsAndCaloricGauge | 2 | 5 (5 / 0) | 0 | 37, 48 |
| AdicEtaleGeometry | 1 | 2 (1 / 1) | 1 | 22 |
| AdicSpacesPartII | 1 | 1 (0 / 1) | 1 | 22 |
| AdicSpacesPartIV | 1 | 1 (1 / 0) | 0 | 22 |
| AlgebraicModuliForArithmeticGeometryPartII | 1 | 1 (1 / 0) | 0 | 95 |
| AmenableTracesOnCStarAlgebras | 1 | 7 (7 / 0) | 2 | 36 |
| CyclotomicClassGroupsAndStickelberger | 1 | 1 (1 / 0) | 0 | 71 |
| DGAInfinity | 1 | 1 (0 / 1) | 1 | 10 |
| DifferentialGeometry | 1 | 1 (0 / 1) | 0 | 52 |
| FlagVarieties | 1 | 1 (1 / 0) | 0 | 79 |
| FukayaTheory | 1 | 1 (1 / 0) | 0 | 56 |
| IntegralHeckeAndGaloisDeterminants | 1 | 1 (1 / 0) | 0 | 69 |
| NoncommutativeIntegration | 1 | 1 (1 / 0) | 0 | 46 |
| PerfectoidSpaces | 1 | 1 (0 / 1) | 0 | 81 |
| RiemannianGeometry/MinimalSurfaces | 1 | 1 (1 / 0) | 0 | 52 |
| SpectralSequencesAndConvergence | 1 | 3 (3 / 0) | 1 | 6 |
| SpinGeometry | 1 | 1 (0 / 1) | 0 | 64 |
| StableReduction | 1 | 2 (0 / 2) | 1 | 24 |
| SymplecticGeometry/CotangentLagrangian | 1 | 1 (0 / 1) | 1 | 92 |
| TaubesGromov | 1 | 1 (1 / 0) | 0 | 60 |
| VariationalMethods | 1 | 1 (1 / 0) | 0 | 34 |

Distinct definitions served: 78. Items: see per-roadmap sections.

## Key ordering facts across items

- SchemeAndStackFoundations §4.14 (Hilbert/Quot) is the choke point for the Jacobian cluster
  (defs 19, 24, 30, 71, 80, 84, 85). Required order: JacobianChallenge §C.1 coherence (whose proper
  case needs SSF §4.12 Chow's lemma; only Chow's graph-closure construction is in code) and §C.2
  base change, then SSF §4.14, then §D.3 Hilbert quotients and §D.4 projective Picard
  representability, then §D.5 `Pic⁰` and the Abel maps and §D.8 the Jacobian. `Symᵈ X` (§C.4) needs
  only §C.2, not §4.14; §D.5 needs it.
- SSF Layer 1 is a linear chain: §1.3 (done), then §1.5, §1.6, §1.7/§1.8, §1.9, then §1.19, §1.20,
  §1.21, §1.22, §1.23. §1.5 is partial (`EtaleEquivRel` in code), so §1.6 waits on §1.5's quotient
  sheaf. §1.18 has `StackInGroupoids` in code; its stackification and 2-fibre products, which §1.19
  needs, can proceed in parallel with §1.5.
- LieGroups Layer 7 (compact real form, Cartan involution θ) unblocks Layer 9 beyond `GL n`. Layer 9
  in turn heads the real-reductive chain: ArithmeticLocallySymmetricSpaces ALS.F.1 and ALS.0.1–ALS.0.3,
  then AutomorphicFormsOnReductiveGroups §2.3a and §§2.3–2.4, then RealSemisimpleLieGroups Layers 2–5
  and §5.7, for defs 1, 4, 7, 15, 31, 54, 62, 79. Layer 7 is partial (`serreCompactInvolution`, the
  conjugate-linear Chevalley involution of a Serre presentation) and ready now; RealSemisimpleLieGroups
  Layers 0–1 can start now with the existence of Cartan involutions as a hypothesis.
- EtaleCohomologyFoundations §F.0.1 (étale module sheaves) precedes every étale cohomology item
  (§F.1, §F.2.x, §F.4.x). It is partial (geometric stalks and finite lisse sheaves in code), and its
  constructible part is ready now.
- RiemannianGeometry R5a (B, S, normal connection) is formally blocked on SmoothBundlesConnections
  B3–B4 per its README, though that dependency looks soft. It heads the chain R5a, then R5a.2 (with
  R5a.1, which is partial and ready now), then R5b, then R5c, then MinimalSurfaces MS6, for defs 49,
  52, 65, 66.

## TauCetiRoadmap/SchemeAndStackFoundations
STATUS.md snapshot: a5cae7f 2026-11-16, generated against Tau Ceti aa6e43e (Tau Ceti checked at 7cbfff3ef, 2026-11-16)

### §1.4 AlgSpace.overEquiv (algebraic spaces over a base)
- Status: PARTIAL: §1.3 is complete in code: the predicates `SchemePresheaf`, `Spaces.RepresentableDiagonal`, `Spaces.EtaleAtlas`, `Spaces.IsAlgebraicSpace` (TauCeti/AlgebraicGeometry/AlgebraicSpace/Basic.lean), `Spaces.isAlgebraicSpace_of_etale_cover` with `EtaleAtlas.of_sigma` (AlgebraicSpace/EtaleCover.lean) and `IsAlgebraicSpace.diagonal_locallyQuasiFinite` with `EtaleAtlas.locallyOfFiniteType_diag` (AlgebraicSpace/Diagonal.lean). §1.4 has `Spaces.AlgSpace`, `toPresheaf`, `ofScheme` (Full/Faithful), `homFromSchemeEquiv`, terminal `Spec ℤ`, initial `∅` (AlgebraicSpace/Category.lean). The presheaf-level input exists: `TauCeti.overYonedaEquivPresheafOver X : Over (yoneda.obj X) ≌ (Over X)ᵒᵖ ⥤ Type` with `overYonedaEquivPresheafOverYonedaIso` (TauCeti/CategoryTheory/Comma/Presheaf/OverYoneda.lean). Missing: `IsAlgebraicSpaceOver S` and `AlgSpace.overEquiv` (algebraic spaces over `h_S` ≃ fppf sheaves on `Over S` satisfying `IsAlgebraicSpaceOver S`).
- Ready now: yes (needs only §1.3, which is done; the presheaf equivalence is in code)
- Serves defs: 16, 20, 28
- Evidence: README l.2899 "### 1.4 The category of algebraic spaces" (l.2905 `IsAlgebraicSpaceOver S`); STATUS Layer 1 remaining "... algebraic spaces over a base (1.4), 1.5 onward"; grep `overEquiv|IsAlgebraicSpaceOver` in AlgebraicSpace/ empty.

### §1.2 fppf descent of quasi-finite morphisms and of algebraic spaces
- Status: NOT-STARTED
- Ready now: yes (needs §1.3, done, including `isAlgebraicSpace_of_etale_cover`)
- Serves defs: 20 ("fppf descent for alg spaces")
- Evidence: README l.2819 "### 1.2 Fppf descent of quasi-finite morphisms and of algebraic spaces" (Needs §1.3; Mathlib `Presheaf.IsSheaf`, `MorphismProperty.presheaf`, `LocallyQuasiFinite`); no matching declarations in Tau Ceti.

### §1.5 étale equivalence relations and the quotient sheaf
- Status: PARTIAL: `TauCeti.AlgebraicGeometry.Spaces.EtaleEquivRel s t` (Mathlib's internal `IsEquivalenceRelation t s` with `s`, `t` étale) with `refl`, `symm`, `trans` and their laws, `swap`, `hom_ext`, `etale_refl`, `etale_trans`, `id`, `of_isKernelPair` (TauCeti/AlgebraicGeometry/AlgebraicSpace/EtaleEquivRel.lean), on `TauCeti.CategoryTheory.isEquivalenceRelation_iff` (jointly monic plus an equivalence relation on `T`-points, the README's `IsEquivRel`), `IsKernelPair.isEquivalenceRelation` and `IsEquivalenceRelation.id` (TauCeti/CategoryTheory/EquivalenceRelation.lean). Missing: `EtaleEquivRel.restrict`, `EtaleEquivRel.ofAtlas`, and all of the quotient sheaf: `quotientSheaf s t`, `quotientSheaf.π`, `.desc`, `.kernelPair`, `.represented_of`, `.restrict`.
- Ready now: yes (needs §1.3 only)
- Serves defs: 16, 20, 28 (as the start of the §1.6–§1.9 chain)
- Evidence: README l.2917 "### 1.5 Étale equivalence relations and the quotient sheaf"; grep `quotientSheaf` in AlgebraicSpace/ empty (the hits in Curves/NodalGluing/ and AlgebraicGeometry/Quotient/EquivalenceRelation.lean are unrelated).

### §1.6–§1.9 presentations, points |X|, fibre products and étale-local properties, separation and properness
- Status: NOT-STARTED (no `etaleQuotientTheorem`, `spacePresentation`, `points`, `isAlgebraicSpace_pullback`, `EtaleLocal`, `IsSeparatedSpace`, `IsProperSpace`)
- Ready now: no: §1.6 needs §1.5's `quotientSheaf` (§1.5 is partial: `EtaleEquivRel` is in code, the quotient sheaf is not); §1.7 and §1.8 need §1.6; §1.9 needs §1.7 and §1.8
- Serves defs: 16, 20, 28 (§1.7 `points F` for 28; §1.9 `IsProperSpace` for 16/20)
- Evidence: README l.2955 "### 1.6 Quotients by étale equivalence relations and presentations" (Needs §1.3, §1.5; `etaleQuotientTheorem` is about "the quotient sheaf `U/R`"), l.2969 "### 1.7 Points of an algebraic space" (Needs §1.3, §1.6), l.2996 "### 1.8 Fibre products and étale-local properties of morphisms" (Needs §1.3, §1.6), l.3064 "### 1.9 Separation and properness" (Needs §1.3, §1.7, §1.8); every named declaration greps empty.

### §1.14 groupoids in algebraic spaces, stabilizer, stabilizerAt
- Status: NOT-STARTED (TauCeti/AlgebraicGeometry/Inertia/Basic.lean is decomposition/inertia groups of a point under a group acting on a scheme, unrelated)
- Ready now: no: needs §1.5, §1.8, §1.13 (group spaces, which needs §1.4, §1.8)
- Serves defs: 28, 29
- Evidence: README l.3247 "### 1.14 Groupoids in algebraic spaces and stabilizers", l.3267 "`stabilizerAt` for a field-valued point"; grep `stabilizerAt` returns nothing.

### §1.18 StackInGroupoids, stackification, 2-fibre products
- Status: PARTIAL: `TauCeti.AlgebraicGeometry.StackInGroupoids` (a `SchPseudofunctor` with groupoid fibres that is a stack for `Scheme.fppfTopology`), `StackInGroupoids.Hom` (strong transformations), `Hom.IsFiberwiseEquiv` with identities, composition and two-out-of-three (TauCeti/AlgebraicGeometry/Stack/StackInGroupoids.lean). Missing: `StackInGroupoids.ofSheaf`, `yonedaEquiv`, `isFiberedInGroupoids`, `limit`, the site-level `Stack.stackification` with `toStackification`, `isStack_stackification`, `stackificationUniversal`, and `Stack.twoFibreProduct`/`twoFiberProduct`. §1.1's `Descent.qcohPseudofunctor` (an fpqc prestack: Descent/QuasicoherentSheaf/Prestack.lean) and fpqc uniqueness of descended morphisms are prerequisites, not §1.18.
- Ready now: yes: the missing definitions use only Mathlib `Pseudofunctor`, `IsStack`, `DescentData`, `sheafHom`, `CategoricalPullback`, `StrongTrans` and the existing carrier; README lists §1.1, which is PARTIAL (effective descent of objects missing)
- Serves defs: 20, 24, 27, 28, 29
- Evidence: README l.3538 "### 1.18 Stacks in groupoids, stackification and 2-fibre products", Needs l.3580 "§1.1; Mathlib `Pseudofunctor`, `IsStack`, `IsPrestack`, ..."; grep `twoFiberProduct|twoFibreProduct|stackification|yonedaEquiv` in AlgebraicGeometry/Stack/ empty.

### §1.19 IsRepresentableBySpaces, IsAlgebraicStack, IsDeligneMumford
- Status: NOT-STARTED
- Ready now: no: needs §1.4 (partial), §1.9, §1.18 (partial: 2-fibre products missing)
- Serves defs: 16, 17, 20, 24, 27, 28, 29
- Evidence: README l.3612 "### 1.19 Representable morphisms, algebraic stacks and Deligne–Mumford stacks" (Needs §1.4, §1.9, §1.18); grep `AlgebraicStack|DeligneMumford` empty.

### §1.20 inertia, automorphismGroup, Stacks.points, IsProperStack
- Status: NOT-STARTED
- Ready now: no: needs §1.7, §1.8, §1.9, §1.14, §1.18, §1.19
- Serves defs: 16, 24, 28, 29
- Evidence: README l.3638 "### 1.20 Inertia, the setoid criterion, properties of morphisms and presentations" (`automorphismGroup x` l.3641, `Stacks.points` l.3652, `IsProperStack` l.3679); grep `automorphismGroup` hits only unrelated algebra/topology files; `IsProperStack`, `Stacks.points` empty.

### §1.21 quotient stacks, BG, root stacks
- Status: NOT-STARTED
- Ready now: no: needs §1.13, §1.14, §1.15, §1.19, §1.20
- Serves defs: 17, 29
- Evidence: README l.3744 "### 1.21 Quotient stacks, line bundles with a section, root stacks", Needs l.3770; grep `QuotientStack|classifyingStack` empty.

### §1.22 Stacks.QCoh, QCoh.pushforward
- Status: NOT-STARTED
- Ready now: no: needs §1.1 (partial), §1.11, §1.18 (partial), §1.21
- Serves defs: 17, 27, 29
- Evidence: README l.3797 "### 1.22 Quasi-coherent modules on stacks" (Needs §1.1, §1.11, §1.18, §1.21; Mathlib `CoGrothendieck`); grep `Stacks.QCoh` empty.

### §1.23 moduli functors, coarse moduli, Keel–Mori, IsTame
- Status: NOT-STARTED (the existing `IsTame` hits are tame ramification, unrelated)
- Ready now: no: needs §1.17, §1.19, §1.20, §1.22
- Serves defs: 16, 17, 24
- Evidence: README l.3829 "### 1.23 Moduli functors, fine and coarse moduli spaces, Keel–Mori, tame stacks", Needs l.3866; grep `CoarseModuli|KeelMori` empty.

### §2.6 quasi-coherent cohomology (cited for 20)
- Status: PARTIAL: higher direct images of quasi-coherent modules along qcqs morphisms are quasi-coherent (`Scheme.Hom.isQuasicoherent_higherDirectImage`), with sections over a basic open of an affine base `Hⁿ(f⁻¹ D(g), M)` (`Scheme.Hom.higherDirectImageBasicOpenSectionsAddEquiv`) and the localization property (`isLocalizedModule_higherDirectImagePresheaf_map_basicOpen`) (Cohomology/HigherDirectImage/Quasicoherent.lean, Presheaf.lean, Scalars.lean); flat base change over an affine base for qcqs `X` (`TauCeti.AlgebraicGeometry.bijective_cohomologyBaseChange`, Cohomology/FlatBaseChange.lean); uniform vanishing (QuasiSeparated.lean); `H^q(ℙⁿ_A, O(d))` in every degree, the top degree as the dual of `Sym^j` (`Module.Basis.nonempty_linearEquiv_cohomology_top_twistingSheaf_dual`, Cohomology/ProjectiveSpace/TopDual.lean). Missing: commutation of `R^p f_*` with filtered colimits and with flat base change over a non-affine base, `ample_serre_vanishing`, `proper_fibreDimension_vanishing`, the vanishing-implies-affine direction of `serre_affineness_criterion` (`QCoh.isAffine_of_H1_vanishing`).
- Ready now: yes (needs §0.3, §0.4, both begun, plus existing Tau Ceti cohomology; `ample_serre_vanishing` also needs StableReduction Layer 2 relative ampleness)
- Serves defs: 20, 21 (via §2.7, §2.10)
- Evidence: README l.4357 "### 2.6 Quasi-coherent cohomology", Needs "§0.3, §0.4; Tau Ceti `Scheme.Modules.Cohomology`, ...; StableReduction Layer 2; JacobianChallenge Layer C"; grep `ample_serre_vanishing|isAffine_of_H1` empty.

### §2.7 cohomology with supports and local cohomology
- Status: PARTIAL: the topological-space case for abelian and module sheaves: cohomology with closed supports `CategoryTheory.Sheaf.supportedH` with the support long exact sequence and excision (TauCeti/Topology/Sheaves/SupportedCohomology.lean, SupportedCohomology/), the local cohomology sheaves `supportedHSheaf` with their long exact sequence and the edge comparison (Topology/Sheaves/LocalCohomology/); `localCohomology_degreeZero` as `localCohomology.degreeZeroToModule_injective` and `range_degreeZeroToModule` (Algebra/Homology/LocalCohomology/DegreeZero.lean). Missing: the scheme versions `sectionsWithSupport`, `cohomologyWithSupport` with their `O(X)`-module structure, `rHZ_adjunction`, `localToGlobal`, `localCohomology_colimit_ext_comparison`, `localCohomology_module_comparison`, `localCohomology_flat_baseChange`, `depth_localCohomology_vanishing`.
- Ready now: no for the scheme-level part: needs §2.1 and §2.6 (partial). The ring-level `localCohomology_flat_baseChange` and `depth_localCohomology_vanishing` use only Mathlib's `localCohomology` and depth and could start now
- Serves defs: 21
- Evidence: README l.4433 "### 2.7 Cohomology with supports and local cohomology" (Needs §0.17, §2.1, §2.6; *Lean:* "nothing of this subsection"); grep `sectionsWithSupport|cohomologyWithSupport` empty.

### §2.10 comparisons between the fppf, étale, Nisnevich and Zariski topologies
- Status: PARTIAL: the étale-to-Nisnevich morphism of topoi `etaleToNisnevich X` through its functors: `AlgebraicGeometry.Scheme.etaleToNisnevichPushforward` (direct image, fully faithful), `etaleToNisnevichPullback` (étale sheafification, exact when sheafification preserves finite limits), `etaleToNisnevichAdjunction` (TauCeti/AlgebraicGeometry/Sites/Nisnevich/EtaleComparison.lean). Missing: `epsilonFppfEtale`, `aX`, `nisnevichToZariski`, `comparison_comp`, `comparison_baseChange`, `aX_inverseImage_obj`, `quasiCoherent_topology_comparison`, `etale_pullback_fppf_comparison`, `smoothGroup_fppf_etale_comparison`, and the pro-étale part (`Scheme.toProEt`, `proetalePushforward`, `proetaleComparison`).
- Ready now: no for the cohomology comparisons: they need §2.1, §2.6, §2.9, §2.12 (all partial). The remaining morphisms of topoi `epsilonFppfEtale`, `aX`, `nisnevichToZariski` can be defined from the Mathlib topologies and the existing Nisnevich site, as `etaleToNisnevich` is
- Serves defs: 21 (20 also cites it)
- Evidence: README l.4643 "### 2.10 Comparison morphisms between the topologies of a scheme", Needs "§2.1, §2.6, §2.9, §2.12"; grep `epsilonFppfEtale|nisnevichToZariski|quasiCoherent_topology_comparison|toProEt` empty.

### §2.20 relative dualising complexes, Serre duality (cited for 20)
- Status: NOT-STARTED
- Ready now: no: needs §0.18, §2.18, §2.19, §2.21
- Serves defs: 20
- Evidence: README l.5380 "### 2.20 Relative dualising complexes and modules, Serre duality, curve comparison"; grep `relativeDualizingModule|RelativeDualizingComplex|cm_serre_duality` empty.

### §4.1 thickenings and formally smooth/étale morphisms (cited for 20)
- Status: PARTIAL: thickenings (Morphisms/Thickening.lean); `TauCeti.AlgebraicGeometry.FormallySmooth` and `FormallyEtale` for morphisms of schemes (lifting along affine first-order thickenings), stable under isomorphisms, composition and base change, `FormallyEtale.formallySmooth`, `formallyEtale_iff` (Morphisms/FormallySmooth.lean). Missing: `IsThickening.factor_firstOrder`, `formallySmooth_specMap_iff`, `FormallySmooth.iff_affineLocally`, `FormallyEtale.of_isOpenImmersion`, `FormallySmooth.of_smooth`, `smooth_iff_formallySmooth`, `etale_iff_formallyEtale`, `smooth_lifting_torsor`.
- Ready now: yes for the API and the smooth/étale comparisons; `smooth_lifting_torsor` needs §2.3 (partial)
- Serves defs: 20
- Evidence: README l.6278 "### 4.1 Thickenings, formally smooth and étale morphisms, the lifting criterion, torsors of lifts", Needs "§2.3; Tau Ceti `.../Morphisms/Thickening.lean`"; STATUS Layer 4 remaining "lifting criterion (4.1)".

### §4.14 Hilbert/Quot/Hom/Isom schemes
- Status: NOT-STARTED for Hilbert/Quot/Hom/Isom (no `hilbert_quot_schemes`, Quot or Hilb functor anywhere in Tau Ceti)
- Ready now: no: needs §2.6 (partial), §4.12 (partial: the graph-closure construction of Chow's lemma, `TauCeti.AlgebraicGeometry.graphClosure` with `isModification_graphClosureFst` and `isImmersion_graphClosureSnd`, Morphisms/Modification/GraphClosure.lean; no `generic_flatness`, `chow_lemma`), StableReduction Layer 2 (partial: "coherent cohomology and base change ... ampleness criterion and openness" remaining), JacobianChallenge §§C.1–C.2 (partial: "coherence of R^q f_* for proper f, flat base change over a non-affine base, semicontinuity, cohomology and base change" remaining). JacobianChallenge §§D.3–D.4 consume §4.14; §C.4's `Symᵈ` does not
- Serves defs: 24, 30 (and, through JacobianChallenge §§D.3–D.4, 19, 71, 80, 84, 85)
- Evidence: README l.7025 "### 4.14 Hilbert and Quot schemes", Needs l.7042 "§2.6, §4.12; StableReduction Layer 2; JacobianChallenge Layer C". STATUS's Layer 4 "remaining" list (lifting criterion 4.1, deformation functors 4.3, formal functions and algebraization 4.9–4.10, strict transforms 4.11, Bertini 4.13) only names sections that have started; §4.14 is untouched, not done.

### §4.14 (Grassmannian clause) relative Grassmannian Gr(E, d), Plücker embedding
- Status: PARTIAL: the affine case is done. `Module.Grassmannian.scheme R M k` over `Spec R` for any module `M`, with charts and gluing (Grassmannian/Basic.lean), functor of points on affine tests (`schemeHomEquiv`, Points.lean), separated and proper for finite `M` (`isProper_toSpec`, Proper.lean), base change along `Spec R' → Spec R` (`Module.Grassmannian.isPullback_baseChangeHom`, BaseChange.lean), plus ideal/rank/isotropic loci and the universal quotient. Missing: gluing over a non-affine base `S`, representability on all `S`-schemes, the Plücker closed immersion with `det Q` very ample. No `Plucker` in AlgebraicGeometry; there is only linear-algebra `LinearAlgebra/Projectivization/Plucker.lean`.
- Ready now: yes. This clause does not need §4.12; it is the same object that ModularCurves §0.7 owns (see below), so implement it once there
- Serves defs: 25, 26 (through AlgebraicModuliForArithmeticGeometry §1.3, whose coherent Grassmannian is built from this locally free one)
- Evidence: README l.7035 "The construction embeds Quot into a relative Grassmannian, which is stated here: for `S` Noetherian, `E` locally free of rank `r`..."; ModularCurves §0.7 claims ownership of the same object.

### §4.15 StableCurves.Mbar g n
- Status: NOT-STARTED (grep `Mbar|StableCurves|isom_stable_curves` empty)
- Ready now: no: the definition needs §1.18 `StackInGroupoids` (in code) and StableReduction Layer 3 stable families (partial: "semistable and stable families with their criteria" remaining). Algebraicity needs §1.20, §4.6, §4.14 and StableReduction Layers 2–3, 8–9
- Serves defs: 24
- Evidence: README l.7054 "### 4.15 The moduli stack of stable pointed curves" (l.7056 "Define `StableCurves.Mbar g n : StackInGroupoids` (§1.18)").

### §4.11 modifications and strict transforms (weak link for 25)
- Status: PARTIAL: `TauCeti.AlgebraicGeometry.IsModification` with `.birational`, `.comp`, `.isIso_of_isFinite` (Morphisms/Modification/*); the centre: `Scheme.Hom.isoLocus`, `Scheme.Hom.centre` (Morphisms/IsoLocus.lean) with `IsModification.dense_isoLocus`, `IsModification.isNowhereDense_centre` (Modification/Centre.lean); the strict transform under a blow-up as a scheme-theoretic closure (Blowup/StrictTransform.lean, Blowup/Pullback.lean). Missing: `IsModification.functionField_equiv`, `.isAlteration`, and the general witness-based `strictTransform*` API (`strictTransform_eq_closure`, `strictTransformModule`, `strictTransform_supportComparison`).
- Ready now: yes (Needs §0.9 and StableReduction Layer 4 blow-ups, which exist)
- Serves defs: 25
- Evidence: README l.6824 "### 4.11 Modifications and strict transforms"; STATUS Layer 4 remaining "strict transforms (4.11)"; grep `functionField_equiv|isAlteration|strictTransformModule` empty.

### §0.20 Japanese/Nagata rings, finiteness of normalization
- Status: PARTIAL: `TauCeti.Ring.IsN1`, `IsJapanese`, `IsUniversallyJapanese`, `IsNagata` and their API (RingTheory/Japanese.lean, Nagata.lean, UniversallyJapanese.lean), `IsJapanese.polynomial`, `IsJapanese.of_quasiFinite` (the README's *IsJapanese.of_quasiFinite_extension*, RingTheory/Japanese/QuasiFinite.lean), `IsUniversallyJapanese.isNagata_of_finiteType`, and `isFinite_fromNormalization_of_isJapanese` (AlgebraicGeometry/Normalization/Finite.lean). Missing: Nagata's theorem, i.e. `IsNagata.polynomial`, `IsNagata.of_finiteType`, `isNagata_iff_isUniversallyJapanese`, `IsNagata.integralClosure_finite`, and the complete-local cases.
- Ready now: yes (Needs only existing Tau Ceti files)
- Serves defs: 26
- Evidence: README l.1930 "### 0.20 Japanese and Nagata rings"; STATUS Layer 0 remaining "0.20-0.21", which understates §0.20: grep shows none of the missing names. 26's finiteness does not wait on this item: finite-type algebras over a field are Japanese and Nagata (`IsUniversallyJapanese.of_field`, `.isJapanese`, `.isNagata_of_finiteType`), and `isFinite_fromNormalization_of_isJapanese` turns that into finiteness of normalization for integral schemes of finite type over `k`.

### §3.3 degrees of vector bundles
- Status: PARTIAL: `FiniteLocallyFreeSheaf.FixedRank.vectorBundleDegree` (VectorBundle/Degree.lean) with additivity in short exact sequences under finiteness hypotheses on cohomology (`vectorBundleDegree_add_of_shortExact`, `_of_isCurveOver`), direct sums (`vectorBundleDegree_biprod`), `_elementaryModification`, `_baseChange`, pullback along finite flat maps (`vectorBundleDegree_pullback_of_finrank_eq`, `vectorBundleDegree_pullback_eq_finrank_functionField_mul`), twisting by a line bundle and by an effective Cartier divisor (`vectorBundleDegree_twist`, `vectorBundleDegree_twist_of_isEffective`), and tensoring a finitely supported modification with a vector bundle (`vectorBundleDegree_tensor_eq_add_mul_eulerCharBelow_of_shortExact`). Rank-one Riemann–Roch `InvertibleSheaf.eulerCharBelow_eq_relativeDegree_add_one_sub_genus` (WeilDivisor/Scheme/RiemannRoch/Basic.lean) and `LineBundleClass.intersectionNumber` (IntersectionNumber/Basic.lean). Missing: `_tensor` for a general vector bundle `V`, `_dual`, `_det`, the discharge of the finiteness hypotheses on proper `X` of dimension `≤ 1`, `vectorBundle_riemann_roch`, `curve_serre_duality`.
- Ready now: yes for `_tensor`, `_dual`, `_det` under the existing finiteness hypotheses (the dual and determinant are in VectorBundle/Dual/ and VectorBundle/Determinant/); discharging the hypotheses needs §2.6, and Riemann–Roch and duality need §2.6 and §2.20
- Serves defs: 24 (curve class β)
- Evidence: README l.5863 "### 3.3 Degrees of vector bundles, Riemann–Roch and Serre duality on curves"; STATUS Layer 3 remaining "degree laws for tensor, dual and determinant, Riemann-Roch on curves (3.3)".

### §3.7 Picard stacks, universal sections, Abel maps
- Status: NOT-STARTED (`picardStack`, `sectionStack`, `picard_norm_sequence` absent). Functor-level Abel maps exist in TauCeti/AlgebraicGeometry/PicardFunctor/Abel/*, but they belong to JacobianChallenge Layers D/F, not to §3.7's stack-level maps.
- Ready now: no: needs §1.18 (partial), §1.19, §3.4, §3.5, §3.6 and JacobianChallenge Layers C–D
- Serves defs: 30
- Evidence: README l.6146 "### 3.7 Picard stacks, universal sections, Abel maps and the norm sequence", Needs l.6183 "§1.18, §1.19, §3.4, §3.5, §3.6; JacobianChallenge Layers C–D".

### §5.2 proper pushforward beyond closed immersions
- Status: PARTIAL: cycle-level pushforward over a field, `Chow.cyclesMap` (functorial, degree-compatible), in Chow/Pushforward.lean; Chow-group pushforward along closed immersions (Chow/ClosedImmersion.lean); restriction of cycles to an open subscheme `Chow.cyclesRestrict` (the flat pullback along an open immersion) and the cycle-level localization sequence `Chow.range_cyclesPushforward_eq_ker_cyclesRestrict` (Chow/OpenRestriction.lean). Missing: descent of proper pushforward to `ChowGroup`, general `flatPullback`, `flatPullback_properPushforward`, `localization_exact` on Chow groups.
- Ready now: yes (needs §5.1, which is present; injectivity of homotopy invariance needs §5.4)
- Serves defs: 16, 27
- Evidence: README l.8057 "### 5.2 Proper pushforward, flat pullback and the localisation sequence"; STATUS Layer 5 remaining "proper pushforward on Chow groups, flat pullback and Chow localization (5.2)".

### §5.4 projective bundles and Chern classes
- Status: NOT-STARTED (grep `chernClass|ChernClass|firstChernClass` empty in AlgebraicGeometry)
- Ready now: no: needs §0.3 (begun), §5.2 (partial), §5.3 (not started; needs §3.3, §5.1, §5.2)
- Serves defs: 27
- Evidence: README l.8122 "### 5.4 Projective bundles and Chern classes", Needs l.8142 "§0.3, §5.2, §5.3; AlgebraicVectorBundles".

### §5.5 normalCone, deformationToNormalCone, refined Gysin
- Status: NOT-STARTED
- Ready now: no: needs §0.2, §0.3, §5.2, §5.3, §5.4 and StableReduction Layer 4. `normalCone` and `conormal` as definitions need only §0.2 (relative Spec) and Mathlib `reesAlgebra`, so they could start now
- Serves defs: 27
- Evidence: README l.8166 "### 5.5 Normal cones, deformation to the normal cone and refined Gysin maps"; grep `normalCone|deformationToNormalCone|refinedGysin` empty.

### §5.9–§5.10 surface pairing Chow.intersectionNumber, numerical equivalence, Num
- Status: PARTIAL: the definitions are in code: `Chow.intersectionNumber k S L M` (`χ(𝒪) − χ(L⁻¹) − χ(M⁻¹) + χ(L⁻¹ ⊗ M⁻¹)`, symmetric, invariant under isomorphism), its descent `Chow.classIntersectionNumber` to `LineBundleClass S`, `Chow.NumericallyEquivalent` and the quotient type `Chow.Num` with the descended pairing (AlgebraicGeometry/Chow/SurfaceIntersection.lean). Missing: bilinearity of the pairing and the group structure on `Num` (from the numerical polynomial, Stacks 0BEM), the comparison with intersection of curves, adjunction, Riemann–Roch on surfaces, Noether's formula, Hodge index.
- Ready now: yes for bilinearity and the group structure on `Num`. The theorems (Hodge index, Riemann–Roch on surfaces) need §2.20, §3.3, §5.3, §5.6.
- Serves defs: 19
- Evidence: README l.8519 "### 5.9 Surfaces: the relative intersection pairing ...", l.8625 "### 5.10 ...", l.8639 "**Numerical equivalence.** *Chow.NumericallyEquivalent* / *Num*".

### §5.10 "Numerical Néron–Severi finiteness" `Num.free_finiteRank`
- Status: NOT-STARTED
- Ready now: no: needs the group structure on `Num` (above) and the Néron–Severi theorem
- Serves defs: 78 (paper only, not the definition)
- Evidence: README l.8649 "**Numerical Néron–Severi finiteness.** *Num.free_finiteRank*". It is stated only for smooth projective surfaces over algebraically closed fields.

## TauCetiRoadmap/ReductiveGroupsPartII
STATUS.md snapshot: d92acc5 2026-11-09 (Tau Ceti checked at 7cbfff3ef, 2026-11-16)

### RG2.0 Topologies on rational points (local and adelic G(F_v))
- Status: PARTIAL. Exists: the affine point topology and topological group (Topology/Algebra/PointTopology/Basic.lean, Group.lean, Separation.lean); compact open integral points `isOpenEmbedding_integralPoints` (Topology/Algebra/PointTopology/IntegralPoints.lean); congruence subgroups (Algebra/AlgebraicGroup/CongruenceSubgroup/Topology.lean, ProP.lean); scheme point topology with open and closed immersions, separation and functoriality (PointTopology/Scheme/, including ClosedImmersion.lean, Separation.lean, Functoriality.lean), fibre products as homeomorphisms of points `pointsHomeomorphOfIsPullback` (Scheme/FiberProduct.lean) and local compactness for schemes locally of finite type `locallyCompactSpace_of_locallyOfFiniteType` (Scheme/LocallyCompact.lean); Frobenius fixed points of Ĕ, `TauCeti.MaxUnramifiedCompletion.fixedPoints_frobenius`, `fixedPoints_integerFrobenius`, `frobenius_congr` (NumberTheory/LocalField/Unramified/Frobenius.lean), and `G(E) = G(Ĕ)^σ` on points of affine groups, `rationalPointsContinuousMulEquiv` (NumberTheory/LocalField/Unramified/Points.lean). Missing: smooth maps open on points and analytic charts with Haar Jacobians (the archimedean charts are here).
- Ready now: yes. The remaining items depend only on this layer and on Mathlib/LocalFields. Adelic points themselves are owned by AdelicAlgebraicGroups (see its section), which consumes the RG2.0 analytic charts.
- Serves defs: 67, 68, 73, 83, 90
- Evidence: README l.437 "## Layer RG2.0: topologies on rational points"; STATUS "remaining: smooth maps open on points, analytic charts and Haar Jacobians, Frobenius fixed points of Ĕ, scheme-level functoriality" (STATUS predates `fixedPoints_frobenius`, `rationalPointsContinuousMulEquiv` and the scheme functoriality files).

### RG2.3 (RG2.3.1) Reductive integral models and hyperspecial subgroups
- Status: NOT-STARTED. No `SmoothModel`, `IsHyperspecialSubgroup` or `ModelField`. The relative reductivity predicate `reductiveCommHopfAlgPropertyOver` exists (Algebra/AlgebraicGroup/Reductive/Over.lean).
- Ready now: yes for RG2.3.1 (*smooth-affine-model*, *reductive-model*): it needs RG2.0 integral points (done) and ReductiveGroups Layer 3. The rest of RG2.3 (parahorics, Bruhat-Tits schemes) needs RG2.1 (partial) and RG2.2 (untouched).
- Serves defs: 67, 82, 83, 88, 90 (88 and 90 through SmoothRepresentationsOfLocalGroups SR.4 and AdelicAlgebraicGroups AA.3.1)
- Evidence: README l.3760 "## Layer RG2.3: parahoric and congruence group schemes", l.3858 "**Reductive models over O and hyperspecial subgroups.** (*reductive-model*)"; STATUS RG2.3 "untouched". AdelicAlgebraicGroups l.2572 and SmoothRepresentationsOfLocalGroups (From ReductiveGroupsPartII) cite RG2.3 *reductive-model*, *hyperspecial-vertices*.

### RG2.5 Dual group and L-group
- Status: NOT-STARTED. No `AbsoluteRootData`, `LGroup` or dual-group declarations. Supplier pieces exist: `TauCeti.Pinning`, `RootPairingIsogeny`, `centerGroupScheme`, `IsCentralIsogeny`.
- Ready now: no: needs RG2.1 (π₁(G), z-extensions; partial), the ReductiveGroups Layer 7 root datum and the Layer 9 pinned Chevalley-Demazure group (both partial).
- Serves defs: 11, 88, 90 (through SmoothRepresentationsOfLocalGroups SR.4.2 spherical parameters)
- Evidence: README l.6704 "## Layer RG2.5: integral dual data", l.6724 "### RG2.5.1 the dual group and its Galois action", l.6931 "### RG2.5.2 the L-group and its functoriality"; STATUS RG2.5 "untouched".

## TauCetiRoadmap/AdelicAlgebraicGroups
No STATUS.md (roadmap merged 2026-11-13; Tau Ceti checked at 7cbfff3ef, 2026-11-16). No Suggested.lean declaration (`Reduction.IsSArithmetic`, `Reduction.levelArithmetic`, `Neat.IsNeatLevel`, adelic points) exists in Tau Ceti.

### AA.0 Restricted products of Haar measures; Haar measures of the adeles and ideles
- Status: NOT-STARTED. Suppliers in code: `TauCeti.awayDecomposition` (Topology/Algebra/RestrictedProduct/Away/Decomposition.lean), `InfiniteAdeleRing.homeomorphMixedSpace` (NumberTheory/NumberField/Global/Adeles/Basic.lean), `restrictedProductCongr`.
- Ready now: partly. AA.0.1 (Borel structure of a restricted product) needs only Mathlib. The measure targets (AA.0.2–AA.0.4) need AnalyticNumberTheoryPartII §5.3f `exists_unique_restrictedAddHaar` (not implemented).
- Serves defs: 68, 83, 90
- Evidence: README l.633 "## Layer 0: restricted products of Haar measures", l.989 Dependencies ("AnalyticNumberTheoryPartII §5.3f for the restricted product of Haar measures").

### AA.1.1–AA.1.3 Adelic points, integral models, restricted-product comparison, Lie group structure of archimedean points, rational points and the centre
- Status: NOT-STARTED. Suppliers in code: point topology `TauCeti.PointTopology` with `isOpenEmbedding_mapValue_integer`, `isCompact_range_mapValue_integer`; Weil restriction; `TauCeti.GlobalNumberFields.adeleBaseChangeEquiv`; congruence subgroups `TauCeti.HopfAlgebra.congruenceSubgroup`.
- Ready now: yes for AA.1.1 (adelic points, integral models over `S`-integers, spreading out, reductive models outside finitely many places): it needs only Tau Ceti's points and point topology. AA.1.2 needs AA.0.3 (measure-free clauses aside) and, for "Archimedean points are a Lie group with finitely many components", RepresentationTheory/LieGroups layer 2.
- Serves defs: 67, 68, 73, 76, 83, 88, 90
- Evidence: README l.996 "## Layer 1: adelic points of algebraic groups", l.1003 "### 1.1 Affine points and integral models", l.1155 "### 1.2 Restricted-product realization", l.1211 "**Archimedean points are a Lie group with finitely many components.**", l.1258 "### 1.3 Rational points and functoriality" ("The centre on adelic points").

### AA.1.5 Unimodularity and compact open levels
- Status: NOT-STARTED.
- Ready now: no: needs AA.1.2, AA.0.1 and, for local unimodularity of reductive groups, ReductiveGroupsPartII RG2.4 (untouched).
- Serves defs: 67, 68, 76, 83, 90
- Evidence: README l.1444 "### 1.5 Unimodularity and compact open levels"; l.3420 (arithmetic lattices need "AA.1.5 (*The modular character on compact and central elements*)").

### AA.2.1 Characters, the Harish-Chandra map H_G and the split centre A_G
- Status: NOT-STARTED.
- Ready now: no: needs AA.1 and, for `A_G`, ReductiveGroups layers 4 and 7 and ReductiveGroupsPartII RG2.1 (partial).
- Serves defs: 73, 90
- Evidence: README l.1564 "### 2.1 Characters, logarithms and the split centre" (*split-centre-decomposition* `G(𝔸) = G(𝔸)^1 × A_G(ℝ)^0`).

### AA.2.2–AA.2.3 Quotient integration and rational quotients
- Status: NOT-STARTED. Suppliers in code: `MeasureTheory.Measure.exists_isFundamentalDomain_of_properlyDiscontinuousSMul` (MeasureTheory/Group/ProperlyDiscontinuous.lean), `measure_preimage_mul_right_eq_modularCharacter_mul_of_regular` (MeasureTheory/Group/ModularCharacter.lean).
- Ready now: no: needs AA.1, RG2.4 (parabolic modulus) and AnalyticNumberTheoryPartII §5.3k `exists_unique_quotientMeasure` (not implemented).
- Serves defs: 15, 31 (lattices in PU(1,n)), 68, 90
- Evidence: README l.1773 "### 2.2 Parabolic modulus and homogeneous integration", l.1885 "### 2.3 Rational quotients".

### AA.3.1 Rational parabolics, Iwasawa integration, admissible maximal compact K = ∏K_v
- Status: NOT-STARTED.
- Ready now: no: needs ReductiveGroups layer 7, ReductiveGroupsPartII RG2.1, RG2.3 (*reductive-model*, *hyperspecial-vertices*) and RG2.4 (*iwasawa-parabolic-integral*).
- Serves defs: 67, 83, 90
- Evidence: README l.2401 "### 3.1 Rational parabolics and Iwasawa integration", l.2563 "**Admissible maximal compact subgroup of `G(𝔸)`.**".

### AA.3.4 Adelic reduction, S-arithmetic subgroups, Borel–Harish-Chandra, arithmetic lattices in a real Lie group
- Status: NOT-STARTED.
- Ready now: no: needs AA.1–AA.3.3 (and through them RG2.1, RG2.3, RG2.4, LieGroups layer 9).
- Serves defs: 15, 31 (lattices in PU(1,n)), 68 (target: "Arithmetic lattices in a real Lie group" is Def. 68.3), 90
- Evidence: README l.3112 "### 3.4 Adelic reduction and arithmetic quotients", l.3184 `Reduction.IsSArithmetic`, l.3215 "**Borel–Harish-Chandra criterion for arithmetic covolume.**", l.3384 "**Arithmetic lattices in a real Lie group.**".

### AA.4.2 and AA.5.2 Strong approximation; GL₂ over ℚ, K₀(N), and the GL₂ quotients as quotients of the upper half-plane
- Status: NOT-STARTED. Suppliers in code: `TauCeti.HopfAlgebra.congruenceSubgroup`, `IsDedekindDomain.FiniteAdeleRing.integralAdeles`, `FiniteAdeleRing.denseRange_algebraMap`.
- Ready now: no: AA.4.2 needs AA.1–AA.3; AA.5.2's level definitions (*number-field-congruence-levels*) accompany AA.1.5, and its quotient statements follow AA.4.
- Serves defs: 76, 77
- Evidence: README l.4262 "### 4.2 Strong approximation and arithmetic closures", l.5410 "### 5.2 `GL₂` over `ℚ` and principal levels" ("**The `GL_2/ℚ` quotient and the upper half-plane.**").

## TauCetiRoadmap/SmoothRepresentationsOfLocalGroups
No STATUS.md (roadmap merged 2026-11-13; Tau Ceti checked at 7cbfff3ef, 2026-11-16). None of the Suggested.lean declarations (`SmoothRep`, `smoothVectors`, `IsAdmissible`, `HeckeAlgebraLevel`, `isAdmissible_of_isIrreducible`, `WeilDeligneParameter`) exists in Tau Ceti for this purpose.

### SR.0.1–SR.0.4 The smooth category over any ring: smoothness, the abelian category, invariants and averaging, admissibility, smooth characters, the centre
- Status: NOT-STARTED. Suppliers in code: the smooth discrete carrier `TauCeti.SmoothDiscreteTopRep` and `discreteRepEquivSmoothTopRep` (RepresentationTheory/Homological/ContCohomology/SmoothDiscrete/Basic.lean).
- Ready now: yes. Its suppliers are Mathlib's `Representation`, `Rep`, invariants and `CatCenter`, and Tau Ceti's discrete carrier and profinite exhaustion (ProfiniteCohomology layers 0–1, Completed/ProfiniteProPGroups layer 1).
- Serves defs: 67, 73, 83, 88, 90
- Evidence: README l.581 "## Layer SR.0: the smooth category and its basic API", l.869 "### SR.0.4 Admissibility, characters, duals, coefficients and the centre", l.1037 Dependencies.

### SR.1.1–SR.1.3 Hecke algebras over rings: C_c^∞(G), convolution, level algebras, smooth representations as Hecke modules
- Status: NOT-STARTED. Supplier in code: the double-coset Hecke ring (NumberTheory/HeckeRing/).
- Ready now: no: needs SR.0. The reductive-group statements also need ReductiveGroups layer 7 and ReductiveGroupsPartII RG2.3 and RG2.4 (untouched).
- Serves defs: 67, 83
- Evidence: README l.1042 "## Layer SR.1: Hecke algebras over rings", l.1050 "### SR.1.1 Functions, measures and convolution", l.1220 "### SR.1.2 Level algebras and the double-coset ring", l.1299 "### SR.1.3 Smooth representations as Hecke modules", l.1661 Dependencies.

### SR.3a.1 Irreducible representations are admissible; Schur's lemma; central character
- Status: NOT-STARTED.
- Ready now: no: needs SR.0, SR.1 and SR.2 (Jacquet functors, parabolic induction; not started) and ReductiveGroupsPartII RG2.0, RG2.3, RG2.4.
- Serves defs: 67, 73
- Evidence: README l.2419 "**Irreducible representations are admissible** (*admissibility-of-irreducibles*)" ("V has a central character ω_V : Z(G) → ℂ^×"), l.2556 Dependencies.

### SR.4.1–SR.4.2 The Satake transform and isomorphism; spherical parameters
- Status: NOT-STARTED. Classical `GL₂` input in code: `HeckeRing.GL2.Newform.satakeParameters` (NumberTheory/ModularForms/Newforms/Satake.lean).
- Ready now: no: needs SR.1 and SR.2, ReductiveGroupsPartII RG2.1, RG2.3 (hyperspecial `K`), RG2.4 and RG2.5 (dual group, untouched).
- Serves defs: 67, 88, 90
- Evidence: README l.3184 "## Layer SR.4: spherical representations and Satake", l.3193 *satake-transform*, l.3252 *satake-isomorphism*, l.3317 *spherical-parameter*, l.3701 Dependencies.

### SR.5.2 (WD parameters) *wd-raw-parameters*, *nilpotent-exp-log*, *wd-parameter-operations*, *wd-algebraic-composition*
- Status: PARTIAL for *nilpotent-exp-log*: `IsNilpotent.log` with `log_eq_sum` (independence of the vanishing bound), `isNilpotent_log`, `map_log`, `log_exp`, `exp_log`, `expEquiv` (RingTheory/Nilpotent/Log.lean), matrix one-parameter subgroups `exp(tX)` (`nilpotentOneParameterCoordinateMap`, Algebra/AlgebraicGroup/GeneralLinear/Unipotent/OneParameter.lean); the unique unipotent `m`-th root and the continuous `ℤ_ℓ`-homomorphism clause are missing. NOT-STARTED for the other three (no `WeilDeligneParameter`).
- Ready now: yes. *wd-raw-parameters* needs Mathlib and ClassFieldTheory layer 9 (done); *wd-parameter-operations* adds RepresentationTheory/InductionRestriction layers 0 and 2; *wd-algebraic-composition* adds ReductiveGroups Layers 2 and 4 (done) and 5P (partial, its matrix exponential and logarithm are in code). None needs the earlier SR layers.
- Serves defs: 86 (target: *wd-algebraic-composition* is Def. 86.1–86.3)
- Evidence: README l.4475 "#### WD raw parameters", l.4513 "#### Nilpotent exp-log", l.4561 "#### WD parameter operations", *wd-algebraic-composition* l.4590 ("**Composition with an algebraic representation and symmetric powers**"); ArithmeticGaloisRepresentations §2.4 (arithmetic Weil–Deligne adapter) consumes it.

## TauCetiRoadmap/AutomorphicFormsOnReductiveGroups
No STATUS.md (merged as roadmap PR #1037; Tau Ceti checked at 7cbfff3ef, 2026-11-16). None of `LieTestFunction`, `AdelicSchwartzFunction`, `RestrictedTensor`, `WeilGroupReal`, `HasInfinitesimalCharacter`, `IsGFinite`/`gFiniteSubmodule` exists in Tau Ceti.

### §§0.1a–0.3 Lie test functions, adelic test functions and the adelic Schwartz algebra
- Status: NOT-STARTED.
- Ready now: yes for §0.1a (`LieTestFunction`, convolution, `smoothApproximateIdentity`): it needs Mathlib `ContMDiffMap`, `TestFunction` and LieGroups Layer 0 (done). §§0.2–0.3 need AdelicAlgebraicGroups Layers 0–3, ArithmeticLocallySymmetricSpaces ALS.F.1, ALS.F.6 and SmoothRepresentationsOfLocalGroups SR.0–SR.1 (not started), and LieGroups Layer 9 `KAK` (partial) for `integrable_height_rpow_neg`.
- Serves defs: 83 (target: `AdelicSchwartzFunction`, §0.3), 90
- Evidence: README l.87 "## Layer 0: Smooth adelic functions, growth and convolution", l.114 "### 0.1a Test functions on the archimedean group", l.127 "### 0.2 Test functions and their topology", l.143 "### 0.3 Schwartz functions on the group", l.228 Dependencies.

### §§2.1–2.4, 2.6–2.7 Harish-Chandra modules, infinitesimal characters, real induction, discrete series, explicit GL₂ modules, smooth vectors and globalization
- Status: NOT-STARTED. Inputs in code: `TauCeti.harishChandraIso`, `centralCharacterModules`, `TauCeti.centerToEnd`, `TauCeti.envelopingAction`, `lieExp`.
- Ready now: yes for the smooth vectors of §2.7 (`IsLieSmoothVector`, `lieSmoothVectors` of a Banach `ContRepresentation`), which use `lieExp` and Mathlib `ContMDiff`. §2.1 needs CompactGroups Layer 5's `IsGFinite`, `gFiniteSubmodule_dense` (recorded as `gap:banach-gfinite-density`, not in code); §2.2 needs LieHighestWeight §9.2 (ready, not started); §§2.3–2.4 need ArithmeticLocallySymmetricSpaces ALS.F.1 and ALS.0.1–ALS.0.3 (not started) and LieGroups Layers 7 and 9 (partial).
- Serves defs: 5 (target: §2.2 `HasInfinitesimalCharacter`), 7 (target: `IsSquareIntegrable` §2.4, `D_k(μ)` §2.6), 67, 73, 76 (§2.6), 83 (§2.7 smooth vectors), 88 (§2.2)
- Evidence: README l.299 "## Layer 2: real reductive representations and globalizations", l.301 "### 2.1 Compact-finite vectors and admissibility", l.345 "### 2.2 Infinitesimal characters and Harish-Chandra finiteness" (*Needs* l.351), l.390 §2.3, l.416 §2.4, l.462 "### 2.6 Explicit GL₂ modules and the generic unitary dual", l.487 "### 2.7 Smooth Fréchet representations and globalization", l.520 Dependencies.

### §2.3a Minimal parabolic subgroups and the Langlands decomposition
- Status: NOT-STARTED (only the `GL_n` Iwasawa decomposition `TauCeti.iwasawaDiffeomorph`, Geometry/Lie/Iwasawa.lean, and dynamic parabolics for the algebraic comparison).
- Ready now: no: needs LieGroups Layer 9 (partial), ArithmeticLocallySymmetricSpaces ALS.F.1 and ALS.0.1–ALS.0.3 (not started), and ReductiveGroups Layer 7 (partial) for the algebraic comparison.
- Serves defs: 79 (target), 4 (minimal parabolics), 1 (maximal `ℝ`-split torus for RealSemisimpleLieGroups §2.4)
- Evidence: README l.372 "### 2.3a Minimal parabolic subgroups and the Langlands decomposition", *Needs* l.380.

### §2.5 Weil groups and archimedean parameters
- Status: NOT-STARTED.
- Ready now: yes for the first paragraph (`WeilGroupComplex`, `WeilGroupReal`, `norm`, `induceCharacter`, `irreducibleClassification`, symmetric powers of semisimple continuous Weil representations): Mathlib only. `recGL` needs §§2.3–2.4.
- Serves defs: 86 (target: 86.4), 5 (Remark 2)
- Evidence: README l.446 "### 2.5 Weil groups and archimedean parameters" ("For every `m≥0`, the `m`-th symmetric power `w↦Sym^m(r(w))` ... is again a semisimple continuous representation").

### §§3.1–3.5 Adelic automorphic modules, central characters, restricted tensor products and Flath factorization
- Status: NOT-STARTED.
- Ready now: yes for the algebraic part of §3.4 (`RestrictedTensor`, `ofFinite`, `tprod`, `finiteCornerFactorization`): Mathlib finite tensor products, filtered colimits and finite-dimensional density only. The rest needs ArithmeticLocallySymmetricSpaces ALS.F.6, Layers 0–2, AdelicAlgebraicGroups §§1.1, 3.1, 3.4, SmoothRepresentationsOfLocalGroups SR.0, SR.1, SR.4.1 and ReductiveGroupsPartII RG2.3 (none started).
- Serves defs: 67 (target: §§3.4–3.5), 72 (`twist`, §3.2), 73 (target: `centralCharacter`, §3.2), 76, 88, 90
- Evidence: README l.524 "## Layer 3: adelic modules and their local factors", l.543 "### 3.2 The global algebra and automorphic representations", l.581 "### 3.4 Restricted tensor products and finite corners", l.598 "### 3.5 Spherical lines and Flath factorization", l.620 Dependencies.

### §§4.1–4.2 Constant terms, cuspidal globalization and discrete occurrences
- Status: NOT-STARTED.
- Ready now: no: needs Layers 0–3, ArithmeticLocallySymmetricSpaces ALS.F.6, AdelicAlgebraicGroups §§2.2, 3.4, 4.2 and ReductiveGroupsPartII RG2.4.
- Serves defs: 72, 90
- Evidence: README l.624 "## Layer 4: constant terms, cuspidal realizations and Fourier tests", l.644 "### 4.2 Cuspidal globalization and actual discrete occurrences" (`DiscreteOccurrence(G,ω)`), l.731 Dependencies.

### §§7.2–7.3 The GL₂ adelization, adelic lifts, Hecke and diamond normalization
- Status: NOT-STARTED. Classical inputs in code: `HeckeRing.GL2.Newform`, `EigenformAwayFromLevel.conductor`, `primitiveAssociate` (NumberTheory/ModularForms/Newforms/Conductor.lean), `HeckeCharacter.finiteConductor`.
- Ready now: no: needs Layers 0–6 as listed in its Dependencies, in particular §§3.1–3.2, §2.6 and AdelicAlgebraicGroups AA.4.2, AA.5.2 (strong approximation, `K₀(N)`).
- Serves defs: 76 (target: `adelize` and the newform's cuspidal occurrence)
- Evidence: README l.1148 "### 7.2 The GL₂ adelization and its inverse", l.1174 §7.2a, l.1187 "### 7.3 Hecke and diamond normalization for GL₂", l.1305 Dependencies.

## TauCetiRoadmap/ArithmeticLocallySymmetricSpaces
No STATUS.md (merged as roadmap PR #871; Tau Ceti checked at 7cbfff3ef, 2026-11-16). Grep `IsCartanInvolution`, `LocallySymmetric.AutomorphicForm` in Tau Ceti: no hits; the matrix polar and Cartan decompositions `Subgroup.cartanHomeomorph` exist.

### ALS.F.1, ALS.0.1–ALS.0.4 Real points and maximal compact subgroups, Cartan involutions of real reductive groups, the Cartan datum, the symmetric space X^G
- Status: NOT-STARTED.
- Ready now: no: ALS.F.1 and ALS.0.1 need LieGroups Layer 9 (partial); ALS.0.1–ALS.0.2 also AdelicAlgebraicGroups AA.3.7; ALS.0.4 needs ALS.0.1, ALS.0.3 and AdelicAlgebraicGroups §2.1 (`A_G`, not started).
- Serves defs: 1, 79 (ALS.0.1 conjugacy of Cartan involutions), 4, 7 (through AutomorphicFormsOnReductiveGroups §§2.3a–2.4), 62 (ALS.0.4)
- Evidence: README l.579 "### ALS.F.1 Real points of linear algebraic groups and their maximal compact subgroups", l.1167 "### ALS.0.1 Cartan involutions of real reductive groups", l.1246 "### ALS.0.2 Real points and the Lie-theoretic Cartan datum", l.1287 "### ALS.0.3 Maximal compact subgroups from Cartan involutions", l.1309 "### ALS.0.4 The symmetric space of G with the split-centre correction".

### ALS.F.6 Automorphic forms, constant terms and cusp forms
- Status: NOT-STARTED (no `LocallySymmetric.AutomorphicForm`).
- Ready now: no: needs ALS.F.1, AdelicAlgebraicGroups §§1.3, 2.1, 3.4, 3.6 and SmoothRepresentationsOfLocalGroups SR.0 (not started); LieHighestWeight Layer 7 is done.
- Serves defs: 67, 72, 73, 76, 88, 90
- Evidence: README l.995 "### ALS.F.6 Automorphic forms, constant terms and cusp forms" (`cuspidalSpectrum_discrete`, `cuspidalRepresentation`).

### ALS.0.6, ALS.1, ALS.3 Arithmetic locally symmetric spaces X_K, Betti complexes and finite-level Hecke actions
- Status: NOT-STARTED.
- Ready now: no: ALS.0.6 needs ALS.0.4 and AdelicAlgebraicGroups §§3.4, 4.4; ALS.1.1 needs ALS.0.6, ALS.0.9 and ALS.F.4; ALS.3.1 needs SmoothRepresentationsOfLocalGroups SR.1.1–SR.1.2 (not started).
- Serves defs: 77 (the finite-level spaces `X_K` with Betti cohomology and Hecke actions)
- Evidence: README l.1399 "### ALS.0.6 The arithmetic locally symmetric space `X_K`" (*Needs* "ALS.0.4; AdelicAlgebraicGroups §4.4 ... §3.4"), l.1754 "## Layer ALS.1: Arithmetic coefficients and Betti complexes", l.2680 "## Layer ALS.3: Finite-level Hecke actions and correspondences".

## TauCetiRoadmap/RepresentationTheory/LieGroups
STATUS.md snapshot: a6027b1 2026-11-11 (umbrella RepresentationTheory/STATUS.md; Tau Ceti checked at 7cbfff3ef, 2026-11-16)

### Layer 7 (first bullet) Compact real form of a complex semisimple Lie algebra; Cartan involution θ of a real semisimple 𝔤₀
- Status: PARTIAL. Exists: the conjugate-linear involution τ of the Serre-presented algebra, `TauCeti.serreCompactInvolution` (τHᵢ = −Hᵢ, τEᵢ = −Fᵢ, τFᵢ = −Eᵢ, `serreCompactInvolution_lie`, `serreCompactInvolution_involutive`, uniqueness `eq_serreCompactInvolution`, agreement with `serreChevalleyInvolution` for a trivial star; Algebra/Lie/Presentation/Serre/CompactInvolution.lean), on the conjugate Lie algebra `TauCeti.ConjLieAlgebra` (Algebra/Lie/Conjugate.lean). Other ingredients: `serreLiftEquiv` (Serre/Injective.lean), `serreChevalleyInvolution` (Serre/Automorphism.lean), Chevalley involution and structure-constant normalization (Algebra/Lie/Weights/Chevalley/Involution.lean, Algebra/Lie/Weights/StructureConstant/Normalization.lean). Missing: the Hermitian form H_τ(x, y) = −B(x, τy) and its positivity, the compact real form 𝔲 = Fix τ, real-form descent, and θ = στ|𝔤₀ (grep `compactRealForm|CartanInvolution` empty).
- Ready now: yes. This is a purely Lie-algebraic bullet. Its inputs (LieHighestWeight Layer 7 Serre presentation and Layer 0 sl₂ strings, and τ) are in place. H_τ positivity, real-form descent and θ = στ|𝔤₀ can all be built now. The later group-level Layer 7 bullets (universal complexification, compact integration) are not ready: they need Layer 4 integration (partial) and Layer 5 covers.
- Serves defs: 1, 4, 7, 15, 31, 54, 62, 79
- Evidence: README l.787 "### Layer 7: complexification and real forms", first bullet l.788 "**Compact real forms of semisimple Lie algebras.**", θ at l.802-806 ("Layer 9 consumes this θ"); STATUS "Layer 7 holding only realification"; Tau Ceti PR #37665 (CompactInvolution.lean). Consumers: RealSemisimpleLieGroups Layers 0 and 2 (existence of Cartan involutions, real forms §2.5) and AutomorphicFormsOnReductiveGroups §§2.3–2.4.

### Layer 9 Cartan, Iwasawa, KAK decompositions (CartanInvolution, IsRealReductive, cartan_polar_decomposition, IwasawaData, restricted roots, kakDecomposition)
- Status: PARTIAL. Only matrix cases exist: Iwasawa `iwasawaDiffeomorph` (Geometry/Lie/Iwasawa.lean, LinearAlgebra/Matrix/GeneralLinearGroup/Iwasawa.lean), KAK for GL_n(ℝ/ℂ) (LinearAlgebra/Matrix/GeneralLinearGroup/Cartan.lean), maximal compact (…/MaximalCompact.lean), symplectic polar and Cartan involution (Analysis/Matrix/Polar/Symplectic.lean, Geometry/Lie/Symplectic/Cartan.lean), unitary upper-triangular with positive diagonal = 1 (Analysis/Matrix/Triangular.lean); the Cartan decomposition `Subgroup.cartanHomeomorph` of a star-stable subgroup of the units of a C*-algebra (Analysis/SpecialFunctions/ContinuousFunctionalCalculus/Cartan.lean), instantiated for `SL n`, `Sp(2n, ℝ)` and the realified `GL(n, ℂ)` (Analysis/Matrix/Cartan.lean, Analysis/Matrix/Cartan/Realify.lean); the positive upper-triangular group as a Lie group with global exponential coordinates and its real-diagonal triangular Lie algebra (`TauCeti.Lie.posUpperTriangularLieGroup`, `posUpperTriangularLog`, Geometry/Lie/Subgroup/PosUpperTriangular/{Basic,Exponential}.lean; `upperTriangularRealDiagonalLieSubalgebra`, Algebra/Lie/GeneralLinear/RealTriangular.lean). None of the Suggested.lean names exist: `FiniteCartanMatrixModel`, `CartanInvolution`, `IsRealReductive`, `IwasawaData`, `IsIwasawaTriple`, `iwasawaDecomposition`, `kakDecomposition`, `cartan_polar_decomposition`, `restrictedRoots`, `Nplus`, `triangularRealDiagonal`, `positiveTriangular`, `bijOn_exp_triangular`, `lieExp_bijective_of_immersed_positiveTriangular`.
- Ready now: partly. Ready: the global matrix-cover model with `cartan_polar_decomposition` for a closed transpose-stable H ≤ GL_N (it consumes the matrix polar decomposition and `Subgroup.cartanHomeomorph`), and the "Connected subgroups of the positive triangular group" bullet, whose carrier and exponential coordinates are in code. Not ready: the semisimple finite-center specialization, restricted roots/KAK and the general Iwasawa theorem. These need Layer 7's θ (partial: τ only) and Layer 6 tori (partial).
- Serves defs: 1, 4, 7, 15, 31, 54, 62, 79, 83
- Evidence: README l.1199 "### Layer 9: the Cartan, Iwasawa, and KAK decompositions", l.1230 `cartan_polar_decomposition`/`CartanInvolution`/`IsRealReductive`, l.1354 "**Restricted roots and KAK.**"; STATUS "remaining: the global real-reductive Cartan, Iwasawa and KAK decompositions beyond GL n"; Suggested.lean l.459-652. Consumers: RealSemisimpleLieGroups Layers 2–5 (§5.7 for 15, 31), AutomorphicFormsOnReductiveGroups §§2.3a–2.4 and ArithmeticLocallySymmetricSpaces ALS.F.1, ALS.0.1.

### Layer 5 enveloping-algebra bullet U(𝔤) as left-invariant differential operators; central characters
- Status: PARTIAL. Done: `TauCeti.envelopingAction` and `range_envelopingAction` (Geometry/Lie/EnvelopingAlgebra/Basic.lean); `envelopingAction_injective` and `envelopingAlgEquivAdjoin` (Geometry/Lie/EnvelopingAlgebra/Faithful.lean); the central action `TauCeti.centerToEnd : Z(A) →ₐ[k] End_A(M)` for any module over any algebra (RingTheory/Semisimple/CentralCharacter.lean), so `Z(U_ℝ(𝔤)) → End_{U(𝔤)}(V)`; the scalar central character of a finite-dimensional irreducible Lie module over an algebraically closed field, `TauCeti.UniversalEnvelopingAlgebra.centralCharacter` with `representation_eq_centralCharacter_smul`, `centerEigenspace_centralCharacter`, `centralCharacter_congr` (Algebra/Lie/UniversalEnveloping/CentralCharacter.lean, Tau Ceti PR #37752), whose docstring records the real circle rotation module example. Missing: the scalar central character of real absolutely irreducible modules, and the division-commutant statement for irreducible real modules. The highest-weight version exists in LieHighestWeight (`vermaCentralCharacter`).
- Ready now: yes. Layer 5's other bullets (covers, centres) are listed separately; this bullet needs only LieHighestWeight Layer 3 PBW, which is done.
- Serves defs: 1, 5, 83
- Evidence: README l.518 "### Layer 5: simply-connected covers and the enveloping algebra", bullet l.626 "**The universal enveloping algebra.**"; STATUS Layer 5 "partial" (no remaining text); grep envelopingAction hits the 2 files above.

### Layer 8 Borel-Weil, complex flag manifolds, Bruhat (minimal parabolics P_α)
- Status: NOT-STARTED
- Ready now: no: needs the Layer 7 algebraization of compact complexifications and ReductiveGroups Layer 7 generic Bruhat (partial).
- Serves defs: 4 (weak link)
- Evidence: README l.1078 "### Layer 8: Borel-Weil, flag manifolds, and Bruhat"; the minimal parabolics are complex algebraic P_α ⊂ G_ℂ (l.1155 "minimal-parabolic map pα:G/B+→G/Pα+"), not real parabolics; STATUS Layer 8 "untouched".

## TauCetiRoadmap/RepresentationTheory/LieHighestWeight
STATUS.md snapshot: a6027b1 2026-11-11 (umbrella RepresentationTheory/STATUS.md; Tau Ceti checked at 7cbfff3ef, 2026-11-16; README at roadmap c6ef576)

### §9.2 Reductive enveloping centers and the reductive Harish-Chandra isomorphism
- Status: NOT-STARTED. No `productEnveloping`, `productCenterEquiv` or reductive HC isomorphism (grep empty). The inputs exist: `TauCeti.UniversalEnvelopingAlgebra.mapEquiv` (Algebra/Lie/UniversalEnveloping/Functoriality.lean), `prodEquivTensor` (UniversalEnveloping/Prod.lean), `symmetricAlgebraEquiv` (UniversalEnveloping/Abelian.lean), `pbwSymmetrization_mem_center_iff` (UniversalEnveloping/PBW/Symmetrization/Basic.lean), the semisimple `TauCeti.harishChandraIso`/`harishChandraLinearIso` (Algebra/Lie/HighestWeight/CentralCharacter/Isomorphism.lean), `LieSubalgebra.lieChevalleyRestrictionIso` (HighestWeight/ChevalleyRestriction.lean), and the reductive structure with `centralWeight` (Algebra/Lie/Reductive/Basic.lean, Algebra/Lie/Weights/Central.lean).
- Ready now: yes. The README builds `U(L) ≃ Sym(z(L)) ⊗ U([L,L])` from universal properties, then `Z(U(L)) ≃ Sym(z(L)) ⊗ Z(U([L,L]))`, then the reductive HC isomorphisms by tensoring the derived algebra's `harishChandraIso` with the identity; all of these are in code.
- Serves defs: 5, 7, 88 (AutomorphicFormsOnReductiveGroups §2.2 consumes it)
- Evidence: README l.2695 "## Layer 9: reductive Lie algebras and `gl_n`", l.2819 "### 9.2 Reductive enveloping centers and the actual invariant maps" ("Tensor the derived algebra's native **raw** HC isomorphism `TauCeti.harishChandraIso` with the identity on `Sym(z(L))`"); this is the gap merged AutomorphicFormsOnReductiveGroups records as `gap:reductive-enveloping-centers`.

## TauCetiRoadmap/RealSemisimpleLieGroups
No STATUS.md (merged as roadmap PR #2229; Tau Ceti checked at 7cbfff3ef, 2026-11-16). Grep `IsCartanInvolution|restrictedRoot|realRank|IsRiemannianSymmetricSpace` in Tau Ceti: no hits.

### Layers 0–1 Cartan involutions of real semisimple and reductive Lie algebras; restricted roots and real rank (§§0.1–0.4, 1.1–1.4)
- Status: NOT-STARTED. Only special cases: `LieAlgebra.Symplectic.cartanInvolution` (Algebra/Lie/Symplectic/Cartan.lean), `TauCeti.serreCompactInvolution` (Algebra/Lie/Presentation/Serre/CompactInvolution.lean).
- Ready now: yes for §0.1, §0.3, §0.4 and the direct route of §1.1, with existence of Cartan involutions taken as a hypothesis (README "Ordering"); §0.2 and §1.3 need LieGroups Layers 2, 4 and 9 (`Int(𝔤₀)`, `Ad(K)𝔞 = 𝔭`; Layer 9 partial).
- Serves defs: 1 (target: §1.3 `realRank`), 4, 54, 62, 79
- Evidence: README l.327 "## Layer 0: Cartan involutions of real semisimple and reductive Lie algebras", l.448 "## Layer 1: restricted roots and real rank", l.511 "### 1.3 Conjugacy of maximal abelian subspaces and the real rank"; l.1349 "## Ordering".

### Layer 2 Real rank of groups, global Cartan involution, restricted Weyl group, split tori, real forms (§§2.1–2.5)
- Status: NOT-STARTED.
- Ready now: no: needs Layer 1 and LieGroups Layers 4, 5A, 7 and 9 (§2.4 also AutomorphicFormsOnReductiveGroups §2.3a and ReductiveGroups Layers 4, 6).
- Serves defs: 1 (target: §2.1 `groupRealRank`, §2.4 Borel–Tits rank), 4, 54 (§2.5 is Definition 54.1), 62 (§2.2), 79 (§2.4)
- Evidence: README l.585 "## Layer 2: real rank, restricted Weyl group, hyperbolic elements and real forms", l.587 §2.1, l.621 §2.2, l.674 §2.4, l.734 "### 2.5 Real forms of complex reductive groups"; *Needs* l.619, l.638, l.731, l.788.

### Layers 3–4 Minimal parabolics, Bruhat decomposition, standard and general parabolic subgroups (§§3.1–4.5)
- Status: NOT-STARTED. Inputs in code: Tits systems and standard parabolics (GroupTheory/TitsSystem/), algebraic `IsParabolic` and `Cocharacter.parabolic`.
- Ready now: no: needs Layer 2, AutomorphicFormsOnReductiveGroups §2.3a and LieGroups Layer 9.
- Serves defs: 4 (target: §3.1, §§4.1–4.5), 79 (§3.1 for non-linear groups with finite centre)
- Evidence: README l.802 "## Layer 3: minimal parabolic subgroups and the Bruhat decomposition", l.910 "## Layer 4: parabolic subgroups and Langlands decompositions"; *Needs* l.838, l.897, l.956, l.1029, l.1063.

### Layer 5 (§§5.1–5.6) Riemannian symmetric spaces: G/K, Killing metric, maximal compacts, flats, quotients
- Status: NOT-STARTED. Inputs in code: `TauCeti.RiemannianIsometry`, `CovariantDerivative.HasParallelCurvature` (Geometry/Manifold/Riemannian/Isometry/LocallySymmetric.lean), the free proper quotient theorem (Geometry/Manifold/GroupAction/Quotient.lean), O'Neill's curvature formula (Geometry/Manifold/Riemannian/Submersion/Curvature.lean).
- Ready now: yes for §5.1 (`IsRiemannianSymmetricSpace`; needs Tau Ceti isometries and parallel curvature, HopfRinow, RiemannianGeometry R1.2); no for §§5.2–5.6: they need Layer 2 (§2.2), LieGroups Layer 9, SmoothBundlesConnections B1.4's `G/H`, RiemannianGeometry R1.3 and R4 item 4.
- Serves defs: 62 (target), 15, 31 (§5.7 builds on §§5.2, 5.3, 5.5)
- Evidence: README l.1076 "## Layer 5: Riemannian symmetric spaces", l.1078 §5.1, l.1104 §5.2, l.1133 §5.3, l.1168 §5.4, l.1219 §5.5, l.1253 §5.6; *Needs* l.1101, l.1131, l.1166, l.1216, l.1282.

### §5.7 Complex hyperbolic space (U(1,n), PU(1,n), the ball, ω_X, complex totally geodesic submanifolds)
- Status: NOT-STARTED (no `PU(1,n)` or ball in Tau Ceti; only the `n = 1` Fuchsian theory).
- Ready now: no: needs §0.4, §§5.2, 5.3, 5.5, LieGroups Layer 9 and ComplexKahlerGeometry Kähler forms.
- Serves defs: 15, 31 (Setting 31.1, Proposition 31.3)
- Evidence: README l.1285 "### 5.7 Complex hyperbolic space"; *Needs* l.1337.

## TauCetiRoadmap/JacobianChallenge
STATUS.md snapshot: 794f43e 2026-11-16, generated against Tau Ceti aa6e43e (Tau Ceti checked at 7cbfff3ef, 2026-11-16; README at roadmap c6ef576)

### Layer C §§C.1–C.2 relative coherent cohomology and base change, §C.4 Hilbᵈ = Symᵈ X
- Status: PARTIAL. §C.1: higher direct images local on the target `Scheme.Hom.higherDirectImageRestrictIso`, quasi-coherent for qcqs `f` `Scheme.Hom.isQuasicoherent_higherDirectImage` (Cohomology/HigherDirectImage/Quasicoherent.lean), vanishing along affine morphisms `isZero_higherDirectImage_succ_of_isAffineHom` and finite presentation along finite morphisms `isFinitePresentation_higherDirectImage_of_isFinite` (HigherDirectImage/Affine.lean); Hartshorne II.5.14 `exists_map_eq_tmulRight_tensorPowSection` (LineBundle/TwistedSections.lean). §C.2: flat base change over an affine base `bijective_cohomologyBaseChange` (Cohomology/FlatBaseChange.lean), Mumford's finite projective model `CochainComplex.exists_quasiIso_finite_projective` (Algebra/Homology/ModuleCat/BaseChange.lean) and `LinearMap.upperSemicontinuous_finrank_fiber_homology` (RingTheory/Spectrum/Prime/Semicontinuity.lean). §C.4: the functor `relativeEffectiveCartierDegreeSubfunctor` (EffectiveCartierDivisor/Degree/Basic.lean), representable for `d ≤ 1` (`graphDivisorDegreeOne`, EffectiveCartierDivisor/Representable.lean). Missing: coherence of `R^q f_*` for proper `f`, flat base change over a non-affine base, semicontinuity and cohomology and base change for proper flat `f`, Grauert, `Hilbᵈ` for `d ≥ 2`.
- Ready now: yes for §C.1 in the projective case (global generation of high twists from II.5.14); the proper case needs SchemeAndStackFoundations §4.12 Chow's lemma (partial: graph closure only). §C.2 follows §C.1. §C.4 needs only A.2 and C.2, no Hilbert or Quot scheme.
- Serves defs: 30 (§C.4, and through Layer D); 19, 71, 80, 84, 85 (through SchemeAndStackFoundations §4.14 and Layer D)
- Evidence: README l.673 "## Layer C: relative coherent cohomology and base change"; l.677 "### C.1 Coherent higher direct images under proper morphisms" (*Needs:* B.1; SchemeAndStackFoundations §4.12); l.714 "### C.2 Flat base change, semicontinuity, cohomology and base change"; l.785 "### C.4 The Hilbert scheme of points of a curve" (`isRepresentable_relativeEffectiveCartierDegreeSubfunctor`, "the construction needs no Quot scheme", *Needs:* A.2, C.2); Dependencies l.829 "SchemeAndStackFoundations §4.9, §4.12 (not §4.14, which consumes this layer)". STATUS Layer C remaining "coherence of R^q f_* for proper f, flat base change over a non-affine base, semicontinuity, cohomology and base change, Grauert, Hilb^d"; frontier "Coherence of higher direct images (C.1, hence B.1). Use II.5.14 ...".

### Layer D §§D.2–D.5, D.8 Picard scheme, Pic^0, Jacobian
- Status: PARTIAL: the fppf Picard sheaf `relativePicardFppfSheaf` (PicardFunctor/Fppf.lean) with base change `relativePicardPresheafBaseChangeIso`, the rigidified functor `rigidifiedPicardFunctor`, `relativePicardFiberDegree`, `Pic⁰_{X/S}` as `relativePicardDegreeZeroFppfSheaf` (PicardFunctor/PicZero/), Abel maps on functors `abelJacobiMapOfDegree`, `abelJacobiMapToPicZeroFppf` (PicardFunctor/Abel/), point separation `abelJacobiMap_app_injective_of_genus_pos`. Missing: the named `HasPicardScheme`/`picardScheme` (§D.2), Hilbert quotients (§D.3), projective Picard representability (§D.4), representability of `Pic⁰` and the Abel morphisms `AJ_d` (§D.5), smoothness and properness (§§D.6–D.7), `jacobianScheme` (§D.8).
- Ready now: yes for §D.2 (needs only D.1, in code, and Mathlib representability API). No for §§D.3–D.8: §D.3 needs C.2 and SchemeAndStackFoundations §§1.1, 4.14 (not started); §D.4 needs C.1–C.3, D.3 and SSF §§0.9, 4.9, 4.14.
- Serves defs: 19, 30, 71, 80, 84, 85
- Evidence: README l.834 "## Layer D: the relative Picard functor and the Jacobian scheme"; l.862 "### D.2 The Picard scheme as a named representing object" (*Needs:* D.1); l.903 "### D.3 Hilbert quotients for Picard charts" (*Needs:* C.2; SchemeAndStackFoundations §1.1, §4.14); l.922 "### D.4 Projective Picard representability"; l.974 "### D.5 The degree-zero piece and the Abel maps of the curve"; l.1064 "### D.8 The Jacobian over any field" (`jacobianScheme X := (picZeroSets X).reprX`); Dependencies l.1144. STATUS Layer D remaining "named Picard scheme, Hilbert quotients, representability, smoothness and properness of Pic0, the Jacobian over any field". `HasPicardScheme`, `picardScheme`, `jacobianScheme` absent from Tau Ceti.

### Layer E §§E.1–E.5 cube and square, projectivity, dual, polarizations and theta W_{g−1}
- Status: PARTIAL: the `AbelianVariety` carrier, rigidity (`existsUnique_snd_comp_eq_of_flat`, Rigidity/Relative.lean; pointed morphisms of proper flat group schemes are homomorphisms, Rigidity/GroupScheme.lean), the tangent space, dimension zero, elliptic curves. No theorem of the cube or square, projectivity, dual abelian variety, polarization, `W_{g−1}` or theta (grep `cube|thetaDivisor` in AlgebraicGeometry empty).
- Ready now: no. §E.1 (cube over a field) needs C.2 (remaining); §E.3 (dual) needs D.4; §E.5 (theta) needs D.5, D.8, E.1, E.3, E.4.
- Serves defs: 30, 80
- Evidence: README l.1148 "## Layer E: abelian varieties"; l.1150 "### E.1 Cube and square" (*Needs:* A.1, C.2); l.1183 "### E.2 Abelian varieties and projectivity"; l.1203 "### E.3 The higher-dimensional Picard functor and dual" (*Needs:* D.1, D.4, E.1, E.2); l.1240 "### E.5 Polarizations and theta" ("construct the Cartier divisor `W_{g−1} ⊂ Pic^{g−1}` of effective classes", *Needs:* D.5, D.8, E.1, E.3, E.4). STATUS Layer E: "It lacks every milestone: cube, projectivity, dual, polarizations, autoduality, and `[n]` for `n ≠ 0`."

### Layer F §F.1 Abel–Jacobi and the Albanese property
- Status: PARTIAL: Abel–Jacobi on functors of points (PicardFunctor/Abel/{Jacobi,Fppf,PicZero,Degree}.lean, `abelJacobiMapToPicZeroFppf`), point separation, the `AbelianVariety.IsAlbanese` carrier (AbelianVariety/Albanese.lean). No `abelJacobi` morphism of schemes, `isAlbanese_abelJacobi`, closed immersion or base change.
- Ready now: no: needs D.5, D.8, E.4, E.6
- Serves defs: 30
- Evidence: README l.1329 "## Layer F: Abel–Jacobi and the universal property"; l.1331 "### F.1 Abel–Jacobi and the Albanese property" (*Needs:* D.5, D.8, E.4, E.6); STATUS Layer F "lacks the morphism, the universal property, the closed immersion and base change".

## TauCetiRoadmap/AbelianSchemesAndArithmeticModuli
No STATUS.md (merged; Tau Ceti checked at 7cbfff3ef, 2026-11-16). No `AbelianScheme`, `AbelianLattice`, `AbelianNS` in Tau Ceti; only the field carrier `TauCeti.AlgebraicGeometry.AbelianVariety` with `TangentSpace`.

### §A0.1 `AbelianScheme S`, §A1.3 invariant differentials, §A2.2 dual, §A4.3 `H¹_dR`
- Status: NOT-STARTED.
- Ready now: yes for §A0.1 (needs only Mathlib `GrpObj`, `IsProper`, `Smooth`, `GeometricallyConnected`, `Over.pullback` and Tau Ceti `AbelianVariety`). §A1.3 needs A0.3 and SchemeAndStackFoundations §3.8; §A2.2 needs A2.1 (Raynaud) and JacobianChallenge Layer E; §A4.3 needs A1.3, A2.2, A4.2.
- Serves defs: 70, 74, 78, 85
- Evidence: README l.600 "### A0.1 Abelian schemes" (*Needs* l.658), l.789 "### A1.3 Invariant differentials", l.1093 "### A2.2 The dual abelian scheme and the Poincaré bundle", l.1916 "### A4.3 First de Rham cohomology".

### §A1.5 relative cube and multiplication pullbacks; §A2.10 Néron–Severi group
- Status: NOT-STARTED (no cube theorem or `AbelianNS` in Tau Ceti).
- Ready now: no: §A1.5 needs A0.3, A1.2, A1.4 and JacobianChallenge §E.1; §A2.10 needs A2.3, AlgebraicModuliForArithmeticGeometry Layer 7 and JacobianChallenge Layer E.
- Serves defs: 80 (§A1.5: `[n]^*L` for symmetric and antisymmetric `L`), 78 (§A2.10, for the paper)
- Evidence: README l.898 "### A1.5 The theorem of the cube and multiplication pullbacks"; l.1343 "### A2.10 The Néron–Severi group".

### §§A3.3, A6.3, A6.5 Quotients by finite locally free subgroups, images of homomorphisms, Poincaré complete reducibility
- Status: NOT-STARTED.
- Ready now: no: §A3.3 needs A2.1, A3.1 and SchemeAndStackFoundations §§1.5–1.6 (quotient sheaves, §1.5 partial) and §1.17; §A6.3 needs A3.1 and JacobianChallenge Layer E; §A6.5 needs A2.3, A2.5, A2.8, A3.4, A6.3, A6.4.
- Serves defs: 71 (abelian subvarieties, images and quotients `B/C`)
- Evidence: README l.1481 "### A3.3 Quotients by finite locally free subgroups" (*Needs* "A2.1, A3.1; ModularCurves 0E; SchemeAndStackFoundations Layer 1 §§1.5–1.6 (quotient sheaves), §1.17"), l.2868 "### A6.3 Images of homomorphisms over the original field", l.2921 "### A6.5 Poincaré complete reducibility".

### §§A5.1–A5.7 Lattice uniformization, Riemann forms, the polarized Hodge equivalence, analytic families, degree-one realizations
- Status: NOT-STARTED. Tau Ceti inputs in code: `lieExp`, `isLocalDiffeomorphAt_lieExp_zero`, `IsRiemannForm`, `latticeHodgeStructure`, `latticeHodgeStructureEquiv`, `isRiemannForm_iff_isPolarization`, `HodgeStructureOn.dual`, ComplexTori Milestone 1's orbit quotient and homology. No `AbelianLattice`, `RiemannForm.hodgeDual` or `polarizedHodgeEquivalence`.
- Ready now: no: §A5.1 needs ComplexComparisonPartII §§C-1.1, C4.4 (not started) and A4.1 (the integral Tate module); §A5.3 needs Chow's theorem and proper GAGA (ComplexComparisonPartII §§C1.9, C4.2). §A5.2's purely lattice-theoretic API (`RiemannForm.hermitian`, `scale`, `homological`, `hodgeDual` on an abstract lattice with complex structure) uses only Tau Ceti and Mathlib and could start now; its application to `A` needs §A5.1.
- Serves defs: 12 (target: §§A5.1–A5.5), 13, 23 (through 12), 74 (§§A5.1, A5.6–A5.7), 85 (§A5.1), 89 (Layer A5)
- Evidence: README l.2518 "## Layer A5: Complex uniformization and families", l.2527 "### A5.1 Lattice uniformization" (*Needs:* A4.1; ComplexTori; ComplexComparisonPartII C−1.1, C4.4), l.2574 "### A5.2 Riemann forms" (*Needs* l.2606), l.2678 "### A5.5 The polarized Hodge equivalence" (*Needs* l.2695), l.2698 "### A5.6 Analytic families and the algebraic comparison", l.2736 "### A5.7 Degree-one realization conventions".

### §§A6.11, A6.21 The characteristic polynomial on the Tate module; Frobenius semisimplicity
- Status: NOT-STARTED.
- Ready now: no: §A6.11 needs A4.1 (the Tate module) and A6.10; §A6.21 needs A6.8, A6.11, A6.14.
- Serves defs: 89
- Evidence: README l.3042 "### A6.11 The characteristic polynomial on the Tate module", l.3360 "### A6.21 Frobenius semisimplicity".

### §A6.38 The Hodge line bundle
- Status: NOT-STARTED.
- Ready now: no: needs A1.3, A5.8 and AlgebraicVectorBundles L0C (determinants).
- Serves defs: 85
- Evidence: README l.3867 "### A6.38 The Hodge line bundle" (`λ_H = det ω_A`, `ω_A = e^*Ω¹_{A/S}`).

## TauCetiRoadmap/ComplexComparisonPartII
No STATUS.md (merged as roadmap PR #848; Tau Ceti checked at 7cbfff3ef, 2026-11-16). Tau Ceti has the holomorphic structure sheaf `TauCeti.holomorphicSheaf` (Analysis/Complex/HolomorphicSheaf.lean) and the holomorphic structure sheaf of complex manifolds (Geometry/Manifold/Complex/StructureSheaf/); no `ComplexAnalyticSpace` or `complexSchemeAnalytification`.

### §C-1.1 Analytic local models and scheme analytification `complexSchemeAnalytification`
- Status: NOT-STARTED.
- Ready now: no: the local models need ComplexKahlerGeometry K3–K4 and RealAnalyticGeometry R3.2 item 0; the scheme analytification also cites ReductiveGroups §§3A.5c–3A.5e (smooth complex charts, not started).
- Serves defs: 12, 15, 13, 23, 74, 85 (the last four through AbelianSchemesAndArithmeticModuli §A5.1)
- Evidence: README l.1003 "### C-1.1 Analytic local models and scheme analytification", l.1053 "Define `complexSchemeAnalytification` ..."; *Needs* lines cite "ComplexKahlerGeometry K3–K4", "RealAnalyticGeometry R3.2 item 0", "ReductiveGroups §3A.5c–3A.5e".

### §C-1.2, §C1.9, §§C4.1–C4.4 Analytic quotients and completed stalks, proper GAGA, Remmert, Chow, maps out of proper schemes
- Status: NOT-STARTED.
- Ready now: no: §C-1.2 needs §C-1.1, AlgebraicModuliForArithmeticGeometry Layer 3 and SchemeAndStackFoundations Layer 1; §C1.9 needs C0, C1.5, C1.7 (`CoherentAnalytification`, `cartanTheoremB`, `projectiveLerayCover`); §C4.1 needs §C-1.1; §C4.4 needs §C1.9.
- Serves defs: 15 (target for analytification of quasi-projective varieties and GAGA), 12, 13, 23, 74, 85, 89 (through AbelianSchemesAndArithmeticModuli §§A5.1, A5.3)
- Evidence: README l.1103 "### C-1.2 Complex analytic quotients and completed stalks", l.1976 "### C1.9 Projective and proper coherent GAGA", l.2678 "### C4.1 Remmert's theorems", l.2700 "### C4.2 Chow's theorem with nilpotents", l.2741 "### C4.4 Holomorphic maps out of proper schemes".

### §C5.1 The ordinary comparison
- Status: NOT-STARTED.
- Ready now: no: needs DerivedDeRhamCohomology Layer 2 §§2.1–2.19 (`DeRham.complex`, not in Tau Ceti) and AlgebraicVectorBundles L0C exterior powers.
- Serves defs: 74 (Betti duality in open PR #1543 §5.1 builds on it)
- Evidence: README l.2993 "### C5.1 The ordinary comparison".

### §C6.6 Integral and rational Artin comparison
- Status: NOT-STARTED.
- Ready now: no: needs §§C6.0–C6.5 and EtaleCohomologyFoundations §F.4 (`normalizedAdicSystems`, `classicalAdicRealization`, `rationalAdicRealization`; not started).
- Serves defs: 89
- Evidence: README l.5145 "### C6.6 Integral and rational Artin comparison".

## TauCetiRoadmap/CyclotomicClassGroupsAndStickelberger
No STATUS.md (merged; Tau Ceti checked at 7cbfff3ef, 2026-11-16).

### §4.3 Abelian subvariety quotient B/C and the Albanese modular quotient A_f
- Status: NOT-STARTED (Tau Ceti has `AbelianVariety`, `AbelianVariety.MorphismGroup`, isogenies and newform coefficient fields; no quotient of an abelian variety, no Jacobian of `X₁(N)`).
- Ready now: no: `B/C` needs JacobianChallenge Layer E (ample bundles, duality, polarization) and ModularCurves 0C; `A_f` needs JacobianChallenge Layers D–F (the Jacobian) and ModularCurves Layers 4–10 (`X₁(N)` and Hecke correspondences).
- Serves defs: 71 (its `J₁(N)` variant; the `J₀(N)` form is in open PR #913 Layer 16)
- Evidence: README l.754 "### 4.3 Shared abelian arithmetic and the modular residual extension"; l.778 "The shared modular construction is the Albanese quotient A_f ..."; l.780 "Construct the abelian subvariety quotient B/C for any abelian subvariety C of an abelian variety B over a field k".

## TauCetiRoadmap/ReductiveGroups
STATUS.md snapshot: 23dce4e 2026-11-16, generated against Tau Ceti aa6e43e (Tau Ceti checked at 7cbfff3ef, 2026-11-16; README at roadmap c6ef576)

### Layer 5 (solvable groups) Structure of smooth connected solvable groups, G = G_u ⋊ T
- Status: PARTIAL. Exists: `torus_coinvariants_unipotentRadical` (G/G_u is a torus), and the triviality of homomorphisms from diagonalizable groups to unipotent groups, scheme-theoretically, so a diagonalizable closed subgroup of a unipotent group is trivial (`TauCeti.geometricallyUnipotentPointsCommHopfAlgProperty.bialgHom_eq_unit_comp_counit_of_groupLikeSetSpan_eq_top`, Algebra/AlgebraicGroup/Unipotent/Diagonalizable.lean, on `Module.Basis.map_coefficientMatrix_eq_one_of_isUpperTriangular_of_groupLikeSetSpan_eq_top`, Algebra/AlgebraicGroup/Representation/UpperUnitriangular.lean). Missing: the consequence that a maximal torus T meets G_u trivially and maps isomorphically onto G/G_u, the decomposition G = G_u ⋊ T, and conjugacy of subgroups of multiplicative type into T by G_u(k̄) (Milne, Theorem 16.33(b),(d)). STATUS lists Layer 5 as done.
- Ready now: yes. It is the input that Layer 7 torus conjugacy, and through it the root datum, wait on.
- Serves defs: 1, 4, 11, 23, 79
- Evidence: README l.2268 "## Layer 5: solvable and unipotent groups; the unipotent radical", l.2293 "**Solvable groups.**" bullet ("Prove, over `k̄`, the decomposition `G = G_u ⋊ T` ... (Milne, Theorem 16.33(d), p. 336)"; *Needs:* the unipotent theory, the pinned Lie–Kolchin theorem and torus quotient, Layer 4's tori, Layer 3's quotients); grep finds no `G_u ⋊ T` decomposition in Algebra/AlgebraicGroup/Solvable/ (SemidirectProduct.lean only proves solvability of semidirect products); Layer 7 torus conjugacy goes through Borel containment (Borel/Conjugacy/Containment.lean) and then conjugacy of maximal tori inside the solvable Borel.

### Layer 7 Root datum, relative root system, parabolics P_G(λ) and Levi decompositions
- Status: PARTIAL. Exists: the parabolic predicates `IsParabolic`/`IsParabolicOverAlgClosed` (Algebra/AlgebraicGroup/Parabolic/Basic.lean); dynamic `parabolicDefiningHopfIdeal`/`leviDefiningHopfIdeal` with `parabolicLeviFppfQuotientIso` (Algebra/AlgebraicGroup/Dynamic/…); GL_n weight parabolics proved parabolic (Algebra/AlgebraicGroup/GeneralLinear/Weight/Parabolic/Borel.lean); torus conjugacy under extra hypotheses (Torus/Conjugation.lean). Missing: `StructureAcceptance.exists_conjugate_eq_of_isMaximalTorus` (unconditional), `exists_levi_complement_of_isParabolic`, `exists_titsSystem_of_isBorel`, P_G(λ) parabolic for general reductive G, the root datum of (G,T), and the relative root system.
- Ready now: no. Unconditional torus conjugacy needs the structure of smooth connected solvable groups, G = G_u ⋊ T with subgroups of multiplicative type conjugate into T by G_u(k̄) (Milne, Theorem 16.33(b),(d)). The README assigns this to Layer 5's "Solvable groups" bullet, which STATUS lists as done, but Tau Ceti has only `torus_coinvariants_unipotentRadical` (G/G_u is a torus) and the triviality of diagonalizable subgroups of unipotent groups (Unipotent/Diagonalizable.lean); Borel containment (Borel/Conjugacy/Containment.lean) is in place. The split root datum needs torus conjugacy, then the rank-one subgroups G_α with their coroots (Milne 21.11) and generation of N/T by reflections (Milne 21.37). The roots, pinnings and rational Weyl group exist (Tangent/RootSpace.lean, Pinning/Basic.lean, DiagonalizableGroup/Normalizer/WeylGroup.lean). The completeness of G/P needs the Layer 3 quotient representability (partial). Bruhat cells need Layer 7C (partial).
- Serves defs: 1, 4, 11, 23, 79
- Evidence: README l.2821 "## Layer 7: structure theory", l.2861 "**Parabolic subgroup schemes and Levi decompositions.**", l.2916 "**Root datum**", l.2929 "**relative root system** for non-split groups"; Torus/Conjugation.lean has `exists_conjugate_eq_of_isMaximalTorus` only with containment hypotheses (`hcontainI`); STATUS "remaining: unconditional torus conjugacy, root datum, centralizer equals torus, Bruhat and general parabolic Levi theory".

### Layer 7b Algebraic parabolics and Levi intersections (comparison with standard parabolics)
- Status: NOT-STARTED
- Ready now: no: needs Layer 7 Levi complements, Bruhat decomposition and the common-torus theorem, plus Layer 7a rational points (partial).
- Serves defs: 1, 4, 11, 23, 79
- Evidence: README l.3236 "## Layer 7b: algebraic parabolics and Levi intersections" (l.3275 double cosets "consuming Layer 7's Bruhat decomposition, common-torus theorem"; Dependencies l.3314 "Layers 7 and 7a"); STATUS Layer 7b "untouched"; grep `exists_levi_complement_of_isParabolic|exists_titsSystem_of_isBorel` empty.

### Layer 9D Isomorphism and existence theorems: split reductive groups ↔ root data
- Status: NOT-STARTED for the isomorphism and existence theorems. Related pieces exist: pinning transport across isomorphisms (Algebra/AlgebraicGroup/Pinning/Isomorphism.lean) and the Chevalley carriers, including Algebra/AlgebraicGroup/Chevalley/Orthogonal.lean.
- Ready now: no: needs the Layer 7 root datum, Layer 8 split data over general bases (partial) and the Layer 9 uniform pinned construction (partial).
- Serves defs: 11
- Evidence: README l.4976 "## Layer 9D: classification, relative groups and forms", l.4977 "The **isomorphism** and **existence theorems**: split reductive groups ↔ root data"; STATUS "remaining: isomorphism and existence theorems, relative center and derived group, forms, perfect-field pseudo-reductivity, nilradical filtration of the Weil example".

### 3A.5e The complex Lie group G(ℂ)
- Status: NOT-STARTED. Only the pinned inputs exist: point topology and topological group `TauCeti.PointTopology.isTopologicalGroup` (Topology/Algebra/PointTopology/Group.lean) and scheme point topology with charts (Topology/Algebra/PointTopology/Scheme/Charts.lean). No complex manifold or Lie-group structure on G(ℂ).
- Ready now: no: needs 3A.5b-3A.5d (open-chart embeddings, scheme-level fibre product, smooth complex charts). STATUS lists these as the 3A remainder ("complex-point comparison").
- Serves defs: 68
- Evidence: README l.1914 "**3A.5e The complex Lie group `G(ℂ)`.**" ("By 3A.5c–3A.5d, `G(ℂ)` is a Hausdorff, second-countable complex manifold"); STATUS 3A "remaining: complex-point comparison, restriction to O(1) sections and remaining worked tests"; supplier contract l.1058 "The library does not state that an affine open chart is an open embedding…".

## TauCetiRoadmap/RiemannianGeometry
STATUS.md snapshot: d9fbe7b 2026-11-11 (Tau Ceti checked at 7cbfff3ef, 2026-11-16)

### R5a Immersion geometry: pullback connection, normal bundle, B, S, ∇⊥
- Status: PARTIAL: flat-ambient case and projections only: `TauCeti.secondFundamentalForm` (Analysis/InnerProductSpace/SecondFundamentalForm.lean), `shapeOperator` (Analysis/InnerProductSpace/ShapeOperator.lean), on manifold sources `TauCeti.manifoldSecondFundamentalForm` and `TauCeti.manifoldShapeOperator` (Geometry/Manifold/Immersion/{SecondFundamentalForm,ShapeOperator}.lean), smooth tangent and normal projections along immersions into a Riemannian manifold (Geometry/Manifold/Riemannian/Immersion/Projection.lean), Gauss formula along curves (Geometry/Manifold/VectorBundle/CovariantDerivative/AlongCurve/Immersion.lean), embedding normal spaces (Geometry/Manifold/SmoothEmbedding/NormalSpace/), pullback metric along immersions (Geometry/Manifold/Riemannian/Pullback/Basic.lean). Nothing for a Riemannian ambient beyond the projections: no pullback ambient connection, normal bundle ν_f as a bundle, intrinsic B, S, ∇⊥, or Gauss/Codazzi/Ricci
- Ready now: normal-bundle comparison: yes (needs SBC B2.1 pullback/Hom bundles, which Mathlib already supplies natively, and GT 1.5 normal bundle, pinned in Tau Ceti). B/S/∇⊥: no per README, which lists "SmoothBundlesConnections B2–B4" (B3–B4 untouched). This dependency looks soft, since R5a uses Tau Ceti's vector-bundle `CovariantDerivative`, not principal connections; R1 curvature is done and the normal projections exist
- Serves defs: 31, 49, 52, 65, 66
- Evidence: README l.3205 "### R5a. Immersion geometry and first variation"; *Needs* l.3231 "SmoothBundlesConnections B2.1 (smooth pullback and Hom bundles); GeometricTopology Layer 1 (embedding normal bundle)" and l.3300 "R1 curvature and tensor connections; R5a smooth normal comparison; SmoothBundlesConnections B2–B4"; STATUS coverage Layer 5 remaining "R5a beyond flat-ambient groundwork, and all of R5b"; grep `normalConnection|meanCurvature|principalCurvature` in Tau Ceti: no hits

### R5a.1 Orientation-free C² relative volume
- Status: PARTIAL: the relative density of two Riemannian metrics `Bundle.ContMDiffRiemannianMetric.relativeVolumeDensity` (Geometry/Manifold/Riemannian/VolumeDensity/Relative.lean): positive, `C^n`, basis/chart independent, `relativeVolumeDensity_self`; `dV_{g'} = J dV_g` (`riemannianVolume_eq_map_withDensity_relativeVolumeDensity`, `integral_riemannianVolume_eq_integral_relativeVolumeDensity_smul`), no orientation; pullback along local diffeomorphisms and restriction to open sets and time intervals (VolumeDensity/Restriction.lean); also `hasDerivAt_chartVolumeDensity`, `eventually_forall_injective_mfderiv_of_isCompact`. Missing: joint parameter dependence of `J_t` for a family `F_t`, and the C² functional `V(t) = ∫(J_t − 1) dvol_(g_0)` with its two derivatives.
- Ready now: yes (induced metric `ContMDiffRiemannianMetric.pullback`, `riemannianVolume` and the relative density exist; what remains is differentiation under the integral).
- Serves defs: 52
- Evidence: README l.3304 "#### R5a.1. Orientation-free C² relative volume" ("Define the positive relative density J_t ... and prove `dvol_(g_t)=J_t dvol_(g_0)`"); *Needs* l.3358.

### R5a.2 Principal curvatures, H, minimality, first variation, minimal cones
- Status: NOT-STARTED (only the flat-ambient B/S above)
- Ready now: no: needs R5a's B/S pairing; the first-variation part also needs R5a.1 and DG Layer 12 integration/divergence
- Serves defs: 49, 52, 65, 66
- Evidence: README l.3362 "#### R5a.2. First variation and immersion examples", l.3364 "Define principal curvatures as the eigenvalues of S_ν ... H=(tr B)/m ... minimality is H=0"; l.3399 "minimal cone equivalence away from the cone vertex"; *Needs* l.3387

### R5b Second variation, Jacobi operator, stability, Dirichlet index
- Status: NOT-STARTED (only the abstract coercive-form spectral API, e.g. `IsCoercive.isLeast_rayleighQuotient`, which the README consumes)
- Ready now: no: needs R5a, R5a.1, R5a.2
- Serves defs: 52, 65
- Evidence: README l.3581 "### R5b. General normal second variation and hypersurface stability", l.3583 "consumes R5a's immersion geometry, R5a.1's ... relative-volume lemma and R5a.2's first variation"; l.3639 "Define the Dirichlet operator L_D of L, the Dirichlet Jacobi operator"; STATUS "R5b has not begun"

### R5c Schrödinger operators on compact manifolds: closed case, index on smooth sections, principal eigenfunction
- Status: NOT-STARTED: `TauCeti.Manifold.laplaceBeltrami`, `laplaceBeltrami_eq_sum_hessian` and `IsCoercive.formSolutionOperator` exist; no bundle Schrödinger operator `∇*∇ + K`, closed-manifold realization, min–max or principal eigenfunction
- Ready now: no: needs R5b's Dirichlet realization, ComplexKahlerGeometry K5a (closed case), PDE A4, A6 and E20, PseudodifferentialOperators P1.0's connection Laplacian, SBC B2–B4
- Serves defs: 52, 66 (through open PR #2451 Layer 3)
- Evidence: README l.3715 "### R5c. Schrödinger operators on compact manifolds: spectrum, principal eigenfunction and Dirichlet problem"; *Needs* l.3807; roadmap PR #2222; MinimalSurfaces MS6.1 *Needs* "R5c (the closed case, the index on smooth sections and the smoothness of eigensections)"

### R7.9 Separating and two-sided hypersurfaces
- Status: NOT-STARTED: the inputs it names exist (`TauCeti.SmoothEmbedding.NormalSpace`, `normalExp` and the Riemannian tubular neighbourhood, `TauCeti.IsBicollar`, `TauCeti.periodHom`, regular sublevels, `TauCeti.VectorBundleOrientationCover`); no unit normal double cover `S(ν_f)`, two-sidedness predicate or separation theorem
- Ready now: no: needs R5a's normal bundle (ν_f as a bundle) and DifferentialGeometry 12.5's outward unit normal
- Serves defs: 52, 66 (through open PR #2451 Layer 3) (one-sided index through the normal double cover, MinimalSurfaces MS6.3)
- Evidence: README l.4469 "### R7.9. Separating and two-sided hypersurfaces", "Call f *two-sided* when it has a unit normal field ν ... The unit vectors of `ν_f` form the *unit normal double cover*"; *Needs* l.4745; roadmap PR #2223

### R1.3 Normal homogeneous metrics on G/H
- Status: NOT-STARTED: Riemannian submersions have splitting, connection and O'Neill tensors with their symmetries, their transport under local isometries, and the integrability criterion for the horizontal distribution (Geometry/Manifold/Riemannian/Submersion/{Basic,Connection,Integrability}.lean, Submersion/ONeill/{Basic,Isometry}.lean); O'Neill's horizontal curvature formula `inner_curvatureTensor_of_mem_orthogonal_ker` with `sectionalCurvature_mfderiv` (Submersion/Curvature.lean); no homogeneous quotient metric. STATUS coverage Layer 1 remaining "... and the O'Neill curvature formulas" (STATUS predates Submersion/Curvature.lean)
- Ready now: no: needs SBC B1.4's smooth G/H (partial: the free proper quotient theorem and Cartan's closed-subgroup theorem are in code, G/H for a closed subgroup H is not assembled)
- Serves defs: 62, 15, 31 (through RealSemisimpleLieGroups §§5.3, 5.7)
- Evidence: README l.1205 "### 1.3 Metric changes, Lie groups and submersions", l.1310 "homogeneous metric on SBC B1.4's G/H with horizontal space h^perp and prove G→G/H is a Riemannian submersion"

### R4 item 4 Cartan–Hadamard
- Status: NOT-STARTED: the supplier `norm_le_norm_mfderiv_riemannianExp_of_sectionalCurvature_nonpos` exists (Geometry/Manifold/Riemannian/Jacobi/Comparison.lean); no `cartanHadamard_isCoveringMap`, no R4.3 covering criterion for local isometries (the generic covering criterion from local sections is in Topology/Covering/LocalSection.lean)
- Ready now: no: needs R4 item 3 (covering criterion for local isometries from complete manifolds; not in code). HopfRinow L4 is completed
- Serves defs: 62, 15, 31 (through RealSemisimpleLieGroups §§5.3, 5.7)
- Evidence: README l.2565 "4. Cartan–Hadamard (`cartanHadamard_isCoveringMap`)", *Needs* l.2577 "R4.3 (covering criterion), HopfRinow (Completed) Layer 4"; STATUS "R4 has its models, the nonpositive-curvature exponential bound ... but no comparison theorem"

### R6 Euclidean ε-tube inversion and nearest-point retraction
- Status: NOT-STARTED: the Euclidean normal tube of a `C²` embedding of a compact manifold `TauCeti.exists_isTubularNeighborhood_normalBundle` (`TubularNeighborhood/Euclidean.lean`) and the squared-distance Hessian declarations R6 consumes are in code; no nearest-point retraction.
- Ready now: yes (its *Needs* are Tau Ceti declarations).
- Serves defs: 37, 48 (through YangMillsConnectionsAndCaloricGauge §1.2)
- Evidence: README l.4081 "### R6. Focal geometry and squared-distance Morse functions", l.4199–4203 "R6 owns the ε-tube inversion for closed-image Euclidean embeddings ... a nearest-point retraction".

## TauCetiRoadmap/RiemannianGeometry/MinimalSurfaces
No STATUS.md; sub-roadmap from roadmap PR #2226 (Tau Ceti checked at 7cbfff3ef, 2026-11-16)

### MS6.1–MS6.3 Morse index and nullity of minimal submanifolds (compact, by exhaustion, hypersurfaces)
- Status: NOT-STARTED (grep for a Morse index of minimal immersions, Jacobi operator or nullity: no hits; the only index form is along curves, Geometry/Manifold/Riemannian/IndexForm/Basic.lean)
- Ready now: no: needs R5b (index form, Dirichlet realization of `−J^⊥`) and R5c (closed case, index on smooth sections); MS6.3's one-sided case needs R7.9's normal double cover
- Serves defs: 52
- Evidence: README l.1181 "### 6.1 Morse index on compact minimal submanifolds and negative eigenvalues of `−J^⊥`" ("the nullity `null(Σ) = dim ker(−J^⊥)`"), l.1217 "### 6.2 Morse index of minimal submanifolds in `ℝ^m` via exhaustions" ("independent of the choice of smooth exhaustion and equals the supremum of `dim E` over finite-dimensional subspaces `E ⊂ C^∞_c(Σ ∖ ∂Σ;ν_f)`"), l.1255 "### 6.3 Specialization to hypersurfaces and two-sided hypersurfaces"; *Needs* l.1214, l.1253, l.1296

## TauCetiRoadmap/EtaleCohomologyFoundations
STATUS.md snapshot: 53f4df3 2026-11-16, generated against Tau Ceti aa6e43e (Tau Ceti checked at 7cbfff3ef, 2026-11-16; README at roadmap c6ef576)

### §F.0.2 Finite étale Galois categories, `EtaleFundamentalGroup` and the étale fundamental groupoid
- Status: PARTIAL, and enough for def 84's use of π₁. In code: `PreGaloisCategory (FiniteEtaleScheme S)` for every S (AlgebraicGeometry/FiniteEtale/Quotient.lean); `FiberFunctor (fiber x)` and `GaloisCategory (FiniteEtaleScheme S)` for connected S, with any two geometric points joined by a path (FiniteEtale/Galois/Category.lean); `Aut (FiniteEtaleScheme.fiber x)` with functoriality `mapAutFiber`/`mapFiberIso` and change of basepoint `mapAutFiber_conjAut` (Galois/Functoriality.lean); paths on disconnected bases (Galois/Component.lean); `galContinuousMulEquivAutFiber : Gal(Ω/K) ≃ₜ* π₁(Spec K,x)` (Galois/FundamentalGroup.lean). Missing: the named `EtaleFundamentalGroup`, `EtalePath`, `EtaleFundamentalGroup.map` and `EtaleFundamentalGroup.small`; lisse monodromy; tensor/dual transport.
- Ready now: yes: the named `EtaleFundamentalGroup` package needs only what is in code; lisse monodromy can use `CategoryTheory.Sheaf.IsFiniteLisse` and the fully faithful `TauCeti.FiniteEtaleScheme.toSheafFullyFaithful` (STATUS frontier).
- Serves defs: 84
- Evidence: README l.312 "## F.0.2 Finite étale Galois categories and the étale fundamental groupoid", l.380 (block "The canonical fundamental group", `EtaleFundamentalGroup`, EtalePath); STATUS "§F.0.2 is partial: the Galois category, paths, functoriality of `π₁` and the connected-component criterion are done, but lisse monodromy and tensor/dual transport are missing". `EtaleFundamentalGroup` absent from Tau Ceti.

### §F.0.1 Finite and constructible étale module sheaves (prerequisite of every cohomology item below)
- Status: PARTIAL. Geometric stalks with their module structure, `TauCeti.AlgebraicGeometry.Scheme.etaleStalk`, exactness `shortExact_map_etaleStalk`, joint conservativity `isIso_of_forall_isIso_etaleStalk`, stalkwise exactness criteria `exact_iff_forall_exact_map_etaleStalk`; finite lisse sheaves `CategoryTheory.Sheaf.IsFiniteLisse` with `isFiniteLisse_constantSheaf`, `IsFiniteLisse.finite_etaleStalk` (AlgebraicGeometry/Sites/Etale/ModuleSheaf.lean); coefficient-invertibility criteria (per STATUS). Missing: `VanishingCycles.constructibleEtale`: stratifications, constructibility, pullback and étale descent, extension by zero, closure under limits, colimits, extensions and tensor products, and the weak Serre class property.
- Ready now: yes, mostly. The cited SchemeAndStackFoundations §1.1 (`sheaf_stack`) and §§2.1, 2.9 have only first definitions, so work may have to supply local substitutes.
- Serves defs: 18, 19, 69, 77, 84 (F.1, F.4.x and F.0.2's monodromy all need it)
- Evidence: README l.173 "## F.0.1 Finite and constructible étale module sheaves" (*Needs:* SchemeAndStackFoundations §1.1, §§2.1, 2.9); STATUS "§F.0.1 has stalks, finite lisse sheaves and coefficient-invertibility criteria, and nothing on constructibility"; frontier "Constructible étale sheaves ... Everything from §F.0.3 onward depends on this".

### §F.1 and §0.9 cup products: `finiteCoefficientCohomology` and classes as shifted morphisms
- Status: NOT-STARTED. Neither `constructibleDerivedCategory` nor `finiteCoefficientCohomology` exists, and no cup product on `Sheaf.H` or on étale cohomology exists in Tau Ceti or Mathlib (the cup files in Tau Ceti are for cochains, Hochschild cochains and Galois cohomology).
- Ready now: no. §F.1 needs §§F.0.1–F.0.4, §0.7 (`supportLocalization`), EnhancedDerivedSheaves §§0.1–0.4 (`tensorHom`, `functorCoherence`) and SchemeAndStackFoundations §§2.1–2.2, 2.5, 2.7, 2.17. §0.9's `ShiftedHom` cup product needs §0.7 and Mathlib `ShiftedHom`; its plain (unsupported) form on `D(X,Λ)` could be built on Mathlib's `DerivedCategory` once a monoidal structure on `D(X,Λ)` is available.
- Serves defs: 18 (cup products), 69, 77 (étale cohomology with Z/ℓⁿ coefficients)
- Evidence: README l.827 "## F.1 Derived sheaves and coherent diagrams", l.874 "**Finite-coefficient cohomology and coherent actions.** ... Build cup products"; l.1838 "**Classes as shifted morphisms, cup products with supports and purity.** ... `Hⁿ(X,K) = ShiftedHom Λ_X K n` ... Define the cup product `Hᵃ(X,K) × Hᵇ(X,L) → Hᵃ⁺ᵇ(X,K⊗L)`" (*Needs:* §0.7); STATUS "§§F.0.3, F.0.4, F.0.A2, 0.5–0.11, F.1–F.3a ... are untouched".

### §F.2.1 Proper base change and §F.2.2 Smooth base change
- Status: NOT-STARTED. `VanishingCycles.properBaseChange` and `smoothBaseChange` are absent.
- Ready now: no. F.2.1 needs SchemeAndStackFoundations §§2.1–2.2 and EnhancedDerivedSheaves §§0.1–0.4. F.2.2 needs F.1 `finiteCoefficientCohomology` and SchemeAndStackFoundations §0.9.
- Serves defs: 69 (and 77 through the étale cohomology of modular curves)
- Evidence: README l.898 "## F.2.1 Proper base change for arbitrary torsion" (*Needs* l.907); l.916 "## F.2.2 Smooth base change in the rotated square" (*Needs* l.927); STATUS: F.2 untouched.

### §§F.4.1–F.4.2 Normalized adic systems and classical Z_ℓ realization
- Status: NOT-STARTED. `normalizedAdicSystems` and `classicalAdicRealization` are absent. Mathlib's pro-étale `Scheme.EllAdicCohomology` is the §F.4.3 comparison target, not this.
- Ready now: no. Needs §§F.0.1–F.0.4, F.1, F.2–F.3 and EnhancedDerivedSheaves §0.3 `inverseLimits`/`derivedCompletion`.
- Serves defs: 69 (Z_ℓ coefficients), 77
- Evidence: README l.1470 "## F.4.1 Normalized bounded constructible systems" (*Needs* l.1494: "§§F.0.1–F.0.4, F.1; EnhancedDerivedSheaves §0.3 inverseLimits and derivedCompletion"); l.1506 "## F.4.2 Classical realization and finite-level cohomology limits" (*Needs* l.1517); STATUS: F.4.1–F.4.6 untouched.

### §F.4.5 Rational realization and finite-dimensional cohomology (b₂)
- Status: NOT-STARTED. `VanishingCycles.rationalAdicRealization` is absent.
- Ready now: no. Its *Needs* line is "normalizedAdicSystems through adicFiniteness" (§§F.4.1–F.4.4, which need F.3 finiteness), §F.0.2, F.2 Künneth and §F.4.0 stable lattices (partial in code: `Subgroup.isCompact_closure_iff_exists_stable_lattice`, `TauCeti.GaloisLattice.IntegralModel.nonempty`). It is near the end of the ECF dependency chain.
- Serves defs: 19
- Evidence: README l.1665 "## F.4.5 Rational realization and finite-dimensional cohomology" (`RΓ_(c)(X,K_Qℓ)≅RΓ_(c)(X,K_Zℓ)⊗ᴸℚ_ℓ`, finite-dimensional `Hⁱ_(c)`, l.1690); *Needs* l.1696; STATUS: F.4.1–F.4.6 untouched.

### §F.0.A2 The arithmetic fundamental-group sequence and sections of rational points
- Status: NOT-STARTED. `arithmeticExactSequence` is absent. Its §F.0.A0 input is done for fields (`galContinuousMulEquivAutFiber`); §F.0.4 topological invariance (`universalHomeomorphismEtaleEquivalence`) is not started.
- Ready now: no: needs §F.0.4 (finite étale covers along the universal homeomorphism `X_{k̄} → X_{k^sep}`), descent of finite étale covers along limits from SchemeAndStackFoundations §0.9, and §F.0.2's named `EtaleFundamentalGroup.map`.
- Serves defs: 84
- Evidence: README l.613 "## F.0.A2 The arithmetic fundamental-group sequence" (`1 → π₁^ét(X_{k̄}) → π₁^ét(X) → π₁^ét(Spec k) → 1` for qcqs geometrically connected `X/k`; "A `k`-rational point `a` of `X` gives a continuous section `s_a`"; *Needs:* §F.0.A0, §F.0.2, §F.0.4, SchemeAndStackFoundations §0.9); STATUS lists §F.0.A2 among the untouched sections.

## TauCetiRoadmap/ArithmeticGaloisRepresentations
No STATUS.md (merged; Tau Ceti checked at 7cbfff3ef, 2026-11-16).

### Layer 1 (§§1.1, 1.6, 1.8–1.9) and Layer 5 Continuous representations, integral models, Brauer–Nesbitt, residual representations, recognition by Frobenius
- Status: PARTIAL: the carrier `TauCeti.ContinuousRep` with `Iso`, `ofCharacter`, `baseChange`, `toContRepresentation` (RepresentationTheory/Continuous/ContinuousRep.lean) and `GaloisLattice.IntegralModel` (Continuous/IntegralModel.lean), from EtaleCohomologyFoundations §F.4.0. Missing: `ContinuousRep.Hom`, `continuous_iff_matrixCoeff`, `ContinuousRep.charpoly` and the rest of Layer 1; all of Layer 5.
- Ready now: yes: §1.1 needs only Mathlib and the §F.4.0 carrier in code.
- Serves defs: 69
- Evidence: README l.767 "## Layer 1: continuous representations and integral models", l.779 "### 1.1 Continuous representations" (*Needs:* "EtaleCohomologyFoundations §F.4.0 (Tau Ceti `TauCeti.ContinuousRep`); Mathlib"), l.1124 "### 1.6 Lattices and integral models", l.1226 "### 1.8 Brauer–Nesbitt", l.3447 "## Layer 5: recognition by Frobenius polynomials".

### §1.11 Reductive quotients over fields and DVRs (`Conj_H = H//H`, `χ_H`)
- Status: NOT-STARTED. Inputs in code: `TauCeti.HopfAlgebra.conjugationAlgHom` (Algebra/AlgebraicGroup/Hopf/Conjugation.lean), `TauCeti.ComoduleAlgebra.finiteType_coinvariants` for linearly reductive Hopf algebras (Algebra/Bialgebra/ComoduleAlgebra/LinearlyReductive.lean), `reductiveCommHopfAlgProperty`.
- Ready now: yes over a field (ReductiveGroups Layer 6, Mathlib `AlgHom.equalizer`); the DVR case needs ReductiveGroupsPartII RG2.3.1 *reductive-model* (not started).
- Serves defs: 89
- Evidence: README l.1382 "### 1.11 Uniqueness of lattices and symplectic models", l.1436 "**Reductive quotients over fields and DVRs.**", `Conj_H` and the `GL_n` characteristic-polynomial instance l.1456–1475, *Needs* l.1476.

### §§2.1–2.2 Decomposition groups, inertia, unramifiedness and Frobenius
- Status: NOT-STARTED (no `GaloisRep.decompositionGroup`, `GaloisRep.inertiaGroup`, `IsArithFrobAtIntegralPrime` in Tau Ceti).
- Ready now: yes for §2.1's local closure and decomposition and inertia groups: Mathlib `IsKrasner.krasner`, `AlgHom.IsArithFrobAt`, `ValuationSubring.decompositionSubgroup` and the completed LocalFieldsRamification. §2.2 follows §2.1.
- Serves defs: 69, 89
- Evidence: README l.1599 "## Layer 2: decomposition groups, inertia and Weil–Deligne representations", l.1616 "### 2.1 Decomposition groups" (*Needs* "Mathlib `IsKrasner.krasner`; `TauCetiRoadmap.LocalFieldsRamification`"), l.1796 "### 2.2 Ramification and Frobenius".

## TauCetiRoadmap/IntegralHeckeAndGaloisDeterminants
No STATUS.md (merged; Tau Ceti checked at 7cbfff3ef, 2026-11-16).

### §3a.1 GLₙ Hecke polynomials, Frobenius conventions and the rank-two modular-form normalization
- Status: NOT-STARTED (grep `heckePolynomial` in Tau Ceti: no hits; the rank-two input `HeckeRing.GL2.Newform.satakeParameters` is in code).
- Ready now: no: the integral GLₙ Hecke polynomial needs IHG.0 and SmoothRepresentationsOfLocalGroups SR.4.3 *gln-generators* (not started); the rank-two normalization needs it.
- Serves defs: 69 (the Frobenius-polynomial normalization of `ρ_{f,λ}`)
- Evidence: README l.1730 "### 3a.1 GLₙ Hecke polynomials and Frobenius conventions", l.1833 "**Rank-two classical modular-form normalization.**" (*Needs* "Integral GLn Hecke polynomial, Arithmetic and geometric Frobenius conversion, Tau Ceti `HeckeRing.GL2.Newform.satakeParameters`").

## TauCetiRoadmap/ComplexKahlerGeometry
STATUS.md snapshot: d9fbe7b 2026-11-11 (Tau Ceti checked at 7cbfff3ef, 2026-11-16)

### K1 + K2 type calculus, T^{1,0}, (1,1)-forms, Dolbeault, i∂∂̄
- Status: PARTIAL: the pieces def 38 needs are in place: eigenbundles T^{1,0}/T^{0,1} (Geometry/Symplectic/Manifold/AlmostComplex/Eigenbundle/), type projections and `IsOfType φ J p q` (Geometry/Manifold/DifferentialForm/AlmostComplexType.lean:205), ∂, ∂̄, d=∂+∂̄, ∂̄²=0 (Geometry/Manifold/DifferentialForm/Dolbeault/{Basic,ComplexManifold}.lean), `dC` with ddᶜ=2i∂∂̄ (Dolbeault/DC.lean), Dolbeault complex and cohomology with pullback, wedge product and `H^(p,0)` (Dolbeault/{Complex,Cohomology,Wedge}.lean), the `(0,q)` polydisc Dolbeault–Grothendieck lemma on smaller concentric polydiscs (`exists_contDiffOn_delBarCoeff_eq_of_polydisc`, Analysis/Complex/Wirtinger/Polydisc.lean). Missing: Newlander–Nirenberg, parametrized submanifolds, the whole-polydisc `(p,q)` lemma, Dolbeault theorem; i∂∂̄ only for smooth forms (no C² version, which is not a target either)
- Ready now: yes (remaining K1/K2 work is not needed for def 38)
- Serves defs: 38
- Evidence: README l.370 "## Layer 1: complex structures and type calculus (K1)", l.558 "## Layer 2: Dolbeault calculus and the local lemmas (K2)"; STATUS "K1 is partial ... K2 is partial: ∂ and ∂̄ have their bidegrees ... `dᶜ = i(∂̄ − ∂)` satisfies `ddᶜ = 2i∂∂̄`"; grep confirms `typeProjection`, `IsOfType`, `dC`, `delBar_delBar_ofComplexManifold`

### §6.1 K6.0 Kähler predicate IsKahler and local Kähler identities
- Status: PARTIAL: the real-carrier predicate `TauCeti.SmoothTwoForm.IsKahler` (closed, `Compatible`, `J.nijenhuis = 0`) with `isKahler_iff`, `IsKahler.isSymplectic`, `isKahler_ofComplexManifold_iff` and the flat example (Geometry/Symplectic/Manifold/Kahler.lean, Tau Ceti PR #37267). Missing: the Hermitian-metric form of the predicate and its comparison with the real carrier, and the local Kähler and curvature identities of 6.1
- Ready now: no: the rest of 6.1 needs K4, 5.1's formal-adjoint comparison and K1 Newlander–Nirenberg for the complex-manifold comparison
- Serves defs: 38 (open PR #2440 Layers 5–6 consume K6.0 for the theorem)
- Evidence: README l.2321 "### 6.1 Local Kähler and curvature identities (K6.0)", "The canonical predicate is a Hermitian metric on a complex manifold with closed fundamental form ... real-carrier condition `IsKahler form J`"; Dependencies l.2690 "6.1 uses Layers 1, 2 and 4 and 5.1's local formal-adjoint comparison"

### §5.7 K5a Hodge/Laplace self-adjoint H² realization, compact resolvent
- Status: NOT-STARTED: the smooth operators exist (`hodgeLaplacian` Geometry/Manifold/Riemannian/Codifferential.lean:246, `laplaceBeltrami` Geometry/Manifold/Riemannian/Laplacian.lean:274) and the abstract `LinearPMap.HasCompactResolvent` API exists (Analysis/InnerProductSpace/LinearPMap/CompactResolvent.lean), as do integer-order bundle Sobolev spaces `TauCeti.SobolevSection` over a finite bundle atlas (Geometry/Manifold/VectorBundle/Sobolev/), but there is no H² realization, real-order distributional Sobolev scale or Rellich on manifolds
- Ready now: no: needs PseudodifferentialOperators P1.0 (Layer 1 partial), 5.4 compact-bundle Sobolev scale (the distributional `BundleSobolev E s` is missing), 5.1 density/test layer (partial: the pointwise star, `DensityBundle` (Geometry/Manifold/VectorBundle/Density.lean) and the fixed-compact topology on compactly supported sections (Geometry/Manifold/VectorBundle/Section/CompactSupportTopology.lean) exist; the orientation line, `BundleTest` on density-twisted bundles and bundle distributions do not); HopfRinow L1 and DG 8.5 are in place
- Serves defs: 40, 38 (open PR #2440 §5.2 consumes K5a)
- Evidence: README l.1948 "### 5.7 Laplace-type estimates, spectral theory and the real Hodge theorem (K5a)", l.2013 "For every formally self-adjoint nonnegative Laplace-type system P on a compact boundaryless base, build its geometric H² realization", l.2038 "satisfies `LinearPMap.HasCompactResolvent`"; *Needs* l.2075; STATUS "K5a is partial: ... Hodge Laplacian ... chart `C^k` seminorms and the topology on smooth sections ... but not the orientation line, density bundle, bundle distributions or Sobolev scale"

### §4.2 K4 Chern connections
- Status: NOT-STARTED (no Chern connection; holomorphic line bundles exist, `Geometry/Manifold/Complex/StructureSheaf/LineBundle/Basic.lean`).
- Ready now: no: needs 4.1 and K1 §1.4's Newlander–Nirenberg theorem (missing).
- Serves defs: 38 (the Ricci form in open PR #2440 Layer 6, for the paper's theorem)
- Evidence: README l.1134 "### 4.2 Chern connections and Koszul–Malgrange"; *Needs* l.1155.

## TauCetiRoadmap/HeegaardFloer
STATUS.md snapshot: 7b9b7c6 2026-11-16, generated against Tau Ceti aa6e43e (Tau Ceti checked at 7cbfff3ef, 2026-11-16)

### F0.5 (§2.7) finite-C^ℓ almost-complex parameter spaces and regularity-loss comparisons
- Status: PARTIAL: finite-regularity carriers `ContMDiffAlmostComplexStructure`, families `ContMDiffAlmostComplexStructureFamily`, chart reading/reconstruction `chartEquiv`, `inChart` (…/Manifold/AlmostComplex/{ContMDiff,Family,Chart,Family/Chart}.lean). Missing: the Banach manifold of C^ℓ tame/compatible J (conjugation charts, openness, Nemytskii estimates), universal CR section, derivative-budget comparisons.
- Ready now: no: needs F1.1–F1.2 `W^{1,p}`/bundle estimates (STATUS Layer 3 remaining) and F0.0 Banach-manifold floor (partial).
- Serves defs: 56, 60 (through F2.4/F2.6d)
- Evidence: README l.1873 "### 2.7 Regularity-loss comparisons for surface and strip Cauchy–Riemann sections (F0.5)"; STATUS Layer 3 remaining "W^{1,p} and bundle interior estimates, totally real boundary estimates, Sobolev spaces on strips, ..."; grep `universalCauchyRiemann` none.

### F2.2 (§4.2) local theory: unique continuation, isolated critical points, adapted coordinates
- Status: PARTIAL (linear inputs only): unique continuation and isolated zeros for `C¹` solutions of `∂ₛξ + J(z)∂ₜξ + Cξ = 0` with a `C¹` field of complex structures, `TauCeti.eqOn_zero_of_contDiffOn_of_forall_isBigO_of_complexStructure`, `eqOn_zero_of_contDiffOn_of_eqOn_zero_of_complexStructure`, `setOf_ne_zero_mem_codiscreteWithin_of_contDiffOn_of_complexStructure` (Analysis/Complex/CauchyRiemann/UniqueContinuation/VariableStructure.lean); the linearized Floer version `SymplecticForm.eqOn_zero_of_floerLinearization_eq_zero_of_forall_isBigO` (Geometry/Symplectic/Floer/UniqueContinuation.lean); the constant-`i` similarity principle. Missing: F2.2a–c for the J-curve itself (W^{2,p} regularity, unique continuation of curves, isolated critical points and point preimages, finite critical sets), adapted coordinates, the accumulation-to-factorization lemma.
- Ready now: no: F2.2a starts from PH5.1 `W^{2,p}` regularity and PH3.5's `W^{1,p}` similarity principle; its differentiated-equation step for `C¹` curves with `C²` J could begin on the variable-structure theorems.
- Serves defs: 60
- Evidence: README l.2592 "### 4.2 Local theory (F2.2)", *Needs* l.2643; STATUS Layer 4 remaining "local theory"; no isolated-critical-point/unique-continuation results for J-curves in Geometry/Symplectic/JHolomorphic/.

### F2.4 (§4.4) and F2.6d (§4.6d) universal moduli spaces, regular J
- Status: NOT-STARTED; local-coordinate linearization exists (`cauchyRiemannLinearization`, Geometry/Symplectic/JHolomorphic/Linearization.lean), the localized variation of a smooth J at an injective point (positive pairing with a cokernel covector, Geometry/Symplectic/Manifold/AlmostComplex/Variation.lean), and F0.0's transversality package: the Sard–Smale theorem `TauCeti.isMeagre_image_criticalPoints_of_isFredholm` for `C^k` Fredholm maps with `k > max(index, 0)` (Analysis/Fredholm/SardSmale.lean), universal level sets and parametric transversality (Analysis/Fredholm/{UniversalLevelSet,Parametric}.lean).
- Ready now: no: needs F0.5 parameter spaces, F2.2 somewhere-injectivity, F1.2 adjoint identification; F2.6d also F2.6b–c and PH5.2.
- Serves defs: 56, 60
- Evidence: README l.2688 "### 4.4 Transversality (F2.4)", *Needs* l.2711; l.2975 "### 4.6d Transversality and degree (F2.6d)", *Needs* l.3027; STATUS Layer 4 remaining "transversality and gluing"; STATUS prose "the abstract transversality package (sharp Sard, Sard–Smale, parametric transversality, the determinant line bundle) is in place".

### F2.6e (§4.6e) normal operator of embedded spheres, four-dimensional regularity
- Status: PARTIAL (local only): `normalCauchyRiemannLinearization` (JHolomorphic/Normal/Linearization.lean) with target covariance `normalFDerivMap` and source covariance `normalCauchyRiemannLinearization_comp_right`, `normalCauchyRiemannLinearization_comp_right_of_surjective` (Normal/Naturality.lean); normal rescaling (Normal/Rescaling.lean). Missing: the global normal-bundle real CR operator, intersection multiplicities, Micallef–White, adjunction, automatic surjectivity for d ≥ −1.
- Ready now: no: needs F2.2, F2.6b, F1.5, F1.2.
- Serves defs: 60
- Evidence: README l.3029 "### 4.6e Four-dimensional curves and regularity (F2.6e)", "For an embedded sphere construct the quotient real CR operator on its normal" (l.3140), *Needs* l.3172.

### F4.B (§6.2) Spin^c, Turaev model, grading carrier
- Status: NOT-STARTED for Spin^c: no Turaev vector-field model, no Spin^c torsor, no c₁. Adjacent combinatorial code only: `HeegaardRegionSystem.WeaklyAdmissibleAt` (spin^c read through Maslov index of periodic domains) and relative grading in TauCeti/LowDimTopology/Heegaard/{SpincAdmissibility,RelativeGrading}.lean; the group `CliffordAlgebra.spinCGroup` = (Spin × U(1))/(−1,−1) with `det` and `toSpecialOrthogonal` (LinearAlgebra/CliffordAlgebra/Spin/SpinC.lean) and its Lie-group structure (Geometry/Lie/CliffordAlgebra/SpinC/Basic.lean).
- Ready now: no: needs F4.A geometric pointed diagrams (only combinatorial `HeegaardRegionSystem`, no handlebody-glued Y found) and F1.4–F1.5.
- Serves defs: 64
- Evidence: README l.3646 "### 6.2 Spinᶜ, periodic surfaces and the grading carrier (F4.B)", *Needs* l.3744; STATUS Layer 6 remaining "spin^c structures in general"; SpincAdmissibility.lean: "identification ... with the Chern class pairing is geometric and is not formalized here".

## TauCetiRoadmap/ModularCurves
STATUS.md snapshot: 7ca783d 2026-11-09, written against the layer numbering before the README reorganisation of roadmap PR #2140 (old 0G is §0.7, old 2B is §2.2, old Layer 9 coarse schemes is Layer 6; Tau Ceti checked at 7cbfff3ef, 2026-11-16)

### §0.7 relative finite-locally-free Grassmannian, Plücker
- Status: PARTIAL: affine case fully in Tau Ceti (TauCeti/AlgebraicGeometry/Grassmannian/*: `scheme`, `glueData`, `chartι`, `schemeHomEquiv`, `isProper_toSpec`, `schemeUniversalIdeal`, Hopf-ideal locus, `FiniteLocallyFree.lean`), with base change along `Spec R' → Spec R`, `G(k, R' ⊗[R] M) ≅ Spec R' ×_{Spec R} G(k, M)` (`Module.Grassmannian.isPullback_baseChangeHom`, `baseChangeHom`, Grassmannian/BaseChange.lean), the comparison used to glue over a non-affine base. Missing: gluing over a non-affine base with independence of trivialisations, universal quotient and kernel there, the universal property over arbitrary `S`, subbundle/dual comparisons, `Grass_1(F) ≅ Proj_S(Sym F)`, the Plücker closed immersion.
- Ready now: yes for gluing over a non-affine base. The rank-one identification and Plücker need StableReduction Layer 2's relative Proj and AlgebraicVectorBundles L0C/L2A (exterior powers, `gradedSymmetricAlgebra`).
- Serves defs: 25, 26 (through AlgebraicModuliForArithmeticGeometry §1.3, whose *Needs* is "ModularCurves §0G")
- Evidence: README l.1076 "### 0.7. Parameter spaces for subgroup schemes" ("This block owns the relative Grassmannian of a finite locally free `𝒪_S`-module"); STATUS Layer 0 remaining "0G over a non-affine base".

### Layer 10 compactified coarse X_H, X_0(N)
- Status: NOT-STARTED (TauCeti/AlgebraicGeometry/ModularCurve/ has `Y₁(N)`, Legendre and level-three lines, no coarse `Y₀(N)` or `X_H`)
- Ready now: no: needs §2.2 quotient isogenies (STATUS "2B quotients E/C" remaining), §3.2 naive `[Γ₀(N)]` (STATUS "naive Gamma0(N)" remaining), Layer 6 quotients, coarse schemes and the `j`-line (STATUS old Layer 9 "everything beyond the Legendre and level-three rings"), the formal-cusp package and a Riemann–Hurwitz package. It uses nothing from Layers 7–9
- Serves defs: 69, 71
- Evidence: README l.4030 "## Layer 10: compactified coarse curves over `ℤ[1/N]`, cusps, and the Shimura covering", Dependencies l.4266; README l.4399 "Dependency order and parallel work" ("Layer 10 uses nothing from Layers 7–9"); STATUS "Layer 10 has not begun".

## TauCetiRoadmap/AlgebraicModuliForArithmeticGeometry
No STATUS.md (merged as roadmap PR #853; Tau Ceti checked at 7cbfff3ef, 2026-11-16).

### §1.3 coherentGrassmannian, plucker (with §1.1 projectiveBundle for the P(E) and Plücker clauses)
- Status: NOT-STARTED (grep `coherentGrassmannian|projectiveBundle|ProjectiveBundles` empty; the affine `Module.Grassmannian.scheme` with base change is in code under ModularCurves §0.7)
- Ready now: no: `coherentGrassmannian` (classifying maps, base change, agreement with `Module.Grassmannian` on affines, properness over `Spec R`) needs ModularCurves §0.7 over a non-affine base (partial; that gluing is ready now). `Gr_1(E) ≅ P(E)` and `plucker` also need §1.1 `ProjectiveBundles.projectiveBundle`, whose Needs are SSF §0.3 (begun: TauCeti/AlgebraicGeometry/RelativeProj/), StableReduction Layer 2, AlgebraicVectorBundles L0C and SSF §5.4 (not started)
- Serves defs: 25, 26
- Evidence: README l.609 "### 1.3 Coherent quotients, Plücker and partial flags" ("Define `coherentGrassmannian`. For a quasi-coherent finite-type E on arbitrary S ..."; *Needs:* ModularCurves §0G, `ProjectiveBundles.projectiveBundle`, ...), l.313 "### 1.1 Projective quotients and all integer twists"; cited by PR #2413 §1.2 and its supplier contract.

### §4.1 IsGerbe and relative gerbes
- Status: NOT-STARTED (grep `IsGerbe|relativeGerbe` empty; the `TrivialGerbe` files in Geometry/Manifold/Etale/ and Topology/CategoryTheory/Groupoid/Effective/ are topological groupoid gerbes, unrelated)
- Ready now: yes (Needs only Mathlib `Pseudofunctor.IsStack`, `IsPrestack`, `Aut`)
- Serves defs: 29
- Evidence: README l.1862 "### 4.1 Gerbes and relative locality" ("Define `IsGerbe`. For `F : C`ᵒᵖ → Cat a pseudofunctor ..."); PR #2429's supplier contract cites §4.1 `IsGerbe`, `relativeGerbe`, `relativePullback`, `relativeComposition`, `relativeDescent` for its Layer 2.

## TauCetiRoadmap/SmoothBundlesConnections
STATUS.md snapshot: d137fc6 2026-11-09 (to Tau Ceti d92acc5; Tau Ceti checked at 7cbfff3ef, 2026-11-16)

### B1.4 Slices, quotients and homogeneous spaces G/H
- Status: PARTIAL: the free proper quotient theorem is in code: for a finite-dimensional real Lie group acting smoothly, freely and properly on a boundaryless manifold, `M ⧸ G` is a manifold of dimension `dim M − dim G` (`ProperSMul.orbitRelQuotientChartedSpace`, `instIsManifoldOrbitRelQuotient`) and the orbit map is a smooth submersion (`isSubmersion_quotientMk`, `ker_mfderiv_quotientMk`), Geometry/Manifold/GroupAction/Quotient.lean. Its inputs: orbit-space charts from transverse slices (`TauCeti.MulAction.isOpenEmbedding_quotientMk_slice`, `TauCeti.exists_contMDiffAt_quotientMk_slice_eq_iff`, GroupAction/SliceChart.lean), transverse slice maps as local diffeomorphisms (`isLocalDiffeomorphAt_smul_slice_iff`, GroupAction/TransverseSlice.lean), orbit maps of free points as closed smooth embeddings (`isSmoothEmbedding_smul_const`, GroupAction/Orbit.lean), compact stabilizers and closed orbits of proper actions (Topology/Algebra/ProperAction/Orbit.lean), Haar-averaged invariant metrics (Geometry/Manifold/Riemannian/Invariant.lean), equivariant charts for finite groups (GroupAction/Linearization.lean), and smooth functions on orbit spaces (GroupAction/SmoothFunctions.lean, Geometry/Manifold/Quotient/). Missing: the compact-isotropy equivariant exponential chart and slice theorem `G ×_H B`, and smooth G/H for a closed subgroup H as a named construction (its inputs are in code: the free proper quotient theorem and Cartan's closed-subgroup theorem `isEmbeddedLieSubgroup_of_isClosed`, Geometry/Lie/Subgroup/Embedded.lean)
- Ready now: yes for the slice theorem and for G/H, both on the free proper quotient theorem
- Serves defs: 62, 15, 31 (through RealSemisimpleLieGroups §§5.2, 5.7)
- Evidence: README l.421 "### B1.4 Slices, quotients and homogeneous spaces", l.432 "Prove the free proper quotient theorem first by transverse local charts and properness"; *Needs* l.490

### B2 pullback connection (as cited)
- Status: B2.1 (pullback/Hom/associated bundles) is PARTIAL: smooth associated bundles and complexification exist. B2 has no connection content
- Ready now: n/a (see R5a)
- Serves defs: 49
- Evidence: README l.559 "### B2.1 Associated bundles and complex structures" constructs pullback, tensor, dual and Hom bundles only; connection pullback is in B3.1 l.879 ("smoothness, pullback, restriction") and B3.3 l.948 for principal/associated connections

### B3–B4 Principal connections, curvature, gauge group
- Status: NOT-STARTED (Layers 3–7 "untouched"; no principal connections, curvature or gauge group in code; the gauge code is the U(1) vortex theory on ℂ, Analysis/PDE/Vortex/, unrelated). Inputs that exist: the orthonormal (unitary) frame bundle of a metric vector bundle as a topological principal `O(n)`/`U(n)` bundle `TauCeti.OrthonormalFrameBundle.Fiber` with proper projection (Topology/VectorBundle/OrthonormalFrame/{Principal,Basic}.lean), and the splitting of the first-jet sequence by a vector-bundle connection (Geometry/Manifold/VectorBundle/FirstJet/Connection.lean)
- Ready now: no: B3.1 needs B1.5 (Ehresmann connections, not in code) and B2.5 (smooth GL frame bundles, reductions and ad(P); only the topological orthonormal frame bundle exists); B4 needs B3.1–B3.3
- Serves defs: 37, 48 (consumed by YangMillsConnectionsAndCaloricGauge §1.3)
- Evidence: README l.871 "### B3.1 Principal connections" (*Needs* l.904 "B1.5, B2.5; DifferentialGeometry Layer 0, Layer 1; LieGroups Layer 1"), l.979 "### B4.1 Curvature and the exterior covariant derivative", l.1010 "### B4.2 The gauge group"; STATUS coverage Layer 3/4 "state":"untouched"

## TauCetiRoadmap/YangMillsConnectionsAndCaloricGauge
No STATUS.md; Tau Ceti checked at 7cbfff3ef, 2026-11-16 (grep `caloric`, `YangMills`, `instanton`: no hits). Its Tau Ceti suppliers are in code: `TauCeti.WeakDerivStep`, `TauCeti.D1p0` with `sobolevEmbeddingL`, `TauCeti.heatKernel`, the Mihlin–Hörmander theorem, the closed-subgroup theorem (`Geometry/Lie/Subgroup/`), `Ad`-invariant inner products (`TauCeti.Lie.exists_isSymm_bilinForm_Ad_invariant`, `Geometry/Lie/Adjoint/InvariantForm.lean`), `HomotopyGroup.bijective_hurewicz`, the smooth degree (`Geometry/Manifold/Degree/`).

### Layer 1 (§§1.1–1.6) Structure group, nearest-point retraction, gauge identities, invariant and Chern–Simons forms, self-duality
- Status: NOT-STARTED.
- Ready now: §1.1 yes (its *Needs* are Mathlib, the pinned Tau Ceti closed-subgroup declarations and LieGroups Layers 1, 5A, whose invariant metric is in code); §1.5 yes (Tau Ceti `Orientation.formHodgeStar`); §1.2 no: needs RiemannianGeometry R6's Euclidean tube inversion; §1.3 no: needs SmoothBundlesConnections B3.1, B4.1–B4.2 (untouched); §1.4 no: needs CharacteristicClasses C4 item 1 and C5a.3 (untouched).
- Serves defs: 37, 48
- Evidence: README l.490 "## Layer 1: structure groups and pointwise gauge algebra"; *Needs* l.521 (§1.1), l.568 (§1.2 "RiemannianGeometry R6"), l.600 (§1.3 "SmoothBundlesConnections B3.1, B4.1, B4.2"), l.648 (§1.4 "CharacteristicClasses C4 item 1 and C5a.3").

### Layers 2–3 (§§2.1–2.5, 3.1–3.4) `G^{k,p}_loc`, rough connections, gauge invariance of finite energy
- Status: NOT-STARTED (order-one vector-valued `W^{1,p}` is `TauCeti.WeakDerivStep`; no `G`-valued classes).
- Ready now: no: §2.1 needs PDE gap `vector-valued-wkp` (orders `k ≥ 2` and local classes of `W^{k,p}(Ω; V)`, requested of PDE Layer 1 in the Exact supplier contracts) and §1.1; §2.2 needs §1.2; §3.2 needs §1.3.
- Serves defs: 48 (48.1), 37
- Evidence: README l.739 "## Layer 2: critical Sobolev maps into `G`", l.905 "## Layer 3: rough connections and gauge invariance"; *Needs* "Tau Ceti `TauCeti.WeakDerivStep`; gap `vector-valued-wkp` (PDE)", l.951 "1.3, 2.4, 3.1"; gap text l.394 "What PDE must provide (gap:vector-valued-wkp)".

### Layers 4–6 (§§4.1–4.4, 5.1–5.6, 6.1–6.4) Uhlenbeck gauges, good global gauge, `Top(d, G)`, characteristic numbers, `SU(2)` instanton number
- Status: NOT-STARTED.
- Ready now: no: §4.1 needs PDE gaps `lp-neumann-ball` and `lp-divcurl-normal-ball`; §§5.2, 5.3, 6.1 need PDE gap `hardy-inequality`; all need Layers 2–3; §6.4 also needs AlgebraicTopology §§6.5, 8.3 (Hurewicz in code).
- Serves defs: 48 (48.2–48.5), 37
- Evidence: README l.1020 "## Layer 4: Uhlenbeck's lemmas and the good gauge on a ball", l.1192 "## Layer 5: the good global gauge and the topological class", l.1294 "### 5.4 The topological class, the trivial class and `Top(4, G) ≅ π₃(G)`", l.1376 "## Layer 6: characteristic numbers and the instanton number", l.1452 "### 6.4 The instanton number for `SU(2)`"; *Needs* l.1057, l.1260, l.1334, l.1506.

### Layer 7 (§§7.1–7.7) Harmonic Yang–Mills connections, energy gap, BPST, ground state
- Status: NOT-STARTED.
- Ready now: no: needs Layers 4–6, Yamabe Y2 item 1 (sharp Sobolev inequality `sphereYamabeConstant_mul_le`, not in code; `TauCeti.Yamabe.sphereYamabeConstant` is) for §7.5, and the LieGroups gap `compact-su2-subalgebra` for §7.7.
- Serves defs: 37 (§§9.6–9.7 and §10.2 consume §7.7)
- Evidence: README l.1520 "## Layer 7: harmonic Yang–Mills connections and the ground state"; *Needs* l.1631 "Yamabe Y2 item 1; 6.3, 7.3, 7.4", l.1686 "gap `compact-su2-subalgebra` (LieGroups); 1.6, 7.5, 7.6".

### Layers 8–10 (§§8.1–8.4, 9.1–9.7, 10.1–10.5) Homogeneous spaces on `ℝ⁴`, Yang–Mills heat flow, caloric gauge and caloric manifold
- Status: NOT-STARTED (only inhomogeneous Littlewood–Paley blocks and Besov spaces in code; `TauCeti.D1p0` supplies `Ḣ¹(ℝ⁴)`).
- Ready now: no: §8.1 needs PDE §7.1–7.2's homogeneous blocks and homogeneous Besov spaces (PDE Layer 7 partial, not in code) on `TauCeti.D1p0` (in code); §9.1 needs §1.3; §§9.6–9.7 need Layers 4, 6–7; Layer 10 needs Layer 9 and Layers 3–4.
- Serves defs: 37
- Evidence: README l.1697 "## Layer 8: homogeneous spaces and linear covariant flows on `ℝ⁴`", l.2038 "## Layer 9: the Yang–Mills heat flow on `ℝ⁴`", l.2303 "## Layer 10: the caloric gauge and the caloric manifold"; *Needs* l.1880, l.2082, l.2390, l.2424, l.2526; build order l.486–488.

New items in other sections:

## TauCetiRoadmap/GeometricCurrents
STATUS.md snapshot: 941bb58 2026-11-12 (Tau Ceti checked at 7cbfff3ef, 2026-11-16)

### G1–G2 Mass and pushforward of Lipschitz images
- Status: PARTIAL, Euclidean only: mass/local mass (Analysis/Distribution/Mass/Basic.lean), the Radon mass measure (Mass/Measure.lean), L¹ extension and Borel restriction (Mass/Extension.lean), normal currents (Mass/Normal.lean), weak compactness (Mass/Compactness.lean), smooth pushforward of compactly supported currents (Analysis/Distribution/CutoffPushforward.lean), integration and simplex currents, the cone operator with mass bounds (Mass/Cone.lean), slicing of locally normal currents by a smooth function (Mass/Slice.lean). Missing: the manifold `TestForm`/`Current` carrier, integer-rectifiable currents, Lipschitz pushforward (G2)
- Ready now: no for the manifold carrier: G1 needs K5a's early `BundleTest` (CKG 5.1, missing), Calib C1 comass and HopfRinow L0. G2 needs GMT G2–6 (G2 lacks tangent-plane uniqueness and the tangential area formula) and CalibratedGeometry C2. A Euclidean Lipschitz pushforward could start on the existing Euclidean carrier
- Serves defs: 57
- Evidence: README l.137 "## G1. Test forms, currents and mass", l.240 "## G2. Integer rectifiability, integration, pushforward and slicing", l.298 "Extend pushforward to locally Lipschitz maps"; dependency graph l.964-966; STATUS "The Euclidean half of G1 is essentially complete ... Nothing yet lives on a manifold, there are no integer-rectifiable or integral currents, and G3 and G4b–G7 have not begun"

### G3 Lipschitz singular subcomplex
- Status: NOT-STARTED (grep for a Lipschitz singular complex: no hits)
- Ready now: no: needs G2, G4a, Calib C2, AT/GT
- Serves defs: 57
- Evidence: README l.406 "## G3. Ordinary integral-current homology and chain comparisons", l.434 "A Lipschitz singular ..."; dependency graph l.967 "`{G2, G4a, Calib C2, AT/GT, DGF0 adapter} → G3`"

### G6 Varifolds of currents, first variation, monotonicity
- Status: NOT-STARTED (no varifold or Grassmann-bundle code)
- Ready now: no: needs G4b, G5, R5a/R5b, GMT perimeter, PDE strong-solution upgrades, Calib C1/TopK T1.5
- Serves defs: 53, 65
- Evidence: README l.668 "## G6. First variation, normal stability and interior regularity", l.679 "Give the auxiliary rectifiable varifold's restriction, weight, integer multiplicity ...", l.688 "Develop density, monotonicity"; dependency graph l.973

## TauCetiRoadmap/GeometricMeasureTheory
STATUS.md snapshot: 59c8654 2026-11-16, generated against Tau Ceti aa6e43e (Tau Ceti checked at 7cbfff3ef, 2026-11-16)

### G2 Rectifiable sets, approximate tangents, area formula
- Status: PARTIAL: `CountablyRectifiable`, the density theorem, a.e. existence of approximate tangent planes (Geometry/MeasureTheory/Rectifiable/ApproximateTangent.lean) and a measurable choice of tangent projections (Rectifiable/MeasurableTangent.lean), and the cone condition for the classical tangent plane of a differentiable normal graph (Rectifiable/Graph.lean). The Lipschitz area formula ℝᵐ→ℝⁿ with multiplicity is in MeasureTheory/Function/AreaFormula/{Basic,Lipschitz,Multiplicity}.lean, and the coarea formula for locally Lipschitz maps with a.e. countably rectifiable fibres is in MeasureTheory/Function/Coarea/Lipschitz.lean and Geometry/MeasureTheory/Rectifiable/Coarea.lean. Missing: a.e. uniqueness of tangent planes, tangential differentiation, and the tangential area formula on rectifiable sets
- Ready now: yes
- Serves defs: 53, 57
- Evidence: README l.148 "## G2: Rectifiability, area, and coarea"; STATUS coverage G2 remaining "a.e. uniqueness of approximate tangent planes, tangential differentiation of Lipschitz maps, the tangential area formula"

### G5 De Giorgi structure theorem
- Status: PARTIAL: perimeter API, essential and reduced boundaries, outer normal, density estimates, the `|Dχ| ≤ nω_n Hⁿ⁻¹` bound, blow-ups with the density of the perimeter measure at reduced-boundary points (`tendsto_perimeter_ball_div`, Analysis/BoundedVariation/BlowUp.lean), and slicing of perimeters. Missing: De Giorgi's theorem itself (rectifiability of ∂*E, `|Dχ_E| = Hⁿ⁻¹⌞∂*E`), the essential/reduced comparison, and the frontier criterion
- Ready now: yes (G3–G4 are essentially done; the needed G2 rectifiability API exists)
- Serves defs: 55
- Evidence: README l.248 "## G5: Finite perimeter and boundary structure", "Prove ... De Giorgi's structure theorem"; STATUS coverage G5 remaining "rectifiability of the reduced boundary, perimeter measure as Hn-1 on it, essential/reduced boundary comparison, frontier criterion"

## TauCetiRoadmap/CStarAlgebras
STATUS.md snapshot: 3930ad9 2026-11-11 (Tau Ceti checked at 7cbfff3ef, 2026-11-16; stale on C3.2 and C4.1). The CStarAlgebras items also feed merged AmenableTracesOnCStarAlgebras, which specifies #36.

### C2.1 State extension
- Status: PARTIAL: the unital case is in code: along an injective unital star homomorphism every state extends (`TauCeti.surjOn_pullbackFunctional_stateSpace`), and every state of a closed unital star subalgebra is the restriction of a state (`StarSubalgebra.exists_mem_stateSpace_forall_apply_coe_eq`), TauCeti/Analysis/CStarAlgebra/State/Extension.lean, on the state space API of TauCeti/Analysis/CStarAlgebra/State/Space.lean. Missing: pure extensions of pure states (the face of extensions), functorial restriction, the nonunital case.
- Ready now: yes for pure extensions (Krein–Milman `closure_convexHull_extremePoints_stateSpace` exists); the nonunital case goes through C1.2 unitization, which STATUS lists as remaining in Layer 1.
- Serves defs: 36
- Evidence: README l.544 "### 2.1 State extension (C2.1)" ("Prove that every pure state has a pure extension ... Include functorial restriction and the nonunital case through the unitizations"), *Needs* "BanachSpaceTheory B1–B2; VonNeumannAlgebras V0"; Tau Ceti commit 4c2e91858 (#37569).

### C3.2 Completely bounded maps
- Status: PARTIAL: at the C*-algebra level (operator-space structure through `CStarMatrix`) `LinearMap.IsCompletelyBounded` and `LinearMap.cbNorm` with `norm_map_le_cbNorm_mul`, `cbNorm_le_iff`, the norm laws (`cbNorm_add_le`, `cbNorm_smul`, `cbNorm_eq_zero_iff`), `cbNorm_comp_le`, `cbNorm_id`, `NonUnitalStarAlgHom.cbNorm_le_one` and the transpose example `CStarMatrix.cbNorm_transposeₗ` (cb norm `n`), TauCeti/Analysis/CStarAlgebra/CompletelyBounded.lean (Tau Ceti #38429). Missing: abstract operator spaces (C3.1), `CB(E, F)` as a normed space with completeness, the matrix-norm structure on `CB(E, F)` and `E*`, `E → E**` completely isometric, Smith's lemma.
- Ready now: yes for the C*-level remainder (completeness of the cb maps between C*-algebras, Smith's lemma for C*-algebra domains, `‖u‖_cb = ‖u‖` for functionals); the operator-space parts need C3.1 (not started).
- Serves defs: 36, 46
- Evidence: README l.918 "### 3.2 Completely bounded maps (C3.2)" ("`Suggested.lean` defines complete boundedness of a linear map between C*-algebras as `IsCompletelyBounded`"), *Needs* "§3.1; BanachSpaceTheory B1"; PR #2421 §1.4 compares its Schatten amplification norm with C3.2.

### C3.3 / C5.3 Column/row, MIN/MAX; operator-space tensor products
- Status: NOT-STARTED.
- Ready now: no: C3.3 needs C3.1–3.2; C5.3 needs §3.1–3.3 and §4.4 (Wittstock).
- Serves defs: 36, 46
- Evidence: README l.948 "### 3.3 Column and row spaces, MIN and MAX, operator algebras (C3.3)"; l.1169 "### 5.3 Operator-space tensor products (C5.3)", *Needs* "§3.1–§3.3, §4.4"; grep `OperatorSpace|Ruan` only unrelated hits.

### C4.1 Completely positive maps, Schwarz, multiplicative domain
- Status: PARTIAL: `n`-positivity `TauCeti.IsNPositive` with `CompletelyPositiveMap.ofIsNPositive`; the Kadison–Schwarz inequality `IsNPositive.star_map_mul_map_le` (`φ(a)*φ(a) ≤ ‖φ 1‖ • φ(a*a)` for 2-positive maps) and `IsNPositive.star_map_mul_map_le_of_map_one` (unital), `CompletelyPositiveMapClass.star_map_mul_map_le`; `‖φ a‖ ≤ ‖φ 1‖‖a‖` and `‖φ‖ = ‖φ 1‖` (`IsNPositive.opNorm_eq_norm_map_one`, `CompletelyPositiveMapClass.opNorm_ofClass_eq_norm_map_one`), TauCeti/Analysis/CStarAlgebra/CompletelyPositiveMap.lean (Tau Ceti #38424). Missing: `‖φ‖_cb = ‖φ(1)‖`, the approximate-unit formula and unitization of c.p.c. maps, complete positivity of positive maps with commutative domain or range, the multiplicative domain and bimodularity.
- Ready now: yes for `‖φ‖_cb = ‖φ(1)‖` (C3.2's C*-level `cbNorm` exists), the unitization of c.p.c. maps (used by AmenableTracesOnCStarAlgebras §2.1) and the commutative domain/range theorems; the multiplicative domain by the README's dilation route needs C4.2 (not started).
- Serves defs: 36
- Evidence: README l.986 "### 4.1 Completely positive maps, Schwarz and the multiplicative domain (C4.1)", *Needs* "VonNeumannAlgebras V13a; Mathlib `CompletelyPositiveMap`, `CStarMatrix`; §4.2 for the dilation route"; grep `multiplicativeDomain` empty.

### C4.2 Stinespring dilation and Arveson's Radon–Nikodym theorem
- Status: NOT-STARTED (grep `Stinespring`: no hits). Inputs present: GNS and the Gelfand–Naimark faithful representation `exists_faithful_nondegenerate_representation` (TauCeti/Analysis/CStarAlgebra/Representation/GNS.lean), Mathlib `CStarAlgebra.approximateUnit`.
- Ready now: yes for unital domains (*Needs* VonNeumannAlgebras V0 GNS, in code); the nonunital approximate-unit step cites §1.4, not started.
- Serves defs: 36 (AmenableTracesOnCStarAlgebras §2.2 multiplicativity defects, §4.5, and C4.1's multiplicative domain)
- Evidence: CStarAlgebras README l.1021 "### 4.2 Stinespring dilation and the Radon–Nikodym theorem (C4.2)", *Needs* "VonNeumannAlgebras V0 (GNS); ... §1.4 (approximate units)"; AmenableTracesOnCStarAlgebras README l.985 (§2.2 *Needs* "CStarAlgebras C4.1 ..., C4.2").

### C5.1–C5.2 C*-tensor products: minimal and maximal norms, tensoring maps and functionals
- Status: NOT-STARTED.
- Ready now: no: C5.1 needs VonNeumannAlgebras V13b.SpatialNorm (Layer 13 untouched), V2 (partial) and §4.2; C5.2 needs §5.1 and V4.
- Serves defs: 36 (AmenableTracesOnCStarAlgebras §1.5 bimodule identification, §§3.5, 4.3–4.4)
- Evidence: CStarAlgebras README l.1112 "### 5.1 The maximal C*-norm and the comparison of C*-norms (C5.1)", l.1143 "### 5.2 Tensoring maps and functionals; concrete identifications (C5.2)"; AmenableTracesOnCStarAlgebras README l.1399 (§4.4 *Needs* "CStarAlgebras C4.1 (multiplicative domain), C5.1–C5.2").

### C5.4 Direct sums, products, inductive limits, C*(F_∞)
- Status: PARTIAL: bounded products and their `c₀` quotients are in code: `lp.inftyCStarAlgebra` (the bounded product of nonzero unital C*-algebras is a unital C*-algebra, TauCeti/Analysis/CStarAlgebra/BoundedProduct.lean), `lp.c0Ideal` closed and star-closed with quotient norm `limsup_i ‖a_i‖` (`lp.isClosed_c0Ideal`, `lp.star_mem_c0Ideal`, `lp.norm_mk_c0Ideal`, TauCeti/Analysis/Normed/Lp/C0Ideal.lean), so `∏ M_{k_n} / ⊕ M_{k_n}` is a C*-algebra. Missing: C*-inductive limits with their universal property and norm formula (needed for AF algebras), `c₀` direct sums as C*-algebras with universal properties, `C*(F_∞)`.
- Ready now: yes (*Needs* "Mathlib `lp`; §1.3 (ideals and quotients)"; quotient by closed ideal present).
- Serves defs: 36
- Evidence: README l.1203 "### 5.4 Direct sums, products, inductive limits and the universal unitary algebra (C5.4)"; Tau Ceti commit dcb25a745 (#37764); grep for C*-algebra `DirectLimit`/inductive limit in TauCeti/Analysis/CStarAlgebra: only a comment in QuantumSpin/Interaction.lean.

### C6.1–C6.2 Nuclear maps and nuclearity characterizations
- Status: NOT-STARTED (no `IsNuclearContraction`).
- Ready now: no: C6.1 needs C4.1 (the definition alone is statable on Mathlib `→CP`); C6.2 needs §5.1–5.2, §6.1, V13b, V1, V4.
- Serves defs: 36
- Evidence: README l.1272 "### 6.1 Nuclear maps and nuclear algebras (C6.1)" (*Needs* "§4.1"), l.1297 "### 6.2 The equivalent characterizations of nuclearity (C6.2)"; grep `IsNuclear` empty.

### C7.1 Exactness
- Status: NOT-STARTED.
- Ready now: no: needs §5.1–5.2, §6.1–6.2, §3.2, VonNeumannAlgebras V13b.SpatialNorm.
- Serves defs: 36
- Evidence: README l.1455 "### 7.1 Exactness (C7.1)"; grep empty.

## TauCetiRoadmap/AmenableTracesOnCStarAlgebras
No STATUS.md (merged as roadmap PR #2260; Tau Ceti checked at 7cbfff3ef, 2026-11-16). Grep `IsTracialState`, `matrixTwoNorm`, `IsAmenableTrace`, `IsHypertrace` in Tau Ceti: no hits.

### §§1.1–1.2 Tracial states, `T(A)`, the trace kernel and faithfulness
- Status: NOT-STARTED. Inputs present: `TauCeti.CStarAction.trivial`, `isKMSState_zero_iff`, `kmsStates` with `convex_kmsStates`, `isCompact_kmsStates` (TauCeti/Analysis/CStarAlgebra/Action/{Basic,KMS/Basic,KMS/StateSpace}.lean), `LinearMap.traceRadical`, Mathlib `PositiveLinearMap.GNS`.
- Ready now: yes (*Needs* VonNeumannAlgebras V0 states, whose state space and GNS are in code).
- Serves defs: 36
- Evidence: README l.503 "### 1.1 Tracial states and the tracial state space" (`IsTracialState` as the `0`-KMS condition of the trivial action), l.562 "### 1.2 The trace kernel, faithfulness and simplicity".

### §1.5 The normalized trace and 2-norm on matrix algebras
- Status: NOT-STARTED. Inputs present: `Matrix.frobeniusInnerProductSpace`, `Matrix.frobenius_inner_eq_trace_conjTranspose_mul` (TauCeti/Analysis/Matrix/Frobenius.lean), `LinearMap.existsUnique_trace_mul_eq`, `Matrix.mem_range_scalar_iff_trace_mul_mul_comm` (TauCeti/LinearAlgebra/Matrix/Trace/Duality.lean).
- Ready now: yes for `tr_k`, `matrixTwoNorm` and its inequalities, block and tensor laws; the bimodule identification `M_k ⊗ M_kᵒᵖ ≅ B(L²(M_k, tr_k))` needs CStarAlgebras C5.1 (not started).
- Serves defs: 36
- Evidence: README l.751 "### 1.5 The normalized trace and 2-norm on matrix algebras", *Needs* "§1.1; VonNeumannAlgebras V0, V3; CStarAlgebras C5.1 (uniqueness of the C*-norm on `M_n ⊙ A`)".

### §§2.1–2.2 Completely positive contractions into matrices, multiplicativity defects
- Status: NOT-STARTED.
- Ready now: no: §2.1 needs §1.5 and CStarAlgebras C4.1's unital extension of c.p.c. maps (missing; ready); §2.2 needs §2.1 and C4.2 Stinespring (not started).
- Serves defs: 36
- Evidence: README l.895 "### 2.1 Operations on completely positive contractions into matrices", *Needs* "§1.5; CStarAlgebras C4.1 (composition, unital extension, Kadison–Schwarz)"; l.963 "### 2.2 Multiplicativity defects and asymptotic multiplicative domains", *Needs* "§1.5, §2.1; CStarAlgebras C4.1, C4.2".

### §3.1, §3.2, §3.4 Amenable traces (Definition 36.3), nets, sequences and u.c.p. forms, pullback
- Status: NOT-STARTED.
- Ready now: no: §3.1 needs §§1.1–1.2 and §1.5 only; §3.2 needs §1.3, §1.6, §2.1 and C4.1's unital extension; §3.4 needs §§1.1–1.2, §3.1.
- Serves defs: 36 (§3.1 is the definition)
- Evidence: README l.1122 "### 3.1 The three approximation properties" (`IsAmenableTrace`, `AdmitsFaithfulAmenableTrace`), *Needs* "§1.1–§1.2, §1.5; Mathlib `CompletelyPositiveMap`, `CStarMatrix`"; l.1179 "### 3.2 Nets, sequences, unital maps and finite-dimensional approximants"; l.1248 "### 3.4 Pullback along star homomorphisms".

### §§4.1–4.4 Hypertraces and the Connes–Kirchberg theorem
- Status: NOT-STARTED.
- Ready now: no: §4.1 needs VonNeumannAlgebras V13a and CStarAlgebras C4.1's multiplicative domain; §4.4 needs §§1.4–1.5, 3.2, 4.1–4.3, CStarAlgebras C5.1–C5.2, VonNeumannAlgebras V13b.SpatialNorm.
- Serves defs: 36 (Prop 36.4(ii))
- Evidence: README l.1310 "### 4.1 Hypertraces and representation independence", l.1422 "### 4.4 The Connes–Kirchberg theorem", *Needs* l.1399 and l.1446.

### §§5.1–5.4 Nuclear maps, uniform amenable traces, nuclear and exact algebras
- Status: NOT-STARTED.
- Ready now: no: needs CStarAlgebras C6.1, C6.5, C7.1, C2.8, VonNeumannAlgebras V13a and §4.4, §4.6.
- Serves defs: 36 (Prop 36.4(iii))
- Evidence: README l.1702 "### 5.3 Nuclear C*-algebras", *Needs* "§3.2–§3.3, §5.1–§5.2; CStarAlgebras C6.1, C6.5"; l.1723 "### 5.4 Exact C*-algebras", *Needs* "§3.3, §4.4, §5.1–§5.2; CStarAlgebras C6.1, C7.1; VonNeumannAlgebras V13a".

### §7.2, §8.5 AF and UHF traces; subalgebras of simple unital AF algebras (Schafhauser)
- Status: NOT-STARTED.
- Ready now: no: §8.5 needs §1.2, §3.4, §6.3, §7.2, CStarAlgebras C6.5, C7.1, CStarClassification CL2; §7.2 needs CStarAlgebras C2.1 and CL2 (C*-inductive limits of C5.4 not in code).
- Serves defs: 36 (the cited paper's application)
- Evidence: README l.1981 "### 7.2 AF and UHF algebras", l.2272 "### 8.5 Subalgebras of simple unital AF algebras" (`subalgebra_isAF_simple`).

## TauCetiRoadmap/DerivedModuleAlgebra
STATUS.md snapshot: d9fbe7b 2026-11-11 (Tau Ceti checked at 7cbfff3ef, 2026-11-16)

### §0.4 The full cotangent complex and §0.8 transitivity triangle
- Status: NOT-STARTED. `Algebra.CotangentComplex` is absent. Only Mathlib's naive `Extension.cotangentComplex` is used. Inputs: the standard polynomial resolution stages and their varying-base maps exist (Algebra/Category/CommAlgCat/PolynomialResolution/{Basic,Map,Simplicial}.lean), but the resolution property does not.
- Ready now: no. §0.4 needs §0.1 (resolution property and the Lπ_! comparison missing) and §0.2 (derived tensor bifunctor and base-change adjunction missing; K-flat models exist). §0.8 needs §§0.4, 0.6 and 0.2.
- Serves defs: 27
- Evidence: README l.1271 "### 0.4 The full cotangent complex" (signature `Algebra.CotangentComplex (A B) : DerivedCategory (ModuleCat B)`); l.1463 "### 0.8 The cotangent transitivity triangle". STATUS Layer 2 remaining: "the full cotangent complex (§0.4) and everything built on it, §§0.6–0.25". Layer 1 remaining: "the derived tensor bifunctor and base-change adjunction, resolution comparison of §0.1 ...".

### §1.3 derived completion; §1.7 I-completely flat
- Status: NOT-STARTED for these sections; their input §1.2 is done. §1.2 in code: `TauCeti.derivedComplete` in D(A), the radical ideal `derivedCompleteIdeal`, generator and radical invariance, the module telescope criterion `TauCeti.IsDerivedComplete`, and the cohomology criterion `TauCeti.derivedComplete_iff_isDerivedComplete_homology` (every `Hⁿ(M)` derived complete, Stacks 091T), with closure under products, shifts and cones (RingTheory/AdicCompletion/DerivedComplete.lean, .../DerivedComplete/Module.lean). No `derivedCompletion` or `completeFlatness` in code.
- Ready now: §1.3: no, needs §1.1.1 derived Hom with the tensor–Hom adjunction (`derivedHom` exists, adjunction remaining). §1.7: no, needs §0.2's derived tensor bifunctor.
- Serves defs: 81
- Evidence: README l.2024 "### 1.2 Derived ideal completeness", l.2064 "### 1.3 The derived completion reflector", l.2359 "### 1.7 Complete flatness and complete faithful flatness". STATUS Layer 3 remaining (stale on the cohomology criterion, which is in code): "exactness of the derived limit, tensor–Hom adjunction, cohomology criterion for completeness, §§1.3–1.9".

## TauCetiRoadmap/EnhancedDerivedSheaves
STATUS.md snapshot: 385ec2d 2026-11-06 (Tau Ceti checked at 7cbfff3ef, 2026-11-16)

### §0.3 Derived tensor and internal Hom `ClassicalDerived.tensorHom` (with §0.4 functorCoherence)
- Status: PARTIAL, inputs only. The K-flat half of §0.2 exists: every unbounded complex of sheaves of modules has a K-flat resolution by flat terms (`CochainComplex.exists_quasiIso_isKFlat_sheafOfModules`, Algebra/Category/ModuleCat/Sheaf/TensorProduct/KFlat.lean). Tensoring with a fixed K-flat complex descends to the derived category (`CochainComplex.kFlatTensor`, Algebra/Homology/Monoidal/KFlat/DerivedTensor.lean). Missing: the derived tensor bifunctor on sheaves, internal RHom, the tensor–Hom adjunction, K-injective replacement on ringed sites, the enhanced category (§0.1) and all of §0.4.
- Ready now: no, as the README specifies it. §0.3 needs §§0.1–0.2, i.e. the enhanced category via the dg nerve, which needs E0.6 shift/cone comparison and E0.8 presentability, both remaining. A homotopy-category-level ⊗ᴸ on `DerivedCategory (SheafOfModules R)` from the existing K-flat resolutions could start now as a substep.
- Serves defs: 18
- Evidence: README l.455 "### 0.3 Tensor, internal Hom and derived limits" ("provide `ClassicalDerived.tensorHom`: K-flat replacement defines `⊗ᴸ_R` ..."). README l.492 "### 0.4 Coherent derived functors". STATUS Layer 0 remaining: "K-injective replacement on ringed sites, the enhanced module-sheaf category, derived tensor-Hom, derived limits, completion comparison, functor coherence".

### Layer E5:cotangent-export The cotangent complex of animated rings
- Status: NOT-STARTED. No `squareZeroExtension` (animated), `derivedDerivations` or animated `cotangentComplex`.
- Ready now: no. Needs E5:animation (`animatedAlgebras`, `animatedModules`, `animationExtension`, `animatedPushout`; untouched) and DerivedModuleAlgebra §§0.4–0.13 (not started).
- Serves defs: 27
- Evidence: README l.2865 "## Layer E5:cotangent-export: The cotangent complex of animated rings". STATUS coverage: "Layer E5 ... untouched".

## TauCetiRoadmap/GeometricTopology
STATUS.md snapshot: 7bb61fc 2026-11-16, generated against Tau Ceti aa6e43e (Tau Ceti checked at 7cbfff3ef, 2026-11-16)

### Layer 1.1 Smooth collars
- Status: PARTIAL: `TauCeti.SmoothCollar` (a `C^k` injective local diffeomorphism `∂M × [0, 1) → M` with zero slice the boundary inclusion) with `isOpenEmbedding`, `opensRange`, `diffeomorphOpensRange`, `reparam`, `isCollar`/`isCollared`, `ofIsEmpty` (Geometry/Manifold/Boundary/Collar/Smooth.lean); local smooth product collars `IsProductCollarChart.diffeomorphProd` (Collar/Diffeomorph.lean); topological collars. Missing: the existence theorem (Collar/Diffeomorph.lean's docstring: the global theorem "still requires patching these local diffeomorphisms along the whole boundary"), uniqueness up to isotopy, the interior as a boundaryless manifold.
- Ready now: yes (existence by patching the local `diffeomorphProd`, or by flowing an inward field).
- Serves defs: 66 (through PR #2451 §§3.3–3.5)
- Evidence: README l.788 "### 1.1 Smooth collars"; STATUS coverage Layer 1 remaining "general boundary collars, gluing along boundary pieces, handle attachment and embeddings of all compact surfaces in R^4"; grep `SmoothCollar`: only Collar/Smooth.lean, no existence statement.

### 1.3 Gluing along the boundary, the double, handle attachment
- Status: NOT-STARTED. Inputs in code: compatible open gluing of manifolds (`TopCat.GlueData.IsCompatible.isManifold`, Geometry/Manifold/Gluing/GlueData.lean) and the double of a charted space along an open subset (`TauCeti.isCompatible_doubleGlueData`, Gluing/Double.lean). No gluing of manifolds with boundary through collars, no double `M ∪_id M`, no handle attachment.
- Ready now: no: needs 1.1's smooth collar existence (partial) and 1.2 (complements of embedded balls).
- Serves defs: 66 (the double, through open PR #2451 Layer 3), 59 (1.7 needs 1.3)
- Evidence: README l.851 "### 1.3 Gluing along the boundary and handle attachment" ("The double `M ∪_id M` is a boundaryless manifold containing `M` ..."; *Needs* "Tau Ceti `TauCeti.chartedSpaceOfIsOpenEmbedding`, `TauCeti.SmoothEmbedding`; Layer 1.1, Layer 1.2; DifferentialGeometry *Boundary and corners*"); STATUS coverage Layer 1 remaining "... gluing along boundary pieces, handle attachment ...".

### 1.7 / 1.7.2 Compact smooth surfaces, Mod(F)
- Status: PARTIAL: the mapping class group is in code, in every dimension: `TauCeti.MappingClassGroup I M` = `Diff(M, ∂M)` modulo the path component of the identity for compact `M`, with `mk`, `mk_eq_mk_iff`, `lift`, `mk_final_eq_one` and `Mod⁺` as `MappingClassGroup.orientationPreserving` (Geometry/Diffeomorphism/MappingClassGroup.lean), on `TauCeti.RelativeDiff` (Geometry/Diffeomorphism/FixingSubgroup/Basic.lean) and `TauCeti.Diffeotopy`. Missing: compact smooth surfaces (1.7), Dehn twists (the `DehnTwist` hits are group-theoretic HNN/pushout and limit-group files), `Mod(T²) ≅ GL₂(ℤ)`, Lickorish generation
- Ready now: no: the 1.7.2 theorems need 1.7, and 1.7 needs Layer 11.2.1 (partial), 1.2, 1.3 (missing), 1.3.1, 1.4 and 11.3
- Serves defs: 59
- Evidence: README l.1049 "### 1.7 Compact smooth surfaces" (*Needs* l.1096), l.1212 "### 1.7.2 Mapping class groups of compact surfaces and Dehn twists" (*Needs* l.1279 "Layer 1.5 ..., Layer 1.7 ..., Layer 3.1 ..., Layer 3.3 ..., Layer 3.4")

## TauCetiRoadmap/OperatorTheory/SelfAdjointSpectralTheory
STATUS.md snapshot: ad0502e 2026-11-16 (umbrella OperatorTheory/STATUS.md, generated against Tau Ceti aa6e43e; Tau Ceti checked at 7cbfff3ef, 2026-11-16)

### SA-E01, SA-E03–E07 Spectral PVM of an unbounded self-adjoint operator, projections, resolvent formula
- Status: NOT-STARTED (no `ProjValMeasure ℝ` built from a `LinearPMap`). Inputs present: unitary Cayley transform `IsSelfAdjoint.cayley_mem_unitary` (Analysis/InnerProductSpace/LinearPMap/Cayley.lean), bounded normal `ContinuousLinearMap.spectralPVM` (Analysis/InnerProductSpace/BorelCalculus/Basic.lean), reindexing `ProjValMeasure.map` (ProjValMeasure/Map.lean), resolvent API (LinearPMap/Resolvent.lean).
- Ready now: yes (Part D done, Part B PVM/Borel calculus and SA-B25 present; SA-E02 zero mass at 1 must be proved first). SA-E09 later needs Part C SA-C12–19 (Part C partial).
- Serves defs: 35, 45
- Evidence: README l.1202 "SA-E01: Spectral PVM of an unbounded self-adjoint operator", l.1208–1215 SA-E03..E07; STATUS Part E remaining "the unbounded spectral PVM, resolvent formula, generated group and Stone uniqueness"; Suggested.lean l.692 `spectralPVM (hA : IsSelfAdjoint A) : ProjValMeasure ℝ H := sorry`.

## TauCetiRoadmap/OperatorTheory/UnboundedOperators
Umbrella OperatorTheory/STATUS.md ad0502e 2026-11-16 lists all six UnboundedOperators layers as untouched; Tau Ceti checked at 7cbfff3ef, 2026-11-16. Only the scalar-measure step of UO-C03 is in code (below): grep for `exists_spectralType_decomposition`, `essentialSpectrum`, `discreteSpectrum`, `existsUnique_maximal_multiplier`, Friedrichs/closed forms in TauCeti: no hits.

### UO-A01 (§1.1) Unbounded spectral integral
- Status: NOT-STARTED. Inputs present: `TauCeti.ProjValMeasure` with integral and diagonal measures (Analysis/InnerProductSpace/ProjValMeasure/, BorelCalculus/DiagonalMeasure.lean).
- Ready now: partly: the PVM-side construction uses only Tau Ceti's `ProjValMeasure` API; the cited HilbertModules H6 graph-closure API is not started (Mathlib's `LinearPMap.closure` covers the Hilbert-space case).
- Serves defs: 35
- Evidence: README l.241 "### 1.1 Spectral-integral domain and action (UO-A01)", *Needs* l.245 "Tau Ceti's `TauCeti.ProjValMeasure` API ...; HilbertModules H6 graph closure".

### UO-C01, UO-C03 (§3.1, §3.3) Spectral projections and the pp/ac/sc decomposition
- Status: PARTIAL: UO-C03's scalar-measure step is in code: the unique split of an s-finite measure into atomic, absolutely continuous and singular continuous parts relative to a reference measure without atoms, `MeasureTheory.Measure.atomicPart_add_withDensity_rnDeriv_add_singularContinuousPart`, its uniqueness, and `not_isAtom_singularContinuousPart` (MeasureTheory/Measure/Decomposition/SingularContinuous.lean, on `atomicPart` in Decomposition/Atomic.lean). Missing: UO-C01, and the subspaces `H_pp`, `H_ac`, `H_sc` of a PVM with `exists_spectralType_decomposition`.
- Ready now: no: §3.1 needs §1.1, §1.5, §1.6; §3.3 needs §1.1, §3.1, SelfAdjointSpectralTheory SA-E06–E07 (not started, after SA-E01) and VonNeumannAlgebras V2.
- Serves defs: 35 (UO-C03 is its target), 45 (to state the paper's a.c. spectrum)
- Evidence: README l.523 "### 3.1 Approximate eigenvectors and spectral projections (UO-C01)", l.552 "### 3.3 Pure-point/absolutely-continuous/singular decomposition (UO-C03)" (headline `exists_spectralType_decomposition`).

### UO-C02 (§3.2) Essential and discrete spectrum
- Status: NOT-STARTED.
- Ready now: no: needs §3.1, HilbertModules H6 closed range (not started), OperatorKTheory §8.4 for the bounded comparison.
- Serves defs: 40
- Evidence: README l.533 "### 3.2 Essential spectrum (UO-C02)" (`discreteSpectrum`, `essentialSpectrum`, `notMem_essentialSpectrum_iff`).

### UO-D06 (§4.7) Closed forms and the Friedrichs extension
- Status: NOT-STARTED. Inputs present: Mathlib Lax–Milgram (`IsCoercive.continuousLinearEquivOfBilin`); Tau Ceti's Dirichlet realization `TauCeti.PDE.dirichletOperator` (Analysis/PDE/Spectrum/Operator.lean) is a concrete instance built from a coercive form.
- Ready now: yes for the form representation theorem over `RCLike` (its *Needs* are Mathlib and Tau Ceti's complexification); square roots need §1.1–§1.3 and SA-E01, and the real case GeneralizedCohomology G5.5-RealHilbert.
- Serves defs: 40 (and VariationalMethods Layer 2, on the chain of 34)
- Evidence: README l.703 "### 4.7 Closed forms and the Friedrichs extension (UO-D06)", *Needs* l.819.

### UO-A07, UO-E04–E06 (§1.7, §§5.4–5.7) Maximal multipliers, Kato–Rellich, cores, the free Laplacian on ℝ³
- Status: NOT-STARTED. Inputs present: Kato–Rellich `IsSelfAdjoint.add_of_isRelativelyBounded` (SA-C55), bounded multiplication operators on `Lᵖ` (MeasureTheory/Function/Lp/Multiplication.lean, Analysis/Semigroups/Multiplication/).
- Ready now: yes for UO-A07's existence and self-adjointness headline `existsUnique_maximal_multiplier` (Mathlib `Lp`, `MemLp`; the V10 cyclic-model comparison and intertwining identities wait on V10 and §1.1–§1.3); UO-E06 needs §5.4 and §5.6, which need §3.2 and §5.1–§5.3.
- Serves defs: 45 (UO-E06 specifies it for d = 3 only; the free Laplacian on ℝ^d is UO-A07 conjugated by the Fourier transform)
- Evidence: README l.309 "### 1.7 Multiplier model (UO-A07)", l.983 "### 5.4 Kato–Rellich and relatively compact perturbations (UO-E04)", l.1033 "### 5.7 Three-dimensional L²+L∞ potentials (UO-E06)" ("This is an ℝ³ theorem ... the statement is not extended to ℝⁿ").

## TauCetiRoadmap/VariationalMethods
No STATUS.md; Tau Ceti checked at 7cbfff3ef, 2026-11-16 (grep `CompactFormPair`, `rayleighMinMax`: no hits).

### §3.1, §§4.1–4.4 Compact form pairs, successive minima, Courant–Fischer on the form domain
- Status: NOT-STARTED. Inputs present: Courant–Fischer for compact self-adjoint operators (Analysis/InnerProductSpace/CourantFischer.lean), Rayleigh quotients and variational spectrum (Analysis/InnerProductSpace/Variational/{Rayleigh,Spectrum}.lean), direct method (Analysis/Variational/DirectMethod.lean).
- Ready now: no: Layer 3 needs Layers 1–2, and Layer 2 consumes UnboundedOperators UO-D06's coercive solution map (not started); Layer 1 (direct method) is ready.
- Serves defs: 34 (min–max formula of Thm 34.2, 34.4(c); the Neumann spectrum itself is PR #1614)
- Evidence: README l.562 "### 3.1 Compact form pairs", l.782 "### 4.4 Courant–Fischer on the form domain" (`CompactFormPair.eigenvalue_eq_rayleighMinMax`); Layer 2 Dependencies "UnboundedOperators UO-D06 (coercive solution over `𝕜`)".
## TauCetiRoadmap/PseudodifferentialOperators
STATUS.md snapshot: 49adf64 2026-11-16, generated against Tau Ceti aa6e43e (Tau Ceti checked at 7cbfff3ef, 2026-11-16)

### §5.4 Compact-base C^{k,α} Hölder spaces
- Status: PARTIAL: for a fixed compact chart atlas `A : TauCeti.CompactChartAtlas I M`, the vector-valued space `TauCeti.CompactChartAtlas.CkHolderSpace A k α F` with norm = finite-atlas `C^k` norm + chart Hölder seminorms of the `k`th coordinate derivatives (`CkHolderSpace.norm_def`, `ContMDiffMap.chartHolderNorm`), and its completeness on boundaryless `M` (`CkHolderSpace.instCompleteSpace`), TauCeti/Geometry/Manifold/ContMDiffMap/Chart/Holder.lean. Missing: the comparison of two atlases (the file says it is not included), bundle `C^(k,α)` norms by connection comparisons, Zygmund `C^r_*`, the mapping theorems and the identification `C^(k+α)_* = C^(k,α)`.
- Ready now: yes for the atlas comparison (finite-atlas `C^k` comparison `ContMDiffMap.exists_finiteAtlasSeminorm_le` and the Hölder file exist); the Zygmund and mapping parts: no, they need P2–P4 (partial) and §5.3 Besov estimates.
- Serves defs: 32
- Evidence: README l.1337 "### 5.4 Hölder, Zygmund and little Hölder spaces", "Supply the compact-base bundle C^(k,α) norms by chart/connection comparisons"; *Needs* l.1428; Tau Ceti commit 97ec502a0 (#37238); STATUS coverage Layer 5 remaining "... Zygmund mapping ..."

### P7 §7.1 and P7a §8.1 Scalar self-adjoint Laplacian realization on closed manifolds
- Status: NOT-STARTED. Layer 6 has ellipticity, parametrix symbols, interior regularity and estimates for localized operators on Sobolev data, and interior elliptic regularity of differential operators on arbitrary distributions on open subsets of `ℝⁿ` (`Distribution.IsLocallySobolevAt.of_sum_smul_smulLeftCLM_iteratedLineDerivOp`, Analysis/Pseudodifferential/DistributionalRegularity.lean); Layers 7 and 8 are preparatory (polar decomposition and normalization of elliptic symbols, equivariant Fredholm multiplicities, parameter-dependent symbols; equal eigenspace multiplicities for almost-conjugate subgroups). No closed-manifold Laplacian `LinearPMap` in TauCeti/Geometry
- Ready now: no: §7.1 needs P6's patched global parametrix and Fredholm theory on compact bases (missing) and K5a's realization (CKG §5.7, not started). §8.1 needs RiemannianGeometry R4.7, P5 density, P6 and P7
- Serves defs: 40
- Evidence: README l.1600 "### 7.1 Powers and their Sobolev domains" ("Consume K5a's generic nonnegative Laplace-system self-adjoint H² realization"), l.1935 "### 8.1 Quotients and the scalar realization" (*Needs* l.1981); STATUS coverage Layer 6 remaining "regularity for arbitrary distributions, patched global parametrix, Fredholm theory on compact bases", Layer 8 remaining "scalar Laplacian H^2 realization, normalized pullback on H^2, isospectrality"; prose "Layers 7 and 8 are preparatory"

## TauCetiRoadmap/SobolevMapsBetweenManifolds
No STATUS.md; Tau Ceti checked at 7cbfff3ef, 2026-11-16 (grep `IsSobolevMap`, `HasWeakMFDeriv`, `orientedJacobian`, `MemW1pLocM`: no hits). Its inputs in code: Euclidean `TauCeti.HasWeakFDerivOn` with chain rule and change of variables, planar `MemLpLoc`/`MemWkpLoc` (Analysis/Sobolev/Local/), chartwise null sets `TauCeti.IsNullSet`, Riemannian volume, orientations, and the two-dimensional-source class `TauCeti.MemWkpLocMap` of PseudoholomorphicCurveAnalysis PH4.1 (Geometry/Manifold/Sobolev/LocalMap.lean, chart independence for `k ≤ 1` in LocalMap/Atlas.lean, locality `TauCeti.memWkpLocMapOnGroupoid_iff_locally` in LocalMap/Locality.lean).

### Layer 1 (§§1.1–1.2) `MemLpLoc`, `W^{1,p}_loc(Ω; F)` on open subsets of finite-dimensional real normed spaces
- Status: NOT-STARTED (`MemLpLoc`, `MemWkpLoc` take `U : Set ℂ`, Analysis/Sobolev/Local/Basic.lean).
- Ready now: yes (*Needs* Tau Ceti `TauCeti.HasWeakFDerivOn` and its a.e. uniqueness, present).
- Serves defs: 47 (and 41, 42 through it)
- Evidence: README l.344 "### 1.1 Local Lebesgue and Sobolev classes", l.386 "### 1.2 The first-order class `W^{1,p}_loc(Ω; F)`".

### Layer 2 (§§2.1–2.3) chain rules, change of variables, local mollification
- Status: NOT-STARTED in every dimension; the planar `MemWkpLoc.contDiffOn_comp`, `MemWkpLoc.comp_contDiffOn_diffeo` and the Euclidean `HasWeakFDerivOn.contDiffOn_comp`, `HasWeakFDerivOn.comp_contDiffOn_diffeo` exist.
- Ready now: no: needs §1.2 (§2.3 first, then §2.1–§2.2).
- Serves defs: 47 (Proposition 47.1), 41, 42
- Evidence: README l.438 "### 2.1 Chain rules and the composition operator", l.489 "### 2.2 Change of variables", l.518 "### 2.3 Local mollification"; *Needs* l.486, l.513 "§1.2, §2.3".

### Layer 3 (§§3.1–3.2) the almost-everywhere filter, measurability and `L^p_loc` on a manifold
- Status: NOT-STARTED. `TauCeti.IsNullSet` and `TauCeti.isNullSet_iff_riemannianVolume_eq_zero` exist; images of null sets under differentiable maps `TauCeti.IsNullSet.image_of_mdifferentiableOn` (Geometry/Manifold/Measure/Differentiable.lean) cover the first claim of §3.3.
- Ready now: no: §3.1 needs §2.2; §3.2 needs §1.1, §2.2, §3.1.
- Serves defs: 47, 41, 42
- Evidence: README l.634 "### 3.1 Null sets, positive densities and the almost-everywhere filter" (*Needs* l.675 "§2.2; Tau Ceti `TauCeti.IsNullSet`"), l.679 "### 3.2 Measurability and local `Lᵖ`", l.722 "### 3.3 Null sets under `C¹` maps".

### Layer 4 (§§4.1–4.3) Sobolev functions on `M`, the class `IsSobolevMap`, the weak differential `HasWeakMFDeriv`
- Status: NOT-STARTED for finite-dimensional sources in general; for Riemann-surface sources the class (without `Df`) is `TauCeti.MemWkpLocMap`.
- Ready now: no: needs §1.2, §2.1, §2.2, §3.1, §3.2.
- Serves defs: 47 (47.3(a)–(b), Proposition 47.2), 41, 42
- Evidence: README l.755 "### 4.1 Sobolev functions on a manifold", l.779 "### 4.2 The class `W^{1,p}_loc(M, N)`" (*Needs* l.809), l.811 "### 4.3 The weak differential" (*Needs* l.837).

### §5.1, §§6.1–6.2 `‖Df‖` and the Jacobian `J_f`
- Status: NOT-STARTED.
- Ready now: §6.1 (`orientedJacobian` of a linear map between oriented inner product spaces): yes (*Needs* only Mathlib `Orientation.volumeForm`, `LinearMap.normDet`); §5.1 and §6.2: no, they need §3.2 and §4.3.
- Serves defs: 47 (47.3(c)–(d)), 41, 42
- Evidence: README l.1009 "### 5.1 The norm `‖Df‖`" (*Needs* l.1048 "§3.2, §4.3"), l.1173 "### 6.1 The oriented Jacobian of a linear map" (*Needs* l.1197), l.1201 "### 6.2 The Jacobian of a Sobolev map" (*Needs* l.1227).

## TauCetiRoadmap/PseudoholomorphicCurveAnalysis
STATUS.md snapshot: 1928c2e 2026-11-14, describing Tau Ceti to aa6e43e 2026-11-13 (Tau Ceti checked at 7cbfff3ef, 2026-11-16; the Schottky double, which STATUS lists as remaining, is in code)

### PH6.1 Sobolev sections over compact surfaces with boundary
- Status: PARTIAL: a generic boundaryless bundle carrier `TauCeti.SobolevSection A μ p k` (`W^{k,p}(V)` over a `FiniteBundleAtlas`, closedness/completeness, `lowerOrderL`) exists in TauCeti/Geometry/Manifold/VectorBundle/Sobolev/{Basic,ContMDiffSection,SMul}.lean, and for surfaces modelled on `ℂ` its chart readings are the local classes `MemWkpLoc` and conversely (`TauCeti.SobolevSection.memWkpLoc_coord`, `exists_ae_eq_coord_of_memWkpLoc`, Sobolev/Local.lean), in arbitrary bundle charts rather than isothermal ones, with Morrey's embedding for `p > 2` (Sobolev/Morrey.lean), Rellich compactness for the boundaryless carrier `TauCeti.SobolevSection.isCompactOperator_lowerOrderL` (Sobolev/Rellich.lean) and chart transfer `FiniteBundleAtlas.transferL`, `restrictL_eq_transferL` (Sobolev/Transfer.lean). For `∂Σ ≠ ∅`, `TauCeti.BorderedSobolevSection` over a half-plane `FiniteBundleAtlas` (FiniteBundleAtlas/HalfPlane.lean) is complete, contains the `Cᵏ` sections and is closed under multiplication by smooth functions (Sobolev/Bordered/{Basic,SMul}.lean). Missing: norm independence of the atlas, density of smooth sections, Rellich and Morrey up to the boundary and multiplication by `W^{k,p}` coefficients for kp>2, the totally real boundary subspace `W^{k,p}_F`, comparison with P5.2 on interior subsurfaces.
- Ready now: no: needs PH2.4 isothermal coordinates/bordered atlas (partial: planar isothermal charts from the Beltrami solution with holomorphic transitions, Analysis/Complex/Beltrami/Transition.lean and Geometry/Manifold/Complex/Isothermal.lean, but no bordered isothermal atlas), PH1.2 Morrey/algebra/composition at higher order (partial: first-order chain rule and multiplication in Analysis/Sobolev/Local/{ChainRule,Multiplication}.lean; the half-disc higher-order reflection with its weak derivative `HasWeakFDerivOn.planarReflection` is in Local/Reflection.lean), PDE Lane A item 6 trace; the boundaryless sub-case could start against the existing carrier.
- Serves defs: 56, 60
- Evidence: README l.1045 "### 6.1 Sobolev sections over compact surfaces with boundary"; STATUS Layer 6 remaining "Fredholm property, duality and agreement with the smooth theory for real Cauchy–Riemann operators", Layer 1 remaining "higher-order Morrey and Rellich up to the half-disc boundary; continuity of composition above order one"; grep `SobolevSection` hits the bundle files above (Sobolev/ and Sobolev/Bordered/).

### PH6.2 Real Cauchy–Riemann operators
- Status: PARTIAL: the smooth half is in code: `TauCeti.IsRealCauchyRiemannOperator` (Leibniz-rule definition), `difference`/`isZeroOneForm_difference` (two operators differ by a zeroth-order (0,1)-form), `add_zeroOrder`, complex-linear part `sectionComplexLinearPart` + `antilinearPart` with uniqueness (MS Ex. C.1.7), and `IsCovariantDerivativeOn.isRealCauchyRiemannOperator_zeroOnePart` (a complex connection gives `(∇)^{0,1}`), in TauCeti/Geometry/Manifold/VectorBundle/CauchyRiemann/{Basic,Connection}.lean, with local-frame readings, direct sums, transport, straight lines and holomorphic frames (CauchyRiemann/{LocalFrame,Constructions,HolomorphicFrame}.lean); the boundaryless target space of Sobolev `(0,1)`-forms `TauCeti.zeroOneSobolevSections` with its projection (Sobolev/ZeroOneForm.lean); weak real CR equations with Sobolev coefficients (Analysis/Complex/CauchyRiemann/RoughCoefficients/Weak.lean) and the formal adjoint of such an operator as a reflected real CR operator (`TauCeti.crFormalAdjoint_crReflectedAdjoint`, RoughCoefficients/Adjoint.lean). The chart calculus `(D s)ᵢ = ∂̄ sᵢ + Zᵢ sᵢ` with `TauCeti.FiniteBundleAtlas.chartZeroOrder`: `coord_tangentHom_eq_complexAntilinearPartL_fderiv_add_chartZeroOrder`, overlap law `complexAntilinearPartL_fderiv_coordChangeL_add_chartZeroOrder`, `contDiffOn_chartZeroOrder`, `exists_norm_chartZeroOrder_apply_le` (Geometry/Manifold/VectorBundle/CauchyRiemann/Chart.lean). Missing: operators of class `W^{ℓ−1,p}` (`D = D₀ + α`), the realizations `W^{ℓ,p} → W^{ℓ−1,p}`, the totally real boundary condition `F`.
- Ready now: yes for the boundaryless realization of a smooth operator (`SobolevSection`, `zeroOneSobolevSections` and the chart calculus exist); no for the bordered case and `F`, which need PH6.1.
- Serves defs: 56, 60
- Evidence: README l.1083 "### 6.2 Real Cauchy–Riemann operators"; STATUS Layer 6 "partial"; grep `IsRealCauchyRiemannOperator` -> CauchyRiemann/Basic.lean (496 lines), Connection.lean.

### PH6.3 Fredholm property, kernel and cokernel
- Status: NOT-STARTED (generic Fredholm library exists: TauCeti/Analysis/Fredholm/*, incl. Adjoint, CompactPerturbation, DeterminantLine with its bundle and path transport of orientations; the vector similarity principle for `C¹` solutions with constant `i`, Analysis/Complex/CauchyRiemann/Similarity.lean; nothing CR-specific on bundles).
- Ready now: no: needs PH6.1–6.2 Sobolev realizations, PH3.3–3.5 (Sobolev-coefficient and boundary estimates, the `W^{1,p}` vector similarity principle with variable `J`; only the `C¹` constant-`i` similarity principle is in code), PH4.1, PH2.4.
- Serves defs: 56, 60
- Evidence: README l.1128 "### 6.3 Fredholm property, kernel and cokernel"; deps l.1215 "PH1 (through PH6.1's localizations), PH2.4, PH3.3–PH3.5, PH4.1"; STATUS Layer 3 remaining "Sobolev-coefficient estimates (3.3), boundary estimates (3.4), vector similarity principle (3.5)".

### PH7 (7.1 Maslov index of a bundle pair, 7.2 Riemann–Roch)
- Status: PARTIAL (ingredients only): loop Maslov index `TotallyRealLoop.maslovIndex`, `maslovIndex_map/_prod/_rotation`, loop concatenation and base-point invariance in TauCeti/LinearAlgebra/TotallyReal/Maslov/*.lean; the Robbin–Salamon crossing-form formula for paths of Lagrangian graphs (`Matrix.UnitaryGroup.maslovIndex_eq_crossingForm_add_finsum_of_souriau_eq_cayley`, Analysis/Matrix/UnitaryGroup/Maslov/Crossing.lean); the zero axiom for paths `Matrix.UnitaryGroup.maslovIndex_eq_zero_of_rootMultiplicity_eq`, `maslovIndex_eq_zero_of_forall_not_isRoot`, `Matrix.det_eq_neg_one_pow_mul_exp_spectralAngleSum` (Analysis/Matrix/UnitaryGroup/Maslov.lean); the disc model of 7.2, the cokernel of `∂̄` with rotating-line boundary of Maslov index `k` of real dimension `max (−1 − k) 0`, `TauCeti.exists_conjWirtingerDeriv_eq_and_eq_zpow_mul_conj_iff` (Analysis/Complex/UnitDisc/Cokernel.lean); STATUS also cites nowhere-vanishing sections in high rank and Hermitian metrics. No doubled bundle `E_F`, no `μ(E,F)`, no index formula.
- Ready now: no: 7.1 needs CharacteristicClasses C3.2's `c₁` (its other input, PH2.4's Schottky double as a compact Riemann surface with the antiholomorphic involution, is in code: `TauCeti.SchottkyDouble`, `SchottkyDouble.doubleChart`, Geometry/Manifold/Complex/BorderedHolomorphic/SchottkyDouble.lean); 7.2 needs PH6 (incl. 6.3) and PH3.5, plus CharacteristicClasses C2.3/C3.2 and AlgebraicTopology Stage 6/7.1/8.7.
- Serves defs: 56, 60
- Evidence: README l.1223 "### 7.1 Maslov index of a bundle pair", l.1271 "### 7.2 Riemann–Roch" ("prove `ind_ℝ D = nχ(Σ) + μ(E, F)`"); STATUS Layer 7 remaining "Maslov index of a bundle pair and Riemann–Roch; only model-case index computations exist".

## TauCetiRoadmap/AnalyticStableMaps
No STATUS.md (merged as roadmap PR #987; Tau Ceti checked at 7cbfff3ef, 2026-11-16).

### §§0.1–0.2 The Cauchy–Riemann section, energy and virtual dimension; the linearized operator D_u and the closed index
- Status: NOT-STARTED (inputs only: the local CR linearization `cauchyRiemannLinearization` with coordinate covariance, Geometry/Symplectic/JHolomorphic/{Linearization,Naturality}.lean; `IsPseudoholomorphic`, `stdComplexLineEnergy`, `SmoothTwoForm.Tames`).
- Ready now: no: §0.1 needs HeegaardFloer F2.6c, DifferentialGeometry 8.3–8.5 and CharacteristicClasses C3; §0.2 needs §0.1 and PseudoholomorphicCurveAnalysis PH6.2–PH6.3, PH7.2.
- Serves defs: 56 (target: §0.2 is Definition 56.3), 60
- Evidence: README l.120 "### 0.1 The Cauchy–Riemann section, energy, area and the virtual dimension", l.138 "### 0.2 The linearized operator and the closed index" (*Needs* "§0.1; PseudoholomorphicCurveAnalysis PH6.2–PH6.3, PH7.2; CharacteristicClasses C3; ...").

### §0.4 Finite exceptional sets of a nonconstant closed curve (with §0.5 normalization)
- Status: NOT-STARTED.
- Ready now: no: needs HeegaardFloer F2.2a and F2.3.
- Serves defs: 60 (60.1)
- Evidence: README l.170 "### 0.4 Finite exceptional sets and compact-image localization", l.182 "### 0.5 Normalization of a nonconstant closed curve through a simple curve".

### §2.1 Completely metrizable smooth-J topology, Baire property, density in J^ℓ
- Status: NOT-STARTED. Inputs in code: `ContMDiffSection.completeSpace_frameTopology` (Section/Complete.lean), `SmoothAlmostComplexStructure.frameTopology` with `isClosedEmbedding_toEndomorphism_frameTopology`, `isClosed_setOf_invariant_tames_frameTopology`, `secondCountableTopology_frameTopology_of_sigmaCompactDomains` (Section/SecondCountable.lean).
- Ready now: yes for complete metrizability and the Baire property on compact X; no for density in `J^ℓ` and tangent-space statements (need HeegaardFloer F0.5, partial).
- Serves defs: 63 (63.4(b))
- Evidence: README l.266 "### 2.1 Finite-regularity parameter spaces and the smooth-J topology".

## TauCetiRoadmap/FukayaTheory
No STATUS.md (merged as roadmap PR #1045; Tau Ceti checked at 7cbfff3ef, 2026-11-16).

### FK2.2 Nonlinear CR section and linearization (polygons with Lagrangian boundary)
- Status: NOT-STARTED (inputs only: local `cauchyRiemannLinearization` with coordinate covariance, JHolomorphic/{Linearization,Naturality}.lean; cylinder Floer operator `floerSobolevOperator`, Floer/SobolevRealization.lean).
- Ready now: no: needs PH6.1, PH6.3, PH7.2, PH3, HeegaardFloer F0.0, F1.1–F1.5.
- Serves defs: 56 (bordered analogue of D_u; implicit)
- Evidence: README l.354 "### 2.2 Nonlinear CR section and linearization (FK2.2)"; *Needs* l.376.

## TauCetiRoadmap/AdicEtaleGeometry
STATUS.md snapshot: 39df4ea 2026-11-16, generated against Tau Ceti aa6e43e (Tau Ceti checked at 7cbfff3ef, 2026-11-16)

### Layer A0 Completed tensor products and fibre products
- Status: PARTIAL. In code: `Huber.IsCompletedPushout` and the Huber-pair `completedTensor` (RingTheory/Huber/TensorProduct/{Pushout,Pair,Plus,UniversalProperty}.lean). Ring-level associativity, symmetry and unit (TensorProduct/{Associator,Symmetry,Unit}.lean; A0.7 at ring level). Rational localisation (TensorProduct/Rational.lean; A0.4 algebra). Finite étale base change (TensorProduct/FiniteEtale.lean; A0.5 algebra). Transitivity (BaseChange.lean). Affinoid fibre products `AdicSpace.affinoid_isPullback`, `affinoid_isPullback_of_isStablySheafyRing_left/right`, and Tate point lifting `exists_ofPair_completedTensor_point` (AlgebraicGeometry/AdicSpace/Pullback/Affinoid.lean). A0.8 in full: analytic points, the analytic locus `PreAdicSpace.analyticLocus` with `analyticLocus.ι`, `analyticLocus.lift`, `analyticLocus.range_ι` (AlgebraicGeometry/AdicSpace/PreAdicSpace/Analytic.lean), the cartesian restriction square for adic morphisms `IsAdic.isPullback_analyticLocusMap` (Morphisms/AnalyticLocus.lean), and `isAdic_iff_mapsTo_analyticPoints` (Morphisms/Adic.lean). Fibre products are local on the source, `TauCeti.AdicSpace.hasPullback_of_cover` (AlgebraicGeometry/AdicSpace/Pullback/Cover.lean). Missing: global fibre products for morphisms locally of finite type, `AdicSpace.FibreProduct.lift`/`ofPairPushout`, chart independence (A0.6), and the adic-space-level A0.4/A0.5/A0.7 comparisons.
- Ready now: yes for the A0.4/A0.5/A0.7 adic-space packaging. The glued fibre product depends on AdicSpacesPartII R0.7 existence (below).
- Serves defs: 22
- Evidence: README l.747 "## Layer A0: completed tensor products and the fibre products actually used". STATUS coverage Layer A0 remaining "geometric fibre product and maps into affinoids in A0.1, A0.2, A0.4, A0.6, symmetry and unit in A0.7, base change of the analytic locus"; prose "A0.8 is done apart from its base-change clause".

### A1.6 étale/finite étale sites, A1.7 geometric points, A1.14 change of base field
- Status: NOT-STARTED. No `AdicSpace.IsEtaleLocalDescription`, `AdicSpace.smallEtale` or `smallEtaleTopology` for adic spaces. What exists in A1: A1.0.0, A1.0.1, the morphism half of A1.0.3, and part of A1.2 (`finiteAlgebra.homEquiv`).
- Ready now: no. A1.6 needs *strongly-sheafy-huber-pair* (A1.1), *etale-morphism* and *etale-base-change* (A1.3–A1.5) and A0 pullbacks. A1.7 needs A1.6. A1.14 needs the pro-étale site (A1.10–A1.12, *proetale-coherence*), the etale-descent targets and AdicSpacesPartII R0.7/R0.19.
- Serves defs: 22
- Evidence: README l.3259 "### A1.6 the étale and finite étale sites" (*etale-site*, `AdicSpace.smallEtale X`); l.3670 "### A1.7 geometric points, enough points, strict localisations"; l.5511 "### A1.14 coherence and change of base field" (*etale-descent-along-algebraic-extension* l.5539, *proetale-field-extension-slice* l.5565). STATUS coverage Layer A1 remaining "A1.0.3a, Elkik A1.0.4 and A1.0.5, A1.1, finiteness and strong sheafiness in A1.2, A1.3 onward".

## TauCetiRoadmap/AdicSpacesPartII
STATUS.md snapshot: 1c6a1a4 2026-11-11 (Tau Ceti checked at 7cbfff3ef, 2026-11-16)

### R0.7 Fibre products (and R0.6 lft for rigid spaces)
- Status: PARTIAL. *valuation-amalgamation* (`ValuationSpectrum.exists_amalgamation`) is done. *affinoid-fibre-product* is in code (`TauCeti.AdicSpace.affinoid_isPullback`, `isPullback_ofPair_of_isCompletedPushout`, the unconditional version when one factor is stably sheafy and the other is topologically of finite type; AlgebraicGeometry/AdicSpace/Pullback/Affinoid.lean). The reduction of existence to an affinoid source is in code: fibre products exist once they exist over the members of an open cover of the source (`TauCeti.AdicSpace.hasPullback_of_cover`, AdicSpace/Pullback/Cover.lean). Missing: *fibre-product-along-finite-type* (the non-adic ascending-union case), the reduction on the base and target, *fibre-products-existence* (`hasPullback_of_finiteType`), `exists_pullback_point` and base-change stability. For "rigid space lft" (R0.6): `IsAdic`, `LocallyOfWeaklyFiniteType`, `LocallyOfPlusWeaklyFiniteType` and `QuasiCompact` exist (AdicSpace/Morphisms/), as does `TauCeti.AdicSpace.IsLocallyHuberStandard` (AdicSpace/PreAdicSpace/LocallyHuberStandard.lean, with Huber's standing class stable under rational localisation); finite presentation is missing.
- Ready now: yes for gluing affinoid fibre products to *fibre-products-existence* in the lft-over-stably-sheafy case (the gluing step uses the Huber-pair rational-localisation comparison of R0.3, whose ring-level form is RingTheory/Huber/TensorProduct/Rational.lean). The non-adic case needs R0.6 completion. R0.2 sheafiness for noetherian rings of definition (*noetherian-type-stably-sheafy*, partial) remains a prerequisite for the noetherian-type charts.
- Serves defs: 22
- Evidence: README l.3557 "### R0.7 fibre products" (*affinoid-fibre-product* at ~l.3622, *fibre-products-existence* at ~l.3702). *fibre-products-existence* Needs l.3736 (*affinoid-fibre-product*, *fibre-product-along-finite-type*, *adic-iff-analytic-locus*, *noetherian-type-stably-sheafy*, ...). STATUS remaining: "non-affinoid fibre products (R0.7)", with "The Huber-pair form of the rational-localisation comparison (R0.3) is a prerequisite".

## TauCetiRoadmap/AdicSpacesPartIV
STATUS.md snapshot: 7ca783d 2026-11-09 (Tau Ceti checked at 7cbfff3ef, 2026-11-16)

### R4.1–R4.6 étale sites on analytic adic spaces, rigid comparison, geometric points
- Status: NOT-STARTED for the site theory. Only R4.7 algebraic normal-crossings charts and the punctured-disc noncompactness check exist.
- Ready now: no. R4 re-exports AdicEtaleGeometry A1's *etale-site* (not started) onto R0/R1 carriers. R4.4's rigid comparison also needs AdicSpacesPartII R1 (untouched).
- Serves defs: 22
- Evidence: README l.562 "## Layer R4: étale and pro-étale sites"; l.583 "### R4.1 the étale site on the analytic carriers"; l.727 "### R4.4 rigid comparison"; l.827 "### R4.6 geometric points and pullback". The Checks at l.1712 have Sh(X_ét) ≃ continuous Gal(K^sep/K)-sets via ξ. STATUS remaining: "the étale and pro-étale sites, nu, rigid comparison and geometric points".

## TauCetiRoadmap/CharacteristicClasses
STATUS.md snapshot: 2bec3fc 2026-11-09 (to Tau Ceti d92acc5; Tau Ceti checked at 7cbfff3ef, 2026-11-16)

### C4 Chern–Weil forms
- Status: NOT-STARTED (no Chern–Weil code; grep `ChernWeil`: no hits)
- Ready now: no: C4.1 applies invariant polynomials to "SBC's principal curvature" (SBC B4.1, untouched); comparisons need C1–C3 (C1 partial, C3 untouched)
- Serves defs: 37, 48 (YangMillsConnectionsAndCaloricGauge §1.4 and Layer 6 consume C4 item 1; §§9.6–9.7 and §10.2 reach Layer 6)
- Evidence: README l.1321 "## C4. Curvature classes and their integral comparison", item 1 "Apply them to curvature using DG's value-bundle wedge/composition and SBC's principal curvature"; l.1996 "C4's invariant-form construction and line comparison use C1–C3 and the smooth suppliers"; STATUS "C3, C4, C5, C5a and C7 are untouched"

### C5a.3 Weil algebra and normalized Chern–Simons forms
- Status: NOT-STARTED (grep `WeilAlgebra`, `ChernSimons`: no hits).
- Ready now: no: "C5a.3 builds the Weil algebra and finite universal connection maps from C4" (C4 untouched).
- Serves defs: 37, 48 (through YangMillsConnectionsAndCaloricGauge §1.4)
- Evidence: README l.1530 "**C5a.3. The Weil differential and normalized transgression forms.**", l.2011.

## TauCetiRoadmap/DGAInfinity
STATUS.md snapshot: bf232a2 2026-11-16, generated against Tau Ceti aa6e43e (Tau Ceti checked at 7cbfff3ef, 2026-11-16)

### Layer 8 Hochschild cochains (ordinary algebras, normalized, HH²)
- Status: PARTIAL. Positive-arity Hochschild cochains of an A∞ algebra, with the Hochschild differential `[m,-]`, braces, the Gerstenhaber bracket and cohomology (Algebra/Homology/AInfinity/Algebra/Hochschild/{Basic,Complex,Cohomology}.lean). Normalized cochains for a strict unit, `PositiveHochschild.normalizedComplex` (Hochschild/Normalized.lean); whether the inclusion is a quasi-isomorphism is not addressed. Formal deformations and obstruction classes in Hochschild degree two (Deformation.lean); first-order deformations are degree-one cocycles. An ordinary or DG algebra becomes an A∞ algebra via `IsNonUnitalDGAlgebra.toAInfinityAlgebra` (DG.lean). For an ordinary algebra `A` and an `A`-bimodule `M` (so `M = A` gives Cⁿ(A,A)), the multilinear cochains `Aⁿ → M` in every arity including zero carry the Hochschild coboundary `TauCeti.hochschildBimoduleCoboundary` with `δ ∘ δ = 0`, degree-zero cocycles the centre and degree-one cocycles the derivations (RingTheory/HochschildCohomology/Coboundary.lean); the packaged cochain complex and cohomology there, `hochschildCochainComplex`/`hochschildCohomology` (Complex.lean), have coefficients in `Hom_R(A, M)`, not in `M`. Missing: the cochain complex and cohomology HHⁿ(A, M) with bimodule coefficients, HH² ↔ infinitesimal deformations and HH³ ↔ obstructions for ordinary algebras, normalization comparison, and quasi-equivalence/Morita invariance.
- Ready now: yes. The README names no blocking prerequisites for the ordinary-algebra HH²/HH³ clause, and both the A∞ machinery it specializes and the bimodule-coefficient coboundary are present.
- Serves defs: 10
- Evidence: README l.520 "### Layer 8: Hochschild cochains, deformations, Massey products, and formality" ("For an ordinary associative algebra, recover `HH²` for infinitesimal deformations and `HH³` for obstructions"). STATUS Layer 8 remaining "normalization and Morita invariance comparisons, Deligne groupoids over Q-algebras, higher m_n encoding Massey defining systems".

## TauCetiRoadmap/DifferentialGeometry
STATUS.md snapshot: 53c246b 2026-11-16, generated against Tau Ceti aa6e43e (Tau Ceti checked at 7cbfff3ef, 2026-11-16)

### Layer 12 (12.4 density, 12.5 divergence theorem)
- Status: PARTIAL: `riemannianVolume`, the gradient, divergence and Laplacian, the boundaryless compactly supported divergence theorem `integral_divergence_eq_zero` (Geometry/Manifold/Riemannian/DivergenceTheorem.lean:225), and, on oriented manifolds, `measure_riemannianVolumeForm` (`|dV| = riemannianVolume`) with the agreement of `integralTopForm` of `f dV` and the integral against `riemannianVolume` for continuous compactly supported `f` (Geometry/Manifold/Riemannian/VolumeForm/Measure.lean) exist. Missing: the 12.4 Riemannian density and its `integralDensity` link, and the 12.5 boundary divergence theorem `integral_divergence_eq_boundaryFlux`
- Ready now: no: 12.4 needs 5.5a's `integralDensity` and its agreement with top-form integration. The rest of 5.5a is in code: `Density`, `RoughDensity` and the density `toDensity` of a top form and an orientation (LinearAlgebra/Density/{Basic,Orientation}.lean, Geometry/Manifold/Density/Basic.lean), and the smooth `DensityBundle` (Geometry/Manifold/VectorBundle/Density.lean). `integralDensity` itself needs only 5.2 (form integration, in code), so it can start now. 12.5 needs 12.4. Compactly supported variations on boundaryless sources can already use `integral_divergence_eq_zero`
- Serves defs: 52
- Evidence: README l.2796 "### Layer 12: Riemannian metrics and the Laplace–Beltrami operator", l.2936 "**12.5 Divergence theorem and Green.**"; STATUS coverage Layer 12 remaining names the Riemannian density with its `integralDensity` comparison (12.4) and the divergence theorem with boundary (12.5); Layer 5 remaining "densities on manifolds, integralDensity and Stokes with corners (5.5)"; grep `integralDensity` in Tau Ceti: no hits

## TauCetiRoadmap/FlagVarieties
STATUS.md snapshot: 7ca783d 2026-11-09 (Tau Ceti checked at 7cbfff3ef, 2026-11-16; README at roadmap c6ef576)

### Layer 2 Standard algebraic parabolics P_J
- Status: NOT-STARTED for general G. The GL_n case is done in Layer 1 (`standardWeight`, weight parabolics; Algebra/AlgebraicGroup/GeneralLinear/Weight/Parabolic/). Abstract Tits-system standard parabolics exist (GroupTheory/TitsSystem/Parabolic/).
- Ready now: no: STATUS says "blocked on ReductiveGroups 7/7b" (needs the Tits system on G(k), B W_J B and the BN-pair comparison with algebraic parabolics).
- Serves defs: 79
- Evidence: README l.156 "## Layer 2: standard algebraic parabolics and the BN-pair bridge" (inputs: "ReductiveGroups Layer 7's actual algebraic-group Tits system on G(k)"); STATUS Layer 2 "untouched", "remaining: standard parabolics P_J and their order classification; blocked on ReductiveGroups 7/7b".

## TauCetiRoadmap/NoncommutativeIntegration
STATUS.md snapshot: 2cc438a 2026-11-11 (Tau Ceti checked at 7cbfff3ef, 2026-11-16)

### §1.5 Finite-trace inclusions; Lp(B(H),Tr) = S_p
- Status: NOT-STARTED (no generalized singular numbers / τ-measurable operators). Supporting: approximation numbers (TauCeti/Analysis/OperatorIdeal/ApproximationNumber/), operator-ideal Schatten families (Analysis/OperatorIdeal/Family*), finite-dimensional Schatten seminorm (Analysis/InnerProductSpace/UnitarilyInvariantSeminorm/Schatten.lean).
- Ready now: no: needs §1.1, §1.3, §1.4 (not started) and VonNeumannAlgebras V10.Affiliation/V10.TracialLp (Layer 10 untouched).
- Serves defs: 46 (weak link)
- Evidence: README l.360 "### 1.5 Finite-trace inclusions and the commutative and Schatten identifications", *Needs* "§1.1, §1.3, §1.4; OperatorTheory/OperatorIdeals Parts A–B"; grep `generalizedSingularNumber|tauMeasurable` empty.

## TauCetiRoadmap/PerfectoidSpaces
STATUS.md snapshot: b885423 2026-11-16, generated against Tau Ceti aa6e43e (Tau Ceti checked at 7cbfff3ef, 2026-11-16); STATUS lists Layer P4 as untouched

### P4.15.2 universal prisms and perfection; P4.15.3 the affine Hodge–Tate input (Čech–Alexander Δ_{C/B})
- Status: PARTIAL, δ-rings only: `TauCeti.DeltaRing` (a `δ`-structure for a fixed prime `p`, with the polynomial `DeltaRing.addCorrection`), its Frobenius lift `DeltaRing.frobenius`, the `δ`-structure of a Frobenius lift on a `p`-torsion-free ring `DeltaRing.ofFrobeniusLift` with uniqueness `DeltaRing.ext_of_frobenius`, and the unique `δ`-structure on `ℤ` (RingTheory/DeltaRing/Basic.lean). Missing: free `δ`-algebras, distinguished elements, prisms (bounded, perfect), rigidity, prismatic envelopes, perfection of prisms, the perfect-prism/perfectoid equivalence, `A_inf` initiality, `Δ_init`, and all of P4.15.3. The "prism" hits elsewhere in TauCeti are simplicial/cubical topology.
- Ready now: no for the sections as written. P4.15.2 needs P4.15.1, which needs DerivedModuleAlgebra §§0.1–0.4, 0.14 and 1.1–1.9 (largely unstarted), plus P1.16–P1.18, P1.24 and P0.19 cotangent. P4.15.3 additionally needs P0.19's full cotangent complex. Distinguished elements, prisms and rigidity have no derived prerequisites beyond `TauCeti.DeltaRing` and the derived (p,J)-completeness predicate (both exist) and could start now as a substep.
- Serves defs: 81
- Evidence: README l.11053 "#### P4.15.2 universal prisms and perfection" (*semiperfectoid-universal-prism*); l.11090 "#### P4.15.3 the affine Hodge–Tate input" (*semiperfectoid-affine-hodge-tate*, which states "No global prismatic-cohomology output is required"). l.10959 "#### P4.15.1 derived completion and complete flat descent" is the prerequisite.

## TauCetiRoadmap/SpinGeometry
STATUS.md snapshot: 8f0def6 2026-11-11 (describes Tau Ceti to a6027b1; Tau Ceti checked at 7cbfff3ef, 2026-11-16)

### G4.2 Principal spin lifts
- Status: PARTIAL: the structure, its equivalences and pullback are in code: `TauCeti.SpinStructure` for rank `n ≥ 1` (a `TauCeti.PrincipalBundle` for `realCliffordSpinGroupZero n` with a continuous frame map to `TauCeti.OrthonormalFrameBundle`, equivariant along `CliffordAlgebra.spinVectorAction`, no numerability field, as the README's `Suggested.lean` specifies), `SpinStructure.Equiv` (`refl`, `symm`, `trans`, `toHomeomorph`), `SpinStructure.pullback`, `Equiv.pullback` (Topology/VectorBundle/SpinStructure.lean). Missing: descent, metric-change independence, smooth structures on lifts, and G4.3 onward. G4.1a–b frame adapters are done. The carriers the section names exist: `TauCeti.PrincipalBundle` with `PrincipalBundle.pullback` (Topology/FiberBundle/Principal/Basic.lean, Geometry/Manifold/FiberBundle/Pullback.lean), cocycle gluing `TauCeti.fiberBundleCoreOfGroupCocycle` (Geometry/Manifold/FiberBundle/GroupCocycle.lean), `TauCeti.OrthonormalFrameBundle` with `toOrientationCover` (Topology/VectorBundle/Orientation/OrthonormalFrame.lean) and its presentation as a principal `O(n)`-bundle `TauCeti.OrthonormalFrameBundle.Fiber` with proper projection (Topology/VectorBundle/OrthonormalFrame/Principal.lean), the structure group `CliffordAlgebra.realCliffordSpinGroupZero` (LinearAlgebra/CliffordAlgebra/Spin/Real/Basic.lean).
- Ready now: no for the rest: descent and metric-change independence need TopologicalKTheory T6.4's numerable principal-bundle category and CharacteristicClasses C1.0's oriented frames and metric-change transport (neither in code). G4 has no Spin^c content; it is only the Spin analogue for def 64.
- Serves defs: 64
- Evidence: README l.1461 "## Layer 4: Spin lifts, obstruction and classification", l.1585 "### 4.2 Principal spin lifts (G4.2)" ("A spin structure on an oriented metric V of rank n is a numerable principal Spin(n)-bundle P with an equivariant map P→Fr⁺_SO(V)"), *Needs* l.1652; STATUS "The topological and smooth frame adapters of G4.1 are done ... there are no Clifford bundles (G3), spin structures (G4.2–G4.4)", which predates Topology/VectorBundle/SpinStructure.lean.

## TauCetiRoadmap/StableReduction
STATUS.md snapshot: 1b19ebb 2026-11-11 (Tau Ceti checked at 7cbfff3ef, 2026-11-16)

### Layer 10 PrestableMap, IsStableMap, openness
- Status: PARTIAL: `PrestableMap`, isomorphisms/category, automorphisms with `infinitesimalAut`, contracted components with the closed-point, dimension and field-extension characterizations (TauCeti/AlgebraicGeometry/Curves/StableMaps/{Basic,Category,Automorphism,Contracted}.lean). Missing: `IsStableMap`, base-change invariance, openness for projective targets, the finite-automorphism and ampleness characterizations, and the constant-map/source-stability theorem.
- Ready now: yes for `IsStableMap` (needs the Layer 3 pointed-prestable core, which exists, plus a normalization genus of components; no `normalizationGenus` is in Tau Ceti yet, so build it from Normalization/ and `Scheme.genus`). Openness and the ampleness criterion need Layer 2's openness of ampleness (remaining).
- Serves defs: 24
- Evidence: README l.732 "### Layer 10: stable maps and their stability condition"; STATUS l.32 "Layer 10 has prestable maps, automorphisms and contracted components, but no `IsStableMap`"; grep `IsStableMap` empty.

### Layer 11 stable-map API and map-aware stabilization
- Status: PARTIAL: evaluation maps and polarization degree (StableMaps/Degree.lean); decorated dual graphs, clutching, contraction, cutting, forgetting, stabilization files exist in StableMaps/DualGraph/; descent of a prestable map along a contraction of its source curve, `PrestableMap.descend` with `toDescend` and uniqueness `descend_eq`, compatible with postcomposition, reindexing and base change (StableMaps/Descent.lean). STATUS remaining: "additivity and local constancy of degree, single-marking contraction, gluing of stable maps, map-aware stabilization in families".
- Ready now: no: needs Layer 10 `IsStableMap`, Layer 2 polarized descent and contraction descent, and Layer 3 single-marking contraction (all remaining)
- Serves defs: 24
- Evidence: README l.778 "### Layer 11: basic stable-map API and map-aware stabilization"; STATUS l.32 "Layer 11 has evaluation maps, the polarization degree of a map over a field, and decorated dual graphs".

## TauCetiRoadmap/SymplecticGeometry/CotangentLagrangian
STATUS.md snapshot: 62acfe6 2026-11-16 (umbrella SymplecticGeometry/STATUS.md, generated against Tau Ceti aa6e43e; Tau Ceti checked at 7cbfff3ef, 2026-11-16)

### C3.1 Discrete action, iterates and convex billiards
- Status: PARTIAL. Exists: the lifted next-collision map β̃ on `ℝ × (−1, 1)`, `TauCeti.StrictConvexBilliardTable.nextCollision`, with existence and uniqueness of the exit parameter (`exists_collision`, `eq_nextParam_of_areaForm_eq_zero`), `nextTangential_mem_Ioo`, the reflection law `outgoingDir_nextCollision` and τ-equivariance `nextCollision_add_period`, for any unit-speed table, not only smooth ones (TauCeti/Dynamics/Billiard/NextCollision.lean); periodic billiard polygons `TauCeti.exists_billiard_periodic_reflection` (Dynamics/Billiard/PeriodicPolygon.lean); the inverse of β̃ by time reversal, `nextCollisionEquiv`, and its descent to a bijection β of `AddCircle L × (−1, 1)`, `billiardMap` with `billiardMap_symm_coe` (Dynamics/Billiard/Inverse.lean); the generating function `S(s, t) = −‖χ(t) − χ(s)‖` (`generatingFunction`, `generatingFunction_add_period`) with `v = ∂_sS`, `w = −∂_tS` at the next collision (`deriv_generatingFunction_left_nextParam`, `deriv_generatingFunction_right_nextParam`, `nextParam_eq_iff_deriv_generatingFunction_left_eq`), the twist `∂_s∂_tS < 0` (`deriv_deriv_generatingFunction_left_neg`, `_right_neg`) and, for fixed `s`, `∂t/∂v < 0` with continuity of `v ↦ t` (`hasDerivAt_nextParam`, `deriv_nextParam_neg`, `continuousOn_nextParam`, `strictAntiOn_nextParam`) (Dynamics/Billiard/GeneratingFunction.lean); the chain dictionary `TauCeti.CotangentBundle.exists_equiv_periodic_of_generating` with `TauCeti.cyclicAction` (Geometry/Symplectic/Cotangent/GeneratingFunction/Chain.lean). Missing: joint continuity and smoothness of β̃ and its inverse in `(s, v)` (so β as a homeomorphism), the primitive identity `β̃*λ − λ = dℓ` and `β̃*ω = ω`, `MeasurePreserving` for β, the application of the chain dictionary to billiards (critical inscribed N-gons ↔ periodic states), the circular formula with its periodicity criterion, and finite-volume recurrence.
- Ready now: yes: consumes C3's generating relations (TauCeti/Geometry/Symplectic/Cotangent/GeneratingFunction/{Correspondence,Composition,MixedHessian,Family,...}.lean), the carrier, β̃ and the generating function above, plus Mathlib `AddCircle` measure and `MeasurePreserving.conservative`. The merged MathematicalBilliards restates these properties at regularity `C^k` on its own carrier `ConvexTable` (§§2.1–2.2, 3.1–3.3), consumes C3.1's map and circular formula (§§1.5, 2.5, 5.6) and its finite-volume recurrence (§4.4), and does not cite the Tau Ceti carrier.
- Serves defs: 92
- Evidence: CotangentLagrangian/README l.471 "### C3.1. Discrete action, iterates and convex billiards", paragraph "Convex planar billiards" (l.527), l.728 "C3.1 consumes C3's generating relations, Mathlib's `AddCircle` measure ..."; SymplecticGeometry STATUS "C3 is partial: generating functions, their composition, and the next-collision map of a convex billiard are in"; grep `primitive|measurePreserving_billiardMap|continuous_billiardMap` in TauCeti/Dynamics/Billiard empty.

## TauCetiRoadmap/MathematicalBilliards
No STATUS.md (merged as roadmap PR #2255; Tau Ceti checked at 7cbfff3ef, 2026-11-16).

### Layer 1 Convex billiard tables (`ConvexTable`, curvature criterion, exit points, oriented lines)
- Status: NOT-STARTED on the roadmap's carrier (grep `ConvexTable` empty). Tau Ceti's `TauCeti.StrictConvexBilliardTable` (TauCeti/Dynamics/Billiard/NextCollision.lean) is the same strict-convexity and orientation condition for `C¹` unit-speed tables in an oriented Euclidean plane, with exit parameters (`exists_collision`, `nextParam`); the roadmap works in `ℂ` with a regularity index `k` and does not cite it.
- Ready now: yes for §§1.1, 1.3–1.5 (Mathlib `StrictConvex`, `convexHull`; Tau Ceti `TauCeti.IsJordanCurve`, `isJordanCurve_frontier_of_convex`); §1.2 (curvature criterion) needs RiemannianGeometry/Surfaces §3.1 `integral_signedCurvature_add_sum_exteriorAngle_eq_two_pi` (not in code).
- Serves defs: 92
- Evidence: README l.96 "## Layer 1: Convex billiard tables", l.100 (§1.1 carrier), l.120 (§1.2), Dependencies l.172.

### Layers 2–3 The billiard ball map, its regularity and closed-cylinder extension; generating function and invariant measure
- Status: NOT-STARTED on `ConvexTable`. Tau Ceti analogues in the coordinates `(s, cos δ)`: the lift and the bijection of the open cylinder with time reversal (`nextCollision`, `nextCollisionEquiv`, `billiardMap`, `billiardMap_symm_coe`; cf. §§2.1, 2.4) and the chord-length derivatives and twist (`generatingFunction`, `deriv_deriv_generatingFunction_left_neg`; cf. §3.1). Missing: homeomorphism and `C^{k−1}` regularity (§2.2), the closed cylinder (§2.3), the comparison with C3.1 (§2.5), exactness and the Jacobian (§3.2), `phaseMeasure` and `ConvexTable.measurePreserving_billiardMap` (§3.3).
- Ready now: no: needs Layer 1 (§2.1 needs §1.3; Layer 3 needs Layers 1–2; §2.5 also needs C3.1's map).
- Serves defs: 92
- Evidence: README l.174 "## Layer 2: The billiard ball map", l.251 "## Layer 3: Generating function and invariant measure", Dependencies l.249, l.304.

### Layers 4–5 Twist maps of the annulus; rotational invariant curves, Birkhoff's graph theorem and rotation numbers
- Status: NOT-STARTED (grep `IsTwistLift|IsRotationalInvariantCurve|nonwanderingSet` empty).
- Ready now: yes for §§4.1–4.2 (twist lifts, monotone and exact twist maps; Mathlib only) and §5.1 (`IsRotationalInvariantCurve`, Definition 92.5; Mathlib `ContinuousMap.Nullhomotopic`, Tau Ceti Jordan curve theorem). No for the rest: §4.3 needs Layers 2–3; §4.4 needs C3.1's finite-volume recurrence (not in code); §5.2 needs GeometricTopology §2.3, the annulus theorem in dimension two (not in code); §§5.3–5.6 need §§2.3, 3.3, 4.3–4.4.
- Serves defs: 92
- Evidence: README l.306 "## Layer 4: Twist maps of the annulus", l.383 "## Layer 5: Rotational invariant curves" (§5.1 l.385, §5.3 l.416, §5.4 l.433), Dependencies l.381, l.479.

### Layers 7–8 Polygonal tables, phase space, trajectories, singular set, billiard flow and Liouville measure
- Status: NOT-STARTED (grep `billiardFlow|polygonalTable` empty). Supplier pieces exist: `TauCeti.SimplePolygon`, `Polygon.boundaryParamCircle`, `Polygon.IsSimple.isJordanCurve_boundary` (TauCeti/Geometry/Polygon/Simple.lean).
- Ready now: yes for Layer 7 (Mathlib, Tau Ceti polygons); Layer 8 needs Layer 7.
- Serves defs: 93
- Evidence: README l.554 "## Layer 7: Polygonal tables" (§7.1 l.556, §7.2 l.576, §7.3 l.594), l.620 "## Layer 8: The singular set and the billiard flow" (§8.2 l.632, §8.3 l.648), Dependencies l.618, l.664.

### Layer 12 (§§12.1–12.5) Weak mixing of flows
- Status: NOT-STARTED (grep `IsWeaklyMixing|WeakMixing` in TauCeti empty). Supplier pieces exist: `TauCeti.bochner_charFun_real` (Analysis/Bochner/CharFun/Bochner.lean), `TauCeti.Semigroups.StronglyContinuousGroup` and `.IsUnitary` (Analysis/Semigroups/Group/).
- Ready now: yes for §§12.1–12.5 (Mathlib measure theory, `charFun`, `Lp.compMeasurePreserving`; Tau Ceti Bochner and strongly continuous groups); §12.6 needs Layers 9–11.
- Serves defs: 93
- Evidence: README l.866 "## Layer 12: Weak mixing of flows" (§12.1 l.868, §12.5 l.929), Dependencies l.963.

## TauCetiRoadmap/TaubesGromov
STATUS.md snapshot: af2393b 2026-11-16, generated against Tau Ceti aa6e43e (Tau Ceti checked at 7cbfff3ef, 2026-11-16)

### TG1 Embedded normal operators and application regularity
- Status: NOT-STARTED (only the local normal linearization of HF, Geometry/Symplectic/JHolomorphic/Normal/Linearization.lean, the normal rescaling of J along a curve, Normal/Rescaling.lean, and the generic Fredholm determinant line bundle with orientation transport, Analysis/Fredholm/DeterminantLine/).
- Ready now: no: needs PH6.2–6.3 realizations, HF F1.4 determinant orientation, GT tube, HF/M simple-curve transversality (F2.4/F2.6d).
- Serves defs: 60
- Evidence: README l.40 "## TG1. Embedded normal operators and application regularity"; STATUS prose "TG1 has only the normal linearization of J along a holomorphic section".

## TauCetiRoadmap/VonNeumannAlgebras
STATUS.md snapshot: 5be5068 2026-11-11 (Tau Ceti checked at 7cbfff3ef, 2026-11-16; README at roadmap c6ef576, which includes the #2242 revision on Jones 2015 and bounded Tomita–Takesaki)

### Layer 13 (V13b) injective = hyperfinite
- Status: NOT-STARTED.
- Ready now: no: needs V13a and V11 standard form, V12 ultrapowers, V5/V6 traces; Layers 3–7 and 9–13 are all untouched.
- Serves defs: 36
- Evidence: README l.4792 "## Layer 13: Hyperfiniteness and injective classification", l.4851 "### 13.2 Semidiscreteness, approximation and classification (V13b)"; STATUS `{"id":"Layer 13","state":"untouched"}`; grep `Hyperfinite|Semidiscrete` empty.

### V13a Tensor-independent CP maps, Arveson extension, Tomiyama, injectivity
- Status: NOT-STARTED.
- Ready now: no: needs V0–V3, V4.Core, V4.Normality; Layers 3–4 are untouched.
- Serves defs: 36 (AmenableTracesOnCStarAlgebras §4.1 hypertraces, §4.4, §5.4)
- Evidence: VonNeumannAlgebras README l.4794 "### 13.1 Tensor-independent CP and extension foundations (V13a)", *Needs* "V0–V3, V4.Core, V4.Normality"; AmenableTracesOnCStarAlgebras README l.1321 (§4.1 *Needs* "VonNeumannAlgebras V13a (Arveson's extension theorem)").

### Layer 9 (lattice part) Lattices in unimodular locally compact groups, Weil's formula, uniform lattices
- Status: NOT-STARTED (no lattice-subgroup predicate in Tau Ceti; Mathlib has `IsFundamentalDomain`, `covolume`, `QuotientGroup.integral_eq_integral_automorphize`).
- Ready now: yes for the lattice notion and Weil's formula (Mathlib inputs only); the lattice-module part of Layer 9 needs V7 and V8.
- Serves defs: 15, 31 (lattices in `PU(1,n)`, read in open PR #2425 §5.1)
- Evidence: README l.2882 "## Layer 9: Lattice modules and discrete series", l.2893 "Define a lattice as a discrete subgroup of finite covolume in a unimodular second-countable locally compact group".

## TauCetiRoadmap/SpectralSequencesAndConvergence
No STATUS.md (merged as roadmap PR #2302; Tau Ceti checked at 7cbfff3ef, 2026-11-16).

### Layer 1 and §2.1 Cycle and boundary towers, stabilisation, the limit page; bidegree assignments
- Status: NOT-STARTED for an arbitrary spectral sequence (grep `limitPage|HasLimitPage|infiniteCycles` empty). Tau Ceti has `E∞` and stabilisation only for spectral objects and filtered complexes (`Abelian.SpectralObject.EInftyIsoCokernel`, `spectralSequencePageXIsoEInfty`, Algebra/Homology/SpectralObject/{Abutment,Stabilization}.lean; `filtrationSpectralSequencePageXIsoEInftyOfFinite`, .../SpectralSequence/Filtered/Stabilization.lean).
- Ready now: yes (Mathlib `Subobject`, `kernelSubobject`, `imageSubobject`, `SpectralSequence`; countable products for §1.4 in general).
- Serves defs: 6
- Evidence: README l.404 "## Layer 1: cycle and boundary towers and the limit page" (§1.4 l.513), l.564 "### 2.1 Bidegree assignments".

### Layer 3 (§§3.1–3.2, 3.4) Filtered abutments, convergence structures, finite filtrations
- Status: NOT-STARTED (no convergence structure for an arbitrary spectral sequence; the filtered-complex convergence results in Tau Ceti, `filtrationSpectralSequencePageXIsoGradedOfFinite` and the exhaustive and complete variants in .../SpectralSequence/Filtered/{Convergence,Exhaustive,Complete}.lean, are instances in Layer 5's setting).
- Ready now: no: §3.2 needs §§1.4, 2.1, 3.1; §3.4 needs §3.2 and §2.3 for its Serre-class clause.
- Serves defs: 6
- Evidence: README l.703 "## Layer 3: filtered abutments and convergence", l.738 "### 3.2 Convergence structures" (*Needs:* 1.4, 2.1, 3.1), l.805 "### 3.4 Finite filtrations".

### §4.4 Convergence in a range of degrees (with §§4.1–4.3)
- Status: NOT-STARTED (grep `HasConvergenceBounds` empty). Supplier pieces exist: Tau Ceti `abutment`, `abutmentFiltration`, `isZero_abutmentFiltration`, `isIso_abutmentFiltrationι`, `EInfty`, `spectralSequencePageXIsoEInfty`.
- Ready now: no: needs §§3.2, 3.4, 4.2, 4.3 (and §4.1 on §1.2).
- Serves defs: 6
- Evidence: README l.961 "## Layer 4: spectral objects indexed by `EInt`", l.1114 "### 4.4 Convergence in a range of degrees" (*Needs:* 3.2, 3.4, 4.2, 4.3).

## TauCetiRoadmap/AlgebraicModuliForArithmeticGeometryPartII
No STATUS.md (merged as roadmap PR #1754; Tau Ceti checked at 7cbfff3ef, 2026-11-16).

### Layer 1 (§§1.1, 1.5, 1.7(ii)) `Num(X/S)`, `N¹(X/S)_ℝ`, nef classes and Kleiman's nonnegativity
- Status: NOT-STARTED (grep `numericallyTrivialClasses|relNumericallyTrivialClasses|IsNef` empty). Supplier pieces exist: `TauCeti.AlgebraicGeometry.LineBundleClass` and `LineBundleClass.IsAmple` (AlgebraicGeometry/LineBundle/Ample.lean), `LineBundleClass.intersectionNumber` with curves (AlgebraicGeometry/IntersectionNumber/Basic.lean), `Chow.intersectionNumber` and `Chow.Num` on surfaces (AlgebraicGeometry/Chow/SurfaceIntersection.lean).
- Ready now: no: §1.1 needs Layer 0 (§0.4 `Pic^τ(X/S)`, §§0.6–0.7); §1.5 needs §1.4; §1.7(ii) needs SchemeAndStackFoundations §§5.2–5.3 (§5.2 partial, §5.3 not started).
- Serves defs: 95 (through open PR #2431, which imports §§0.1, 1.1, 1.5–1.7)
- Evidence: README l.244 "## Layer 1: numerical groups, cones, nefness and bigness", l.246 "### 1.1 The relative numerical group Num(X/S)", l.335 "### 1.5 Relatively nef invertible sheaves", l.387 "### 1.7 Ampleness, the Nakai–Moishezon criterion and Kleiman's criterion"; Dependencies l.442.
