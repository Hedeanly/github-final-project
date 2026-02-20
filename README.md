<<<<<<< HEAD
# github-final-project

=======
#!/bin/bash
# This script calculates simple interest.
# Formula: SI = P * T * R / 100

echo "Enter the principal:"
read p
echo "Enter rate of interest per year:"
read r
echo "Enter time period in years:"
read t

s=$(echo "scale=2; $p * $t * $r / 100" | bc -l)
echo "The simple interest is: $s"# github-final-project
hiwo
>>>>>>> c35b48196bd1673030d5804aee5b92dea0479691
