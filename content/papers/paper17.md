
<style>    
    h2 {
        margin-top: 0;
        margin-bottom: 1.5rem;
        line-height: 1.3;
    }
    
    h3 {
        margin-top: 2rem;
        margin-bottom: 1rem;
        font-size: 1.4rem;
        font-weight:bold;
    }
    
    .metadata {
        background-color: #f7fafc;
        padding: 1rem;
        border-radius: 6px;
        margin-bottom: 2rem;
    }
    
    .metadata p {
        margin: 0.5rem 0;
    }
    
    .abstract {
        text-align: justify;
        padding: 1rem;
        background-color: #f7fafc;
        border-left: 4px solid #2c5282;
        border-radius: 0 6px 6px 0;
    }
    
    strong {
        color: #2d3748;
        font-weight: 600;
    }
</style>
<main role="main">
<h2>Integrating Visual and Textual Inputs for Searching Large-Scale Map Collections with CLIP</h2>

<section class="metadata">
<p style='font-size:1rem'><i>(long paper)</i></p>
<p><strong>Authors:</strong> Jamie Mahowald and Benjamin Charles Germain Lee</p>
<p><strong>Presented in</strong> <a href="/programme/#session5B">Session 5B: Search & Discovery</a></p>
<p><strong>Paper:</strong> LINK TBA</p>
</section>

<section>
<h3>Abstract</h3>
<div class="abstract">
<p>Despite the prevalence and historical importance of maps in digital collections, current methods of navigating and exploring map collections are largely restricted to catalog records and structured metadata. In this paper, we explore the potential for interactively searching large-scale map collections using natural language inputs (``maps with sea monsters''), visual inputs (i.e., reverse image search), and multimodal inputs (an example map + ``more grayscale''). As a case study, we adopt 562,842 images of maps publicly accessible via the Library of Congress's API. To accomplish this, we use the mulitmodal Contrastive Language-Image Pre-training (CLIP) machine learning model to generate embeddings for these maps, and we develop code to  implement exploratory search capabilities with these input strategies. We present results for example searches created in consultation with staff in the Library of Congress's Geography and Map Division and describe the strengths, weaknesses, and possibilities for these search queries. Moreover, we introduce a fine-tuning dataset of 10,504 map-caption pairs, along with an architecture for fine-tuning a CLIP model on this dataset. To facilitate re-use, we provide all of our code in documented, interactive Jupyter notebooks and place all code into the public domain. Lastly, we discuss the opportunities and challenges for applying these approaches across both digitized and born-digital collections held by galleries, libraries, archives, and museums.</p>
</div>
</section>
</main>