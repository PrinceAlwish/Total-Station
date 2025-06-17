Of course. This is an excellent request, and by combining the general principles of surveying with the specific details from the Leica FlexLine TS02 manual you provided, we can create a perfect step-by-step guide for your task.

You want to perform a traverse survey starting from a known point (CM9), orienting to another known point (CM10), and then measuring a series of new, unknown points.

First, a crucial point from the manual: The Leica TS02 model **does not** include the automated "TraversePRO" application (see page 91/197 of the manual). This is not a problem! It simply means we will perform the traverse using the standard **Surveying** application, which is the classic and fundamental way to conduct a traverse.

Here is your detailed guide.

---

### **Traverse Survey with a Leica TS02: CM9 to CM10**

#### **Objective:**
To set up the total station on a known control point (CM9), orient it by backsighting another known control point (CM10), and then measure a sequence of new traverse points (TP1, TP2, etc.).

#### **What You Will Need:**
*   Leica TS02 Total Station (with charged battery)
*   Tripod
*   Prism and Prism Pole
*   The coordinates (Northing, Easting, Elevation) for CM9 and CM10.
*   Survey nails/markers for your new traverse points (TP1, TP2...).

---

### **Phase 1: Physical Setup over CM9**

This phase is about physically getting the instrument perfectly centered and leveled over your starting point, CM9. The Leica manual covers this excellently on pages 29-34.

1.  **Set Up the Tripod:** Place the tripod over the ground marker for **CM9**. Extend the legs to a comfortable height (chest level) and press the feet firmly into the ground for stability.
2.  **Mount the Instrument:** Securely attach the TS02 to the tripod.
3.  **Power On and Level/Plummet:**
    *   Press the **On/Off key** (p. 16, item h).
    *   The **Level/Plummet** screen will likely appear automatically (p. 31). If it doesn't, press the `[FNC]` key and select **Level/Plummet**.
    *   Use the **laser plummet** to center the instrument over the CM9 nail. Loosen the main screw underneath, slide the instrument until the laser dot is on the point, and re-tighten.
4.  **Level the Instrument:**
    *   **Rough Leveling:** Adjust the tripod legs to get the circular bubble (p. 31, item 7) mostly centered.
    *   **Fine Leveling:** Use the electronic level on the screen. Follow the on-screen arrows and turn the three black **footscrews** (p. 17, item p) until the checkmarks appear, indicating the instrument is perfectly level (p. 32-33).
5.  **Final Check:** Look at the laser plummet one last time to ensure it is still perfectly on the nail. Adjust slightly if needed and re-check the level.

**You are now physically set up on CM9.**

---

### **Phase 2: On-Instrument Setup (Job, Station & Orientation)**

Now you will tell the TS02 where it is (Station CM9) and which way it is facing (Orientation to CM10).

1.  **Access the Programs Menu:**
    *   After leveling, you will be at the **Main Menu** (p. 38).
    *   Select **Prog** (Programs). You can either press the number `2` on the keypad or use the navigation keys to highlight it and press `[ENTER]`.

2.  **Start the "Surveying" Application:**
    *   From the `PROGRAMS` menu, select **Surveying** (p. 104). This will take you to the application's pre-settings screen.

3.  **Step 1: Set the Job (p. 94):**
    *   The `SURVEYING` screen will show `[ F1 ] Set Job`. Press `[F1]`.
    *   You can now select an existing job or create a new one. It's best practice to create a new job for your traverse.
    *   Press the `[ NEW ]` softkey.
    *   Give your job a name (e.g., `TRAV_20231027`) and press `[ OK ]`.
    *   Press `[ OK ]` again to confirm and return to the `SURVEYING` screen. You will see a `[*]` next to "Set Job", indicating it is complete.

4.  **Step 2: Set the Station (p. 95-96):**
    *   Now press `[ F2 ] Set Station`.
    *   The instrument needs to know the coordinates of your setup point, CM9.
    *   **StnID:** Enter `CM9`.
    *   Since CM9 is a new point in this job, you need to enter its coordinates. Press the `[ ENH ]` softkey to enter Northing (Easting in the manual), Easting (Northing), and Height values. *Note: Leica often uses E, N, H order. Be sure you enter your values in the correct fields.*
    *   Press `[ OK ]` to accept the coordinates.
    *   **hi:** Measure the instrument height (from the top of the CM9 nail to the mark on the side of the TS02) and enter it here. This is critical for correct elevations.
    *   Press `[ OK ]`. You will see a `[*]` next to "Set Station".

5.  **Step 3: Set the Orientation (p. 97-101):**
    *   This is the most important step. You will tell the instrument where CM10 is.
    *   Press `[ F3 ] Set Orientation`.
    *   You have coordinates, so you must select the **Coordinates** method.
    *   The screen will ask for the **BS ID** (Backsight ID). Enter `CM10`.
    *   Since CM10 is also new to this job, you will again need to press `[ ENH ]` and enter its known Northing, Easting, and Elevation.
    *   Press `[ OK ]`.
    *   Now the `Sight target point!` screen appears. Have your partner hold the prism pole (with the prism on it) perfectly level on top of the **CM10** survey marker.
    *   Enter the **hr** (height of reflector/prism). Make sure this matches the height set on the prism pole.
    *   Carefully aim the telescope crosshairs at the center of the prism on CM10.
    *   Press the `[ ALL ]` softkey. The instrument will measure the distance and angles to CM10.
    *   The instrument will now display the **ORIENTATION RESULT** screen (p. 101). This screen is your quality check. It shows you the difference between the calculated position and your measured position. The **Std. Dev.** (Standard Deviation) values should be very small (a few millimeters or less). If they are large, your setup or coordinates are incorrect.
    *   If the results are good, press `[ OK ]` to set the orientation.

**Your TS02 is now set up on CM9, oriented to CM10, and ready to survey.**

---

### **Phase 3: Measuring the Traverse**

You will now start the classic traverse loop: measure a foresight, move the instrument, and backsight your previous position.

1.  **Start Surveying:**
    *   You are back at the `SURVEYING` pre-settings screen. All three items should have a `[*]`.
    *   Press `[ F4 ] Start`. This takes you to the main `SURVEYING 1/3` screen (p. 104).

2.  **Measure Your First Foresight (TP1):**
    *   Have your partner move the prism to the location of your first new point, **TP1**.
    *   **PtID:** Enter `TP1`.
    *   **Code:** Enter a description, for example, `TRAVPT` or `TP`. This is vital for identifying points later.
    *   **hr:** Confirm the prism height is correct.
    *   Aim the telescope at the center of the prism on TP1.
    *   Press `[ ALL ]`. The instrument will measure and store the coordinates for TP1. The `PtID` will automatically increment to TP2.

3.  **Move the Instrument to TP1:**
    *   Carefully pack up the instrument and tripod from CM9.
    *   Move to the location of TP1 and perform the **full physical setup procedure** from Phase 1, ensuring the instrument is perfectly centered and leveled over the TP1 marker.

4.  **Set Up on the New Station (TP1):**
    *   Once physically set up, you need to tell the instrument its new position and orientation.
    *   Go to the `SURVEYING 1/3` screen. Press the down arrow key to get to the softkeys `[STATION]` and `[Hz=0]`.
    *   Press `[ STATION ]`. This re-opens the `Set Station` routine.
    *   **StnID:** Enter `TP1`. Since you just measured this point, its coordinates are stored. Press `[ FIND ]` or simply `[ ENTER ]` and the instrument will load the coordinates for TP1.
    *   **hi:** Measure and enter the new instrument height at TP1.
    *   **Set Orientation:** Now, your backsight is your *previous station*, **CM9**. Enter `CM9` as the **BS ID**. The coordinates for CM9 are already in the job.
    *   Have your partner move the prism back to **CM9**.
    *   Enter the correct **hr**.
    *   Aim at the prism on CM9, press `[ ALL ]`, check the orientation results, and press `[ OK ]`.

5.  **Continue the Traverse (Measure TP2, TP3...):**
    *   You are now oriented at TP1 and looking back at CM9.
    *   Rotate the instrument and aim at your next new point, **TP2**.
    *   Enter `TP2` for the `PtID` and press `[ ALL ]`.
    *   To measure TP3, you would move the instrument to TP2, set the station to TP2, and backsight TP1.

This loop—**Measure Foresight -> Move -> Set Station -> Backsight Previous Station**—is the essence of a traverse.

---

### **Phase 4: Closing the Traverse and Data Download**

*   **Closing:** For a traverse to be valid, you must "close" it, meaning your last measurement should be of a known point. This could be your starting point (CM9) or another known control point. This allows software to calculate the misclosure error and adjust your traverse for accuracy.
*   **Data Download (p. 220):** When you are finished, you can export your data. Go to `Main Menu -> Transfer -> Export Data`. You can export to a USB stick or via the RS232 cable to a computer running Leica FlexOffice or other survey software.