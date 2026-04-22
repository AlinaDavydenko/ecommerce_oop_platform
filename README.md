# E-commerce platform 
## Creation of a platform for online trading 

A Python-based e-commerce backend built with OOP principles.  
Implements core online store functionality: products, categories, and order management.

## Features

- Product and category management using OOP class hierarchy
- Data loading from JSON files
- Input validation and error handling
- Test coverage with pytest

## Tech Stack

- Python 3.10+
- Poetry (dependency management)
- pytest
- flake8 (code style)

## Project Structure
src/        
> Core application logic and classes

tests/
> pytest test suite

data/
> Sample data (JSON)

## Installation

```bash
git clone https://github.com/AlinaDavydenko/ecommerce-oop-python
cd ecommerce-oop-python
poetry install
```

## Running Tests

```bash
poetry run pytest
```

## OOP Concepts Applied

- Classes and inheritance
- Encapsulation and properties
- Magic methods (`__str__`, `__len__`, `__add__`)
- Abstract classes
