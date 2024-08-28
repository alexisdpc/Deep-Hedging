## Deep Hedging

Deep Hedging was proposed in [[1802.03042]](https://arxiv.org/abs/1802.03042)  by Hans Bühler, Lukas Gonon, Josef Teichmann and Ben Wood. The aim is to use a neural network architecture to hedge a portfolio of derivatives without computing the "greeks". This repository is based on lectures given by Josef Teichmann

In the plots below, we show the histograms for the predictions of the deep hedging model and the Black-Scholes model. The results concentrate around zero as expected.

![image](https://github.com/alexisdpc/Deep-Hedging/assets/124795834/89528a85-bef1-41b9-8242-b966c16bba8d) ![image](https://github.com/alexisdpc/Deep-Hedging/assets/124795834/cf4c6c96-1b71-451f-8027-6140f05266dc)

In the figure below we show the Delta as a function of the stock price for a fixed time. The two lines show a very good overlap, except on the regions in the corners of the plot, since there was not enough data on these regions to generate good predictions.

![image](https://github.com/alexisdpc/Deep-Hedging/assets/124795834/a1627c8c-b95c-4ddb-8d87-7684c54e35c1)


