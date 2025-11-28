# Finite Element Analysis of QTZ125 Tower Crane
This report summarizes the structural design, finite element modelling, modal analysis, and seismic response simulation of the QTZ125 tower crane.

---

## 1. Research Objectives
1. Complete structural design of the tower crane  
2. Determine load combinations  
3. Perform structural safety verification  
4. Establish the finite element model  
5. Conduct seismic response analysis

## 2. Structural Design Summary
<img width="1073" height="916" alt="tower crane" src="https://github.com/user-attachments/assets/2b530ee0-49a6-4cac-bada-35b7c94c630f" />
<img width="1644" height="629" alt="image" src="https://github.com/user-attachments/assets/6aaff4e2-b514-4b92-8abd-52ef3bd6de02" />

##3. Finite Element Modelling

### 3.1 Modelling Goals
- Simplify structural geometry  
- Preserve stiffness, load paths, and boundary conditions  

### 3.2 Modelling Procedure
- 399 keypoints, 1016 lines
- Beam and truss elements assigned density, Young’s modulus, Poisson ratio, section properties
- Mesh generated after element assignment
<img width="1151" height="302" alt="image" src="https://github.com/user-attachments/assets/75957305-6bcb-4b10-bdbd-d9ea9c683f85" />


### 3.3 Simplifications
<img width="1702" height="433" alt="image" src="https://github.com/user-attachments/assets/b19f6d23-5d72-4a5f-a2e8-cda17d35b96b" />

- Equipment & accessories → equivalent loads  
- Base of mast → fully fixed  
- Loads:
  - Gravity  
  - Equivalent wind & inertial loads  
  - Seismic excitation  

---

## 4. Finite Element Analysis

### 4.1 Static Analysis
- Three critical working conditions chosen  
- Maximum stress & deformation extracted  
- Results meet stiffness and strength requirements  
<img width="1520" height="551" alt="image" src="https://github.com/user-attachments/assets/dbcede4c-0854-4bc4-b102-49bb402eff02" />

### 4.2 Modal Analysis
- Block Lanczos method  
- First six natural frequencies obtained  
- Boom sensitive to low-frequency excitation → resonance risk  
<img width="1084" height="411" alt="image" src="https://github.com/user-attachments/assets/8a400b05-52db-44ea-af91-1e1fafb02aea" />

### 4.3 Seismic Response Analysis
- El Centro wave, 53.8 s, Δt = 0.02 s  
- Three directions: X, Y, Z  
<img width="789" height="285" alt="image" src="https://github.com/user-attachments/assets/434f30fa-570b-41bf-945a-04d753e16786" />

Key findings:
- Boom tip → largest displacement (Z-direction dominant)  
- Mast top → Y-direction displacement largest  
- Periodic swinging behavior  
- Excessive amplitude → risk of boom cracking  
- Y-direction seismic wave → strongest effect on tower crane  

---

## 5. Main Conclusions
- Structural design meets required codes  
- Boom highly sensitive to low-frequency excitation  
- Seismic displacement significant in Y and Z directions  
- Long-term vibration may cause mast instability  
- Y-direction response is the key factor for seismic design
