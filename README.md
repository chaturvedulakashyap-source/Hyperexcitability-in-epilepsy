# Epileptiform Hyperexcitability Model (Brian2)

## Overview
This project models network hyperexcitability using a recurrent spiking neural network. A brief external stimulus produces a strong, synchronized response across multiple neurons.

## Model Description
- Network of excitatory neurons using leaky integrate-and-fire dynamics  
- Recurrent synaptic connections amplify activity  
- Synaptic weight increased to simulate hyperexcitability  

## Key Results
- Brief stimulus triggers widespread neuronal firing  
- High-frequency, synchronized spike activity observed  
- Population firing rate increases sharply during stimulation  

## Interpretation
The model demonstrates hyperexcitability, where neural networks show exaggerated responses to input. While activity is stimulus-driven, it reflects increased excitatory dynamics seen in epileptiform states.

## How to Run
```bash
pip install brian2 matplotlib
python epileptiform_activity_model.py
