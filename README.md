# Deep Leakage from Gradients
A project developed in completion of CSCM38 Advanced Topics: Artificial Intelligence and Cyber Security Coursework 2.

_Cited source: https://dlg.mit.edu/_

## Background
"Exchanging gradients is a widely used method in modern multi-node machine learning system (e.g., distributed training, collaborative learning). For a long time, people believed that gradients are safe to share: i.e., the training data will not be leaked by gradient exchange.

However, we show that it is possible to obtain the private training data from the publicly shared gradients. We name this leakage as Deep Leakage from Gradient and empirically validate the effectiveness on both computer vision and natural language processing tasks. Experimental results show that our attack is much stronger than previous approaches: the recovery is pixel-wise accurate for images and token-wise matching for texts.

We want to raise people's awareness to rethink the gradient's safety. Finally, we discuss several possible strategies to prevent such deep leakage. The most effective defense method is gradient pruning."

<p align="center">
  <img width="640" src="https://github.com/mit-han-lab/dlg/raw/master/assets/nips-dlg.jpg">
</p>

<p align="center">
  <img width="640" src="https://github.com/mit-han-lab/dlg/raw/master/assets/demo-crop.gif">
</p>

More information to come _(time dependent)_.
