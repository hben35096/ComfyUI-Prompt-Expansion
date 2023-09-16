# ComfyUI Prompt Expansion
### Dynamic prompt expansion, powered by GPT-2 locally on your device.
Based on my testing, it's evident that incorporating additional keywords generated by GPT-2 notably improves the quality of the resulting images.

Many thanks to the authors of the Fooocus project for generously providing most of the code.

## Installation
- To install this custom node for ComfyUI, clone the repository using Git or download it, and then copy the node files to: ComfyUI\custom_nodes\ComfyUI-GPU-temperature-protection
```
https://github.com/meap158/ComfyUI-Prompt-Expansion.git
```

## Usage
To use this custom node (located within the 'utils' submenu), simply connect your positive prompt to it, which will then output the joined prompt.

You can also load the example workflow by dragging the workflow file (workflow_example.json or workflow_example.png) onto ComfyUI.

<p float="left">
  <img src="" width="300" />
</p>

## Inputs

- text: Your positive prompt.
- log_prompt: Whether to log the Prompt Expansion suffix and the final prompt to the console.