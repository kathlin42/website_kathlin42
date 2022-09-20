---
title: Cognition and Affect - Let's try to disentangle them!
summary: The central research question od my doctoral thesis and reason for sleepless nights is how cognitive processes and emotional distractions interact with each other. How are these processes entangled ? Which control mechanisms are triggered? Does the valence of the emotional distraction play a fundamental role? And is there a further interaction with the level of task difficulty or workload level? Which neuronal activation patterns underly these processes? I accept the major challenge of this research question and its complexity and act as Sherlock Holmes...First insights from an EEG Pilot Study!

tags:
  - Electroencephalography (EEG)
  - Interaction Emotion - Cognition
  - Working Memory Load
  - Arithmetics
  - Emotional Processing

date: '2016-04-19T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Experimental Environment using MEG, eye-tracking and a driving simulator
  focal_point: Smart

url_code: ''
url_pdf: ''
url_slides: ''
url_video: 'https://youtu.be/usoU87BaEyY'

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

- Motivation and Aim: 

In the past decade, theoretical models of modular architectures with cold cognitive and hot affective-emotional systems have been progressively revised [1-3]. Nowadays, these mechanisms are suggested to be interwoven [4-5] and even processed in shared underlying neurocircuitry (e.g., [1,3]). Particularly in naturalistic environments, we are confronted with complex, (socio-)emotional stimuli claiming attentional and working memory resources (e.g., a crying baby during home office or laughter in open-plan offices). However, the precise nature of emotion-cognition interactions is still subject to research [5-8]. Previous studies revealed detrimental effects of emotional distraction on cognitive processes [9-11] with strongest interference when cognitive load is low and distractors’ valence deviates from neutral [1,12]. Electroencephalography (EEG) is a technique that provides separable brain correlates for emotional and cognitive states. EEG research suggested the frontal alpha asymmetry (FAA) as a suitable correlate indicating emotional states [13-15] and the ratio of frontal theta (4 – 7 Hz) and parietal alpha (8 – 12 Hz) power to index cognitive load (workload (WL); [16-17]). Here, we investigate whether these correlates can capture interactions between cognitive control and affective-emotional distraction processes. More precisely, we are interested in how auditory distractors and their affective valence influence neurophysiological indices associated with valence and cognitive load (here working memory load, WML). We assume stronger detrimental effects (i) under low WML because of sufficient available resources to process emotional distractors fully, and (ii) for (potentially harming) stimuli with low valence due to a higher salience and relevance (cf., [1,18]).

- Methods:

We analyzed EEG data from 12 participants (5 female; 1 diverse; M = 24; SD = 2.6 years). Participants performed a series of elementary arithmetic additions either with 1-digit numbers (low WML, LWML) or 2-digit numbers (high WML, HWML), presented visually (cf., [19-20]). 
Concurrently, we presented auditory distractions using negatively (low valence, LV), neutrally (neutral valence, NV), and positively (high valence, HV) associated sounds of the International Affective Digitized Sounds (IADS) database [21] resulting in a two-factorial 2(LWML-HWML)×3(LV-NV-HV)-levels within-subject design. 
EEG were recorded from 20 channels using a mobile, dry-EEG system at a sampling rate of 500 Hz (Cognionics Inc.).
We calculated power spectral measures via Welch’s method of the Fast Fourier Transformation (FFT). 
The WL index indicating WML was calculated by log-transforming the ratio of theta-band at Fz and alpha-band power at Pz.
The FAA index was computed by subtracting and log-transforming alpha-band power in F3 (left hemisphere) from F4 (right hemisphere). 
To increase interpretability, we reversed the FAA and scaled both indices between 0 and 1. 
For the FAA, low values are associated with negative and high values with positive experiences. 
For the WL, low values indicate low and high values high WML.
After scaling, the FAA boundary was set to 0.699 (previously at zero). 
Our results revealed higher alpha power in the left compared to the right hemisphere in all conditions. 
We observed a significant difference in the FAA for HV distractors under LWML compared to HWML with higher values in the LWML condition (HV HWML-
LWML). 
Interestingly, there was a trend that HV distractors evoked lower FAA compared to NV (HV-NV HWML) and LV (HV-LV HWML) under HWML (n.s.).
Regarding the WL index, there is a trend indicating higher WL in the NV HWML compared to the HV HWML and LV HWML as well as in the NV LWML compared to LV LWML condition (n.s.).

- Discussion:

Investigating effects of emotional auditory distractors on WML, we observed higher alpha power in the left hemisphere in all conditions suggesting negative emotional processing and an avoidance tendency [13-15]. This might be explained by the arithmetic task probably inducing tension and negative emotions as well as task-irrelevance of the auditory stimuli. Hence, the simultaneous working memory task altered emotional evaluation with strongest effects for HV stimuli. The significant difference in the FAA for HV distractors between LWML and HWML and effect of reduced positivity for HV in comparison to NV or LV distractors under HWML contribute to this explanation. Generally, we observed a trend for decreased FAA and increased WL under HWML compared to LWML independent of stimulus valence (n.s.). Hence, the WML level affected the neuronal correlates stronger than emotional manipulation. Contrary to our assumptions, LV distractors did not show stronger detrimental effects. NV distractors, however, seem to have stronger detrimental effects than HV and LV distractors, especially, under HWML (n.s.). This finding suggests stronger claims of cognitive resources when processing neutral distractors. Interestingly, a meta-analysis concluded that neutral stimuli are processed as rather mild negatively when compared to emotional stimuli [18]. Our study highlights the necessity to further investigate emotion-cognition interactions using a larger sample since inconsistencies between findings and uncertainty regarding precise underlying processes remain. We further point out difficulties when investigating strongly intertwined processes. There is a great need for suitable experimental paradigms and methods to isolate interacting effects and components. For instance, potential suppression mechanisms of emotional content to prioritize the cognitive task. Possible implications of this research include a higher context sensitivity and holistic evaluation of identified mental states in safety-critical environments, e.g., during driving or in human-computer interactions.

[1] Cromheeke, S., and Mueller, S. C. (2014). Probing emotional influences on cognitive control: an ALE meta-analysis of cognition emotion interactions. Brain Struct Funct 219, 995–1008. doi:10.1007/s00429-013-0549-z
[2] Gray, J. R., Braver, T. S., and Raichle, M. E. (2002). Integration of emotion and cognition in the lateral prefrontal cortex. Proceedings of the National Academy of Sciences 99(6), 4115-4120.
[3] Pessoa, L. (2008). On the relationship between emotion and cognition. Nature reviews neuroscience 9(2), 148-158.
[4] Ihme, K., Unni, A., Zhang, M., Rieger, J. W., and Jipp, M. (2018) Recognizing frustration of drivers from face video recordings and brain activation measurements with functional near-infrared spectroscopy. Front. Hum. Neurosci. 12, 327. doi:10.3389/fnhum.2018.00327
[5] Seleznov, I., Zyma, I., Kiyono, K., Tukaev S., Popov, A., Chernykh, M., and Shpenkov, O. (2019) Detrended fluctuation, coherence, and spectral power analysis of activation rearrangement in EEG dynamics during cognitive workload. Front. Hum. Neurosci. 13, 270. doi:10.3389/fnhum.2019.00270
[6] Okon-Singer, H., Hendler, T., Pessoa, L., and Shackman, A. J. (2015). The neurobiology of emotion-cognition interactions: Fundamental questions and strategies for future research. Front Hum Neurosci 9, 58. doi:10.3389/fnhum.2015.00058
[7] Zinchenko, A., Kotz, S. A., Schröger, E., and Kanske, P. (2020). Moving towards dynamics: Emotional modulation of cognitive and emotional control. Int J Psychophysiol 147, 193–201. doi:10.1016/j.ijpsycho.2019.10.018
[8] Morawetz, C., Riedel, M. C., Salo, T., Berboth, S., Eickhoff, S. B., Laird, A. R., et al. (2020). Multiple large-scale neural networks underlying emotion regulation. Neurosci Biobehav Rev 116, 382–395. doi:10.1016/j.neubiorev.2020.07.001
[9] Dolcos, F., and Denkova, E. (2014). Current emotion research in cognitive neuroscience: Linking enhancing and impairing effects of emotion on cognition. Emotion Review 6, 362–375. doi: 10.1177/1754073914536449
[10] Iordan, A. D., Dolcos, S., and Dolcos, F. (2013). Neural signatures of the response to emotional distraction: A review of evidence from brain imaging investigations. Front Hum Neurosci 7, 200. doi: 10.3389/fnhum.2013.00200
[11] Wessa, M., Heissler, J., Schönfelder, S., and Kanske, P. (2013). Goal-directed behavior under emotional distraction is preserved by enhanced task-specific activation. Soc Cogn Affect Neurosci 8, 305–312. doi: 10.1093/scan/nsr098
[12] Shafer, A. T., Matveychuk, D., Penney, T., O'Hare, A. J., Stokes, J., and Dolcos, F. (2012). Processing of emotional distraction is both automatic and modulated by attention: evidence from an event-related fMRI investigation. J Cogn Neurosci 24, 1233–1252. doi:10.1162/jocn_a_00206
[13] Ahern, G. L., and Schwartz, G. E. (1985). Differential lateralization for positive and negative emotion in the human brain: EEG spectral analysis. Neuropsychologia 23, 745–755. doi:10.1016/0028-3932(85)90081-8
[14] Briesemeister, B. B., Tamm, S., Heine, A., and Jacobs, A. M. (2013). Approach the good, withdraw from the bad—A review on frontal alpha asymmetry measures in applied psychological research. PSYCH 04, 261–267. doi:10.4236/psych.2013.43A039
[15] Smith, E. E., Reznik, S. J., Stewart, J. L., and Allen, J. J. B. (2017). Assessing and conceptualizing frontal EEG asymmetry: An updated primer on recording, processing, analyzing, and interpreting frontal alpha asymmetry. Int J Psychophysiol 111, 98–114. doi:10.1016/j.ijpsycho.2016.11.005
[16] Gevins, A., Smith, M. E., McEvoy, L., and Yu, D. (1997). High-resolution EEG mapping of cortical activation related to working memory: Effects of task difficulty, type of processing, and practice. Cereb Cortex 7, 374–385. doi:10.1093/cercor/7.4.374
[17] Brouwer, A.-M., Hogervorst, M. A., van Erp, J. B. F., Heffelaar, T., Zimmerman, P. H., and Oostenveld, R. (2012). Estimating workload using EEG spectral power and ERPs in the n-back task. J Neural Eng 9, 45008. doi: 10.1088/1741-2560/9/4/045008
[18] Joseph, D. L., Chan, M. Y., Heintzelman, S. J., Tay, L., Diener, E., and Scotney, V. S. (2020). The manipulation of affect: A meta-analysis of affect induction procedures. Psychol Bull 146, 355–375. doi: 10.1037/bul0000224
[19] Gado, S., Lingelbach, K., Bui, M., Rieger, J. W., and Vukelić, M. (2021). “Real-time feedback of subjective affect and working memory load based on neurophysiological activity,” in The International Conference, HCI International 2021, Washington DC, USA, July 24-29, 2021, Proceedings (in-press). Springer.
[20] Lingelbach, K., Gado, S., Vukelić, M, and Rieger, J. W. (2021). “What I feel and what I say: Decoding neurophysiological correlates of cognitive and affective states,” in The 3rd International Neuroergonomics Conference, Munich, Germany, September 11-16, 2021, (submitted).
[21] Bradley, M. M., and Lang, P. J. (2007). The International Affective Digitized Sounds (IADS-2): Affective ratings of sounds and instruction manual. University of Florida, Gainesville, FL, Tech. Rep. B-3.