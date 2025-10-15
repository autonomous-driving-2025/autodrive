# autodrive

Autonomous Driving Platform 2025

## Getting Started

Follow these instructions to set up the development environment for the autodrive project.

### Prerequisites

- Git
- vcstool
- ROS 2

### Installation

1. Clone the main repository:
   ```bash
   git clone https://github.com/autonomous-driving-2025/autodrive.git
   cd autodrive
   ```

2. Import all required repositories using vcstool:
   ```bash
   sudo apt install vcstool
   ```

   ```bash
   vcs import src < .repos
   ```

3. Build the project (if using ROS 2):
   ```bash
   colcon build
   ```

## Project Structure

The project uses a multi-repository structure managed through the `.repos` file.

## License

This project is licensed under [LICENSE NAME] - see the LICENSE file for details.

## Contributors

- Autonomous Driving Team 2025
