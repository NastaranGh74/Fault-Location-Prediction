HIF Detection Study
The fault current due to HIFs is small and cannot be detected by relays. Therefore, the aim of this study is to find the phase and location of the HIFs using the transients in voltage measurements. To do so, first, the Daubechies-4 (db-4) discrete wavelet transform (DWT) is applied to the voltage measurements to obtain the scale-2 wavelet transform coefficients (WTC). Later, the normalized wavelet energies of postfault three-phase transient voltages are calculated. Equation (1) shows the calculation of wavelet energies for each of the three phases and (2) normalizes the wavelet energies of the three phases. M shows the number of DWT coefficients in (1). The voltage measurements are captured in 10 ms intervals. The normalized wavelet energies are used as inputs for training and testing of the classification algorithm.

E_Vk = ∑_(m=0)^(M-1) [WTC_k^2(m)]       for k ∈ {a, b, c}             (1)
E_NVk = E_Vk / (E_Va + E_Vb + E_Vc)      for k ∈ {a, b, c}             (2)
