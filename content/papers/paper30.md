
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
<h2>Does Context Matter? Enhancing Handwritten Text Recognition with Metadata in Historical Manuscripts</h2>

<section class="metadata">
<p style='font-size:1rem'><i>(long paper)</i></p>
<p><strong>Authors:</strong> Benjamin Kiessling and Thibault Clérice</p>
<p><strong>Presented in</strong> <a href="/programme/#session4">Session 4B: Automatic Text Recognition</a></p>
<p><strong>Paper:</strong> <a href="https://ceur-ws.org/Vol-3558/paper30.pdf">Download PDF</a></p>
</section>

<section>
<h3>Abstract</h3>
<div class="abstract">
<p>The digitization of historical manuscripts has significantly advanced in recent decades, yet many documents remain as images without machine-readable text. Handwritten Text Recognition (HTR) has emerged as a crucial tool for converting these images into text, facilitating large-scale analysis of historical collections. In 2024, the CATMuS Medieval dataset was released, featuring extensive diachronic coverage and a variety of languages and script types. Previous research indicated that model performance degraded on the best manuscripts over time as more data was incorporated, likely due to over-generalization. This paper investigates the impact of incorporating contextual metadata in training HTR models using the CATMuS Medieval dataset to mitigate this effect. Our experiments compare the performance of various model architectures, focusing on Conformer models with and without contextual inputs, as well as Conformer models trained with auxiliary classification tasks. Results indicate that Conformer models utilizing semantic contextual tokens (Century, Script, Language) outperform baseline models, particularly on challenging manuscripts. The study underscores the importance of metadata in enhancing model accuracy and robustness across diverse historical texts.</p>
</div>
</section>
</main>