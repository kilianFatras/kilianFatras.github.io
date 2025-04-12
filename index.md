---
layout: default
---

<style>
.profile-container {
    display: flex;
    align-items: center;
    gap: 20px;
}

.profile-image {
    width: 200px; /* Adjust size */
    height: 200px;
    border-radius: 0%;
    transition: opacity 0.3s ease; /* Smooth transition */
}

.profile-image-hover {
    width: 200px; /* Adjust size */
    height: 200px;
    border-radius: 0%;
    opacity: 0; /* Hide the second image by default */
    transition: opacity 0.3s ease; /* Smooth transition */
    position: absolute; /* Position it on top of the first image */
}

.profile-container:hover .profile-image {
    opacity: 0; /* Hide the original image on hover */
}

.profile-container:hover .profile-image-hover {
    opacity: 1; /* Show the second image on hover */
}

.bio-text {
    max-width: 600px;
    text-align: justify; /* Justification du texte */
}

p {
    text-align: justify; /* Justification des paragraphes */
}
</style>

<div class="profile-container">
    <div style="position: relative;">
        <!-- Hover Image (another picture shown on hover) -->
        <img src="images/kilian_over.png" alt="Profile Picture Hover" class="profile-image-hover">
        <!-- Original Profile Picture -->
        <img src="images/kilian_new.jpg" alt="Profile Picture" class="profile-image">
    </div>
    <div class="bio-text">
        <h2><b>Machine Learning Research Scientist</b></h2>
        <h3>Training Foundation Models to Decode the Complexity of Life</h3>
    </div>
</div>
<br>

## **About Me**

I am a **machine learning research scientist** at [EvolutionaryScale](https://www.evolutionaryscale.ai/). Leveraging my expertise in **computational biology** and **generative AI**, I build **foundation models**—from protein language models to diffusion-based architectures—to **understand biological systems** and **design functional proteins** for real-world applications in **drug discovery** and **structural biology**.

Previously, I was a **Postdoctoral Fellow** at **Mila** and **McGill University** in Montréal, where I worked under the mentorship of **Prof. Adam Oberman** and **Prof. Ioannis Mitliagkas**. My research during this time focused on **generative modeling**, **distribution shifts**, and **optimal transport**. I began applying these methods to **single-cell trajectory inference** and **protein design**, and I co-created the open-source **[TorchCFM](https://github.com/torchcfm/torchcfm)** library to share our work on **Flow Matching generative models**.

I completed my **PhD** at **INRIA Rennes** in Brittany, France, under the supervision of **Prof. Nicolas Courty** and **Prof. Rémi Flamary**. My work explored the intersection of **optimal transport** and **deep learning**, with applications to **domain adaptation**, **noisy label learning**, and **generative modeling**. I developed expertise in **minibatch approximations for optimal transport**, and my [thesis defense](https://www.youtube.com/watch?v=paqpidEnnHw) and [manuscript](pdf/thesis_kf.pdf) are both available online.

My résumé can be found [here](pdf/cv_kilian_fatras.pdf) *(last updated: April 2025)*. Outside of research, I enjoy exploring New York City with my wife and love getting outdoors—whether it's **hiking** in the Hudson Valley or **scuba diving** in the Caribbean.

---

## **Research Interests**

For a complete list of my publications, visit my [Google Scholar](https://scholar.google.ca/citations?hl=fr&user=DHMjyDgAAAAJ&view_op=list_works). My current areas of focus include:

- **Next-Generation Generative Models**  
   - Designing novel **diffusion models** and **flow matching techniques** for protein modeling, computer vision, and tabular data.  
   - Advancing **discrete generative modeling** through **masked language models**, **discrete diffusion**, and **discrete flow matching**.

- **Protein Structure and Sequence Generation**  
   - Building deep generative frameworks for **3D protein backbone generation** and **sequence optimization**.  
   - Modeling **molecular evolution** and generating **functional proteins** through learned priors and structure-aware objectives.  
   - Engineering **protein-protein interactions**, **binder design**, and **multimer assembly** via **spatial constraints**, **evolutionary signals**, and **machine learning-based docking**.

---

**Feel free to reach out** if you’re interested in collaborating or discussing any of these research areas!
