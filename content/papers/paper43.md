
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
<h2>Clustering Tasks and Decision Trees with Augustan Love Poets: Cohesion and Separation in Feature Importance Extraction</h2>

<section class="metadata">
<p style='font-size:1rem'><i>(poster)</i></p>
<p><strong>Authors:</strong> Carlos Javier Nusch, Gimena Del Río Riande, Leticia Cagnina, Marcelo Luis Errecalde, Leandro Antonelli</p>
<p><strong>Presented in</strong> <a href='/programme/#postersession'>Poster Session</a></p>
<p><strong>Paper:</strong> <a href="https://ceur-ws.org/Vol-3558/paper43.pdf">Download PDF</a></p>
</section>

<section>
<h3>Abstract</h3>
<div class="abstract">
<p>This article extends various automatic text analysis tasks from previous works by applying natural language processing techniques to a corpus of Latin texts from the 1st century BC and 1st century AD. The motivation behind this work is to delve into and understand a historical literary trend revolving around the themes of love, spanning from antiquity through to the medieval period. The analyzed authors include Gaius Valerius Catullus, Albius Tibullus, and Sextus Propertius, representing the literary movement of the neoterics, and Publius Vergilius Maro and Marcus Annaeus Lucanus, epic poets with distinct styles, serving as control samples. Unlike previous works, various corrections were added to the preprocessing tasks, including improved word tokenization with enclitics and handling of orthographic variances. For the clustering tasks, the K-Means method and the Silhouette Score were used to determine the optimal cluster sizes. Using these optimal clusters as labels, decision trees were trained for each range of n-grams, aiming to identify features with the highest Information Gain and Information Gain Ratio. The trees were trained based on the criterion of Entropy, and calculations of Feature Importance were performed. In this study, we focused on detailing the classification results and features extracted by the decision trees, based on the best Silhouette scores obtained and the Information Gain. We examined whether the words or parts of words with classificatory potential identified in the process matched the findings from previous exploratory tasks performed using other techniques.</p>
</div>
</section>
</main>