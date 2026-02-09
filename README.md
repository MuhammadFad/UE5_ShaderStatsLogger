# UE5 Shader Stats Logger

A comprehensive performance logging system for Unreal Engine 5 that automatically collects and transmits shader and system performance data from players to help developers optimize game performance.

## 📋 Project Overview

This project is designed to gather real-world performance metrics from players' computers while they play a demo game built with Unreal Engine 5. The primary focus is on shader performance statistics, which are crucial for understanding how games perform across different hardware configurations.

### What This Project Does

- **Automatic Performance Logging**: Runs silently in the background while players enjoy the demo game
- **Shader Statistics Collection**: Captures detailed metrics about shader compilation, execution times, and rendering performance
- **System Metrics**: Records hardware specifications and performance characteristics
- **Telemetry Transmission**: Automatically sends collected data to developers for analysis
- **Demo Game Integration**: Ships with a small demo game that showcases various rendering scenarios and shader techniques

## 🎯 Key Features (Planned)

- **Non-Intrusive Monitoring**: Minimal performance overhead to ensure accurate real-world measurements
- **Comprehensive Shader Metrics**:
  - Shader compilation times
  - GPU execution performance
  - Frame rendering statistics
  - Material complexity metrics
- **Hardware Profiling**:
  - GPU model and driver information
  - CPU specifications
  - Memory configuration
  - Operating system details
- **Scene-Based Analysis**: Performance data categorized by different game scenes and scenarios
- **Privacy-Conscious**: Only collects performance and hardware data - no personal information
- **Opt-in System**: Players are informed about data collection with clear privacy policies

## 🎮 Demo Game

The project includes a small demo game built in Unreal Engine 5 that features:
- Multiple scenes with varying rendering complexity
- Diverse shader usage (PBR materials, post-processing effects, particle systems)
- Different lighting scenarios (dynamic, static, ray-traced)
- Various gameplay scenarios to test performance under different conditions

This demo serves as both a testing ground for the logging system and a realistic gameplay environment to collect meaningful performance data.

## 🔬 Research Goals

The collected data will be used to:
- Understand shader performance across different hardware configurations
- Identify optimization opportunities for UE5 shader code
- Analyze real-world performance patterns that might not appear in controlled testing
- Create hardware-specific optimization profiles
- Improve shader compilation strategies
- Better understand the relationship between scene complexity and shader performance

## 🔒 Privacy & Data Collection

**What We Collect:**
- Shader performance metrics and statistics
- GPU and CPU hardware specifications
- Frame rate and rendering performance data
- Scene and gameplay context information
- Operating system and driver versions

**What We DON'T Collect:**
- Personal information (names, emails, etc.)
- User behavior or input data
- Screenshots or game content
- Network activity or browsing history
- Any data unrelated to game performance

Players will be clearly informed about data collection before playing, and all data transmission is handled securely.

## 📊 Project Status

**Current Status**: 🏗️ **In Development**

This repository is in its early stages. The project is being planned and designed. The following components are planned for development:

### Roadmap

- [ ] Design logging architecture
- [ ] Implement shader statistics capture system
- [ ] Create demo game with test scenes
- [ ] Develop data transmission backend
- [ ] Build privacy and consent system
- [ ] Create data analysis pipeline
- [ ] Testing and optimization
- [ ] Documentation and deployment

## 🛠️ Technology Stack (Planned)

- **Game Engine**: Unreal Engine 5
- **Programming Languages**: C++ (UE5 native), potentially Blueprint
- **Data Format**: JSON/Binary for telemetry data
- **Backend**: TBD (for receiving and storing performance data)

## 📚 Documentation

As the project develops, documentation will be added for:
- Installation and setup instructions
- Building the demo game
- Configuring the logger
- Understanding collected metrics
- Contributing guidelines
- API documentation

## 🤝 Contributing

This is a research project. More information about contributing will be provided as the project progresses.

## 📄 License

License information will be added as the project develops.

## 📧 Contact

For questions or inquiries about this project, please open an issue on this repository.

---

**Note**: This project is under active development. Features, implementation details, and documentation are subject to change as the project evolves.
