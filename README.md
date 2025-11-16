# 📦 Repository Name
**VAE-Phone-Object-Generator**

# 📝 Repository Description
A lightweight Variational Autoencoder (VAE) project trained on smartphone-captured images to generate synthetic samples, compare **BCE vs MSE** reconstruction losses, visualize training behavior, and demonstrate KL divergence in mean–variance form. Focused on visuals with minimal text.

---

# 📷 Sample Dataset
<img src="sample_dataset.png" width="500"/>

---

# 🔧 VAE Reconstructions (BCE vs MSE)
<img src="vae_recon_images_with_bce_mse.png" width="850"/>

---

# 📉 Training Curves

### ✅ Total Loss  
<img src="total_loss_bce_vs_mse.png" width="700"/>

### ✅ Reconstruction Loss  
<img src="recon_loss_bce_vs_mse.png" width="700"/>

### ✅ KL Divergence  
<img src="kl_loss_bce_vs_mse.png" width="700"/>

---

# 🧪 Generated Images From Prior Distribution

### 🎯 MSE-Trained Model  
<img src="generated_from_prior_mse.png" width="850"/>

### 🎯 BCE-Trained Model  
<img src="generated_from_prior_BCE.png" width="850"/>

---

# 🧮 KL Divergence (Mean & Variance Form)

\[
D_{KL}(q||p)
= -\frac{1}{2}\sum_{i=1}^{d}
\left(1 + \log\sigma_i^2 - \mu_i^2 - \sigma_i^2\right)
\]

---

# ✔️ Quick Summary
- **BCE** → Sharper, higher-scale loss  
- **MSE** → Smoother, higher PSNR & SSIM  
- VAE successfully reconstructs + generates new samples  
- KL term regularizes latent distribution  

---
