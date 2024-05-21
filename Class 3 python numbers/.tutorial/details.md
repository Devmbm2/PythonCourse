# Python Numbers

There are three types in Python:

int
float
complex

### Integer (int)

An integer, or int, is a whole number, positive or negative, without decimals. Integers in Python have unlimited length, meaning they can be as large as needed for calculations without overflow.

```
# Positive integer
x = 12345678901234567890

# Negative integer
y = -98765432109876543210

print(x)
print(y)

```
### Float

A float, or "floating point number," is a number that is positive or negative and contains one or more decimal points. Floats are used to represent real numbers and are especially useful for more precise calculations.

```

# Positive float
x = 123.45

# Negative float
y = -987.65

# Float with no decimal (represented as a float)
z = 1.0

```

Floating point numbers can represent very large or very small values by using scientific notation:

```

large_float = 1.23e10  # 1.23 * 10^10
small_float = 1.23e-10 # 1.23 * 10^-10

print(large_float)
print(small_float)


```


### Complex

Complex numbers are written with a "j" as the imaginary part. In Python, a complex number is composed of a real part and an imaginary part.

```
# Complex number with both real and imaginary parts
x = 3 + 5j

# Complex number with only imaginary part
y = 7j

# Complex number with negative imaginary part
z = -2 - 3j

```
###practical example of complex numbers 

Let's say you have a simple problem where you need to calculate the total resistance in an electrical circuit with both resistors and capacitors. The resistance of a resistor is represented by a real number, while the impedance of a capacitor is represented by a complex number.
Here's a practical example where we have a resistor with resistance 10 ohms and a capacitor with impedance Z=5−2j ohms. We want to calculate the total impedance of the circuit, which is the sum of resistor and capacitor impedances

Example

```
# Define resistor resistance
resistor_resistance = 10

# Define capacitor impedance (5 - 2j)
capacitor_impedance = 5 - 2j

# Calculate total impedance
total_impedance = resistor_resistance + capacitor_impedance

# Print total impedance
print("Total impedance:", total_impedance)

```

