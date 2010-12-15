.. _background:

Background
==========

Endocrine systems function as one of the body's main communication networks controlling many aspects of mammalian function including growth, metabolism, reproduction and stress-related adaptations.  Most hormones are secreted in a pulsatile or burst-like manner into the bloodstream. Information, coded in the frequency and amplitude of these secretory pulses, allows for the differential regulation of specific target cell function and structure.  A detailed knowledge of hormone dynamics is therefore essential for understanding endocrine communication networks.

Increased understanding of hormone dynamics has fundamental clinical implications for both the prevention and treatment of acute and chronic stress. The focus of the current project is around stress hormones, particularly glucocorticoids, which are released during periods of high stress. Elevation in circulating levels of glucocorticoids is a classic endocrine response to stress. However, despite this knowledge, it remains a mystery as to what purpose such hormone pulses serve during periods of stress, and how they affect gene expression in target cells. By characterizing the patterns of stress hormone secretion using mathematical modeling, coupled with high precision measurements of cell responses in hormone secreting cells, we anticipate to establish an accurate estimation of the temporal dynamics of glucocorticoid secretion as well as the resultant pattern of dynamic hormone exposure experienced by target cells and tissues.

Further, developing biophysically relevant cell models for each of the hypothalamic - pituitary - adrenal (HPA) axis components is one of the future goals of the project. The HPA axis is described as a complex self-regulated multilevel dynamic system, which coordinates the activity of the hypothalamus, the anterior pituitary and the adrenal cortex through tight hormonal coupling. Dysfunction of the HPA axis, through either prolonged or inadequate activation, can cause numerous stress-related diseases such as Cushing's syndrome. To improve our understanding of the functional complexity of the HPA axis several phenomenological models have been proposed, where different components in the HPA axis display only input and output characteristics without much detail about the underlying biophysical mechanisms and the cell level behavior of each component. Although these mathematical models are successful in capturing different global observations about system malfunctioning, they do not provide any insight about the molecular basis for the diseased state. Using the Physiome standards such as CelllML, that have been developed at Auckland Bioengineering Institute of the University of Auckland , current work on stress hormones can be integrated with available higher scale models of the endocrine system. In the clinical environment such multi-scale model integration will empower the objective diagnosis and targeted treatments of stress-related disorders.

Pulsatile Hormone Secretion
---------------------------

Most hormones are secreted in a pulsatile rather than continuous manner :cite:`6879944`. In simple terms pulsatile secretion is a phenomenon characterized by the recurrence of individual events such as bursts, peaks, or pulses leading to an abrupt increase and subsequent decrease in pulse size, or amplitude superimposed onto a basal secretion process which may or may not, be constant over time :cite:`6879939`. The physiological mechanisms that generate the hormone pulsatility are poorly understood and underlying phenomenon is very much dependent on hormone. In general basic pulse-generating mechanisms includes different hierarchies of rhythms such as circadian, ultradian, and seasonal, with additional varying complexity added by feedback control systems :cite:`115913`. These pulsatile signals are characterized by their amplitude and frequency. Both the amplitude and frequency of the hormone signal are very important for the control of normal or pathological responses. In most pulsatile hormone systems the mean concentration, or average value of the hormone is determined by pulse amplitude and/or frequency. In systems such as growth hormone, adrenocorticotropin, cortisol, parathormone and insulin pulses, it is purely the amplitude which determines mean concentration, while in others it can be just frequency or both frequency and amplitude. A better understanding of the mechanisms that govern pulsatile hormone secretion requires simultaneous quantification of the amplitude, frequency, underlying continuous basal secretion and associated hormone elimination kinetics. In fact our understanding about the pulsatile hormone secretion and associated variability is increasing with the advent of frequent sampling techniques. Normal variability of pulsatile hormone secretion is airses due to age, growth and environment related physiological alterations which is quite distinctive from the disruption of hormonal pulsatility associated with stress, human illness and disease. 

Physiological efficiency and efficacy of hormones is generally related to the frequency of their pulsatile secretion. However it is not clear exactly how targets cells recognize the frequency encoded in these hormonal pulses. In the case of membrane receptors the role of receptor desensitization and/or internalization appear to be critical for the frequency encoding of pulsatile signals :cite:`6879933`, :cite:`341355`. In the presence of receptor desensitization and/or internalization in the target cell, a pulsatile signal can generate a more efficient response than a continuous one. Often the time between one desensitization-resensitization cycle fits very well with the interval that separates successive hormone pulses. For example, Growth hormone (GH) is secreted with a frequency of about 1 pulse every 3 hours and it takes nearly 3 hours for the resensitization of GH receptor in target cells. Again frequency encoding of pulsatile signals is quite different in nuclear receptors and it is primarily based on ligand binding transcription factors which in turn activate a whole cascade of transcriptional events. Despite all this knowledge there are many questions which remained unanswered, such as how the physiologic response to a high frequency, low-amplitude pulse signal is different from the response to a low-frequency, high-amplitude signal, albeit that both of them can deliver the same amount of the hormone? Furthermore, it is unclear how pulse shape is important, and it is also not very clear whether or not it plays any role in frequency encoding.


Mechanism of Pulse Generation in the Stress-Responsive HPA Axis
---------------------------------------------------------------

The HPA axis is characterized not only by a classic circadian rhythm, but also by an ultradian pattern of discrete pulsatile release of glucocorticoids. Under the influence of stress this pattern is altered leading to the disruption of physiological homeostasis. The main regulation of the circadian, and stress-related activity of the HPA axis occurs at the paraventricular nucleus (PVN) of the hypothalamus which receives circadian inputs from the suprachiasmatic nucleus (SCN) and homeostatic/stress inputs from the brain stem and limbic areas. The final regulation (Fig. :ref:`hpa-label`) is an outcome of interplay between two hypothalmic feedforward signals secreted by parvocellular neurons of the PVN in the hypothalamic region into the hypothalamic–pituitary portal circulation, corticotropin-releasing hormone (CRH) and arginine vasopressin (AVP), and two feedback signals, cortisol and aldosterone produced by adrenal gland. Once released into the portal circulation, CRH stimulate corticotroph cells of the anterior pituitary gland in a cooperative manner to release ACTH from pre-formed granules into the venous circulation. Further, the trophic and the steroidogenic actions of ACTH on the adrenal cortex lead to the synthesis and secretion of glucocorticoids (cortisol in humans, corticosterone in rats and mice) and mineralocorticoids (e.g., aldosterone). Although the exact source and potential mechanisms of ultradian pulsatility in the HPA axis are still elusive.

.. _hpa-label:

.. figure:: /images/HPAaxis.png
   :scale: 100 %
   :alt: HPA axis
   :align: center

   **Regulation of HPA axis activity**

   ``Regulation of HPA axis activity.`` Image credits :cite:`6879904`


ACTH-induced Steroidogenesis
----------------------------

The adrenal glands are triangular-shaped bilateral structures located above the kidneys. These endocrine glands are composed of an outer region, or cortex, and an inner region, or medulla. The outer  region can be divided in three distinct histological zones. ACTH hormone binds to a specific  melanocortin 2 receptor  (MC2R) on the outer cell membranes of zona fasciculata and zona reticularis cells  of the adrenal cortex to stimulate secretion of glucocorticoids and androgens. Stimulation with ACTH increases steroid hormone secretion within 1 to 2
minutes, and peak rates of secretion are seen in about 15 minutes. The whole  steroidogenic cascade has been subjected to extensive molecular analysis. However, despite  this in depth examination, the mechanisms underlying the differential responses of  the various cascade components to basal and acutely stimulated steroid secretion remain  poorly understood. This issue will be addressed by developing a modular computational  model for the ACTH-induced steroidogenesis using CellML 1.1. The proposed model will integrate  an ACTH inducted signaling cascade model, receptor-mediated endocytosis of low-density-lipoprotein, formulation of steroidogenic acute  regulatory protein (StAR), and a metabolic model for cholesterol management. Integration  will allow components which have been characterized and modeled in isolation to be re-examined in the context of their global behavior. 

It is well known that binding of ACTH to G-protein-coupled receptor MC2R and triggers production of Cyclic AMP (cAMP) by activating adenylyl cyclase. Further, cAMP activates protein kinase A (PKA), which catalyzes the phosphorylation of a variety of proteins and consequently stimulation of expression of steroidogenic enzymes. In the zones fasciculata and reticularis, elevated level of PKA increases deesterification of cholesterol esters, transport of cholesterol to the mitochondria, and synthesis of StAR protein.  Cell response to ACTH is therefore dependent to a large extent on the expression and function of the MC2R. 

Like many other  G-protein-coupled receptors, initial ACTH-MC2R interaction leading to signaling cascade activation is rapidly followed by a MC2R desensitization event. Traditionally desensitization events are  either heterologous or homologous in nature. Usually in a homologous desensitization events phosphorylation of agonist-occupied receptor  by specific  G protein receptor kinase (GRK) family occurs. Heterologous desensitization events are mediated by phosphorylation by nonspecific cellular kinases such as PKA or protein kinase C and it is not clear which receptor state undergoes phosphorylation.  The desensitization of MC2R seems to be unusual, for instance in mouce Y1 cells it was found that it has some characteristics of a homologous desensitization but also mediated by PKA.

Cholesterol is starting substrate for ACTH induced steroidgenesis. In adrenal cortex cells cholesterol can be potential obtained from different sources. Inside the cells, De nova cellular cholesterol synthesis and mobilisation of cholesterol esters (CE) stored in lipid droplets via the action of neutral cholesterol ester hydrolase (CEH). Activity of CEH is dependent on  cAMP-dependent protein kinase or PKA. HMG-CoA reductase is the rate-limiting step in De nova cholesterol synthesis. Intracellular cholesterol production and lipid stores are insufficient to support maximal steroid production. Typically majority of  cholesterol is derived from circulating Low-density lipoprotein (LDL) particles by receptor mediated endocytic (humans) or selective cellular uptake (rodent). Cholesterol regulates its own De nova synthesis and the synthesis of LDL receptors at the level of transcription through a negative feedback mechanism via sterol regulated protease (SRP).

Regardless of the hormones synthesized, the initial step in steroidogenesis is the conversion of cholesterol to the pregnenolone by P450 side-chain cleavage enzyme  ($P450_{SCC}$), situated in the inner mitochondrial membrane in all steroidogenic cells. Conversion of cholesterol to the pregnenolone is also the rate-limiting step for the steroidogenesis pathway. The rate limiting behavior arises from hydrophobic character of cholesterol which restricts its diffusion via aqueous intermembrane space of the mitochondria to reach  reach the $P450_{SCC}$ enzyme rapidly enough to support acute synthesis.  Once pregnenolone is formed, it is then subjected to isomerizations and hydroxylations by several steroidogenic enzymes to producethe end product of the sterodogenesis pathway which depends on the tissue specific enzymes.

Sterol transporter protein StAR plays the crucial role of transferring the hydrophobic cholesterol across the aqueous barrier between the outer and inner mitochondrial membrane.  In mammalian systems, StAR gene transcription, StAR protein levels  and steroidogenesis all increase in response to ACTH, via activation of the PKA intracellular signalling pathway, albeit the level of increase may not be same. 
Using the mathematical modelling and experimental measurements we expect to explore the several key areas of ACTH-induced steroidogenesis, such as how MC2R receptor system encodes the frequency-amplitude relationship for ACTH pulse signals, role of receptor desensitization and internalization, kinetics of StAR gene transcription and protein synthesis.


Measurement of Hormone Concentration
------------------------------------

Direct measurement of hormones secreted by a endocrine gland is not possible and generally hormone secretion rates are inferred from equilibrium hormone concentration measured in biological fluid such as plasma(blood) or saliva which provides a distorted picture of hormone secretion at the glandular level due to excretion, chemical breakdown, and redistribution into other compartments (see Fig. :ref:`adme-label`). 

.. _adme-label:

.. figure:: /images/ADME.png
   :scale: 100 %
   :alt: ADME
   :align: center

   **Hormone-secretion time series s(t) vs Hormone-concentration time series c(t)**

   ``Hormone-secretion time series s(t) vs Hormone-concentration time series c(t). Hormone sampling techniques can measure only the concentration time series data which is generally resultant of superimposed biological noise in form of ADME profile on the Hormone secretion rates.``


Due to the lack of unique chemistry of hormone molecules chemical detection of hormones in biological fluids is very difficult. Furthermore, hormones circulate in low quantities in blood and hence their detection is very much dependent on the sensitivity of the method employed. The performance of early methods for hormone detection, especially the bioassays was hampered by their poor sensitivity and  ability to detect hormone molecules uniquely. Currently most hormone detection methods employ various modifications of competitive immunoassays and sandwich-type assays (see Fig. ). 

Again the strategy for laboratory measurement or estimation of hormones concentration is very much hormone specific and it depends on their distribution, disposition and compartmentation characteristics (see Fig. :ref:`hdist-label`).


.. _hdist-label:

.. figure:: /images/HormoneDistribution.png
   :scale: 100 %
   :alt: Hormone Distribution
   :align: center

   **Distribution of hormone in various physiological compartments**

   ``Distribution of hormone in various physiological compartments.``


Unlike steroid and thyroid hormone where a large fraction of hormone circulates bound with plasma proteins such as albumin, polypeptide hormones circulates mostly in a free form. The estimation of free polypeptide hormones is quite straightforward in fact it's the only hormone fraction which is tissue available or capillary exchangeable. Estimation of steroid hormone levels in the blood is quite complicated as it constitutes  three different fractions: a free hormone fraction, a weakly albumin bound fraction and a strongly bound fraction with hormone specific binding proteins. As the steroid hormones are weakly bound to albumin, their binding/dissociation kinetics are very rapid which makes free and weakly albumin bound hormone fractions rapidly exchangeable. Also it is important to note that on the capillary bed the protein/albumin bound fraction dissociate more readily. Hence, in the case of steroid hormones the free plus weakly albumin bound hormone fraction appears to be tissue available or capillary exchangeable :cite:`6886673`. 


The bioactive cellular exchangeable hormone, the pool that drives cellular hormone receptor occupancy and other activities such as hormone metabolism, and the hormone fraction transported into the salivary glands from the blood vessels/ capillaries  are subsets of the tissue available capillary exchangeable hormone fraction. Studies suggest that unconjugated steroids enter saliva by passive diffusion through the cells of the salivary glands and that their concentration in the saliva does not depend on the rate of saliva production :cite:`2295121`. However the same may not be true for the  conjugated steroids, thyroxin, and protein hormones. Again, the exact transport mechanisms of hormones into saliva, their relation with plasma concentration, and corresponding clinical relevance, are all hormone specific (see Fig. :ref:`saliva-label`). Having said that, estimation of hormones concentration in saliva is more convenient as it offers a noninvasive and stress-free alternative to blood based sampling. In fact saliva sampling has proved more popular and equally reliable compared to blood sampling with application in diverse areas such as stress research, clinical endocrinology and sports medicine. However, there are several issues related to the analysis and interpretation of salivary hormone concentration time-series data.  For instance, various computer modelling and simulation techniques have been developed for the calculation of hormone secretion rates from plasma hormone concentration time-series (described in next section). To this end there is no well optimized computational algorithm which can interpret the glandular hormone secretion rates from the salivary hormone concentration time-series data. This is due, at least is part, to poor understanding about mode of entry of various hormones into the saliva along with their post-transport fate.  

.. _saliva-label:

.. figure:: /images/Salivarysystem.png
   :scale: 100 %
   :alt: Salivary system
   :align: center

   **Mode of entry of Hormones in saliva**

   ``Mode of entry of Hormones in saliva.``


Time Series Analysis of Hormonal Patterns
-----------------------------------------

Hormone-concentration time-series (HTS) data have been widely considered to be rich in valuable patterns.  Many initiative and creative approaches have been proposed to interpret HTS data. A significant challenge in dealing with HTS data comes from the limited sampling, or number of time points taken, due to considerable assay expenses. In order to do a plausible HTS analysis, it is necessary to have 60-300 HTS data points where each data point can have multiple replicates in order to  provide a reliable measure of the measurement error. Even with 60-300 data points a normal HTS is a short-time series and most of standard time series analysis methods are  not optimized for this kind of data sets. In a typical hormone sampling experiment plasma or saliva samples are collected on every 10-min or 20-min for a 24-hour period from a group of normal (or sick) human subjects and assayed (RIA/ELISA) for hormone concentration. The final outcome of the HTS analysis is significantly influenced by the sampling frequency, for instance islet hormone secretory pulse period calculations are very much dependent upon the sampling frequency. More frequent sampling such as every 0.5-5 min  may not necessarily help, in fact the pattern of hormone secretion can be too complex and noisy to reach a clear conclusion. An unresolved challenge is finding, for a given hormone, which sampling strategy is better. Also frequent sampling over long periods is good as a research tool but may not be ideal for clinical applications. In clinical settings coarser (frequency) and shorter (interval) sampling protocols can be more effective as a first order screening tool. 

Variability in the HTS values arises from at least four sources: intra-assay variation or measurement errors from the RIA/ELISA, fluctuations in the basal level of the hormone secretion, a slowly changing component or baseline contributing long-term trends, and the abruptly changing component in form of secretory episodes. A typical HTS exhibits the pulses superimposed on the baseline. The term baseline is not well defined, it may represent the circadian rhythm or a diurnal change in hormone concentration level. As slowly changing component and abruptly changing component are closely related these components may blur into one another. Most of computational methods developed to analyze the HTS try to model the data using more than one source of variability but no single method deals optimally with all possible sources of the variability .

HTS analysis approaches can be broadly classified in to the following classes: Methods for secretion estimation or deconvolution analyses, pulse analysis, regularity analysis, and coupling analysis.

Deconvolution Analysis
^^^^^^^^^^^^^^^^^^^^^^

Deconvolution is a widely used technique for signal and image processing. The basic idea is to isolate the individual signal components from  a convolved signal. In the case of HTS analysis deconvolution is not only used to determine underlying secretion or elimination rates from a hormone-concentration time series data but also for pulse detection. Here a convolved signal is formed by mixing a hormone secretion profile , clearance rate, and random experimental perturbations :cite:`6910262`, :cite:`6908506`.  A secretion profile comprises a variably pulsatile and stable basal component. Mathematically the temporal shape of hormone pulses is a convolution integral of

.. math::

	\begin{equation}
	C(t)= E(t) \times C(0) + \int_{0}^{t} S(z) \times E(t-z)dz +\epsilon
	\end{equation} 

where $C(t)$ is the concentration of hormone in blood at time $t> 0$. $C(0)$ is the concentration of hormone at time $t=0$. $E(t)$ defines the clearance profile, normally a exponential process (mono, bi or multi-exponential). $S(z)$ is the amount of hormone secreted at time z per unit time and unit distribution
volume. $E(t-z)$ is the amount of hormone clearance in the time interval t-z and clearance process starts after secretion has occurred at time t. Here $\\epsilon$ signifies unexplained variability observed in hormone concentration due to random elements such as sampling or experimental errors. 

The quality of deconvolution analysis of HTS data is affected due to low signal-to-noise ratio or high experimental uncertainties, sparse and irregular data.  

Pulse identification and characterization
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

These methods provide information about  secretory-pulse size (amplitude or mass) and shape (waveform) :cite:`6892126`. They also identify the number and locations of secretory bursts. There are mainly two classes of pulse analysis methods: criterion-based methods and model-based methods :cite:`6908506`. Criterion-based methods were early approach for pulse analysis and they apply a simple threshold criterion, or test statistics such as t-test, to identify pulses depending on rises and/or falls in hormone concentration. The criterion-based approach uses the RIA/ELISA assay’s coefficient of variance (CV) as only sources of variability or true CV and other types of biological noise are ignored. This simple fixed-criterion based approach does not consider the pulse configuration, uniformity of pulse amplitude, base-line drift, variable peak width, or sampling rate resulting in false-positive and false-negative errors. Criterion-based methods are mainly used to identify initial pulses for model-based methods which use statistical models to approximate the secretion patterns. Deconvolution is the most common strategy for the model based methods and they are preferred to criterion-based methods based.
\numberwithin{equation}{subsection}

Regularity analysis
^^^^^^^^^^^^^^^^^^^

Regularity analysis methods approximate entropy (ApEn) :cite:`6908512` and sample entropy (SampEn) :cite:`697330`  provide a model independent measure of the regularity or complexity of underlying hormone secretion process from the hormone-concentration time series data (details in Box). Entropy is a measure of disorder or randomness. ApEn and SampEn have tremendous clinical value as they are used as a measure of the underlying 'complexity'
of the system producing the dynamics, and this complexity appears to be lost in the presence
of illness. Cross-entropy approaches (cross-ApEn and cross-SampEn) can quantify the degree of asynchrony or similarity for two related yet distinct hormone time series which enables us to differentiate an altered  state from a normal subject. 

Although ApEn and SampEn are promising clinical tools they have few limitations. First of all they evaluate regularity on one scale only. For example they evaluate differences between sequences of length $m$ and $m+1$, but higher scales such as differences between sequences of length $m$ and $m+2$ or $m+3$ are ignored.  An increase in the ApEn/SampEn may not always be associated with an increase in dynamical complexity. Also ApEn is heavily dependent on time series length and it is uniformly lower for short records. While the SampEn is largely independent of record length because it excludes self-matches during the analysis, it has residual bias due to correlation of templates. Moreover, Cross-ApEn is not always defined and it very much direction dependent. Recently developed multiscale entropy (MSE) appears to be a more robust measure of complexity than ApEn/SampEn :cite:`754337`, but it's performance is not evaluated yet with hormone time series data-sets. 


.. topic:: Approximate entropy (ApEn) and Sample entropy (SampEn)

	For a given hormone-concentration time series $H(N)$ with $N$ data point, $H_N= H(1), H(2), H(3)....., H(N)$, the time series is evaluated for patterns that recur. This is performed by evaluating time series subsequences of length $m$, $p_m(i)= H(i), H(i+1),...., H(i+m-1)$, where vector $p_m(i)$ is subsequence of $m$ hormone concentration measurements, beginning at position $i$.  Two patterns, $p_m(i)$ and $p_m(j)$, are similar if the difference between any pair of corresponding measurements in the patterns is less than r, i.e., if

	.. math::

			\begin{equation}
				|H(i+k)- H(j+k)|<r
			\end{equation}
	
	where for ApEn/SampEn $0\leq k< m$, $i\geq 1$ and $j\geq N-m$, with additional condition for SampEn $i\neq j$. As can be seen in the equations described above, m and r are the two input parameters that must be specified by user for the calculation of both ApEn and SampEn. Set $P_m$ gives all patterns with length m in time series $H_N$, $P_m = p_m(1), p_m(2),....,p_m(N-m+1)$. Now we may define

	.. math::
			
			\begin{equation}
			C_{im} (r)= \frac{n_{im} (r)}{N-m+1}
			\end{equation}
			
	where $n_{im} (r)$ is the number of total patterns in  $P_m$ that are similar to $p_m(i)$(given the similarity criterion $r$). Also we can define the mean of all $C_{im}(r)$ values,
			
	.. math::

			\begin{equation}
			C_m(r)= \frac{\sum_{i=1}^{N-m+1} C_{im}(r)}{N}
			\end{equation} 
			
	Finally, ApEn and SampEn are given by,

	.. math::

			\begin{equation}
			ApEn(H_N, m , r)= ln\left[\frac {C_m(r)}{C_{m+1}(r)}\right]
			\end{equation}

	and,

	.. math::

			\begin{equation}
			SampEn(H_N, m , r)= -ln\left[\frac {C_{m+1}(r)}{C_m(r)}\right]
			\end{equation}


Coupling analysis
^^^^^^^^^^^^^^^^^

Coupling analysis is used to estimate the strength of relationship between two or more simultaneously collected hormone concentration-time series  data-sets. For example, to evaluate the coupling between the hormones X and Y, the corresponding HTS data-sets are analyzed using the basic assumption that the concentration of hormone X drives the secretion of hormone Y, which may depends on current (or previous) concentrations of X. Although coupling analysis can be a very powerful tool as it may explain changes that occur in various pathophysiological states, the clinical applications can be quite restricted due to the difficulties associated with the simultaneous sampling of multiple hormones. 








