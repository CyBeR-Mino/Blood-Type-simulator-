Got it! Here's the README with the original design style:

---

# Genetic Inheritance Simulation

This project simulates the genetic inheritance of blood types across multiple generations using C. The simulation models how alleles are passed down from parents to their offspring, allowing you to visualize the inheritance pattern within a family tree.

## Features

- **Multi-Generational Simulation**: Simulate inheritance across any number of generations.
- **Randomized Alleles**: Alleles are randomly assigned based on typical blood type inheritance patterns.
- **Family Tree Visualization**: Print out the family tree with each individual's blood type.

## How It Works

Each person in the simulation has two alleles and two parents. The program starts with the youngest generation and recursively generates parents for each person until the oldest generation is reached. Alleles are randomly assigned to each individual based on their parents' alleles, or randomly for the oldest generation.

### Blood Type Alleles

The alleles are represented as follows:

- `A`
- `B`
- `O`

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/CyBeR-Mino/Blood-Type-simulator-.git
   ```
    ```bash
   cd Blood-Type-simulator-
   ```

2. Compile the program:
   ```bash
   gcc -o inheritance simulation.c
   ```

3. Run the program:
   ```bash
   ./inheritance
   ```

4. Enter the number of generations you want to simulate when prompted.

## Example Output

```
How many Generations do you want to simulate: 3
Child (Generation 0): blood type AO
Parent (Generation 1): blood type AB
Grandparent (Generation 2): blood type OO
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions, please contact [Y.Yint Aung](mailto:yeyeye1980aung@gmail.com).

---

This should match the style you prefer!
