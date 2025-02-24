# SimulatingHospitalWaitTimes

This project employed Simio to simulate hospital wait times as patients moved through treatment wards and rehabilitation before discharge. The simulation helped identify system bottlenecks that were subsequently adjusted to minimize delays. This proved to be an excellent opportunity to familiarize myself with Simio.

Using provided data, Python was used to fit distributions to patient arrival times as well as treatment and rehabilitation durations, which then served as inputs for our Simio model. I was fortunate to lead the development of the model, deepening my understanding of simulation techniques and system optimization.

The project's base model was designed as shown below. The warmup time was selected based on when the number of patients in the system stabilized. Next, the number of replications was determined by observing improvements in the confidence interval. With the initial setup organized, we analyzed performance measures and identified 21 scenarios that could reduce wait times before finalizing a recommendation on how best to handle the patient flow.

![Model](https://github.com/user-attachments/assets/fb8a7e77-bf1d-4de7-b46f-ecb96500c313)

