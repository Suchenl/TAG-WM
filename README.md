# TAG-WM: Tamper-Aware Generative Image Watermarking via Diffusion Inversion Sensitivity

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![arXiv](https://img.shields.io/badge/arXiv-2506.23484-b31b1b.svg)](https://arxiv.org/abs/2506.23484)
[![GitHub Stars](https://img.shields.io/github/stars/Suchenl/TAG-WM?style=social)](https://github.com/Suchenl/TAG-WM)

Official implementation of **TAG-WM**, a tamper-aware watermarking framework for diffusion-generated images.  
*Code release coming soon.*

---

## 🔍 Key Contributions
1. **Dual-Mark Joint Sampling**  
   - Simultaneously embeds copyright + localization watermarks in diffusion latent space  
   - Preserves standard normal distribution of latents (lossless visual quality)  
   - Enables tampering localization without degrading generation  

2. **Dense Variation Region Detector**  
   - Leverages diffusion inversion sensitivity to modifications  
   - Detects tampering via statistical deviations between original/reconstructed watermarks  
   - Achieves strong generalization across manipulation types  

3. **Tamper-Aware Message Decoding**  
   - Localization-guided decoding improves robustness against edits  
   - Maintains copyright extraction accuracy even under modifications  

## 🚀 Updates
- **[2025.06]** Paper released on [arXiv](https://arxiv.org/abs/2506.23484)  
- **[2025.07]** Code packaging in progress (Expected: August 2025)  

## 📜 License
MIT License - See [LICENSE](LICENSE) for details.  

## 📜 License
This project is licensed under the **MIT License** - a permissive free software license with minimal restrictions.  

### You are free to:
- ✅ Use the code **commercially or privately** (even in proprietary software)  
- ✅ Modify, adapt, or build upon the work  
- ✅ Distribute your modified versions  
- ✅ Use for research, education, or production systems  

### Requirements:
- 📝 Include original copyright notice  
- 📜 Retain license file  

[View full license text](LICENSE)

## 📄 Citation
If you find this work useful, please consider citing our paper and giving the repo a ⭐:
```bibtex
@article{chen2025tag,
  title={TAG-WM: Tamper-Aware Generative Image Watermarking via Diffusion Inversion Sensitivity}, 
  author={Chen, Yuzhuo and Ma, Zehua and Fang, Han and Zhang, Weiming and Yu, Nenghai},
  journal={arXiv preprint arXiv:2506.23484},
  year={2025}
}
