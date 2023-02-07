# energy-consumption-prediction
This is a small project on <a href="https://archive.ics.uci.edu/ml/datasets/Steel+Industry+Energy+Consumption+Dataset">Steel Industry Energy Consumption Dataset.</a>

A Jupyter Notebook in this project has the following scope:
1) performs EDA on the dataset
2) constructs ML pipeline to automatically check the most common regression algorithms in order to choose the one with the best performance
3) includes the usage of the most common data science techniques such as K-Fold cross-validation, scaling, encoding, gradient boosting etc.
4) visualizes the results with Altair and Seaborn

<h2>Introduction to the dataset from UCI Machine Learning Repository</h2>
<p dir="auto">The information gathered is from the DAEWOO Steel Co. Ltd in Gwangyang, South Korea. It produces several types of coils, steel plates, and iron plates. The information on electricity consumption is held in a cloud-based system. The information on energy consumption of the industry is stored on the website of the Korea Electric Power Corporation (pccs.kepco.go.kr), and the perspectives on daily, monthly, and annual data are calculated and shown.</p>

<h2>Attribute Information</h2>
<p dir="auto">
    <ul dir="auto">
        <li>Data Variables Type Measurement</li>
        <li>Industry Energy Consumption Continuous kWh</li>
        <li>Lagging Current reactive power Continuous kVarh</li>
        <li>Leading Current reactive power Continuous kVarh</li>
        <li>tCO2(CO2) Continuous ppm</li>
        <li>Lagging Current power factor Continuous %</li>
        <li>Leading Current Power factor Continuous %</li>
        <li>Number of Seconds from midnight Continuous S</li>
        <li>Week status Categorical (Weekend (0) or a Weekday(1))</li>
        <li>Day of week Categorical Sunday, Monday â€¦. Saturday</li>
        <li>Load Type Categorical Light Load, Medium Load, Maximum Load </li>
    </ul>   
</p>
