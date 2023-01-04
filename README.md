# Awesome Model Optimization Techniques
This repository contains a curated list of different ways of optimization and compression techiniques for the Machine Learning Models.

# Main Content
## Quick links to sections in this page

## Concepts 

Model Compression and Architecture Optimization
1. Compression Techniques 
      - Pruning
      - Quantization
      - hashing 
      - Knowledge Distillation
      - Low-Rank Approximation
      - Precision reduction [ Floating Point Operation, Floating Point Operations per Second, Multiply-Accumulate Computations [ 1 MAC = 2 FLOPs ]  ] 

2. Architecture Optimization
      - Architecture Changes 
      - Neural Architecture Search 


## Raw listing
List of all possible ways of optimization 

1. Pruning : Removing redundant connections present in the architecture. Pruning involves cutting out unimportant weights (which are usually defined as weights with small absolute value).
    - Unstructured Pruning
    - Structured Pruning

2. Quantization: Quantization involves bundling weights together by clustering them or rounding them off so that the same number of connections can be represented using lesser amount of memory.
    - Dynamic Quantization 
    - Static Quantization 
    - Quantization Aware training 
 
3. ONNX conversion and ONNX Runtime
4. Distillation
5. coreML for mobile device
6. Neural Architecture Search (NAS)
7. Low-Rank Approximation



## References 
1. https://www.thinkautonomous.ai/blog/deep-learning-optimization/
2. https://github.com/yoshitomo-matsubara/torchdistill
