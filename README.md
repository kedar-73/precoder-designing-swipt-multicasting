# Precoder Designing for SWIPT Multicasting System

This project involves the design of a precoder that manipulates transmitted signals before sending them over a network to improve the quality and reliability of data transmission in SWIPT (Simultaneous Wireless Information and Power Transfer) multicasting systems. The goal is to optimize signal transmission by employing advanced precoding techniques like Zero Forcing (ZF), Minimum Mean Square Error (MMSE), and Matched Filter (MF), and compare their respective transmitted power.

## Project Objective

The objective of this project is to design an efficient precoding scheme for SWIPT multicasting systems that minimizes the overall transmitted power. This is done while considering constraints such as the minimum Signal-to-Noise Ratio (SINR) and the threshold of harvested energy at the corresponding users/groups.

### Key Techniques Implemented:
- **Zero Forcing (ZF) Precoder**
- **Minimum Mean Square Error (MMSE) Precoder**
- **Matched Filter (MF) Precoder**

These techniques are evaluated based on their transmitted power and their ability to optimize signal transmission while maintaining the integrity and efficiency of the data.


### Step 2: Navigate to the project directory
#### This will take you into the folder where the project files are located
```bash
cd precoder-designing-swipt-multicasting
```

### Step 3: Set up a virtual environment (Optional but recommended)
#### This creates an isolated Python environment for your project
```bash
python -m venv venv
```
### Step 4: Activate the virtual environment
#### For Windows:
```bash
venv\Scripts\activate
```
#### For macOS/Linux:
```bash
source venv/bin/activate
```
### Step 5: Install the required dependencies
#### This will install all the libraries mentioned in the 'requirements.txt' file
```bash
pip install -r requirements.txt
```
### Step 6: Run the main script
#### This will execute the main Python file and perform the precoding operations
```bash
python src/main.py
```



