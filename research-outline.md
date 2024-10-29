# Understanding Human Perceptual Decision-Making Through Neural Networks: A Study of Bistable Perception

## Project Overview

### What We're Studying
We're investigating how artificial neural networks handle ambiguous visual inputs (like the famous duck-rabbit illusion) and comparing this to human perceptual decision-making. This helps us understand both human cognition and machine learning behavior.

### Why It Matters
- Bridges computational neuroscience and human psychology
- Provides insights into decision-making under uncertainty
- Helps understand how both brains and machines handle ambiguous information
- Could inform better AI systems that mirror human perception

## The Science Behind It

### Key Concept: Bistable Perception
When humans encounter ambiguous images (like the Necker cube), they:
- See one interpretation at a time
- Spontaneously switch between interpretations
- Show predictable patterns in switching behavior
- Are influenced by prior expectations

### The Big Question
How do neural networks process these same ambiguous inputs, and what does this tell us about human perception?

## Why This is Feasible for Undergraduates

### Technical Requirements (All Readily Available)
- Python with PyTorch
- Standard CNN architectures
- Basic GPU access (Google Colab is sufficient)
- Common datasets + bistable images

### Required Skills (All Standard CS/Neuro Coursework)
- Basic deep learning concepts
- Python programming
- Data analysis
- Experiment design

### Clear Scope
- Well-defined experiments
- Established evaluation metrics
- Manageable timeline (one semester)
- Builds on existing code frameworks

## The Literature That Backs Us Up

### Foundational Papers
1. Lee & Mumford (2003) - "Hierarchical Bayesian Inference in the Visual Cortex"
   - Provides theoretical framework
   - Shows how brain handles ambiguity

2. Yamins & DiCarlo (2016) - "Using Goal-Driven Deep Learning Models to Understand Sensory Cortex"
   - Links neural networks to brain function
   - Provides methodological framework

### Recent Technical Implementations
3. Lotter et al. (2017) - "Deep Predictive Coding Networks"
   - Practical implementation examples
   - Available code base

## Proposed Experiment

### Phase 1: Network Training
1. Train standard CNNs on image classification
2. Create variations with different architectures:
   - Basic CNN
   - ResNet
   - Vision Transformer

### Phase 2: Bistable Testing
1. Present networks with classic bistable images:
   - Necker cube
   - Duck-rabbit illusion
   - Rubin's vase

2. Analyze network behavior:
   - Classification probabilities
   - Hidden layer activations
   - Response to slight image variations

### Phase 3: Human Comparison
1. Compare with existing human behavioral data:
   - Switching patterns
   - Classification tendencies
   - Response to priming

## What We Need

### Data Sources
1. Standard datasets:
   - MNIST
   - CIFAR-10
   - ImageNet subset

2. Bistable image sets:
   - Available through vision research databases
   - Can be synthesized using existing tools

### Tools
1. Programming:
   - Python
   - PyTorch
   - Jupyter Notebooks

2. Analysis:
   - NumPy/Pandas
   - Matplotlib/Seaborn
   - Basic statistical tools

## Expected Results and Implications

### What We Might Find
1. How neural networks "decide" between competing interpretations
2. Whether networks show human-like switching behavior
3. How architecture affects ambiguity resolution
4. Role of training in bias development

### Broader Implications
1. Understanding human perception better
2. Improving AI systems
3. Insights into decision-making processes
4. Connections between machine and biological learning

## Timeline and Milestones

### Month 1-2
- Literature review
- Setup development environment
- Initial network implementation

### Month 3-4
- Train networks
- Run bistable experiments
- Collect results

### Month 5-6
- Analysis
- Comparison with human data
- Documentation

## Extensions and Future Work

### Possible Extensions
1. Different network architectures
2. More complex stimuli
3. Real-time analysis
4. Additional behavioral comparisons

### Applications
1. Computer vision systems
2. Perceptual psychology
3. AI interpretability
4. Cognitive modeling

## Why This Project Matters

### Scientific Value
- Bridges computational and cognitive approaches
- Tests theoretical predictions
- Provides quantitative insights

### Educational Value
- Hands-on experience with:
  - Deep learning
  - Experimental design
  - Data analysis
  - Scientific writing

### Practical Value
- Clear deliverables
- Manageable scope
- Real results
- Publication potential
