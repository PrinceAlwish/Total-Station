### **Detailed Notes: Leica FlexLine TS02/TS06/TS09 User Manual**

These notes prioritize the practical steps and concepts needed for a surveyor to use the instrument effectively. Page numbers are referenced for quick lookup in the full PDF.

#### **Part 1: The Basics - Instrument & Interface**

##### **1.1. Key Instrument Components (p. 16-17)**
*   **(f) Objective Lens:** Where the laser (EDM) beam exits.
*   **(m) Eyepiece:** For sighting the target. Focus this first to get a sharp crosshair (graticule). Then focus the main telescope image.
*   **(g) & (j) Vertical & Horizontal Drives:** The large knobs for coarse rotation. The smaller knobs on top are for fine, precise aiming.
*   **(h) On/Off Key:** Located on the side.
*   **(i) Trigger Key:** A quick-measure key on the side of the instrument. Can be programmed to `DIST` (measure only) or `ALL` (measure and record). *Note: On the TS02, it has one function; on TS06/09 it has two (p. 21).*
*   **(k) Keyboard & (q) Display:** Your primary interface.
*   **(p) Footscrews:** Three screws on the tribrach for fine-leveling the instrument.

##### **1.2. The Keyboard and Softkeys (p. 19-21, 24)**
The instrument is controlled by a combination of fixed keys and context-sensitive softkeys.
*   **Function Keys `[F1]` - `[F4]`:** These are **softkeys**. Their function changes depending on what is displayed on the screen directly above them.
*   **Navigation Key:** The circular key with arrows for moving through menus and fields.
*   **`[ENTER]`:** Confirms a selection or entry.
*   **`[ESC]`:** Exits a menu or cancels an action without saving.
*   **`[FNC]` (Function Key):** A quick-access menu for common tools like `Level/Plummet`, `Target Offset`, and toggling the laser pointer (p. 72).
*   **Page Key (icon with sheets of paper):** Toggles between different pages of information or softkey options.

##### **1.3. Understanding the Screen & Status Icons (p. 21-23)**
The status icons at the top of the screen give critical information at a glance.
*   **Battery Icon:** Shows remaining battery life.
*   **Compensator Icons:** A tilted rectangle with a line means the compensator is **ON** (correcting for instrument tilt). A crossed-out icon means it is **OFF**.
*   **`P` (Prism Mode):** You are measuring to a standard prism.
*   **`NP` (Non-Prism Mode):** You are in reflectorless mode, measuring directly to a surface.
*   **`I` or `II`:** Indicates the telescope's face (Face I or Face II). Essential for checking accuracy.
*   **Prism Type Icons:** Different icons for Standard, Mini, 360°, and Reflector Tape prisms. **Crucially, you must select the correct one.**
*   **Angle Direction Arrow:** A circular arrow indicates that the horizontal angle is set to measure counter-clockwise (Left). The default is clockwise (Right).

---

#### **Part 2: The Core Workflow: Setup & Surveying**

This section follows the exact sequence you would in the field.

##### **2.1. Physical Instrument Setup (p. 29-34)**
**Goal:** Get the instrument perfectly level and centered over a ground point.
1.  **Tripod:** Place over the point, legs wide and stable, head plate roughly horizontal and at a comfortable viewing height. Press feet firmly into the ground.
2.  **Mount Instrument:** Secure the total station to the tripod head.
3.  **Power On & Laser Plummet:** Turn the instrument on. The `Level/Plummet` screen should appear. Use the laser dot to do your initial centering over the ground nail.
4.  **Rough Leveling:** Adjust the **tripod legs** to center the **circular bubble** (the physical bullseye).
5.  **Fine Leveling (Electronic Level):**
    *   The `Level/Plummet` screen shows a precise electronic level.
    *   Rotate the instrument so it is parallel to two footscrews. Turn these two screws in opposite directions to center the bubble on that axis.
    *   Rotate the instrument 90 degrees. Turn the third footscrew to center the bubble on this axis.
    *   Repeat until the instrument is perfectly level. On-screen checkmarks will confirm this (p. 33).
6.  **Final Centering:** Loosen the main screw and slide the instrument (without rotating) to place the laser dot exactly on the point. Re-tighten and re-check your level.

##### **2.2. Essential Pre-Survey Settings (p. 42-58)**
Before starting a job, ensure your instrument settings are correct. From the `MAIN MENU`, select `Setting`.
*   **General Settings (p. 42):**
    *   `Tilt Corr`: Set to **2-Axis** for the highest accuracy. This corrects for tilt in both the horizontal and vertical axes.
    *   `V-Setting`: Set to **Zenith** (0° is straight up) or **Horiz.** (0° is level), depending on your preference.
    *   `Angle Unit` & `Dist. Unit`: Set to your project's units (e.g., `° ' "`, `Meter` or `US-ft`).
    *   `Data Output`: For normal surveying, this should be **Int.Mem.** (Internal Memory).
*   **EDM Settings (p. 54):** This is CRITICAL for accurate distances.
    *   `EDM Mode`: Choose `Prism-Standard` for normal prism work or `NP-Std` for reflectorless shots.
    *   `Prism Type`: Select the exact type of prism you are using (e.g., `Round`, `Mini`, `Tape`).
    *   **Prism Constant:** The instrument displays both `Leica Const` and `Abs. Const` (Absolute Constant).
        *   **Leica Const:** A value specific to Leica prisms, relative to their standard of +34.4mm.
        *   **Abs. Const:** The industry-standard absolute offset (e.g., 0mm, -30mm). **For non-Leica prisms, you must set the `Prism Type` to `User1` or `User2` and enter the correct `Abs. Const` value here.**

##### **2.3. Starting a Job and Setting Station (p. 91-102)**
This is the heart of the setup, done through the `Surveying` application.
1.  From the `MAIN MENU`, select `Prog` -> `Surveying`.
2.  **`F1 Set Job`:** Create a `[NEW]` job or select an existing one. All your data will be saved here.
3.  **`F2 Set Station`:** Tell the instrument where it is.
    *   Enter the `StnID` (Station ID/Point Name).
    *   If the point is known, enter its coordinates using the `[ENH]` softkey.
    *   Measure and enter the `hi` (instrument height).
4.  **`F3 Set Orientation`:** Tell the instrument where it is looking (backsight).
    *   **Method 1: Manual Angle Setting (p. 98):** Use if you want to set the horizontal angle to a specific bearing (e.g., 0°00'00") by aiming at a target.
    *   **Method 2: Coordinates (p. 99):** **This is the standard method for a traverse.**
        *   Select `Coordinates`.
        *   Enter the `BS ID` (Backsight Point Name).
        *   Enter its known coordinates via `[ENH]`.
        *   Aim at the prism on the backsight point.
        *   Confirm the `hr` (height of reflector/prism).
        *   Press `[ALL]` to measure.
        *   The **ORIENTATION RESULT** screen shows you the quality of your setup. Standard deviation (`Std. Dev.`) should be very small.
        *   Press `[OK]` to accept.
5.  **`F4 Start`:** Once Job, Station, and Orientation are set (`*` appears next to each), press `F4` to begin measuring.

##### **2.4. Measuring Points (Surveying Application) (p. 104)**
*   Enter the `PtID` (Point ID) for your new point.
*   Enter a `Code` (e.g., "FENCE", "EOP") to describe the point.
*   Confirm the `hr` (prism height).
*   Aim at the prism on the new point.
*   Press **`[ALL]`** to measure the point and automatically record its coordinates to your job.
*   Press **`[DIST]`** to measure without recording.

---

#### **Part 3: Key Applications & Functions**

##### **3.1. Common Applications (p. 104-111)**
*   **Surveying (p. 104):** The main application for topographic surveys and data collection.
*   **Stakeout (p. 105):** Used to find and mark the location of a point with known coordinates. The screen displays the required directional changes (e.g., Left/Right, In/Out) to guide the prism holder to the correct spot.
*   **Free Station (p. 111):** Also called **Resection**. Allows you to set up the instrument at an **unknown** location and determine its coordinates by measuring to 2 or more known points. Extremely useful when you cannot occupy a known control point.

##### **3.2. Common FNC Functions (p. 72-73)**
Pressing `[FNC]` gives you quick access to tools:
*   **Level/Plummet:** Re-opens the leveling screen. Use this if you think the instrument has been bumped.
*   **Offset (p. 74):** Allows you to calculate the position of an inaccessible point by measuring to a prism held a known distance away from it (e.g., measuring the center of a tree by offsetting from a prism held on its face).
*   **Delete Last Record:** Deletes the last point or code you recorded. **This is not reversible.**
*   **Non-Prism/Prism Toggle:** Quickly switches between `P` and `NP` measurement modes.

---

#### **Part 4: Data Management**

##### **4.1. Data Storage and File Structure (p. 37, 299)**
*   All data is stored in **Jobs**.
*   The TS02 has internal memory. Models with the communication side cover can also use a USB memory stick.
*   On a USB stick, data is stored in a specific directory structure:
    *   `\JOBS\` for exported job files (.gsi, .dxf)
    *   `\CODES\` for code lists (.cls)
    *   `\SYSTEM\` for firmware, language files, etc.

##### **4.2. Exporting Data (p. 220-223)**
1.  Go to `MAIN MENU -> Transfer -> Export Data`.
2.  `To`: Select **USB-Stick** (if available) or **Interface** (for RS232 cable).
3.  `Data Type`: Choose **Measurements** or **Meas. & Fixpoints**.
4.  `Job`: Select the job you want to export.
5.  `Format`: Choose the file format (e.g., GSI, DXF, or a custom format).
6.  Press `[OK]` and follow prompts to save the file.

##### **4.3. Importing Data (p. 224-225)**
*   You can import job files (.gsi, .dxf), fixpoint lists, or code lists from a USB stick.
*   Go to `MAIN MENU -> Transfer -> Import Data`.
*   Select the file from the USB stick. The instrument automatically places it in the correct internal directory based on its extension.
