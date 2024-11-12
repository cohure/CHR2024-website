
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
<h2>Bootstrap Distance Imposters: High Precision Authorship Verification with Improved Interpretability</h2>

<section class="metadata">
<p style='font-size:1rem'><i>(long paper)</i></p>
<p><strong>Authors:</strong> Ben Nagy</p>
<p><strong>Presented in</strong> <a href="/programme/#session3B">Session 3B: Stylometry</a></p>
<p><strong>Paper:</strong> <a href="https://ceur-ws.org/Vol-3558/paper61.pdf">Download PDF</a></p>
</section>

<section>
<h3>Abstract</h3>
<div class="abstract">
<p>This paper describes an update to the open-source Python implementation of the General Imposters method of authorship verification by Mike Kestemont et al. The new algorithm, called Bootstrap Distance Imposters (henceforth BDI), incorporates a key improvement introduced by Potha and Stamatatos, as well as introducing a novel method of bootstrapping that has several attractive properties when compared to the reference algorithm. Initially, we supply an updated version of the Kestemont et al. code (for Python 3.x) which incorporates the same basic improvements. Next, the two approaches are benchmarked using the problems from the multi-lingual PAN 2014 author identification task, as well as the more recent PAN 2021 task. Additionally, the interpretability advantages of BDI are showcased via real-world verification studies. When operating as a summary verifier, BDI tends to be more conservative in its positive attributions, particularly when applied to difficult problem sets like the PAN2014  en \_ novels. In terms of raw performance, the BDI verifier outperforms all PAN2014 entrants and appears slightly stronger than the improved Kestemont GI according to the PAN metrics for both the 2014 and 2021 problems, while also offering superior interpretability.</p>
</div>
</section>
</main>