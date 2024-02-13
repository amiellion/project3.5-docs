<div class="markdown prose w-full break-words dark:prose-invert dark">
    <h1>AG-Grid Row Grouping Documentation</h1>
    <h2>Introduction to Row Grouping</h2>
    <p>
        Row grouping in AG-Grid allows users to view and analyze grid data in a hierarchical structure. This powerful feature enables the categorization of data by one or more columns and is essential for summarizing or examining subsets of
        data within the grid.
    </p>
    <h2>How to Use Row Grouping</h2>
    <h3>Basic Grouping</h3>
    <ol>
        <li><strong>Drag and Drop</strong>: Simply drag a column header and drop it into the 'Row Groups' area in the side panel to create a group by that column.</li>
        <li><strong>Expanding/Collapsing</strong>: Click on the group row to expand or collapse the view to see the rows under each group.</li>
        <li><strong>Removing Groups</strong>: To remove grouping, drag the column out of the 'Row Groups' area or click the 'x' on the column tag in the 'Row Groups' area.</li>
    </ol>
    <h3>Hierarchical Grouping</h3>
    <ol>
        <li><strong>Order Matters</strong>: The order in which you place columns in the 'Row Groups' area defines the grouping hierarchy.</li>
        <li><strong>Nested Grouping</strong>: Placing one column below another creates a nested group. The topmost column creates the primary group, and each column below it creates a subgroup within the group above.</li>
        <li><strong>Expand/Collapse at Levels</strong>: You can expand or collapse groups at any level to view the data you're interested in.</li>
    </ol>
    <h2>Grouping Features</h2>
    <h3>Multi-Level Grouping</h3>
    <p>You can group by multiple columns to create a multi-level hierarchy. For instance, grouping by 'Country' first and then by 'City' will show cities grouped within each country.</p>
    <h3>Aggregation</h3>
    <p>When using row grouping, you can also aggregate the data within each group. By dragging a column into the 'Values' area, you can choose an aggregation function (like sum, average, etc.) to apply to that column for each group.</p>
    <h3>Custom Grouping</h3>
    <p>AG-Grid allows customization of the grouping functionality:</p>
    <ul>
        <li><strong>Group Keys</strong>: Customize the keys used for grouping.</li>
        <li><strong>Group Footers</strong>: Add footers to display summary information for each group.</li>
        <li><strong>Custom Aggregations</strong>: Implement custom aggregation functions beyond the standard sum, average, etc.</li>
    </ul>
    <h2>Best Practices</h2>
    <ul>
        <li><strong>Choose the Grouping Order Wisely</strong>: Consider how your users will want to analyze the data when deciding the order of columns for grouping.</li>
        <li><strong>Limit Grouping Levels</strong>: Too many levels can make the data hard to read, so try to limit the number of nested groups.</li>
        <li><strong>Combine with Aggregation</strong>: Use aggregation in conjunction with grouping to provide summarized information about each group.</li>
    </ul>
    <h2>Conclusion</h2>
    <p>Row grouping in AG-Grid is an intuitive and interactive way to view data hierarchically. By using the drag-and-drop interface, you can quickly group and summarize data to facilitate better data analysis and decision-making.</p>
    <hr />
</div>
