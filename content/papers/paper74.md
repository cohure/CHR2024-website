
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
<h2>Direct and Indirect Annotation with Generative AI: A Case Study into Finding Animals and Plants in Historical Text</h2>

<section class="metadata">
<p style='font-size:1rem'><i>(short paper)</i></p>
<p><strong>Authors:</strong> Arjan van Dalfsen, Folgert Karsdorp, Ayoub Bagheri, Dieuwertje Mentink, Thirza van Engelen and Els Stronks</p>
<p><strong>Presented in</strong> <a href="/programme/#session6A">Session 6A: Annotation</a></p>
<p><strong>Paper:</strong> LINK TBA</p>
</section>

<section>
<h3>Abstract</h3>
<div class="abstract">
<p>This study explores the use of generative AI (GenAI) for annotation in the humanities, comparing direct and indirect annotation approaches with human annotations. Direct annotation involves using GenAI to annotate the entire corpus, while indirect annotation uses GenAI to create training data for a specialized model. The research investigates zero-shot and few-shot methods for direct annotation, alongside an indirect approach incorporating active learning, few-shotting, and k-NN example retrieval. The task focuses on identifying words (also referred to as entities) related to plants and animals in Early Modern Dutch texts. Results show that indirect annotation outperforms zero-shot direct annotation in mimicking human annotations. However, with just a few examples, direct annotation catches up, achieving similar performance to indirect annotation. Analysis of confusion matrices reveals that GenAI annotators make similar types of mistakes, such as confusing parts and products or failing to identify entities, which are broader than those made by humans. Manual error analysis indicates that each annotation method (human, direct, and indirect) has some unique errors. Given the limited scale of this study, it is worthwhile to further explore the relative affordances of direct and indirect GenAI annotation methods.</p>
</div>
</section>
</main>