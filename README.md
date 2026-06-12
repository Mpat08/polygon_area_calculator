# Polygon Area Calculator

A Python tool for computing geometric properties of rectangles and squares. Built using object-oriented programming with inheritance, the calculator supports area, perimeter, diagonal, and visual representations of shapes. Built to practice class design, inheritance, and method overriding in Python.

---

## Installation

No external dependencies required — just Python 3.x and the built-in `math` module.

```bash
# Clone the repository
git clone https://github.com/your-username/polygon-area-calculator.git

# Navigate into the project folder
cd polygon-area-calculator
```

---

## Usage

Run the script directly with Python:


```bash
python polygon_area_calculator.py
```

### `Rectangle` Class

| Method | Parameters | Description |
|---|---|---|
| `set_width(width)` | int/float | Updates the width |
| `set_height(height)` | int/float | Updates the height |
| `get_area()` | — | Returns width × height |
| `get_perimeter()` | — | Returns 2 × (width + height) |
| `get_diagonal()` | — | Returns the diagonal length|
| `get_picture()` | — | Returns a `*` visual of the shape (max size 50) |
| `get_amount_inside(shape)` | Rectangle/Square | Returns how many times a shape fits inside |

### `Square` Class (inherits from `Rectangle`)

| Method | Parameters | Description |
|---|---|---|
| `set_side(side)` | int/float | Sets all sides equally |
| `set_width(width)` | int/float | Updates both dimensions to maintain square shape |
| `set_height(height)` | int/float | Updates both dimensions to maintain square shape |

### Examples

**Rectangle**

<img width="400" height="600" alt="image" src="https://github.com/user-attachments/assets/62d8edd3-ccd2-44ac-9688-83d68c4289e8" />

**Square**

<img width="400" height="600" alt="image" src="https://github.com/user-attachments/assets/2622f580-f33d-4862-ac0a-430ee5588684" />

**Fit shape inside, get_amount_inside(self, shape)**

<img width="600" height="200" alt="image" src="https://github.com/user-attachments/assets/d6b7b326-4331-4aae-9b34-bd0f3cc185a4" />


---

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, copy, modify, and distribute this project as long as the original license and copyright notice are included.

---

## Contributors

**Mayur Patel** — Computer Engineering Major at the University of Central Florida

