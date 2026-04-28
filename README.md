Interactive Leaky Integrate-and-Fire (LIF) Neural Simulation
This project is an interactive demonstration of the Leaky Integrate-and-Fire (LIF) model, illustrating the fundamental principles of neural computation and temporal summation. By manipulating the membrane time constant (the "leak") and the firing threshold, the simulation visualizes how biological neurons process information through a balance of excitation and decay.

Temporal Summation: Demonstrates how high-frequency inputs can overcome the passive leak to reach the action potential threshold.

The Necessity of Leak: Highlights how the leak serves as a "forgetting" mechanism, ensuring the neuron remains sensitive to recency rather than just cumulative input.

Threshold Dynamics: Explores how varying the threshold mimics the effects of neuromodulation and lateral inhibition, transitioning the cell from a state of hypo-excitability to hyper-activity.




Experiment 1 — Feel the leak. Click "Send input pulse" once, then watch. The potential rises, then slowly bleeds back to zero. The neuron forgets.
Experiment 2 — Fire it. Click the pulse button 4–5 times quickly. Potential accumulates faster than it leaks → crosses threshold → spike! Notice it resets to zero instantly.
Experiment 3 — Turn leak OFF. Now every pulse you send stays permanently. The neuron becomes unrealistically sensitive — it remembers everything forever. This is why leak is essential: it enforces recency and prevents runaway activity.
Experiment 4 — Change the threshold. Drag it low (~30%) and the neuron fires easily — hyperactive. Drag it high (~90%) and it takes a barrage of inputs before it fires — sluggish. In a real brain, inhibitory neurons raise the effective threshold of their neighbors. That's the mechanism of lateral inhibition 

try now- https://the-synaptic-logic-initiative.github.io/Leaky-Integrate-and-Fire-neuron/
