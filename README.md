# Dil - Guided Breathing Meditation App
Dil is a web-based meditation app designed to reduce anxiety and lower blood pressure through scientifically-backed breathing techniques. The app offers different guided modes, including the 4-7-8 technique, 4-7-3 technique, and 4-4-4-4 square breathing. These customizable modes are complemented by visual and textual cues, creating a calming experience for users.

## Features
### Breathing Techniques:
Offers multiple guided breathing modes:
- 4-7-3 Technique: Inhale for 4 seconds, hold for 7 seconds, exhale for 3 seconds.
- 4-7-8 Technique: Inhale for 4 seconds, hold for 7 seconds, exhale for 8 seconds.
- 4-4-4-4 Square Breathing: Inhale, hold, exhale, and pause for 4 seconds each.

### Calming Visuals:
Animated clouds and a central "breathing balloon" guide users through each stage of the breathing cycle.
A soothing color palette enhances the relaxation experience.

### Affirmations:
Randomly displayed affirmations encourage and motivate users during their session.

### Session Timer:
A countdown timer displays the remaining session time (default: 4 minutes).

Interactive End Screen:
At the end of the session, users are prompted to either start another session or exit the app.

## Getting Started
Prerequisites
To run this project, you need a modern web browser that supports HTML5 and JavaScript.

Installation
Clone this repository to your local machine:

git clone https://github.com/your-username/dil-guided-breathing-app.git

Navigate to the project folder:
cd dil-guided-breathing-app

Open the index.html file in your preferred browser.

Deployment

This project can be deployed to any static hosting platform, such as:

GitHub Pages

Netlify

Vercel

Usage

Open the app in your browser.

Select your preferred breathing mode (4-7-8, 4-7-3, or 4-4-4-4 square breathing).

Click on the canvas to start the meditation session.

Follow the visual and textual cues to breathe in, hold, and breathe out.

At the end of the session, decide whether to start a new session or close the app.

File Structure

.
├── index.html        # Main HTML file for the app
├── app_logo.png      # Placeholder for the app logo (replace with your logo)
├── Mid_Bubble.svg    # Central balloon image used for breathing animation
├── white fluffy cloud.png  # Background cloud image
└── README.md         # Documentation file (this file)

Customization

Breathing Techniques

Modify or add new techniques in the <script> section of index.html by adjusting the inhale, hold, exhale, and pause durations.

Session Duration

Change the default session duration by modifying the totalDuration variable in the <script> section of index.html (default: 240 seconds).

Images

Replace the placeholder images (app_logo.png, Mid_Bubble.svg, and white fluffy cloud.png) with your own assets to personalize the app.

Affirmations

Add, remove, or modify the affirmations in the affirmations array to suit your audience.

Technologies Used

HTML5: For structuring the app.

CSS3: For styling and layout.

JavaScript (Vanilla): For animation and interactivity.

Contributing

Contributions are welcome! If you’d like to contribute, please follow these steps:

Fork the repository.

Create a new branch for your feature or bug fix:

git checkout -b feature-name

Commit your changes:

git commit -m "Add new feature"

Push to your branch:

git push origin feature-name

Open a pull request on GitHub.

License

This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments

Special thanks to all open-source contributors who made this project possible.

Inspired by the need for accessible, simple tools for mindfulness and relaxation.

Contact

For questions or feedback, feel free to contact:

Name: Your Name

Email: your.email@example.com

GitHub: your-username

