# TimeTart

**TimeTart** is a productivity app designed to help you visualize and manage your office hours using the Pomodoro technique. It divides your workday into a 9-hour pie chart, allowing you to track how your time is spent on different tasks.

## Features

- **Pomodoro Timer**: Configurable Pomodoro sessions with alerts.
- **Full-Screen Modal**: Blocks the screen after each session to encourage focus and reflection.
- **Interactive Pie Chart**: Select the task you worked on during each session, updating a 9-hour chart in real time.
- **Custom Task Categories**: Predefine categories like "Data Engineering," "LLM Engineering," etc., to suit your workday.
- **Data Tracking**: Save and analyze how your time is distributed across tasks.

## Screenshots
(Insert screenshots of the app interface, including the pie chart and modal screen)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/rhasanm/time-tart.git
   ```
2. Navigate to the project directory:
   ```bash
   cd time-tart
   ```
3. Install Rust and Cargo (if not already installed). Follow instructions from [rust-lang.org](https://www.rust-lang.org/).
4. Install the Tauri CLI:
   ```bash
   cargo install tauri-cli
   ```
5. Build and run the app:
   ```bash
   cargo tauri dev
   ```

## Usage

1. Configure your task categories and Pomodoro session length in the settings.
2. Start the timer to begin your first Pomodoro session.
3. At the end of each session, a full-screen modal will appear, prompting you to select the task you worked on.
4. Watch as your 9-hour pie chart updates dynamically, reflecting your time allocation.

## Tech Stack

- **Language**: Rust
- **Framework**: Tauri
- **Frontend**: WebAssembly (WASM) with a lightweight web-based UI
- **Charts**: D3.js or Chart.js for the pie chart visualization
- **Styling**: CSS (or frameworks like Tailwind CSS for styling the frontend)

## Future Enhancements

- Add support for exporting time data as CSV or PDF.
- Integrate with calendars for automated task suggestions.
- Provide insights and recommendations based on time usage patterns.
- Enable cross-device synchronization.

## Contributing

Contributions are welcome! To get started:

1. Fork the repository.
2. Create a new branch for your feature or bugfix:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature-name"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

TimeTart is inspired by the Pomodoro technique and aims to make time tracking simple and intuitive. Special thanks to all contributors and users for their support!

---

Feel free to reach out with any feedback or suggestions via [GitHub Issues](https://github.com/rhasanm/time-tart/issues).
