# Reference for markdown files

## Topics 1: Heading
Add one to six # to add heading.  One # means first / top level in heirarchy, while six # means sixth / bottom lever in heirarchy

```
# Level 1 heading
## Level 2 heading
### Level 3 heading
#### Level 4 heading
##### Level 5 heading
###### Level 6 heading
```

# Level 1 heading
## Level 2 heading
### Level 3 heading
#### Level 4 heading
##### Level 5 heading
###### Level 6 heading

When two or more headings are used, Github automaticallly generates a table of contents.

## Topic 2: Styling text
1. Bold: ** ** or __ __
```
**This is bold**
```
**This is bold**
```
__This is bold__
```
__This is bold__
2. Italic:
```
*This is italic*
```
*This is italic*

3. Strikethrough:
```
~~This is strikethrough~~
```
~~This is strikethrough~~

4. Bols and nested italic:
```
** ** and _ _
```
**This is bold and _nested italics_**
5. All bold and italic:
```
*** ***
```
***This is all bold and all italics***
6. Subscript:
```
<sub> </sub>
```
This is subscript. Eg: K<sub>12</sub>
This is nested subscript. Eg: K<sub>1<sub>2</sub></sub>
7. Superscript:
```
<sup> </sup>
```
This is superscript. K<sup>23</sup>
This is Nested superscript. K<sup>2<sup>3</sup></sup>

## Topic 3: Quoting text
This is not a quote
> This is a quote

## Topic 4: Links
This page is for practicing syntax for creating .md files for my profile on [Github](https://github.com/abhinayh56)

## Topic 5: Adding images
![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://myoctocat.com/assets/images/base-octocat.svg)

## Topic 6: Lists
### 6.1 Unordered list
Unordered list by preceeding one or more lines with -, * or +
```
+ This is item 1
+ This is item 2
- This is item 3
* This is item 4
* This is item 5
- This is item 6
```
+ This is item 1
+ This is item 2
- This is item 3
* This is item 4
* This is item 5
- This is item 6

Precede each line with a number for ordered list
```
1. This is item 1
2. This is item 2
3. This is item 3
1. This is item 4
7. This is item 5
```
1. This is item 1
2. This is item 2
3. This is item 3
1. This is item 4
7. This is item 5

### 6.2 Nested list
1. This is item 1
2. This is item 2
3. This is item 3
   1. This is item 3.1
   2. This is item 3.2
4. This is item 4

## Topic 7: Task lists
- [ ] This is task 1
- [x] This is task 2
- [x] #739
- [x] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:
- \[x] Ignore items in list

# References
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