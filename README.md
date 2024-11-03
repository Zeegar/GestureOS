# Gesture OS

## Overview

**Gesture OS** is an experimental project that leverages movement and gestures to control basic OS functions on Windows, macOS, and Linux. Using the **Ultraleap Motion Controller 2** and **Ultraleap Hyperion software**, this project aims to transform repetitive computer tasks into interactive, movement-based actions. The goal is to create a minimalistic, gesture-driven interface as an alternative to traditional inputs, engaging users in physical activity while performing tasks like email management, app navigation, and media control.

For more detailed information, please refer to the [Software Requirements Specification (SRS)](SRS.md).

---

## Project Aims

The primary aim of **Gesture OS** is to blend productivity with movement, turning mundane OS tasks into engaging "mini-games" that encourage regular physical activity and break up sedentary time. Key objectives include:

- **Physical Interaction**: Introduce light exercise through OS tasks.
- **Gesture-Based Efficiency**: Simplify routine actions with intuitive, hands-free gestures.
- **Minimalist Design**: Focus on uncluttered interaction.
- **Expandability**: Create a flexible foundation for additional gestures and functionality.

---

## Features & User Interface

1. **Minimalistic Main Interface**:
   - Clean, essential task-related icons optimised for gesture interaction.
   
2. **Expandable Settings**:
   - A collapsible settings area for gesture, sensitivity, and task configuration, accessible by both gesture and traditional inputs.
   
3. **Gesture Feedback**:
   - Visual cues like trails or subtle colour changes confirm gesture recognition.
   
4. **Flexible Task Integration**:
   - Quick access to tasks like email, app shortcuts, and media control, with gesture customisation options.

---

## Inputs

**Gesture OS** uses the **Ultraleap Motion Controller 2** with **Ultraleap Hyperion** software for high-accuracy gesture tracking:

- **Hand Gestures**: Predefined gestures like swipes, pinches, and taps for control.
- **Complex Movements**: Recognition of nuanced gestures for task switching and dismissing notifications.
- **Sensitivity Customisation**: Adjustable gesture sensitivity tailored to user preference.

---

## Getting Started

### Unity Setup

To create the application UI, we use Unity. Follow these steps to set up Unity for the project:

1. **Download and Install Unity**: Visit the [Unity website](https://unity.com/) and download the latest version of Unity Hub. Use Unity Hub to install the latest LTS (Long Term Support) version of Unity.
2. **Open the Project in Unity**: Clone the repository and open the project folder in Unity Hub. Click on "Add" and select the project folder.
3. **Install Required Packages**: Open the project in Unity and go to "Window" > "Package Manager". Install any required packages listed in the project documentation.
4. **Configure Build Settings**: Go to "File" > "Build Settings" and configure the build settings according to the target platform (Windows, macOS, or Linux).
5. **Run the Project**: Click on the "Play" button in the Unity Editor to run the project and test the UI.

### Roadmap

#### 1. Setup and Testing
   - **Install Ultraleap Hyperion** and calibrate the device.
   - **Basic Interaction Testing**: Confirm basic gestures for actions like clicks, swipes, and zooms.

#### 2. Prototype UI
   - **UI Layout**: Create a simple interface with task icons and collapsible settings.
   - **Gesture Feedback System**: Add visual gesture confirmations.
   - **Gesture Focus Icon**: Create a focus icon that can lock onto clickable items on screen.

#### 3. Core Gesture Integration
   - **OS Function Controls**: Integrate gestures for email management, web browsing, and media control.
   - **Gesture Customisation**: Enable user-defined gesture assignments.

#### 4. Advanced Interaction and Testing
   - **Complex Gestures**: Experiment with gestures for task switching and notifications.
   - **User Feedback**: Iterate on gesture accuracy and UI layout.

---

## Project Roadmap

1. **Phase 1: Setup & Basic Gesture Testing**
   - Set up Ultraleap Hyperion and test basic gesture interactions.

2. **Phase 2: UI Prototype & Core Functionality**
   - Develop core gesture functions and initial UI layout using Unity.

3. **Phase 3: Advanced Gestures & Cross-Platform Testing**
   - Implement advanced gestures and ensure compatibility across OS platforms.

4. **Phase 4: User Testing & Expansion**
   - Gather feedback and add additional OS tasks and gestures.

---

## Contributing

Contributions are encouraged in areas like:
- **Gesture Development**: Experiment with and refine gestures.
- **UI Enhancements**: Improve the interface or add new features.
- **Cross-Platform Support**: Help optimise for various OS environments.

---

## Future Enhancements

- **Voice Integration**: Add voice commands as a complement to gestures.
- **Activity Tracking**: Monitor physical activity during use.
- **Third-Party App Support**: Allow users to map gestures to custom apps for a tailored experience.

---

## Contact

For questions, suggestions, or to contribute, please reach out via the Issues section on GitHub.
