<p align="center">
  <kbd>    
    <img alt="Lamina Promo" src="https://github.com/user-attachments/assets/09a1d838-7571-4929-82a4-19c88c12889e" />
  </kbd>
</p>

<div align="center">

Template Module for Lamina ✦!

Get Modules for Lamina ✦ [here](https://github.com/Chill-Astro/Lamina-Modules-Repo).

Get Lamina ✦ [here](https://github.com/Chill-Astro/Lamina-Calculator).

For Maximum Reach, ensure to Fork the Above Mentioned Repo and I will add you here!

</div>

## The Basic Structure for a .lamina file :

- A `.lamina` is Essentially a .json file.
  
- Structure :

        
      {
        "Metadata": {
          "Name": "", // This is What your Module Shows Up!
          "Author": "", // Write your Username.
          "Version": "", // This is the Version of your Scriptie.
          "Description": "", //
          "Repo": "https://github.com/yourlink"
        },
        "UI": {
          "Formula": "", // Example y = mx + c
          "Inputs": [
            { "Header": "Input Label", "Placeholder": "0.0", "Key": "var_name" } // Add as many as you like.
          ]
        },
        "Logic": {
          "Output": "NCalc math string using [var_name]", // Your Output.
          "Error": "Message if math fails" // Your Error.
        }
      }

- Example :

      {
        "Metadata": {
          "Name": "Quadratic Equation Demo",
          "Author": "Chill-Astro Software",
          "Version": "1.0",
          "Description": "Solves ax² + bx + c = 0",
          "Repo": "https://github.com/Chill-Astro/Lamina-Modules-Repo"
        },
        "UI": {
          "Formula": "x = [-b ± √(b² - 4ac)] / 2a",
          "Inputs": [
            { 
              "Label": "Coefficient a", 
              "Key": "a", 
              "Header" : "Enter A",
              "Placeholder": "1.0" 
            },
            { 
              "Label": "Coefficient b", 
              "Key": "b", 
              "Header" : "Enter B",
              "Placeholder": "0.0" 
            },
            { 
              "Label": "Coefficient c", 
              "Key": "c", 
              "Header" : "Enter C",
              "Placeholder": "0.0" 
            }
          ]
        },
        "Logic": {
          "Output": "'x1 = ' + ((-b + Sqrt(Pow(b, 2) - 4*a*c)) / (2*a)) + ' | x2 = ' + ((-b - Sqrt(Pow(b, 2) - 4*a*c)) / (2*a))",
          "Error": "Invalid Input (Check Discriminant)"
         }
      }


---

## Contributing :

- Fork this Repo.
- Sample Code is Given. Modify as you Need.
- I will add you to the Lamina ✦ Modules Repo!

---

## Note from Developer :

A Star ⭐ will be Appreciated to Support this Project! :)

---

