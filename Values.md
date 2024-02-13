<div class="markdown prose w-full break-words dark:prose-invert dark">
    <h1>AG-Grid Values Aggregation Documentation</h1>
    <h2>Introduction to Values Aggregation</h2>
    <p>
        The 'Values' feature in AG-Grid is used in conjunction with row grouping to perform data aggregation. It computes summary statistics for a column, like the sum, average, minimum, or maximum, which helps in analyzing numerical data
        across different groups.
    </p>
    <h2>How to Use Values Aggregation</h2>
    <h3>Basic Aggregation</h3>
    <ol>
        <li><strong>Drag and Drop</strong>: Drag a column header into the 'Values' section in the side panel to start aggregating data in that column.</li>
        <li><strong>Select Aggregation Function</strong>: Once a column is in the 'Values' area, choose the type of aggregation function from the provided options (sum, average, min, max, etc.).</li>
        <li><strong>Viewing Aggregated Data</strong>: The aggregated data will automatically display in the group rows or footers, depending on your configuration.</li>
    </ol>
    <h3>Aggregation with Grouping</h3>
    <ol>
        <li><strong>Combine with Row Groups</strong>: Drag columns to the 'Row Groups' area first, then use the 'Values' feature to aggregate within these groups.</li>
        <li><strong>Hierarchical Aggregation</strong>: Aggregations will apply at each grouping level, providing summaries at each level of the hierarchy.</li>
    </ol>
    <h2>Features of Values Aggregation</h2>
    <h3>Multiple Aggregations</h3>
    <p>You can perform multiple aggregations by adding more than one column to the 'Values' area.</p>
    <h3>Custom Aggregations</h3>
    <p>AG-Grid enables the creation of custom aggregation functions if the built-in functions do not meet your specific requirements.</p>
    <h3>Aggregation Functions</h3>
    <p>The standard aggregation functions provided by AG-Grid include:</p>
    <ul>
        <li><strong>Sum</strong>: Total value of the column for the group.</li>
        <li><strong>Average</strong>: Mean value of the column for the group.</li>
        <li><strong>Min</strong>: Minimum value in the column for the group.</li>
        <li><strong>Max</strong>: Maximum value in the column for the group.</li>
        <li><strong>Count</strong>: Number of non-null/undefined entries in the column for the group.</li>
    </ul>
    <h2>Best Practices</h2>
    <ul>
        <li><strong>Relevant Data</strong>: Only aggregate columns where it makes sense to summarize data numerically.</li>
        <li><strong>Clear Labels</strong>: Ensure that the aggregated data is clearly labeled so that users understand what the numbers represent.</li>
        <li><strong>Use with Grouping</strong>: Aggregation is most powerful when used in combination with row grouping to provide insights into subsets of data.</li>
    </ul>
    <h2>Conclusion</h2>
    <p>
        The 'Values' feature in AG-Grid is essential for summarizing data, enabling users to quickly gain insights into their data set. By utilizing the intuitive drag-and-drop interface, data can be grouped and aggregated to support
        efficient data analysis workflows.
    </p>
</div>
