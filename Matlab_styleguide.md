Wagner Lab Matlab Style Guide
=======================
 
Naming Variables
--------------
 
```
df_name = load('data.mat')
numConstant = 200
```
 
Defining Functions
------------------
```
function [c] = calculateSum(a, b)
% Calculates the sum of two numbers
% Args:
%   a: one number to be added
%   b: another number to be added
%
% Returns: 
%   The sum of a and b.
  
  c = a + b

```
 
If/Else Statements
---------------------
```
if condition
	one or more lines;
elseif condition2
	one or more lines
else
	one or more lines
end
```