# Blazor DataGrid - Single Click Editing with Boolean Column

## Overview

This sample demonstrates how to perform single-click editing of a Boolean column in the Syncfusion [Blazor DataGrid](https://www.syncfusion.com/blazor-components/blazor-datagrid). Instead of entering the grid's standard edit mode, the sample renders an `SfCheckBox` component inside a Grid column template, allowing users to update Boolean values directly with a single click. This approach provides a faster editing experience for status, flag, and selection-based fields while keeping the grid data source synchronized with user interactions.

## Key Features

- Uses the Syncfusion Blazor `SfGrid` component to display tabular data.
- Renders an `SfCheckBox` component inside a Grid column template.
- Associates the checkbox with a mapped data field so Boolean values can be updated directly.
- Demonstrates single-click editing behavior without requiring users to enter the grid's normal edit mode.
- Updates the underlying grid data source immediately when the checkbox value changes.
- Provides a practical example of template-based editing for Boolean fields in a Syncfusion DataGrid.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the `SingleClickEditing.sln` solution file.
3. Restore all NuGet packages.
4. Ensure the `SingleClickEditing` project is selected as the startup project if required.
5. Build the solution.
6. Run the application using `Ctrl+F5`.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the folder containing `SingleClickEditing.csproj`.

```bash
dotnet restore
dotnet run
```

4. Open the local URL displayed in the terminal after the application starts.

## Project Structure

- `Pages/` — contains the Blazor page implementing the Syncfusion DataGrid and Boolean column template with `SfCheckBox`.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For feature documentation, see the Syncfusion Blazor DataGrid editing documentation: https://help.syncfusion.com/grid-sdk/blazor/data-grid/editing#update-boolean-column-value-with-a-single-click

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.
