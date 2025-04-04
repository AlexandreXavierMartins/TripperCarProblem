Each instance has two sets and nine parameters as in the example:

set T := 1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16 17 18 19 20;  %% Periods set

set P := 1 2 3 4; %% Bins set

param n := 4; %% Number of bins

param e := 20; %% Number of periods

param lmax := 100; %% Max level

param lmin := 0; %% Min level

param q := 4; %% Input mass flow

param Q default 1; Output mass flow

param K default 1; %% Bins Level coef.

param p := 1; %% Initial position

param I := 1 32 2 93 3 31 4 75 %% Initial level for each bin
