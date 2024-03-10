# Knowledge-Graph

Why Knowledge graph:

Some might argue that powerful attention mechanisms can automatically learn the syntactic and semantic relationships. Though no theoretical work is out there in my knowledge which highlights where is attention ineffective. Here is an example- let’s consider the task of aspect-based sentiment analysis (finding sentiment for each feature- If we are trying to get sentiment for our brand we can get sentiment for different features like- fitting, material, shipping, etc.- These all are different aspects) Now if the sentence given to the network is-

“Its size is ideal and the weight is acceptable.” Attention-based models often identify acceptable as a descriptor of the aspect size, which is in fact not the case. In order to address the issue (He et al.) imposed some syntactical constraints on attention weights.

This gives us a slight hint of why we could use dependency parse as additional information in our NLP applications.
