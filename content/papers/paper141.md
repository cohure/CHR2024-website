
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
<h2>Computational segmentation of Wayang Kulit video recordings using a Cross-Attention Temporal Model</h2>

<section class="metadata">
<p style='font-size:1rem'><i>(short paper)</i></p>
<p><strong>Authors:</strong> Hong Wei Shawn Liew, Miguel Escobar Varela</p>
<p><strong>Presented in</strong> <a href="/programme/#session1A">Session 1A: Visual Arts and Art History</a></p>
<p><strong>Paper:</strong> <a href="https://ceur-ws.org/Vol-3558/paper141.pdf">Download PDF</a></p>
</section>

<section>
<h3>Abstract</h3>
<div class="abstract">
<p>We report preliminary findings on a novel approach to automatically segment Javanese wayang kulit (traditional leather puppet) performances using computational methods. We focus on identifying comic interludes, which have been the subject of scholarly debate regarding their increasing duration. Our study employs action segmentation techniques from a Cross-Attention Temporal Model, adapting methods from computer vision to the unique challenges of wayang kulit videos. We manually labelled 100 video recordings of performances to create a dataset for training and testing our model. These videos, which are typically 7 hours long, were sampled from our comprehensive dataset of 12,638 videos uploaded to a video platform between 03 Jun 2012 and 30 Dec 2023. The resulting algorithm achieves an accuracy of 89.06 %  in distinguishing between comic interludes and regular performance segments, with F1-scores of 96.53 %, 95.91 %, and 92.47 %  at overlapping thresholds of 10 %, 25 %, and 50 %  respectively. This work demonstrates the potential of computational approaches in analyzing traditional performing arts and other video material, offering new tools for quantitative studies of audiovisual cultural phenomena, and provides a foundation for future empirical research on the evolution of wayang kulit performances.</p>
</div>
</section>
</main>