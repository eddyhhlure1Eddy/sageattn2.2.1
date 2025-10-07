## [2.2.1] - 2025-10-07

### Added
- Smart routing system for dynamic kernel selection
- GPU architecture-aware optimizations (SM75-SM120)
- Scenario-adaptive configuration (decode/prefill/batch)
- Hybrid quantization strategy (INT8+FP8)
- Comprehensive benchmarking suite
- Technical paper with detailed analysis

### Enhanced
- Performance improvements up to 34.5% in multi-batch scenarios
- Memory bandwidth reduction through optimized quantization
- Numerical stability with adaptive smooth quantization
- Support for latest GPU architectures (Blackwell SM120)

### Technical Details
- Integration with SageAttention 2.2.0 base
- Advanced compilation optimizations
- Architecture-specific kernel implementations
- Intelligent workload classification

### Performance
- Average 2.4x speedup over baseline implementations
- Up to 3.68x speedup in large sequence scenarios
- Maintained numerical accuracy (>99.95%)
- Reduced memory bandwidth requirements

## [2.2.0] - Base Version
- Official SageAttention 2.2.0 features
- SageAttention2++ implementation
- SageAttention3 for Blackwell architecture
- FlashAttention3 integration
<img width="4767" height="3543" alt="figure5_comprehensive_advantage" src="https://github.com/user-attachments/assets/11029572-8584-4d96-bf3a-a19a6a1afaa2" />
<img width="4773" height="2292" alt="figure4_smart_routing_effectiveness" src="https://github.com/user-attachments/assets/699cdb7a-3464-427a-8bff-d35f9c5a2110" />
<img width="4472" height="1759" alt="figure3_quantization_analysis" src="https://github.com/user-attachments/assets/0935997e-a5c6-4a8b-8ff6-80d289f15ec1" />
<img width="3780" height="2405" alt="figure2_system_architecture" src="https://github.com/user-attachments/assets/75a5602c-3d93-486a-84ee-f7f9a33c04a3" />
<img width="4171" height="2363" alt="figure1_performance_comparison" src="https://github.com/user-attachments/assets/624dfd26-67fe-4e1a-bf83-aeace03d3ca4" />
