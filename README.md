## Tutorial on modeling a single neuron

By Peter Rupprecht ( p.t.r.rupprecht+hodgkin+huxley@gmail.com )

The following tutorial shown in the Jupyter Notebook / Colab Notebook was used in an online course for students interested in neurophysiology, as a complementary modeling section for a practical ephys course that involved patch clamp recordings in slices (https://neurotechnology.ethz.ch/education.html, "Electrophysiological Recording Techniques"). It might, however, be interesting for others who want to use minimal code to explore the **membrane dynamics of a simulated point neuron**.


The tutorial consists of three sections.

1. In the first section, code for a simple leaky integrating neuron is written. This is very close to a leaky-integrate-and-fire neuron model (**LIF neuron**) that is commonly used for network modeling. For the purpose of the course, I live-coded this example from scratch.

2. In the second section, and already existing code describing the **Hodgkin-Huxley equations** (largely taken from https://github.com/swharden/pyHH) is provided to the students, together with functions to plot *e.g.* membrane potential or the dynamics of gating variables. The task of the students was to understand the code (more or less, depending on previous knowledge of Python and mathematics) and to play around with parameters, current pulses etc.

3. The third section was an optional addition to the interactive part. The task for students was to rewrite the code for section (2) such that it simulates not unperturbed behavior of the channels in the neuron, but rather as if there was a **voltage-clamp experiment** going on. The code in section (3) is an example how such code could look like.
The Hodgkin-Huxley neuron model, simulated both in current clamp and voltage clamp


<p align="center">
  <img width="566" height="296" src="https://github.com/PTRRupprecht/Hodgkin-Huxley-CC-VC/blob/main/HH_examples.png">
</p>
