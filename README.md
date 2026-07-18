# smart-device-management-system
This repository contains an interactive Python app showcasing OOP principles (Inheritance, Encapsulation, Polymorphism) to manage a smart device technology system. You can run this program using `python main.py` or within a jupyter notebook cell.


# Smart Device Management System
This is a  Python-based Object-Oriented Programming (OOP) project showcasing a management program for handling a system of smart home appliances. 

## Project Features
Encapsulation: Protects internal device identities and configurations using private variables and strict validation workflows.
Inheritance: Leverages a single core `SmartDevice` base layout extended cleanly into `SmartThermostat`, `SmartLight`, and `SmartCamera` models.
Polymorphism: Manages distinct hardware models dynamically within a centralized system registry.
Interactive Interface: Features a robust, built-in CLI terminal menu loop for live component tracking and testing.

## System Architecture Details
SmartDevice (Base Parent): Tracks common attributes like ID, naming schemas, and baseline power states.
SmartThermostat (Child): Incorporates isolated temperature metrics extraction ways.
SmartLight (Child): Regulates lighting limits safely by enforcing structural boundary checks. (0-100%).
SmartCamera (Child): Controls recording feeds based on the device's live power availability.


## How to Run the Code

### Prerequisites
Make sure you have Python 3.x installed on your computer. You can check your version by running:
```bash
python --version
