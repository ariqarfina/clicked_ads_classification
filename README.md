# Predict Clicked Ads Visitor Classification by using Machine Learning

“A company in Indonesia wants to know the effectiveness of an advertisement that they run. this is important for the company because it allows them to determine how successful the advertisements are in attracting Visitors to see advertisements. It can help companies determine marketing targets by processing historical advertisement data and finding insights and patterns that occur. The focus of this case is to create machine learning classification models that function to determine the right target Visitors.”

![Dataset Info](https://user-images.githubusercontent.com/101324931/182505067-c9f9736a-126a-4b40-abf0-6ffc3cf8d219.jpg)

# Segmentation

Visitors who have the potential to click on ads are:
- Visitors who have `Daily Time Spent on Site` <= 63.99
- Visitor with `Daily Time Spent on Site` > 63.99, with `Area Income` > Rp 307,499,920, and `Daily Internet Usage` <= 163.0
- Visitor with `Daily Time Spent on Site` > 63.99; `Income Area` <= IDR 307,499,920

Visitors who have no potential to click on ads are:
- Visitor with `Daily Time Spent on Site` > 63.99, with `Area Income` > Rp 307,499,920, and `Daily Internet Usage` > 163.0

# Modelling

![Decision Tree ](https://user-images.githubusercontent.com/101324931/182505186-fbbd2e84-348f-496a-9b4b-13dd6172ab31.jpg)

Evaluation for this model:
- Recall (Train|Test) : 0,97

![Business Impact](https://user-images.githubusercontent.com/101324931/182505395-a04bab1e-3645-4d8c-9a15-565ad1a7f399.jpg)

For more details, you can see it on Notebook.

Thankyou
