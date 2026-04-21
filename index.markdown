---
layout: home
---

<style>
    .logo-row {
      display: flex;
      flex-direction: row;
      justify-content: center;
      align-items: center;
      gap: 2.5rem;
      flex-wrap: wrap;
    }

    .logo-item {
      display: flex;
      justify-content: center;
      align-items: center;
      transition: transform 0.25s ease, filter 0.2s;
    }

    .logo-img {
      height: 150px;
      width: auto;
      max-width: 100%;
      object-fit: contain;
      display: block;
    }

    @media (max-width: 768px) {
      .logo-row {
        flex-direction: column;
        gap: 2rem;
        align-items: center;
      }

      .logo-img {
        height: 150px;
      }
    }

    @media (max-width: 480px) {
      .logo-row {
        gap: 1.75rem;
      }
    }

    @media (max-width: 320px) {
      .logo-img {
        height: 150px;
        max-width: 90vw;
      }
    }

</style>

Large-scale digitization initiatives are generating massive image datasets from natural history collections. Computer vision is essential for unlocking the scientific value of these data, enabling automated extraction of specimen information and supporting research in biodiversity, ecology, and evolution, including studies of migration and ongoing mass extinction. However, despite controlled imaging conditions and rich metadata, automated analysis remains challenging due to complex specimen structures, varying appearances, and handwritten labels.

The <b>Computer Vision for Natural Heritage (CVNH) is an <font size="+1">ECCV workshop</font></b> that brings together computer vision researchers, natural heritage digitization experts, and domain scientists to advance methods for analyzing 2D, 3D, and multi-modal imaging of natural history collections and to identify open challenges.

CVNH workshop has a <b><font color="red">Call for Papers</font></b> and presents two Challenges:

* <b>Forams</b>: Detection and classification of microCT 3D scans of Forameniferas,
* <b>OCR Museum Labels</b>: Optical Character Recognition of Museum label images.

Top-performing teams of the Forams challenge will be invited to participate in a paper related to the challenge.

<iframe width="480px" height="580px" src="https://forms.cloud.microsoft/Pages/ResponsePage.aspx?id=I_FR8s7JjkSSdzS7KFkR2TMT5yfaW_hGvFBYipukVclUN1BVUVpFWE1YT1FTM0c3N0hYTE9BS0lSNy4u&amp;embed=true" scrolling="no" frameborder="0" marginwidth="0" marginheight="0" style="border: none; max-width:100%; max-height:100vh" allowfullscreen="" webkitallowfullscreen="" mozallowfullscreen="" msallowfullscreen="" spellcheck="false"> </iframe>

<br><br>

<div class="logo-row">

<div class="logo-item">
  <img class="logo-img" src="/assets/images/dtu_logo.png" alt="DTU logo"
       loading="lazy">
</div>

<!-- Logo 2: Mid-century modern style (using placeholder with brand feel) -->
<div class="logo-item">
  <img class="logo-img" src="/assets/images/ku_logo.png" alt="KU logo"
       loading="lazy">
</div>

<!-- Logo 3: Tech / futuristic logo -->
<div class="logo-item">
  <img class="logo-img" src="/assets/images/snm_logo.png" alt="SNM logo"
       loading="lazy">
</div>
</div>
