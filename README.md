# Anish Shenoy, Ashneel Das: Period 5

# Features:
1) Updated "vary" command to accept custom mathematical functions
    - VARY SYMBOL NUMBER NUMBER NUMBER NUMBER TEXT
    - ex: VARY right 0 49 69 109 =abs(sin(0.2*))
    - The last 2 numbers should specify a range in your mathematical function that is the same size as the range of your frames
    - The final argument should be a mathematical function that begins with an "="

# Specifics:
1) Exponents are specified with "**"
2) sine and cosine are specified with "sin(x)" and "cos(x)"
3) Absolute Value is specified with "abs(x)"
4) Functions that are bounded between 0 and 1 work well

# Neat Examples:
    - =-0.0000015*(((x**3)-1)*(x-50)) from X=1 to X=50 (50 frames total)
    - =sin(abs((0.2*x))) from X=0 to X=49 (50 frames total)
