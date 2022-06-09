# Appointment-Booking

Nair Shruthi Viju - 16030721006
Rai Shrishti Sanjay - 16030721007


In this smart contract , appointment details of the patient will be stored in the blockchain.
Each patient will be assigned to a doctor through a mapping concept and accordingly that particular doctor will be able to consult the patient.
The functions included in the smart contract are as follows
setPatientData : To save the details of the patient who wants to book a particular doctor’s  appointment. The details saved are name , appointment time, mobile number, health issue and doctor's name.
setDoctor : To set the doctor’s address.
bookAppoinment: To book a patient’s appointment based on the patient's hash address and one of the appointment details like time of the appointment. If wrong time is provided for the corresponding patient’s hash address which was not mentioned in the setPatientData function , then the bookAppointment function will show an error.

The mapping concepts used are :

Patient mapping and doctor mapping
So if the doctor’s address is the same as the address stored in the function setDoctor then the mapping function will be correct.
If we provide a different address of the patient in the book appointment function , then it will provide error. 
If we provide the correct patient address (the address stored in the blockchain) then the book appointment function will successfully book the corresponding doctor’s  appointment for that patient.



