# Pips Solver by Kai Gowers

This project uses logical constraint solving (via Z3) to solve any configuration of **Pips**, the New York Times domino placement puzzle. The interface allows you to visualize the board, run the solver, and display a valid domino placement solution.

## Repository Structure

- **`pips_solver_interface.py`** - PyGame fully interactive app for solving pips
- **`pips_solver_report.pdf`** - Written report/discussion of methodologies
- **`pips_solver_report_notebook.ipynb`** - Written report/discussion of code in a Jupyter notebook (**REFER TO THIS FOR CODE EXPLANATIONS**)

## Quick Start Guide

Follow the steps below to set up and run the interface on your machine.

## 1. Clone the repository

```bash
git clone https://github.com/Kai-Gowers/Pips-Major-Paper.git
cd Pips-Major-Paper
```

## 2. Create and activate a virtual environment

```bash
python3 -m venv pips-env
source pips-env/bin/activate
```

## 3. Install dependencies

```bash
pip install -r requirements.txt
```

## 4. Run the application

```bash
python3 pips_solver_interface.py
```

## Done

The application should now be running.
