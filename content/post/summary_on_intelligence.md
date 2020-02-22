+++
title = "Summary of On Intelligence by Jeff Hawkins"

date = 2020-02-15T00:00:00
lastmod = 2020-02-22T00:22:30
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["SM Mazharul Islam"]

tags = ["Common Knowledge", "Book Summary"]
summary = "From biological brain to artificial general intelligence. Description of the whole framework."

[header]
image = ""
caption = ""

+++

## 1. Intelligence and Biological Brain

The key concept in understanding intelligence is that understanding is an intrinsic concept happens within the agent who is trying to understand something. External behavious is not a good indicator of understanding or intelligence. 

Three major things are essential to understanding the brain. 

1. Inclusion of Temporal Aspect to data
2. Importance of Feedback
3. Physical architecture of the brain

## 2. Neo-Cortical Memory

It is because biological brains retrives answer of a problem from memory rather than computing the solution everytime, it seems so fast compared to conventional computers. This neocortical memory is different than computer memory in the following aspects:

1. The neocortex stores sequences of patterns.
2. The neocortex recalls patterns auto-associatively.
3. The neocortex stores patterns in an invariant form.
4. The neocortex stores patterns in a hierarchy.

## 3. Neo-Cortex

The neocortex is the part that probably contributes the most to our human-level intelligence. This thin multi-layer structure that encompasses the old brain is the place where learning takes place. It is mainly consisted of columns of neuron cells (6 cells per column in human neo-cortex) stacked tightly. Cells of same column has both feed-forward and feedback connections, usually feedback connection outnumbering feed-forward by a factor of 10. Also there are lateral connection among cells of the same hierarchy level. The notion of hierarchy and majority-feedback connections are of utmost importance. 

In an usual human brain, different regions of neo-cortex are assigned with different tasks, like region for processing auditory signal, region for processing visual signal etc. However, it has been proven that all the regions have the same hierarchical structure and have the capability to process different signals if they were connected with different signals/sensors. There are also higher level association regions that receive input from different sensors.


## 4. Major Functionalities of Neo-cortex

### 4.1 Invarient Representation of Our Experiences

Neo-cortex uses heirarchical memory storage system with feedback signals to predict about our next experience. This predictions process is never-ending but our attention is drawn towards them when the prediction do no meet the experience (input through sensors). As the signal travels up the hierarchy, the signal gets converted from being spatially variant, fast changing, small-scale-features into spatially invariant, slow changing, large-scale-features.

{{< figure src="/img/invarient-representations.png" title="Forming invariant representations in hearing, vision, and touch. Images from On Intelligence (2004).  " numbered="true" lightbox="true" width="50%">}}


### 4.2 Multi-Sensory Predictions and Unified Sensory Experiences 

Input signal from one sensory organ can be fed back and propagated down through connected paths of associated memory of other sensory organs. This can evoke prediction from other sensors while input was received through another sensor. This type of associative multi-sensory prediction are in the root of incidents like "if someone calls my name, I hear it, but involuntarily I move my face into the direction of the sound source, and expect to see the caller. Even though I didnt receive any signal thorugh my visual cortex"

{{< figure src="/img/create-prediction-and-unified-sensory-exp.png" title="Information flows up and down sensory hierarchies to form predictions and create a unified sensory experience. Images from On Intelligence (2004).  " numbered="true" lightbox="true" width="50%">}}


### 4.3 Sequence of Sequences and Hierarchical Processing of Information

Everything around us is built with a highly hierarchical structures. Like, electrons-protons-neutrons are forming atoms. Atoms are forming molecules, molecules forming compounds, then complex structures like a living human, an airplane, human-cortex is created. The underlying electron-proton-neitron are still same. So, through evolution, to memorize experience from this highly hierarchical surroundings, cortex has also developed ways to memorize hierarchical structures. Hence, memory inside each cortex regions are best described as sequence of sequences.

When a region of cortex is presented with some input, first it classifies the input into one of the limited number of possibilities, then looks for sequences. If lower regions of cortex fail to predict what patterns they are seeing, they consider this an error and pass the error up the hierarchy. This is repeated until some region does anticipate the pattern. Due to the formation of these sequences ambiguous inputs can be deciphered from the context (realizing that the current input is part of a previously experienced sequence).

Also due to these sequences each cortical regions can anticipate about what might be the next input that is most likely to come up (predicting a little ahead into the future, probably that is what intelligence is). This future prediction is propagated down to the lower cortical regions and gives them a heads up on what sort of input is to expect next. So, it's like the higher regions are giving a context to the lower regions, and the lower regions look for related sequences within the input stream.

## 5. Common Cortical Algorithm

To make the cortex symmetric and homogeneous in every region and every layer, the following model is proposed. This model shows that the cortex do not care in which region or in which layer it currently belongs. Rather it does the same operation everywhere, relay converging information from lower sub-regions to higher higher association areas and send down feedback signals from higher association regions to lower sub-regions. This explain why cortex is not domain-specific, rather it treats all the incoming pattern and feedback signals universally same. This is known as "Common Cortical Algorithm"

{{< figure src="/img/common-cortical-algorithm.png" title="Alternate view of the cortical hierarchy. Images from On Intelligence (2004).  " numbered="true" lightbox="true" width="50%">}}


## 6. Architecture of Neo-Cortex

### 6.1 Neuron Cells of Neo-Cortex

These are the main building blocks of neo-cortex. Each cell has a cell body, axons, dendrites.  When the axon from one neuron touches the dendrite of another, they form small connections called synapses. Synapses can be excitatory or inhibitory, when it comes to influencing the cell body to fire a spike. The strength of these synapses can change (example is when two neurons spike at the same time, connections between them strengthens). Also, entire new synapse can be formed between two neurons. These formation and strengthening of synapses cause our memory to be stores. There are different types of neuron cells such as pyramidal cells, star cells, large pyramidal cells etc.


### 6.2 A Region of Neo-Cortex - Layers and Columns

Each major region of the neo-cortex is comprised of lots of smaller regions. However, everywhere we can see six layers of cortical tissues. The top, called layer 1, is the most distinct of the six layers. It has very few cells, consisting primarily of a mat of axons running parallel to the cortical surface. Layers 2 and 3 look similar. They contain many tightly packed pyramidal cells. Layer 4 has a type of star-shaped cell. Layer 5 has regular pyramidal cells as well as a class of extra-big pyramid-shaped cells. The bottom layer, layer 6, also has several types of unique neurons.

{{< figure src="/img/layers-and-columns-of-cortex.png" title="Layers and columns in a region of cortex. Images from On Intelligence (2004).  " numbered="true" lightbox="true" width="50%">}}


There are column-like structures that run parpendicular to the layers, and the cells of each column work together, are tightly connected by axons and tend to get activated by the same input/stimulus. Specifically, an active cell in layer 4 causes cells above it in layers 3 and 2 to become active, which then cause cells below in layers 5 and 6 to become active. Activity spreads up and down within a column of cells.  At least 90 percent of the synapses on cells within each column come from places outside the column itself. Some connections arrive from neighboring columns. Others come from halfway across the brain.


### 6.3 The Information Highways: Upward and Downward Flow

Converging inputs from lower regions always arrive at layer 4— the main input layer. In passing, they also form a connection in layer 6 (we'll see later why this is important). Layer 4 cells then send projections up to cells in layers 2 and 3 within their column. When a column projects information up, many layer 2 and layer 3 cells send axons to the input layer of that next higher region. Thus information flows from region to region, going up through the hierarchy.

{{< figure src="/img/upward-flow-of-info.png" title="Upward flow of information through a region of cortex. Images from On Intelligence (2004).  " numbered="true" lightbox="true" width="50%">}}

{{< figure src="/img/downward-flow-of-info.png" title="Downward flow of information through a region of cortex. Images from On Intelligence (2004).  " numbered="true" lightbox="true" width="50%">}}


As information flows down the hierarchy, it has a less direct route. It can branch in many different directions via the spread on layer 1. Feedback information starts in a layer 6 cell in the higher region; it spreads across layer 1 in the lower region. There are very few cells in layer 1, but cells in layers 2, 3, and 5 have dendrites in layer 1, so these cells can be excited by the feedback running all across layer 1. Some cells in layers 2, 3, and 5 in the lower region are excited, and some of these excite layer 6 cells, which project to layer 1 in regions hierarchically below, and so on.


### 6.4 Delayed Feedback Connections Through Thalamus

When the output of a group of artificial neurons is fed back to form the input to all the neurons, and a delay is added to the feedback, then patterns learn to follow each other in sequence. Cortical algorithm performs this delayed feedback with the help of Thalamus. Layer 5 cells throughout multiple cortical regions project to the thalamus, which sends the information back to layer 1 of those same and associated regions.

{{< figure src="/img/with-thalamus.png" title="How current state and current motor behavior is communicated broadly via the thalamus. Images from On Intelligence (2004)." numbered="true" lightbox="true" width="50%">}}

Hence, there are two inputs to layer 1. Higher regions of cortex spread activity across layer 1 in lower regions. Active columns within a region also spread activity across layer 1 in the same region via the thalamus. We can think of these
inputs to layer 1 as the name of a song (input from above) and where we are in a song (delayed activity from active columns in the same region). Thus layer 1 carries much of the information we need to predict when a column should be active— the sequence name and where we are within the sequence. Using these two signals in layer 1, a region of cortex can learn and recall multiple sequences of patterns


## 7. How the Magic Happens

To understand how a region of cortex does what it does, we want to know the follwoings:

1. How does a region of cortex classify its inputs (like the buckets)?

- The layer 4 cells in every column receive input fibers from several regions below it and will fire if they have the right combination of inputs. When a layer 4 cell fires, it is "voting" that the input fits its label. Inputs can be ambiguous, so several columns might be possible matches for the input. To decide on one interpretation, a column with strong input should prevent other columns from firing. Brains have inhibitory cells that do just this. These inhibitory cells only affect the area surrounding a column. So even though there is a lot of inhibition, many columns in a region can still be active at once. Hence, despite of infibition, many columns will be active within a region, and these activitis associated with a set a columns is classified as input by each region of cortex.


2. How does it learn sequences of patterns (such as intervals of a melody, or the "eye nose eye" of a face)?

- For a column of cells, if input from a lower region causes one of your layer 4 cells to fire, cells in layers 2 and 3, then 5, and then 6 also to fire subsequently. The entire column becomes active when driven from below. However, cells in layers 2, 3, and 5 each have thousands of synapses in layer 1. If some of these synapses are active when layer 2, 3, and 5 cells fire, the synapses are strengthened. If this occurs often enough, these layer 1 synapses become strong enough to make the cells in layers 2, 3, and 5 fire even when a layer 4 cell hasn't fired— meaning parts of the column can become active without receiving input from a lower region of the cortex. In this way, cells in layers 2, 3, and 5 learn to "anticipate" when they should fire based on the pattern in layer 1. Before learning, the column can only become active if driven by a layer 4 cell. After learning, the column can become partially active via memory.

- Half of the input to layer 1 comes from layer 5 cells in neighboring columns and regions of the cortex. This information represents what was happening moments before. It represents columns that were active prior to your column becoming active. The other half of the input to layer 1 comes from layer 6 cells in hierarchically higher regions. This information is more stationary. It represents the name of the sequence you are currently experiencing. Thus the information in layer 1 represents both the name of a sequence and the last item in the sequence. In this way, a particular column can be shared among many different sequences without getting confused. Columns learn to fire in the right context and in the correct order.


3. How does it form a constant pattern or "name" for a sequence? \[confusing\]

-  Layer 2 cells, learns to stay on during learned sequences. These cells, as a group, represent the name of the sequence. They will present a constant pattern to higher cortical regions as long as a region can predict what columns will be active next.  A layer 3b cell represents an unexpected pattern. It fires when a column becomes active unexpectedly. Before learning both cells fire on and off with the column, but after training the layer 2 cell is constantly active and the layer 3b cell is quiet. When the layer 3a cell sees the learned pattern in layer 1, it quickly activates an inhibitory cell that prevents the layer 3b cell from firing.

{{< figure src="/img/contsant-names-for-learned-sequence.png" title="Forming a constant name for a learned sequence. Images from On Intelligence (2004).  " numbered="true" lightbox="true" width="50%">}}


- To be active throughout a known sequence of patterns, Layer 2 cells could learn to be driven purely from the hierarchically higher regions of cortex. They could form synapses preferentially with the axons from layer 6 cells in the regions above. The layer 2 cells would therefore represent the constant name pattern from the higher region. When a higher region of cortex sends a pattern down to layer 1 of the region below, a set of layer 2 cells in the lower region would become active, representing all the columns that are members of the sequence. Since these layer 2 cells also project back to the higher region, they would form a semistable group of cells. 


4. How does it make specific predictions from invarient representations (meeting the train at the right time, or predicting the specific note in a melody)

- Cortex solves the problem of making specifc prediction from an invariant memoies by using the last specific information to convert an invariant prediction into a specific prediction. Axons from layer 2 and layer 3 cells generally form synapses in layer 5 as they leave the cortex, and similarly axons approaching layer 4 from lower regions of cortex make a synapse in layer 6. The intersection of these two synapses (top down and bottom up) provides the specific prediction. A layer 6 cell that receives these two active inputs will fire. A layer 6 cell represents what a region of cortex believes is happening, a specific prediction.

{{< figure src="/img/prediction-from-invariant-memories.png" title="How a region of cortex makes specific predictions from invariant memories. Images from On Intelligence (2004)." numbered="true" lightbox="true" width="50%">}}

- In addition to projecting to lower cortical regions, layer 6 cells can send their output back into layer 4 cells of their own column. When they do, our predictions become the input. This is what we do when daydreaming or thinking. It
allows us to see the consequences of our own predictions.


## 8. How to Boot the Cortical System from Scratch: Responsibilies of Hippocampus

Hippocampus is essential to the formation of new memories. If someone loses both halves of the hippocampus, he loses the ability to form most new memories. The connections between the hippocampus and the neocortex suggest that the hippocampus is the top region of the neocortex, not a separate structure. Neocortex appeared on the evolutionary scene sandwiched between the hippocampus and the rest of the brain.

Each region of neocortex tries to understand the input in terms of the sequences it knows. If it does understand the input, the input is passed over to the higher regions to be classified and feedback down. However, a pattern that is truly novel will escalate further and further up the hierarchy. Each successively higher region will project it upward hoping that the higher regions can recognize the pattern, but all of them fails. The net effect is that when a pattern gets to the top of the cortical pyramid, that piece of information couldn't be understood by any previous experience. This part of the input is truly new and unexpected. It is these unexplained and unanticipated remainders, the new stuff, that enter the hippocampus and are stored there. This information won't be stored forever. Either it will be transferred down into the cortex below or it will eventually be lost.

The hippocampus has a heterogeneous structure with several specialized regions. It's good at the unique task of quickly storing whatever patterns it sees. We can instantly remember a novel event in the hippocampus, but we will permanently remember something in the cortex only if we experience it over and over, either in reality or by thinking of it.

As we get older, we have trouble remembering new things. New experiences fit into memories of past experiences, and the information just doesn't make it to our hippocampus. So, no memories of that experience is created.


## 9. Alternate Pathway for Upward Information Flow: Attention Shift

While listening to a song, we can just hear it as a song, but we try we can hear all the instruments playing. When we talk to each other in a noisy environment, we can discard the noise and focus on the conversation, but if we chose we can focus on the noise too. We are doing this sort of attentional shift all the time, but we aren't generally aware of it.

This attention shift is achived by an alternate upward pathway that starts with cells in layer 5, which project to the thalamus (a different part of the thalamus from the one we discussed earlier) and then from the thalamus up to the next higher region of cortex. Whenever two regions of cortex directly connect to each other in a hierarchical fashion, they also connect indirectly through the thalamus. This second pathway passes information only up the hierarchy, not down. So as we move up the cortical hierarchy, there is a direct path between two regions and an indirect path through the thalamus.

The second path has two modes of operation determined by cells in the thalamus. In one mode, the path is mostly shut down so information does not flow through. In the other mode, information flows accurately between regions. Sensory input
that normally is handled low in the cortical hierarchy, can be brought to higher levels if we attend to it, through this alternate pathway through the thalamus.

The alternate pathway can be turned on in one of two ways. One is by a signal from the higher region of the cortex itself. This is the method we use when we make ourself to attend to details that we normally wouldn't notice (like making me notice the drum beat in a song). The second method that can activate this pathway is a large, unexpected signal from below. If the input to the alternate pathway is strong enough, it sends a wake-up signal to the higher region, which again can turn on the pathway. For example, if someone showed me a face and asked me what it was, I would say "Face." If I was showed the same face but it had a strange mark on the nose, I would first recognize the face, but then immediately my lower levels of vision would notice that something is wrong. This error forces the opening of the attentional pathway. The details will now take the alternate path, bypassing the grouping that normally occurs, and my attention will be drawn to the mark. I now see the mark and not just the face. If it was sufficiently odd, the mark could occupy my entire attention. In this way, unusual events quickly rise to central attention.



## 10. My Thoughts

1. I feel that "Bayesian Probility Theory" seems to be the most closely linked theory to the one presented here. Cortex solves the problem of making specifc prediction from an invariant memoies by using the last specific information to convert an invariant prediction into a specific prediction. Another way to phrase this, in terms of the cortex, is to say that it combines feedforward information (actual input) with feedback information (a prediction in an invariant form). Yet another way to think this is that invariant memories (feedback signal) are analogous to prior probablity. They only keep the generic information about a given signal. As we receive new expereince (feedforward signals through sensors) the posterior probability of a specific prediction is evaluated to make sense of the world around us.
\[could it be that all the current conventional networks are like frequency interpretation of probability and we need the Bayesian version to solve the drawbacks?\]

2. Some of the claims this book makes that make neural network a poor model of biological brain, has been corrected through later models I believe. For example, CNN uses hierarchical representation and small spacial filters to make sense of an image. Models like LSTM has the capability to process sequence of event. But may be the last FC layers as exclusive classifier is not right, probably each layer should have independent ability to have invarient representation of signal and make prediction from them.

3. However, it feels like that the hierarchical memory system with association and feedback connections are the key components that are missing from the current ML models. Also I think, the correct model should have the capability to run or predict even without any input (like idle thought process of a human). Feedback can solve this automatically I think. Backpropagation is not a feedback mechanism, as it only occurs during the training phase. When the system is actually live, information only flows in one direction.

4. I think that the correct model should have the ability to control and focus the sensors (for example the location and scope of the convolution window of a CNN) in disposal. This could accertain the fact that behaviour (activity of the sensor) will be a byproduct of the intelligence (prediction capability of the model).

5. All the input data should have both spacial and temporal attributes to it.

6. Observing new-borns of human or any other intelligent species might give us some key revelations
