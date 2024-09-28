# FECG Dataset Visualizer

## Overview

This repository contains a Python code implementation for visualizing 5 fetal ECG (FECG) datasets from PhysioNet. The tool allows users to load and visualize specific channels (e.g., abdominal ECG, maternal ECG) with the option to leave certain subplots empty for MECG and FECG, as requested.

The tool is built using Python and leverages libraries such as `wfdb` and `matplotlib` for signal loading and plotting. It is particularly useful for visualizing physiological data in research applications involving fetal ECG datasets.

## Features

- **Load FECG Datasets**: Select and load individual FECG datasets from PhysioNet.
- **Custom Subplots**: Visualize individual channels of abdominal ECG while leaving MECG and FECG subplots empty.
- **User Input**: User can specify which dataset to visualize from the available files.
- **Plot Time-Series Data**: Visualize time-series data with proper axis labels, titles, and grid.

## Requirements

Make sure you have the following Python packages installed:

```bash
pip install wfdb matplotlib
