# Filters
**Types of filters**
1. Low-Pass Filter
2. High-Pass Filter
3. Band-Pass Filter
4. Band-Stop Filter (Notch Filter / Band Reject Filter)
5. All-Pass Filter
6. Active Filter
7. Passive Filter

**Methods for filter design**
1. Butterworth
2. Chebyshev
   1. Chebyshev type 1
   2. Chebyshev type 2
3. Elliptic (Cauer)
4. Bessel
5. Gaussian
6. Linkwitz-Riley
7. Sallen-Key
8. MFB (Multiple Feedback)
9. State Variable
10. KHN (Kerwin-Huelsman-Newcomb)
11. Digtal FIR (Finite Impulse Response)
12. DIGITAL IIR (Infinite Impulse Response)
13. Bilinear Transformation
14. Impulse Invariant

**Methods of converting continuous system to discrete**
1. Bilinear Transformation
2. Impulse Invariant Transformation
3. Zero-Order_Hold (ZOH)
4. First-Order Hold (FOH)
5. Matched Z-Transform
6. Backward Difference Method
7. Forward Difference Method
8. Tustin Approximation
9. Zero-Pole Matching
10. Least Squares Method
11. Euler's Method
12. Trapezoidal Rule
13. Runge-Kutta Methods
14. Numerical Approximations of Differential Equations
15. Discretization of State Variable Models

**Process of filter design**
1. Define specifications / requirements
    - Type of filter: High-pass, low-pass, band-pass, band-stop etc
    - Cutoff frequencies $(f_c)$: One or more cutoff frequencies
    - Passband ripple $(\delta_p)$
    - Stopband attenuation
    - Sampling frequency $(f_s)$ (for digital filters)
2. Choose a filter design method
    - Analog filters: Butterworth, Chebyshev Type I, Chebyshev Type II, Elliptic, Bessel, etc.
    - Digital Filters: FIR (Finite Impulse Response), IIR (Infinite Impulse Response), Bilinear Transformation, Impulse Invariant, etc.
3. Determine filter order: Calculate the order of the filter to meet the specifications. Higher order filter provide steeper roll-off but are more complex.
4. Design the filter
    - Analog filters: Use standard design equations or software tools to determine the components values (resistors, capacitors, inductors)
    - Digital filters: Convert analog filter to digital using one of the method of discretization. Use algorithms or software tools to determine the filter coefficients.
5. Implementation
    - Analog filters: Build the circuit using calculated component values
    - Digital filters: Implement the filter in software or hardware using calculated coefficients
6. Verification
    1. Simulate the filter response using software tools to ensure it meets the specifications
    2. Test the filter with actual signals to verify the performance
7. Optimization and iteration: If the filter does not meet the specifications, adjust the design parameters and repeat the process.

**Process of digital filter design: Low-Pass Filter**
1. Specify requirements
    - Cutoff frequency ($f_c$)
    - Sampling frequency ($f_s$)
    - Passband Ripple ($\delta_p$)
2. Choose a filter design method. Eg. Buttorworh, Chebyshev Type 1, 2 Elliptic etc
3. Convert analog filter to digital using techniques like bilineaer transform, impulse invariat.

**Process of digital filter design: High-Pass Filter**

**Process of digital filter design: Band-Pass Filter**

**Process of digital filter design: Band-Stop Filter**

**Process of digital filter design: All-Pass Filter**

**Process of digital filter design: Active Filter**

**Process of digital filter design: Passive Filter**
