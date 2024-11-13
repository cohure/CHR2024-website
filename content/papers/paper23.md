
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
        background-color: rgba(96,24,67,0.03);
        padding: 1rem;
        font-size:0.8rem;
        border-radius: 6px;
        margin-bottom: 2rem;
    }
    
    .metadata p {
        margin: 0.5rem 0;
    }
    
    .abstract {
        text-align: justify;
        font-size:0.8rem;
        padding: 1rem;
        background-color: rgba(96,24,67,0.03);
        border-left: 4px solid #2c5282;
        border-radius: 0 6px 6px 0;
    }
    
    strong {
        color: #2d3748;
        font-weight: 600;
    }
</style>
<main role="main">
<h2>Catching Feelings: Aspect-Based Sentiment Analysis for Fanfiction Comments about Greek Myth</h2>

<section class="metadata">
<p style='font-size:0.8rem'><i>(short paper)</i></p>
<p><strong>Authors:</strong> Julia Neugarten, Tess Dejaeghere, Pranaydeep Singh, Amanda Robin Hemmons and Julie M. Birkholz</p>
<p><strong>Presented in</strong> <a href="/programme/#session<NA>nan">Poster Session</a></p>
<p><strong>Paper:</strong> LINK TBA</p>
</section>

<section>
<h3>Abstract</h3>
<div class="abstract">
<p>The application of sentiment analysis in literary studies has been limited and often criticized, yet aspect-based sentiment analysis (ABSA) offers interesting applications in this domain because it addresses some limitations of traditional SA tools and provides a more detailed and context-sensitive analysis of sentiment. To investigate its usage in literary reception studies, we apply ABSA to a corpus of ±25,000 comments written by readers in response to fanfiction about Greek mythology on fanfiction website  Archive of Our Own (AO3), one of the largest platforms for fanfiction in English. Our ABSA pipeline detects sentiment (positive/negative) associated with eight aspects of fanfiction stories (general evaluation, Greek mythology, character, character emotion, reading experience, writing style, events and storyworld, and non-specific sentiment). We explain the process of data collection and annotation and present a small inter-annotator agreement study (Pairwise Cohen’s   0.86 for aspects and 0.88 for sentiments). We develop, evaluate, and fine-tune a machine-learning pipeline for ABSA, tackling the aspect extraction and sentiment analysis tasks respectively. We obtain the best results using NuNER for aspect extraction (0.5 macro F1) and Twitter-roBERTa-sentiment for sentiment analysis (0.75 macro F1). Finally, we outline some avenues for future research and reflect on the generalizability of our method to other domains, especially to fanfiction from other fandoms and platforms but also other social media.</p>
</div>
</section>
</main>