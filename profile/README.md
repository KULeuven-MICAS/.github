## 
![](https://user-images.githubusercontent.com/84473288/235626814-7550aa13-baff-4ddd-bcb0-69a6f0a46f88.svg) 

This is the GitHub organization for the MICAS research group at KU Leuven. Here you can find open-source projects made by us and our collaborators.

## SNAX Framework

Snax is an end-to-end, open-source multi-accelerator cluster design framework. It consists of the snax-mlir compile toolchain and the snax cluster hardware framework.

### SNAX-MLIR [Repo](https://github.com/kuleuven-micas/snax-mlir)

### SNAX Cluster [Repo](https://github.com/kuleuven-micas/snax_cluster)

### HeMAiA [Repo](https://github.com/kuleuven-micas/HeMAiA)

## Fast DNN Accelerator Design Space Exploration Frameworks


### ZigZag [Repo](https://github.com/KULeuven-MICAS/zigzag) | [Documentation](https://kuleuven-micas.github.io/zigzag/) | [Tutorial](https://www.youtube.com/watch?v=VgUuG4QaSQQ&list=PLUi74Rw4uFDIuK_6FCF9Bv7SMJlHfG4l3)
ZigZag targets rapid DSE for DNN accelerator platforms supporting an broad set of hardware architectures and workload scheduling scenarios beyond other existing frameworks.<br>
The latest version of ZigZag includes support for modeling of analog and digital in-memory computing accelerators and estimating both peak/workload performance at the macro and system level.
### Stream [Repo](https://github.com/KULeuven-MICAS/stream) | [Documentation](https://kuleuven-micas.github.io/stream/) | [Tutorial](https://www.youtube.com/watch?v=9LVIVy1_ukw&list=PLUi74Rw4uFDIuK_6FCF9Bv7SMJlHfG4l3&index=6)
Stream is an extension of ZigZag capable of modeling multi-core DNN acceleration employing fine-grained layer-fused processing.
### ZigZag-LLM [Repo](https://github.com/KULeuven-MICAS/zigzag-llm)
ZigZag-LLM is a framework to rapidly model Large Language Models on dedicated, single-core accelerators and facilitates early identification of energy bottlenecks within the hardware architecture.
### DeFiNes [Repo](https://github.com/KULeuven-MICAS/defines)
DeFiNes extends ZigZag to enable the DSE of cross-layer depth-first scheduling (a.k.a. layer fusion, or cascaded execution)
</br>

## Accelerator-aware Neural Network Deployment
### HTVM [Repo](https://github.com/KULeuven-MICAS/htvm)
HTVM is a neural network compiler based on [Dory](https://github.com/pulp-platform/dory) and [TVM](https://github.com/apache/tvm) that allows for efficient neural network deployment on heterogenous TinyML platforms with scratchpad-memory accelerators.
</br>

## Standalone hardware blocks
### [Chisel-Float](https://github.com/KULeuven-MICAS/chisel-float)
Floating point units (add, mul, FMA) for transprecision computing in arbitrary FP formats, wrapped and tested in Chisel.

## Artificial Intelligence System on Chips (SoCs)

### TinyVers [Repo](https://github.com/KULeuven-MICAS/tinyvers)
<p><img src="https://user-images.githubusercontent.com/84473288/235628502-2c759d2c-3881-4beb-ab17-9a6b078547f9.png"
 style="float: left; margin-right: 20px; width:19%"  /> </p>

[TinyVers: A Tiny Versatile System-on-Chip With State-Retentive eMRAM for ML Inference at the Extreme Edge](https://ieeexplore.ieee.org/document/10022047) (JSSC'23)

[TinyVers: A 0.8-17 TOPS/W, 1.7 μW-20 mW, Tiny Versatile System-on-chip with State-Retentive eMRAM for Machine Learning Inference at the Extreme Edge](https://ieeexplore.ieee.org/document/9830409) (VLSI Technology and Circuits'23)

### DIANA

<p><img src="https://user-images.githubusercontent.com/84473288/235630431-4c3c79f3-3979-4e70-b451-ff7e452d894c.png"
 style="float: left; margin-right: 14px; width:20%"  /> </p>
 
[DIANA: An End-to-End Energy-Efficient Digital and ANAlog Hybrid Neural Network SoC](https://ieeexplore.ieee.org/document/9731716) (ISSCC'22)

[DIANA: An End-to-End Hybrid DIgital and ANAlog Neural Network SoC for the Edge](https://ieeexplore.ieee.org/document/9932871) (JSSC'23)


### DPU [Repo](https://github.com/nimish15shah/DPU_DAG_Processing_Unit)
<p><img src="https://user-images.githubusercontent.com/84473288/235633846-b25ab195-c78e-42fb-8d45-f81c61ed774d.JPG"
 style="float: left; margin-right: 12px; width:20%" /> </p>

[DPU: DAG Processing Unit for Irregular Graphs With Precision-Scalable Posit Arithmetic in 28 nm](https://ieeexplore.ieee.org/document/9663412) (JSSC'22)

### DPU-v2 [Repo](https://github.com/nimish15shah/DAG_Processor)

[DPU-v2: Energy-efficient execution of irregular directed acyclic graphs](https://ieeexplore.ieee.org/document/9923858) (MICRO'22)

### AIA [Repo](https://github.com/KULeuven-MICAS/aia_chip)
[AIA: A Customized Multi-Core RISC-V SoC for Discrete Sampling Workloads in 16 nm](https://ieeexplore.ieee.org/abstract/document/10980265) (JSSC'25)

</br></br>




