# README for Brian Code Associated with the Paper

Peter beim Graben and Serafim Rodrigues

A Biophysical observation model for field potentials of networks of  
leaky-integrate-and-fire neurons.  
*Front. Comput. Neurosci*, 04 January 2013  
doi: 10.3389/fncom.2012.00100

*******************************

This python code, Gunft6.py, requires and runs under the Brian simulator.

## Note for developers:

- **Note 1:** As it stands, the code is not efficient (fast) as it does not use the facilities vector processing and uses a lot of for-loops which is not efficient. So it can be improved.  
- **Note 2:** Periodic thalamic input is not yet implemented.

*****************************

1. This is a network of 5000 neurons, 80% of which excitatory, and 20% inhibitory.  
2. The network is randomly connected (between pairs) with connection probability = 0.2.  
3. Both Excitatory and Inhibitory neurons are described via LIF model.  
4. The currents are double exponential, but the excitatory currents can receive external noise.

---

2025-07-09: Converted README to Markdown.