
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
<h2>Remember to Forget: A Study on Verbatim Memorization of Literature in Large Language Models</h2>

<section class="metadata">
<p style='font-size:1rem'><i>(long paper)</i></p>
<p><strong>Authors:</strong> Xinhao Zhang, Olga Seminck, Pascal Amsili</p>
<p><strong>Presented in</strong> <a href="/programme/#session4A">Session 4A: Large Language Models</a></p>
<p><strong>Paper:</strong> LINK TBA</p>
</section>

<section>
<h3>Abstract</h3>
<div class="abstract">
<p>We examine the extent to which English and French literature is memorized by freely accessible LLMs, using a name cloze inference task (which focuses on the model's ability to recall proper names from a book). We replicate the key findings of previous research conducted with OpenAI models, concluding that, overall, the degree of memorization is low. Factors that tend to enhance memorization include the absence of copyrights, belonging to the Fantasy or Science Fiction genres, and the work's popularity on the Internet. Delving deeper into the experimental setup using the open source model Olmo and its freely available corpus Dolma, we conducted a study on the evolution of memorization during the LLM’s training phase. Our findings suggest that excerpts of a book online can result in some level of memorization, even if the full text is not included in the training corpus. This observation leads us to conclude that the name cloze inference task is insufficient to definitively determine whether copyright violations have occurred during the training process of an LLM. Furthermore, we highlight certain limitations of the name cloze inference task, particularly the possibility that a model may recognize a book without memorizing its text verbatim. In a pilot experiment, we propose an alternative method that shows promise for producing more robust results.</p>
</div>
</section>
</main>