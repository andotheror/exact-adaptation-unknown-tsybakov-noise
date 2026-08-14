# Exact Adaptation to Unknown Tsybakov Noise

## Abstract

The minimax excess-risk rate for a binary class of VC dimension $d$ under Tsybakov noise with exponent $\alpha\in(0,1)$ is 

$$\left(\frac{d+\log(1/\delta)}{n}\right)^{1/(2-\alpha)}.$$

 A recent proper learner attains this rate for every VC class, but it requires both noise parameters. Whether exact adaptation is possible without either parameter was left open. We answer this question affirmatively. Our learner is proper, receives only the class, sample size, and confidence, and simultaneously attains the minimax rate for every fixed tail constant and exponent. There is no $\log\log n$ or other adaptation loss. Ordinary validation over the required $\Theta(\\!\log n)$ noise profiles would incur such a loss. We avoid it through three scale-sensitive devices. First, an off-design analysis of a capped noise-profile learner makes conservative-profile failures decay geometrically with their distance from the true fixed point. Second, a stop-at-first-instability selector charges comparisons to their risk scale instead of the number of profiles. Third, a prior-weighted empirical-Bernstein tournament removes the unknown tail constant while returning one candidate. The key proof is a two-scale concentration argument: deep regional comparisons have large nominal confidence, while shallow comparisons gain variance from the stronger true noise exponent. Their balance makes all profile costs summable. This resolves exact parameter adaptation for arbitrary VC classes while preserving properness and the sharp confidence dependence.

## Keywords

Tsybakov noise, adaptation, proper learning, VC dimension, minimax rates, excess risk, parameter-free learning

## Files

- `main.pdf`
- `main.tex`
- `references.bib`
- `iclr2027_conference.sty`, `iclr2027_conference.bst`, `natbib.sty`, `fancyhdr.sty`
- `main.pdf.ots`, `README.md.ots` OpenTimestamps priority proofs
