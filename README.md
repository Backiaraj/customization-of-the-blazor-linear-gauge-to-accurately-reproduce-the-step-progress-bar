# Blazor Linear Gauge Step Progress Bar Customization

This sample demonstrates how to effectively customize the [Blazor Linear Gauge](https://www.syncfusion.com/blazor-components/blazor-linear-gauge) component to accurately reproduce the Step Progress Bar component in Blazor. Learn how to leverage advanced customization features like annotations, pointers, ranges, and event handlers to create a professional multi-step progress tracker.

## Overview

Building multi-step progress indicators is a common requirement in modern applications. While dedicated progress components are available, the Blazor Linear Gauge component offers exceptional flexibility for creating sophisticated step-by-step progress trackers with custom icons and labels.

This sample includes:
- A 5-step progress bar with custom icons and labels
- Real-time step state visualization (completed, current, pending)
- Responsive horizontal layout
- Custom axis labels mapped to step names
- Image-based markers for visual indicators

## Features

- **Multi-Step Progress Tracking** - Create sophisticated 5-step workflow indicators using the flexible Linear Gauge component
- **Custom Icons & Labels** - Replace default indicators with your own icons and meaningful step names (Select Item, Add to Cart, Fill Details, etc.)
- **Visual State Management** - Color-coded ranges distinguish completed steps (green: #1FAC8A) from pending steps (gray: #D1D9DD)
- **Advanced Pointer Customization** - Use image-based markers and circle indicators to show step completion status
- **Dynamic Label Mapping** - Event-driven `AxisLabelRendering` handler converts numeric values to user-friendly step names in real-time
- **Responsive Horizontal Layout** - Clean, centered gauge that adapts to different screen sizes
- **Production-Ready Code** - Well-structured Blazor components with clear separation of concerns
- **Easy to Customize** - Modify step count, colors, icons, and labels without complex re-architecture

## Prerequisites

* [.NET SDK 10.0](https://dotnet.microsoft.com/en-us/download/dotnet/10.0) or later
* [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
* [Visual Studio Code](https://code.visualstudio.com/)

## Getting Started

### Clone the Repository

```bash
git https://github.com/SyncfusionExamples/customization-of-the-blazor-linear-gauge-to-accurately-reproduce-the-step-progress-bar.git
cd customization-of-the-blazor-linear-gauge-to-accurately-reproduce-the-step-progress-bar
```

### Run with Visual Studio

1. Open the solution file using Visual Studio 2022 or later.
2. Restore the NuGet packages by rebuilding the solution.
3. Build the project to ensure there are no compilation errors.
4. Run the project.

### Run with .NET CLI

```bash
# Restore dependencies
dotnet restore

# Run the project
dotnet run
```

## References

**Documentation**: https://blazor.syncfusion.com/documentation/linear-gauge/getting-started-with-server-app

**Online examples**: https://blazor.syncfusion.com/demos/linear-gauge/step-progress-bar?theme=fluent2