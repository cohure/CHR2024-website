
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
<h2>Early Modern Book Catalogues and Multilingualism: Identifying Multilingual Texts and Translations using Titles</h2>

<section class="metadata">
<p style='font-size:1rem'><i>(long paper)</i></p>
<p><strong>Authors:</strong> Yann Ryan and Margherita Fantoli</p>
<p><strong>Presented in</strong> <a href="/programme/#session6B">Session 6B: Multilingualism & Translation Studies</a></p>
<p><strong>Paper:</strong> LINK TBA</p>
</section>

<section>
<h3>Abstract</h3>
<div class="abstract">
<p>With this paper we aim to assess whether Early Modern book titles can be exploited to track two aspects of multilingualism in book publishing: publications featuring multiple languages and the distinction between editions of works in their original language and in translation. To this scope we leverage the manually annotated language information available in two book catalogs: the Collectio Academica Antiqua, recording publications of scholars of the Old University of Leuven (1425-1797) and a subset of the Eighteenth Century Collections Online, namely publications of Ancient Greek and Latin works. We evaluate three different approaches: we train a simple tf-idf based support vector classifier, we fine-tune a multilingual transformer model (BERT) and we use a few-shot approach with a pre-trained sentence transformer model. In order to get a better understanding of the results, we make use of SHAP, a library for explaining the output of any machine Learning model. We conclude that while the few-shot prediction is not currently usable for this task, the tf-idf approach and BERT fine-tuning are comparable and both usable. BERT shows  better results for the task of identifying translations and when generalizing across different datasets.</p>
</div>
</section>
</main>