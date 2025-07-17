<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Credit Card Transaction Analysis Dashboard</title>
    <style>
        body { font-family: Arial, sans-serif; line-height: 1.6; margin: 20px; }
        h1 { color: #2c3e50; }
        h2 { color: #34495e; border-bottom: 1px solid #ccc; padding-bottom: 5px; margin-top: 20px; }
        ul { list-style-type: disc; margin-left: 20px; }
        ul ul { list-style-type: circle; margin-left: 20px; }
        strong { color: #2980b9; }
    </style>
</head>
<body>

    <h1>Credit Card Transaction Analysis Dashboard</h1>

    <p>This repository contains an interactive Power BI dashboard for <strong>Credit Card Transaction Analysis</strong>.</p>

    <h2>Dashboard Features:</h2>
    <ul>
        <li><strong>Overview of Transactions:</strong> Provides a high-level summary of credit card revenue, total interest, total amount, and transaction count.</li>
        <li><strong>Quarterly Performance:</strong> Visualizes credit card transactions across different quarters, allowing for easy identification of trends and seasonal patterns.</li>
        <li><strong>Demographic Segmentation:</strong> Analyze transactions by various customer demographics including:
            <ul>
                <li><strong>Education Level:</strong> Understand spending habits across different educational backgrounds.</li>
                <li><strong>Customer Job:</strong> Identify transaction patterns based on customer's profession.</li>
                <li><strong>Marital Status:</strong> Explore how marital status influences credit card usage.</li>
                <li><strong>Age and Gender:</strong> Segment transactions by age groups and gender to uncover specific consumer behaviors.</li>
                <li><strong>Income Group:</strong> Observe spending across different income levels.</li>
                <li><strong>State and City:</strong> Drill down into geographical transaction data.</li>
            </ul>
        </li>
        <li><strong>Card Type Analysis:</strong> Break down transactions by credit card type (e.g., Silver, Gold, Platinum, Medium, High, M, Low, In).</li>
        <li><strong>Transaction Details:</strong> Examine transactions based on:
            <ul>
                <li><strong>Expense Type:</strong> Categorize spending by different expense types (e.g., Food, Travel, Bills, Entertainment, Fuel, Grocery, Business, Other).</li>
                <li><strong>Chip Usage:</strong> Differentiate between transactions made with and without a chip.</li>
            </ul>
        </li>
        <li><strong>Interactive Filters:</strong> Dynamic filters allow users to slice and dice the data by:
            <ul>
                <li>Card type (Silver, Gold, Platinum, Medium, High, M, Low, In)</li>
                <li>Quarter (Q1, Q2, Q3, Q4)</li>
                <li>Start/End Date (Calendar selection)</li>
                <li>Gender</li>
                <li>Customer Job</li>
                <li>Education Level</li>
                <li>Marital Status</li>
                <li>Age Group</li>
                <li>State</li>
                <li>Dependent Count</li>
            </ul>
        </li>
    </ul>

    <h2>Purpose:</h2>
    <p>This dashboard aims to provide comprehensive insights into credit card transaction data, enabling users to:</p>
    <ul>
        <li>Identify key revenue drivers and areas for improvement.</li>
        <li>Understand customer spending behavior and preferences.</li>
        <li>Segment customers based on various attributes for targeted marketing.</li>
        <li>Track performance over time and across different categories.</li>
        <li>Make data-driven decisions related to credit card products and services.</li>
    </ul>

    <h2>Technologies Used:</h2>
    <ul>
        <li><strong>Power BI Desktop:</strong> For data modeling, visualization, and dashboard creation.</li>
        <li><strong>PostgreSQL:</strong> As the data source for credit card transaction data.</li>
    </ul>

    <h2>How to Use:</h2>
    <ol>
        <li>Ensure you have PostgreSQL installed and the necessary credit card transaction data loaded into your database.</li>
        <li>Clone this repository to your local machine.</li>
        <li>Open the <code>.pbix</code> file (Power BI Desktop file) in Power BI Desktop.</li>
        <li>You may need to refresh the data connection in Power BI Desktop to point to your PostgreSQL database.</li>
        <li>Interact with the various filters and visualizations to explore the data.</li>
    </ol>

    <h2>Contributions:</h2>
    <p>Contributions are welcome! Please feel free to open issues or submit pull requests.</p>

</body>
</html>
