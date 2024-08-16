# Planner-hut---a-customized-diet-application


# Planner Hut Website

Welcome to the Planner Hut website repository! This website is designed to help users organize their diet plans and maintain physical fitness. It features various sections including workout videos, diet recommendations, and contact information.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Structure](#structure)
- [Usage](#usage)
- [Customization](#customization)
- [Contact](#contact)
- [License](#license)

## Introduction

Planner Hut is a simple and responsive website created using HTML, CSS, and JavaScript. It offers users access to diet plans and workout videos to support their physical fitness journey.

## Features

- **Responsive Design**: The website adapts to different screen sizes for a seamless user experience.
- **Workout Section**: A collection of workout videos to help users burn calories and stay fit.
- **Diet Section**: Includes videos on different diet types like Carbo Diet, Liquid Diet, and Protein Diet.
- **Embedded YouTube Videos**: Users can watch videos directly on the website.
- **Contact Form**: Allows users to send messages directly from the website.

## Structure

The website is organized into several sections:

1. **Header**: Contains the logo, navigation menu, and a brief description of the website's purpose.
2. **Main Content**: Divided into multiple articles:
   - **Intro**: Overview of healthy food recipes and introductory videos.
   - **Workout**: Collection of workout videos.
   - **Diet**: Sections on Carbo Diet, Liquid Diet, and Protein Diet with corresponding videos.
3. **Contact**: Form for users to send messages and contact information.
4. **Footer**: Contains copyright information.




# Planner Hut Website - CSS Structure

This repository contains the CSS files used to style the Planner Hut website. The CSS is organized into several modular components, making it easier to manage and customize the website's appearance.

## Table of Contents

- [Introduction](#introduction)
- [File Structure](#file-structure)
- [Breakpoints](#breakpoints)
- [Base Styles](#base-styles)
- [Components](#components)
- [Layout](#layout)
- [External Libraries](#external-libraries)
- [Customization](#customization)
- [License](#license)

## Introduction

The CSS is organized using the SCSS (Sassy CSS) preprocessor, which allows for variables, mixins, and modular file imports. This structure is designed to be flexible and easy to maintain.

## File Structure

The CSS is divided into several key sections:

- **libs**: Contains reusable variables, functions, mixins, vendor styles, and breakpoint definitions.
- **base**: Includes base styles for resetting default browser styles, page layout, and typography.
- **components**: Contains styles for individual UI components like forms, buttons, icons, and tables.
- **layout**: Manages the overall layout of the website, including background, wrapper, header, main content, and footer.

## Breakpoints

The breakpoints are defined using a custom mixin that sets the media queries for responsive design. The breakpoints are as follows:

- **xlarge**: 1281px - 1680px
- **large**: 981px - 1280px
- **medium**: 737px - 980px
- **small**: 481px - 736px
- **xsmall**: 361px - 480px
- **xxsmall**: 360px and below

These breakpoints ensure that the website looks good on all screen sizes, from large desktops to mobile devices.

## Base Styles

- **reset**: Resets default browser styles to provide a consistent base across all browsers.
- **page**: Defines global styles for the page layout.
- **typography**: Sets global typography styles, including font-family, font-size, line-height, and text alignment.

## Components

Each component has its own SCSS file, making it easy to manage and customize:

- **form**: Styles for form elements like inputs, textareas, and buttons.
- **box**: Box component styles, used for card-like elements.
- **icon**: Styles for icons.
- **image**: Image styles.
- **list**: Styles for lists.
- **actions**: Styles for action buttons and links.
- **icons**: Additional icon styles.
- **table**: Table styles.
- **button**: Button styles.

## Layout

The layout section controls the overall structure of the website:

- **bg**: Background styles for the website.
- **wrapper**: Styles for the main content wrapper.
- **header**: Header layout and styling.
- **main**: Main content area styles.
- **footer**: Footer layout and styling.

## External Libraries

- **FontAwesome**: The website uses FontAwesome for icons, imported via `fontawesome-all.min.css`.
- **Google Fonts**: The website uses the "Source Sans Pro" font from Google Fonts, imported via `@import url('https://fonts.googleapis.com/css?family=Source+Sans+Pro:300italic,600italic,300,600');`.

## Customization

To customize the styles:

1. **Variables**: Modify the variables in the `libs/vars` file to change global values like colors, fonts, and spacing.
2. **Mixins**: Use or modify the mixins in `libs/mixins` for consistent styling across components.
3. **Components**: Modify individual component files in the `components/` directory to update specific UI elements.
4. **Layout**: Update the layout files in the `layout/` directory to change the overall structure of the website.









