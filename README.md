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
<img width="4773" height="2292" alt="figure4_smart_routing_effectiveness" src="https://github.com/user-attachments/assets/a920c264-c6ee-48dd-accb-c4b56e8587cf" />
<img width="3780" height="2405" alt="figure2_system_architecture" src="https://github.com/user-attachments/assets/bac44171-b131-42ba-861e-e779fd851faa" />
<img width="4767" height="3543" alt="figure5_comprehensive_advantage" src="https://github.com/user-attachments/assets/747e2ba0-c2c1-475b-8f83-e7c5b9d06693" />

