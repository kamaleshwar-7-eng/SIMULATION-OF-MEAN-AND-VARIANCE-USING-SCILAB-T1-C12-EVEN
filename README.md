# SIMULATION-OF-MEAN-AND-VARIANCE-USING-SCILAB-T1-C12-EVEN
# AIM:

To write a program for mean, variance and cross correlation in SCILAB and verify the output.

# EQUIPMENTS NEEDED:

  *Computer with i3 Processor

  *SCI LAB

# ALGORITHM:

Define the Function: Specify the function you want to simulate. For example, f(x)=sin⁡(x)f(x)=sin(x) or any other function.
Generate Sample Points: Decide on the range and the number of sample points. Generate these sample points within the desired range.
Evaluate the Function: Compute the function values at each of these sample points.
Compute Mean, Variance and Cross Correlation: Use Scilab's functions to calculate the mean and variance of the computed function values.
Display Results: Output the computed mean variance and Cross Correlation

# PROCEDURE:

1.Refer Algorithms and write code for the experiment.

2.Open SCILAB in System

3.Type your code in New Editor

4.Save the file

5.Execute the code If any Error, correct it in code and execute again

6.Verify the generated results

# PROGRAM:
```matlab
X = [1 4 9 16 25];
N = length(X);
mean_value = sum(X) / N;
variance_value = sum((X - mean_value).^2) / N;
disp("Mean = ",mean_value);


disp("Variance = ");
disp(variance_value);
```

# OUTPUT :

<img width="846" height="219" alt="Mean and Variance" src="https://github.com/user-attachments/assets/cedea029-0669-426d-80f4-651b0647dce5" />

# Manual Calculations:

![MEAN](https://github.com/user-attachments/assets/380e7069-58cb-4190-82d2-7ad773aa578f)

![VARIANCE](https://github.com/user-attachments/assets/0709424b-141e-4182-a112-34d347fe397c)


# RESULT:
Thus the mean , variance and cross correlation are executed in Scilab and output is verified.
