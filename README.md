# Resource Allocation and Task Breakdown in Angular Gantt Chart

An Angular Gantt sample demonstrating resource‑centered scheduling, multi‑taskbar rendering, and over‑allocation visibility.

## Repository Description

This repository provides an Angular example that demonstrates how to configure the [Angular Gantt Chart](https://www.syncfusion.com/angular-components/angular-gantt-chart) in Resource View mode to assign tasks to shared resources and visualize workload distribution.

## Project Overview

The sample highlights resource‑based scheduling scenarios where tasks are grouped by assigned resources. It demonstrates how multiple tasks linked to the same resource are rendered together and how overlapping assignments are identified visually.

## Features

- Resource allocation using `resources` and `resourceInfo`
- Resource View mode with grouped task assignments
- Multi‑taskbar rendering for shared resources
- Over‑allocation detection using `showOverAllocation`
- Inline add and edit support through toolbar and editing settings

## Getting Started

### Prerequisites

- Node.js (LTS or later)
- Angular CLI


## Run Locally

1. Install dependencies:

```bash
npm install
```

2. Start the app:

```bash
ng serve --open
```

3. Open the browser at:

```text
http://localhost:4200
```

## Notes

- The chart runs with `viewType="ResourceView"` enabled.
- enableMultiTaskbar allows multiple tasks to appear for a resource.
- Editing actions are enabled using toolbar and edit settings.

## Related Links

- [Explore Angular Gantt Chart](https://www.syncfusion.com/angular-components/angular-gantt-chart)
- [Gantt Resource Allocation Documentation](https://ej2.syncfusion.com/angular/documentation/gantt/resources/)
- [Gantt Chart Feature Overview](https://ej2.syncfusion.com/angular/documentation/gantt/overview)
- [Angular Gantt Chart Getting Started Guide](https://ej2.syncfusion.com/angular/documentation/gantt/getting-started)
- [Gantt API Documentation](https://ej2.syncfusion.com/angular/documentation/api/gantt/)
- [Gantt Chart Live Demos and Examples](https://ej2.syncfusion.com/angular/demos/#/tailwind3/gantt/resources)
