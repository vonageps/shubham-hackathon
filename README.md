# shubham-hackathon
This solution is for the General Hospital where patients can call and tell the symptoms they are experiencing.

The symptom is then analysed by the AI and if it can be handled by a pharmacist, they are asked to whether get the pharmacist details sent by SMS or get a doctor's appointment.

If the symptom cannot be handled by a pharmacist, the user will be asked to book a doctor's appointment directly and communicated the booking details via SMS.

In case the call bot doesnt understand the patient's symptom it will repeat the options using IVR with numbers as input.

If IVR can't assist the patient, then the user is redirected to the agent.

If the agents are busy, user is given option to either get arranged a callback or stay on the line.

In case the user agrees to the callback option, the user and agent both receives the details via SMS.

If user stays on the line then the line will be connected to the agent.

*Note: If the patient calls for an emergency or life threatening condition, the call will be redirected to the agent without any call flow.
