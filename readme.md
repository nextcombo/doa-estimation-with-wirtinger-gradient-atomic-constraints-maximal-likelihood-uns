# DOA Estimation with Wirtinger Gradient: Atomic Constraints Maximal Likelihood Unstructured DOA[with MATLAB Code]

A log-likelihood grid sparse direction of arrival (DOA) estimation is proposed. The likelihood fitting is optimized using the sample covariance matrix and the reconstruction covariance matrix restricted to a few atoms. This method allows the use of Wirtinger gradients for DOA. By initializing with the best DOA in the grid sparse DOA method, the sensitivity to local minima is mitigated. In simulations, this method achieves Cramer-Rao bounds compared to traditional ungridded DOA methods, providing higher resolution.
Introduction: Sparse signal processing provides high resolution DOA by imposing sparsity constraints, resulting in some sharp peaks in continuous DOA spectral data. A common DOA method uses the sample covariance matrix (SCM) from one or more observation vectors and exploits second order statistics. The SCM is then compared with the true covariance matrix (CM) derived from a linear observation model. Common methods for comparing SCM and CM include covariance fitting [1] -[5] and maximum likelihood estimation [6] -[9]. These problems can be solved using grid-based optimization, but the true CM is dependent on the grid and the extracted source power is not analytically dependent on DOA, thus preventing the gradient of the DOA objective function.
We maximize a likelihood function containing atom-constrained reconstruction sample covariance matrix (RCM). The RCM is formed by mapping the SCM to a matrix spanned by DOA projection matrices [5] through DOA-projection matrices. For a given set of DOAs, the RCM is most suitable for the SCM. The likelihood objective is parameterized by DOA, allowing the use of maximum likelihood (ML) objectives and Wirtinger gradients for ungridded DOA estimation.
Sparse processing is popular in DOA estimation [10] - [12] because they outperform traditional DOA estimators [6], [13]. The grid-based sparse methods assume that the true sparse DOA lies on predefined grid points and identify the true DOA among these points. However, grid methods can be sensitive to off-grid mismatches [14]. To address this mismatch issue, adjustments or additional parameters for the grid [10] are introduced, known as off-grid sparse methods [15], [16]. Alternatively, ungrid-based sparse methods [4], [17], [18] that operate directly in continuous domains are introduced.
Ungrid-based sparse methods for DOA estimation employ different forms of objective functions, including atomic norms (or total variation norms) to snapshot data fitting methods [4], [17] - [21], [23] and covariance fitting methods [4], [22], [24]. These optimizations adapt to measurement values while incorporating sparse regularizers, which are sensitive to the setting of regularization parameters. They formulate a semidefinite programming (SDP), which has computational costs and inherent limitations, such as minimum separation thresholds even without noise [25] - [27].
Contributions from Atomic Constraint Optimization [4], [17] - [24] lead us to derive RCM [ 13, (8.300)]. Using RCM, we perform gradient descent with Wirtinger gradients of the log likelihood objective. This achieves faster convergence and potential higher resolution than atomic constraint optimization [25] - [27].
Conclusion We propose an atomic constraint method for unstructured sparse DOA estimation based on gradient-based optimization. The objective maximizes the likelihood function to obtain the reconstructed sample covariance matrix (RCM), which is constrained by several atoms of the DOA steering vector. The RCM is parameterized in DOA, supporting the use of Wirtinger gradients, thereby providing efficient and accurate optimization.

## Images

![DOA Estimation with Wirtinger Gradient for Atomic Constraints Maximal Likelihood Unstructured DOA [with MATLAB Code]](01.jpg)
![DOA Estimation with Wirtinger Gradient for Atomic Constraints Maximal Likelihood Unstructured DOA [with MATLAB Code]](02.jpg)
![DOA Estimation with Wirtinger Gradient for Atomic Constraints Maximal Likelihood Unstructured DOA [with MATLAB Code]](03.jpg)
![DOA Estimation with Wirtinger Gradient for Atomic Constraints Maximal Likelihood Unstructured DOA [with MATLAB Code]](04.jpg)

<!-- PAYMENT_BLOCK -->

## Get this dataset

- Payment link (Stripe): [Buy now](https://buy.stripe.com/3cs8yP7sY87d0vu9AB)
- Payment QR code: ![Payment QR code](pay.png)

<!-- /PAYMENT_BLOCK -->
