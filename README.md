# Overlooked Implications of the Reconstruction Loss for VAE Disentanglement 🎨♟️🚗

**Nathan Michlo**\*, **Richard Klein**\*, **Steven James**\*

_Affiliations_: &nbsp; \* &nbsp; [RAIL Lab](https://www.raillab.org) &nbsp; & &nbsp; [Wits University](https://www.wits.ac.za/)

## Abstract

> Learning disentangled representations with variational autoencoders (VAEs) is often attributed to the regularisation component of the loss. In this work, we highlight the interaction between data and the reconstruction term of the loss as the main contributor to disentanglement in VAEs. We show that standard benchmark datasets have unintended correlations between their subjective ground-truth factors and perceived axes in the data according to typical VAE reconstruction losses. Our work exploits this relationship to provide a theory for what constitutes an adversarial dataset under a given reconstruction loss. We verify this by constructing an example dataset that prevents disentanglement in state-of-the-art frameworks while maintaining human-intuitive ground-truth factors. Finally, we re-enable disentanglement by designing an example reconstruction loss that is once again able to perceive the ground-truth factors. Our findings demonstrate the subjective nature of disentanglement and the importance of considering the interaction between the ground-truth factors, data and notably, the reconstruction loss, which is under-recognised in the literature.

## Resources

This repo contains additional conference resources:

- 📜 [Paper](https://github.com/nmichlo/ijcai-2023-overlooked-implications/blob/main/overlooked-implications__ijcai-2023__paper.pdf)
  &nbsp; (➕ [Extended Paper](https://arxiv.org/pdf/2202.13341.pdf) on arXiv)
- 🖼 [Poster](https://github.com/nmichlo/ijcai-2023-overlooked-implications/blob/main/overlooked-implications__ijcai-2023__poster.pdf)
- 🧑‍🏫 [Presentation](https://github.com/nmichlo/ijcai-2023-overlooked-implications/blob/main/overlooked-implications__ijcai-2023__presentation.pdf)

Code and experiments are extensions to my [🧪 MSc. Research](https://github.com/nmichlo/msc-research)
- VAE frameworks and experiments are run using my [🧶 disent](https://github.com/nmichlo/disent) framework.

## Acknowledgements

> Computations were performed using the High Performance Computing infrastructure provided by the Mathematical Sciences Support unit at the University of the Witwatersrand.
