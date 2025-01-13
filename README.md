# EEGscape

**EEGscape** is a groundbreaking project designed to make gaming accessible to individuals with disabilities while also offering unique challenges to able-bodied users. By utilizing EEG (electroencephalogram) technology, we enable players to interact with games using head movements, concentration, and blinks, creating an immerse and inclusive gaming experience.

![EEGscape.png](https://github.com/user-attachments/assets/16092501-7fc9-45ab-9566-d2710ba2491f)


## :rocket: Inspiration

EEGscape started with a simple idea: let’s make gaming something everyone can enjoy, no matter what challenges they face. Traditional controllers can be tough for people who don’t have full motor control, so we thought, "Why not use your brain instead?"
But wait, there’s more! EEGscape isn’t just about accessibility—it’s a workout for your brain, too. Think of it as leveling up your focus and memory while playing awesome games. We’re just scratching the surface of what tech can do to make gaming fun, inclusive, and maybe even a little mind-bending.

---

## :video_game: What It Does

EEGscape uses EEG-powered headset like Muse to translate brain activity and physical gestures into in-game commands. Players can control a suite of interactive video games through:

- **Head Tilts**: Gyroscope data is used to detect head orientation for directional inputs.
- **Concentration**: Cognitive effort influences actions such progress in certain games.
- **Blinking**: Deliberate eye blinks are mapped to specific controls like stacking towers.
  These innovative input uses controls such as gyroscopes, brainwaves, and other actions that are built into the EEG headset.

---

## :hammer_and_wrench: How We Built It

EEGscape combines cutting-edge hardware and modern web technologies to deliver an engaging experience:

1. **Frontend Development**: The React framework serves as the foundation of our user interface, ensuring a dynamic and responsive experience.
2. **Real-Time EEG Data**: We used the MuseJS library to interpret raw signals from the EEG headset, including gyroscopic data, brainwave frequencies, and blink patterns.
3. **Game Development**: Games were built using JavaScript to provide seamless interaction and integrate with the EEG-powered input methods.
4. **Styling**: Tailwind CSS and DaisyUI were used to create a visually appealing and user-friendly interface.

---


## :hammer_and_wrench: Built With

- **React**: Frontend framework for building the user interface.
- **Vite**: Fast build tool for modern web development.
- **Tailwind CSS**: Utility-first CSS framework for styling.
- **DaisyUI**: UI components for enhanced visuals.
- **MuseJS**: Library for interfacing with Muse EEG headsets.

---

## :book: Getting Started

### Prerequisites

- A Muse EEG headset compatible with MuseJS.
- Node.js installed on your system.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/EEGscape.git
   cd EEGscape
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the application:
   ```bash
   npm run dev
   ```

## Contributors

This project was created for Hack Western 11 by the following people:

- [Dhir Pathak](https://www.linkedin.com/in/dhirpathak/)
- [Nathan Schultz](https://www.linkedin.com/in/nathan-r-a-schultz/)
- [Fatih Nararya](https://www.linkedin.com/in/fatih-nararya/)
- [Mahdi Raza Khunt](https://www.linkedin.com/in/mrkhunt/)
