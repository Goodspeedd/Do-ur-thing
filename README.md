README.md # Do-ur-thing
Matlab
% Define variables
cvx_begin
    variable x
    variable y
    minimize(x + y)
    subject to
        x + y >= 1
        x - y <= 2
cvx_end
