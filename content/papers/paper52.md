
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
<h2>Extracting Social Connections from Finnish Karelian Refugee Interviews Using LLMs</h2>

<section class="metadata">
<p style='font-size:0.8rem'><i>(long paper)</i></p>
<p><strong>Authors:</strong> Joonatan Laato, Jenna Kanerva, John Loehr, Virpi Lummaa and Filip Ginter</p>
<p><strong>Presented in</strong> <a href="/programme/#session1B">Session 1B: Classification & Information Extraction</a></p>
<p><strong>Paper:</strong> <a href="https://ceur-ws.org/Vol-3834/paper52.pdf">Download PDF</a></p>
</section>

<section>
<h3>Abstract</h3>
<div class="abstract">
<p>We performed a zero-shot information extraction study on a historical collection of 89,339 brief Finnish-language interviews of refugee families relocated post-WWII from Finnish Eastern Karelia. Our research objective is two-fold. First, we aim to extract social organizations and hobbies from the free text of the interviews, separately for each family member. These can act as a proxy variable indicating the degree of social integration of refugees in their new environment. Second, we aim to evaluate several alternative ways to approach this task, comparing a number of generative models and a supervised learning approach, to gain a broader insight into the relative merits of these different approaches and their applicability in similar studies.  We find that the best generative model (GPT-4) is roughly on par with human performance, at an F-score of 88.8 %. Interestingly, the best open generative model (Llama-3-70B-Instruct) reaches almost the same performance, at 87.7 %  F-score, demonstrating that open models are becoming a viable alternative for some practical tasks even on non-English data. Additionally, we test a supervised learning alternative, where we fine-tune a Finnish BERT model (FinBERT) using GPT-4 generated training data. By this method, we achieved an F-score of 84.1 %  already with 6K interviews up to an F-score of 86.3 %  with 30k interviews. Such an approach would be particularly appealing in cases where the computational resources are limited, or there is a substantial mass of data to process.</p>
</div>
</section>
</main>