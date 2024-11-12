
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
<h2>Sub-optimal Recall in Visual Cluster Retrieval: When Clusters Look Like Bridges</h2>

<section class="metadata">
<p style='font-size:1rem'><i>(poster)</i></p>
<p><strong>Authors:</strong> Mathieu Jacomy, Matilde Ficozzi, Anders K. Munk</p>
<p><strong>Presented in</strong> <a href='/programme/#postersession'>Poster Session</a></p>
<p><strong>Paper:</strong> LINK TBA</p>
</section>

<section>
<h3>Abstract</h3>
<div class="abstract">
<p>Force-directed node placement algorithms, a popular technique to visualise networks, are known to optimize ``cluster separability'': when sets of densely connected nodes get represented as well-separated groups of dots. Using these techniques leads us to conceive networks as sets of clusters connected by bridges. This is also how we tend to think of the ``community structure'' model embedded in clustering techniques like modularity maximization. Yet this mental model has flaws. We specifically address the notion that clusters (``communities'') necessarily look like groups of dots, through the mediation of a node placement algorithm. Although often true, we provide a reproducible counterexample: topological clusters that look like bridges. First, we present an empirical case that we encountered in a real world situation, while mapping the academic landscape of AI and algorithms. Second, we show how to generate a network of arbitrary size where a cluster looks like a bridge. In conclusion, we open a discussion about layout algorithms as a visual mediation of a network's community structure. We contend that when it comes to the accuracy of retrieving clusters visually, node placement algorithms have an imperfect recall despite an excellent precision.</p>
</div>
</section>
</main>