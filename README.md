# Python Modules for Math/Stats/ML
A collection of modules that I am writing to cleanup messy, procedural mathematical python programs.

#### By_**Dawson Mortenson** [@codigntea17](https://github.com/codingtea17)_

## Getting Started
* Clone the repository.
* Choose the module that contains the method(s) that is/are relevant to your project. (Ex. The method backwards_elimination(x,y,columns,p_sig) preforms backwards elimination on a dataset)
* Place it in your project directory
* `from ###FILE_NAME### import ###METHOD_IN_MODULE###` (Ex. `from eliminations import backwards_elimination`)
* Ta-da! 😁

## Methods Guide
### "backwards_elimination" in elimination.py
* Inputs:
  * x: The dependent variables in the dataset
  * y: The independent variables in the dataset
  * columns: The number of features in the x dataset
  * p_sig: The p value significance level (default = 0.05)
* Outputs:
  * Returns the full fit of the model

## Authors

* **Dawson Mortenson** [@codigntea17](https://github.com/codingtea17)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
