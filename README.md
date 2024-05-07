# The Patterns of Evolution: A Phylogenetic Analysis of Fur Pattern Evolution in Panthera

Jared Van Der Loo
Dr. Oscar Vargas
BIOL 550: Phylogenetic Systematics
May 7th, 2024

## Introduction: 
This study focused on how fur color and pattern changed and evolved in Panthera as the genus diversified. The extant members of the Genus Panthera are lion (Panthera leo), tiger (Panthera tigris), jaguar (Panthera onca), leopard (Panthera pardus), and snow leopard (Panthera uncia). The Clouded leopard (Neofelis nebulosa) was chosen as the outgroup because it is considered to be the closest living relative to the big cats of the Panthera genus but still distinctly separate. Phylogenetically, Neofelis splits from the other big cats earlier than the divergence of the Panthera species from each other. So it is closely related enough to provide relevant comparative genetic material, yet sufficiently divergent to help root the Panthera clade. 

The genus Panthera is believed to have originated in Asia around 10-15 million years ago with phylogenetic studies estimating divergence of the species occurring between 3.9 and 1.9 million years ago (Johnson et al., 2006). Using fossil evidence researchers have been able to estimate the paths Panthera made as they dispersed through various regions of Asia, Africa, Europe, and North America (Antón et al., 2004).

The main question of this project was what fur pattern and color were present in Panthera ancestors before the diversification and change into the distinct characteristics within the genus. 

I hypothesized that the ancestor of the Panthera genus had plain tan fur and as the species diverged and adapted to new environments they developed different colors and patterns. As Panthera dispersed to new environments spanning several continents they faced selective pressures that forced them to adapt. Fur color and pattern are a key component of their ability to camouflage and remain efficient predators, but they also allow species to communicate with one another and protect themselves through mimicry (Filip. 2012). 

Exploring the evolution of Panthera fur character states will enhance our understanding of the genus and the selective pressures that honed the camouflage of these efficient hunters. Understanding how Panthera trait variability is affected by environmental challenges could also unlock new avenues of conservation. 

## Materials and Methods: 
The data was collected from GenBank, a majority coming from the accession numbers available in the paper, “Supermatrix and species tree methods resolve phylogenetic relationships within the big cats, Panthera (Carnivora: Felidae)” by Brian Davis, et al. This paper used the mitochondrial DNA gene segment sequences from 12S, 16S, CYTB, ND1, ND2, ND4, and ND5 for their phylogenetic analyses. For this study, the entire mitochondrial DNA sequence for each species was used which included the 7 mitochondrial genes.  

The entire mitochondrial genome sequences were aligned using Maft and their alignments were found to not contain any problematic sections and it was determined the data would yield better results without any trimming. 

A phylogenetic tree was constructed utilizing the aligned sequences. This analysis was performed in a virtual Linux environment using the Maximum Likelihood method implemented in IQ-TREE software. A Maximum Likelihood method was selected based on its robustness in handling varied evolutionary models and its effectiveness in detailed phylogenetic studies. 

Following the phylogenetic analysis, RStudio was employed to conduct stochastic character mapping. This statistical approach was applied to infer the evolutionary changes in fur color and pattern across the phylogenetic tree. The method integrated tree topology, branch lengths, and a model of character evolution to probabilistically reconstruct ancestral states and map character changes through evolutionary history. 

The methodology used provided a robust framework for examining the evolutionary trajectories of phenotypic traits in the genus Panthera, utilizing complete mitochondrial genomes to enhance the resolution and reliability of phylogenetic and trait evolution analyses.

## Results: 
![sequence al fasta treefile](https://github.com/JaredVDL/biol550/assets/160165664/82e94a64-7e58-41a2-bb06-417f1e2193a1)

Figure 1: Maximum likelihood Phylogenetic Tree. The tree was made in virtual Linux with iqTree. The tree has Clouded leopard as the outgroup and the first diversification of the genus belonging to the tiger (Panthera tigris). The tree is supported with high bootstrap values ranging from 98 to 100. 

<img width="877" alt="Screenshot 2024-05-05 at 2 59 12 PM" src="https://github.com/JaredVDL/biol550/assets/160165664/0b1f1894-5d62-4549-af2f-17f9924040a2">

Figure 2: Stochastic Character Map of Fur Color Character States. The pie graph at each node displays what fur color the ancestor most likely had. Orange fur is depicted by an orange color, white fur is depicted by a white color, and yellow fur is depicted by a yellow color.

<img width="763" alt="Screenshot 2024-05-05 at 3 07 09 PM" src="https://github.com/JaredVDL/biol550/assets/160165664/0d0c1a2e-0490-41e3-ad0c-11cc77920f44">

Figure 3: Stochastic Character Map of Fur Pattern Character States. The pie graph at each node displays what fur pattern the ancestor most likely had. Spotted fur is depicted by a red color, striped fur is depicted by a green color, and plain fur is depicted by a blue color.


## Discussion: 
The maximum likelihood phylogenetic tree shows that the first diversification of the genus Panthera belongs to the tiger (Panthera tigris) then the jaguar (Panthera onca), then the snow leopard (Panthera uncia), and finally the lion (Panthera leo) and leopard (Panthera pardus) (Fig 1). The tree is supported by high bootstrap values and is consistent with recent academic studies of the phylogeny. The tree also shows a broad theoretical blueprint for the diversification through dispersal of the genus. As the genus dispersed from Asia, Tigers and Leopards remained. Snow leopards dispersed to the mountainous regions of Asia. Lions dispersed throughout Africa, and Jaguars dispersed through South America. Further research into the extinct members of this genus and the traits and adaptations they accumulated throughout this dispersal would shed even more light onto what fur character traits developed and changed throughout each species' history. 

Stochastic character maps involve statistical probability to attempt to predict ancestral states, with this arises uncertainty. The stochastic methods determine a distribution of possible character states and not a single definitive state. In particular, the stochastic character map in this study does not show a single state as being largely more likely than the others. However, the analysis of the results will focus on what more definitive results would infer about the ancestor of the Panthera genus. 

The fur color stochastic character map estimates that orange fur is slightly more likely to be the color character state of the ancestor of Panthera (Fig. 1). This estimate makes sense when looking at the character states through a parsimonious lens as a majority of extant Panthera also have orange fur. If this is the case, as snow leopards diversified they adapted to northern and central Asia's snowy mountain climate with white fur, and lions adapted to Africa’s grasslands and savannas with yellow fur. 

The fur pattern stochastic character map estimates that stripes, spots, or plain patterns are all equally likely for the ancestor of Panthera (Fig. 2). Looking further, the ancestor at the next node was much more likely to have a spotted pattern over the others states. If this is accurate, then during the lion’s diversification, it actually lost its spots in favor of a plain fur pattern that better suited its environment. It would also mean that the tigers’ stripes are a derived character state that exists in another feline species through convergent evolution. 

With more definitive results we could come to the conclusion that the Panthera ancestor had orange fur and spots leading to the novel adaptations of the white fur in snow leopards, stripes in tigers, and the plain yellow fur of lions. These findings are logical when considering the habitat and evolutionary niche the Panthera ancestor occupied. The genus originated in Asia where leopards remain, suggesting the evolutionary benefits that orange and spotted fur would have in this environment. 

Mammalian hair has only two kinds of pigment: one that produces black or brown hair and one that produces yellow or reddish-orange hair. Mixing those pigments will never make a vibrant green that we would expect to be the best camouflage in forest or jungle environments. Broadly speaking, Panthera favors medium to large ungulate mammals such as deer, wild pigs, antelope, and water buffalo. Ungulates have a dichromatic vision so they only see yellow, blue, black, and white. This means they are essentially red-green color blind. The color vision of ungulates is what makes the orange fur color so efficient for camouflage. 

As the genus spread out, the distinct colors and patterns took shape leading to the best advantage in the new environments leading to novel adaptations that make the Panthera species so beautiful. The initial hypothesis of the fur character states of the Panthera ancestor was incorrect. This hypothesis was under the false assumption that the ancestor was just a starting point for the genus, but it was not only this, but also a feline predator that needed its own useful fur character states to camouflage, hunt, and survive. 

Researchers have found several genes responsible for Panthera fur color and pattern. The ASIP (Agouti Signaling Protein) gene affects the distribution of pigments in the fur and can influence patterns such as the agouti patterning. The TYR (Tyrosinase) gene is essential for melanin production and can affect overall color intensity. The genes KIT, SOX10, and MITF affect the movement and survival of melanocytes which are cells that produce pigment. Further research focused on determining what genetic changes and mutations led to the development and evolution of the distinct fur patterns and color within the Panthera genus would have made great strides in understanding their ancestral character states.

With further research, this study could yield much more supportive and conclusive results with the implementation of more data, models of evolution, and a larger sample size. By using specific models of evolution that account for different rates of change or the potential for certain colors to evolve preferentially in certain environments, the ancestral character state reconstruction would have more validity. Exploring the genetic basis of fur color variations among extant species would lead to a better understanding of what genetic possibilities their ancestors had. Increasing the sample size by including several related genera to Panthera would enhance the accuracy and reliability of the Stochastic Character Mapping. This would broaden the phylogenetic context while also clarifying which traits are ancestral and which are derived. With more data points estimated, parameters like the fur color transition rates would become more robust and reliable. A larger sample size would also reduce the impact of sampling bias likely caused by the studies’ use of a small number of closely related species. 





## Literature Cited: 

Johnson, W. E., Eizirik, E., Pecon-Slattery, J., Murphy, W. J., Antunes, A., Teeling, E., and O'Brien, S. J. 2006. The Late Miocene Radiation of Modern Felidae: A Genetic Assessment. Science 311 (5757): 73-77. 

Davis, B. W., Li, G., and Murphy, W. J. 2010. Supermatrix and Species Tree Methods Resolve Phylogenetic Relationships within the Big Cats, Panthera (Carnivora: Felidae). Molecular Phylogenetics and Evolution 56 (1): 64-76. 

Jaroš, Filip. 2012. The Ecological and Ethological Significance of Felid Coat Patterns (Felidae). PhD diss., Charles University in Prague. Supervised by Prof. RNDr. Stanislav Komárek. 

Dr. Antón, M., García-Perea, R., and Turner, A. 2004. Reconstructed Facial Appearance of the Sabretoothed Felid Smilodon. Zoological Journal of the Linnean Society 140 (1): 129-141.










