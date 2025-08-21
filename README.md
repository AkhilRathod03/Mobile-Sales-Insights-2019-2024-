
# Mobile Sales Insights (2019–2024)

## Objective
This project provides a comprehensive Power BI dashboard to analyze mobile phone sales trends, market share, and regional performance for major brands from 2019 to 2024.

## Files Included
- `sales_data.csv`: The dataset containing 5 years of mobile sales data.
- `generate_data.py`: The Python script used to generate the dataset.

---

## How to Build the Dashboard in Power BI (5-Minute Setup)

### 1. Open Power BI and Load the Data
1.  Open Power BI Desktop.
2.  On the Home tab, click **Get Data** and select **Text/CSV**.
3.  Navigate to the `MobileSales_Dashboard` folder on your desktop and select `sales_data.csv`.
4.  Click **Load** in the preview window. Power BI will automatically detect the headers and data types.

### 2. Create the Dashboard Layout

#### **Card KPIs (Key Metrics)**
1.  Select the **Card** visual from the Visualizations pane.
2.  Drag **Units Sold** to the `Fields` well. Click the down arrow and select **Sum**.
3.  Create a second card and drag **Revenue** to the `Fields` well. Ensure it's summed.
4.  Create a third card. Drag **Customer Rating** to the `Fields` well and select **Average** from the dropdown.

#### **Line Chart: Year-wise Sales Trend**
1.  Select the **Line chart** visual.
2.  Drag **Year** to the `X-axis`.
3.  Drag **Units Sold** to the `Y-axis`.

#### **Pie Chart: Market Share by Brand**
1.  Select the **Pie chart** visual.
2.  Drag **Brand** to the `Legend`.
3.  Drag **Revenue** to the `Values`.

#### **Bar Chart: Top-Selling Models by Revenue**
1.  Select the **Stacked bar chart** visual.
2.  Drag **Model** to the `Y-axis`.
3.  Drag **Revenue** to the `X-axis`.

#### **Map: Regional Sales Distribution**
1.  Select the **Map** visual.
2.  Drag **Region** to the `Location` field.
3.  Drag **Revenue** to the `Bubble size` field to make high-sales regions appear as larger bubbles.

### 3. Add Interactivity with Slicers
1.  Select the **Slicer** visual from the Visualizations pane.
2.  Drag **Year** to the `Field` well. In the slicer's header, choose **Dropdown** for a cleaner look.
3.  Create a second slicer for **Brand**.
4.  Create a third slicer for **Region**.

*Now, clicking on any brand, year, or region will filter all the other charts on the dashboard automatically.*

### 4. Apply Theme and Final Touches
1.  **Theme**: Go to the **View** tab. Click the dropdown in the **Themes** gallery and select a theme that uses a blue, white, and grey palette (e.g., the default theme often works well, or you can browse for one).
2.  **Title**: Go to the **Insert** tab and click **Text Box**. Type **"Mobile Sales Insights (2019–2024)"**. Drag it to the top of the dashboard and format the font size and color.
3.  **Tooltips**: Hover over any chart (like the bar chart or map) to see the default tooltips showing model, revenue, and other details.
4.  **Arrange**: Drag and resize all the visuals to create a clean, organized layout.

---

Your professional, interactive dashboard is now ready. You can publish it to the Power BI service or explore the data further.
