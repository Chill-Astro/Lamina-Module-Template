<p align="center">
  <kbd>    
    <img alt="Lamina Promo" src="https://github.com/user-attachments/assets/09a1d838-7571-4929-82a4-19c88c12889e" />
  </kbd>
</p>

<div align="center">

This is Where Modules for Lamina ✦ are Stored! These Moduls are Loaded through Dynamo Scripties Loader

Get Modules for Lamina ✦ [here](https://github.com/Chill-Astro/Lamina-Modules-Repo).

Get Lamina ✦ [here](https://github.com/Chill-Astro/Lamina-Calculator).

For Maximum Reach, ensure to Fork the Above Mentioned Repo and I will add you here!

</div>

## WHAT IS DYNAMO???????

Dynamo is a Dynamic Scriptie Loader. Think of MODS in a Game, or Magisk Modules.

Yes that's right! An Importer of Math Scripts. Now you can Program her without Proper Coding Skills!

Check for Details [here!](https://github.com/Chill-Astro/Lamina-Dynamo-Scripties-Loader)

For Maximum Reach, ensure to Fork the Above Mentioned Repo and I will add you to my Modules!

---

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

- Fork [Lamina ✦ Modules Template](https://github.com/Chill-Astro/Lamina-Modules-Template).
- Sample Code is Given. Modify as you Need.
- I will add you to the Lamina ✦ Modules Repo

---

## HALL OF FAME MODULES 👍 : 

// Will Add Modules Here!

---

## ⚠️ IMPORTANT NOTICE ⚠️

Please be aware: There are fraudulent repositories on GitHub that are cloning this project's name and using AI-generated readmes, but they contain **completely random and unrelated files in each release**. These are NOT official versions of this project.

**ALWAYS ensure you are downloading or cloning this project ONLY from its official and legitimate source:**
`https://github.com/Chill-Astro/Lamina-Modules-Repo`

I am trying my best to report these people.

---

## ⚠️ Smoking Gun for Danger :

> [!CAUTION]
> **MALWARE ALERT:** If your downloaded folder looks like the images below, **DO NOT OPEN** any files. Format the drive or delete the folder immediately. Official releases are ONLY `.msix` files or an Inno Setup `.exe`.

<details>
<summary><b>View Details</b></summary>
  
* **Suspicious Windows Executables:** Files ending in `.exe`, `.bat`, or `.dll` (e.g., `luau.exe`, `StartApp.bat`).
* **Compressed Archives:** This project is distributed as an **MSIX**, never as a `.zip` or `.7z` containing Windows binaries.
* **Hidden Scripts:** Text files like `asm.txt` used to execute malicious code on your PC.
* The Following Folder Structure is used by Malware (Shown in a VM) :

![Screenshot_2026-03-01-18-52-39-337_com clone android dual space](https://github.com/user-attachments/assets/be691c9f-7def-4e8b-982c-c7ca2e9a067d)

![Screenshot_2026-03-01-18-53-09-759_com clone android dual space](https://github.com/user-attachments/assets/1c75031d-95be-4716-9347-b762e3dad5b8)

</details>

---


## Note from Developer :

Appreciate my effort? Why not leave a Star ⭐ ! Also if forked, please credit me for my effort and thanks if you do! :)

---

