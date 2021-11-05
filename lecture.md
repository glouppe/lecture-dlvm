class: middle, center, title-slide

# Deep latent variable models

TRAIL doctoral seminars

November 5, 2021

<br><br>
Prof. Gilles Louppe<br>
[g.louppe@uliege.be](mailto:g.louppe@uliege.be)

---

class: middle

.center.circle.width-30[![](figures/lec9/feynman.jpg)]

.italic.center["What I cannot create, I do not understand."]

.pull-right[Richard Feynman]

---

class: middle

A **generative model** is a probabilistic model $p$ that can be used as *a simulator of the data*.
Its purpose is to generate synthetic but realistic high-dimensional data
$$\mathbf{x} \sim p(\mathbf{x};\theta),$$
that is as close as possible from the unknown data distribution $p(\mathbf{x})$.

---

class: middle 

## Why generative models

.center[
.width-100[![](figures/lec9/why-gm.png)]

Generative models have a role in many important problems]

---

count: false
class: middle

# Part I: Variational inference

---

class: middle, black-slide

.center[<video controls autoplay loop muted preload="auto" height="480" width="640">
  <source src="./figures/lec9/galton.mp4" type="video/mp4">
</video>]

---

class: middle, center

See blackboard.

---

count: false
class: middle

# Part II: Variational auto-encoders

---

class: middle, center

See blackboard.

---

class: middle, center

See code example 1.

---

# Examples

Consider as data $\mathbf{d}$ the MNIST digit dataset:

.center.width-100[![](figures/lec9/mnist.png)]

---

class: middle, center

.width-100[![](figures/lec9/vae-samples.png)]

(Kingma and Welling, 2013)

---

class: middle, center

.width-100[![](figures/lec9/vae-interpolation.png)]

(Kingma and Welling, 2013)

---

class: middle

.center[
.width-100[![](figures/lec9/generative-compression.png)]

Hierarchical .bold[compression of images and other data], e.g., in video conferencing systems (Gregor et al, 2016).
]

---

class: middle

.center[
.width-100[![](figures/lec9/generative-factors.png)]

.bold[Understanding the factors of variation and invariances] (Higgins et al, 2017).
]

---

class: middle 

.center[

.width-80[![](figures/lec9/vae-styletransfer.jpg)]

.bold[Voice style transfer] [[demo](https://avdnoord.github.io/homepage/vqvae/)] (van den Oord et al, 2017).
]

---

class: middle

.center.width-100[![](figures/lec9/bombarelli.jpeg)]

.center[.bold[Design of new molecules] with desired chemical properties (Gomez-Bombarelli et al, 2016).]

---

class: middle, black-slide

.center[

<iframe width="640" height="400" src="https://www.youtube.com/embed/Wd-1WU8emkw?&loop=1&start=0" frameborder="0" volume="0" allowfullscreen></iframe>

Bridging the .bold[simulation-to-reality] gap (Inoue et al, 2017).

]

---

count: false
class: middle

# Part III: Hierarchical VAEs

---

class: middle, center

See blackboard.

---

class: middle

.center.width-90[![](figures/vdvae_diagram.png)]

.center[VDVAE: Very Deep VAEs (Child, 2020-2021).]

---

class: middle

.center.width-70[![](figures/vdvae_samples.png)]

.center[VDVAE samples (Child, 2020-2021).]

---

class: middle

.center.width-100[![](figures/nvae_model_diagram.png)]

.center[NVAE: A Deep Hierarchical Variational Autoencoder (Vahdat and Kautz, 2020).]

---

class: middle

.center.width-90[![](figures/nvae_samples.png)]

.center[NVAE samples (Vahdat and Kautz, 2020).]

---

class: black-slide, middle

.center[
.width-60[![](figures/lec9/nvae.gif)]

NVAE: Random walks in latent space. (Vahdat and Kautz, 2020)

]

---

count: false
class: middle

# Part IV: Denoising diffusion probabilistic models

---

class: middle, center

See blackboard.

---

class: middle

.center.width-100[![](figures/pgm_diagram_xarrow.png)]

.center[Denoising Diffusion Probabilistic Models (Ho et al, 2020).]

---

class: middle

.center.width-100[![](figures/ddpm_samples.png)]

.center[DDPM samples (Ho et al, 2020).]

---

class: middle

.center.width-100[![](figures/score_sde_diagram.jpg)]

.center[Score-based generative modeling through SDEs (Song et al, 2021).]

---

class: middle

.center.width-100[![](figures/perturb_vp.gif)]

.center[Perturbing data with an SDE (Song et al, 2021)]

---

class: middle

.center.width-100[![](figures/denoise_vp.gif)]

.center[Reversing the SDE for sample generation (Song et al, 2021)]

---

class: middle

.center.width-100[![](figures/score_sde_samples.jpg)]

.center[(Song et al, 2021)]

---

count: false
class: middle

# Part V: Priors

---

class: middle, center

See blackboard.

---

class: middle

.center.width-100[![](figures/dp_samples.png)]

.center[Diffusion priors in VAEs (Wehenkel and Louppe, 2021).]

---

class: middle

.center.width-100[![](figures/lsgm_diagram.jpeg)]

.center[LSGM: Latent Score-based Generative Model (Vahdat et al, 2021).]

---

class: middle

.center.width-100[![](figures/lsgm_samples.jpeg)]

.center[LSGM samples (Vahdat et al, 2021).]

---

class: end-slide, center
count: false

The end.
