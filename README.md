# 3DOF-robotics-kinematics-tool
3-Degree of freedom planar robot arm with forward kinematics and Jacobian computations


This repository demonstrates symbolic and numeric computations for a **3-DOF planar robot arm**, including forward kinematics, Jacobian computation, and a gradient descent example for moving the end-effector to a target.

---

## Repository Structure

- `robot_arm_3d_kinematics.ipynb`  
  - Contains the **original exploratory code**.  
  - Computes symbolic forward kinematics, Jacobian, and a symbolic error function.  
  - Useful for understanding the step-by-step process.

- `robot_arm_3d_kinematics_modular.ipynb`  
  - Contains the **refactored, modular version** of the code.  
  - Organized into functions for defining symbols, computing FK, evaluating Jacobian, and gradient descent optimization.  
  - Cleaner and reusable for experiments or extensions.

---

## Features

- **Forward Kinematics (FK):** Compute end-effector `(Xf, Yf)` symbolically and numerically.  
- **Jacobian Matrix:** Compute symbolic and numeric Jacobian for the 3-DOF arm.  
- **Error Function:** Define a symbolic error function for potential optimization.  
- **Gradient Descent:** Iteratively update joint angles to move the end-effector toward a target position.  
- **SymEngine:** Faster symbolic differentiation if installed.  

---

## Requirements

- Python 3.x  
- Libraries: `sympy`, `numpy`, `math` (built-in), `symengine`   

Install dependencies:

```bash
pip install sympy numpy symengine

