# FullRe

## Paper

FullRe: Full 4D Reconstruction from Casual Videos

## Abstract

From casual videos in daily life, humans can effortlessly recognize 3D object shapes, perceive variations in viewpoints, decompose dynamic objects and infer their motions. This suggests that reconstruction algorithms should also, like humans, simultaneously achieve these capabilities. However, existing methods tackle the aforementioned tasks in multiple stages. The phased processing approaches mean that each stage's performance heavily depends on the preceding one, and the entire reconstruction process cannot be optimized in an end-to-end manner, which limits its overall potential. In response, we present an algorithm, Full 4D Reconstruction(FullRe), designed to simultaneously integrate these capabilities for casual videos in an end-to-end manner. Specifically, we represent the 4D scene in a video as the combination of local multi-view depth maps and a shared canonical space, where a continuous bijective mapping is used to model motions between local and canonical space. We also extend the depth estimation network to decompose scenes into static and dynamic parts, which helps to avoid degenerate cases and leads to accurate tracking. Experiments demonstrate that FullRe performs well on casual videos, and achieves performance comparable to state-of-the-art methods across all tasks.

## Project Page

https://fullre.github.io/FullRe

## Codes

Work in progress
