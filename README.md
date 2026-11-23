# ANSYS-Mounting-Bracket-FEA

Static Structural and Modal Analysis of a Mechanical Mounting Bracket using ANSYS.



\1. Project Overview



This project focuses on the 3D design and finite element analysis of a mechanical mounting bracket using ANSYS SpaceClaim and ANSYS Mechanical.



The objective is to investigate the structural response of the bracket under an applied load and study its vibration characteristics through modal analysis.



Two major analyses were performed:



\- Static Structural Analysis

\- Modal Analysis



\ 2. Software and Tools



\- ANSYS Workbench

\- ANSYS SpaceClaim

\- ANSYS Mechanical



\ 3. CAD Model



The mounting bracket was modelled using ANSYS SpaceClaim.



The geometry consists of a vertical mounting plate, a horizontal platform, mounting holes and reinforcement features where applicable.



The model was prepared as a solid body for finite element analysis.



\4. Material Properties



The model uses Structural Steel.



| Property | Value |

|---|---:|

| Young's Modulus | 200 GPa |

| Poisson's Ratio | 0.30 |

| Density | 7850 kg/m³ |

| Yield Strength | \[Actual/assumed value] |



\5. Static Structural Analysis



Static Structural Analysis was performed to investigate the response of the bracket under the specified loading and support conditions.



\Boundary Conditions



\- Support: Fixed support on the rear planar face.

\- Applied load: 1000N Downwards.

\- Material: Structural Steel.



\Meshing



The geometry was discretized using a finite element mesh in ANSYS Mechanical.



\Results



\Equivalent von Mises Stress



Maximum equivalent stress: 46.627 MPa.



\Total Deformation



Maximum total deformation: 1.0854e-5 mm.



\Equivalent Elastic Strain



Maximum equivalent elastic strain: 0.0003415.



\6. Modal Analysis



Modal analysis was performed to determine the natural frequencies and corresponding vibration mode shapes of the bracket.



The first six natural frequencies obtained are:



| Mode | Natural Frequency |

|---|---:|

| 1 | 1442 Hz |

| 2 | 1664.3 Hz |

| 3 | 2904 Hz |

| 4 | 3838.9 Hz |

| 5 | 4206.5 Hz |

| 6 | 5455.1 Hz |



\Mode Shapes



The mode shapes represent the relative deformation patterns associated with the calculated natural frequencies.



\7. Engineering Interpretation



The static structural results were used to investigate the stress distribution and deformation behaviour of the bracket under the specified loading conditions.



The modal results were used to understand the vibration characteristics of the structure and identify its first six natural frequencies.



The results are dependent on the idealized geometry, material properties, mesh and boundary conditions used in the simulation.



\8. Project Files



\- CAD: Native SpaceClaim model and STEP geometry.

\- ANSYS\_Project: Archived Workbench simulation.

\- Static\_Structural: Static analysis results.

\- Modal\_Analysis: Modal frequencies and mode shapes.

\- Calculations: Engineering results spreadsheet.

\- Documentation: Technical report.



\9. Conclusion



This project demonstrates the application of ANSYS Workbench for static structural and modal analysis of a mechanical component.



It provided practical experience in CAD modelling, finite element meshing, material assignment, boundary conditions, structural result interpretation and vibration analysis.



