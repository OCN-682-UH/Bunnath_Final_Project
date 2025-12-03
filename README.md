# Bunnath_Final_Project

## Shiny App Overview

This repository contains a Shiny application that I developed to demonstrate and explore a Discrete Choice Experiment (DCE) using wind farm data. The app is part of my course project and is meant to show how people make trade-offs between different renewable energy options, as well as how DCE data can be explored before running formal models.

👉 Shiny app link: [<https://zocool.shinyapps.io/ZBFinalProject/>]

## App Structure

The Shiny app has three main tabs:

### Tab 1: Welcome

This tab provides a brief introduction to the app and the idea behind discrete choice experiments. Users can enter their name and select a date, which helps personalize the experience before starting the survey.

### Tab 2: Sample Survey

This tab presents a simplified discrete choice experiment based on wind farm attributes such as turbine size, height, distance from residential areas, impacts on wildlife, and cost. Users complete a small number of hypothetical choice tasks and answer basic socio-demographic questions. Responses are saved to demonstrate how DCE data would typically be collected.

### Tab 3: Data Table

This tab provides an interactive data table that displays the underlying wind farm choice data used in the app. Users can select which variables to view using the checkbox panel, making it easier to focus on specific columns such as choice outcomes, choice tasks, or respondent characteristics.

### Tab 4: Explore the Data

This tab allows users to interactively explore the wind farm dataset. Users can choose variables for the x- and y-axes, color points by different attributes, and facet plots by categorical variables. The app also includes options to add jitter (to reduce overlapping points) and smooth curves (to highlight overall trends).

The Explore tab is designed for exploratory data analysis, with a focus on visualizing individual-level data and identifying patterns such as trends across choice tasks or potential missing responses, rather than producing final summary results.

## Purpose of the App

The main purpose of this app is to practice building a Shiny application for DCE data and to better understand response behavior through visualization. It helps explore data structure, check data quality, and gain insights into how choices evolve across tasks before moving on to econometric analysis.
