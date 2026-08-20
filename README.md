# Rise Youth Pass — Name QR Prototype

This version encodes the student's exact **First Name + Last Name** directly in the QR code.

Example:

`Dax Clarke`

Student experience:
1. Enter first name
2. Enter last name
3. Select High School or Middle School
4. Tap Create My Pass
5. The pass is saved on that device
6. Future opens go straight to the saved QR pass

If your existing Rise Youth controller already expects a student's name from the QR scanner, this version can plug into that flow without a database or token lookup.

Important: names are personally identifying information. This prototype stores the name locally on the student's device and also embeds it in the visible QR.
