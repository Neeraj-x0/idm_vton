# IDM-VTON Colab

Run [IDM-VTON](https://github.com/yisol/IDM-VTON) virtual try-on in Google Colab.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Neeraj-x0/idm_vton/blob/main/IDM_VTON_Colab.ipynb)

## Requirements

- Google Colab with GPU runtime (**A100 or L4 recommended**; T4 often runs out of memory)
- First run downloads ~8 GB (Space code + parsing checkpoints; SDXL weights stream from Hugging Face at runtime)

## Quick start

1. Open the notebook in Colab (badge above).
2. **Runtime → Change runtime type → GPU**.
3. **Runtime → Run all**.
4. Use the Gradio public URL from the last cell.

## Links

- [Official Hugging Face demo](https://huggingface.co/spaces/yisol/IDM-VTON) (no setup)
- [Model weights](https://huggingface.co/yisol/IDM-VTON)
- [Paper](https://arxiv.org/abs/2403.05139)
