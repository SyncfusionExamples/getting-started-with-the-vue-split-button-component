# Getting Started with the Vue Split Button Component

## Repository Description

A quick start project demonstrating how to integrate the Syncfusion Vue Split button component into a Vue application, including separators, icons, and custom icon positioning.

## Overview

This project provides a practical guide for implementing the Syncfusion Split Button component in Vue applications. The Split Button combines a standard button with a dropdown menu, enabling users to trigger primary actions or access additional options.

## Features

- Split Button implementation and configuration
- Separator support in dropdown menus
- Icon display and customization
- Icon positioning control (left, right, top)
- Vue 3.x integration

## Prerequisites

- Node.js 12.x or higher
- npm 6.x or higher
- Vue.js 3.x
- Syncfusion Vue components package

## Installation

1. Clone or download the project
2. Install dependencies:
   ```
   npm install
   ```
3. Install Syncfusion Vue Split Button:
   ```
   npm install @syncfusion/ej2-vue-splitbutton
   ```

## Usage

Import and use the Split Button component in your Vue components:

```vue
<template>
  <ejs-splitbutton :items="items" :iconCss="'e-icons e-edit'" />
</template>
```

Configure dropdown items with separators and custom icons as needed.

## Configuration

The Split Button component supports various options including:

- Button text and styling
- Dropdown menu items and separators
- Icon positioning and styling
- Click handlers and event binding

## Support

For additional information, refer to the official Syncfusion Vue documentation and Vue.js integration guides.
