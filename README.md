# Combinational-Lock-with-Alert-Mechanism
🔹 Digital Logic Design Project

📌 Goal
To build a secure lock using combinational and sequential logic with a warning system after multiple invalid password entries.

⚙️ Working
The 4-bit input is stored using D flip-flops.
A 4-bit comparator checks the input against the preset password.
If the password is correct, the green LED turns ON.
If the password is incorrect, a 1-bit comparator detects the wrong entry and sends a count pulse to the 3-bit counter.
The accumulated wrong attempts are compared with the limit (e.g., more than 3 wrong attempts) using a 3-bit comparator.
Once the wrong attempt count exceeds the threshold, the red LED turns ON as an alert.

🔧 Modules Used
D Flip-Flops, 4-bit Comparator, 1-bit Comparator, 3-bit Counter, 3-bit Comparator, Green LED, Red LED

⭐ Highlights
Multiple wrong attempts tracking, Alert after exceeding threshold, Pure logic circuit implementation without microcontroller

🧠 Skills Gained
Digital logic design, Counter and comparator interfacing, Sequential circuit integration, Team collaboration

📱 Applications:

• Electronic door and locker security systems

• Access control for labs and offices

• Academic demonstration of combinational and sequential logic

🚀 Future Improvements:

• Keypad-based password input

• Buzzer or alarm alert

• Temporary lockout after multiple wrong attempts
