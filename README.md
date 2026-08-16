# Custom Subgraph Nodes for ComfyUI

A set of custom subgraph nodes designed to streamline your workflow in ComfyUI.

---

## 📦 Prerequisites & Installation

Before importing the nodes, make sure you have installed the required extension and model:

### 1. Required Custom Nodes Extension
Clone the **ComfyUI-PainterI2Vadvanced** extension into your ComfyUI `custom_nodes` directory:

```bash
cd ComfyUI/custom_nodes
git clone [https://github.com/princepainter/ComfyUI-PainterI2Vadvanced.git](https://github.com/princepainter/ComfyUI-PainterI2Vadvanced.git)
```

### 2. Required Model / Patch

Download the **Anima-LLLite Inpainting v2** model:

* **Download Link:** [anima-lllite-inpainting-v2.safetensors](https://huggingface.co/kohya-ss/Anima-LLLite/resolve/main/anima-lllite-inpainting-v2.safetensors?download=true)
* **Destination Folder:** Place the downloaded `.safetensors` file into:
```text
ComfyUI/models/model_patches/
```

---

## 🚀 How to Use

1. **Import the Subgraph:**
* Simply drag and drop the provided `.json` file directly into your ComfyUI canvas.


2. **Add Nodes:**
* Right-click anywhere on the canvas (or double-click to search) and add your custom subgraph nodes directly to your workflow.
