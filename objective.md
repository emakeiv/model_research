**Objective:**  
Using Python and the historical data provided, we would like you to explore,
build a simple forecasting model (e.g.: forecasting `Wind Power Density` for the
next hour), and integrate the model into an app using an external API to source
fresh data.

**Steps:**

1.  **Data Exploration:**

    -   Start by exploring the historical data available.

    -   Share your insights and observations from the data.

2.  **Modeling:**

    -   Based on your exploration, develop simple forecasting model.

    -   You can use any modeling technique or library of your choice.

    -   Remember, the goal isn't to build the most sophisticated model but to
        have a working prototype.

3.  **App Integration:**

    -   Build a minimalistic app (or use a framework you're comfortable with)
        that will utilize the models you've created.

    -   Use `https://thingspeak.com/channels/1785844` API to pull in fresh data.
        Documentation can be found here:
        `https://www.mathworks.com/help/thingspeak/read-data-from-channel.html`.

    -   Ensure the app displays the results of the forecasting and fresh data in
        a user-friendly manner.

4.  **Comments:**

    -   Ensure you add comments, especially in areas where you'd do things
        differently with more time or resources.

**Note:** We understand that time is limited and don't expect you to spend more
than 2 hours on this exercice. The objective here is to build a minimum viable
product that can serve as a discussion point during the interview. We're more
interested in understanding your thought process, approach, and problem-solving
skills rather than the perfection of the solution. Please ensure you highlight
areas you'd improve upon or address differently if given more time.

**Note:** There are 4 files containing historical data in parquet format. Fields
mapping: { "field1": "Wind Speed", "field2": "Wind Power Density (Watts/m\^2)",
"field4": "Air Density (kg/m\^3)", "field5": "Temperature (F)" }
