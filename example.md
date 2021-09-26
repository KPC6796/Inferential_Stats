Royal enfield : 
Mileage - mu = 50kms/1lt

Ho : mu = 50 (Population mean)
Ha : mu != 50 (2-tailed test), mu < 50 (1-tailed test)

Sample mean

Ho : Sample mean = Population mean
Ha : Sample mean < Population mean

CL = 95% (by default) - Every time you take a sample you will get 95% of the times the same result

output of every test is some p-value

compare this output p-value with alpha (1-CL = 1-0.95 = 0.05)

p-value < alpha, reject Ho
p-value >= alpha, accept Ho

1-sample test:
Compare a sample with population

2-sample test:
Compare 2 samples

Ho : Sample1 mean = Sample2 mean
Ha : Sample1 mean != Sample2 mean

test (between 2 arrays/lists)

Check for normality (Anderson darling test, Shapiro-Wilks test, Kolmogorov Smirnov test, Histogram)

Normalization - (x - min(x)) / (max(x) - min(x))

Log transformation (data transformation) - to reduce skewness in data or making the data symmetric

log(x) - more zero/negative values not applicable

log1 - 0
log0 - undefined
log

Square root transformation
Cubic transformation



Chi-square:
sum((O-E)^2/E)

O - Observed data
E - Expected data

O : 
10  10  20
10  20  30

20  30  50


E :
rt*ct/n

20*20/50 = 8   20*30/50 = 12
30*20/50 = 12    30*30/50 = 18

(10-8)^2/8 + (10-12)^2/12 + (10-12)^2/12 + (20-18)^2/18
= 0.5 + 0.33 + 0.33 + 0.1
= 1.2