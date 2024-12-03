# Problem 1

Given the production function \( Q = \left(K^{1/4} + L^{1/4}\right)^\alpha \), where \(\alpha\) is a parameter:

## (a) Marginal Products of Capital and Labor

The marginal product of capital (\(MP_K\)) and labor (\(MP_L\)) are the partial derivatives of \(Q\) with respect to \(K\) and \(L\), respectively.

\[
MP_K = \frac{\partial Q}{\partial K} = \alpha (K^{1/4} + L^{1/4})^{\alpha-1} \left(\frac{1}{4} K^{-3/4}\right)
\]

\[
MP_L = \frac{\partial Q}{\partial L} = \alpha (K^{1/4} + L^{1/4})^{\alpha-1} \left(\frac{1}{4} L^{-3/4}\right)
\]

## (b) Average Products of Capital and Labor

\[
AP_K = \frac{Q}{K} = \frac{\left(K^{1/4} + L^{1/4}\right)^\alpha}{K}
\]

\[
AP_L = \frac{Q}{L} = \frac{\left(K^{1/4} + L^{1/4}\right)^\alpha}{L}
\]

## (c) Returns to Scale

To determine returns to scale, scale both inputs by a factor \(t\):

\[
Q' = \left((tK)^{1/4} + (tL)^{1/4}\right)^\alpha = t^{1/4}(K^{1/4} + L^{1/4})^\alpha
\]

- **Increasing Returns to Scale**: If \(\alpha / 4 > 1\)
- **Constant Returns to Scale**: If \(\alpha / 4 = 1\)
- **Decreasing Returns to Scale**: If \(\alpha / 4 < 1\)

## (d) Marginal Rate of Technical Substitution (MRTS)

The MRTS is given by:

\[
MRTS_{KL} = -\frac{MP_K}{MP_L} = -\frac{K^{-3/4}}{L^{-3/4}} = -\left(\frac{L}{K}\right)^{3/4}
\]

## (e) Elasticity of Substitution

\[
\sigma = \frac{d\ln(K/L)}{d\ln(MRTS_{KL})}
\]

From part (d):

\[
\ln(MRTS_{KL}) = \frac{3}{4} \ln\left(\frac{L}{K}\right)
\]

\[
\frac{d\ln(MRTS_{KL})}{d\ln(K/L)} = -\frac{3}{4} \quad \text{so,} \quad \sigma = \frac{1}{-\frac{3}{4}} = \frac{4}{3}
\]

## For \(\alpha = 4\):

\[
Q = \left(K^{1/4} + L^{1/4}\right)^4
\]

## (f) Short-Run Cost Minimization (Capital Fixed at \(\bar{K}\))

1. **Production Constraint**:  
   \[
   Q = \left(\bar{K}^{1/4} + L^{1/4}\right)^4
   \]

2. **Solving for \(L\)**:  
   \[
   \left(Q^{1/4} - \bar{K}^{1/4}\right)^4 = L
   \]

3. **Short-Run Cost Function**:  
   \[
   C_{SR} = wL + v\bar{K} = w\left(Q^{1/4} - \bar{K}^{1/4}\right)^4 + v\bar{K}
   \]

## (g) Long-Run Cost Minimization (Both Inputs Variable)

1. **Objective Function**: Minimize \(C = wL + vK\)
2. **Constraint**: \(Q^{1/4} = K^{1/4} + L^{1/4}\)
3. **Using the Lagrangian**:  
   \[
   \mathcal{L} = wL + vK - \lambda\left(K^{1/4} + L^{1/4} - Q^{1/4}\right)
   \]

4. **Solving yields**:  
   \[
   C = vQ \left(1 + \left(\frac{w}{v}\right)^{1/3}\right)
   \]
