Download Link: https://assignmentchef.com/product/solved-blg549e-graph-theory-main
<br>
<h1></h1>

You need to have Python and Pip installed in your computer to install Jupyter Notebook.

Windows

On command prompt (cmd.exe with admin mode):

C:**path**&gt; <sup>python </sup>−m pip install jupyter

After changing your current folder to the folder which you want to work on (see ’cd’ command):

C:**your_working_folder**&gt; jupyter notebook

Then it will be launched on your default browser

<h2>Ubuntu/Linux/Unix/Mac</h2>

On Terminal: $ pip install notebook

Then launch with:

$ jupyter notebook

For more information: <a href="https://jupyter.org/install">https://jupyter.org/install</a>

<h1>Introduction</h1>

You will carry out all the tasks below using <strong>Ipython Notebook</strong>. Simply add all your work to the provided template file <strong>HW1_template.ipynb </strong>using jupyter notebook. In this homework, you will code up several experiments in Oldham et al. paper[3] (<a href="https://drive.google.com/file/d/1I1YmLbqiN4nktWsZ3_p-0M5MhFszGYvN/view">You </a><a href="https://drive.google.com/file/d/1I1YmLbqiN4nktWsZ3_p-0M5MhFszGYvN/view">can click anywhere on this sentence instead of a small, hard-to-click word “here” to </a><a href="https://drive.google.com/file/d/1I1YmLbqiN4nktWsZ3_p-0M5MhFszGYvN/view">find the paper</a><a href="https://drive.google.com/file/d/1I1YmLbqiN4nktWsZ3_p-0M5MhFszGYvN/view">)</a>.To this aim, first simulate 40 networks: 20 unconstrained weighted using Erdos-Renyi generative model [1] and 20 constrained unweighted using MaslovSneppen algorithm [2]. For more details, check the attached supplementary material. For this task, you can use ready-made pieces of code. But all needs to be commented out. The number of nodes in each network category (e.g., ER) should equal to 200.

<h2>Part A Simulate random weighted and unweighted networks</h2>

<ol>

 <li>Briefly explain how Erdos-Renyi generative model works.</li>

 <li>What are the key properties of Erdos-Renyi graphs?</li>

 <li>Briefly explain how Maslov-Sneppen algorithm works.</li>

 <li>What are the key properties of Maslov-Sneppen graphs?</li>

 <li>Visualize two random graphs you simulated (ER and MS).</li>

</ol>

Figure 1: Example visualization of two graphs.

<h2>Part B: Analyzing Erdos-Renyi and Maslov-Sneppen graphs using centrality measures</h2>

<ol>

 <li><strong> </strong>Code up the necessary steps to reproduce plots A and B in Figure 2 using the Centrality Measure Correlation(CMC)s of the 40 networks you simulated: 20 weighted Erdos-Renyi and 20 unweighted Maslov-Sneppen networks.</li>

 <li>What conclusions can you derive from the plots?</li>

</ol>

Figure 2: <strong>Distributions of Centrality Measure Correlations (CMCs) for example unweighted and weighted networks. </strong>Distributions of CMCs for every pair of centrality measures for five example unweighted (panel A); and weighted networks (panel B). Networks have been ordered from highest (left) to lowest (right) median CMC. <strong>Both the figure and the caption is from [</strong><strong>3</strong><strong>]</strong>

<ol start="3">

 <li>Code up the necessary steps to reproduce Figure 3 (A to D) using the between-network CMCs of the 40 networks you simulated: 20 weighted ErdosRenyi and 20 unweighted Maslov-Sneppen networks.</li>

 <li>What conclusions can you derive from the plots?</li>

</ol>

Figure 3: <strong>Mean and standard deviation of between-network CMCs. </strong>Panels A and B show the between-network CMC mean and standard deviation for unweighted measures, respectively. Panels C and D show the between-network CMCs mean and standard deviation for weighted measures, respectively. <strong>Both the figure and the caption is from [</strong><strong>3</strong><strong>]</strong>

<ol start="5">

 <li>Plot the CMC distributions using bar plots as in the Figure 4 for your 20 unweighted and 20 weighted networks. What do you notice?</li>

</ol>

Figure 4: Example bar plot of CMC distributions.

Part C: Association between mean within-network Centrality Measure Correlation(CMC) and network properties

<ol>

 <li><strong> </strong>Choose two different network properties (e.g., modularity and density) and regenerate similar plots to Figure 5 by plotting the mean within-network CMC against the selected network property. Erdos-Renyi networks should have the same color (e.g., transparent blue) and Maslov-Sneppen networks can be assigned a different color (e.g., transparent red). You can use existing codes to compute the network properties.</li>

 <li><strong> </strong>Interpret your plots. What conclusions can you derive?</li>

</ol>

Figure 5: <strong>Association between mean within-network CMC and network properties in unweighted networks. </strong>The association between the mean within-network CMC (the average of all CMCs within a single network) and each of the global topological properties. Networks are coloured by their natural category (blue = social, grey = technological, brown = biological, orange = informational, purple = transportation; green = economic). <strong>Both the figure and the caption is from [</strong><strong>3</strong><strong>]</strong>