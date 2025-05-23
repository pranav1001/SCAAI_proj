# SCAAI Project
https://arxiv.org/abs/2306.09385

Abstract
In the current information age, the human lifestyle has become more knowledge-oriented,
leading to sedentary employment. This has given rise to a number of health and mental
disorders. Mental wellness is one of the most neglected, however crucial, aspects of today's
fast-paced world. Mental health issues can, both directly and indirectly, affect other sections
of human physiology and impede an individual's day-to-day activities and performance.
However, identifying the stress and finding the stress trend for an individual that may lead to
serious mental ailments is challenging and involves multiple factors. Such identification can
be achieved accurately by fusing these multiple modalities (due to various factors) arising from
a person's behavioral patterns. Specific techniques are identified in the literature for this
purpose; however, very few machine learning-based methods are proposed for such
multimodal fusion tasks. In this work, a multimodal AI-based framework is proposed to
monitor a person's working behavior and stress levels. We propose a methodology for
efficiently detecting stress due to workload by concatenating heterogeneous raw sensor data
streams (e.g., face expressions, posture, heart rate, computer interaction). This data can be
securely stored and analyzed to understand and discover personalized unique behavioral
patterns leading to mental strain and fatigue. The contribution of this work is twofold – namely,
proposing a multimodal AI-based strategy for fusion to detect stress and its level and, secondly,
identify a stress pattern over a period of time. We were able to achieve 96.09% accuracy on
the test set in stress detection and classification. Further, we were able to reduce the stress scale
prediction model loss to 0.036 using these modalities. This work can prove important for the
community at large, specifically those working sedentary jobs, to monitor and identify stress
levels, especially in current times of COVID-19. 

Analysis contains data exploration and understanding

SCAAI_final contains the tensorflow model that uses Swivel gives a validation accuracy of 0.88 and training accuracy of  0.96

SCAAI_LSTM contains the lstm model for text classification gives a validation accuracy of 0.82 and training accuracy of  0.90

ANN contains a nn model which gives a validation accuracy of 0.88 and training accuracy of  0.90

model3 uses GLoVe embedding method and that gives us a training accuracy of 0.9236 and val_acc: 0.7481



