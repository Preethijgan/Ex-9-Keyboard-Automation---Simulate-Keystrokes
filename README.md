### Name: Preethi J
### Registration Number: 212223220080

# Aim:

To develop a UiPath automation process that simulates keyboard operations such as typing text and pressing shortcut keys using Type Into and Send Hotkey activities.

# Procedure:

## Step 1 : Open UiPath Studio.

- Create a new process named KeyboardAutomation_Exercise9.

## Step 2: Launch the Target Application.

- Use the Use Application/Browser activity to open Notepad (or any text editor).
  * Path: C:\Windows\System32\notepad.exe

## Step 3: Simulate Typing Text.

- Drag a Type Into activity inside the Use Application/Browser container.
- Enter the text:
  * This is Keyboard Automation using UiPath.
- In the Properties panel, enable SimulateType = True (for background typing).

## Step 4: Simulate Shortcut Keys.

- Add a Send Hotkey activity to perform key combinations such as:
  * Ctrl + S → to save the file.

## Step 5: Add Delay (Optional).

- Insert Delay activities between actions to ensure the system has enough time to respond.

## Step 6: Save and Run the Workflow.

Execute the process and observe the simulated keystrokes in Notepad.
<img width="1919" height="1075" alt="Screenshot 2025-11-09 132306" src="https://github.com/user-attachments/assets/c6d362ca-729f-4dab-a5d4-707c311103f9" />
<img width="1919" height="1079" alt="Screenshot 2025-11-09 134147" src="https://github.com/user-attachments/assets/ab759557-dac3-419b-9c3a-2de549721cbe" />
<img width="1919" height="1079" alt="Screenshot 2025-11-09 134153" src="https://github.com/user-attachments/assets/3d77bf5a-12bc-4ffe-b3c9-571fed74a008" />


## Output:

The text written into notedpad and saved

<img width="1919" height="1079" alt="Screenshot 2025-11-09 133933" src="https://github.com/user-attachments/assets/8912ba20-5d0f-4f57-b6a9-7c06e8ca3915" />
<img width="1114" height="1079" alt="Screenshot 2025-11-09 133945" src="https://github.com/user-attachments/assets/0e9ef99e-6ee0-417d-bf1a-cc50f7f664d4" />



# Result:

- The UiPath robot successfully simulates keyboard actions:
  * Opens Notepad.
  * Types the given text automatically.
  * Executes keyboard shortcuts like Ctrl + S (save)
Hence, keyboard automation using simulated keystrokes is successfully implemented.

