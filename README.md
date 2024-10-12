Objective: Predict the food delivery time by analyzing various factors such as delivery distance, age of the delivery person, and customer ratings.

Distance Calculation:

Applied the Haversine formula to calculate the distance between the restaurant and the delivery location using the latitude and longitude coordinates.
Data Exploration:

Visualized key features like the relationship between delivery distance and time taken, identifying trends and patterns that would influence the model.
Model Training:

Used an LSTM (Long Short-Term Memory) neural network to model sequential data and predict delivery time.
The model was trained on features such as:
Delivery person's age
Delivery distance (calculated using the Haversine formula)
Customer rating for the order
Outcome: Developed a robust system to predict delivery times based on these inputs, leveraging the LSTM model's ability to capture long-term dependencies in the data.
