<p align="center">
  <img src="./img.png" alt="Project Banner" width="100%">
</p>

# Parallel universe generator 🎯

## Basic Details

### Team Name: ElNova

### Team Members
- Member 1:riya anna kf - sree narayana gurukulam college of engineering
- Member 2:parvathy venu - sree narayana gurukulam college of engineering

### Hosted Project Link
https://parallel-universe.netlify.app/

### Project Description
Parallel Universe Generator is an web application that shows users two possible future narratives based on their habits and consistency. It creates reflective, motivating outcomes that help users visualize the long-term impact of their daily choices.

### The Problem statement
Many people struggle to stay consistent with their goals because the long-term consequences of their habits feel abstract and distant. Traditional goal-tracking tools focus on numbers and reminders, not emotional motivation or self-reflection.

### The Solution
Our project simulates “parallel futures” — one where the user stays consistent and one where they don’t. By turning habits into personalized, narrative-based outcomes, the app makes future consequences feel real, emotional, and motivating, helping users reflect and take action.

---

## Technical Details

### Technologies/Components Used

**For Software:**
Languages used:
JavaScript, HTML, CSS

Frameworks used:
Node.js, Express.js

Libraries used:
Google Gemini Generative AI API, Fetch API, CORS

Tools used:
Visual Studio Code, Git, GitHub, Live Server (VS Code extension), Browser DevTools

**For Hardware:**
Main components:
Personal Computer / Laptop

Specifications:

Minimum 8 GB RAM

Modern web browser (Chrome / Edge / Firefox)

Internet connection for AI API access

Tools required:
Keyboard, Mouse/Trackpad, Internet connectivity

---

## Features


Generates two distinct future narratives 

Personalized Goal Narratives
Uses user inputs such as goal, habit, time period, challenges, and strengths to create highly customized motivational stories.

Reflective & Motivational Storytelling
Moves beyond simple reminders by focusing on identity, consequences, and long-term growth through narrative-based motivation.

Consistency Comparison
Displays side-by-side outcomes for consistent vs inconsistent behavior, encouraging self-reflection and accountability.

Simple & Intuitive Interface
Clean, minimal UI that allows users to generate insights with just a few inputs.

Goal Saving & Review
Users can save generated futures and revisit them later to track mindset and motivation over time.

Real-Time AI Generation
Narratives are generated instantly using generative AI, making each experience unique.
---

## Implementation

### For Software:

#### Installation
```bash
[Installation: npm install, ]
```

#### Run
```bash
Run commands -, npm start
```

### For Hardware:

#### Components Required
[List all components needed with specifications]

#### Circuit Setup
[Explain how to set up the circuit]

---

## Project Documentation

### For Software:

#### Screenshots (Add at least 3)


*Add caption explaining what this shows*

https://drive.google.com/file/d/1XY5uhR2xo3BJYHdxXymDZxNqzlYFw9_I/view?usp=drivesdk
Data entering menu

https://drive.google.com/file/d/1-pJVbDcWnLzXBo5C9L2pMbSWb2zZe0oS/view?usp=drivesdk
Program result

![Screenshot3](Add screenshot 3 here with proper name)
*Add caption explaining what this shows*

#### Diagrams

**System Architecture:**

![Architecture Diagram](docs/architecture.png)
*Explain your system architecture - components, data flow, tech stack interaction*

**Application Workflow:**

https://drive.google.com/file/d/1RqI_wTNvhqKMbE-gB4S2bjKQBHePGI_5/view?usp=drivesdk

The web works starting from Login/Register to a central Launch/Revise hub. Choosing "Launch" opens a detailed setup form for goals and habits, which then sorts users into Version A (Consistent) or Version B (Inconsistent) before reaching a final Saved state. Alternatively, selecting "Revise" allows users to manage Already Saved Goals by checking their current status. If the user is Still Continuing, the goal remains Saved; if not, the record is permanently deleted from the Web.

---

### For Hardware:

#### Schematic & Circuit

![Circuit](Add your circuit diagram here)
*Add caption explaining connections*

![Schematic](Add your schematic diagram here)
*Add caption explaining the schematic*

#### Build Photos

![Team](Add photo of your team here)

![Components](Add photo of your components here)
*List out all components shown*

![Build](Add photos of build process here)
*Explain the build steps*

![Final](Add photo of final product here)
*Explain the final build*

---

## Additional Documentation

### For Web Projects with Backend:

#### API Documentation

**Base URL:** `https://api.yourproject.com`

##### Endpoints

**GET /api/endpoint**
- **Description:** [What it does]
- **Parameters:**
  - `param1` (string): [Description]
  - `param2` (integer): [Description]
- **Response:**
```json
{
  "status": "success",
  "data": {}
}
```

**POST /api/endpoint**
- **Description:** [What it does]
- **Request Body:**
```json
{
  "field1": "value1",
  "field2": "value2"
}
```
- **Response:**
```json
{
  "status": "success",
  "message": "Operation completed"
}
```

[Add more endpoints as needed...]

---

### For Mobile Apps:

#### App Flow Diagram

![App Flow](docs/app-flow.png)
*Explain the user flow through your application*

#### Installation Guide

**For Android (APK):**
1. Download the APK from [Release Link]
2. Enable "Install from Unknown Sources" in your device settings:
   - Go to Settings > Security
   - Enable "Unknown Sources"
3. Open the downloaded APK file
4. Follow the installation prompts
5. Open the app and enjoy!

**For iOS (IPA) - TestFlight:**
1. Download TestFlight from the App Store
2. Open this TestFlight link: [Your TestFlight Link]
3. Click "Install" or "Accept"
4. Wait for the app to install
5. Open the app from your home screen

**Building from Source:**
```bash
# For Android
flutter build apk
# or
./gradlew assembleDebug

# For iOS
flutter build ios
# or
xcodebuild -workspace App.xcworkspace -scheme App -configuration Debug
```

---

### For Hardware Projects:

#### Bill of Materials (BOM)

| Component | Quantity | Specifications | Price | Link/Source |
|-----------|----------|----------------|-------|-------------|
| Arduino Uno | 1 | ATmega328P, 16MHz | ₹450 | [Link] |
| LED | 5 | Red, 5mm, 20mA | ₹5 each | [Link] |
| Resistor | 5 | 220Ω, 1/4W | ₹1 each | [Link] |
| Breadboard | 1 | 830 points | ₹100 | [Link] |
| Jumper Wires | 20 | Male-to-Male | ₹50 | [Link] |
| [Add more...] | | | | |

**Total Estimated Cost:** ₹[Amount]

#### Assembly Instructions

**Step 1: Prepare Components**
1. Gather all components listed in the BOM
2. Check component specifications
3. Prepare your workspace
![Step 1](images/assembly-step1.jpg)
*Caption: All components laid out*

**Step 2: Build the Power Supply**
1. Connect the power rails on the breadboard
2. Connect Arduino 5V to breadboard positive rail
3. Connect Arduino GND to breadboard negative rail
![Step 2](images/assembly-step2.jpg)
*Caption: Power connections completed*

**Step 3: Add Components**
1. Place LEDs on breadboard
2. Connect resistors in series with LEDs
3. Connect LED cathodes to GND
4. Connect LED anodes to Arduino digital pins (2-6)
![Step 3](images/assembly-step3.jpg)
*Caption: LED circuit assembled*

**Step 4: [Continue for all steps...]**

**Final Assembly:**
![Final Build](images/final-build.jpg)
*Caption: Completed project ready for testing*

---

### For Scripts/CLI Tools:

#### Command Reference

**Basic Usage:**
```bash
python script.py [options] [arguments]
```

**Available Commands:**
- `command1 [args]` - Description of what command1 does
- `command2 [args]` - Description of what command2 does
- `command3 [args]` - Description of what command3 does

**Options:**
- `-h, --help` - Show help message and exit
- `-v, --verbose` - Enable verbose output
- `-o, --output FILE` - Specify output file path
- `-c, --config FILE` - Specify configuration file
- `--version` - Show version information

**Examples:**

```bash
# Example 1: Basic usage
python script.py input.txt

# Example 2: With verbose output
python script.py -v input.txt

# Example 3: Specify output file
python script.py -o output.txt input.txt

# Example 4: Using configuration
python script.py -c config.json --verbose input.txt
```

#### Demo Output

**Example 1: Basic Processing**

**Input:**
```
This is a sample input file
with multiple lines of text
for demonstration purposes
```

**Command:**
```bash
python script.py sample.txt
```

**Output:**
```
Processing: sample.txt
Lines processed: 3
Characters counted: 86
Status: Success
Output saved to: output.txt
```

**Example 2: Advanced Usage**

**Input:**
```json
{
  "name": "test",
  "value": 123
}
```

**Command:**
```bash
python script.py -v --format json data.json
```

**Output:**
```
[VERBOSE] Loading configuration...
[VERBOSE] Parsing JSON input...
[VERBOSE] Processing data...
{
  "status": "success",
  "processed": true,
  "result": {
    "name": "test",
    "value": 123,
    "timestamp": "2024-02-07T10:30:00"
  }
}
[VERBOSE] Operation completed in 0.23s
```

---

## Project Demo

### Video
[Add your demo video link here - YouTube, Google Drive, etc.]

*Explain what the video demonstrates - key features, user flow, technical highlights*

### Additional Demos
[Add any extra demo materials/links - Live site, APK download, online demo, etc.]

---

## AI Tools Used (Optional - For Transparency Bonus)

If you used AI tools during development, document them here for transparency:

**Tool Used:** [e.g., GitHub Copilot, v0.dev, Cursor, ChatGPT, Claude]

**Purpose:** [What you used it for]
- Example: "Generated boilerplate React components"
- Example: "Debugging assistance for async functions"
- Example: "Code review and optimization suggestions"

**Key Prompts Used:**
- "Create a REST API endpoint for user authentication"
- "Debug this async function that's causing race conditions"
- "Optimize this database query for better performance"

**Percentage of AI-generated code:** [Approximately X%]

**Human Contributions:**
- Architecture design and planning
- Custom business logic implementation
- Integration and testing
- UI/UX design decisions

*Note: Proper documentation of AI usage demonstrates transparency and earns bonus points in evaluation!*

---

## Team Contributions

- [Name 1]: [Specific contributions - e.g., Frontend development, API integration, etc.]
- [Name 2]: [Specific contributions - e.g., Backend development, Database design, etc.]
- [Name 3]: [Specific contributions - e.g., UI/UX design, Testing, Documentation, etc.]

---

## License

This project is licensed under the [LICENSE_NAME] License - see the [LICENSE](LICENSE) file for details.

**Common License Options:**
- MIT License (Permissive, widely used)
- Apache 2.0 (Permissive with patent grant)
- GPL v3 (Copyleft, requires derivative works to be open source)

---

Made with ❤️ at TinkerHub
