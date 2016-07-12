# SUPERVASION
## Knowledge Acquisition by Abduction for Skills Monitoring: Application to Surgical Skills

In this GitHub entry, we present some features related to the work sent to the ILP congress (26th International Conference on Inductive Logic Programming) that holds in London in September of 2016. This entry shows some of the experiments not included in the paper because of the lack of space. Besides, we have included the Narrative used in the experiments as well as the code in XHAIL used for the experiments.

The files that can be found in this entry are (for more information see the Wiki):

1.- fifteenth_approx.lp: that contains the XHAIL code of the Scenario A.

2.- ninth_approx_2.lp: that contains the XHAIL code of the Scenario B.

2.- real_events.pdf: a graph that shows the low-level events contained in the narrative of the Scenario A.

3.- real_fluent_graph.pdf: a graph that shows the low-level fluents (black) and high-level fluents (blue) contained in the narrative and the examples provided in Scenario A.

4.- real_fluent_graph_detect.pdf: a graph that shows the vertical bands that are the temporal windows for the initiatesF/2 (the leftmost point of the high-level fluents clip_object/2) and for the terminatesF/2 (the rightmost point of the high-level fluents clip_object/2) obtained from the rules learned in Scenario B.

5.- synthetic_events.pdf: a graph that shows the low-level events contained in the narrative of the Scenario B.

6.- synthetic_fluents.pdf: a graph that shows the low-level fluents (black) and high-level fluents (blue) contained in the narrative and the examples provided in Scenario B.

7- synthetic_fluents_detect.pdf: a graph that show the vertical bands that are the temporal windows for the initiatesF/2 (the leftmost point of the high-level fluents clip_object/2) and for the terminatesF/2 (the rightmost point of the high-level fluents clip_object/2) obtained from the rules learned in Scenario A. Here, the initiatesF/2 of the second high-level fluent is not detected (see the wiki for details).

8.- synthetic_fluents_detect_mod.pdf: the same graph as synthetic_fluents_detect.pdf shows but removing the presence of the tool i1 from bin g2 in the rules learned from Scenario A. This rule modification has suggested by experts and demonstrates the easy supervision of the learning and ease modification of the rules learned. Modification done by experts without deep knowledge in computer programming. With this modification, the initiatesF/2 of the second high-level fluent is detected (see the wiki for details).
