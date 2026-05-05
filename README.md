# FlowerShop (Java)

This is a simple console program for managing a small flower inventory.

## Requirements

- Java JDK 17+ (JDK 11+ usually works too)

## Files

- `FlowerShop driver class.txt` currently contains the `public class FlowerShop`.
  - **To compile in Java, this file must be renamed to `FlowerShop.java`.**
- The code also references a `Flower` class (e.g. `new Flower(...)`), so you must have a `Flower.java` file in the same folder.

## How to run

1) Open Terminal in this folder:

`/Users/mac/Desktop/LET'S FIX GITHUB/FLOWER SHOP/CODES`

2) Rename the source file to match the public class name:

```bash
mv "FlowerShop driver class.txt" FlowerShop.java
```

3) Make sure `Flower.java` exists in the same folder.

4) Compile:

```bash
javac Flower.java FlowerShop.java
```

5) Run:

```bash
java FlowerShop
```

## Notes

- The program will prompt you to type a flower name to search (for example: `Rose`).
- If you get `cannot find symbol: class Flower`, it means `Flower.java` is missing or not in the same directory.
