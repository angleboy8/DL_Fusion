# Hyperspectral Image Reconstruction Employing TV-loss and Smooth L1-loss in SSR-NET

This project studies the implementation of two denoising algorithms,
Total Variation (TV) loss function and Smooth L1-loss, as a proposal to
improve the quality of the final fused image. To prove the efectiveness
of our implementations, three different networks have been created, us-
ing SSR-NET as a reference in which they have been implemented: 1)
TV-loss loss; 2) Smooth L1-loss; 3) TV-loss plus Smooth L1-loss. After
comparing the results with respect to the original SSR-NET, in five dif-
ferent HSI databases, Botswana, Urban, Pavia Center, Pavia University,
and Kennedy Space Center, it has been verified that the proposed im-
plementations represent an improvement in the results, being TV-loss
more efective for databases with high spatial resolution per pixel, and
TV-loss plus Smooth L1-loss with better results for databases with lower
resolution.

*More information in the file Paper.pdf*
