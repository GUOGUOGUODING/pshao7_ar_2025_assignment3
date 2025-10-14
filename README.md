# Assignment 3 — AR and Phong Reflection Model  
**Author:** Pucheng Shao  

---

## Q3 – Babylon.js AR Scene (Pikachu)
- Implements an AR scene using **Babylon.js** and **WebXR**.
- A Pikachu model (`pikachu2.glb`) is loaded and can be spawned and moved with the right-hand controller in AR mode.
- **How to run:**
  1. Clone the repository.  
  2. Open `Q3/index.html` in a browser supporting WebXR (e.g. Chrome + Quest 3 or Android device).  
  3. Allow camera access and click “Enter AR”.  

---

## Q5 – Phong Reflection Model
- Implements classic Phong shading in Babylon.js.
- The fragment shader completes the `shadePointLight()` function.
- Includes experiments with different light and material parameters and a second point light.

**Files:**
- `5a.js` – Base Phong implementation  
- `5b.js` – Parameter experiments (ambient, diffuse, specular, shininess, light color / pos)  
- `5c.js` – Adds second point light  

**How to run:**
1. Open `Q5/index.html` in a browser.  
2. Replace the shader script section with the code from 5a.js / 5b.js / 5c.js to view each part’s result.  


