​🔭 Convex Lens Simulation with Ray Tracing





​A JavaFX application designed to simulate how light rays interact with a convex lens using fundamental principles of geometric optics. This project demonstrates ray tracing, refraction via Snell's Law, and the generation of a visual spot diagram.


​🎯 Project Objective
​The goal of this simulation is to provide a valuable educational tool for optics and physics.It allows users to visualize and understand the behavior of light rays as they pass through a convex lens, confirming theoretical principles with adjustable parameters.  


​✨ Features
​

Adjustable Parameters: Users can input the Focal Length and Aperture Diameter of the convex lens.  
​

Ray Tracing Simulation: Simulates light rays passing through the lens, showing the path of the incident and refracted rays.  
​

Physics-Based Refraction: Light rays are refracted according to Snell's Law as they pass through the lens.  
​

Spot Diagram Generation: Creates a graphical representation (ScatterChart) showing the convergence point of the refracted rays, which is essential for understanding lens behavior and aberrations. 
​
JavaFX GUI: Built using JavaFX for a robust graphical user interface.  
​
Technical implementation 




Component Technology / Concept Used Rationale
Java Used for backend logic and application framework-- GUI Framework JavaFX
                                    
                              


Core Physics
Used to calculate the refractedAngle as light passes through the assumed lens material (refractive index n=1.5)-- Snell's Law



Visualization JavaFX Line and ScatterChart -- Used to draw the light paths and generate the spot diagram.



🚀 Getting Started




​Prerequisites
​🌟Java Development Kit (JDK) 8 or later.



🌟An IDE supporting JavaFX (e.g., IntelliJ, Eclipse).


🌀​ Running the Simulation



1.Clone the repository



2.Navigate to the ConvexLensSimulation.java file (or the relevant project directory).


3.Run the main application class: ConvexLensSimulation.



4.An input window will appear, allowing you to set the Focal Length (mm) and Aperture Diameter (mm). 



5.Click "Simulate Lens" to open two separate windows: the Ray Diagram simulation and the Spot Diagram.  





🖼️ Sample Output
​The application generates two main visual outputs upon simulation:
​

🌟Ray Diagram: Shows parallel incident rays converging after passing through the convex lens.  


​🌟Spot Diagram: A scatter chart illustrating the points where the refracted rays converge.  

