# DebugSubGraph
This is an Unity SubGraph specifically designed for debugging in the ShaderGraph Window. It's incredibly easy to set up and use.

# Credits
All the code in this repository is based on the work of [aras-p](https://github.com/aras-p) and [bestknighter](https://github.com/bestknighter) as seen in [DebugNode.hlsl](https://gist.github.com/aras-p/657a4947bb8a4549fda53a84bb91fb25). 

# How to Use
Follow these simple steps to get started:

1. Download the package and import it into your Unity project.
2. Drag the subgraph into the ShaderGraph window.
3. Link the input value you want to debug.

The subgraph has two input parameters:

1. DebugValue (float) : This is the value you want to debug. The value will be displayed in the subgraph preview.
2. DecimalDigits (float) : This is the number of decimal digits that the debugged value will display in the subgraph preview.

Here's an example of how it looks:

![image](https://github.com/WillardPeng/DebugSubGraph/assets/42560230/8a0816ae-8913-48de-b025-76fdd2d9ac44)
