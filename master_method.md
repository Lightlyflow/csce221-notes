# Master Method
Given the form: $T(n)=aT(n/b)+f(n)$

| Case | Solution | Case # |
| --- | --- | --- |
| $n^{\log_ba} > f(n)$ | $O(n^{\log_ba})$ | 1 |
| $n^{\log_ba} = f(n)$ | $O(n^{\log_ba}\log_2n)$ | 2 |
| $n^{\log_ba} < f(n)$ | $O(f(n))$ | 3 |

> *In each case, compare the powers and not the functions themselves