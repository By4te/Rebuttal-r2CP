# Answer to Reviewer r2CP

## The overall framework of ConfSleepNet

![图](https://github.com/user-attachments/assets/f5df4a43-47b2-4015-b6ab-e95ca65aa0da)
_Figure 1_. Illustration of ConfSleepNet. Four evidential DNNs $\{ f_v(\cdot)\}_{v=1}^4$ learn stage-specific evidences from various views, which involve two different category structures. Next, an evidence mapping layer maps the coarse-grained evidence into fine-grained evidence. After that, we construct view-specific opinions $\{ \mathcal M^v \}_{v=1}^4 $ based on the obtained evidence and then combine them to form a joint opinion $\mathcal M$. In multi-view fusion, we identify conflictive opinions via uncertainty estimation and accordingly reduce their impact in decision-making.
