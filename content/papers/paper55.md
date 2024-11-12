
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
<h2>Visual Navigation of Digital Libraries: Retrieval and Classification of Images in the National Library of Norway’s Digitised Book Collection</h2>

<section class="metadata">
<p style='font-size:1rem'><i>(short paper)</i></p>
<p><strong>Authors:</strong> Marie Roald, Magnus Breder Birkenes and Lars Gunnarsønn Bagøien Johnsen</p>
<p><strong>Presented in</strong> <a href="/programme/#session5">Session 5B: Search & Discovery</a></p>
<p><strong>Paper:</strong> <a href="https://ceur-ws.org/Vol-3558/paper55.pdf">Download PDF</a></p>
</section>

<section>
<h3>Abstract</h3>
<div class="abstract">
<p>Digital tools for text analysis have long been essential for the searchability and accessibility of digitised library collections. Recent computer vision advances have introduced similar capabilities for visual materials, with deep learning-based embeddings showing promise for analysing visual heritage. Given that many books feature visuals in addition to text, taking advantage of these breakthroughs is critical to making library collections open and accessible. In this work, we present a proof-of-concept image search application for exploring images in the National Library of Norway’s pre-1900 books, comparing Vision Transformer (ViT), Contrastive Language-Image Pre-training (CLIP), and Sigmoid loss for Language-Image Pre-training (SigLIP) embeddings for image retrieval and classification. Our results show that the application performs well for exact image retrieval, with SigLIP embeddings slightly outperforming CLIP and ViT in both retrieval and classification tasks. Additionally, SigLIP-based image classification can aid in cleaning image datasets from a digitisation pipeline.</p>
</div>
</section>
</main>