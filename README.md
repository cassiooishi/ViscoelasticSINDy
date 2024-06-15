# ViscoelasticSINDy
These codes were used to construct the results of the paper ``Nonlinear Parametric Models of Viscoelastic Fluid Flows'' by Cassio Oishi, Alan Kaptanoglu, J. Nathan Kutz, and Steven L. Brunton. The process involves several key steps:
Proper Orthogonal Decomposition (POD): We start by applying POD to the simulation data to extract the most energetic modes.
Sparse Identification of Nonlinear Dynamics (SINDy): Using the computed modes, we implement SINDy to identify a sparse system for the first two modes, employing linear and cubic polynomial bases.
Quadratic Regression: For the third and fourth modes, we apply quadratic regression using the first modes as the basis.
Numerical Integration: The resulting system is numerically integrated over time to predict the temporal behavior of the modes.
Field Reconstruction: Finally, the field is reconstructed based on the computed modes, providing a comprehensive understanding of the flow dynamics.
This approach allows for an efficient and accurate representation of viscoelastic fluid flows, leveraging the strengths of data-driven modeling techniques. Due to the limitation in uploading large datasets, all simulation data can be found in https://drive.google.com/drive/folders/1ukKo8uuNUAW2GIStLC4oWOBPFJlzBlBR?usp=drive_link
