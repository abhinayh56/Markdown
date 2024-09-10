1. Filters
   1. IIR
      1. LPF_1 (Butterworth)
      2. HPF_1 (Butterworth)
      3. LPF_2 (Butterworth)
      4. HPF_2 (Butterworth)
      5. BPF_2 (Butterworth)
      6. BSF_2 (Butterworth)
      7. APF (All Pass Filter)
      8. QF_1 (Butterworth)
      9. QF_2 (Butterworth)
      10. SRL
      11. FLC
      12. WFLC
      13. BMFLC
   2. FIR
      1. MA
      2. Median
      3. 

## Filter design methods
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
13. Bilinea Transformation
14. Impulse Invariant

## Types of filters
1. Low-Pass Filter
2. High-Pass Filter
3. Band-Pass Filter
4. Band-Stop Filter (Notch Filter / Band Reject Filter)
5. All-Pass Filter
6. Active Filter
7. Passive Filter

## Methods of converting continuous time system into discrete time system
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

## Process of Digital Filter Design
1. Low-Pass Filter
   1. Specify requirements
      - Cutoff frequency ($f_c$)
      - Sampling frequency ($f_s$)
      - Passband Ripple ($\delta_p$)
   2. Choose a filter design method. Eg. Buttorworh, Chebyshev Type 1, 2 Elliptic etc
   3. Convert analog filter to digital using techniques like bilineaer transform, impulse invariat.
2. High-Pass Filter
3. Band-Pass Filter
4. Band-Stop Filter (Notch Filter / Band Reject Filter)
5. All-Pass Filter
6. Active Filter
7. Passive Filter