# **Smart Fan Speed Controller using Fuzzy Logic**

## Project Overview

This smart control system implements a **Mamdani Fuzzy Inference System** to automatically determine fan speed based on temperature and humidity inputs. Unlike conventional on/off systems, this project utilizes fuzzy logic to produce smoother and more efficient speed transitions alligned with environmental conditions.

## Project Context

This project was developed as a **Freelance Commission**. It serves as a simulation tool to demonstrate how Fuzzy Logic can be applied to home automation (IoT) scenarios to optimize energy consumption and user comfort.

## The Problem & Solution

- **Rigid Control**: Traditional control system are often too rigid, typically operating in a simple binary state.
- **Smooth Transition**: By utilizing Fuzzy Logic, fan speed varies dynamically (Slow, Medium, Fast) based on the calculated membership degrees of temperature and humidity.

## Tech Stack

- **Language**: Python
- **Math & Logic**: NumPy (Used for the manual implementation of Fuzzy Membership Functions)
- **Visualization**: Matplotlib (Used for generating membership functions and aggregation plots)

## Key Features (Technical Highlights)

- **Manual Fuzzification**: Designed custom membership functions for `Temperature` (Cold, Normal, Hot) and `Humidity` (Low, Medium, High) from scratch without external fuzzy libraries.
- **9-Rule Inference Base**: Implemented a comprehensive logic gate system to handle every possible environmental combination.
- **Centroid Defuzzification**: Utilized area aggregation and center-of-gravity calculations to determine precise, crisp fan speed percentages.
- **Interactive CLI**: Features a user-friendly command-line interface for real-time simulation and testing.
- **Data Visualization**: Provides clear graphical representations of degree of membership and final aggregation for transparent analysis.

## How to Run

1. **Clone Repository**: `git clone https://github.com/desdjaja/fuzzy-fan-control.git`
2. **Install Dependencies**: Ensure you have NumPy and Matplotlib installed via (`pip install numpy matplotlib`).
3. **Run Script**: Run the cell.
4. **Input Parameters**: Enter the current temperature and humidity when prompted.
5. **Analyze Results**: Review the calculated fuzzification values, active rules, and generated output graphs.

## Repository Structure

- `notebooks/`: Main file `Mamdani_FIS_Sistem_Pengaturan_Kecepatan_Kipas_Otomatis_Berdasarkan_Suhu_dan_Kelembapan.ipynb`.
- `docs/`: Technical documentation and detailed fuzzy rule explanations.

## My Role

**Independent Developer**

- Architected and coded all mathematical functions for the fuzzy logic system from the scratch.
- Developed a visualization suite to simplify the interpretation of complex inference results.
- Conducted rigorous unit testing to ensure linguistic outputs perfectly aligned with the established rule base.

<br>

_Developed by Des Djaja Mahesa_
