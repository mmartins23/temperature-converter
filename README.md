### Overview of the Project
We will create a temperature converter application that can convert:

* Celsius to Fahrenheit and Kelvin
* Fahrenheit to Celcius and Kelvin
* Kelvin to Fahrenheit and Celcius

We have direct formulas for each conversion. Using these formulas we can convert from one to another pretty easily. Below is given the formulas we need:

```js
Celcius = (Fahrenheit - 32) / 1.8
Celcius = Kelvin - 273.15
Fahrenheit = (Celcius * 1.8) + 32
Fahrenheit = ((Kelvin - 273.15) * 1.8) + 32
Kelvin = Celcius + 273.15
Kelvin = ((Fahrenheit - 32) / 1.8) + 273.15
```

We will create three input fields for Celcius, Fahrenheit, and Kelvin. Once one input is given, the other two will convert automatically. Suppose, We input a Celcius temperature, Fahrenheit, and Kelvin value for this input will change automatically.

***

The project is live on GitHub pages. You can check how it works using the link below:
https://mmartins23.github.io/temperature-converter/
