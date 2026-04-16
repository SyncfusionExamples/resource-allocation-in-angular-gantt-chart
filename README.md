# Resource Allocation and Task Breakdown in Angular Gantt Chart

A Syncfusion Angular Gantt sample demonstrating resource-centered scheduling, multi-taskbar rendering, and over-allocation visibility.

## Overview

This project uses `@syncfusion/ej2-angular-gantt` in an Angular app to display a resource view chart with task assignments and inline editing.

## Features

- Resource allocation using `resources` and `resourceInfo`
- Resource View mode with grouped assignments
- Multi-taskbar support for shared resources
- Over-allocation detection with `showOverAllocation`
- Inline add/edit support through toolbar options

## Dependencies

- Angular `~19.2.16`
- `@syncfusion/ej2-angular-gantt` `^20.1.56`

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

## What the App Shows

- Task grid with Task ID, Task Name, Resources, Start Date, End Date, and Duration
- Resource assignments defined in `src/data.ts`
- Task bar labels showing resources and task names
- Built-in add/edit support using `editSettings` and `toolbarOptions`

## Notes

- Uses `viewType="ResourceView"`
- `enableMultiTaskbar` is enabled
- `showOverAllocation` highlights overload conditions
