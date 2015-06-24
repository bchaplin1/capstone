# capstone
## capstone project
### Predict if an insurance customer will use the web or call on the phone

Examine the characteristics of a customer who calls vs. using the web for insurance self-service.  Examine for correlations and incorporate into a predictive model.

Some possible variables or variable categories include:

* Customer demographic characteristics like zip code, education.  Some of these may be available via public APIs.
* Which customer service region is the customer serviced from?  Some are more agressive in training the phone callers in how to use self-service web features.
* Policy characteristics.  Would a simpler policy invite more web self-service?
* Action desired.  Some are more complicated than others and may invite more phone calls.

Certain actions can only be done via phone, such as cancelling the last policy on a vehicle.
The prediction will be either a binary classification using a logistic regression or the option is left open for other types of regression such as call length based on action desired or policy characteristics.

