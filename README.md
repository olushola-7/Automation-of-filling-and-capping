# Automation-of-filling-and-capping
Filling and capping is a common process in the packaging industry. This project explains the automation of bottle filling and capping using a Mitsubishi PLC.  The system consist of a conveyor that moves empty bottle to a filling head (solenoid valve) which opens to supply water to the bottle for a predefined time after which the  conveyor moves the filled bottle to a capping machine which operates to perform the capping operation after which it is moved down the system as a finished product.

Mitsubishi PLC was used in this project. The program/source code is written using GX Developer FX software (A software for writing, editing and downloading/uploading program to/from Mitsubishi FX series PLC). You will need to install GX Developer FX to be able to open the project after you have unzipped it. You will see the source code.  

BRIEF EXPLANATION OF THE PROGRAM/SOURCE CODE
When the start button (X000) is pressed, the conveyor (Y000) starts to operate and moves empty bottle placed on it towards the direction of sensor 1 (X002) which becomes active on detecting the presence of the bottle. The conveyor stops and the valve operate for 2 seconds to supply water to the bottle. The conveyor starts again and move the filled bottle towards the direction of sensor 2 (X003) placed at the capping machine position. The sensor becomes active on detecting the filled bottle. The conveyor stops and the capping machine operates for 2 seconds to complete the capping process.

The source code is written using ladder logic programming language. View the JPG files in this repository
for the io assignment, flow chart etc.




For further explanation or clarification on this project, send a mail to: akandeolushola14@gmail.com or sholagentle@yahoo.com. You can also send a WhatsApp message to: +2348029266470.
