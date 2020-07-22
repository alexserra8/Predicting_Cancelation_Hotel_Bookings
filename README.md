# Predicting_Cancelation_Hotel_Bookings

This is a **Data Science project** where we try to predict if an hotel booking will be canceled or not by the client. **Is a clasifications supevised machine learning problem.** We have several features like: number of adults of he booking, lead time, country of origin of the client,...

As we can see in this image, there are a lot of booking cancelations in the last 10 days. This cancelations are a big problema for the hotel, because they won't find any client that will use this room. This bookings are criticial and a direct lose of incomes. The idea of this project is try to predics this cancelations to avoid this losses. A mean of 250.000€ are not finaly obtained due to this problematic.

![image](https://user-images.githubusercontent.com/68638309/88177079-917f0400-cc28-11ea-993a-29c3af5dbff6.png)


We have used the data set from Kaggle: https://www.kaggle.com/jessemostipak/hotel-booking-demand

The data have to hotels data. In this case, we only used the "City Hotel".


The repository is structered like this:

* **1_CleaningData:** Where the data is cleande (we removed instances and features).

* **2_OverviewData:** we obtained information and graphs about our data in order to understand it in a more depth way.

* **3_Generical Machine Learning Models:** we made an inicial approaching of the beahaviour of the main machine learning algorithms.

* **4_Improving Machine Learning Models:** we selected the best features (in order to reduce the computing time) and the best hyperparameters for the next models:

    * Decision Tree
    * Bagging 
    * Random Forest
    * AdaBoost (Boosting)
 
 * **5_Final Comparison**: a final comparision between the final models obtained is made.




