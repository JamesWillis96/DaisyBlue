# GUI Audio Router

## Project Overview
This project aims to develop a GUI application written in C++ for Windows that allows users to pass audio from other applications through it, modifying the audio input based on user selection. As a stretch goal, the application will also support input via an attached microcontroller.

## Project Requirements
### Core Functional Requirements
1. **Audio Routing:**
   - Capture audio input from other applications.
   - Modify the audio input based on user selection.
   - Output the modified audio to the default audio output device.

2. **Graphical User Interface (GUI):**
   - Develop a user-friendly GUI for configuring audio routing and modifications.
   - Provide options for different audio modifications (e.g., equalizer, effects).

### Stretch Goals
1. **Microcontroller Integration:**
   - Allow users to provide input via an attached microcontroller (e.g., Arduino).

### Constraints
- The application must be developed using C++ and should run on Windows.
- Time constraints and technological limitations should be considered.

## Development Plan
### Step 1: Define Project Requirements
- Identify and document the core functional requirements.
- Identify and document the stretch goals.
- Document any limitations or constraints.

### Step 2: Setup Development Environment
- Select the technology stack:
  - Programming Language: C++
  - GUI Framework: [Qt](https://www.qt.io/) or [Win32 API](https://docs.microsoft.com/en-us/windows/win32/api/)
- Configure version control:
  - Initialize a Git repository.
  - Create an initial commit with a basic project structure.
- Setup CI/CD pipeline:
  - Use services like GitHub Actions to automate testing, building, and deployment.

### Step 3: Design the Application
- **GUI Design:**
  - Design wireframes and mockups for the GUI.
  - Define the layout and user interactions.

- **Audio Processing:**
  - Research and select libraries for audio capture and processing (e.g., [portaudio](http://www.portaudio.com/), [RtAudio](https://www.music.mcgill.ca/~gary/rtaudio/)).
  - Design the audio processing pipeline.

### Step 4: Implement Core Features
1. **Audio Routing:**
   - Implement audio capture from other applications.
   - Implement audio modification based on user selection.
   - Implement audio output to the default audio device.

2. **Graphical User Interface:**
   - Develop the main window and layout.
   - Implement user controls for configuring audio routing and modifications.

### Step 5: Implement Stretch Goals
1. **Microcontroller Integration:**
   - Implement communication with the microcontroller (e.g., via serial port).
   - Process input from the microcontroller to control audio modifications.

### Step 6: Testing and Debugging
- Write unit tests for core functionalities.
- Perform integration testing to ensure all components work together.
- Debug and fix any issues that arise during testing.

### Step 7: Documentation
- Document the code and provide comments for clarity.
- Create a user manual for the application.
- Update the README with usage instructions and examples.

### Step 8: Deployment
- Build the final executable for Windows.
- Package the application for distribution.
- Release the application on GitHub or other platforms.

## Project Timeline
- **Week 1-2:** Define requirements and set up the development environment.
- **Week 3-4:** Design the application and research necessary libraries.
- **Week 5-8:** Implement core features.
- **Week 9-10:** Implement stretch goals (if time permits).
- **Week 11-12:** Testing, debugging, and documentation.
- **Week 13:** Deployment and release.

## Contribution
- Fork the repository and create a new branch for your feature or bugfix.
- Submit a pull request with a detailed description of your changes.
- Ensure your code follows the project's coding standards and passes all tests.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
